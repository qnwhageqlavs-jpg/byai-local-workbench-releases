# 百应外呼工作台发布与下载

当前正式版本：**0.4.9**。本仓库提供 Windows 安装包、更新资产、员工指南与逐设备加密签名的 Token 同步文件，源码在私有仓库维护。

- [下载 0.4.9](https://github.com/qnwhageqlavs-jpg/byai-local-workbench-releases/releases/tag/v0.4.9)
- [员工操作指南](USER_GUIDE.md)
- [BYAI Token 自动同步首次配置](CREDENTIAL_SYNC.md)
- [完整更新说明](https://github.com/qnwhageqlavs-jpg/byai-local-workbench-releases/releases/download/v0.4.9/CHANGELOG.md)
- [升级与迁移](https://github.com/qnwhageqlavs-jpg/byai-local-workbench-releases/releases/download/v0.4.9/MIGRATION.md)
- [已知限制](https://github.com/qnwhageqlavs-jpg/byai-local-workbench-releases/releases/download/v0.4.9/KNOWN-LIMITATIONS.md)

每任务可选择50、100、150、200、300、500并发，默认200；第三步可修复当前园区失效匹配，或明确全部解绑重配，并撤销最近一次操作。同园区已被其他任务使用的数据包排后并浅黄标记，仍允许共用。修复跨盘更新目录切换及遗留安装中状态；保留四步排期、人工预览同步、拖拽与自动规划、线路记忆、内置Python和加密Token同步。

**旧更新器首次升级提醒：** 程序在C盘、数据和更新包在D盘时，旧版自动更新仍可能失败或卡在安装中。此时退出工作台后，使用0.4.9官方Setup覆盖原正式版程序目录，保留current/workbench-profile.json及其数据目录。旧helper无法仅靠发布新包自动修复；安装本版后后续更新使用新处理。

数据库schema保持7，旧任务并发默认200，历史快照不改写；话术、排期、凭据与执行历史保留，正式/测试数据不自动合并，不自动开始外呼。实际并发能力仍取决于百应账号和线路额度。

本次按用户授权跳过人工现场测试，已完成自动回归与安装包校验；企业网络、配额和透明加密仍需现场核对。内置Python依赖管理员白名单，同一百应账号下测试执行仍会创建真实任务。

Token文件与程序Release独立，CSMS保持原方式。客户资料、个人数据、明文凭据、私钥和数据库不得提交到本仓库。旧正式版本继续保留。
