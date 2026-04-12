# 改善您的 Windows Insider 体验

> 原文：[***Improving your Windows Insider experience***](https://blogs.windows.com/windows-insider/2026/04/10/improving-your-windows-insider-experience)  
> 作者：Alec Oot 与 Windows 预览体验计划团队  
> 译者：Ling Gao  
> 日期：2026 年 4 月 10 日

各位 Windows 预览体验成员，大家好，

上个月，Pavan 分享了我们致力于[提升 Windows 质量的承诺]()，重点聚焦性能、可靠性和匠心工艺，同时也包括为让 Windows 预览体验计划更简单、更透明而做出的一些调整。今天，我们将具体说明这些调整的内容。

在过去的几个月里，我们一直与 Windows Insider 社区保持直接互动：无论是在我们首次举办的线下见面会、通过反馈中心、在社交媒体上，还是在与你们许多人的线下一对一交流中。有两点反馈非常明确。

首先，频道结构令人困惑。大家不清楚该根据自己期望从计划中获得什么来选择哪个频道。

其次，大家在我们的博客上读到某项新功能，更新了电脑，却发现它根本不在那里。这种宣布了新功能，却因我们逐步推送的机制，导致只有部分人能收到的体验，是我们听到的最令人感到挫败的一点。

以下是我们针对这些问题正在采取的措施。

## 更清晰的频道定义

为了简化您的 Insider 体验，我们将转向两个主要频道，并提供在其中选择特定 Windows 核心版本的高级选项。这两个新频道分别是 Experimental 和 Beta。

**Experimental** 取代了之前的 Dev 和 Canary 频道。这个名字是经过深思熟虑的：您将尽早体验到正在积极开发中的功能，同时也需要理解，**您所看到的这些内容可能会发生变化、被推迟，甚至最终根本不会发布**。我们听到了大家的反馈，即你们希望在开发早期就能体验新功能并为其做出贡献，而这就是实现这一目标的专属频道。

**Beta** 是之前 Beta 频道的更新版本，主要预览我们计划在未来几周内发布的内容。**最大的改变是：我们将在 Beta 中取消渐进式功能推送**。当我们在 Beta 更新中宣布了一项功能，只要您安装了该更新，您就会获得该功能。在我们测试不同变体时，您可能偶尔会看到一项功能内部存在微小差异，但该功能本身将始终存在于您的设备上。

如果您不确定该选择哪一个：Experimental 通常是新功能首先亮相的地方，在这里您的反馈对我们的开发有着最直接的影响。如果您希望获得更稳定的体验以及更接近正式发布的功能，那么 Beta 会是更好的选择。

<img src="https://github.com/Lingggao/LGHUB/blob/main/Images/Improving%20your%20Windows%20Insider%20experience_1.png?raw=true" width = "60%" />

> 全新更新的 Windows 预览体验计划设置界面，显示了新的 Experimental 和 Beta 频道

对于大多数预览体验成员来说，选择 Beta 或 Experimental 频道就足以完成设置了，但对于那些希望进行更深入探索的用户，我们增加了一个高级选项，让您可以选择与您的硬件兼容的 Windows 核心版本。大多数用户将会看到这些选项显示为 25H2 或 26H1 版本。

Experimental 频道还将包含一个更深入的 Future Platforms 选项，这是我们针对 Windows 提供的最早期的预览版本，且不与 Windows 的零售版本对齐。这主要面向那些希望站在平台开发最前沿的用户。希望最早体验到各项功能的预览体验成员应保持使用与零售版本对齐的版本。

<img src="https://github.com/Lingggao/LGHUB/blob/main/Images/Improving%20your%20Windows%20Insider%20experience_2.png?raw=true" width = "60%" />

> 显示选择 Windows 核心版本的高级设置

**Release Preview** 将继续作为一个高级选项，面向商业客户以及那些希望在全面发布前的几天内抢先体验生产版本的预览体验成员。要选择 Release Preview，您需要在 “高级选项” 中启用它，但其内容保持不变。我们正在积极与商业预览体验成员探讨如何对其进行改进，我们也期待听到您的建议。

## 加强对渐进式推送的控制

我们从预览体验成员那里收到的最常见的问题之一就是：“为什么我无法使用 WIP 博客中已经宣布的功能？” 这通常是由于一种名为 “受控功能推出” (CFR) 的技术所致。这是一个逐步推出新功能的过程，旨在确保在向更广泛的受众发布之前保证质量。这种渐进式推送是行业标准，有助于我们在广泛发布之前衡量其影响。但这也会使您的体验变得不可预测，通常意味着您无法获得那些最初促使您加入预览体验计划的新功能。

为了解决这个问题，除了终止 Beta 频道的渐进式功能推送之外，**Experimental 频道的预览体验成员还将获得一项新功能**，即可以通过 Windows 预览体验计划设置页面中新增的 **“Feature flags” 页面**来启用或禁用特定功能。

我们将首先为 WIP 中宣布的显著新功能启用 Feature flags。这意味着 WIP 中宣布的那些不太明显的更改 (如错误修复和系统改进) 可能不会出现在 Feature flags 中。随着我们推出这项功能，请针对您希望在 Feature flags 页面上看到的新功能类型提供反馈。

<img src="https://github.com/Lingggao/LGHUB/blob/main/Images/Improving%20your%20Windows%20Insider%20experience_3.png?raw=true" width = "60%" />

> 设置中新增的 Feature flags 界面

## 在频道之间切换及退出 WIP 变得更加容易

根据您当前所在的频道，退出 Windows 预览体验计划，甚至在频道之间切换，有时可能需要擦除设备并全新安装 Windows。这对考虑加入该计划的人员以及想要退出的预览体验成员来说，都可能是一个阻碍。

为了提供更流畅且一致的体验，我们正在后台进行一些更改，使预览体验版本能够使用就地升级 (IPU) 在版本之间跳转。在大多数情况下，这将允许预览体验成员在 Experimental、Beta 和 Release Preview 之间切换，或者在无需全新安装的情况下退出该计划。IPU 会比常规更新多花一点时间，但会在原位迁移您的应用、设置和数据。

由于 Experimental 的 Future Platforms 是我们最早期的预览版本选项，且不与 Windows 的零售生产版本对齐，因此切换到不同的频道或退出 WIP 计划仍将需要进行全新安装。

最后，我们还重新设计了 Windows 预览体验计划设置页面，使其加载速度显著提升，布局更加简洁，旨在让您的选择更加清晰，同时减少重启次数和额外步骤。

## 这对您意味着什么？

我们很高兴在接下来的几周内开始推出这些更改，首先面向的是你们 —— 我们的预览体验成员。

发布时，所有预览体验成员 (Release Preview 除外) 都将被迁移至新的 Beta 或 Experimental 频道。这仅会改变您所属的频道，不会改变您的 Windows 版本。对于大多数预览体验成员，即当前处于 Beta 和 Dev 频道的成员，向新频道的过渡方式如下：

- Beta 频道 > Beta
- Dev 频道 > Experimental

当前处于 Canary 频道的预览体验成员，也将根据与其 Windows 核心版本相关的特定版本，被迁移至 Experimental 频道。这两个特定版本是 Future Platforms 和 26H1，过渡方式如下：

- Canary 频道 29500 系列版本 > Experimental (Future Platforms)
- Canary 频道 28000 系列版本 > Experimental (26H1)

来自 Canary 频道，或在 “高级选项” 下明确选择了这些 Windows 核心版本的预览体验成员，应在这些更改推出后查阅相应版本的发布说明。

目前加入了商业版 Windows 预览体验计划的商业客户，也可期待看到上述相同的更改和改进。而加入了 Windows Server 预览体验计划的成员则会发现该计划保持不变。

我们之所以存在，是因为这个社区的热情反馈，而这些更改仅仅是一个起点。正如[本周早些时候]()宣布的那样，我们将在接下来的几个月中继续举办 Windows 预览体验成员系列见面会。您也可以通过下方的社交媒体链接关注我们并直接互动。

Alec 与 Windows 预览体验计划团队

X：[Windows Insider Program]()  
Alec：[@AlecOot]()