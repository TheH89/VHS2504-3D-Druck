# 3D Druck Workshop - Day 1 - The Basics

## Druck Arten
* FDM (Fused Deposition Modeling - Filament Druck)
* SLA (Flüssiger Kunstharz giftig aber hoch präzise)
* SLS (Pulver Druck)

### 🔧 1. FDM / FFF (Fused Deposition Modeling / Fused Filament Fabrication)
* Material: Thermoplastisches Filament (z. B. PLA, ABS, PETG)
* Funktionsweise: Das Filament wird geschmolzen und schichtweise aufgetragen.
* Vorteile: Günstig, einfach, weit verbreitet
* Einsatz: Prototypen, Haushaltsgegenstände, Hobbybereich

### 🧪 2. SLA (Stereolithografie) / DLP (Digital Light Processing)
* Material: Flüssiges Photopolymer (Harz)
* Funktionsweise: Harz wird durch Licht (Laser oder Projektor) gehärtet.
* Vorteile: Sehr hohe Detailgenauigkeit, glatte Oberflächen
* Einsatz: Schmuck, Zahntechnik, Miniaturen, Formenbau

### 🧲 3. SLS (Selective Laser Sintering)
* Material: Kunststoffpulver (z. B. Nylon)
* Funktionsweise: Pulver wird durch einen Laser schichtweise verschmolzen.
* Vorteile: Keine Stützstrukturen nötig, hohe Festigkeit
* Einsatz: Funktionsteile, Prototypen, Kleinserien


## Toxizität
### 🥇 1. FDM / FFF – am ungefährlichsten (bei richtigem Material)
* Materialien wie PLA (Polylactid) sind biologisch abbaubar und ungiftig.
* Kaum Dämpfe oder Gerüche, besonders bei PLA.
* Gefahren: Bei ABS oder anderen Kunststoffen können schädliche Dämpfe (Styrol) entstehen – gute Belüftung nötig.

➕ Mit geschlossener Druckkammer + Filter sehr sicher.
✅ Empfehlung für Hobby und Zuhause: PLA mit FDM – ideal bei guter Belüftung.

### ⚠️ 2. SLA / DLP – sehr toxisch, Schutz nötig
* Harze (Photopolymere) sind chemisch aggressiv und hautreizend.
* Beim Aushärten können giftige Dämpfe entstehen.
* Nachbearbeitung mit Isopropanol und UV-Licht ist nötig.
* Nur mit Handschuhen, Maske und Belüftung!
🚫 Nicht geeignet für Kinder oder schlecht belüftete Räume.

### ⚠️ 3. SLS / SLM / andere Pulververfahren – nur industriell
* Feinstaubbelastung, hoher Energieaufwand
* Gefahr durch lungengängigen Staub (explosionsfähig!)
* Nur in geschlossenen, professionellen Anlagen mit Absaugung


## FDM/FFF Filamente
### 🧵 1. Standard-Filamente (ideal für Einsteiger)
🔹 PLA (Polylactid)
    Vorteile: Sehr einfach zu drucken, geruchsarm, verzugsfrei, biologisch abbaubar
    Drucktemp: 180–220 °C, Bett: 0–60 °C
    Nachteile: Geringe Hitzebeständigkeit (~60 °C), spröde
    Verwendung: Deko, Prototypen, Figuren

🔹 PETG (Polyethylenterephthalat Glykol)
    Vorteile: Robust, zäh, leicht flexibel, feuchtigkeitsresistent
    Drucktemp: 220–250 °C, Bett: 70–90 °C
    Nachteile: Neigt zu Stringing (Fädenbildung), weniger steif als PLA
    Verwendung: Gehäuse, mechanische Teile, Flaschen

🔹 ABS (Acrylnitril-Butadien-Styrol)
    Vorteile: Zäh, temperaturbeständig (~100 °C), robust
    Drucktemp: 230–260 °C, Bett: 90–110 °C
    Nachteile: Schrumpft beim Abkühlen → Verzug, giftige Dämpfe
    Verwendung: Technische Teile, Auto- oder Haushaltskomponenten
    ⚠️ Nur in gut belüfteter Umgebung!

### 🧪 2. Technische Filamente
🔹 Nylon (Polyamid)
    Vorteile: Sehr stark, zäh, abriebfest, flexibel
    Drucktemp: 240–270 °C, Bett: 70–100 °C
    Nachteile: Extrem feuchtigkeitsanfällig → vor Druck trocknen!
    Verwendung: Zahnräder, Lager, bewegliche Teile

🔹 PC (Polycarbonat)
    Vorteile: Hitzebeständig (~110–130 °C), sehr robust
    Drucktemp: 260–300 °C, Bett: >100 °C
    Nachteile: Schwierig zu drucken (warping!), braucht hohe Temp
    Verwendung: Mechanisch stark beanspruchte Teile

🔹 ASA (Alternative zu ABS)
    Vorteile: UV-beständig, witterungsfest, ähnlich stabil wie ABS
    Drucktemp: 230–260 °C, Bett: 90–110 °C
    Nachteile: Braucht geschlossenen Bauraum
    Verwendung: Outdoor-Teile, Gehäuse, Solarhalterungen

### 🌈 3. Spezialfilamente
🔹 TPU / TPE (Thermoplastisches Elastomer)
    Vorteile: Gummiartig, flexibel, vibrationsdämpfend
    Drucktemp: 210–250 °C, Bett: 30–60 °C
    Nachteile: Braucht langsamen Druck, Direct Drive empfohlen
    Verwendung: Handyhüllen, Dichtungen, Reifen

