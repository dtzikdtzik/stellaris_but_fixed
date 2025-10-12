A Stellaris mod intending to fix some of the current issues

Three Design Intentions:

## 1 PERFORMANCE and POWERCREEP (make this the mod)
 This mod should increase performance!
- Smaller Economies
- Fewer Ships
- Logistics mechanic (while I am a fan of the concept) are reported to be a performance issue and have been turned off for AI

**Direct economic changes include:**
1. Significantly weakening basic resource production modifiers by a) scaling down the +20% techs, b) decreasing the effects of the basic resource edicts and c) decreasing the effects of the purification buildings. They're still viable! In fact, I suspect they're still very powerfuL!
2. Nerfed Arc Furnaces.
3. Minor increase to tradition costs
4. Nerfed Hydroponics, Solar Panels, Trade Hubs
5. Reduced Starbase cap
**More subtle economic downscaling includes:**
1. Making wars more destructive to pops. Bombardment is significantly more lethal to populations. Collateral damage from armies is slightly increased. 

## 2 Balance
Revitalise dead or underused mechanics, including:
- War Exhaustion
- Bombardment / Ground Combat
- Claims
- Espionage
- Threat
- GalCOM

## 3 AI and Difficulty (TODO: Split this off as a separate mod)
These changes should benefit not only hardcore Grand Admiral players looking for a challenge. They intend to keep the AI more stable and less liable to collapse or dramatically fall off in the late-game.
While 4.0, according to dev diaries, improved AI, it feels much weaker, and falls off quickly as the game lasts. 


### HOW IS THE ECONOMY DOWNSCALED?
Instead of a big, specific change (the strategy of mods like the excellent _Compact Armadas_), I have made broad, diverse, incremental changes. The result is a mod that shouldn't feel to disruptive from vanilla and doesn't turn the balance on it's head, while still solving or mitigating the issues.

# Changelog
## Empire
- Halved base influence from power projection (2>1)
- Influence deficits now cause +100% leader upkeep
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

## Megastructures
- Arc Furnace resource station modifier progression decreased from 25/50/75/100% to 15/30/40/50% (for furnace levels 1/2/3/4)
- Arc Furnace level 4 (final level) now requires Mega-Engineering tech
- Strategic Coordination Center grants an additional +150 fleet command limit
## Ships
- Increased Corvette, Frigate, Destroyer, Cruiser, Battleship, Titan hull section cost by 50% (equates to roughly 25% increased ship cost)
- Bioship hulls cost +50% (as above)
- Space Fauna ship cost +50% (NOT component cost)
- Offspring ship cost +50%
- Increased most ship component alloy/food costs by 50% (except reactors and cloaking, YET)
- Increased military ship build time by 50%
IMPORTANT: SPACE FAUNA components NOT BEEN ADJUSTED (YET)
IMPORTANT2: UPKEEP HAS NOT BEEN ADJUSTED (YET)
## Crime
- Center of Drug Trade planetary modifier now comes with an additional -5% pop growth
- Mob Rule planetary modifier comes with an additional -20% governing ethics attraction
## Galactic Community
- 
## Other
- slightly buffed Bubbles









