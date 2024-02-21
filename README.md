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

&emsp;&emsp;上次更新时间：2024 年 2 月 21 日 12:00 (UTC+8)。记录的反馈数量：102，访问次数：880+

&emsp;&emsp;中心更新目录：**今日更新 LG095-101。**- Ling 😀 [总览图](https://raw.githubusercontent.com/Lingggao/LGHUB/main/Linggao%20Hub.png) | [已修复图](https://raw.githubusercontent.com/Lingggao/LGHUB/main/Linggao%20Hub_Fixed.png)

|     频道     |  最新版本  |   时间    |                             公告                             |
| :----------: | :--------: | :-------: | :----------------------------------------------------------: |
| Canary & Dev |   26058    | 2024/2/15 | [aka.ms/wip26058](https://blogs.windows.com/windows-insider/2024/02/14/announcing-windows-11-insider-preview-build-26058-canary-and-dev-channels) |
|     Beta     | 22635.3209 | 2024/2/17 | [aka.ms/wip-beta-2-16](https://blogs.windows.com/windows-insider/2024/02/16/announcing-windows-11-insider-preview-build-22635-3209-beta-channel) |

| 编号 (点击跳转) |                             问题                             |            状态            |
| :-------------: | :----------------------------------------------------------: | :------------------------: |
| [LG002](#LG002) |                部分热门游戏可能无法正常运行。                | 需要更多详细信息、正在处理 |
| [LG068](#LG068) |         回退系统将导致开发驱动器硬盘损坏并丢失数据。         |          正在处理          |
| [LG066](#LG066) | 设置 > 系统 > 屏幕 > 显示卡位置出现 “显示连接” 选项，点击时菜单崩溃。 |          正在处理          |
| [LG069](#LG069) |       安装此版本时可能自动回退，错误代码 0xC1900101。        |          正在调查          |
| [LG070](#LG070) |  连接 VPN 时，托盘网络图标 / 部分应用可能提示无 Internet。   |          正在处理          |
| [LG071](#LG071) |    输入切换器 (WIN + 空格) 变为旧版样式，且显示位置错误。    |          正在调查          |
| [LG072](#LG072) | 此版本无法显示在 “设置”>“Windows 更新”>“更新历史记录” 页面。 |          正在调查          |
| [LG073](#LG073) |         文件资源管理器的右键菜单可能丢失亚克力效果。         |          正在处理          |
| [LG074](#LG074) |                小组件看板可能不显示任何内容。                |          正在处理          |
|     **——**      | [**Canary - 公告已知问题**](#0) **▲ \| ▼** [**Canary - 用户反馈问题**](#1) |           **——**           |
| [LG013](#LG013) |           “设置”>“应用”>“启动” 页面中的图标异常。            |          正在调查          |
| [LG015](#LG015) |      在文件资源管理器中按下两次 F11 后地址栏将被冻结。       |          正在调查          |
| [LG018](#LG018) | Oracle VM VirtualBox 软件无法启动，显示 “Unknown rc=-3748” 错误。 |          正在处理          |
| [LG019](#LG019) |            远程桌面显示 “图形组件无法启动” 错误。            |          正在处理          |
| [LG024](#LG024) | Tips (提示) 应用现已移除，但 “Windows 更新”>“更新历史记录” 页面中的 “查看新增功能” 选项仍指向此应用，导致显示 “没有可打开 ms-get-started 链接的应用” 错误。 |          正在调查          |
| [LG030](#LG030) | 在 Microsoft Store 中下载 Xbox Identity Provider 时显示 0x80073CFB 错误。 |          正在调查          |
| [LG031](#LG031) |    Microsoft Edge (正式版) “固定到任务栏” 功能可能失效。     |          正在调查          |
| [LG033](#LG033) | “阿凡达：潘多拉边境” (Avatar Frontiers of Pandora) 游戏崩溃。 |          正在调查          |
| [LG034](#LG034) |          Grand Theft Auto V (GTA 5) 游戏无法运行。           |          正在调查          |
| [LG037](#LG037) |    显示 WDAG (Edge) - Container: Error: 0x80004005 错误。    |          正在处理          |
| [LG040](#LG040) |    文件资源管理器 “登录时还原上一个文件夹窗口” 选项失效。    |          正在调查          |
| [LG046](#LG046) |           远程桌面显示 0x3 错误 / 0x11 扩展错误。            |          正在调查          |
| [LG049](#LG049) |  事件查看器显示 DeviceSetupManager 元数据错误 (事件 131)。   |          正在调查          |
| [LG055](#LG055) |              隐藏 “购物” 等小组件后其再次出现。              |          正在调查          |
| [LG057](#LG057) |              战眼 (BattlEye) 反作弊系统不兼容。              |          正在调查          |
| [LG058](#LG058) | 在 Microsoft Store 更新 “快速助手” 应用时显示 0x80073CFB 错误。 |          正在调查          |
| [LG059](#LG059) |               罗布乐思 (Roblox) 无法正常运行。               |          正在调查          |
| [LG060](#LG060) |            堡垒之夜 (Fortnite) 游戏无法正常运行。            |          正在调查          |
| [LG061](#LG061) |                    EA 反作弊系统不兼容。                     |          正在调查          |
| [LG062](#LG062) |    彩虹六号：围攻 (Rainbow Six Siege) 游戏无法正常运行。     |          正在调查          |
| [LG063](#LG063) |              绝地求生 (PUBG) 游戏无法正常运行。              |          正在调查          |
| [LG064](#LG064) |   全新安装 Windows 11 时，系统生成 Windows.old 空文件夹。    |          正在调查          |
| [LG065](#LG065) |              使用浏览器观看视频时屏幕可能冻结。              |          正在处理          |
| [LG077](#LG077) |        启用 “管理移动设备” 时，“手机连接” 应用断线。         |          正在调查          |
| [LG078](#LG078) |                      电脑无法播放音频。                      |          正在调查          |
| [LG079](#LG079) |            无法使用 Office，显示 0x426-0x0 错误。            |          正在调查          |
| [LG080](#LG080) |                       Visio 应用崩溃。                       |          正在处理          |
| [LG081](#LG081) |               无法登录 Microsoft Sudoku 游戏。               |          正在调查          |
| [LG082](#LG082) |       文件资源管理器右键菜单中的图标显示在错误的位置。       |          正在调查          |
| [LG083](#LG083) |                    光标阴影 / 形状异常。                     |          正在调查          |
| [LG084](#LG084) |                    光标随机消失 / 卡住。                     |          正在调查          |
| [LG085](#LG085) |         战地风云 2042 (Battlefield 2042) 游戏崩溃。          |          正在调查          |
| [LG086](#LG086) |        逃离塔科夫 (Escape from Tarkov) 游戏无法启动。        |          正在调查          |
| [LG087](#LG087) |               新版 Microsoft Teams 应用崩溃。                |          正在调查          |
| [LG088](#LG088) |       无法使用截图工具对开始菜单 / 右键菜单进行截图。        |          正在调查          |
| [LG089](#LG089) |                 Steam 平台窗口可能无法打开。                 |          正在调查          |
| [LG090](#LG090) |        百战天虫：大杀器 (Worms W.M.D) 游戏无法启动。         |          正在调查          |
| [LG091](#LG091) |  生化危机4：重制版 (Resident Evil 4 Remake) 游戏无法启动。   |          正在调查          |
| [LG092](#LG092) |              命运 2 (Destiny 2) 游戏无法启动。               |          正在调查          |
| [LG093](#LG093) |                   放大镜无法跟随鼠标移动。                   |          正在调查          |
| [LG094](#LG094) |           相机和 Studio Effects 可能无法正常工作。           |          正在调查          |
| [LG095](#LG095) | **通过 Microsoft Store / Xbox 下载盗贼之海 (Sea of Thieves) 游戏时显示 0x87E0000D 错误**。 |          正在处理          |
| [LG097](#LG097) |           **最终决战 (THE FINALS) 游戏无法启动**。           |          正在调查          |
| [LG098](#LG098) |          **战地 5 (Battlefield Ⅴ) 游戏无法启动**。           |          正在调查          |
| [LG099](#LG099) |      **赛博朋克 2077 (Cyberpunk 2077) 游戏无法启动**。       |          正在调查          |
| [LG100](#LG100) |        **守望先锋：归来 (OVERWATCH2) 游戏无法启动**。        |          正在调查          |
| [LG101](#LG101) |                **EA SPORTS FC 24 游戏崩溃**。                |          正在调查          |
|     **——**      | [**Canary - 用户反馈问题**](#1) **▲ \| ▼** [**Canary - 归档 (已做出更改 0 - 28 天)**](#2) |           **——**           |
| [LG056](#LG056) |             显示器黑屏 / 电脑无法从睡眠中唤醒。              |          已修复 ✓          |
| [LG054](#LG054) |   Microsoft Store 中的部分视频流媒体应用可能无法正常播放。   |          已修复 ✓          |
| [LG075](#LG075) |     “设置”>“系统”>“可选功能” 页面中所有功能均为 0 字节。     |          已修复 ✓          |
| [LG022](#LG022) |     Windows Sandbox 显示 0x80072746 / 0x800736b3 错误。      |          已修复 ✓          |
| [LG076](#LG076) |    “设置”>“Windows 更新” 页面的 “上次检查时间” 存在错误。    |          已修复 ✓          |
| [LG028](#LG028) | 文件资源管理器地址栏中图标和箭头间有一个缝隙，可能导致不小心切换为编辑模式。 |          已修复 ✓          |
| [LG045](#LG045) |                        共享窗口崩溃。                        |          已修复 ✓          |
| [LG096](#LG096) |   安装 KB5035384 (26052.1100) 更新时显示 0x800f0904 错误。   |          已修复 ✓          |
|     **——**      |     ✦ [**Canary - 归档 (已做出更改 >28 天)**](28+.md) ✦      |           **——**           |

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

<SPAN ID = 'LG002'/>编号：LG002  
版本：Canary 25951 - 26058  
**问题**：**部分热门游戏可能无法正常运行**。  
状态：<img src="Images/I.png" width = "17%" /> <img src="Images/W.png" width = "10%" />  
Microsoft 官方回复：“从 Build 26016 开始，更多游戏正在受到多个错误的影响。从 Build 26040 开始，部分游戏可能导致电脑绿屏。如果您在预览体验版本中玩游戏时发现任何问题，请务必在反馈中心提交。” *(Ling 译)*  
<img src="Images/M.png" width = "15%" />

---

<SPAN ID = 'LG068'/>编号：LG068  
版本：Canary 26052 - 26058  
**问题**：**回退系统将导致开发驱动器硬盘损坏并丢失数据**。  
状态：<img src="Images/W.png" width = "10%" />  
Microsoft 官方回复：“请在回退前备份开发驱动器硬盘。” *(Ling 译)* <img src="Images/M.png" width = "15%" />

---

<SPAN ID = 'LG066'/>编号：LG066  
版本：Canary 26052 - 26058  
**问题**：**设置 > 系统 > 屏幕 > 显示卡位置出现 “显示连接” 选项，点击时菜单崩溃**。  
状态：<img src="Images/W.png" width = "10%" />  
Microsoft 官方回复：“此选项将在未来的版本中移除。” *(Ling 译)* <img src="Images/M.png" width = "15%" />

<img src="Images/LG066.png" width = "50%" />

---

<SPAN ID = 'LG069'/>编号：LG069  
版本：Canary 26058  
**问题**：**安装此版本时可能自动回退，错误代码 0xC1900101**。  
状态：<img src="Images/L.png" width = "10%" />

---

<SPAN ID = 'LG070'/>编号：LG070  
版本：Canary 26058  
**问题**：**连接 VPN 时，托盘网络图标 / 部分应用可能提示无 Internet**。  
状态：<img src="Images/W.png" width = "10%" />

---

<SPAN ID = 'LG071'/>编号：LG071  
版本：Canary 26052 - 26058  
**问题**：**输入切换器 (WIN + 空格) 变为旧版样式，且显示位置错误**。  
状态：<img src="Images/L.png" width = "10%" />  
Microsoft 官方回复：“我们正在调查此问题，请耐心等待。” *(Ling 译)* <img src="Images/M.png" width = "15%" />  
典型反馈：[aka.ms/AAp5tgd](https://aka.ms/AAp5tgd)

<img src="Images/LG071.png" width = "15%" />

---

<SPAN ID = 'LG072'/>编号：LG072  
版本：Canary 26058  
**问题**：**此版本无法显示在 “设置”>“Windows 更新”>“更新历史记录” 页面**。  
状态：<img src="Images/L.png" width = "10%" />

<img src="Images/LG072.png" width = "40%" />

---

<SPAN ID = 'LG073'/>编号：LG073  
版本：Canary 26058  
**问题**：**文件资源管理器的右键菜单可能丢失亚克力效果**。  
状态：<img src="Images/W.png" width = "10%" />  
Microsoft 官方回复：“此问题将在未来的版本中得到修复。” *(Ling 译)* <img src="Images/M.png" width = "15%" />

---

<SPAN ID = 'LG074'/>编号：LG074  
版本：Canary 26058  
**问题**：**小组件看板可能不显示任何内容**。  
状态：<img src="Images/W.png" width = "10%" />

---

[**希望分享线索？联系 Ling Gao**](https://forms.office.com/Pages/ResponsePage.aspx?id=DQSIkWdsW0yxEjajBLZtrQAAAAAAAAAAAAO__Q3sH7RUNjUyUzJLN0JBREZGMzBBVlpVOEVBQkRENy4u)

<SPAN ID = '1'/>

## ✦ Canary - 用户反馈问题 ✦

&emsp;&emsp;记录[反馈中心应用](https://aka.ms/fbh)中 Microsoft 明确响应的问题。

---

<SPAN ID = 'LG013'/>编号：LG013  
版本：Canary 26002 - 26058  
**问题**：**“设置”>“应用”>“启动” 页面中的图标异常**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAo5wd6](https://aka.ms/AAo5wd6)

<img src="Images/LG013.png" width = "50%" />

---

<SPAN ID = 'LG015'/>编号：LG015  
版本：Canary 25992 - 26058  
**问题**：**在文件资源管理器中按下两次 F11 后地址栏将被冻结**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAnkkd6](https://aka.ms/AAnkkd6)

---

<SPAN ID = 'LG018'/>编号：LG018  
版本：Canary 25987 - 26058  
**问题**：**Oracle VM VirtualBox 软件无法启动，显示 “Unknown rc=-3748” 错误**。  
状态：<img src="Images/W.png" width = "10%" />  
典型反馈：[aka.ms/AAo7kst](https://aka.ms/AAo7kst)

---

<SPAN ID = 'LG019'/>编号：LG019  
版本：Canary 25997 - 26058  
**问题**：**远程桌面显示 “图形组件无法启动” 错误**。  
状态：<img src="Images/W.png" width = "10%" />  
典型反馈：[aka.ms/AAnyzb4](https://aka.ms/AAnyzb4)

---

<SPAN ID = 'LG024'/>编号：LG024  
版本：Canary 26002 - 26058  
**问题**：**Tips (提示) 应用现已移除，但 “Windows 更新”>“更新历史记录” 页面中的 “查看新增功能” 选项仍指向此应用，导致显示 “没有可打开 ms-get-started 链接的应用” 错误**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAo7div](https://aka.ms/AAo7div)

<img src="Images/LG024.png" width = "50%" />

---

<SPAN ID = 'LG030'/>编号：LG030  
版本：Canary 25905 - 26058  
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
版本：Canary 26016 - 26058  
**问题**：**“阿凡达：潘多拉边境” (Avatar Frontiers of Pandora) 游戏崩溃**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAoa2ag](https://aka.ms/AAoa2ag)

---

<SPAN ID = 'LG034'/>编号：LG034  
版本：Canary 26016 - 26058  
**问题**：**Grand Theft Auto V (GTA 5) 游戏无法运行**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAo9e71](https://aka.ms/AAo9e71)

---

<SPAN ID = 'LG037'/>编号：LG037  
版本：Canary 25997 - 26058  
**问题**：**显示 WDAG (Edge) - Container: Error: 0x80004005 错误**。  
状态：<img src="Images/W.png" width = "10%" />  
Microsoft 官方回复：“我们正在努力修复此问题。” *(Ling 译)* <img src="Images/M.png" width = "15%" />  
典型反馈：[aka.ms/AAnzef8](https://aka.ms/AAnzef8)

---

<SPAN ID = 'LG040'/>编号：LG040  
版本：未知 - Canary 26058  
**问题**：**文件资源管理器 “登录时还原上一个文件夹窗口” 选项失效**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAoawwk](https://aka.ms/AAoawwk)

<img src="Images/LG040.png" width = "30%" />

---

<SPAN ID = 'LG046'/>编号：LG046  
版本：Canary 26020 - 26058  
**问题**：**远程桌面显示 0x3 错误 / 0x11 扩展错误**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAnyjyk](https://aka.ms/AAnyjyk)

---

<SPAN ID = 'LG049'/>编号：LG049  
版本：Canary 26020 - 26058  
**问题**：**事件查看器显示 DeviceSetupManager 元数据错误 (事件 131)**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAoipfs](https://aka.ms/AAoipfs)

---

<SPAN ID = 'LG055'/>编号：LG055  
版本：Canary 26040 - 26058  
**问题**：**隐藏 “购物” 等小组件后其再次出现**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAotzrh](https://aka.ms/AAotzrh)

<img src="Images/LG055.png" width = "35%" />

---

<SPAN ID = 'LG057'/>编号：LG057  
版本：Canary 26040 - 26058  
**问题**：**战眼 (BattlEye) 反作弊系统不兼容**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAox7us](https://aka.ms/AAox7us)

---

<SPAN ID = 'LG058'/>编号：LG058  
版本：Canary 26040 - 26058  
**问题**：**在 Microsoft Store 更新 “快速助手” 应用时显示 0x80073CFB 错误**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAov9fo](https://aka.ms/AAov9fo)

---

<SPAN ID = 'LG059'/>编号：LG059  
版本：Canary 26040 - 26058  
**问题**：**罗布乐思 (Roblox) 无法正常运行**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAovw5h](https://aka.ms/AAovw5h)

---

<SPAN ID = 'LG060'/>编号：LG060  
版本：Canary 26040 - 26058  
**问题**：**堡垒之夜 (Fortnite) 游戏无法正常运行**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAow3xj](https://aka.ms/AAow3xj)

---

<SPAN ID = 'LG061'/>编号：LG061  
版本：Canary 26040 - 26058  
**问题**：**EA 反作弊系统不兼容**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAox7vk](https://aka.ms/AAox7vk)

---

<SPAN ID = 'LG062'/>编号：LG062  
版本：Canary 26040 - 26058  
**问题**：**彩虹六号：围攻 (Rainbow Six Siege) 游戏无法正常运行**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAow3xx](https://aka.ms/AAow3xx)

---

<SPAN ID = 'LG063'/>编号：LG063  
版本：Canary 26040 - 26058  
**问题**：**绝地求生 (PUBG) 游戏无法正常运行**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAn5erb](https://aka.ms/AAn5erb)

---

<SPAN ID = 'LG064'/>编号：LG064  
版本：Canary 26040 - 26058  
**问题**：**全新安装 Windows 11 时，系统生成 Windows.old 空文件夹**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAovgrv](https://aka.ms/AAovgrv)

---

<SPAN ID = 'LG065'/>编号：LG065  
版本：Canary 26040 - 26058  
**问题**：**使用浏览器观看视频时屏幕可能冻结**。  
状态：<img src="Images/W.png" width = "10%" />  
典型反馈：[aka.ms/AAoxr0y](https://aka.ms/AAoxr0y)

---

<SPAN ID = 'LG077'/>编号：LG077  
版本：ALL  
**问题**：**启用 “管理移动设备” 时，“手机连接” 应用断线**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAp2105](https://aka.ms/AAp2105)

---

<SPAN ID = 'LG078'/>编号：LG078  
版本：Canary 26052 - 26058  
**问题**：**电脑无法播放音频**。  
状态：<img src="Images/L.png" width = "10%" />  
Microsoft 官方回复：“如果您受到此问题影响，请尽可能地提交反馈，捕获 ‘尝试播放音频但没有声音’ 的跟踪信息。请向 ‘设备和驱动程序’ - ‘音频和声音’ 类别提交。” *(Ling 译)* <img src="Images/M.png" width = "15%" />  
典型反馈：[aka.ms/AAp2b8r](https://aka.ms/AAp2b8r)

---

<SPAN ID = 'LG079'/>编号：LG079  
版本：Canary 26040 - 26058  
**问题**：**无法使用 Office，显示 0x426-0x0 错误**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAp3qas](https://aka.ms/AAp3qas)

---

<SPAN ID = 'LG080'/>编号：LG080  
版本：Canary 26052 - 26058  
**问题**：**Visio 应用崩溃**。  
状态：<img src="Images/W.png" width = "10%" />  
Microsoft 官方回复：“我们已经找出问题所在，正在修复中。” *(Ling 译)* <img src="Images/M.png" width = "15%" />  
典型反馈：[aka.ms/AAp5m7i](https://aka.ms/AAp5m7i)

---

<SPAN ID = 'LG081'/>编号：LG081  
版本：ALL  
**问题**：**无法登录 Microsoft Sudoku 游戏**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAp536h](https://aka.ms/AAp536h)

---

<SPAN ID = 'LG082'/>编号：LG082  
版本：Canary 26058  
**问题**：**文件资源管理器右键菜单中的图标显示在错误的位置**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAp536r](https://aka.ms/AAp536r)

---

<SPAN ID = 'LG083'/>编号：LG083  
版本：Canary 26058  
**问题**：**光标阴影 / 形状异常**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAp4zrc](https://aka.ms/AAp4zrc)

---

<SPAN ID = 'LG084'/>编号：LG084  
版本：Canary 26058  
**问题**：**光标随机消失 / 卡住**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAp4op2](https://aka.ms/AAp4op2)

---

<SPAN ID = 'LG085'/>编号：LG085  
版本：Canary 26052 - 26058  
**问题**：**战地风云 2042 (Battlefield 2042) 游戏崩溃**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAp40f1](https://aka.ms/AAp40f1)

---

<SPAN ID = 'LG086'/>编号：LG086  
版本：Canary 26052 - 26058  
**问题**：**逃离塔科夫 (Escape from Tarkov) 游戏无法启动**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAp6nv5](https://aka.ms/AAp6nv5)

---

<SPAN ID = 'LG087'/>编号：LG087  
版本：Canary 26040 - 26058  
**问题**：**新版 Microsoft Teams 应用崩溃**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAp5inl](https://aka.ms/AAp5inl)

---

<SPAN ID = 'LG088'/>编号：LG088  
版本：ALL  
**问题**：**无法使用截图工具对开始菜单 / 右键菜单进行截图**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAp5evo](https://aka.ms/AAp5evo)

---

<SPAN ID = 'LG089'/>编号：LG089  
版本：Canary 26052 - 26058  
**问题**：**Steam 平台窗口可能无法打开**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAp5wml](https://aka.ms/AAp5wml)

---

<SPAN ID = 'LG090'/>编号：LG090  
版本：Canary 26058  
**问题**：**百战天虫：大杀器 (Worms W.M.D) 游戏无法启动**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAp5p23](https://aka.ms/AAp5p23)

---

<SPAN ID = 'LG091'/>编号：LG091  
版本：Canary 26052 - 26058  
**问题**：**生化危机4：重制版 (Resident Evil 4 Remake) 游戏无法启动**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAp6bv6](https://aka.ms/AAp6bv6)

---

<SPAN ID = 'LG092'/>编号：LG092  
版本：Canary 26058  
**问题**：**命运 2 (Destiny 2) 游戏无法启动**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAp5wnk](https://aka.ms/AAp5wnk)

---

<SPAN ID = 'LG093'/>编号：LG093  
版本：Canary 26058  
**问题**：**放大镜无法跟随鼠标移动**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAp5woq](https://aka.ms/AAp5woq)

---

<SPAN ID = 'LG094'/>编号：LG094  
版本：Canary 26052 - 26058  
**问题**：**相机和 Studio Effects 可能无法正常工作**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAp3q1v](https://aka.ms/AAp3q1v)

---

<SPAN ID = 'LG095'/>编号：LG095  
版本：ALL  
**问题**：**通过 Microsoft Store / Xbox 下载盗贼之海 (Sea of Thieves) 游戏时显示 0x87E0000D 错误**。  
状态：<img src="Images/W.png" width = "10%" />  
Microsoft 官方回复：“感谢反馈，请查看下方的图片。” *(Ling 译)* <img src="Images/M.png" width = "15%" />  
典型反馈：[aka.ms/AAp7hon](https://aka.ms/AAp7hon)

<img src="Images/LG095.png" width = "40%" />

---

<SPAN ID = 'LG097'/>编号：LG097  
版本：Canary 26040 - 26058  
**问题**：**最终决战 (THE FINALS) 游戏无法启动**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAp2lrp](https://aka.ms/AAp2lrp)

---

<SPAN ID = 'LG098'/>编号：LG098  
版本：Canary 26058  
**问题**：**战地 5 (Battlefield Ⅴ) 游戏无法启动**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAp81aj](https://aka.ms/AAp81aj)

---

<SPAN ID = 'LG099'/>编号：LG099  
版本：Canary 26058  
**问题**：**赛博朋克 2077 (Cyberpunk 2077) 游戏无法启动**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAp81aj](https://aka.ms/AAp81aj)

---

<SPAN ID = 'LG100'/>编号：LG100  
版本：Canary 26058  
**问题**：**守望先锋：归来 (OVERWATCH2) 游戏无法启动**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAp8ed6](https://aka.ms/AAp8ed6)

---

<SPAN ID = 'LG101'/>编号：LG101  
版本：Canary 26058  
**问题**：**EA SPORTS FC 24 游戏崩溃**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAp8kid](https://aka.ms/AAp8kid)

---

[**希望分享线索？联系 Ling Gao**](https://forms.office.com/Pages/ResponsePage.aspx?id=DQSIkWdsW0yxEjajBLZtrQAAAAAAAAAAAAO__Q3sH7RUNjUyUzJLN0JBREZGMzBBVlpVOEVBQkRENy4u)

<SPAN ID = '2'/>

## ✦ Canary - 归档 (已做出更改) ✦

&emsp;&emsp;记录 Microsoft 已做出更改 0 - 28 天的问题 & 超过 30 日无新增赞成票的问题。

&emsp;&emsp;无特殊情况，问题归档后不再更新。

---

<SPAN ID = 'LG056'/>编号：LG056  
版本：Canary 26040 - 26052  
**问题**：**显示器黑屏 / 电脑无法从睡眠中唤醒**。  
状态：Canary 26058 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
Microsoft 官方回复：“如果您遇到了这种情况，请尝试按下键盘快捷键 WIN + CTRL + Shift + B，看看能否解决问题。” *(Ling 译)* <img src="Images/M.png" width = "15%" />  
典型反馈：[aka.ms/AAovgp0](https://aka.ms/AAovgp0)

---

<SPAN ID = 'LG054'/>编号：LG054  
版本：Canary 26040 - 26052  
**问题**：**Microsoft Store 中的部分视频流媒体应用可能无法正常播放**。  
状态：Canary 26058 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
Microsoft 官方回复：“请暂时使用浏览器播放视频，作为一种变通方案。” *(Ling 译)* <img src="Images/M.png" width = "15%" />

---

<SPAN ID = 'LG075'/>编号：LG075  
版本：Canary 26052  
**问题**：**“设置”>“系统”>“可选功能” 页面中所有功能均为 0 字节**。  
状态：Canary 26058 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAp5tnp](https://aka.ms/AAp5tnp)

---

<SPAN ID = 'LG022'/>编号：LG022  
版本：Canary 25997 - 26052  
**问题**：**Windows Sandbox 显示 0x80072746 / 0x800736b3 错误**。  
状态：Canary 26058 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAo6y4i](https://aka.ms/AAo6y4i)

---

<SPAN ID = 'LG076'/>编号：LG076  
版本：Canary 26052  
**问题**：**“设置”>“Windows 更新” 页面的 “上次检查时间” 存在错误**。  
状态：Canary 26058 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓

---

<SPAN ID = 'LG028'/>编号：LG028  
版本：未知 - Canary 26052  
**问题**：**文件资源管理器地址栏中图标和箭头间有一个缝隙，可能导致不小心切换为编辑模式**。  
状态：Canary 26058 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAo7kib](https://aka.ms/AAo7kib)

<img src="Images/LG028.png" width = "50%" />

---

<SPAN ID = 'LG045'/>编号：LG045  
版本：ALL  
**问题**：**共享窗口崩溃**。  
状态：ALL - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAohsni](https://aka.ms/AAohsni)

---

<SPAN ID = 'LG096'/>编号：LG096  
版本：Canary 26052  
**问题**：**安装 KB5035384 (26052.1100) 更新时显示 0x800f0904 错误**。  
状态：Canary 26058 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAp7pch](https://aka.ms/AAp7pch)

---

[Microsoft 已做出更改 >28 天的问题](28+.md)

[**希望分享线索？联系 Ling Gao**](https://forms.office.com/Pages/ResponsePage.aspx?id=DQSIkWdsW0yxEjajBLZtrQAAAAAAAAAAAAO__Q3sH7RUNjUyUzJLN0JBREZGMzBBVlpVOEVBQkRENy4u)

---

[回到顶部](#HEAD)

<img src="https://mirrors.creativecommons.org/presskit/icons/cc.xlarge.png" width = "3%" /> <img src="https://mirrors.creativecommons.org/presskit/icons/by.xlarge.png" width = "3%" /> <img src="https://mirrors.creativecommons.org/presskit/icons/sa.xlarge.png" width = "3%" />

在 “[署名 - 相同方式共享 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode.zh-Hans)” 协议 (CC BY-SA 4.0) 之条款下提供。

2023 - 2024, 高楷修 (Ling Gao), 灵糕中心 (Linggao Hub), [github.com/Lingggao/LGHUB](https://github.com/Lingggao/LGHUB)

[字体许可使用授权书](Images/字体许可使用授权书.png) | [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FLingggao%2FLGHUB&count_bg=%23737373&title_bg=%230078D7&icon=microsoft.svg&icon_color=%23FFFFFF&title=LGHUB&edge_flat=false)](https://hits.seeyoufarm.com) (访问次数统计：今日 / 累计)