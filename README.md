# IDS/IPS Lab mit pfSense & Suricata 🛡️

Ein praxisorientiertes Abschlussprojekt zur Implementierung eines Intrusion Detection & Prevention Systems (IDS/IPS) in einer virtualisierten Testumgebung mit pfSense, Suricata und Kali Linux.

## 🎯 Ziel

Ziel war es, Angriffe wie Portscans oder DoS frühzeitig zu erkennen und aktiv zu blockieren. Die Lösung wurde in einer Hyper-V-Testumgebung auf mehreren virtuellen Maschinen umgesetzt.

## 🛠️ Technologien & Tools

- **Hyper-V** – Virtualisierung
- **pfSense** – Firewall & Gateway
- **Suricata** – IDS/IPS
- **SIDmgmt** – Regelmanagement
- **Kali Linux** – Angriffssimulation (Nmap)
- **WinSCP & PuTTY** – Dateiübertragung & SSH-Verwaltung

## 🧪 Architektur

- 3 isolierte Netzwerke (LAN, OPT1, OPT2)
- Windows-Clients, Kali als Angreifer, pfSense als zentrale Firewall
- Suricata auf LAN/OPT1 im IDS- und IPS-Modus

## 📊 Highlights & Learnings

- IDS vs. IPS: Vergleich & Tests mit realen Angriffsszenarien
- Asymmetrisches Routing: Analyse & Debugging
- Einsatz von Snort- & Emerging Threats-Regeln
- Konfigurierbare Regel-Prioritäten mit SIDmgmt
- Performancevergleich Legacy- vs. Inline-IPS

## 🔍 Testphase

> IDS → Alerts in Logs  
> IPS → Aktives Blockieren (Suricata DROP)  
> Fokus auf Scan-, Exploit- & Malware-Signaturen

## 📎 Struktur des Repos

Projektdoku im Anhang (Docx)
-Beispielkonfigs pfSense / Suricata  
-GUI & Alerts  
-Ergebnisse  
 

## ✅ Status

Abgeschlossen. Ideal für Fortsetzung im Bereich Netzwerksicherheit, z. B. mit Zeek, ELK oder Zabbix.

---

**Autor:** Kai Kauffmann  
📫 Kontakt: linkedin.com/in/kai-kauffmann 
📁 [Hier geht’s zur vollständigen Dokumentation](./docs/Projektdokumentation.docx)
