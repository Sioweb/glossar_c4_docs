---
title: "Erste Schritte"
weight: 1
---

# Erste Schritte

Damit der Glossar funktioniert, sind leider einige Schritte notwendig. In diesem Dokument wird näher gebracht, welche Einstellungen vorgenommen werden müssen, damit der Glossar genutzt werden kann. Alle Einstellungen finden im Backend statt.

Sollte einer der unten genannten Punkte nicht sichtbar und, oder erreichbar sein, kann es sein dass Sie nicht genügend Rechte besitzen. Fragen Sie Ihren Administrator, ob diese Seiten ggf. freigeschaltet werden können, oder ob er/sie diese Schritte übernehmen kann.

## Schritt 1

Legen Sie eine Seite in der Seitenstruktur an und nennen Sie diese `Glossar`. Diese Seite dient später als Begriff-Liste und Detailseite.

## Schritt 2

Öffnen Sie das Seitenlayout unter Themes / Seitenlayouts, die den Glossar enthalten wird. Sollten es mehrere Seitenlayouts sein, wiederholen Sie diesen Schritt.

In dem geöffneten Seitenlayout, muss nun das Template `j_glossar` unter jQuery eingebunden werden. Dadurch wird das Template `j_glossar.html5` geladen. Dieses Template kann verwendet werden um den Ablauf im Frontend zu individualisieren.

Speichern Sie nun das Seitenlayout.

## Schritt 3

Öffnen Sie die Einstellungen von Contao, sie finden diese im Menü auf der rechten Seite des Backends.

Ziehmlich am Ende der Einstellungen, befindet sich nun die Legende `Glossar Einstellungen` und eine einzelne Checkbox `Glossar aktivieren`, die Sie nun bitte aktivieren.

Contao blendet einige weitere für den Glossar essentielle Einstellungsmöglichkeiten ein. Für jetzt ist es ausreichend, wenn Sie am Ende der Glossar-Einstellungen die Weiterleitungsseite auswählen, auf die alle Begriffe im Frontend verlinken sollen. Wählen Sie nun die Seite, die Sie in Schritt 1 erstellt haben.

## Fertig

Der Glossar ist nun grundsätzlich eingerichtet. Bitte lassen Sie sich nicht durch die vielen Einstellungsmöglichkeiten verwirren, auf den nächsten Seiten, wird Ihnen erklärt, wie Sie weiter vorgehen müssen.