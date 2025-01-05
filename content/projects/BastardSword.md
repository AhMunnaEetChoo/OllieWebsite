+++
title = "Bastard Sword"
aliases = ["bastard sword", ]
+++

A prototype concept developed in pico-8. Action games rarely lean into physics simulations for combat. Opting for controlled fixed animation sequences and predefined 'hit boxes'. The idea behind Bastard Sword was to find fun and 'game feel' with some simple 2D physics.

The main character and sword tip are treated as particles with their own individual weight connected via stiff rod. Applying impulses over a few frames on the sword tip perpendicular to this connection produced the nice swing you can see in the gifs.

<p>
<center>
<img src="/images/ss_0.gif" alt="particles!">
</center>
</p>
Initial experiments. This is a single frame impulse applied to the sword tip. Snappy and immediate! The weight ratio here is roughly 10:1 player to tip.

<p>
<center>
<img src="/images/bs_collision.gif" alt="collision!">
</center>
</p>
Modelling the enemy with a circular hitbox momentum can be transferred by calculating a line-circle intersection and inferring the velocity at impact point.

<p>
<center>
<img src="/images/bastardsword_7.gif" alt="enemies!">
</center>
</p>
Adding juice! Screen shake, time-slow on hit (not stop!), particles, health bars. All that good stuff.

Would love to continue with this project when I have space. 