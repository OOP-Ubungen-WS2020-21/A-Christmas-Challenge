---
title: Christmas Challenge: Platformer Game
author: Zuletzt bearbeitet von Jürgen Hahn
documentclass: scrartcl
classoption:
  - a4paper
header-includes: |
    \usepackage{german} 
    \usepackage[a4paper,left=2.5cm, right=2.5cm,top=2.5cm, bottom=3cm]{geometry}
    \usepackage{fancyhdr}
    \usepackage{graphicx}
    \pagestyle{fancy}
    \fancyhf{}
    \rhead{OOP WS 2020/21}
    \lhead{Christmas Challenge: Platformer Game}
    \cfoot{\includegraphics[height=2cm]{docs/footer.png}}
    \fancypagestyle{plain}{
      \fancyhf{}
      \rhead{OOP WS 2020/21}
      \lhead{Christmas Challenge: Platformer Game}
      \cfoot[C]{\includegraphics[height=2cm]{docs/footer.png}}}
---


# Christmas Challenge: Platformer Game

## Wichtige Informationen zur Bearbeitung der Aufgabe 
 - [Informationen zur Entwicklungsumgebung *IntelliJ IDEA*](https://elearning.uni-regensburg.de/mod/book/view.php?id=1480675)
 - [Informationen zum Im- und Export von Projekten](https://elearning.uni-regensburg.de/mod/book/view.php?id=1480675&chapterid=51551)
 - [GraphicsApp](https://elearning.uni-regensburg.de/mod/url/view.php?id=1482162)

## Starterpaket

Ein vorbereitetes Starterpaket zur selbständigen Implementierung der Christmas Challenge finden Sie [hier](https://github.com/OOP-Ubungen-WS2020-21/A-Christmas-Challenge/archive/Starterpaket.zip).

## Die OOP-Weihnachts-Challenge

Sie kriegen nicht genug vom Programmieren? In den Weihnachtsferien ist Ihnen langweilig? Dann nehmen Sie doch an der **OOP-Weihachts-Challenge** teil und entwerfen Sie Ihr ganz persönliches Weihnachtsspiel!

## Die Aufgabe

Programmieren Sie ein weihnachtliches [*Jump and Run*-Spiel](https://en.wikipedia.org/wiki/Platform_game). Sie können dabei alle Aspekte frei gestalten. Damit wir alle Einreichungen fair vergleichen können, gelten die folgenden Regeln:

- Ihr Spiel muss auf Basis des Starterpakets und der dort vorhandenen Version der *GraphicsApp* implementiert werden.
- Ihr Spiel muss dem Genre der *Jump and Run* bzw. *Platformer* zu geordnet werden können.
- Ihr Spiel muss erkennbar ein weihnachtliches oder winterliches *Theme* vorweisen.

Das Aussehen und die Spielmechanik können Sie frei wählen. Sounds, Musik und Grafiken finden Sie z.B. auf [freesound.org](https://freesound.org/), im [Free Music Archive](https://freemusicarchive.org/static) (Aktuell mit eingeschränkter Suchfunktion), auf [OpenGameArt.org](https://opengameart.org/) und [itch.io](https://itch.io/).

## Teilnahme

Laden Sie das [Starterpaket](https://github.com/OOP-Regensburg/A-Christmas-Challenge-Starter/archive/starter.zip) herunter und beginnen Sie mit dem Programmieren. Entwickeln Sie ein *Jump and Run*-Spiel und schicken Sie das fertige Projekt als ZIP-Datei bis zum 7. Januar 2020 an **alexander.bazo@ur.de**. Im Starterpaket finden Sie eine Textdatei mit dem Namen `README.md`. Bitte füllen Sie diese vor Abgabe aus. Sollte Ihr Spiel auf Grund der Dateigröße nicht per E-Mail versendet werden können, können Sie mir auch einen Download-Link (z.B. via Dropbox) schicken.


### Neue Funktionen in der GraphicsApp

Im Starterpaket zur *Challenge* wird eine neue Version der GraphicsApp verwendet, in der Sie diese zusätzlichen Funktionen verwenden können:

#### Audio

Mithilfe der Klasse `AudioClip` können Sie [`WAV`-Dateien](https://en.wikipedia.org/wiki/WAV) wiedergeben. Bestehende Audiodateien können Sie z.B. mit dem kostenlosen Werkzeuge [Audacity](https://www.audacityteam.org/) in das `WAV`-Format konvertieren.


``` java
Audio Clip backgroundMusic = new AudioClip("sound.wav");
backgroundMusic.loop();
```

#### Label

Die `Label`-Klasse verfügt jetzt über neue Methoden zum Ändern der Schriftart und -Größe. Die verwendete Schriftart muss auf dem jeweiligen Rechner installiert sein - verwenden Sie am besten Standardschriften.

``` java
Label label = new Label(0, 0, "Hello World");
label.setFont("Monospaced");
label.setFontSize(24);
label.setColor(Colors.WHITE);
```

## Bewertung 

Das OOP-Team spielt und bewertet alle Einreichungen. Die drei besten Einreichungen werden im Kurs vorgestellt.
Mitmachen lohnt sich! Wenn Sie wollen, machen wir Ihr Spiel auch für die übrigen KursteilnehmerInnen zugänglich.

**Viel Erfolg und erholsame Feiertage!**
