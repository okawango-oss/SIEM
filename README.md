# SIEM
Security Information and Event Management

## Wazuh:
Die Wazuh Security Information and Event Management (SIEM)-Lösung ist eine zentralisierte Plattform für die Aggregation und Analyse von Telemetriedaten in Echtzeit zur Erkennung von Bedrohungen und zur Einhaltung von Vorschriften. Wazuh sammelt Ereignisdaten aus verschiedenen Quellen wie Endpunkten, Netzwerkgeräten, Cloud-Workloads und Anwendungen für eine breitere Sicherheitsabdeckung.

## XDR:
Die Wazuh Extended Detection and Response (XDR)-Plattform bietet eine umfassende Sicherheitslösung, die Bedrohungen über mehrere IT-Infrastrukturebenen hinweg erkennt, analysiert und auf sie reagiert. Wazuh sammelt Telemetriedaten von Endpunkten, Netzwerkgeräten, Cloud-Workloads, APIs von Drittanbietern und anderen Quellen für eine einheitliche Sicherheitsüberwachung und Schutz.

## Hardware Voraussetzung:
- Für 1 - 25 Agenten
- x86_64 4vCPU
- 8 GB ECC RAM Arbeitsspeicher
- 50 GB Speicher für 90 Tage

## Minimum Hardware Empfehlung für KMU:
- HPE ProLiant MicroServer Gen10 Plus v2

## Software Voraussetzung:
- Debian Bookworm


## Installation von Wazuh:

1. Lade den Wazuh-Installationsassistenten herunter und führe ihn aus.
####   curl -sO https://packages.wazuh.com/4.7/wazuh-install.sh && sudo bash ./wazuh-install.sh -a -I 

2. Sobald der Assistent die Installation abgeschlossen hat, zeigt die Ausgabe die Zugangsdaten und eine Meldung, die bestätigt, dass die Installation erfolgreich war.

3. INFO: Du kannst die Webschnittstelle https://wazuh-dashboard-ip aufrufen. 

User: admin

Password: <ADMIN_PASSWORD> # siehe wazuh-install-files.tar im Installationsverzeichniss

Installation beendet.

Wenn Du zum ersten Mal auf das Wazuh-Dashboard zugreifst, zeigt der Browser eine Warnmeldung an, die besagt, dass das Zertifikat nicht von einer vertrauenswürdigen Stelle ausgestellt wurde. Dies ist zu erwarten und der Benutzer hat die Möglichkeit, das Zertifikat ausnahmsweise zu akzeptieren oder alternativ das System so zu konfigurieren, dass ein Zertifikat einer vertrauenswürdigen Stelle verwendet wird.

## Übersicht
### a) Security Information Management
### b) Threat Detection and Response
### c) Auditing and Policy Monitoring
### d) Regulatory Compliance

![Bildschirmfoto 2024-05-04 um 08 02 40](https://github.com/okawango-oss/SIEM/assets/125760839/ee532975-c39d-40fb-a0c5-bac4c941a63c)

￼
## Event Darstellung:

![Bildschirmfoto 2024-05-04 um 07 36 41](https://github.com/okawango-oss/SIEM/assets/125760839/2e1f9eb5-a107-4015-92f6-327308bb88e6)


