# Day 2 - Einführung in Bambu Studio (Bambu Lab Slicer Software)
<br>


## 🔧 Was ist Bambu Studio?

**Bambu Studio** ist die offizielle Slicer-Software von **Bambu Lab** für deren 3D-Drucker wie P1P, P1S, X1 Carbon etc.  
Sie basiert auf **PrusaSlicer**, wurde aber stark erweitert – mit Fokus auf Benutzerfreundlichkeit, Multi-Material-Unterstützung und direkte Integration mit den Bambu-Geräten.

* [BambuLab Wiki](https://wiki.bambulab.com/en/home)
* Offizielle Download Seite von [Bambu Studio](https://bambulab.com/en/download/studio)
* [Portable Standalone Variante für Windows](https://github.com/bambulab/BambuStudio/releases/download/V02.00.03.54/Bambu_Studio_win-v02.00.03.54-20250424182834.zip)

Die portable Version muss nur entpackt werden und dann innerhalb des entpackten Ordners die Datei ***bambu-studio.exe*** ausgeführt werden. ( Doppel-Klick! ;) )

---


### 🧭 Aufbau & Oberfläche

- **Prepare-Ansicht**: Modell importieren und bearbeiten
- **Preview-Ansicht**: Vorschau der Druckschichten und Druckzeiten
- **Device Panel**: Verbindung zum Drucker via Netzwerk oder Cloud
- **Print Settings**: Druckqualität, Material, Geschwindigkeit, Supports etc.

Hier gehts zum [BambuLab Wiki Quick Start](https://wiki.bambulab.com/en/software/bambu-studio/studio-quick-start)

---

### ⭐️ Wichtige Funktionen

#### 1. 🖼️ Modellbearbeitung
- Platzieren, skalieren, rotieren, spiegeln
- Cut/Slice-Funktion für große Modelle
- Auto-Layout bei mehreren Objekten

#### 2. 🧵 Slicing & Vorschau
- Layer-by-Layer-Vorschau
- Anzeige von:
  - Druckzeit
  - Materialverbrauch
  - Temperaturverläufen
- Farbige Darstellung von Infill, Perimeter, Supports

#### 3. ⚙️ Druckprofile & Einstellungen
- Vorinstallierte Profile für alle Bambu-Drucker
- Anpassbar:
  - Schichthöhe (inkl. adaptiv)
  - Geschwindigkeit
  - Temperaturen
  - Rückzug (Retraction)
  - Flussrate (Flow Rate)
  - Lüftersteuerung
  - Z-Seam Position

#### 4. 🎨 Multi-Material & Farbwechsel (AMS)
- Unterstützung für das **AMS**
- Farbzuweisung per Klick (z. B. bei mehrteiligen Objekten)
- Automatischer Materialwechsel während des Drucks

#### 5. 🧱 Support-Management
- Auto- oder manuelle Platzierung
- Tree Supports verfügbar
- Einstellung von Support-Dichte, Winkel, Overhang etc.

#### 6. 🌐 Cloud- & Netzwerkfunktionen
- Direktdruck über WLAN oder Bambu-Cloud
- Live-Kamera & Statusanzeige
- Steuerung über die **Bambu Handy App**

#### 7. 📊 Weitere Tools
- **Flow Calibration Tool**
- **Pressure Advance Tuning**
- **Arachne Engine** für dynamische Perimeter
- **Vibration Compensation (Input Shaping)**


### 📁 Exportformate
- `.3mf` für vollständige Projektdateien
- `.gcode` zum Drucken
- `.png` für Vorschau im Druckermenü


### 📱 Bambu Handy App
- Live-Drucküberwachung
- Benachrichtigungen (z. B. Druck fertig, Filament leer)
- Integration mit Cloud-Account


### ✅ Typischer Workflow

1. Modell importieren (z. B. `.stl`)
2. Modell platzieren, skalieren, ggf. schneiden
3. Drucker, Filament & Qualität einstellen
4. Supports und Haftmethoden wählen
5. Slice ausführen und Vorschau prüfen
6. Direkt an Drucker senden oder Datei speichern

---


## 🚶‍♂️ Walkthrough durch Bambu Studio

Exemplarisch ein typischer Workflow – vom Import eines 3D-Modells bis zum Druckstart mit Bambu Studio.


### 1. 📂 Modell importieren

- Öffne **Bambu Studio**.
- Ziehe eine `.stl`, `.obj` oder `.3mf` Datei in das Hauptfenster  
  **oder** nutze oben links den Button **„Import Model“**.
- Das Modell erscheint auf dem virtuellen Druckbett.

💡 *Tipp: Nutze „Arrange“, um mehrere Modelle automatisch zu platzieren.*


### 2. 🛠 Modell bearbeiten

Verwende die Tools links:

- **Move** – Modell auf dem Bett verschieben  
- **Rotate** – Modell drehen (X/Y/Z-Achse)  
- **Scale** – Größe anpassen (proportional oder einzeln)  
- **Mirror** – Spiegelung des Modells  
- **Cut** – Modell zerschneiden, z. B. für große Drucke

💡 *Für Farbwechsel: Rechtsklick → „Paint“ oder „Assign Toolhead“ (bei AMS).*


### 3. ⚙️ Druckeinstellungen wählen

Unten rechts:

- **Drucker auswählen** (z. B. X1C, P1P)
- **Filamenttyp wählen** (PLA, PETG, TPU etc.)
- **Druckqualität wählen** (Standard, High Speed, High Quality)

🔧 *Wechsle in den „Custom“-Modus für Feineinstellungen wie:*
- Layerhöhe
- Geschwindigkeit
- Temperatur
- Retraction
- Flow Rate
- Z-Seam


### 4. 🧱 Support & Adhesion konfigurieren

In der rechten Leiste:

- **Supports aktivieren**: automatisch oder manuell  
- **Support-Art wählen**: Normal, Tree Supports  
- **Build Plate Adhesion**: Skirt, Brim, Raft

💡 *Bei Überhängen über 45° empfiehlt sich Support.*


### 5. ✂️ Slicen & Vorschau prüfen

- Klick auf **„Slice“**
- Bambu Studio zeigt:
  - Schicht-für-Schicht-Vorschau
  - Druckzeit, Materialverbrauch, Temperaturen
  - Farbige Darstellung (Infill, Perimeter, Supports etc.)

🔍 *Verwende den Layer-Slider rechts, um den Druck zu analysieren.*


### 6. 📤 Druck starten oder Datei exportieren

#### Option A: Direktdruck
- Klick auf **„Send via Network“** oder **„Start Print“**, wenn der Drucker verbunden ist.

#### Option B: Export
- Speichere den G-Code lokal auf SD/USB
- Automatisch wird eine .png-Vorschau erzeugt (für Bildschirmvorschau auf dem Drucker)


### 7. 📱 Druck per App überwachen

Mit der **Bambu Handy App** kannst du:

- Den Druck in Echtzeit verfolgen (inkl. Webcam)
- Druckerstatus checken
- Benachrichtigungen empfangen (z. B. Druck fertig, Filament leer)



## ✅ Zusammenfassung: Ablauf in Kurzform

1. Modell importieren  
2. Positionieren, skalieren, schneiden  
3. Druckeinstellungen auswählen  
4. Support & Haftung konfigurieren  
5. Slicen & Vorschau prüfen  
6. Direktdruck oder Export  
7. Überwachung per App

---
