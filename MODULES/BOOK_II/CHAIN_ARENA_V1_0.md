# Preserved source — Ashes_of_Thay_Book_II_Chain_Arena_Complete_Module_v1_0.docx

**Import date:** 2026-10-07

**Disposition:** DM FUNCTIONAL MODULE v1.0. Future relative to current checkpoint. Its default values and blank live-save tables are not current resources.

**Original source:** `libfile_d5fc51c2461081918c38d858a88925b8` · `Ashes_of_Thay_Book_II_Chain_Arena_Complete_Module_v1_0.docx`

**Source created:** 2026-07-13T14:03:04.289554Z

**Recovery:** Complete available text extraction (1817 reported lines, all line windows read). This is preserved source text, not a verbatim chat transcript or a newly designed module. Original pagination/table extraction may differ from the source layout.

**Extracted-text SHA-256:** `a6da3672f21145d201f1e129d62466a71e06120518b296dcd7cb540ad3befcb8`

---

## Original extracted text























Ashes of Thay Book II - Chain Arena Complete Module

ASHES OF THAY · BOOK II · CHAIN ARENA
ASHES OF THAY — BOOK II
CHAIN ARENA
The Containment Spine · Complete Module v1.0

	
	MODULE PURPOSE
Kompletní hratelný encounter mezi Maintenance Spine a Prison Core. Obsahuje všechny minimoduly CA-00 až CA-13, live save šablonu, scaling, statblocky, DC, failure-forward a DM run sheet.



	Field
	Value

	Canon position
	After Lower Rootglass Bridge and Maintenance Spine; before Prison Core.

	Default difficulty
	Matthael level 9–10 + Ti + Crew support blocks.

	Tone
	Ancient containment horror, tactical movement, crew rescue, catastrophic restraint.

	Primary question
	Can the Crew break the prison’s definition without destroying the only route out?

	Hard locks
	No physical Barten, no Anaxaster name, no true storm inside Arena.



Contents
1. Live Game Save template
2. CA-00 Core Design Lock
3. CA-01 Arena Anatomy
4. CA-02 Chain-Lock Node System
5. CA-03 Enemy Package
6. CA-04 Round Engine
7. CA-05 Encounter Phases
8. CA-06 Crew Spotlight Actions
9. CA-07 Checks & Spell Interactions
10. CA-08 Failure Matrix
11. CA-09 Echoes & Hidden Information
12. CA-10 Rewards
13. CA-11 Transition to Prison Core
14. CA-12 DM Run Sheet
15. CA-13 Assembly Notes


LIVE GAME SAVE — COMPACT
	Resource
	Current / max
	Resource
	Current / max

	HP
	— / —
	Temp HP
	—

	AC
	—
	Sorcery Points
	— / —

	Hit Dice
	— / —
	Inspiration
	yes / no

	Concentration
	—
	Conditions / exhaustion
	—

	Slots 1st–5th
	— / — / — / — / —
	Riftblade
	charges / mode

	Silverstrain
	dormant / reacting / unstable
	Storm Seed
	faint / rising / severe

	Ti
	HP / condition / position
	Location
	—



	Crew
	State
	Crew
	State

	Mira
	—
	Eryn
	—

	Norbyn
	—
	Naevyra
	—

	Red Veil
	—
	Caern & Nessie
	—



	Breaches
	Structural
	Pressure
	Control
	Separated
	Echo

	0 / 3
	0 / 4
	1 / 6
	0 / 2
	No
	0 / 2



	
	Δ CHANGE
HP ___ | slots ___ | SP ___ | concentration/conditions ___ | trackers ___ | NPC state ___





ASHES OF THAY — BOOK II
CA-00 · CORE DESIGN LOCK
The Containment Spine

	
	CANON PURPOSE
Chain Arena otevírá cestu k Prison Core. Nepropouští Anaxastera, nevytváří pravou storm a nesmí zničit celý dungeon dřív, než Crew získá payoff.



Module Snapshot
	Field
	Locked value

	Recommended level
	Matthael 9–10; Ti active; core Crew support.

	Duration
	90–150 minut podle roleplay a taktického tempa.

	Type
	Objective combat + environmental puzzle + failure-forward.

	Primary objective
	Breach NAME, MOTION a VOICE containment nodes.

	Secondary objective
	Zachovat alespoň 2 ze 3 support pylons: ROOT, RELAY, GLASS.

	True boss
	Prison logic a action economy, ne jen HP Chain-Wardena.

	End state
	Cesta do Prison Core se otevře; hodnoty trackerů se přenesou dál.



Non-Negotiable Rules
• Damage může node prolomit, ale brute-force přidává Structural Damage. Chytrá deaktivace je vždy bezpečnější.
• Chain-Warden může být zničen, obejit nebo převzat. Jeho smrt sama o sobě encounter nevyhraje.
• Tři Chain Breaches jsou čisté objective victory. Dvě breaches + poražený Warden otevřou fail-forward route.
• Pád do shaftu není instantní smrt. Je to damage + restrained + separace, aby encounter trestal bez levného game overu.
• Barten Echo dává timing, ne řešení. Anaxasterovo jméno se zde nesmí objevit in-character.
• Pravá storm zde nevzniká. Pressure pouze zesiluje Storm Seed.


Victory Ladder
	Outcome
	Requirement
	Handoff

	Strong Victory
	3 Breaches; Structural Damage 0–1; Pressure 0–2; Guardian Control 2; no separation.
	Core gate opens cleanly; 1 automatic setup advantage in Prison Core.

	Standard Victory
	3 Breaches; Structural Damage max 2; Pressure max 4.
	Core gate opens; normal Prison Core start.

	Costly Victory
	3 Breaches with Structural Damage 3–4 or Pressure 5.
	Core opens, but collapse / overload complication begins active.

	Failure Forward
	2 Breaches + Warden at 0 HP, seized, or forced into emergency override.
	Gate tears open; +1 Structural Damage, +2 Pressure, possible separation.

	Catastrophic Transfer
	Pressure reaches 6 before valid route.
	Emergency system drags survivors toward Core; 4d6 force, DEX save 16 half; Crew split by 1 zone.



Starting Trackers
	Tracker
	Start
	Range
	Function

	Chain Breaches
	0
	0–3
	Objective progress.

	Structural Damage
	0
	0–4
	Stability of escape route and future dungeon.

	Pressure
	1
	0–6
	Storm Seed / containment overload escalation.

	Guardian Control
	0
	0–2
	Destroyed = 0, disabled = 1, seized = 2.

	Crew Separation
	No
	Yes/No
	Who enters Core together.

	Echo Alignment
	0
	0–2
	Strength of Barten / relay overlap; not physical presence.



