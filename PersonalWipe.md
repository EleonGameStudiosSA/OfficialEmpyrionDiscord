---
layout: default
title: Wipe Types Guide
---

<div class="section">

<div class="rule">
<h3>Wipe Types</h3>
<p>
    Empyrion uses several different types of wipes, each affecting different parts of the game.
    Understanding the difference helps you know what is safe and what may be removed during scheduled maintenance.
</p>
</div>

<div class="rule">
<h3>Full Wipe</h3>

<p>
    A <strong>Full Wipe</strong> means a complete server wipe.
</p>

<p>
    You lose your entire progress except for the contents of your
    <strong>Orbital Auto Miner</strong> (use <code>am:?</code> in chat to check it).
</p>

<div class="warning">
<strong>Everything else is lost.</strong>
<ul>
<li>Bases</li>
<li>Ships</li>
<li>Inventory</li>
<li>Progress</li>
</ul>
</div>

<p>
    A Full Wipe generally happens with every major Empyrion patch, which has been roughly
    <strong>every 3 months</strong>.
</p>
</div>

<div class="rule">
<h3>Playfield Wipe</h3>

<p>
    A <strong>Playfield Wipe</strong> removes every structure and placed device on a specific playfield.
</p>

<div class="subsection">
<h4>What is removed</h4>
<ul>
<li>Bases</li>
<li>Ships left on that playfield</li>
<li>Water Generators</li>
<li>Other placed devices</li>
</ul>

<p>
    Your inventory and anything located on other playfields remain safe.
</p>
</div>

<div class="note">
<strong>Current Server Status:</strong> We do <strong>not</strong> run Playfield Wipes.
</div>
</div>

<div class="rule">
<h3>Hard Ground / Surface Wipe</h3>

<p>
    A <strong>Hard Ground Wipe</strong> restores an entire planet's terrain to its original state.
</p>

<div class="subsection">
<h4>What changes</h4>

<ul>
<li>Every dug hole is filled.</li>
<li>Every placeable device (such as Water Generators) is removed.</li>
<li>Terrain returns to its original shape.</li>
</ul>

<p>
    Your structures and inventory remain safe.
</p>
</div>

<div class="warning">
<strong>Structural Integrity Warning:</strong>
Terrain supporting your base may change, so unsupported structures can become unstable.
</div>

<div class="note">
<strong>Current Server Status:</strong> We do <strong>not</strong> run Hard Ground Wipes.
</div>
</div>

<div class="rule">
<h3>Soft Ground / Surface Wipe</h3>

<p>
    A <strong>Soft Ground Wipe</strong> works similarly to a Hard Ground Wipe, but the terrain around and inside your base is preserved.
</p>

<div class="subsection">
<h4>What changes</h4>

<ul>
<li>Underground bases remain protected.</li>
<li>Terrain surrounding player bases is not reset.</li>
<li>Placeable devices such as Water Generators are removed.</li>
</ul>
</div>

<div class="subsection">
<h4>Schedule</h4>

<p>Starter Planets are wiped:</p>

<ul>
<li><strong>Monday</strong></li>
<li><strong>Wednesday</strong></li>
<li><strong>Friday</strong></li>
</ul>

<p>at <strong>9:00 AM</strong>.</p>
</div>
</div>

<div class="rule">
<h3>Deposit Wipe</h3>

<p>
    A <strong>Deposit Wipe</strong> regenerates every resource deposit back to <strong>100%</strong> and resets the terrain around those deposits.
</p>

<div class="subsection">
<h4>Schedule</h4>

<p>Starter Planets are wiped:</p>

<ul>
<li><strong>Monday</strong></li>
<li><strong>Wednesday</strong></li>
<li><strong>Friday</strong></li>
</ul>

<p>at <strong>9:00 AM</strong>.</p>
</div>
</div>

<div class="rule">
<h3>POI Wipe</h3>

<p>
    A <strong>POI Wipe</strong> restores every Point of Interest to its original state, even if a player has claimed it with their own core.
</p>

<div class="warning">
<strong>Don't live in POIs.</strong>
Claiming a POI with your own core does <strong>not</strong> protect it from a POI wipe.
</div>

<div class="subsection">
<h4>Schedule</h4>

<ul>
<li><strong>Every Planet</strong></li>
<li><strong>Daily</strong></li>
</ul>
</div>
</div>

<div class="rule">
<h3>Personal Wipe</h3>

<p>
    The <strong>Personal Wipe Counter</strong> applies only to the <strong>Starter System</strong> (starter planets and their orbits).
</p>

<p>
    Each spawned structure has its own independent <strong>7-day timer</strong>.
</p>

<div class="subsection">
<h4>Check Your Timer</h4>

<p>Use:</p>

<pre><code>cb:wipe</code></pre>

<p>Run it in:</p>

<ul>
<li><strong>Faction Chat</strong> (if you're in a faction)</li>
<li><strong>Global Chat</strong> (if you're not)</li>
</ul>
</div>

<div class="subsection">
<h4>Example</h4>

<table>
<thead>
<tr>
<th>Structure</th>
<th>Built</th>
<th>Result</th>
</tr>
</thead>
<tbody>
<tr>
<td>SV</td>
<td>3rd</td>
<td>Removed by the 13th</td>
</tr>
<tr>
<td>Base</td>
<td>8th</td>
<td>Still has 2 days remaining</td>
</tr>
</tbody>
</table>
</div>

<div class="note">
The Personal Wipe Counter only applies to the <strong>Starter Planets and their Orbits</strong>. It does <strong>not</strong> affect structures on other playfields.
</div>

</div>

<div class="note">
<strong>Best Practice:</strong> Check <code>cb:wipe</code> regularly while you're in the Starter System. Once you move beyond the starter playfields, the Personal Wipe Counter no longer applies.
</div>

</div>