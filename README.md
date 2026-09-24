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

Minibosses (2× HP each unless noted)
Gekko & Snapper: while crawling on the walls, Gekko lobs mud bubbles that knock you back. Snapper's rolling charge ends in a stomp shockwave, which you clear with a sidehop or backflip.

Gekko & Mad Jelly: the reformed jelly drops from the ceiling as a shockwave. Mini jellies hop at you instead of just crawling. Shattering the frozen jelly throws ice shards you need to shield against.
Wart: during the bubble phase, the eye glows and then fires a short sweeping laser, and bubbles launch in rings. In the charging phase, every wall slam rains bubbles down around the room.

Captain Keeta: his big slam sends a shockwave up the path and raises 2 Stalchildren near you (his soldiers). When he stops to fight, he adds a leaping spin slash.

Iron Knuckle: the overhead smash sends a shockwave forward. When the armor breaks, the pieces fly out as shrapnel. Without armor, it sometimes throws its axe like a boomerang (the axe is its own limb, so this works). While the axe is out, it's unarmed and open to attack.

Igos du Ikana & lackeys: the fire breath leaves burning patches on the floor, and the flying head spits fireballs. A lackey that falls and isn't finished with fire or light gets back up faster. Once Igos is at half health, the lackeys fight in tandem (one blocks while the other flanks).

Garo Master: its flaming swords send fire waves along the floor. The teleport-drop lands in a ring of flames. At half health it calls in 2 Garos. The death explosion throws embers first, as a warning.

Gomess: bats break off the swarm to dive at you in waves. The spin attack throws the scythe out and back. At low health it fades out and reappears behind you.

Eyegore (about 2× harder)
16 HP instead of 8.
Laser: 5 shots that step toward you with a lag, instead of 3 at fixed angles. Once enraged, the last shot becomes a 2-second beam sweeping the floor. The Mirror Shield still cancels it.
Slam: sends out a shockwave ring, and rubble rains down around you.
Enraged (half health): its eye glows red and it walks 25% faster. It slams twice, turning to face you for the second slam. It now also hits behind itself, so standing behind it is no longer a safe spot.
New opening: an arrow in the eye while it's charging the laser makes it stagger. How long its eye stays open to damage after a slam or stun doesn't change.

Deep Python (pick one below)
A. Burrow hunters (safe look): 8 HP instead of 4. They lunge and bite without needing to grab you first, and they spit water shots. When hurt, a python retreats and can burst out of a different, emptied burrow later, so they hunt you through the rock. The last one alive becomes a real miniboss: miniboss music, 3× HP, and bigger attacks.
B. Free swimmers (experimental): they leave the burrow and circle you in open water. The model was built to stay half inside a hole, so I'd fake a tail by tapering the back segments and add a swimming wave in code. I can't see the result rendered here, so it may look odd until you test it.

Them (the ranch aliens):
They weave from side to side as they come, and about half of them blink out for a moment on the way.
Once a few have died, a bigger leader can appear. It takes two arrows and drops an extra red rupee.
Aliens near you fire slow balls of light worth half a heart.
The ball of light over the barn drops light bombs near you about every 10 seconds, with the landing spots marked on the ground.
They still reach the barn at exactly the same time, so winning and losing work as before.

More encounters:
Enemies sometimes bring companions of their own kind.
In some areas you also get a local creature: Keese with Chuchus on the night fields, Dragonflies over the swamp Octoroks, Ice Keese with Eenos, Bubbles with Ikana's Stalchildren.
Random encounters sometimes send an extra: a second Dragonfly in the swamp, or a second Garo who drops in behind you.
In dungeons, companions only appear in rooms where no door or chest waits on killing every enemy.
Boss rooms, minigames, the Moon, Spider Houses, grottos and Secret Shrine are left alone.

Regular enemies (mostly new behavior, not more HP)
Big Octo: fires spreads of Octorok rocks at range. After a hit it dives and resurfaces somewhere else in its pond. At half health it calls up 2 Octoroks.
Boe (black & white): groups pounce together. 4 or more that touch merge into a Big Boe (twice the size), which splits back into small ones when hit. A White Boe's pounce can freeze you briefly.
Dinolfos: the fire breath sweeps side to side. It tail-spins if you get behind it. Pairs work together: one breathes fire while the other jump-slashes from the side.
Eeno: big Eenos roll a snowball that grows as it rolls. Small ones throw from three sides at once. Merging into a big one slams down a snow shockwave.
Wolfos / White Wolfos: they feint a lunge and then sidestep. They circle instead of attacking into your raised shield. One howl per fight calls in a second Wolfos. A White Wolfos slash can freeze you.
Death Armos: its crash-down sends a shockwave ring. When one spots you, it wakes the others nearby. Its death dive now homes in on you before it explodes.
ReDead / Gibdo: if not finished with fire, they get back up once. A ReDead scream calls the others in the room. A burned hostile Gibdo loses its bandages and keeps fighting as a ReDead.
Poe Sisters: each sister gets her own trick. Meg's clones all attack at once. Jo leaves fire trails. Beth throws a blue flame that freezes. Amy vanishes and reappears behind you. Their HP stays the same because of the 3-minute timer.

Random encounters

Enemies gain companions only from their own region:

Swamp: Dragonflies, Octoroks, Mad Scrubs.
Mountains: White Wolfos in pairs; Eenos arriving with White Boe.
Great Bay: Skullfish packs led by a Desbreko; bigger Leever rings.
Ikana: the Garo's Mask ambush becomes a chain of 2–3 Garos; bigger Stalchild groups; more Stalchildren during Keeta's chase.

Elites: about 1 enemy in 20 is bigger, sparkles gold, has double health and drops something better.
Final Day frenzy: companions are twice as common on the third day and three times as common after midnight. After midnight elites are also twice as common.


