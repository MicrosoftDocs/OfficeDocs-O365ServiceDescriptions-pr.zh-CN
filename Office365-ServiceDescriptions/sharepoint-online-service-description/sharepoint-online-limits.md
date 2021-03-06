---
title: SharePoint 限制
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: 了解SharePoint独立Microsoft 365计划的限制。
ms.openlocfilehash: 44571cedf74b2a094231173b87731916d9e26975
ms.sourcegitcommit: 10699cc17ddfed6af78ce1466f478b2bd67ba26a
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/08/2021
ms.locfileid: "53338335"
---
# <a name="sharepoint-limits"></a>SharePoint 限制

了解 SharePoint for Microsoft 365 中的服务Microsoft 365。
  
## <a name="limits-by-plan"></a>按计划的限制 

| 功能 | Microsoft 365 商业基础版、Business Standard 或 Business 高级版 | Microsoft 365 E3 E5、Office 365 E1、E3 或 E5，或 SharePoint 计划 1 或 2 | Microsoft 365 F1 F3、Office 365 F3 |
|:-----|:-----|:-----|:-----|
|每个组织的总存储<sup>量 1、2、6</sup> <br/> |1 TB 加上每个购买的许可证 10 GB<sup>3</sup>  <br/> |1 TB 加上每个购买的许可证 10 GB<sup>3</sup> <br/> |1 TB<sup>3</sup> <br/> |
|每个网站集的最大存储 (4) <sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|每个 (网站集) 网站集  <br/> |200 万<sup>6</sup> <br/> |200 万<sup>6</sup> <br/> |200 万<br/> |
|用户数  <br/> |最多 300 个  <br/> |1- 500，000<sup>7</sup> <br/> |1- 500，000<sup>7</sup> <br/> |
   
<sup>1</sup> [Learn how to find the total and available storage for your organization](/sharepoint/manage-site-collection-storage-limits). 你可以购买无限量的额外存储空间SharePoint存储空间。 请参阅 [为订阅添加存储空间](/office365/admin/subscriptions-and-billing/add-storage-space)。 
<br/><sup>2</sup> 我们建议监视回收站并定期清空回收站。 它使用的存储空间是组织的总存储空间上限的一部分。 
<br/> <sup>3</sup>如果你有一个Microsoft 365订阅和一Office 365 额外文件存储空间加载项，则添加存储量。 
<br/> <sup>4</sup> 这是单个网站 *集的存储 (* 以前称为"网站集") ，而不是每个 *网站提供* 的存储量。 此限制适用于所有类型的网站，包括Office 365组连接的团队网站和OneDrive。 SharePoint管理员可以[手动设置较低的存储限制](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits)。 
<br/> <sup>5</sup>一线员工无法管理SharePoint网站。 
<br/> <sup>6</sup>不包括OneDrive用户创建的许可证。 
<br/> <sup>7</sup> 如果你的用户数超过 500，000，请与 Microsoft 代表联系。 
  
## <a name="service-limits-for-all-plans"></a>所有计划的服务限制

### <a name="items-in-lists-and-libraries"></a>列表和库中的项目

一个列表最多包含 3000 万个项目，一个库可以有多达 3000 万个文件和文件夹。 当列表、库或文件夹包含的项目超过 100，000 个时，无法中断对列表、库或文件夹的权限继承。 也不能重新继承对它的权限。 但是，您仍可以中断该列表、库或文件夹中单个项目的继承，最多只能中断列表或库中唯一权限的最大数量 (请参阅下一节) 。 若要详细了解查看大型列表的其他限制，请参阅[管理大型列表和库在 Office 365 中](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)。

### <a name="unique-security-scopes-per-list-or-library"></a>每个列表或库的唯一安全作用域

对于大型列表，设计应具有尽可能少的唯一权限，并总共保持在 5，000 以下。

### <a name="file-size-and-file-path-length"></a>文件大小和文件路径长度

- **250 GB - 文件上载限制。** 适用于上传到"文件"选项卡、SharePoint文档 Microsoft Teams库、OneDrive文件夹Yammer会话的每个单个文件。

- **250 MB - 附加到列表项的文件。** 适用于 Microsoft 列表和SharePoint列表 - 两者基于同一列表平台。

若要了解有关使用新的应用程序应用应用OneDrive 同步限制 (OneDrive.exe) ，请参阅无效[的文件名和文件类型](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)。

### <a name="moving-and-copying-across-sites"></a>跨网站移动和复制

在单个操作中复制/移动多个文件有三个要求：

- 总文件大小不超过 100 GB
- 不超过 30，000 个文件
- 每个文件必须小于 15 GB

### <a name="sync"></a>同步

为获得最佳性能，我们建议在单个网站或工作组网站库中存储的文件OneDrive不超过 300，000 个文件。 尽管 SharePoint Online 可以存储每个库 3000 万个文档，但为了获得最佳性能，我们建议在所有文档库中同步的文件不超过 300，000 个。 此外，如果同步的所有库中包含 300，000 个项目或更多的项目，即使未同步这些库中的所有项目，也会出现相同的性能问题。 如果使用以前的 OneDrive for Business 同步客户端 (Groove.exe) ，则每个库的同步限制为 20，000 个项目 (包括每个团队网站集 5，000) 。

### <a name="versions"></a>版本

50，000 个主要版本和 511 个次要版本。

### <a name="sharepoint-groups"></a>SharePoint 组数

用户可以属于每个网站集或网站集 (5，000) 组，并且每个组最多具有 5，000 个用户。 每个网站集可包含最多 10，000 个 (组) 。

> [!NOTE]
> 有关 Azure AD 组限制，请参阅 [Azure AD 服务](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions) 限制和限制，因为此类限制可能会影响公共和专用组网站成员身份管理。

### <a name="managed-metadata"></a>托管元数据

总数为 100 万个术语，共有 200 万个术语标签和 100 万个术语属性 (这些限制适用于全球 & 网站级别术语组合) 。 1，000 个全局术语集和 1，000 个全局组。

### <a name="overall-site-metadata"></a>整体网站元数据

每个网站 1000 GB (元数据很少达到此大小) 。

### <a name="subsites"></a>子网站

每个网站集 2，000 (2，000) 。 我们建议创建网站，将它们组织到中心，而不是创建子网站。 如果使用子网站，我们建议限制其数量， (高度密集网站) 。

> [!NOTE]
> 你的组织限制为 2，000 个中心网站。 你可能不需要每个功能的中心网站，并且创建中心之前进行一些规划很重要。 有关详细信息，请访问规划[中心SharePoint网站。](/sharepoint/planning-hub-sites)

### <a name="sharepoint-hosted-applications"></a>SharePoint托管的应用程序

每个组织 20，000 个实例。

### <a name="users"></a>用户

每个网站集 200 万个。

> [!NOTE]
> 可以邀请加入网站的网站的来宾数量没有SharePoint限制。 有关外部共享的信息，请参阅外部 [共享概述](/sharepoint/external-sharing-overview)。

## <a name="see-also"></a>另请参阅

[搜索限制SharePoint](/sharepoint/search-limits)