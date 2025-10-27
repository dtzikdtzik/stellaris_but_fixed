
# TODO
- Remove Ministry of Production? Change to Empire Limit 1? Or lock behind prosperity?
- The above for other efficiency buildings?
- Can I make it so that you can't take every tradition in a tree, but have to choose?
- Make Robots decline if there is no assembly
- Halve the flat buffs to edict fund?

# Changelog
## Economy
### Empire
- Halved base influence from power projection (2>1)
- Influence deficits now cause +100% leader upkeep
### Ethics
- Authoritarians: +20%/+10% leader upkeep REVIEW
- Egalitarian: -50%/-25% governing ethics attraction, +50%/25% ethics shift speed REVIEW
- Xenophobe: +50%/+25% diplomatic influence cost
- Xenophile: -2/-1 Intel Encryption
- Pacifists: -2/-1 Commander Cap
- Militarists: +50%/+25% border friction
- Spiritualists: TO BE ADDED
- Materialists: Tradition cost from empire size +10%/+5% REVIEW
### Authorities
- Democratic: Early Agenda Activation cost +25%
- Elite pop upkeep +10% SWITCH WITH AUTH ETHIC??
### Species Traits
- Shelled: Nerfed housing usage reduction (-75% > -40%), but added -15% army damage taken
- Thrifty: Nerfed from +25% to +20% trader jobs workforce
- Docile/Unruly: Reduced trait point value to +1/-1
- Sedentary/Nomadic: Added -35%/+35% colonist workforce
- Charismatic/Repugnant: Added +1/-1 Elite political power REMOVE
### Leader Traits
- NON-Paragon: Nerfed all ship focus traits from -30% to -20% cost reduction
#### Officials
- Architectural Interest: Nerfed from -20%/-10% building upkeep and +20%/+10% build speed to -15%/-7.5% and 15%/+7.5%
### Buildings
- Food processing center: Increased mineral cost (900>1000), halved base farmer production increase (+1 from +2), halved ringworld production increase (+1 from +2)
- Mineral Purification Hub: See above (Note: Ringworld versions still get +0.5 alloys)
- Energy Nexus: See above
### Traditions
Supremacy:
- Adopt: Halved army damage (20%>10%)
- Logistical Corps: Halved naval cap (20%>10%)
Prosperity:
- Pursuit of Profit: Replaced production with workforce (crucially NOT bonus workforce)
Statecraft:
- Constitutional Focus agenda speed reduced (25%>15%)
### Megastructures
- Arc Furnace resource station modifier progression decreased from 25/50/75/100% to 15/30/40/50% (for furnace levels 1/2/3/4)
- Arc Furnace level 4 (final level) now requires Mega-Engineering tech
- Strategic Coordination Center grants an additional +150 fleet command limit
### Ships
- Increased Corvette, Frigate, Destroyer, Cruiser, Battleship, Titan hull section cost by 50% ~~(equates to roughly 25% increased ship cost)~~
- Bioship hulls cost +50% (as above)
- Space Fauna ship cost +50% (NOT component cost)
- Offspring ship cost +50%
- Increased most ship component alloy/food costs by 50% (except reactors and cloaking, YET)
- Increased military ship build times by 50% across the board
IMPORTANT: SPACE FAUNA components NOT BEEN ADJUSTED (YET)
IMPORTANT2: UPKEEP HAS NOT BEEN ADJUSTED (YET)
### Technology
- Energy tech line: Nerfed technician energy production (20%>15%)

- Consumer Good Refinement 2: Removed (weight reduced to 0, cannot be drawn regularly)
- Advanced Metallurgy 2: As above
- Eco-Integration Studies: Removed
- Naval Cap tech line now gives +20 naval cap (was +25)
### Starbase Modules
- Solar Panel: Energy nerfed from 6 to 5
- Trade Hub: Trade nerfed from 8 to 6
### Jobs
- Robotic Bath Attendant assembly multiplier reduced (7.5%>5%) and amenity upkeep increase increased (0.03>0.04)


