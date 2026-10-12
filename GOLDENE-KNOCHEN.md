# Goldene Knochen und Hundestrategie ab Level 4

In jeder Welt werden ab Level 4 standardmäßig **fünf vorhandene braune Knochen durch goldene Knochen ersetzt**. Die Gesamtzahl bleibt gleich. Die goldenen Knochen werden auf erreichbare Knochenstellen verteilt und sind durch ihre goldene Farbe und einen kleinen Glanz erkennbar.

## Zwei Möglichkeiten, dich zu schützen

- **Goldener Knochen:** Ein aktiver Hund macht vier Sekunden **PLATZ**. Er bleibt stehen, verfolgt Pac Cat nicht und kann währenddessen nicht beißen. Liegepose, PLATZ-Anzeige, Restzeit und ein zuordenbarer Testton zeigen den Zustand.
- **P-Kraft:** Ab Level 4 schützt P vor Hundebissen. Der Hund bleibt im Spiel; es gibt keinen Hundesieg und keinen 75-Punkte-Bonus. Sobald P endet, kann er wieder verletzen. Gegen Geister funktioniert P weiterhin wie bisher.

**Level 3 bleibt unverändert:** Dort gibt es noch keine goldenen Knochen; P kann den Hund besiegen und gibt 75 Punkte. In Level 1 und 2 erscheint der Hund standardmäßig weiterhin nicht.

Goldene Knochen sind beim Einsammeln harmlos. Ist kein Hund aktiv, werden sie normal eingesammelt, ohne einen Hund zu erzeugen oder einen Befehl für später zu speichern. Knochenpunkte richten sich weiterhin nach der bestehenden Knochenregel: ohne P kein Zusatzbonus, mit P die bisherigen 50 Punkte.

## Zeitregeln

Der erste Hund erscheint nach ungefähr acht Sekunden aktiver Spielzeit. Sein Auftritt dauert weiterhin höchstens 15 Sekunden, einschließlich der letzten drei Sekunden ungefährlichen Rückzugs. Danach folgen 60 Sekunden Pause.

Die Besuchszeit läuft während PLATZ weiter. Rückzug ab Sekunde 12 und das Zeitlimit bei 15 Sekunden haben Vorrang; ein spät gesammelter Knochen verlängert den Auftritt nicht. Ein weiterer goldener Knochen kann PLATZ erneut auf bis zu vier Sekunden setzen. Bereits zurückziehende Hunde werden nicht angehalten.

## Im vorhandenen Baukasten

1. Unter **Levelprojekte** ein vorhandenes `.pclevel` öffnen oder ein neues Projekt anlegen.
2. Einen Zielplatz ab Level 4 auswählen.
3. **Goldene Knochen platzieren / verwalten** öffnen.
4. **Automatisch ab Level 4** mit vier oder fünf Knochen, **Keine goldenen Knochen** oder **Eigene Positionen ab Level 4** wählen.
5. Für eigene Positionen vorhandene braune Knochen auf der Vorschau anklicken. Erneuter Klick macht die Stelle wieder braun. Empfohlen sind vier bis fünf verteilte Orte; maximal fünf sichere Stellen sind auswählbar.
6. **Ins Levelprojekt übernehmen**, danach **Projekt speichern**.
7. **Am Kampagnenplatz testweise spielen**. Für das normale Weltmenü anschließend **In Spielwelt übernehmen** und eine Spielerfassung neu exportieren.

Wegeplan, übrige Projektabschnitte, Hundezuteilung und Audio bleiben erhalten. Die Knochenauswahl wird im Projekt gespeichert und beim Export mitgegeben. Nach einer Änderung des Labyrinths müssen nicht mehr passende eigene Knochenstellen neu gewählt werden; ein ungültiger Export wird mit einer Meldung verhindert.

In sehr kleinen eigenen Labyrinthen können insgesamt weniger als fünf Knochen vorhanden sein. Die Automatik verwendet dann die verfügbaren erreichbaren Knochen und erhöht deren Gesamtzahl nicht. Unter Level 4 bleibt eine gespeicherte Goldauswahl im Spiel inaktiv.

Der bisherige Levelabschluss über die Pflichtpunkte und den Katzenbaum bleibt bestehen; goldene Knochen sind keine neue zusätzliche Abschlussbedingung.

## Audio

Im bestehenden **Audio-Baukasten → Spielgeräusche** gibt es zusätzlich:

- **Pac Cat sammelt einen goldenen Knochen**
- **Hund macht PLATZ**

Die bisherigen Zuordnungen bleiben erhalten. Die zwei neuen Ereignisse erhalten zunächst kurze Testtöne. Du kannst wie bisher WAV/MP3, Ausschnitt und Lautstärke wählen. Neue Spieler-EXEs enthalten die benötigten Audiodaten; ältere EXEs werden nicht automatisch verändert.

## Geprüft und noch offen

Geprüft wurden die Standards aller 60 Levelplätze, Gesamtzahl und goldene Untermenge, Einsammeln mit/ohne aktiven Hund, harmlose Goldknochen, vier Sekunden Stillstand, Wiederaufnahme, Rückzug/15-Sekunden-Limit/60-Sekunden-Pause, P-Ablauf und erneuter Biss, Level-3-Hundesieg und Geister-P-Sieg. Außerdem Editor-Mausauswahl, Projekt-Speichern/Neuladen, fremde Projektabschnitte, eigenes Labyrinth, Levelabschluss, Audioerhalt, normale Levelauswahl und unabhängiger Spielerexport.

Nicht vollständig geprüft: fremde Windows-PCs, Langzeit-Spielrunden in jeder Welt und das subjektive Schwierigkeitsgefühl. Die Geräusche bleiben vorläufige Testtöne. Die Comic-Hundegrafik und ihre Bewegungsdarstellung beschreibt [HUND-GRAFIK.md](HUND-GRAFIK.md). Bitte die Strategie selbst praktisch spielen und ihre Fairness sowie die Lautstärken beurteilen.
