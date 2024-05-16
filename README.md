<SPAN ID = 'HEAD'/>

<div align="center">
<img src="Images/LING_1.png" width = "25%" /> <img src="Images/MCC2024.png" width = "12%" />
</div>


<h1 align="center">灵糕中心 (Linggao Hub)</h1>

[github.com/Lingggao/LGHUB](https://github.com/Lingggao/LGHUB) (GitHub) & [lingggao.github.io/LGHUB](https://lingggao.github.io/LGHUB) (Pages)

&emsp;&emsp;**用于跟踪 “Windows 11 预览体验版本 (Canary 频道) 哪些反馈正在由 Microsoft 调查 / 处理 / 已做出更改” 的信息枢纽**。由 2021 Windows Insider Most Valuable Professional (MVP) · **Ling Gao** 先生管理。

&emsp;&emsp;灵糕中心成立于 2023 年 12 月 12 日，其前身可追溯至 2019 年 5 月 14 日由 Microsoft 社区创建的 “[\[BUG 汇总\] Windows 10 2019 年 5 月更新 (1903_18362) 已知问题与处理进度汇总](https://answers.microsoft.com/zh-hans/insider/forum/all/bug-%E6%B1%87%E6%80%BBwindows-10-2019-%E5%B9%B4-5/252d0d6a-022c-4bf7-9976-55b57590aee2)” 讨论话题。

> &emsp;**声明**：灵糕中心为个人项目，管理者不是 Microsoft 公司员工，不能代表 Microsoft 公司立场、态度。中心无意且无法代替 “反馈中心” (Feedback Hub) 应用的重要作用。中心不提供 Microsoft 产品技术支持服务。中心不接受有关 Windows 11 预览体验版本的反馈，用户应始终通过 “反馈中心” 应用提交。

> &emsp;Windows、Windows Insider Program 等是 Microsoft 公司的商标。

&emsp;&emsp;**宗旨**：独立管理、服务用户、信息精准、更新及时

[反馈中心](https://aka.ms/fbh) | [深入了解反馈](https://learn.microsoft.com/zh-cn/windows-insider/feedback) | [Flight Hub](https://learn.microsoft.com/en-us/windows-insider/flight-hub) | Windows 预览体验计划 - [网站](https://www.microsoft.com/zh-cn/windowsinsider) · [博客](https://blogs.windows.com/windows-insider) · [X (Twitter)](https://twitter.com/windowsinsider) · 社区 ([中](https://answers.microsoft.com/zh-hans/insider/forum) / [英](https://answers.microsoft.com/en-us/insider/forum))

## ✦ 总览 ✦

&emsp;&emsp;上次更新时间：2024 年 5 月 16 日 18:30 (UTC+8)。访问次数：3850+

&emsp;&emsp;收录反馈 170 个，其中正在调查 8 个 (含[搁置](#3) 6 个)、正在处理 3 个、已修复 159 个。

&emsp;&emsp;反馈更新记录：**今日更新反馈状态**。- Ling 🍀 [总览图](https://raw.githubusercontent.com/Lingggao/LGHUB/main/Images/Linggao%20Hub.png) | [反馈更新记录](Documents/Update_Feedback.md) | [平台更新记录](Documents/Update_Platform.md)

|      频道       |    最新版本    | 时间 (UTC+8) |                             公告                             |
| :-------------: | :------------: | :----------: | :----------------------------------------------------------: |
|     Canary      | **[新]** 26217 |  2024/5/16   | [aka.ms/wip26217](https://blogs.windows.com/windows-insider/2024/05/15/announcing-windows-11-insider-preview-build-26217-canary-channel) |
|       Dev       |   26120.470    |  2024/5/11   | [aka.ms/wip-dev-5-10](https://blogs.windows.com/windows-insider/2024/05/10/announcing-windows-11-insider-preview-build-26120-470-dev-channel) |
|      Beta       |   22635.3575   |  2024/5/11   | [aka.ms/wip-beta-5-10](https://blogs.windows.com/windows-insider/2024/05/10/announcing-windows-11-insider-preview-build-22635-3575-beta-channel) |
| Release Preview | 226(3/2)1.3520 |  2024/4/12   | [blogs.windows.com](https://blogs.windows.com/windows-insider/2024/04/11/releasing-windows-11-builds-22621-3520-and-22631-3520-to-the-release-preview-channel) |

<img src="Images/Graph_0.png" width = "90%" />

---

&emsp;&emsp;**提醒**：多数问题是仅有 1 - 2 位 Insiders 反馈的 “偶发性” 问题，而非所有人都会遇到的 “广泛性” 问题。请放心地更新 Windows 11 预览体验版本，不必担心新版使用体验过差。

|      编号       |                             问题                             |   状态   |
| :-------------: | :----------------------------------------------------------: | :------: |
| [LG123](#LG123) |                 接收不到 Build 26080+ 更新。                 | 正在处理 |
|     **——**      | [**Canary - 公告已知问题**](#0) **▲ \| ▼** [**Canary - 用户反馈问题**](#1) |  **——**  |
| [LGH02](#LGH02) |       **[集合]** 文件资源管理器中的软件缺陷。(含列表)        | 正在处理 |
| [LG148](#LG148) |            无法调整启动 “照片” 应用时窗口的大小。            | 正在调查 |
| [LGH03](#LGH03) |           **[集合]** 小组件中的软件缺陷。(含列表)            | 正在处理 |
| [LG169](#LG169) |            “照片” 应用在 HDR 显示模式中亮度异常。            | 正在调查 |
|     **——**      | [**Canary - 用户反馈问题**](#1) **▲ \| ▼** [**Canary - 归档 (已做出更改 0 - 7 天)**](#2) |  **——**  |
| [LG111](#LG111) |              **任务视图卡顿或 CPU 占用率高**。               | 已修复 ✓ |
| [LG158](#LG158) |                **电脑卡顿 / CPU 性能下降**。                 | 已修复 ✓ |
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

<SPAN ID = 'LGH02'/>编号：LGH02  
日期：2024 年 4 月 7 日  
版本：Canary 26100 - 26217  
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

<SPAN ID = 'LGH03'/>编号：LGH03  
日期：2024 年 4 月 19 日  
版本：Canary 26100 - 26217  
**集合**：**小组件中的软件缺陷**。  
状态：<img src="Images/W.png" width = "9%" />

列表

- 点击小组件时 Windows 崩溃 / 显示错误 - [aka.ms/AAq43k9](https://aka.ms/AAq43k9)
- “待办事项” 等小组件随机消失 - [aka.ms/AAq1w40](https://aka.ms/AAq1w40)
- 已固定的小组件随机消失 - [aka.ms/AAq33qp](https://aka.ms/AAq33qp)
- “悬停时打开小组件板” 选项始终显示为关 - [aka.ms/AAq70ys](https://aka.ms/AAq70ys)
- 交互时系统崩溃 / 显示 Windows 错误 - [aka.ms/AAq43k9](https://aka.ms/AAq43k9)
- “Windows 徽标键 + W” 快捷键失效 - [aka.ms/AAqgz49](https://aka.ms/AAqgz49)

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

<SPAN ID = 'LG111'/>编号：LG111  
版本：Canary 26063 - 26212  
**问题**：**任务视图卡顿或 CPU 占用率高**。  
状态：Canary 26217 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAph34g](https://aka.ms/AAph34g)

---

<SPAN ID = 'LG158'/>编号：LG158  
日期：2024 年 4 月 17 日  
版本：Canary 26100 - 26212  
**问题**：**电脑卡顿 / CPU 性能下降**。  
状态：Canary 26217 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
Microsoft 官方回复：“我们将持续监控用户反馈和 Windows 错误报告，以保障 Windows 的可靠性。如果您发现性能异常，请立即提交反馈，让我们了解您遇到的问题。” *(Ling 译)* <img src="Images/M.png" width = "14%" />  
典型反馈：[aka.ms/AAq21jx](https://aka.ms/AAq21jx) & [aka.ms/AAq296v](https://aka.ms/AAq296v)

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