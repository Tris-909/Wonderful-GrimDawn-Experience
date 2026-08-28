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

### Combat & farming

- **Boss Respawn Count** skill — cycle **Off → 1–10** (default **Off**)
  - Disabled in Shattered Realm / Endless Dungeon
- **Monster regen / heal nerf** — global regen/leech heavily reduced; many non-player heals cut

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

## Notes

- Custom Game stashes are **separate** from vanilla, from Faster Leveling (L), and from each other (`Tris` vs `Tris-Original`)
- Shared transfer stash is typically `transfer.gst` in that save folder. Steam Cloud may also mirror under `userdata\...\219990\remote\save`
- `wings.arc` is stored with **Git LFS** (over GitHub’s 100 MB file limit). Clone with Git LFS installed, or the wings file will be a tiny pointer instead of the real asset

---

## Credits

- Base QoL pack (Tris only): **Faster Leveling (L)**
- Expanded UI: **X-Mod / Grim UI**
- Additional Tris changes: progression caps, boss respawn, regen nerfs, bounty reputation tuning, Kymon/Order exclusivity, UI fit tweaks
- Wing / cosmetic medals: [cosmetic wings pack](https://forums.crateentertainment.com/t/cosmetic-wings-inarius-wings/51190)
