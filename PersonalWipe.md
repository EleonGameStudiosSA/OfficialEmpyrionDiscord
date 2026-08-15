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

A **Full Wipe** means a complete server wipe.

You lose your entire progress except for the contents of your **Orbital Auto Miner** (use `am:?` in chat to check it).

A Full Wipe generally happens with every major Empyrion patch, which has been roughly every **3 months** so far.

</div>

<div class="rule">

## Playfield Wipe

A **Playfield Wipe** removes every structure and placed device on a specific playfield.

You lose:

- Bases
- Ships left on that playfield
- Water Generators
- Other placed devices

Your inventory and anything located on other playfields remain safe.

<div class="note">

**Current Server Status:** We do **not** run Playfield Wipes.

</div>

</div>

<div class="rule">

## Hard Ground / Surface Wipe

A **Hard Ground Wipe** restores an entire planet's terrain to its original state.

This means:

- Every dug hole is filled.
- Every placeable device (such as Water Generators) is removed.
- Terrain returns to its original shape.

Your structures and inventory remain safe.

<div class="warning">

Be careful with **Structural Integrity**, as terrain supporting your base may change.

</div>

<div class="note">

**Current Server Status:** We do **not** run Hard Ground Wipes.

</div>

</div>

<div class="rule">

## Soft Ground / Surface Wipe

A **Soft Ground Wipe** works similarly to a Hard Ground Wipe, but the terrain around and inside your base is preserved.

This means:

- Underground bases remain protected.
- Terrain surrounding player bases is not reset.
- Placeable devices such as Water Generators are removed.

<div class="subsection">

#### Schedule

Starter Planets are wiped:

- **Monday**
- **Wednesday**
- **Friday**

at **9:00 AM**.

</div>

</div>

<div class="rule">

## Deposit Wipe

A **Deposit Wipe** regenerates every resource deposit back to **100%** and resets the terrain around those deposits.

<div class="subsection">

#### Schedule

Starter Planets are wiped:

- **Monday**
- **Wednesday**
- **Friday**

at **9:00 AM**.

</div>

</div>

<div class="rule">

## POI Wipe

A **POI Wipe** restores every Point of Interest to its original state, even if a player has claimed it with their own core.

Because of this, it is **not recommended** to permanently live inside POIs.

<div class="subsection">

#### Schedule

- **Every Planet**
- **Daily**

</div>

</div>

<div class="rule">

## Personal Wipe

The **Personal Wipe Counter** applies only to the **Starter System** (starter planets and their orbits).

Each spawned structure has its own independent **7-day** timer.

You can always check your remaining time with the command:

```text
cb:wipe
```

Use it in:

- **Faction Chat** (if you're in a faction), or
- **Global Chat** (if you're not).

<div class="subsection">

#### Example

- Build an **SV** on the **3rd** of the month.
- Build a **Base** on the **8th**.
- Try leaving Eleen on the **13th**.

Result:

- The **SV** has already been removed.
- The **Base** still has **2 days** remaining.

</div>

<div class="note">

The Personal Wipe Counter only applies to the **Starter Planets and their Orbits**. It does **not** affect structures on other playfields.

</div>

</div>

<div class="note">

## Best Practice

Check your `cb:wipe` timer regularly while you're in the Starter System. Once you move beyond the starter playfields, the Personal Wipe Counter no longer applies.

</div>