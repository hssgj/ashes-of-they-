# Preserved source — Ashes_of_Thay_Book_II_Controlled_Catastrophe_Engine_v1_0.docx

**Import date:** 2026-10-07

**Disposition:** DM FUNCTIONAL ENGINE v1.0. Future relative to current checkpoint; no release or catastrophe is marked played by this import.

**Original source:** `libfile_0b11ba7e9f088191a6ea74b9352d89fb` · `Ashes_of_Thay_Book_II_Controlled_Catastrophe_Engine_v1_0.docx`

**Source created:** 2026-07-13T14:23:42.275995Z

**Recovery:** Complete available text extraction (1542 reported lines, all line windows read). This is preserved source text, not a verbatim chat transcript or a newly designed module. Original pagination/table extraction may differ from the source layout.

**Extracted-text SHA-256:** `d1b0a2af9ffc188565baf30a9aed4aeef3c7ba27966f07c84f9ce3846b418653`

---

## Original extracted text























Ashes of Thay Book II - Controlled Catastrophe Engine

ASHES OF THAY · BOOK II · CATASTROPHE ENGINE
ASHES OF THAY — BOOK II
CONTROLLED CATASTROPHE ENGINE
The Prison Must Break Correctly · Complete Module v1.0

	
	MODULE PURPOSE
Kompletní systém od Anaxasterova release decision po únik na povrch. Převádí Chain Arena outcomes do pěti trackerů, dává Crew konkrétní role a uzamyká, že pravou storm vytvoří Matthael záměrným sky-ventem — nikoli náhodný fail.



	Field
	Value

	Canon position
	After Chain Arena and Anaxaster reveal; before Stormwake Surface.

	Recommended level
	Matthael 9–10 + Ti + core Crew support blocks.

	Duration
	90–180 minutes including release roleplay and escape.

	Primary question
	Can the Crew free Anaxaster, preserve an exit, and turn overload into sky instead of corpses?

	Hard truth
	A catastrophe is guaranteed only after the Crew chooses release. Its direction, cost, and loyalty are not.



Contents
	Part I
	Part II

	Live Save · CE-00 Canon Lock
	CE-08 Anaxaster Profile

	CE-01 Prison Core Bridge
	CE-09 Crew Actions

	CE-02 Tracker Engine
	CE-10 Spell Interactions

	CE-03 Round Engine
	CE-11 Failure & Last Choice

	CE-04 Chain-Lock Actions
	CE-12 Release & Escape

	CE-05 Sky Vent System
	CE-13 Storm States & Rewards

	CE-06 Catastrophe Pulses
	CE-14 Handoff & Run Sheet

	CE-07 Matthael’s Disagreement
	CE-15 Assembly & Version Lock





LIVE GAME SAVE — CATASTROPHE EXTENSION
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

	Slots 1st–5th
	— / — / — / — / —
	Riftblade
	charges / mode

	Concentration
	—
	Conditions / exhaustion
	—

	Silverstrain
	reacting / unstable / conduit
	Storm status
	Seed / forming / true

	Ti
	HP / condition / position
	Location
	Prison Core / escape zone



	Chain-Lock
	Integrity
	Overload
	Sky Vent
	Escape Ready
	Disposition

	__/6
	__/6
	__/8
	__/4
	__/3
	Hostile / Defiant / Bargained / Aligned



	
	Δ CHANGE
HP ___ | slots/SP ___ | condition ___ | Chain-Lock ___ | Integrity ___ | Overload ___ | Sky Vent ___ | Escape ___ | Anaxaster ___





ASHES OF THAY — BOOK II
CE-00 · CANON & INPUT LOCK
What enters the Engine

	
	CANON PURPOSE
Engine začíná po Anaxasterově reveal a rozhodnutí pokusit se o release. Převádí výsledek Chain Areny do kontrolované katastrofy, vytvoří pravou Thaylambar storm pouze Matthaelovým záměrným sky-ventem a dovede Crew na povrch.



Inputs from Chain Arena
	Input
	Range
	Engine use

	Chain Breaches
	0–3
	Starting Chain-Lock progress.

	Structural Damage
	0–4
	Starting Prison Integrity.

	Pressure
	0–6
	Starting Overload; Pressure 6 becomes Overload 5 after transfer.

	Guardian Control
	0–2
	Control 2 grants +1 starting Chain-Lock and one Warden override.

	Crew Separation
	yes/no
	Affects Escape Readiness and first support block.

	Echo Alignment
	0–2
	May grant advantage on one architecture / Silverstrain distinction.

	Intact pylons
	ROOT/RELAY/GLASS
	Unlock safe Integrity, timing, and sky-refraction options.



Derived Starting Values
	Tracker
	Formula

	Chain-Lock
	Start = Chain Breaches +1 if Guardian Control 2; maximum 4.

	Prison Integrity
	Start = 6 − Structural Damage; minimum 2.

	Overload
	Start = previous Pressure; if Pressure was 6, start at 5.

	Sky Vent
	Start 0. If RELAY and GLASS both intact, first Vent check has advantage.

	Escape Readiness
	Start 1 if no separation and Structural Damage 0–1; otherwise 0.

	Anaxaster Disposition
	Set by Prison Core scene: Hostile, Defiant, Bargained, or Aligned.



