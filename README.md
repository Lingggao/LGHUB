<SPAN ID = 'HEAD'/>

<div align="center">
<img src="Images/LING_1.png" width = "25%" /> <img src="Images/MCC2024.png" width = "12%" />
</div>


<h1 align="center">灵糕中心 (Linggao Hub)</h1>

[github.com/Lingggao/LGHUB](https://github.com/Lingggao/LGHUB) (GitHub) & [lingggao.github.io/LGHUB](https://lingggao.github.io/LGHUB) (Pages)

&emsp;&emsp;用于跟踪 “**Windows 11 预览体验版本 (Canary 频道) 哪些反馈正在由 Microsoft 调查 / 处理 / 已做出更改**” 的信息枢纽。由 2021 Windows Insider Most Valuable Professional (MVP) · **Ling Gao** 先生管理。

&emsp;&emsp;灵糕中心成立于 2023 年 12 月 12 日，其前身可追溯至 2019 年 5 月 14 日由 Microsoft 社区创建的 “[\[BUG 汇总\] Windows 10 2019 年 5 月更新 (1903_18362) 已知问题与处理进度汇总](https://answers.microsoft.com/zh-hans/insider/forum/all/bug-%E6%B1%87%E6%80%BBwindows-10-2019-%E5%B9%B4-5/252d0d6a-022c-4bf7-9976-55b57590aee2)” 讨论话题。

> &emsp;**声明**：灵糕中心为个人项目，管理者不是 Microsoft 公司员工，不能代表 Microsoft 公司立场、态度。中心无意且无法代替 “反馈中心” (Feedback Hub) 应用的重要作用。中心不提供 Microsoft 产品技术支持服务。中心不接受有关 Windows 11 预览体验版本的反馈，用户应始终通过 “反馈中心” 应用提交。

> &emsp;Windows、Windows Insider Program 等是 Microsoft 公司的商标。

&emsp;&emsp;**宗旨**：独立管理、服务用户、信息精准、更新及时

[反馈中心](https://aka.ms/fbh) | [深入了解反馈](https://learn.microsoft.com/zh-cn/windows-insider/feedback) | [Flight Hub](https://learn.microsoft.com/en-us/windows-insider/flight-hub) | Windows 预览体验计划 - [网站](https://www.microsoft.com/zh-cn/windowsinsider) · [博客](https://blogs.windows.com/windows-insider) · [X (Twitter)](https://twitter.com/windowsinsider) · [社区](https://answers.microsoft.com/zh-hans/insider/forum)

## ✦ 总览 ✦

&emsp;&emsp;上次更新时间：2024 年 3 月 30 日 18:00 (UTC+8)。访问次数：2480+

&emsp;&emsp;收录反馈 138 个，其中正在调查 15 个 (含搁置 3 个)、正在处理 4 个、已修复 119 个。

&emsp;&emsp;反馈更新记录：**今日更新 LG136 - 137**。- Ling ☀️ [总览图](https://raw.githubusercontent.com/Lingggao/LGHUB/main/Images/Linggao%20Hub.png) | [反馈更新记录](Documents/Update_Feedback.md) | [平台更新记录](Documents/Update_Platform.md)

|      频道       |      最新版本       | 时间 (UTC+8) |                             公告                             |
| :-------------: | :-----------------: | :----------: | :----------------------------------------------------------: |
|  Canary & Dev   |   **[新]** 26090    |  2024/3/29   | [aka.ms/wip26090](https://blogs.windows.com/windows-insider/2024/03/28/announcing-windows-11-insider-preview-build-26090-canary-and-dev-channels) |
|      Beta       | **[新]** 22635.3420 |  2024/3/30   | [aka.ms/wip-beta-3-29](https://blogs.windows.com/windows-insider/2024/03/29/announcing-windows-11-insider-preview-build-22635-3420-beta-channel) |
| Release Preview |   226(3/2)1.3371    |  2024/3/22   | [blogs.windows.com](https://blogs.windows.com/windows-insider/2024/03/21/releasing-windows-11-builds-22621-3371-and-22631-3371-to-the-release-preview-channel) |

<img src="Images/Graph_1.png" width = "88%" />

|      编号       |                             问题                             |   状态   |
| :-------------: | :----------------------------------------------------------: | :------: |
| [LG123](#LG123) |                 接收不到 Build 26080+ 更新。                 | 正在处理 |
| [LG116](#LG116) |                  电脑无法正常关机 / 睡眠。                   | 正在处理 |
|     **——**      | [**Canary - 公告已知问题**](#0) **▲ \| ▼** [**Canary - 用户反馈问题**](#1) |  **——**  |
| [LG111](#LG111) |  **[合并]** 任务视图 / 文件资源管理器卡顿或 CPU 占用率高。   | 正在处理 |
| [LGH01](#LGH01) | **[集合]** 仍有一些游戏在 Build 26080+ 中无法正常运行。(含列表) | 正在处理 |
| [LG122](#LG122) |                      Copilot 功能消失。                      | 正在调查 |
| [LG126](#LG126) |                Surface 设备的摄像头可能失效。                | 正在调查 |
| [LG127](#LG127) |                  在手写板上写字时文字错位。                  | 正在调查 |
| [LG128](#LG128) |              SteelSeries 耳机软件无法正常使用。              | 正在调查 |
| [LG129](#LG129) | 在 Microsoft Store 和 Windows 更新页面下载时显示 0x80240067 错误。 | 正在调查 |
| [LG130](#LG130) |        更新 Windows 后，已禁用的音频设备被自动启用。         | 正在调查 |
| [LG132](#LG132) |               部分第三方壁纸软件无法正常运行。               | 正在调查 |
| [LG133](#LG133) |            鼠标在锁屏界面无法显示为设定的主题色。            | 正在调查 |
| [LG134](#LG134) |            重启电脑后，已下载的语言包被自动删除。            | 正在调查 |
| [LG135](#LG135) |               鼠标和键盘无法在安全模式中使用。               | 正在调查 |
| [LG136](#LG136) |              **Visual Studio 2022 IDE 崩溃**。               | 正在调查 |
| [LG137](#LG137) |                  **添加小组件时窗口冻结**。                  | 正在调查 |
|     **——**      | [**Canary - 用户反馈问题**](#1) **▲ \| ▼** [**Canary - 归档 (已做出更改 0 - 28 天)**](#2) |  **——**  |
| [LG115](#LG115) |                右键菜单变为 Windows 10 样式。                | 已修复 ✓ |
| [LG069](#LG069) |    安装 Canary 版本时可能自动回退，错误代码 0xC1900101。     | 已修复 ✓ |
| [LG125](#LG125) |         电脑风扇负荷更重 / 温度更高 / 电池续航更短。         | 已修复 ✓ |
| [LG131](#LG131) |                     播放视频时鼠标卡顿。                     | 已修复 ✓ |
| [LG117](#LG117) |                任务栏应用缩略图无法正常显示。                | 已修复 ✓ |
|     **——**      | **✦** [**Canary - 归档 (已做出更改 >28 天)**](28+.md) **✦ \| ✦** [**Canary - 搁置 (未做出更改)**](#3) **✦** |  **——**  |

[**希望分享线索？联系 Ling。**](https://forms.office.com/Pages/ResponsePage.aspx?id=DQSIkWdsW0yxEjajBLZtrQAAAAAAAAAAAAO__Q3sH7RUNjUyUzJLN0JBREZGMzBBVlpVOEVBQkRENy4u) | [**反馈平台问题？联系 Ling。**](https://forms.office.com/Pages/ResponsePage.aspx?id=DQSIkWdsW0yxEjajBLZtrQAAAAAAAAAAAAO__Q3sH7RUQ0haOElMVkxOWDE4U1pHQUZWMDhEM1gwSC4u)

<SPAN ID = '0'/>

## ✦ Canary - 公告已知问题 ✦

&emsp;&emsp;记录 [Windows Insider 博客](https://blogs.windows.com/windows-insider)中明确公开的已知问题。

---

<SPAN ID = 'LG123'/>编号：LG123  
版本：ALL  
**问题**：**接收不到 Build 26080+ 更新**。  
状态：<img src="Images/W.png" width = "9%" />  
Microsoft 官方回复：“我们正在调查有关部分 Insider 卡在 26040 / 23620 版本的反馈。如果您迫切期望立即回到正轨，可使用最新 ISO 全新安装 Windows，然后重新加入 Canary 或 Dev 频道。” *(Ling 译)*  
<img src="Images/M.png" width = "14%" />  
典型反馈：[aka.ms/AApjbci](https://aka.ms/AApjbci)

---

<SPAN ID = 'LG116'/>编号：LG116  
版本：Canary 26080 - 26090  
**问题**：**电脑无法正常关机 / 睡眠**。  
状态：<img src="Images/W.png" width = "9%" />  
Microsoft 官方回复：“不幸的是，我们看到一些反馈称 Build 26085+ 版本中仍然存在这一问题。我们正在努力修复，请暂时使用 shutdown -t 0 -s 命令关机。” *(Ling 译)* <img src="Images/M.png" width = "14%" />  
典型反馈：[aka.ms/AApjd80](https://aka.ms/AApjd80)

<SPAN ID = '1'/>

## ✦ Canary - 用户反馈问题 ✦

&emsp;&emsp;记录[反馈中心应用](https://aka.ms/fbh)中 Microsoft 明确响应的问题。

---

<SPAN ID = 'LG111'/>编号：LG111  
版本：Canary 26063 - 26090  
**问题**：**任务视图 / 文件资源管理器卡顿或 CPU 占用率高**。  
状态：<img src="Images/W.png" width = "9%" />  
典型反馈：[aka.ms/AAph34g](https://aka.ms/AAph34g)

---

<SPAN ID = 'LGH01'/>编号：LGH01  
版本：Canary 26080 - 26090  
**集合**：**仍有一些游戏在 Build 26080+ 中无法正常运行**。  
状态：<img src="Images/W.png" width = "9%" />  
Microsoft 官方回复：“大多数游戏应当可以在 Build 26080 中恢复正常运行。如果您在预览体验版本中玩游戏时发现任何问题，请务必在反馈中心提交。” *(Ling 译)* <img src="Images/M.png" width = "14%" />

列表 (排名不分先后)

- Grand Theft Auto V (GTA 5) - [aka.ms/AApjkjp](https://aka.ms/AApjkjp)
- PUBG (绝地求生) - [aka.ms/AApjd7p](https://aka.ms/AApjd7p)
- Battlefield 2042 (战地风云 2042) - [aka.ms/AApjkk7](https://aka.ms/AApjkk7)
- EVE Online (星战前夜) - [aka.ms/AApjz1t](https://aka.ms/AApjz1t)
- Avatar Frontiers of Pandora (阿凡达：潘多拉边境) - [aka.ms/AApmqnc](https://aka.ms/AApmqnc)
- Assassin's Creed Origins (刺客信条：起源) - [aka.ms/AApmqnc](https://aka.ms/AApmqnc)
- Electronic Arts (EA) 旗下游戏 - [aka.ms/AApsxln](https://aka.ms/AApsxln)
- It Takes Two (双人成行) - [aka.ms/AApqr1c](https://aka.ms/AApqr1c)
- Watch Dogs: Legion (看门狗：军团) - [aka.ms/AApr6d6](https://aka.ms/AApr6d6)
- FARCRY 6/5 (孤岛惊魂 6/5) - [aka.ms/AApr6d6](https://aka.ms/AApr6d6)

---

<SPAN ID = 'LG122'/>编号：LG122  
版本：Canary 26080 - 26090  
**问题**：**Copilot 功能消失**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AApmcet](https://aka.ms/AApmcet)

---

<SPAN ID = 'LG126'/>编号：LG126  
版本：Canary 26085 - 26090  
**问题**：**Surface 设备的摄像头可能失效**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AApno2g](https://aka.ms/AApno2g)

---

<SPAN ID = 'LG127'/>编号：LG127  
版本：Canary 26085 - 26090  
**问题**：**在手写板上写字时文字错位**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AApnq5x](https://aka.ms/AApnq5x)

---

<SPAN ID = 'LG128'/>编号：LG128  
版本：Canary 26085 - 26090  
**问题**：**SteelSeries 耳机软件无法正常使用**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AApoga9](https://aka.ms/AApoga9)

---

<SPAN ID = 'LG129'/>编号：LG129  
版本：Canary 26085 - 26090  
**问题**：**在 Microsoft Store 和 Windows 更新页面下载时显示 0x80240067 错误**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AApqooc](https://aka.ms/AApqooc)

---

<SPAN ID = 'LG130'/>编号：LG130  
版本：Canary 26085 - 26090  
**问题**：**更新 Windows 后，已禁用的音频设备被自动启用**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AApsxmc](https://aka.ms/AApsxmc)

---

<SPAN ID = 'LG132'/>编号：LG132  
版本：Canary 26085 - 26090  
**问题**：**部分第三方壁纸软件无法正常运行**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AApsqd8](https://aka.ms/AApsqd8)

---

<SPAN ID = 'LG133'/>编号：LG133  
版本：Canary 26085 - 26090  
**问题**：**鼠标在锁屏界面无法显示为设定的主题色**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAps4ch](https://aka.ms/AAps4ch)

---

<SPAN ID = 'LG134'/>编号：LG134  
版本：Canary 26085 - 26090  
**问题**：**重启电脑后，已下载的语言包被自动删除**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AApr6d2](https://aka.ms/AApr6d2)

---

<SPAN ID = 'LG135'/>编号：LG135  
版本：Canary 26085 - 26090  
**问题**：**鼠标和键盘无法在安全模式中使用**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AApqyoc](https://aka.ms/AApqyoc)

---

<SPAN ID = 'LG136'/>编号：LG136  
版本：Canary 26090  
**问题**：**Visual Studio 2022 IDE 崩溃**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AApthgp](https://aka.ms/AApthgp)

---

<SPAN ID = 'LG137'/>编号：LG137  
版本：Canary 26090  
**问题**：**添加小组件时窗口冻结**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AApuv37](https://aka.ms/AApuv37)

<SPAN ID = '2'/>

## ✦ Canary - 归档 (已做出更改) ✦

&emsp;&emsp;记录 Microsoft 已做出更改 0 - 28 天的问题 & 超过 30 日无新增赞成票的问题。

&emsp;&emsp;无特殊情况，问题归档后不再更新。

---

<SPAN ID = 'LG115'/>编号：LG115  
版本：Canary 26080 - 26085  
**问题**：**右键菜单变为 Windows 10 样式**。  
状态：Canary 26090 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AApjkju](https://aka.ms/AApjkju) <img src="Images/M.png" width = "14%" />

---

<SPAN ID = 'LG069'/>编号：LG069  
版本：Canary 26058 - 26085  
**问题**：**安装 Canary 版本时可能自动回退，错误代码 0xC1900101**。  
状态：Canary 26090 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
Microsoft 官方回复：“我们做了很多更改以帮助缓解回退现象，并将继续调查用户反馈。” *(Ling 译)*  
 <img src="Images/M.png" width = "14%" />

---

<SPAN ID = 'LG125'/>编号：LG125  
版本：Canary 26080 - 26085  
**问题**：**电脑风扇负荷更重 / 温度更高 / 电池续航更短**。  
状态：Canary 26090 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AApmnl6](https://aka.ms/AApmnl6)

---

<SPAN ID = 'LG131'/>编号：LG131  
版本：Canary 26085  
**问题**：**播放视频时鼠标卡顿**。  
状态：Canary 26090 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AApqopo](https://aka.ms/AApqopo)

---

<SPAN ID = 'LG117'/>编号：LG117  
版本：Canary 26080 - 26085  
**问题**：**任务栏应用缩略图无法正常显示**。  
状态：Canary 26090 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AApjd83](https://aka.ms/AApjd83)

[Microsoft 已做出更改 >28 天的问题](28+.md)

<SPAN ID = '3'/>

## ✦ Canary - 搁置 (未做出更改) ✦

&emsp;&emsp;“并非所有软件缺陷都要修复。” —— Ron Patton (出自《软件测试》)

&emsp;&emsp;已收录的反馈也可能因缺少资源、修复风险过大、商业决策调整等长期或永久不予修复。本板块记录 Microsoft 超过 90 天未修复的问题，中心将每间隔 30 天在 Canary 频道最新版本中进行测试。

[Microsoft 超过 90 天未修复的问题](90+.md)

---

[回到顶部](#HEAD)

<img src="https://mirrors.creativecommons.org/presskit/icons/cc.xlarge.png" width = "3%" /> <img src="https://mirrors.creativecommons.org/presskit/icons/by.xlarge.png" width = "3%" /> <img src="https://mirrors.creativecommons.org/presskit/icons/sa.xlarge.png" width = "3%" />

在 “[署名 - 相同方式共享 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode.zh-Hans)” 协议 (CC BY-SA 4.0) 之条款下提供。

2023 - 2024, 高楷修 (Ling Gao), 灵糕中心 (Linggao Hub), [github.com/Lingggao/LGHUB](https://github.com/Lingggao/LGHUB)

[字体许可使用授权书](Images/字体许可使用授权书.png) | [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FLingggao%2FLGHUB&count_bg=%23737373&title_bg=%230078D7&icon=microsoft.svg&icon_color=%23FFFFFF&title=LGHUB&edge_flat=false)](https://hits.seeyoufarm.com) (访问次数统计：今日 / 累计)