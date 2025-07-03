# Cisco Netzwerkprojekt – VLAN, DHCP, WLAN, VoIP, L3-Routing

## Projektübersicht

Dieses Projekt dokumentiert den Aufbau eines skalierbaren, logisch segmentierten Unternehmensnetzwerks mit Hilfe von Cisco Packet Tracer. Das Netzwerk umfasst mehrere VLANs, zentrale Serverdienste, WLAN und die Inter-VLAN-Kommunikation über einen Multilayer-Switch.

---

## Netzwerkstruktur

**Topologie:** Ein zentraler Multilayer-Switch (Layer 3) steuert sowohl Layer-2 Switching als auch Layer-3 Routing und verbindet alle VLANs.

**VLAN-Übersicht:**

| VLAN-ID | Name        | Zweck                                       |
|---------|-------------|---------------------------------------------|
| 10      | Management  | Zugriff für administrative Geräte           |
| 20      | Mitarbeiter | Produktives Arbeitsnetz für Endgeräte       |
| 30      | Gäste       | Isolierter Internetzugang für Besucher      |
| 40      | VoIP        | Netzwerk für IP-Telefonie mit QoS-Optimierung |
| 50      | Server      | Zentrale Dienste: DHCP, DNS, Web, Datei, Mail |

---

## Infrastruktur & Dienste

- DHCP-Server zur zentralen IP-Vergabe im Server-VLAN  
- Lokaler DNS- und Webserver zur Namensauflösung und Hosting  
- Access Points für WLAN-Zugang, getrennt für Mitarbeiter und Gäste  
- Drucker in den VLANs für Mitarbeiter und Gäste  
- Trunk-Links zwischen zentralem Switch und Edge-Switches  
- Access-Ports, die Endgeräte VLAN-spezifisch zuweisen  

---

## Technische Highlights

- VLAN-Isolation mit logischer Netztrennung für Sicherheit  
- Gast-WLAN mit separater VLAN-Konfiguration  
- QoS-Konfiguration für VoIP-Traffic zur Optimierung der Sprachqualität  
- Einsatz von Layer-3-Routing auf Multilayer-Switch für Inter-VLAN-Kommunikation  

---

## Screenshots und Dateien

- `topologie.png` – vollständige Netzwerktopologie  
- `vlan-config.png` – Beispielkonfiguration der VLAN-Zuweisung auf Switch-Ports  
- Projektdatei: `projekt.pkt` (Cisco Packet Tracer Datei)  
- Screenshots befinden sich im Verzeichnis `screenshots/`

---

## Lernziele und Umsetzung

- Praktische Anwendung von Layer-2- und Layer-3-Netzwerkkonzepten  
- Segmentierung und Netzwerksicherheit durch VLANs  
- Konfiguration zentraler Dienste wie DHCP und DNS  
- Einbindung von drahtlosem Netzwerk und VoIP-Komponenten  
- Professionelle Dokumentation und Visualisierung der Netzwerkarchitektur  

---

## Haftungsausschluss

Das Projekt dient ausschließlich Lern- und Demonstrationszwecken. Es basiert auf eigenständiger Planung und Umsetzung in einer simulierten Umgebung.

---

## Autor

Mario Madersbacher
