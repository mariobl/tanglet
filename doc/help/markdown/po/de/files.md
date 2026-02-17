<!-- SPDX-FileCopyrightText: 2026 Graeme Gott <graeme@gottcode.org> -->

# Dateien

> [!WARNING] > Die von **Tanglet** verwendeten Dateien sind nicht für die
manuelle Bearbeitung vorgesehen. > Bearbeiten Sie sie nicht manuell, es sei
denn, Sie wissen genau, was Sie tun.

## Benutzerkonfigurationsdatei

Die Benutzerkonfiguration befindet sich in der Datei
*~/.config/Gottcode/Tanglet.conf*. Der Ordner *~/.config/Gottcode/* wird
auch von anderen [Gottcode](https://gottcode.org/)-Spielen verwendet. Achten
Sie daher darauf, nichts zu verwechseln. Wie bereits erwähnt, ist die Datei
nicht für die manuelle Bearbeitung vorgesehen. Sollten Sie sie dennoch
bearbeiten, könnten Ihre Spielstände verloren gehen. Beachten Sie dies
bitte.

## Gespeicherte Spiele

Ein Spiel, das Sie mit **Spiel** ➠ **Speichern…** speichern, ist eine mit
`gzip` komprimierte Textdatei. Wenn Sie neugierig genug sind, können Sie
eine solche Datei mit folgendem Befehl entpacken:

```console $ rename tanglet gz savedgame.tanglet && gunzip savedgame.gz ```

### <a name="file_structure"></a>Dateistruktur

Die ersten vier Zeilen nach `[Game]` spiegeln die [Einstellungen der
Spielfeldsprache](./configuration.md) wider.

Sieben weitere Zeilen folgen:

* `Letters` – Die auf dem Spielfeld angezeigten Buchstaben.

* `Locale` – Die für das Spielfeld konfigurierte Locale.

* `Minimum` – Minimale Wortlänge.

* `Size` – Größe des Spielfelds.

* `TimerMode` – Timer-Modus, abhängig vom gewählten Spiel.

* `Version` – TBD.

* `Words` – Die verwendete Wortliste.

Wir raten davon ab, hier etwas zu ändern. Es kann leicht passieren, dass die
Datei unbrauchbar wird.

[Zurück zur Indexseite](./index.md)