Hard Locks
• The full deeper hunger-force remains unnamed. It may recognize Silverstrain, but cannot explain itself.
• Barten does not physically appear. Any echo is limited to architecture / timing and cannot confirm present status.
• The true storm forms only when Matthael deliberately routes overload upward. Prison failure alone creates pressure, not the canonical storm.
• Anaxaster is now named and present; he is not automatically innocent, ally, or enemy.
• Failure changes storm quality, injuries, debt, and escape cost. It does not erase the dungeon payoff or produce a cheap TPK.
Required End State
The Engine must end in one of four states: Crowned Storm, Wounded Storm, Fractured Storm, or No-Storm Branch. The first three hand directly into Stormwake & Wrong Gate. No-Storm is a player-chosen alternate route, not a random failed roll.


ASHES OF THAY — BOOK II
CE-01 · PRISON CORE BRIDGE
Reveal, negotiation input, and starting geometry

Read-Aloud: The Wrong Prisoner
	Za pečetí není cela. Je tam horizont. Černý kámen klesá do žáru bez plamene a řetězy silné jako věže se sbíhají k tělu, které by se do žádné místnosti vejít nemělo. Když se otevře první oko, celé jezero nad vámi na okamžik zapomene, kterým směrem leží obloha. „Kdo,“ řekne hlas starší než zdejší stěny, „otevírá vězení Anaxastera?“



Core Zones
	Zone
	Function
	Hazard

	Threshold
	Crew entry and retreat anchor.
	First zone lost when Integrity reaches 1.

	Chain Crown
	Six final chain interfaces around central void.
	Checks here provoke chain backlash.

	Royal Scar
	Nearest safe speaking position to Anaxaster.
	Heat / pressure; CON save under hostility.

	Sky Conduit
	Vertical architecture through lake and wounded Weave.
	Dormant until Sky Vent progress 2.

	Root Support
	Living brace if ROOT survived.
	Absent / corrupted if ROOT destroyed.

	Relay Heart
	Timing engine if RELAY survived.
	Accelerates Overload if uncontrolled.

	Glass Lens
	Upward refraction chamber if GLASS survived.
	Violent shrapnel if broken under load.



Disposition Input
	Disposition
	How it starts
	Engine effect

	Hostile
	Crew attacked, betrayed, or threatens execution.
	Anaxaster uses one hostile pressure action each round; coordination checks DC +2.

	Defiant
	No agreement, but common enemy / survival is obvious.
	No help until Crew proves release is real.

	Bargained
	Specific terms accepted by both sides.
	One Anaxaster Assist per phase after first Chain-Lock progress.

	Aligned
	Crew offered recognition, truth, or meaningful risk and kept terms.
	Start Chain-Lock +1, once/engine prevent one Integrity loss.



Fast Negotiation Bridge
Pokud samostatný Prison Core social module ještě není odehraný, použij tři exchange beats. Neházej jeden Persuasion check za celý vztah.
1. Recognition: Crew prokáže, že ví, že Anaxaster je vězeň, ne mechanismus. Insight/History/Draconic DC 16.
2. Terms: Crew řekne, co přesně rozbije a co od něj požaduje. Persuasion/Intimidation DC 17; konkrétní nabídka může dát advantage.
3. Risk: někdo přijme osobní cenu nebo dá Anaxasterovi možnost odmítnout. No automatic roll; roleplay determines Defiant, Bargained, or Aligned.
	
	ATTACK PATH
Útok není zakázaný. Pokud Crew pokračuje v boji, nastav Hostile disposition a použij CE-08. Zničení bound projection nezkruší skutečného Anaxastera; rozbije jeho bezpečné rozhraní a release bude násilný.





ASHES OF THAY — BOOK II
CE-02 · TRACKER ENGINE
Five systems, one catastrophe

Tracker Summary
	Tracker
	Range
	Question

	Chain-Lock
	0–6
	Je definice vězně dost rozbitá, aby se mohl pohnout?

	Prison Integrity
	6–0
	Zůstane zachovaná cesta, vent a nosná konstrukce?

	Overload
	0–8
	Kolik wounded-Weave / chain / Silverstrain pressure je v systému?

	Sky Vent
	0–4
	Je energie nasměrovaná vzhůru místo skrz Crew?

	Escape Readiness
	0–3
	Kolik bezpečných rozhodnutí bylo připraveno ještě před release?



Chain-Lock
	Value
	State
	Effect

	0–2
	Bound
	Anaxaster cannot move; hostile pressure is limited.

	3–4
	Cracking
	Overload rises at end of each round.

	5
	Almost free
	Matthael may attempt Disagreement if Sky Vent 3+.

	6
	Released definition
	Final conduit action can free Anaxaster; without vent, Integrity immediately −2.



Prison Integrity
	Value
	State
	Effect

	6–5
	Stable
	No global penalty.

	4
	Cracked
	First failed movement check each round also deals 1d6 debris.

	3
	Failing
	One Core zone becomes difficult terrain; escape gains one complication.

	2
	Near collapse
	All structural DC +1; end-of-round Overload cannot be reduced below 4.

	1
	Breach
	Threshold begins collapsing; one separated route closes.

	0
	Collapse
	Immediate Last Choice sequence. Not a TPK.



