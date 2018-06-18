## Pflichtenheft

###  Funktionale Anforderungen

#### Allgemein
	- Text zusammenfassen

#### Eingabe
	- Import als PDF, Word, Präsentation
	- Copy & Paste Textfeld

![Use Case Eingabe](https://raw.githubusercontent.com/FHB-SS18-Softwareprojekt/Dokumentation/Pflichtenheft/bilder/Eingabe.png)

#### Ausgabe
	- Anzeige des zusammengefassten Texts
	- Export als PDF

![Use Case Ausgabe](https://raw.githubusercontent.com/FHB-SS18-Softwareprojekt/Dokumentation/Pflichtenheft/bilder/Ausgabe_Use_Case_Diagramm.png)

#### Einstellungen
	- Sprache : Deutsch und Englisch
	- Anzahl der Sätze (Prozentual, um wie viel Prozent soll gekürzt werden)

![Use Case Einstellungen](https://raw.githubusercontent.com/FHB-SS18-Softwareprojekt/Dokumentation/Pflichtenheft/bilder/Einstellungen_Use_Case_Diagramm.png)

| Schritt          | Akteur          | Ablauf (Basic Flow)  |
| :-------------: |:-------------:| :-----:|
| 1.      | User | Import einer Datei oder Copy & Paste eines Textes |
| 2.      | User      |   Einstellen um wie viel Prozent der Text gekürzt werden soll|
| 3. | User      |    Anzeige des zusammengefassten Textes |
| 4.      | User | Exportieren des Textes als PDF-Datei |
|           |          | **Ausnahmen, Varianten**  |
| 1.a      | System      |   Mitteilung falls ein falsches Dateiformat gewählt wurde |
| 3.a | System      |    Mitteilung falls der Ausgangstext zu kurz ist |

### Nicht-Funktionale Anforderungen

#### Anwendung
	- Wir wollen ein ausführbares Programm erstellen, welches auf allen gängigen Betriebssystemen läuft (Windows, Linux, OS X).
	- Die Anwendung sollte intuitiv nutzbar sein und die Aufgabe der Zusammenfassung schnell und sicher erledigen (effiziente Algorithmen).

### User-Stories

#### Import
	- Als Nutzer möchte ich einen Text PDF, Word-Datei oder als HTML-Datei importieren, um diese anschließend zusammenzufassen.

| Name	| Rolle	| In meiner Rolle möchte ich | so dass| Akzeptanz	| Priorität	|
| :----:| :----:|:--------------------------:|:------:|:-----------:|:---------:|
|Import | User | Dateien importieren | diese zusammengefasst werden können | der Text wird importiert und zusammengeafsset | muss |

#### Copy & Paste
	- Als Nutzer möchte ich einen Text kopieren und in ein Textfeld einfügen, um diesen zusammenfassen zu können.

| Name	| Rolle	| In meiner Rolle möchte ich | so dass| Akzeptanz	| Priorität	|
| :----:| :----:|:--------------------------:|:------:|:-----------:|:---------:|
| Copy & Paste | User | Texte in ein Textfeld kopieren können | dieser Text zusammengefasst wird ohne eine Datei importieren zu müssen | Es existiert ein Textfeld für die Option Copy & Paste | optional |

#### Anzeige
	- Als Nutzer möchte ich den zusammengefassten Text angezeigt bekommen.

| Name	| Rolle	| In meiner Rolle möchte ich | so dass| Akzeptanz	| Priorität	|
| :----:| :----:|:--------------------------:|:------:|:-----------:|:---------:|
| Anzeige | User | eine Vorschau des zusammengefassten Text haben | man sehen kann ob die gewählten Einstellungen passend sind | Der Text wird im Programm als Vorschau angezeigt | muss |

#### Export
	- Als Nutzer möchte ich den zusammengefassten Text als PDF exportieren können, um diesen später wiederverwenden zu können.

| Name	| Rolle	| In meiner Rolle möchte ich | so dass| Akzeptanz	| Priorität	|
| :----:| :----:|:--------------------------:|:------:|:-----------:|:---------:|
|Export | User | den zusammengefassten Text als Datei exportieren können | der Text gespeichert werden kann und wiederverwendbar ist | Es gibt die Möglichkeit Texte zu exportieren | muss |

#### Kürzen um X%
	- Als Nutzer möchte ich einstellen können, um wie viel Prozent der Text gekürzt werden soll, falls ich eine kurze beziehungsweise lange Zusammenfassung brauche.

| Name	| Rolle	| In meiner Rolle möchte ich | so dass| Akzeptanz	| Priorität	|
| :----:| :----:|:--------------------------:|:------:|:-----------:|:---------:|
| Kürzen um X% | User | die Länge des gekürzten Textes bestimmen können | die Zusammenfassung detailierter oder aber kompakter ist | Man kann die Prozentzahl zur Kürzung bestimmen | muss |


### Mockups

##### Allgemeines Programm

![Allgemeines/Import Mockup](https://raw.githubusercontent.com/FHB-SS18-Softwareprojekt/Dokumentation/Pflichtenheft/bilder/HauptGUI.png)

##### Hilfe

![Importieren Mockup](https://raw.githubusercontent.com/FHB-SS18-Softwareprojekt/Dokumentation/Pflichtenheft/bilder/Hilfe.png)


### Klassendiagramm

![Klassendiagramm](https://raw.githubusercontent.com/FHB-SS18-Softwareprojekt/Dokumentation/Pflichtenheft/bilder/architecture.jpg)

### Aktivitätsdiagramm

![Aktivitätsdiagramm](https://raw.githubusercontent.com/FHB-SS18-Softwareprojekt/Dokumentation/Pflichtenheft/bilder/Aktivitätsdiagramm.png)

### Glossar

##### Import
Eine Datei aus einem Verzeichnis laden, um diese im Programm zu nutzen.

##### Export
Die Ausgabe der Zusammenfassung als Datei in einem Verzeichnis speichern.

##### Ausgabe
Ein Textfenster oder eine Datei, in der die Zusammenfassung steht beziehungsweise gespeichert wird.

##### Einstellungen
Auswahl um wie viel Prozent der Text gekürzt werden soll.