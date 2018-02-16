# Informatikprojekt-3-Nele-und-Marit
## Stundenübersicht des Informatikunterichts

[15/02/18, 1. Stunde](#1)

## Erste Stunde<a name="1"></a>

Wir haben  unser zweites Projekt abgegeben. Als drittes Projekt werden wir nun mit der Starlogo TNG Lernaktivität dort weitermachen, wo wir in der letzten Lernaktivität aufgehört haben. 

In unseren letzten Projekt haben wir mit der siebten Lernaktivität abgeschlossen: Wir haben ein Egoshooter-Spiel programmiert, in dem ein steuerbarer Luigi mit Paintbällen auf Giraffen schießt. Wird eine Giraffe getroffen, so färbt sie sich rot. Außerdem gibt es Löwen, welche sich zufällig im Spaceland bewegen. Trifft Luigi auf einen Löwen, so wird er gefressen, und das Spiel ist vorbei.

### Lernaktivität acht:

Wir haben unser Spiel zunächst so ergänzt, dass die Giraffen und Löwen verschwinden, wenn Luigi von einem Löwen gefressen worden ist.
Hierzu haben wir die globale Variable "Luigi Tot" eingeführt. Im "setup"-Bereich setzten wir diese zuerst auf "false". Im "collisions"-Bereich programmierten wir nun, dass die Variable als "true" wiedergegeben wird, wenn Luigi mit einem Löwen zusammengestoßen ist.
Dann fügten wir im "forever"-Bereich "if-test-then"-Blöcke hinzugefügt, und Die Paintbälle, Löwen und Giraffen sterben lassen, wenn "Luigi Tot" als "true" wiedergegeben wird.

![Screenshot01](Bilder/Screenshot29.png "Shot!")
