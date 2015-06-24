---
layout:     post
title:      Ventilate
date:       2015-06-23 11:21:29
summary:    Die letzte Aufgabe bestand darin, einen auf dem Arduino Mikrocontroller basierenden, funktionsfähigen Prototypen bzw. „Apparat“ zu entwickeln, welcher auf einen bestimmten Input einen bestimmten Output liefert. Die Wahl der Sensoren und Komponenten zur Ein- und Ausgabe waren dabei frei wählbar...
categories: Project
---

<img src="{{site.image_path}}/posts/tookii_test.jpg" />

###Konzeption
Mein Hauptintention bei der Konzeption des Apparates war es, einen „nützlichen“ Gegenstand zu entwickeln, den ich im täglichen Leben einsetzen kann und mich vor etwas warnt, das ich als Mensch nur schwer bzw. nicht unmittelbar wahrnehmen kann. Letztendlich habe ich mich dafür entschiedenen, eine „intelligente“ Uhr für mein Büro zu konstruieren, welche mich über die Kohlenstoffmonoxid-Konzentration in der Luft informiert und mir durch eine Art „Schnapp-Atmung“ zu verstehen gibt, dass es nun höchste Zeit ist, den Raum zu lüften.

###Pulse Width Modulation
Über Pulse-Width-Modulation (PMW) wird das Pulsieren des LED-Rings ermöglicht, welcher über die PMW-fähigen, digitalen Pins 5, 9 und 10 mit einem Arduino Micro verbunden ist. Im Prinzip können LEDs nur die Zustände „Ein“ oder „Aus“ annehmen; durch Pulsbreitenmodulation ist es aber möglich, das Intervall zwischen diesen Zuständen gezielt zu steuern. Durch die Trägheit des menschlichen Auges entsteht dadurch die Illusion, dass die LED dunkler (längeres Intervall) bzw. heller (kürzeres Intervall) leuchten würde.

####Embedded Gist 
<script src="https://gist.github.com/pfingstday/1932989f2535daaa0618.js"></script>
