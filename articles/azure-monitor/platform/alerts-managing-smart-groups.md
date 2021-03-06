---
title: スマート グループを管理する
description: アラート インスタンスに対して作成されたスマート グループを管理します
ms.topic: conceptual
ms.subservice: alerts
ms.date: 09/24/2018
ms.openlocfilehash: d7077e51282864f1208080838a1bb94ddd773b7d
ms.sourcegitcommit: 2ec4b3d0bad7dc0071400c2a2264399e4fe34897
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/28/2020
ms.locfileid: "77667467"
---
# <a name="manage-smart-groups"></a>スマート グループを管理する

[スマート グループ](https://aka.ms/smart-groups)では、機械学習アルゴリズムを使用して、同時発生または類似性に基づいてアラートがグループ化されるので、ユーザーは、各アラートを個別に管理するのではなく、スマート グループを管理することができます。 この記事では、Azure Monitor でスマート グループにアクセスしてそれを使用する手順について説明します。

1. アラート インスタンスに対して作成されたスマート グループを表示するには、次のどちらかの方法を使用できます。

     1. **[Alerts Summary]\(アラートの概要\)** ページで **[スマート グループ]** をクリックします    
    ![Monitoring](./media/alerts-managing-smart-groups/sg-alerts-summary.jpg)
    
     1. [すべてのアラート] ページで [スマート グループ別のアラート] をクリックします   
     ![監視](./media/alerts-managing-smart-groups/sg-all-alerts.jpg)

2. アラート インスタンスに対して作成されたすべてのスマート グループのリスト ビューが表示されます。 複数のアラートを選別する代わりに、スマート グループを処理できるようになります。   
![監視](./media/alerts-managing-smart-groups/sg-list.jpg)

3. いずれかのスマート グループをクリックすると詳細ページが開き、グループ化の理由とメンバーのアラートを見ることができます。 この集計により、複数のアラートを選別するのではなく、1 つのスマート グループを扱うことができるようになります。   
![監視](./media/alerts-managing-smart-groups/sg-details.jpg)
