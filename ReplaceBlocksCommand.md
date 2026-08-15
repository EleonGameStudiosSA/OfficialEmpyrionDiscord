---
layout: default
title: Replace Blocks Command
---



<div class="warning">
<strong>DO NOT USE THIS IN MULTIPLAYER!</strong><br/>
        This command permanently modifies a structure and <strong>cannot be undone.</strong>
</div>
<div class="rule">
<h3>What the Command Does</h3>
<p>
            The <code>replaceblocks</code> command replaces one block type with another throughout an entire vessel or base.
            The number used is the <strong>Vessel/Base ID</strong>, not an individual block ID.
        </p>
<div class="subsection">
<h4>Basic Syntax</h4>
<pre><code>replaceblocks &lt;StructureID&gt; &lt;FromBlock&gt; &lt;ToBlock&gt;</code></pre>
</div>
<div class="subsection">
<h4>Examples</h4>
<p>Upgrade Steel to Combat Steel:</p>
<pre><code>replaceblocks 1009 HullLargeBlocks HullCombatLargeBlocks</code></pre>
<p>Upgrade Concrete to Armored Concrete:</p>
<pre><code>replaceblocks 1009 ConcreteFull ConcreteArmoredFull</code></pre>
</div>
</div>
<div class="rule">
<h3>Block Groups</h3>
<p>
            Block Groups replace every matching block within the structure, making upgrades much faster.
        </p>
<table>
<thead>
<tr>
<th>Block Group</th>
<th>Structures</th>
<th>Material</th>
</tr>
</thead>
<tbody>
<tr><td><code>WoodBlocks</code></td><td>BA</td><td>Wood</td></tr>
<tr><td><code>ConcreteBlocks</code></td><td>BA</td><td>Concrete</td></tr>
<tr><td><code>ConcreteArmoredBlocks</code></td><td>BA</td><td>Armored Concrete</td></tr>
<tr><td><code>PlasticLargeBlocks</code></td><td>BA, CV</td><td>Carbon Composite (Large)</td></tr>
<tr><td><code>HullLargeBlocks</code></td><td>BA, CV</td><td>Steel (Large)</td></tr>
<tr><td><code>HullArmoredLargeBlocks</code></td><td>BA, CV</td><td>Hardened Steel (Large)</td></tr>
<tr><td><code>HullCombatLargeBlocks</code></td><td>BA, CV</td><td>Combat Steel (Large)</td></tr>
<tr><td><code>AlienLargeBlocks</code></td><td>BA, CV</td><td>Xeno Steel</td></tr>
<tr><td><code>AlienBlocks</code></td><td>POIs</td><td>Alien Building Blocks</td></tr>
<tr><td><code>PlasticSmallBlocks</code></td><td>HV, SV</td><td>Carbon Composite (Small)</td></tr>
<tr><td><code>HullSmallBlocks</code></td><td>HV, SV</td><td>Steel (Small)</td></tr>
<tr><td><code>HullArmoredSmallBlocks</code></td><td>HV, SV</td><td>Hardened Steel (Small)</td></tr>
<tr><td><code>HullCombatSmallBlocks</code></td><td>HV</td><td>Combat Steel (Small)</td></tr>
</tbody>
</table>
</div>
<div class="rule">
<h3>Removing Blocks</h3>
<div class="subsection">
<h4>Empty Block Space</h4>
<p>
                You can remove blocks entirely by replacing them with <code>empty</code> or <code>0</code>.
            </p>
<pre><code>replaceblocks 1009 ContainerExtension empty</code></pre>
<p>
                This is especially useful for mass-removing container extensions or other unwanted blocks.
            </p>