## Pops
- Increased 'recently conquered' happiness penalty (-20%>-25%) and governing ethics attraction penalty (-25%>50%)
- Increased occupation happiness penalty (-10%>-25%)
- Devastation now impacts pop happiness, maxing out at -50%
- Low habitability now affects pop happiness, maxing out at -25% at 0% habitability
- Reduced governing ethics attraction from high happiness (50%>25%)
## Factions / Pop ethics attraction
- Individualist pops are more politically interested now (happiness penalties from low/very low faction approval increased to -15/-50% happiness from -10/-40%)
- Reduced ethics attraction from promoting a faction from 100% to 75%
- Promoting an ethic now comes with a small fee: +5% leader upkeep, representing increased incentive for them to run (or tolerate) your propaganda
- Being at high war exhaustion grants +100% pacifist attraction
## Traditions
- Mercantile: Trickle up economics now increases civilian consumer goods upkeep by 0.2 (instead of 0.1)
## Edicts
- Fortify the Border is now locked behind the Eternal Vigilance ascension perk
## Civics
- Cordyceptic Drones: Lowered Space Fauna component damage buff (50%>25%) and fire rate buff (50%>15%) 
## Armies
- Defense and Occupation Armies now give minor war exhaustion on death and cause collateral damage. 
- Rebel, pre-ftl and various event armies now cause collateral damage
## AI
ALL regular AI empires get:
- Ship and army exp. +100%
- No ship logistics upkeep (due to performance concerns)
Vanilla AI gets various positive modifiers at above Ensign difficulty, mainly to production. I have added several more, designed to make AI life easier and prevent AI collapse. At Grand Admiral, AI empires will get:
- Leader upkeep -40%
- Leader lifespan +20 years
- Starbase upkeep -40%
- Army upkeep -40%
- Edicts upkeep -40%
- Planetary Ascension cost -40%
- Planetary Ascension effect +20%
- Disabled Eternal Vigilance Policy for AI due to performance concerns
### AI LATEGAME PATCH 
Ascension perks give additional modifiers only to AI empires:
(NOTE: These are NOT dependant on difficulty settings...)
(TODO: Adjust for dlc-based tradition swaps)
- Defender of the Galaxy: Fire rate +10%, naval cap +10%, damage to player crisis +25%
- Lord of War: Fire Rate +10%, Ship upkeep -10%, Trade +10%
- Hydrocentric: +15% habitability, +15% Unity
- Enigmatic Engineering: +2 Scientist cap, +30% engineering research
- Nihilistic Acquisition: +50% Orbital Bombardment, +25% slave bonus workforce
- Colossus: +20% naval cap, +50% army damage, +50% bombardment damage
- World Shaper: -50% terraforming cost, +50% terraforming speed, +10% habitability
- Galactic Force Projection: Ship build speed +30%, ship upkeep -15%
- Interstellar Dominion: +50% Influence, -20% empire size
- Grasp the Void: -50% station upkeep, -50% starbase upgrade cost, +100% starbase upgrade speed
- Eternal Vigilance: +8 defense platform cap, -50% defense platform cost, -50% defense platform upkeep
- Galactic Contender: +50% force disparity bonus firerate effect, -20% war exhaustion, +20% sublight speed
- Technological Ascendancy: +25% bonus researcher workforce, +2 scientist leader skill
- One Vision: +5 Stability, -20% pop upkeep
- Consecrated Worlds: +20% unity, -15% pop amenities upkeep
- Mastery of Nature: +100% clear blocker speed, +20% habitability, -30% building build time
- Imperial Prerogative: +2 Official leader skill, -20% empire size, -50% leader upkeep
- Executive Vigor: -25% Leader upkeep, -25% edict upkeep
- Transcendent Learning: +25 years leader lifespan, +50% councilor exp. gain
- Shared Destiny: Trust cap +20, trust growth +50%, Influence +50%
- Voidborn: Megastructure build speed +25%, megastructure upkeep -25%, Alloys +5%
- Master Builders: -50% Megastructure upkeep, +5% Alloys
- Galactic Wonders: +75% megastructure build speed, +5% Alloys
- Machine Worlds: +20% habitability, -20% pop amenities upkeep, +10% bonus workforce
- Hive Worlds: +20% habitability, -20% pop amenities upkeep, +10% bonus workforce
- Arcology: +20% habitability, -20% pop amenities upkeep, +10% bonus workforce
- Xenocompatibility: +25% pop growth
- Universal Transactions: +10% trade, +25% branch office value, +2 envoys
- Detox: +20% habitability, +100% terraform speed, -50% terraform cost
- Mechromancy: +25% army damage, +15% fire rate
- Weather Control Systems: -20% jump drive cooldown, +10% habitability (no idea, I don't play cosmic storms)
- Ascension Path Perks: +20% bonus pop workforce, +10% pop growth


## Crime
- Center of Drug Trade planetary modifier now comes with an additional -5% pop growth
- Mob Rule planetary modifier comes with an additional -20% governing ethics attraction
## Galactic Community
- 
## Other
- slightly buffed Bubbles









