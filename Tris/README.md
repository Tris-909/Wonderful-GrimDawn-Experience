# Tris

A **Custom Game** QoL / farming mod for [Grim Dawn](https://store.steampowered.com/app/219990/Grim_Dawn/), built as a fork of **Faster Leveling (L)** with extra progression, UI, and combat quality-of-life.

> Launch via **Custom Game → Tris - Copy**. Do not overwrite the original `Faster Leveling (L)` or `Tris` folders.

---

## Features

### From Faster Leveling (L)

| Feature | Description |
|--------|-------------|
| **Sam the Good Boy** | Summon pet that grants a blessing: damage, run speed, and XP |
| **Honck** | Special merchant spawned via Sam |
| **Transmutation** | Recycle ground items into something else (uniques skipped) |
| **Beutekugeln** | Loot spheres (common → divine, MI, materials, and more) |
| **XP Tomes** | Short / medium / large experience buffs |
| **Potions** | Iron bits, attribute, skill, and devotion point potions |

### Progression

- **Max level** raised to **100**
- **Devotion cap** raised to **60**
- **Elite / Ultimate XP** tuned upward (Elite uses a stronger XP curve; Ultimate higher still)
- **Shrines / totems** biased toward stronger epic–legendary outcomes

### Stash & UI

- Shared **transfer stash** (Smuggler / caravan) with Tris-tuned layout
- Transfer tab unlock costs kept at **vanilla** prices
- **X-Mod / Grim UI** integrated — expanded Character, Smuggler, Factions, Transmuter, Map, and Quest windows

> **Tip:** Set **UI Scale** to default (left). Max UI Scale will clip X-Mod layouts.

### Combat & farming

- **Boss Respawn Count** skill — cycle **Off → 1–10** (default **Off**)
  - Disabled in Shattered Realm / Endless Dungeon
- **Monster regen / heal nerf** — global regen/leech heavily reduced; many non-player heals cut

### Factions & bounties

- Reputation is earned normally (no auto-Revered on load)
- **Every bounty turn-in grants 2000 faction reputation** (all difficulties, base game + DLC)
  - From **Respected → Revered**: about **10 bounties** (~2 sessions at 5 per session)
- **Kymon’s Chosen / Order of Death’s Vigil** stay exclusive — the side you didn’t pick remains hostile

### Cosmetics (from the `test` wing mod)

Wing / cape / robe looks are **medals**: an invisible medal mesh attaches the 3D wing FX. Equip the medal, or apply it as a **Medal Illusion**.

- **50** cosmetic medals (Pride, Aion, Kayle, Inarius, Nightfall, TLI robe, and the rest), plus Katana / Chillrend / Chaos Eater weapon meshes
- Craft them at the **Devil’s Crossing blacksmiths** (Master or Apprentice): 1 healing potion + 10 iron bits, same recipe the test mod used for Pride / Aion
- Vanilla blacksmith weapon crafts are unchanged; only extra formulas were added
- Names live in `tags_test_cosmetics.txt` (`tagPrideWings`, `tagTlirobe`, …)

---

## Install

1. Place this folder at:

   ```text
   <Grim Dawn>\mods\Tris - Copy
   ```

2. Start Grim Dawn → **Custom Game** → select **Tris - Copy**

3. Optional UI textures: if X-Mod icons are missing, unpack / place `x-mod` textures under:

   ```text
   Documents\My Games\Grim Dawn\Settings\x-mod\
   ```

---

## Saves & stash

Custom Game stashes are **separate** from vanilla, from Faster Leveling (L), and from the main `Tris` folder:

```text
Documents\My Games\Grim Dawn\save\Tris - Copy\
```

Shared transfer stash is typically `transfer.gst` in that folder. Steam Cloud may also mirror under `userdata\...\219990\remote\save`.

---

## Notes

- Characters already maxed to Revered by older Tris builds keep that standing; new gains use the bounty path above
- Boss respawn is off by default — enable the skill when you want farm loops
- This is a single-player / private-group QoL pack, not a multiplayer balance mod

---

## Credits

- Base QoL pack: **Faster Leveling (L)**
- Expanded UI: **X-Mod / Grim UI**
- Additional Tris changes: progression caps, boss respawn, regen nerfs, bounty reputation tuning, Kymon/Order exclusivity, UI fit tweaks
- Wing / cosmetic medals: the `test` Asset Manager pack (meshes, FX, and blacksmith formulas)
