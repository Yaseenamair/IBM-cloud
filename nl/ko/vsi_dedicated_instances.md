---



copyright:
  years: 2017
lastupdated: "2017-10-25"


---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:table: .aria-labeledby="caption"}


# 전용 인스턴스 프로비저닝

전용 인스턴스를 프로비저닝하는 방법에는 두 가지 옵션이 있습니다. 첫 번째는 {{site.data.keyword.Bluemix}} 카탈로그를 통한 방법이며 두 번째는 {{site.data.keyword.slportal_full}}을 통합 방법입니다. 카탈로그 및 {{site.data.keyword.slportal}}은 고유 로그인 ID를 필요로 합니다. 카탈로그 사용자 이름 및 비밀번호로는 포털에 로그인할 수 없으며 그 반대 또한 마찬가지입니다. {{site.data.keyword.Bluemix_notm}} 카탈로그 또는 {{site.data.keyword.slportal}} 신임 정보를 설정하려면 [{{site.data.keyword.Bluemix_notm}}에 등록](https://console.bluemix.net/docs/admin/adminpublic.html#signing-up-for-bluemix){: new_window}을 참조하십시오.
{:shortdesc}

## IBM Cloud 카탈로그에 로그인
{{site.data.keyword.Bluemix_notm}}에 로그인하여 전용 인스턴스 프로비저닝을 시작하려면 다음 단계를 사용하십시오. 

1. 새 브라우저 창을 열고 [https://console.bluemix.net/catalog/](https://console.bluemix.net/catalog/){: new_window}를 입력하십시오.
2.	**로그인** 링크(오른쪽 상단에 있음)를 클릭하십시오. 
3.	이메일 또는 IBM ID를 입력하고 **계속**을 클릭하십시오.
4.	비밀번호를 입력하고 **로그인**을 클릭하십시오.
5.	**인프라 > 계산**을 선택하십시오.
6.  **Virtual Server** 타일을 클릭하십시오.
7.	**전용 Virtual Server** 옵션을 선택하십시오.
8.  **작성**을 클릭하십시오. 

{{site.data.keyword.slportal}}의 기본 페이지로 이동됩니다.

## Customer Portal에 로그인
{{site.data.keyword.slportal}}에 로그인하여 전용 인스턴스 주문을 시작하려면 다음 단계를 사용하십시오.

1.	새 브라우저 창을 열고 [https://control.softlayer.com](https://control.softlayer.com){: new_window}을 입력하십시오. 
2.	사용자 이름 및 비밀번호를 입력하고 **로그인**을 클릭하거나 **IBM ID로 로그인**을 클릭하십시오.
3.	이메일 또는 IBM ID를 입력하고 **계속**을 클릭하십시오.
4.	비밀번호를 입력하고 **로그인**을 클릭하십시오.

{{site.data.keyword.slportal}}의 기본 페이지로 이동됩니다.

## 전용 인스턴스 프로비저닝
{: #provision-dedicated-instances}
두 가지 방법(**디바이스** 아이콘 또는 **디바이스** 메뉴)을 통해 전용 인스턴스를 프로비저닝할 수 있습니다.

### 디바이스 아이콘을 통한 전용 호스트 인스턴스 프로비저닝
{: #ordering-dedicated-devices-menu}
전용 호스트 인스턴스 프로비저닝을 수행하는 첫 번째 옵션은 {{site.data.keyword.slportal}} 홈 페이지에 있는 **디바이스** 아이콘을 사용하는 것입니다. 다음 단계는 이 프로세스를 단계별로 안내합니다.

1.	**디바이스** 아이콘을 클릭하십시오. **SoftLayer 제품 및 서비스 주문** 창이 표시됩니다. 
2.  전용 Virtual Server 아래에서 **시간별** 또는 **월별**을 선택하십시오. *클라우드 서버 구성* 페이지로 이동됩니다. 

3.	다음 정보를 입력하십시오.
       
    <table>
    <CAPTION>표 1. 전용 호스트 인스턴스 선택사항</CAPTION>
    <THEAD>
    <TR>
    <th>필드</th>
    <th>값</th>
    </TR>
    </THEAD>
    <TBODY>
    <tr>
    <td>수량</td>
    <td>배치될 전용 인스턴스의 수입니다.</td>
    </tr>
    <tr>
    <td>배치</td>
    <td>
    <ul>
    <li>자동 지정 – {{site.data.keyword.Bluemix_notm}}가 인스턴스를 선택된 데이터 센터에 있는 호스트에 자동으로 지정합니다.</li>
    <li>호스트 지정 - 전용 호스트 인스턴스에 사용됩니다. 전용 호스트 및 전용 호스트 인스턴스에 대한 자세한 정보는 [전용 가상 서버](../vsi/vsi_dedicated.html)를 참조하십시오.</li>
    </ul>
    </td>
    </tr>
    <tr>
    <td>데이터 센터</td>
    <td>인스턴스가 프로비저닝될 데이터 센터를 선택하십시오.</td>
    </tr>
    <tr>
    <td>계산 인스턴스</td>
    <td> 프로비저닝 주문의 각 인스턴스에 대한 메모리 및 CPU를 선택하십시오.</td>
    </tr>
    <tr>
    <td>RAM</td>
    <td> 프로비저닝 주문의 각 인스턴스에 대한 RAM을 선택하십시오.</td>
    </tr>
    <tr>
    <td>운영 체제</td>
    <td>인스턴스의 운영 체제를 선택하십시오. 서버와 운영 체제 간에 충돌이 있는 경우에는 오류 메시지가 발행된다는 점을 참고하십시오. 예를 들면, Microsoft SQL Server에 대해 Linux를 선택하는 경우가 있습니다.</td>
    </tr>
    <tr>
    <td>첫 번째 디스크</td>
    <td>주문 내의 각 인스턴스에 대해 SAN 또는 로컬을 선택하십시오.</td>
    </tr>
    <tr>
    <td>추가 디스크</td>
    <td>전용 인스턴스당 최대 네 개의 부트 디스크(SAN 또는 로컬)를 프로비저닝할 수 있습니다.</td>
    </tr>
    <td>네트워크 옵션</td>
    <td> 적절한 옵션을 선택하거나 기본값을 사용하십시오.</td>
    </tr>
    <tr>
    <td>추가 기능</td>
    <td> 적절한 옵션을 선택하거나 기본값을 사용하십시오.</td>
    </tr>
    <tr>
    </TBODY>
    </table> 

4.	**주문에 추가** 단추를 클릭하십시오. 체크아웃 페이지로 경로 재지정됩니다.
5.  *고급 시스템 구성*의 *체크아웃* 페이지에 다음 정보를 입력하십시오.

<table>
    <CAPTION>표 2. 전용 인스턴스 고급 시스템 구성</CAPTION>
    <THEAD>
    <TR>
    <th>필드</th>
    <th>값</th>
    </TR>
    </THEAD>
    <TBODY>
    <tr>
    <td>VLAN 선택</td>
    <td>이미 하나 이상의 서버를 주문한 경우에는 계정의 VLAN에 새 서버를 추가하십시오.</td>
    </tr>
    <tr>
    <td>프로비저닝 스크립트</td>
    <td>프로비저닝 후 특정 단계를 자동화할 수 있게 해 주는 스크립트를 제공하십시오.</td>
    </tr>
    <tr>
    <td>SSH 키</td>
    <td>서버가 프로비저닝된 후 서버에 로그인할 수 있게 해 주는 SSH 키의 공개 키를 제공하십시오.</td>
    </tr>
    <tr>
    <td>사용자 메타데이터</td>
    <td>사용자 정의 프로비저닝 스크립트를 위한 선택적 메타데이터입니다.</td>
    </tr>
    <tr>
    <td>호스트 이름</td>
    <td>서버의 영구적 또는 임시 이름(예: server1)을 입력하십시오.</td>
    </tr>
    <tr>
    <td>도메인</td>
    <td>인터넷 도메인 이름과 충돌하지 않는 하위 도메인 이름(예: test.acme.com)을 입력하십시오.</td>
    </tr>
    </TBODY>
    </table>

6.  **클라우드 서비스 이용 약관** 및 **써드파티 서비스 계약** 선택란을 클릭하십시오.
7. 지불 정보를 확인하거나 입력하고 **주문 제출** 단추를 클릭하십시오. 사용자의 프로비저닝 주문 번호가 있는 화면으로 이동됩니다. 이는 프로비저닝 주문 영수증이기도 하므로 사용자는 이 화면을 인쇄할 수 있습니다.

    일련의 이메일(프로비저닝 주문 확인, 프로비저닝 주문 승인 및 처리, 프로비저닝 완료)이 관리자에게 발송됩니다. 프로비저닝 완료 이메일은 {{site.data.keyword.Bluemix_notm}}에 로그인한 후 **디바이스 세부사항** 페이지로 바로 이동하는 링크를 포함합니다. 또 다른 옵션은 {{site.data.keyword.slportal}}에 직접 로그인하는 것입니다.

### 디바이스 메뉴를 통한 전용 인스턴스 프로비저닝

두 번째 옵션은 기본 {{site.data.keyword.slportal}} 페이지에서 **디바이스** 메뉴를 통해 전용 인스턴스를 프로비저닝하는 것입니다. 다음 단계는 이 프로세스를 단계별로 안내합니다.

1.	**디바이스 > 디바이스 목록**을 클릭하십시오. 
 
    *디바이스* 페이지는 계정에 속한 모든 디바이스 유형(가상 서버, 베어메탈 서버, 전용 호스트 및 NetScaler 애플리케이션 제공 제어기)을 표시합니다. 

2.	페이지의 오른쪽에 있는 **디바이스 주문** 링크를 클릭하십시오.
    **SoftLayer 제품 및 서비스 주문** 창이 표시됩니다.
3.	[디바이스 아이콘을 통한 전용 인스턴스 프로비저닝](#ordering-dedicated-devices-menu)의 단계를 2단계부터 따르십시오.

### 다음 단계
가상 서버가 프로비저닝된 후에는 이 서버의 관리를 시작할 수 있습니다. 자세한 정보는 [가상 서버 관리](../vsi/vsi_managing.html)를 참조하십시오.
