---



copyright:
  years: 2017, 2018
lastupdated: "2018-02-28"


---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:table: .aria-labeledby="caption"}

# 仮想サーバーの概説
{{site.data.keyword.BluVirtServers}} のデプロイは、ほんの数分で行うことができます。 仮想サーバーは、ユーザーが選択した仮想サーバー・イメージから、ワークロードに適した地理的地域にデプロイされます。
{:shortdesc}

仮想サーバーの作成時に、パブリック (マルチテナンシー) 環境か専用 (単一テナンシー) 環境を選択することができます。 その後、選択した環境に応じて、時間単位の仮想サーバー、月単位の仮想サーバー、または一時仮想サーバーを選択する必要もあります。 パブリック仮想サーバーの場合、さらに SAN ベースのストレージかローカル・ストレージのいずれかを使用するように選択します。

## 始めに

始めに、以下の前提条件を確認してください。

  1. 仮想サーバーをオーダーするには、アップグレードされたアカウントを持っている必要があります。 このプロセスにはある程度時間がかかり、続行する前にユーザーの要求が承認される必要があります。 アカウントのアップグレードについて詳しくは、[IBM ID への切り替え](https://console.bluemix.net/docs/admin/softlayerlink.html)を参照してください。
  2. デプロイメント・オプションを確認および選択します。 詳しくは、以下のトピックを参照してください。

|デプロイメント・オプション                           |説明                                        |
| --------------------------------------------------------- | --------------------------------------------------- |
|[パブリック仮想サーバー](../vsi/vsi_public.html)            |IBM が管理するマルチテナンシー仮想サーバー・デプロイメント |
|[一時仮想サーバー](../vsi/vsi_about_transient.html)|割引コストで提供され、柔軟なワークロードに最適な、IBM が管理するマルチテナンシー仮想サーバー・デプロイメント |
|[専用仮想サーバー](../vsi/vsi_dedicated.html)      |IBM が管理する単一テナンシー仮想サーバー・デプロイメント             |
{: caption="表 1. デプロイメント・オプション" caption-side="top"}   

## 仮想サーバーのプロビジョニング

デプロイメント・オプションを決定したら、プロビジョニング・プロセスを開始します。

|プロビジョニングの説明                                         |説明                                            |
| -------------------------------------------------------------------------- | ------------------------------------------------------- |
|[パブリック・インスタンスのプロビジョニング](../vsi/vsi_provision_public.html)                |さまざまなオプションによるパブリック・インスタンスのプロビジョン             |
|[一時インスタンスのプロビジョニング](../vsi/vsi_provision_transient.html)                |さまざまなオプションによる一時インスタンスのプロビジョン            |
|[専用ホストおよび専用インスタンスのプロビジョニング](../vsi/vsi_provision_dedicated.html)|専用ホスト上のプライベート・インスタンスまたは専用インスタンスのプロビジョン|
{: caption="表 2. プロビジョニング情報" caption-side="top"}

## 次のステップ

仮想サーバーがプロビジョンされて使用可能になったら、{{site.data.keyword.slportal_full}}または {{site.data.keyword.slapi_full}} を使用して仮想サーバーを構成できます。 詳しくは、[仮想サーバーの構成](../vsi/vsi_configuring.html)を参照してください。