Overload
	Value
	State
	Effect

	0–2
	Quiet / Charged
	Cosmetic pressure; no extra pulse.

	3
	Active
	One Catastrophe Pulse at initiative 20.

	4
	Recognizing
	Deeper pressure notices Silverstrain; Matthael hears nonverbal answer.

	5
	Tearing
	Pulse affects two zones or one zone at increased damage.

	6
	Critical
	Integrity −1 at end of round unless someone stabilises.

	7
	Catastrophic
	All conduit checks DC +2; release damage increases.

	8
	Last Choice
	Matthael must become conduit, abort release, or accept Fractured Storm.



Sky Vent & Escape
	Tracker
	Milestones

	Sky Vent 0–1
	No safe upward route. Overchannel cannot create canonical storm.

	Sky Vent 2
	Conduit visible; vent actions can be performed at range.

	Sky Vent 3
	Disagreement attempt unlocked at Chain-Lock 5+.

	Sky Vent 4
	Clean route; storm quality improves one tier.

	Escape 0
	No route prepared.

	Escape 1
	Threshold cleared / regroup point chosen.

	Escape 2
	One future escape beat can be auto-passed.

	Escape 3
	Two future consequences can be negated or one separated ally auto-recovered.





ASHES OF THAY — BOOK II
CE-03 · ROUND & PHASE ENGINE
When the prison stops pretending

Default Initiative
1. Matthael + Ti use normal initiative and full rules.
2. Mira/Eryn and Norbyn/Naevyra use two support blocks as in Chain Arena unless running full sheets.
3. Anaxaster acts on initiative 10 according to disposition.
4. Catastrophe Pulse resolves at initiative 20, losing ties, once Overload reaches 3.
5. At end of round: if Chain-Lock 3+, Overload +1; if Overload 6+, Integrity −1 unless prevented.
Phase I — Cut the Last Definition
	Trigger
	Objective
	Special

	Start until Chain-Lock 4.
	Advance Chain-Lock; read surviving supports; prepare escape.
	Overload rises only on failed release action or hostile Anaxaster action.



Phase II — The Deep Recognizes You
	Trigger
	Objective
	Special

	Chain-Lock 4 or Overload 4.
	Build Sky Vent and prevent Integrity loss.
	Silverstrain recognition scene; Catastrophe Pulse every round.



Phase III — Open the Sky
	Trigger
	Objective
	Special

	Chain-Lock 5 and Sky Vent 2+.
	Reach Sky Vent 3–4; position Crew; negotiate final pull.
	Anaxaster may take one assist or fury action each round.



Phase IV — Disagreement
	Trigger
	Objective
	Special

	Matthael chooses conduit action.
	Route overload upward and complete release.
	Time pauses for one decision beat; resolve CE-07.



Phase V — Release Event
Resolve release damage, Anaxaster disposition, storm quality, and immediate zone collapse. Then move directly into the four escape beats in CE-12. Do not begin a second full boss fight unless the player deliberately chooses the hostile projection path.
Soft Round Limit
	
	7 CORE ROUNDS
At end of round 7, set Overload to at least 7 and trigger Last Choice. The engine does not stall because everyone kept trying to heal the architecture forever.





ASHES OF THAY — BOOK II
CE-04 · CHAIN-LOCK ACTIONS
Breaking the definition, not every chain

Release Actions
	Method
	DC / roll
	Success
	Failure

	Arcana reclassification
	DC 17
	Chain-Lock +1.
	2d6 force or Overload +1.

	Investigation / tools
	DC 16
	Expose safe sequence; next release check advantage OR Chain-Lock +1 if RELAY intact.
	Lose action; Bailiff/Warden residue pulses.

	Athletics on crown chain
	DC 18
	Chain-Lock +1; no damage to support if ROOT intact.
	3d6 bludgeoning and Integrity −1 or let chain go.

	Nature / Deepgreen
	DC 17
	Separate living support from imposed binding; Chain-Lock +1 and protect ROOT.
	Rootglass restrains actor, escape DC 16.

	Grudgebell timing
	DC 16 or module action
	Chain-Lock +1 or cancel one backlash.
	Overload +1; bell rings wrong name.

	Anaxaster Royal Pull
	Assist action
	Chain-Lock +1 automatically.
	Always Overload +1; unavailable while Hostile unless bargain changes.

	Direct magical damage
	Node/object AC 17, HP 40
	At 0 HP Chain-Lock +1.
	Brute release: Integrity −1 and Overload +1.



Method Limits
• A single character cannot advance Chain-Lock more than once per round, even with Quickened Spell or Haste. Extra actions may stabilise, move, attack hazards, or prepare vent.
• The same skill may be reused only if fiction changes: another chain, new tool, different position, revealed sequence, or resource expenditure.
• Critical success on a release check grants +1 Chain-Lock and either Overload −1 or advantage on next related check. It does not grant +2 progress.
• At Chain-Lock 6 without Sky Vent 3, Integrity immediately −2 and Overload +1. This is the exact mistake Barten’s echo warned against.
Unbreached Arena Nodes
	Node still active
	Core consequence

	NAME
	First release check DC +2. A successful identity / recognition beat removes penalty.

	MOTION
	Chain-Lock maximum is 5 until one extra Athletics/Arcana DC 17 success.

	VOICE
	Anaxaster cannot provide assist or negotiate during round 1; correct with Arcana/Religion DC 17.

	All three breached
	No penalty; Crew understands the difference between supports and definition.





