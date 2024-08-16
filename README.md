<SPAN ID = 'HEAD'/>

<div align="center">
<img src="Images/LING_1.png" width = "25%" /> <img src="Images/MCA2024.png" width = "12%" />
</div>

<h1 align="center">灵糕中心 (Linggao Hub)</h1>

[github.com/Lingggao/LGHUB](https://github.com/Lingggao/LGHUB) (GitHub)

&emsp;&emsp;**用于跟踪 “Windows 11 预览体验版本 (Canary 频道) 中哪些反馈正在由 Microsoft 调查、处理 / 已做出更改” 的信息枢纽**。由 2021 Windows Insider 最有价值专家 (MVP) · **Ling Gao** 先生管理。

&emsp;&emsp;灵糕中心成立于 2023 年 12 月 12 日，其前身可追溯至 2019 年 5 月 14 日由 Microsoft 社区创建的 “[\[BUG 汇总\] Windows 10 2019 年 5 月更新 (1903_18362) 已知问题与处理进度汇总](https://answers.microsoft.com/zh-hans/insider/forum/all/bug-%E6%B1%87%E6%80%BBwindows-10-2019-%E5%B9%B4-5/252d0d6a-022c-4bf7-9976-55b57590aee2)” 讨论话题。

> [!IMPORTANT]
>
> &emsp;灵糕中心为个人项目，管理者不是 Microsoft 公司员工，不能代表 Microsoft 公司立场、态度。中心无意且无法代替 “反馈中心” (Feedback Hub) 应用的重要作用。中心不提供 Microsoft 产品技术支持服务。中心不接受有关 Windows 11 预览体验版本的反馈，用户应始终通过 “反馈中心” 应用提交。
>
> &emsp;Windows、Windows Insider Program 等是 Microsoft 公司的商标。

&emsp;&emsp;**宗旨**：独立管理、服务用户、信息精准、更新及时

[反馈中心](https://aka.ms/fbh) | [深入了解反馈](https://learn.microsoft.com/zh-cn/windows-insider/feedback) | [Flight Hub](https://learn.microsoft.com/en-us/windows-insider/flight-hub) | Windows 预览体验计划 - [网站](https://www.microsoft.com/zh-cn/windowsinsider) · [博客](https://blogs.windows.com/windows-insider) · [X](https://twitter.com/windowsinsider) · Microsoft 社区 ([中](https://answers.microsoft.com/zh-hans/insider/forum) / [英](https://answers.microsoft.com/en-us/insider/forum))

## ✦ 总览 ✦

&emsp;&emsp;上次更新时间：2024 年 8 月 16 日 16:00 (UTC+8)。访问次数：5400+

&emsp;&emsp;收录反馈 213 个，其中正在调查 8 个 (含[搁置](#3) 3 个)、正在处理 5 个、已修复 200 个。

&emsp;&emsp;反馈更新记录：**今日更新反馈状态**。- Ling 🛫 [总览图](https://raw.githubusercontent.com/Lingggao/LGHUB/main/Images/Linggao%20Hub.png) | [反馈更新记录](Documents/Update_Feedback.md) | [平台更新记录](Documents/Update_Platform.md)

|  🎖️ **推 荐**   |  [**Microsoft 电脑管家**](https://pcmanager.microsoft.com)   |     [**Microsoft WowTab**](https://wowtab.microsoft.com)     |
| :------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|                | **Windows 预览体验计划 - [信息 & 日志 & 链接](https://answers.microsoft.com/zh-hans/insider/forum/all/windows/2a5add38-c6d9-4c9d-958d-7451f7632b1c)** |                                                              |
| 🏅 **友情推荐** | **[WinDiscover](https://windiscover.com) - 独立 Microsoft 新闻博客** | **关注 [@Microsoft 信仰中心](https://weibo.com/u/3139784387) 微博** |
|                | **[Windows Up-to-Date](https://wutd.crrashh.com) - Windows 实时版本** |                                                              |

|         频道         |              最新版本               | 时间 (UTC+8) |                             公告                             |
| :------------------: | :---------------------------------: | :----------: | :----------------------------------------------------------: |
|        Canary        |                **[新]** 27686                |  2024/8/16  | [aka.ms/wip27686](https://aka.ms/wip27686) |
|         Dev          |              26120.1350 (24H2)              |   2024/8/10   | [aka.ms/wip-dev-8-9](https://blogs.windows.com/windows-insider/2024/08/09/announcing-windows-11-insider-preview-build-26120-1350-dev-channel) |
|         Beta         | 22635.4010 *(23H2)* |   2024/8/10   | [aka.ms/wip-beta-8-9](https://blogs.windows.com/windows-insider/2024/08/09/announcing-windows-11-insider-preview-build-22635-4010-beta-channel) |
|   Release Preview    | 26100.1301 (24H2) |  2024/7/31  | [support.microsoft.com](https://support.microsoft.com/zh-cn/topic/july-30-2024-kb5040529-os-build-26100-1301-preview-89f3ad4f-a5fe-4065-b217-01e622133ca1) |
| General Availability |    22631.4037 *(23H2)*    |  2024/8/14  | [support.microsoft.com](https://support.microsoft.com/help/5041585) |

<img src="Images/Graph_0.png" width = "93%" />

统计图 - 2024 年 | [1 - 4 月](Images/Graph_2401_2404.png) · [5 - 8 月](Images/Graph_0.png) · [9 - 12 月](https://github.com/Lingggao/LGHUB)

---

> [!NOTE]
>
> &emsp;多数问题是仅有 1 - 2 位 Insiders 反馈的 “偶发性” 问题，而非所有人都会遇到的 “广泛性” 问题。请放心地更新 Windows 11 预览体验版本，不必担心新版使用体验过差。

|      编号       |                             问题                             |   状态   |
| :-------------: | :----------------------------------------------------------: | :------: |
| [LG212](#LG212) | **在 Copilot+ 设备上加入 Canary 频道后，PIN 和生物识别信息将会丢失**。 | 正在处理 |
| [LG202](#LG202) |               表情符号面板可能意外地自动关闭。               | 正在处理 |
|     **——**      | [**Canary - 公告已知问题**](#0) **▲ \| ▼** [**Canary - 用户反馈问题**](#1) |  **——**  |
| [LGH02](#LGH02) |       **[集合]** 文件资源管理器中的软件缺陷。(*含列表)       | 正在处理 |
| [LG177](#LG177) |              任务管理器 “性能” 选项卡颜色异常。              | 正在处理 |
| [LG178](#LG178) |          任务管理器设置菜单 Mica (云母) 效果异常。           | 正在调查 |
| [LG191](#LG191) | 将桌面背景设置为 “Windows 聚焦” 时，其在一段时间后变为 “图片”。 | 正在调查 |
| [LG206](#LG206) |     点击手机连接应用中的 “新照片” 通知时，截图工具崩溃。     | 正在调查 |
| [LG207](#LG207) |                   截图工具可能挂起或闪退。                   | 正在调查 |
| [LG208](#LG208) |      “设置”>“账户”>“关联的设备” 菜单中的内容不断闪烁。       | 正在处理 |
| [LG211](#LG211) |                      鼠标光标随机卡住。                      | 正在调查 |
|     **——**      | [**Canary - 用户反馈问题**](#1) **▲ \| ▼** [**Canary - 归档 (已做出更改 0 - 7 天)**](#2) |  **——**  |
| [LG123](#LG123) |               **接收不到 Build 26080+ 更新**。               | 已修复 ✓ |
| [LG201](#LG201) |      **无法启动 Windows 沙盒，显示 0x80370106 错误**。       | 已修复 ✓ |
| [LG203](#LG203) |          **“物理键盘文本建议” 功能无法正常工作**。           | 已修复 ✓ |
| [LG188](#LG188) |               **安装 WSL 时显示灾难性错误**。                | 已修复 ✓ |
| [LG189](#LG189) |         **将大图片设置为桌面背景时，其显示为黑色**。         | 已修复 ✓ |
| [LG195](#LG195) |            **手写笔在 Surface 设备中精度变低**。             | 已修复 ✓ |
| [LG199](#LG199) |             **Windows 通知被前台应用窗口遮挡**。             | 已修复 ✓ |
| [LG209](#LG209) |  **Euro Truck Simulator 2 (欧洲卡车模拟 2) 游戏无法运行**。  | 已修复 ✓ |
| [LG210](#LG210) |         **Microsoft Edge (Canary 频道) 频繁崩溃**。          | 已修复 ✓ |
| [LG149](#LG149) | **Windows 安全中心 “防火墙和网络保护” 页面中的图标变为方块**。 | 已修复 ✓ |
|     **——**      | **✦** [**Canary - 归档 (已做出更改 >7 天)**](7+.md) **✦ \| ✦** [**Canary - 搁置 (未做出更改)**](#3) **✦** |  **——**  |

[分享反馈线索](https://forms.office.com/Pages/ResponsePage.aspx?id=DQSIkWdsW0yxEjajBLZtrQAAAAAAAAAAAAO__Q3sH7RUNjUyUzJLN0JBREZGMzBBVlpVOEVBQkRENy4u) | [反馈平台问题](https://forms.office.com/Pages/ResponsePage.aspx?id=DQSIkWdsW0yxEjajBLZtrQAAAAAAAAAAAAO__Q3sH7RUQ0haOElMVkxOWDE4U1pHQUZWMDhEM1gwSC4u)

<SPAN ID = '0'/>

## ✦ Canary - 公告已知问题 ✦

> [!TIP]
>
> &emsp;记录 [Windows Insider 博客](https://blogs.windows.com/windows-insider)中明确公开的已知问题。

---

<SPAN ID = 'LG212'/>编号：LG212  
日期：2024 年 8 月 16 日  
版本：Canary 27686  
**问题**：**在 Copilot+ 设备上加入 Canary 频道后，PIN 和生物识别信息将会丢失**。  
状态：<img src="Images/W.png" width = "9%" />  
Microsoft 官方回复：“如果您使用 Copilot+ 设备从 Dev、Release Preview 或 Retail 频道加入至 Canary 频道，Windows Hello PIN 和生物识别信息将会丢失。您将无法登录系统，显示 0xd0000225 错误和 ‘出错了，您的 PIN 不可用’ 信息。点击 ‘设置我的 PIN’ 选项应当可以重设 PIN。” *(Ling 译)* <img src="Images/M.png" width = "14%" />

---

<SPAN ID = 'LG202'/>编号：LG202  
日期：2024 年 7 月 25 日  
版本：Canary 26257 - 27686  
**问题**：**表情符号面板可能意外地自动关闭**。  
状态：<img src="Images/W.png" width = "9%" />

<SPAN ID = '1'/>

## ✦ Canary - 用户反馈问题 ✦

> [!TIP]
>
> &emsp;记录[反馈中心应用](https://aka.ms/fbh)中 Microsoft 明确响应的问题。

---

<SPAN ID = 'LGH02'/>编号：LGH02  
日期：2024 年 4 月 7 日  
版本：Canary 26100 - 27686  
**集合**：**文件资源管理器中的软件缺陷**。  
状态：<img src="Images/W.png" width = "9%" />

列表

- 卡顿 / 内存泄漏 / CPU 占用率高
- 无法为 HEVC 视频生成缩略图 - [aka.ms/AArjpwi](https://aka.ms/AArjpwi)
- 打开主文件夹或添加新标签时崩溃 - [aka.ms/AAqyaoe](https://aka.ms/AAqyaoe)
- 双击压缩文件时没有反应 - [aka.ms/AAqk1zl](https://aka.ms/AAqk1zl) - 已修复 ✓
- 打开含有 SLN 文件的文件夹时崩溃 - [aka.ms/AAqyaoa](https://aka.ms/AAqyaoa) - 已修复 ✓
- 预览性能下降 - [aka.ms/AAqmzfc](https://aka.ms/AAqmzfc) - 已修复 ✓
- 在搜索栏中输入的字符随机被删除 - [aka.ms/AAq9sqa](https://aka.ms/AAq9sqa) - 已修复 ✓
- 菜单中的文本可能过长 - [aka.ms/AApyuo4](https://aka.ms/AApyuo4) - 已修复 ✓
- 缩放设定为 175% 时图标模糊不清 - [aka.ms/AApytl6](https://aka.ms/AApytl6) - 已修复 ✓
- 出现旧版白色工具栏 - [aka.ms/AAn4f6s](https://aka.ms/AAn4f6s) \- 已修复 ✓
- 新建文件夹时，焦点可能定位到地址栏 - [aka.ms/AAqjq2b](https://aka.ms/AAqjq2b) \- 已修复 ✓
- 导航窗格中的 OneDrive 随机变化位置 - [aka.ms/AApxwbw](https://aka.ms/AApxwbw) \- 已修复 ✓
- 切换 “项目复选框” 选项时出现异常 - [aka.ms/AApydtm](https://aka.ms/AApydtm) - 已修复 ✓
- 出现多个地址栏 / 搜索栏 - [aka.ms/AApymuw](https://aka.ms/AApymuw) - 已修复 ✓
- 在深色模式添加新标签时窗口闪烁 - [aka.ms/AAq33qn](https://aka.ms/AAq33qn) - 已修复 ✓

---

<SPAN ID = 'LG177'/>编号：LG177  
日期：2024 年 6 月 9 日  
版本：Canary 26231 - 26244 & 26257 - 27686  
**问题**：**任务管理器 “性能” 选项卡颜色异常**。  
状态：Canary 27686 - <img src="Images/W.png" width = "9%" /> (Canary 26252 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓)  
典型反馈：[aka.ms/AAqtf01](https://aka.ms/AAqtf01) <img src="Images/M.png" width = "14%" />

<img src="Images/LG177.png" width = "45%" />

---

<SPAN ID = 'LG178'/>编号：LG178  
日期：2024 年 6 月 9 日  
版本：Canary 26231 - 27686  
**问题**：**任务管理器设置菜单 Mica (云母) 效果异常**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAqsxwz](https://aka.ms/AAqsxwz)

<img src="Images/LG178.png" width = "45%" />

---

<SPAN ID = 'LG191'/>编号：LG191  
日期：2024 年 7 月 13 日  
版本：Canary 26252 - 27686  
**问题**：**将桌面背景设置为 “Windows 聚焦” 时，其在一段时间后变为 “图片”**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AArdunq](https://aka.ms/AArdunq) & [aka.ms/AAregd1](https://aka.ms/AAregd1)

---

<SPAN ID = 'LG206'/>编号：LG206  
日期：2024 年 8 月 3 日  
版本：Canary 26257 - 27686  
**问题**：**点击手机连接应用中的 “新照片” 通知时，截图工具崩溃**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AArkcs7](https://aka.ms/AArkcs7)

---

<SPAN ID = 'LG207'/>编号：LG207  
日期：2024 年 8 月 3 日  
版本：Canary 26257 - 27686  
**问题**：**截图工具可能挂起或闪退**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAroi77](https://aka.ms/AAroi77)

---

<SPAN ID = 'LG208'/>编号：LG208  
日期：2024 年 8 月 3 日  
版本：Canary 26257 - 27686  
**问题**：**“设置”>“账户”>“关联的设备” 菜单中的内容不断闪烁**。  
状态：<img src="Images/W.png" width = "9%" />  
典型反馈：[aka.ms/AAroaxp](https://aka.ms/AAroaxp) <img src="Images/M.png" width = "14%" />

---

<SPAN ID = 'LG211'/>编号：LG211  
日期：2024 年 8 月 14 日  
版本：Canary 26257 - 27686  
**问题**：**鼠标光标随机卡住**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AArterh](https://aka.ms/AArterh)

<SPAN ID = '2'/>

## ✦ Canary - 归档 (已做出更改) ✦

> [!TIP]
>
> &emsp;记录 Microsoft 已做出更改 0 - 7 天的问题 & 超过 14 天无新增赞成票的问题。
>
> &emsp;无特殊情况，问题归档后不再更新。

---

<SPAN ID = 'LG123'/>编号：LG123  
版本：ALL  
**问题**：**接收不到 Build 26080+ 更新**。  
状态：Canary 27686 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
Microsoft 官方回复：“我们正在调查有关部分 Insider 卡在 26040 / 23620 版本的反馈。如果您迫切期望立即回到正轨，可使用最新 ISO 全新安装 Windows，然后重新加入 Canary 或 Dev 频道。” *(Ling 译)*  
<img src="Images/M.png" width = "14%" />  
典型反馈：[aka.ms/AApjbci](https://aka.ms/AApjbci)

---

<SPAN ID = 'LG201'/>编号：LG201  
日期：2024 年 7 月 25 日  
版本：Canary 26257  
**问题**：**无法启动 Windows 沙盒，显示 0x80370106 错误**。  
状态：Canary 27686 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓

---

<SPAN ID = 'LG203'/>编号：LG203  
日期：2024 年 8 月 3 日  
版本：Canary 26257  
**问题**：**“物理键盘文本建议” 功能无法正常工作**。  
状态：Canary 27686 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓

---

<SPAN ID = 'LG188'/>编号：LG188  
日期：2024 年 7 月 13 日  
版本：Canary 26252 - 26257  
**问题**：**安装 WSL 时显示灾难性错误**。  
状态：Canary 27686 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AArbr2b](https://aka.ms/AArbr2b)

---

<SPAN ID = 'LG189'/>编号：LG189  
日期：2024 年 7 月 13 日  
版本：Canary 26252 - 26257  
**问题**：**将大图片设置为桌面背景时，其显示为黑色**。  
状态：Canary 27686 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AArbr2d](https://aka.ms/AArbr2d)

---

<SPAN ID = 'LG195'/>编号：LG195  
日期：2024 年 7 月 13 日  
版本：Canary 26252 - 26257  
**问题**：**手写笔在 Surface 设备中精度变低**。  
状态：Canary 27686 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AArdnci](https://aka.ms/AArdnci)

---

<SPAN ID = 'LG199'/>编号：LG199  
日期：2024 年 7 月 23 日  
版本：Canary 26252 - 26257  
**问题**：**Windows 通知被前台应用窗口遮挡**。  
状态：Canary 27686 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AArhznv](https://aka.ms/AArhznv) <img src="Images/M.png" width = "14%" />

---

<SPAN ID = 'LG209'/>编号：LG209  
日期：2024 年 8 月 3 日  
版本：Canary 26257  
**问题**：**Euro Truck Simulator 2 (欧洲卡车模拟 2) 游戏无法运行**。  
状态：Canary 27686 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AArjpwj](https://aka.ms/AArjpwj)

---

<SPAN ID = 'LG210'/>编号：LG210  
日期：2024 年 8 月 14 日  
版本：Edge Canary  
**问题**：**Microsoft Edge (Canary 频道) 频繁崩溃**。  
状态：Edge 129.0.2773.0 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AArslxp](https://aka.ms/AArslxp) <img src="Images/M.png" width = "14%" />

---

<SPAN ID = 'LG149'/>编号：LG149  
日期：2024 年 4 月 10 日  
版本：Canary 26100 - 26257  
**问题**：**Windows 安全中心 “防火墙和网络保护” 页面中的图标变为方块**。  
状态：Canary 27686 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AApy8i2](https://aka.ms/AApy8i2)

<img src="Images/LG149.png" width = "50%" />

[Microsoft 已做出更改 >7 天的问题](7+.md)

<SPAN ID = '3'/>

## ✦ Canary - 搁置 (未做出更改) ✦

> [!TIP]
>
> &emsp;“并非所有软件缺陷都要修复。” —— Ron Patton (出自《软件测试》)
>
> &emsp;已收录的反馈也可能因缺少资源、修复风险过大、商业决策调整等长期或永久不予修复。本板块记录 Microsoft 超过 90 天未修复的问题，中心将每间隔 30 天在 Canary 频道最新版本中进行测试。

[Microsoft 超过 90 天未修复的问题](90+.md)

---

[回到顶部](#HEAD)

<img src="https://mirrors.creativecommons.org/presskit/icons/cc.xlarge.png" width = "3%" /> <img src="https://mirrors.creativecommons.org/presskit/icons/by.xlarge.png" width = "3%" /> <img src="https://mirrors.creativecommons.org/presskit/icons/sa.xlarge.png" width = "3%" />

在 “[署名 - 相同方式共享 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode.zh-Hans)” 协议 (CC BY-SA 4.0) 之条款下提供。

2023 - 2024, 高楷修 (Ling Gao), 灵糕中心 (Linggao Hub), [github.com/Lingggao/LGHUB](https://github.com/Lingggao/LGHUB)

[字体许可使用授权书](Images/字体许可使用授权书.png) | [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FLingggao%2FLGHUB&count_bg=%23737373&title_bg=%230078D7&icon=microsoft.svg&icon_color=%23FFFFFF&title=LGHUB&edge_flat=false)](https://hits.seeyoufarm.com) (访问次数统计：今日 / 累计)