# STALKER-Zone
Gesamtüberblick über das, was wir für deine S.T.A.L.K.E.R.-Mod bisher aufgebaut haben:

1. Dimension & Generation
Dimension (stalker_zone:the_zone): Eigene S.T.A.L.K.E.R.-Dimension ist registriert, speichert mit der Welt und lässt sich per Teleport betreten.

Prozeduraler ZoneSpawner: Läuft beim Laden neuer Chunks auf dem Server und platziert mit definierter Chance dynamisch Zonen-Ereignisse und Anomalien.

2. Anomalien & Artefakte
Flexibles AnomalyBlock-System: Einziges Block-System für alle Zonen-Anomalien inklusive optischer Partikel (Client-Side), Schadenseffekte und automatischem Artefakt-Spawning per Random Ticks.

4 Haupt-Anomalien:

Electro: Stromschaden & spuckt Moonlight aus.

Fire: Hitzeschaden/Feuer & spuckt Fireball aus.

Gravity: Schleudert den Spieler hoch & spuckt Gravi aus.

Acid: Säureschaden + Gift & spuckt Slime aus.

3. S.T.A.L.K.E.R. Überlebenssystem (Player Stats)
Custom Stats Framework: Verfolgt Strahlung (mSv), Blutung (Stufe 0–3), Ausdauer (Stamina) und Durst.

NeoForge Attachments (ModAttachments): Binde die Zonen-Stats direkt an den Spieler inkl. NBT-Speicherung und Erhalt beim Tod (copyOnDeath).

Survival Game Loop (StalkerSurvivalEvents): Server-Tick verarbeitet sekündlich Blutungsverlust, Strahlungsvergiftung sowie passiven Strahlungsabbau.

4. Items & Ausrüstung
Radioaktiver Müll (radioactive_waste): Block-Gefahrenquelle für die Umgebung.

Geigerzähler (geiger_counter): Werkzeug zur Strahlungsmessung.

Artefakte & Creative Tab: Eigener Mod-Tab im Kreativinventar für bequemen Zugriff auf alle Zonen-Objekte.
