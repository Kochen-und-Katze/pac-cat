# Pac Cat

Pac Cat ist ein Windows-Labyrinthspiel mit Katzenfigur, Hundegeistern, Sammelgegenständen, verschiedenen Spielwelten und einem getrennten Entwicklerbaukasten. Diese Ausgabe ist eine **Testversion**, keine fertige Vollversion. Viele Levelplätze verwenden noch vorhandene Labyrinthvorlagen.

## Downloads: v0.3.0-preview

| Ich möchte … | Download | Start |
|---|---|---|
| Nur spielen | [Spielerpaket als ZIP](https://github.com/Kochen-und-Katze/pac-cat/releases/download/v0.3.0-preview/Pac-Cat-Windows-v0.3.0-preview.zip) | Entpacken, `Pac-Cat.exe` doppelklicken |
| Direkt die einzelne Spiel-EXE | [Pac-Cat.exe](https://github.com/Kochen-und-Katze/pac-cat/releases/download/v0.3.0-preview/Pac-Cat.exe) | Doppelklicken |
| Eigene Levels bauen und testen | [Entwicklerbaukasten als ZIP](https://github.com/Kochen-und-Katze/pac-cat/releases/download/v0.3.0-preview/Pac-Cat-Baukasten-Windows-v0.3.0-preview.zip) | Komplett entpacken, `bin/Pac-Cat-Baukasten.exe` starten |
| Downloads prüfen | [SHA256SUMS.txt](https://github.com/Kochen-und-Katze/pac-cat/releases/download/v0.3.0-preview/SHA256SUMS.txt) | SHA-256 mit heruntergeladener Datei vergleichen |

[Neue Veröffentlichung](https://github.com/Kochen-und-Katze/pac-cat/releases/tag/v0.3.0-preview) · [Bisherige Ausgabe v0.1.0-preview](https://github.com/Kochen-und-Katze/pac-cat/releases/tag/v0.1.0-preview)

Der Hund ist in der neuen Spielerfassung eingebaut und erscheint standardmäßig in jeder Welt ab Level 3. Kein Zusatzmodul muss installiert werden. Die alte Veröffentlichung erhält dadurch kein Update.

## Anleitungen

- [Spielen und Hund ausprobieren](ANLEITUNG.md)
- [Baukasten, eigene Level und Spielausgabe](BAUKASTEN.md)
- [Geräusche auswählen und zuordnen](AUDIO.md)
- [Änderungen und Prüfumfang](AENDERUNGEN.md)
- [Quellen und Nutzungsrechte](QUELLEN.md)

Windows mit .NET Framework 4.5 oder neuer; das Framework ist auf vielen aktuellen Windows-Systemen bereits vorhanden. Kein GitHub-Konto und keine Programmierkenntnisse nötig. Die EXEs sind nicht digital signiert; Windows kann beim Start eine Warnung anzeigen.

Der Baukasten enthält die bestehenden Werkzeuge und den integrierten Hund. Ein allgemeiner Import beliebiger Gegnermodule und automatische Updates gehören nicht zu dieser Ausgabe. Dieses Repository enthält fertige Downloads und Dokumentation; der vollständige Spielquellcode wird mit dieser Veröffentlichung nicht bereitgestellt.

Neu: gemeinsame Audioverwaltung im vorhandenen Baukasten. Die Downloads enthalten vorläufige Testtöne für zwölf Ereignisse; eigene Klänge können zugeordnet und in Spieler-EXEs exportiert werden. Die bisherigen Ausgaben [v0.2.0-preview](https://github.com/Kochen-und-Katze/pac-cat/releases/tag/v0.2.0-preview) und v0.1.0-preview bleiben verfügbar.