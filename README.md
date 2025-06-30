# Wetteranzeige auf Knopfdruck (Luxemburg & Belgien)

Dieses Node-RED-Projekt zeigt auf Knopfdruck das aktuelle Wetter **für Luxemburg und Belgien** auf einem DigiLab-Display an. 
Es nutzt die Open-Meteo API (kostenfrei, ohne API-Key) und läuft auf einem **Raspberry Pi** mit Node-RED.

---

## 🎯 Projektziel

Ziel ist es, per Button-Druck auf dem DigiLab-Gerät (z. B. 2 Tasten) das aktuelle Wetter **für Luxemburg oder Belgien** abzurufen und auf einem Bildschirm anzuzeigen. Dieses Projekt eignet sich ideal für **Bildungszwecke**, **IoT-Experimente** oder als praktische Einführung in **API-Nutzung mit Node-RED**.

---

## 🛠 Verwendete Technologien

- **Node-RED (auf Raspberry Pi)**: Visuelle Programmierung und Datenfluss-Steuerung  
- **Open-Meteo API**: Kostenlose Wetterdaten ohne Registrierung  
- **DigiLab-Display**: Anzeige der Wetterinformationen  
- **Zwei physische Buttons**: Einer für Luxemburg, einer für Belgien  
- **GitHub Projects (Planner)**: Aufgabenplanung und Dokumentation  

---

## 💡 Warum dieses Projekt besonders ist

- Kein API-Key notwendig → ideal für Schulen oder Workshops  
- Zwei-Knopf-System: Je nach Button wird Luxemburg oder Belgien angezeigt  
- Echtzeitdaten: Button drücken → Wetterdaten sofort auf dem Display  
- Flexibel erweiterbar: Weitere Länder, Sprachausgabe, Icons etc. möglich  

---

## 📋 Projektphasen & Aufgaben

### Phase 1 – Planung (Wichtigkeit: Hoch)

| 📌 Projektziel definieren | Ziel (Wetteranzeige für 2 Länder per Knopfdruck) festlegen 
| 📌 API recherchieren | Wetter-API ohne Authentifizierung finden (Open-Meteo) 
| 📌 GitHub Planner einrichten | Öffentliches Projekt-Board anlegen 

---

### Phase 2 – Entwicklung (Wichtigkeit: Hoch)

| ⚙️ Node-RED vorbereiten | Zwei Buttons, HTTP-Requests, Function- und Display-Knoten 
| ⚙️ API-Daten abrufen | Open-Meteo mit GET-Request für beide Länder abfragen
| ⚙️ JSON verarbeiten | Temperatur, Wind etc. extrahieren und formatieren 
| ⚙️ Ausgabe auf Display | Je nach Button → passende Wetterdaten anzeigen 

---

### Phase 3 – Test & Optimierung (Wichtigkeit: Mittel)


| ✅ Funktionstest | Beide Buttons testen: Anzeige korrekt? 
| ✅ Fehlerbehandlung | API-Fehler mit Catch Node behandeln 
| ✅ Feintuning | Textlayout, evtl. Flagge oder Stadtname anzeigen

---

## 🧪 Tests & Qualitätssicherung

- **Button-Test**: Beide Buttons mehrfach auslösen  korrekte Anzeige?  
- **Debug-Node**: Kontrolle der API-Antworten & Fehler  
- **Fallback-Szenarien**: Kein Netz?  Fehlertext anzeigen  
- **Display-Test**: Ist Text gut lesbar? Kein Überlauf?

---

## 📋 Projektplanung

Alle Aufgaben, Fortschritte und den Status findest du hier:

👉 [Zum Projekt-Board auf GitHub](https://github.com/users/fr24244/projects/6)