Default Table Mode
Pro The Game použij tři allied initiative blocks: Matthael + Ti; Mira/Eryn support block; Norbyn/Naevyra support block. V každém support blocku jedná jedna postava plnou zjednodušenou akcí a druhá může poskytnout krátkou reakci, pokud ji má. Red Veil jedná samostatně pouze při explicitní přítomnosti. Tím Crew zůstává živá, ale boss se neutopí v šesti plných character sheetech.


ASHES OF THAY — BOOK II
CA-01 · ARENA ANATOMY
Battlefield, zones and movement

Read-Aloud: First Sight
	Chodba končí bez dveří. Kámen prostě přestane před obrovským kruhovým prostorem, jako by se stavitelé báli pokračovat ve stejné geometrii. Šest mostů z řetězů a kořenového skla visí nad černou vodou. Tři pylony drží místnost pohromadě. Tři menší uzly drží pohromadě něco jiného. Uprostřed klečí postava vyrobená z příliš mnoha pout. Když zvedne hlavu, žádný obličej tam není. Jen pečeť, která se vás pokouší pojmenovat.



Dimensions & Zones
	Zone
	Size / elevation
	Rules

	Entry Gallery
	30×20 ft; +10 ft above ring
	Safe start, half cover, cannot remain safe after Phase II.

	Outer Ring
	100 ft diameter
	Main movement lane; intermittent half cover.

	Central Dais
	30 ft diameter; +5 ft
	Warden start; counts as difficult terrain while chains move.

	Core Gate
	North wall; +15 ft
	Sealed until victory condition.

	Support Pylons
	3 balconies; +10 ft
	ROOT, RELAY, GLASS. Each has local cover and control station.

	Definition Nodes
	Inner ring
	NAME, MOTION, VOICE. Each has 10ft control radius.

	Chain Bridges
	10 ft wide
	Move / rotate at initiative 20. Falling edge save DEX 15.

	Black-Water Shaft
	40 ft below
	4d6 bludgeoning + restrained by chain cradle; escape DC 16.





Battlefield Schematic (zone map)
Každé pole představuje přibližně 10 stop. Pro standardní 5ft grid rozděl každé pole na 2×2. Zóny jsou autoritativní; přesné hrany lze během hry přizpůsobit popisu.
	
	
	
	CORE
	CORE
	CORE
	CORE
	CORE
	
	
	

	
	ROOT
	ROOT
	BR
	NAME
	CHAIN
	MOTION
	BR
	GLASS
	GLASS
	

	
	ROOT
	ROOT
	BR
	
	CHAIN
	
	BR
	GLASS
	GLASS
	

	
	BR
	BR
	BR
	
	CHAIN
	
	BR
	BR
	BR
	

	
	NAME
	
	
	DAIS
	DAIS
	DAIS
	
	
	MOTION
	

	
	
	
	DAIS
	WARDEN
	WARDEN
	WARDEN
	DAIS
	
	
	

	
	VOICE
	
	DAIS
	WARDEN
	WARDEN
	WARDEN
	DAIS
	
	
	

	
	BR
	BR
	BR
	DAIS
	DAIS
	DAIS
	BR
	BR
	BR
	

	
	RELAY
	RELAY
	BR
	
	ECHO
	
	BR
	SHAFT
	SHAFT
	

	
	RELAY
	RELAY
	BR
	ENTRY
	ENTRY
	ENTRY
	BR
	SHAFT
	SHAFT
	

	
	
	
	
	
	
	
	
	
	
	


	Kód
	Význam

	CORE
	Uzavřená brána do Prison Core.

	ROOT / RELAY / GLASS
	Nosné pylony. Zachovat nebo přesměrovat.

	NAME / MOTION / VOICE
	Containment-definition nodes. Cíl encounteru.

	BR
	Řetězové mosty; mohou se hýbat nebo mizet.

	DAIS / WARDEN
	Centrální dais a počáteční pozice Chain-Wardena.

	SHAFT
	Black-water shaft; pád není instant death, ale separuje.

	ECHO
	Maintenance relay point pro Barten Echo / Grudgebell timing.

	ENTRY
	Vstup z Maintenance Spine.



Terrain Rules
	Feature
	Rule

	Chain Bridge
	Difficult terrain when Pressure 4+. Dash across requires Acrobatics DC 14 or fall prone at destination.

	Rootglass Cover
	Half cover. AC 15, HP 20 per 5ft section; thunder damage ignores resistance.

	Moving Platform
	When it shifts, creature makes DEX save 15 or moves 10 ft with it and falls prone.

	Open Edge
	Forced movement over edge allows DEX save 15 to catch chain; success hanging, failure falls.

	Chain Cradle
	Creature in shaft is restrained. Action Athletics or Acrobatics DC 16; ally can pull with Athletics DC 14.

	Core Gate Steps
	Full cover from one side. At Phase IV steps become unstable difficult terrain.



Starting Positions
• Crew begins in Entry Gallery within 20 ft of each other unless prior scene caused separation.
• Chain-Warden begins dormant on Central Dais.
• Relay Bailiff A begins at NAME node. Bailiff B begins inactive at GLASS pylon and activates in Phase II.
• Ti may begin hidden after Stealth DC 15 or Arcane Eye / prior scouting success.
• Red Veil, if present, begins on a side bridge, not inside Crew formation.


ASHES OF THAY — BOOK II
CA-02 · CHAIN-LOCK NODE SYSTEM
Three definitions, three supports

Containment Architecture
Arena má dvě odlišné vrstvy. Definition Nodes určují, co vězeň smí být. Support Pylons drží místnost a cestu naživu. Zničení všeho je nejrychlejší způsob, jak vyhrát proti vlastnímu escape route.
Definition Nodes
	Node
	Active effect
	Safe breach
	Brute-force breach

	NAME
	Warden má Seal Persistence: jednou při 0 HP zůstane na 1 HP. Node také označuje první nový cíl každé kolo.
	2 successes: Arcana/Investigation/Insight DC 17. První success Exposes; druhý Breaches.
	AC 16, HP 35. Na 0 HP: Breach +1 Structural Damage.

	MOTION
	Warden reach 20 ft pro opportunity attacks; initiative 20 může táhnout most.
	2 successes: Athletics/Acrobatics/Arcana DC 16.
	AC 16, HP 35. Na 0 HP: Breach +1 Pressure.

	VOICE
	První Help / Crew Support bonus každé kolo vyžaduje CHA save DC 15; failure bonus propadne.
	2 successes: Religion/Arcana/Performance/Persuasion DC 17 po expose.
	AC 16, HP 35. Na 0 HP: Breach +1 Pressure; echo manifests violently.



	
	NODE CHECK ENGINE
