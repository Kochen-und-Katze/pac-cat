# Spielgeräusche im vorhandenen Audio-Baukasten

Der Entwicklerbaukasten enthält jetzt eine gemeinsame Geräuschverwaltung für Spielwelten, eigene Levelprojekttests und exportierte Spielerfassungen. Der Hund und andere Gegner verwenden denselben Ereignis- und Wiedergabeweg.

## Ausprobieren

1. Den Baukasten vollständig entpacken und `bin/Pac-Cat-Baukasten.exe` starten.
2. **Baukästen → Audio-Baukasten** öffnen.
3. Unter **Spielgeräusche** ein Ereignis auswählen und **Zuordnung anhören** anklicken.
4. Für eigene Klänge **Audiodatei öffnen** (WAV/MP3) oder **Projekt öffnen** verwenden.
5. Den Klang abspielen, Anfang/Ende markieren und Lautstärke einstellen.
6. **Geladenen Ausschnitt diesem Ereignis zuordnen** wählen. Falls nötig zuerst einen Namen für das Audioprojekt angeben. Die Zuordnung wird sofort gespeichert; benötigte Audiodaten werden in den eigenen Arbeitsordner kopiert.
7. Über **Zuordnung bearbeiten** den bisherigen Ausschnitt laden, ändern und erneut zuordnen. **Zuordnung entfernen** entfernt die zusätzliche Regel für dieses Ereignis.

Ein neuer Baukasten und die Standard-Spielerfassung enthalten vierzehn kurze, unterscheidbare **vorläufige Testtöne**. Diese sind noch keine endgültigen Bell- oder Spielgeräusche. **Testtöne einrichten** ersetzt nach Rückfrage die vierzehn Zuordnungen durch diese Platzhalter.

## Verfügbare Ereignisse

| Ereignis | Wann der Klang ausgelöst wird |
|---|---|
| Punkte | Pac Cat sammelt einen kleinen Punkt |
| Futter | Ein Futternapf wird eingesammelt |
| P-Kraft, Medkit, Knochen | Der betreffende Gegenstand wird eingesammelt |
| Geistkontakt ohne P | Pac Cat berührt einen Geist; auch Abwehr am Katzenbaum zählt als Kontakt |
| Geist mit P besiegt | Ein Geist wird tatsächlich durch P-Kraft besiegt |
| Hund erscheint | Ein neuer Hundeauftritt beginnt |
| Hund bellt | Das Hundemodul meldet Bellen |
| Hund versucht anzugreifen | Ein Kontaktangriff wird versucht |
| Hund beißt | Der Angriff zieht tatsächlich Gesundheit oder ein Leben ab |
| Hund mit P besiegt | Bis Level 3: Hund durch P-Kraft besiegt; 75 Punkte |
| Goldener Knochen | Gold wird harmlos eingesammelt |
| Hund macht PLATZ | Ein aktiver Hund beginnt seine Stillhaltephase |

Angriff und Biss sind getrennt. Schutz kann den Biss verhindern, während der Angriffston dennoch gespielt wird. Ein P-Sieg löst keinen Angriff oder Biss aus. Schnelle Wiederholungen desselben Klangereignisses werden begrenzt; unterschiedliche Ereignisse können gleichzeitig erklingen.

## Speicherung und Spielerexport

Die Zuordnungen gelten gemeinsam für alle Welten und Level. Eine gesonderte Zuordnung pro Level gehört nicht zu diesem Schritt. Die bestehende Levelmusik und der optionale Start-Audiotest bleiben getrennt erhalten.

Zuordnungen und kopierte Geräusche liegen unter `Arbeit`. Diesen Ordner zusammen sichern; die neuen Verweise auf verwaltete Geräusche sind relativ und können mitkopiert werden. Einzelne `.pcaudio`-Dateien benötigen ihre jeweils danebenliegende Audiodatei.

Nach Änderungen einen Level neu starten oder eine neue Spieler-EXE exportieren. Der Export enthält die Audio-Dateien, Ausschnitte und Lautstärken. Empfänger benötigen nur die EXE. Bereits erzeugte oder weitergegebene EXEs ändern sich nicht automatisch.

Geräuschdateien sind auf 20 MB je Zuordnung begrenzt. Nur Inhalte verwenden, deren Nutzung und Weitergabe erlaubt sind. Fremde Geräuschpakete wurden dieser Veröffentlichung nicht hinzugefügt.

## Prüfumfang

Technisch geprüft wurden Vorschau und fortschreitende Windows-Abspielposition, Speichern/Neuladen, Ausschnitt/Lautstärke, Kopieren des Arbeitsordners, tatsächliche Sammel-/Geist-/Hundeereignisse, Schutz und P-Sieg, eigene Levelprojekttests und eigenständige Spielerexporte. Bestehende Audio- und Hundetests bestehen weiterhin.

Bitte selbst prüfen: Klangqualität, gewünschte Lautstärken und mögliche störende Überlagerungen. Es gab keinen unabhängigen Hörtest sämtlicher Situationen und keinen Test auf einem fremden Windows-PC.

Ab Level 4 besiegt P den Hund nicht mehr. Gold- und PLATZ-Ereignisse werden in der bestehenden Verwaltung zugeordnet; vorhandene Zuordnungen werden beim ersten Start erhalten und nur die zwei fehlenden neuen Einträge ergänzt.