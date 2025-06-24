# Digilab-Discord-Status mit Node-RED

Dieses Projekt verbindet ein Digilab-Gerät mit Discord über Node-RED.

## Ziel

Wenn ich online bin, soll auf dem kleinen Digilab-Bildschirm angezeigt werden, dass ich online bin. Außerdem soll angezeigt werden, wenn jemand eine Nachricht auf Discord schreibt.

## Voraussetzungen

- Node-RED installiert
- Discord-Bot mit Token
- Digilab-Gerät mit Bildschirm
- Verbindung zwischen Node-RED und dem Bildschirm (z. B. seriell, MQTT oder HTTP)

## Funktionen

- Zeigt auf dem Bildschirm an, wenn ich online bin
- Zeigt neue Discord-Nachrichten live auf dem Bildschirm an
- Läuft vollständig über Node-RED-Workflows

## Einrichtung

1. Erstelle einen Discord-Bot und kopiere den Token.
2. Installiere Node-RED und richte die folgenden Nodes ein:
   - `discord-connector` (z. B. über ein Node-RED-Discord-Modul)
   - `function`-Node zur Verarbeitung der Nachrichten
   - Node zur Ausgabe auf dem Digilab-Bildschirm (je nach Verbindung)
3. Integriere den Bot in deinen Discord-Server.
4. Verbinde Node-RED mit dem Digilab-Gerät.

## Beispielanzeige

- **Online-Status:** "Status: Online"
- **Nachricht:** "Benutzer123: Hallo!"

## Lizenz

Dieses Projekt steht unter der MIT-Lizenz.
