## 腾讯云web播放器SDK
本库为腾讯云直播的web播放器sdk镜像。

* 源文件 [http://imgcache.qq.com/open/qcloud/video/vcplayer/TcPlayer.js](http://imgcache.qq.com/open/qcloud/video/vcplayer/TcPlayer.js)
* 腾讯云直播web播放器文档 [https://www.qcloud.com/document/product/267/7479](https://www.qcloud.com/document/product/267/7479)

## 广告
腾讯这个sdk闭源，代码写得忒烂，直播rtmp时使用的swf事件不全，bug众多，又无处反馈。

so，我自己写了个播放器，用在公司项目中，各位有兴趣可以来使用、拍砖、贡献代码。

传送门：[https://github.com/duxiaofeng-github/zaojiu-player](https://github.com/duxiaofeng-github/zaojiu-player)

## 安装

```bash
npm install tcplayer --save
```

or

```bash
yarn add tcplayer
```

如果需要锁定某个版本，如下：

```bash
npm install tcplayer@0.0.1 --save
```

or

```bash
yarn add tcplayer@0.0.1
```

## 自动更新
本库每天会做自动更新，检查源地址的md5是否变更，变更则自动提交commit，tag自增，并自动发布到 [npm](https://www.npmjs.com/package/tcplayer) 。

## LICENSE
MIT