ASHES OF THAY — BOOK II
CE-05 · SKY VENT SYSTEM
Up is pressure

Vent Actions
	Method
	Requirement / DC
	Success

	Relay Alignment
	RELAY intact; Arcana/Investigation DC 16
	Sky Vent +1 and once reduce Overload 1.

	Glass Refraction
	GLASS intact; Arcana DC 17 or 10+ thunder damage into lens
	Sky Vent +1; first release blast avoids one Crew zone.

	Root Conduit
	ROOT intact; Nature DC 16
	Sky Vent +1 or Integrity +1; creates living route around broken shaft.

	Wounded Radiance
	Naevyra; Religion/Arcana DC 17
	Sky Vent +1; suppress false downward conduit for one round.

	Paradox Angle
	Mira; Investigation/Tools DC 17
	Sky Vent +1; next Matthael conduit check gains +2.

	Grudgebell Vertical Timing
	Norbyn; DC 16
	Sky Vent +1 if at 2+, or prevent one Overload increase.

	Rift Cut Through Lake
	Matthael; Riftblade attack AC 17
	Sky Vent +1 automatically; Overload +1 and Integrity −1 unless GLASS intact.

	Raw spell conduit
	Expend 4th+ slot; CHA(Arcana) DC 17
	Sky Vent +1; on failure slot spent and Overload +1.



Vent State
	Progress
	What exists

	0
	No route. Energy will explode laterally through Core.

	1
	A possible vertical seam; not stable enough for Matthael.

	2
	Conduit visible through lake / wounded Weave.

	3
	Conduit usable. Disagreement attempt unlocked at Chain-Lock 5+.

	4
	Conduit aligned. Storm quality improves and release damage decreases.



Destroyed Pylons
	Missing support
	Replacement

	ROOT
	Two Integrity successes from any methods before release, or accept Escape complication.

	RELAY
	Vent checks cannot reduce Overload; first Matthael conduit roll disadvantage unless Command Shard/fuses used.

	GLASS
	Sky Vent 4 requires one extra success or an expended 5th-level slot / Riftblade Rift mode; release damage +1d6.

	Two or more missing
	Crowned Storm impossible; Wounded or Fractured only.



Relay Fuses & Command Shard
• Relay Fuse: consume for +2 after a vent or timing roll, or prevent Overload +1 from failed machine interaction.
• Warden Command Shard: consume to treat RELAY as intact for one action or cancel one false conduit pulse.
• Rootglass Brace Fragment: consume / plant to prevent Integrity −1 once and create 10ft safe path.


ASHES OF THAY — BOOK II
CE-06 · CATASTROPHE PULSES
The prison, lake, and wounded Weave answer

Initiative 20 Pulse Table
	d6 / choose
	Pulse
	Effect

	1
	Chain Crown Backlash
	One release actor DEX save 16; 3d6 slashing/force, half success. Failure also pushed 10 ft.

	2
	Lake Inversion
	All in one zone STR save 16 or pulled 15 ft upward / toward shaft and prone.

	3
	Rootglass Rewrite
	One path becomes difficult terrain and restrains first entrant; STR/DEX 16 to escape.

	4
	Wounded-Weave Surge
	Concentration checks DC 15; one spellcaster reaction suppressed until next pulse.

	5
	False Sky
	Vent actor Arcana/Insight DC 17; failure loses progress opportunity and Overload +1, no false lore.

	6
	Deeper Recognition
	Matthael WIS or CHA save 16; failure 2d6 psychic and Silverstrain becomes Unstable; success gains advantage on next Disagreement-related roll.



Escalation
	Overload
	Pulse rule

	0–2
	No automatic pulse.

	3–4
	One pulse each round.

	5–6
	Choose two zones or add +1d6 to one damaging pulse.

	7
	Two different pulses; one must target architecture rather than a downed creature.

	8
	No normal pulse. Resolve Last Choice immediately.



DM Pulse Principle
	
	PRESSURE, NOT EXECUTION
Pulse má nutit Crew změnit plán, zachránit spojence nebo utratit resource. Nevybírej opakovaně efekt, který pouze doráží downed postavu bez nové volby.



Integrity Stabilisation
	Action
	DC
	Effect

	Athletics brace
	16
	Prevent next Integrity loss this round.

	Nature / Rootbrace
	16
	Integrity +1, maximum starting value; once per phase.

	Arcana / tools shunt
	17
	Move incoming structural loss into Overload +1 instead.

	Sacrifice support pylon
	No roll
	Prevent Integrity −2, but pylon becomes destroyed and consequences apply.

	Anaxaster Hold Weight
	Assist
	Prevent Integrity −1; unavailable Hostile, once per phase Bargained, twice Aligned.





ASHES OF THAY — BOOK II
CE-07 · MATTHAEL’S DISAGREEMENT
The moment the storm is made

