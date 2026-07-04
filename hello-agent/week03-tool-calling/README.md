# week03-tool-calling

## TODO
- Calculator.execute()

这是Agent真正开始。

定义工具：

例如：
```
calculator()

Python：

def calculator(a,b):
    return a+b
```
LLM：
```
用户：

1+2
```
LLM输出：
```
Call Tool

calculator

1

2
```
程序：
```
执行calculator

↓

返回3

↓

LLM继续
```
第一次拥有：

Agent可以行动。
