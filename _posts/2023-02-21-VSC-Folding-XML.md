# Visual Studio Code Folding XML

Dieser Post ist für Benutzer von Visual Studio Code interessant. 
Er beschreibt, wie man XML-Dateien besser im Editor darsstellen kann.

## Folding

Unter Folding vestehen wir die Möglichkeit, Bereiche im Quellcode einzuklappen (falten) und dadurch die umschleißenden Bereiche besser zu erfassen.

Bei XML-Dateien kann Visual Studio Code die Struktur erkennen und entsprechend die einzelnen Elemente zusammenfalten. 

![](https://raw.githubusercontent.com/ingraban/ingraban.github.io/main/img/vsc-folding-xml-00003.png)

Dadurch geht immer noch ein wenig Platz verloren, der nicht unbedingt notwendig ist, wenn die Formatierung korrekt ist.

![](https://raw.githubusercontent.com/ingraban/ingraban.github.io/main/img/vsc-folding-xml-00002.png)

Das obige Bild zeigt, wie es auch aussehen kann, wenn man die Einstellung XML > Foldings > **Include Closing Tag in Fold** aktiviert.

![](https://raw.githubusercontent.com/ingraban/ingraban.github.io/main/img/vsc-folding-xml-00001.png)

Wenn man die Einstellungen öffnet und nach *fold* sucht, findet man die Einstellung im Bereich Erweiterungen > XML.

## Tastatur

Man kann auch über die Tastatur das Falten (folding) aktivieren.

### Alle Falten

Mit der Standard-Tastenkombination <kbd>⌘</kbd>+<kbd>K</kbd> <kbd>⌘</kbd>+<kbd>0</kbd> wird die gesamte Datei zugefalten.  
Mit der Standard-Tastenkombination <kbd>⌘</kbd>+<kbd>K</kbd> <kbd>⌘</kbd>+<kbd>J</kbd> wird die gesamte Datei aufgefalten.

Um einzelne Bereiche zusammenzufalten, muss man seine Einstellen prüfen und ggf. anpassen.
Man öffnet die Tastaturkombinationen über <kbd>⌘</kbd>+<kbd>K</kbd> <kbd>⌘</kbd>+<kbd>S</kbd>.
Dort sucht man nach *falten*.

Ich habe für mich <kbd>⌘</kbd>+<kbd>K</kbd> <kbd>⌘</kbd>+<kbd>+</kbd> für das Auffalten und <kbd>⌘</kbd>+<kbd>K</kbd> <kbd>⌘</kbd>+<kbd>-</kbd> für das Zufalten eines Bereichs definiert.

Diese Einstellungen funktionieren auch bei Markdown.
