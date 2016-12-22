# RobotConductor

*(English below)*

Dieses Tool kann ein (Flaschenblas-)Orchester quasi automatisch dirigieren.

Noten können dynamisch hinzugefügt werden. Man übergibt einfach einen Text (ohne Zeilenumbrüche!), in dem die Noten durch Buchstaben repräsentiert werden - unterstützt werden bisher `AHcdefgahCDEFG`, wobei die Kleinbuchstaben die "Standard-Oktave" vom mittleren C aus sind. Direkt darauf folgt eine Zahl (1, 2, 4, 8 oder 16), die die Länge (ganze, halbe, viertel etc.) angibt. Mit einem direkt dahinter folgenden `.` kann man die Note punktieren. Schreibt man eine `3` für die Länge, wird das als Achtelnote, die Teil einer Synkope ist, gewertet.

Pausen kann man verwenden, indem man als "Notenbuchstaben" ein `p` oder ein `-` schreibt und die Länge analog zu Noten angibt.

Zwischendurch darf man so viele Leerzeichen u.ä. verwenden wie man will, sinnvoll ist wohl zwischen jeder Note eines. Man kann außerdem mit `|` Taktstriche setzen. Beides ist dem Programm völlig egal, hilft aber bestimmt bei der Orientierung, wenn man die Noten schreibt.

Stille Nacht sieht dann z.B. so aus:

    g8. a16 g8 e4. | g8. a16 g8 e4. | D4 D8 h4. | C4 C8 g4. | a4 a8 C8. h16 a8 | g8. a16 g8 e4. | a4 a8 C8. h16 a8 | g8. a16 g8 e4. | D4 D8 F8. D16 h8 | C4. E4. | C8 g8 e8 g8 f8 d8 | c2.

Den Text einfach in das Feld auf der Seite einfügen und Hinzufügen klicken. Wenn man die erste Stimme hinzugefügt hat, kann man auch eine zweite hinzufügen, indem man einfach den Notentext für die zweite ebenfalls in das Textfeld kopiert und dann nochmal auf Hinzufügen klickt. Eine dritte geht nicht.

**Frohes Musizieren!**

----

This tool can quasi-automatically conduct a (bottle) orchestra.

Scores with music notes can be added dynamically. Input a simple text (without linebreaks!) in which the notes are represented by letters - so far `AHcdefgahCDEFG` are supported (note the tool uses the German term H for what is known as the B in English), where the lower case letters are the "standard octave" from the center C. Directly after the letter follows a number (1, 2, 4, 8, or 16) which encodes the length (full, half, quart etc.) of the note. With a directly following `.` one can make the note dotted. Specifying a `3` for the length treats the note as an eighth note which is part of a syncope.

One can use pauses by writing a `p` or a `-` as the note's letter and adding a length as one would do with notes.

Inbetween one can use as much whitespace etc. as they please, it's probably useful to put a space after each note. Also, bar lines can be added with the `|`. The tool doesnt care about either, but they probably help orientating when writing down scores.

For example, Silent Night looks like this:

    g8. a16 g8 e4. | g8. a16 g8 e4. | D4 D8 h4. | C4 C8 g4. | a4 a8 C8. h16 a8 | g8. a16 g8 e4. | a4 a8 C8. h16 a8 | g8. a16 g8 e4. | D4 D8 F8. D16 h8 | C4. E4. | C8 g8 e8 g8 f8 d8 | c2.

Simply copy this text into the input field on the webpage and click Add. After inserting the first voice, one can add a second by simply copying that second voice's score text into the box and hitting Add again. A third is not supported.

**Happy playing!**

----

"Made with ❤️ for the geofs Flaschenblasorchester in der Adventszeit anno domini 2016."
