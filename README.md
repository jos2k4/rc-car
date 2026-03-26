# Remote Controlled Car (Arduino + RemoteXY)

Dieses Projekt umfasst die Entwicklung und Programmierung eines ferngesteuerten Fahrzeugs (RC Car), das über eine Smartphone-App gesteuert wird. Es wurde im Rahmen eines Universitätsprojekts realisiert und kombiniert eingebettete Programmierung mit mechanischen Komponenten wie einem Ball-Launcher.

## 🚀 Features
- **Smartphone-Steuerung:** Vollständige Kontrolle über Fahrtrichtung und Geschwindigkeit mittels der **RemoteXY** App.
- **Ball-Launcher:** Integrierter Mechanismus zum Abschießen von Bällen, gesteuert über die App-Oberfläche.
- **Echtzeit-Interaktion:** Optimierte Kommunikation zwischen Smartphone und Arduino für geringe Latenz.
- **Modularer Code:** Trennung der Logik in Fahrtsteuerung (`main.cpp`) und Schussmechanismus (`shooting.cpp`).

## 🛠 Tech Stack & Komponenten
- **Sprache:** C++ (Arduino Sketch)
- **Hardware:**
  - Arduino Mikrocontroller
  - Motor
  - Servomotoren für den Launcher
  - integrierter Bluetooth-Modul
- **Software:** RemoteXY Library zur GUI-Erstellung ohne App-Programmierung.

## 📂 Projektstruktur
- `main.cpp`: Enthält die Hauptschleife (Setup/Loop) sowie die Logik für die Motorsteuerung und App-Verbindung.
- `shooting.cpp`: Beinhaltet die spezifischen Funktionen und Zeitabläufe für den Ball-Wurfmechanismus.
- `README.md`: Projektdokumentation.

## 🔧 Installation & Nutzung
1. **Hardware-Setup:** Verbinde die Motoren und Servos gemäß der Pin-Belegung im Code mit deinem Arduino.
2. **Bibliotheken:** Installiere die `RemoteXY` Bibliothek über den Arduino Library Manager.
3. **Upload:** Lade die Dateien auf deinen Arduino hoch.
4. **App-Verbindung:** Öffne die RemoteXY App auf deinem Smartphone, verbinde dich mit dem Fahrzeug und starte die Steuerung.

## 🎓 Hintergrund
Das Projekt wurde entwickelt, um die Grundlagen von **Embedded Systems** und **Robotik** praktisch anzuwenden. Ein besonderer Fokus lag dabei auf der effizienten Steuerung von Aktoren durch Sensordaten (oder in diesem Fall App-Eingaben).
