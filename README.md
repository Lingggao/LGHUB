<SPAN ID = 'HEAD'/>

<div align="center">
<img src="Images/LING_1.png" width = "25%" /> <img src="Images/MCC2024.png" width = "12%" />
</div>


<h1 align="center">灵糕中心 (Linggao Hub)</h1>

[github.com/Lingggao/LGHUB](https://github.com/Lingggao/LGHUB) (GitHub) & [lingggao.github.io/LGHUB](https://lingggao.github.io/LGHUB) (Pages)

&emsp;&emsp;用于跟踪 “**Windows 11 预览体验版本 (Canary 频道) 哪些反馈正在由 Microsoft 调查 / 处理 / 已做出更改**” 的信息枢纽。由 2021 Windows Insider Most Valuable Professional (MVP) · **Ling Gao** 先生管理。

> &emsp;**声明**：灵糕中心为个人项目，管理者不是 Microsoft 公司员工，不能代表 Microsoft 公司立场、态度。中心无意且无法代替 “反馈中心” (Feedback Hub) 应用的重要作用。中心不提供 Microsoft 产品技术支持服务。中心不接受有关 Windows 11 预览体验版本的反馈，用户应始终通过 “反馈中心” 应用提交。

> &emsp;Windows、Windows Insider Program 等是 Microsoft 公司的商标。

&emsp;&emsp;**宗旨**：独立管理、服务用户、信息精准、更新及时

[反馈中心](https://aka.ms/fbh) | [深入了解反馈](https://learn.microsoft.com/zh-cn/windows-insider/feedback) | [Flight Hub](https://learn.microsoft.com/en-us/windows-insider/flight-hub) | Windows 预览体验计划 - [网站](https://www.microsoft.com/zh-cn/windowsinsider) · [博客](https://blogs.windows.com/windows-insider) · [X (Twitter)](https://twitter.com/windowsinsider) · [社区](https://answers.microsoft.com/zh-hans/insider/forum)

## ✦ 总览 ✦

&emsp;&emsp;上次更新时间：2024 年 3 月 23 日 14:00 (UTC+8)。访问次数：1980+

&emsp;&emsp;收录反馈 129 个，其中正在调查 10 个、正在处理 5 个、已修复 114 个。

&emsp;&emsp;反馈更新目录：**今日更新 LG127 - 128**。- Ling 🐕 [总览图](https://raw.githubusercontent.com/Lingggao/LGHUB/main/Images/Linggao%20Hub.png) | [已修复图](https://raw.githubusercontent.com/Lingggao/LGHUB/main/Images/Linggao%20Hub_Fixed.png)

|     频道     |  最新版本  | 时间 (UTC+8) |                             公告                             |
| :----------: | :--------: | :----------: | :----------------------------------------------------------: |
| Canary & Dev |   26085    |  2024/3/21   | [aka.ms/wip26085](https://blogs.windows.com/windows-insider/2024/03/20/announcing-windows-11-insider-preview-build-26085-canary-and-dev-channels) |
|     Beta     | 22635.3350 |  2024/3/14   | [aka.ms/wip-beta-3-13](https://blogs.windows.com/windows-insider/2024/03/13/announcing-windows-11-insider-preview-build-22635-3350-beta-channel) |

<img src="Images/Graph_1.png" width = "88%" />

|      编号       |                             问题                             |   状态   |
| :-------------: | :----------------------------------------------------------: | :------: |
| [LG069](#LG069) |    安装 Canary 版本时可能自动回退，错误代码 0xC1900101。     | 正在处理 |
| [LG115](#LG115) |                右键菜单变为 Windows 10 样式。                | 正在处理 |
|     **——**      | [**Canary - 公告已知问题**](#0) **▲ \| ▼** [**Canary - 用户反馈问题**](#1) |  **——**  |
| [LG013](#LG013) |           “设置”>“应用”>“启动” 页面中的图标异常。            | 正在调查 |
| [LG015](#LG015) |      在文件资源管理器中按下两次 F11 后地址栏将被冻结。       | 正在调查 |
| [LG088](#LG088) |       无法使用截图工具对开始菜单 / 右键菜单进行截图。        | 正在调查 |
| [LG111](#LG111) |  **[合并]** 任务视图 / 文件资源管理器卡顿或 CPU 占用率高。   | 正在处理 |
| [LGH01](#LGH01) | **[集合]** 仍有几款游戏在 Build 26080 中无法正常运行。(含列表) | 正在处理 |
| [LG122](#LG122) |                      Copilot 功能消失。                      | 正在调查 |
| [LG123](#LG123) |                 接收不到 Build 26080+ 更新。                 | 正在调查 |
| [LG125](#LG125) |         电脑风扇负荷更重 / 温度更高 / 电池续航更短。         | 正在调查 |
| [LG116](#LG116) |                  电脑无法正常关机 / 睡眠。                   | 正在处理 |
| [LG117](#LG117) |                任务栏应用缩略图无法正常显示。                | 正在调查 |
| [LG126](#LG126) |                Surface 设备的摄像头可能失效。                | 正在调查 |
| [LG127](#LG127) |                **在手写板上写字时文字错位**。                | 正在调查 |
| [LG128](#LG128) |            **SteelSeries 耳机软件无法正常使用**。            | 正在调查 |
|     **——**      | [**Canary - 用户反馈问题**](#1) **▲ \| ▼** [**Canary - 归档 (已做出更改 0 - 28 天)**](#2) |  **——**  |
| [LG030](#LG030) | **在 Microsoft Store 中下载 Xbox Identity Provider 时显示 0x80073CFB 错误**。 | 已修复 ✓ |
|     **——**      |     ✦ [**Canary - 归档 (已做出更改 >28 天)**](28+.md) ✦      |  **——**  |

[**希望分享线索？联系 Ling。**](https://forms.office.com/Pages/ResponsePage.aspx?id=DQSIkWdsW0yxEjajBLZtrQAAAAAAAAAAAAO__Q3sH7RUNjUyUzJLN0JBREZGMzBBVlpVOEVBQkRENy4u) | [**反馈平台问题？联系 Ling。**](https://forms.office.com/Pages/ResponsePage.aspx?id=DQSIkWdsW0yxEjajBLZtrQAAAAAAAAAAAAO__Q3sH7RUQ0haOElMVkxOWDE4U1pHQUZWMDhEM1gwSC4u)

---

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

[反馈更新记录](Documents/Update_Feedback.md) | [平台更新记录](Documents/Update_Platform.md)

<SPAN ID = '0'/>

## ✦ Canary - 公告已知问题 ✦

&emsp;&emsp;记录 [Windows Insider 博客](https://blogs.windows.com/windows-insider)中明确公开的已知问题。

---

<SPAN ID = 'LG069'/>编号：LG069  
版本：Canary 26058 - 26085  
**问题**：**安装 Canary 版本时可能自动回退，错误代码 0xC1900101**。  
状态：<img src="Images/W.png" width = "10%" />  
Microsoft 官方回复：“我们做了很多更改以帮助缓解回退现象，并将继续调查用户反馈。” *(Ling 译)*  
 <img src="Images/M.png" width = "15%" />

---

<SPAN ID = 'LG115'/>编号：LG115  
版本：Canary 26080 - 26085  
**问题**：**右键菜单变为 Windows 10 样式**。  
状态：<img src="Images/W.png" width = "10%" />  
典型反馈：[aka.ms/AApjkju](https://aka.ms/AApjkju) <img src="Images/M.png" width = "15%" />

<SPAN ID = '1'/>

## ✦ Canary - 用户反馈问题 ✦

&emsp;&emsp;记录[反馈中心应用](https://aka.ms/fbh)中 Microsoft 明确响应的问题。

---

<SPAN ID = 'LG013'/>编号：LG013  
版本：Canary 26002 - 26085  
**问题**：**“设置”>“应用”>“启动” 页面中的图标异常**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAo5wd6](https://aka.ms/AAo5wd6)

<img src="Images/LG013.png" width = "50%" />

---

<SPAN ID = 'LG015'/>编号：LG015  
版本：Canary 25992 - 26085  
**问题**：**在文件资源管理器中按下两次 F11 后地址栏将被冻结**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAnkkd6](https://aka.ms/AAnkkd6)

---

<SPAN ID = 'LG088'/>编号：LG088  
版本：ALL  
**问题**：**无法使用截图工具对开始菜单 / 右键菜单进行截图**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAp5evo](https://aka.ms/AAp5evo)

---

<SPAN ID = 'LG111'/>编号：LG111  
版本：Canary 26063 - 26085  
**问题**：**任务视图 / 文件资源管理器卡顿或 CPU 占用率高**。  
状态：<img src="Images/W.png" width = "10%" />  
典型反馈：[aka.ms/AAph34g](https://aka.ms/AAph34g)

---

<SPAN ID = 'LGH01'/>编号：LGH01  
版本：Canary 26080 - 26085  
**集合**：**仍有几款游戏在 Build 26080 中无法正常运行**。  
状态： <img src="Images/W.png" width = "10%" />  
Microsoft 官方回复：“大多数游戏应当可以在 Build 26080 中恢复正常运行。如果您在预览体验版本中玩游戏时发现任何问题，请务必在反馈中心提交。” *(Ling 译)* <img src="Images/M.png" width = "15%" />

列表 (排名不分先后)

- Grand Theft Auto V (GTA 5) - [aka.ms/AApjkjp](https://aka.ms/AApjkjp)
- PUBG (绝地求生) - [aka.ms/AApjd7p](https://aka.ms/AApjd7p)
- Battlefield 2042 (战地风云 2042) - [aka.ms/AApjkk7](https://aka.ms/AApjkk7)
- EVE Online (星战前夜) - [aka.ms/AApjz1t](https://aka.ms/AApjz1t)
- Avatar Frontiers of Pandora (阿凡达：潘多拉边境) - [aka.ms/AApmqnc](https://aka.ms/AApmqnc)
- Assassin's Creed Origins (刺客信条：起源) - [aka.ms/AApmqnc](https://aka.ms/AApmqnc)

---

<SPAN ID = 'LG122'/>编号：LG122  
版本：Canary 26080 - 26085  
**问题**：**Copilot 功能消失**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AApmcet](https://aka.ms/AApmcet)

---

<SPAN ID = 'LG123'/>编号：LG123  
版本：Canary  
**问题**：**接收不到 Build 26080+ 更新**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AApjbci](https://aka.ms/AApjbci)

---

<SPAN ID = 'LG125'/>编号：LG125  
版本：Canary 26080 - 26085  
**问题**：**电脑风扇负荷更重 / 温度更高 / 电池续航更短**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AApmnl6](https://aka.ms/AApmnl6)

---

<SPAN ID = 'LG116'/>编号：LG116  
版本：Canary 26080 - 26085  
**问题**：**电脑无法正常关机 / 睡眠**。  
状态：<img src="Images/W.png" width = "10%" />  
Microsoft 官方回复：“不幸的是，我们看到一些反馈称 Build 26085 版本中仍然存在这一问题。我们正在调查中，请暂时使用 shutdown -t 0 -s 命令关机。” *(Ling 译)* <img src="Images/M.png" width = "15%" />  
典型反馈：[aka.ms/AApjd80](https://aka.ms/AApjd80)

---

<SPAN ID = 'LG117'/>编号：LG117  
版本：Canary 26080 - 26085  
**问题**：**任务栏应用缩略图无法正常显示**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AApjd83](https://aka.ms/AApjd83)

---

<SPAN ID = 'LG126'/>编号：LG126  
版本：Canary 26085  
**问题**：**Surface 设备的摄像头可能失效**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AApno2g](https://aka.ms/AApno2g)

---

<SPAN ID = 'LG127'/>编号：LG127  
版本：Canary 26085  
**问题**：**在手写板上写字时文字错位**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AApnq5x](https://aka.ms/AApnq5x)

---

<SPAN ID = 'LG128'/>编号：LG128  
版本：Canary 26085  
**问题**：**SteelSeries 耳机软件无法正常使用**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AApoga9](https://aka.ms/AApoga9)

<SPAN ID = '2'/>

## ✦ Canary - 归档 (已做出更改) ✦

&emsp;&emsp;记录 Microsoft 已做出更改 0 - 28 天的问题 & 超过 30 日无新增赞成票的问题。

&emsp;&emsp;无特殊情况，问题归档后不再更新。

---

<SPAN ID = 'LG030'/>编号：LG030  
版本：Canary  
**问题**：**在 Microsoft Store 中下载 Xbox Identity Provider 时显示 0x80073CFB 错误**。  
状态：Canary - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAlzfg7](https://aka.ms/AAlzfg7)

[Microsoft 已做出更改 >28 天的问题](28+.md)

---

[回到顶部](#HEAD)

<img src="https://mirrors.creativecommons.org/presskit/icons/cc.xlarge.png" width = "3%" /> <img src="https://mirrors.creativecommons.org/presskit/icons/by.xlarge.png" width = "3%" /> <img src="https://mirrors.creativecommons.org/presskit/icons/sa.xlarge.png" width = "3%" />

在 “[署名 - 相同方式共享 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode.zh-Hans)” 协议 (CC BY-SA 4.0) 之条款下提供。

2023 - 2024, 高楷修 (Ling Gao), 灵糕中心 (Linggao Hub), [github.com/Lingggao/LGHUB](https://github.com/Lingggao/LGHUB)

[字体许可使用授权书](Images/字体许可使用授权书.png) | [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FLingggao%2FLGHUB&count_bg=%23737373&title_bg=%230078D7&icon=microsoft.svg&icon_color=%23FFFFFF&title=LGHUB&edge_flat=false)](https://hits.seeyoufarm.com) (访问次数统计：今日 / 累计)