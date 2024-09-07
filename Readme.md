# Über diesen Fork

Dieser Fork soll das Verhalten des Helpers ändern, so dass sich stufenweise zuerst die Anzahl angezeigter richtiger Kombinationen nach dem Geschicklichkeitswert richtet und ab einer Weile die Richtigkeit der gezeigten Kombinationen vom Geschick abhängt.

Beispiel: Zuerst werden immer nur die letzten zwei richtigen Kombinationen angezeigt, mit etwas mehr Geschicklichkeit dann drei usw. bis hin zu einem bestimmten Wert.
Ab dort hängt es dann von der Geschicklichkeit ab, ob die gezeigte Richtung auch richtig ist.

## Status

Momentan ist nur die Idee dazu vorhanden. Ich werde mir den Quelltext dazu bald ansehen.

# Verwendete Bibliotheken

- Ikarus (Ninja-Intern)
- LeGo (Ninja-Intern)

# Build Anleitung

1. GothicVDFS 2.6 starten.
1. Filename auf "Mein\Toller\Pfad\PickLockHelper.vdf" setzen.
1. Root Path auf "Pfad\Zu\Repository\" setzen.
1. Unter "File(mask)(s) to search for" den Wert "Ninja\" hinzufügen.
1. Build Volume drücken.
1. Ninja 2+ installieren, wenn noch nicht getan.
1. Erstellte .VDF in das "Gothic2\Data"-Verzeichnis legen.

# How it looks

![IngameExample](./Ingame_Gothic2.jpg)

# Credits
`F A W K E S` (WoG) - Für die reguläre Implementation 
