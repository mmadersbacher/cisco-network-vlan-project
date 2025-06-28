# 🧠 Cisco Netzwerkprojekt – VLAN, DHCP, WLAN, VoIP, L3-Routing

## 📌 Projektübersicht

Dieses Projekt stellt ein vollständiges, logisch segmentiertes Unternehmensnetzwerk dar – aufgebaut in **Cisco Packet Tracer**.  
Ziel war es, ein skalierbares und sicheres Netz zu schaffen, das mehrere **VLANs**, zentrale Serverdienste, WLAN sowie **Inter-VLAN-Kommunikation über einen Multilayer-Switch** umfasst.

---

## 🧰 Netzwerkstruktur

![Topologie](Screenshots/topologie.png)

### 🔗 Zentrale Komponente
- **Multilayer-Switch (L3)** zur Verwaltung des Layer-2-Switchings und des Layer-3-Routings  
- Verbindet alle VLANs und regelt kontrollierten Datenfluss

### 🧱 VLAN-Übersicht

| VLAN-ID | Name        | Zweck                                          |
|---------|-------------|------------------------------------------------|
| 10      | Management  | Zugriff für administrative Geräte             |
| 20      | Mitarbeiter | Produktives Arbeitsnetz für Endgeräte         |
| 30      | Gäste       | Internetzugang für Besucher (isoliert)        |
| 40      | VoIP        | Netz für IP-Telefonie, QoS optimiert           |
| 50      | Server      | Zentrale Dienste: DHCP, DNS, Web, File, Mail  |

---

## 🖥️ Infrastruktur & Dienste

- **DHCP**: Zentrale IP-Zuweisung über den Server im VLAN 50  
- **DNS & Webserver**: Lokale Namensauflösung und Hosting-Demo  
- **Access Point**: WLAN für mobiles Arbeiten (Mitarbeiter & Gäste)  
- **Drucker**: Jeweils in VLAN 20 & 30 integriert  
- **Trunk-Links**: Zwischen zentralem Switch und allen Edge-Switches  
- **Access-Ports**: Gerätebindung an dedizierte VLANs  

---

## 📸 Screenshots

- `topologie.png` – Netzwerktopologie vollständig  
- `vlan-config.png` – VLAN-Zuordnung auf den Switchports  
  
> Alle Screenshots befinden sich im Ordner `screenshots/`.

---

## 📁 Projektdateien

| Datei                    | Beschreibung                                |
|--------------------------|---------------------------------------------|
| `projekt.pkt`            | Cisco Packet Tracer Netzwerkdatei           |
| `screenshots/`           | Visualisierung der Konfiguration            |

---

## 🛠️ Technische Highlights

- VLAN-Isolation mit logischer Netztrennung
- Gast-WLAN mit VLAN-Trennung vom Unternehmensnetz

---

## 🎯 Lernziele & Umsetzung

- Anwendung von Layer-2- & Layer-3-Konzepten
- Einsatz logischer Netzwerksegmentierung über VLAN
- DHCP- und DNS-Konfiguration im Firmennetz
- Erweiterung um drahtlose Netzwerke und VoIP-Design
- Einsatz professioneller Dokumentationstechniken

---

## 🛡️ Hinweis

Dieses Projekt dient ausschließlich zu Lern- und Demonstrationszwecken.  
Die Inhalte basieren auf eigenständiger Planung und Umsetzung in einer simulierten Umgebung.

---

## 👣 „Netzwerke baut man nicht für die Gegenwart, sondern für das Wachstum der Zukunft.“

