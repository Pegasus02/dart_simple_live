# Simple Live 编译产物

## 文件说明

- `SimpleLive-macOS.app.zip` - macOS 桌面版 (Apple Silicon, Release)
- `SimpleLive-iOS-Runner.app.zip` - iOS 设备版 (需侧载/签名后使用)

## 编译信息

- Flutter 3.38.1
- macOS 26.4 / Xcode 26.4
- 源码版本: [dart_simple_live](https://github.com/xiaoyaocz/dart_simple_live) by xiaoyaocz

## macOS 使用

1. 下载 `SimpleLive-macOS.app.zip`
2. 解压后得到 `Simple Live.app`
3. 双击运行

## iOS 使用

1. 下载 `SimpleLive-iOS-Runner.app.zip`
2. 使用 Sideloadly、AltStore 或 Xcode 签名安装到设备

> 注意：iOS 版本编译时未签名 (--no-codesign)，安装前需要手动签名。
