---
title: "SQL Server on Linux の概要 |Microsoft ドキュメント"
description: "ここでは、SQL Server on Linux を実行し、方法の詳細について説明します。"
author: rothja
ms.author: jroth
manager: jhubbard
ms.date: 10/02/2017
ms.topic: article
ms.prod: sql-non-specified
ms.prod_service: database-engine
ms.service: 
ms.component: sql-linux
ms.suite: sql
ms.custom: 
ms.technology: database-engine
ms.assetid: 9dcc6a90-0add-42c2-815b-862e4e2a21ac
ms.workload: Active
ms.openlocfilehash: b598357bb8ebe17ad15fb10e1d74c21c169c1da8
ms.sourcegitcommit: 531d0245f4b2730fad623a7aa61df1422c255edc
ms.translationtype: MT
ms.contentlocale: ja-JP

ms.lasthandoff: 12/01/2017
---
# <a name="sql-server-on-linux"></a>SQL Server on Linux

SQL Server 2017はLinux上で動作します。SQL Server と同じデータベースエンジンで、オペレーティングシステムに関係なく多くの同様の機能とサービスがあります。

## <a name="install"></a>Install

作業を開始するには、次のクイック スタート チュートリアルのいずれかの方法により Linux に SQL Server をインストールします。

- [Red Hat Enterprise Linux にインストールします。](quickstart-install-connect-red-hat.md)
- [SUSE Linux Enterprise Server をインストールします。](quickstart-install-connect-suse.md)
- [Ubuntu をインストールします。](quickstart-install-connect-ubuntu.md)
- [Docker で実行します。](quickstart-install-connect-docker.md)
- [Azure での SQL VM プロビジョニング](/azure/virtual-machines/linux/sql/provision-sql-server-linux-virtual-machine?toc=%2fsql%2flinux%2ftoc.json)

> [!NOTE]
> Docker 自体は複数のプラットフォーム上で動作します。つまり、Linux、Mac、Windows上でDockerイメージを実行できます。

## <a name="connect"></a>Connect

インストール後、Linuxマシン上のSQL Serverインスタンスに接続します。ローカルまたはリモートで、さまざまなツールやドライバで接続できます。クイックスタートチュートリアルでは、[sqlcmd](sql-server-linux-setup-tools.md)コマンドラインツールの使用方法を示します。その他のツールには、次のものがあります。

| ツール | チュートリアル |
|-----|-----|
| Visual Studio Code (VS Code) | [SQL Server on Linux で VS コードを使用します。](sql-server-linux-develop-use-vscode.md) |
| SQL Server Management Studio (SSMS) | [Windows で SSMS を使用して Linux 上の SQL Server に接続するには](sql-server-linux-develop-use-ssms.md) |
| SQL Server Data Tools (SSDT) | [SQL Server on Linux で SSDT を使用します。](sql-server-linux-develop-use-ssdt.md) |

## <a name="explore"></a>Explore

SQL Server 2017 は、Linuxを含むすべてのサポートされているプラットフォーム上で同じデータベースエンジンを使います。多くの既存の機能や能力はLinux上でも同じように動作します。このドキュメントでは、これらの機能の一部をLinuxの観点から公開しています。また、Linuxに固有の要件を持つ領域も紹介します。

SQL Serverに精通している場合は、[リリース ノート](sql-server-linux-release-notes.md)でこのリリースの一般的なガイドラインと既知の問題を確認してください。 そして、[SQL Server on Linux の新](sql-server-linux-whats-new.md) や[新機能の全体的な SQL Server 2017](../sql-server/what-s-new-in-sql-server-2017.md) を確認して下さい。

##  <a name="infotipmediageneralinfotippng-engage-with-the-sql-server-engineering-team"></a>![info_tip](./media/general/info_tip.png) SQL Server エンジニアリング チームと連携する

- [DBA スタック Exchange](https://dba.stackexchange.com/questions/tagged/sql-server): データベースの管理の質問
- [スタックのオーバーフロー](http://stackoverflow.com/questions/tagged/sql-server): 開発の質問
- [MSDN フォーラム](https://social.msdn.microsoft.com/Forums/en-US/home?category=sqlserver): 技術的な質問
- [Microsoft Connect](https://connect.microsoft.com/SQLServer/Feedback): バグ、および要求機能の報告
- [Reddit](https://www.reddit.com/r/SQLServer/): SQL Server の説明

