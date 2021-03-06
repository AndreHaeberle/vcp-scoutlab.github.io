---
layout: multipage
title: Arduino - LED leuchtet
navtitle: LED leuchtet
category: Scoutlab Session Kit 1 für Arduino
permalink: /arduino-scoutlab-session-kit-1/led
section_start: true
---
# LED leuchtet

## Material
* 1x LED
* 1x 220 Ohm Widerstand
* 2x Kabel
* 1x Steckbrett

![Material: Aufbau: Arduino als Stromquelle](images/material_led1_arduino.png)

Wir nutzen den Arduino als Stromquelle. Für dieses Experiment musst du nichts programmieren.

## Die LED (Leuchtdiode)
LED’s leuchten nur, wenn der Strom in die richtige Richtung fließt. Das kürzere Bein wird an den GND-Pin(-), das längere Bein wird an den jeweiligen Pin angeschlossen. Damit die LED nicht zu viel Strom bekommt und durchbrennt haben wir zwischen LED und Pin noch einen Widerstand geschaltet.

![](images/LED-Aufbaue-leg.png)

## Wie funktioniert das Steckbrett?
Eine Steckbrett (englisch breadboard) verwenden wir, um elektronische Bauteile miteinander zu verbinden. Die mechanische Befestigung der elektronischen Bauteilen ermöglicht uns Versuchsschaltungen.
Beim Steckbrett sind die Bauteile nicht gelötet, sondern in Federkontakte gesteckt. Dadurch kann die Schaltung durch einfaches Umstecken geändert werden.

![Die Steckplatine](images/Steckplatine_BB-301_tutorial.png)

Bei diesem Steckbrett sind die äußeren Längsreihen über Kontakte (X und Y) alle miteinander verbunden. In den anderen Kontaktreihen sind jeweils fünf Kontakte (A bis E und F bis J) quer miteinander verbunden, wobei in der Mitte des Steckbretts eine Lücke (Isolator) ist.

<div style="page-break-after: always;"></div>
## Aufbau
![Aufbau: Arduino als Stromquelle](images/led1_arduino_Steckplatine.png)

Die LED wird mit dem Schutzwiderstand (am längeren Bein) am 5V - Pin angeschlossen. Das kürze Bein (GND) wird am GND-Pin angeschlossen. Wenn du alles richtig an geschlossen hast, leuchtet die LED.
