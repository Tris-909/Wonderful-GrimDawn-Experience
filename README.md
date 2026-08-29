# Wonderful Grim Dawn Experience

Custom-game packs by **TriTran** for [Grim Dawn](https://store.steampowered.com/app/219990/Grim_Dawn/).

This repo has **two** mods pack. Pick one:

| Folder | What you get |
| ------ | ------------ |
| **[`Tris-Original`](./Tris-Original)** | **Cosmetics + stash UI only.** Wings/outfit medals and X-Mod expanded stash/windows. Vanilla leveling, devotion, XP, bounties, and combat. |
| **[`Tris`](./Tris)** | Full QoL pack (Faster Leveling features, progression, farming, bounty reputation, **plus** the same wings and X-Mod UI). |

---

## Tris-Original (cosmetics + stash only)

This is the lightweight pack. It does **not** include Sam, Honck, Transmutation, loot spheres, XP tomes, potions, level/devotion cap changes, Elite/Ultimate XP tuning, shrine changes, boss respawn, regen nerfs, or extra bounty reputation.

### Wings & cosmetics

Wing / cape / robe looks are **medals**. Equip the medal, or apply it as a **Medal Illusion**.

- **50+** cosmetic medals (Pride, Aion, Kayle, Inarius, Nightfall, TLI robe, and the rest), plus Katana / Chillrend / Chaos Eater
- Craft at the **Devil’s Crossing blacksmiths** (Master or Apprentice): **1 healing potion + 10 iron bits**
- Or talk to **Rook** (prison-gate door guard) in Devil’s Crossing and choose **Give me the wings** / **Give me the rest of the wings**

### Stash & UI

- **X-Mod / Grim UI** — expanded Character, Smuggler, Factions, Transmuter, Map, and Quest windows
- **HUD** (HP/MP orbs and skill bar) is **1.4× vanilla** so it stays readable when UI Scale is lowered for X-Mod

> **Tip:** Set **UI Scale** to default (left). Max UI Scale will clip X-Mod layouts.

### Install Tris-Original

1. Copy the `Tris-Original` folder into:

   ```text
   <Grim Dawn>\mods\Tris-Original
   ```

   Example Steam path:

   ```text
   C:\Program Files (x86)\Steam\steamapps\common\Grim Dawn\mods\Tris-Original
   ```

2. Start Grim Dawn → **Custom Game** → select **Tris-Original**

3. Optional: if X-Mod icons are missing, place `x-mod` textures under:

   ```text
   Documents\My Games\Grim Dawn\Settings\x-mod\
   ```

Saves for this pack:

```text
Documents\My Games\Grim Dawn\save\Tris-Original\
```

---

## Tris (full QoL pack)

The playable full mod lives in [`Tris`](./Tris) — a fork of **Faster Leveling (L)** with extra progression, UI, combat QoL, bounty reputation, and the same cosmetic wings.

> In-game: **Custom Game → Tris**

### From Faster Leveling (L)

| Feature              | Description                                                  |
| -------------------- | ------------------------------------------------------------ |
| **Sam the Good Boy** | Summon pet that grants a blessing: damage, run speed, and XP |
| **Honck**            | Special merchant spawned via Sam                             |
| **Transmutation**    | Recycle ground items into something else (uniques skipped)   |
| **Beutekugeln**      | Loot spheres (common → divine, MI, materials, and more)      |
| **XP Tomes**         | Short / medium / large experience buffs                      |
| **Potions**          | Iron bits, attribute, skill, and devotion point potions      |

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

Same medals and obtain methods as **Tris-Original** (blacksmith crafts and Rook).

Cosmetic meshes and FX come from the [Crate forums cosmetic wings pack](https://forums.crateentertainment.com/t/cosmetic-wings-inarius-wings/51190).

### Install Tris

1. Copy the `Tris` folder from this repo into your Grim Dawn mods directory:

   ```text
   <Grim Dawn>\mods\Tris
   ```

2. Start Grim Dawn → **Custom Game** → select **Tris**

Saves:

```text
Documents\My Games\Grim Dawn\save\Tris\
```

---

## Updating Tris (keep your character)

New GitHub versions of **Tris** are still the same Custom Game. You do **not** start a new hero if you overwrite the same folder.

1. **Quit Grim Dawn** completely (not just to the menu).
2. Download the latest repo (or clone/pull).
3. Copy the `Tris` folder over the old one, so it stays exactly:

   ```text
   <Grim Dawn>\mods\Tris
   ```

   Keep the folder name **`Tris`**. Do not install as `Tris2`, `Tris-new`, or similar.
4. Start Grim Dawn → **Custom Game** → **Tris** → pick your character.

Your hero lives in `Documents\My Games\Grim Dawn\save\user\` (for example `user\_GodBlade\player.gdc`). The Smuggler stash and related files live in `Documents\My Games\Grim Dawn\save\Tris\`. Updating the mod does not replace those folders.

Optional backup before you overwrite the mod:

```text
Documents\My Games\Grim Dawn\save\user\
Documents\My Games\Grim Dawn\save\Tris\
```

**Same idea for Tris-Original:** overwrite `mods\Tris-Original` and keep that name. Characters are in `save\user\`; stash is in `save\Tris-Original\`.

If you ever installed the pack under a **different** folder name, copy the stash files (`transfer.gst`, `reagents.gst`, `formulas.gst`, `transmutes.gst`) from that name’s save folder into `save\Tris\`, then launch **Custom Game → Tris**.

---

## Notes

- Custom Game stashes are **separate** from vanilla, from Faster Leveling (L), and from each other (`Tris` vs `Tris-Original`)
- Shared transfer stash is typically `transfer.gst` in that save folder. Steam Cloud may also mirror under `userdata\...\219990\remote\save`
- `wings.arc` is stored with **Git LFS** (over GitHub’s 100 MB file limit). Clone with Git LFS installed, or the wings file will be a tiny pointer instead of the real asset

---

## Credits

- Base QoL pack (Tris only): **Faster Leveling (L)**
- Expanded UI: **X-Mod / Grim UI**
- Additional Tris changes: progression caps, Normal HP/damage, pack density, boss respawn, regen nerfs, bounty reputation tuning, Kymon/Order exclusivity, 1.4× HUD and dialog
- Wing / cosmetic medals: [cosmetic wings pack](https://forums.crateentertainment.com/t/cosmetic-wings-inarius-wings/51190)
