# Informatikprojekt-3-Nele-und-Marit
## Stundenübersicht des Informatikunterichts

[15/02/18, 1. Stunde](#1)

[16/02/18, 2. und 3. Stunde](#2)

[22/02/18, 4. Stunde](#3)

[23/02/18, 5. und 6. Stunde](#4)

## Erste Stunde<a name="1"></a>

Wir haben  unser zweites Projekt abgegeben. Als drittes Projekt werden wir nun mit der Starlogo TNG Lernaktivität dort weitermachen, wo wir in der letzten Lernaktivität aufgehört haben. 

In unseren letzten Projekt haben wir mit der siebten Lernaktivität abgeschlossen: Wir haben ein Egoshooter-Spiel programmiert, in dem ein steuerbarer Luigi mit Paintbällen auf Giraffen schießt. Wird eine Giraffe getroffen, so färbt sie sich rot. Außerdem gibt es Löwen, welche sich zufällig im Spaceland bewegen. Trifft Luigi auf einen Löwen, so wird er gefressen, und das Spiel ist vorbei.

### Lernaktivität acht:

Wir haben unser Spiel zunächst so ergänzt, dass die Giraffen und Löwen verschwinden, wenn Luigi von einem Löwen gefressen worden ist.
Hierzu haben wir die globale Variable "Luigi Tot" eingeführt. Im "setup"-Bereich setzten wir diese zuerst auf "false". Im "collisions"-Bereich programmierten wir nun, dass die Variable als "true" wiedergegeben wird, wenn Luigi mit einem Löwen zusammengestoßen ist.
Dann fügten wir im "forever"-Bereich "if-test-then"-Blöcke hinzugefügt, und Die Paintbälle, Löwen und Giraffen sterben lassen, wenn "Luigi Tot" als "true" wiedergegeben wird.

![Screenshot01](Bilder/Screenshot.sltng.29.png "sltng")


## Zweite und dritte Stunde<a name="2"></a>

Zunächst haben wir den Stundenblog der letzten Stunde ergänzt.

Dann haben wir begonnen, die erste vorgegebene Aufgabe der achten Lernaktivität umzusetzen. Mit dem "Edit Terrain" Tool haben wir Wände im Spaceland erstellt, indem wir die Höhe einzelner Partien des Spacelands erhöht haben. Damit diese Wände auffälliger sind haben wir sie mit dem "drawing" Tool weiß angemalt. Wir fühlten uns in unsere Kindergartenzeit zurückversetzt, als wir merkten, wie nervenaufreibend es ist, ständig "überzumalen" und diese Fehler dann wieder verbessern zu müssen.

![Screenshot01](Bilder/Screenshot.sltng.31.png "sltng")

![Screenshot01](Bilder/Screenshot.sltng.30.png "sltng")


## Vierte Stunde<a name="3"></a>

Wir begannen die Stunde damit, Luigi, die Paintbälle und die Tiere so zu programmieren, dass sie nicht mehr durch die Wände durchlaufen. Hierzu haben wir in den jeweiligen Methoden "if-test-then"-Blöcke benutzt: Mit dem Block "Wall ahead?" ließen wir testen, ob der jeweilige actor gegen eine Wand läuft. Für den Fall, dass er dies tut, haben wir die Paintbälle verschwinden lassen, Luigi um 90°, und die Giraffen und Löwen um 180° drehen lassen.  

![Screenshot01](Bilder/Screenshot.sltng.32.png "sltng")

Wir beschlossen mit dieser Änderung die Lernaktivität acht abzuschließen und begannen mit Lernaktivität neun.

### Lernaktivität neun

Die Aufgabe dieser Lernaktivität besteht daraus, eine Epidemie zu programmieren. Hierzu erstellten wir zunächst die Rasse der Bären. Wir programmierten einen slider, mit dem man die Anzahl der Bären einstellen kann, und dass diese blau gefärbt sind. Außerdem programmierten wir die Prozedur "bewegen", nach der die Bären sich willkürlich bewegen.

![Screenshot01](Bilder/Screenshot.sltng.33.png "sltng")
![Screenshot01](Bilder/Screenshot.sltng.34.png "sltng")

## Fünfte und sechste Stunde<a name="4"></a>



