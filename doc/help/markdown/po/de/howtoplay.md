<!-- SPDX-FileCopyrightText: 2026 Graeme Gott <graeme@gottcode.org> -->

# Das Spiel spielen

## Steuerung mit Maus und Tastatur


| Aktion             | Mit der Maus                                         | Mit der Tastatur                                  |
|--------------------|------------------------------------------------------|---------------------------------------------------|
| Wort wählen        | Auf die Buchstaben eines Worts klicken.              | Buchstaben eines Wortes eingeben.                 |
| Versuchen          | Auf den zuletzt gewählten Buchstaben klicken.        | <kbd>Eingabetaste</kbd> drücken.                  |
| Buchstaben löschen | Auf den zuvor gewählten Buchstaben klicken.          | <kbd>Rückschritt</kbd> drücken.                   |
| Wort löschen       | Doppelt auf den zuerst gewählten Buchstaben klicken. | <kbd>Strg</kbd> + <kbd>Rückschritt</kbd> drücken. |

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

Wenn das Spiel beendet ist und Sie in dem gewählten Spielmodus unter den Top Ten waren, erscheint die **Highscores**-Liste. Unter **Name** ist Ihr Name (aus Ihrem Benutzerkonto) bereits eingetragen und hervorgehoben. Falls Sie einen anderen Namen verwenden möchten oder jemand anderes das Spiel gespielt hat, können Sie den Namen direkt ändern oder ihn unverändert lassen. Klicken Sie anschließend in jedem Fall auf **Schließen**.

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
