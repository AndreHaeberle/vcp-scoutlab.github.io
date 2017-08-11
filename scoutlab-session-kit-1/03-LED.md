---
layout: multipage
title: LED leuchtet
permalink: /scoutlab-session-kit-1/led
section_start: true
---
# LED leuchtet

## Material
* 1x LED
* 1x 220 Ohm Widerstand
* 2x Kabel
* 1x Steckbrett

![Material: Aufbau: Raspberry Pi als Stromquelle](images/material_led1.png)

Wir nutzen den Raspberry Pi als Stromquelle. Für dieses Experiment musst du nichts programmieren.

## Die LED (Leuchtdiode)
LED’s leuchten nur, wenn der Strom in die richtige Richtung fließt. Das kürzere Bein wird an den GND-Pin(-), das längere Bein wird an den jeweiligen GPIO-Pin angeschlossen. Damit die LED nicht zu viel Strom bekommt und durchbrennt haben wir zwischen LED und Pin noch einen Widerstand geschaltet.

## Wie funktioniert das Steckbrett?
Eine Steckbrett (englisch breadboard) verwenden wir, um elektronische Bauteile miteinander zu verbinden. Die mechanische Befestigung der elektronischen Bauteilen ermöglicht uns Versuchsschaltungen.
Beim Steckbrett sind die Bauteile nicht gelötet, sondern in Federkontakte gesteckt. Dadurch kann die Schaltung durch einfaches Umstecken geändert werden.

![Die Steckplatine](images/Steckplatine_BB-301_tutorial.png)

<div style="page-break-after: always;"></div>
## Aufbau
![Aufbau: Raspberry Pi als Stromquelle](images/led1_Steckplatine_gpio.png)

Die LED wird mit dem Schutzwiderstand (am längeren Bein) am 5.5V - Pin angeschlossen. Das kürze Bein (GND) wird am GND-Pin angeschlossen. Wenn du alles richtig an geschlossen hast, leuchtet die LED.