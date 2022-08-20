# javascript-map-delegate

# Überblick
Angenommen wir haben eine Liste mit Zahlen. 

Dann sind einige Zahlen gerade, und einige Zahlen sind ungerade.

Wir wollen die geraden Zahlen in einem Array und die ungeraden Zahlen in einem anderen Array ordnen.

Dazu möchten wir wieder `map()` benutzen.

## Aufgabenstellung - Teil 1
Dazu brauchen wir erst einmal die beiden Arrays, in die wir später ordnen werden.

Schreibe ein leeres Array `ungeradeZahlen`.

Schreibe nun ein leeres Array `geradeZahlen`.

Natürlich brauchen wir noch die Liste mit den Zahlen.

Das sind 9, 1, 4, 7, 2, 56, 3, 33, 89, 76, 473.

Lege sie auch in einem Array an.

## Aufgabenstellung - Teil 2
Jetzt brauchen wir `map()` auf das Array mit den Zahlen.

Hier wird es zur vorigen Aufgabe komplizierter.

Wir müssen in der `map()` nacheinander prüfen, ob die Zahlen gerade oder ungerade sind.

Je nachdem müssen wir die Zahl anschließend in das jeweilige Array `ungeradeZahlen` oder `geradeZahlen` pushen.

## Bonus
Findest du einen Weg, die Funktion aus der `map()` auszulagern?

D.h. die Funktion wird in `map()` nur noch aufgerufen, aber dort nicht definiert.
