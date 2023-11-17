---
description: VistaUpdaterについての解説
---

# VistaUpdaterについて

VistaUpdaterは、Windows Vista及びWindows 7を更新できるようにするツールです。

## VistaUpdaterがリリースされた理由

初めに、2020年8月の出来事を知る必要があります。

Microsoftは、2020年8月にWindows UpdateでSHA-1ベースのエンドポイントを廃止しました。

そのことにより、Windows VistaとWindows 7ではWindows Updateが利用できなくなりました。

Windows Updateでは、セキュリティ更新、Service Pack、ドライバーなどを取得することができますが、その方法が利用できなくなったのです。

そこで、2023年にVistaUpdaterをリリースしたのです。

### VistaUpdaterの仕組み

Windows Server 2008 (SP2) では、SHA-2ベースのエンドポイントに対応するためのアップデートが配信されています。

Windows VistaとWindows Server 2008のベースは同じなので、Server 2008の更新プログラムを適用できます。

その仕様を使用すると、Windows VistaでもWindows Updateが使用できるようになると思います。

ただし、SHA-2ベースのエンドポイントに対応するための更新プログラムをインストールしてもエラー(80072EFE)が発生します。

理由としては、Windows VistaでSHA-2ベースのエンドポイントをサポートする更新プログラムをインストールしても、Windows Update Client (Windows Updateの基礎)が更新されません。

VistaUpdaterは、Windows Update Clientの更新とVistaでも使えるようにする改造も行います。

## VistaUpdaterを使用する際の注意点

VistaUpdaterはとても便利なツールですが、使用する際に注意することがあります。

* PCを破壊されても、完全な補償はVistaUpdaterがしないこと。

VistaUpdaterは破壊された時のサポートも行いますが、元の状態に修復できなくても自己責任とさせていただきます。

## お願い

VistaUpdaterのサイトは広告がありません。なので、アフィリエイトをしていません。

PatreonやBuy me a coffeeでサポートしていただくと、VistaUpdaterを継続するための支援ができます。

素晴らしいプログラムと思った方でお金がある方、支援をお願いします。



