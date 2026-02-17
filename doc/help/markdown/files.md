<!-- SPDX-FileCopyrightText: 2026 Graeme Gott <graeme@gottcode.org> -->

# Files

> [!WARNING]
> The files used by **Tanglet** are not intended for manual editing. Do not do
> so unless you know exactly what you are doing.

## User configuration file

The user configuration is located in the *~/.config/Gottcode/Tanglet.conf*
file. The folder *~/.config/Gottcode/* is shared with other
[Gottcode](https://gottcode.org/) games, therefore, make sure you don't mix
anything up. As mentioned above, the file is not intended to be edited
manually. However, if you actually want to edit it, your game scores could be
lost. Be aware of this.

## Saved Games

A game you save using **Game** ➠ **Save…** is a text file, compressed with
`gzip`. If you are curious enough, you can unpack such a file using the
following command:

```console
$ rename tanglet gz savedgame.tanglet && gunzip savedgame.gz
```

<a name="file_structure"></a>
### File structure

The first four lines after `[Game]` mirror the
[settings of the board language](./configuration.md).

Seven more lines follow:

* `Letters` – The letters shown in the board.

<!-- Really…? Or the application language settings? -->
* `Locale` – The configured Locale for the board.

* `Minimum` – Minimum word length.

* `Size` – Size of the board.

* `TimerMode` – Timer mode, depending on the initially chosen game.

<!-- What is "Version" here? -->
* `Version` – TBD.

* `Words` – The used wordlist

We don't recommend to change anything here. It can easily happen that the file
becomes unusable.

[Back to the index page](./index.md)
