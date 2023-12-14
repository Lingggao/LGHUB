<img src="Images/LING.png" width = "25%" />

# 灵糕中心 (Linggao Hub)

[github.com/Lingggao/LGHUB](https://github.com/Lingggao/LGHUB)

&emsp;&emsp;用于跟踪 “**Windows 11 预览体验版本 (Canary 频道) 哪些反馈正在由 Microsoft 调查 / 处理 / 已做出更改**” 的信息枢纽。由 2021 Windows Insider Most Valuable Professional (MVP) · **Ling Gao** 先生管理。

> &emsp;**声明**：灵糕中心的管理者不是 Microsoft 公司全职员工 (FTE)，不能代表 Microsoft 公司立场、态度。中心无意且无法代替 “反馈中心” (Feedback Hub) 应用的重要作用。中心不提供 Microsoft 产品技术支持服务。中心不接受有关 Windows 11 预览体验版本的反馈，用户应始终通过 “反馈中心” 应用提交。

> &emsp;Windows、Windows Insider Program 等是 Microsoft 公司的商标。

&emsp;&emsp;**宗旨**：独立管理、服务用户、信息精准、更新及时。

[反馈中心](https://aka.ms/fbh) | [深入了解反馈](https://learn.microsoft.com/zh-cn/windows-insider/feedback) | [Flight Hub](https://learn.microsoft.com/en-us/windows-insider/flight-hub) | Windows 预览体验计划 - [网站](https://www.microsoft.com/zh-cn/windowsinsider) · [博客](https://blogs.windows.com/windows-insider) · [X (Twitter)](https://twitter.com/windowsinsider) · [社区](https://answers.microsoft.com/zh-hans/insider/forum)

## 外部测试版

|  频道  |  最新版本  |    时间    |                         公告                         |
| :----: | :--------: | :--------: | :--------------------------------------------------: |
| Canary |   26016    | 2023/12/14 |      [aka.ms/WIP26016](https://aka.ms/WIP26016)      |
|  Dev   |   23606    | 2023/12/14 |      [aka.ms/WIP23606](https://aka.ms/WIP23606)      |
|  Beta  | 22635.2850 | 2023/12/09 | [aka.ms/WIP-Beta-12-8](https://aka.ms/WIP-Beta-12-8) |

**标准格式**

编号：LGxxx  
版本：Canary xxxxx  
**问题**：**xxxxx**  
状态：正在调查 / 正在处理 / 需要更多详细信息 / 所做的更改 / (其他)  
Microsoft 官方回复 (如果有)：xxxxx  
典型反馈 (如果有)：[aka.ms/AAxxxxx](https://aka.ms/fbh)  
图像等补充信息 (如果有)    

## Canary - 公告已知问题

&emsp;&emsp;记录 [Windows Insider 博客](https://blogs.windows.com/windows-insider)中明确公开的已知问题。

---

编号：LG000  
版本：Canary 26016  
**问题**：**无法下载 Build 26016 更新，显示 8024200D 错误**。  
状态：<img src="Images/W.png" width = "10%" />  
Microsoft 官方回复：“部分 Insiders 可能遇到 ‘下载循环’，即 Build 26016 更新多次下载后出现 8024200D 错误。通常第 4 次尝试时可以成功下载并安装。我们正在积极监控中。” *(Ling 译)* <img src="Images/M.png" width = "15%" />

---

编号：LG001  
版本：Canary 26010 - 26016  
**问题**：**无法打开设置菜单 / 设置菜单崩溃**。  
状态：<img src="Images/L.png" width = "10%" />  
Microsoft 官方回复：“我们正在调查导致部分 Insiders 无法打开 ‘设置’ 菜单的问题。如果您正在受此影响，请查看下面的社区话题了解解决方案。” *(Ling 译)* <img src="Images/M.png" width = "15%" />

[临时解决方案](https://aka.ms/26010SettingsCrash) *(Jason Howard 整理)*

---

编号：LG002  
版本：Canary 25951 - 26016  
**问题**：**部分热门游戏可能无法正常运行**。  
状态：<img src="Images/I.png" width = "17%" />  
Microsoft 官方回复：“如果您在预览体验版本中玩游戏时发现任何问题，请务必在反馈中心提交。” *(Ling 译)*  
<img src="Images/M.png" width = "15%" />

---

编号：LG003  
版本：Canary 26016  
**问题**：**点击 “设置”>“系统”>“电源” 时菜单崩溃**。  
状态：<img src="Images/W.png" width = "10%" />  
Microsoft 官方回复：“您可以使用命令在电脑上配置电源模式，作为一种变通方案。使用 powercfg /overlaysetactive 设置用户配置的活动电源模式，使用 powercfg /q OVERLAY_SCHEME_CURRENT 获取用户配置的活动电源模式。查看下面的网站详细了解 powercfg。” *(Ling 译)* <img src="Images/M.png" width = "15%" />

[自定义 Windows 性能电源滑块](https://learn.microsoft.com/windows-hardware/customize/desktop/customize-power-slider) *(Microsoft Learn)*

---

编号：LG004  
版本：Canary 26010 - 26016  
**问题**：**打开打印队列时提示 “找不到应用程序”**。  
状态：<img src="Images/L.png" width = "10%" />  

## Canary - 用户反馈

&emsp;&emsp;记录[反馈中心应用](https://aka.ms/fbh)中 Microsoft 明确响应的问题。

---

//  
//  
//  

---

//  
//  
//  

## Canary - 归档 (已做出更改 >14 天)

&emsp;&emsp;记录 Microsoft 已做出更改 14 - 28 天的问题。

[Microsoft 已做出更改 >28 天的问题](28+.md)

---

//  
//  
//  

---

//  
//  
//  

---

[回到顶部](https://github.com/Lingggao/LGHUB#%E7%81%B5%E7%B3%95%E4%B8%AD%E5%BF%83-linggao-hub)

<img src="https://mirrors.creativecommons.org/presskit/icons/cc.xlarge.png" width = "3%" /> <img src="https://mirrors.creativecommons.org/presskit/icons/by.xlarge.png" width = "3%" /> <img src="https://mirrors.creativecommons.org/presskit/icons/sa.xlarge.png" width = "3%" />

在 “[署名 - 相同方式共享 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode.zh-Hans)” 协议 (CC BY-SA 4.0) 之条款下提供。

2023, 高楷修 (Ling Gao), 灵糕中心 (Linggao Hub), [github.com/Lingggao/LGHUB](https://github.com/Lingggao/LGHUB)