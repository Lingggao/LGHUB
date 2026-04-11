# 微软更新文档，详解 “已知问题回滚” (KIR) 功能如何自动修复 Windows 更新中的问题

**作者**：Ling Gao (微软 Management 社区引领者)

2025 年 11 月 5 日，微软更新了 **“**[**已知问题回滚**](https://learn.microsoft.com/en-us/troubleshoot/windows-server/installing-updates-features-roles/known-issue-rollback)**” (Known Issue Rollback，简称 KIR)** 功能的说明文档，详细阐明了此功能如何在 Windows 更新引发问题时快速将受影响设备恢复至正常状态，从而显著提升系统可靠性。

该功能自 Windows 10 2004 版本起逐步优化，并于 2021 年 3 月[正式对外公布](https://techcommunity.microsoft.com/blog/windows-itpro-blog/known-issue-rollback-helping-you-keep-windows-devices-protected-and-productive/2176831)。目前，其已覆盖支持周期内的所有 Windows [客户端](https://learn.microsoft.com/zh-cn/windows/release-health/supported-versions-windows-client)与[服务器](https://learn.microsoft.com/zh-cn/windows/release-health/windows-server-release-info)系统，包括 Windows 11 及 Windows Server 系列。KIR 功能的核心优势在于 “精准性”：当某个 Windows 更新引入 Bug 时，系统可以仅回滚出现问题的代码，保留其他更新内容。这一机制避免了过去必须整体卸载或跳过一次更新所带来的安全风险与合规隐患。

**对于个人及家庭用户 (零售和消费类设备)，KIR 功能完全自动化运行，无须用户干预。**只要设备正常连接至 Windows 更新服务，微软即可通过云端推送回滚策略。一旦监测到潜在问题，微软会先收集详细信息、确定根本原因，并据此评估是否需要启动回滚措施。如果决定实施，相关回滚部署将在 24 小时内通过 Windows 更新下发，自动在数以亿计的设备中禁用引发故障的代码，实现 “无感修复”。

KIR 功能近期已发挥实际作用。微软同日披露，正在调查一个与 10 月 14 日发布的 [KB5066835](https://support.microsoft.com/en-us/help/5066835) 更新 (及后续版本) 有关的问题：部分设备在开机或重启时可能意外进入 BitLocker 界面，要求用户输入恢复密钥。该问题主要影响支持 “现代待机” 功能 (用于在低功耗状态下维持网络连接) 的 Intel 设备。**针对此问题，微软部署了 KIR 回滚，受影响设备将自动接收修复更新以规避此 Bug。**

用户如果发现异常，可以查阅 Windows 更新公告中的 “[已知问题](https://learn.microsoft.com/en-us/windows/release-health/status-windows-11-25h2)” 部分，或联系微软支持团队获取帮助。在企业环境中，IT 管理员可通过微软提供的组策略模板手动部署 KIR 功能，对内部设备实施精细控制。