Trigger Requirements
• Chain-Lock 5 or 6.
• Sky Vent at least 3.
• Matthael consciously chooses to become conduit rather than merely casting a spell at the machinery.
• The table understands that success creates the true Thaylambar storm and permanently changes the current arc state.
Choose Fuel
	Fuel
	Benefit
	Cost

	3 Sorcery Points
	Advantage on Disagreement check.
	SP spent.

	4th+ spell slot
	+2 to check and Overload −1 before roll.
	Slot spent.

	Riftblade — Rift
	Treat Sky Vent as +1 for requirements.
	Overload +1; Rift mode unavailable until short rest.

	Warden Command Shard
	Ignore RELAY destroyed disadvantage.
	Shard consumed.

	Body as conduit
	No resource required.
	On success take 3d6 force/psychic; on failure 5d6.



Disagreement Check
	Element
	Rule

	Base check
	CHA (Arcana) DC 18.

	DC +2
	Sky Vent only 3; GLASS destroyed without replacement; Overload 7.

	DC −1
	RELAY intact and stabilised; Anaxaster Aligned; Echo Alignment 2 used here.

	Advantage
	3 SP fuel, Guardian Control 2 override, or successful Deeper Recognition save.

	Success
	Overload is routed upward. Chain-Lock becomes 6 if it was 5. True storm begins forming.

	Natural 20
	Success; Overload −2 after conversion; one Crew zone ignores release damage.

	Failure
	Choose Abort, Reconfigure, or Force Through.

	Natural 1
	Integrity −1 before choice; still no automatic TPK or stolen agency.



Failure Choices
	Choice
	Result

	Abort
	No storm. Chain-Lock drops to 4, Anaxaster remains partially bound or tears free later; enter No-Storm Branch.

	Reconfigure
	Overload +1 and one other Crew member immediately takes a vent action; Matthael may retry next round, DC +1.

	Force Through
	Automatic success. Matthael takes 6d6 force/psychic, loses all remaining SP, gains 1 exhaustion, and storm quality cannot be Crowned.



Silverstrain Description Rule
	The thing below does not speak. It recognizes. For one impossible second the prison, the wounded Weave, and the silver fracture inside Matthael all agree on what he is supposed to become. Matthael’s answer is not a word. It is a refusal with weather behind it.



	
	DO NOT EXPLAIN THE DEEPER FORCE
Popiš recognition, hunger, pressure a nesouhlas. Neříkej původ Silverstrain, jméno Sea of Hunger ani proč Matthaela systém poznává.





ASHES OF THAY — BOOK II
CE-08 · ANAXASTER PRESSURE PROFILE
King, prisoner, weapon, witness

Assist Actions
	Action
	Effect

	Royal Pull
	Chain-Lock +1; Overload +1.

	Hold the Weight
	Prevent Integrity −1 this round.

	Remember the Sky
	Grant advantage on one Sky Vent action or Matthael check.

	Desert Crown
	Clear one Rootglass / debris zone and create 20ft safe path.

	Name the Debt
	After Crew honors bargain, convert Defiant → Bargained or Bargained → Aligned once.



Hostile Pressure Actions
	Action
	Effect

	Royal Roar
	WIS save 17 in one zone; frightened until end next turn, success immune 24h.

	Chain-Tail Sweep
	DEX save 17; 4d6 bludgeoning/force and prone, half/no prone success.

	Glass-Sand Breath
	30ft cone through projection; DEX save 17, 6d6 slashing/fire, half success; recharge narratively once.

	Refuse the Hand
	One coordination / social check automatically fails; Crew may still progress mechanically.

	Violent Pull
	Chain-Lock +1 and Overload +2; Anaxaster chooses timing, not Crew.



Bound Projection (Optional Combat)
	Stat
	Value

	AC / HP
	19 / 180

	Saves
	STR +10, CON +10, CHA +9

	Resistances
	fire, cold, lightning, force

	Immunities
	frightened; cannot be knocked prone while chains hold

	Attack
	Desert Fang +10, 3d10+6 piercing/fire

	Legendary actions
	2/round: sweep, move projection, glass burst

	At 0 HP
	Projection shatters; actual Anaxaster remains. Disposition locked Hostile, Integrity −1, Overload +2, Chain-Lock +1.



Disposition Changes
	Trigger
	Shift

	Crew keeps exact bargain term under pressure
	One step toward Aligned.

	Crew uses Anaxaster as disposable shield without consent
	One step toward Hostile.

	Ti speaks / acts draconically and is protected rather than offered
	May unlock one free Remember the Sky, not automatic friendship.

	Crew attacks after accepting bargain
	Immediately Hostile; Debt Marker unavailable.

	Crew aborts release to save everyone
	Defiant or Bargained depending honesty; not automatically betrayal.





ASHES OF THAY — BOOK II
CE-09 · CREW SPOTLIGHT ACTIONS
Everyone holds one piece of the disaster

Matthael
	Action
	Effect

	Frostfire Argument
	CHA(Arcana) DC 17: Chain-Lock +1 or Sky Vent +1; failure Overload +1 and 2d6 psychic. Once before Disagreement.

	Runic Lock
	Cancel one forced relocation, false conduit, or Integrity loss caused by a single pulse.

	Riftblade Control
	Freeze protects route; Scorch burns binding but Overload +1 on failure; Rift advances Vent or Lock with listed cost.

	Disagreement
	Resolve CE-07; this is the canonical storm-making action.



