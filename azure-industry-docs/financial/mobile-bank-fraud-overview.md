---
title: 手机银行欺诈
author: dstarr
ms.author: dastarr
ms.date: 09/26/2018
ms.topic: article
ms.service: industry
description: 概述了手机银行欺诈
ms.openlocfilehash: f1ddd07428d2abf63337d63e64b7d703a4cc345d
ms.sourcegitcommit: 76f2862adbec59311b5888e043a120f89dc862af
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/03/2018
ms.locfileid: "51654144"
---
# <a name="mobile-bank-fraud"></a><span data-ttu-id="3ead0-103">手机银行欺诈</span><span class="sxs-lookup"><span data-stu-id="3ead0-103">Mobile Bank Fraud</span></span>

<span data-ttu-id="3ead0-104">在过去，银行欺诈检测是通过规则引擎完成，它通过回答一系列二元问题来简单回答这是否是欺诈性交易：“是”或“否”。</span><span class="sxs-lookup"><span data-stu-id="3ead0-104">In the past, bank fraud detection was accomplished using a rules engine, which went down a set of binary questions to arrive at a simple “yes or no” to the question: is this a fraudulent transaction?</span></span> <span data-ttu-id="3ead0-105">如今，大多数银行业务都是联机完成的，网络罪犯使用的窃取方法都很复杂。</span><span class="sxs-lookup"><span data-stu-id="3ead0-105">Today most banking is done online, and cybercriminals are using sophisticated ways to steal.</span></span> <span data-ttu-id="3ead0-106">一旦帐户被入侵，盗窃者只需几分钟，即可窃取数千个帐户。</span><span class="sxs-lookup"><span data-stu-id="3ead0-106">And once an account is compromised, thieves need only a few minutes to steal thousands.</span></span> <span data-ttu-id="3ead0-107">欺诈检测必须是准实时发生才能生效，而规则引擎则无法满足此需求。</span><span class="sxs-lookup"><span data-stu-id="3ead0-107">Fraud detection must happen in near-real-time to be effective, and a rules engine will not suffice.</span></span> <span data-ttu-id="3ead0-108">相反，需要将高级数据分析等新工具与机器学习相结合，以适应新威胁。</span><span class="sxs-lookup"><span data-stu-id="3ead0-108">Instead, new tools such as advanced data analytics are combined with machine learning to adapt to new threats.</span></span> <span data-ttu-id="3ead0-109">看似无害的数据可用于确定用户是否真实存在。比如，“此设备或使用者多久登录一次？”等问题</span><span class="sxs-lookup"><span data-stu-id="3ead0-109">Data that seems innocuous can be used to determine if a user is real—questions such as "how frequently does this device or consumer log in?"</span></span> <span data-ttu-id="3ead0-110">可用于发现欺诈行为。</span><span class="sxs-lookup"><span data-stu-id="3ead0-110">can be used to spot fraud.</span></span>

<span data-ttu-id="3ead0-111">本手机银行欺诈解决方案指南逐步介绍了挑战，以及可用于构建欺诈检测解决方案（即在两秒内回答“是”或“否”）的策略。</span><span class="sxs-lookup"><span data-stu-id="3ead0-111">Our solution guide on mobile bank fraud walks through the challenge and the strategies that can be used to build a fraud-detection solution—one that answers yes or no in two seconds.</span></span>