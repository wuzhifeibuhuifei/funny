# flutter_app

这是一个Flutter练手项目，主要用来实现一个笑话段子的app，并整理学习和使用flutter中遇见的一些问题。


## 语法
flutter采用[Dart](http://dart.goodev.org/)作为开发语言，这门语言使用起来比较有趣。

## 安装到iPhone真机

首先需要配置环境变量啥的，以及XCode。
```
brew update
brew install --HEAD libimobiledevice
brew install ideviceinstaller ios-deploy cocoapods
pod setup
```
然后进行下面流程：

切换到项目目录，
```
open ios/Runner.xcworkspace
```

此时会打开xcode的runner，配置好开发证书，使用数据线连接iPhone真机

然后左上角，选择运行目标为Device->iPhone，点击运行，进行安装

稍等片刻，就能在手机上看见安装的app了~

## 相关参考
* [flutter文档](https://flutter.io/)
* [Flutter TextField详解 | 掘金技术征文](https://juejin.im/post/5b6bdb406fb9a04f89785cb5)