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

| 😸 欢迎加入 [“Ling 的 Windows Insider 小屋”](https://teams.live.com/l/community/FEAd0AVp_B_pTH5Zgk) Microsoft Teams 社区 😽 |
| :----------------------------------------------------------: |

上次更新时间：2025 年 5 月 26 日 16:00 (UTC+8)。Star 数量：49 ⭐

收录反馈 385 个，其中正在调查 26 个 (含[搁置](#3) 0 个)、正在处理 7 个、已修复 352 个。

反馈更新记录：**今日更新 LG379 - 384**。- Ling 🤭 [总览图](https://raw.githubusercontent.com/Lingggao/LGHUB/main/Images/Linggao%20Hub.png) | [反馈更新记录](Documents/Update_Feedback.md) | [平台更新记录](Documents/Update_Platform.md)

[**WIP Canary 27863 更新简报**](Canary.md) | [往期简报](Documents/Canary_Previous)

|         频道         |              最新版本               | 时间 (UTC+8) | 公告 |
| :------------------: | :---------------------------------: | :----------: | :------------------: |
|        Canary        |                27863                |  2025/5/24  | [aka.ms/wip27863](https://blogs.windows.com/windows-insider/2025/05/23/announcing-windows-11-insider-preview-build-27863-canary-channel) |
|       Dev        | 26200.5603 |   2025/5/20   | [aka.ms/wip-dev-5-19-25](https://blogs.windows.com/windows-insider/2025/05/19/announcing-windows-11-insider-preview-build-26200-5603-dev-channel) |
|         Beta         | 26120.4161 |   2025/5/24   | [aka.ms/wip-beta-5-23-25](https://blogs.windows.com/windows-insider/2025/05/23/announcing-windows-11-insider-preview-build-26120-4161-beta-channel) |
| Release Preview  | 26100.4188 |  2025/5/20  | [blogs.windows.com](https://blogs.windows.com/windows-insider/2025/05/19/releasing-windows-11-build-26100-4188-to-the-release-preview-channel) |
| General Availability |    26100.4061    |  2025/5/14  | [support.microsoft.com](https://support.microsoft.com/en-us/help/5058411) |

<img src="Images/Graph_1.png" width = "93%" />

统计图 - 2024 年 ([1 - 4 月](Images/Graph_2401_2404.png) · [5 - 8 月](Images/Graph_2405_2408.png) · [9 - 12 月](Images/Graph_2409_2412.png)) | 2025 年 ([1 - 4 月](Images/Graph_2501_2504.png) · [5 - 8 月](Images/Graph_1.png) · 9 - 12 月)

---

> [!NOTE]
>
> &emsp;多数问题是仅有 1 - 2 位 Insiders 反馈的 “偶发性” 问题，而非所有人都会遇到的 “广泛性” 问题。请放心地更新 Windows 11 预览体验版本，不必担心新版使用体验过差。

|      编号       |                             问题                             |   状态   |
| :-------------: | :----------------------------------------------------------: | :------: |
|       ——        |              [**Canary - 公告已知问题**](#0) ▼               |    ——    |
| [LG212](#LG212) | **[Copilot+ 电脑]** 加入 Canary 频道后，PIN 和生物识别信息将丢失。 | 正在处理 |
| [LG342](#LG342) |                 打开组策略编辑器时提示错误。                 | 正在处理 |
| [LG368](#LG368) |              任务栏材质效果消失，变成了深灰色。              | 正在处理 |
| [LG374](#LG374) |            高采样率 (192 kHz) 设备无法播放音频。             | 正在处理 |
| [LG365](#LG365) |                     手写笔无法正常使用。                     | 正在处理 |
| [LG366](#LG366) |               任务管理器的搜索和筛选功能失效。               | 正在处理 |
|       ——        | [**Canary - 公告已知问题**](#0) ▲ \| ▼ [**Canary - 用户反馈问题**](#1) |    ——    |
| [LG252](#LG252) |              组策略编辑器和服务管理器 UI 错误。              | 正在调查 |
| [LG258](#LG258) |            拖动表情符号面板中的滚动条时卡顿严重。            | 正在调查 |
| [LG277](#LG277) |     右键文件时，删除按钮的鼠标悬停提示为 “删除 (删除)”。     | 正在调查 |
| [LG279](#LG279) |   在反馈中心提交的反馈有状态更新或官方回复时无法收到通知。   | 正在调查 |
| [LG281](#LG281) |           使用 ms-search: 链接时任务栏搜索框消失。           | 正在调查 |
| [LG286](#LG286) | Microsoft Store 宣传视频中的 “投放到设备” 被译为 “强制转换为设备”。 | 正在调查 |
| [LG311](#LG311) |          文件资源管理器地址栏溢出列表无法正确呈现。          | 正在调查 |
| [LG323](#LG323) | 将鼠标悬停在 “系统信息” 菜单顶部的选项卡时，边框显示为直角。 | 正在调查 |
| [LG347](#LG347) |            满足条件后在反馈中心无法获得成就徽章。            | 正在调查 |
| [LG348](#LG348) |       安装 Windows 11 时，菜单按照从右到左的方式排列。       | 正在调查 |
| [LG357](#LG357) |         截图工具无法截取搜索界面、上下文菜单等 UI。          | 正在调查 |
| [LG361](#LG361) |          Microsoft Store 不显示较早的应用更新记录。          | 正在调查 |
| [LG367](#LG367) |         安装 Canary 27858 更新时，屏幕显示白色画面。         | 正在调查 |
| [LG370](#LG370) |                  重启 explorer.exe 时白屏。                  | 正在调查 |
| [LG371](#LG371) |              开启 “自动隐藏任务栏” 后出现黑边。              | 正在调查 |
| [LG372](#LG372) |                   玩 DNF 游戏时电脑绿屏。                    | 正在调查 |
| [LG373](#LG373) |         电脑 WIN32K_CRITICAL_FAILURE (0x164) 绿屏。          | 正在调查 |
| [LG375](#LG375) |              触摸屏的双击、长按右键等操作失效。              | 正在处理 |
| [LG376](#LG376) |           使用 NVIDIA GeForce NOW 平台时电脑绿屏。           | 正在调查 |
| [LG377](#LG377) |                红外 (IR) 摄像头无法正常工作。                | 正在调查 |
| [LG378](#LG378) |           记事本文档中的下划线 “_” 无法正常显示。            | 正在调查 |
| [LG379](#LG379) |  **Microsoft Store 最小化时，无法右键任务栏图标将其关闭**。  | 正在调查 |
| [LG380](#LG380) |    **使用 “照片” 应用裁剪图片后，保存时屏幕会闪烁一下**。    | 正在调查 |
| [LG381](#LG381) |               **玩 PUBG 游戏时电脑自动重启**。               | 正在调查 |
| [LG382](#LG382) |            **微信输入法候选框周围出现黑粗边框**。            | 正在调查 |
| [LG383](#LG383) | **开启 “管理员保护” 功能并以管理员身份运行终端时，UAC 对话框死锁**。 | 正在调查 |
| [LG384](#LG384) |    **将背景设置为 “Windows 聚焦” 后自动恢复为 “图片”**。     | 正在调查 |
|       ——        | [**Canary - 用户反馈问题**](#1) ▲ \| ▼ [**Canary - 归档 (已做出更改 0 - 7 天)**](#2) |    ——    |
| [LG362](#LG362) |                打开 OneDrive 时桌面图标变乱。                | 已修复 ✓ |
| [LG364](#LG364) |              在小组件中滚动鼠标浏览新闻时卡住。              | 已修复 ✓ |
| [LG369](#LG369) |      Windows Sandbox 初始化失败，显示 0xc0370106 错误。      | 已修复 ✓ |
|       ——        | *部分未收录反馈详见 [WIP Canary 27863 更新简报](Canary.md)*  |    ——    |
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
版本：Canary 27686 - 27863  
**问题**：**[Copilot+ 电脑] 加入 Canary 频道后，PIN 和生物识别信息将丢失**。  
状态：<img src="Images/W.png" width = "9%" />  
Microsoft 官方回复：“如果您使用 Copilot+ 设备从 Dev、Release Preview 或 Retail 频道加入至 Canary 频道，Windows Hello PIN 和生物识别信息将会丢失。您将无法登录系统，显示 0xd0000225 错误和 ‘出错了，您的 PIN 不可用’ 信息。点击 ‘设置我的 PIN’ 选项应当可以重设 PIN。” *(Ling 译)* <img src="Images/M.png" width = "14%" />

---

<SPAN ID = 'LG342'/>编号：LG342  
日期：2025 年 4 月 26 日  
版本：Canary 27842 - 27863  
**问题**：**打开组策略编辑器时提示错误**。  
状态：<img src="Images/W.png" width = "9%" />  
典型反馈：[aka.ms/AAvskqo](https://aka.ms/AAvskqo)

<img src="Images/LG342.png" width = "50%" />

---

<SPAN ID = 'LG368'/>编号：LG368  
日期：2025 年 5 月 18 日  
版本：Canary 27858 - 27863  
**问题**：**任务栏材质效果消失，变成了深灰色**。  
状态：<img src="Images/W.png" width = "9%" />  
典型反馈：[aka.ms/AAw9ms9](https://aka.ms/AAw9ms9) & [aka.ms/AAwak57](https://aka.ms/AAwak57)

<img src="Images/LG368.png" width = "60%" />

---

<SPAN ID = 'LG374'/>编号：LG374  
日期：2025 年 5 月 20 日  
版本：Canary 27858 - 27863  
**问题**：**高采样率 (192 kHz) 设备无法播放音频**。  
状态：<img src="Images/W.png" width = "9%" />  
典型反馈：[aka.ms/AAwc9vi](https://aka.ms/AAwc9vi) <img src="Images/M.png" width = "14%" />

---

<SPAN ID = 'LG365'/>编号：LG365  
日期：2025 年 5 月 17 日  
版本：Canary 27858 - 27863  
**问题**：**手写笔无法正常使用**。  
状态：<img src="Images/W.png" width = "9%" />  
典型反馈：[aka.ms/AAwc3xq](https://aka.ms/AAwc3xq) <img src="Images/M.png" width = "14%" />

---

<SPAN ID = 'LG366'/>编号：LG366  
日期：2025 年 5 月 18 日  
版本：Canary 27858 - 27863  
**问题**：**任务管理器的搜索和筛选功能失效**。  
状态：<img src="Images/W.png" width = "9%" />  
典型反馈：[aka.ms/AAwafdz](https://aka.ms/AAwafdz) <img src="Images/M.png" width = "14%" />

<img src="Images/LG366.png" width = "50%" />

<SPAN ID = '1'/>

## Canary - 用户反馈问题

> [!TIP]
>
> &emsp;记录[反馈中心应用](https://aka.ms/fbh)中 Microsoft 明确响应的问题。

---

<SPAN ID = 'LG252'/>编号：LG252  
日期：2024 年 12 月 20 日  
版本：Canary 27764 - 27863  
**问题**：**组策略编辑器和服务管理器 UI 错误**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAty56l](https://aka.ms/AAty56l)

<img src="Images/LG252.png" width = "50%" />

---

<SPAN ID = 'LG258'/>编号：LG258  
日期：2025 年 1 月 10 日  
版本：Canary 27766 - 27863  
**问题**：**拖动表情符号面板中的滚动条时卡顿严重**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAtws2s](https://aka.ms/AAtws2s)

<img src="Images/LG258.png" width = "30%" />

---

<SPAN ID = 'LG277'/>编号：LG277  
日期：2025 年 1 月 29 日  
版本：Canary 27764 - 27863  
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
版本：Canary 27774 - 27863  
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

<SPAN ID = 'LG311'/>编号：LG311  
日期：2025 年 3 月 24 日  
版本：Canary 27818 - 27863  
**问题**：**文件资源管理器地址栏溢出列表无法正确呈现**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAv26rl](https://aka.ms/AAv26rl)

<img src="Images/LG311.png" width = "50%" />

---

<SPAN ID = 'LG323'/>编号：LG323  
日期：2025 年 4 月 3 日  
版本：Canary 27823 - 27863  
**问题**：**将鼠标悬停在 “系统信息” 菜单顶部的选项卡时，边框显示为直角**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAvc3jh](https://aka.ms/AAvc3jh)

<img src="Images/LG323.png" width = "60%" />

---

<SPAN ID = 'LG347'/>编号：LG347  
日期：2025 年 5 月 1 日  
版本：ALL  
**问题**：**满足条件后在反馈中心无法获得成就徽章**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAw0kh1](https://aka.ms/AAw0kh1)

---

<SPAN ID = 'LG348'/>编号：LG348  
日期：2025 年 5 月 4 日  
版本：ALL  
**问题**：**安装 Windows 11 时，菜单按照从右到左的方式排列**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAw2o68](https://aka.ms/AAw2o68) & [aka.ms/AAw5fk3](https://aka.ms/AAw5fk3)

<img src="Images/LG348.png" width = "40%" />

---

<SPAN ID = 'LG357'/>编号：LG357  
日期：2025 年 5 月 10 日  
版本：ALL  
**问题**：**截图工具无法截取搜索界面、上下文菜单等 UI**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAw7f38](https://aka.ms/AAw7f38)

---

<SPAN ID = 'LG361'/>编号：LG361  
日期：2025 年 5 月 15 日  
版本：ALL  
**问题**：**Microsoft Store 不显示较早的应用更新记录**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAw8czh](https://aka.ms/AAw8czh)

---

<SPAN ID = 'LG367'/>编号：LG367  
日期：2025 年 5 月 18 日  
版本：Canary 27858 - 27863  
**问题**：**安装 Canary 27858 更新时，屏幕显示白色画面**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAw9msg](https://aka.ms/AAw9msg) & [aka.ms/AAwdmg2](https://aka.ms/AAwdmg2)

<img src="Images/LG367.png" width = "45%" />

---

<SPAN ID = 'LG370'/>编号：LG370  
日期：2025 年 5 月 18 日  
版本：Canary 27858 - 27863  
**问题**：**重启 explorer.exe 时白屏**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAw9m8s](https://aka.ms/AAw9m8s)

---

<SPAN ID = 'LG371'/>编号：LG371  
日期：2025 年 5 月 18 日  
版本：Canary 27858 - 27863  
**问题**：**开启 “自动隐藏任务栏” 后出现黑边**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAwafxd](https://aka.ms/AAwafxd) & [aka.ms/AAwc9vp](https://aka.ms/AAwc9vp)

---

<SPAN ID = 'LG372'/>编号：LG372  
日期：2025 年 5 月 18 日  
版本：Canary 27858 - 27863  
**问题**：**玩 DNF 游戏时电脑绿屏**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAwal5x](https://aka.ms/AAwal5x)

---

<SPAN ID = 'LG373'/>编号：LG373  
日期：2025 年 5 月 18 日  
版本：Canary 27858 - 27863  
**问题**：**电脑 WIN32K_CRITICAL_FAILURE (0x164) 绿屏**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAwafxe](https://aka.ms/AAwafxe)

---

<SPAN ID = 'LG375'/>编号：LG375  
日期：2025 年 5 月 20 日  
版本：Canary 27858 - 27863  
**问题**：**触摸屏的双击、长按右键等操作失效**。  
状态：<img src="Images/W.png" width = "9%" />  
典型反馈：[aka.ms/AAwapbn](https://aka.ms/AAwapbn) & [aka.ms/AAwa9gh](https://aka.ms/AAwa9gh) <img src="Images/M.png" width = "14%" />

---

<SPAN ID = 'LG376'/>编号：LG376  
日期：2025 年 5 月 20 日  
版本：Canary 27858 - 27863  
**问题**：**使用 NVIDIA GeForce NOW 平台时电脑绿屏**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAwc3xt](https://aka.ms/AAwc3xt)

---

<SPAN ID = 'LG377'/>编号：LG377  
日期：2025 年 5 月 20 日  
版本：Canary 27858 - 27863  
**问题**：**红外 (IR) 摄像头无法正常工作**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAwapc6](https://aka.ms/AAwapc6)

---

<SPAN ID = 'LG378'/>编号：LG378  
日期：2025 年 5 月 20 日  
版本：ALL  
**问题**：**记事本文档中的下划线 “_” 无法正常显示**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAwcalk](https://aka.ms/AAwcalk)

---

<SPAN ID = 'LG379'/>编号：LG379  
日期：2025 年 5 月 26 日  
版本：ALL  
**问题**：**Microsoft Store 最小化时，无法右键任务栏图标将其关闭**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAwd8s4](https://aka.ms/AAwd8s4)

---

<SPAN ID = 'LG380'/>编号：LG380  
日期：2025 年 5 月 26 日  
版本：ALL  
**问题**：**使用 “照片” 应用裁剪图片后，保存时屏幕会闪烁一下**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAw9alj](https://aka.ms/AAw9alj)

---

<SPAN ID = 'LG381'/>编号：LG381  
日期：2025 年 5 月 26 日  
版本：Canary 27863  
**问题**：**玩 PUBG 游戏时电脑自动重启**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAwd8az](https://aka.ms/AAwd8az)

---

<SPAN ID = 'LG382'/>编号：LG382  
日期：2025 年 5 月 26 日  
版本：Canary 27863  
**问题**：**微信输入法候选框周围出现黑粗边框**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAwdlyb](https://aka.ms/AAwdlyb)

---

<SPAN ID = 'LG383'/>编号：LG383  
日期：2025 年 5 月 26 日  
版本：Canary 27863  
**问题**：**开启 “管理员保护” 功能并以管理员身份运行终端时，UAC 对话框死锁**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAwdmg7](https://aka.ms/AAwdmg7)

---

<SPAN ID = 'LG384'/>编号：LG384  
日期：2025 年 5 月 26 日  
版本：ALL  
**问题**：**将背景设置为 “Windows 聚焦” 后自动恢复为 “图片”**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAwe72g](https://aka.ms/AAwe72g)

<SPAN ID = '2'/>

## Canary - 归档 (已做出更改)

> [!TIP]
>
> &emsp;记录 Microsoft 已做出更改 0 - 7 天的问题 & 超过 14 天无新增赞成票的问题。
>
> &emsp;无特殊情况，问题归档后不再更新。

---

<SPAN ID = 'LG362'/>编号：LG362  
日期：2025 年 5 月 15 日  
版本：Canary 27842 - 27858  
**问题**：**打开 OneDrive 时桌面图标变乱**。  
状态：Canary 27863 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAw9dni](https://aka.ms/AAw9dni)

---

<SPAN ID = 'LG364'/>编号：LG364  
日期：2025 年 5 月 15 日  
版本：Canary 27842 - 27858  
**问题**：**在小组件中滚动鼠标浏览新闻时卡住**。  
状态：Canary 27863 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAw9hur](https://aka.ms/AAw9hur)

---

<SPAN ID = 'LG369'/>编号：LG369  
日期：2025 年 5 月 18 日  
版本：Canary 27858  
**问题**：**Windows Sandbox 初始化失败，显示 0xc0370106 错误**。  
状态：Canary 27863 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAw9m8q](https://aka.ms/AAw9m8q)

---

*部分未收录反馈详见 [WIP Canary 27863 更新简报](Canary.md)*

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

2023 - 2025, [高楷修 (Ling Gao)](https://github.com/Lingggao), 灵糕中心 (Linggao Hub), [github.com/Lingggao/LGHUB](https://github.com/Lingggao/LGHUB)

[字体许可使用授权书](Images/字体许可使用授权书.png) | [Windows Insider 最有价值专家](https://github.com/Lingggao/LGHUB/blob/main/Images/Windows%20Insider%20MVP.png?raw=true)