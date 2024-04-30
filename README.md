# aspekte-formale-uebersetzung-programmiersprachen
Arbeitsergebnisse der PA 4 im Bezug auf den Transpiler vertiefen und verfeinern. Als Werkzeug hauptsächlich JavaCC. Möglichkeiten der automatisierten Codegenerierung sollen untersucht werden, insbesondere durch die Wahl eines geeigneten Datenmodells für PL/I Datentypen, indem Aspkete der objektorientierten Programmierung berrücksichtigt werden.

# 1 Kanban-board für die Erarbeitung der Bachelorarbeits

| Backlog                                         | To Do | Doing | Review | Done |
| :---------------------------------------------- | :---- | :---- | :----- | :--- |
| Theorie Teil1: Formale Grammatik                |       |       |        |      |
| Theorie Teil2: Aspektorientierte Programmierung |       |       |        |      |
| Programmierung: Projektstrukturierung           |       |       |        |      |
| Programmierung: Testing                         |       |       |        |      |

## 1.1 Theorie Teil 1: Formale Grammatik
- Theoretischer Abriss
- Einordnung der resultate der PA 4
	- PL/1 Syntax Wo zu finden?
	- Reguläre Ausdrücke Syntax
- Literatur
	- Chomsky Hierarchie Bücher
	- https://www-igm.univ-mlv.fr/~berstel/LivreCodes/Codes.html

## 1.2 Theorie Teil 2: Aspektorientierte Programmierung
- Wie funktioniert Aspektorientiert Programmierung?
	- Wie Löse ich mit Aspektorientierter Programmierung konkrete Probleme?
- JavaBeans
- Spring
	- Wie setzt Spring Aspektorientierte Programmierkonzepte ein?

## 1.3 Programmierung: Projektstrukturierung
Bausteine
- Software Architektur
	- Planen mithilfe eines UML
	- UX Design 
		- Website?
		- Docker Container?
- Fehlertracking

## 1.4 Programmierung: Testing
1. Transpiler wird getestet
1.1 Testen der Methoden von Lexer, Parser usw. (Bsp.: Kann dieses Zeichen verarbeitet werden?)
1.2 Baum testen auf Korrektheit

2. Transpilieren wird getestet
2.1 Output des transpilierten Pl/1 Codes im Verhältnis zum Pl/1 Code testen.

3. Der Transpilierte Code wird getestet
- Wie wird PL/1 Code Native getestet
- Funktioniert der Java Code richtig

4. Performance Test (erst am ende)

# 2 Ziele & Motivation
- Wie eine Art JavaScript Minifier oder 
- Einer Art PL/1 für alle um PL/I Code zu testen

## 2.1 Inhaltliche Schwerpunkte
- Beschreibung von formalen Grammatiken, als Input für den Compiler Compiler JavaCC.
- Entwurf von Java Klassenhierachie für PL/I Datentypen
- Übersetzung von Kontrollstrukturen und komplexeren Programmabläufen
- Struktuierung des Programms, sodass ein Benutzer es selbständig erweitern kann

# 2.2 Zielgruppe
Junior Entwickler die gerade in PL/1 einsteigen.

# 2.3 Warum ein Transpiler?
- Lernhilfe für angehende junge Pl/1 Entwickler
- Smoketest

### 2.3.1 Unterschied zwischen Interpreter und Compiler
- Erweiterung des Umfangs während der Laufzeit
- Trennung Laufzeit/Konzeptionsphase

# 3 Gliederung
## 3.1 Prototype der Gliederung
1 Theoretische Grundlagen
1.1 Problemstellung 
1.2 Zielsetzung 
1.5 Abgrenzung Interpreter und Transpiler
1.3 Formale Grammatiken / Wofür Formale Grammatiken
1.4 Anwendung in JavaCC / Verwendung von regulären Ausdrücken als Datentyp (Tokens)

2 Technisches Vorgehen / Aspektorientierte Programmierung / Beans
2.1 Technisches Vorgehen / Aspektorientierte Programmierung / Beans
2.3 Architektur

3 Technische Spezifikation / Ausführung des Transpilers
2.4 Ausführung des Transpilers
3.1 Testing

4 Auswertung und Diskussion
2.2 Bedienung
4.1 Bewertung des Versuchs
4.2 Erweiterungsmöglichkeiten
4.3 Fazit

