# Fast Shield (unfinished scaffold)

Fabric mod for Minecraft Java 1.21.11. Shield blocks after 3 ticks instead of 5.

## Get the jar
1. Create a new GitHub repo and upload everything in this folder (keep the `.github` folder).
2. Open the **Actions** tab, wait for the `build` run to finish (or click "Run workflow").
3. Open the run, download the `fastshield` artifact, unzip it.
4. Put `fastshield-0.1.0.jar` (not the `-sources` one) in your `mods` folder, with Fabric API.

## If the build fails
- "version not found": edit `gradle.properties` with the newest versions from https://fabricmc.net/develop
- Error in `FastShield.java` about `BlocksAttacksComponent`: the constructor differs in your mappings. Fix the TODO there.

## Notes
- Install on the client AND on any server you run.
- Don't use on public servers; it changes combat in your favor.
