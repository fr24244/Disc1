# DigiLab ↔ Discord Integration mit Node-RED

Dieses Projekt verbindet DigiLab mit einem Discord-Server mithilfe von **Node-RED**.

##  Was das Projekt macht

Sobald ein Ereignis in DigiLab passiert (z. B. ein neues Ergebnis oder eine Warnung), wird automatisch eine Nachricht in einem bestimmten Discord-Kanal gepostet.

##  Wie es funktioniert

- **Node-RED** hört auf Ereignisse von DigiLab.
- Die Daten werden im Flow verarbeitet.
- Danach wird eine formatierte Nachricht an Discord gesendet – entweder über einen Webhook oder einen Bot.

##  Voraussetzungen

- Node-RED ist installiert und läuft
- Zugriff auf die DigiLab-API oder Eventquelle
- Ein Discord-Bot oder ein Webhook-Link
- Optional: JSON- oder HTTP-Nodes in Node-RED

##  Einrichtung

1. Dieses Repository klonen oder den Node-RED Flow importieren.
2. Discord Webhook oder Bot-Token einrichten.
3. DigiLab-Datenquelle anschließen.
4. Flow nach Bedarf anpassen.
5. Deployen und testen!

##  Beispiel

> „Wenn ein neues Ergebnis in DigiLab verfügbar ist, postet der Discord-Bot z. B.:  
> ` Neues Ergebnis für Patient X – Test: Blutbild – Status: Abgeschlossen`“

##  Mitwirken

Forks und Verbesserungen sind willkommen! Pull Requests gerne gesehen.

##  Lizenz

MIT – frei verwendbar.

---

Erstellt mit ❤ dank Node-RED + Discord