Každý node má stav Sealed → Exposed → Breached. Jeden check = action. Failure způsobí 2d6 force nebo +1 Pressure (DM zvolí podle fiction). Po dvou failures se node může dál řešit, ale další safe check má DC +2.





Support Pylons
	Pylon
	If active
	Stabilise / redirect
	If destroyed

	ROOT
	Snižuje Structural Damage z prvního environmentálního hazardu každé kolo na 0.
	Nature DC 16 nebo Eryn Deepgreen action. Úspěch: root-bridge, safe lane, remove 1 Structural Damage once.
	+1 Structural Damage; všechny bridges difficult terrain.

	RELAY
	Zvyšuje Pressure o +1 na initiative 20, dokud není stabilizován.
	Investigation/Arcana/Thieves’ Tools DC 16. Úspěch: initiative 20 pulse lze jednou zrušit.
	+1 Pressure; Warden může Node Command jako legendary action zdarma jednou.

	GLASS
	Warden má Redirection reaction: změň cíl jednoho ranged spell attack na nejbližší Rootglass section.
	Arcana DC 17 nebo thunder resonance. Úspěch: Crew získá half cover against Warden Seal Pulse once.
	+1 Structural Damage; 10ft glass shrapnel zone, 2d6 slashing on entry.



Object Rules
• Nodes a pylony jsou magical objects: immune poison/psychic; resistant fire/cold; thunder damage ignores resistance.
• Shatter nebo thunder Chromatic Orb automaticky Exposes node, pokud způsobí alespoň 10 damage v jednom zásahu. Další zásah jej stále musí breachnout.
• Dispel Magic proti DC 17 počítá jako jeden safe success. Nelze jím získat dva successes najednou.
• Melee attack s Riftblade může místo damage provést Control Cut: attack vs AC 16; hit = one safe success, ale Rift mode určí side effect.
• Repair by enemy může odstranit pouze Exposed state, nikdy již získaný Chain Breach.
Riftblade Interactions
	Mode
	Node effect
	Cost / risk

	Freeze
	Hit může stabilizovat MOTION nebo jednu bridge do příští initiative 20.
	No extra damage; counts as control.

	Scorch
	Hit proti Exposed node má +1 damage die / narrative burn-through.
	If it touches ROOT pylon: Pressure +1.

	Rift
	Hit counts as one safe success regardless of node shell.
	Pressure +1 immediately; cannot be used twice on same node.

	No mode
	Normal attack and damage.
	No special interaction.





ASHES OF THAY — BOOK II
CA-03 · ENEMY PACKAGE
Chain-Warden and relay enforcers

Default Encounter Package
	Table state
	Package

	Matthael lvl 9 / low resources
	Warden 155 HP; Bailiff A active; Bailiff B arrives Phase II; 1 legendary action until first breach.

	Matthael lvl 9 / normal
	Warden 175 HP; 2 Bailiffs; 2 legendary actions.

	Matthael lvl 10 / strong resources
	Warden 200 HP; 2 Bailiffs; 2 legendary actions; one Chain Echo at Pressure 4.

	4–5 full PCs
	Warden 225 HP; 2 Bailiffs; 3 legendary actions; Chain Echo at Phase III.



CHAIN-WARDEN OF THE WRONG SEAL
Large construct, unaligned. Default lvl 9 statistics are listed; scaling only changes HP and legendary actions unless stated.
	Stat
	Value

	AC / HP
	18 / 175 (see scaling)

	Speed
	30 ft, climb 30 ft across chains

	STR DEX CON INT WIS CHA
	20 (+5), 12 (+1), 20 (+5), 12 (+1), 16 (+3), 14 (+2)

	Saving Throws
	STR +9, CON +9, WIS +7, CHA +6

	Skills
	Athletics +9, Perception +7, Arcana +5

	Resistances
	fire, cold, lightning; bludgeoning/piercing/slashing from nonmagical attacks

	Immunities
	poison, psychic; charmed, frightened, paralyzed, petrified, poisoned

	Senses
	darkvision 120 ft, truesight 30 ft, passive Perception 17

	CR guidance
	Approximately CR 10–11 objective boss; not balanced as solo HP fight.



Traits
• Definition-Fed. Active nodes grant NAME, MOTION, and VOICE benefits listed in CA-02.
• Bound to the Dais. Before Phase II the Warden cannot leave Central Dais, but can attack through chains at 20 ft.
• Objective Body. When reduced to 0 HP before at least 2 Chain Breaches, it collapses and reforms at initiative 20 with 45 HP unless NAME is breached. Reform adds +1 Pressure.
• Magic Weapons. Its attacks are magical.
Actions
	Action
	Rule

	Multiattack
	Two Chain Glaive attacks.

	Chain Glaive
	Melee +9, reach 15 ft, one target. 2d8+5 slashing + 1d6 force.

	Hook and Drag
	Melee +9, reach 20 ft. 2d6+5 piercing; STR save DC 16 or pulled 15 ft and prone.

	Seal Pulse (Recharge 5–6)
	Creatures of Warden’s choice within 30 ft: CON save DC 16; 4d8 force and pushed 10 ft, half/no push on success.

	Lockdown Chain (Recharge 4–6)
	One target within 60 ft: DEX save DC 16 or restrained. Chain AC 16, HP 20; escape Athletics/Acrobatics DC 16.

	Emergency Reclassification (1/encounter)
	After first node breach, mark one creature. Until end of Warden’s next turn, attacks against marked target deal +1d8 force; mark ends if target reaches another node and succeeds DC 15 Arcana/Insight as bonus action.



Bonus Action / Reaction
	Feature
	Rule

	Anchor Step
	Teleport 30 ft to an active node or pylon it can see.

	Interdict Reaction
	When a creature within 30 ft attempts a node check, Warden moves 15 ft without provoking and makes one Chain Glaive attack. Once/round.

	Glass Redirection Reaction
	Only while GLASS active; redirect one ranged spell attack targeting Warden to Rootglass cover within 10 ft of line. The attacker may choose to miss instead.



