A Stellaris mod intending to fix some of the current issues

For Consideration
Increased Alloy Upkeep for ballistic/explosive weapon components
Influence Costs for Dyson Swarm and Arc Furnace
Negative Civics?
Increased energy upkeep for energy based weapons
Food/Trade upkeep for strike craft??
Negative Effects from Planet Designations??
Flight Academy to give strike craft buffs (maybe as education policies? Education could be a whole tradition tree tbh)
Remove ship cost reduction from shipclass techs
Unlock ship sections with more slots
Increase food upkeep for bioships and fauna

**Direct economic changes include:**
1. Significantly weakening basic resource production modifiers by a) scaling down the +20% techs, b) decreasing the effects of the basic resource edicts and c) decreasing the effects of the purification buildings. They're still viable! In fact, I suspect they're still very powerfuL!
2. Nerfed Arc Furnaces.
3. Minor increase to tradition costs
4. Nerfed Hydroponics, Solar Panels, Trade Hubs
5. Reduced Starbase cap
**More subtle economic downscaling includes:**
1. Making wars more destructive to pops. Bombardment is significantly more lethal to populations. Collateral damage from armies is slightly increased. 

### HOW IS THE ECONOMY DOWNSCALED?
Instead of a big, specific change (the strategy of mods like the excellent _Compact Armadas_), I have made broad, diverse, incremental changes. The result is a mod that shouldn't feel to disruptive from vanilla and doesn't turn the balance on it's head, while still solving or mitigating the issues.

# Changelog
### Policies
- Economic Policies (Alloys vs. Consumer Goods) have impact reduced: +25/-25% > +20/-20%
### Empire
- Halved base influence from power projection (2>1)
- Slowed Agendas (Base Agenda Cost 7000 > 8000, 3500 > 4000 for short agendas)
### Planetary Designations
- Nerfed production buffs for all basic resource designations (+25%>20%)
- Trade production from urban designations: +20%>15%
### Ethics
- Authoritarians: +20%/+10% leader upkeep REVIEW
- Egalitarian: -50%/-25% governing ethics attraction, +50%/25% ethics shift speed REVIEW
**- Xenophobe: +50%/+25% diplomatic influence cost** !
- Xenophile: -2/-1 Intel Encryption
**- Pacifists: -2/-1 Commander Cap** !
**- Militarists: +50%/+25% border friction** !
- Spiritualists: TO BE ADDED (slower ethics shift???)
- Materialists: Tradition cost from empire size +10%/+5% REVIEW
### Authorities
**- Democratic: Early Agenda Activation cost +25%** !
**- Oligarchy: Elite pop upkeep +10% SWITCH WITH AUTH ETHIC??** !
### Species Traits
**- Shelled: Nerfed housing usage reduction (-75% > -40%), but added -15% army damage taken** !
- Thrifty: Nerfed from +25% to +20% trader jobs workforce
**- Docile/Unruly: Reduced trait point value to +1/-1** !
- Sedentary/Nomadic: Added -35%/+35% colonist workforce
- Charismatic/Repugnant: Added +1/-1 Elite political power REMOVE
### Leader Traits
- NON-Paragon: Nerfed all ship focus traits from -30% to -20% cost reduction
#### Officials
- Architectural Interest: Nerfed from -20%/-10% building upkeep and +20%/+10% build speed to -15%/-7.5% and 15%/+7.5%
### Buildings !
- Reduced Amenities from all housing buildings by -20%
- Food processing center: Increased mineral cost (900>1000), halved base farmer production increase (+1 from +2), halved ringworld production increase (+1 from +2)
- Mineral Purification Hub: See above (Note: Ringworld versions still get +0.5 alloys)
- Energy Nexus: See above
- Ministry of Production is now Empire Unique (instead of planet unique) and grants +5% alloys/consumer goods empire-wide 
### Megastructures
- Arc Furnace resource station modifier progression decreased from 25/50/75/100% to 15/30/40/50% (for furnace levels 1/2/3/4)
- Upgrading to Arc Furnace level 4 (final level) now requires Citadel Starbase tech
- Arc Furnace now costs 150 influence
- Strategic Coordination Center grants an additional +150 fleet command limit
- AI will build fewer or almost no Hyper Relays (performance concerns)
### Orbital Deposits
- Made the highest energy/mineral/trade deposits slightly more rare (Chances for celestial bodies to spawn with 4/5+ energy, minerals or trade reduced by 25%
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
- Energy tech line: Nerfed technician energy production (20%>15%) !
- The same for Minerals, Food
- Consumer Good Refinement 2: Removed (weight reduced to 0, cannot be drawn regularly) !
- Advanced Metallurgy 2: As above !
- Eco-Integration Studies: Removed !
- Naval Cap tech line now gives +20 naval cap (was +25) !
### Starbase Modules
- Solar Panel: Energy nerfed from 6 to 5 !
- Trade Hub: Trade nerfed from 8 to 6 !


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
### Supremacy
- Logistical Corps: Naval Cap +20%>+10%
### Prosperity
- Adopt: Mining Station Output +20% > Mining Station Cost -15% (otherwise it is weirdly redundant with the finish)
- Finish: Station Output +25% > +15%
### Statecraft
- Constitutional Focus: Agenda Speed +25% > +15%
- Amongst Peers: Exp Reward 150 > 120 (per level) (this is a -20% nerf)
## Traditions (Ascension)
### Genetics
- Finish: Clone Vats Upkeep -33%>25%
### Purity
- Exemplary Genetics: Modify Species Cost -50%>-33% (purity-obsessed societies would be slow, thorough and deliberate with their modifications, possibly?)
### Cloning
- Evolutionary Extrapolation: Clone Vat Upkeep -50%>-35%
### Synthetics
- Power Systems: Robot & Assembler upkeep: -25%>-20%
- Optimization Algorithms: Robotic pop efficiency +10%>+06.283% (the first few digits of Tau, an important constant in mathematics)
### Virtuality
- 2: Empire Size from colonies +100%>+150%
- 2: added Empire size from systems +50%
## Edicts
- Costs raised by 20% (Edict Cap is currently trivial)
TLDR: Mandatory "always-on" edicts are now more situational, basic resource edicts have been nerfed (they were huge)
- Fortify the Border: Starbase upgrade speed +50%>33%, now comes at the cost of +25% border friction #and +25% empire size from systems
- Information Quarantine now grants +1 Encryption instead of +5 Stability and governing ethics attraction is reduced from +50% to +33%
- Peace Festivals cannot be held while at war
- Capacity, Farming and Mining Subsidies: Production buff reduced +50%>+33% and extra upkeep changed from 0.5 Energy > 1 Trade (paying technicians energy to produce more energy was weird). At base 6 Food/Energy and 4 Minerals, 33% still grants min. +2 Food/Energy and +1.4 Minerals per 1 Trade. This is profitable and, given enough edict cap, a better rate than the internal market, but no longer so mandatory)
## Civics
- Cordyceptic Drones: Lowered Space Fauna component damage buff (50%>25%) and fire rate buff (50%>15%) 
## Armies
- Defense/occupation armies now cause collateral damage at a rate of roughly 10-20% of assault armies (previously, they caused none).
- Defense/occupation armies now cause war exhaustion on death, at a rate of roughly 10-20% of assault armies (previously, losing defense armies had no effect on war exhaustion).
- Rebel, pre-ftl and various event armies now cause collateral damage.

## Crime
- Center of Drug Trade planetary modifier now comes with an additional -5% pop growth
- Mob Rule planetary modifier comes with an additional -20% governing ethics attraction
## Galactic Community
- 
## Other
- slightly buffed Bubbles









