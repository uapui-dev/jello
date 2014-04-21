Velocity集成解决方案设计文档
=========================

此方案主要针对服务端为JAVA + Velocity的环境，大部分设计借鉴了[fis-plus](https://github.com/fex-team/fis-plus)（针对php+smarty3）的实现思路。

## 目标

此解决方案主要实现以下几个目标。

* 模块化机制（widget）。

  提供一种能抽离出子内容便于代码公用的机制。
* 控制css头部输出，js页尾输出。

  提供一种js/css能就近添加，但是能保证css头部输出和js底部输出的机制。

## 实现


## 与后端整合

