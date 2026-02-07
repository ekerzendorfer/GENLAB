# GENLAB - Vom genetischen Code zum Peptid 🧬

Ein interaktives, webbasiertes Labor für den Biologie- und Chemieunterricht (SEK 1 & 2), das den Prozess der Translation vom DNA-Code zur chemischen Strukturformel eines Peptids visualisiert.

**[Hier klicken, um GENLAB zu öffnen](https://DEIN-USERNAME.github.io/DEIN-REPO-NAME/)**
*(Ersetze den Link oben, sobald du GitHub Pages aktiviert hast)*

## 🎯 Über das Projekt
Dieses Tool wurde entwickelt, um SchülerInnen den abstrakten Weg vom genetischen Code (DNA) zum fertigen Biomolekül transparent zu machen. Es verbindet Informatik, Biologie und Chemie in einer einfachen Oberfläche.

### Features
* **Live-Übersetzung:** Eingabe von DNA-Tripletts (A, C, G, T) und sofortige Umwandlung in die Aminosäuresequenz.
* **Chemische Visualisierung:** Automatische Generierung der korrekten 2D-Strukturformel (SMILES-Algorithmus) unter Berücksichtigung der Peptidbindungen.
* **Smart-Zoom & Optimierung:** "Zauberstab"-Funktion, um komplexe Molekülketten zu entwirren und lesbar darzustellen.
* **Export-Funktionen:**
    * Kopieren der **FASTA**-Sequenz (für Bioinformatik-Tools).
    * Kopieren des **SMILES**-Codes (für Chemie-Software).
    * Kopieren des **Strukturbildes** (mit weißem Hintergrund für Arbeitsblätter/Präsentationen).
* **Brücke zu 3D:** Direkter Link zu **ColabFold (AlphaFold2)**, um die gefaltete 3D-Struktur zu berechnen.

## 🚀 Nutzung
Es ist keine Installation notwendig. Das Tool läuft vollständig im Browser (Client-Side).

1.  Klone dieses Repository oder lade die `index.html` herunter.
2.  Öffne die Datei in einem modernen Browser (Chrome, Firefox, Edge, Safari).
3.  **Tipp:** Für die Nutzung im Unterricht empfiehlt sich das Hosting via **GitHub Pages** (Settings -> Pages -> Branch: main).

## 🧪 Theoretischer Hintergrund
Das Tool simuliert die **Translation**:
1.  Der DNA-Strang (coding strand) wird in Tripletts gelesen.
2.  Jedes Triplett codiert für eine spezifische Aminosäure (oder ein Stopp-Signal).
3.  Die Aminosäuren werden durch **Peptidbindungen** (Kondensationsreaktion unter Wasserabspaltung) verknüpft.
4.  Die Seitenketten (R) bestimmen die chemischen Eigenschaften und die Faltung.

## 🛠 Technologien
* **HTML5 / CSS3 / Vanilla JavaScript**: Keine Frameworks, leichtgewichtig.
* **[SmilesDrawer](https://github.com/reymond-group/smilesDrawer)**: Open-Source Bibliothek zur Darstellung chemischer Strukturen.

## 👨‍🏫 Credits
* **Konzept & Erstellung:** Mag. Erich Kerzendorfer
* **Technische Umsetzung:** Entwickelt mit Unterstützung von Google Gemini Pro (AI).

---
*Lizenz: MIT License (Open Source - Frei für Bildungszwecke)*
