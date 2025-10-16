# Excercise 1 - Linux, VSCode, SSH

## 1. 课前准备

在习题课开始之前，请完成以下准备工作：

- 配置 **WSL 2** （针对 Windows 用户）
  - [安装 WSL](https://learn.microsoft.com/windows/wsl/install?wt.mc_id=studentamb_407760)

- 安装 **Visual Studio Code**
  - [开始通过 WSL 使用 VSCode](https://learn.microsoft.com/windows/wsl/tutorials/wsl-vscode?wt.mc_id=studentamb_407760)
  - 欲了解 VSCode 的更多内容，可访问 [VSCode 文档](https://code.visualstudio.com/docs?wt.mc_id=studentamb_407760)

- 安装 **Termius**
  - [Termius 安装指南](https://support.termius.com/hc/en-us/articles/900007733143-Installation)

## 常见问题解答

- 在 Powershell 中运行 `wsl --install` 后提示 "A connection with the server could not be established" （或 "无法与服务器建立连接"），该怎么办？
  - WSL 安装过程会访问 https://raw.githubusercontent.com/microsoft/WSL/master/distributions/DistributionInfo.json ，可检查能否在浏览器中访问该链接。如无法访问，则确为网络问题
  - 解决方案参阅 microsoft/WSL#8025 及 microsoft/WSL#9460
