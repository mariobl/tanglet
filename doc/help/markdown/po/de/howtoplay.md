<!-- SPDX-FileCopyrightText: 2026 Graeme Gott <graeme@gottcode.org> --> <!--
SPDX-License-Identifier: CC-BY-SA-4.0 -->

# Das Spiel spielen

## Steuerung mit Maus und Tastatur


| Action         | Using the mouse                           | Using the keyboard                            |
|----------------|-------------------------------------------|-----------------------------------------------|
| Select a word  | Click on the letters of a word.           | Type the letters of a word.                   |
| Make a guess   | Click on the last selected letter.        | Press <kbd>Enter</kbd>                        |
| Erase letters  | Click on an earlier selected letter.      | Press <kbd>Backspace</kbd>.                   |
| Clear the word | Click twice on the first selected letter. | Press <kbd>Ctrl</kbd> + <kbd>Backspace</kbd>. |

## Ein Wort aktivieren

Wenn Sie ein Wort gefunden haben, klicken Sie auf den ersten Buchstaben. Nun
sehen Sie um dieses Feld herum die Buchstaben, aus denen Sie das Wort
fortsetzen können; alle anderen Felder sind ausgegraut.
     
Während der Eingabe der Buchstaben wird das Wort oberhalb der Wortliste auf
der linken Seite angezeigt.

![Das Spielfeld mit einem aktivierten Wort](./figures/tanglet_board.png)


Sobald Sie ein Wort gefunden haben, das Ihrer Meinung nach gültig ist,
doppelklicken Sie auf den zuletzt aktivierten Buchstaben oder drücken Sie
die <kbd>Eingabetaste</kbd>. Wenn **Tanglet** das Wort akzeptiert, wird es
in der Liste **Gefunden** links neben dem Spielfeld angezeigt.

Falls Sie das Wort *wieder* (auch in einer anderen Buchstabenfolge auf dem
Spielfeld) finden, wird es in dieser Liste hervorgehoben.

Lässt sich das Wort durch einen oder mehrere Buchstaben zu einem neuen Wort
erweitern, klicken Sie darauf, um es erneut auf dem Spielfeld
anzuzeigen. Sie können dann auf die weißen Felder klicken, um weitere
Buchstaben hinzuzufügen und so ein neues Wort zu bilden. Beachten Sie: Sie
erhalten Punkte für das *gesamte* neue Wort, nicht nur für die hinzugefügten
Buchstaben!

Wenn Sie Buchstaben über die Tastatur aktivieren oder versehentlich eine
Taste mit einem Buchstaben drücken, der vom Ende des aktuellen Wortes aus
nicht erreichbar ist oder gar nicht auf dem Spielfeld existiert, wird das
gesamte Spielfeld ausgegraut und das Feld über der Wortliste mit rotem
Hintergrund angezeigt.

<!-- I remember, there was such an icon in previous versions... -->
<!-- When you hover the mouse pointer over one of the accepted words in
       the list, a clickable book icon will be displayed, which leads you to
       the appropriate entry in Wiktionary. -->
When the game ends and if you have achieved a place among the top ten in the
chosen game mode, the **High Scores** list appears. Under **Name**, your name
(taken from your user account) is already entered, but highlighted. If you like
to use a different name, or anyone else has played the game, you can change the
name directly, or leave it as-is. In either case, finally click on **Close**.

Sie können das Spiel jederzeit schließen. Wenn Sie das Spiel schließen,
bevor es beendet wurde, wird beim nächsten Start von **Tanglet** dasselbe
Spiel mit demselben Spielstand erneut geöffnet.

## Übersehene Wörter anzeigen

Die Wortliste hat einen Reiter **Übersehen**, der während des Spiels inaktiv
ist. Nach Spielende können Sie darauf klicken, um die Wörter anzuzeigen, die
Sie nicht gefunden haben.

## Spielstände anzeigen

Wählen Sie **Spiel** ➠ **Highscores**, um die Highscore-Liste zu öffnen. Um
zwischen den verschiedenen Spielmodi zu wechseln, verwenden Sie die
vertikale Reiterleiste links.

## Ein Spiel exportieren oder importieren

Um ein Spiel zu exportieren, wählen Sie **Spiel** ➠ **Exportieren…**. Ein
Dialog zum Speichern der Datei öffnet sich. Hier können Sie einen Dateinamen
eingeben und den Speicherort festlegen. Beachten Sie, dass die gespeicherte
Datei nur die Spieleigenschaften selbst enthält, nicht Ihre gefundenen
Wörter oder erzielten Punkte. Siehe auch [die Erklärung der
Dateistruktur](./files.md#file_structure).

Umgekehrt können Sie **Spiel** ➠ **Importieren…** wählen. Es öffnet sich ein
Dateiauswahldialog, in dem Sie die gewünschte Datei auswählen und öffnen
können.

[Zurück zur Indexseite](./index.md)
