# 彩金统计工作台｜公开升级发布

此仓库只用于分发 Windows 安装包、数字签名升级清单和 SHA-256 校验文件，不存放源码、账本或客户数据。

软件内置的稳定升级清单地址：

```text
https://github.com/xsssxsssx888-cell/caijin-stat-platform-updates/releases/latest/download/latest.json
```

每次发布请创建 `caijin-v版本号` 格式的 Release，并上传以下附件：

- `CaijinStatPlatform-Setup-v版本号.exe`
- `latest.json`（由管理员电脑上的更新签名私钥签名）
- `SHA256SUMS.txt`

签名私钥只保存在管理员电脑，不得上传到本仓库。客户端会校验清单签名和安装包 SHA-256 后才运行安装程序。
