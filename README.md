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
