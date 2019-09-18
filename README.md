# Quiz Game
JavaScript Quiz-Spiel

Das Projekt soll in Zweier-Gruppen programmiert werden.

### Spiel-Logik
- Der Spieler interagiert mit dem Spiel über Eingaben im prompt-Fenster
- Am Anfang wird eine Begrüßungsnachricht angezeigt: "Willkommen beim DCI-Quiz! Bist du bereit, dich meinen Fragen zu stellen?"
- Es werden zwei mögliche Antworten vorgeschlagen: "a. Halt die Klappe und leg endlich los!", "b. Lass mal, ich will nicht denken."
- Der Spieler kann "a" oder "b" eingeben. Bei "a" wird die erste Frage angezeigt
- Die Quiz-Fragen können Multiple-Choice-Fragen sein, wie die Begrüßungsfrage oder Freitext-Fragen, für die der Spieler ein Wort als Antwort schreiben muss.


## Aufgaben Partner A
- Arbeite in der Datei questions.js
- Erstell ein "questions"-Objekt
- Es soll die Methode "getQuestion" haben. Diese Methode hat einen Parameter für die Nummer der Frage und gibt den String der entsprechenden Frage zurück
- Es soll die Methode "checkAnswer" haben. Diese Methode soll einen Parameter für die Antwort haben und true oder false zurückgeben, je nach dem ob die Antwort richtig ist

## Aufgaben Partner B
- Arbeite in der Datei interface.js
- Erstell ein "game"-Objekt
- Es soll die Methode "startGame" haben
- Es soll Eigenschaften zum Speichern dieser Informationen haben:
  - Wieviele Fragen hat der Spieler bisher beantwortet
  - Wieviele Fragen hat der Spieler richtig beantwortet
- Füg die Methode "askQuestion" hinzu. Diese Methode soll:
  - Die nächste Frage mit der "getQuestion"-Methode des questions-Objekts holen
  - Ein prompt mit der Frage stellen
  - Die Antwort mit der "checkAnswer"-Methode des questions-Objekts prüfen
  - Speichern, ob die Antwort richtig war

## Hilfe
###### Objekt erstellen
```javascript
var name = {
  property: value,
}
```
