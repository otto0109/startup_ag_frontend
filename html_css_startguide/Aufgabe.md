# Guide

Erstelle eine Datei und nenne Sie ```index.html```

Html ist eine Scriptsprache, mit welcher sich die Struktur einer Webseite gestalten lässt.

In Html gibt es verschiedene Elemente, diese werden mit ```<Element> </Element>```
definiert. Innerhalb dieses Elements können mehrere andere Elemente platziert werden.
Diese nennt man Children. Man spricht auch von einer Child-Parent Beziehung.

Der oberste Parent ist immer ```<html></html>```
dieser Parent beinhaltet üblicherweise 
```
<html>
    <head></head>
    <body></body>
</html>
```
In ```<head></head>``` können Metainformationen mitgeben werden, wie zum Beispiel 
den Title einer Webseite oder wie die Webseite auf anderen Seiten dargestellt werden soll.

In ```<body></body>``` werden üblicherweise alle Elemente der Webseite gepackt.

## Get your hands on
Erstelle eine datei und nenne sie ```index.html```

Füge folgenden Code hinzu:
```
<html>
    <head></head>
    <body></body>
</html>
```

Schaue dir doch mal auf https://www.codecademy.com/learn/learn-html/modules/learn-html-elements/cheatsheet
ein paar Elemente an und probiere ein bisschen aus.

Mit Doppelklick kann man die Datei ausführen.

## CSS
CSS ist eine Sprache, welche es ermöglicht HTML Elemente zu designen.

Um Html in CSS nutzen zu können, solltest du eine Datei erstellen und sie ```index.css``` nennen.
Füge ```<link rel="stylesheet" href="index.css"/>``` in den Head der Html Datei ein.

Nun kann man über Attribute einem HTML Element css Klassen zuweisen:
```<div class="test"></div>```
Füge doch dieses Element einmal in den html body ein.

In der css datei können wir nun wie folgt dem Element css Styles geben:
```
.test {
 width: 200px;
 height: 200px;
 background-color: pink;
}
```
Probiere doch selber ein paar CSS Attribute aus.

Als Nächstes könntest du dich hier einmal umschauen und ein bisschen was davon ausprobieren:
https://css-tricks.com/snippets/css/a-guide-to-flexbox/

Fühlst du dich fit mit CSS?
Besuche doch mal:
https://cssbattle.dev
und versuche, dass eine oder andere battle zu lösen.
Ein einfaches wäre: https://cssbattle.dev/play/30