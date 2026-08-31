# 百应本地任务工作台

百应本地任务工作台是一款面向 Windows 10/11 的内部外呼任务工具。每名员工在自己的电脑上独立安装，任务、客户数据、执行记录和凭据均保存在本机；本仓库只提供经过验证的安装包和公开使用说明，不公开源码。

## 第一次使用：下载、安装、启动

1. 打开[最新版本下载页](https://github.com/qnwhageqlavs-jpg/byai-local-workbench-releases/releases/latest)，不需要注册或登录 GitHub。
2. 找到页面底部的 **Assets**，下载名称类似 `BYAIWorkbench-版本号-Setup.exe` 的安装包。
3. 普通员工不要下载 `Source code`、`windows-x64.zip` 或 `release-manifest.json`；这些文件用于发布和程序更新校验。
4. 确认浏览器地址属于 `github.com/qnwhageqlavs-jpg/byai-local-workbench-releases`。如需校验文件，可同时下载 `SHA256SUMS.txt` 交给管理员核对。
5. 双击 Setup 安装包，按提示完成安装。当前内部版可能显示“未知发布者”；只有在文件来自上述官方页面且版本、校验值无误时才继续安装。
6. 从桌面或开始菜单打开“百应本地任务工作台”。

## 第一次打开后怎么配置

进入“系统设置”，按顺序完成：

1. 点击“一键导入配置”。本机有旧配置时会自动迁移；没有旧配置时，填写管理员提供的 Client ID、Company ID、手机号、Access Token 和有效期。
2. 保存当天的 CSMS Token。该 Token 跨天或超过 24 小时后需要重新获取。
3. 设置本机客户数据根目录。保存目录不会自动扫描，必须在“数据准备”页面手动点击扫描。
4. 检查园区别名与推广模块映射；缺少映射时按页面提示维护，不能随意选择近似模块。

不要把 Token、客户文件、完整数据目录或包含手机号的截图发送到群聊、邮件、网盘或 GitHub。

## 每天按这六步操作

`开工准备 → 任务计划 → 数据准备 → 任务配置 → 执行前检查 → 执行任务`

- 第 5 步只检查，不创建百应任务。
- 只有员工在第 6 步明确点击“执行任务”后，程序才会创建百应任务、回传 CSMS、导入客户并启动。
- 遇到“结果未确认”“部分成功”或“不确定”时，不要重复点击、改名重建或重新导入，应先到百应和 CSMS 后台核对。

完整步骤、首次任务检查方法和常见问题见[《员工使用手册》](USER_GUIDE.md)。

## 后续更新

从支持公开更新的版本开始，可在工作台“帮助与更新”中匿名检查新版本、下载、校验并安装，不需要 GitHub 授权。覆盖升级只替换程序，不删除本机任务、回执和设置；升级前仍应确认没有任务正在执行。

## 下载与求助

- [最新正式版本](https://github.com/qnwhageqlavs-jpg/byai-local-workbench-releases/releases/latest)
- [全部历史版本](https://github.com/qnwhageqlavs-jpg/byai-local-workbench-releases/releases)
- [员工使用手册](USER_GUIDE.md)

求助时只提供：程序版本、任务本地编号、错误代码、脱敏错误摘要和发生时间。不要提交 Token、手机号、客户数据、数据库或凭据文件。
