# IoT Abschlussprojekt

## Beschreibung
Dieses Projekt bietet Python-Skripte zur Konstantlichtregelung und Tageslichtsteuerung. 

## Inhaltsverzeichnis
- [Voraussetzungen](#voraussetzungen)
- [Installation](#installation)
- [Verwendung](#verwendung)
- [Konstantlichtregelung.py](#konstantlichtregelungpy)
- [Tageslichtsteuerung.py](#tageslichtsteuerungpy)
- [Mitwirkende](#mitwirkende)
- [Lizenz](#lizenz)

## Voraussetzungen
- RaspberryPi Pico W mit Circuitpython
- Adafruit libraries wie im Repository

## Installation
1. Lade den zip-Ordner auf dein lokales Gerät
2. Extrahiere den zip-Ordner
3. Kopiere den gesamten Ordner auf den unbeschriebenen RaspberryPi Pico W

## Verwendung
- Die Skript ekönnen mithilfe einer IDE ausgeführt werden.
- Das gewünschte Skript kann in code.py umbenannt werden. Dieses wird beim nächsten Mal automatisch eingeschaltet.

## Konstantlichtregelung.py
Dieses Skript fürt eine Konstantlichtregelung zu Demonstrationszwecken durch.

## Tageslichtsteuerung.py
Dieses Skript führt eine Tageslichtsteuerung nach DIN-Norm aus. Die Konfiguration kann wie folgt aussehen:
- lokal: Die Parameter sind lokal im Code etabliert und nicht veränderbar.
- über MQTT: Die Parameter können über einen MQTT-Broker verändert werden. (Dies ist nur auf Python möglich, da gewisse Pakete nicht auf Circuitpyhton verfügbar sind)

## Mitwirkende
- Posch Stefan
- Streicher Sandro
- Zischg Elias
