# Der Comic-Hund in v0.5.0-preview

Der Hund erhält die Comic-Darstellung des bereitgestellten Entwurfs. Die normale Pose verwendet die freigestellte Originalzeichnung mit transparentem Hintergrund. Für das Kommando PLATZ wurde daraus mit ImageGen eine liegende Pose abgeleitet.

Beim Laufen folgt seine Blickrichtung der Bewegung; leichtes Wippen unterstützt den Bewegungseindruck. Eine vollständige Animation aus mehreren Laufbildern ist noch nicht enthalten. Während PLATZ zeigen die liegende Pose, die Anzeige und die verbleibende Zeit seinen Zustand.

## Die Spielregeln bleiben erhalten

- Standardmäßig Hund ab Level 3, erster Auftritt nach ungefähr acht Sekunden aktiver Spielzeit.
- Höchstens 15 Sekunden Anwesenheit mit ungefährlichem Rückzug in den letzten drei Sekunden; danach 60 Sekunden Pause.
- Level 3: P besiegt den Hund und gibt 75 Punkte.
- Ab Level 4: P schützt vor Hundebissen und entfernt den Hund nicht. Goldene Knochen lassen einen aktiven Hund vier Sekunden PLATZ machen.
- PLATZ verlängert die Anwesenheit nicht. Geister, Schutzmechanismen und gemeinsame Audiozuordnungen behalten ihre Regeln.

Die Grafik wird auch in Levelprojekttests und eigenständigen Spielerexporten verwendet. Im Baukasten sind dafür keine neuen Einstellungen nötig. Bereits exportierte Spieler-EXEs behalten ihren bisherigen Stand; für die Comic-Grafik eine neue Spielerfassung exportieren.

## Praktisch ausprobieren

1. Die neue Spielerfassung starten und **Gartenwege → Level 3** wählen. Nach ungefähr acht Sekunden auf Erscheinung, Blickrichtung und Bewegung des Hundes achten.
2. **Gartenwege → Level 4** starten. Einen goldenen Knochen sammeln, während der Hund verfolgt, und die liegende PLATZ-Pose sowie die Wiederaufnahme beobachten.
3. Den Hund mit P-Kraft berühren: In Level 3 verschwindet er; ab Level 4 bleibt er erhalten und zieht während P keine Gesundheit ab.
4. Im Baukasten ein eigenes Level testen und eine neue Spieler-EXE exportieren. Die Hundedarstellung soll in beiden Fassungen übereinstimmen.

Fremde Windows-PCs, Langzeittests sämtlicher Welten und das subjektive Schwierigkeitsgefühl sind weiterhin nicht vollständig geprüft. Geräusche bleiben die austauschbaren Testtöne der gemeinsamen Audioverwaltung. Herkunftsangaben: [QUELLEN.md](QUELLEN.md).