Legendary Actions
• Chain Shift (1): move up to half speed without provoking.
• Lash (1): one Chain Glaive attack.
• Node Command (2): trigger the active effect of NAME, MOTION, or VOICE once. Cannot use same node twice in one round.
RELAY BAILIFF
Medium construct, unaligned. Two are the default maximum.
	Stat
	Value

	AC / HP
	16 / 48

	Speed
	30 ft

	Attack
	Relay Pike +7, reach 10 ft, 1d10+4 piercing + 1d6 force; two attacks.

	Clamp
	On one hit/turn target STR save DC 15 or speed becomes 0 until start of Bailiff’s next turn.

	Repair Node
	Action adjacent to Exposed node: node returns to Sealed unless a character within 5 ft uses reaction and succeeds Athletics/Arcana DC 15.

	Body Block
	Reaction: impose disadvantage on attack against adjacent node or pylon; Bailiff becomes target on miss.

	Death Pulse
	At 0 HP, adjacent creatures DEX save 14 or 2d6 force; success half. Does not damage nodes.



CHAIN ECHO (optional hazard)
	Stat
	Value

	AC / HP
	14 / 1; immune to all damage except thunder, radiant, or magical slashing.

	Spawn
	Pressure 4+ at initiative 20, one Echo adjacent to isolated creature.

	Bind
	Attack +6; no damage; target grappled, escape DC 14. Echo vanishes when grapple ends.

	Purpose
	Consumes movement and rescue actions; never becomes grindy minion HP.



Warden AI Priorities
1. Stop the creature currently interacting with a Definition Node; use Interdict before raw damage.
2. Use forced movement toward edges only when a catch / rescue opportunity exists. The Warden captures; it does not cheaply execute.
3. Use Seal Pulse when at least two targets are in range or when it can clear a node zone.
4. After second Breach, focus on isolating the character who produced the most control progress, not automatically the lowest-HP target.
5. If NAME is breached, the Warden becomes visibly uncertain and prioritises repairing / protecting remaining definitions.
Bailiff Tactics
• One Bailiff pressures a node actor; the other protects a support pylon or repairs an Exposed node.
• Bailiffs use Body Block on objective attacks, not every attack against the Warden.
• Below 15 HP a Bailiff attempts Repair Node before reckless damage, because its purpose is maintenance.


ASHES OF THAY — BOOK II
CA-04 · ROUND ENGINE
Initiative 20, Pressure and structure

Initiative Order
1. Roll normal initiative. Matthael and Ti use normal actions.
2. Use two Crew Support blocks unless running full individual NPC sheets.
3. Chain-Warden and Bailiffs use normal initiative.
4. At initiative count 20, losing ties, resolve Arena Pulse.
5. At end of each round, check phase triggers and update LIVE GAME SAVE if a tracked value changed significantly.
Pressure Track
	Pressure
	State
	Arena effect

	0
	Quieted
	No automatic escalation this round.

	1
	Listening
	Starting state. Cosmetic Storm Seed resonance.

	2
	Active
	First failed node check each round deals +1d6 force.

	3
	Severe
	Arena Pulse affects two zones instead of one.

	4
	Rupturing
	Chain bridges are difficult terrain; optional Chain Echo spawns.

	5
	Critical
	At end of each round one intact pylon takes 10 damage or Crew accepts +1 Structural Damage.

	6
	Catastrophic
	Emergency transfer / failure-forward triggers immediately.



How Pressure Changes
• +1 at initiative 20 while RELAY pylon is active and unstabilised.
• +1 for Rift mode node cut, failed overchannel, destroyed MOTION/VOICE node, or Warden reform.
• +1 when DM chooses pressure instead of direct damage on failed node check.
• -1 once per encounter from stabilised RELAY pylon.
• -1 from successful Matthael Disagreement action, Grudgebell timing, or fully seizing the Warden. Pressure cannot drop below 0.


Structural Damage Track
	Damage
	State
	Effect

	0
	Intact
	No penalty.

	1
	Cracked
	One bridge begins unstable; DEX save 13 when first crossed.

	2
	Failing
	One zone loses safe cover; future escape gains one complication.

	3
	Severe
	All forced-movement saves +1 DC; Prison Core starts with collapsing architecture.

	4
	Near collapse
	Costly victory minimum; any further Structural Damage becomes +1 Pressure and 2d6 debris damage to all on Outer Ring.



Arena Pulse Table
	d6 / choose
	Pulse
	Effect

	1
	Chain Sweep
	One bridge/zone: DEX save 15 or 2d6 slashing and pushed 10 ft.

	2
	Platform Rotation
	One platform shifts 20 ft. Creatures DEX save 15 or move with it and fall prone.

	3
	Black-Water Draw
	Creatures within 10 ft of edge STR save 15 or pulled 10 ft toward edge.

	4
	Seal Static
	Spellcasters CON save 15 or cannot take reactions until next initiative 20. Concentration is checked only if damage occurs.

	5
	Glass Rain
	One pylon zone: DEX save 15, 2d6 slashing, half on success; creates 10ft difficult terrain.

	6
	Wrong Name
	NAME marks a creature. Warden has advantage on first attack against it before next initiative 20.



	
	PULSE CHOICE RULE
Neválej náhodně, když příběh jasně ukazuje lepší hazard. DM volí pulse, který tlačí na aktuální objective, ne pulse, který levně dorazí downed postavu.





ASHES OF THAY — BOOK II
CA-05 · ENCOUNTER PHASES
From measurement to core access

Phase 0 — Read the Machine
Probíhá před initiative nebo během prvních sekund. Crew může získat maximálně dva starting benefits.
	Check
	DC
	Benefit

	Arcana / Investigation
	16
	Identify one true Definition Node; first check against it has advantage.

	Nature
	16
	Identify ROOT pylon as structural; first Structural Damage from environment is ignored.

	Perception
	15
	Spot Chain Cradle below; first falling creature has advantage to catch.

	Grudgebell / timing
	Automatic if invoked
	Pressure does not rise on first initiative 20.

	Arcane Eye / Ti scout
	No roll if safely performed
	Reveal Bailiff B and one bridge rotation path.



Phase I — The Arena Measures
	Trigger
	Rules
	Goal

	Start of combat; ends at first Breach or end of round 2.
	Warden bound to dais; one Bailiff active. NAME marks Matthael or first overt spellcaster.
	Expose one node and stabilise one pylon.



Phase II — Enforcement
	Trigger
	Rules
	Goal

	First Chain Breach or round 3.
	Warden leaves dais; Bailiff B activates; Seal Pulse becomes available; Pressure +1 if no pylon stabilised.
	Reach second Breach while keeping 2 pylons intact.



