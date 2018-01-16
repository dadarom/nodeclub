
yz1923
=

待改进点
==

* 登入／注册（去掉github登入）
* 微信登入／push
* 图片上传（改到阿里云的对象存储）
* 注册按手机号（非邮箱）

待确认点
===

* 极光推送是否仅和app相关，是否可推到微信

运营点
===

* 聚会·活动推广
* 个人分享·讨论 - 营造氛围
* 网聚全国各地校友 - 不仅仅局限在上海周边
* 新加入校友 - 归属感
* 好文分享
* 大群实时讨论（低优先级）
* 每日每句
* 美剧／电影推荐
* 好文转发
* 分享到微信群／朋友圈



收支平衡点
===

* sidebar广告
* 软文广告（难度较大，点击量也小）
* 校友广告（也不太好推广）最低优先级

相比微信群
===

* 不强制消费注意点
* 有选择性的信息
* 可以重复浏览
* 拥抱新同学



~~~
=========华丽分割线==========
~~~

Nodeclub
=

[![build status][travis-image]][travis-url]
[![codecov.io][codecov-image]][codecov-url]
[![David deps][david-image]][david-url]
[![node version][node-image]][node-url]

[travis-image]: https://img.shields.io/travis/cnodejs/nodeclub/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/cnodejs/nodeclub
[codecov-image]: https://img.shields.io/codecov/c/github/cnodejs/nodeclub/master.svg?style=flat-square
[codecov-url]: https://codecov.io/github/cnodejs/nodeclub?branch=master
[david-image]: https://img.shields.io/david/cnodejs/nodeclub.svg?style=flat-square
[david-url]: https://david-dm.org/cnodejs/nodeclub
[node-image]: https://img.shields.io/badge/node.js-%3E=_4.2-green.svg?style=flat-square
[node-url]: http://nodejs.org/download/

## 介绍

Nodeclub 是使用 **Node.js** 和 **MongoDB** 开发的社区系统，界面优雅，功能丰富，小巧迅速，
已在Node.js 中文技术社区 [CNode(http://cnodejs.org)](http://cnodejs.org) 得到应用，但你完全可以用它搭建自己的社区。

## 安装部署

*不保证 Windows 系统的兼容性*

线上跑的是 [Node.js](https://nodejs.org) v4.4.0，[MongoDB](https://www.mongodb.org) 是 v3.0.5，[Redis](http://redis.io) 是 v3.0.3。

```
1. 安装 `Node.js[必须]` `MongoDB[必须]` `Redis[必须]`
2. 启动 MongoDB 和 Redis
3. `$ make install` 安装 Nodeclub 的依赖包
4. `cp config.default.js config.js` 请根据需要修改配置文件
5. `$ make test` 确保各项服务都正常
6. `$ node app.js`
7. visit `http://localhost:3000`
8. done!
```

## 测试

跑测试

```bash
$ make test
```

跑覆盖率测试

```bash
$ make test-cov
```

## 贡献

有任何意见或建议都欢迎提 issue，或者直接提给 [@alsotang](https://github.com/alsotang)

## License

MIT
