# week01-hello-llm

## TODO
- LLM.chat()


第一章：Agent是什么（Week1）

目标：

理解Agent本质。

内容：

```
LLM != Agent

Agent =
LLM
+
Tools
+
Loop
```
举例：

普通ChatGPT：
```
用户

↓

LLM

↓

回答
```
Agent：
```
用户

↓

LLM

↓

决定：

我要调用工具

↓

Tool

↓

结果

↓

LLM

↓

继续思考

↓

回答
```
实验：

写第一个
```
chat.py
```
调用OpenAI API：
```
User

↓

GPT

↓

Reply
```
Hello World完成。
