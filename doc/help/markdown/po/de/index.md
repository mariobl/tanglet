<!-- SPDX-FileCopyrightText: 2026 Graeme Gott <graeme@gottcode.org> -->

# Benutzerhandbuch für Tanglet

**Tanglet** ist ein Wortsuchspiel für Einzelspieler, das auf [Boggle](https://de.wikipedia.org/wiki/Boggle) basiert. Ziel des Spiels ist es, innerhalb der vorgegebenen Zeit so viele Wörter wie möglich aufzulisten. Es gibt verschiedene Zeitmodi, die festlegen, wie viel Zeit man zu Beginn hat und ob man zusätzliche Zeit erhält, wenn man ein Wort findet.

Buchstaben können horizontal, vertikal oder diagonal in beliebiger Richtung
zu einem Wort verbunden werden, solange sie auf dem Spielfeld nebeneinander
liegen. Es dürfen jedoch keine Buchstabenfelder desselben Buchstabens in
einem Wort wiederholt werden. Jedes Wort muss auf einem normalen Spielfeld
mindestens drei und auf einem großen Spielbrett mindestens vier Buchstaben
haben.

## Das Spiel starten

You can start the game using the application menu of your desktop
environment.  Open the application menu and choose **Games** ➠ **Tanglet**
or open a quick start prompt using <kbd>Alt</kbd> + <kbd>F2</kbd> and start
typing `tanglet`, then click on the application name found.

When **Tanglet** starts, two board sizes are available, 4x4 and 5x5. Click
on one of them to apply. In the drop-down list right to **Amount Of Words**,
you can choose between more or less words contained in the board. Try out
how it results in the created word counts in the board, in many cases, with
a 5x5 board, you get more than 1000 contained words. The other drop-down
list **Minimum Word Length** lets you choose between acceptable character
counts.  The minimally configurable word length depends on the board let's
say 5, then words with 4 letters, which actually exists, won't be accepted
by **Tanglet**.

Anschließend können Sie zwischen verschiedenen Spielmodi wählen:

![Spielmodi](./figures/tanglet_change_modes.png)

Die folgenden Modi sind verfügbar:

* **Festanzahl** – Spiel endet nach 30 Versuchen.
* **Klassisch** – Zählt von 3 Minuten abwärts.
* **Disziplin** – Zählt von 30 Sekunden abwärts und erhöht bei richtigen
  Versuchen.
* **Zurücksetzen** – Zählt von 30 Sekunden abwärts und setzt bei richtigen
  Versuchen zurück.
* **Ausdauer** – Zählt von 45 Sekunden abwärts und pausiert bei richtigen
  Versuchen.
* **Verlieren** – Spiel endet nach 3 falschen Versuchen.
* **Tanglet** – Zählt von 30 Sekunden abwärts und erhöht bei richtigen
  Versuchen.
* **Unbegrenzt** – Spiel endet, wenn alle Wörter gefunden sind.

[Das Spiel spielen](./howtoplay.md)

[Konfiguration](./configuration.md)

[Übersicht über die Menüleiste](./menubar.md)

[Dateien](./files.md)

[Mitwirken](./contributing.md)

[Danksagungen und Lizenz](./credits.md)
