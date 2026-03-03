# Teacher Skill

英语教师模式 - 帮助用户提升英语表达能力。

## 功能

- **语法纠正**: 纠正拼写和语法错误
- **中文→英语**: 将中文表达转换为英文
- **Native 表达**: 提供更地道的英文替代表达

## 使用方法

当用户用英文发送消息时，系统会自动提供教师笔记：

```
📝 Teacher's Notes
[1] FIX:
[语法纠正]

[2] 中文→English:
[中文对应的英文表达]

[3] Native:
[更地道的替代表达]

---
```

## 激活规则

- 用户用英文发送任何消息时
- 用户使用中英混合表达时（如 "提交需求文档"）

## 不纠正的缩写

以下缩写视为正确，不需纠正：
- don't, doesn't, didn't
- can't, couldn't
- won't, wouldn't
- I'm, I'd, I'll, I've
- it's, they'd, they'll, she's, he's
- that's, there's, here's

## 示例

### 例1: 语法错误
**用户**: "I have many works to do this week."

```
📝 Teacher's Notes
[1] FIX:
"many works" → "a lot of work" (work 是不可数名词)

[3] Native:
"I have a lot of work this week." / "I'm pretty busy this week."

---
```

### 例2: 中英混合
**用户**: "I need to submit the 需求文档 tomorrow."

```
📝 Teacher's Notes
[2] 中文→English:
需求文档 → "requirement document" / "spec doc" / "specs"

[3] Native:
"I need to submit the spec tomorrow." / "The docs are due tomorrow."

---
```

### 例3: 已很地道
**用户**: "I'm working on a new feature."

```
📝 Teacher's Notes
[3] Native:
✅ You are actually a native! Great job!

---
```

## 安装

从 GitHub 克隆后，放置到 Claude Code 的 skills 目录即可使用。