Phase III — Reversal
	Trigger
	Rules
	Goal

	Second Chain Breach.
	All bridges rotate once; Warden immediately uses Lockdown Chain if available; VOICE or remaining node intensifies.
	Breach final node or achieve controlled override.



Phase IV — Core Access
Po třetím Breach se Core Gate začne otevírat. Encounter nekončí okamžitě. Crew má jeden stabilisation round: může převzít Wardena, zachránit separovaného člena, snížit Pressure nebo sprintovat do Core.
	Choice
	Check / action
	Handoff

	Seize Warden
	Arcana/Smith tools/Grudgebell group check: 2 successes before 1 failure, DC 16.
	Guardian Control 2; Pressure -1.

	Disable Warden
	Reduce to 0 HP after NAME breached or Arcana DC 17 adjacent.
	Guardian Control 1.

	Destroy Warden
	Damage to 0 HP without control.
	Guardian Control 0; gain Command Shard.

	Stabilise exit
	Nature/Investigation/Athletics DC 16.
	Remove 1 Structural Damage or clear separation.

	Rush Core
	Movement + optional Dash.
	No extra check; keep current consequences.



Round Limit
	
	SOFT CLOCK: 8 ROUNDS
Na konci 8. kola, pokud není otevřen Core Gate, Pressure jde na 6 a spustí se Catastrophic Transfer. Encounter pokračuje do dalšího modulu; kampaň se nezasekne.





ASHES OF THAY — BOOK II
CA-06 · CREW SPOTLIGHT ACTIONS
Useful, bounded, and not auto-solving

Matthael IX-Lambda
	Action
	Mechanic

	Frostfire Disagreement (1/arena)
	Action; CHA (Arcana) DC 17. Success: Expose one node within 30 ft and reduce Pressure 1 OR deal 3d8 force/cold to Warden. Failure: 2d6 psychic + Pressure 1. This is a module feature, not free spellcasting.

	Riftblade Control Cut
	Attack vs node AC 16; hit counts as one safe node success. Mode side effects from CA-02.

	Runic Lock
	Reaction or action against forced relocation / node rewrite. Cancel one pull, platform shift, or Warden Anchor Step; expend as normal.

	Sorcery Point Push
	Spend 2 SP after failed node check to reroll. Must use new roll; on second failure Pressure +1.



Ti
	Action
	Mechanic

	Draconic Ping
	Once per phase, identify which visible node / pylon is real, active, or about to pulse. No roll.

	Heroic Relay Crossing
	DEX (Stealth or Acrobatics) DC 15. Success: deliver key / Help across one zone and ignore opportunity attacks. Failure: Ti hangs from chain; no damage, but ally must spend reaction or action to recover before next pulse.

	Help
	Normal Help action; VOICE may suppress until breached.

	Tiny Bite of Administrative Violence
	If adjacent to Exposed node, Ti may use action to keep it Exposed until next round, preventing Bailiff repair.





Eryn / Deepgreen Witness
	Action
	Mechanic

	Rootbrace (1/arena)
	Nature DC 16. Success: stabilise ROOT, create 20ft safe rootglass path, and remove 1 Structural Damage once. Failure: path exists but Pressure +1.

	Living Memory Test
	Action at pylon/node; Nature DC 15. Reveal whether structure is support, imposed memory, or containment definition; next ally gets advantage.

	Protective Roots
	Reaction 1/round: reduce forced movement of one ally within 30 ft by 10 ft; if reduced to 0, ally does not need edge save.



Mira
	Action
	Mechanic

	Paradox Cut (1/arena)
	Investigation or Thieves’ Tools DC 16 at node. Success: node Exposed and next breach check advantage. Failure: Mira may move 10 ft without provoking, but no progress.

	Cut the Angle
	Reaction when Warden Interdicts: impose disadvantage on its attack; if it misses, node check proceeds with +2.

	Route Call
	Bonus action once/phase: one ally ignores difficult terrain and opportunity attacks for 10 ft of movement.



Norbyn / Grudgebell
	Action
	Mechanic

	Grudgebell Timing (1/arena)
	Cancel one initiative 20 Arena Pulse or reduce Pressure by 1 after hearing it begin.

	Hold the Chain
	Athletics DC 16. Pin one bridge/platform until next round; creatures on it immune to shift/pull.

	Hammer the Rhythm
	Attack against node/pylon; on hit, ally’s next Arcana/Investigation check against same target gains +1d4 instead of dealing bonus effect.



Naevyra
	Action
	Mechanic

	Radiant Interference (2/arena)
	Religion or Arcana DC 16. Suppress VOICE active effect until next initiative 20; on success also grant one ally advantage on next save.

	Memory Warning
	Reaction: when Warden uses named ability, one ally gains +2 to the save or AC against it.

	Wounded Advance
	Move 20 ft and interact with node/pylon as same action once/arena; after use Naevyra cannot take reactions until next turn.



Red Veil (optional)
	Action
	Mechanic

	Blade-Line Mark
	One visible node or Warden: next related attack/check gains +1d4.

	Red Step Rescue
	Reaction 2/arena: teleport 15 ft and pull one adjacent ally 5 ft away from edge or hazard.

	Private Objective
	Once in Phase III she may attempt to copy a node signature. Crew can allow it, stop it, or bargain. This affects trust, not main objective.



Caern & Nessie
Default canon: Caern’s route diverges before Chain Arena. Pokud z rozhodnutí u stolu zůstane, použij pouze jeden cameo support: Thornline (Nature DC 16) creates a bridge for one round, or Nessie drags one fallen ally from edge. Potom se jeho red-leash route opět oddělí.
Support Block Rotation
	Round need
	Recommended actor
	Reason

	Read / stabilise structure
	Eryn or Norbyn
	Roots and timing create safe objective windows.

	Expose / breach node
	Mira or Matthael
	Precision and spell-control advance the actual goal.

	Survive pulse / rescue
	Naevyra, Eryn, or Ti
	Protection and movement prevent action-economy collapse.

	Phase IV control
	Norbyn + Matthael
	Grudgebell timing plus Arcana can seize Warden.

	Do not repeat same NPC every round
	Rotate
	Every Crew member gets a visible beat without six full turns.



Example Crew Round
Matthael uses Shatter to Expose MOTION. Mira/Eryn block chooses Mira: Paradox Cut adds the safe success. Norbyn/Naevyra block chooses Naevyra: Radiant Interference suppresses VOICE so Ti can Help. The other members still speak, react, and protect, but the tracker load stays sane.


ASHES OF THAY — BOOK II
CA-07 · CHECKS & SPELL INTERACTIONS
Strict 5e first, cinematic second

