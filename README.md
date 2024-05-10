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


## 1.1 Theorie Teil 1: Formale Grammatik


## 1.2 Theorie Teil 2: Aspektorientierte Programmierung


## 1.3 Programmierung: Projektstrukturierung


## 1.4 Programmierung: Testing


# 2 Kanban-board für die Programmierung des Transpilers

| Backlog                               | To Do                       | Doing                   | Review                   | Done |
| :------------------------------------ | :-------------------------- | :---------------------- | :----------------------- | :--- |
|                                       |                             | Error Handeling         |                          |      |
|                                       |                             |                         | Migrate Project to Maven |      |
| Clean up Code                         |                             |                         |                          |      |
|                                       |                             | Testing current version |                          |      |
| Expand PictureMapper                  |                             |                         |                          |      |
| Tests for translated Regex            |                             |                         |                          |      |
|                                       |                             | Restructure Project     |                          |      |
| Add all Tokens to SymbolTable         |                             |                         |                          |      |
|                                       |                             | Restructure Main        |                          |      |
| Use PL/I Program Name in Java Program |                             |                         |                          |      |
|                                       | Config-Datei                |                         |                          |      |
|                                       | Check for Inherietence      |                         |                          |      |
|                                       | Redo o. Remove Lexer        |                         |                          |      |
|                                       | Remove Spaces from Grammar  |                         |                          |      |
|                                       |                             | Integration Testing     |                          |      |

## 2.1 Expand PictureMapper
In der PL/I Language Reference, S. 329 bis S. 343 wird der Picture Typ genauer beschrieben. Hier sind alle Ausprägungen des Typs beschrieben,
in der aktuellen Version fehlen einige Ausdrücke, diese müssen implementiert werden.

## 2.2 Tests for translated Regex
Tests für das transformierte Regex schreiben. Das Regex sollte durch den Java Regex Compilier, kombiliert und das Pattern angewendet werden.
Dazu am besten eine Testklasse schreiben die diesen Fall testet.

## 2.3 Add all Tokens to SymbolTable
Es sollen nahezu alle Tokens aus dem PL/I Handbuch von IBM abgedeckt werden.
Hierzu sollten auch alle Symbole in der Symboltabelle erfasst werden. Eventuelle sollten die Symbole aus einer externen Art "Dictonary" Datei in den Hashtable geladen werden.

# 3 Ziele & Motivation


## 3.1 Inhaltliche Schwerpunkte

## 3.2 Zielgruppe


## 3.3 Warum ein Transpiler?

### 3.3.1 Unterschied zwischen Interpreter und Compiler

# 4 Gliederung
## 4.1 Prototype der Gliederung


