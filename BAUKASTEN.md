# Pac Cat Entwicklerbaukasten

## Start und Datensicherung

Lade das Baukasten-ZIP herunter und entpacke **den gesamten Inhalt** in einen beschreibbaren Ordner, beispielsweise in deine Dokumente. Nicht innerhalb der ZIP-Datei starten. Starte `bin/Pac-Cat-Baukasten.exe`.

Der Baukasten verwendet die bestehende Pac-Cat-Plattform mit ihrer Baukastenübersicht, Levelprojekten und Spielausgabe. Die Bedienung entspricht der lokal getesteten Integration. Er ist nicht an ein bestimmtes Windows-Konto gebunden und erfordert keine Administratorrechte.

Das Profil, Kampagnenzuordnungen und lokale Spielausgaben liegen neben `bin` im Ordner `Arbeit`, der beim Start angelegt wird. Projektdateien kannst du über den Speicherdialog an einem eigenen Ort ablegen. Sichere deshalb sowohl `Arbeit` als auch extern gespeicherte Projekte. Das Löschen einer frisch entpackten Baukastenkopie verändert andere Spielausgaben nicht; vorher eigene Daten sichern.

## Hund für vorhandene Levelplätze auswählen

1. **Baukästen → Spielgegner / Hund** öffnen.
2. Welt und Hund wählen.
3. **Standard ab Level 3** verwenden oder **Alle aus** und einzelne Level, beispielsweise 4, 5 und 6, anhaken.
4. **Auswahl speichern**. Danach den betreffenden Level neu starten.

Diese Auswahl gilt pro Welt. Eigene Projekte mit ausdrücklicher EIN-/AUS-Regel haben Vorrang vor den Welthäkchen.

## Eigene Levels mit Hund

1. Unter **Levelprojekte** ein neues Projekt anlegen oder ein `.pclevel` öffnen.
2. Projektname, Welt und Levelnummer festlegen. Die vorhandenen Wege-, Wand-, Weihnachts- und Audiowerkzeuge bleiben verfügbar.
3. Im Abschnitt **Spielgegner** den Hund einstellen:
   - **Wie Levelauswahl**: übernimmt die Weltregel; ohne Sonderauswahl Hund ab Level 3.
   - **In diesem Level EIN**: Hund in diesem Projekt, auch vor Level 3.
   - **In diesem Level AUS**: Hund in diesem Projekt ausgeschaltet.
4. Im jeweiligen Werkzeug Änderungen ins Projekt übernehmen und danach auf der Projektseite **Projekt speichern**.
5. **Am Kampagnenplatz testweise spielen** wählen. Nach ungefähr acht Sekunden sollte der Hund erscheinen, wenn er für das Projekt eingeschaltet ist.
6. Mit **In Spielwelt übernehmen** den gespeicherten Entwurf dem gewählten Welt-/Levelplatz zuordnen. Das ist eine lokale Zuordnung, kein Internet-Upload.

Ein freies Projekt ohne Zielplatz wird beim Test als Level 1 behandelt. Dort den Hund ausdrücklich einschalten oder zuerst einen Zielplatz festlegen. Unter `Beispiele` liegt ein kleines Gartenwege-Level-4-Projekt mit eingeschaltetem Hund.

## Eigenständige Spielerfassung exportieren

1. Projekte speichern und die gewünschten Projekte in die Spielwelt übernehmen.
2. Links **Spielausgabe** öffnen.
3. **Spielausgabe im Arbeitsordner erstellen** oder **Spiel-EXE für USB / Weitergabe speichern** wählen.
4. Eine bereits laufende Ziel-EXE vorher schließen. Der Export darf den laufenden Baukasten nicht überschreiben.
5. Die erzeugte EXE getrennt starten und die betreffenden Level auswählen.

Der Export enthält die wirksamen Hunderegeln, die übernommenen Labyrinthe und benötigte Grafik-/Audiodaten. Spieler brauchen nur diese EXE, keine Baukasteninstallation und kein Programmieren. Autorenfelder, Notizen und ursprüngliche Projektpfade werden nicht als Laufzeitprojekt mitgegeben.

## Grenzen und Rechte

Die vorhandenen Werkzeuge sind weiterhin teilweise Entwicklungswerkzeuge: Weihnachtsdekoration ist nicht automatisch eine neue Spielmechanik, und nicht jede vorbereitete Projekteigenschaft wirkt bereits im Spiel. Die beiliegende Bedienungsanleitung erklärt die bestehenden Werkzeuge ausführlicher.

Das vorhandene Audiowerkzeug verwaltet jetzt gemeinsame Spielereignisse; siehe AUDIO.md. Der Hund wird mit dem vorhandenen eigenständigen Modul und der neuen Goldstrategie betrieben. Weitere Gegner können später denselben Auswahl-, Projekt- und Exportweg verwenden; beliebige externe DLLs lassen sich hier noch nicht als neue Gegner installieren.

Verwende für eigene Audio-/Grafikinhalte nur Inhalte, die du weitergeben darfst. Für Spielcode und Spielgrafiken wird keine allgemeine Open-Source-Lizenz vergeben. Siehe `QUELLEN.md`.

## Gemeinsame Spielgeräusche
Baukästen → Audio-Baukasten → Spielgeräusche. Ereignis auswählen, Zuordnung anhören oder eigenen Ausschnitt zuordnen. Beim ersten Start werden vierzehn vorläufige Testtöne vorbereitet. Bestehende Levelmusik bleibt getrennt. Details: AUDIO.md.
## Goldene Knochen ab Level 4
Im Levelprojekt Goldene Knochen platzieren / verwalten wählen. Vier/fünf automatisch oder sichere Knochenstellen selbst auswählen, ins Projekt übernehmen, speichern und testen. Ab Level 4 bleibt der Hund unter P erhalten; Gold befiehlt PLATZ. Export übernimmt die Knochenauswahl. Details: GOLDENE-KNOCHEN.md.