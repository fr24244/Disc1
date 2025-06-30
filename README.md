# 🌦 Wetteranzeige für Nigeria per Knopfdruck

Dieses Node-RED-Projekt zeigt auf Knopfdruck das aktuelle Wetter **für Nigeria** auf einem DigiLab-Display an.  
Ein zweiter Button leert den Bildschirm vollständig.  
Es nutzt die **Open-Meteo API**  und läuft auf einem **Raspberry Pi** mit Node-RED.

---

## 🎯 Projektziel

Ziel ist es, per Button-Druck auf dem DigiLab-Gerät:

- Mit **Button 1** das aktuelle Wetter für **Nigeria** anzuzeigen  
- Mit **Button 2** den Bildschirm vollständig zu **leeren**

Ideal für **IoT-Projekte**, **Bildungszwecke** oder zum Lernen von **API-Anbindungen mit Node-RED**.

---

## 🛠 Verwendete Technologien

- **Node-RED (auf Raspberry Pi)**: Visuelle Steuerung und Logik  
- **Open-Meteo API**: Kostenlose Wetterdaten  
- **DigiLab-Display**: Zeigt Wetterinfos oder wird geleert  
- **Zwei physische Buttons**:  
  - Button 1: Wetter anzeigen  
  - Button 2: Display leeren  

---

## 📋 Projektphasen & Aufgaben

### Phase 1 – Planung

| Aufgabe | Beschreibung |
|--------|--------------|
| 📌 Ziel definieren | Wetteranzeige + Clear-Funktion |
| 📌 API wählen | Open-Meteo (ohne Key) |
| 📌 Städte koordinieren | Koordinaten für Nigeria (z. B. Lagos) |

---

### Phase 2 – Umsetzung

| Aufgabe | Beschreibung |
|--------|--------------|
| ⚙️ Node-RED einrichten | GPIO für zwei Buttons, HTTP-Request, Function & Display-Knoten |
| ⚙️ API-Daten abrufen | Open-Meteo GET-Request für Nigeria |
| ⚙️ JSON verarbeiten | Temperatur, Wind etc. extrahieren |
| ⚙️ Display leeren | Zweiter Button löscht alle Inhalte vom Display |

---

### Phase 3 – Test & Optimierung

| Aufgabe | Beschreibung |
|--------|--------------|
| ✅ Buttons testen | Funktionieren beide wie gewünscht? |
| ✅ Fehler abfangen | Kein Netz? API down? → Fallback-Text |
| ✅ Lesbarkeit prüfen | Passt Text auf das Display? Kein Überlauf? |

---

## 🧪 Tests & Qualität

- **Button-Test**: Beide Buttons wiederholt testen  
- **API-Check**: Rückgabewerte via Debug-Node prüfen  
- **Display-Test**: Guter Kontrast? Text vollständig sichtbar?  
- **Fallback**: Anzeige bei Fehlern wie „Kein Internet“  

---

## 🗂 GitHub-Projektplanung

👉 [Zum Projekt-Board auf GitHub](https://github.com/users/fr24244/projects/6)

---

## Json


👉 [Click here to view the Node-RED flow (JSON)](https://github.com/user-attachments/files/20985890/message.1.txt)
