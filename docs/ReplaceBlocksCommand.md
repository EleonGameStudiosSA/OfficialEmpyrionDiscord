# Replace Blocks Command Guide

> **Warning:** **Do not use this in multiplayer.** This command permanently modifies a structure and **cannot be undone.**

The `replaceblocks` command replaces one block type with another throughout an entire vessel or base. The ID used is the **Vessel/Base ID**, not an individual block ID.

---

## Basic Syntax

```text
replaceblocks <StructureID> <FromBlock> <ToBlock>
```

### Examples

Upgrade Steel to Combat Steel:

```text
replaceblocks 1009 HullLargeBlocks HullCombatLargeBlocks
```

Upgrade Concrete to Armored Concrete:

```text
replaceblocks 1009 ConcreteFull ConcreteArmoredFull
```

---

## Block Groups

Block Groups replace every matching block within the structure, making large upgrades much faster.

| Block Group | Structures | Material |
|-------------|------------|----------|
| `WoodBlocks` | BA | Wood |
| `ConcreteBlocks` | BA | Concrete |
| `ConcreteArmoredBlocks` | BA | Armored Concrete |
| `PlasticLargeBlocks` | BA, CV | Carbon Composite (Large) |
| `HullLargeBlocks` | BA, CV | Steel (Large) |
| `HullArmoredLargeBlocks` | BA, CV | Hardened Steel (Large) |
| `HullCombatLargeBlocks` | BA, CV | Combat Steel (Large) |
| `AlienLargeBlocks` | BA, CV | Xeno Steel |
| `AlienBlocks` | POIs | Alien Building Blocks |
| `PlasticSmallBlocks` | HV, SV | Carbon Composite (Small) |
| `HullSmallBlocks` | HV, SV | Steel (Small) |
| `HullArmoredSmallBlocks` | HV, SV | Hardened Steel (Small) |
| `HullCombatSmallBlocks` | HV | Combat Steel (Small) |

---

## Removing Blocks

You can remove blocks entirely by replacing them with `empty` or `0`.

```text
replaceblocks 1009 ContainerExtension empty
```

This is especially useful for mass-removing Container Extensions or other unwanted blocks.

---

## Special Block Types

### Truss Blocks

- `TrussCube`
- `TrussWedge`
- `TrussCorner`

### Shutter Windows

- `WindowVertShutterArmored`
- `WindowSlopedShutterArmored`
- `WindowSloped2ShutterArmored`
- `WindowVertShutterTransArmored`
- `WindowSlopedShutterTransArmored`

### Normal Windows

Includes vertical, sloped, corner, curved, diagonal, and inverted variants.

```text
Window_v1x1
Window_v1x2
Window_v2x2
Window_s1x1
Window_s1x2
Window_sd1x1
Window_sd1x2
Window_sd1x2V2
Window_c1x1
Window_c1x2
Window_cr1x1
Window_crc1x1
Window_crsd1x1

Window_v1x1Inv
Window_v1x2Inv
Window_v2x2Inv
Window_s1x1Inv
Window_s1x2Inv
Window_sd1x1Inv
Window_sd1x2Inv
Window_sd1x2V2Inv
Window_c1x1Inv
Window_c1x2Inv
Window_cr1x1Inv
Window_crc1x1Inv
Window_crsd1x1Inv
```

### Armored Windows

All standard window shapes also have armored (`Thick`) variants.

```text
Window_v1x1Thick
Window_v1x2Thick
Window_v2x2Thick
Window_s1x1Thick
Window_s1x2Thick
Window_sd1x1Thick
Window_sd1x2Thick
Window_sd1x2V2Thick
Window_c1x1Thick
Window_c1x2Thick
Window_cr1x1Thick
Window_crc1x1Thick
Window_crsd1x1Thick

Window_v1x1ThickInv
Window_v1x2ThickInv
Window_v2x2ThickInv
Window_s1x1ThickInv
Window_s1x2ThickInv
Window_sd1x1ThickInv
Window_sd1x2ThickInv
Window_sd1x2V2ThickInv
Window_c1x1ThickInv
Window_c1x2ThickInv
Window_cr1x1ThickInv
Window_crc1x1ThickInv
Window_crsd1x1ThickInv
```

---

## Block Type Reference

| Material | Block Types |
|----------|-------------|
| Wood | `WoodFull`, `WoodThin`, `WoodExtended2-7` |
| Concrete | `ConcreteFull`, `ConcreteThin`, `ConcreteExtended2-7` |
| Armored Concrete | `ConcreteArmoredFull`, `ConcreteArmoredThin`, `ConcreteArmoredExtended2-7` |
| Carbon Composite (Large) | `PlasticFullLarge`, `PlasticThinLarge`, `PlasticExtendedLarge2-7` |
| Steel (Large) | `HullFullLarge`, `HullThinLarge`, `HullExtendedLarge2-7` |
| Hardened Steel (Large) | `HullArmoredFullLarge`, `HullArmoredThinLarge`, `HullArmoredExtendedLarge2-7` |
| Combat Steel (Large) | `HullCombatFullLarge`, `HullCombatThinLarge`, `HullCombatExtendedLarge2-7` |
| Xeno Steel | `AlienFullLarge`, `AlienThinLarge`, `AlienExtendedLarge2-7` |
| Alien Building | `AlienFull`, `AlienThin`, `AlienExtended2-7` |
| Carbon Composite (Small) | `PlasticFullSmall`, `PlasticThinSmall`, `PlasticExtendedSmall2-7` |
| Steel (Small) | `HullFullSmall`, `HullThinSmall`, `HullExtendedSmall2-7` |
| Hardened Steel (Small) | `HullArmoredFullSmall`, `HullArmoredThinSmall`, `HullArmoredExtendedSmall2-7` |
| Combat Steel (Small) | `HullCombatFullSmall`, `HullCombatThinSmall`, `HullCombatExtendedSmall2-7` |

---

## Best Practice

- Test `replaceblocks` in **Single Player** or on a backup save first.
- Double-check the **Structure ID** before running the command.
- Remember that there is **no built-in undo**, so the changes are permanent.