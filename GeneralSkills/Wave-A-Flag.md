# Wave a flag
## BESCHREIBUNG
Can you invoke help flags for a tool or binary? [This program](https://mercury.picoctf.net/static/beec4f433e5ee5bfcd71bba8d5863faf/warm) has extraordinarily helpful information...
## HINWEISE
1. This program will only work in the webshell or another Linux computer
2. To get the file accessible in your shell, enter the following in the Terminal prompt: $ wget https://mercury.picoctf.net/static/beec4f433e5ee5bfcd71bba8d5863faf/warm
3. Run this program by entering the following in the Terminal prompt: $ ./warm, but you'll first have to make it executable with $ chmod +x warm
4. -h and --help are the most common arguments to give to programs to get more information from them!
5. Not every program implements help features like -h and --help.
## LÖSUNG
1. Als erstes müssen wir die Datei herunterladen `$ wget https://mercury.picoctf.net/static/beec4f433e5ee5bfcd71bba8d5863faf/warm`
2. Mit dem Befehl `$ file warm` bekommen wir mehr Information über die Datei. Es handelt sich hierbei um eine ausführbare Datei.
3. Um die Datei ausführen, müssen wir es die erforderlichen Berechtigungen geben `$ sudo chmod +x ./warm`
4. Jetzt können wir die Datei ausführen `$ ./warm` -> `Hello user! Pass me a -h to learn what I can do!`
5. Noch einen einen Parameter mitgeben `$ ./warm -h` -> `Oh, help? I actually don't do much, but I do have this flag here: picoCTF{b1scu1ts_4nd_gr4vy_616f7182}`
## FLAG
```
picoCTF{b1scu1ts_4nd_gr4vy_616f7182}
```