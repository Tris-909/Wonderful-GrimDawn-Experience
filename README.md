# Wonderful Grim Dawn Experience

Custom-game QoL pack for [Grim Dawn](https://store.steampowered.com/app/219990/Grim_Dawn/).

The playable mod lives in the [`Tris`](./Tris) folder — a fork of **Faster Leveling (L)** with extra progression, UI, combat QoL, and fast bounty reputation.

> In-game: **Custom Game → Tris**  
> Do not overwrite the original `Faster Leveling (L)` folder.

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

---

## Install

1. Copy the `Tris` folder from this repo into your Grim Dawn mods directory:

   ```text
   <Grim Dawn>\mods\Tris
   ```

   Example Steam path:

   ```text
   C:\Program Files (x86)\Steam\steamapps\common\Grim Dawn\mods\Tris
   ```

2. Start Grim Dawn → **Custom Game** → select **Tris**

3. Optional UI textures: if X-Mod icons are missing, place `x-mod` textures under:

   ```text
   Documents\My Games\Grim Dawn\Settings\x-mod\
   ```

---

## Saves & stash

Custom Game stashes are **separate** from vanilla and from Faster Leveling (L):

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
- Additional Tris changes: progression caps, boss respawn, regen nerfs, bounty reputation tuning, Kymon/Order exclusivity, UI fit tweaks
