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

## 📈 GitHub Planner (öffentlich)

> [→ Zum öffentlichen GitHub Planner](https://github.com/YOUR-USERNAME/YOUR-REPOSITORY/projects)  
(Diesen Link musst du ersetzen mit deinem echten GitHub-Project-Board)

---

## 🧪 Tests & Qualitätssicherung

- **Manueller Funktionstest**: Mehrfaches Auslösen per Button
- **Debug-Node**: Überprüfung des JSON-Outputs und Fehlermeldungen
- **Grenzfall-Test**: Kein Internet? Falsche API-Antwort? → Anzeige testweise ersetzen
- **Display-Test**: Korrekte Darstellung auf deinem DigiLab-Screen (kein Textüberlauf, saubere Ausgabe)

---

## 🧭 Umsetzung der Planung

Die Aufgaben aus dem GitHub Planner wurden in der geplanten Reihenfolge umgesetzt. Falls spontane Änderungen notwendig waren (z. B. API-Wechsel), 
wurden diese dokumentiert und der Plan entsprechend angepasst.

---

## 📦 API-Info: Open-Meteo Beispiel-URL (Berlin)

```txt
https://api.open-meteo.com/v1/forecast?latitude=52.52&longitude=13.405&current_weather=true
