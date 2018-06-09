## Pflichtenheft

###  Funktionale Anforderungen

#### Allgemein
	- Text zusammenfassen

#### Eingabe
	- Import als PDF, Word, Präsentation, (HTML)
	- Einstellung ob alles oder nur ein Teil gekürzt werden soll (Import)
	- Copy & Paste Textfeld

![Use Case Eingabe](https://raw.githubusercontent.com/FHB-SS18-Softwareprojekt/Dokumentation/Pflichtenheft/bilder/Eingabe.png)

#### Ausgabe
	- Anzeige des zusammengefassten Texts
	- Export als PDF

![Use Case Ausgabe](https://raw.githubusercontent.com/FHB-SS18-Softwareprojekt/Dokumentation/Pflichtenheft/bilder/Ausgabe_Use_Case_Diagramm.png)

#### Einstellungen
	- Sprache : Deutsch und Englisch
	- Anzahl der Sätze (Prozentual)
	- Heatmap : Priorität der Sätze

![Use Case Einstellungen](https://raw.githubusercontent.com/FHB-SS18-Softwareprojekt/Dokumentation/Pflichtenheft/bilder/Einstellungen_Use_Case_Diagramm.png)

| Schritt          | Akteur          | Ablauf (Basic Flow)  |
| :-------------: |:-------------:| :-----:|
| 1.      | User | Import einer Datei |
| 2.      | User      |   Überprüfen ob alle Einstellungen stimmen |
| 3. | User      |    Anzeige des zusammengefassten Textes |
| 4.      | User | Exportieren des Textes als PDF-Datei |
|           |          | **Ausnahmen, Varianten**  |
| 1.a      | System      |   Mitteilung falls ein falsches Dateiformat gewählt wurde |
| 1.b      | User      |   Einstellung ob alles gekürzt werden soll |
| 1.c     | User    |   Bestimmte Seitenzahl zum kürzen eingeben |
| 2.a      | User      |   Sprache ändern, falls dies notwendig ist |
| 2.b | User      |    Anzahl der Sätze ändern (siehe Use Case für die Einstellungen) |
| 2.c | User      |    Heatmap anzeigen lassen |
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

#### Sprache
	- Als Nutzer möchte ich einstellen können ob es sich um einen deutschen oder englischen Text handelt, damit die Zusammenfassung richtig abläuft.

| Name	| Rolle	| In meiner Rolle möchte ich | so dass| Akzeptanz	| Priorität	|
| :----:| :----:|:--------------------------:|:------:|:-----------:|:---------:|
| Sprache | User | die Sprache für die Texte einstellen können | man Texte auch in anderen Sprachen zusammenfassen kann | Es gibt eine Sprachauswahl | muss |

#### Anzahl der Sätze
	- Als Nutzer möchte ich einstellen können wie viele Sätze die Zusammenfassung gegenüber dem Ursprungstext haben soll (prozentual), falls ich eine kurze beziehungsweise lange Zusammenfassung brauche.

| Name	| Rolle	| In meiner Rolle möchte ich | so dass| Akzeptanz	| Priorität	|
| :----:| :----:|:--------------------------:|:------:|:-----------:|:---------:|
| Anzahl der Sätze | User | die Anzahl der Sätze verringern oder erhöhen können | die Zusammenfassung detailierter oder aber kompakter ist | Mna kann die Anzahl der Sätze bestimmen | muss |

#### Heatmap
	- Als Nutzer möchte ich eine Heatmap angezeigt bekommen, damit ich direkt weiß welche Sätze in der Zusammenfassung am wichtigsten sind.

| Name	| Rolle	| In meiner Rolle möchte ich | so dass| Akzeptanz	| Priorität	|
| :----:| :----:|:--------------------------:|:------:|:-----------:|:---------:|
| Heatmap | User | die Option haben eine Heatmap zu benutzen | man sieht welche Relevanz die einzelnen Sätze haben | Die Sätze werden farbig makiert sobald die Option Heatmap ausgewählt ist | muss |

### Mockups

##### Allgemeines Programm

![Allgemeines/Import Mockup](https://raw.githubusercontent.com/FHB-SS18-Softwareprojekt/Dokumentation/Pflichtenheft/bilder/Mockup_Allgemein.png)

##### Import

![Importieren Mockup](https://raw.githubusercontent.com/FHB-SS18-Softwareprojekt/Dokumentation/Pflichtenheft/bilder/Mockup_Importieren.png)

##### Einstellungen

![Einstellungen Mockup](https://raw.githubusercontent.com/FHB-SS18-Softwareprojekt/Dokumentation/Pflichtenheft/bilder/Einstellungen_Mockup.png)

##### Export

![Exportieren Mockup](https://raw.githubusercontent.com/FHB-SS18-Softwareprojekt/Dokumentation/Pflichtenheft/bilder/Exportieren_Mockup.png)

### Klassendiagramm

![Klassendiagramm](https://raw.githubusercontent.com/FHB-SS18-Softwareprojekt/Dokumentation/Pflichtenheft/bilder/architecture.jpg)

### Glossar

##### Import
Eine Datei aus einem Verzeichnis laden, um diese im Programm zu nutzen.

##### Export
Die Ausgabe der Zusammenfassung als Datei in einem Verzeichnis speichern.

##### Heatmap
Farbige Markierung der einzelnen Sätze, je nach der Priorität  für die Zusammenfassung.

##### Ausgabe
Ein Textfenster oder eine Datei, in der die Zusammenfassung steht beziehungsweise gespeichert wird.

##### Einstellungen
Extra wie die Auswahl des Sprache, Anzahl der Sätze, die angezeigt werden und ob die Heatmap aktiviert werden soll oder nicht.