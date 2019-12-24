This file contains 3 sets of SR files, all usable offline.

SR Modded is a modded SR, the main focus of this file pack. Contains new classes, weapons, compo types and stages. 

SR Offline is the canonical SR edited to be playable offline.

SR Wiped has most weapons, all compos and most stages removed. Only starting weapons and Opening Street remain.

Auto save not available. Use Get/Set for manual saving.

Open the HTML file within each folder using Firefox/IE11 to use. For Chrome, follow the instructions on the Mod's page in DB Wiki.

Please do NOT redistribute this package regardless of its integrity. 

If you got into any trouble from this file and you are NOT downloading from the original link at Dan-Ball wiki I will DEFINITELY NOT help.

All credits to ha55ii, the original creator of Stick Ranger. Please support ha55ii by going to dan-ball.jp and play his games, including the original SR and many other games.

Credits
--------------------------------------------------
ha55ii, the original creator of Stick Ranger, for creating the game at first.
Samuel17 on DB/FB wiki for the idea of Hammerer.
HankGuideDude on DB/FB wiki for the idea of Dusts and Predator, and creating the Exchanger icons.
Omega16 on DB/FB wiki for the idea of Blood Lust 7.
stixx44 on DB/FB wiki for the idea of Midas Touch 7, who proposed for a Sword version initially. Also he proposed the revival of Satan's Card 1, now made LV 6.
RadiantDarkBlaze on DB/FB wiki for the idea of Magic Amp's Card, the 1st Challenge Zone Boss, ideas for several new weapons in Hell A and reporting several bugs for fixing.
NNW on DB/FB wiki for the idea of Fire Soul 5 and Thunder Soul 5's attacks, which was first made as LV7 versions.
RedHardcore on DB/FB wiki for various ideas including inspiration of 5 of the Desert A special weapons, namely Flame Knuckle 4, Flame Chain 4, Frostbite Staff 4, Freeze Circle 4 and Ice Mallet 4 based on his Bloodcage stage idea where a "buffed" SSh Boss can be found and giving out weapons with SSh Boss-like attacks, and the LV 5-6 Pierce's/Explosion's/Reflection Card. In addition, the renaming suggestion of the canonical Rail Gun 7 was this person's idea.
Aeinstein on DB/FB wiki for (passively) providing motivation on Rubber's Card revival.
1X3B on FB wiki for the Wizard idea.
Majorlee on DB wiki for proposing the implementation of Quick SP investment algorithm.
Poisonshot on DB/FB wiki for a bug fix.

IMPORTANT NOTICE
--------------------------------------------------
Saves from each set of SR are not compatible. Do NOT use any code from one version in another. (e.g. SR Offline in SR Modded)

History
--------------------------------------------------
SRM ver7.3 - 18/03/2018
New Stages. (Challenge Zone Stages)
First Challenge Zone Boss now gives the same gold drop as the others.
Removed SR Wiped 17.4.
Hammerer Knockback tweaked, should be better at actually slamming stuff away now.
A minor QOL update for those who want to refight the Final Boss after beating the Final Boss Stage at least once.
Reintroduced the Angel + Critical's Card "bug", due to me finding proof that this "bug" is decided to be kept (and will not be fixed) by ha55ii.
Zooming with the browser now works similarly to the updated DB site (Nearest Neighbour).

NOTE: For those wanting to utilize the Angel + Critical's Card combo, the damage cap is 2^31-1 = 2147483647. Any higher damage will suffer from overflowing.


SRM ver7.2 - 01/01/2018
New Stage. (Challenge Zone Stage)
Fixed some documentation typo. (Credits to Hachi from DBCB)
Another Vampire's Card rework, restoring the original % heal with nerfs and new limitations.


SRM ver7.1a - 19/11/2017
Bug Fix: Fixed bug on older browser versions not able to open the game by replacing instances of "**" with Math.pow() in new stat effect codes.
Dark Bomb 8 reworked: Bullet now travel straight and pierce terrain.
Hammerers now heal twice the LP per attack with Vampire's Card.

