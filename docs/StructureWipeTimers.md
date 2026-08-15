# Structure Decay & Wipe Timers Guide

Empyrion includes two cleanup timers in `gameoptions.yaml` that automatically remove abandoned player-built structures after they have not been visited for a specified period.

---

## Structure Cleanup Timers

### DecayTime

**Current Setting:** `24`

This timer removes player-built structures that either:

- Have **no core**, or
- Contain **fewer than 10 blocks**.

The cleanup occurs after the structure has not been visited for **24 hours**.

> Setting `DecayTime` to `0` disables this cleanup.

---

### WipeTime

**Current Setting:** `0`

This timer removes **any** player-built structure after it has not been visited for the configured time.

Since the current value is `0`, this automatic wipe is **disabled**.

---

## How the Timer Resets

### Physical Interaction Required

The visit timer only resets when a player physically walks onto or touches the structure.

The following actions reset the timer:

- Walking onto a **Base (BA)**
- Entering or touching a **CV**
- Entering or touching an **SV**
- Entering or touching an **HV**

---

## Important

Opening a structure through the **F4 Logistics Menu** does **not** reset the visit timer.

You must physically visit the structure for the timer to refresh.

---

## Remember

If you're relying on remote logistics to manage your base, make sure to periodically visit your structures in person.

Remote access alone will not prevent cleanup timers from continuing to count down.