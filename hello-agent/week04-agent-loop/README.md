# week04-agent-loop

## TODO
- Agent Loop

这是整个课程最重要的一章。

普通聊天：
```
User

↓

LLM

↓

End
```
Agent：
```
while True:

LLM

↓

Tool?

↓

Yes

↓

Execute

↓

LLM

↓

Tool?

↓

Execute

↓

No

↓

Answer
```
学生实现：
```
while True:
    response=model(...)
```
第一次真正拥有Agent。
