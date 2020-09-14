# System-Programmierung
## Hands-on zu Lektion 8
Für Slides und Code Beispiele, siehe [Lektion 8](../../../fhnw-syspr/blob/master/08/README.md)

> *Achtung: Arbeiten Sie nicht direkt auf diesem Repository.*<br/>
> *[Prüfen Sie die vorhandenen Forks, um das Repository für Ihre Klasse zu finden.](../../network/members)*

### a) Pipes, 15'
* Schreiben Sie ein Programm *my_pipe.c*, welches eine Pipe von Child zu Parent Prozess erstellt.
* Der Child Prozess soll die Nachricht "hello" an den Parent Prozess schicken, über diese Pipe.

### b) FIFO, 15'
* Schreiben Sie ein Programm *my_fifo_r.c*, das ein neues FIFO File erzeugt, und zum Lesen öffnet.
* Und ein zweites Programm *my_fifo_w.c*, welches dasselbe File öffnet und eine Nachricht überträgt.
* Was ist der Unterschied zu einem regulären File?
