---
title: Office 365 美国政府版
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 3f482abc-993f-41bf-8754-0f489a7e4861
description: 为了响应美国公共部门不断变化的独特要求，Microsoft 创建了一个Office 365 US 政府计划 (Office 365 政府版) 。 本文概述了特定于美国环境Office 365 政府版的功能。
ms.openlocfilehash: 1a69b6a2366a8855970775b6ca3af7b8f507a6d8
ms.sourcegitcommit: b1b852bcef2c7ae0bdce8ca4ae5d3eafe9b454b3
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/28/2021
ms.locfileid: "52699078"
---
# <a name="office-365-government"></a>Office 365 政府版

> [!IMPORTANT]
> Microsoft Teams COVID-19 冠状病毒（COVID-19）和冠状病毒（COVID-19）导致在线呼叫和音频 (/视频会议) 峰值。<br/>
>
>为了响应前所未有的呼叫数量增长，为了确保连续性和可用性，Microsoft 允许 Microsoft Teams GCC 音频/视频服务器利用我们的商业数据中心以及政府数据中心中的处理能力。<br/>
>
>这些音频/视频服务器驻留在美国Microsoft Azure FedRAMP 高资格鉴定边界服务器中，不存储任何客户内容。 但是，这些服务器正在处理通话和会议的音频和视频，并在此临时期间由我们的商业员工运营。<br/>
>
>合格的屏蔽人员通过查看这些服务器的任何交互式登录来监视这些服务器以潜在访问客户数据。 合格的人员GCC访问客户内容的要求。 有关屏蔽要求的详细信息，请参阅GCC[服务说明](gcc.md)。<br/>
>
>感谢你的支持，我们采取一些措施来确保我们的服务在这些不时时刻保持可用和可靠。<br/>

为了响应美国公共部门不断变化的独特要求，Microsoft 已创建Office 365 政府版计划 (或Office 365 政府版) 。 此服务说明概述了特定于美国环境Office 365 政府版功能。 我们建议您与其他服务说明一起阅读此服务[Microsoft 365 Office 365说明。](../../office-365-service-descriptions-technet-library.md)

## <a name="how-to-use-this-service-description"></a>如何使用本服务说明

Office 365 政府版服务说明旨在作为常规服务说明Office 365覆盖。 它定义了唯一承诺以及与 Office 365 企业版产品的差异。

## <a name="about-office-365-government-environments"></a>关于Office 365 政府版环境

Office 365 政府版计划是按月订阅，可以授权给任意数量的用户。

- 该 **Office 365 GCC** 环境符合联邦对云服务（包括 FedRAMP High）的要求，以及针对犯罪和联邦税务信息系统 (CJI 和 FTI 数据类型的要求) 。

- 高 **Office 365 GCC DoD** 环境符合美国国防部安全要求指南、国防联邦购置条例补充程序 (DFARS) 以及 ITAR (国际武器) 。

除了组织的特性和功能Office 365，使用Office 365 政府版组织还受益于以下Office 365 政府版：

- 您组织的客户内容与 Microsoft 商业 Office 365 服务中的客户内容在逻辑上是隔离的。

- 您组织的客户内容存储在美国境内。

- 对组织的客户内容的访问权限只限于屏蔽的 Microsoft 员工。

- Office 365 政府版符合美国公共部门客户所需的认证和资格鉴定。

## <a name="customer-eligibility"></a>客户资格

Office 365 政府版 适用于 (1) 美国联邦、州、地方、地方、领地和地区政府实体，以及 (2) 其他实体，这些实体处理受政府法规和要求限制的数据，并且使用 Office 365 政府版 适合满足这些要求，但需经过资格验证。 Microsoft 的资格验证包括确认处理的是受符合国际武器贸易条例 (ITAR) 约束的数据，还是受 FBI 的刑事司法信息服务 (CJIS) 政策约束的执法数据，亦或是其他受政府监管或控制的数据。 对于 ITAR 数据，资格验证可能需要提供美国国务院注册证明；对于数据处理的具体要求，可能需要提供政府机构资助证明。 Office 365 DoD 环境专供美国国防部使用。

尽管资格条件在产品/服务Office 365 政府版一致，但 Microsoft 将仅同意适用于高环境的 DFARS 和 ITAR GCC语言。

对资格有疑问的实体Office 365 政府版咨询其帐户团队。

在续订客户合同以购买Office 365 政府版，需要重新验证资格。

## <a name="customer-content-located-within-the-united-states"></a>位于美国境内的客户内容

Office 365 政府版服务从物理上位于美国的数据中心提供。 下面的客户内容存储在仅物理上位于美国的数据中心中的其余部分：

- Exchange Online电子邮件 (、日历条目以及电子邮件附件内容中的邮箱) 

- SharePoint联机网站内容和存储在该网站中的文件

- Skype for Business存档的对话、上传的文档和白板会话

- Microsoft Teams持久聊天线程

> [!NOTE]
> 对于一般用途，Skype for Business 不存储客户内容，但如果存储，内容会存储在美国的数据中心内。

