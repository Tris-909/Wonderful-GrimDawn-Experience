# Tris

A **Custom Game** QoL / farming mod for [Grim Dawn](https://store.steampowered.com/app/219990/Grim_Dawn/), built as a fork of **Faster Leveling (L)** with extra progression, UI, and combat quality-of-life.

> Launch via **Custom Game → Tris**. Do not overwrite the original `Faster Leveling (L)` folder.

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
- **HUD** (HP/MP orbs and skill bar) is **1.4× vanilla** so it stays readable when UI Scale is lowered for X-Mod
- **NPC conversation** and **quest-reward** dialogs are **1.4×**, including the text inside

> **Tip:** Set **UI Scale** to default (left). Max UI Scale will clip X-Mod layouts. HUD and dialog size are already raised in the mod; you do not need to raise Scale for those.

### Combat & farming

- **Normal only:** all monsters and bosses (base game + DLCs) have **+50% HP** and **+20% damage**
- **Pack density (all difficulties):** **+50% extra mobs** in a pack on Normal, Veteran, Elite, and Ultimate. Story bosses stay one copy
- **Boss Respawn Count** skill — cycle **Off → 1–10** (default **Off**)
  - Disabled in Shattered Realm / Endless Dungeon
- **Monster regen / heal nerf** — global regen/leech heavily reduced; many non-player heals cut

### Difficulty at a glance

| Mode | Monster HP | Monster damage | Pack density | XP |
| ---- | ---------- | -------------- | ------------ | -- |
| **Normal** | +50% vs vanilla | +20% vs vanilla | +50% extra mobs | N |
| **Veteran** | Normal + Veteran overlay | Normal + Veteran overlay | +50% extra mobs | N × 1.1 |
| **Elite** | Vanilla | Vanilla | +50% extra mobs | N^1.06 + 40 |
| **Ultimate** | Vanilla | Vanilla | +50% extra mobs | N^1.12 + 80 |

### Factions & bounties

- Reputation is earned normally (no auto-Revered on load)
- **Every bounty turn-in grants 2000 faction reputation** (all difficulties, base game + DLC)
  - From **Respected → Revered**: about **10 bounties** (~2 sessions at 5 per session)
- **Kymon’s Chosen / Order of Death’s Vigil** stay exclusive — the side you didn’t pick remains hostile

### Wings & cosmetics

Wing / cape / robe looks are **medals**: an invisible medal mesh attaches the 3D wing FX. Equip the medal, or apply it as a **Medal Illusion**.

- **50+** cosmetic medals (Pride, Aion, Kayle, Inarius, Nightfall, TLI robe, and the rest), plus Katana / Chillrend / Chaos Eater weapon meshes
- Craft them at the **Devil’s Crossing blacksmiths** (Master or Apprentice): **1 healing potion + 10 iron bits**. Vanilla weapon recipes are unchanged
- Or talk to **Rook** (door guard) at Devil’s Crossing and choose **Give me the wings** / **Give me the rest of the wings**
- Pack source: [cosmetic wings on the Crate forums](https://forums.crateentertainment.com/t/cosmetic-wings-inarius-wings/51190)

---

## Install

1. Place this folder at:

   ```text
   <Grim Dawn>\mods\Tris
   ```

2. Start Grim Dawn → **Custom Game** → select **Tris**

3. Optional UI textures: if X-Mod icons are missing, unpack / place `x-mod` textures under:

   ```text
   Documents\My Games\Grim Dawn\Settings\x-mod\
   ```

---

## Saves & stash

Custom Game stashes are **separate** from vanilla, from Faster Leveling (L), and from the main `Tris` folder:

```text
Documents\My Games\Grim Dawn\save\Tris\
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
- Additional Tris changes: progression caps, Normal HP/damage, pack density, boss respawn, regen nerfs, bounty reputation tuning, Kymon/Order exclusivity, 1.4× HUD and dialog
- Wing / cosmetic medals: [cosmetic wings pack](https://forums.crateentertainment.com/t/cosmetic-wings-inarius-wings/51190) (meshes, FX, and blacksmith formulas)
