---
layout: default
title: Structure Decay & Wipe Timers
---



<div class="section">
<div class="rule">
<h3>Structure Cleanup Timers</h3>
<p>
                Empyrion includes two cleanup timers in <strong>gameoptions.yaml</strong> that
                automatically remove abandoned player-built structures after they have not been visited
                for a specified period.
            </p>
</div>
<div class="rule">
<h3>DecayTime</h3>
<div class="subsection">
<h4>Current Setting: 24</h4>
<p>
                    Removes player-built structures that either:
                </p>
<ul>
<li>Have no core, or</li>
<li>Contain fewer than 10 blocks.</li>
</ul>
<p>
                    This timer activates after the structure has not been visited for
                    <strong>24 hours</strong>.
                </p>
<p>
                    Setting this value to <strong>0</strong> disables this cleanup.
                </p>
</div>
</div>
<div class="rule">
<h3>WipeTime</h3>
<div class="subsection">
<h4>Current Setting: 0</h4>
<p>
                    Removes any player-built structure after it has not been visited for the configured time.
                </p>
<p>
                    Since the current value is <strong>0</strong>, this automatic wipe is disabled.
                </p>
</div>
</div>
<div class="rule">
<h3>How the Timer Resets</h3>
<div class="subsection">
<h4>Physical Interaction Required</h4>
<p>
                    The visit timer only resets when a player physically walks onto or touches the structure.
                </p>
<ul>
<li>✔ Walking onto a Base (BA)</li>
<li>✔ Entering or touching a CV</li>
<li>✔ Entering or touching an SV</li>
<li>✔ Entering or touching an HV</li>
</ul>
</div>
</div>
<div class="warning">
<strong>Important:</strong>
            Opening a structure through the <strong>F4 Logistics Menu</strong> does <strong>not</strong> reset the visit timer.
            You must physically visit the structure for the timer to refresh.
        </div>
<div class="note">
<strong>Remember:</strong>
            If you're relying on remote logistics to manage your base, make sure to periodically visit your structures in person.
            Remote access alone will not prevent cleanup timers from continuing to count down.
        </div>
</div>

