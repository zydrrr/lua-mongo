## Introduction

This is a simple lua mongo driver, work in progress.

## Building

Install lua-bson first.
https://github.com/cloudwu/lua-bson

```
make win
```
or
```
先编译lua-bson 将生成的so 拷贝到当前目录 后编译lua-mongo 运行test(lua 版本5.2以上)
make linux
```

## Features

* connect to mongod
* runCommand
* insert document
* update document
* find return basic cursor, cursor hasNext() and next()
* findone

## Todo list

* write concern
* replica set
* gridFS
* tailable cursor
* more options for cursor
* more command
* and more ...

## Getting started

See test.lua
