# System-Programmierung
## Hands-on zu Lektion 6
Für Slides und Code Beispiele, siehe [Lektion 6](../../../fhnw-syspr/blob/master/06/README.md)

> *Achtung: Arbeiten Sie nicht direkt auf diesem Repository.*<br/>
> *[Prüfen Sie die vorhandenen Forks, um das Repository für Ihre Klasse zu finden.](../../network/members)*

### a) Threads, 20'
* Schreiben Sie ein Programm *my_pthreads.c* welches einen Thread erzeugt, und mit *pthread_exit()* endet.
* Geben Sie Thread ID, Argument und Resultat aus.
* Wie würde man mehrere Argumente übergeben?

### b) Mutex, 20'
* Lösen Sie die _Aufgabe 2_ aus [Assessment II von 2018](http://www.tamberg.org/fhnw/2018/Syspr14Assessment2.pdf).
* Implementieren Sie die fehlende _main()_ Funktion.
* Committen Sie die Lösung in _my_prod_cons.c_

### c) Producer/Consumer, 10'
* Das Producer/Consumer Problem ist ein Klassiker.
* Studieren Sie diese Version mit zirkulärem Buffer:<pre>
http://www.cs.fsu.edu/~baker/realtime/restricted/notes/prodcons.html</pre>

### Abgabe (optional)
* Lokale Änderungen [committen und pushen](#git).
* GitHub [Issue erstellen](../../issues/new) mit "Bitte um Review, @tamberg".
* Offene Fragen ausformulieren, was geht nicht, was haben Sie versucht.
* GitHub mailt mir (@tamberg) automatisch, ich versuche in weniger als 24h zu antworten :)

## Tools
### Git
Auf Ihrem Computer
* Zu Beginn jeder Lektion wird ein Hands-on Repository Link freigeschaltet
* Nachdem Sie das "Assessment" annehmen, bekommen Sie per Email ein Repository
* Die REPO_URL enthält Ihren GitHub Account USER_NAME und Ihre Klasse 3ia oder 3ib, z.B.<br/>
            https://github.com/fhnw-syspr-3ia/fhnw-syspr-work-06-tamberg

Auf dem Raspberry Pi
* Repository klonen<pre>
    $ cd ~
    $ git clone REPO_URL</pre>
* Neue Datei kreieren<pre>
    $ git add FILE</pre>
* Änderungen committen<pre>
    $ git commit FILE -m "Fixed all bugs"</pre>
* Änderungen hochladen<pre>
    $ git push</pre>

### Nano
Auf dem Raspberry Pi
* Neue oder bestehende Datei öffnen mit $ nano FILE
* Editieren (Achtung, nano hat kein Undo)
* Speichern mit `CRTL-X` `Y` `RETURN`

### SSH
Auf Ihrem Computer
* Terminal öffnen (Mac) oder `WINDOWS` `R` cmd `RETURN` (Windows)
* SSH Session starten mit<pre>
    $ ssh pi@raspberrypi.local</pre>

## Support
- [FHNW Syspr Slack](https://fhnw-syspr.slack.com/)
