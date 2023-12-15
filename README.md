<img src="Images/LING.png" width = "25%" />

# 灵糕中心 (Linggao Hub)

[github.com/Lingggao/LGHUB](https://github.com/Lingggao/LGHUB)

&emsp;&emsp;用于跟踪 “**Windows 11 预览体验版本 (Canary 频道) 哪些反馈正在由 Microsoft 调查 / 处理 / 已做出更改**” 的信息枢纽。由 2021 Windows Insider Most Valuable Professional (MVP) · **Ling Gao** 先生管理。

> &emsp;**声明**：灵糕中心的管理者不是 Microsoft 公司全职员工 (FTE)，不能代表 Microsoft 公司立场、态度。中心无意且无法代替 “反馈中心” (Feedback Hub) 应用的重要作用。中心不提供 Microsoft 产品技术支持服务。中心不接受有关 Windows 11 预览体验版本的反馈，用户应始终通过 “反馈中心” 应用提交。

> &emsp;Windows、Windows Insider Program 等是 Microsoft 公司的商标。

&emsp;&emsp;**宗旨**：独立管理、服务用户、信息精准、更新及时。

&emsp;&emsp;上次更新时间：2023 年 12 月 15 日，记录的反馈数量：18

[反馈中心](https://aka.ms/fbh) | [深入了解反馈](https://learn.microsoft.com/zh-cn/windows-insider/feedback) | [Flight Hub](https://learn.microsoft.com/en-us/windows-insider/flight-hub) | Windows 预览体验计划 - [网站](https://www.microsoft.com/zh-cn/windowsinsider) · [博客](https://blogs.windows.com/windows-insider) · [X (Twitter)](https://twitter.com/windowsinsider) · [社区](https://answers.microsoft.com/zh-hans/insider/forum)

## 外部测试版

|  频道  |  最新版本  |    时间    |                          公告                          |
| :----: | :--------: | :--------: | :----------------------------------------------------: |
| Canary |   26016    | 2023/12/14 |       [aka.ms/WIP26016](https://aka.ms/WIP26016)       |
|  Dev   |   23606    | 2023/12/14 |       [aka.ms/WIP23606](https://aka.ms/WIP23606)       |
|  Beta  | 22635.2915 | 2023/12/15 | [aka.ms/WIP-Beta-12-14](https://aka.ms/wip-beta-12-14) |

**标准格式**

```markdown
编号：LGxxx  
版本：Canary xxxxx  
**问题**：**xxxxx**  
状态：正在调查 / 正在处理 / 需要更多详细信息 / 所做的更改 / (其他)  
Microsoft 官方回复 (如果有)：xxxxx  
典型反馈 (如果有)：[aka.ms/AAxxxxx](https://aka.ms/fbh)  
图像等补充信息 (如果有)
```

## 一、Canary - 公告已知问题

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

---

编号：LG005  
版本：Canary 26010  
**问题**：**Windows RE (恢复环境) 无法正确呈现**。  
状态：Canary 26016 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓

---

编号：LG006  
版本：Canary 26002 - 26010  
**问题**：**无法在桌面上使用 Ctrl 快捷键、Alt + F4 快捷键、Del 删除键**。  
状态：Canary 26016 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
Microsoft 官方回复：“如果您需要操作桌面文件，请暂时访问文件资源管理器中的 ‘桌面’ 文件夹。导致三种按键失效的根本原因一致，我们已经确认原因并将其在 Build 26016 中修复。” *(Ling 译)* <img src="Images/M.png" width = "15%" />  
典型反馈：[aka.ms/AAo73hv](https://aka.ms/AAo73hv)

## 二、Canary - 用户反馈

&emsp;&emsp;记录[反馈中心应用](https://aka.ms/fbh)中 Microsoft 明确响应的问题。

---

编号：LG007  
版本：ALL - Canary 26016  
**问题**：**切换桌面时任务栏应用图标可能随机消失**。  
状态：<img src="Images/L.png" width = "10%" />  
Microsoft 官方回复：“我们在 Dev 频道中对此进行了修复，正在持续调查有关此问题的报告。” *(Ling 译)*  
<img src="Images/M.png" width = "15%" />  
典型反馈：[aka.ms/AAo73ko](https://aka.ms/AAo73ko)

<img src="Images/LG007.png" width = "50%" />

---

编号：LG008  
版本：Canary 26002 - 26016  
**问题**：**“Wallpaper Engine：壁纸引擎” 软件崩溃**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAnwevt](https://aka.ms/AAnwevt)

---

编号：LG009  
版本：ALL  
**问题**：**通过快捷键截图后无法直接打开图片**。  
状态：截图工具 11.2310.54.0 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
Microsoft 官方回复：“Snipping 工作人员已完成调查，并在 11.2310.54.0 版本中包含了修复程序。如果您在使用此版本 (或更高版本) 时仍然遇到问题，请立即提交新的反馈。” *(Ling 译)* <img src="Images/M.png" width = "15%" />  
典型反馈：[aka.ms/AAo7jbd](https://aka.ms/AAo7jbd)

---

编号：LG010  
版本：Canary 26010 - 26016  
**问题**：**任务栏 “快速设置” 中滑块颜色异常**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAo74l5](https://aka.ms/AAo74l5)

<img src="Images/LG010.png" width = "25%" />

---

编号：LG011  
版本：Canary 26002 - 26016  
**问题**：**无法通过任务栏 “快速设置” 导航至 “节能模式” 菜单**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAo74m3](https://aka.ms/AAo74m3)

<img src="Images/LG011.png" width = "25%" />

---

编号：LG012  
版本：ALL  
**问题**：**截图工具的 “设置” 页面存在中文语法错误**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAo6pkw](https://aka.ms/AAo6pkw)

<img src="Images/LG012.png" width = "50%" />

---

编号：LG013  
版本：Canary 26002 - 26016  
**问题**：**“设置”>“应用”>“启动” 页面中的图标异常**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAo5wd6](https://aka.ms/AAo5wd6)

<img src="Images/LG013.png" width = "50%" />

---

编号：LG014  
版本：Canary 25997 - 26002  
**问题**：**在文件资源管理器中打开上下文菜单时崩溃 / 显示为旧版样式**。  
状态：Canary 26010 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
Microsoft 官方回复：“此问题应当已经在 Canary 频道 Build 26010 中得到修复。如果您在更新后仍然遇到问题，请立即提交新的反馈。” *(Ling 译)* <img src="Images/M.png" width = "15%" />  
典型反馈：[aka.ms/AAnslj4](https://aka.ms/AAnslj4)

---

编号：LG015  
版本：Canary 25992 - 26016  
**问题**：**在文件资源管理器中按下两次 F11 后地址栏将被冻结**。  
状态：<img src="Images/L.png" width = "10%" />  
典型反馈：[aka.ms/AAnkkd6](https://aka.ms/AAnkkd6)

---

编号：LG016  
版本：ALL - Canary 25992  
**问题**：**文件资源管理器中 Filter 功能被错误地翻译为 “滤镜”**。  
状态：Canary 25997 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAo5wfq](https://aka.ms/AAo5wfq)

---

编号：LG017  
版本：ALL  
**问题**：**反馈中心无法在中国大陆网络环境中使用**。  
状态：2023 年 10 月 20 日 - <img src="Images/C_0.png" width = "12%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAo6pov](https://aka.ms/AAo6pov)

<img src="Images/LG017.png" width = "40%" />

---

占  
位  
符

## 三、Canary - 归档 (已做出更改 >14 天)

&emsp;&emsp;记录 Microsoft 已做出更改 14 - 28 天的问题。无特殊情况，问题归档后不再更新。

[Microsoft 已做出更改 >28 天的问题](28+.md)

---

占  
位  
符

---

占  
位  
符

---

[回到顶部](https://github.com/Lingggao/LGHUB#%E7%81%B5%E7%B3%95%E4%B8%AD%E5%BF%83-linggao-hub)

<img src="https://mirrors.creativecommons.org/presskit/icons/cc.xlarge.png" width = "3%" /> <img src="https://mirrors.creativecommons.org/presskit/icons/by.xlarge.png" width = "3%" /> <img src="https://mirrors.creativecommons.org/presskit/icons/sa.xlarge.png" width = "3%" />

在 “[署名 - 相同方式共享 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode.zh-Hans)” 协议 (CC BY-SA 4.0) 之条款下提供。

2023, 高楷修 (Ling Gao), 灵糕中心 (Linggao Hub), [github.com/Lingggao/LGHUB](https://github.com/Lingggao/LGHUB)