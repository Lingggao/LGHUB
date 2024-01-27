<SPAN ID = 'HEAD'/>
<img src="Images/LING.png" width = "25%" />

# 灵糕中心 (Linggao Hub)

[github.com/Lingggao/LGHUB](https://github.com/Lingggao/LGHUB)

&emsp;&emsp;用于跟踪 “**Windows 11 预览体验版本 (Canary 频道) 哪些反馈正在由 Microsoft 调查 / 处理 / 已做出更改**” 的信息枢纽。由 2021 Windows Insider Most Valuable Professional (MVP) · **Ling Gao** 先生管理。

> &emsp;**声明**：灵糕中心的管理者不是 Microsoft 公司全职员工 (FTE)，不能代表 Microsoft 公司立场、态度。中心无意且无法代替 “反馈中心” (Feedback Hub) 应用的重要作用。中心不提供 Microsoft 产品技术支持服务。中心不接受有关 Windows 11 预览体验版本的反馈，用户应始终通过 “反馈中心” 应用提交。

> &emsp;Windows、Windows Insider Program 等是 Microsoft 公司的商标。

&emsp;&emsp;**宗旨**：独立管理、服务用户、信息精准、更新及时。

[反馈中心](https://aka.ms/fbh) | [深入了解反馈](https://learn.microsoft.com/zh-cn/windows-insider/feedback) | [Flight Hub](https://learn.microsoft.com/en-us/windows-insider/flight-hub) | Windows 预览体验计划 - [网站](https://www.microsoft.com/zh-cn/windowsinsider) · [博客](https://blogs.windows.com/windows-insider) · [X (Twitter)](https://twitter.com/windowsinsider) · [社区](https://answers.microsoft.com/zh-hans/insider/forum)

## ✦ 总览 ✦

&emsp;&emsp;上次更新时间：2024 年 1 月 27 日 13:00 (UTC+8)。记录的反馈数量：53，访问次数：500+

&emsp;&emsp;中心更新目录：**今日更新 LG053 - 054 和反馈状态**。- Ling 1/27 😘 [获取总览图](https://raw.githubusercontent.com/Lingggao/LGHUB/main/Linggao%20Hub.png)

|  频道  |  最新版本  |   时间    |                         公告                         |
| :----: | :--------: | :-------: | :--------------------------------------------------: |
| Canary |   26040    | 2024/1/27 |      [aka.ms/wip26040](https://aka.ms/wip26040)      |
|  Dev   |   23620    | 2024/1/26 |      [aka.ms/wip23620](https://aka.ms/wip23620)      |
|  Beta  | 22635.3130 | 2024/1/26 | [aka.ms/wip-beta-1-25](https://aka.ms/wip-beta-1-25) |

| 编号 (点击跳转) |                             问题                             |       状态       |
| :-------------: | :----------------------------------------------------------: | :--------------: |
| [LG053](#LG053) |                                                              |     正在调查     |
| [LG054](#LG054) |                                                              |     正在调查     |
| [LG002](#LG002) |                部分热门游戏可能无法正常运行。                | 需要更多详细信息 |
| [LG004](#LG004) |            打开打印队列时提示 “找不到应用程序”。             |     正在处理     |
|     **——**      | [**Canary - 公告已知问题**](#0) **▲ \| ▼** [**Canary - 用户反馈问题**](#1) |      **——**      |
| [LG007](#LG007) |            切换桌面时任务栏应用图标可能随机消失。            |     正在调查     |
| [LG008](#LG008) |        “Wallpaper Engine：壁纸引擎” 等壁纸软件崩溃。         |     正在调查     |
| [LG013](#LG013) |           “设置”>“应用”>“启动” 页面中的图标异常。            |     正在调查     |
| [LG015](#LG015) |      在文件资源管理器中按下两次 F11 后地址栏将被冻结。       |     正在调查     |
| [LG018](#LG018) | Oracle VM VirtualBox 软件无法启动，显示 “Unknown rc=-3748” 错误。 |     正在处理     |
| [LG019](#LG019) |            远程桌面显示 “图形组件无法启动” 错误。            |     正在处理     |
| [LG021](#LG021) |      调节任务栏 “快速设置” 中的音量滑块时不再发出声音。      |     正在调查     |
| [LG022](#LG022) |            Windows Sandbox 显示 0x80072746 错误。            |     正在处理     |
| [LG024](#LG024) | Tips (提示) 应用现已移除，但 “Windows 更新”>“更新历史记录” 页面中的 “查看新增功能” 选项仍指向此应用，导致显示 “没有可打开 ms-get-started 链接的应用” 错误。 |     正在调查     |
| [LG028](#LG028) | 文件资源管理器地址栏中图标和箭头间有一个缝隙，可能导致不小心切换为编辑模式。 |     正在调查     |
| [LG030](#LG030) | 在 Microsoft Store 中下载 Xbox Identity Provider 时显示 0x80073CFB 错误。 |     正在调查     |
| [LG031](#LG031) |    Microsoft Edge (正式版) “固定到任务栏” 功能可能失效。     |     正在调查     |
| [LG033](#LG033) | “阿凡达：潘多拉边境” (Avatar Frontiers of Pandora) 游戏崩溃。 |     正在调查     |
| [LG034](#LG034) |          Grand Theft Auto V (GTA 5) 游戏无法运行。           |     正在调查     |
| [LG035](#LG035) |  极限竞速 (Forza Motorsport) Racing World 无法运行 / 崩溃。  |     正在调查     |
| [LG037](#LG037) |    显示 WDAG (Edge) - Container: Error: 0x80004005 错误。    |     正在处理     |
| [LG040](#LG040) |    文件资源管理器 “登录时还原上一个文件夹窗口” 选项失效。    |     正在调查     |
| [LG045](#LG045) |                        共享窗口崩溃。                        |     正在处理     |
| [LG046](#LG046) |           远程桌面显示 0x3 错误 / 0x11 扩展错误。            |     正在调查     |
| [LG047](#LG047) |         运行 WinSCP 时电脑出现 win32kbase.sys 绿屏。         |     正在处理     |
| [LG048](#LG048) | 极限竞速：地平线 5 (Forza Horizon 5) 游戏停止运行，显示 0xc0000005 错误。 |     正在调查     |
| [LG049](#LG049) |  事件查看器显示 DeviceSetupManager 元数据错误 (事件 131)。   |     正在调查     |
| [LG050](#LG050) |          启动 Print Spooler 服务时显示错误 / 崩溃。          |     正在调查     |
|     **——**      | [**Canary - 用户反馈问题**](#1) **▲ \| ▼** [**Canary - 归档 (已做出更改 14 - 28 天)**](#2) |      **——**      |
| [LG000](#LG000) |       无法下载 Build 26016 更新，显示 8024200D 错误。        |     已修复 ✓     |
| [LG003](#LG003) |            点击 “设置”>“系统”>“电源” 时菜单崩溃。            |     已修复 ✓     |
| [LG005](#LG005) |             Windows RE (恢复环境) 无法正确呈现。             |     已修复 ✓     |
| [LG006](#LG006) | 无法在桌面上使用 Ctrl 快捷键、ALT + F4 快捷键、Del 删除键。  |     已修复 ✓     |
| [LG038](#LG038) | Windows 电脑自动安装 HP Smart 应用 / 打印机图标变化，型号显示为 LaserJet M101-M106 / 双击打印机时显示 “此页面无可用任务” 错误。 |     已修复 ✓     |
| [LG009](#LG009) |              通过快捷键截图后无法直接打开图片。              |     已修复 ✓     |
| [LG011](#LG011) |      无法通过任务栏 “快速设置” 导航至 “节能模式” 菜单。      |     已修复 ✓     |
| [LG014](#LG014) |  在文件资源管理器中打开上下文菜单时崩溃 / 显示为旧版样式。   |     已修复 ✓     |
| [LG016](#LG016) |     文件资源管理器中 Filter 功能被错误地翻译为 “滤镜”。      |     已修复 ✓     |
| [LG017](#LG017) |            反馈中心无法在中国大陆网络环境中使用。            |     已修复 ✓     |
| [LG023](#LG023) | 电脑显示 Microsoft 365 家庭版订阅已过期，但实际上仍处于激活状态。 |     已修复 ✓     |
| [LG012](#LG012) |           截图工具的 “设置” 页面存在中文语法错误。           |     已修复 ✓     |
|     **NEW**     |                           **NEW**                            |     **NEW**      |
| [LG001](#LG001) |            可能无法打开设置菜单 / 设置菜单崩溃。             |     已修复 ✓     |
| [LG010](#LG010) |              任务栏 “快速设置” 中滑块颜色异常。              |     已修复 ✓     |
| [LG020](#LG020) |          部分游戏无法识别 Xbox 控制器 (手柄) 输入。          |     已修复 ✓     |
| [LG025](#LG025) |                   关闭电脑时电脑重新启动。                   |     已修复 ✓     |
| [LG026](#LG026) |                无法在 Microsoft Edge 中打印。                |     已修复 ✓     |
| [LG027](#LG027) | 打开 “设置”>“Windows 更新” 页面一段时间后设置菜单随机崩溃。  |     已修复 ✓     |
| [LG029](#LG029) |                桌面背景变黑 / 桌面图标消失。                 |     已修复 ✓     |
| [LG032](#LG032) | 连接 Citrix Desktop Viewer (CDViewer.exe) 几秒钟后，USER32.dll 崩溃。 |     已修复 ✓     |
| [LG036](#LG036) |      任务栏自动隐藏后，鼠标悬停在托盘区域无法将其激活。      |     已修复 ✓     |
| [LG039](#LG039) |               Copilot (预览版) 可能无法启动。                |     已修复 ✓     |
| [LG041](#LG041) |                   SurfShark VPN 停止工作。                   |     已修复 ✓     |
| [LG042](#LG042) |             自动 HDR 功能在游戏过程中意外关闭。              |     已修复 ✓     |
| [LG043](#LG043) |    Copilot 无法与其他窗口正确重叠 / 显示在其他窗口后方。     |     已修复 ✓     |
| [LG044](#LG044) |  将鼠标悬停在 Copilot 图标上时，单词错误地拼写为 Co-pilot。  |     已修复 ✓     |
| [LG051](#LG051) | Windows 更新菜单 “使用时段” 中显示的时间与选择的时间不一致。 |     已修复 ✓     |
| [LG052](#LG052) |    锁屏界面 Windows 聚焦随机显示其他语言的内容 (如泰文)。    |     已修复 ✓     |
|     **——**      |     ✦ [**Canary - 归档 (已做出更改 >28 天)**](28+.md) ✦      |      **——**      |

[**希望分享线索？联系 Ling Gao**](https://forms.office.com/Pages/ResponsePage.aspx?id=DQSIkWdsW0yxEjajBLZtrQAAAAAAAAAAAAO__Q3sH7RUNjUyUzJLN0JBREZGMzBBVlpVOEVBQkRENy4u)

**标准格式**

```markdown
<SPAN ID = 'LGxxx'/>编号：LGxxx  
版本：Canary xxxxx  
**问题**：**xxxxx**  
状态：正在调查 / 正在处理 / 需要更多详细信息 / 所做的更改 / (其他)  
Microsoft 官方回复 (如果有)：xxxxx  
典型反馈 (如果有)：[aka.ms/AAxxxxx](https://aka.ms/fbh)  
图像等补充信息 (如果有)
```

<SPAN ID = '0'/>

## ✦ Canary - 公告已知问题 ✦

&emsp;&emsp;记录 [Windows Insider 博客](https://blogs.windows.com/windows-insider)中明确公开的已知问题。

---

<SPAN ID = 'LG053'/>编号：LG053  
版本：Canary 26040  
**问题**：**xxxxx**  
状态：<img src="Images/L.png" width = "10%" />  
Microsoft 官方回复：xxxxx

---

<SPAN ID = 'LG054'/>编号：LG054  
版本：Canary 26040  
**问题**：**xxxxx**  
状态：<img src="Images/L.png" width = "10%" />  
Microsoft 官方回复：xxxxx

---

<SPAN ID = 'LG002'/>编号：LG002  
版本：Canary 25951 - 26040  
**问题**：**部分热门游戏可能无法正常运行**。  
状态：<img src="Images/I.png" width = "17%" />  
Microsoft 官方回复：“从 Build 26016 开始，更多游戏正在受到多个错误的影响。如果您在预览体验版本中玩游戏时发现任何问题，请务必在反馈中心提交。” *(Ling 译)* <img src="Images/M.png" width = "15%" />

---

<SPAN ID = 'LG004'/>编号：LG004  
版本：Canary 26010 - 26040  
**问题**：**打开打印队列时提示 “找不到应用程序”**。  
状态：<img src="Images/W.png" width = "10%" />  
Microsoft 官方回复：“我们已经找出问题所在，正在修复中。您可以复制 explorer.exe shell:appsFolder\Microsoft.Windows.PrintQueueActionCenter_cw5n1h2txyewy!App 到运行窗口 (WIN + R 快捷键) 打开打印队列，作为一种变通方案。” *(Caozhi Li 线索，Ling 译)* <img src="Images/M.png" width = "15%" />  
典型反馈：[aka.ms/AAod17l](https://aka.ms/AAod17l)

---

[**希望分享线索？联系 Ling Gao**](https://forms.office.com/Pages/ResponsePage.aspx?id=DQSIkWdsW0yxEjajBLZtrQAAAAAAAAAAAAO__Q3sH7RUNjUyUzJLN0JBREZGMzBBVlpVOEVBQkRENy4u)

<SPAN ID = '1'/>

## ✦ Canary - 用户反馈问题 ✦

&emsp;&emsp;记录[反馈中心应用](https://aka.ms/fbh)中 Microsoft 明确响应的问题。

---

<SPAN ID = 'LG007'/>编号：LG007  
版本：ALL - Canary 26040  
**问题**：**切换桌面时任务栏应用图标可能随机消失**。  
状态：<img src="Images/L.png" width = "10%" />  
Microsoft 官方回复：“我们在 Dev 频道中对此进行了修复，正在持续调查有关此问题的报告。” *(Ling 译)*  
<img src="Images/M.png" width = "15%" />  
典型反馈：[aka.ms/AAo73ko](https://aka.ms/AAo73ko)

<img src="Images/LG007.png" width = "50%" />

---

<SPAN ID = 'LG008'/>编号：LG008  
版本：Canary 26002 - 26040  
**问题**：**“Wallpaper Engine：壁纸引擎” 等壁纸软件崩溃**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAnwevt](https://aka.ms/AAnwevt)

---

<SPAN ID = 'LG013'/>编号：LG013  
版本：Canary 26002 - 26040  
**问题**：**“设置”>“应用”>“启动” 页面中的图标异常**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAo5wd6](https://aka.ms/AAo5wd6)

<img src="Images/LG013.png" width = "50%" />

---

<SPAN ID = 'LG015'/>编号：LG015  
版本：Canary 25992 - 26040  
**问题**：**在文件资源管理器中按下两次 F11 后地址栏将被冻结**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAnkkd6](https://aka.ms/AAnkkd6)

---

<SPAN ID = 'LG018'/>编号：LG018  
版本：Canary 25987 - 26040  
**问题**：**Oracle VM VirtualBox 软件无法启动，显示 “Unknown rc=-3748” 错误**。  
状态：<img src="Images/W.png" width = "10%" />  
典型反馈：[aka.ms/AAo7kst](https://aka.ms/AAo7kst)

---

<SPAN ID = 'LG019'/>编号：LG019  
版本：Canary 25997 - 26040  
**问题**：**远程桌面显示 “图形组件无法启动” 错误**。  
状态：<img src="Images/W.png" width = "10%" />  
典型反馈：[aka.ms/AAnyzb4](https://aka.ms/AAnyzb4)

---

<SPAN ID = 'LG021'/>编号：LG021  
版本：Canary 26002 - 26040  
**问题**：**调节任务栏 “快速设置” 中的音量滑块时不再发出声音**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAo4oyt](https://aka.ms/AAo4oyt)

---

<SPAN ID = 'LG022'/>编号：LG022  
版本：Canary 25997 - 26040  
**问题**：**Windows Sandbox 显示 0x80072746 错误**。  
状态：<img src="Images/W.png" width = "10%" />  
典型反馈：[aka.ms/AAo6y4i](https://aka.ms/AAo6y4i)

---

<SPAN ID = 'LG024'/>编号：LG024  
版本：Canary 26002 - 26040  
**问题**：**Tips (提示) 应用现已移除，但 “Windows 更新”>“更新历史记录” 页面中的 “查看新增功能” 选项仍指向此应用，导致显示 “没有可打开 ms-get-started 链接的应用” 错误**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAo7div](https://aka.ms/AAo7div)

<img src="Images/LG024.png" width = "50%" />

---

<SPAN ID = 'LG028'/>编号：LG028  
版本：未知 - Canary 26040  
**问题**：**文件资源管理器地址栏中图标和箭头间有一个缝隙，可能导致不小心切换为编辑模式**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAo7kib](https://aka.ms/AAo7kib)

<img src="Images/LG028.png" width = "50%" />

---

<SPAN ID = 'LG030'/>编号：LG030  
版本：Canary 25905 - 26040  
**问题**：**在 Microsoft Store 中下载 Xbox Identity Provider 时显示 0x80073CFB 错误**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAlzfg7](https://aka.ms/AAlzfg7)

---

<SPAN ID = 'LG031'/>编号：LG031  
版本：ALL  
**问题**：**Microsoft Edge (正式版) “固定到任务栏” 功能可能失效**。  
状态：<img src="Images/L.png" width = "10%" />  
Microsoft 官方回复：“Edge 团队正在积极研究中。” *(Ling 译)* <img src="Images/M.png" width = "15%" />

<img src="Images/LG031.png" width = "35%" />

---

<SPAN ID = 'LG033'/>编号：LG033  
版本：Canary 26016 - 26040  
**问题**：**“阿凡达：潘多拉边境” (Avatar Frontiers of Pandora) 游戏崩溃**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAoa2ag](https://aka.ms/AAoa2ag)

---

<SPAN ID = 'LG034'/>编号：LG034  
版本：Canary 26016 - 26040  
**问题**：**Grand Theft Auto V (GTA 5) 游戏无法运行**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAo9e71](https://aka.ms/AAo9e71)

---

<SPAN ID = 'LG035'/>编号：LG035  
版本：Canary 26016 - 26040  
**问题**：**极限竞速 (Forza Motorsport) Racing World 无法运行 / 崩溃**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAo9e77](https://aka.ms/AAo9e77)

---

<SPAN ID = 'LG037'/>编号：LG037  
版本：Canary 25997 - 26040  
**问题**：**显示 WDAG (Edge) - Container: Error: 0x80004005 错误**。  
状态：<img src="Images/W.png" width = "10%" />  
Microsoft 官方回复：“我们正在努力修复此问题。” *(Ling 译)* <img src="Images/M.png" width = "15%" />  
典型反馈：[aka.ms/AAnzef8](https://aka.ms/AAnzef8)

---

<SPAN ID = 'LG040'/>编号：LG040  
版本：未知 - Canary 26040  
**问题**：**文件资源管理器 “登录时还原上一个文件夹窗口” 选项失效**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAoawwk](https://aka.ms/AAoawwk)

<img src="Images/LG040.png" width = "30%" />

---

<SPAN ID = 'LG045'/>编号：LG045  
版本：ALL  
**问题**：**共享窗口崩溃**。  
状态：<img src="Images/W.png" width = "10%" />  
典型反馈：[aka.ms/AAohsni](https://aka.ms/AAohsni)

---

<SPAN ID = 'LG046'/>编号：LG046  
版本：Canary 26020 - 26040  
**问题**：**远程桌面显示 0x3 错误 / 0x11 扩展错误**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAnyjyk](https://aka.ms/AAnyjyk)

---

<SPAN ID = 'LG047'/>编号：LG047  
版本：Canary 26020 - 26040  
**问题**：**运行 WinSCP 时电脑出现 win32kbase.sys 绿屏**。  
状态：<img src="Images/W.png" width = "10%" />  
典型反馈：[aka.ms/AAoiwp6](https://aka.ms/AAoiwp6)

---

<SPAN ID = 'LG048'/>编号：LG048  
版本：Canary 26016 - 26040  
**问题**：**极限竞速：地平线 5 (Forza Horizon 5) 游戏停止运行，显示 0xc0000005 错误**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAojirz](https://aka.ms/AAojirz)

---

<SPAN ID = 'LG049'/>编号：LG049  
版本：Canary 26020 - 26040  
**问题**：**事件查看器显示 DeviceSetupManager 元数据错误 (事件 131)**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAoipfs](https://aka.ms/AAoipfs)

---

<SPAN ID = 'LG050'/>编号：LG050  
版本：Canary 26016 - 26040  
**问题**：**启动 Print Spooler 服务时显示错误 / 崩溃**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAoiwqe](https://aka.ms/AAoiwqe)

---

[**希望分享线索？联系 Ling Gao**](https://forms.office.com/Pages/ResponsePage.aspx?id=DQSIkWdsW0yxEjajBLZtrQAAAAAAAAAAAAO__Q3sH7RUNjUyUzJLN0JBREZGMzBBVlpVOEVBQkRENy4u)

<SPAN ID = '2'/>

## ✦ Canary - 归档 (已做出更改 >14 天) ✦

&emsp;&emsp;记录 Microsoft 已做出更改 14 - 28 天的问题。无特殊情况，问题归档后不再更新。

---

<SPAN ID = 'LG001'/>编号：LG001  
版本：Canary 26010 - 26020  
**问题**：**可能无法打开设置菜单 / 设置菜单崩溃**。  
状态：Canary 26040 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
Microsoft 官方回复：“我们正在调查导致部分 Insiders 无法打开 ‘设置’ 菜单的问题。如果您正在受此影响，请查看下面的社区话题了解解决方案。” *(Ling 译)* <img src="Images/M.png" width = "15%" />

[临时解决方案](https://aka.ms/26010SettingsCrash) *(Jason Howard 整理)*

---

<SPAN ID = 'LG010'/>编号：LG010  
版本：Canary 26010 - 26020  
**问题**：**任务栏 “快速设置” 中滑块颜色异常**。  
状态：Canary 26040 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAo74l5](https://aka.ms/AAo74l5)

<img src="Images/LG010.png" width = "25%" />

---

<SPAN ID = 'LG020'/>编号：LG020  
版本：Canary 25982 - 26020  
**问题**：**部分游戏无法识别 Xbox 控制器 (手柄) 输入**。  
状态：Canary 26040 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAny4gq](https://aka.ms/AAny4gq)

---

<SPAN ID = 'LG025'/>编号：LG025  
版本：未知 - Canary 26020  
**问题**：**关闭电脑时电脑重新启动**。  
状态：Canary 26040 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAo6y4u](https://aka.ms/AAo6y4u)

---

<SPAN ID = 'LG026'/>编号：LG026  
版本：ALL  
**问题**：**无法在 Microsoft Edge 中打印**。  
状态：<img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
Microsoft 官方回复：“Edge 团队正在处理此事。” *(Ling 译)* <img src="Images/M.png" width = "15%" />  
典型反馈：[aka.ms/AAo7djt](https://aka.ms/AAo7djt)

---

<SPAN ID = 'LG027'/>编号：LG027  
版本：Canary 26010 - 26020  
**问题**：**打开 “设置”>“Windows 更新” 页面一段时间后设置菜单随机崩溃**。  
状态：Canary 26040 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAo6qvy](https://aka.ms/AAo6qvy)

---

<SPAN ID = 'LG029'/>编号：LG029  
版本：Canary 26002 - 26020  
**问题**：**桌面背景变黑 / 桌面图标消失**。  
状态：Canary 26040 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
Microsoft 官方回复：“此问题似乎与部分壁纸软件或桌面个性化软件有关。在我们调查期间，您可能需要暂时关闭这类软件。” *(Ling 译)* <img src="Images/M.png" width = "15%" />  
典型反馈：[aka.ms/AAo7kvj](https://aka.ms/AAo7kvj)

---

<SPAN ID = 'LG032'/>编号：LG032  
版本：Canary 26016 - 26020  
**问题**：**连接 Citrix Desktop Viewer (CDViewer.exe) 几秒钟后，USER32.dll 崩溃**。  
状态：Canary 26040 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAoa2a8](https://aka.ms/AAoa2a8)

---

<SPAN ID = 'LG036'/>编号：LG036  
版本：Canary 26002 - 26020  
**问题**：**任务栏自动隐藏后，鼠标悬停在托盘区域无法将其激活**。  
状态：Canary 26040 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
Microsoft 官方回复：“我们已经找出问题所在，正在修复中。” *(Ling 译)* <img src="Images/M.png" width = "15%" />  
典型反馈：[aka.ms/AAo9oc7](https://aka.ms/AAo9oc7)

<img src="Images/LG036.png" width = "50%" />

---

<SPAN ID = 'LG039'/>编号：LG039  
版本：Canary 26016 - 26020  
**问题**：**Copilot (预览版) 可能无法启动**。  
状态：Canary 26040 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAoan4g](https://aka.ms/AAoan4g)

<img src="Images/LG039.png" width = "50%" />

---

<SPAN ID = 'LG041'/>编号：LG041  
版本：Canary 26016 - 26020  
**问题**：**SurfShark VPN 停止工作**。  
状态：Canary 26040 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAobhcg](https://aka.ms/AAobhcg)

---

<SPAN ID = 'LG042'/>编号：LG042  
版本：未知 - Canary 26020  
**问题**：**自动 HDR 功能在游戏过程中意外关闭**。  
状态：Canary 26040 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
Microsoft 官方回复：“我们需要更多细节。请在反馈中心使用 ‘重现问题’ 功能，向我们发送日志。” *(Ling 译)*  
<img src="Images/M.png" width = "15%" />  
典型反馈：[aka.ms/AAo77ve](https://aka.ms/AAo77ve)

---

<SPAN ID = 'LG043'/>编号：LG043  
版本：Canary 26020  
**问题**：**Copilot 无法与其他窗口正确重叠 / 显示在其他窗口后方**。  
状态：Canary 26040 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAoi08a](https://aka.ms/AAoi08a)

---

<SPAN ID = 'LG044'/>编号：LG044  
版本：Canary 26020  
**问题**：**将鼠标悬停在 Copilot 图标上时，单词错误地拼写为 Co-pilot**。  
状态：Canary 26040 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAoi08e](https://aka.ms/AAoi08e)

---

<SPAN ID = 'LG051'/>编号：LG051  
版本：Canary 26016 - 26020  
**问题**：**Windows 更新菜单 “使用时段” 中显示的时间与选择的时间不一致**。  
状态：Canary 26040 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
Microsoft 官方回复：“我们正在努力修复此问题。” *(Ling 译)* <img src="Images/M.png" width = "15%" />  
典型反馈：[aka.ms/AAoj5el](https://aka.ms/AAoj5el)

<img src="Images/LG051.png" width = "50%" />

---

<SPAN ID = 'LG052'/>编号：LG052  
版本：Canary 26020  
**问题**：**锁屏界面 Windows 聚焦随机显示其他语言的内容 (如泰文)**。  
状态：Canary 26040 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAopddk](https://aka.ms/AAopddk)

---

[Microsoft 已做出更改 >28 天的问题](28+.md)

[**希望分享线索？联系 Ling Gao**](https://forms.office.com/Pages/ResponsePage.aspx?id=DQSIkWdsW0yxEjajBLZtrQAAAAAAAAAAAAO__Q3sH7RUNjUyUzJLN0JBREZGMzBBVlpVOEVBQkRENy4u)

---

[回到顶部](#HEAD)

<img src="https://mirrors.creativecommons.org/presskit/icons/cc.xlarge.png" width = "3%" /> <img src="https://mirrors.creativecommons.org/presskit/icons/by.xlarge.png" width = "3%" /> <img src="https://mirrors.creativecommons.org/presskit/icons/sa.xlarge.png" width = "3%" />

在 “[署名 - 相同方式共享 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode.zh-Hans)” 协议 (CC BY-SA 4.0) 之条款下提供。

2023 - 2024, 高楷修 (Ling Gao), 灵糕中心 (Linggao Hub), [github.com/Lingggao/LGHUB](https://github.com/Lingggao/LGHUB)

[字体许可使用授权书](Images/字体许可使用授权书.png) | [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FLingggao%2FLGHUB&count_bg=%23737373&title_bg=%230078D7&icon=microsoft.svg&icon_color=%23FFFFFF&title=LGHUB&edge_flat=false)](https://hits.seeyoufarm.com) (访问次数统计：今日 / 累计)