Core DC Table
	Task
	DC
	Notes

	Read active node
	Arcana / Investigation 16
	Identify effect and safe interaction.

	Safe breach check
	16–17
	By node; see CA-02.

	Stabilise pylon
	16–17
	One success unless damaged / critical state.

	Cross moving bridge
	Acrobatics 14–15
	Failure prone or edge catch, not automatic fall.

	Catch edge
	DEX save 15
	Success hanging; action or ally needed.

	Escape chain restraint
	Athletics / Acrobatics 16
	Action.

	Pull ally from cradle
	Athletics 14
	Action; advantage with rope/root/chain tool.

	Seize Warden
	Group check DC 16
	2 successes before 1 failure in Phase IV.



Matthael Spell Adjudication
	Spell / feature
	Arena ruling

	Shield
	Works normally. Does not stop saves, pulls, or platform movement.

	Misty Step
	Repositions Matthael only. Valid across gaps if destination visible. Does not carry Ti or ally.

	Haste
	RAW extra action only: one weapon attack, Dash, Disengage, Hide, or Use Object. Node skill check is not automatically allowed as Haste action unless it is Use Object on a prepared interface.

	Shatter
	Normal thunder damage. Against node/pylon, 10+ damage Exposes it. Structural objects can be damaged; choose target carefully.

	Chromatic Orb — thunder
	Normal attack/damage; 10+ thunder on node Exposes it.

	Sorcerous Burst — thunder
	Normal spell attack/damage. Thunder result interacts as above; no guaranteed type unless rolled/selected by actual feature wording.

	Cone of Cold
	Damages creatures normally. Does not automatically freeze magical nodes or bridges; may grant cinematic ice without extra condition.

	Ray of Frost
	On Warden hit, reduce speed as spell says. Does not freeze node.

	Burning Hands
	Damages creatures. If deliberately aimed through ROOT pylon, failed control may add Pressure 1.

	Fear
	Warden/Bailiffs immune to frightened.

	Detect Thoughts
	No conventional mind in nodes/Warden. Caster makes WIS save 15 or 1d6 psychic; success reveals active node priority.

	Arcane Eye
	Excellent scouting before combat; reveals layout, hidden Bailiff, and real nodes.

	Tiny Hut
	Casting time prevents normal combat use. Arena does not require special anti-Hut rule.

	Ashardalon’s Stride
	Mobility and creature damage only; it does not automatically damage objects unless spell explicitly says so.

	Dispel Magic
	Ability check DC 17 counts as one safe node success or suppresses pylon active effect for one round.

	Counterspell
	May counter Seal Pulse or Node Command as a 4th-level magical effect. Warden may still use other actions.



Creative Magic Rule
	
	TRANSLATE, DO NOT DENY
Když popis přesahuje RAW, převeď ho na attack, save, ability check, spell damage, reposition nebo temporary advantage. Cool idea může snížit DC, dát advantage nebo změnit consequence. Nemůže bez hodu odstranit celý objective encounter.



Critical Results
	Result
	Effect

	Natural 20 on node check
	Counts as 2 successes only if node is already Exposed; otherwise Exposes + grants advantage on next check.

	Natural 1 on node check
	Normal failure + DM chooses Pressure 1 or immediate minor pulse. No random permanent maiming.

	Critical hit vs node
	Double damage as normal; if 15+ thunder/slashing magical damage, may breach but brute-force consequence still applies.

	Counterspell check natural 20
	Cancel effect and reduce Pressure 1 once/arena.

	Death save natural 20
	Normal 5e recovery; environment does not immediately re-down unless fiction demands and DM avoids cheap targeting.





ASHES OF THAY — BOOK II
CA-08 · FAILURE & CONSEQUENCE MATRIX
Punishing, legible, never a dead end

Failure Principles
• Failure mění cenu vstupu do Prison Core, ne právo pokračovat v příběhu.
• Use direct damage for immediate danger, Pressure for magical escalation, Structural Damage for future route cost, and Separation for tactical drama. Neházej všechny čtyři následky najednou.
• Downed postavy nejsou automaticky cílem environmental pulses, pokud pulse nemá jasnou plošnou fiction.
• NPCs mohou padnout na 0 HP, ale jejich permanentní smrt vyžaduje skutečné consequence window, ne náhodný bookkeeping crit.
• Žádný failed check neposkytne falešnou lore informaci. Dostaneš fragment pravdy plus cenu.
Consequence Matrix
	Trigger
	Primary consequence
	Alternative

	Failed safe node check
	2d6 force to actor
	Pressure +1 if direct damage would be repetitive.

	Second failure on same node
	Node DC +2 until ally changes method
	Bailiff immediately attempts repair / control.

	Support pylon destroyed
	Listed Structural / Pressure consequence
	Create persistent hazard in its zone.

	Fall into shaft
	4d6 bludgeoning, restrained, separated
	On successful edge catch: hanging, no damage.

	Pressure rises to 4
	Bridges difficult terrain
	Spawn one Chain Echo at isolated target.

	Pressure rises to 5
	Pylon takes 10 damage or Structural +1
	Crew may spend action to vent and prevent.

	Pressure reaches 6
	Catastrophic Transfer
	No TPK; force-move survivors toward Core with damage.

	Warden reforms
	45 HP, Pressure +1
	If NAME breached, reform fails.

	Round 8 ends
	Set Pressure 6
	Immediate transfer / costly access.



NPC Injury States
	State
	Rule

	Wounded
	Below half HP or narrative injury; no automatic mechanical penalty unless listed.

	Downed
	0 HP; death saves normal or use one Crew Rescue Clock of 2 rounds if simplifying NPC sheets.

	Separated
	Cannot use support action until rescued / reunited.

	Relic Strain
	After overusing one major support action, character loses reaction until end of next turn or takes 1d6 appropriate damage.

	Protected by player choice
	If Matthael spends action/resource to rescue, reward with tracker benefit or advantage rather than treating it as wasted turn.



Fail-Forward Opening
	Řetězy se nepřetrhnou. Udělají něco horšího: souhlasí. Celá aréna na jediný okamžik přijme, že vy jste další část nákladu, a otevře cestu dolů tím, že vás tam začne přesouvat.



