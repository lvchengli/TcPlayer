## 腾讯云web播放器SDK
本库为腾讯云直播的web播放器sdk镜像 的修改版。
增加了移动端的分辨率切换和安卓4.X版本webView内视频不能播放的问题

* 源文件 [http://imgcache.qq.com/open/qcloud/video/vcplayer/TcPlayer.js](http://imgcache.qq.com/open/qcloud/video/vcplayer/TcPlayer.js)
* 腾讯云直播web播放器文档 [https://www.qcloud.com/document/product/267/7479](https://www.qcloud.com/document/product/267/7479)

## 安装

```bash
npm install vvtcplayer --save
```

or

```bash
yarn add vvtcplayer
```

如果需要锁定某个版本，如下：

```bash
npm install vvtcplayer@0.0.1 --save
```

or

```bash
yarn add vvtcplayer@0.0.1
```

## 解决低版本安卓4.x webView问题
在安卓低版本报错：当前系统环境不支持播放该视频格式，此时引入video.js，可以解决该问题

```javascript
var {Videojs} = require('vvtcplayer/video.min.js')
var {TcPlayer} = require('vvtcplayer/TcPlayer.js')

this.player = new TcPlayer('id_test_video', {/* your option */})
```

## LICENSE
MIT