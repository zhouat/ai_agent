# week05-file-tool

## TODO
- Read/Write/List File

开始增加工具。

例如：
```
Read File

Write File

List Directory

Run Shell

Search

Download
```
课程重点：

Tool统一接口：
```
Tool

name

description

parameters

execute()
```
例如：
```
ReadFile.execute(path)
```
Agent无需关心实现。

支持：
```
读取

写入

复制

删除

搜索
```
案例：
```
帮我统计Python文件数量
```
Agent：
```
ListDir

↓

Read

↓

统计

↓

回答
```
已经开始像Claude Code。
