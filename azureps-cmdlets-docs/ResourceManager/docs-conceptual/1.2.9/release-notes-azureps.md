---
title: "Azure PowerShell の変更履歴 | Microsoft Docs"
description: "Azure PowerShell の最新リリースで行われた変更の履歴です。"
services: azure
author: sdwheeler
ms.author: sewhee
manager: carmonm
ms.service: azure-powershell
ms.product: azure
ms.devlang: powershell
ms.topic: conceptual
ms.workload: 
ms.date: 05/18/2017
ms.openlocfilehash: 5fe7591855577e083aad5923aed37b18d0b2a40c
ms.sourcegitcommit: 226527be7cb647acfe2ea9ab151185053ab3c6db
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/29/2017
---
# <span data-ttu-id="dafd5-103">リリース ノート</span><span class="sxs-lookup"><span data-stu-id="dafd5-103">Release notes</span></span>
<a id="release-notes" class="xliff"></a>

<span data-ttu-id="dafd5-104">これは Azure PowerShell の今回のリリースで行われた変更の一覧です。</span><span class="sxs-lookup"><span data-stu-id="dafd5-104">This is a list of changes made to Azure PowerShell in this release.</span></span>

## <span data-ttu-id="dafd5-105">バージョン 1.2.9</span><span class="sxs-lookup"><span data-stu-id="dafd5-105">Version 1.2.9</span></span>
<a id="version-129" class="xliff"></a>

<span data-ttu-id="dafd5-106">このリリースの変更</span><span class="sxs-lookup"><span data-stu-id="dafd5-106">Changes This Release</span></span>

* <span data-ttu-id="dafd5-107">AzureRm.AzureStackAdmin モジュール</span><span class="sxs-lookup"><span data-stu-id="dafd5-107">AzureRm.AzureStackAdmin Module</span></span>
    + <span data-ttu-id="dafd5-108">管理者の Azure Resource Manager とテナントの Azure Resource Manager の分割に対応するために Add-AzureRmResourceProviderRegistration コマンドレットを変更しました。</span><span class="sxs-lookup"><span data-stu-id="dafd5-108">Changes in the Add-AzureRmResourceProviderRegistration cmdlet for the support of Admin Azure resource manager and tenant azure resource manager split.</span></span> <span data-ttu-id="dafd5-109">新しいパラメーター (-ResourceManagerType) を追加しました。</span><span class="sxs-lookup"><span data-stu-id="dafd5-109">A new parameter -ResourceManagerType has been added.</span></span>
    + <span data-ttu-id="dafd5-110">各コマンドレットから -AdminUri、-ApiVersion、-SubscriptionId、-Token の各パラメーターを削除しました。</span><span class="sxs-lookup"><span data-stu-id="dafd5-110">Removal of the parameters -AdminUri, -ApiVersion, -SubscriptionId and -Token from each cmdlets.</span></span> <span data-ttu-id="dafd5-111">これらのパラメーターが廃止予定であると、かねてからお伝えしてきましたが、今回でそれらが削除されたことになります。</span><span class="sxs-lookup"><span data-stu-id="dafd5-111">We have been printing warnings that these parameters will be deprecated and now they got removed.</span></span>
* <span data-ttu-id="dafd5-112">AzureStackStorage モジュール</span><span class="sxs-lookup"><span data-stu-id="dafd5-112">AzureStackStorage module</span></span>
    + <span data-ttu-id="dafd5-113">コンテナーの移行のシナリオに対応するために新しいコマンドレットを追加しました。</span><span class="sxs-lookup"><span data-stu-id="dafd5-113">Added new cmdlets to support container migration scenarios.</span></span>
    + <span data-ttu-id="dafd5-114">内部コンポーネントと基になる機能を参照するコマンドレットを削除しました。</span><span class="sxs-lookup"><span data-stu-id="dafd5-114">Removed cmdlets referring to internal components and underlying features.</span></span>
* <span data-ttu-id="dafd5-115">AzureRM.BootStrapper</span><span class="sxs-lookup"><span data-stu-id="dafd5-115">AzureRM.BootStrapper</span></span>
    + <span data-ttu-id="dafd5-116">バージョン プロファイルを使って Azure PowerShell コマンドレットのバージョンを管理する新しいモジュールを作成しました。</span><span class="sxs-lookup"><span data-stu-id="dafd5-116">Created new module to manage versions of Azure PowerShell cmdlets through the use of version profiles</span></span>