Ti
	Action
	Effect

	Draconic Ping
	Once/phase identify true chain, false vent, or safest escape direction.

	Final Seal Participation
	At Chain-Lock 5+, Ti can hold an alignment key: next release or vent check +1d4; failure may create Fracture Scar.

	Smoke Through the Seam
	Auto-deliver fuse/key across one blocked zone; if Overload 6+, DEX save 15 or Ti becomes separated until rescued.

	Heroic Witness
	If Ti remains beside Matthael during Disagreement, Matthael may reroll one d20 but Ti takes 2d6 force and marks Echo Seed eligibility.



Eryn / Mira
	Character action
	Effect

	Eryn — Rootbrace the World
	Nature DC 16: Integrity +1 or Escape +1; once/phase remove restraint from all in one zone.

	Eryn — Living Memory
	Identify support vs imposed binding; next related check advantage.

	Mira — Paradox Vent
	Investigation/Tools DC 17: Sky Vent +1; on critical success also Escape +1.

	Mira — Cut the Exit
	Escape +1 and one character ignores opportunity / hazard movement this round.



Norbyn / Naevyra
	Character action
	Effect

	Norbyn — Grudgebell Timing
	Cancel one Overload increase or add +1d4 to Chain-Lock/Vent check.

	Norbyn — Hold the Crown
	Athletics DC 16: prevent Integrity loss; on failure take 3d6 bludgeoning instead.

	Naevyra — Wounded Radiance
	Religion/Arcana DC 17: suppress false conduit; Sky Vent +1 or advantage on next save.

	Naevyra — Memory Warning
	Reaction: one ally +2 AC/save against pulse or Anaxaster pressure action.



Red Veil
	Action
	Effect

	Blade-Line Geometry
	Mark one vent / chain: next check +1d4.

	Red Step Rescue
	Reaction, 2/engine: move adjacent ally 15 ft away from collapse.

	Copy the Catastrophe
	Private objective at Sky Vent 3. Allowing it gives Vent +1 but changes trust / future faction state.

	Refuse Her Copy
	No main progress lost; she may still help based on trust.





ASHES OF THAY — BOOK II
CE-10 · SPELL & RULE INTERACTIONS
Strict 5e inside impossible architecture

Common Spell Rulings
	Spell / feature
	Ruling

	Shield
	Works normally against attacks; not saves or structural collapse.

	Misty Step
	Cross one visible gap; cannot carry ally. Useful in escape beats.

	Haste
	RAW limited extra action. It may Dash/Disengage or make one attack, not perform arbitrary Arcana check.

	Shatter
	10+ thunder damage exposes / damages chain interface; brute consequences still apply.

	Chromatic Orb — thunder
	Normal damage; can qualify for GLASS refraction or interface exposure.

	Cone of Cold
	Creature damage normally. May Freeze one route cosmetically; extra structural effect requires Arcana DC 16 or Riftblade interaction.

	Ray of Frost
	Slows projection / hazard creature only; not a free Integrity repair.

	Burning Hands
	Creature damage; careless use near ROOT may add Overload on failed control.

	Fear
	Anaxaster / constructs immune as appropriate.

	Detect Thoughts
	No readable mind in deeper pressure. On Anaxaster projection, only surface fury / intent; not hidden cosmic truth.

	Arcane Eye
	Can inspect vent route before initiative; grants advantage on first Vent check.

	Tiny Hut
	Casting time remains; cannot pause active catastrophe.

	Counterspell
	Can counter false conduit pulse as 4th-level effect; cannot counter the entire release.

	Dispel Magic
	DC 17 check = one safe Chain-Lock success or suppress one pulse source for round.

	Teleport / Dimension Door
	Dimension Door can rescue / bypass one escape beat if available. Teleport cannot safely target through this damaged network during Core event.



Creative Magic Translation
	
	SHOW, THEN PRICE
Silný nápad může dát advantage, snížit DC, nahradit jednu metodu nebo změnit consequence. Nemůže bez resource a hodu současně dokončit Chain-Lock, Sky Vent i escape.



Concentration & Damage
• Every damage instance causes normal concentration check. Do not add extra checks merely because the scene is loud.
• Structural movement without damage does not cause concentration check unless a rule explicitly says so.
• Release blast is one damage instance, not separate damage from fire, force, glass, and narrative screaming.


ASHES OF THAY — BOOK II
CE-11 · FAILURE & LAST CHOICE
The engine bends; it does not dead-end

Failure Matrix
	Trigger
	Primary consequence
	Alternative

	Failed Chain-Lock action
	2d6 force / actor displaced
	Overload +1.

	Failed Vent action
	Overload +1
	Lose one prepared advantage / fuse.

	Integrity 3
	Escape complication armed
	Close one route.

	Integrity 1
	Threshold collapsing
	Separate one support block unless rescued.

	Integrity 0
	Last Choice
	No instant death.

	Overload 7
	Conduit DC +2
	Anaxaster can absorb 1 point at cost of disposition / injury.

	Overload 8
	Last Choice
	Become conduit, abort, or Fractured Storm.

	Three downed allies
	Catastrophe pauses offensively for rescue window
	Integrity −1 instead of enemy damage.

	Round 7 end
	Overload at least 7
	Force decision, not endless rolling.



