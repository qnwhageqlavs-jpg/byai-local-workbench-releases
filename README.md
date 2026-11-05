# 百应外呼工作台发布与下载

当前正式版本：**0.4.10**。本仓库提供Windows安装包、程序更新资产与员工指南，源码在私有仓库维护。

- [下载0.4.10](https://github.com/qnwhageqlavs-jpg/byai-local-workbench-releases/releases/tag/v0.4.10)
- [员工操作指南](USER_GUIDE.md)
- [百应Token获取与管理员操作](CREDENTIAL_SYNC.md)
- [完整更新说明](https://github.com/qnwhageqlavs-jpg/byai-local-workbench-releases/releases/download/v0.4.10/CHANGELOG.md)
- [升级与迁移](https://github.com/qnwhageqlavs-jpg/byai-local-workbench-releases/releases/download/v0.4.10/MIGRATION.md)
- [已知限制](https://github.com/qnwhageqlavs-jpg/byai-local-workbench-releases/releases/download/v0.4.10/KNOWN-LIMITATIONS.md)

## 0.4.10
系统设置直接获取百应当前有效Token，成功后隐藏保存并显示真实到期时间；管理员密码解锁后可明确强制刷新。日常不再依赖GitHub凭据发布与设备申请码。首次由负责人在各电脑保存AppSecret并设置本机固定管理员密码，安装包不含公司秘密或万能密码。CSMS仍按原方式更新。

普通获取不带强刷参数；强刷后其他电脑旧Token约五分钟后失效，需点击获取最新Token。管理员密码是本机工作台门禁，持有AppSecret的人仍可自行调用百应接口。百应获取接口单并发，多台电脑遇繁忙时稍后重试。

保留0.4.9的50/100/150/200/300/500并发、默认200、当前园区匹配修复和撤销、共享包排序，以及跨盘更新修复。保留四步排期、拖拽、自动规划、人工预览同步、线路记忆与内置Python。

**旧更新器首次升级提醒：** 0.4.8及更早客户端程序在C盘、数据及更新包在D盘时仍可能更新失败；退出工作台后用最新官方Setup覆盖原程序目录，保留current/workbench-profile.json和数据目录。0.4.9起已修复更新器跨盘切换。

schema保持7；话术、排期与执行历史保留，正式/测试数据不合并，不自动开始外呼。程序更新仍从GitHub下载，与Token直接获取独立。

本版用户授权跳过人工现场验收，已完成自动回归与安装包校验；未用真实凭据执行OAuth强刷。企业网络、配额及透明加密仍需现场核对，内置Python需企业白名单。

客户资料、明文凭据、私钥及数据库不得提交到本仓库。旧版本继续保留；旧GitHub Token文件仅供旧版本兼容，新版不再自动应用。
