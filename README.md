# 酱海带公开发布页

这里用于发布酱海带 App 的安装包和在线更新清单。主项目源码仓库保持私有，本仓库只放公开发布内容。

## 下载

请进入 [Releases](https://github.com/sunjingquan/jianghaidai-release/releases/latest) 下载最新版安装包。

Android 用户通常选择：

- `android-arm64-v8a.apk`：大多数近几年的手机
- `android-armeabi-v7a.apk`：较老的 32 位手机
- `android-x86_64.apk`：少数 x86 模拟器或设备

## 反馈与建议

QQ群：`1049643673`

如果无法下载、无法登录、课表或考试信息异常，可以加群一起讨论。

## 在线更新

应用会读取本仓库根目录的 [`update.json`](./update.json) 判断是否有新版本。发布流程会由私有仓库 CI 自动更新该文件。
