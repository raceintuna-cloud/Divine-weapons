# Divine Weapons — Fabric 1.21.11

A Fabric mod project for Minecraft Java 1.21.11. It adds three altar blocks and three ability weapons.

## Important multiplayer note
Because this mod registers new items and blocks, **every player who joins the modded server must also install the same mod on their client**. This is not a vanilla-client/server-only plugin.

## Altar crafting
Place the matching altar block, then right-click it while holding the listed offering:
- **Void Altar + Nether Star** → Voidbreaker
- **Storm Altar + Trident** → Stormpiercer
- **Soul Altar + Netherite Sword** → Soulreaper

The offering is consumed in Survival. Creative players keep the offering.

## Weapon abilities
Right-click while holding the weapon in your main hand:
- **Voidbreaker**: large void shockwave, area damage and knockback. 3.5-second cooldown.
- **Stormpiercer**: forward lightning dash and close-range shockwave. 2.75-second cooldown.
- **Soulreaper**: soul burst plus temporary regeneration and absorption. 4.5-second cooldown.

These are custom ability items rather than vanilla mace/spear/sword combat items in this first build.

## Build
Requires JDK 21 and internet access for Gradle to download Minecraft/Fabric dependencies.

On Windows:
```bat
gradlew.bat build
```
On Linux/macOS:
```sh
./gradlew build
```

The built mod JAR will be in `build/libs/`.

## Notes
- Source project is provided; it has **not been compiled or tested in this environment**.
- The Gradle wrapper is not included. Generate one with `gradle wrapper` on a machine with Gradle installed, or open the folder in IntelliJ IDEA with the Gradle plugin.