Last Choice Sequence
1. Freeze initiative. State exact current Chain-Lock, Integrity, Overload, Sky Vent, and who is separated.
2. Matthael chooses: Conduit, Abort, or Let Anaxaster Tear Free.
3. Conduit uses CE-07, with Force Through available even after failure.
4. Abort creates No-Storm Branch; Crew retreats / seals partial breach, Anaxaster relationship changes.
5. Tear Free creates Fractured Storm only if Matthael still opens any upward seam; otherwise violent lateral collapse and no canonical storm.
Recovery Valves
	Problem
	Valve

	Resources nearly empty
	Body-as-conduit option exists; costly but playable.

	Vent progress stalled
	Anaxaster Remember the Sky, Red Veil copy, Command Shard, or 4th+ slot can create route.

	Integrity collapsing
	Sacrifice one pylon, Rootglass fragment, or Anaxaster Hold Weight.

	Crew separated
	Spend Escape Readiness or dedicate one support action; no arbitrary off-screen loss.

	Hostile Anaxaster dominating
	Breaking projection advances violent release and removes repeated actions.

	Encounter too easy
	Start pulses at Overload 2 or make private Red Veil objective active; do not secretly raise all DCs.





ASHES OF THAY — BOOK II
CE-12 · RELEASE & ESCAPE
Four beats out of the collapsing prison

Release Quality
	State
	Requirements
	Release blast

	Controlled
	Vent 4; Integrity 3+; Overload ≤6.
	All in Core DEX or CON save 16; 3d6 force/fire, half success.

	Violent
	Vent 3; Integrity 1–2 or Overload 7.
	Save 17; 5d6 force/fire/glass, half success; one route closes.

	Fractured
	Force Through, Integrity 0, or Vent below 3 with last-second seam.
	Save 17; 6d6 mixed damage, half; separation check and storm fractured.

	Abort / No Storm
	Matthael aborts conduit.
	No release blast; retreat / partial collapse consequences instead.



Escape Readiness Spend
• Spend 1 to automatically pass one escape beat after describing the prepared route.
• Spend 1 to recover one separated ally into current zone.
• Spend 1 to negate damage consequence from one failed beat, but movement still costs time.
• At Escape 3, one point may rescue an NPC without consuming Matthael’s action.
Beat 1 — Leave the Core
	Lead options
	DC
	Failure

	Athletics / Nature / Arcana
	16
	2d6 debris and one character starts next beat restrained.

	Anaxaster cooperative
	Automatic
	He holds opening; disposition cannot be Hostile.

	Misty Step / movement magic
	Normal spell
	Pass self; ally still needs route.



Beat 2 — Cross the Broken Spine
	Lead options
	DC
	Failure

	Acrobatics / Survival / Mira route
	16
	4d6 fall/catch damage or separation.

	ROOT route intact
	Advantage
	No difficult terrain.

	Dimension Door / equivalent
	Automatic for carried targets
	Consumes spell normally.



Beat 3 — Outrun Black Water
	Lead options
	DC
	Failure

	Athletics / Perception / Grudgebell timing
	16
	2d6 bludgeoning and lose one carried object or take 1 extra round.

	Anaxaster Desert Crown
	Automatic once
	Clears one route if Bargained/Aligned.

	Ti scout
	+1d4
	Ti must not already be separated.



Beat 4 — Break the Surface Seal
	Lead options
	DC
	Failure

	Arcana / Athletics / Riftblade
	17
	3d6 force; emerge scattered across shore zones.

	True storm forming
	Advantage
	The upward pressure is now helping.

	No-Storm branch
	DC 18
	Seal resists; Anaxaster or Crew must pay extra cost.



	
	ESCAPE FAILURE
A failed beat changes damage, timing, location, lost gear, or separation. It never says “you remain underground and cannot continue.”





ASHES OF THAY — BOOK II
CE-13 · STORM STATES & REWARDS
What the catastrophe creates

Storm Classification
	Storm
	Requirements
	Next-module effect

	Crowned Storm
	Vent 4; Integrity 3+; Overload ≤5 after conversion; no Force Through.
	Stable red-silver crown. First storm-listening check advantage; warp power cleaner.

	Wounded Storm
	Vent 3–4; Integrity 1+; Overload 6–7.
	Powerful but unstable. Normal Stormwake; one hazard starts active.

	Fractured Storm
	Force Through, Integrity 0, missing major supports, or violent release.
	Storm answers in broken voices; warp activation easier to power but harder to aim.

	No Storm
	Matthael aborts and no upward seam is opened.
	Alternate route required; Wrong Gate cannot proceed as planned without new source.



Anaxaster Outcome
	Outcome
	Reward / debt

	Aligned release
	Anaxaster Debt Marker; one safe route / future intervention; possible Scale Fragment.

	Bargained release
	Debt Marker only if terms honored; Barten network clue; relationship remains dangerous.

	Defiant release
	No debt, but he does not attack during escape; future meeting neutral-hostile.

	Hostile / violent release
	Long-term enemy mark; projection shards / scale material may still remain.

	Abort
	Anaxaster remains partly bound or becomes future crisis; no automatic death / erasure.



