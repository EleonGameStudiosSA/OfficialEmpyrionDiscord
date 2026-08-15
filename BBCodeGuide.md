---
layout: default
title: BBCode Tags for Device Names
---



<div class="rule">
<h3>BBCode Support</h3>
<p>
            Device names in the Control Panel support a selection of BBCode formatting tags.
            These tags allow you to organize and color-code devices for easier navigation.
        </p>
</div>
<div class="rule">
<h3>Text Formatting Tags</h3>
<div class="subsection">
<h4>Basic Formatting</h4>
<table>
<thead>
<tr>
<th>Tag</th>
<th>Effect</th>
</tr>
</thead>
<tbody>
<tr><td><code>[b][/b]</code></td><td>Bold</td></tr>
<tr><td><code>[i][/i]</code></td><td>Italic</td></tr>
<tr><td><code>[u][/u]</code></td><td>Underline</td></tr>
<tr><td><code>[s][/s]</code></td><td>Strikethrough</td></tr>
<tr><td><code>[sup][/sup]</code></td><td>Superscript</td></tr>
<tr><td><code>[sub][/sub]</code></td><td>Subscript</td></tr>
</tbody>
</table>
</div>
</div>
<div class="rule">
<h3>Color Tags</h3>
<div class="subsection">
<h4>Base Color</h4>
<table>
<thead>
<tr>
<th>Tag</th>
<th>Effect</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>[c][/c]</code></td>
<td>Sets the text base color to white instead of the default light-blue.</td>
</tr>
</tbody>
</table>
</div>
<div class="subsection">
<h4>Hex Colors</h4>
<table>
<thead>
<tr>
<th>Tag</th>
<th>Effect</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>[######][-]</code></td>
<td>Apply a 6-digit RGB or 8-digit RGBA hex color.</td>
</tr>
<tr>
<td><code>[##]</code></td>
<td>Set alpha (transparency) using a 2-digit hex value.</td>
</tr>
</tbody>
</table>
<p>
                The closing tag for hex colors is <code>[-]</code>.
            </p>
</div>
</div>
<div class="rule">
<h3>How Color Mixing Works</h3>
<div class="subsection">
<h4>Using <code>[c]</code> with Hex Colors</h4>
<p>
                The default device-name color is light blue. Hex colors are multiplied against this base color,
                so they will inherit a blue tint unless you reset the base color first.
            </p>
<p>
                For pure white, use:
            </p>
<pre><code>[c][FFFFFF]My Device[-][/c]</code></pre>
<p>
                If you omit <code>[c]</code>, the text will keep the default light-blue tint, which can be useful
                if you want to save a few characters.
            </p>
</div>
</div>
<div class="rule">
<h3>Example Formatting</h3>
<div class="subsection">
<h4>Common Examples</h4>
<pre><code>[b]Main Generator[/b]

[c][FFAA00]Fuel Tank[-][/c]

[c][00FF00][b]Solar Capacitor[-][/b][/c]

[c][FF0000]Warning[-][/c]</code></pre>
</div>
</div>
<div class="note">
<strong>Tip:</strong>
        Combining <code>[c]</code> with hex colors gives you accurate color reproduction, while skipping
        <code>[c]</code> produces a blue-tinted version that can help save characters in device names.
    </div>

