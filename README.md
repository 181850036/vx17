# 云开发 quickstart

这是云开发的快速启动指引，其中演示了如何上手使用云开发的三大基础能力：

- 数据库：一个既可在小程序前端操作，也能在云函数中读写的 JSON 文档型数据库
- 文件存储：在小程序前端直接上传/下载云端文件，在云开发控制台可视化管理
- 云函数：在云端运行的代码，微信私有协议天然鉴权，开发者只需编写业务逻辑代码

## 参考文档

- [云开发文档](https://developers.weixin.qq.com/miniprogram/dev/wxcloud/basis/getting-started.html)
//111
目前首页里面的东西都是创建的时候自带的。除了下面三个网页以外应该都是要删掉的以后。
我修改了顶部的一些样式pages里面的index,catogory,collection三个页面是我想的以后主要用得到的：
- 首页即推送功能，可以随机推荐电影，就不考虑啥推荐算法了；我加了一个下拉刷新功能，但是还没写代码，我想的是下拉就推荐一个新的；
- 分类页面进入之后可以选择不同种类电影浏览
- 收藏是根据个人id 记录收藏过的电影
icons文件夹是我新建的，里面是导航栏的六个图标，具体代码在 app.json 的 tabBar 里大家可以看一下；