Recovery Valves
	Problem
	Recovery option

	Two allies down
	Warden spends next turn on reclassification / node control instead of Multiattack; Crew gains a rescue window.

	Pressure 5 with no relay access
	A character may sacrifice action and take 2d6 force to vent Pressure -1 through any exposed node.

	All bridges lost
	ROOT or a rope / spell route can create one temporary 10ft path for a round; check DC 16.

	No progress after 3 rounds
	Barten Echo / Grudgebell reveals one safe sequence. Gain advantage, not an automatic success.

	Warden damage too high
	Reduce legendary actions by 1 until next Breach; narrate damaged timing.

	Encounter too easy
	Activate Bailiff B early or add one Chain Echo; do not inflate node HP mid-fight.



Example Costly Failure Chain
Failed MOTION check → Pressure +1. Arena Pulse pulls Eryn to edge; he catches chain. Matthael spends movement / action to rescue instead of attacking. That rescue earns advantage on Eryn’s next Rootbrace check. Failure created cost, changed the round, and produced a Crew beat without deleting progress.


ASHES OF THAY — BOOK II
CA-09 · ECHOES, NPCs & HIDDEN INFORMATION
What may speak, what must remain silent

Barten Echo
	Moment
	Allowed manifestation
	Major clue

	Approach / Echo point
	Tier II silhouette beside impossible prison cross-section.
	“Do not break every chain. Break the pattern.”

	First look at pylons
	Handwriting appears across three layers.
	ROOT, RELAY, GLASS are support logic, not prisoner definitions.

	Before Phase III
	Voice only, no full figure.
	“Up is not out. Up is pressure.”

	After victory
	No new conversation. One fading correction line.
	Preserve uncertainty about Barten’s physical status.



	
	BARTEN SAFETY
Echo cannot answer where he is, whether he is alive now, or when he returns. No durable personal object may be looted from the echo.



The Prisoner’s Pressure
• Before VOICE breach: felt as heatless breath, chain vibration, massive weight changing direction.
• After VOICE breach: one broken line may be heard, such as “Not… mine,” “Wrong… measure,” or “You are cutting the name, not the chain.”
• Do not say Anaxaster. Do not provide a full sentence that proves personality, allegiance, or innocence.
• The pressure may react differently to Ti, Frostfire, and draconic speech, but no bargain occurs here.


Red Veil
	State
	Use

	Absent
	Leave one blade-line mark or bypass clue. Do not teleport her into scene merely to explain mechanics.

	Present / low trust
	She helps once, withholds why she recognizes a node, and pursues her private copy objective.

	Present / moderate trust
	She warns that breaking support pylons will bury everyone and offers Red Step rescue.

	High trust
	She reveals a personal stake fragment, not true allegiance. Mechanical benefit remains bounded to one major intervention.



Caern Continuity
Chain Arena is not Caern’s spotlight. His expected Book II route diverges before entry. If the table insists he remains, use the one cameo support from CA-06 and then separate his red-leash pursuit after the arena. Do not convert him into permanent sixth Crew sheet.
Hidden Truth Table
	May reveal now
	Must remain hidden

	Beast collars and dragon-scale chain system share command rhythm.
	Full identity of the deeper hunger-force.

	Prison architecture has original, Netherese, and Thayan layers.
	Who moved the Prisoner and why.

	Network is classifying the wrong primary threat.
	Red Veil’s master / true allegiance.

	Pressure can eventually be sent upward through preserved architecture.
	Exact method and final cost of Matthael’s storm creation.

	The Prisoner is draconic-scale and conscious.
	Name Anaxaster until Prison Core reveal.





ASHES OF THAY — BOOK II
CA-10 · REWARDS & DISCOVERIES
Progress without premature payoff

Guaranteed Discoveries
• Containment has three definition functions: NAME, MOTION, VOICE.
• ROOT, RELAY, and GLASS are support / routing architecture and must survive long enough for controlled release.
• The collar network from the Kennel is derivative technology from the deeper chain timing system.
• The Prisoner is not the only signature being measured; the network’s classification logic is compromised.
• Pressure has an upward route, but the Crew does not yet know the full sky-vent procedure.
Physical Loot
	Loot
	Amount / function

	Warden Command Shard
	1 if Warden destroyed; grants advantage on one future check to interrupt a prison construct, then cracks.

	Relay Alignment Fuses
	2; each may grant +2 to one machine / warp relay check when consumed.

	Chain-Silver Ingot
	1–2 depending on Structural Damage; crafting material, not currency-only scrap.

	Rootglass Brace Fragment
	1 if ROOT survives; Eryn / crafting / structural repair hook.

	Seal Diagram Rubbing
	Automatic if Crew takes one minute; records NAME/MOTION/VOICE relationship.

	No Anaxaster Scale
	Reserved for actual release / relationship result.

	No Ti Echo Seed
	Reserved for final seal participation, not Arena access.





Mechanical Rewards by Result
	Result
	Reward in Prison Core

	Guardian Control 2
	One automatic success on first containment-control challenge OR negate first guardian reaction.

	Guardian Control 1
	Advantage on first control check.

	Structural Damage 0–1
	Safe retreat lane; first escape complication ignored.

	Structural Damage 2
	Normal route.

	Structural Damage 3–4
	Escape / Core architecture complication starts active.

	Pressure 0–2
	Core starts Quiet.

	Pressure 3–4
	Core starts Charged.

	Pressure 5
	Core starts Critical; one pressure pulse before negotiation.

	Echo Alignment 2
	Advantage to distinguish support architecture from prison definition once in Core.

	No separation
	All Crew enters together; support blocks available immediately.



Character Progression Seeds
	Character
	Seed

	Eryn
	Deepgreen Witness can identify “forced memory” in future Glass Dunes zones.

	Norbyn
	Grudgebell’s voice becomes clearer around containment timing.

	Mira
	Paradox angles connect blade geometry to relay weak points; relic still incomplete.

	Naevyra
	Confirms old radiant suppression was used as prison maintenance; relic still incomplete.

	Ti
	Draconic omen reaction intensifies, but no permanent Echo Seed yet.

	Matthael
	Silverstrain recognizes prison logic as something it can reject; true storm ability remains unformed.





ASHES OF THAY — BOOK II
CA-11 · TRANSITION TO PRISON CORE
Handoff, read-aloud, and state transfer

Gate Opening Read-Aloud — Clean Victory
	Třetí uzel nezhasne. Zapomene. Řetězy kolem centrálního daisu zůstanou celé, ale jejich napětí se změní, jako když ruka přestane svírat krk a začne držet dveře. Za nimi se černá stěna rozdělí po stříbrné linii. Z hloubky přijde dech dost velký na to, aby se voda v shaftu na okamžik zvedla ke stropu.