</div>
</div>
<div class="rule">
<h3>Special Block Types</h3>
<div class="subsection">
<h4>Truss Blocks</h4>
<div class="compact">
<code>TrussCube</code>
<code>TrussWedge</code>
<code>TrussCorner</code>
</div>
</div>
<div class="subsection">
<h4>Shutter Windows</h4>
<div class="compact">
<code>WindowVertShutterArmored</code>
<code>WindowSlopedShutterArmored</code>
<code>WindowSloped2ShutterArmored</code>
<code>WindowVertShutterTransArmored</code>
<code>WindowSlopedShutterTransArmored</code>
</div>
</div>
<div class="subsection">
<h4>Normal Windows</h4>
<p>
                Includes vertical, sloped, corner, curved, diagonal, and inverted variants.
            </p>
<pre><code>Window_v1x1
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
Window_crsd1x1Inv</code></pre>
</div>
<div class="subsection">
<h4>Armored Windows</h4>
<p>
                All standard window shapes also have armored ("Thick") variants.
            </p>
<pre><code>Window_v1x1Thick
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
Window_crsd1x1ThickInv</code></pre>
</div>
</div>
<div class="rule">
<h3>Block Type Reference</h3>
<table>
<thead>
<tr>
<th>Material</th>
<th>Block Types</th>
</tr>
</thead>
<tbody>
<tr>
<td>Wood</td>
<td><code>WoodFull</code>, <code>WoodThin</code>, <code>WoodExtended2-7</code></td>
</tr>
<tr>
<td>Concrete</td>
<td><code>ConcreteFull</code>, <code>ConcreteThin</code>, <code>ConcreteExtended2-7</code></td>
</tr>
<tr>
<td>Armored Concrete</td>
<td><code>ConcreteArmoredFull</code>, <code>ConcreteArmoredThin</code>, <code>ConcreteArmoredExtended2-7</code></td>
</tr>
<tr>
<td>Carbon Composite (Large)</td>
<td><code>PlasticFullLarge</code>, <code>PlasticThinLarge</code>, <code>PlasticExtendedLarge2-7</code></td>
</tr>
<tr>
<td>Steel (Large)</td>
<td><code>HullFullLarge</code>, <code>HullThinLarge</code>, <code>HullExtendedLarge2-7</code></td>
</tr>
<tr>
<td>Hardened Steel (Large)</td>
<td><code>HullArmoredFullLarge</code>, <code>HullArmoredThinLarge</code>, <code>HullArmoredExtendedLarge2-7</code></td>
</tr>
<tr>
<td>Combat Steel (Large)</td>
<td><code>HullCombatFullLarge</code>, <code>HullCombatThinLarge</code>, <code>HullCombatExtendedLarge2-7</code></td>
</tr>
<tr>
<td>Xeno Steel</td>
<td><code>AlienFullLarge</code>, <code>AlienThinLarge</code>, <code>AlienExtendedLarge2-7</code></td>
</tr>
<tr>
<td>Alien Building</td>
<td><code>AlienFull</code>, <code>AlienThin</code>, <code>AlienExtended2-7</code></td>
</tr>
<tr>
<td>Carbon Composite (Small)</td>
<td><code>PlasticFullSmall</code>, <code>PlasticThinSmall</code>, <code>PlasticExtendedSmall2-7</code></td>
</tr>
<tr>
<td>Steel (Small)</td>
<td><code>HullFullSmall</code>, <code>HullThinSmall</code>, <code>HullExtendedSmall2-7</code></td>
</tr>
<tr>
<td>Hardened Steel (Small)</td>
<td><code>HullArmoredFullSmall</code>, <code>HullArmoredThinSmall</code>, <code>HullArmoredExtendedSmall2-7</code></td>
</tr>
<tr>
<td>Combat Steel (Small)</td>
<td><code>HullCombatFullSmall</code>, <code>HullCombatThinSmall</code>, <code>HullCombatExtendedSmall2-7</code></td>
</tr>
</tbody>
</table>
</div>
<div class="note">
<strong>Best Practice:</strong> Test the <code>replaceblocks</code> command in Single Player or on a backup save first. Since the command permanently modifies the structure, there is no built-in undo.
    </div>

