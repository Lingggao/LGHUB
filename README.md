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

[反馈中心](https://aka.ms/fbh) | [深入了解反馈](https://learn.microsoft.com/zh-cn/windows-insider/feedback) | [Flight Hub](https://learn.microsoft.com/en-us/windows-insider/flight-hub) | Windows 预览体验计划 - [网站](https://www.microsoft.com/zh-cn/windowsinsider) · [博客](https://blogs.windows.com/windows-insider) · [X (Twitter)](https://twitter.com/windowsinsider) · 社区 ([中](https://answers.microsoft.com/zh-hans/insider/forum) / [英](https://answers.microsoft.com/en-us/insider/forum))

## ✦ 总览 ✦

&emsp;&emsp;上次更新时间：2024 年 5 月 9 日 8:00 (UTC+8)。访问次数：3700+

&emsp;&emsp;收录反馈 170 个，其中正在调查 8 个 (含[搁置](#3) 5 个)、正在处理 5 个、已修复 157 个。

&emsp;&emsp;反馈更新记录：**今日更新反馈状态**。- Ling 💕 [总览图](https://raw.githubusercontent.com/Lingggao/LGHUB/main/Images/Linggao%20Hub.png) | [反馈更新记录](Documents/Update_Feedback.md) | [平台更新记录](Documents/Update_Platform.md)

|      频道       |    最新版本    | 时间 (UTC+8) |                             公告                             |
| :-------------: | :------------: | :----------: | :----------------------------------------------------------: |
|     Canary      | **[新]** 26212 |   2024/5/9   | [aka.ms/wip26212](https://blogs.windows.com/windows-insider/2024/05/08/announcing-windows-11-insider-preview-build-26212-canary-channel) |
|       Dev       |   26120.461    |   2024/5/4   | [aka.ms/wip-dev-5-3](https://blogs.windows.com/windows-insider/2024/05/03/announcing-windows-11-insider-preview-build-26120-461-dev-channel) |
|      Beta       |   22635.3570   |   2024/5/4   | [aka.ms/wip-beta-5-3](https://blogs.windows.com/windows-insider/2024/05/03/announcing-windows-11-insider-preview-build-22635-3570-beta-channel) |
| Release Preview | 226(3/2)1.3520 |  2024/4/12   | [blogs.windows.com](https://blogs.windows.com/windows-insider/2024/04/11/releasing-windows-11-builds-22621-3520-and-22631-3520-to-the-release-preview-channel) |

<img src="Images/Graph_1.png" width = "88%" />

---

&emsp;&emsp;**提醒**：多数问题是仅有 1 - 2 位 Insiders 反馈的 “偶发性” 问题，而非所有人都会遇到的 “广泛性” 问题。请放心地更新 Windows 11 预览体验版本，不必担心新版使用体验过差。

|      编号       |                             问题                             |   状态   |
| :-------------: | :----------------------------------------------------------: | :------: |
| [LG123](#LG123) |                 接收不到 Build 26080+ 更新。                 | 正在处理 |
|     **——**      | [**Canary - 公告已知问题**](#0) **▲ \| ▼** [**Canary - 用户反馈问题**](#1) |  **——**  |
| [LG111](#LG111) |                任务视图卡顿或 CPU 占用率高。                 | 正在处理 |
| [LGH02](#LGH02) |       **[集合]** 文件资源管理器中的软件缺陷。(含列表)        | 正在处理 |
| [LG148](#LG148) |            无法调整启动 “照片” 应用时窗口的大小。            | 正在调查 |
| [LG158](#LG158) |                  电脑卡顿 / CPU 性能下降。                   | 正在调查 |
| [LGH03](#LGH03) |           **[集合]** 小组件中的软件缺陷。(含列表)            | 正在处理 |
| [LG168](#LG168) | 将 “合并任务栏按钮并隐藏标签” 调整为 “从不” 时部分图标消失。 | 正在处理 |
| [LG169](#LG169) |            “照片” 应用在 HDR 显示模式中亮度异常。            | 正在调查 |
|     **——**      | [**Canary - 用户反馈问题**](#1) **▲ \| ▼** [**Canary - 归档 (已做出更改 0 - 7 天)**](#2) |  **——**  |
| [LGH01](#LGH01) | **[集合]** **仍有一些游戏在 Build 26080+ 中无法正常运行**。(含列表) | 已修复 ✓ |
| [LG139](#LG139) |   **以 “禁用驱动程序强制签名” 选项启动 Windows 时崩溃**。    | 已修复 ✓ |
| [LG144](#LG144) |          **无法使用 Visual Studio 调试应用程序**。           | 已修复 ✓ |
| [LG145](#LG145) |        **无法在 VMware Workstation 中开启 3D 加速**。        | 已修复 ✓ |
| [LG146](#LG146) |     **无法连接蓝牙耳机 / 连接蓝牙耳机后无法播放音频**。      | 已修复 ✓ |
| [LG147](#LG147) |       **Microsoft Family Safety 无法添加家庭组成员**。       | 已修复 ✓ |
| [LG150](#LG150) |               **无法使用 PIN 登录安全模式**。                | 已修复 ✓ |
| [LG153](#LG153) | **C:\Windows\Microsoft.NET\\... 配置解析器 0x80004005 错误**。 | 已修复 ✓ |
| [LG161](#LG161) |              **快速设置页面中的蓝牙功能丢失**。              | 已修复 ✓ |
| [LG163](#LG163) |      **无法更改 Windows 启动设置 (如进入安全模式等)**。      | 已修复 ✓ |
| [LG164](#LG164) |                    **电脑开机动画消失**。                    | 已修复 ✓ |
| [LG165](#LG165) |                    **无法安装可选功能**。                    | 已修复 ✓ |
| [LG166](#LG166) |        **在中文系统中，小组件的部分内容显示为英文**。        | 已修复 ✓ |
| [LG167](#LG167) |              **蓝屏 / 绿屏页面无法正确呈现**。               | 已修复 ✓ |
| [LG152](#LG152) |        **拖动音量合成器滑块时 “快速设置” 窗口崩溃**。        | 已修复 ✓ |
|     **——**      | **✦** [**Canary - 归档 (已做出更改 >7 天)**](7+.md) **✦ \| ✦** [**Canary - 搁置 (未做出更改)**](#3) **✦** |  **——**  |

[**分享反馈线索**](https://forms.office.com/Pages/ResponsePage.aspx?id=DQSIkWdsW0yxEjajBLZtrQAAAAAAAAAAAAO__Q3sH7RUNjUyUzJLN0JBREZGMzBBVlpVOEVBQkRENy4u) | [**反馈平台问题**](https://forms.office.com/Pages/ResponsePage.aspx?id=DQSIkWdsW0yxEjajBLZtrQAAAAAAAAAAAAO__Q3sH7RUQ0haOElMVkxOWDE4U1pHQUZWMDhEM1gwSC4u)

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

<SPAN ID = '1'/>

## ✦ Canary - 用户反馈问题 ✦

&emsp;&emsp;记录[反馈中心应用](https://aka.ms/fbh)中 Microsoft 明确响应的问题。

---

<SPAN ID = 'LG111'/>编号：LG111  
版本：Canary 26063 - 26212  
**问题**：**任务视图卡顿或 CPU 占用率高**。  
状态：<img src="Images/W.png" width = "9%" />  
典型反馈：[aka.ms/AAph34g](https://aka.ms/AAph34g)

---

<SPAN ID = 'LGH02'/>编号：LGH02  
日期：2024 年 4 月 7 日  
版本：Canary 26100 - 26212  
**集合**：**文件资源管理器中的软件缺陷**。  
状态：<img src="Images/W.png" width = "9%" />

列表

- 卡顿 / 严重卡顿
- 内存泄漏
- CPU 占用率高
- 切换 “项目复选框” 选项时出现异常 - [aka.ms/AApydtm](https://aka.ms/AApydtm)
- 缩放设定为 175% 时图标模糊不清 - [aka.ms/AApytl6](https://aka.ms/AApytl6)
- 菜单中的文本可能过长 - [aka.ms/AApyuo4](https://aka.ms/AApyuo4)
- 出现多个地址栏 / 搜索栏 - [aka.ms/AApymuw](https://aka.ms/AApymuw)
- 在深色模式添加新标签时窗口闪烁 - [aka.ms/AAq33qn](https://aka.ms/AAq33qn)
- 导航窗格中的 OneDrive 随机变化位置 - [aka.ms/AApxwbw](https://aka.ms/AApxwbw)
- 在搜索栏中输入的字符随机被删除 - [aka.ms/AAq9sqa](https://aka.ms/AAq9sqa)

---

<SPAN ID = 'LG148'/>编号：LG148  
日期：2024 年 4 月 10 日  
版本：ALL  
**问题**：**无法调整启动 “照片” 应用时窗口的大小**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AApztdn](https://aka.ms/AApztdn)

---

<SPAN ID = 'LG158'/>编号：LG158  
日期：2024 年 4 月 17 日  
版本：Canary 26100 - 26212  
**问题**：**电脑卡顿 / CPU 性能下降**。  
状态：<img src="Images/L.png" width = "9%" />  
Microsoft 官方回复：“我们将持续监控用户反馈和 Windows 错误报告，以保障 Windows 的可靠性。如果您发现性能异常，请立即提交反馈，让我们了解您遇到的问题。” *(Ling 译)* <img src="Images/M.png" width = "14%" />  
典型反馈：[aka.ms/AAq21jx](https://aka.ms/AAq21jx) & [aka.ms/AAq296v](https://aka.ms/AAq296v)

---

<SPAN ID = 'LGH03'/>编号：LGH03  
日期：2024 年 4 月 19 日  
版本：Canary 26100 - 26212  
**集合**：**小组件中的软件缺陷**。  
状态：<img src="Images/W.png" width = "9%" />

列表

- 点击小组件时 Windows 崩溃 / 显示错误 - [aka.ms/AAq43k9](https://aka.ms/AAq43k9)
- “待办事项” 等小组件随机消失 - [aka.ms/AAq1w40](https://aka.ms/AAq1w40)
- 已固定的小组件随机消失 - [aka.ms/AAq33qp](https://aka.ms/AAq33qp)
- “悬停时打开小组件板” 选项始终显示为关 - [aka.ms/AAq70ys](https://aka.ms/AAq70ys)
- 交互时系统崩溃 / 显示 Windows 错误 - [aka.ms/AAq43k9](https://aka.ms/AAq43k9)

---

<SPAN ID = 'LG168'/>编号：LG168  
日期：2024 年 5 月 4 日  
版本：Canary 26200 - 26212  
**问题**：**将 “合并任务栏按钮并隐藏标签” 调整为 “从不” 时部分图标消失**。  
状态：<img src="Images/W.png" width = "9%" />  
典型反馈：[aka.ms/AAq9sq4](https://aka.ms/AAq9sq4) <img src="Images/M.png" width = "14%" />

---

<SPAN ID = 'LG169'/>编号：LG169  
日期：2024 年 5 月 4 日  
版本：ALL  
**问题**：**“照片” 应用在 HDR 显示模式中亮度异常**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAq9sq8](https://aka.ms/AAq9sq8)

<SPAN ID = '2'/>

## ✦ Canary - 归档 (已做出更改) ✦

&emsp;&emsp;记录 Microsoft 已做出更改 0 - 7 天的问题 & 超过 14 天无新增赞成票的问题。

&emsp;&emsp;无特殊情况，问题归档后不再更新。

---

<SPAN ID = 'LGH01'/>编号：LGH01  
版本：Canary 26080 - 26200  
**集合**：**仍有一些游戏在 Build 26080+ 中无法正常运行**。  
状态：Canary 26212 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
Microsoft 官方回复：“大多数游戏应当可以在 Build 26080 中恢复正常运行。如果您在预览体验版本中玩游戏时发现任何问题，请务必在反馈中心提交。” *(Ling 译)* <img src="Images/M.png" width = "14%" />

列表

- Avatar Frontiers of Pandora (阿凡达：潘多拉边境) - [aka.ms/AApmqnc](https://aka.ms/AApmqnc) - 已修复 ✓
- Assassin's Creed Origins (刺客信条：起源) - [aka.ms/AApmqnc](https://aka.ms/AApmqnc) - 已修复 ✓
- Grand Theft Auto V (GTA 5) - [aka.ms/AApjkjp](https://aka.ms/AApjkjp) - 已修复 ✓
- Electronic Arts (EA) 旗下游戏 - [aka.ms/AApsxln](https://aka.ms/AApsxln) - 已修复 ✓
- Battlefield 2042 (战地风云 2042) - [aka.ms/AApjkk7](https://aka.ms/AApjkk7) - 已修复 ✓
- PUBG (绝地求生) - [aka.ms/AApjd7p](https://aka.ms/AApjd7p) - 已修复 ✓
- Watch Dogs: Legion (看门狗：军团) - [aka.ms/AApr6d6](https://aka.ms/AApr6d6) - 已修复 ✓
- FARCRY 6/5 (孤岛惊魂 6/5) - [aka.ms/AApr6d6](https://aka.ms/AApr6d6) - 已修复 ✓
- EVE Online (星战前夜) - [aka.ms/AApjz1t](https://aka.ms/AApjz1t) - 已修复 ✓
- It Takes Two (双人成行) - [aka.ms/AApqr1c](https://aka.ms/AApqr1c) - 已修复 ✓

---

<SPAN ID = 'LG139'/>编号：LG139  
日期：2024 年 4 月 2 日  
版本：Canary 26090 - 26200  
**问题**：**以 “禁用驱动程序强制签名” 选项启动 Windows 时崩溃**。  
状态：Canary 26212 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AApv3y2](https://aka.ms/AApv3y2)

---

<SPAN ID = 'LG144'/>编号：LG144  
日期：2024 年 4 月 7 日  
版本：Canary 26100 - 26200  
**问题**：**无法使用 Visual Studio 调试应用程序**。  
状态：Canary 26212 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AApyec1](https://aka.ms/AApyec1)

---

<SPAN ID = 'LG145'/>编号：LG145  
日期：2024 年 4 月 7 日  
版本：Canary 26100 - 26200  
**问题**：**无法在 VMware Workstation 中开启 3D 加速**。  
状态：Canary 26212 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AApyec1](https://aka.ms/AApyec1)

---

<SPAN ID = 'LG146'/>编号：LG146  
日期：2024 年 4 月 10 日  
版本：Canary 26100 - 26200  
**问题**：**无法连接蓝牙耳机 / 连接蓝牙耳机后无法播放音频**。  
状态：Canary 26212 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AApz29f](https://aka.ms/AApz29f) & [aka.ms/AApz29h](https://aka.ms/AApz29h)

---

<SPAN ID = 'LG147'/>编号：LG147  
日期：2024 年 4 月 10 日  
版本：ALL  
**问题**：**Microsoft Family Safety 无法添加家庭组成员**。  
状态：ALL - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AApzoge](https://aka.ms/AApzoge)

---

<SPAN ID = 'LG150'/>编号：LG150  
日期：2024 年 4 月 10 日  
版本：Canary 26100 - 26200  
**问题**：**无法使用 PIN 登录安全模式**。  
状态：Canary 26212 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AApyjss](https://aka.ms/AApyjss)

---

<SPAN ID = 'LG153'/>编号：LG153  
日期：2024 年 4 月 11 日  
版本：Canary 26100 - 26200  
**问题**：**C:\Windows\Microsoft.NET\\... 配置解析器 0x80004005 错误**。  
状态：Canary 26212 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
Microsoft 官方回复：“请参照下方的步骤分享更多日志信息。” *(Ling 译)* <img src="Images/M.png" width = "14%" />  
典型反馈：[aka.ms/AApy7yg](https://aka.ms/AApy7yg)

步骤

1. 转到 [aka.ms/vscollect](https://aka.ms/vscollect) 下载 collect.exe。
2. 此程序将创建 %TEMP%\vslogs.zip 压缩文件，包含所有 VS 和 .NET 日志。
3. 将 vslogs.zip 上传至反馈中心。
4. 将以下文件保存至 config.zip 压缩文件：
   - %windir%\Microsoft.NET\Framework\v4.0.30319\config\machine.config
   - %windir%\Microsoft.NET\Framework64\v4.0.30319\config\machine.config
   - %windir%\Microsoft.NET\Framework\v4.0.30319\config\web.config
   - %windir%\Microsoft.NET\Framework64\v4.0.30319\config\web.config
5. 将 config.zip 上传至反馈中心。
6. 请在评论中告诉我们：
   - 错误信息何时出现？
   - 错误信息与哪个应用有关？

---

<SPAN ID = 'LG161'/>编号：LG161  
日期：2024 年 4 月 19 日  
版本：Canary 26100 - 26200  
**问题**：**快速设置页面中的蓝牙功能丢失**。  
状态：Canary 26212 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAq26to](https://aka.ms/AAq26to) & [aka.ms/AAq3il1](https://aka.ms/AAq3il1)

---

<SPAN ID = 'LG163'/>编号：LG163  
日期：2024 年 4 月 24 日  
版本：Canary 26200  
**问题**：**无法更改 Windows 启动设置 (如进入安全模式等)**。  
状态：Canary 26212 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAq3xrr](https://aka.ms/AAq3xrr)

<img src="Images/LG162.jpg" width = "50%" />

---

<SPAN ID = 'LG164'/>编号：LG164  
日期：2024 年 4 月 24 日  
版本：Canary 26200  
**问题**：**电脑开机动画消失**。  
状态：Canary 26212 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAq4mav](https://aka.ms/AAq4mav)

---

<SPAN ID = 'LG165'/>编号：LG165  
日期：2024 年 4 月 24 日  
版本：Canary 26200  
**问题**：**无法安装可选功能**。  
状态：Canary 26212 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAq44f1](https://aka.ms/AAq44f1)

---

<SPAN ID = 'LG166'/>编号：LG166  
日期：2024 年 5 月 2 日  
版本：Canary 26200  
**问题**：**在中文系统中，小组件的部分内容显示为英文**。  
状态：Canary 26212 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAq8xz5](https://aka.ms/AAq8xz5)

---

<SPAN ID = 'LG167'/>编号：LG167  
日期：2024 年 5 月 2 日  
版本：Canary 26200  
**问题**：**蓝屏 / 绿屏页面无法正确呈现**。  
状态：Canary 26212 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAq8xy5](https://aka.ms/AAq8xy5)

---

<SPAN ID = 'LG152'/>编号：LG152  
日期：2024 年 4 月 11 日  
版本：Canary 26100 - 26200  
**问题**：**拖动音量合成器滑块时 “快速设置” 窗口崩溃**。  
状态：Canary 26212 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAq0phj](https://aka.ms/AAq0phj)

<img src="Images/LG152.png" width = "30%" />

[Microsoft 已做出更改 >7 天的问题](7+.md)

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