Gate Opening Read-Aloud — Costly / Transfer
	Vězení se neotevře. Udělá chybu. Mosty se nakloní, černá voda vyrazí vzhůru a pečeť ve stěně vás přepíše z vetřelců na náklad. Cesta do Core vznikne pod vašima nohama, násilná a příliš rychlá — ale vznikne.



State Handoff Card
	Field
	Carry forward

	Chain Breaches
	0–3; expected 2–3.

	Structural Damage
	0–4.

	Pressure
	0–6; if 6, reset to 5 after transfer, not 0.

	Guardian Control
	0–2.

	Crew Separation
	Who is in first Core zone / secondary route.

	Echo Alignment
	0–2.

	NPC injury / resources
	Exact current state.

	Intact pylons
	ROOT / RELAY / GLASS; each matters in controlled catastrophe.

	Loot / keys
	Command Shard, fuses, brace fragment, diagram.

	Storm status
	Still Storm Seed. True storm not formed.



Prison Core Starting Modifiers
	Arena result
	Core modifier

	NAME unbreached
	Prisoner reveal begins partially misclassified; first identity-related check disadvantage or DC +2.

	MOTION unbreached
	Prisoner remains physically pinned; release requires extra action / success.

	VOICE unbreached
	Initial communication is impossible until corrected; no bargain first round.

	ROOT destroyed
	No living support route; Eryn must rebuild before safe escape.

	RELAY destroyed
	Timing becomes unstable; Pressure rises faster.

	GLASS destroyed
	Magic cannot be cleanly redirected; sky-vent setup becomes riskier.



	
	FINAL LINE BEFORE REVEAL
The pressure behind the door does not ask who you are. It asks why the prison has been calling you by the same kind of name.



Before the Reveal
• Update full LIVE GAME SAVE and all six Arena trackers.
• State who crosses the threshold first and who is separated.
• Record intact pylons; they become real tools or liabilities in Controlled Catastrophe.
• Do not speak the Prisoner’s name until the next module’s reveal beat.
• Give the table a breath. Chain Arena ending is a threshold, not initiative round five with a new boss stapled on.


ASHES OF THAY — BOOK II
CA-12 · DM RUN SHEET
Quick encounter control

Start
	Tracker
	Start

	Breaches
	0/3

	Structural
	0/4

	Pressure
	1/6

	Control
	0/2

	Separated
	No

	Echo
	0/2



Objectives
• Breach NAME, MOTION, VOICE.
• Keep at least 2 of ROOT, RELAY, GLASS intact.
• Open Core Gate. Warden death alone is not victory.
Phases
	Phase
	Trigger
	Do

	I Measure
	Start–first breach / R2 end
	Warden dais-bound; 1 Bailiff; expose node.

	II Enforcement
	First breach / R3
	Warden mobile; Bailiff B; Seal Pulse.

	III Reversal
	Second breach
	Rotate bridges; Lockdown Chain; final node.

	IV Access
	Third breach
	One stabilisation round; seize / disable / rescue / enter.



Initiative 20
If RELAY active and unstabilised: Pressure +1. Then choose one pulse: Chain Sweep, Platform Rotation, Black-Water Draw, Seal Static, Glass Rain, Wrong Name. Pressure 4+: bridges difficult. Pressure 6: Catastrophic Transfer.
Warden Short Stats
AC 18; HP 175; +9 attacks; Multiattack 2× (2d8+5 slashing +1d6 force); Hook/Drag STR 16; Seal Pulse CON 16, 4d8; Lockdown DEX 16. 2 legendary actions: move, lash, Node Command (2).
Node Reminder
	Node
	While active
	Breach

	NAME
	Reform / mark
	2 checks DC17 or AC16 HP35; brute +Structural.

	MOTION
	Reach / pull
	2 checks DC16 or HP35; brute +Pressure.

	VOICE
	Suppress Help
	2 checks DC17 or HP35; brute +Pressure.



Support Reminder
ROOT = structure; RELAY = Pressure pulse; GLASS = spell redirection. Stabilise DC16–17. Destroying support is always expensive.
Update Save At
• Before initiative.
• After first breach / Phase II.
• After second breach / Phase III.
• After Arena resolution before Core.
	
	DO NOT FORGET
No Barten reunion. No Anaxaster name. No true storm. No dead-end failure.





ASHES OF THAY — BOOK II
CA-13 · FINAL ASSEMBLY & PRODUCTION NOTES
How this module fits the book

Canonical Placement
Rootglass Kennel aftermath → Lower Rootglass Bridge → Maintenance Spine / Barten Echo → Chain Arena → Prison Core → Controlled Catastrophe → Sky Vent / Release → Escape → Stormwake → Warp Ruins / Wrong Gate.
Module Boundaries
	This module owns
	Next module owns

	Arena battlefield, nodes, Warden, support pylons, Core access.
	Full Anaxaster reveal, negotiation, release decision.

	Pressure accumulation up to Core handoff.
	Controlled Catastrophe Engine and sky-vent procedure.

	Barten timing clue.
	No true Barten contact / reunion.

	Storm Seed escalation.
	Creation of the true Thaylambar storm.

	Core gate opening.
	Surface escape, storm-hearing, warp ruins, Wrong Gate.



Dependencies Before Live Play
• Fill current LIVE GAME SAVE from the last played state.
• Confirm Matthael level 9 or 10 and current max HP / spell slots.
• Resolve whether short rest occurs in Maintenance Spine before Arena.
• Resolve Caern departure and whether Red Veil is physically present.
• Select scaling row from CA-03 and write Warden HP on run sheet.
Post-Play Logging
• Record exact node order and methods used.
• Record intact / destroyed pylons.
• Record Warden outcome and loot.
• Record important Crew lines / injuries / relationship changes.
• Paste final LIVE GAME SAVE and Handoff Card into The Game canon log.
Version Lock
	
	CHAIN ARENA v1.0
This module supersedes the original generic Anti-Seal Guardian Arena and 5-success skill challenge. It does not supersede the Glass Dunes v2 Canon Lock, Revised Flow, or Barten Echo Alignment.



Next Module Queue
1. Prison Core / The Wrong Prisoner — reveal, negotiation, hostility and release conditions.
2. Controlled Catastrophe Engine — Integrity, Chain-Lock, Overload, Sky Vent and Escape clocks.
3. Stormwake & Wrong Gate — surface fight, hearing the storm, warp ruins and Kossuth misroute.
Change Log Template
	Version
	Date
	Change

	1.0
	2026-07-13
	Initial complete Chain Arena assembly.

	—
	—
	Post-play balance / continuity notes.

	—
	—
	Final Book II manuscript integration.



Chain Arena · Containment Spine  |  

