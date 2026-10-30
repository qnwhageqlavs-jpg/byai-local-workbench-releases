# 百应外呼工作台发布与下载

当前正式版本：**0.4.7**。本仓库只发布安装包、更新资产和员工文档，源码在私有仓库维护。

- [下载 0.4.7](https://github.com/qnwhageqlavs-jpg/byai-local-workbench-releases/releases/tag/v0.4.7)
- [员工操作指南](USER_GUIDE.md)
- [完整版本说明](https://github.com/qnwhageqlavs-jpg/byai-local-workbench-releases/releases/download/v0.4.7/CHANGELOG.md)
- [升级与迁移说明](https://github.com/qnwhageqlavs-jpg/byai-local-workbench-releases/releases/download/v0.4.7/MIGRATION.md)
- [已知限制](https://github.com/qnwhageqlavs-jpg/byai-local-workbench-releases/releases/download/v0.4.7/KNOWN-LIMITATIONS.md)

本次基于 0.4.6：更新下载显示真实进度，慢下载持续查询，临时状态读取失败自动重试，刷新或浏览器后退返回可接续进度；校验完成后由用户点击安装并重启。精简清洗、匹配、仪表盘及开工准备页的重复说明，保留业务功能与必要状态提示。

0.4.6 更新自身时仍使用旧更新界面，新进度条在安装 0.4.7 后生效。若旧页面慢下载等待超时，可退出程序后使用本版官方 Setup 覆盖原程序目录并保留环境配置。数据库结构仍为版本 7，不清空话术、排期、配置或执行历史。

安装前退出旧版并核对 SHA-256。独立本地 0.4.4/0.4.5 构建首次升级必须使用安装包同目录覆盖并保留 workbench-profile.json，详见迁移说明。正式版日常使用并检查公开更新，测试版用于本地验证，两套数据不自动合并。

企业透明加密读取需管理员完成白名单授权并现场验证。独立测试环境若连接相同百应账号，真正执行外呼仍会影响远端账号。

客户资料、个人数据、凭据及数据库不得提交到本仓库。旧正式版本继续保留。
