<SPAN ID = 'HEAD'/>

<div align="center">
<img src="Images/WCC2024_2.png" width = "12%" /> <img src="Images/LING_2.png" width = "25%" /> <img src="Images/WCC2024_1.png" width = "12%" />
</div>

<h1 align="center">灵糕中心 (Linggao Hub)</h1>

[github.com/Lingggao/LGHUB](https://github.com/Lingggao/LGHUB) (GitHub)

&emsp;&emsp;**用于跟踪 “Windows 11 预览体验版本 (Canary 频道) 中哪些反馈正在由 Microsoft 调查、处理 / 已做出更改” 的信息枢纽**。由 2021 Windows Insider 最有价值专家 (MVP) · [**Ling Gao**](https://github.com/Lingggao) 先生管理。

&emsp;&emsp;灵糕中心成立于 2023 年 12 月 12 日，其前身可追溯至 2019 年 5 月 14 日由 Microsoft 社区创建的 “[\[BUG 汇总\] Windows 10 2019 年 5 月更新 (1903_18362) 已知问题与处理进度汇总](https://answers.microsoft.com/zh-hans/insider/forum/all/bug-%E6%B1%87%E6%80%BBwindows-10-2019-%E5%B9%B4-5/252d0d6a-022c-4bf7-9976-55b57590aee2)” 讨论话题。

> [!IMPORTANT]
>
> &emsp;灵糕中心为个人项目，管理者不是 Microsoft 公司员工，不能代表 Microsoft 公司立场、态度。中心无意且无法代替 “反馈中心” (Feedback Hub) 应用的重要作用。中心不提供 Microsoft 产品技术支持服务。中心不接受有关 Windows 11 预览体验版本的反馈，用户应始终通过 “反馈中心” 应用提交。
>
> &emsp;Windows、Windows Insider Program 等是 Microsoft 公司的商标。

&emsp;&emsp;**宗旨**：独立管理、服务用户、信息精准、更新及时

[反馈中心](https://aka.ms/fbh) | [深入了解反馈](https://learn.microsoft.com/zh-cn/windows-insider/feedback) | [Flight Hub](https://learn.microsoft.com/en-us/windows-insider/flight-hub) | Windows 预览体验计划 - [网站](https://www.microsoft.com/zh-cn/windowsinsider) · [博客](https://blogs.windows.com/windows-insider) · [X](https://twitter.com/windowsinsider) · Microsoft 社区 ([中](https://answers.microsoft.com/zh-hans/insider/forum) / [英](https://answers.microsoft.com/en-us/insider/forum))

| 🎖️ **推荐** | **[WinDiscover](https://windiscover.com) - 独立 Microsoft 新闻网站** | **关注 [@Microsoft 信仰中心](https://weibo.com/u/3139784387) 微博** |
| :--------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|            |            [**LCZBlog**](https://blog.licaoz.com)            |       [**GuCATs'摸鱼站**](https://goo-aw233.github.io)       |

## 总览

上次更新时间：2025 年 3 月 24 日 5:00 (UTC+8)。访问次数：8360+

收录反馈 316 个，其中正在调查 15 个 (含[搁置](#3) 1 个)、正在处理 5 个、已修复 296 个。

反馈更新记录：**今日更新 LG310 - 315**。- Ling 🫤 [总览图](https://raw.githubusercontent.com/Lingggao/LGHUB/main/Images/Linggao%20Hub.png) | [反馈更新记录](Documents/Update_Feedback.md) | [平台更新记录](Documents/Update_Platform.md)

[**WIP Canary 27818 更新简报**](Canary.md) | [往期简报](Documents/Canary_Previous)

|         频道         |              最新版本               | 时间 (UTC+8) | 公告 |
| :------------------: | :---------------------------------: | :----------: | :------------------: |
|        Canary        |                27818                |  2025/3/20  | [aka.ms/wip27818](https://blogs.windows.com/windows-insider/2025/03/19/announcing-windows-11-insider-preview-build-27818-canary-channel) |
|       Dev        | 26120.3576 |   2025/3/18   | [aka.ms/wip-dev-3-17-25](https://blogs.windows.com/windows-insider/2025/03/17/announcing-windows-11-insider-preview-build-26120-3576-dev-and-beta-channels) |
|         Beta         | 26120.3576 |   2025/3/18   | [aka.ms/wip-dev-3-17-25](https://blogs.windows.com/windows-insider/2025/03/17/announcing-windows-11-insider-preview-build-26120-3576-dev-and-beta-channels) |
| Release Preview  | 26100.3613 |  2025/3/19  | [blogs.windows.com](https://blogs.windows.com/windows-insider/2025/03/18/releasing-windows-11-build-26100-3613-to-the-release-preview-channel) |
| General Availability |    26100.3476    |  2025/3/12  | [support.microsoft.com](https://support.microsoft.com/en-us/help/5053598) |

<img src="Images/Graph_1.png" width = "93%" />

统计图 - 2024 年 ([1 - 4 月](Images/Graph_2401_2404.png) · [5 - 8 月](Images/Graph_2405_2408.png) · [9 - 12 月](Images/Graph_2409_2412.png)) | 2025 年 ([1 - 4 月](Images/Graph_1.png) · 5 - 8 月 · 9 - 12 月)

---

> [!NOTE]
>
> &emsp;多数问题是仅有 1 - 2 位 Insiders 反馈的 “偶发性” 问题，而非所有人都会遇到的 “广泛性” 问题。请放心地更新 Windows 11 预览体验版本，不必担心新版使用体验过差。

|      编号       |                             问题                             |   状态   |
| :-------------: | :----------------------------------------------------------: | :------: |
|       ——        |              [**Canary - 公告已知问题**](#0) ▼               |    ——    |
| [LG212](#LG212) | **[Copilot+ 电脑]** 加入 Canary 频道后，PIN 和生物识别信息将丢失。 | 正在处理 |
| [LG309](#LG309) |        以平板电脑方式使用时，任务栏中的图标不会变大。        | 正在处理 |
|       ——        | [**Canary - 公告已知问题**](#0) ▲ \| ▼ [**Canary - 用户反馈问题**](#1) |    ——    |
| [LG310](#LG310) | **[置顶]** **启动部分应用 / 功能时 WHEA_UNCORRECTABLE_ERROR 绿屏**。 | 正在调查 |
| [LG225](#LG225) |        文件资源管理器 “...” 二级菜单无法向下方弹出。         | 正在处理 |
| [LG252](#LG252) |              组策略编辑器和服务管理器 UI 错误。              | 正在调查 |
| [LG258](#LG258) |            拖动表情符号面板中的滚动条时卡顿严重。            | 正在调查 |
| [LG265](#LG265) |        Windows 安全中心 “智能应用控制” 功能丢失图标。        | 正在调查 |
| [LG277](#LG277) |     右键文件时，删除按钮的鼠标悬停提示为 “删除 (删除)”。     | 正在调查 |
| [LG279](#LG279) |   在反馈中心提交的反馈有状态更新或官方回复时无法收到通知。   | 正在调查 |
| [LG281](#LG281) |           使用 ms-search: 链接时任务栏搜索框消失。           | 正在调查 |
| [LG286](#LG286) | Microsoft Store 宣传视频中的 “投放到设备” 被译为 “强制转换为设备”。 | 正在调查 |
| [LG289](#LG289) | 使用深色模式时，“电池使用情况” 菜单中的鼠标悬停提示显示为浅色。 | 正在调查 |
| [LG301](#LG301) |     在文件资源管理器中新建标签页时，地址栏中的路径不变。     | 正在调查 |
| [LG308](#LG308) |    最小化并使用 ALT + TAB 还原文件资源管理器时 UI 异常。     | 正在处理 |
| [LG311](#LG311) |        **文件资源管理器地址栏溢出列表无法正确呈现**。        | 正在调查 |
| [LG312](#LG312) |             **在截图工具中使用画笔时应用冻结**。             | 正在调查 |
| [LG313](#LG313) |    **[3 月 22 日]** **搜索功能的结果出现速度大幅变慢**。     | 正在调查 |
| [LG314](#LG314) |                **记事本应用更新后性能变差**。                | 正在处理 |
| [LG315](#LG315) |           **无法启动 IP Helper (IpHlpSvc) 服务**。           | 正在调查 |
|       ——        | [**Canary - 用户反馈问题**](#1) ▲ \| ▼ [**Canary - 归档 (已做出更改 0 - 7 天)**](#2) |    ——    |
| [LG306](#LG306) |    **[27802+]** 部分应用因 d3d9.dll 崩溃而无法正常运行。     | 已修复 ✓ |
| [LG307](#LG307) |   Windows 更新时自动重置蜂窝设置，导致 eSIM 设备丢失网络。   | 已修复 ✓ |
|       ——        | *部分未收录反馈详见 [WIP Canary 27818 更新简报](Canary.md)*  |    ——    |
|       ——        |       ▲ [**Canary - 归档 (已做出更改 0 - 7 天)**](#2)        |    ——    |
|       ——        | [**Canary - 归档 (已做出更改 >7 天)**](7+.md) \| [**Canary - 搁置 (未做出更改)**](#3) |    ——    |

[分享反馈线索](https://forms.office.com/Pages/ResponsePage.aspx?id=DQSIkWdsW0yxEjajBLZtrQAAAAAAAAAAAAO__Q3sH7RUNjUyUzJLN0JBREZGMzBBVlpVOEVBQkRENy4u) | [反馈平台问题](https://forms.office.com/Pages/ResponsePage.aspx?id=DQSIkWdsW0yxEjajBLZtrQAAAAAAAAAAAAO__Q3sH7RUQ0haOElMVkxOWDE4U1pHQUZWMDhEM1gwSC4u)

<SPAN ID = '0'/>

## Canary - 公告已知问题

> [!TIP]
>
> &emsp;记录 [Windows Insider 博客](https://blogs.windows.com/windows-insider)中明确公开的已知问题。

---

<SPAN ID = 'LG212'/>编号：LG212  
日期：2024 年 8 月 16 日  
版本：Canary 27686 - 27818  
**问题**：**[Copilot+ 电脑] 加入 Canary 频道后，PIN 和生物识别信息将丢失**。  
状态：<img src="Images/W.png" width = "9%" />  
Microsoft 官方回复：“如果您使用 Copilot+ 设备从 Dev、Release Preview 或 Retail 频道加入至 Canary 频道，Windows Hello PIN 和生物识别信息将会丢失。您将无法登录系统，显示 0xd0000225 错误和 ‘出错了，您的 PIN 不可用’ 信息。点击 ‘设置我的 PIN’ 选项应当可以重设 PIN。” *(Ling 译)* <img src="Images/M.png" width = "14%" />

---

<SPAN ID = 'LG309'/>编号：LG309  
日期：2025 年 3 月 21 日  
版本：Canary 27818  
**问题**：**以平板电脑方式使用时，任务栏中的图标不会变大**。  
状态：<img src="Images/W.png" width = "9%" />  
典型反馈：[aka.ms/AAv7ss7](https://aka.ms/AAv7ss7) <img src="Images/M.png" width = "14%" />

<SPAN ID = '1'/>

## Canary - 用户反馈问题

> [!TIP]
>
> &emsp;记录[反馈中心应用](https://aka.ms/fbh)中 Microsoft 明确响应的问题。

---

<SPAN ID = 'LG310'/>编号：LG310  
日期：2025 年 3 月 24 日  
版本：Canary 27818  
**问题**：**启动部分应用 / 功能时 WHEA_UNCORRECTABLE_ERROR 绿屏**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAv7zrj](https://aka.ms/AAv7zrj) & [aka.ms/AAv7s0c](https://aka.ms/AAv7s0c) & [aka.ms/AAv7l43](https://aka.ms/AAv7l43) & [aka.ms/AAv7l46](https://aka.ms/AAv7l46)

已知异常应用 / 功能列表：

- VMware Workstation Pro
- 火绒安全软件 6.0
- 网易 MuMu 模拟器
- 适用于 Linux 的 Windows 子系统 (WSL)

---

<SPAN ID = 'LG225'/>编号：LG225  
日期：2024 年 10 月 9 日  
版本：Canary 27718 - 27818  
**问题**：**文件资源管理器 “...” 二级菜单无法向下方弹出**。  
状态：<img src="Images/W.png" width = "9%" />  
典型反馈：[aka.ms/AAspbvg](https://aka.ms/AAspbvg) & [aka.ms/AAtyk9a](https://aka.ms/AAtyk9a) <img src="Images/M.png" width = "14%" />

<img src="Images/LG225.png" width = "55%" />

---

<SPAN ID = 'LG252'/>编号：LG252  
日期：2024 年 12 月 20 日  
版本：Canary 27764 - 27818  
**问题**：**组策略编辑器和服务管理器 UI 错误**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAty56l](https://aka.ms/AAty56l)

<img src="Images/LG252.png" width = "50%" />

---

<SPAN ID = 'LG258'/>编号：LG258  
日期：2025 年 1 月 10 日  
版本：Canary 27766 - 27818  
**问题**：**拖动表情符号面板中的滚动条时卡顿严重**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAtws2s](https://aka.ms/AAtws2s)

<img src="Images/LG258.png" width = "30%" />

---

<SPAN ID = 'LG265'/>编号：LG265  
日期：2025 年 1 月 20 日  
版本：Canary 27774 - 27818  
**问题**：**Windows 安全中心 “智能应用控制” 功能丢失图标**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAu1k0e](https://aka.ms/AAu1k0e)

<img src="Images/LG265.png" width = "35%" />

---

<SPAN ID = 'LG277'/>编号：LG277  
日期：2025 年 1 月 29 日  
版本：Canary 27764 - 27818  
**问题**：**右键文件时，删除按钮的鼠标悬停提示为 “删除 (删除)”**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAu4457](https://aka.ms/AAu4457)

<img src="Images/LG277.png" width = "30%" />

---

<SPAN ID = 'LG279'/>编号：LG279  
日期：2025 年 1 月 29 日  
版本：ALL  
**问题**：**在反馈中心提交的反馈有状态更新或官方回复时无法收到通知**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAu3v9h](https://aka.ms/AAu3v9h) <img src="Images/M.png" width = "14%" />

---

<SPAN ID = 'LG281'/>编号：LG281  
日期：2025 年 1 月 29 日  
版本：Canary 27774 - 27818  
**问题**：**使用 ms-search: 链接时任务栏搜索框消失**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAu42tm](https://aka.ms/AAu42tm)

---

<SPAN ID = 'LG286'/>编号：LG286  
日期：2025 年 2 月 1 日  
版本：ALL  
**问题**：**Microsoft Store 宣传视频中的 “投放到设备” 被译为 “强制转换为设备”**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAu5r06](https://aka.ms/AAu5r06)

<img src="Images/LG286.png" width = "30%" />

---

<SPAN ID = 'LG289'/>编号：LG289  
日期：2025 年 2 月 22 日  
版本：Canary 27788 - 27818  
**问题**：**使用深色模式时，“电池使用情况” 菜单中的鼠标悬停提示显示为浅色**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAuk2qa](https://aka.ms/AAuk2qa)

<img src="Images/LG289.png" width = "30%" />

---

<SPAN ID = 'LG301'/>编号：LG301  
日期：2025 年 3 月 1 日  
版本：Canary 27788 - 27818  
**问题**：**在文件资源管理器中新建标签页时，地址栏中的路径不变**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAuq4uj](https://aka.ms/AAuq4uj)

<img src="Images/LG301.png" width = "50%" />

---

<SPAN ID = 'LG308'/>编号：LG308  
日期：2025 年 3 月 9 日  
版本：Canary 27802 - 27818  
**问题**：**最小化并使用 ALT + TAB 还原文件资源管理器时 UI 异常**。  
状态：<img src="Images/W.png" width = "9%" />  
典型反馈：[aka.ms/AAuyemc](https://aka.ms/AAuyemc) <img src="Images/M.png" width = "14%" />

<img src="Images/LG308.png" width = "50%" />

---

<SPAN ID = 'LG311'/>编号：LG311  
日期：2025 年 3 月 24 日  
版本：Canary 27818  
**问题**：**文件资源管理器地址栏溢出列表无法正确呈现**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAv26rl](https://aka.ms/AAv26rl)

<img src="Images/LG311.png" width = "50%" />

---

<SPAN ID = 'LG312'/>编号：LG312  
日期：2025 年 3 月 24 日  
版本：Canary 27818  
**问题**：**在截图工具中使用画笔时应用冻结**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAv26rl](https://aka.ms/AAv26rl)

---

<SPAN ID = 'LG313'/>编号：LG313  
日期：2025 年 3 月 24 日  
版本：Canary 27818  
**问题**：**[3 月 22 日] 搜索功能的结果出现速度大幅变慢**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAv7ss9](https://aka.ms/AAv7ss9)

---

<SPAN ID = 'LG314'/>编号：LG314  
日期：2025 年 3 月 24 日  
版本：11.2501.30.0  
**问题**：**记事本应用更新后性能变差**。  
状态：<img src="Images/W.png" width = "9%" />  
典型反馈：[aka.ms/AAv7l3r](https://aka.ms/AAv7l3r) <img src="Images/M.png" width = "14%" />

---

<SPAN ID = 'LG315'/>编号：LG315  
日期：2025 年 3 月 24 日  
版本：Canary 27818  
**问题**：**无法启动 IP Helper (IpHlpSvc) 服务**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAv80jo](https://aka.ms/AAv80jo)

<SPAN ID = '2'/>

## Canary - 归档 (已做出更改)

> [!TIP]
>
> &emsp;记录 Microsoft 已做出更改 0 - 7 天的问题 & 超过 14 天无新增赞成票的问题。
>
> &emsp;无特殊情况，问题归档后不再更新。

---

<SPAN ID = 'LG306'/>编号：LG306  
日期：2025 年 3 月 2 日  
版本：Canary 27802 - 27813  
**问题**：**[27802+] 部分应用因 d3d9.dll 崩溃而无法正常运行**。  
状态：Canary 27818 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAutwf5](https://aka.ms/AAutwf5) <img src="Images/M.png" width = "14%" />

---

<SPAN ID = 'LG307'/>编号：LG307  
日期：2025 年 3 月 2 日  
版本：Canary 27802 - 27813  
**问题**：**Windows 更新时自动重置蜂窝设置，导致 eSIM 设备丢失网络**。  
状态：Canary 27818 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAutwf0](https://aka.ms/AAutwf0)

---

*部分未收录反馈详见 [WIP Canary 27818 更新简报](Canary.md)*

[Microsoft 已做出更改 >7 天的问题](7+.md)

<SPAN ID = '3'/>

## Canary - 搁置 (未做出更改)

> [!TIP]
>
> &emsp;并非所有软件缺陷都要修复。
>
> &emsp;已收录的反馈也可能因缺少资源、修复风险过大、商业决策调整等长期或永久不予修复。本板块记录 Microsoft 超过 90 天未修复的问题，中心将每间隔 30 天在 Canary 频道最新版本中进行测试。

[Microsoft 超过 90 天未修复的问题](90+.md)

---

[回到顶部](#HEAD)

<img src="https://mirrors.creativecommons.org/presskit/icons/cc.xlarge.png" width = "3%" /> <img src="https://mirrors.creativecommons.org/presskit/icons/by.xlarge.png" width = "3%" /> <img src="https://mirrors.creativecommons.org/presskit/icons/sa.xlarge.png" width = "3%" />

在 “[署名 - 相同方式共享 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode.zh-Hans)” 协议 (CC BY-SA 4.0) 之条款下提供。

2023 - 2025, 高楷修 (Ling Gao), 灵糕中心 (Linggao Hub), [github.com/Lingggao/LGHUB](https://github.com/Lingggao/LGHUB)

[字体许可使用授权书](Images/字体许可使用授权书.png) | [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FLingggao%2FLGHUB&count_bg=%23737373&title_bg=%230078D7&icon=microsoft.svg&icon_color=%23FFFFFF&title=LGHUB&edge_flat=false)](https://hits.seeyoufarm.com) (访问次数统计：今日 / 累计)