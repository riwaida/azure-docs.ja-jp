---
title: Always-On VPN ユーザー トンネルの構成
titleSuffix: Azure VPN Gateway
description: この記事では、VPN ゲートウェイに対して Always On VPN ユーザー トンネルを構成する方法について説明します。
services: vpn-gateway
author: cherylmc
ms.service: vpn-gateway
ms.topic: conceptual
ms.date: 03/12/2020
ms.author: cherylmc
ms.openlocfilehash: 56934dd13661d8f623e673e2817e87618675c7ed
ms.sourcegitcommit: 2ec4b3d0bad7dc0071400c2a2264399e4fe34897
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/28/2020
ms.locfileid: "79502258"
---
# <a name="configure-an-always-on-vpn-user-tunnel"></a>Always On VPN ユーザー トンネルの構成

[!INCLUDE [intro](../../includes/vpn-gateway-vwan-always-on-intro.md)]

## <a name="configure-the-gateway"></a>ゲートウェイを構成する

 IKEv2 と証明書ベースの認証を使用するように VPN ゲートウェイを構成するには、[ポイント対サイト VPN 接続の構成](vpn-gateway-howto-point-to-site-resource-manager-portal.md)に関する記事の手順に従ってください。

## <a name="configure-a-user-tunnel"></a>ユーザー トンネルを構成する

[!INCLUDE [user configuration](../../includes/vpn-gateway-vwan-always-on-user.md)]

## <a name="to-remove-a-profile"></a>プロファイルを削除するには

プロファイルを削除するには、次の手順に従います。

1. 次のコマンドを実行します。

   ```powershell
   C:\> Remove-VpnConnection UserTest  
   ```

1. 接続を切断し、 **[Connect automatically]\(自動的に接続する\)** チェック ボックスをオフにします。

   ![クリーンアップ](./media/vpn-gateway-howto-always-on-user-tunnel/disconnect.jpg)

## <a name="next-steps"></a>次のステップ

発生する可能性のある接続の問題をトラブルシューティングするには、「[Azure ポイント対サイト接続の問題](vpn-gateway-troubleshoot-vpn-point-to-site-connection-problems.md)」を参照してください。
