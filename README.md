# dyguard

抖音辅助插件，适用于 LSPosed/Xposed 环境，无桌面图标。

## 支持版本

- Android 9 及以上。
- 抖音 39.9.0（390901）、40.8.0（400801）。

## 使用

安装后在 LSPosed 启用 dyguard，作用域勾选抖音，强制停止并重新打开抖音。在抖音搜索框输入 `#dy` 打开设置。

首次获取或更新云端适配规则后，按提示强制停止并重新打开抖音。已验签的规则会按抖音版本缓存；断网或更新失败时保留已有规则。首次没有缓存时需先联网获取配置。授权有效期与适配缓存分别校验。

覆盖安装新版后，同样强制停止并重新打开抖音。

[使用说明](https://my.feishu.cn/wiki/NDk8w0XJTiyJcFkGgz3cPR9Kn3d) · [正式版下载](https://github.com/Xposed-Modules-Repo/top.myfyfy.dyguard/releases/latest) · [赞助](https://zf.myfyfy.top/?product=dyguard) · [加入交流群](https://t.me/+PKuwqsS_H64yMDE9)

## 已知限制与反馈

部分由系统代发的密友状态栏通知仍无法精确隐藏。

反馈请提供手机型号、Android 版本、抖音版本、插件版本和复现步骤。
