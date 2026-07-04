AI Agent 系统开发：从 Hello World 到 Claude Code

# 目前很多智能体（例如 Hermes、OpenClaw、OpenCode 等）其实都是围绕同一个核心思想：

```
LLM（大脑） + Tools（工具） + Agent Loop（循环决策） + Memory（记忆） + UI（交互）
```
真正神奇的地方其实不是模型，而是Agent Runtime（智能体运行时）。

# 最终课程目标（Project Goal）

课程结束后，每位学生完成一个自己的智能体：

HelloAgent

你：
> 帮我下载Python

Agent：
✓ 理解需求
✓ 去官网寻找下载地址
✓ 下载文件
✓ 执行安装（可确认）
✓ 告诉用户完成

-------------------

你：
> 帮我整理Downloads

Agent：
✓ 扫描目录
✓ 分类文件
✓ 删除垃圾
✓ 输出报告

-------------------

你：
> 写一个Flask网站

Agent：
✓ 创建目录
✓ 写代码
✓ 安装依赖
✓ 运行
✓ 浏览器打开

最终效果类似：

Hermes

OpenClaw

OpenCode

Claude Code

Cursor Agent

但是只有约1000~2000行代码。