🔹 Holz-, Metall-, Carbon-Filamente (gefüllt)
    Vorteile: Spezielles Aussehen, Haptik oder Eigenschaften
    Drucktemp: ähnlich wie PLA, je nach Basis
    Nachteile: Abrasiv! → gehärtete Düse nötig
    Verwendung: Deko, Bauteile mit Metalloptik, Leichtbau

### 🔒 Tipp zur Lagerung
Viele Filamente ziehen Feuchtigkeit → das führt zu Druckproblemen:
* Luftdicht lagern
* Trockenboxen oder Silikagel nutzen
* Für Nylon & TPU → vorher trocknen

Recycling von Druckresten und Einkauf von recycelten Filamenten unter:
[Recycling Fabrik](https://www.recyclingfabrik.com/)

## Spezialdruck mit Filamenten / gehärtete Düsen

### ⚠️ Warum sind gehärtete Düsen wichtig?
Partikelhaltige Filamente sind abrasiv – sie schleifen das Innere der Düse ab, vor allem bei Standard-Messingdüsen. Das führt zu:
* Größer werdender Düsenöffnung
* Schlechter Druckqualität (unsaubere Linien, Unterextrusion)
* Frühzeitigem Düsenversagen

### ✅ Gehäuse-Düsentypen im Vergleich
| **Düsentypen**     | **Material**           | **Eignung für abrasive Filamente**           |
|--------------------|------------------------|----------------------------------------------|
| Messing            | Weich, günstig         | ❌ Nein – nur für PLA, PETG etc.             |
| Stahl (gehärtet)   | Hart, langlebig        | ✅ Ja – ideal für abrasive Materialien        |
| Edelstahl          | Mittelhart, rostfrei   | ➖ Geht, aber nicht ideal                     |
| Rubin-Düsen        | Messing + Rubinspitze  | ✅✅ Extrem langlebig, teuer                  |
| Tungsten (Wolfram) | Sehr hart, High-End    | ✅✅ Industriequalität  

### 🔍 Woran erkenne ich, dass die Düse verschlissen ist?
* Druckbild wird unsauber
* Es kommt zu Unterextrusion
* Layer sind unregelmäßig
* Du musst mehr Flow einstellen, um dasselbe Ergebnis zu kriegen

### 💡 Tipps im Umgang mit abrasiven Filamenten
* Immer gehärtete Düse verwenden (am besten 0.4 mm oder größer)
* Druckgeschwindigkeit leicht reduzieren – wirkt sich auf Qualität aus
* Filamenthersteller prüfen – nicht jedes "Holz" ist gleich abrasiv
* Düse regelmäßig prüfen und ggf. tauschen
* Für viele dieser Materialien lohnt sich eine Direct Drive-Extrusion

### 🔧 Düsenwechsel leicht gemacht
Wenn du viel experimentierst:
* Setz auf ein System wie E3D V6, Volcano oder Revo
* Manche Systeme erlauben schnellen Düsenwechsel ohne Werkzeug

---

## 🛠️ TROUBLE SHOOT - Häufige Fehler beim FDM / FFF 3D-Druck & Lösungen

### 🔺 Warping (Ecken lösen sich vom Druckbett)
**Ursachen:**
- Material schrumpft beim Abkühlen (z. B. ABS)

**Lösungen:**
- Bett richtig leveln
- Bett-Temperatur erhöhen
- Brim oder Raft aktivieren
- Enclosure verwenden

---

### ↔️ Layer Shift (versetzte Schichten)
**Ursachen:**
- Riemen locker
- Motorprobleme
- Kabel blockieren Bewegung

**Lösungen:**
- Riemen spannen
- Achsen prüfen
- Motorspannung/Temperatur checken

---

### 🧵 Unterextrusion
**Ursachen:**
- Verstopfte Düse
- Extruder greift nicht richtig
- Filament feucht oder spröde

**Lösungen:**
- Düse reinigen
- Extruder prüfen
- Temperatur leicht erhöhen
- Trockene Lagerung

---

### 🕸️ Stringing (Fädenbildung)
**Ursachen:**
- Tropfendes Filament bei Leerfahrt

**Lösungen:**
- Retract aktivieren & optimieren
- Drucktemperatur leicht senken
- Reisegeschwindigkeit erhöhen
- Filament trocken halten

---

### 🧲 Erste Schicht haftet nicht
**Ursachen:**
- Bett nicht eben oder verschmutzt
- Düse zu weit weg

**Lösungen:**
- Bett leveln
- Oberfläche reinigen (Isopropanol)
- Z-Offset justieren
- Erste Schicht langsamer & mit mehr Flow drucken

---

### 🐘 Elefantenfuß
**Ursachen:**
- Zu heißes Bett
- Düse zu nah an Bett

**Lösungen:**
- Bett-Temp senken
- Z-Offset leicht anheben

---

### 🚫 Verstopfte Düse
**Ursachen:**
- Verbranntes Filament
- Fremdpartikel

**Lösungen:**
- Cold Pull (z. B. mit Nylon)
- Reinigungsnadel verwenden
- Düse ggf. tauschen

---

### 📐 Z-Wobble (vertikale Wellen)
**Ursachen:**
- Schiefe Z-Spindel
- Ungleichmäßige Bewegung

**Lösungen:**
- Z-Spindeln prüfen (gerade, sauber)
- Gewindemuttern & Lager korrekt montieren
- Führungen ölen/reinigen

---

### ✅ Bonus-Tipps
- Immer nur eine Einstellung auf einmal ändern
- Gute Einstellungen dokumentieren
- Community nutzen (z. B. Reddit, Discord, Foren)

