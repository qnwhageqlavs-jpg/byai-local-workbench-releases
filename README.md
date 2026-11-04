# 百应外呼工作台发布与下载

当前正式版本：**0.4.8**。本仓库发布程序安装包、更新资产、员工文档及经过逐设备加密与签名的 Token 同步文件，源码在私有仓库维护。

- [下载 0.4.8](https://github.com/qnwhageqlavs-jpg/byai-local-workbench-releases/releases/tag/v0.4.8)
- [员工操作指南](USER_GUIDE.md)
- [BYAI Token 自动同步：首次配置](CREDENTIAL_SYNC.md)
- [完整版本说明](https://github.com/qnwhageqlavs-jpg/byai-local-workbench-releases/releases/download/v0.4.8/CHANGELOG.md)
- [升级与迁移](https://github.com/qnwhageqlavs-jpg/byai-local-workbench-releases/releases/download/v0.4.8/MIGRATION.md)
- [已知限制](https://github.com/qnwhageqlavs-jpg/byai-local-workbench-releases/releases/download/v0.4.8/KNOWN-LIMITATIONS.md)

本次新增 BYAI Token 的 GitHub 加密集中发布与自动同步，CSMS 不变；修复原文件移除后有效清洗结果不可匹配、重新扫描沿用旧文件版本；话术核验明确区分过期、认证、权限、名称及连接问题，集中提示系统凭据问题，保留文件准备结果与原文件错误。

同事首次需生成设备申请码，由负责人添加授权；负责人保存仅所选仓库 Contents 读写权限的 GitHub 发布凭据。完成授权并发布后，同事打开工作台或点击同步即可更新 BYAI Token 和到期时间。仅安装新版不会自动完成授权，不会发布真实 Token。凭据文件与程序 Release 分开管理，不在程序发布附件中混放 Token 包。

正式版可在「帮助与更新」检查并下载；校验通过后人工安装并重启。0.4.6 首次慢网络升级仍可使用本版 Setup。数据库 schema 保持 7，保留排期、话术、配置和执行历史；正式/测试数据继续隔离，不自动合并。覆盖安装时保留原程序目录和 workbench-profile.json。

透明加密读取仍需管理员给内置 Python 配置白名单；同一百应账号下测试执行会创建真实外呼任务。新 Token 同步经过模拟多设备测试，实际员工电脑授权和网络需现场验证。

客户资料、个人数据、明文凭据、任何私钥和数据库不得提交到本仓库。旧正式版本继续保留。
