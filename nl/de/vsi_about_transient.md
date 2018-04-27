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
{:tip: .tip}
{:table: .aria-labeledby="caption"}

# Transiente virtuelle Server
Das transiente Angebot von {{site.data.keyword.BluVirtServers}} ist eine gute Option, wenn Sie flexible Workloads haben und Kosten sparen möchten. Sie können Geld sparen, indem Sie Ihre Workload auf einem transienten virtuellen Server ausführen. Transiente Instanzen werden bereitgestellt, wenn ungenutzte Kapazitäten verfügbar sind. Wenn also Rechenzentrumsressourcen vollständig für bedarfsgesteuerte Konten benötigt werden, können Sie diese Ressourcen auch verlieren. Die Bereitstellung transienter Instanzen wird nach der Methode First In/First Out aufgehoben, wenn diese Ressourcen freigegeben werden müssen.   

Transiente virtuelle Server sind ideal für Nicht-Produktions-Workloads. Sie können beispielsweise eine transiente Instanz zum Testen oder Entwickeln von Anwendungen oder zum Testen der Skalierbarkeit in Umgebungen, für die keine konstante Verfügbarkeit erforderlich ist, verwenden.

## Voraussetzungen
Damit Sie die Vorteile transienter Instanzen nutzen können, müssen Sie die Bereitstellung mit den folgenden Optionen für öffentliche virtuelle Server durchführen:
* Transient
* Rechenzentrum Mex01

Transiente Instanzen sind öffentliche Instanzen, die SAN-gestützten Speicher verwenden.

## Benachrichtigungen
Sie können die {{site.data.keyword.slapi_short}} zum Empfangen von Benachrichtigungen verwenden, wenn Ressourcen für eine transiente Instanz verfügbar sind. Sie können die API auch verwenden, um einen transienten virtuellen Server programmgesteuert bereitzustellen, wenn Ressourcen verfügbar werden. Analog können Sie die API verwenden, um die Bereitstellung von Instanzen programmgesteuert zu stoppen, wenn Ressourcen nicht mehr verfügbar sind.  

## Einschränkungen
Beachten Sie die folgenden Einschränkungen, bevor Sie einen transienten virtuellen Server bereitstellen.

* Die Anzahl der unterstützten gleichzeitig ausgeführten Instanzen ist Teil Ihres kontoweiten Einheitenkontingents. Weitere Informationen zu Einschränkungen bei gleichzeitig ausgeführten Instanzen finden Sie unter [FAQs: Virtuelle Server](vsi_faqs_vs.html#concurrent).
* Für transiente Instanzen kann kein Upgrade oder Downgrade durchgeführt werden.
* Ressourcen können jederzeit ohne Benachrichtigung freigegeben werden.
* Transiente Instanzen können keinen lokalen Speicher verwenden.
* Transiente Instanzen verwenden nur SAN-gestützten Speicher (ausgeglichen, Compute, Speicher).
* Transiente Instanzen können keine GPU-gestützten Versionen (Flavors) verwenden.


## Nächste Schritte

Nach dem Überprüfen und Auswählen der Version (Flavor) Ihres virtuellen Servers können Sie nun Ihren transienten virtuellen Server bereitstellen. Lesen Sie zunächst die folgenden Informationen:
1. [Auswahlen für die Bereitstellung](../vsi/vsi_public_selections.html)
2. [Bereitstellung transienter Instanzen](../vsi/vsi_provision_transient.html)