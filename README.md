# Prüfungsaufgaben zur Vorlesung

In der Vorlesung wurde/wird ein Spiel (TicTacToe) entwickelt und dabei eine Reihe von
Hilfsfunktionen entwickelt und benutzt, die den Umgang mit rechteckigen Spielfeldern
unterstützen.

Im Rahmen der Prüfungsaufgaben sollen Sie nun ein weiteres Spiel in diesem Stil
entwickeln, dabei die vorhandenen Funktionen verwenden, anpassen und ggf.
neue Funktionen hinzufügen.
Außerdem sollen Sie das Spiel und ggf. neue Hilfsfunktionen dokumentieren und testen.


## Aufgabe: Entwicklung eines weiteren Spiels auf Basis der Hilfsfunktionen aus der Vorlesung.

- Entwickeln Sie ein Spiel in Python auf Basis der Hilfsfunktionen aus der Vorlesung.
  Erweitern Sie die Sammlung an Hilfsfunktionen, um die benötigte Funktionalität
  für Ihr Spiel bereitzustellen.
- Dokumentieren Sie Ihr Spiel sowie die Hilfsfunktionen.
  Stellen Sie zu jeder Funktion einen *Docstring* bereit, der die Funktion erklärt.
  - Hinweis: *Docstring* steht für "Documentation String".
    In Python sind das die `'''...'''`-Strings unter den Funktionen.
- Schreiben Sie für die wesentlichen Funktionen Unit-Tests,
  die das Verhalten beschreiben und prüfen.
- Das Spiel sollte in einem funktionalen Stil geschrieben sein, also möglichst ohne
  Seiteneffekte, Schleifen etc.

### Spielideen
 
 Es folgt eine kurze Liste von Spielen bzw. Spielideen, die für die Aufgaben geeignet
 sein könnten:

 - Vier gewinnt
 - Reversi
 - Schiffe Versenken
 - TicTacToe-Erweiterungen
   - z.B. 9x9-Feld oder [Ultimate TicTacToe](https://ultimatetictactoe.creativitygames.net/)

Dies sind nur Ideen, Sie sind grundsätzlich frei in der Wahl des Spiels.
Falls Sie eigene Ideen haben, die Sie gerne umsetzen möchten, können Sie das machen.


## Bewertungskriterien

- Funktionalität
  - Das Spiel muss grundsätzlich funktionieren, d.h. einer oder mehrere menschliche
    Spieler müssen es an einem Computer über die Konsole spielen können.
    Eine KI oder grafische Benutzeroberfläche ist nicht notwendig.
- Modularität
  - Der Code sollte so weit wie möglich in sinnvolle Teilfunktionen zerlegt sein.
  - Konkrete Spiel-Funktionalität sollte auf allgemeine Funktionen abgebildet werden,
    die das Spielfeld als Listen, Strings etc. modellieren.
  - Jede Funktion sollte möglichst nur einen Zweck erfüllen.
  - Code-Duplizierung sollte vermieden werden.
- Tests
  - Die wesentliche Funktionalität muss durch Unit-Tests geprüft/abgedeckt sein.
    Dies gilt insbesondere für alle Hilfsfunktionen, die für die Umsetzung der
    Spiellogik benutzt werden.
    Ein-/Ausgabe muss nicht automatisiert getestet werden.
- Code-Qualität und Dokumentation
  - Sind Funktionen sinnvoll benannt und dokumentiert?
  - Haben Variablen sprechende Namen?
  - Gibt es Kommentare im Code an Stellen, wo das notwendig erscheint?
  - Sind Einrückungen einheitlich, ist der Code insgesamt gut lesbar?
- Programmierstil
  - Gibt es Seiteneffekte, wurde funktional programmiert?
    Zur Erinnerung: Das ist eine der Anforderungen.
  - Schleifen und imperativer Stil sollten möglichst wenig vorkommen,
    Generator-Ausdrücke, -Funktionen und List Comprehensions sind zu bevorzugen.
    

## Rahmenbedingungen
- Es darf in Gruppen gearbeitet werden, 2-3 Personen pro Gruppe.
- Bei der Abgabe müssen die Teilnehmer der Gruppe sowie die jeweiligen Arbeitsanteile
  kenntlich gemacht werden.
- Jede Gruppe bzw. jeder Teilnehmer muss seine Arbeit in einem kurzen Prüfungsgespräch
  vorstellen.
  - Ziel: Prüfung der Eigenständigkeit und Hilfestellung/Hinweise.
  - Die Aufgabe muss dabei noch nicht abgeschlossen sein.
  - **Beim Prüfungsgespräch muss jeder Teilnehmer einen Beitrag leisten.**


## Termine
- Abgabe über Moodle bis Ende des Semesters (7. Mai)
  - Als Zip-Datei mit dem Code, Link zu Git-Repo o.Ä.
- Prüfungsgespräche ab Montag, 19. April bis zur Abgabe.
