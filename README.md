For 2 ship 2 harkinian Majora's Mask Pc port v https://github.com/lightmanLP/2ship2harkinian/releases/tag/M3.1.0
Mouse support 3.1.0 for 2S2H 5.0.0+dev by lightmanLP

Majora: 3× HP in every phase (Mask 14→42, Incarnation 30→90, Wrath 40→120)

Mask: every 150 frames it shakes as a warning, then fires one of three volleys in turn: a fan of 5 aimed at you, an expanding ring of 12, or 6 orbs raining down around you. Incarnation: its pirouette sprays a two-armed spiral of orbs. Its moonwalk leaves slow drifting orbs behind it. Its energy-ball attack now throws two extra side shots with each ball. Wrath: every whip crack sends a fan of 3 bolts along the floor from the whip tip, and its spin attack flings orbs in all directions. Summoned enemies: at ¾, ½ and ¼ health, Wrath calls the Remains back into the fight as flying enemies that shoot and ram you. First Odolwa and Goht, then Gyorg and Twinmold, then all four. They die when Wrath dies. Fierce Deity: Majora takes half damage, the Mask uses its fire beam (vanilla deliberately never does against FD), and every pattern above gets bigger: fan 7, ring 16, a four-armed spiral, 5 whip bolts, and all four Remains in every wave. This has its own checkbox, so you can turn it off.

Twinmold: 2× HP

Fire breath: a long-range stream of burning fireballs, about 2,800 units. It sweeps toward you with a lag rather than snapping onto you, so you can outrun it or hide behind a ruin, which blocks it. Eruptions: every time a head bursts through the sand, a ring of fireballs rains down around the hole. After one head dies: the survivor's breath lasts longer and splits into three jets. Giant's Mask: that mode shrinks the whole arena rather than enlarging Link, so the fire scales with it and still reads as a real flamethrower against giant Link.

Odolwa: 2× HP

Fire wave: when he slashes from range, 3 flames race along the floor at you (5 when enraged). Walls stop them. Flame ring: his spin attack throws off a ring of embers. More bugs: up to 8 bugs at a time once he's enraged, instead of 5.

Goht: 2× HP

Electric mines: while running, it leaves floating balls of lightning on the track behind it for you to steer around, two side by side once enraged. Homing ball: at half health it fires its homing electric ball on its own. In vanilla it only did that after you hit it with Goron spikes. Earlier bombs: it starts throwing bombs at half health instead of a third.

Gyorg: 2× HP

Water bullets: while you're on the central platform, it bursts volleys of 3 out of the lake (5 when enraged). They lob onto the platform and can knock you back, often straight into the water.

Two bugs fixed along the way:

Majora's Mask: after the Mask turns into the Incarnation, the Remains still read the Mask's freed memory whenever they fire. That's a vanilla bug, but the summoned Remains would hit it constantly, so I fixed it.
Boss Health Multiplier: 2S2H's own option multiplies boss health using a small signed number, so stacking it on Wrath's new 120 would wrap its health around to negative. It now switches itself off while Boss HP is on.

Epona Control Overhaul

In game: it's under Enhancements > Epona, and it's on by default in Freeform mode.

Control Mode:
Tank: the normal way the games steer.
Freeform: Epona runs wherever you point the stick, relative to the camera, the same way Link moves on foot. Letting go of the stick brakes, and she never backs up by herself.
Hybrid: Freeform, but it switches to Tank while you aim in first person, like shooting the bow from horseback.
Handling sliders: turn and brake strength for each mode, plus a minimum turn speed for Freeform.
Bunny Hood Boost: Epona runs and turns twice as fast while Link wears the Bunny Hood. The hood only exists in Majora's Mask, so this option does nothing in Ship of Harkinian.
Unticking "Enable Epona Control Overhaul" gives you vanilla riding back.

Ship of Harkinian (Master Sword):

What it does: with full hearts, each normal slash throws a spinning blue-white beam of light, like A Link to the Past.
Power: it hits for exactly the damage of a Master Sword slash. It disappears when it hits an enemy, a shield or a wall.
Aiming: when you're locked on with Z, it aims up or down at the target.
Menu: Enhancements > Items > Master Sword Beam.

2 Ship 2 Harkinian (Enhancements > Items/Songs > Sword Projectiles):

Sword	When	Projectile	Damage
Gilded Sword	Full hearts	Golden crescent, fast, disappears on the first hit	3, same as a Gilded Sword slash
Great Fairy's Sword	Full hearts	Big pink spinning ring, slower, cuts through every enemy in its path	4 to each enemy
Fierce Deity	Any health	Glowing orb, the fastest, bursts on impact and hits everything around it	6, plus 4 from the burst

The Gilded Sword crescent is the same power as the Master Sword beam in Ocarina of Time: each hits for its own sword's slash damage.

Fierce Deity: the orb replaces the old sword beam, so the two can't look alike. It fires on any normal slash, even without Z-targeting.
Fierce Deity magic: each orb costs 1 magic, the same as the old beam. With an empty magic meter, no orb comes out.