Ti Outcome
	Condition
	Result

	Ti participates in final alignment and survives
	Eligible for Anaxaster Echo Seed.

	Anaxaster Bargained/Aligned
	Echo Seed is stable omen milestone, not possession.

	Hostile / Fractured release
	Ti may instead gain one Fracture Scar; future draconic omen checks more intense.

	Ti protected by Crew during release
	Anaxaster notices; improves future relationship by one narrative step.



Barten Clue
	
	ALLOWED CLUE
Anaxaster can confirm that Barten’s signature touched the gate / prison network but was not held in this chamber. He may identify a direction, relay family, or warning — never Barten’s exact current location or guaranteed survival.



Matthael Consequence
• True storm creation is a narrative milestone, not a free reusable spell after this scene.
• Force Through grants 1 exhaustion and visible Frostfire fracture until recovery; do not add permanent mechanical penalty without later player-facing choice.
• Crowned/Wounded success establishes that Matthael can later learn to hear the storm. The actual discovery happens in Stormwake, not inside Core.


ASHES OF THAY — BOOK II
CE-14 · HANDOFF & DM RUN SHEET
Ready for Stormwake

Handoff Card
	Field
	Record

	Storm state
	Crowned / Wounded / Fractured / None

	Anaxaster
	Hostile / Defiant / Bargained / Aligned; free / partial / bound

	Debt Marker
	yes/no; exact term

	Ti
	Echo Seed / Fracture Scar / none

	Matthael
	HP, SP, slots, exhaustion, Silverstrain state

	Crew injuries
	exact HP / conditions / separation

	Intact supports
	ROOT / RELAY / GLASS

	Final Integrity / Overload
	values at release

	Barten clue
	exact wording revealed

	Surface emergence
	shore / dunes / ruins / scattered zones

	Warp resources
	fuses, Command Shard, storm quality modifier



Quick Run Order
1. Set inputs and disposition.
2. Advance Chain-Lock while preparing Escape.
3. At Chain-Lock 4 / Overload 4, reveal deeper recognition.
4. Build Sky Vent to 3–4.
5. Resolve Matthael’s Disagreement.
6. Classify release and storm.
7. Run four escape beats.
8. Update Live Game Save and handoff to Stormwake.
One-Line Reminders
	System
	Reminder

	Chain-Lock
	Need 6; direct damage costs structure.

	Integrity
	0 triggers Last Choice, not death.

	Overload
	8 forces decision.

	Sky Vent
	3 unlocks Disagreement; 4 improves storm.

	Escape
	Spend to auto-pass / rescue / negate consequence.

	Anaxaster
	Disposition determines assist or pressure action.

	Storm
	Only Matthael’s deliberate upward routing creates it.



	
	NEXT MODULE
Stormwake & Wrong Gate begins on the surface: the storm fully establishes, Matthael discovers he can hear it during conflict, Crew finds warp ruins, powers them, and arrives at the Temple of Kossuth by mistake.





ASHES OF THAY — BOOK II
CE-15 · ASSEMBLY & VERSION LOCK
Production notes

Canonical Placement
Chain Arena → Prison Core reveal / disposition → Controlled Catastrophe Engine → Release → Escape → Stormwake Surface → Warp Ruins → Wrong Gate → Temple of Kossuth.
Module Boundaries
	This module owns
	Next module owns

	Final release mechanics, Integrity, Overload, Sky Vent, Disagreement, escape.
	Surface battle and environmental storm behavior.

	Creation and classification of the true storm.
	Matthael learning to hear / command its immediate rhythm.

	Anaxaster release outcome and debt.
	Anaxaster’s surface departure / intervention if present.

	Barten network clue boundary.
	Warp ruin discovery and misroute.

	Crew emergence state.
	Wrong Arrival at Temple of Kossuth.



Before Live Play
• Complete Chain Arena and copy its Handoff Card.
• Resolve Anaxaster disposition through Prison Core roleplay or CE-01 fast bridge.
• Fill exact Live Game Save.
• Mark intact ROOT / RELAY / GLASS and available fuses / Command Shard.
• Choose whether Red Veil is present and whether her private copy objective is active.
Post-Play Log
• Record exact Disagreement roll, fuel, and whether Force Through was used.
• Record storm state and the visual / words used at creation.
• Record Anaxaster bargain terms and whether Crew kept them.
• Record Ti outcome, Barten clue, injuries, lost items, and surface emergence zone.
• Paste final save + handoff into The Game canon log.
	
	CONTROLLED CATASTROPHE ENGINE v1.0
Supersedes the original automatic overload + generic 5-success escape challenge. Does not supersede Glass Dunes v2 Canon Lock or Chain Arena v1.0.



Next Module Queue
1. Stormwake & Wrong Gate — surface conflict, storm-hearing, warp ruins, misroute.
2. Final Glass Dunes Assembly — merge Canon Lock, Chain Arena, Prison Core bridge, Catastrophe Engine, and Stormwake into the book-ready dungeon.
Controlled Catastrophe Engine  |  

