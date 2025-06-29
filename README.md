# Wetteranzeige auf Knopfdruck (Berlin)

Dieses Node-RED-Projekt zeigt auf Knopfdruck das aktuelle Wetter für Berlin an. Es verwendet die Open-Meteo API (kostenfrei, ohne API-Key) und ein digitales Display (z. B. DigiLab oder Node-RED Dashboard).

---

## 🎯 Projektziel

Ziel ist es, per Button-Druck im Node-RED Dashboard das aktuelle Wetter für Berlin abzurufen und auf einem Display anzuzeigen. Dies ist besonders nützlich in Bildungskontexten (z. B. Schul-Labor DigiLab), bei IoT-Experimenten oder zur Visualisierung von APIs.

---

## 🛠 Verwendete Technologien

- **Node-RED**: Für visuelle Programmierung und Steuerung des Datenflusses
- **Open-Meteo API**: Kostenlose Wetterdaten ohne Registrierung
- **Node-RED Dashboard / DigiLab Screen**: Anzeige der Wetterinformationen
- **GitHub Projects (Planner)**: Für Aufgabenplanung und Projektmanagement

---

## 💡 Warum dieses Projekt besonders ist

- Extrem einfache Umsetzung ohne API-Key
- Realtime-Interaktion (Button → Wetterdaten in Echtzeit)
- Ideal für Lernprojekte oder praktische Demonstrationen von REST-APIs
- Modular erweiterbar (z. B. andere Städte, Sprachausgabe, Icons, etc.)

---

## 📋 Projektphasen & Aufgaben

### Phase 1 – Planung (Wichtigkeit: Hoch)

| Aufgabe | Beschreibung | Zeit | Wichtigkeit |
|--------|--------------|------|-------------|
| 📌 Projektziel definieren | Klar formulieren, was erreicht werden soll | 30 min | Hoch |
| 📌 API recherchieren | Wetter-API ohne Authentifizierung finden (Open-Meteo) | 30 min | Hoch |
| 📌 GitHub Planner einrichten | Öffentlichen Projektplan erstellen | 15 min | Hoch |

---

### Phase 2 – Entwicklung (Wichtigkeit: Hoch)

| Aufgabe | Beschreibung | Zeit | Wichtigkeit |
|--------|--------------|------|-------------|
| ⚙️ Node-RED vorbereiten | Button, HTTP-Request, Function, Display-Knoten erstellen | 1 h | Hoch |
| ⚙️ API-Daten abrufen | Open-Meteo mit GET-Request abfragen | 30 min | Hoch |
| ⚙️ JSON verarbeiten | Temperatur, Wind etc. extrahieren und als Text formatieren | 30 min | Hoch |
| ⚙️ Ausgabe auf Display | Wettertext an DigiLab/Display senden | 30 min | Hoch |

---

### Phase 3 – Test & Optimierung (Wichtigkeit: Mittel)

| Aufgabe | Beschreibung | Zeit | Wichtigkeit |
|--------|--------------|------|-------------|
| ✅ Funktionstest | Mehrfach testen: Button → Anzeige → korrekt? | 30 min | Hoch |
| ✅ Fehlerbehandlung | Catch Node bei API-Fehlern, Debug-Node prüfen | 30 min | Mittel |
| ✅ Feintuning | Textlayout, Symbol oder weitere Infos | 30 min | Mittel |

---


## 🧪 Tests & Qualitätssicherung

- **Manueller Funktionstest**: Mehrfaches Auslösen per Button
- **Debug-Node**: Überprüfung des JSON-Outputs und Fehlermeldungen
- **Grenzfall-Test**: Kein Internet? Falsche API-Antwort? → Anzeige testweise ersetzen
- **Display-Test**: Korrekte Darstellung auf deinem DigiLab-Screen (kein Textüberlauf, saubere Ausgabe)

---


## 📋 Projektplanung

Alle Aufgaben, Fortschritt und Status findest du im öffentlichen GitHub Planner:

👉 [Zum Projekt-Board auf GitHub](https://github.com/users/fr24244/projects/6)


