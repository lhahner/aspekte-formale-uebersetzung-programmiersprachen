# aspekte-formale-uebersetzung-programmiersprachen
Arbeitsergebnisse der PA 4 im Bezug auf den Transpiler vertiefen und verfeinern. Als Werkzeug hauptsächlich JavaCC. Möglichkeiten der automatisierten Codegenerierung sollen untersucht werden, insbesondere durch die Wahl eines geeigneten Datenmodells für PL/I Datentypen, indem Aspkete der objektorientierten Programmierung berrücksichtigt werden.

# 1 Kanban-board für die Erarbeitung der Bachelorarbeits 

| Timeline | Backlog                                                       | To Do                                  | Doing                             | Review             | Done               |
| :------- | :------------------------------------------------------------ | :------------------------------------- | :-------------------------------- | :----------------- | :----------------- |
|          |                                                               |                                        | Gliederung                        |                    |                    |
|          |                                                               |                                        | Abstract                          |                    |                    |
|          |                                                               | Theorie Teil 1: Formale Grammatik      |                                   |                    |                    |
|          | Theorie Teil 2: Aspektorientierte Programmierung              |                                        |                                   |                    |                    |
|          | Technisches Vorgehen Teil 1: Aspektorientierte Programmierung |                                        |                                   |                    |                    |
|          | Technisches Vorgehen Teil 2: Architektur                      |                                        |                                   |                    |                    |
|          | Technische Spezifikation: Ausführung des Transpilers          |                                        |                                   |                    |                    |
|          | Technische Spezifikation: Testing                             |                                        |                                   |                    |                    |
|          | Auswertung und Diskussion: Bedienung                          |                                        |                                   |                    |                    |
|          | Auswertung und Diskussion: Erweiterungsmöglichkeiten          |                                        |                                   |                    |                    |
| :------- | :------------------------------------------------------------ | :------------------------------------- | :-------------------------------- | :----------------- | :----------------- |
| 14.05.24 |                                                               |                                        |                                   | Diagramm           |                    |
|          |                                                               |                                        |                                   | Maven project setup|                    |
|          |                                                               |                                        |                                   |                    |                    |
| 21.05.24 | (Sebastian Urlaub)                                            |                                        |                                   |                    |                    |
|          |                                                               |                                        |                                   |                    |                    |
| 28.05.24 | (Sebastian Remote)                                            |                                        |                                   | Einleitung Entwurf |                    |
|          |                                                               |                                        |                                   |                    |                    |
| 04.06.24 |                                                               |                                        |                                   |                    |                    |
|          |                                                               |                                        |                                   |                    |                    |
| 11.06.24 |                                                               |                                        |                                   |                    |                    |
|          |                                                               |                                        |                                   |                    |                    |
| 18.06.24 |                                                               |                                        |                                   |                    |                    |
|          |                                                               |                                        |                                   |                    |                    |
| 25.06.24 |                                                               |                                        |                                   |                    |                    |
|          |                                                               |                                        |                                   |                    |                    |
| 02.07.24 |                                                               |                                        |                                   |                    |                    |
|          |                                                               |                                        |                                   |                    |                    |
| 09.07.24 | (Sebastian lernt für Klausur)                                 |                                        |                                   |                    |                    |
|          |                                                               |                                        |                                   |                    |                    |
| 16.07.24 |                                                               |                                        |                                   |                    |                    |
|          |                                                               |                                        |                                   |                    |                    |
| 23.07.24 |                                                               |                                        |                                   |                    |                    |
|          |                                                               |                                        |                                   |                    |                    |
|          |                                                               |                                        |                                   |                    |                    |
|          |                                                               |                                        |                                   |                    |                    |
|          |                                                               |                                        |                                   |                    |                    |

# 3 Ziel der Architektur
## 3.1 Perspektive des Entwicklers
Die Architektur soll so aufgebaut sein das der Entwickler die PL/I Grammatikdatei und die PL/I Symboldatei mit einer X-Beliebigen Grammatikdatei und einer X-Beliebigen Symboldatei
austauschen kann. Es soll also möglich sein ohne Probleme einen COBOL zu Java Parser zu bauen, wenn sich an die nötigen Normen der Zwischencode erzeugung gehalten wird.

## 3.2 Perspektive des Benutzers
Dem Benutzer soll es möglich sein ein Pl/i Programm einzubinden ohne großartige Wartung betreiben zu müssen.
Er soll die Auswahl zwischen Präzisionsstufen der Übersetzung haben. Die Ansicht soll aus dem Webbrowser erfolgen.


