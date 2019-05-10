---
title: "Installation"
weight: 1
---

# Installation

## Composer

Der Glossar, kann über die Konsole und den Contao Manager installiert werden. Im Manager muss lediglich der Paketname `sioweb/glossar` gesucht werden, in der Konsole wird etwas mehr benötigt.

Die Konsole benötigt in jedem Fall [Composer](https://getcomposer.org/). Composer kann lokal als `composer.phar`-Datei oder global auf dem Server bzw. der Laufzeitumgebung hinterlegt sein.

**Hinweis:** Da Composer ohne Weiteres 1GiB - 3GiB Arbeitsspeicher belegen kann, ist es ratsam Pakete lokal mit Composer zu laden und mit der Cache-Datei `composer.lock` den Stand auf dem Server mit `composer install` zu aktualisieren.

### Composer global

```
composer req sioweb/glossar
```

### Composer als PHAR-Datei

Je nach Hoster, reicht es nicht aus einfach `php ...` zu nutzen, Domainfactory nutzt in der Konsole standardmäßig PHP 4. Es ist zwingen empfohlen, PHP 7+ zu verwenden. Fragen Sie ggf. Ihren Hoster, wie der Pfad zu anderen PHP Versionen lautet.


*PHP ist global nutzbar*

Mit `php -v` kann die Version von PHP ermittelt werden.

```
php composer.phar req sioweb/glossar
```

*PHP als Pfad*

Der Speicherort der PHP-Versionen, ist von Hoster zu Hoster unterschiedlich, hier ein Beispiel:

```
/usr/local/bin/php7-71/bin/php composer.phar req sioweb/glossar
```

## Datenbank

Damit der Glossar funktioniert, muss die Datenkbank aktualisiert werden. Dazu wird das Install-Tool von Contao verwendet. Der Contao Manager wird direkt nach der Installation fragen, ob die Datenbank installiert werden soll. Sollte dies nicht passieren, kann das Tool auch oben rechts über den Menüpunkt `Tools/Install Tool` geöffnet werden.

Alternativ ist das Tool auch direkt über die URL erreichbar, dazu muss lediglich `/contao/install` an die Domain angehängt werden. (https://www.domain.tld/contao/install)

Nach der Anmeldung im Install-Tool, kann die Datenbank aktualisiert werden.