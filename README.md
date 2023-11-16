# simple-ratio

用于求解多个整数简约比值的工具函数

## 简介

`simple-ratio`是一个计算整数比的工具，结果比值，对用户友好。

在一些业务场景中，比如计算男女比例，往往用户只想看大致的比例，而不是精确的比例。此时，`simple-ratio`就很有帮助。


数值比较直观，通常是百分比之后最简整数比。比如，男女原先的数字是`15008:14173`，计算出的结果是`51:49`，再如`1889:1734`的结果是`13:12`。

比值悬殊的情况下，会变成最小数的倍数，比如`192:23333`的结果是`1:122`。



## 安装下载

```js
npm install simple-ratio --save
```

## 快速使用

```js
import { simpleRatio } from 'simple-ratio'
let ratio = simpleRetio([2, 4])
console.log(ratio) // 1:2
```

更多使用参考：[使用文档](https://simple-ratio.github.io/doc/use/)

## 在线案例

<a href="https://simple-ratio.github.io/example/test.html" target=“_blank>动手测一测</a>

## 交流 & 提问

https://github.com/simple-ratio/simple-ratio/issues

## 关于作者

- [个人主页](https://juejin.cn/user/78820536232855)
- 如果有用，欢迎赞赏

<img src="./tip.jpg" alt="微信赞赏码" style="width:50%; height:auto;" />
