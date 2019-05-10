---
title: "System"
weight: 1
---

# Systemeinstellungen

Um den Glossar und seine Einstellungen zu aktivieren, muss die Option `Glossar aktivieren` aktiviert sein.

## Einstellungen in Detail

### Glossar in der Systemwartung/Daten bereinigen anzeigen

Um den Glossar aufzuräumen bzw. komplett auf allen Seiten zurückzusetzen, kann dieser in der Systemwartung angezeigt werden. Lassen Sie dieses Häkchen inaktiv, wenn Sie es gewohnt sind immer komplett alle Daten zu bereinigen.

### Tooltips deaktivieren

Die Tooltipps erscheinen, sobald der Besucher mit der Maus über einen Begriff fährt. Dieses Verhalten ist nicht immer Informativ und kann als nervend empfunden werden. Diese Option verhindert, dass die Vorschau überhaupt angezeigt wird.

### Begriffe immer verlinken

Begriffe ohne Inhaltselemente, werden normalerweise nicht verlinkt. Sie zeigen lediglich, falls nicht anders eingestellt, das Vorschaufenster. Diese Option verlinkt auch `leere` Begriffe und zeigt auf der Detailseite den hinterlegten Teasertext an.

### Begriffe als Headline aktivieren

Dieses Hilfsmittel fügt den Begriff auf der Detailseite als Headline-Element ein, falls kein anderes Headline-Element hinzugefügt wird.

### Pluralsuche deaktivieren

Wenn der Glossar `Wasser` sucht, findet dieser auch das Wort `Wasserfall`. Diese Einstellung unterdrück das Verhalten und findet nur alleinstehende Begriffe.

### Von der Suche ausgeschlossene Inhalte einbeziehen

Inhalte wie Navigation, Footer etc. sind von der Suche ausgeschlossen, da diese sonst immer in der Suche auftauchen würden, auch wenn diese auf allen Seiten sichtbar sind. Diese Elemente sind ebenfalls vom Glossar ausgeschlossen. Möchten Sie diese einbinden, müssen Sie diese Option aktivieren.

### Glossar Tags aktivieren

Diese Option bietet entwicklern ein Äquivalent zu den von der Suche ausgeschlossenen Inhalten.

```
<!-- glossar::stop -->
<div id="something">
    <p>Diese Inhalte werden vom Glossar ignoriert</p>
</div>
<!-- glossar::continue -->
```

### Cache umgehen

Diese Option macht die Webseite vermutlich sehr langsam, wenn es mehrere Begriffe zu suchen gibt. Bei ein - zehn Begriffen sollte diese Option kein Problem darstellen, allerdings ist dies nicht empfohlen. Der Vorteil dieser Option ist allerdings, dass der Glossar-Index nicht aufgebaut werden muss.

### Keine fremdsprachigen Glossare

Der Glossar sucht nach allen Begriffen die definiert wurden und unterscheidet erst einmal nicht, ob diese sich in einem deutschem oder englischen Glossar befinden. Begriffe aus anderssprachigen Glossaren, werden allerdings in ein extra Feld in der Datenbank gespeichert. `Keine fremdsprachigen Glossare` verhindert, dass beispielsweise englische Begriffe auf deutschen Seiten ersetzt werden.
 
### Archive ausschließen

Sollten Sie News, Events und oder FAQ installiert haben, können Sie diese hier global vom Glossar ausschließen. Sie können aber auch in den jeweiligen Archiven, einzelne Archive deaktivieren.

### Strikte Suche

### Maximale Vorschauhöhe und Vorschaubreite

Diese Einstellung bestimmt, wie groß das Vorschaufenster sein soll.

### Tags ingonieren

Hierbei handelt es sich um HTML-Tags. Notieren Sie hier kommagetrennt, welche HTML-Tags vom Glossar ignoriert werden sollen.

### Pluralsuche

Der Glossar erkennt nicht wirklich, ob ein Begriff nun in Plural, oder Singular geschrieben steht. Der Glossar identifiziert ein Wort, bis eines der hier eingetragenen Sonderzeichen oder ein Leerzeichen erscheint. Schreiben Sie zum Beispiel `eins+eins`, wird nur die das erste Wort ersetzt: `eins`+eins.

### Glossar-Seite

In den meisten Fällen, reicht es aus, wenn es nur eine Glossar-Seite gibt. Ein Inhaltselement auf dieser Seite, kann alle Begriffe als Liste oder Detailansicht darstellen. Geben Sie hier an, wohin der Benutzer geleitet wird, wenn er auf einen Begriff klickt. Sie können diese Seite nochmals pro Begriff angeben.

### Maximale Begriffsmarkierung auf einer Seite

Sollte ein Begriff oft im Text einer Seite auftauchen, wäre die ganze Seite voller Links welche eine Vorschau laden können. Damit die Seite nicht Überlädt mit Links, können Sie hier angeben, wie oft ein Begriff maximal ersetzt werden darf. 0 (Null) entspricht unendlich oft. Sollte ein Begriff zwar auf der Seite erscheinen, aber nicht als Begriff markiert worden sein, könnte der Begriff auch in einem bislang unsichtbaren Element stecken. Sie können also die Zahl solange erhöhen, bis dieser markiert wird. Testweise ist es empfehlenswert, 1 und 20 auszuprobieren und danach erst 2, 3, 4.