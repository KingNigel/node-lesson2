# node-lesson2

# 1.复习

## 1.1 概念
- Node.js是JavaScript吗?

  `Node.js不是JavaScript，是一个提供解析和执行JavaScript运行环境的平台，不是框架、也不是库、更不是一门语言`
  
- Node.js基于哪个JavaScript引擎？

  `Chrome的V8引擎`
  
- Node.js的特性？

  `事件驱动、无阻塞IO----->异步、高io`
  
- Node.js只能运行在Windows上吗？

  `不仅仅能运行在Windows上，Node.js是跨平台`
  
## 1.2 nvm常用命令
- nvm项目地址：[nvm-github地址](https://github.com/coreybutler/nvm-windows)
- 查看所有已安装的node版本
``` nvm list ```
- 切换node版本
``` nvm use 版本号 ```
- 安装指定版本的node
``` nvm install 版本号 ```
- 卸载已安装的指定版本的node
``` nvm uninstall 版本号 ```

## 1.3 cmd
- cd（change directory）切换目录
- md（make directory）新建目录
- rd（remove directory）删除非空目录
- dir（directory）查看目录中的条目
- ren（rename）重命名文件
- del（delete）删除文件
- cls（clear screen）清屏

## 1.4 path 环境变量
- path环境变量的作用是什么？
- 在Windows中配置path环境变量的方法是什么？  

## 1.5 REPL（Read Eval Print Loop）运行环境

- 作用：一般来说，可以用来做一些API的测试

- 进入REPL运行环境
  `在控制台中输入node命令直接敲回车`
  
- 退出REPL运行环境
  ` 1.Ctrl+c 两次 2..exit `

## 1.6 Node.js基础知识
- 如何让Node.js执行一个js文件
  `node 文件名`


## 1.6 global
- __dirname和__filename
  ` 关于这俩家伙，一般在读取文件的时候，最好使用绝对路径的方式，通过这俩家伙拼接 `
- setTimeout和clearTimeout
- setInterval和clearInterval
- console
  + time('timer')
  + timeEnd('timer')
  + 成对的出现

## 1.7 模块系统
- 什么是模块
  ``` 在CommonJS规范中，一个文件就是一个模块 ```
- 模块作用域
  ``` 普通方式定义的变量、函数、对象等都属于该模块内 ```
- require
  ``` 通过require的方式可以加载一个模块 ```
- exports
- module.exports