如果您的用户位于美国境内。 对 Web Office 使用 (Office（以前称为 Office Web Apps) ）或采用 Active Directory 联合身份验证服务 (AD FS) 2.0 并设置策略以帮助确保用户通过单一登录连接到服务，则临时缓存在 Office 网页中的客户内容将位于美国。

虽然根据合规性，SharePoint网站的网站使用率页面可用于政府版计划，但此页面的一些功能仅适用于商业客户。 若要了解更多信息，请参阅网站[中的网站SharePoint网站Microsoft 365。](https://support.microsoft.com/office/2fa8ddc2-c4b3-4268-8d26-a772dc55779e)

## <a name="office-365-government-and-third-party-services"></a>Office 365 政府版和第三方服务

Office 365 可以将第三方应用程序集成到 Microsoft 365 企业应用版 (中包含的 SharePoint Online 网站、Skype for Business、Office 应用程序，如 Word、Excel、PowerPoint 和 Outlook) 以及 Outlook Web App。 此外，Office 365 还支持与第三方服务提供商集成。 这些第三方应用程序和服务可能参与存储、传输和处理组织在 Office 365 基础结构外部的第三方系统上的客户数据，因此未涵盖在 Office 365 合规性和数据保护协议中。 我们建议您在为组织评估这些服务的相应使用情况时，查看第三方提供的隐私和合规性声明。

## <a name="restricted-data-access-by-administrators"></a>管理员受限数据访问

Microsoft Office 365 政府版访问客户内容的访问权限仅限于屏蔽人员。 有关屏蔽级别的详细信息，请参阅各个环境的服务说明页面 (GCC或GCC高和 DoD) 。

## <a name="fasttrack-center-onboarding-assistance"></a>FastTrack 中心载入协助

借助适用于 Office 365<sup>1</sup>的 FastTrack 中心权益，你可以与 FastTrack 专家远程合作，让 Office 365 环境可供使用，并计划在组织中推出和使用。 FastTrack 流程提供了载入和用户采用服务。

载入包括：

- 核心载入 - 这些是租户配置和与 Azure AD Azure Active Directory (集成) 所需的任务。 核心载入还为载入其他符合条件的服务提供了基线。

- 服务载入和迁移 - 服务载入任务支持租户中的方案。 数据 (包括电子邮件和文件) 数据迁移 [中介绍](/FastTrack/data-migration)。<sup>2</sup>

用户采用服务由一些任务组成，这些任务可指导用户确保用户了解符合条件的服务，并可以使用它们来推动业务价值。 此协助与载入活动并行发生。

有关 FastTrack 中心流程的特定信息，请参阅 [此处](/FastTrack/us-gov-appendix-overview)。 有关参与角色和职责的细分，请查看 [FastTrack](/FastTrack/us-gov-appendix-fasttrack-responsibilities) 责任以及 [你的责任](/FastTrack/us-gov-appendix-your-responsibilities)。

> <sup>1</sup>必须至少从符合条件的计划列表中购买 150 个许可证[](/fasttrack/eligibility)才能接收 FastTrack 服务。
<br/><sup>2</sup>数据迁移服务适用于Office 365许可证超过 500 个的租户。

## <a name="data-migrations-performed-by-fasttrack"></a>由 FastTrack 执行的数据迁移

选择 [FastTrack](https://fasttrack.microsoft.com/) 迁移权益的客户将需要向管理其数据迁移的团队授予访问权限。 这些人员是美国政府公民，在针对美国政府服务客户Office 365以下背景检查。<br><br>

|背景屏蔽|GCC|GCC High 和 DoD|
|---|---|---|
|验证美国公民|是|是|
|雇佣历史记录检查|是|是|
|教育验证|是|是|
|SSN (搜索) 安全号码|是|是|
|7 年后 (犯罪历史记录) |是|是|

## <a name="office-365-us-government-and-azure-government-expressroute"></a>Office 365 美国政府版和 Azure 政府 ExpressRoute

Office 365美国政府客户可以使用 Azure 政府 ExpressRoute 服务以专用方式连接到受支持的 Office 365 服务，而不是通过公共 Internet 连接。

有关详细信息，如支持的提供程序、定价模型等，请查看 [Azure ExpressRoute 信息](/azure/expressroute/)。

有关 Azure ExpressRoute Office 365的详细信息，请参阅 Azure [ExpressRoute for Office 365](/microsoft-365/enterprise/azure-expressroute)

## <a name="system-requirements"></a>系统要求

有关 Office 365 美国政府版 计划的系统要求，请参阅 [office.com](https://go.microsoft.com/fwlink/?LinkID=626095&amp;clcid=0x409) 产品网站上的 [Office 的系统要求](https://go.microsoft.com/fwlink/?LinkID=509817&amp;clcid=0x409)。

## <a name="security-amp-compliance-center"></a>Security &amp; Compliance Center

有关安全与合规中心 &amp; 的信息以及指向其他信息和可用性的链接，请参阅 [安全 &amp; 与合规中心](../../office-365-platform-service-description/office-365-securitycompliance-center.md)。

## <a name="service-availability-for-each-plan"></a>每个计划的服务可用性

每个 Office 365 计划都包括许多单个服务，例如 Exchange Online 和 SharePoint Online。下表显示了每个 Office 365 美国政府版 计划中可用的服务。<br><br>

|Office 365 服务|Office 365 政府版 G1|Office 365 政府版 G3|Office 365 政府版 G5|Office 365 政府版F3|
|---|---|---|---|---|
|Office 网页版|是|是|是|是|
|Microsoft 365 企业应用版|否|是|是|否|
|Exchange Online|是|是|是|是|
|Exchange Online Protection|是|是|是|是|
|SharePoint Online|是|是|是|是|
|OneDrive for Business|是|是|是|是|
|Skype for Business (Instant Messaging &amp; Presence)|是<sup>1</sup>|是|是|是<sup>1</sup>|
|语音 - 电话系统、音频会议|否<sup>2</sup>|否<sup>2</sup>|是<sup>5</sup>|否|
|Power BI Pro|否<sup>2</sup>|否<sup>2</sup>|是|否<sup>2</sup>|
|Project Online|否<sup>2</sup>|否<sup>2</sup>|否<sup>2</sup>|否<sup>2</sup>|
|Visio 网页版|否<sup>6</sup>|否<sup>6</sup>|否<sup>6</sup>|否<sup>6</sup>|
|Yammer 企业版|否<sup>4</sup>|否<sup>4</sup>|否<sup>4</sup>|否<sup>4</sup>|

> <sup>1</sup> Skype for Business基本版本可供所有客户使用。 Skype for Business 桌面客户端是在本地安装的应用程序，为包含 Skype for Business Online 的 Office 365 计划提供状态、即时消息和会议功能。 Microsoft 365 企业应用版、G3 和 G5 包括完整的 Skype 应用程序，其中包括高级电话支持、存档和合规性功能等附加功能。 必须为每个用户分配 Skype for Business Online 许可证。
<br/><sup>2</sup> 不包含在内，但可以单独购买加载项。 Project Online包括Project Online桌面客户端作为订阅的一部分。
<br/> <sup>3</sup>尚不可用于GCC DoD 计划，但即将推出。
<br/><sup>4</sup> Yammer Enterprise美国政府版的组件Office 365，但对于在美国政府中获得许可使用 Office 365 的每位用户，可GCC独立产品/服务。 This offer is currently limited to customers that purchase Office 365 GCC under Enterprise Agreements and Enterprise Subscription Agreements. Yammer在高GCC DoD 中不可用。
<br/><sup>5</sup> 通话套餐是加载项。
<br/><sup>6</sup> 不包含在内，但可以单独购买加载项。 Visio Web 的一部分Visio桌面应用作为订阅的一部分。

## <a name="platform-features"></a>平台功能

下表列出了Office 365 美国政府版 计划中所提供的平台功能和服务。<br><br>

|功能|Office 365 政府版 G1|Office 365 政府版 G3|Office 365 政府版 G5|Office 365 政府版F3|
|---|---|---|---|---|
|**Office 365 管理**|||||
|使用Microsoft 365管理中心管理Office 365|是<sup>16</sup>|是<sup>16</sup>|是|是<sup>16</sup>|
|从 Office 365 中管理核心服务设置|是|是|是|是|
|使用 Windows PowerShell 管理 Office 365|是|是|是|是|
|使用 Azure 信息保护保护内容|否<sup>1</sup>|是<sup>15</sup>|是<sup>15</sup>|否<sup>1</sup>|
|**[Office 365 套件功能](../../office-365-platform-service-description/office-365-suite-features.md)**|**Office 365 政府版 G1**|**Office 365 政府版 G3**|**Office 365 政府版 G5**|**Office 365 政府版F3**|
|Microsoft Bookings|否|是<sup>21</sup>|是<sup>21</sup>|否|
|Microsoft 简报电子邮件|否|否|否|否|
|Microsoft Power Automate|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|Microsoft Forms|是|是|是<br/>|是</sup>|
|Microsoft Graph API|是|是|是|是|
|Microsoft MyAnalytics|否|否|是<sup>17</sup>|否|
|Microsoft Planner|是|是|是|是|
|Microsoft PowerApps|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|Microsoft StaffHub|否|否|否|否<br/>|
|Microsoft Stream|是<sup>9、15</sup>|是<sup>9、15</sup>|是<sup>9、15</sup>|是<sup>9、15、20</sup>|
|Microsoft Sway|否|否|否|否|
|Microsoft Teams|是|是|是|是|
|Office Delve|是<sup>17</sup>|是<sup>17</sup>|是|是<sup>17</sup>|
|Office 365 组|是|是|是|是|
|**[用户帐户管理](../../office-365-platform-service-description/user-account-management.md)**|**Office 365 政府版 G1**|**Office 365 政府版 G3**|**Office 365 政府版 G5**|**Office 365 政府版F3**|
|云身份|是|是|是|是|
|联合身份（单点登录）|是|是|是|是|
|多重身份验证|是|是|是|是|
|电话身份验证|是<sup>9</sup>|是<sup>9</sup>|是|是<sup>9</sup>|
|Office 365 桌面设置|是|是|是|是|
|使用 Office 365 管理用户|是|是|是|是|
|使用 .csv 文件批量上载|是<sup>9</sup>|是<sup>9</sup>|是|是<sup>9</sup>|
|目录同步工具|是|是|是|是|
|Exchange 简单（直接转换）迁移|是|是|是|是|
|通过使用 Office 365 删除帐户|是<sup>3</sup>|是<sup>3</sup>|是<sup>3</sup>|是<sup>3</sup>|
|管理员可以从 Office 365 中或通过使用 Windows PowerShell 重新设置用户密码|是<sup>4</sup>|是<sup>4</sup>|是<sup>4</sup>|是<sup>4</sup>|
|用户可以更改自己的密码|是<sup>5</sup>|是<sup>5</sup>|是<sup>5</sup>|是<sup>5</sup>|
|管理许可证|是<sup>7、8</sup>|是<sup>7、8</sup>|是<sup>7、8</sup>|是<sup>7、8</sup>|
|从 Office 365 管理安全组|是|是|是|是|
|多个管理员角色可用|是|是|是|是|
|允许合作伙伴为您管理 Office 365|是<sup>11</sup>|是<sup>11</sup>|是<sup>11</sup>|是<sup>11</sup>|
|Azure Active Directory 服务|是|是|是|是|
|**[域](../../office-365-platform-service-description/domains.md)**|**Office 365 政府版 G1**|**Office 365 政府版 G3**|**Office 365 政府版 G5**|**Office 365 政府版F3**|
|添加第二级自定义域，如 fourthcoffee.com|是|是|是|是|
|添加第三级自定义域，如 marketing.fourthcoffee.com是|是|是|是|是|
|添加多达 900 个自定义域|是|是|是|是|
|自定义域需要域所有权验证|是|是|是|是|
|**[服务运行状况和连续性](../../office-365-platform-service-description/service-health-and-continuity.md)**|**Office 365 政府版 G1**|**Office 365 政府版 G3**|**Office 365 政府版 G5**|**Office 365 政府版F3**|
|“服务运行状况”或“服务状态”页面中显示状态信息|是<sup>9、15</sup>|是<sup>9、15</sup>|是<sup>9、15</sup>|是<sup>9、15</sup>|
|Microsoft 365 管理中心仪表板中显示的单个警报的状态|是<sup>9、15</sup>|是<sup>9、15</sup>|是<sup>9、15</sup>|是<sup>9、15</sup>|
|是|是|是|是|是|
|**[报告](../../office-365-platform-service-description/reports.md)**|**Office 365 政府版 G1**|**Office 365 政府版 G3**|**Office 365 政府版 G5**|**Office 365 政府版F3**|
|活动邮箱和非活动邮箱|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|新邮箱和已删除的邮箱|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|新组和已删除的组|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|邮箱使用情况|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|邮箱连接类型|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|已发送和已接收邮件|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|主要发件人和收件人|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|垃圾邮件检测|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|恶意软件检测|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|邮件的主要恶意软件|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|邮件的规则匹配|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|邮件的主要规则匹配|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|邮件的主要 DLP 策略匹配|否|是<sup>15</sup>|是<sup>15</sup>|否|
|按邮件严重性显示的 DLP 策略匹配|否|是<sup>15</sup>|是<sup>15</sup>|否|
|邮件的 DLP 策略匹配、重写和误报|否|是<sup>15</sup>|是<sup>15</sup>|否|
|邮件的主要 DLP 规则匹配|否|是<sup>15</sup>|是<sup>15</sup>|否|
|IM 和音频会话|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|应用程序共享、Web 和电话拨入式会议|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|视频、应用程序共享和文件传输会话|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|IM 和音频/视频会议|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|可下载的邮件保护报告|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|使用的浏览器|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|使用的操作系统|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|使用 Microsoft 365 报告 Web 服务创建自己的报表|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|**[服务更新](../../office-365-platform-service-description/service-updates.md)**|**Office 365 政府版 G1**|**Office 365 政府版 G3**|**Office 365 政府版 G5**|**Office 365 政府版F3**|
|向所有客户提供的定期更新|是|是|是|是|
|通知发送给 消息中心（当需要操作时）|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|是<sup>15</sup>|
|针对某些服务更新的 Roadmap.office.com|否<sup>10、13</sup>|否<sup>10、13</sup>|否<sup>10、13</sup>|否<sup>10、13</sup>|
|打开定向发布的选项|是<sup>10</sup>|是<sup>10</sup>|是<sup>10</sup>|是<sup>10</sup>|
|**[帮助和培训](../../office-365-platform-service-description/help-and-training.md)**|**Office 365 政府版 G1**|**Office 365 政府版 G3**|**Office 365 政府版 G5**|**Office 365 政府版F3**|
|联机帮助|是|是|是|是|
|社区|是|是|是|是|
|其他自助资源|是|是|是|是|
|自学培训|是|是|是|是|
|**[网络](../../office-365-platform-service-description/networking.md)**|**Office 365 政府版 G1**|**Office 365 政府版 G3**|**Office 365 政府版 G5**|**Office 365 政府版F3**|
|IPv4 和 IPv6 协议|是|是|是|是|
|**信任**|**Office 365 政府版 G1**|**Office 365 政府版 G3**|**Office 365 政府版 G5**|**Office 365 政府版F3**|
|**[隐私、安全性和透明度](../../office-365-platform-service-description/privacy-security-and-transparency.md)**|||||
|高级数据治理|否<sup>12</sup>|否<sup>12</sup>|是|否<sup>12</sup>|
|云应用安全|否<sup>12、19</sup>|否<sup>12、19</sup>|是<sup>19</sup>|否<sup>12、19</sup>|
|Microsoft Defender for Office 365|否<sup>12、18</sup>|否<sup>12、18</sup>|是<sup>18</sup>|否<sup>12、18</sup>|
|客户密码箱|否<sup>12</sup>|否<sup>12</sup>|是|否<sup>12</sup>|
|高级电子数据展示|否<sup>12</sup>|否<sup>12</sup>|是|否<sup>12</sup>|
|安全分数<sup>14</sup>|是<sup>9、15</sup>|是<sup>9</sup>|是<sup>9、15</sup>|是<sup>9、15</sup>|
|Office邮件加密|否|是|是|否|
|威胁智能|否<sup>12</sup>|否<sup>12</sup>|是|否<sup>12</sup>|
|**[合规性](/microsoft-365/compliance/offering-home)**|||||
|SAS 70 / SSAE16 评估|是|是|是|是|
|ISO 27001 认证|是|是|是|是|
|欧盟模式条款|是|是|是|是|
|欧盟安全港|是|是|是|是|
|HIPAA 业务关联协议|是|是|是|是|
|FISMA 操作授权|是|是|是|是|
|Microsoft 数据处理协议|是|是|是|是|
|一级 PCI DSS|是|是|是|是|
|PCI 监管的 PAN 数据|否|否|否|否|
|**[服务连续性](../../office-365-platform-service-description/service-health-and-continuity.md)**|是|是|是|是|
|**[BlackBerry](../../office-365-platform-service-description/blackberry.md)**|**Office 365 政府版 G1**|**Office 365 政府版 G3**|**Office 365 政府版 G5**|**Office 365 政府版F3**|
|是|否<sup>2</sup>|否<sup>2</sup>|否<sup>2</sup>|否<sup>2</sup>|
|**[合作伙伴](../../office-365-platform-service-description/partners.md)**|||||
|是|否<sup>11</sup>|否<sup>11</sup>|否<sup>11</sup>|否<sup>11</sup>|
|是|否<sup>11</sup>|否<sup>11</sup>|否<sup>11</sup>|否<sup>11</sup>|
|**[服务级别协议](../../office-365-platform-service-description/service-level-agreement.md)**|是|是|是|是|
|**[产品使用权限](../../office-365-platform-service-description/product-use-rights.md)**|是|是|是|是|

> <sup>1</sup> Azure 信息保护不包括在内，但可以单独购买加载项，并启用支持的信息权限管理 (IRM) 功能。 某些 Azure 信息保护功能需要订阅 Microsoft 365 企业应用版，但 F3 中不包含Office 365 政府版 G1 Office 365 政府版订阅。 >
<br/><sup>2</sup> 现有的 BBCS 和 BIS 客户可继续使用服务。 不接受新客户。
<br/><sup>3</sup> 如果使用目录同步，您必须使用 Active Directory（而不是 Office 365 门户）或使用 Windows PowerShell 的 Azure Active Directory 模块来删除帐户或更改密码。
<br/><sup>4</sup> 如果使用密码同步，用户必须更改本地 Active Directory 中的密码。
<br/><sup>5</sup> 若要了解如何为用户设置自助服务密码管理策略，请参阅 [管理 Azure AD 中的密码](/azure/active-directory/user-help/active-directory-passwords-update-your-own-password)。
<br/><sup>6</sup> Office 365 只能有一个公共网站，除非你已升级旧版 Office 365。 如果已升级，可以拥有两个公共网站，但其中只有一个能够使用自定义域名托管。 若要详细了解如何处理商业版订阅的两个网站，请参阅 [处理两个 Office 365 公共网站](https://go.microsoft.com/fwlink/p/?LinkID=271589)。 如果有其他订阅，请参阅[在 Office 365 中了解合作伙伴网站托管和公共网站](https://go.microsoft.com/fwlink/p/?LinkID=325009)，详细了解公共网站。
<br/><sup>7</sup> 减少按费用折扣购买的席位可能会导致提前终止费用。 这不适用于按月支付的订阅。
<br/><sup>8</sup>以下计划不支持从管理中心Microsoft 365许可证席位更改：Office 365 政府版 G1、Office 365 政府版 G3、Office 365 政府版 F3。
<br/><sup>9</sup>尚未在 GCC High 中可用，但即将推出。
<br/><sup>10</sup>对于 Office 365 政府版 G1、G3 和 F3，定向发布和适用于Office 365路线图适用;但是，由于合规性要求，特定服务更新可能有一些[差异或延迟](https://www.microsoft.com/trust-center)。
<br/><sup>11</sup>尚不可用于Office 365 政府版产品/服务，但即将推出。
<br/><sup>12</sup>不包含在内，但可以在外接程序中作为单独的GCC。
<br/><sup>13</sup>不支持Office 365 政府版产品/服务。
<br/><sup>14</sup> 在 中可用 [https://securescore.office.com](https://securescore.office.com) 。 必须拥有管理员权限。 有关详细信息，请参阅安全分数[Office 365介绍](/microsoft-365/security/mtp/microsoft-secure-score)。
).
<br/><sup>15</sup> 尚不可用于 DoD 环境，但即将推出。
<br/><sup>16</sup>管理中心不包括 DoD 或高GCC使用情况分析。
<br/><sup>17</sup>不支持高GCC DoD 环境。
<br/><sup>18</sup> High 和 DoD 中尚未提供适用于用户和域模拟和欺骗智能GCC防钓鱼。
<br/><sup>19</sup>尚未在GCC中可用，但即将推出。
<br/><sup>20</sup> 仅适用于 Microsoft Stream：不发布或共享。
<br/><sup>21</sup>不适用于 Microsoft Graph API 或 Microsoft Teams。

## <a name="office-application-availability-and-enterprise-value"></a>Office应用程序可用性和企业价值

下表显示 Office 365 美国政府版计划中所提供的 Office 应用程序功能。<br><br>

|应用程序/功能|Office 365 政府版 G1|Office 365 政府版 G3|Office 365 政府版 G5|Office 365 政府版F3|
|---|---|---|---|---|
|**Office 应用程序**|||||
|[Microsoft Word](../../office-applications-service-description/office-applications.md#microsoft-word)<sup>7</sup>|否|是|是|否|
|[Microsoft Excel](../../office-applications-service-description/office-applications.md#microsoft-excel)<sup>7</sup>|否|是|是|否|
|[Microsoft PowerPoint](../../office-applications-service-description/office-applications.md#microsoft-powerpoint)<sup>7</sup>|否|是|是|否|
|[Microsoft OneNote](../../office-applications-service-description/office-applications.md#microsoft-onenote)<sup>7</sup>|否|是|是|否|
|[Microsoft Outlook](../../office-applications-service-description/office-applications.md#microsoft-outlook)<sup>7</sup>|否|是|是|否|
|Microsoft Forms<sup>7</sup>|是|是 <br/>|是|否|
|Microsoft Whiteboard<sup>7</sup>|否|是|是|否|
|[Microsoft Publisher](../../office-applications-service-description/office-applications.md#microsoft-publisher)|否|是|是|否|
|[Microsoft Access](../../office-applications-service-description/office-applications.md#microsoft-access)|否|是|是|否|
|[Skype for Business](../../office-applications-service-description/office-applications.md#skype-for-business)|是<sup>3</sup>|是|是|是<sup>3</sup>|
|[适用于 Office 365 的 Office for Mac](https://support.office.com/article/General-requirements-for-Outlook-2016-for-Mac-A07A593D-B383-4906-A6C1-962D5543ED57)|否|是|是|否|
|[Office Mobile for iPad/iPhone](../../office-applications-service-description/office-applications.md#office-mobile-for-ipadiphone)|是|是<sup></sup>|是<sup></sup>|是|
|[Office Mobile for Android](../../office-applications-service-description/office-applications.md#office-mobile-for-android)|是|是<sup></sup>|是<sup></sup>|是|
|[Office Mobile for Windows Phone](../../office-applications-service-description/office-applications.md#office-mobile-for-windows-phone)|是|是<sup>4</sup>|是<sup>4</sup>|是|
|Office Mobile for Windows 10 tablets|是|是<sup></sup>|是<sup></sup>|是|
|Outlook iOS 和 Android<sup>5、4</sup>|是|是|是|是|
|**企业价值**|**Office 365 政府版 G1**|**Office 365 政府版 G3**|**Office 365 政府版 G5**|**Office 365 政府版F3**|
|每个用户可在 5 台 PC 或 Mac 上进行安装|否|是|是|否|
|自动化用户帐户配置|是|是|是|是|
|多语言用户界面|否|是|是|否|
|客户端推送部署|否|是<sup>4</sup>|是<sup>4</sup>|否|
|内部部署 Exchange 的客户端支持|否|是|是|否|
|内部部署 SharePoint 的客户端支持|否|是|是|否|
|控制软件更新|否|是|是|否|
|数据库比较|否|是|是|否|
|桌面虚拟化|否|是|是|否|
|Excel 电子表格比较|否|是|是|否|
|Excel 电子表格查询|否|是|是|否|
|Exchange Online 和 SharePoint Online 存档和合规性|否|是|是|否|
|组策略支持|否|是|是|否|
|使用 Azure 信息保护的信息权限管理|否<sup>1</sup>|是<sup>6</sup>|是<sup>6</sup>|否<sup>1</sup>|
|使用 Windows Server AD RMS 的信息权限管理|是<sup>2</sup>|是<sup>2</sup>|是<sup>2</sup>|是<sup>2</sup>|
|Office 插件、ActiveX 和 BHO 支持|否|是|是|否|
|在 SharePoint Server、SharePoint Online、OneDrive for Business 和 Office 365 上对笔记本的 OneNote 客户端访问|否|是|是|否|
|Office Lens|否|否|否|否|
|Office 遥测|否|是<sup>4</sup>|是<sup>4</sup>|否|
|客户端应用程序的脱机支持|否|是|是|否|
|优化并排客户端安装|否|是|是|否|
|Power Map for Excel|否|否|否|否|
|Power Pivot for Excel|否|是<sup>4</sup>|是<sup>4</sup>|否|
|Power Query for Excel|否|是<sup>4</sup>|是<sup>4</sup>|否|
|Power View for Excel|否|是<sup>4</sup>|是<sup>4</sup>|否|
|漫游设置|否|是<sup></sup>|是<sup></sup>|否|
|共享计算机激活|否|是|是|否|
|支持阻止基于云的文件存储|否|是|是|否|
|版本升级|否|是<sup>4</sup>|是<sup>4</sup>|否|
|批量激活 (KMS/MAK)|否|否|否|否|

> <sup>1</sup> Azure 信息保护不包括在内，但可以单独购买加载项，并启用支持的信息权限管理 (IRM) 功能。 某些 Azure 信息保护功能需要订阅 Microsoft 365 企业应用版，但 F3 中不包含Office 365 政府版 G1 Office 365 政府版订阅。
<br/><sup>2 Windows</sup>服务器 AD RMS 是一种本地服务器，必须单独购买和管理，才能启用受支持的 IRM 功能。
<br/><sup>3</sup> Skype for Business基本版可供所有客户使用。 Skype for Business 桌面客户端是在本地安装的应用程序，为包含 Skype for Business Online 的 Office 365 计划提供状态、即时消息和会议功能。 Microsoft 365 企业应用版和 Office 365 企业版 E3 包括完整的 Skype 应用程序，其中包括高级电话支持、存档和合规性功能等附加功能。 A Skype for Business Online license must be assigned for each user. For more information on Lync Basic features, see [Skype for Business Online client comparison tables](/lyncserver/lync-server-2013-desktop-client-comparison-tables).
<br/><sup>4</sup>在高GCC DoD 环境中尚不可用，但即将推出。
<br/><sup>5</sup> [请参阅 Outlook for iOS 和 政府社区云中的适用于 iOS](/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-in-the-government-cloud)和 Android 的更多详细信息。
<br/><sup>6</sup>尚不可用于Office 365 DoD 环境，但即将推出。
<br/><sup>7</sup> 应用程序在政府云中完全可用，但目前不可用的特定功能除外。 有关详细信息[Office应用程序功能](#office-application-and-feature-availability-in-government-plans)可用性。

## <a name="office-application-and-feature-availability-in-government-plans"></a>Office计划中提供的应用程序和特性

以下Office应用程序在政府云中可用;但是，某些基于云的功能当前可能不可用，如表所示。<br><br>

|应用程序/功能|GCC|GCC 高|DOD|
|---|---|---|---|
|[**Microsoft Excel**](../../office-applications-service-description/office-applications.md#microsoft-excel)在政府云中完全可用，但以下功能目前不可用： ||||
|3D 嵌入式动画和 3D 模型|否|否|否|
|数据类型|否|否|否|
|快速填充|否|否|否|
|Insight Services (的想法) |否|否|否|
|改进了与自定义Power BI (的集成，直接从自定义视觉对象创建 PBI Excel) |否|否|否|
|智能数字墨迹|否|否|否|
|Office 365 组|否|否|否|
|连接到数据透视表的数据透视图数据|否|否|否|
|PowerPivot|否|否|否|
|发布到 Power BI|否|否|否|
|实时协作 (状态、常规共同授权、文档内聊天) |否|否|否|
|已与我共享|否|否|否|
|智能查找|否|否|否|
|图表：爆炸树图、瀑布图、直方图、地图、日程表、漏斗|否|否|否|
|版本历史记录|否|否|否|
|[**Microsoft Forms**](https://support.office.com/article/5cbd407a-eef7-431e-8e3a-eb666eab4b4c)在政府云中完全可用，但以下功能目前不可用：|**GCC**|**GCC 高**|**DOD**|
|电子邮件通知|否<sup>1</sup>|否<sup>1</sup>|否|
|插入图片|否<sup>1</sup>|否<sup>1</sup>|否|
|插入视频|否<sup>1</sup>|否<sup>1</sup>|否|
|数学|否<sup>1</sup>|否<sup>1</sup>|否|
|Office集成|否<sup>1</sup>|否<sup>1</sup>|否|
|最近的组表单|否<sup>4</sup>|是|是|
|外部共享<sup>3</sup>|是|否|否|
|表单Pro|否|否|否|
|[**Microsoft OneNote**](../../office-applications-service-description/office-applications.md#microsoft-onenote)在政府云中完全可用，但以下功能目前不可用： |**GCC**|**GCC 高**|**DOD**|
|研究工具|否|否|否|
|智能数字墨迹|否|否|否|
|向用户发送电子邮件OneNote (me@onenote.com) |否|否|否|
|Web Clipper|否|否|否|
|[**Microsoft Outlook**](../../office-applications-service-description/office-applications.md#microsoft-outlook)在政府云中完全可用，以下功能除外，这些功能并非在所有政府云中可用，如下表所示。|**GCC**|**GCC 高**|**DOD**|
|Office () |否|否|否|
|动态数据Exchange (DDE) 默认情况下处于禁用状态|否|否|否|
|语音听写|是|是|否<sup>1</sup>|
|[**Microsoft PowerPoint**](../../office-applications-service-description/office-applications.md#microsoft-powerpoint)在政府云中完全可用，但以下功能除外，这些功能并非在所有政府云中可用，如下表所示。|**GCC**|**GCC 高**|**DOD**|
|智能查找|否|否|否|
|Office () |否|否|否|
|3D 模型和 3D 嵌入动画|否|否|否|
|图表：地图|否|否|否|
|智能数字墨迹|否|否|否|
|实时字幕和字幕PowerPoint|是|是|否|
|实时演示文稿|否|否|否|
|沉浸式阅读器|否|否|否|
|演示者指导|否|否|否|
|已与我共享|否|否|否|
|Skype for Business共享集成|否|否|否|
|版本历史记录|否|否|否|
|Office 365 组|否|否|否|
|实时协作 (状态、常规共同授权、文档内聊天) |否|否|否|
|语音听写|是|是|否<sup>1</sup>|
|重复使用幻灯片|否|否|否|
|**Microsoft Whiteboard** 云中的云解决方案目前仅在中心客户端上可用，在桌面上不可用。|**GCC**<sup>2</sup>|**GCC高**<sup>2</sup>|**DOD**<sup>2</sup>|
|插入便笺、文本和图像|是<sup>2</sup> <br/>|是<sup>2</sup> <br/>|是<sup>2</sup> <br/>|
|墨迹到形状和墨迹到表格|是<sup>2</sup> <br/>|是<sup>2</sup> <br/>|是<sup>2</sup> <br/>|
|墨迹化|是<sup>2</sup> <br/>|是<sup>2</sup> <br/>|是<sup>2</sup> <br/>|
|将图像转换为墨迹|是<sup>2</sup> <br/>|是<sup>2</sup> <br/>|是<sup>2</sup> <br/>|
|辅助功能检查器|是<sup>2</sup> <br/>|是<sup>2</sup> <br/>|是<sup>2</sup> <br/>|
|动态模板 (看板、SWOT 等) |否|否|否|
|实时协作|否|否|否|
|实时状态|否|否|否|
|对内容的反应|否|否|否|
|白板的板库，包括与您共享的白板|否|否|否|
|[**Microsoft Word**](../../office-applications-service-description/office-applications.md#microsoft-word)在政府云中完全可用，以下功能除外，并非所有政府云中都提供这些功能，如下表所示。|**GCC**|**GCC 高**|**DOD**|
|智能查找|否|否|否|
|研究工具|否|否|否|
|Office声音|否|否|否|
|3D 模型|否|否|否|
|3D 嵌入式动画|否|否|否|
|点击|否|否|否|
|简历助手|否|否|否|
|地图图表|否|否|否|
|智能数字墨迹|否|否|否|
|已与我共享|否|否|否|
|转换|是<sup>5</sup>|是<sup>5</sup>|是<sup>5</sup>|
|Skype for Business共享集成|否|否|否|
|版本历史记录|否|否|否|
|Office 365 组|否|否|否|
|与合著者进行上下文聊天：与文档中共同创作者聊天|否|否|否|
|语音听写|是|是|否<sup>1</sup>|

有关功能可用性Microsoft Teams/GCC/GCC/DoD 中，请访问Microsoft Teams[服务说明。](../../teams-service-description.md)
> <sup>1</sup> 可用性即将提供。
<br/><sup>2</sup>未登录Surface Hub (本地) 。
<br/><sup>3</sup>外部共享适用于GCC环境。 详细了解如何[为组织关闭或打开 Microsoft Forms。](https://support.office.com/article/cc52287a-4550-464d-9a1b-457bf9df2240#PickTab=Configure) 在高和 DOD GCC禁用外部共享;您组织内的用户可以执行以下操作：填写表单并提交回复、复制和共享表单作为[](https://support.office.com/article/82ea9d8a-260a-47a0-afdb-497f3d746e3f)模板、[共同](https://support.office.com/article/d5bb5cf0-8401-4c15-bb8c-8e108cd7e69b)创作或协作处理表单以及访问[表单结果](https://support.office.com/article/02859424-341d-406f-b32a-9a0fbaf357af)。
<br/><sup>4</sup>最近针对组表单环境禁用GCC功能。 但是，用户仍可以通过选择"组窗体"选项卡上的特定组来访问组表单。
<br/><sup>5</sup> Word，Excel PowerPoint Windows客户端，而非 Web、MacOS、iOS 或 Android。