SRM ver7.1 - 24/09/2017
(MOD ONLY) Stat effect changes for several Classes. Staves of LV 7+ were buffed.
Darkness PATs and BATs now show as X%-Y% instead of X-Y.
Base Knockback power are now shown for Hammers.
First Challenge Zone Boss size reduced.
Second Challenge Zone Boss gold drop reduced.
Vampire's Card nerfed.
New Compo Item (Vampire's Card 7)
War Cry now lasts only 25% as long.

Note: The nerfed AT Aura on Priests will cause the aura color follow AT Aura power (sum of all aura producing %s) instead of total STR invested.

Stat Changes:
Boxer STR, Sniper DEX, Magician MAG, Whipper STR, Angel STR: SP invested are twice as powerful after every 100 SP invested. Does not apply to previously invested SP and stacks as SP reaches higher multiples of 100. 
Example: Boxer STR gains +1/2 Min&Max AT before 100 STR. Further investments of STR gives +1 Min&Max AT after reaching 100 STR and +2 Min&Max AT after 200 STR.
Gladiator STR/DEX and Dual Swordsman STR/DEX: STR/DEX investments gives doubled DPS increment after every 100 total SP invested to STR and DEX. Pure STR/DEX will only increase Max/Min damage while at mixed STR/DEX this doubled DPS increment might be reflected on both Min&Max AT after 100 total SP on STR and DEX.
Priest STR: SP invested on STR is half as powerful after 100 STR (AT Aura +0.5%) and 1/3 times as powerful after 300 STR (AT Aura +0.333%).
Predator MAG: War Cry strength is no longer dependent on MAG but dependent on weapons. Weapons with War Cry available will show their War Cry strength.


SRM ver7.0 - 09/09/2017
First Challenge Zone Boss stats tweaked again under Idea owner's request. EXP/Gold payout further increased.
New Stage. (Challenge Zone Stage)


SRM ver6.9a - 16/08/2017
Bug Fix: Stone Circle 3 wrong buy/sell value. (Credits to Poisonshot from DB/FB wiki)

SRM ver6.9 - 16/08/2017
All enemies in the Mod now has a chance to be Shiny.
Dark Cave weapons nerfed: All Darkness damage from these weapons reduced by 90%.
First Challenge Zone Boss LP and attack stats tweaked under Idea owner's request. EXP payout increased.
(MOD ONLY)Fixed possible blockage of LP display by enemy icon on enemies with 8+ digits of LP.
(MOD ONLY)Hell Castle Boss now only gives 19999 Max EXP instead of 99999.


SRM ver6.8 - 13/08/2017
(MOD ONLY)Bug fix: Crash when receiving EXP that leads to more than 1 LV ups. (e.g. Killing HCa Boss with several Iron Medals.)
(MOD ONLY)Bug fix: Active Anger Crown effect not removed when a save is loaded. 
(MOD ONLY)Minor tweak in Book (GOLD -> $$$).
(MOD ONLY)Team LV hard cap further increased to 151. Soft cap maintains at (LV of strongest enemy available + 10).
New Map Area and Stages, named Challenge Zone, unlocked after defeating the Final Boss.

Note 1: Fixing of the LV up Bug leads to the following Anger Crown changes in the Mod: For X LVs gained at once, The yellow shade lasts for (2.4*X)s, X lasers are spawned per character, and the shuriken effect lasts for (2.4*X-0.6)s.
Note 2: No documentations about the Final Boss and anything beyond it will be given.


SRM ver6.7c - 10/05/2017
Bug Fix: Crowns should now display correctly in SR Offline (Credits to RadiantDarkBlaze from DB wiki)

SRM ver6.7b - 16/04/2017
Bug Fix: Incorrect enemy LP bar display with the new Crown. (Credits to RadiantDarkBlaze from DB wiki)
Electric Rod 10 projectiles now spread very slightly; this should have close to zero effect on weapon strength.

SRM ver6.7a - 03/04/2017
Bug Fix: Scorching Beam 8 wrong buy/sell value. (Credits to Luigge from DB wiki)

SRM ver6.7 - 02/04/2017
SR Offline updated to ver18.9.
SR Modded updated with new changes in ver18.9.

Note: In SR Modded the Restart Mode only activates if you have the new Crown from the new Final Boss. This displays a + sign next to the "NEW GAME" button in the mod. It will still transfer any Crown to the new game.


SRM ver6.6 - 26/02/2017
SR Offline updated to ver18.8.
SR Modded updated with new changes in ver18.8.


SRM ver6.5 - 14/02/2017
Damned Hammer 8 BAT attack mode changed; the weapon should now work more efficiently than before.
Explosion Mjolnir 10 and Explosion Energy Whip 10 BAT undergoes aesthetic changes. No effect on the weapons' power.
(MOD ONLY) Tweaked positioning of Gold drop/EXP detail on Enemy LP bar after purchasing the Book page.
(MOD ONLY) Cavern effects no longer light up attack projectiles/residues from characters.


SRM ver6.4 - 04/02/2017
Stage addition. (Palace)
Unified residue hitbox sizes for Dec Poison 9 and Sept Toxic Shot 10: the former has larger hitbox while the latter has reduced hitbox size.
Triple Inferno 9 BAT increased from 45-60 to 48-64.
Quint Flare Shot 10 BAT reduced from 24-40 to 24-32.
Charge Halo 10 residue lifespan reduced from 1.2s to 0.4s.
Inferno A location changed but is still only linked from Inferno 2.


SRM ver6.3a - 27/01/2017
Actually updated SR Offline to ver18.7. 

SRM ver6.3 - 27/01/2017
SR Offline updated to ver18.7.
SR Modded updated with new changes in ver18.7.
Stage addition. (Wasteland B)
New special weapon set in Wasteland B.
Compo Item addition. (Gambler's Card 8)
Freeze Dual Beamsword 9 PAT reduced from 24-30 to 22-28.
Long Viral Blowgun 10 BAT buffed from 21-34 to 34-55.
Tera Exp Staff 10 AT increased from 24-40 to 40-60.
Guide's Card 8 buffed from providing +80 Guide Range to +100.
Red Boss Smiley Tree (WL4) AT Guide Range increased from 80 to 100.
(MOD ONLY) Changed the "END" word in Hell Castle's sign.


SRM ver6.2 - 20/01/2017
Stage addition. (Wasteland 8, Closing Street)
42nd Weapons addition. (Sonic Gauntlet 10, Frozen Broadsword 10, Quint Flare Shot 10, Holy Light 10, Tera Exp Rod 10, Homing Laser Storm 10, Explosion Energy Whip 10, Charge Halo 10, Toxic Dual Beamsword 10, Charge Mjolnir 10, Scorching Blowgun 10, Glacier 10)
Compo Item addition. (LV8 Cards)
Dec Poison 9 colour changed.
Scalding Ice Flare 9 Slow effect strengthened from 45% to 50%.
Absolute Zero 10 BAT production rate reduced from 15% to 12%.
Diamond Shot 10 AT increased from 480-720 to 600-800.
Mega Thunderstorm 10 AT/BAT increased from 1-222 to 1-444, BAT production rate reduced from 20% to 10%.
Grey Smiley Tree (WLA) AT reduced from 4-5 to 2-4.
Red Big Diamond Block (HC5) is now remade as Red Diamond Tree. No other stats were changed.
Red Boss X Walker (HC6) projectile trajectory and visual size tweaked. Projectile power remain unchanged.
Blue Coconut Germ (DL) LP reduced from 150000 to 120000.
Pink Roundhead Block (DL) LP reduced from 300000 to 240000.
Yellow Gel Eel (DL) no longer has stable AGI: Expected AGI is now 18.98.
Enemies in Dried Lake gives increased Gold drop.
(MOD ONLY) Cavern effects redrawn: this should further reduce lag in Cavern stages but effect may not be as good looking. There is an extra mag.gif file named "laggy cavern edition" which is the original edition and you can swap this file with the default mag.gif if you think the original effects work better.


SRM ver6.1 - 15/01/2017
Stage addition. (Wasteland 7, Hill Country 6, Dried Lake)
41st Weapons addition. (Spark Gauntlet 10, Flame Broadsword 10, Diamond Shot 10, Meteor Storm 10, Impact Rod 10, RPG-7 10, Poison Energy Whip 10, Quick Halo 10, Spark Dual Beamsword 10, Explosion Mjolnir 10, Long Viral Blowgun 10, Mega Thunderstorm 10)
Compo Item addition. (LV8 Medals, LV8 Spirits, LV8 Souls, LV8 Exchangers, LV8 Distributors)
Thunder Mjolnir 9 BAT increased from 1-149 to 1-222.
Fire Mjolnir 9 BAT increased from 50-80 to 80-100.
M40 9 projectile speed increased.
Thorn Mjolnir 9 BAT increased from 100-120 to 120-200.
Electric Rod 10 AT reduced from 1-39 to 1-33, Projectile count increased from 9 to 10.
Ice Dual Beamsword 10 wrong AGI value corrected.
Poison Mjolnir 10 BAT drcreased from 54-72 to 48-72, splashing residue hitbox size reduced.
Glacial Blowgun 10 BAT increased from 64-72 to 128-144, BAT Projectile count reduced from 20 to 10.
Needle Gauntlet 10 attack mode changed.
Absolute Zero 10 BAT projectile production rate reduced from 20% to 15%.
Grey Boss Roundhead Snake (WLA) Gold Drop Reduced from 9999 to 9990.
Red Big Diamond Block (HC5) and Red Boss Diamond Block (HC5) Ice Resistances no longer reduces damage.
(MOD ONLY) Multiple SP can now be invested quickly by holding your mouse click on the desired stat. (like the UP button from Monster Box)

Note: I am not sure if the SP investment tweak will cause any bugs on all sorts of button clicking.


SRM ver6.0 - 12/01/2017
Stage addition. (Hill Country 5)
40th Weapons addition. (Needle Gauntlet 10, Miracle Lightsaber 10, Trigintuple Arrow 10, Avalanche 10, Toxic Rod 10, Intense Laser Gun 10, Thorn Energy Whip 10, Power Halo 10, Long Dual Beamsword 10, Iron Mjolnir 10, Long Dense Blowgun 10, Absolute Zero 10)
Scorching Beam 8 AT reduced from 20-30 to 12-18.
Long Broadsword 10 Range increased from 55 to 60.
Diamond Dust 10 projectile spawning area increased for larger coverage, Freeze Time increased from 0.5s to 0.6s.
Ghost Flame 10 icon corrected, AT reduced from 40-60 to 24-36.
Satan's Card 6 effect AT increased to 9999999 to catch up with increased LP in new stages.
Red Demon Snake (WL5) and Cyan Roundhead Spider (WL6) projectiles tweaked to ensure they can hit characters from its intended range.
Cyan Roundhead Spider (WL6) EXP increased from 750 to 1000.


SRM ver5.9 - 10/01/2017
Stage addition. (Wasteland 4, Wasteland 5, Wasteland 6, Hill Country 4)
39th Weapons addition. (Freeze Gauntlet 10, Long Broadsword 10, Sept Toxic Shot 10, Diamond Dust 10, Electric Rod 10, Milkor MGL 10, Ice Energy Whip 10, Thorn Halo 10, Ice Dual Beamsword 10, Poison Mjolnir 10, Glacial Blowgun 10, Ghost Flame 10)
Compo Item addition. (Quick's Card 6, LV5-7 Spirits, LV8 Jewels, LV8 Charms)
Mossberg 590 9 drop rate reduced.
Molten Rod 9 AT reduced from 24-36 to 24-32.
Thunder Dual Beamsword 9, Poison Dual Beamsword 9, and Fire Dual Beamsword 9 PAT reduced from 24-30 to 22-28.
Forest 7 Purple Boss Cap Mushroom slightly buffed (Poison Time increased from 1.32s to 1.98s).
Body Colour of Cyan Gel Digger (WL1), Grey Smiley Tree (WL3) and Purple Boss Smiley Tree (WL3) changed.
Changed icon for Souls.

Note: The Save Updater from package ver5.6 will be removed from this update. 


SRM ver5.8a - 06/01/2017
Toxic Halo 9 drop rate corrected. (The drop rate was wrongly set to 1/5 of the intended rate)
Frost Rod 9 colour changed.
Wasteland A Boss screen enemy position setup changed.

SRM ver5.8 - 05/01/2017
Stage addition. (Wasteland A)
New special weapon set in Wasteland A.
Magical Blasts 6 renamed as Magical Blast 6.
Soul Seeker 7 BAT increased from 30-45 to 40-60.
Holy Realm 7 now only heals other characters by 4 LP per swing instead of 5 LP.
Electric Shot 8 BAT increased from 1-44 to 1-55.
Infernal Blaze 9 AT increased from 2-6 to 4-6, Burn rate increased from 5% to 8%, projectile count reduced from 60 to 30.
Electrocution 9 projectile lifespan reduced from 1s to 0.8s.
Thunder Mjolnir 9 BAT increased from 1-99 to 1-149. BAT Projectile count reduced from 9x9 to 6x9.
Freeze Mjolnir 9 BAT projectile appearence changed, BAT increased from 40-60 to 60-90, BAT Projectile count reduced from 8x9 to 6x8.
Venom Rain 9 projectiles now spawns over a 3s interval instead of 2s and has a slightly wider projectile spawning range.
Mana Storm 9 AT increased from 120-160 to 240-320, projectile count reduced from 60 to 30. 
(MOD ONLY) Increased maximum allowable projectiles on screen to 10000. Do expect lag at more than 1000 projectiles though.
(MOD ONLY) Cavern effects alpha colouring removed: this should reduce lag in Cavern stages.


SRM ver5.7 - 30/12/2016
Stage addition (Wasteland 2, Wasteland 3)
38th Weapons addition. (Poison Gauntlet 9, Ice Broadsword 9, Sext Diamond Arrow 9, Electrocution 9, Frost Rod 9, M40 9, Thunder Energy Whip 9, Ice Halo 9, Fire Dual Beamsword 9, Freeze Mjolnir 9, Spark Blowgun 9, Mana Storm 9)
Compo Item addition (LV8 Dusts)
Holy Light Flail 6 PAT increased from 6-23 to 6-24.
Cold Rod 9 AT increased from 20-30 to 24-32.
Bug fix: The main needle of Frigid Blowgun 8 should now correctly deal Ice damage without splash instead of Physical damage with splash.
Bug fix: Incorrect display value for Satan's Card 6 effect on Green Smiley Walker (OS), Blue Skull Bat (HC2) and Green Big Diamond Tree (H2).
Bug fix: Incorrect Knockback behaviour for Inverted Trees and Blocks.


SRM ver5.6 - 16/12/2016
SR Offline updated to ver18.6.
SR Modded updated with new changes in ver18.6.
Stage addition (Forest 8, Wasteland 1)
37th Weapons addition. (Mach Gauntlet 9, Thunder Broadsword 9, Triple Inferno 9, Infernal Blaze 9, Long Diamond Rod 9, Mossberg 590 9, Fire Energy Whip 9, Long Halo 9, Poison Dual Beamsword 9, Fire Mjolnir 9, Combat Blowgun 9, Venom Rain 9)
Compo Item addition (LV8 Crystals)
Cavern 9 Red Roundhead Stickman and Red Boss Roundhead Stickman gain Fire resistances.
Fixed the wrong selling price of Blue Crystal 7.
(MOD ONLY) Gold cap raised from $9999999 to $99999999 again.

Note 1: In the modded version Volcano is linked from Settlement instead of Hell Castle.

Note 2: Due to the Gold cap increment, saves from ver5.5 will NOT be compatible with saves from ver5.6 and vice versa. A save updater is included for converting ver5.5 saves to be usable on ver5.6. For your information, I revoked this modification before due to an oversight of get-set mechanism not saving Gold amounts beyond 16777216 (2^24) correctly.


SRM ver5.5a - 08/12/2016
Compo Item addition (Ring's Card 7)
Forest 7 Purple Boss Cap Mushroom nerfed for being too OP.
Railgun 4 is now Type Physical instead of Type Fire, while retaining its enemy piercing properties.
Rapid Explosion 9 Range increased from 150 to 165.
Scalding Ice Flare 9 Range increased from 165 to 180.
Cold Rod 9 AT increased from 18-24 to 20-30.
MP5 9 AT increased from 20-40 to 24-48.

Note: If you have Railgun 4s with Ruby/Garnet/Spinel equipped, please replace these Jewels with random compo items in ver5.5 or your save will not work on ver5.5a.

SRM ver5.5 - 06/12/2016
Stage addition (Cavern 11, Forest 7)
36th Weapons addition. (Fire Gauntlet 9, Fire Broadsword 9, Dec Poison 9, Icicle Blast 9, Molten Rod 9, MP5 9, Stone Energy Whip 9, Thunder Halo 9, Thunder Dual Beamsword 9, Thunder Mjolnir 9, Horror Blowgun 9, Scalding Ice Flare 9)
Compo Item addition (LV5-7 Charms, LV8 Stones)
Light Rod is now LV6 instead of LV8. None of the other stats were changed.
Ice Soul 6 drop rate increased.
Static Electricity 7 now displays its full name in game.


SRM ver5.4b - 03/12/2016
Bug fix involving the $10M starting Glove price that was not revoked after testing.

SRM ver5.4a - 03/12/2016
Broadsword Image changed.
Revoked the Gold Cap increment for the mod.

Note: If you have any saves with more than $9999999 gold in the gane, please spend your gold in ver5.4 until you have less than $9999999 or your save will not work on ver5.4a.

SRM ver5.4 - 02/12/2016
Stage addition (Settlement, Cavern 9, Cavern 10)
35th Weapons addition. (Thunder Gauntlet 9, Broadsword 9, Sept Gold Shot 9, Cluster Explosion 9, Cold Rod 9, Desert Eagle 9, Energy Whip 9, Fire Halo 9, Dual Beamsword 9, Mjolnir 9, Dense Blowgun 9, Rapid Explosion 9)
Compo Item addition. (Knockback's Card 6/7, Big Card 6/7)
(MOD ONLY) Gold cap raised from $9999999 to $99999999.


SRM ver5.3 - 19/11/2016
New compo items (LV7 Exchangers, Distributors and Souls)
Predator's STR now buffed to have 20% to do critical damage at +10% AT per STR.
Static Electricity 7 AT nerfed from 1-199 to 1-144.
Frostbite 8 AT nerfed from 100-120 to 80-120.


SRM ver5.2 - 11/11/2016
SR Offline updated to ver18.5.
SR Modded updated with new changes in ver18.5.
Main Mod now allows 5 different items to be dropped from the same enemy. 
(MOD ONLY) Gold drop detail added to the reformed Enemy LP bar after purchasing the Book page.
Class addition. (Wizard)
Compo Item addition (Blue Crystal, Cobalt Medal)
Bug fix: Pink Gel Tree in CV7 was wrongly changed to a Block in mod ver5.1.


SRM ver5.1 - 04/11/2016
SR Offline updated to ver18.4.
SR Modded updated with new changes in ver18.4.
New Stage (Dark Cave)
New special weapon and compo item set in Dark Cave.
Blazing Cestus 8 BAT Burn Rate buffed from 20% to 25%.
All weapon sets on extra stages of the mod gets increased drop rates.
Seaside A Boss now gives 3000 EXP instead of 2000.

Known Bugs: Killing the Hell Castle Boss with Iron Medals will crash the game if the EXP gain turns out will increase character LV by 2 or higher at once. This occurs in BOTH canonical and modded versions.


SRM ver5.0 - 28/10/2016
SR Offline updated to ver18.3.
SR Modded updated with new changes in ver18.3.
New weapons (Toxic Dual Spikesword 8, Charge Sledgehammer 8, Nitro Blowgun 8)
New compo item (Rubber's Card)
The Fallen 7 colour changed.
Magma Blowgun 6 main Bolt attack lifespan reduced from 4s to 3s.
Thor Blowgun 8 projectile width reduced.
Fire Mallet 3 BAT no longer deals splash damage.
Thunder Maul 5 BAT no longer deals splash damage.
Fire Sledgehammer 7 BAT increased from 22-33 to 25-40 but no longer deals splash damage.
Explosion Mallet 4 BAT increased from 200-300 to 300-500.
Explosion Maul 6 BAT increased from 500-800 to 600-900.
Explosion Sledgehammer 8 BAT increased from 240-320 to 240-360.
Jonquil Dust 7 drop holder changed.
Added attack data to descriptions of Spirits and Souls.
Formatting of attack data of Dusts Changed.
Description changes for compo items concerning both projectiles and residues, such as Garnet and Extension's Card.
Changed LP/STR/DEX/MAG display on HUD. 
Changed Warcry display on HUD for Predators with MAG (now its value shows as 0.6*MAG instead of 1*MAG to reflect the decreased power from the original idea)
Added documentations for Main Weapons of all new Classes.
Bug fix: Incorrect Projectile Lifespan increment for Reflection/Slider's Card 5 and 6.


SRM ver4.9 - 01/10/2016
SR Offline updated to ver18.2.
SR Modded updated with new changes in ver18.2.
Class addition. (Predator)
New compo item (Pierce's Card 7, Explosion's Card 7, Reflection Card 7, Flare's Card 7, Expansion's Card 7, Slider's Card 7, Shredder's Card 7, Extension's Card 7)
Snowfield A enemy parameters and stage location changed.
Explosion's Card 6 and Spinel 7 drop holder changed.
Extension's Card buffed to also affect residues. Also affects similar effects on LV 5+ Reflection Card and Slider's Card.
(MOD ONLY) Shop interface made slightly wider.
(MOD ONLY) Island Shop now sells LV 1-4 Medals.

Notes: There might be bugs and balancing issues on the Predator. Any bug reports/balancing suggestions are highly appreciated.


SRM ver4.8 - 09/09/2016
SR Offline updated to ver18.1.
SR Modded updated with new changes in ver18.1.
Bug fix: Messed up HUD stat display when hovering over a Gun.
New compo item (Spinel 7)


SRM ver4.7 - 02/09/2016
SR Offline updated to ver18.0.
SR Modded updated with new changes in ver18.0.
(MOD ONLY) Diamond 1 now has the same buy/sell cost as other LV1 Jewels.


SRM ver4.6 - 26/08/2016
SR Offline updated to ver17.9.
SR Modded updated with new changes in ver17.9.
HTML interface made more similar to the DB site.


SRM ver4.5 - 19/08/2016
SR Offline updated to ver17.8.
SR Modded updated with new changes in ver17.8.
New stage. (Hell A)
New special weapon set in Hell A.
New weapons (Spark Dual Spikesword 8, Explosion Sledgehammer 8)
New compo item. (Focus's Card 7)
Holy Realm 7 colour changed.
Spark Dual Saber 6 BAT buffed from 1-66 to 1-88.
Bug fix: Incorrect AGI values on Gunners with negative DEX. (Thanks to RadiantDarkBlaze for reporting this bug)


SRM ver4.4 - 12/08/2016
SR Offline updated to ver17.7.
SR Modded updated with new changes in ver17.7.
Ice Mallet 4 colour changed.
Freeze Sledgehammer 7 Freeze time reduced from 1s to 0.5s.


SRM ver4.3 - 05/08/2016
SR Offline updated to ver17.6.
SR Modded updated with new changes in ver17.6.
(MOD ONLY) LV4+ Lightsabers name changed for better identification.
Toxic Chakram 6 BAT raised to 6-16 from 6-6 but residues now decelerate after spawning.


SRM ver4.2 - 29/07/2016
SR Offline updated to ver17.5.
SR Modded updated with new changes in ver17.5.
SR Wiped updated to ver17.4 and is now based on the modded version.
SR Wiped (BATPAT BETA) removed.
(MOD ONLY) Quint Gold Arrow 8 Icon changed.
Bug Fix: Incorrect AT values on Magicians with negative MAG.

NOTE: In my mod Character LV's hard cap is 141 instead of 99, so any enemy with LV>=90 allows player level to reach 100 or above unlike in canonical SR where you are ultimately stuck at LV 99.


SRM ver4.1 - 27/05/2016
SR Offline updated to ver17.4.
SR Modded updated with new changes in ver17.4.
New weapons (Ice Dual Spikesword 8, Poison Sledgehammer 8)
New stages (Snowfield A, Seaside A)
New special weapon set in Snowfield A and Seaside A.
New compo items (Focus's Card 3 and 5, Devil's Card 4)
(MOD ONLY) ONIGIRI's Card, Gold Rush Card, Zombie's Card and Satan's Card redrawn.
(MOD ONLY) New option (Stage Effect: Turn on/off mist/heat/snow effects as you wish like the mobile SR. Switches are merged into one unlike mobile SR which has individual switches.)
Desert A Book price increased to $93000.
Inferno A Book price increased to $95000.
Gluttony 7 remade and renamed as Greed 7. (See weapons description for updated details)
Ice Mallet 4 BAT increased from 24-48 to 25-50.
Hell Fire Maul 6 porjectiles now larger.
Satan's Card buffed by doubling its activation chance.
Damamge caused by Satan's Card now gives out dark red numbers.
Bug where Negative MAG did not incur usage costs on any Gun with zero shooting cost is fixed.
NOTE 1: Eashy updated the bookmarklet and it should now work properly on my mod.
NOTE 2: IMPORTANT: If you are using saves from before ver3.8 you may not be able to load the saves.


SRM ver4.0 - 08/04/2016
New compo items. (LV3-7 Dusts, Extension's Card, LV5-6 Pierce's/Explosion's/Reflection Card, Slider's Card, Shredder's Card)
Fixed incorrect parameters of Cobalt Dust 2.
Thunder Soul 4 attack mode changed to better resemble Yellow Big Coconut Snake's attack.
Characters no longer emit Dust attacks when dragged.


SRM ver3.9a - 02/04/2016
Reverted all changed for the April Fools Joke.
Reintroduced the wiped SR versions.

SRM ver3.9 - 01/04/2016
SR Offline updated to ver17.3.
SR Modded updated with new changes in ver17.3.
New compo item. (LV2 Dusts)
Dust description changed.
Removed the wiped SR versions.

Note: APRIL FOOLS! The game now runs at 5/6 FPS on both unmodded and modded version.


SRM ver3.8a - 25/03/2016
(MOD ONLY)Fixed the Angel + Critical's Card multi-critical-hit bug.

Note: The bug still exists in the canonical SR. I fixed this for the mod only.

SRM ver3.8 - 25/03/2016
SR Offline updated to ver17.2.
SR Modded updated with new changes in ver17.2.
Centred the game interface.
(MOD ONLY)Removed the "VS MODE" button from the start screen.
(MOD ONLY)Changed description of various canonical and mod-only stuff. All affected things retain the same functionality.
(MOD ONLY)Opening the Book now freezes the game screen just like when the Options Screen is open.
Improved algorithms for Dusts.
Crimson Dust 1 projectile burn rate increased from 5% to 7.5%.
Thunder Maul 5 and Fire Maul 5 MP requirement reduced from 60 to 45.
Poison Maul 6 BAT increased from 6-6 to 8-8.
Hell Fire Maul 6 BAT now more similar to Pyramid Boss's attack. 
Explosion Maul 6 BAT increased from 300-500 to 500-800.
Thunder Sledgehammer 7 MP requirement reduced from 80 to 60 but no longer deals splash damage.
Fire Sledgehammer 7 MP requirement reduced from 80 to 60, BAT reduced from 24-36 to 22-33.

Note: The 60FPS update is optional in the modded version: You can change the game FPS through the options tab. This should work properly but if any bug is noticed please report to me.
Note 2: If you use Eashy's bookmarklet in my newest version of the mod it will not work due to some changes in my code. To use it, copy the entire script from the pastebin page. Search for "class_name:reg(/,(..)=\"Stickman /)", change "\"Stickman /" into "\"Stickman;/" and paste the entire script into the console. Press enter and the script should load.
UPDATE on 10/04/2016: Eashy's bookmarklet was fixed to support the changed code. 


SRM ver3.7 - 18/03/2016
SR Offline updated to ver16.9.
SR Modded updated with new changes in ver16.9.
Thunder Dual Spikesword 7 attack mode changed, BAT reduced from 1-88 to 1-77.
New weapons (Fire Dual Spikesword 7, Freeze Sledgehammer 7)
The HUD now displays increased BAT and MP on weapons equipped with Magic Amp's Card.
Bug fix: Hammerer's Knockback stat display bug when STR <=0.
Grassland A X Walkers' projectiles now have a 0.2s delay before it can deal damage.

Note: In SR Modded Rail Gun 7 is renamed as Type 97 Rifle 7. No stats were changed.


SRM ver3.6 - 19/02/2016
(MOD ONLY)Fire weapons now display their burn rates if it is higher than zero. Spinel description changed to better explain its ability after this change.
Power Burst 7 buffed by increasing critical damage from +300% to +400%.
Hell Fire Maul 6 buffed by increasing Burn Rate from 5% to 8%.
Megahammer 5 nerfed by reducing AT from 4800-6000 to 2700-3600.

Note: Burn rate is the chance that a Fire type projectile will deal damage each frame. If this is not displayed for a weapon its attacks behaves like Physical attacks but deals Fire damage (e.g. Spread Explosion 7).


SRM ver3.5a - 17/02/2016
Changed several Hammers' Knockback Power.

SRM ver3.5 - 17/02/2016
Class addition. (Hammerer)
Bug fix: Characters no longer emit Dust attacks when dead.
Bug fix: Red/Yellow Crystals and Katana's Card should now work properly on Dual Swords.


SRM ver3.4 - 14/02/2016
(MOD ONLY)Team LV hard cap raised to 141. Soft cap maintains at (LV of strongest enemy available + 10).
(MOD ONLY)Added BAT=PAT Switch.
LV 6 Distributors drop holder changed. 
Fire Dual Saber 5 projectile homing range increased from 10 to 20.

Note: BAT=PAT Switch + Critical's Card on eligible classes (except Snipers and Gunners) are known to have delayed Critical effects on the extra projectiles assuming they are released each hit. Also the switch does not work with the Dual Swordsman's in-bound Critical's Card effect. In addition, this function may have bugs.


SRM ver3.3b - 13/02/2016
(MOD ONLY)Stabilized Dual Swordsman's attack actions.

SRM ver3.3a - 12/02/2016
(MOD ONLY)Bug fix: Darkness effect in Cavern 7.

SRM ver3.3 - 12/02/2016
SR Offline updated to ver16.8.
SR Modded updated with new changes in ver16.8.
(MOD ONLY)Changed description of various canonical and mod-only stuff. All affected things retain the same functionality.
(MOD ONLY)Switch for secondary attacks enabled on all enemy species.
(MOD ONLY)Using an integer X higher than 1 on the secondary attack switch allows one enemy to have X+1 attacks.

Note: Multiple attacks may make the AGI settings for enemies turn out inaccurate. Also multiple attacks on Mushrooms and Cacti are highly suggested to use the same min AGI and have the AGI consistency set to 1000 (Max AGI = Min AGI). Finally this feature may be bug-infested. If you encounter a bug, you can consider reporting this to me.


SRM ver3.2 - 05/02/2016
SR Modded updated with new changes in ver16.7.
(MOD ONLY)Indra Arrow 6 should now get the damage bonus from the Topaz.
Thunder Shot 4 BAT buffed from 1-49 to 1-59, BAT projectiles last half as long, spread slightly reduced.


SRM ver3.1 - 29/01/2016
SR Modded updated with new changes in ver16.5.
SR Offline reintroduced.


SRM ver3.0a - 20/01/2016
Bug Fix: Orbs + Catapult's Card did not work as expected. (Thanks to RadiantDarkBlaze for reporting this bug)
Spinel 3 drop holder changed.
Enemy AT modes 1 and 2 now support multiple projectiles.

SRM ver3.0 - 08/01/2016
SR Modded updated with new changes in ver16.4.
SR Offline temporarily removed. Will be added back when SR ver16.6 is released.


SRM ver2.9a - 07/01/2016
Bug fix: Expansion's Card was incompatible with Sonic Punch 2, Fire Sword 1, Thunder Sword 1, Ice Sword 1, Fire Great Sword 7 and Fire Dual Sword 1. The card should now be compatible and work on these weapons.

SRM ver2.9 - 05/01/2016
New compo item. (Expansion's Card)
Railgun 4 projectile appearence changed.


SRM ver2.8a - 30/12/2015
Satan's Card is now LV 6 and only available via drops. Also changed selling price of Satan's Card.
Note: The "bosses immune to Satan's Card's attack" stuff should be set up correctly by me, but if you notice an error (non-bosses immune to Satan's Card or bosses getting insta-killed) please report to me at DB/FB wiki. 

SRM ver2.8 - 30/12/2015
Desert A enemies AT nerfed.
New compo item. (Satan's Card 1)
Note: The "bosses immune to Satan's Card's attack" stuff should be set up correctly by me, but if you notice an error (non-bosses immune to Satan's Card or bosses getting insta-killed) please report to me at DB/FB wiki. 


SRM ver2.7b - 28/12/2015
Frostbite Staff 4 and Freeze Circle 4 snowflakes now decelerate as expected.
Heat Blur effects added in Desert A.

SRM ver2.7a - 27/12/2015
Railgun 4 now has doubled AT and AGI. Shooting cost is also increased to $120.

SRM ver2.7 - 27/12/2015
New stage. (Desert A)
New special weapon set in Desert A.
New compo item. (Magic Amp's Card 4)


SRM ver2.6 - 24/12/2015
New compo items (LV 5 and 6 Souls)
Dusts now available as enemy drops.
Several mistakes in documentations corrected.


SRM ver2.5 - 19/12/2015
New stage. (Grassland A)
New special weapon set in Grassland A.
New compo items. (Spinel 1-6, Flare's Card 1-6, Magic Amp's Card 2 and 6)
Time Stop 7 AT further reduced to 36-48.
Blizzard Staff 6 nerfed: Residue production decreased to Constant 6 from Constant 8.
Range of Snipers, Magicians and Priests new have a lower limit of 1.
Increased the range decrement of negative STR and DEX on Priests from 1/4 to 1/2.
Note: As I mentioned, the mod will now lag behind the online version by one update. So I will add Blood Lake to the mod when SR ver16.5 is released. Also I will no longer include my saves in the package.


SRM ver2.4b - 07/12/2015
Time Stop 7 AT reduced to 50-75 from 60-90.

SRM ver2.4a - 06/12/2015
Soul Seeker BAT increased from 20-30 to 30-45, Slow increased from 15% to 20%.
Bug fix: Angel's body colour when equipped with The Fallen 7.

SRM ver2.4 - 06/12/2015
Former DIY Inferno 3 reintroduced as Inferno A. Unlocked by beating Inferno 2.
Dual Spikesword 7 AT changed from 80-125 to 80-120. Critical chance and critical damage unchanged.
New special weapon set added to Inferno A.
Soul related bugs fixed - should work properly on all eligible classes.
Soul activation chances changed. Doubled chance of activation for Gladiators and Whippers.
Bug fix: Code for LP increment by White Stones, Zombie's Cards and Ring's Cards accidentally removed in last revision.


SRM ver2.3 - 04/12/2015
SR Offline updated to ver16.3.
SR Modded updated with new changes in ver16.3.
Former DIY Inferno 3 temporarily removed - Poison Dual Spikesword drop holder changed to Purple Triangle Cactus in Inferno 2. 
NOTE: Due to heavy internal code changes from the optimization updates, there may exist slight discrepancies compared with the previous version and new bugs may exist.


SRM ver2.2 - 02/11/2015
New Compo Items (Ice Souls)
Thunder Soul 4 buffed to deal 1-88 AT per projectile.
Bug fixes:
Toxic Dual Saber 6 Poison Time of needles not increased by Peridot.
Ice Claw 6 + Aquamarine not increasing slowing effect power for smaller needles.
Possibly fixed the crash caused by Souls.


SRM ver2.1 - 01/11/2015
SR Offline 16.0 and SR Modded saves now cannot be used in each other. Saves must remain in its origin.
Exchangers nerfed. (Stat gain-loss ratio reduced from 3:1 to 2:1)
Priest's each point of negative STR and DEX now changed to reduce -3 LP from the previous -4 LP but now also reduces range by 1/4.
New Compo type: Distributors. Works like an exact opposite of the Exchangers. 
Changed drop holder of MAG Exchanger 2, Fire Soul 3, Thunder Soul 3. For the changed drop location refer to the drop location file.
Blizzard Staff 6 colour changed.


SRM ver2.0 - 30/10/2015
SR Offline updated to ver16.0.
SR Modded updated with new changes in ver16.0.
Holy Laser Flail 6 renamed as Holy Light Flail 6.


SRM ver1.9a - 21/10/2015
New weapon (Poison Dual Spikesword 7)
Rockfall 6 replaced by Magical Blasts 6.

SRM ver1.9 - 17/10/2015
Stage addition (Inferno 3).
Description file for new stuff added.
Poison Blade 6 poison time reduced to 0.5s.
Thunder Soul 2 damage further reduced to 1-33.
LV number display for items of LV10-99 fixed (although no such item exist for now).


SRM ver1.8 - 10/10/2015
New Compo Item (Fire/Thunder Soul 1/3/4)
Fire Soul 2 chance of activation reduced to 10% and has reduced burn rate.
Thunder Soul 2 chance of activation reduced to 10% and only deals 1-44 damage.
Thunder Dual Spikesword 7 projectiles tweaked.
Ice Claw 6 projectiles have improved speed, but now only split into 2 instead of 3 and requires 60MP.
Poison Blade 6 projectiles last half as long.
Rockfall 6 Projectile count reduced to 24 from 30. Residues have a larger spread.


SRM ver1.7 - 28/09/2015
LV3-4 Dual Swords redrawn and renamed.
Main Mod now allows 4 different items to be dropped from the same enemy. 
Iron Dual Sword 1's enemy drop changed to Cyan Smiley Walker (OS).
Mountaintop weapons for all other classes added. 
Bug fixes:
Toxic Dual Saber 6 Poison AT not increased by Emerald or AT Aura.
Bug when Exchangers causes Max LP <0, fixed by setting minimum Max LP =1.
Red/Yellow Crystal and Katana's Card AT bonus not working for Dual Swordsman. 


SRM ver1.6 - 17/09/2015
Dual Swords adjustment: 
Thunder/Poison/Fire Dual Sword 1 AT decreased from 6-9 to 4-8. 
Dual Spikesword 7 AT decreased from 100-150 to 80-125, but now has 10% chance to deal triple damage which works independently from Critical's Card


SRM ver1.5 - 11/09/2015
New compo item added (Dusts, Exchangers). 
Dual Swordsman AT increment by STR and DEX changed.


SRM ver1.4 - 09/09/2015
Dual Swordsman added as a separate class in SR modded. Former edit of Swordsmans replacing Gladiators revoked.


SRM ver1.3 - 08/09/2015
New class added for SR Wiped (BATPAT BETA). 
Bug fix: BATPAT match + Priest AT aura causing AT aura bonus to be calculated twice on BATs.


SRM ver1.2 - 06/09/2015
New SR file added (SR Wiped (BATPAT BETA))


SRM ver1.1 - 05/09/2015
New compo item added (Fire Soul 2 and Thunder Soul 2). 
SR Swordsman Mod renamed to SR Modded.


SRM ver1.0 - 03/09/2015
Package released.