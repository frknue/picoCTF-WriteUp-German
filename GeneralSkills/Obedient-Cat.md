# Obedient Cat
## BESCHREIBUNG
This file has a flag in plain sight (aka "in-the-clear"). [Download flag](https://mercury.picoctf.net/static/704f877da185904ec3992e7255a15c6c/flag).
## HINWEISE
1. Any hints about entering a command into the Terminal (such as the next one), will start with a '$'... everything after the dollar sign will be typed (or copy and pasted) into your Terminal.
2. To get the file accessible in your shell, enter the following in the Terminal prompt: $ wget https://mercury.picoctf.net/static/704f877da185904ec3992e7255a15c6c/flag
3. $ man cat
## LÖSUNG
1. Als erstes müssen wir die Datei herunterladen: wget https://mercury.picoctf.net/static/704f877da185904ec3992e7255a15c6c/flag
2. Wir müssen einfach nur den Dateiinhalt auslesen. Entweder einen Texteditor öffnen oder den `cat` Befehl benutzen.
`cat flag`
## FLAG
```
picoCTF{s4n1ty_v3r1f13d_1a94e0f9}
```