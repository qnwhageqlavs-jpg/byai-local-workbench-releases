# 百应外呼工作台发布与下载

当前正式版本：**0.4.6**。本仓库只发布安装包、更新资产和员工文档，源码在私有仓库维护。

- [下载 0.4.6](https://github.com/qnwhageqlavs-jpg/byai-local-workbench-releases/releases/tag/v0.4.6)
- [员工操作指南](USER_GUIDE.md)
- [完整版本说明](https://github.com/qnwhageqlavs-jpg/byai-local-workbench-releases/releases/download/v0.4.6/CHANGELOG.md)
- [升级与迁移说明](https://github.com/qnwhageqlavs-jpg/byai-local-workbench-releases/releases/download/v0.4.6/MIGRATION.md)
- [已知限制](https://github.com/qnwhageqlavs-jpg/byai-local-workbench-releases/releases/download/v0.4.6/KNOWN-LIMITATIONS.md)

本次从 0.4.0 升级：实际排期与执行共用数据、独立草稿与逐日同步对比、按园区复用核验、仪表盘批量删除及保存、独立环境身份与浏览器会话隔离、紧凑匹配问题侧栏、CSMS 映射重新启用。

安装前退出旧版并核对 SHA-256。公开 0.4.0 安装可沿用帮助与更新中的匿名升级；独立本地 0.4.4/0.4.5 构建首次升级必须使用安装包同目录覆盖并保留 workbench-profile.json，详见迁移说明。升级不自动合并两套历史，也不会附带个人数据库或凭据。

企业透明加密读取需管理员完成白名单授权并现场验证。独立测试环境若连接相同百应账号，真正执行外呼仍会影响远端账号。

客户资料、个人数据、凭据及数据库不得提交到本仓库。旧正式版本继续保留。
