## Dev 与 Beta 预览版：OOBE 阶段可自定义用户文件夹名称

**编辑** | Ling Gao

微软在 2025 年 10 月 6 日发布的 [**Dev 26220.6772**](https://blogs.windows.com/windows-insider/2025/10/06/announcing-windows-11-insider-preview-build-26220-6772-dev-channel/) 和 [**Beta 26120.6772**](https://blogs.windows.com/windows-insider/2025/10/06/announcing-windows-11-insider-preview-build-26120-6772-beta-channel/) 版本中优化了用户文件夹命名机制，**允许用户在 OOBE 阶段自定义用户文件夹名称 (C:\Users\<名称>)**。

操作方法：在 OOBE 阶段的 “登录 Microsoft 账户” 页面按下 Shift + F10 打开命令提示符，输入 “cd oobe” 进入相应目录，执行 **“SetDefaultUserFolder.cmd <名称>”** 命令。

自定义名称最多 16 个字符；仅允许 Unicode 字符，不支持特殊字符。若用户未进行自定义，Windows 将默认采用 Microsoft 账户地址前 5 个字符作为文件夹名称。