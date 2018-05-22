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

#### Copy & Paste
	- Als Nutzer möchte ich einen Text kopieren und in ein Textfeld einfügen, um diesen zusammenfassen zu können.

#### Anzeige
	- Als Nutzer möchte ich den zusammengefassten Text angezeigt bekommen.

#### Export
	- Als Nutzer möchte ich den zusammengefassten Text als PDF exportieren können, um diesen später wiederverwenden zu können.

#### Sprache
	- Als Nutzer möchte ich einstellen können ob es sich um einen deutschen oder englischen Text handelt, damit die Zusammenfassung richtig abläuft.

#### Anzahl der Sätze
	- Als Nutzer möchte ich einstellen können wie viele Sätze die Zusammenfassung gegenüber dem Ursprungstext haben soll (prozentual), falls ich eine kurze beziehungsweise lange Zusammenfassung brauche.

#### Heatmap
	- Als Nutzer möchte ich eine Heatmap angezeigt bekommen, damit ich direkt weiß welche Sätze in der Zusammenfassung am wichtigsten sind.
	
### Mockups

![Allgemeines/Import Mockup](https://raw.githubusercontent.com/FHB-SS18-Softwareprojekt/Dokumentation/Pflichtenheft/bilder/Mockup_Allgemein_Import.jpg)

![Einstellungen Mockup](https://raw.githubusercontent.com/FHB-SS18-Softwareprojekt/Dokumentation/Pflichtenheft/bilder/Einstellungen_Mockup.png)

![Exportieren Mockup](https://raw.githubusercontent.com/FHB-SS18-Softwareprojekt/Dokumentation/Pflichtenheft/bilder/Exportieren_Mockup.png)

