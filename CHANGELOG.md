## Shod's Create and TacZ Bridge 1.1 (unreleased)

<!-- Running log: every change that goes into the 1.1 jar is added here the same day.
     On release: drop "(unreleased)", copy to docs/changelog_1.1.md and write docs/changelog_1.1_short.md (CurseForge). -->

### New
- **Four ammo icon styles**, each a built-in resource pack you can pick in Options → Resource Packs: single round with the caliber name (on by default), single round without it ("Clean"), **grouped rounds like default TacZ** with the caliber name ("Grouped"), and grouped without it ("Grouped Clean"). Every pack is complete (icons and 3D ammo boxes); if more than one is on, the top one wins.
- The same four styles are also available as standalone resource packs for players who use only TacZ.
- **.300 Blackout**, the new round in TacZ 1.2.0: Primed Brass Casing + Black Dye, pressed on a basin, just like the 5.56 with its Green Dye. Its icon is the 5.56 case with a black tip, in all four styles.

### Changed
- Shorter caliber names on the icons, so the tip colour stays visible: 5.56, 5.45, 5.8, 5.7, 4.6, 7.92, .22, .45, and x39 / x54R / x25 for the three 7.62 rounds.
- **Everything stands upright on Create belts:** TacZ ammo (shown as its 3D box where it has one) and the Incomplete Heavy Round now stand like the brass casings already did.

### Compatibility
- The two packs from 1.0 keep their IDs, so whatever you had switched on stays on.
- No item IDs changed, and the 24 recipes from 1.0 are the same.
- **Now requires the official TacZ for NeoForge 1.21.1, 1.2.0 or newer** ([Modrinth](https://modrinth.com/mod/timeless-and-classics-zero) · [CurseForge](https://www.curseforge.com/minecraft/mc-mods/timeless-and-classics-zero)). The [UNOFFICIAL] TaCZ 1.21.1 NeoForge Port is no longer supported: it has been taken down since the TacZ team released its own NeoForge version.

## Shod's Create and TacZ Bridge 1.0

> **Heads-up:** automation built for the 0.8 recipes may stop working, because the recipes changed. Check the new ones in JEI.

**Big update: every TacZ round can now be made with Create.**

### New
- **24 ammo types** (was 13), so every vanilla TacZ round is covered.
- **Three production tiers:** press on a basin (early game), mixer (mid game) and a deployer assembly line for .338, .50 BMG, 40mm and RPG (late game).
- **Spent casings:** players drop a spent casing (Pistol, Rifle, Large Caliber or Shotgun Shell) for every round fired. Wash it with an encased fan to get an Empty Brass Casing back.
- **Spent casings as chest loot.** Harder structures have more, and End Cities have the most.
- **Two built-in resource packs:** Create-style ammo icons with caliber labels (on by default) and a "Clean (No Labels)" option, plus 3D ammo boxes for six rounds.
- **Flat ammo icons in Create filter slots** (funnels, smart observers, brass tunnels, deployers).
- **Item tags** for sorting: `#shodscreatetacz:spent_casings`, `brass_casings`, `casings` and `tacz_ammo`.
- **In-game config** (Mods → Config): turn casing drops on or off and set the drop chance.
- New Create-style item art and the mod's own Creative tab.

### Changed
- **Create Big Cannons is no longer needed.** Plain gunpowder is used instead.
- All recipes rebalanced: one casing makes one round, and with recycling it stays cheaper than the TacZ workbench.
- Create (6.0.6+) and TacZ (1.1.8+) are now listed as required dependencies.

### Compatibility
- Minecraft 1.21.1, NeoForge 21.1.190+.
- Worlds from 0.8 keep their brass casings, because the item IDs did not change.
