# STALKER Zone (NeoForge 1.21.1)

First step: one anomaly block (Electro Anomaly) that hurts everything standing inside it.

## Start it
1. Install JDK 21 (e.g. Temurin 21) and an IDE (IntelliJ IDEA Community is easiest).
2. Open this folder as a Gradle project in IntelliJ and wait for the sync to finish (first time takes a few minutes).
3. Run the `runClient` Gradle task (Gradle panel -> Tasks -> modding -> runClient).
4. In-game: Creative mode -> tab "STALKER Zone" -> place the Electro Anomaly and walk into it.

## Build a jar for your normal Minecraft
Run `gradlew build` -> jar is in `build/libs/`. Put it in your `mods` folder (Minecraft 1.21.1 + NeoForge 21.1.x).

## Files
- `StalkerZone.java`: registers block, item and creative tab
- `AnomalyBlock.java`: the damage and spark particles
- `src/main/resources/...`: textures, models, language files, loot table

## If something does not compile
Copy the exact error message and send it to Claude together with the file name.

## Next ideas
Radiation (damage over time + Geiger sound), more anomaly types, artifacts as drops, an emission event.
