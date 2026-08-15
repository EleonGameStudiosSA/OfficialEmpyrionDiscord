---
layout: default
title: Wipe Types Guide
---

<div class="rule">

## Wipe Types

Empyrion uses several different types of wipes, each affecting different parts of the game. Understanding the difference helps you know what is safe and what may be removed during scheduled maintenance.

</div>

<div class="rule">

## Full Wipe

A **Full Wipe** is a complete server reset.

Everything is removed except the contents of your **Orbital Auto Miner** (check it with `am:?` in chat).

<div class="warning">

**Everything else is lost.**

- Bases
- Ships
- Inventory
- Progress

</div>

A Full Wipe generally happens with every major Empyrion patch, which has been roughly **every 3 months**.

</div>

<div class="rule">

## Playfield Wipe

A **Playfield Wipe** removes everything built or placed on a specific playfield.

<div class="subsection">

#### What is removed

- Bases
- Ships left on that playfield
- Water Generators
- Other placed devices

Your inventory and anything on other playfields remain safe.

</div>

<div class="note">

**Current Server Status:** We do **not** run Playfield Wipes.

</div>

</div>

<div class="rule">

## Hard Ground / Surface Wipe

A **Hard Ground Wipe** restores an entire planet's terrain to its original state.

<div class="subsection">

#### What changes

- Every dug hole is filled.
- Every placeable device (such as Water Generators) is removed.
- Terrain returns to its original shape.

Your structures and inventory remain safe.

</div>

<div class="warning">

**Structural Integrity Warning**

Terrain supporting your base may change, so unsupported structures can become unstable.

</div>

<div class="note">

**Current Server Status:** We do **not** run Hard Ground Wipes.

</div>

</div>

<div class="rule">

## Soft Ground / Surface Wipe

A **Soft Ground Wipe** works like a Hard Ground Wipe, except terrain around player bases is preserved.

<div class="subsection">

#### What changes

- Underground bases remain protected.
- Terrain around player bases is untouched.
- Placeable devices such as Water Generators are removed.

</div>

<div class="subsection">

#### Schedule

**Starter Planets**

- Monday
- Wednesday
- Friday

**Time:** **9:00 AM**

</div>

</div>

<div class="rule">

## Deposit Wipe

A **Deposit Wipe** regenerates every resource deposit back to **100%** and resets the terrain around those deposits.

<div class="subsection">

#### Schedule

**Starter Planets**

- Monday
- Wednesday
- Friday

**Time:** **9:00 AM**

</div>

</div>

<div class="rule">

## POI Wipe

A **POI Wipe** restores every Point of Interest to its original state, even if a player has claimed it with their own core.

<div class="warning">

**Don't live in POIs.**

Claiming a POI with your own core does **not** protect it from a POI wipe.

</div>

<div class="subsection">

#### Schedule

- Every Planet
- **Daily**

</div>

</div>

<div class="rule">

## Personal Wipe

The **Personal Wipe Counter** only applies to the **Starter System** (starter planets and their orbits).

Each spawned structure has its own independent **7-day timer**.

<div class="subsection">

#### Check Your Timer

Use:

```text
cb:wipe
```

Run it in:

- **Faction Chat** (if you're in a faction)
- **Global Chat** (if you're not)

</div>

<div class="subsection">

#### Example

| Structure | Built | Result |
|-----------|-------|--------|
| SV | 3rd | Removed by the 13th |
| Base | 8th | Still has 2 days remaining |

</div>

<div class="note">

The Personal Wipe Counter only applies to **Starter Planets and their Orbits**. It does **not** affect structures on other playfields.

</div>

</div>

<div class="note">

## Best Practice

- Check `cb:wipe` regularly while you're in the Starter System.
- Move important structures off the Starter playfields before their timer expires.
- Remember that once you're outside the Starter System, the Personal Wipe Counter no longer applies.

</div>