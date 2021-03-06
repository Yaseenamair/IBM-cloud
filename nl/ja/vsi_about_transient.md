---



copyright:
  years: 2017, 2018
lastupdated: "2018-04-27"


---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:tip: .tip}
{:table: .aria-labeledby="caption"}

# 一時仮想サーバー
{{site.data.keyword.BluVirtServers}} の一時オファリングは、柔軟なワークロードがあり、コストを削減する必要がある場合に適したオプションです。 ワークロードを一時仮想サーバー上で実行することで、コストを節約できます。 一時インスタンスは、使用可能な未使用の容量がある場合にプロビジョンされます。 そのため、完全なオンデマンドのアカウントにデータ・センター・リソースが必要な場合は、これらのリソースを失う可能性もあります。 一時インスタンスは、これらのリソースを再利用する必要があるときに、最初にオンにしたものからプロビジョン解除されます。   

一時仮想サーバーは、非実稼働ワークロードに理想的です。 例えば、一時インスタンスを使用して、アプリケーションのテストと開発や、常時のアップタイムを必要としない環境でのスケーラビリティーのテストを行うことができます。

## 要件
一時インスタンスを活用するには、以下のパブリック仮想サーバーの選択肢を使用してプロビジョンする必要があります。
* 一時
* ホストのロケーション。以下のデータ・センターから選択できます。
    * MEX01 
    * SEO01
    * PAR01

一時インスタンスは、SAN バックアップ付きストレージを使用するパブリック・インスタンスです。

## 通知
{{site.data.keyword.slapi_short}} を使用して、一時インスタンスにリソースを使用できるときに通知を受信することができます。 API を使用して、リソースが使用可能になったときに一時仮想サーバーをプログラムでプロビジョンすることもできます。 同様に、API を使用して、リソースが使用不可になったときにインスタンスのプロビジョニングをプログラムで停止することができます。詳しくは、[自動再利用通知の構成](configuring-automated-reclaim-notifications.html)に関するセクションを参照してください。

## 制限
一時仮想サーバーをプロビジョンする前に、以下の制限を検討してください。

* サポートされる同時インスタンスの数は、アカウント全体のデバイス割り当て量の一部です。 同時インスタンスの制限について詳しくは、[FAQ: 仮想サーバー](../vsi/vsi_faqs_vs.html#concurrent)を参照してください。
* 一時インスタンスは、アップグレードしたりダウングレードすることはできません。
* リソースは、通知なしでいつでも再利用できます。
* 一時インスタンスは、ローカル・ストレージを使用できません。
* 一時インスタンスは、SAN バックアップ付きストレージ (平衡型、コンピュート、メモリー) のみを使用します。
* 一時インスタンスは、GPU ベースのフレーバーを使用できません。


## 次のステップ

仮想サーバー・フレーバーを検討して選択したら、一時仮想サーバーをプロビジョンします。 最初に、以下の情報を検討してください。
1. [プロビジョニングの選択](../vsi/vsi_public_selections.html)
2. [一時インスタンスのプロビジョニング](../vsi/vsi_provision_transient.html)
