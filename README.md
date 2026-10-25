# HoK Helper 测试版发布

手机版当前版本 **0.2.9**；Windows 工作台仍为 **0.2.7**。本仓库仅分发安装包、摘要及更新清单，应用源码保持私有。

[下载手机版 0.2.9](https://github.com/Michael37-tech/HoK-Helper-Releases/releases/tag/v0.2.9)

版本 0.2.9 / versionCode 19，Android 14 及以上。沿用已有个人测试签名，可覆盖安装。Windows 工作台继续使用 0.2.7。

- 悬浮箭头改为自绘细圆头折线，上下把手缩为 48×20 dp，顶部收纳紧贴屏幕上沿，不再为隐藏状态栏预留空白。
- 保留点击与向内拖动展开、沿边移动、四边收纳及位置记忆。
- 删除当前详情中的战绩后自动返回“我的战绩”首页；取消删除仍保留详情。
- 页面重建时等待战绩载入后再判断记录是否存在，保留未删除记录的详情和列表状态。

未更改数据库结构、截图识别与电脑同步协议。已通过模拟器回归，真实手机和游戏环境仍需实际体验。

Windows 工作台 0.2.7：https://github.com/Michael37-tech/HoK-Helper-Releases/releases/tag/v0.2.7

`update.json` 供手机版检查更新；GitHub 自动生成的 Source code 仅为分发资料，不是应用源码。
