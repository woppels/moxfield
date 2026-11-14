===accordion
===panel: Core Combos

**Ultron the Annihilator — 101 active C configurations and 14 active T configurations.**

Entries are retained from the supplied catalog; active status means all named required cards are in decklist(5).txt, not a fresh rules certification. IDs remain stable. Removed-card entries are archived below.

<a id="c001"></a>
===accordion
===panel: C001: Gravecrawler + Phyrexian Altar

[[symbol:b]]

Cards Required:
- [[Gravecrawler]]
- [[Phyrexian Altar]]

Prerequisites:
- Gravecrawler and Phyrexian Altar on the battlefield.
- You control an additional Zombie.

Steps:
1. Sacrifice Gravecrawler to Phyrexian Altar.
2. Resolve the relevant triggers and obtain [[symbol:b]] from Phyrexian Altar. Resolve the life-gain trigger before continuing if using Sephiroth or Zulaport. Resolve any outlet damage, mill, counter, or surveil ability.
3. Use [[symbol:b]] from the Altar or sacrifice the Treasure for [[symbol:b]], then cast Gravecrawler from your graveyard while you control the other Zombie.
4. Resolve Reservoir life gain if present; Gravecrawler entering untaps Blasting Station if present. Repeat. The real Sephiroth transforms on its fourth death-trigger resolution; its emblem then maintains the drain.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Additional Zombie required. Net zero mana; repeatable creature deaths/casts. No artifact event intrinsically, so Ultron alone does not make this line lethal.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="c002"></a>
===accordion
===panel: C002: Sensei's Divining Top + Aetherflux Reservoir + Bolas's Citadel

[[symbol:b]]

Cards Required:
- [[Sensei's Divining Top]]
- [[Aetherflux Reservoir]]
- [[Bolas's Citadel]]

Prerequisites:
- All permanents on the battlefield.
- Your life total is at least 2.
- Your library is nonempty. Stop before an attempted draw from an empty library.

Steps:
1. With at least one card left in your library, tap Top to draw a card, then put Top on top of your library.
2. Cast Top from your library, paying 1 life through Bolas's Citadel.
3. Resolve all entry/cast payoffs. Fleshraker deals one damage for the Spawn and one for Top entering. Reservoir gains life according to the spell count if present.
4. Repeat only while library cards remain. With Reservoir, pay 50 life for each desired damage activation while retaining enough life to survive. This line is finite without an added replenishment/replacement effect.

Results:
- Finite repeated card access / resource conversion as described in the steps.
- Not an unbounded loop: library or graveyard fuel is consumed.
- Finite direct damage or Reservoir lethal potential, subject to remaining resources.

Classification: Finite sequence.

Audit Notes:
- Finite: nonempty library, life >= 2. N <= starting library size; net life formula and Reservoir damage budget are in F02.

===endpanel
===endaccordion

<a id="c003"></a>
===accordion
===panel: C003: Warren Soultrader + Aetherflux Reservoir + Gravecrawler

[[symbol:b]]

Cards Required:
- [[Warren Soultrader]]
- [[Aetherflux Reservoir]]
- [[Gravecrawler]]

Prerequisites:
- All permanents on the battlefield.
- Your life total is at least 2.

Steps:
1. Sacrifice Gravecrawler to Warren Soultrader by paying 1 life.
2. Resolve the relevant triggers and obtain a Treasure from Warren Soultrader. Resolve the life-gain trigger before continuing if using Sephiroth or Zulaport. Resolve any outlet damage, mill, counter, or surveil ability.
3. Use [[symbol:b]] from the Altar or sacrifice the Treasure for [[symbol:b]], then cast Gravecrawler from your graveyard while you control the other Zombie.
4. Resolve Reservoir life gain if present; Gravecrawler entering untaps Blasting Station if present. Repeat. The real Sephiroth transforms on its fourth death-trigger resolution; its emblem then maintains the drain.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Direct lethal damage or life loss through the named payoff.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Life >= 2; Warren is the other Zombie. Reservoir life gain grows on every cast; directly lethal through Reservoir.

===endpanel
===endaccordion

<a id="c004"></a>
===accordion
===panel: C004: Gravecrawler + Pitiless Plunderer + Altar of Dementia

[[symbol:b]]

Cards Required:
- [[Gravecrawler]]
- [[Pitiless Plunderer]]
- [[Altar of Dementia]]

Prerequisites:
- Pitiless Plunderer and Altar of Dementia on the battlefield.
- You control an additional Zombie
- You control another Zombie.
- Gravecrawler is on the battlefield, or [[symbol:b]] is available for its first graveyard cast.

Steps:
1. Sacrifice Gravecrawler to Altar of Dementia.
2. Resolve the relevant triggers and obtain a Treasure from Pitiless Plunderer. Resolve the life-gain trigger before continuing if using Sephiroth or Zulaport. Resolve any outlet damage, mill, counter, or surveil ability.
3. Use [[symbol:b]] from the Altar or sacrifice the Treasure for [[symbol:b]], then cast Gravecrawler from your graveyard while you control the other Zombie.
4. Resolve Reservoir life gain if present; Gravecrawler entering untaps Blasting Station if present. Repeat. The real Sephiroth transforms on its fourth death-trigger resolution; its emblem then maintains the drain.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Repeatable mill; actual cards milled are library-bounded, and emptying a library is not by itself immediate elimination.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Start Gravecrawler on battlefield, or pay initial [[symbol:b]] to cast from graveyard. Additional Zombie required. Treasure pays each recast; net zero.

===endpanel
===endaccordion

<a id="c005"></a>
===accordion
===panel: C005: The Ghoul, Gunslinger + Gravecrawler + Altar of Dementia

[[symbol:b]]

Cards Required:
- [[The Ghoul, Gunslinger]]
- [[Gravecrawler]]
- [[Altar of Dementia]]

Prerequisites:
- All permanents on the battlefield.

Steps:
1. Sacrifice Gravecrawler to Altar of Dementia.
2. Resolve the relevant triggers and obtain a Treasure from The Ghoul, Gunslinger, targeting yourself. Resolve the life-gain trigger before continuing if using Sephiroth or Zulaport. Resolve any outlet damage, mill, counter, or surveil ability.
3. Use [[symbol:b]] from the Altar or sacrifice the Treasure for [[symbol:b]], then cast Gravecrawler from your graveyard while you control the other Zombie.
4. Resolve Reservoir life gain if present; Gravecrawler entering untaps Blasting Station if present. Repeat. The real Sephiroth transforms on its fourth death-trigger resolution; its emblem then maintains the drain.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Repeatable mill; actual cards milled are library-bounded, and emptying a library is not by itself immediate elimination.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- The Ghoul supplies the additional Zombie; target yourself for its Treasure. Accumulate two rad counters per loop. Avoid taking a later rad upkeep if it would be dangerous; win first.

===endpanel
===endaccordion

<a id="c006"></a>
===accordion
===panel: C006: Pitiless Plunderer + Altar of Dementia + Stridehangar Automaton

[[symbol:b]]

Cards Required:
- [[Pitiless Plunderer]]
- [[Altar of Dementia]]
- [[Stridehangar Automaton]]

Prerequisites:
- All permanents on the battlefield.
- You control another creature.

Steps:
1. Sacrifice an extra suitable creature to Altar of Dementia.
2. Pitiless Plunderer creates a Treasure. Stridehangar replaces that event with a Treasure plus a Thopter; the Thopter is 2/2 with its anthem.
3. Resolve the outlet ability and any Station untap triggers. Sacrifice the replacement Thopter through the same outlet.
4. Repeat. Keep Plunderer, Stridehangar and any creature outlet alive. Retain Treasures or sacrifice them for colored mana; do not count a spent Treasure twice.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Repeatable mill; actual cards milled are library-bounded, and emptying a library is not by itself immediate elimination.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Extra starter creature; artifact creature for Ravager/KCI/Grinding. Keep Plunderer, Stridehangar and any creature outlet alive. Treasures accumulate; outlet outputs are in F03.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="c007"></a>
===accordion
===panel: C007: Pitiless Plunderer + Stridehangar Automaton + Arcbound Ravager

[[symbol:b]]

Cards Required:
- [[Pitiless Plunderer]]
- [[Stridehangar Automaton]]
- [[Arcbound Ravager]]

Prerequisites:
- All permanents on the battlefield.
- You control another artifact creature.

Steps:
1. Sacrifice an extra suitable creature to Arcbound Ravager.
2. Pitiless Plunderer creates a Treasure. Stridehangar replaces that event with a Treasure plus a Thopter; the Thopter is 2/2 with its anthem.
3. Resolve the outlet ability and any Station untap triggers. Sacrifice the replacement Thopter through the same outlet.
4. Repeat. Keep Plunderer, Stridehangar and any creature outlet alive. Retain Treasures or sacrifice them for colored mana; do not count a spent Treasure twice.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily many +1/+1 counters on the surviving counter source.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Extra starter creature; artifact creature for Ravager/KCI/Grinding. Keep Plunderer, Stridehangar and any creature outlet alive. Treasures accumulate; outlet outputs are in F03.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="c008"></a>
===accordion
===panel: C008: Dross Scorpion + Retrofitter Foundry + Ashnod's Altar

[[symbol:c]]

Cards Required:
- [[Dross Scorpion]]
- [[Retrofitter Foundry]]
- [[Ashnod's Altar]]

Prerequisites:
- All permanents on the battlefield.
- [[symbol:2]] available

Steps:
1. Pay [[symbol:2]] and tap Retrofitter Foundry to create a Servo.
2. Sacrifice the Servo to Ashnod's Altar, adding [[symbol:c]][[symbol:c]].
3. Resolve Dross Scorpion's death trigger targeting Foundry, untapping it.
4. Repeat using the recovered [[symbol:2]]; there is no net mana gain.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Foundry untapped, initial [[symbol:2]]; two generated and two spent every cycle. No net mana or growing Servo count.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="c009"></a>
===accordion
===panel: C009: Gravecrawler + Pitiless Plunderer + Ashnod's Altar

[[symbol:b]]

Cards Required:
- [[Gravecrawler]]
- [[Pitiless Plunderer]]
- [[Ashnod's Altar]]

Prerequisites:
- All permanents on the battlefield.
- You control an additional Zombie.

Steps:
1. Sacrifice Gravecrawler to Ashnod's Altar.
2. Resolve the relevant triggers and obtain a Treasure from Pitiless Plunderer. Resolve the life-gain trigger before continuing if using Sephiroth or Zulaport. Resolve any outlet damage, mill, counter, or surveil ability.
3. Use [[symbol:b]] from the Altar or sacrifice the Treasure for [[symbol:b]], then cast Gravecrawler from your graveyard while you control the other Zombie.
4. Resolve Reservoir life gain if present; Gravecrawler entering untaps Blasting Station if present. Repeat. The real Sephiroth transforms on its fourth death-trigger resolution; its emblem then maintains the drain.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Additional Zombie required; net two colorless per Gravecrawler recast after spending Treasure for [[symbol:b]].

===endpanel
===endaccordion

<a id="c010"></a>
===accordion
===panel: C010: The Ghoul, Gunslinger + Gravecrawler + Ashnod's Altar

[[symbol:b]]

Cards Required:
- [[The Ghoul, Gunslinger]]
- [[Gravecrawler]]
- [[Ashnod's Altar]]

Prerequisites:
- All permanents on the battlefield.

Steps:
1. Sacrifice Gravecrawler to Ashnod's Altar.
2. Resolve the relevant triggers and obtain a Treasure from The Ghoul, Gunslinger, targeting yourself. Resolve the life-gain trigger before continuing if using Sephiroth or Zulaport. Resolve any outlet damage, mill, counter, or surveil ability.
3. Use [[symbol:b]] from the Altar or sacrifice the Treasure for [[symbol:b]], then cast Gravecrawler from your graveyard while you control the other Zombie.
4. Resolve Reservoir life gain if present; Gravecrawler entering untaps Blasting Station if present. Repeat. The real Sephiroth transforms on its fourth death-trigger resolution; its emblem then maintains the drain.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- The Ghoul supplies Zombie and Treasure. Net two colorless; two rad counters per loop targeting yourself.

===endpanel
===endaccordion

<a id="c011"></a>
===accordion
===panel: C011: Imotekh the Stormlord + Nim Deathmantle + Ashnod's Altar

[[symbol:b]]

Cards Required:
- [[Imotekh the Stormlord]]
- [[Nim Deathmantle]]
- [[Ashnod's Altar]]

Prerequisites:
- All permanents on the battlefield.
- You control at least one nontoken artifact creature.
- [[symbol:2]] available

Steps:
1. Sacrifice another nontoken artifact creature to Ashnod's Altar, adding [[symbol:c]][[symbol:c]].
2. Pay [[symbol:4]] as Nim Deathmantle's trigger resolves, using the initial [[symbol:2]] buffer for the first return. Return the body and attach Deathmantle.
3. Imotekh triggers because an artifact card left your graveyard; create two Necrons.
4. Sacrifice one Necron to Ashnod's Altar for [[symbol:c]][[symbol:c]], then repeat the body sacrifice and return. Retain the other Necron, or sacrifice both for surplus mana. Preserve Imotekh.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Additional nontoken artifact body and initial [[symbol:2]]. Preserve Imotekh. Retain one Necron per neutral cycle, or sacrifice both for net two mana.

===endpanel
===endaccordion

<a id="c012"></a>
===accordion
===panel: C012: Nim Deathmantle + Ashnod's Altar + Marionette Apprentice

[[symbol:b]]

Cards Required:
- [[Nim Deathmantle]]
- [[Ashnod's Altar]]
- [[Marionette Apprentice]]

Prerequisites:
- All three named permanents are on the battlefield.
- You control a Servo created by Apprentice’s fabricate ability. Choose the Servo mode each time Apprentice returns.
- No additional mana is needed once the Servo is present.

Steps:
1. Sacrifice the Servo to Ashnod’s Altar, adding [[symbol:c]][[symbol:c]]. Apprentice triggers; each opponent loses 1 life.
2. Sacrifice Apprentice to Ashnod’s Altar, adding another [[symbol:c]][[symbol:c]]. Nim Deathmantle triggers.
3. Pay [[symbol:4]] as Deathmantle’s trigger resolves, returning Apprentice and attaching Deathmantle to it.
4. Resolve fabricate 1, choosing a Servo rather than a +1/+1 counter.
5. Repeat from step 1. Each cycle restores Apprentice plus Servo and drains every opponent.

Results:
- Arbitrarily many creature deaths, sacrifices, entries and artifact-token deaths.
- Lethal life loss to each opponent.
- Mana-neutral: four generated and four spent per cycle.

Classification: Unbounded resource loop.

Audit Notes:
- Restored from Archive for the Bowmasters → Apprentice swap. C013 is now archived.
- Apprentice does not trigger for its own death; the Servo death supplies the guaranteed drain.
- This is not a KCI substitution: Apprentice is not an artifact and cannot ordinarily be sacrificed to KCI.

===endpanel
===endaccordion

<a id="c014"></a>
===accordion
===panel: C014: Ultron the Annihilator + Nim Deathmantle + Ashnod's Altar

[[symbol:b]]

Cards Required:
- [[Ultron the Annihilator]]
- [[Nim Deathmantle]]
- [[Ashnod's Altar]]

Prerequisites:
- All permanents on the battlefield.
- Ultron the Annihilator has created a 2/2 Robot Villain artifact creature token.

Steps:
1. Sacrifice the Robot to Ashnod's Altar for [[symbol:2]] while Ultron is present; resolve its drain.
2. Sacrifice Ultron to Ashnod's Altar for [[symbol:2]], leaving it in the graveyard.
3. Pay [[symbol:4]] to Deathmantle, return Ultron, attach Deathmantle, then resolve its ETB to create the replacement Robot.
4. Repeat; two sacrifices exactly fund each return.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Direct lethal damage or life loss through the named payoff.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- A Robot already present; leave Ultron in graveyard for Deathmantle. Two sacrifices fund [[symbol:4]]; neutral and directly lethal.

===endpanel
===endaccordion

<a id="c015"></a>
===accordion
===panel: C015: Out of the Tombs + Skullclamp + Ashnod's Altar

[[symbol:b]]

Cards Required:
- [[Out of the Tombs]]
- [[Skullclamp]]
- [[Ashnod's Altar]]

Prerequisites:
- All permanents on the battlefield.
- Your library is empty.
- You control two suitable nontoken creatures that can be sacrificed.
- [[symbol:1]] available for the initial Skullclamp equip.
- Use recyclable bodies that survive Skullclamp unless the entry explicitly uses a 1-toughness auto-dying carrier.

Steps:
1. Pay [[symbol:1]] to equip Skullclamp to a recyclable body that survives its -1 toughness.
2. Sacrifice BOTH recyclable bodies to Ashnod's Altar before Clamp's draw trigger resolves.
3. Resolve resource triggers first, then resolve Clamp. Out of the Tombs replaces its two draws separately by returning both creature cards. Do not remove those cards with another recursion trigger first.
4. Spend one generated mana or Treasure on the next equip and repeat. Both bodies must return each cycle.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Empty library; two other recyclable nontoken bodies surviving Clamp (both artifacts for KCI), [[symbol:1]] equip seed. Four generated minus one equip = net three colorless.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="c016"></a>
===accordion
===panel: C016: Pitiless Plunderer + Ashnod's Altar + Stridehangar Automaton

[[symbol:b]]

Cards Required:
- [[Pitiless Plunderer]]
- [[Ashnod's Altar]]
- [[Stridehangar Automaton]]

Prerequisites:
- All permanents on the battlefield.
- You control another creature.

Steps:
1. Sacrifice an extra suitable creature to Ashnod's Altar.
2. Pitiless Plunderer creates a Treasure. Stridehangar replaces that event with a Treasure plus a Thopter; the Thopter is 2/2 with its anthem.
3. Resolve the outlet ability and any Station untap triggers. Sacrifice the replacement Thopter through the same outlet.
4. Repeat. Keep Plunderer, Stridehangar and any creature outlet alive. Retain Treasures or sacrifice them for colored mana; do not count a spent Treasure twice.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Extra starter creature; artifact creature for Ravager/KCI/Grinding. Keep Plunderer, Stridehangar and any creature outlet alive. Treasures accumulate; outlet outputs are in F03.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="c017"></a>
===accordion
===panel: C017: The Ooze + Stridehangar Automaton + Ashnod's Altar

[[symbol:c]]

Cards Required:
- [[The Ooze]]
- [[Stridehangar Automaton]]
- [[Ashnod's Altar]]

Prerequisites:
- All permanents on the battlefield.
- You control another creature with at least one +1/+1 counter on it.
- [[symbol:1]] available.

Steps:
1. Sacrifice the extra countered body to Ashnod's Altar. Ooze creates a Mutagen; Stridehangar adds a Thopter.
2. During your main phase with an empty stack, spend [[symbol:1]], tap and sacrifice Mutagen to put a +1/+1 counter on the Thopter.
3. Sacrifice that countered Thopter to Ashnod's Altar, creating the replacement Mutagen and Thopter through Ooze and Stridehangar.
4. Repeat the counter transfer and sacrifice. Each Mutagen activation must wait for an empty stack.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Extra countered creature (artifact for KCI), your main phase/empty stack for Mutagen. Generate two, spend one per repeated countered-body death: net one colorless.

===endpanel
===endaccordion

<a id="c018"></a>
===accordion
===panel: C018: Gravecrawler + Pitiless Plunderer + Blasting Station

[[symbol:b]]

Cards Required:
- [[Gravecrawler]]
- [[Pitiless Plunderer]]
- [[Blasting Station]]

Prerequisites:
- Pitiless Plunderer and Blasting Station on the battlefield.
- You control an additional Zombie
- You control another Zombie.
- Gravecrawler is on the battlefield, or [[symbol:b]] is available for its first graveyard cast.

Steps:
1. Sacrifice Gravecrawler to Blasting Station.
2. Resolve the relevant triggers and obtain a Treasure from Pitiless Plunderer. Resolve the life-gain trigger before continuing if using Sephiroth or Zulaport. Resolve any outlet damage, mill, counter, or surveil ability.
3. Use [[symbol:b]] from the Altar or sacrifice the Treasure for [[symbol:b]], then cast Gravecrawler from your graveyard while you control the other Zombie.
4. Resolve Reservoir life gain if present; Gravecrawler entering untaps Blasting Station if present. Repeat. The real Sephiroth transforms on its fourth death-trigger resolution; its emblem then maintains the drain.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Direct lethal damage or life loss through the named payoff.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Start Gravecrawler on battlefield, or pay initial [[symbol:b]] to cast from graveyard. Additional Zombie required. Treasure pays each recast; net zero.

===endpanel
===endaccordion

<a id="c019"></a>
===accordion
===panel: C019: The Ghoul, Gunslinger + Gravecrawler + Blasting Station

[[symbol:b]]

Cards Required:
- [[The Ghoul, Gunslinger]]
- [[Gravecrawler]]
- [[Blasting Station]]

Prerequisites:
- All permanents on the battlefield.

Steps:
1. Sacrifice Gravecrawler to Blasting Station.
2. Resolve the relevant triggers and obtain a Treasure from The Ghoul, Gunslinger, targeting yourself. Resolve the life-gain trigger before continuing if using Sephiroth or Zulaport. Resolve any outlet damage, mill, counter, or surveil ability.
3. Use [[symbol:b]] from the Altar or sacrifice the Treasure for [[symbol:b]], then cast Gravecrawler from your graveyard while you control the other Zombie.
4. Resolve Reservoir life gain if present; Gravecrawler entering untaps Blasting Station if present. Repeat. The real Sephiroth transforms on its fourth death-trigger resolution; its emblem then maintains the drain.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Direct lethal damage or life loss through the named payoff.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- The Ghoul supplies the additional Zombie; target yourself for its Treasure. Accumulate two rad counters per loop. Avoid taking a later rad upkeep if it would be dangerous; win first.

===endpanel
===endaccordion

<a id="c020"></a>
===accordion
===panel: C020: Pitiless Plunderer + Blasting Station + Stridehangar Automaton

[[symbol:b]]

Cards Required:
- [[Pitiless Plunderer]]
- [[Blasting Station]]
- [[Stridehangar Automaton]]

Prerequisites:
- All permanents on the battlefield.
- You control another creature.

Steps:
1. Sacrifice an extra suitable creature to Blasting Station.
2. Pitiless Plunderer creates a Treasure. Stridehangar replaces that event with a Treasure plus a Thopter; the Thopter is 2/2 with its anthem.
3. Resolve the outlet ability and any Station untap triggers. Sacrifice the replacement Thopter through the same outlet.
4. Repeat. Keep Plunderer, Stridehangar and any creature outlet alive. Retain Treasures or sacrifice them for colored mana; do not count a spent Treasure twice.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Direct lethal damage or life loss through the named payoff.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Extra starter creature; artifact creature for Ravager/KCI/Grinding. Keep Plunderer, Stridehangar and any creature outlet alive. Treasures accumulate; outlet outputs are in F03.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="c021"></a>
===accordion
===panel: C021: Gravecrawler + Pitiless Plunderer + Carrion Feeder

[[symbol:b]]

Cards Required:
- [[Gravecrawler]]
- [[Pitiless Plunderer]]
- [[Carrion Feeder]]

Prerequisites:
- Pitiless Plunderer and Carrion Feeder on the battlefield.
- Gravecrawler is on the battlefield, or [[symbol:b]] is available for its first graveyard cast.
- Carrion Feeder supplies the additional Zombie needed for Gravecrawler.

Steps:
1. Sacrifice Gravecrawler to Carrion Feeder.
2. Resolve the relevant triggers and obtain a Treasure from Pitiless Plunderer. Resolve the life-gain trigger before continuing if using Sephiroth or Zulaport. Resolve any outlet damage, mill, counter, or surveil ability.
3. Use [[symbol:b]] from the Altar or sacrifice the Treasure for [[symbol:b]], then cast Gravecrawler from your graveyard while you control the other Zombie.
4. Resolve Reservoir life gain if present; Gravecrawler entering untaps Blasting Station if present. Repeat. The real Sephiroth transforms on its fourth death-trigger resolution; its emblem then maintains the drain.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Arbitrarily many +1/+1 counters on the surviving counter source.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Carrion Feeder itself supplies the additional Zombie; no third Zombie is required. Treasure pays recasts; net zero mana.

===endpanel
===endaccordion

<a id="c022"></a>
===accordion
===panel: C022: The Ghoul, Gunslinger + Gravecrawler + Carrion Feeder

[[symbol:b]]

Cards Required:
- [[The Ghoul, Gunslinger]]
- [[Gravecrawler]]
- [[Carrion Feeder]]

Prerequisites:
- All permanents on the battlefield.

Steps:
1. Sacrifice Gravecrawler to Carrion Feeder.
2. Resolve the relevant triggers and obtain a Treasure from The Ghoul, Gunslinger, targeting yourself. Resolve the life-gain trigger before continuing if using Sephiroth or Zulaport. Resolve any outlet damage, mill, counter, or surveil ability.
3. Use [[symbol:b]] from the Altar or sacrifice the Treasure for [[symbol:b]], then cast Gravecrawler from your graveyard while you control the other Zombie.
4. Resolve Reservoir life gain if present; Gravecrawler entering untaps Blasting Station if present. Repeat. The real Sephiroth transforms on its fourth death-trigger resolution; its emblem then maintains the drain.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Arbitrarily many +1/+1 counters on the surviving counter source.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- The Ghoul supplies the additional Zombie; target yourself for its Treasure. Accumulate two rad counters per loop. Avoid taking a later rad upkeep if it would be dangerous; win first.

===endpanel
===endaccordion

<a id="c023"></a>
===accordion
===panel: C023: Pitiless Plunderer + Stridehangar Automaton + Carrion Feeder

[[symbol:b]]

Cards Required:
- [[Pitiless Plunderer]]
- [[Stridehangar Automaton]]
- [[Carrion Feeder]]

Prerequisites:
- All permanents on the battlefield.
- You control another creature.

Steps:
1. Sacrifice an extra suitable creature to Carrion Feeder.
2. Pitiless Plunderer creates a Treasure. Stridehangar replaces that event with a Treasure plus a Thopter; the Thopter is 2/2 with its anthem.
3. Resolve the outlet ability and any Station untap triggers. Sacrifice the replacement Thopter through the same outlet.
4. Repeat. Keep Plunderer, Stridehangar and any creature outlet alive. Retain Treasures or sacrifice them for colored mana; do not count a spent Treasure twice.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily many +1/+1 counters on the surviving counter source.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Extra starter creature; artifact creature for Ravager/KCI/Grinding. Keep Plunderer, Stridehangar and any creature outlet alive. Treasures accumulate; outlet outputs are in F03.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="c024"></a>
===accordion
===panel: C024: Imotekh the Stormlord + Clock of Omens + Tortured Existence

[[symbol:b]]

Cards Required:
- [[Imotekh the Stormlord]]
- [[Clock of Omens]]
- [[Tortured Existence]]

Prerequisites:
- All permanents on the battlefield.
- You control an artifact that can tap to produce at least [[symbol:b]]
- You have an artifact creature card in hand
- You have a SECOND artifact creature card in your graveyard.

Steps:
1. Tap the black-producing artifact (Vault of Whispers works) for [[symbol:b]].
2. Activate Tortured Existence for [[symbol:b]]: target the artifact creature card already in your graveyard and discard the other artifact creature card as the cost. Return the target to hand.
3. Resolve Imotekh to create two Necrons.
4. Tap both Necrons to Clock of Omens to untap the black-producing artifact.
5. Repeat with the hand/graveyard cards exchanged. Do not cast the exchanged cards.

Results:
- Arbitrarily many artifact-card returns and Necron-token creation events.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Two additional artifact creature cards alternate hand/graveyard. Add an untapped black-producing artifact; Vault of Whispers is present and works. Tap two Necrons to Clock each cycle; accumulate tapped Necrons.

===endpanel
===endaccordion

<a id="c025"></a>
===accordion
===panel: C025: Retrofitter Foundry + Clock of Omens + Stridehangar Automaton

[[symbol:c]]

Cards Required:
- [[Retrofitter Foundry]]
- [[Clock of Omens]]
- [[Stridehangar Automaton]]

Prerequisites:
- All permanents on the battlefield.
- You control a Thopter.

Steps:
1. Tap Foundry and sacrifice a Thopter to its Construct-making ability.
2. Create a Construct and, through Stridehangar, a replacement Thopter.
3. Tap both new tokens to Clock to untap Foundry.
4. Repeat with the replacement Thopter; Constructs accumulate.

Results:
- Arbitrarily many artifact-creature deaths and replacement token entries.
- Arbitrarily many Constructs accumulated (tapped in the Clock variant).
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Untapped Foundry and initial Thopter; no ongoing mana. Clock variant accumulates tapped Constructs, Scorpion variant untapped Constructs.

===endpanel
===endaccordion

<a id="c026"></a>
===accordion
===panel: C026: The Ooze + Clock of Omens + Stridehangar Automaton

[[symbol:c]]

Cards Required:
- [[The Ooze]]
- [[Clock of Omens]]
- [[Stridehangar Automaton]]

Prerequisites:
- All permanents on the battlefield.
- There is at least one card in a graveyard.

Steps:
1. Tap The Ooze to exile a graveyard card and create Mutagen plus a Stridehangar Thopter.
2. Tap the two new artifacts to Clock to untap The Ooze.
3. Repeat while graveyard cards remain; this consumes finite fuel.

Results:
- Finite repeated card access / resource conversion as described in the steps.
- Not an unbounded loop: library or graveyard fuel is consumed.

Classification: Finite sequence.

Audit Notes:
- Finite: one Ooze activation per available graveyard card. Two new artifacts pay Clock. No lasting graveyard-feed mechanism.

===endpanel
===endaccordion

<a id="c027"></a>
===accordion
===panel: C027: Sensei's Divining Top + Mystic Forge + Cloud Key

[[symbol:c]]

Cards Required:
- [[Sensei's Divining Top]]
- [[Mystic Forge]]
- [[Cloud Key]]

Prerequisites:
- All permanents on the battlefield (Cloud Key with "Artifact" chosen).
- Your library is nonempty. Stop before an attempted draw from an empty library.

Steps:
1. With at least one card left in your library, tap Top to draw a card, then put Top on top of your library.
2. Cast Top from your library, paying [[symbol:0]] through Mystic Forge and the cost reducer.
3. Resolve all entry/cast payoffs. Fleshraker deals one damage for the Spawn and one for Top entering. Reservoir gains life according to the spell count if present.
4. Repeat only while library cards remain. With Reservoir, pay 50 life for each desired damage activation while retaining enough life to survive. This line is finite without an added replenishment/replacement effect.

Results:
- Finite repeated card access / resource conversion as described in the steps.
- Not an unbounded loop: library or graveyard fuel is consumed.

Classification: Finite sequence.

Audit Notes:
- Finite: Key names Artifact; library nonempty. Zero recast cost, but each cycle draws one real card.

===endpanel
===endaccordion

<a id="c028"></a>
===accordion
===panel: C028: Dross Scorpion + Retrofitter Foundry + Krark-Clan Ironworks

[[symbol:c]]

Cards Required:
- [[Dross Scorpion]]
- [[Retrofitter Foundry]]
- [[Krark-Clan Ironworks]]

Prerequisites:
- All permanents on the battlefield.
- [[symbol:2]] available

Steps:
1. Pay [[symbol:2]] and tap Retrofitter Foundry to create a Servo.
2. Sacrifice the Servo to Krark-Clan Ironworks, adding [[symbol:c]][[symbol:c]].
3. Resolve Dross Scorpion's death trigger targeting Foundry, untapping it.
4. Repeat using the recovered [[symbol:2]]; there is no net mana gain.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Foundry untapped, initial [[symbol:2]]; two generated and two spent every cycle. No net mana or growing Servo count.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="c029"></a>
===accordion
===panel: C029: Retrofitter Foundry + Dross Scorpion + Stridehangar Automaton

[[symbol:c]]

Cards Required:
- [[Retrofitter Foundry]]
- [[Dross Scorpion]]
- [[Stridehangar Automaton]]

Prerequisites:
- All permanents on the battlefield.
- You control a Thopter.

Steps:
1. Tap Foundry and sacrifice a Thopter to its Construct-making ability.
2. Create a Construct and, through Stridehangar, a replacement Thopter.
3. Scorpion's Thopter-death trigger untaps Foundry before its token-making ability resolves; allow both abilities to resolve in that order.
4. Repeat with the replacement Thopter; Constructs accumulate.

Results:
- Arbitrarily many artifact-creature deaths and replacement token entries.
- Arbitrarily many Constructs accumulated (tapped in the Clock variant).
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Untapped Foundry and initial Thopter; no ongoing mana. Clock variant accumulates tapped Constructs, Scorpion variant untapped Constructs.

===endpanel
===endaccordion

<a id="c030"></a>
===accordion
===panel: C030: Sensei's Divining Top + Foundry Inspector + Mystic Forge

[[symbol:c]]

Cards Required:
- [[Sensei's Divining Top]]
- [[Foundry Inspector]]
- [[Mystic Forge]]

Prerequisites:
- All permanents on the battlefield.
- Your library is nonempty. Stop before an attempted draw from an empty library.

Steps:
1. With at least one card left in your library, tap Top to draw a card, then put Top on top of your library.
2. Cast Top from your library, paying [[symbol:0]] through Mystic Forge and the cost reducer.
3. Resolve all entry/cast payoffs. Fleshraker deals one damage for the Spawn and one for Top entering. Reservoir gains life according to the spell count if present.
4. Repeat only while library cards remain. With Reservoir, pay 50 life for each desired damage activation while retaining enough life to survive. This line is finite without an added replenishment/replacement effect.

Results:
- Finite repeated card access / resource conversion as described in the steps.
- Not an unbounded loop: library or graveyard fuel is consumed.

Classification: Finite sequence.

Audit Notes:
- Finite: Inspector makes Top free; library nonempty. Drawing a finite library prevents an unbounded loop.

===endpanel
===endaccordion

<a id="c031"></a>
===accordion
===panel: C031: Sensei's Divining Top + Glaring Fleshraker + Mystic Forge

[[symbol:c]]

Cards Required:
- [[Sensei's Divining Top]]
- [[Glaring Fleshraker]]
- [[Mystic Forge]]

Prerequisites:
- All permanents on the battlefield.
- [[symbol:1]] available
- Your library is nonempty. Stop before an attempted draw from an empty library.

Steps:
1. With at least one card left in your library, tap Top to draw a card, then put Top on top of your library.
2. Cast Top from your library, paying [[symbol:1]]; Fleshraker creates a Spawn, which you sacrifice for [[symbol:c]] to pay for the NEXT Top cast.
3. Resolve all entry/cast payoffs. Fleshraker deals one damage for the Spawn and one for Top entering. Reservoir gains life according to the spell count if present.
4. Repeat only while library cards remain. With Reservoir, pay 50 life for each desired damage activation while retaining enough life to survive. This line is finite without an added replenishment/replacement effect.

Results:
- Finite repeated card access / resource conversion as described in the steps.
- Not an unbounded loop: library or graveyard fuel is consumed.
- Finite direct damage or Reservoir lethal potential, subject to remaining resources.

Classification: Finite sequence.

Audit Notes:
- Finite: library nonempty and [[symbol:1]] seed. Spawn funds the next cast. Spawn AND Top entries each trigger damage: two to every opponent per iteration.

===endpanel
===endaccordion

<a id="c032"></a>
===accordion
===panel: C032: Gravecrawler + Pitiless Plunderer + Umbral Collar Zealot

[[symbol:b]]

Cards Required:
- [[Gravecrawler]]
- [[Pitiless Plunderer]]
- [[Umbral Collar Zealot]]

Prerequisites:
- Pitiless Plunderer and Umbral Collar Zealot on the battlefield.
- You control an additional Zombie
- You control another Zombie.
- Gravecrawler is on the battlefield, or [[symbol:b]] is available for its first graveyard cast.

Steps:
1. Sacrifice Gravecrawler to Umbral Collar Zealot.
2. Resolve the relevant triggers and obtain a Treasure from Pitiless Plunderer. Resolve the life-gain trigger before continuing if using Sephiroth or Zulaport. Resolve any outlet damage, mill, counter, or surveil ability.
3. Use [[symbol:b]] from the Altar or sacrifice the Treasure for [[symbol:b]], then cast Gravecrawler from your graveyard while you control the other Zombie.
4. Resolve Reservoir life gain if present; Gravecrawler entering untaps Blasting Station if present. Repeat. The real Sephiroth transforms on its fourth death-trigger resolution; its emblem then maintains the drain.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Repeatable surveil events; actual card access is library-bounded.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Start Gravecrawler on battlefield, or pay initial [[symbol:b]] to cast from graveyard. Additional Zombie required. Treasure pays each recast; net zero.

===endpanel
===endaccordion

<a id="c033"></a>
===accordion
===panel: C033: Warren Soultrader + Gravecrawler + Sephiroth, Fabled SOLDIER

[[symbol:b]]

Cards Required:
- [[Warren Soultrader]]
- [[Gravecrawler]]
- [[Sephiroth, Fabled SOLDIER]]

Prerequisites:
- All permanents on the battlefield.
- Your life total is at least 2.

Steps:
1. Sacrifice Gravecrawler to Warren Soultrader by paying 1 life.
2. Resolve the relevant triggers and obtain a Treasure from Warren Soultrader. Resolve the life-gain trigger before continuing if using Sephiroth or Zulaport. Resolve any outlet damage, mill, counter, or surveil ability.
3. Use [[symbol:b]] from the Altar or sacrifice the Treasure for [[symbol:b]], then cast Gravecrawler from your graveyard while you control the other Zombie.
4. Resolve Reservoir life gain if present; Gravecrawler entering untaps Blasting Station if present. Repeat. The real Sephiroth transforms on its fourth death-trigger resolution; its emblem then maintains the drain.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Direct lethal damage or life loss through the named payoff.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Life >= 2; Warren supplies the other Zombie. Resolve the death-drain life gain before continuing; net zero mana and direct lethal drain.

===endpanel
===endaccordion

<a id="c034"></a>
===accordion
===panel: C034: The Ghoul, Gunslinger + Gravecrawler + Umbral Collar Zealot

[[symbol:b]]

Cards Required:
- [[The Ghoul, Gunslinger]]
- [[Gravecrawler]]
- [[Umbral Collar Zealot]]

Prerequisites:
- All permanents on the battlefield.

Steps:
1. Sacrifice Gravecrawler to Umbral Collar Zealot.
2. Resolve the relevant triggers and obtain a Treasure from The Ghoul, Gunslinger, targeting yourself. Resolve the life-gain trigger before continuing if using Sephiroth or Zulaport. Resolve any outlet damage, mill, counter, or surveil ability.
3. Use [[symbol:b]] from the Altar or sacrifice the Treasure for [[symbol:b]], then cast Gravecrawler from your graveyard while you control the other Zombie.
4. Resolve Reservoir life gain if present; Gravecrawler entering untaps Blasting Station if present. Repeat. The real Sephiroth transforms on its fourth death-trigger resolution; its emblem then maintains the drain.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Repeatable surveil events; actual card access is library-bounded.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- The Ghoul supplies the additional Zombie; target yourself for its Treasure. Accumulate two rad counters per loop. Avoid taking a later rad upkeep if it would be dangerous; win first.

===endpanel
===endaccordion

<a id="c035"></a>
===accordion
===panel: C035: Warren Soultrader + Gravecrawler + Zulaport Cutthroat

[[symbol:b]]

Cards Required:
- [[Warren Soultrader]]
- [[Gravecrawler]]
- [[Zulaport Cutthroat]]

Prerequisites:
- All permanents on the battlefield.
- Your life total is at least 2.

Steps:
1. Sacrifice Gravecrawler to Warren Soultrader by paying 1 life.
2. Resolve the relevant triggers and obtain a Treasure from Warren Soultrader. Resolve the life-gain trigger before continuing if using Sephiroth or Zulaport. Resolve any outlet damage, mill, counter, or surveil ability.
3. Use [[symbol:b]] from the Altar or sacrifice the Treasure for [[symbol:b]], then cast Gravecrawler from your graveyard while you control the other Zombie.
4. Resolve Reservoir life gain if present; Gravecrawler entering untaps Blasting Station if present. Repeat. The real Sephiroth transforms on its fourth death-trigger resolution; its emblem then maintains the drain.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Direct lethal damage or life loss through the named payoff.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Life >= 2; Warren supplies the other Zombie. Resolve the death-drain life gain before continuing; net zero mana and direct lethal drain.

===endpanel
===endaccordion

<a id="c036"></a>
===accordion
===panel: C036: Pitiless Plunderer + Stridehangar Automaton + Grinding Station

[[symbol:b]]

Cards Required:
- [[Pitiless Plunderer]]
- [[Stridehangar Automaton]]
- [[Grinding Station]]

Prerequisites:
- All permanents on the battlefield.
- You control another artifact creature.

Steps:
1. Sacrifice an extra suitable creature to Grinding Station.
2. Pitiless Plunderer creates a Treasure. Stridehangar replaces that event with a Treasure plus a Thopter; the Thopter is 2/2 with its anthem.
3. Resolve the outlet ability and any Station untap triggers. Sacrifice the replacement Thopter through the same outlet.
4. Repeat. Keep Plunderer, Stridehangar and any creature outlet alive. Retain Treasures or sacrifice them for colored mana; do not count a spent Treasure twice.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Repeatable mill; actual cards milled are library-bounded, and emptying a library is not by itself immediate elimination.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Extra starter creature; artifact creature for Ravager/KCI/Grinding. Keep Plunderer, Stridehangar and any creature outlet alive. Treasures accumulate; outlet outputs are in F03.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="c037"></a>
===accordion
===panel: C037: Imotekh the Stormlord + Nim Deathmantle + Krark-Clan Ironworks

[[symbol:b]]

Cards Required:
- [[Imotekh the Stormlord]]
- [[Nim Deathmantle]]
- [[Krark-Clan Ironworks]]

Prerequisites:
- All permanents on the battlefield.
- You control at least one nontoken artifact creature.
- [[symbol:2]] available

Steps:
1. Sacrifice another nontoken artifact creature to Krark-Clan Ironworks, adding [[symbol:c]][[symbol:c]].
2. Pay [[symbol:4]] as Nim Deathmantle's trigger resolves, using the initial [[symbol:2]] buffer for the first return. Return the body and attach Deathmantle.
3. Imotekh triggers because an artifact card left your graveyard; create two Necrons.
4. Sacrifice one Necron to Krark-Clan Ironworks for [[symbol:c]][[symbol:c]], then repeat the body sacrifice and return. Retain the other Necron, or sacrifice both for surplus mana. Preserve Imotekh.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Additional nontoken artifact body and initial [[symbol:2]]. Preserve Imotekh. Retain one Necron per neutral cycle, or sacrifice both for net two mana.

===endpanel
===endaccordion

<a id="c038"></a>
===accordion
===panel: C038: Tortured Existence + Phyrexian Altar + Imotekh the Stormlord

[[symbol:b]]

Cards Required:
- [[Tortured Existence]]
- [[Phyrexian Altar]]
- [[Imotekh the Stormlord]]

Prerequisites:
- All permanents on the battlefield.
- You have two artifact creature cards, one in your graveyard and one in your hand; alternate them so EACH return from the graveyard triggers Imotekh.
- [[symbol:b]] available

Steps:
1. Begin with [[symbol:b]] available.
2. Activate Tortured Existence for [[symbol:b]]: target the artifact creature card already in your graveyard and discard the other artifact creature card as the cost. Return the target to hand.
3. Resolve Imotekh to create two Necrons.
4. Sacrifice one Necron to Phyrexian Altar for the next [[symbol:b]]; retain the other or sacrifice it for surplus mana.
5. Repeat with the hand/graveyard cards exchanged. Do not cast the exchanged cards.

Results:
- Arbitrarily many artifact-card returns and Necron-token creation events.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Two additional artifact creature cards alternate hand/graveyard; [[symbol:b]] seed. Two Necrons appear per exchange; sacrifice one for the next [[symbol:b]], retaining one, or both for surplus mana.

===endpanel
===endaccordion

<a id="c039"></a>
===accordion
===panel: C039: Ultron the Annihilator + Nim Deathmantle + Krark-Clan Ironworks

[[symbol:b]]

Cards Required:
- [[Ultron the Annihilator]]
- [[Nim Deathmantle]]
- [[Krark-Clan Ironworks]]

Prerequisites:
- All permanents on the battlefield.
- Ultron the Annihilator has created a 2/2 Robot Villain artifact creature token.

Steps:
1. Sacrifice the Robot to Krark-Clan Ironworks for [[symbol:2]] while Ultron is present; resolve its drain.
2. Sacrifice Ultron to Krark-Clan Ironworks for [[symbol:2]], leaving it in the graveyard.
3. Pay [[symbol:4]] to Deathmantle, return Ultron, attach Deathmantle, then resolve its ETB to create the replacement Robot.
4. Repeat; two sacrifices exactly fund each return.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Direct lethal damage or life loss through the named payoff.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- A Robot already present; leave Ultron in graveyard for Deathmantle. Two sacrifices fund [[symbol:4]]; neutral and directly lethal.

===endpanel
===endaccordion

<a id="c040"></a>
===accordion
===panel: C040: Out of the Tombs + Skullclamp + Krark-Clan Ironworks

[[symbol:b]]

Cards Required:
- [[Out of the Tombs]]
- [[Skullclamp]]
- [[Krark-Clan Ironworks]]

Prerequisites:
- All permanents on the battlefield.
- Your library is empty.
- You control two suitable nontoken artifact creatures that can be sacrificed.
- [[symbol:1]] available for the initial Skullclamp equip.
- Use recyclable bodies that survive Skullclamp unless the entry explicitly uses a 1-toughness auto-dying carrier.

Steps:
1. Pay [[symbol:1]] to equip Skullclamp to a recyclable body that survives its -1 toughness.
2. Sacrifice BOTH recyclable bodies to Krark-Clan Ironworks before Clamp's draw trigger resolves.
3. Resolve resource triggers first, then resolve Clamp. Out of the Tombs replaces its two draws separately by returning both creature cards. Do not remove those cards with another recursion trigger first.
4. Spend one generated mana or Treasure on the next equip and repeat. Both bodies must return each cycle.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Empty library; two other recyclable nontoken bodies surviving Clamp (both artifacts for KCI), [[symbol:1]] equip seed. Four generated minus one equip = net three colorless.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="c041"></a>
===accordion
===panel: C041: Pitiless Plunderer + Stridehangar Automaton + Krark-Clan Ironworks

[[symbol:b]]

Cards Required:
- [[Pitiless Plunderer]]
- [[Stridehangar Automaton]]
- [[Krark-Clan Ironworks]]

Prerequisites:
- All permanents on the battlefield.
- You control another artifact creature.

Steps:
1. Sacrifice an extra suitable creature to Krark-Clan Ironworks.
2. Pitiless Plunderer creates a Treasure. Stridehangar replaces that event with a Treasure plus a Thopter; the Thopter is 2/2 with its anthem.
3. Resolve the outlet ability and any Station untap triggers. Sacrifice the replacement Thopter through the same outlet.
4. Repeat. Keep Plunderer, Stridehangar and any creature outlet alive. Retain Treasures or sacrifice them for colored mana; do not count a spent Treasure twice.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Extra starter creature; artifact creature for Ravager/KCI/Grinding. Keep Plunderer, Stridehangar and any creature outlet alive. Treasures accumulate; outlet outputs are in F03.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="c042"></a>
===accordion
===panel: C042: The Ooze + Stridehangar Automaton + Krark-Clan Ironworks

[[symbol:c]]

Cards Required:
- [[The Ooze]]
- [[Stridehangar Automaton]]
- [[Krark-Clan Ironworks]]

Prerequisites:
- All permanents on the battlefield.
- You control another artifact creature with at least one +1/+1 counter on it.
- [[symbol:1]] available.

Steps:
1. Sacrifice the extra countered body to Krark-Clan Ironworks. Ooze creates a Mutagen; Stridehangar adds a Thopter.
2. During your main phase with an empty stack, spend [[symbol:1]], tap and sacrifice Mutagen to put a +1/+1 counter on the Thopter.
3. Sacrifice that countered Thopter to Krark-Clan Ironworks, creating the replacement Mutagen and Thopter through Ooze and Stridehangar.
4. Repeat the counter transfer and sacrifice. Each Mutagen activation must wait for an empty stack.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Extra countered creature (artifact for KCI), your main phase/empty stack for Mutagen. Generate two, spend one per repeated countered-body death: net one colorless.

===endpanel
===endaccordion

<a id="c043"></a>
===accordion
===panel: C043: Sensei's Divining Top + Mystic Forge + Semblance Anvil

[[symbol:c]]

Cards Required:
- [[Sensei's Divining Top]]
- [[Mystic Forge]]
- [[Semblance Anvil]]

Prerequisites:
- All permanents on the battlefield (Semblance Anvil with an artifact card exiled).
- Your library is nonempty. Stop before an attempted draw from an empty library.

Steps:
1. With at least one card left in your library, tap Top to draw a card, then put Top on top of your library.
2. Cast Top from your library, paying [[symbol:0]] through Mystic Forge and the cost reducer.
3. Resolve all entry/cast payoffs. Fleshraker deals one damage for the Spawn and one for Top entering. Reservoir gains life according to the spell count if present.
4. Repeat only while library cards remain. With Reservoir, pay 50 life for each desired damage activation while retaining enough life to survive. This line is finite without an added replenishment/replacement effect.

Results:
- Finite repeated card access / resource conversion as described in the steps.
- Not an unbounded loop: library or graveyard fuel is consumed.

Classification: Finite sequence.

Audit Notes:
- Finite: Anvil imprints an artifact card; library nonempty. Top is free, but actual draws still consume the library.

===endpanel
===endaccordion

<a id="c044"></a>
===accordion
===panel: C044: Out of the Tombs + Skullclamp + Phyrexian Altar

[[symbol:b]]

Cards Required:
- [[Out of the Tombs]]
- [[Skullclamp]]
- [[Phyrexian Altar]]

Prerequisites:
- All permanents on the battlefield.
- Your library is empty.
- You control two suitable nontoken creatures that can be sacrificed.
- [[symbol:1]] available for the initial Skullclamp equip.
- Use recyclable bodies that survive Skullclamp unless the entry explicitly uses a 1-toughness auto-dying carrier.

Steps:
1. Pay [[symbol:1]] to equip Skullclamp to a recyclable body that survives its -1 toughness.
2. Sacrifice BOTH recyclable bodies to Phyrexian Altar before Clamp's draw trigger resolves.
3. Resolve resource triggers first, then resolve Clamp. Out of the Tombs replaces its two draws separately by returning both creature cards. Do not remove those cards with another recursion trigger first.
4. Spend one generated mana or Treasure on the next equip and repeat. Both bodies must return each cycle.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Empty library; two other recyclable nontoken bodies surviving Clamp; [[symbol:1]] seed. Two generated minus one equip = net one colored mana.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="c045"></a>
===accordion
===panel: C045: Pitiless Plunderer + Phyrexian Altar + Stridehangar Automaton

[[symbol:b]]

Cards Required:
- [[Pitiless Plunderer]]
- [[Phyrexian Altar]]
- [[Stridehangar Automaton]]

Prerequisites:
- All permanents on the battlefield.
- You control another creature.

Steps:
1. Sacrifice an extra suitable creature to Phyrexian Altar.
2. Pitiless Plunderer creates a Treasure. Stridehangar replaces that event with a Treasure plus a Thopter; the Thopter is 2/2 with its anthem.
3. Resolve the outlet ability and any Station untap triggers. Sacrifice the replacement Thopter through the same outlet.
4. Repeat. Keep Plunderer, Stridehangar and any creature outlet alive. Retain Treasures or sacrifice them for colored mana; do not count a spent Treasure twice.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Extra starter creature; artifact creature for Ravager/KCI/Grinding. Keep Plunderer, Stridehangar and any creature outlet alive. Treasures accumulate; outlet outputs are in F03.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="c046"></a>
===accordion
===panel: C046: The Ooze + Stridehangar Automaton + Phyrexian Altar

[[symbol:c]]

Cards Required:
- [[The Ooze]]
- [[Stridehangar Automaton]]
- [[Phyrexian Altar]]

Prerequisites:
- All permanents on the battlefield.
- You control another creature with at least one +1/+1 counter on it.

Steps:
1. Sacrifice the extra countered body to Phyrexian Altar. Ooze creates a Mutagen; Stridehangar adds a Thopter.
2. During your main phase with an empty stack, spend [[symbol:1]], tap and sacrifice Mutagen to put a +1/+1 counter on the Thopter.
3. Sacrifice that countered Thopter to Phyrexian Altar, creating the replacement Mutagen and Thopter through Ooze and Stridehangar.
4. Repeat the counter transfer and sacrifice. Each Mutagen activation must wait for an empty stack.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Extra countered creature; own main phase/empty stack for Mutagen. One Altar mana funds one Mutagen activation: neutral.

===endpanel
===endaccordion

<a id="c047"></a>
===accordion
===panel: C047: Pitiless Plunderer + Umbral Collar Zealot + Stridehangar Automaton

[[symbol:b]]

Cards Required:
- [[Pitiless Plunderer]]
- [[Umbral Collar Zealot]]
- [[Stridehangar Automaton]]

Prerequisites:
- All permanents on the battlefield.
- You control another creature.

Steps:
1. Sacrifice an extra suitable creature to Umbral Collar Zealot.
2. Pitiless Plunderer creates a Treasure. Stridehangar replaces that event with a Treasure plus a Thopter; the Thopter is 2/2 with its anthem.
3. Resolve the outlet ability and any Station untap triggers. Sacrifice the replacement Thopter through the same outlet.
4. Repeat. Keep Plunderer, Stridehangar and any creature outlet alive. Retain Treasures or sacrifice them for colored mana; do not count a spent Treasure twice.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Repeatable surveil events; actual card access is library-bounded.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Extra starter creature; artifact creature for Ravager/KCI/Grinding. Keep Plunderer, Stridehangar and any creature outlet alive. Treasures accumulate; outlet outputs are in F03.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="c048"></a>
===accordion
===panel: C048: Warren Soultrader + Stridehangar Automaton + Sephiroth, Fabled SOLDIER

[[symbol:b]]

Cards Required:
- [[Warren Soultrader]]
- [[Stridehangar Automaton]]
- [[Sephiroth, Fabled SOLDIER]]

Prerequisites:
- All permanents on the battlefield.
- You control at least one additional creature
- Your life total is at least 2.

Steps:
1. Pay 1 life and sacrifice the extra creature to Warren Soultrader.
2. Resolve the death-drain trigger, refunding the life and draining opponents. The real Sephiroth transforms into its emblem engine on its fourth death-trigger resolution.
3. Resolve Warren to create Treasure plus a Stridehangar Thopter.
4. Sacrifice the replacement Thopter to Warren and repeat. Keep the life-gain source alive; Treasures accumulate.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Direct lethal damage or life loss through the named payoff.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Extra creature and life >= 2. Warren life cost refunded; keep drain source and Stridehangar alive. One Treasure accumulated per death; direct lethal drain.

===endpanel
===endaccordion

<a id="c049"></a>
===accordion
===panel: C049: Warren Soultrader + Zulaport Cutthroat + Stridehangar Automaton

[[symbol:b]]

Cards Required:
- [[Warren Soultrader]]
- [[Zulaport Cutthroat]]
- [[Stridehangar Automaton]]

Prerequisites:
- All permanents on the battlefield.
- You control at least one additional creature
- Your life total is at least 2.

Steps:
1. Pay 1 life and sacrifice the extra creature to Warren Soultrader.
2. Resolve the death-drain trigger, refunding the life and draining opponents. The real Sephiroth transforms into its emblem engine on its fourth death-trigger resolution.
3. Resolve Warren to create Treasure plus a Stridehangar Thopter.
4. Sacrifice the replacement Thopter to Warren and repeat. Keep the life-gain source alive; Treasures accumulate.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Direct lethal damage or life loss through the named payoff.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Extra creature and life >= 2. Warren life cost refunded; keep drain source and Stridehangar alive. One Treasure accumulated per death; direct lethal drain.

===endpanel
===endaccordion

<a id="c050"></a>
===accordion
===panel: C050: Metalwork Colossus + Warren Soultrader + Pitiless Plunderer + Aetherflux Reservoir

[[symbol:b]]

Cards Required:
- [[Metalwork Colossus]]
- [[Warren Soultrader]]
- [[Pitiless Plunderer]]
- [[Aetherflux Reservoir]]

Prerequisites:
- Metalwork Colossus in hand.
- All other permanents on the battlefield.
- The total mana value of noncreature artifacts you control is at least 11.

Steps:
1. Cast Metalwork Colossus for [[symbol:0]], maintaining at least 11 mana value of noncreature artifacts. Resolve Reservoir's life gain.
2. Pay 1 life and sacrifice Colossus to Warren. Resolve the token creation: two Treasures with Plunderer, or Treasure plus Thopter with Stridehangar.
3. Sacrifice those two artifacts to Colossus's graveyard-return ability; return it to hand. The sacrificed Treasures are not also spent for mana.
4. Repeat free casts, growing Reservoir's life gains. Pay 50 life per Reservoir shot once sufficiently funded.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Direct lethal damage or life loss through the named payoff.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Corrected threshold: >= 11 maintained mana value of noncreature artifacts, not 10. Colossus begins in hand; cast free each time. Sacrifice both newly created artifacts to return it, not for mana.

===endpanel
===endaccordion

<a id="c051"></a>
===accordion
===panel: C051: Metalwork Colossus + Warren Soultrader + Aetherflux Reservoir + Stridehangar Automaton

[[symbol:b]]

Cards Required:
- [[Metalwork Colossus]]
- [[Warren Soultrader]]
- [[Aetherflux Reservoir]]
- [[Stridehangar Automaton]]

Prerequisites:
- Metalwork Colossus in hand.
- All other permanents on the battlefield.
- The total mana value of noncreature artifacts you control is at least 11.

Steps:
1. Cast Metalwork Colossus for [[symbol:0]], maintaining at least 11 mana value of noncreature artifacts. Resolve Reservoir's life gain.
2. Pay 1 life and sacrifice Colossus to Warren. Resolve the token creation: two Treasures with Plunderer, or Treasure plus Thopter with Stridehangar.
3. Sacrifice those two artifacts to Colossus's graveyard-return ability; return it to hand. The sacrificed Treasures are not also spent for mana.
4. Repeat free casts, growing Reservoir's life gains. Pay 50 life per Reservoir shot once sufficiently funded.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Direct lethal damage or life loss through the named payoff.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Corrected threshold: >= 11 maintained mana value of noncreature artifacts, not 10. Colossus begins in hand; cast free each time. Sacrifice both newly created artifacts to return it, not for mana.

===endpanel
===endaccordion

<a id="c052"></a>
===accordion
===panel: C052: Tortured Existence + Pitiless Plunderer + Imotekh the Stormlord + Altar of Dementia

[[symbol:b]]

Cards Required:
- [[Tortured Existence]]
- [[Pitiless Plunderer]]
- [[Imotekh the Stormlord]]
- [[Altar of Dementia]]

Prerequisites:
- All permanents on the battlefield.
- You have an artifact creature card in hand
- You have a SECOND artifact creature card in your graveyard.
- [[symbol:b]] available

Steps:
1. Begin with [[symbol:b]] available.
2. Activate Tortured Existence for [[symbol:b]]: target the artifact creature card already in your graveyard and discard the other artifact creature card as the cost. Return the target to hand.
3. Resolve Imotekh to create two Necrons.
4. Sacrifice both Necrons to Altar of Dementia; resolve Plunderer to make two Treasures. Spend one Treasure for the next [[symbol:b]]. With Blasting Station, use its two separate untap triggers to fund two activations.
5. Repeat with the hand/graveyard cards exchanged. Do not cast the exchanged cards.

Results:
- Arbitrarily many artifact-card returns and Necron-token creation events.
- Repeatable mill; actual cards milled are library-bounded, and emptying a library is not by itself immediate elimination.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Two additional artifact creature cards alternate hand/graveyard; [[symbol:b]] seed. Sacrifice both Necrons for two Treasures; spend one for the next exchange. C070 uses both separate Station untap triggers.

===endpanel
===endaccordion

<a id="c053"></a>
===accordion
===panel: C053: Out of the Tombs + Skullclamp + Pitiless Plunderer + Altar of Dementia

[[symbol:b]]

Cards Required:
- [[Out of the Tombs]]
- [[Skullclamp]]
- [[Pitiless Plunderer]]
- [[Altar of Dementia]]

Prerequisites:
- All permanents on the battlefield.
- Your library is empty.
- You control two other suitable nontoken creatures.
- [[symbol:1]] available for the initial Skullclamp equip.
- Use recyclable bodies that survive Skullclamp unless the entry explicitly uses a 1-toughness auto-dying carrier.

Steps:
1. Pay [[symbol:1]] to equip Skullclamp to a recyclable body that survives its -1 toughness.
2. Sacrifice BOTH recyclable bodies to Altar of Dementia before Clamp's draw trigger resolves.
3. Resolve resource triggers first, then resolve Clamp. Out of the Tombs replaces its two draws separately by returning both creature cards. Do not remove those cards with another recursion trigger first.
4. Spend one generated mana or Treasure on the next equip and repeat. Both bodies must return each cycle.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Repeatable mill; actual cards milled are library-bounded, and emptying a library is not by itself immediate elimination.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Empty library; two other recyclable nontoken bodies, [[symbol:1]] seed. Both artifact creatures for Ravager. Two Treasures minus one equip = one surplus Treasure.

===endpanel
===endaccordion

<a id="c055"></a>
===accordion
===panel: C055: Out of the Tombs + Skullclamp + Pitiless Plunderer + Arcbound Ravager

[[symbol:b]]

Cards Required:
- [[Out of the Tombs]]
- [[Skullclamp]]
- [[Pitiless Plunderer]]
- [[Arcbound Ravager]]

Prerequisites:
- All permanents on the battlefield.
- Your library is empty.
- You control two other suitable nontoken artifact creatures.
- [[symbol:1]] available for the initial Skullclamp equip.
- Use recyclable bodies that survive Skullclamp unless the entry explicitly uses a 1-toughness auto-dying carrier.

Steps:
1. Pay [[symbol:1]] to equip Skullclamp to a recyclable body that survives its -1 toughness.
2. Sacrifice BOTH recyclable bodies to Arcbound Ravager before Clamp's draw trigger resolves.
3. Resolve resource triggers first, then resolve Clamp. Out of the Tombs replaces its two draws separately by returning both creature cards. Do not remove those cards with another recursion trigger first.
4. Spend one generated mana or Treasure on the next equip and repeat. Both bodies must return each cycle.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily many +1/+1 counters on the surviving counter source.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Empty library; two other recyclable nontoken bodies, [[symbol:1]] seed. Both artifact creatures for Ravager. Two Treasures minus one equip = one surplus Treasure.

===endpanel
===endaccordion

<a id="c057"></a>
===accordion
===panel: C057: Scrap Trawler + Myr Retriever + Ashnod's Altar + Cloud Key

[[symbol:c]]

Cards Required:
- [[Scrap Trawler]]
- [[Myr Retriever]]
- [[Ashnod's Altar]]
- [[Cloud Key]]

Prerequisites:
- Scrap Trawler in your graveyard.
- All other permanents on the battlefield (Cloud Key with "Artifact" or "Creature" chosen).

Steps:
1. Sacrifice Myr Retriever to Ashnod's Altar; return Scrap Trawler to hand from the graveyard.
2. Cast Trawler at the reduced cost: [[symbol:2]] with Key/Inspector, [[symbol:1]] with Anvil.
3. Sacrifice Trawler to Ashnod's Altar; its own death trigger returns lower-value Myr Retriever.
4. Cast Retriever at the reduced cost: [[symbol:1]] with Key/Inspector, [[symbol:0]] with Anvil. Repeat.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Retriever on battlefield, Trawler in graveyard; one-mana reducer. Four generated minus three spent per pair = net one colorless. Key may name Artifact or Creature.

===endpanel
===endaccordion

<a id="c058"></a>
===accordion
===panel: C058: Scrap Trawler + Myr Retriever + Ashnod's Altar + Foundry Inspector

[[symbol:c]]

Cards Required:
- [[Scrap Trawler]]
- [[Myr Retriever]]
- [[Ashnod's Altar]]
- [[Foundry Inspector]]

Prerequisites:
- Scrap Trawler in your graveyard.
- All other permanents on the battlefield.

Steps:
1. Sacrifice Myr Retriever to Ashnod's Altar; return Scrap Trawler to hand from the graveyard.
2. Cast Trawler at the reduced cost: [[symbol:2]] with Key/Inspector, [[symbol:1]] with Anvil.
3. Sacrifice Trawler to Ashnod's Altar; its own death trigger returns lower-value Myr Retriever.
4. Cast Retriever at the reduced cost: [[symbol:1]] with Key/Inspector, [[symbol:0]] with Anvil. Repeat.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Retriever on battlefield, Trawler in graveyard; one-mana reducer. Four generated minus three spent per pair = net one colorless. Key may name Artifact or Creature.

===endpanel
===endaccordion

<a id="c059"></a>
===accordion
===panel: C059: Glaring Fleshraker + Ashnod's Altar + Myr Retriever + Junk Diver

[[symbol:c]]

Cards Required:
- [[Glaring Fleshraker]]
- [[Ashnod's Altar]]
- [[Myr Retriever]]
- [[Junk Diver]]

Prerequisites:
- Glaring Fleshraker and Ashnod's Altar on the battlefield.
- Myr Retriever and Junk Diver in hand or in your graveyard.
- One of the artifact creatures must be in your hand while the other is in your graveyard
- You have enough mana to cast the artifact card in your hand.

Steps:
1. Cast the recycler in hand. Fleshraker creates a Spawn; resolve its entry damage, then let the artifact creature enter for a second damage trigger.
2. Sacrifice the artifact creature to Ashnod's Altar; return the other recycler from graveyard to hand.
3. Sacrifice the Spawn to Ashnod's Altar for [[symbol:2]].
4. Cast the other recycler and repeat the exchange. Trawler returns only lower-value Retriever, not an equal-value 3-mana card.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Direct lethal damage or life loss through the named payoff.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- One recycler in hand, other in graveyard; fund first cast (three always suffices). Sacrifice Spawn to Ashnod, not its intrinsic ability: eight generated minus five spent per pair = net three.

===endpanel
===endaccordion

<a id="c060"></a>
===accordion
===panel: C060: Glaring Fleshraker + Ashnod's Altar + Junk Diver + Workshop Assistant

[[symbol:c]]

Cards Required:
- [[Glaring Fleshraker]]
- [[Ashnod's Altar]]
- [[Junk Diver]]
- [[Workshop Assistant]]

Prerequisites:
- Glaring Fleshraker and Ashnod's Altar on the battlefield.
- Junk Diver and Workshop Assistant in hand or in your graveyard.
- One of the artifact creatures must be in your hand while the other is in your graveyard
- You have enough mana to cast the artifact card in your hand.

Steps:
1. Cast the recycler in hand. Fleshraker creates a Spawn; resolve its entry damage, then let the artifact creature enter for a second damage trigger.
2. Sacrifice the artifact creature to Ashnod's Altar; return the other recycler from graveyard to hand.
3. Sacrifice the Spawn to Ashnod's Altar for [[symbol:2]].
4. Cast the other recycler and repeat the exchange. Trawler returns only lower-value Retriever, not an equal-value 3-mana card.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Direct lethal damage or life loss through the named payoff.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Diver/Assistant start hand/graveyard; three-mana seed. Sacrifice Spawns to Ashnod: eight generated minus six spent = net two colorless per pair.

===endpanel
===endaccordion

<a id="c061"></a>
===accordion
===panel: C061: Glaring Fleshraker + Ashnod's Altar + Myr Retriever + Scrap Trawler

[[symbol:c]]

Cards Required:
- [[Glaring Fleshraker]]
- [[Ashnod's Altar]]
- [[Myr Retriever]]
- [[Scrap Trawler]]

Prerequisites:
- Glaring Fleshraker and Ashnod's Altar on the battlefield.
- Myr Retriever and Scrap Trawler in hand or in your graveyard.
- One of the artifact creatures must be in your hand while the other is in your graveyard
- You have enough mana to cast the artifact card in your hand.

Steps:
1. Cast the recycler in hand. Fleshraker creates a Spawn; resolve its entry damage, then let the artifact creature enter for a second damage trigger.
2. Sacrifice the artifact creature to Ashnod's Altar; return the other recycler from graveyard to hand.
3. Sacrifice the Spawn to Ashnod's Altar for [[symbol:2]].
4. Cast the other recycler and repeat the exchange. Trawler returns only lower-value Retriever, not an equal-value 3-mana card.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Direct lethal damage or life loss through the named payoff.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- One recycler in hand, other in graveyard; fund first cast (three always suffices). Sacrifice Spawn to Ashnod, not its intrinsic ability: eight generated minus five spent per pair = net three.

===endpanel
===endaccordion

<a id="c062"></a>
===accordion
===panel: C062: Glaring Fleshraker + Ashnod's Altar + Myr Retriever + Workshop Assistant

[[symbol:c]]

Cards Required:
- [[Glaring Fleshraker]]
- [[Ashnod's Altar]]
- [[Myr Retriever]]
- [[Workshop Assistant]]

Prerequisites:
- Glaring Fleshraker and Ashnod's Altar on the battlefield.
- Myr Retriever and Workshop Assistant in hand or in your graveyard.
- One of the artifact creatures must be in your hand while the other is in your graveyard
- You have enough mana to cast the artifact card in your hand.

Steps:
1. Cast the recycler in hand. Fleshraker creates a Spawn; resolve its entry damage, then let the artifact creature enter for a second damage trigger.
2. Sacrifice the artifact creature to Ashnod's Altar; return the other recycler from graveyard to hand.
3. Sacrifice the Spawn to Ashnod's Altar for [[symbol:2]].
4. Cast the other recycler and repeat the exchange. Trawler returns only lower-value Retriever, not an equal-value 3-mana card.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Direct lethal damage or life loss through the named payoff.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- One recycler in hand, other in graveyard; fund first cast (three always suffices). Sacrifice Spawn to Ashnod, not its intrinsic ability: eight generated minus five spent per pair = net three.

===endpanel
===endaccordion

<a id="c064"></a>
===accordion
===panel: C064: Imotekh the Stormlord + Junk Diver + Myr Retriever + Ashnod's Altar

[[symbol:b]]

Cards Required:
- [[Imotekh the Stormlord]]
- [[Junk Diver]]
- [[Myr Retriever]]
- [[Ashnod's Altar]]

Prerequisites:
- Junk Diver in your graveyard.
- All other permanents on the battlefield.

Steps:
1. Sacrifice the battlefield recycler to Ashnod's Altar; return its partner from graveyard to hand.
2. Imotekh creates two Necrons. Sacrifice a Necron if needed to fund the partner's cast.
3. Cast that partner and sacrifice it to Ashnod's Altar; return the original recycler and create two more Necrons.
4. Recast the original. Repeat, choosing which surplus Necrons to keep or convert to mana.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- One recycler on battlefield, other in graveyard. Sacrificing both Necrons per return gives 12 total per pair minus five casts = net seven; retain tokens instead if desired.

===endpanel
===endaccordion

<a id="c065"></a>
===accordion
===panel: C065: Imotekh the Stormlord + Junk Diver + Workshop Assistant + Ashnod's Altar

[[symbol:b]]

Cards Required:
- [[Imotekh the Stormlord]]
- [[Junk Diver]]
- [[Workshop Assistant]]
- [[Ashnod's Altar]]

Prerequisites:
- Junk Diver in your graveyard.
- All other permanents on the battlefield.

Steps:
1. Sacrifice the battlefield recycler to Ashnod's Altar; return its partner from graveyard to hand.
2. Imotekh creates two Necrons. Sacrifice a Necron if needed to fund the partner's cast.
3. Cast that partner and sacrifice it to Ashnod's Altar; return the original recycler and create two more Necrons.
4. Recast the original. Repeat, choosing which surplus Necrons to keep or convert to mana.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- One of Diver/Assistant on battlefield, other in graveyard. Both Necron pairs can be sacrificed: 12 generated minus six casts = net six colorless.

===endpanel
===endaccordion

<a id="c066"></a>
===accordion
===panel: C066: Imotekh the Stormlord + Scrap Trawler + Myr Retriever + Ashnod's Altar

[[symbol:b]]

Cards Required:
- [[Imotekh the Stormlord]]
- [[Scrap Trawler]]
- [[Myr Retriever]]
- [[Ashnod's Altar]]

Prerequisites:
- Scrap Trawler in your graveyard.
- All other permanents on the battlefield.

Steps:
1. Sacrifice the battlefield recycler to Ashnod's Altar; return its partner from graveyard to hand.
2. Imotekh creates two Necrons. Sacrifice a Necron if needed to fund the partner's cast.
3. Cast that partner and sacrifice it to Ashnod's Altar; return the original recycler and create two more Necrons.
4. Recast the original. Repeat, choosing which surplus Necrons to keep or convert to mana.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- One recycler on battlefield, other in graveyard. Sacrificing both Necrons per return gives 12 total per pair minus five casts = net seven; retain tokens instead if desired.

===endpanel
===endaccordion

<a id="c067"></a>
===accordion
===panel: C067: Imotekh the Stormlord + Myr Retriever + Workshop Assistant + Ashnod's Altar

[[symbol:b]]

Cards Required:
- [[Imotekh the Stormlord]]
- [[Myr Retriever]]
- [[Workshop Assistant]]
- [[Ashnod's Altar]]

Prerequisites:
- Myr Retriever in your graveyard.
- All other permanents on the battlefield.

Steps:
1. Sacrifice the battlefield recycler to Ashnod's Altar; return its partner from graveyard to hand.
2. Imotekh creates two Necrons. Sacrifice a Necron if needed to fund the partner's cast.
3. Cast that partner and sacrifice it to Ashnod's Altar; return the original recycler and create two more Necrons.
4. Recast the original. Repeat, choosing which surplus Necrons to keep or convert to mana.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- One recycler on battlefield, other in graveyard. Sacrificing both Necrons per return gives 12 total per pair minus five casts = net seven; retain tokens instead if desired.

===endpanel
===endaccordion

<a id="c068"></a>
===accordion
===panel: C068: Scrap Trawler + Myr Retriever + Ashnod's Altar + Semblance Anvil

[[symbol:c]]

Cards Required:
- [[Scrap Trawler]]
- [[Myr Retriever]]
- [[Ashnod's Altar]]
- [[Semblance Anvil]]

Prerequisites:
- Scrap Trawler in your graveyard.
- All other permanents on the battlefield.
- There is an artifact or creature card exiled with Semblance Anvil.

Steps:
1. Sacrifice Myr Retriever to Ashnod's Altar; return Scrap Trawler to hand from the graveyard.
2. Cast Trawler at the reduced cost: [[symbol:2]] with Key/Inspector, [[symbol:1]] with Anvil.
3. Sacrifice Trawler to Ashnod's Altar; its own death trigger returns lower-value Myr Retriever.
4. Cast Retriever at the reduced cost: [[symbol:1]] with Key/Inspector, [[symbol:0]] with Anvil. Repeat.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Retriever on battlefield, Trawler in graveyard; Anvil imprints artifact or creature. Four generated minus one spent = net three colorless.

===endpanel
===endaccordion

<a id="c070"></a>
===accordion
===panel: C070: Tortured Existence + Pitiless Plunderer + Imotekh the Stormlord + Blasting Station

[[symbol:b]]

Cards Required:
- [[Tortured Existence]]
- [[Pitiless Plunderer]]
- [[Imotekh the Stormlord]]
- [[Blasting Station]]

Prerequisites:
- All permanents on the battlefield.
- You have an artifact creature card in hand
- You have a SECOND artifact creature card in your graveyard.
- [[symbol:b]] available

Steps:
1. Begin with [[symbol:b]] available.
2. Activate Tortured Existence for [[symbol:b]]: target the artifact creature card already in your graveyard and discard the other artifact creature card as the cost. Return the target to hand.
3. Resolve Imotekh to create two Necrons.
4. Sacrifice both Necrons to Blasting Station; resolve Plunderer to make two Treasures. Spend one Treasure for the next [[symbol:b]]. With Blasting Station, use its two separate untap triggers to fund two activations.
5. Repeat with the hand/graveyard cards exchanged. Do not cast the exchanged cards.

Results:
- Arbitrarily many artifact-card returns and Necron-token creation events.
- Direct lethal damage or life loss through the named payoff.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Two additional artifact creature cards alternate hand/graveyard; [[symbol:b]] seed. Sacrifice both Necrons for two Treasures; spend one for the next exchange. C070 uses both separate Station untap triggers.

===endpanel
===endaccordion

<a id="c072"></a>
===accordion
===panel: C072: Tortured Existence + Pitiless Plunderer + Imotekh the Stormlord + Carrion Feeder

[[symbol:b]]

Cards Required:
- [[Tortured Existence]]
- [[Pitiless Plunderer]]
- [[Imotekh the Stormlord]]
- [[Carrion Feeder]]

Prerequisites:
- All permanents on the battlefield.
- You have an artifact creature card in hand.
- You have a SECOND artifact creature card in your graveyard.
- [[symbol:b]] available.

Steps:
1. Begin with [[symbol:b]] available.
2. Activate Tortured Existence for [[symbol:b]]: target the artifact creature card already in your graveyard and discard the other artifact creature card as the cost. Return the target to hand.
3. Resolve Imotekh to create two Necrons.
4. Sacrifice both Necrons to Carrion Feeder; resolve Plunderer to make two Treasures. Spend one Treasure for the next [[symbol:b]]. With Blasting Station, use its two separate untap triggers to fund two activations.
5. Repeat with the hand/graveyard cards exchanged. Do not cast the exchanged cards.

Results:
- Arbitrarily many artifact-card returns and Necron-token creation events.
- Arbitrarily many +1/+1 counters on the surviving counter source.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Two additional artifact creature cards alternate hand/graveyard; [[symbol:b]] seed. Sacrifice both Necrons for two Treasures; spend one for the next exchange. C070 uses both separate Station untap triggers.

===endpanel
===endaccordion

<a id="c073"></a>
===accordion
===panel: C073: Out of the Tombs + Skullclamp + Pitiless Plunderer + Carrion Feeder

[[symbol:b]]

Cards Required:
- [[Out of the Tombs]]
- [[Skullclamp]]
- [[Pitiless Plunderer]]
- [[Carrion Feeder]]

Prerequisites:
- All permanents on the battlefield.
- Your library is empty.
- You control two other suitable nontoken creatures.
- [[symbol:1]] available for the initial Skullclamp equip.
- Use recyclable bodies that survive Skullclamp unless the entry explicitly uses a 1-toughness auto-dying carrier.

Steps:
1. Pay [[symbol:1]] to equip Skullclamp to a recyclable body that survives its -1 toughness.
2. Sacrifice BOTH recyclable bodies to Carrion Feeder before Clamp's draw trigger resolves.
3. Resolve resource triggers first, then resolve Clamp. Out of the Tombs replaces its two draws separately by returning both creature cards. Do not remove those cards with another recursion trigger first.
4. Spend one generated mana or Treasure on the next equip and repeat. Both bodies must return each cycle.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily many +1/+1 counters on the surviving counter source.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Empty library; two other recyclable nontoken bodies, [[symbol:1]] seed. Both artifact creatures for Ravager. Two Treasures minus one equip = one surplus Treasure.

===endpanel
===endaccordion

<a id="c075"></a>
===accordion
===panel: C075: The Ooze + Clock of Omens + Stridehangar Automaton + Grinding Station

[[symbol:c]]

Cards Required:
- [[The Ooze]]
- [[Clock of Omens]]
- [[Stridehangar Automaton]]
- [[Grinding Station]]

Prerequisites:
- All permanents on the battlefield and untapped.
- The Ooze is untapped.
- There is at least one card in a graveyard.

Steps:
1. Tap The Ooze to exile a graveyard card and create Mutagen plus a Stridehangar Thopter.
2. Tap the two new artifacts to Clock to untap The Ooze.
3. Tap Grinding Station and sacrifice the tapped Mutagen to mill three. Exile a newly milled graveyard card with Ooze to create the next token pair; token entries untap Station. Repeat until the finite library/graveyard feed is exhausted.

Results:
- Finite repeated card access / resource conversion as described in the steps.
- Not an unbounded loop: library or graveyard fuel is consumed.
- Repeated mill until finite fuel is exhausted.

Classification: Finite sequence.

Audit Notes:
- Finite: requires an initial graveyard card and enough library feed to continue milling. Sacrifice Mutagen to Station after tapping it for Clock; next token entries untap Station.

===endpanel
===endaccordion

<a id="c077"></a>
===accordion
===panel: C077: Scrap Trawler + Myr Retriever + Krark-Clan Ironworks + Cloud Key

[[symbol:c]]

Cards Required:
- [[Scrap Trawler]]
- [[Myr Retriever]]
- [[Krark-Clan Ironworks]]
- [[Cloud Key]]

Prerequisites:
- Scrap Trawler in your graveyard.
- All other permanents on the battlefield (Cloud Key with "Artifact" or "Creature" chosen).

Steps:
1. Sacrifice Myr Retriever to Krark-Clan Ironworks; return Scrap Trawler to hand from the graveyard.
2. Cast Trawler at the reduced cost: [[symbol:2]] with Key/Inspector, [[symbol:1]] with Anvil.
3. Sacrifice Trawler to Krark-Clan Ironworks; its own death trigger returns lower-value Myr Retriever.
4. Cast Retriever at the reduced cost: [[symbol:1]] with Key/Inspector, [[symbol:0]] with Anvil. Repeat.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Retriever on battlefield, Trawler in graveyard; one-mana reducer. Four generated minus three spent per pair = net one colorless. Key may name Artifact or Creature.

===endpanel
===endaccordion

<a id="c080"></a>
===accordion
===panel: C080: Scrap Trawler + Myr Retriever + Krark-Clan Ironworks + Foundry Inspector

[[symbol:c]]

Cards Required:
- [[Scrap Trawler]]
- [[Myr Retriever]]
- [[Krark-Clan Ironworks]]
- [[Foundry Inspector]]

Prerequisites:
- Scrap Trawler in your graveyard.
- All other permanents on the battlefield.

Steps:
1. Sacrifice Myr Retriever to Krark-Clan Ironworks; return Scrap Trawler to hand from the graveyard.
2. Cast Trawler at the reduced cost: [[symbol:2]] with Key/Inspector, [[symbol:1]] with Anvil.
3. Sacrifice Trawler to Krark-Clan Ironworks; its own death trigger returns lower-value Myr Retriever.
4. Cast Retriever at the reduced cost: [[symbol:1]] with Key/Inspector, [[symbol:0]] with Anvil. Repeat.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Retriever on battlefield, Trawler in graveyard; one-mana reducer. Four generated minus three spent per pair = net one colorless. Key may name Artifact or Creature.

===endpanel
===endaccordion

<a id="c083"></a>
===accordion
===panel: C083: Glaring Fleshraker + Myr Retriever + Junk Diver + Krark-Clan Ironworks

[[symbol:c]]

Cards Required:
- [[Glaring Fleshraker]]
- [[Myr Retriever]]
- [[Junk Diver]]
- [[Krark-Clan Ironworks]]

Prerequisites:
- Glaring Fleshraker and Krark-Clan Ironworks on the battlefield.
- Myr Retriever and Junk Diver in hand or in your graveyard.
- One of the artifact creatures must be in your hand while the other is in your graveyard
- You have enough mana to cast the artifact card in your hand.

Steps:
1. Cast the recycler in hand. Fleshraker creates a Spawn; resolve its entry damage, then let the artifact creature enter for a second damage trigger.
2. Sacrifice the artifact creature to Krark-Clan Ironworks; return the other recycler from graveyard to hand.
3. Sacrifice the Spawn to its own ability for [[symbol:c]]; KCI cannot sacrifice the nonartifact Spawn.
4. Cast the other recycler and repeat the exchange. Trawler returns only lower-value Retriever, not an equal-value 3-mana card.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Direct lethal damage or life loss through the named payoff.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- One recycler in hand, other in graveyard; fund first cast. Spawn is NOT an artifact: sacrifice itself for one. Six generated minus five cast cost per pair = net one colorless.

===endpanel
===endaccordion

<a id="c084"></a>
===accordion
===panel: C084: Glaring Fleshraker + Junk Diver + Workshop Assistant + Krark-Clan Ironworks

[[symbol:c]]

Cards Required:
- [[Glaring Fleshraker]]
- [[Junk Diver]]
- [[Workshop Assistant]]
- [[Krark-Clan Ironworks]]

Prerequisites:
- Glaring Fleshraker and Krark-Clan Ironworks on the battlefield.
- Junk Diver and Workshop Assistant in hand or in your graveyard.
- One of the artifact creatures must be in your hand while the other is in your graveyard
- You have enough mana to cast the artifact card in your hand.

Steps:
1. Cast the recycler in hand. Fleshraker creates a Spawn; resolve its entry damage, then let the artifact creature enter for a second damage trigger.
2. Sacrifice the artifact creature to Krark-Clan Ironworks; return the other recycler from graveyard to hand.
3. Sacrifice the Spawn to its own ability for [[symbol:c]]; KCI cannot sacrifice the nonartifact Spawn.
4. Cast the other recycler and repeat the exchange. Trawler returns only lower-value Retriever, not an equal-value 3-mana card.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Direct lethal damage or life loss through the named payoff.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Diver/Assistant start hand/graveyard; three-mana seed. Each body + intrinsic Spawn yields three: six generated and six spent per pair, neutral.

===endpanel
===endaccordion

<a id="c085"></a>
===accordion
===panel: C085: Glaring Fleshraker + Myr Retriever + Scrap Trawler + Krark-Clan Ironworks

[[symbol:c]]

Cards Required:
- [[Glaring Fleshraker]]
- [[Myr Retriever]]
- [[Scrap Trawler]]
- [[Krark-Clan Ironworks]]

Prerequisites:
- Glaring Fleshraker and Krark-Clan Ironworks on the battlefield.
- Myr Retriever and Scrap Trawler in hand or in your graveyard.
- One of the artifact creatures must be in your hand while the other is in your graveyard
- You have enough mana to cast the artifact card in your hand.

Steps:
1. Cast the recycler in hand. Fleshraker creates a Spawn; resolve its entry damage, then let the artifact creature enter for a second damage trigger.
2. Sacrifice the artifact creature to Krark-Clan Ironworks; return the other recycler from graveyard to hand.
3. Sacrifice the Spawn to its own ability for [[symbol:c]]; KCI cannot sacrifice the nonartifact Spawn.
4. Cast the other recycler and repeat the exchange. Trawler returns only lower-value Retriever, not an equal-value 3-mana card.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Direct lethal damage or life loss through the named payoff.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- One recycler in hand, other in graveyard; fund first cast. Spawn is NOT an artifact: sacrifice itself for one. Six generated minus five cast cost per pair = net one colorless.

===endpanel
===endaccordion

<a id="c086"></a>
===accordion
===panel: C086: Glaring Fleshraker + Myr Retriever + Workshop Assistant + Krark-Clan Ironworks

[[symbol:c]]

Cards Required:
- [[Glaring Fleshraker]]
- [[Myr Retriever]]
- [[Workshop Assistant]]
- [[Krark-Clan Ironworks]]

Prerequisites:
- Glaring Fleshraker and Krark-Clan Ironworks on the battlefield.
- Myr Retriever and Workshop Assistant in hand or in your graveyard.
- One of the artifact creatures must be in your hand while the other is in your graveyard
- You have enough mana to cast the artifact card in your hand.

Steps:
1. Cast the recycler in hand. Fleshraker creates a Spawn; resolve its entry damage, then let the artifact creature enter for a second damage trigger.
2. Sacrifice the artifact creature to Krark-Clan Ironworks; return the other recycler from graveyard to hand.
3. Sacrifice the Spawn to its own ability for [[symbol:c]]; KCI cannot sacrifice the nonartifact Spawn.
4. Cast the other recycler and repeat the exchange. Trawler returns only lower-value Retriever, not an equal-value 3-mana card.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Direct lethal damage or life loss through the named payoff.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- One recycler in hand, other in graveyard; fund first cast. Spawn is NOT an artifact: sacrifice itself for one. Six generated minus five cast cost per pair = net one colorless.

===endpanel
===endaccordion

<a id="c089"></a>
===accordion
===panel: C089: Imotekh the Stormlord + Junk Diver + Myr Retriever + Krark-Clan Ironworks

[[symbol:b]]

Cards Required:
- [[Imotekh the Stormlord]]
- [[Junk Diver]]
- [[Myr Retriever]]
- [[Krark-Clan Ironworks]]

Prerequisites:
- Junk Diver in your graveyard.
- All other permanents on the battlefield.

Steps:
1. Sacrifice the battlefield recycler to Krark-Clan Ironworks; return its partner from graveyard to hand.
2. Imotekh creates two Necrons. Sacrifice a Necron if needed to fund the partner's cast.
3. Cast that partner and sacrifice it to Krark-Clan Ironworks; return the original recycler and create two more Necrons.
4. Recast the original. Repeat, choosing which surplus Necrons to keep or convert to mana.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- One recycler on battlefield, other in graveyard. Sacrificing both Necrons per return gives 12 total per pair minus five casts = net seven; retain tokens instead if desired.

===endpanel
===endaccordion

<a id="c090"></a>
===accordion
===panel: C090: Imotekh the Stormlord + Junk Diver + Workshop Assistant + Krark-Clan Ironworks

[[symbol:b]]

Cards Required:
- [[Imotekh the Stormlord]]
- [[Junk Diver]]
- [[Workshop Assistant]]
- [[Krark-Clan Ironworks]]

Prerequisites:
- Junk Diver in your graveyard.
- All other permanents on the battlefield.

Steps:
1. Sacrifice the battlefield recycler to Krark-Clan Ironworks; return its partner from graveyard to hand.
2. Imotekh creates two Necrons. Sacrifice a Necron if needed to fund the partner's cast.
3. Cast that partner and sacrifice it to Krark-Clan Ironworks; return the original recycler and create two more Necrons.
4. Recast the original. Repeat, choosing which surplus Necrons to keep or convert to mana.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- One of Diver/Assistant on battlefield, other in graveyard. Both Necron pairs can be sacrificed: 12 generated minus six casts = net six colorless.

===endpanel
===endaccordion

<a id="c091"></a>
===accordion
===panel: C091: Imotekh the Stormlord + Scrap Trawler + Myr Retriever + Krark-Clan Ironworks

[[symbol:b]]

Cards Required:
- [[Imotekh the Stormlord]]
- [[Scrap Trawler]]
- [[Myr Retriever]]
- [[Krark-Clan Ironworks]]

Prerequisites:
- Scrap Trawler in your graveyard.
- All other permanents on the battlefield.

Steps:
1. Sacrifice the battlefield recycler to Krark-Clan Ironworks; return its partner from graveyard to hand.
2. Imotekh creates two Necrons. Sacrifice a Necron if needed to fund the partner's cast.
3. Cast that partner and sacrifice it to Krark-Clan Ironworks; return the original recycler and create two more Necrons.
4. Recast the original. Repeat, choosing which surplus Necrons to keep or convert to mana.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- One recycler on battlefield, other in graveyard. Sacrificing both Necrons per return gives 12 total per pair minus five casts = net seven; retain tokens instead if desired.

===endpanel
===endaccordion

<a id="c092"></a>
===accordion
===panel: C092: Imotekh the Stormlord + Myr Retriever + Workshop Assistant + Krark-Clan Ironworks

[[symbol:b]]

Cards Required:
- [[Imotekh the Stormlord]]
- [[Myr Retriever]]
- [[Workshop Assistant]]
- [[Krark-Clan Ironworks]]

Prerequisites:
- Myr Retriever in your graveyard.
- All other permanents on the battlefield.

Steps:
1. Sacrifice the battlefield recycler to Krark-Clan Ironworks; return its partner from graveyard to hand.
2. Imotekh creates two Necrons. Sacrifice a Necron if needed to fund the partner's cast.
3. Cast that partner and sacrifice it to Krark-Clan Ironworks; return the original recycler and create two more Necrons.
4. Recast the original. Repeat, choosing which surplus Necrons to keep or convert to mana.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- One recycler on battlefield, other in graveyard. Sacrificing both Necrons per return gives 12 total per pair minus five casts = net seven; retain tokens instead if desired.

===endpanel
===endaccordion

<a id="c094"></a>
===accordion
===panel: C094: Scrap Trawler + Myr Retriever + Krark-Clan Ironworks + Semblance Anvil

[[symbol:c]]

Cards Required:
- [[Scrap Trawler]]
- [[Myr Retriever]]
- [[Krark-Clan Ironworks]]
- [[Semblance Anvil]]

Prerequisites:
- Scrap Trawler in your graveyard.
- All other permanents on the battlefield.
- There is an artifact card exiled with Semblance Anvil.

Steps:
1. Sacrifice Myr Retriever to Krark-Clan Ironworks; return Scrap Trawler to hand from the graveyard.
2. Cast Trawler at the reduced cost: [[symbol:2]] with Key/Inspector, [[symbol:1]] with Anvil.
3. Sacrifice Trawler to Krark-Clan Ironworks; its own death trigger returns lower-value Myr Retriever.
4. Cast Retriever at the reduced cost: [[symbol:1]] with Key/Inspector, [[symbol:0]] with Anvil. Repeat.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Retriever on battlefield, Trawler in graveyard; Anvil imprints artifact or creature. Four generated minus one spent = net three colorless.

===endpanel
===endaccordion

<a id="c097"></a>
===accordion
===panel: C097: Scrap Trawler + Myr Retriever + Phyrexian Altar + Semblance Anvil

[[symbol:c]]

Cards Required:
- [[Scrap Trawler]]
- [[Myr Retriever]]
- [[Phyrexian Altar]]
- [[Semblance Anvil]]

Prerequisites:
- Scrap Trawler in your graveyard.
- All other permanents on the battlefield.
- There is an artifact or creature card exiled with Semblance Anvil.

Steps:
1. Sacrifice Myr Retriever to Phyrexian Altar; return Scrap Trawler to hand from the graveyard.
2. Cast Trawler at the reduced cost: [[symbol:2]] with Key/Inspector, [[symbol:1]] with Anvil.
3. Sacrifice Trawler to Phyrexian Altar; its own death trigger returns lower-value Myr Retriever.
4. Cast Retriever at the reduced cost: [[symbol:1]] with Key/Inspector, [[symbol:0]] with Anvil. Repeat.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Retriever on battlefield, Trawler in graveyard; Anvil imprints artifact or creature. Two generated minus one spent = net one mana of any color.

===endpanel
===endaccordion

<a id="c098"></a>
===accordion
===panel: C098: Ultron the Annihilator + Nim Deathmantle + Phyrexian Altar + Pitiless Plunderer

[[symbol:b]]

Cards Required:
- [[Ultron the Annihilator]]
- [[Nim Deathmantle]]
- [[Phyrexian Altar]]
- [[Pitiless Plunderer]]

Prerequisites:
- All permanents on the battlefield.
- Ultron the Annihilator has created a 2/2 Robot Villain artifact creature token.

Steps:
1. Sacrifice the Robot to Phyrexian Altar for one mana. Resolve Ultron's drain and Plunderer's Treasure creation.
2. Sacrifice Ultron to Phyrexian Altar for one mana, leaving it in the graveyard. Stack Plunderer above Deathmantle and create the second Treasure first.
3. Sacrifice both Treasures for two more mana. Pay [[symbol:4]] to Deathmantle, return Ultron and attach Deathmantle.
4. Resolve Ultron's ETB to create a new Robot; repeat.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Direct lethal damage or life loss through the named payoff.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Robot present. Put the Plunderer trigger from Ultron dying above Deathmantle so the second Treasure resolves first. Two Altar mana plus two Treasure mana pay [[symbol:4]].

===endpanel
===endaccordion

<a id="c099"></a>
===accordion
===panel: C099: Out of the Tombs + Skullclamp + Pitiless Plunderer + Umbral Collar Zealot

[[symbol:b]]

Cards Required:
- [[Out of the Tombs]]
- [[Skullclamp]]
- [[Pitiless Plunderer]]
- [[Umbral Collar Zealot]]

Prerequisites:
- All permanents on the battlefield.
- Your library is empty.
- You control two other suitable nontoken creatures.
- [[symbol:1]] available for the initial Skullclamp equip.
- Use recyclable bodies that survive Skullclamp unless the entry explicitly uses a 1-toughness auto-dying carrier.

Steps:
1. Pay [[symbol:1]] to equip Skullclamp to a recyclable body that survives its -1 toughness.
2. Sacrifice BOTH recyclable bodies to Umbral Collar Zealot before Clamp's draw trigger resolves.
3. Resolve resource triggers first, then resolve Clamp. Out of the Tombs replaces its two draws separately by returning both creature cards. Do not remove those cards with another recursion trigger first.
4. Spend one generated mana or Treasure on the next equip and repeat. Both bodies must return each cycle.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Repeatable surveil events; actual card access is library-bounded.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Empty library; two other recyclable nontoken bodies, [[symbol:1]] seed. Both artifact creatures for Ravager. Two Treasures minus one equip = one surplus Treasure.

===endpanel
===endaccordion

<a id="c100"></a>
===accordion
===panel: C100: Out of the Tombs + Skullclamp + Warren Soultrader + Sephiroth, Fabled SOLDIER

[[symbol:b]]

Cards Required:
- [[Out of the Tombs]]
- [[Skullclamp]]
- [[Warren Soultrader]]
- [[Sephiroth, Fabled SOLDIER]]

Prerequisites:
- All permanents on the battlefield.
- Your library is empty.
- You control two other suitable nontoken creatures.
- Your life total is at least 3.
- [[symbol:1]] available for the initial Skullclamp equip.
- Use recyclable bodies that survive Skullclamp unless the entry explicitly uses a 1-toughness auto-dying carrier.

Steps:
1. Pay [[symbol:1]] to equip Skullclamp to a recyclable body that survives its -1 toughness.
2. Sacrifice BOTH recyclable bodies to Warren Soultrader before Clamp's draw trigger resolves; pay 1 life for each Warren activation and resolve drain triggers to refund those payments.
3. Resolve resource triggers first, then resolve Clamp. Out of the Tombs replaces its two draws separately by returning both creature cards. Do not remove those cards with another recursion trigger first.
4. Spend one generated mana or Treasure on the next equip and repeat. Both bodies must return each cycle.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Direct lethal damage or life loss through the named payoff.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Empty library, two other recyclable nontoken bodies, [[symbol:1]] seed, life >= 3. Two Warren life costs are refunded by two drain triggers. One surplus Treasure per pair.

===endpanel
===endaccordion

<a id="c101"></a>
===accordion
===panel: C101: Out of the Tombs + Skullclamp + Warren Soultrader + Zulaport Cutthroat

[[symbol:b]]

Cards Required:
- [[Out of the Tombs]]
- [[Skullclamp]]
- [[Warren Soultrader]]
- [[Zulaport Cutthroat]]

Prerequisites:
- All permanents on the battlefield.
- Your library is empty.
- You control two other suitable nontoken creatures.
- Your life total is at least 3.
- [[symbol:1]] available for the initial Skullclamp equip.
- Use recyclable bodies that survive Skullclamp unless the entry explicitly uses a 1-toughness auto-dying carrier.

Steps:
1. Pay [[symbol:1]] to equip Skullclamp to a recyclable body that survives its -1 toughness.
2. Sacrifice BOTH recyclable bodies to Warren Soultrader before Clamp's draw trigger resolves; pay 1 life for each Warren activation and resolve drain triggers to refund those payments.
3. Resolve resource triggers first, then resolve Clamp. Out of the Tombs replaces its two draws separately by returning both creature cards. Do not remove those cards with another recursion trigger first.
4. Spend one generated mana or Treasure on the next equip and repeat. Both bodies must return each cycle.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Direct lethal damage or life loss through the named payoff.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Empty library, two other recyclable nontoken bodies, [[symbol:1]] seed, life >= 3. Two Warren life costs are refunded by two drain triggers. One surplus Treasure per pair.

===endpanel
===endaccordion

<a id="c104"></a>
===accordion
===panel: C104: Out of the Tombs + Skullclamp + Pitiless Plunderer + Blasting Station + Stitcher's Supplier

[[symbol:b]]

Cards Required:
- [[Out of the Tombs]]
- [[Skullclamp]]
- [[Pitiless Plunderer]]
- [[Blasting Station]]
- [[Stitcher's Supplier]]

Prerequisites:
- All permanents on the battlefield.
- Your library is empty.
- You control another suitable nontoken creature in addition to Stitcher's Supplier.
- Blasting Station is untapped.
- [[symbol:1]] available for the initial Skullclamp equip.

Steps:
1. Pay [[symbol:1]] to equip Skullclamp to Stitcher's Supplier. Its reduced toughness makes it die; Clamp and Plunderer trigger.
2. Before resolving Clamp, tap Blasting Station and sacrifice the second recyclable body. Resolve damage and both Treasure triggers first.
3. Resolve Clamp's two draws separately: Out of the Tombs replaces each by returning one of the two creature cards. Returning creatures untap Blasting Station.
4. Use one Treasure to fund the next equip; repeat. Supplier's mills do nothing to the empty library.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Direct lethal damage or life loss through the named payoff.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Empty library; Supplier and another nontoken recyclable body, Station untapped, [[symbol:1]] seed. Clamp auto-kills Supplier; use Station on the second body before Clamp resolves. Direct lethal damage; one surplus Treasure.

===endpanel
===endaccordion

<a id="c105"></a>
===accordion
===panel: C105: Scrap Trawler + Myr Retriever + Krark-Clan Ironworks + Sol Ring + Junk Diver

[[symbol:c]]

Cards Required:
- [[Scrap Trawler]]
- [[Myr Retriever]]
- [[Krark-Clan Ironworks]]
- [[Sol Ring]]
- [[Junk Diver]]

Prerequisites:
- Scrap Trawler, Myr Retriever, and Krark-Clan Ironworks are on the battlefield.
- Sol Ring and Junk Diver are in your graveyard.
- No effect prevents casting artifacts or returning artifact cards from the graveyard to hand.
- The starting two colorless mana from sacrificing Myr Retriever can pay for the first Sol Ring.

Steps:
1. Sacrifice Retriever to KCI for [[symbol:2]]. Retriever returns Junk Diver; Trawler returns Sol Ring.
2. Cast Ring for [[symbol:1]], tap it for [[symbol:2]], then sacrifice it to KCI for [[symbol:2]].
3. Cast Diver for [[symbol:3]] and sacrifice it to KCI for [[symbol:2]]. Diver returns Retriever; Trawler returns Ring.
4. Cast Ring for [[symbol:1]], tap it for [[symbol:2]], sacrifice it for [[symbol:2]], then cast Retriever for [[symbol:2]]. The starting zones are restored.
5. Repeat: twelve mana generated, seven spent, net five colorless.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Trawler/Retriever/KCI on battlefield; Ring and Diver in graveyard. Twelve generated minus seven spent = net five colorless per restored cycle; four casts. Detailed legal target ordering in F19.

===endpanel
===endaccordion

<a id="c106"></a>
===accordion
===panel: C106: Animation Module + Pitiless Plunderer + Carrion Feeder

[[symbol:b]]

Cards Required:
- [[Animation Module]]
- [[Pitiless Plunderer]]
- [[Carrion Feeder]]

Prerequisites:
- All permanents on the battlefield.
- You control an additional creature.

Steps:
1. Sacrifice suitable fodder to Carrion Feeder.
2. Resolve Plunderer first to create Treasure, then resolve the outlet's +1/+1-counter ability.
3. Spend the Treasure for [[symbol:1]] on Module's trigger to create a replacement Servo.
4. Repeat; keep the counter-generating outlet and Plunderer alive.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily many +1/+1 counters on the surviving counter source.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Additional creature; Feeder and Plunderer stay alive. Treasure resolves before Feeder counter ability; Module spends one per Servo. Neutral mana.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="c107"></a>
===accordion
===panel: C107: Animation Module + Ashnod's Altar + Super Shredder

[[symbol:b]]

Cards Required:
- [[Animation Module]]
- [[Ashnod's Altar]]
- [[Super Shredder]]

Prerequisites:
- All permanents on the battlefield.
- You control an additional creature.

Steps:
1. Sacrifice suitable extra fodder to Ashnod's Altar.
2. Super Shredder gains a counter. If Plunderer is needed for payment, resolve its Treasure trigger before Shredder's trigger.
3. Pay Module [[symbol:1]] from the mana outlet or Plunderer Treasure; create a Servo. Sacrificing Treasure causes an extra Shredder/Module opportunity; decline unpaid extras.
4. The Servo entering untaps any Station. Sacrifice it through the same outlet and repeat.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily many +1/+1 counters on the surviving counter source.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Extra creature (artifact for KCI); Shredder stays alive. Outlet two minus Module one = net one colorless.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="c108"></a>
===accordion
===panel: C108: Animation Module + Phyrexian Altar + Super Shredder

[[symbol:b]]

Cards Required:
- [[Animation Module]]
- [[Phyrexian Altar]]
- [[Super Shredder]]

Prerequisites:
- All permanents on the battlefield.
- You control an additional creature.

Steps:
1. Sacrifice suitable extra fodder to Phyrexian Altar.
2. Super Shredder gains a counter. If Plunderer is needed for payment, resolve its Treasure trigger before Shredder's trigger.
3. Pay Module [[symbol:1]] from the mana outlet or Plunderer Treasure; create a Servo. Sacrificing Treasure causes an extra Shredder/Module opportunity; decline unpaid extras.
4. The Servo entering untaps any Station. Sacrifice it through the same outlet and repeat.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily many +1/+1 counters on the surviving counter source.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Extra creature; Shredder stays alive. Outlet one minus Module one = neutral.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="c109"></a>
===accordion
===panel: C109: Animation Module + Pitiless Plunderer + Arcbound Ravager

[[symbol:b]]

Cards Required:
- [[Animation Module]]
- [[Pitiless Plunderer]]
- [[Arcbound Ravager]]

Prerequisites:
- All permanents on the battlefield.
- You control an additional artifact creature (Arcbound Ravager can only sacrifice artifacts).

Steps:
1. Sacrifice suitable fodder to Arcbound Ravager.
2. Resolve Plunderer first to create Treasure, then resolve the outlet's +1/+1-counter ability.
3. Spend the Treasure for [[symbol:1]] on Module's trigger to create a replacement Servo.
4. Repeat; keep the counter-generating outlet and Plunderer alive.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily many +1/+1 counters on the surviving counter source.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Additional artifact creature; Ravager and Plunderer stay alive. Resolve Treasure before Ravager counter ability, then pay Module. Neutral mana.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="c110"></a>
===accordion
===panel: C110: Animation Module + Krark-Clan Ironworks + Super Shredder

[[symbol:b]]

Cards Required:
- [[Animation Module]]
- [[Krark-Clan Ironworks]]
- [[Super Shredder]]

Prerequisites:
- All permanents on the battlefield.
- You control an additional artifact creature (Krark-Clan Ironworks can only sacrifice artifacts).

Steps:
1. Sacrifice suitable extra fodder to Krark-Clan Ironworks.
2. Super Shredder gains a counter. If Plunderer is needed for payment, resolve its Treasure trigger before Shredder's trigger.
3. Pay Module [[symbol:1]] from the mana outlet or Plunderer Treasure; create a Servo. Sacrificing Treasure causes an extra Shredder/Module opportunity; decline unpaid extras.
4. The Servo entering untaps any Station. Sacrifice it through the same outlet and repeat.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily many +1/+1 counters on the surviving counter source.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Extra creature (artifact for KCI); Shredder stays alive. Outlet two minus Module one = net one colorless.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="c113"></a>
===accordion
===panel: C113: The Ooze + Animation Module + Ashnod's Altar

[[symbol:c]]

Cards Required:
- [[The Ooze]]
- [[Animation Module]]
- [[Ashnod's Altar]]

Prerequisites:
- All three permanents on the battlefield.
- You control an additional creature (to use as a starter).
- At least one targetable card in a graveyard for The Ooze's {T} ability.
- [[symbol:2]] mana initially available for the first Mutagen and Animation Module activations.
- Your main phase, with an empty stack when activating Mutagen.

Steps:
1. Tap Ooze, exile the seed graveyard card and create Mutagen. Spend [[symbol:1]] to activate Mutagen on the starter body; spend [[symbol:1]] on Module to create a Servo.
2. Sacrifice the countered starter to Ashnod's Altar. Ooze creates another Mutagen.
3. Use the two generated mana (Altar [[symbol:2]], or Phyrexian Altar [[symbol:1]] plus Treasure [[symbol:1]]) to activate Mutagen on the Servo and pay Module for a new Servo.
4. Sacrifice the countered Servo to Ashnod's Altar; repeat. Each Mutagen activation waits for your main phase and an empty stack.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Extra starter body (artifact for KCI), untapped Ooze, a targetable graveyard card, [[symbol:2]] seed. Mutagen activations only in own main phase with stack empty. Two generated and two spent: neutral.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="c114"></a>
===accordion
===panel: C114: The Ooze + Animation Module + Krark-Clan Ironworks

[[symbol:c]]

Cards Required:
- [[The Ooze]]
- [[Animation Module]]
- [[Krark-Clan Ironworks]]

Prerequisites:
- All three permanents on the battlefield.
- You control an extra **artifact creature** to start the loop.
- At least one graveyard card for The Ooze to exile, and [[symbol:2]] initial mana for Mutagen and Animation Module.
- Your main phase with an empty stack to activate Mutagen.

Steps:
1. Tap Ooze, exile the seed graveyard card and create Mutagen. Spend [[symbol:1]] to activate Mutagen on the starter body; spend [[symbol:1]] on Module to create a Servo.
2. Sacrifice the countered starter to Krark-Clan Ironworks. Ooze creates another Mutagen.
3. Use the two generated mana (Altar [[symbol:2]], or Phyrexian Altar [[symbol:1]] plus Treasure [[symbol:1]]) to activate Mutagen on the Servo and pay Module for a new Servo.
4. Sacrifice the countered Servo to Krark-Clan Ironworks; repeat. Each Mutagen activation waits for your main phase and an empty stack.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Extra starter body (artifact for KCI), untapped Ooze, a targetable graveyard card, [[symbol:2]] seed. Mutagen activations only in own main phase with stack empty. Two generated and two spent: neutral.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="c115"></a>
===accordion
===panel: C115: Super Shredder + Animation Module + Pitiless Plunderer + Altar of Dementia

[[symbol:b]]

Cards Required:
- [[Super Shredder]]
- [[Animation Module]]
- [[Pitiless Plunderer]]
- [[Altar of Dementia]]

Prerequisites:
- All four permanents on the battlefield and one other creature you control available to sacrifice.

Steps:
1. Sacrifice suitable extra fodder to Altar of Dementia.
2. Super Shredder gains a counter. If Plunderer is needed for payment, resolve its Treasure trigger before Shredder's trigger.
3. Pay Module [[symbol:1]] from the mana outlet or Plunderer Treasure; create a Servo. Sacrificing Treasure causes an extra Shredder/Module opportunity; decline unpaid extras.
4. The Servo entering untaps any Station. Sacrifice it through the same outlet and repeat.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Repeatable mill; actual cards milled are library-bounded, and emptying a library is not by itself immediate elimination.
- Arbitrarily many +1/+1 counters on the surviving counter source.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Extra creature (artifact for Grinding), Station untapped where used. Plunderer creates Module payment. Order triggers to get Treasure in time; decline extra Module payments. Neutral; counters grow.

===endpanel
===endaccordion

<a id="c116"></a>
===accordion
===panel: C116: Super Shredder + Animation Module + Pitiless Plunderer + Blasting Station

[[symbol:b]]

Cards Required:
- [[Super Shredder]]
- [[Animation Module]]
- [[Pitiless Plunderer]]
- [[Blasting Station]]

Prerequisites:
- All four permanents on battlefield, Blasting Station untapped, and one additional creature to sacrifice.

Steps:
1. Sacrifice suitable extra fodder to Blasting Station.
2. Super Shredder gains a counter. If Plunderer is needed for payment, resolve its Treasure trigger before Shredder's trigger.
3. Pay Module [[symbol:1]] from the mana outlet or Plunderer Treasure; create a Servo. Sacrificing Treasure causes an extra Shredder/Module opportunity; decline unpaid extras.
4. The Servo entering untaps any Station. Sacrifice it through the same outlet and repeat.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Direct lethal damage or life loss through the named payoff.
- Arbitrarily many +1/+1 counters on the surviving counter source.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Extra creature (artifact for Grinding), Station untapped where used. Plunderer creates Module payment. Order triggers to get Treasure in time; decline extra Module payments. Neutral; counters grow.

===endpanel
===endaccordion

<a id="c117"></a>
===accordion
===panel: C117: Super Shredder + Animation Module + Pitiless Plunderer + Grinding Station

[[symbol:b]]

Cards Required:
- [[Super Shredder]]
- [[Animation Module]]
- [[Pitiless Plunderer]]
- [[Grinding Station]]

Prerequisites:
- All four permanents on battlefield, Grinding Station untapped, and another artifact creature to sacrifice initially.

Steps:
1. Sacrifice suitable extra fodder to Grinding Station.
2. Super Shredder gains a counter. If Plunderer is needed for payment, resolve its Treasure trigger before Shredder's trigger.
3. Pay Module [[symbol:1]] from the mana outlet or Plunderer Treasure; create a Servo. Sacrificing Treasure causes an extra Shredder/Module opportunity; decline unpaid extras.
4. The Servo entering untaps any Station. Sacrifice it through the same outlet and repeat.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Repeatable mill; actual cards milled are library-bounded, and emptying a library is not by itself immediate elimination.
- Arbitrarily many +1/+1 counters on the surviving counter source.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Extra creature (artifact for Grinding), Station untapped where used. Plunderer creates Module payment. Order triggers to get Treasure in time; decline extra Module payments. Neutral; counters grow.

===endpanel
===endaccordion

<a id="c118"></a>
===accordion
===panel: C118: Super Shredder + Animation Module + Pitiless Plunderer + Umbral Collar Zealot

[[symbol:b]]

Cards Required:
- [[Super Shredder]]
- [[Animation Module]]
- [[Pitiless Plunderer]]
- [[Umbral Collar Zealot]]

Prerequisites:
- All four permanents on battlefield and one additional creature to sacrifice.

Steps:
1. Sacrifice suitable extra fodder to Umbral Collar Zealot.
2. Super Shredder gains a counter. If Plunderer is needed for payment, resolve its Treasure trigger before Shredder's trigger.
3. Pay Module [[symbol:1]] from the mana outlet or Plunderer Treasure; create a Servo. Sacrificing Treasure causes an extra Shredder/Module opportunity; decline unpaid extras.
4. The Servo entering untaps any Station. Sacrifice it through the same outlet and repeat.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Repeatable surveil events; actual card access is library-bounded.
- Arbitrarily many +1/+1 counters on the surviving counter source.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Extra creature (artifact for Grinding), Station untapped where used. Plunderer creates Module payment. Order triggers to get Treasure in time; decline extra Module payments. Neutral; counters grow.

===endpanel
===endaccordion

<a id="c119"></a>
===accordion
===panel: C119: The Ooze + Animation Module + Pitiless Plunderer + Phyrexian Altar

[[symbol:b]]

Cards Required:
- [[The Ooze]]
- [[Animation Module]]
- [[Pitiless Plunderer]]
- [[Phyrexian Altar]]

Prerequisites:
- All four permanents on battlefield.
- An extra creature to start, a targetable graveyard card, and [[symbol:2]] seed mana.
- Perform Mutagen activations as a sorcery.

Steps:
1. Tap Ooze, exile the seed graveyard card and create Mutagen. Spend [[symbol:1]] to activate Mutagen on the starter body; spend [[symbol:1]] on Module to create a Servo.
2. Sacrifice the countered starter to Phyrexian Altar. Ooze creates another Mutagen; Plunderer creates a Treasure.
3. Use the two generated mana (Altar [[symbol:2]], or Phyrexian Altar [[symbol:1]] plus Treasure [[symbol:1]]) to activate Mutagen on the Servo and pay Module for a new Servo.
4. Sacrifice the countered Servo to Phyrexian Altar; repeat. Each Mutagen activation waits for your main phase and an empty stack.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Extra starter body (artifact for KCI), untapped Ooze, a targetable graveyard card, [[symbol:2]] seed. Mutagen activations only in own main phase with stack empty. Two generated and two spent: neutral.

===endpanel
===endaccordion

<a id="c120"></a>
===accordion
===panel: C120: Marionette Apprentice + Nim Deathmantle + Phyrexian Altar + Pitiless Plunderer

[[symbol:b]]

Cards Required:
- [[Marionette Apprentice]]
- [[Nim Deathmantle]]
- [[Phyrexian Altar]]
- [[Pitiless Plunderer]]

Prerequisites:
- All four named permanents are on the battlefield.
- You control a Servo from Apprentice; choose fabricate’s Servo mode on every return.
- Keep Pitiless Plunderer on the battlefield throughout the loop.

Steps:
1. Sacrifice the Servo to Phyrexian Altar for one mana. Resolve Apprentice’s drain and Plunderer’s trigger to create a Treasure.
2. Sacrifice that Treasure for a second mana while Apprentice is still on the battlefield. Apprentice triggers again, draining every opponent.
3. Sacrifice Apprentice to Phyrexian Altar for a third mana. Both Deathmantle and Plunderer trigger; put Plunderer above Deathmantle.
4. Resolve Plunderer, creating a second Treasure. Sacrifice it for a fourth mana.
5. Pay [[symbol:4]] to Deathmantle’s trigger, returning Apprentice and attaching Deathmantle.
6. Resolve fabricate to create a new Servo. Repeat.

Results:
- Lethal life loss to every opponent: two guaranteed Apprentice triggers per cycle with this ordering.
- Arbitrarily many creature deaths, entries, Treasure creations and artifact sacrifices.
- Mana-neutral: two Altar mana plus two Treasure mana pay the four-mana return.

Classification: Unbounded resource loop.

Audit Notes:
- Net-new configuration enabled by Apprentice in this list.
- The second Treasure is sacrificed while Apprentice is absent, so do not count an Apprentice trigger for that Treasure in this sequence.

===endpanel
===endaccordion

<a id="c121"></a>
===accordion
===panel: C121: Marionette Apprentice + Warren Soultrader + Gravecrawler

[[symbol:b]]

Cards Required:
- [[Marionette Apprentice]]
- [[Warren Soultrader]]
- [[Gravecrawler]]

Prerequisites:
- All three named creatures are on the battlefield.
- Warren Soultrader supplies the additional Zombie required to cast Gravecrawler from the graveyard.
- You have enough life for the finite number of required cycles; at least 21 life suffices against opponents at 40 life each.

Steps:
1. Pay 1 life and sacrifice Gravecrawler to Warren Soultrader. Apprentice triggers, causing each opponent to lose 1 life.
2. Resolve Warren’s ability to create a Treasure.
3. Sacrifice the Treasure for [[symbol:b]]. Apprentice triggers again, causing each opponent to lose another life.
4. With Warren still on the battlefield, cast Gravecrawler from the graveyard for [[symbol:b]].
5. Repeat only while you can pay the life cost safely. Stop when the opponents have lost; the last recast is unnecessary if the Treasure trigger already ends the game.

Results:
- Finite life-limited lethal sequence when the stated life budget suffices.
- Each full cycle costs you 1 life and causes each opponent to lose 2 life.
- Mana-neutral after setup; repeated Gravecrawler casts and creature/artifact sacrifice events.

Classification: Finite sequence.

Audit Notes:
- This is life-limited, not an infinite loop: Apprentice causes life loss but does not gain you life.
- If the highest opposing life total is H, at most ceil(H/2) cycles are needed, and you need more life than that number to pay Warren’s costs safely.
- Against three opponents at 40 life, 20 cycles drain all three for 40 while costing you 20 life; start the sequence with at least 21 life after setup.
- Creature death and Treasure sacrifice are two separate events. A single artifact-creature death triggers Apprentice only once.

===endpanel
===endaccordion

<a id="c122"></a>
===accordion
===panel: C122: Marionette Apprentice + Warren Soultrader + Stridehangar Automaton

[[symbol:b]]

Cards Required:
- [[Marionette Apprentice]]
- [[Warren Soultrader]]
- [[Stridehangar Automaton]]

Prerequisites:
- All three named creatures are on the battlefield.
- You control another creature to sacrifice. Apprentice’s fabricate Servo can supply this starter.
- At least 21 life after setup suffices against three opponents at 40 life each.

Steps:
1. Pay 1 life and sacrifice the starter creature to Warren. Apprentice triggers, causing each opponent to lose 1 life.
2. Resolve Warren’s ability. Create a Treasure plus an additional Thopter through Stridehangar’s replacement effect.
3. Sacrifice the Treasure for one mana. Apprentice triggers again, causing each opponent to lose another life.
4. Sacrifice the replacement Thopter to Warren and repeat while the life budget permits. Stridehangar remains on the battlefield.
5. Stop when all opponents have lost. Surplus mana may be generated, but the number of cycles remains limited by your life total.

Results:
- Finite life-limited lethal sequence when the stated life budget suffices.
- Each full cycle costs you 1 life, causes each opponent to lose 2 life, and adds one mana.
- Repeated token creation and artifact-creature/Treasure sacrifice events.

Classification: Finite sequence.

Audit Notes:
- This is life-limited, not an infinite loop: Apprentice causes life loss but does not gain you life.
- If the highest opposing life total is H, at most ceil(H/2) cycles are needed, and you need more life than that number to pay Warren’s costs safely.
- Against three opponents at 40 life, 20 cycles drain all three for 40 while costing you 20 life; start the sequence with at least 21 life after setup.
- Creature death and Treasure sacrifice are two separate events. A single artifact-creature death triggers Apprentice only once.

===endpanel
===endaccordion

<a id="t001"></a>
===accordion
===panel: T001: Tarrian's Soulcleaver + Animation Module + Ashnod's Altar

[[symbol:c]]

Cards Required:
- [[Tarrian's Soulcleaver]]
- [[Animation Module]]
- [[Ashnod's Altar]]

Prerequisites:
- All named engine permanents are on the battlefield, except any cards explicitly assigned other zones.
- Soulcleaver already equipped to a surviving creature, plus another creature. Equip costs [[symbol:2]]; no extra loop seed mana.

Steps:
1. Sacrifice starter to Altar for [[symbol:2]]; Soulcleaver puts a counter on its host.
2. Pay [[symbol:1]] to Module to make a Servo.
3. Sacrifice Servo and repeat.
4. Do not sacrifice the host.

Results:
- Net [[symbol:c]] per cycle; unbounded counters, artifact-creature entries/deaths. Ultron makes this lethal.

Classification: Unbounded resource loop.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="t002"></a>
===accordion
===panel: T002: Tarrian's Soulcleaver + Animation Module + Krark-Clan Ironworks

[[symbol:c]]

Cards Required:
- [[Tarrian's Soulcleaver]]
- [[Animation Module]]
- [[Krark-Clan Ironworks]]

Prerequisites:
- All named engine permanents are on the battlefield, except any cards explicitly assigned other zones.
- Soulcleaver already equipped to a surviving creature, plus another artifact (not necessarily a creature).

Steps:
1. Sacrifice starter artifact to KCI for [[symbol:2]]; put a counter on the host and pay Module [[symbol:1]] for Servo.
2. Sacrifice Servo to KCI and repeat.

Results:
- Net [[symbol:c]] per cycle; unbounded counters and artifact deaths. Ultron makes this lethal.

Classification: Unbounded resource loop.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="t003"></a>
===accordion
===panel: T003: Tarrian's Soulcleaver + Animation Module + Phyrexian Altar

[[symbol:c]]

Cards Required:
- [[Tarrian's Soulcleaver]]
- [[Animation Module]]
- [[Phyrexian Altar]]

Prerequisites:
- All named engine permanents are on the battlefield, except any cards explicitly assigned other zones.
- Soulcleaver already equipped to a surviving creature, plus another creature.

Steps:
1. Sacrifice starter for one mana.
2. Resolve Soulcleaver counter, spend that mana on Module for Servo.
3. Sacrifice Servo for one and repeat.

Results:
- Mana-neutral; unbounded counters and artifact-creature deaths, not surplus colored mana. Ultron makes this lethal.

Classification: Unbounded resource loop.


Optional Payoff:
- [[Marionette Apprentice]] on the battlefield turns the repeated creature/artifact deaths in this engine into lethal life loss to every opponent. Keep Apprentice alive as the observer.
- Apprentice’s fabricate Servo can provide starter fodder where an expendable artifact creature is needed; it does not replace a required recyclable nontoken body or the additional Zombie for Gravecrawler.
- This is an optional finishing extension, not another independently counted core configuration.

===endpanel
===endaccordion

<a id="t004"></a>
===accordion
===panel: T004: Tarrian's Soulcleaver + Animation Module + Pitiless Plunderer + Altar of Dementia

[[symbol:b]]

Cards Required:
- [[Tarrian's Soulcleaver]]
- [[Animation Module]]
- [[Pitiless Plunderer]]
- [[Altar of Dementia]]

Prerequisites:
- All named engine permanents are on the battlefield, except any cards explicitly assigned other zones.
- Soulcleaver equipped to a surviving host and extra creature. Keep Plunderer and any creature outlet alive.

Steps:
1. Sacrifice fodder through the outlet.
2. Put Plunderer above Soulcleaver on the stack so Treasure resolves first.
3. Soulcleaver counters the host; spend Treasure on Module for a Servo.
4. Treasure sacrifice causes another Soulcleaver trigger: decline its extra Module payment unless funded.
5. Sacrifice the Servo and repeat.

Results:
- Mana-neutral; growing host counters and repeatable artifact deaths. Mills one per Servo; mill alone does not immediately eliminate a player. Ultron also supplies lethal drain.

Classification: Unbounded resource loop.

===endpanel
===endaccordion

<a id="t005"></a>
===accordion
===panel: T005: Tarrian's Soulcleaver + Animation Module + Pitiless Plunderer + Blasting Station

[[symbol:b]]

Cards Required:
- [[Tarrian's Soulcleaver]]
- [[Animation Module]]
- [[Pitiless Plunderer]]
- [[Blasting Station]]

Prerequisites:
- All named engine permanents are on the battlefield, except any cards explicitly assigned other zones.
- Soulcleaver equipped to a surviving host and extra creature. Keep Plunderer and any creature outlet alive. Station starts untapped.

Steps:
1. Sacrifice fodder through the outlet.
2. Put Plunderer above Soulcleaver on the stack so Treasure resolves first.
3. Soulcleaver counters the host; spend Treasure on Module for a Servo.
4. Treasure sacrifice causes another Soulcleaver trigger: decline its extra Module payment unless funded.
5. Sacrifice the Servo and repeat.
6. Its entry untaps the Station.

Results:
- Mana-neutral; growing host counters and repeatable artifact deaths. One direct damage per Servo, directly lethal. Ultron also supplies lethal drain.

Classification: Unbounded resource loop.

===endpanel
===endaccordion

<a id="t006"></a>
===accordion
===panel: T006: Tarrian's Soulcleaver + Animation Module + Pitiless Plunderer + Grinding Station

[[symbol:b]]

Cards Required:
- [[Tarrian's Soulcleaver]]
- [[Animation Module]]
- [[Pitiless Plunderer]]
- [[Grinding Station]]

Prerequisites:
- All named engine permanents are on the battlefield, except any cards explicitly assigned other zones.
- Soulcleaver equipped to a surviving host and extra artifact creature. Keep Plunderer and any creature outlet alive. Station starts untapped.

Steps:
1. Sacrifice fodder through the outlet.
2. Put Plunderer above Soulcleaver on the stack so Treasure resolves first.
3. Soulcleaver counters the host; spend Treasure on Module for a Servo.
4. Treasure sacrifice causes another Soulcleaver trigger: decline its extra Module payment unless funded.
5. Sacrifice the Servo and repeat.
6. Its entry untaps the Station.

Results:
- Mana-neutral; growing host counters and repeatable artifact deaths. Mills three per Servo; mill alone does not immediately eliminate a player. Ultron also supplies lethal drain.

Classification: Unbounded resource loop.

===endpanel
===endaccordion

<a id="t007"></a>
===accordion
===panel: T007: Tarrian's Soulcleaver + Animation Module + Pitiless Plunderer + Umbral Collar Zealot

[[symbol:b]]

Cards Required:
- [[Tarrian's Soulcleaver]]
- [[Animation Module]]
- [[Pitiless Plunderer]]
- [[Umbral Collar Zealot]]

Prerequisites:
- All named engine permanents are on the battlefield, except any cards explicitly assigned other zones.
- Soulcleaver equipped to a surviving host and extra creature. Keep Plunderer and any creature outlet alive.

Steps:
1. Sacrifice fodder through the outlet.
2. Put Plunderer above Soulcleaver on the stack so Treasure resolves first.
3. Soulcleaver counters the host; spend Treasure on Module for a Servo.
4. Treasure sacrifice causes another Soulcleaver trigger: decline its extra Module payment unless funded.
5. Sacrifice the Servo and repeat.

Results:
- Mana-neutral; growing host counters and repeatable artifact deaths. Repeated surveil events, with finite library card access. Ultron also supplies lethal drain.

Classification: Unbounded resource loop.

===endpanel
===endaccordion

<a id="t008"></a>
===accordion
===panel: T008: Tarrian's Soulcleaver + Animation Module + Warren Soultrader + Zulaport Cutthroat

[[symbol:b]]

Cards Required:
- [[Tarrian's Soulcleaver]]
- [[Animation Module]]
- [[Warren Soultrader]]
- [[Zulaport Cutthroat]]

Prerequisites:
- All named engine permanents are on the battlefield, except any cards explicitly assigned other zones.
- Soulcleaver equipped to a surviving host (the drain creature can be the host), an extra creature, and life >= 2.

Steps:
1. Pay one life and sacrifice fodder to Warren.
2. Resolve the death-drain life gain, then Warren creates Treasure.
3. Use Treasure to pay the Module trigger generated by Soulcleaver putting a counter on the host.
4. Make a Servo and repeat.
5. Decline extra Module payments from Treasure deaths.

Results:
- Life- and mana-neutral, unbounded deaths/counters; directly lethal drain. No ongoing card draws.

Classification: Unbounded resource loop.

===endpanel
===endaccordion

<a id="t009"></a>
===accordion
===panel: T009: Tarrian's Soulcleaver + Animation Module + Warren Soultrader + Sephiroth, Fabled SOLDIER

[[symbol:b]]

Cards Required:
- [[Tarrian's Soulcleaver]]
- [[Animation Module]]
- [[Warren Soultrader]]
- [[Sephiroth, Fabled SOLDIER]]

Prerequisites:
- All named engine permanents are on the battlefield, except any cards explicitly assigned other zones.
- Soulcleaver equipped to a surviving host (the drain creature can be the host), an extra creature, and life >= 2.

Steps:
1. Pay one life and sacrifice fodder to Warren.
2. Resolve the death-drain life gain, then Warren creates Treasure.
3. Use Treasure to pay the Module trigger generated by Soulcleaver putting a counter on the host.
4. Make a Servo and repeat.
5. Decline extra Module payments from Treasure deaths.
6. The real Sephiroth transforms after the fourth death-trigger resolution; its emblem continues the drain.
7. Decline its optional ETB sacrifice.

Results:
- Life- and mana-neutral, unbounded deaths/counters; directly lethal drain. No ongoing card draws.

Classification: Unbounded resource loop.

===endpanel
===endaccordion

<a id="t010"></a>
===accordion
===panel: T010: Tarrian's Soulcleaver + Walking Ballista + Gravecrawler + Pitiless Plunderer + Warren Soultrader

[[symbol:b]]

Cards Required:
- [[Tarrian's Soulcleaver]]
- [[Walking Ballista]]
- [[Gravecrawler]]
- [[Pitiless Plunderer]]
- [[Warren Soultrader]]

Prerequisites:
- All named engine permanents are on the battlefield, except any cards explicitly assigned other zones.
- Equip Soulcleaver to Ballista. Ballista has >= 2 counters; Gravecrawler is on battlefield. Warren remains as the additional Zombie; do not use its sacrifice ability. Ballista has no damage marked or toughness reduction.

Steps:
1. Remove one Ballista counter to kill the 2/1 Gravecrawler.
2. Ballista retains at least one counter while the damage resolves.
3. Gravecrawler death gives one Soulcleaver counter and Plunderer gives a Treasure.
4. Sacrifice Treasure for [[symbol:b]], causing another Soulcleaver counter on Ballista.
5. Recast Gravecrawler for [[symbol:b]].
6. Each cycle gains one Ballista counter; spend surplus counters to damage opponents, maintaining the two-counter starting buffer.

Results:
- Direct lethal Ballista damage; mana-neutral, net one counter per cycle before spending surplus. Warren is explicitly required here to avoid using Carrion Feeder, whose Gravecrawler/Plunderer engine would make the equipment line a redundant extension.

Classification: Unbounded resource loop.

===endpanel
===endaccordion

<a id="t011"></a>
===accordion
===panel: T011: Tarrian's Soulcleaver + Walking Ballista + Gravecrawler + The Ghoul, Gunslinger

[[symbol:b]]

Cards Required:
- [[Tarrian's Soulcleaver]]
- [[Walking Ballista]]
- [[Gravecrawler]]
- [[The Ghoul, Gunslinger]]

Prerequisites:
- All named engine permanents are on the battlefield, except any cards explicitly assigned other zones.
- Equip Soulcleaver to Ballista with >= 2 counters, no damage/toughness reduction; Gravecrawler on battlefield. The Ghoul remains as the other Zombie.

Steps:
1. Shoot Gravecrawler for one, leaving a counter on Ballista.
2. Resolve Soulcleaver for +1.
3. The Ghoul death trigger targets you, adds two rad counters and creates Treasure.
4. Sacrifice it for [[symbol:b]], giving Ballista another Soulcleaver counter; recast Gravecrawler.
5. Gain one spare Ballista counter each cycle and spend it on opponents while keeping two for the next cycle.

Results:
- Direct lethal Ballista damage; mana-neutral; accumulate two rad counters per cycle. The Ghoul supplies both Zombie permission and Treasure, so Plunderer is unnecessary.

Classification: Unbounded resource loop.

===endpanel
===endaccordion

<a id="t012"></a>
===accordion
===panel: T012: Tarrian's Soulcleaver + Walking Ballista + Pitiless Plunderer + Stridehangar Automaton

[[symbol:b]]

Cards Required:
- [[Tarrian's Soulcleaver]]
- [[Walking Ballista]]
- [[Pitiless Plunderer]]
- [[Stridehangar Automaton]]

Prerequisites:
- All named engine permanents are on the battlefield, except any cards explicitly assigned other zones.
- Equip Soulcleaver to Ballista with >= 3 counters and no damage/toughness reduction; control an extra Thopter. Stridehangar makes this Thopter 2/2, not 1/1.

Steps:
1. Spend TWO Ballista counters to deal two damage to the Thopter, keeping at least one counter on Ballista throughout.
2. Its death gives Ballista +1 and creates a Plunderer Treasure plus replacement Thopter through Stridehangar.
3. Sacrifice Treasure for mana, giving Ballista another +1.
4. Ballista is back to three counters, with one new mana and a replacement Thopter.
5. Repeat to generate arbitrary mana.
6. Spend [[symbol:4]] at a time to add extra Ballista counters, then shoot opponents while preserving the three-counter loop buffer.

Results:
- Net one mana of any color per cycle; directly lethal via Ballista after converting surplus mana to counters. Three-counter minimum accounts for the Thopter anthem and state-based deaths.

Classification: Unbounded resource loop.

===endpanel
===endaccordion

<a id="t013"></a>
===accordion
===panel: T013: Tarrian's Soulcleaver + Walking Ballista + Animation Module + Pitiless Plunderer

[[symbol:b]]

Cards Required:
- [[Tarrian's Soulcleaver]]
- [[Walking Ballista]]
- [[Animation Module]]
- [[Pitiless Plunderer]]

Prerequisites:
- All named engine permanents are on the battlefield, except any cards explicitly assigned other zones.
- Soulcleaver equipped to Ballista with >= 2 counters, no damage/toughness reduction; another 1/1 Servo to start. If no Servo exists, Module can add a counter to Ballista for [[symbol:3]], then pay [[symbol:1]] to its trigger to create one as a separate setup step.

Steps:
1. Remove one Ballista counter to kill the Servo, retaining at least one counter.
2. Order Plunderer above Soulcleaver so Treasure is ready.
3. Soulcleaver adds one counter; pay the resulting Module trigger with Treasure to create a replacement Servo.
4. Sacrificing Treasure causes a second Soulcleaver counter: decline its extra Module payment.
5. Ballista gains two counters while spending one per Servo, for net one.
6. Spend surplus counters to damage opponents while preserving the two-counter buffer.

Results:
- Mana-neutral; direct lethal Ballista damage, with one net counter per cycle before spending surplus. Ballista supplies the otherwise-missing sacrifice/removal outlet, so this does not contain one of T001–T009 as a smaller named subset.

Classification: Unbounded resource loop.

===endpanel
===endaccordion

<a id="t014"></a>
===accordion
===panel: T014: Tarrian's Soulcleaver + Walking Ballista + Tortured Existence + Imotekh the Stormlord + Pitiless Plunderer

[[symbol:b]]

Cards Required:
- [[Tarrian's Soulcleaver]]
- [[Walking Ballista]]
- [[Tortured Existence]]
- [[Imotekh the Stormlord]]
- [[Pitiless Plunderer]]

Prerequisites:
- All named engine permanents are on the battlefield, except any cards explicitly assigned other zones.
- Soulcleaver equipped to Ballista with >= 3 counters, no damage/toughness reduction. Two other artifact creature cards alternate hand/graveyard; [[symbol:b]] seed. Imotekh and Plunderer survive.

Steps:
1. Pay [[symbol:b]] to Tortured Existence, discarding one artifact creature card to return the other.
2. Imotekh creates two 2/2 Necrons.
3. Shoot the first Necron twice, retaining a Ballista counter; its death gives +1 counter and a Treasure.
4. Sacrifice that Treasure for mana, restoring another counter.
5. Ballista is back to at least three.
6. Repeat for the second Necron.
7. Two Treasure mana were made; reserve [[symbol:b]] for the next exchange and keep one surplus.
8. The two fuel cards have exchanged zones, so the exchange can repeat.
9. Convert surplus mana through Ballista’s [[symbol:4]] ability to more counters and damage opponents while retaining the three-counter buffer.

Results:
- Net one mana of any color per artifact-card exchange; direct lethal Ballista damage after mana conversion. This is a Ballista outlet variant of the Tortured Existence/Imotekh resource architecture.

Classification: Unbounded resource loop.

===endpanel
===endaccordion

===endpanel
===endaccordion

===accordion
===panel: Card Index

Active configurations only; archived configurations are excluded.

===accordion
===panel: Aetherflux Reservoir

- [C002](#c002): Sensei's Divining Top + Aetherflux Reservoir + Bolas's Citadel
- [C003](#c003): Warren Soultrader + Aetherflux Reservoir + Gravecrawler
- [C050](#c050): Metalwork Colossus + Warren Soultrader + Pitiless Plunderer + Aetherflux Reservoir
- [C051](#c051): Metalwork Colossus + Warren Soultrader + Aetherflux Reservoir + Stridehangar Automaton

===endpanel
===endaccordion

===accordion
===panel: Altar of Dementia

- [C004](#c004): Gravecrawler + Pitiless Plunderer + Altar of Dementia
- [C005](#c005): The Ghoul, Gunslinger + Gravecrawler + Altar of Dementia
- [C006](#c006): Pitiless Plunderer + Altar of Dementia + Stridehangar Automaton
- [C052](#c052): Tortured Existence + Pitiless Plunderer + Imotekh the Stormlord + Altar of Dementia
- [C053](#c053): Out of the Tombs + Skullclamp + Pitiless Plunderer + Altar of Dementia
- [C115](#c115): Super Shredder + Animation Module + Pitiless Plunderer + Altar of Dementia
- [T004](#t004): Tarrian's Soulcleaver + Animation Module + Pitiless Plunderer + Altar of Dementia

===endpanel
===endaccordion

===accordion
===panel: Animation Module

- [C106](#c106): Animation Module + Pitiless Plunderer + Carrion Feeder
- [C107](#c107): Animation Module + Ashnod's Altar + Super Shredder
- [C108](#c108): Animation Module + Phyrexian Altar + Super Shredder
- [C109](#c109): Animation Module + Pitiless Plunderer + Arcbound Ravager
- [C110](#c110): Animation Module + Krark-Clan Ironworks + Super Shredder
- [C113](#c113): The Ooze + Animation Module + Ashnod's Altar
- [C114](#c114): The Ooze + Animation Module + Krark-Clan Ironworks
- [C115](#c115): Super Shredder + Animation Module + Pitiless Plunderer + Altar of Dementia
- [C116](#c116): Super Shredder + Animation Module + Pitiless Plunderer + Blasting Station
- [C117](#c117): Super Shredder + Animation Module + Pitiless Plunderer + Grinding Station
- [C118](#c118): Super Shredder + Animation Module + Pitiless Plunderer + Umbral Collar Zealot
- [C119](#c119): The Ooze + Animation Module + Pitiless Plunderer + Phyrexian Altar
- [T001](#t001): Tarrian's Soulcleaver + Animation Module + Ashnod's Altar
- [T002](#t002): Tarrian's Soulcleaver + Animation Module + Krark-Clan Ironworks
- [T003](#t003): Tarrian's Soulcleaver + Animation Module + Phyrexian Altar
- [T004](#t004): Tarrian's Soulcleaver + Animation Module + Pitiless Plunderer + Altar of Dementia
- [T005](#t005): Tarrian's Soulcleaver + Animation Module + Pitiless Plunderer + Blasting Station
- [T006](#t006): Tarrian's Soulcleaver + Animation Module + Pitiless Plunderer + Grinding Station
- [T007](#t007): Tarrian's Soulcleaver + Animation Module + Pitiless Plunderer + Umbral Collar Zealot
- [T008](#t008): Tarrian's Soulcleaver + Animation Module + Warren Soultrader + Zulaport Cutthroat
- [T009](#t009): Tarrian's Soulcleaver + Animation Module + Warren Soultrader + Sephiroth, Fabled SOLDIER
- [T013](#t013): Tarrian's Soulcleaver + Walking Ballista + Animation Module + Pitiless Plunderer

===endpanel
===endaccordion

===accordion
===panel: Arcbound Ravager

- [C007](#c007): Pitiless Plunderer + Stridehangar Automaton + Arcbound Ravager
- [C055](#c055): Out of the Tombs + Skullclamp + Pitiless Plunderer + Arcbound Ravager
- [C109](#c109): Animation Module + Pitiless Plunderer + Arcbound Ravager

===endpanel
===endaccordion

===accordion
===panel: Ashnod's Altar

- [C008](#c008): Dross Scorpion + Retrofitter Foundry + Ashnod's Altar
- [C009](#c009): Gravecrawler + Pitiless Plunderer + Ashnod's Altar
- [C010](#c010): The Ghoul, Gunslinger + Gravecrawler + Ashnod's Altar
- [C011](#c011): Imotekh the Stormlord + Nim Deathmantle + Ashnod's Altar
- [C012](#c012): Nim Deathmantle + Ashnod's Altar + Marionette Apprentice
- [C014](#c014): Ultron the Annihilator + Nim Deathmantle + Ashnod's Altar
- [C015](#c015): Out of the Tombs + Skullclamp + Ashnod's Altar
- [C016](#c016): Pitiless Plunderer + Ashnod's Altar + Stridehangar Automaton
- [C017](#c017): The Ooze + Stridehangar Automaton + Ashnod's Altar
- [C057](#c057): Scrap Trawler + Myr Retriever + Ashnod's Altar + Cloud Key
- [C058](#c058): Scrap Trawler + Myr Retriever + Ashnod's Altar + Foundry Inspector
- [C059](#c059): Glaring Fleshraker + Ashnod's Altar + Myr Retriever + Junk Diver
- [C060](#c060): Glaring Fleshraker + Ashnod's Altar + Junk Diver + Workshop Assistant
- [C061](#c061): Glaring Fleshraker + Ashnod's Altar + Myr Retriever + Scrap Trawler
- [C062](#c062): Glaring Fleshraker + Ashnod's Altar + Myr Retriever + Workshop Assistant
- [C064](#c064): Imotekh the Stormlord + Junk Diver + Myr Retriever + Ashnod's Altar
- [C065](#c065): Imotekh the Stormlord + Junk Diver + Workshop Assistant + Ashnod's Altar
- [C066](#c066): Imotekh the Stormlord + Scrap Trawler + Myr Retriever + Ashnod's Altar
- [C067](#c067): Imotekh the Stormlord + Myr Retriever + Workshop Assistant + Ashnod's Altar
- [C068](#c068): Scrap Trawler + Myr Retriever + Ashnod's Altar + Semblance Anvil
- [C107](#c107): Animation Module + Ashnod's Altar + Super Shredder
- [C113](#c113): The Ooze + Animation Module + Ashnod's Altar
- [T001](#t001): Tarrian's Soulcleaver + Animation Module + Ashnod's Altar

===endpanel
===endaccordion

===accordion
===panel: Blasting Station

- [C018](#c018): Gravecrawler + Pitiless Plunderer + Blasting Station
- [C019](#c019): The Ghoul, Gunslinger + Gravecrawler + Blasting Station
- [C020](#c020): Pitiless Plunderer + Blasting Station + Stridehangar Automaton
- [C070](#c070): Tortured Existence + Pitiless Plunderer + Imotekh the Stormlord + Blasting Station
- [C104](#c104): Out of the Tombs + Skullclamp + Pitiless Plunderer + Blasting Station + Stitcher's Supplier
- [C116](#c116): Super Shredder + Animation Module + Pitiless Plunderer + Blasting Station
- [T005](#t005): Tarrian's Soulcleaver + Animation Module + Pitiless Plunderer + Blasting Station

===endpanel
===endaccordion

===accordion
===panel: Bolas's Citadel

- [C002](#c002): Sensei's Divining Top + Aetherflux Reservoir + Bolas's Citadel

===endpanel
===endaccordion

===accordion
===panel: Carrion Feeder

- [C021](#c021): Gravecrawler + Pitiless Plunderer + Carrion Feeder
- [C022](#c022): The Ghoul, Gunslinger + Gravecrawler + Carrion Feeder
- [C023](#c023): Pitiless Plunderer + Stridehangar Automaton + Carrion Feeder
- [C072](#c072): Tortured Existence + Pitiless Plunderer + Imotekh the Stormlord + Carrion Feeder
- [C073](#c073): Out of the Tombs + Skullclamp + Pitiless Plunderer + Carrion Feeder
- [C106](#c106): Animation Module + Pitiless Plunderer + Carrion Feeder

===endpanel
===endaccordion

===accordion
===panel: Clock of Omens

- [C024](#c024): Imotekh the Stormlord + Clock of Omens + Tortured Existence
- [C025](#c025): Retrofitter Foundry + Clock of Omens + Stridehangar Automaton
- [C026](#c026): The Ooze + Clock of Omens + Stridehangar Automaton
- [C075](#c075): The Ooze + Clock of Omens + Stridehangar Automaton + Grinding Station

===endpanel
===endaccordion

===accordion
===panel: Cloud Key

- [C027](#c027): Sensei's Divining Top + Mystic Forge + Cloud Key
- [C057](#c057): Scrap Trawler + Myr Retriever + Ashnod's Altar + Cloud Key
- [C077](#c077): Scrap Trawler + Myr Retriever + Krark-Clan Ironworks + Cloud Key

===endpanel
===endaccordion

===accordion
===panel: Dross Scorpion

- [C008](#c008): Dross Scorpion + Retrofitter Foundry + Ashnod's Altar
- [C028](#c028): Dross Scorpion + Retrofitter Foundry + Krark-Clan Ironworks
- [C029](#c029): Retrofitter Foundry + Dross Scorpion + Stridehangar Automaton

===endpanel
===endaccordion

===accordion
===panel: Foundry Inspector

- [C030](#c030): Sensei's Divining Top + Foundry Inspector + Mystic Forge
- [C058](#c058): Scrap Trawler + Myr Retriever + Ashnod's Altar + Foundry Inspector
- [C080](#c080): Scrap Trawler + Myr Retriever + Krark-Clan Ironworks + Foundry Inspector

===endpanel
===endaccordion

===accordion
===panel: Glaring Fleshraker

- [C031](#c031): Sensei's Divining Top + Glaring Fleshraker + Mystic Forge
- [C059](#c059): Glaring Fleshraker + Ashnod's Altar + Myr Retriever + Junk Diver
- [C060](#c060): Glaring Fleshraker + Ashnod's Altar + Junk Diver + Workshop Assistant
- [C061](#c061): Glaring Fleshraker + Ashnod's Altar + Myr Retriever + Scrap Trawler
- [C062](#c062): Glaring Fleshraker + Ashnod's Altar + Myr Retriever + Workshop Assistant
- [C083](#c083): Glaring Fleshraker + Myr Retriever + Junk Diver + Krark-Clan Ironworks
- [C084](#c084): Glaring Fleshraker + Junk Diver + Workshop Assistant + Krark-Clan Ironworks
- [C085](#c085): Glaring Fleshraker + Myr Retriever + Scrap Trawler + Krark-Clan Ironworks
- [C086](#c086): Glaring Fleshraker + Myr Retriever + Workshop Assistant + Krark-Clan Ironworks

===endpanel
===endaccordion

===accordion
===panel: Gravecrawler

- [C001](#c001): Gravecrawler + Phyrexian Altar
- [C003](#c003): Warren Soultrader + Aetherflux Reservoir + Gravecrawler
- [C004](#c004): Gravecrawler + Pitiless Plunderer + Altar of Dementia
- [C005](#c005): The Ghoul, Gunslinger + Gravecrawler + Altar of Dementia
- [C009](#c009): Gravecrawler + Pitiless Plunderer + Ashnod's Altar
- [C010](#c010): The Ghoul, Gunslinger + Gravecrawler + Ashnod's Altar
- [C018](#c018): Gravecrawler + Pitiless Plunderer + Blasting Station
- [C019](#c019): The Ghoul, Gunslinger + Gravecrawler + Blasting Station
- [C021](#c021): Gravecrawler + Pitiless Plunderer + Carrion Feeder
- [C022](#c022): The Ghoul, Gunslinger + Gravecrawler + Carrion Feeder
- [C032](#c032): Gravecrawler + Pitiless Plunderer + Umbral Collar Zealot
- [C033](#c033): Warren Soultrader + Gravecrawler + Sephiroth, Fabled SOLDIER
- [C034](#c034): The Ghoul, Gunslinger + Gravecrawler + Umbral Collar Zealot
- [C035](#c035): Warren Soultrader + Gravecrawler + Zulaport Cutthroat
- [C121](#c121): Marionette Apprentice + Warren Soultrader + Gravecrawler
- [T010](#t010): Tarrian's Soulcleaver + Walking Ballista + Gravecrawler + Pitiless Plunderer + Warren Soultrader
- [T011](#t011): Tarrian's Soulcleaver + Walking Ballista + Gravecrawler + The Ghoul, Gunslinger

===endpanel
===endaccordion

===accordion
===panel: Grinding Station

- [C036](#c036): Pitiless Plunderer + Stridehangar Automaton + Grinding Station
- [C075](#c075): The Ooze + Clock of Omens + Stridehangar Automaton + Grinding Station
- [C117](#c117): Super Shredder + Animation Module + Pitiless Plunderer + Grinding Station
- [T006](#t006): Tarrian's Soulcleaver + Animation Module + Pitiless Plunderer + Grinding Station

===endpanel
===endaccordion

===accordion
===panel: Imotekh the Stormlord

- [C011](#c011): Imotekh the Stormlord + Nim Deathmantle + Ashnod's Altar
- [C024](#c024): Imotekh the Stormlord + Clock of Omens + Tortured Existence
- [C037](#c037): Imotekh the Stormlord + Nim Deathmantle + Krark-Clan Ironworks
- [C038](#c038): Tortured Existence + Phyrexian Altar + Imotekh the Stormlord
- [C052](#c052): Tortured Existence + Pitiless Plunderer + Imotekh the Stormlord + Altar of Dementia
- [C064](#c064): Imotekh the Stormlord + Junk Diver + Myr Retriever + Ashnod's Altar
- [C065](#c065): Imotekh the Stormlord + Junk Diver + Workshop Assistant + Ashnod's Altar
- [C066](#c066): Imotekh the Stormlord + Scrap Trawler + Myr Retriever + Ashnod's Altar
- [C067](#c067): Imotekh the Stormlord + Myr Retriever + Workshop Assistant + Ashnod's Altar
- [C070](#c070): Tortured Existence + Pitiless Plunderer + Imotekh the Stormlord + Blasting Station
- [C072](#c072): Tortured Existence + Pitiless Plunderer + Imotekh the Stormlord + Carrion Feeder
- [C089](#c089): Imotekh the Stormlord + Junk Diver + Myr Retriever + Krark-Clan Ironworks
- [C090](#c090): Imotekh the Stormlord + Junk Diver + Workshop Assistant + Krark-Clan Ironworks
- [C091](#c091): Imotekh the Stormlord + Scrap Trawler + Myr Retriever + Krark-Clan Ironworks
- [C092](#c092): Imotekh the Stormlord + Myr Retriever + Workshop Assistant + Krark-Clan Ironworks
- [T014](#t014): Tarrian's Soulcleaver + Walking Ballista + Tortured Existence + Imotekh the Stormlord + Pitiless Plunderer

===endpanel
===endaccordion

===accordion
===panel: Junk Diver

- [C059](#c059): Glaring Fleshraker + Ashnod's Altar + Myr Retriever + Junk Diver
- [C060](#c060): Glaring Fleshraker + Ashnod's Altar + Junk Diver + Workshop Assistant
- [C064](#c064): Imotekh the Stormlord + Junk Diver + Myr Retriever + Ashnod's Altar
- [C065](#c065): Imotekh the Stormlord + Junk Diver + Workshop Assistant + Ashnod's Altar
- [C083](#c083): Glaring Fleshraker + Myr Retriever + Junk Diver + Krark-Clan Ironworks
- [C084](#c084): Glaring Fleshraker + Junk Diver + Workshop Assistant + Krark-Clan Ironworks
- [C089](#c089): Imotekh the Stormlord + Junk Diver + Myr Retriever + Krark-Clan Ironworks
- [C090](#c090): Imotekh the Stormlord + Junk Diver + Workshop Assistant + Krark-Clan Ironworks
- [C105](#c105): Scrap Trawler + Myr Retriever + Krark-Clan Ironworks + Sol Ring + Junk Diver

===endpanel
===endaccordion

===accordion
===panel: Krark-Clan Ironworks

- [C028](#c028): Dross Scorpion + Retrofitter Foundry + Krark-Clan Ironworks
- [C037](#c037): Imotekh the Stormlord + Nim Deathmantle + Krark-Clan Ironworks
- [C039](#c039): Ultron the Annihilator + Nim Deathmantle + Krark-Clan Ironworks
- [C040](#c040): Out of the Tombs + Skullclamp + Krark-Clan Ironworks
- [C041](#c041): Pitiless Plunderer + Stridehangar Automaton + Krark-Clan Ironworks
- [C042](#c042): The Ooze + Stridehangar Automaton + Krark-Clan Ironworks
- [C077](#c077): Scrap Trawler + Myr Retriever + Krark-Clan Ironworks + Cloud Key
- [C080](#c080): Scrap Trawler + Myr Retriever + Krark-Clan Ironworks + Foundry Inspector
- [C083](#c083): Glaring Fleshraker + Myr Retriever + Junk Diver + Krark-Clan Ironworks
- [C084](#c084): Glaring Fleshraker + Junk Diver + Workshop Assistant + Krark-Clan Ironworks
- [C085](#c085): Glaring Fleshraker + Myr Retriever + Scrap Trawler + Krark-Clan Ironworks
- [C086](#c086): Glaring Fleshraker + Myr Retriever + Workshop Assistant + Krark-Clan Ironworks
- [C089](#c089): Imotekh the Stormlord + Junk Diver + Myr Retriever + Krark-Clan Ironworks
- [C090](#c090): Imotekh the Stormlord + Junk Diver + Workshop Assistant + Krark-Clan Ironworks
- [C091](#c091): Imotekh the Stormlord + Scrap Trawler + Myr Retriever + Krark-Clan Ironworks
- [C092](#c092): Imotekh the Stormlord + Myr Retriever + Workshop Assistant + Krark-Clan Ironworks
- [C094](#c094): Scrap Trawler + Myr Retriever + Krark-Clan Ironworks + Semblance Anvil
- [C105](#c105): Scrap Trawler + Myr Retriever + Krark-Clan Ironworks + Sol Ring + Junk Diver
- [C110](#c110): Animation Module + Krark-Clan Ironworks + Super Shredder
- [C114](#c114): The Ooze + Animation Module + Krark-Clan Ironworks
- [T002](#t002): Tarrian's Soulcleaver + Animation Module + Krark-Clan Ironworks

===endpanel
===endaccordion

===accordion
===panel: Marionette Apprentice

- [C012](#c012): Nim Deathmantle + Ashnod's Altar + Marionette Apprentice
- [C120](#c120): Marionette Apprentice + Nim Deathmantle + Phyrexian Altar + Pitiless Plunderer
- [C121](#c121): Marionette Apprentice + Warren Soultrader + Gravecrawler
- [C122](#c122): Marionette Apprentice + Warren Soultrader + Stridehangar Automaton

===endpanel
===endaccordion

===accordion
===panel: Metalwork Colossus

- [C050](#c050): Metalwork Colossus + Warren Soultrader + Pitiless Plunderer + Aetherflux Reservoir
- [C051](#c051): Metalwork Colossus + Warren Soultrader + Aetherflux Reservoir + Stridehangar Automaton

===endpanel
===endaccordion

===accordion
===panel: Myr Retriever

- [C057](#c057): Scrap Trawler + Myr Retriever + Ashnod's Altar + Cloud Key
- [C058](#c058): Scrap Trawler + Myr Retriever + Ashnod's Altar + Foundry Inspector
- [C059](#c059): Glaring Fleshraker + Ashnod's Altar + Myr Retriever + Junk Diver
- [C061](#c061): Glaring Fleshraker + Ashnod's Altar + Myr Retriever + Scrap Trawler
- [C062](#c062): Glaring Fleshraker + Ashnod's Altar + Myr Retriever + Workshop Assistant
- [C064](#c064): Imotekh the Stormlord + Junk Diver + Myr Retriever + Ashnod's Altar
- [C066](#c066): Imotekh the Stormlord + Scrap Trawler + Myr Retriever + Ashnod's Altar
- [C067](#c067): Imotekh the Stormlord + Myr Retriever + Workshop Assistant + Ashnod's Altar
- [C068](#c068): Scrap Trawler + Myr Retriever + Ashnod's Altar + Semblance Anvil
- [C077](#c077): Scrap Trawler + Myr Retriever + Krark-Clan Ironworks + Cloud Key
- [C080](#c080): Scrap Trawler + Myr Retriever + Krark-Clan Ironworks + Foundry Inspector
- [C083](#c083): Glaring Fleshraker + Myr Retriever + Junk Diver + Krark-Clan Ironworks
- [C085](#c085): Glaring Fleshraker + Myr Retriever + Scrap Trawler + Krark-Clan Ironworks
- [C086](#c086): Glaring Fleshraker + Myr Retriever + Workshop Assistant + Krark-Clan Ironworks
- [C089](#c089): Imotekh the Stormlord + Junk Diver + Myr Retriever + Krark-Clan Ironworks
- [C091](#c091): Imotekh the Stormlord + Scrap Trawler + Myr Retriever + Krark-Clan Ironworks
- [C092](#c092): Imotekh the Stormlord + Myr Retriever + Workshop Assistant + Krark-Clan Ironworks
- [C094](#c094): Scrap Trawler + Myr Retriever + Krark-Clan Ironworks + Semblance Anvil
- [C097](#c097): Scrap Trawler + Myr Retriever + Phyrexian Altar + Semblance Anvil
- [C105](#c105): Scrap Trawler + Myr Retriever + Krark-Clan Ironworks + Sol Ring + Junk Diver

===endpanel
===endaccordion

===accordion
===panel: Mystic Forge

- [C027](#c027): Sensei's Divining Top + Mystic Forge + Cloud Key
- [C030](#c030): Sensei's Divining Top + Foundry Inspector + Mystic Forge
- [C031](#c031): Sensei's Divining Top + Glaring Fleshraker + Mystic Forge
- [C043](#c043): Sensei's Divining Top + Mystic Forge + Semblance Anvil

===endpanel
===endaccordion

===accordion
===panel: Nim Deathmantle

- [C011](#c011): Imotekh the Stormlord + Nim Deathmantle + Ashnod's Altar
- [C012](#c012): Nim Deathmantle + Ashnod's Altar + Marionette Apprentice
- [C014](#c014): Ultron the Annihilator + Nim Deathmantle + Ashnod's Altar
- [C037](#c037): Imotekh the Stormlord + Nim Deathmantle + Krark-Clan Ironworks
- [C039](#c039): Ultron the Annihilator + Nim Deathmantle + Krark-Clan Ironworks
- [C098](#c098): Ultron the Annihilator + Nim Deathmantle + Phyrexian Altar + Pitiless Plunderer
- [C120](#c120): Marionette Apprentice + Nim Deathmantle + Phyrexian Altar + Pitiless Plunderer

===endpanel
===endaccordion

===accordion
===panel: Out of the Tombs

- [C015](#c015): Out of the Tombs + Skullclamp + Ashnod's Altar
- [C040](#c040): Out of the Tombs + Skullclamp + Krark-Clan Ironworks
- [C044](#c044): Out of the Tombs + Skullclamp + Phyrexian Altar
- [C053](#c053): Out of the Tombs + Skullclamp + Pitiless Plunderer + Altar of Dementia
- [C055](#c055): Out of the Tombs + Skullclamp + Pitiless Plunderer + Arcbound Ravager
- [C073](#c073): Out of the Tombs + Skullclamp + Pitiless Plunderer + Carrion Feeder
- [C099](#c099): Out of the Tombs + Skullclamp + Pitiless Plunderer + Umbral Collar Zealot
- [C100](#c100): Out of the Tombs + Skullclamp + Warren Soultrader + Sephiroth, Fabled SOLDIER
- [C101](#c101): Out of the Tombs + Skullclamp + Warren Soultrader + Zulaport Cutthroat
- [C104](#c104): Out of the Tombs + Skullclamp + Pitiless Plunderer + Blasting Station + Stitcher's Supplier

===endpanel
===endaccordion

===accordion
===panel: Phyrexian Altar

- [C001](#c001): Gravecrawler + Phyrexian Altar
- [C038](#c038): Tortured Existence + Phyrexian Altar + Imotekh the Stormlord
- [C044](#c044): Out of the Tombs + Skullclamp + Phyrexian Altar
- [C045](#c045): Pitiless Plunderer + Phyrexian Altar + Stridehangar Automaton
- [C046](#c046): The Ooze + Stridehangar Automaton + Phyrexian Altar
- [C097](#c097): Scrap Trawler + Myr Retriever + Phyrexian Altar + Semblance Anvil
- [C098](#c098): Ultron the Annihilator + Nim Deathmantle + Phyrexian Altar + Pitiless Plunderer
- [C108](#c108): Animation Module + Phyrexian Altar + Super Shredder
- [C119](#c119): The Ooze + Animation Module + Pitiless Plunderer + Phyrexian Altar
- [C120](#c120): Marionette Apprentice + Nim Deathmantle + Phyrexian Altar + Pitiless Plunderer
- [T003](#t003): Tarrian's Soulcleaver + Animation Module + Phyrexian Altar

===endpanel
===endaccordion

===accordion
===panel: Pitiless Plunderer

- [C004](#c004): Gravecrawler + Pitiless Plunderer + Altar of Dementia
- [C006](#c006): Pitiless Plunderer + Altar of Dementia + Stridehangar Automaton
- [C007](#c007): Pitiless Plunderer + Stridehangar Automaton + Arcbound Ravager
- [C009](#c009): Gravecrawler + Pitiless Plunderer + Ashnod's Altar
- [C016](#c016): Pitiless Plunderer + Ashnod's Altar + Stridehangar Automaton
- [C018](#c018): Gravecrawler + Pitiless Plunderer + Blasting Station
- [C020](#c020): Pitiless Plunderer + Blasting Station + Stridehangar Automaton
- [C021](#c021): Gravecrawler + Pitiless Plunderer + Carrion Feeder
- [C023](#c023): Pitiless Plunderer + Stridehangar Automaton + Carrion Feeder
- [C032](#c032): Gravecrawler + Pitiless Plunderer + Umbral Collar Zealot
- [C036](#c036): Pitiless Plunderer + Stridehangar Automaton + Grinding Station
- [C041](#c041): Pitiless Plunderer + Stridehangar Automaton + Krark-Clan Ironworks
- [C045](#c045): Pitiless Plunderer + Phyrexian Altar + Stridehangar Automaton
- [C047](#c047): Pitiless Plunderer + Umbral Collar Zealot + Stridehangar Automaton
- [C050](#c050): Metalwork Colossus + Warren Soultrader + Pitiless Plunderer + Aetherflux Reservoir
- [C052](#c052): Tortured Existence + Pitiless Plunderer + Imotekh the Stormlord + Altar of Dementia
- [C053](#c053): Out of the Tombs + Skullclamp + Pitiless Plunderer + Altar of Dementia
- [C055](#c055): Out of the Tombs + Skullclamp + Pitiless Plunderer + Arcbound Ravager
- [C070](#c070): Tortured Existence + Pitiless Plunderer + Imotekh the Stormlord + Blasting Station
- [C072](#c072): Tortured Existence + Pitiless Plunderer + Imotekh the Stormlord + Carrion Feeder
- [C073](#c073): Out of the Tombs + Skullclamp + Pitiless Plunderer + Carrion Feeder
- [C098](#c098): Ultron the Annihilator + Nim Deathmantle + Phyrexian Altar + Pitiless Plunderer
- [C099](#c099): Out of the Tombs + Skullclamp + Pitiless Plunderer + Umbral Collar Zealot
- [C104](#c104): Out of the Tombs + Skullclamp + Pitiless Plunderer + Blasting Station + Stitcher's Supplier
- [C106](#c106): Animation Module + Pitiless Plunderer + Carrion Feeder
- [C109](#c109): Animation Module + Pitiless Plunderer + Arcbound Ravager
- [C115](#c115): Super Shredder + Animation Module + Pitiless Plunderer + Altar of Dementia
- [C116](#c116): Super Shredder + Animation Module + Pitiless Plunderer + Blasting Station
- [C117](#c117): Super Shredder + Animation Module + Pitiless Plunderer + Grinding Station
- [C118](#c118): Super Shredder + Animation Module + Pitiless Plunderer + Umbral Collar Zealot
- [C119](#c119): The Ooze + Animation Module + Pitiless Plunderer + Phyrexian Altar
- [C120](#c120): Marionette Apprentice + Nim Deathmantle + Phyrexian Altar + Pitiless Plunderer
- [T004](#t004): Tarrian's Soulcleaver + Animation Module + Pitiless Plunderer + Altar of Dementia
- [T005](#t005): Tarrian's Soulcleaver + Animation Module + Pitiless Plunderer + Blasting Station
- [T006](#t006): Tarrian's Soulcleaver + Animation Module + Pitiless Plunderer + Grinding Station
- [T007](#t007): Tarrian's Soulcleaver + Animation Module + Pitiless Plunderer + Umbral Collar Zealot
- [T010](#t010): Tarrian's Soulcleaver + Walking Ballista + Gravecrawler + Pitiless Plunderer + Warren Soultrader
- [T012](#t012): Tarrian's Soulcleaver + Walking Ballista + Pitiless Plunderer + Stridehangar Automaton
- [T013](#t013): Tarrian's Soulcleaver + Walking Ballista + Animation Module + Pitiless Plunderer
- [T014](#t014): Tarrian's Soulcleaver + Walking Ballista + Tortured Existence + Imotekh the Stormlord + Pitiless Plunderer

===endpanel
===endaccordion

===accordion
===panel: Retrofitter Foundry

- [C008](#c008): Dross Scorpion + Retrofitter Foundry + Ashnod's Altar
- [C025](#c025): Retrofitter Foundry + Clock of Omens + Stridehangar Automaton
- [C028](#c028): Dross Scorpion + Retrofitter Foundry + Krark-Clan Ironworks
- [C029](#c029): Retrofitter Foundry + Dross Scorpion + Stridehangar Automaton

===endpanel
===endaccordion

===accordion
===panel: Scrap Trawler

- [C057](#c057): Scrap Trawler + Myr Retriever + Ashnod's Altar + Cloud Key
- [C058](#c058): Scrap Trawler + Myr Retriever + Ashnod's Altar + Foundry Inspector
- [C061](#c061): Glaring Fleshraker + Ashnod's Altar + Myr Retriever + Scrap Trawler
- [C066](#c066): Imotekh the Stormlord + Scrap Trawler + Myr Retriever + Ashnod's Altar
- [C068](#c068): Scrap Trawler + Myr Retriever + Ashnod's Altar + Semblance Anvil
- [C077](#c077): Scrap Trawler + Myr Retriever + Krark-Clan Ironworks + Cloud Key
- [C080](#c080): Scrap Trawler + Myr Retriever + Krark-Clan Ironworks + Foundry Inspector
- [C085](#c085): Glaring Fleshraker + Myr Retriever + Scrap Trawler + Krark-Clan Ironworks
- [C091](#c091): Imotekh the Stormlord + Scrap Trawler + Myr Retriever + Krark-Clan Ironworks
- [C094](#c094): Scrap Trawler + Myr Retriever + Krark-Clan Ironworks + Semblance Anvil
- [C097](#c097): Scrap Trawler + Myr Retriever + Phyrexian Altar + Semblance Anvil
- [C105](#c105): Scrap Trawler + Myr Retriever + Krark-Clan Ironworks + Sol Ring + Junk Diver

===endpanel
===endaccordion

===accordion
===panel: Semblance Anvil

- [C043](#c043): Sensei's Divining Top + Mystic Forge + Semblance Anvil
- [C068](#c068): Scrap Trawler + Myr Retriever + Ashnod's Altar + Semblance Anvil
- [C094](#c094): Scrap Trawler + Myr Retriever + Krark-Clan Ironworks + Semblance Anvil
- [C097](#c097): Scrap Trawler + Myr Retriever + Phyrexian Altar + Semblance Anvil

===endpanel
===endaccordion

===accordion
===panel: Sensei's Divining Top

- [C002](#c002): Sensei's Divining Top + Aetherflux Reservoir + Bolas's Citadel
- [C027](#c027): Sensei's Divining Top + Mystic Forge + Cloud Key
- [C030](#c030): Sensei's Divining Top + Foundry Inspector + Mystic Forge
- [C031](#c031): Sensei's Divining Top + Glaring Fleshraker + Mystic Forge
- [C043](#c043): Sensei's Divining Top + Mystic Forge + Semblance Anvil

===endpanel
===endaccordion

===accordion
===panel: Sephiroth, Fabled SOLDIER

- [C033](#c033): Warren Soultrader + Gravecrawler + Sephiroth, Fabled SOLDIER
- [C048](#c048): Warren Soultrader + Stridehangar Automaton + Sephiroth, Fabled SOLDIER
- [C100](#c100): Out of the Tombs + Skullclamp + Warren Soultrader + Sephiroth, Fabled SOLDIER
- [T009](#t009): Tarrian's Soulcleaver + Animation Module + Warren Soultrader + Sephiroth, Fabled SOLDIER

===endpanel
===endaccordion

===accordion
===panel: Skullclamp

- [C015](#c015): Out of the Tombs + Skullclamp + Ashnod's Altar
- [C040](#c040): Out of the Tombs + Skullclamp + Krark-Clan Ironworks
- [C044](#c044): Out of the Tombs + Skullclamp + Phyrexian Altar
- [C053](#c053): Out of the Tombs + Skullclamp + Pitiless Plunderer + Altar of Dementia
- [C055](#c055): Out of the Tombs + Skullclamp + Pitiless Plunderer + Arcbound Ravager
- [C073](#c073): Out of the Tombs + Skullclamp + Pitiless Plunderer + Carrion Feeder
- [C099](#c099): Out of the Tombs + Skullclamp + Pitiless Plunderer + Umbral Collar Zealot
- [C100](#c100): Out of the Tombs + Skullclamp + Warren Soultrader + Sephiroth, Fabled SOLDIER
- [C101](#c101): Out of the Tombs + Skullclamp + Warren Soultrader + Zulaport Cutthroat
- [C104](#c104): Out of the Tombs + Skullclamp + Pitiless Plunderer + Blasting Station + Stitcher's Supplier

===endpanel
===endaccordion

===accordion
===panel: Sol Ring

- [C105](#c105): Scrap Trawler + Myr Retriever + Krark-Clan Ironworks + Sol Ring + Junk Diver

===endpanel
===endaccordion

===accordion
===panel: Stitcher's Supplier

- [C104](#c104): Out of the Tombs + Skullclamp + Pitiless Plunderer + Blasting Station + Stitcher's Supplier

===endpanel
===endaccordion

===accordion
===panel: Stridehangar Automaton

- [C006](#c006): Pitiless Plunderer + Altar of Dementia + Stridehangar Automaton
- [C007](#c007): Pitiless Plunderer + Stridehangar Automaton + Arcbound Ravager
- [C016](#c016): Pitiless Plunderer + Ashnod's Altar + Stridehangar Automaton
- [C017](#c017): The Ooze + Stridehangar Automaton + Ashnod's Altar
- [C020](#c020): Pitiless Plunderer + Blasting Station + Stridehangar Automaton
- [C023](#c023): Pitiless Plunderer + Stridehangar Automaton + Carrion Feeder
- [C025](#c025): Retrofitter Foundry + Clock of Omens + Stridehangar Automaton
- [C026](#c026): The Ooze + Clock of Omens + Stridehangar Automaton
- [C029](#c029): Retrofitter Foundry + Dross Scorpion + Stridehangar Automaton
- [C036](#c036): Pitiless Plunderer + Stridehangar Automaton + Grinding Station
- [C041](#c041): Pitiless Plunderer + Stridehangar Automaton + Krark-Clan Ironworks
- [C042](#c042): The Ooze + Stridehangar Automaton + Krark-Clan Ironworks
- [C045](#c045): Pitiless Plunderer + Phyrexian Altar + Stridehangar Automaton
- [C046](#c046): The Ooze + Stridehangar Automaton + Phyrexian Altar
- [C047](#c047): Pitiless Plunderer + Umbral Collar Zealot + Stridehangar Automaton
- [C048](#c048): Warren Soultrader + Stridehangar Automaton + Sephiroth, Fabled SOLDIER
- [C049](#c049): Warren Soultrader + Zulaport Cutthroat + Stridehangar Automaton
- [C051](#c051): Metalwork Colossus + Warren Soultrader + Aetherflux Reservoir + Stridehangar Automaton
- [C075](#c075): The Ooze + Clock of Omens + Stridehangar Automaton + Grinding Station
- [C122](#c122): Marionette Apprentice + Warren Soultrader + Stridehangar Automaton
- [T012](#t012): Tarrian's Soulcleaver + Walking Ballista + Pitiless Plunderer + Stridehangar Automaton

===endpanel
===endaccordion

===accordion
===panel: Super Shredder

- [C107](#c107): Animation Module + Ashnod's Altar + Super Shredder
- [C108](#c108): Animation Module + Phyrexian Altar + Super Shredder
- [C110](#c110): Animation Module + Krark-Clan Ironworks + Super Shredder
- [C115](#c115): Super Shredder + Animation Module + Pitiless Plunderer + Altar of Dementia
- [C116](#c116): Super Shredder + Animation Module + Pitiless Plunderer + Blasting Station
- [C117](#c117): Super Shredder + Animation Module + Pitiless Plunderer + Grinding Station
- [C118](#c118): Super Shredder + Animation Module + Pitiless Plunderer + Umbral Collar Zealot

===endpanel
===endaccordion

===accordion
===panel: Tarrian's Soulcleaver

- [T001](#t001): Tarrian's Soulcleaver + Animation Module + Ashnod's Altar
- [T002](#t002): Tarrian's Soulcleaver + Animation Module + Krark-Clan Ironworks
- [T003](#t003): Tarrian's Soulcleaver + Animation Module + Phyrexian Altar
- [T004](#t004): Tarrian's Soulcleaver + Animation Module + Pitiless Plunderer + Altar of Dementia
- [T005](#t005): Tarrian's Soulcleaver + Animation Module + Pitiless Plunderer + Blasting Station
- [T006](#t006): Tarrian's Soulcleaver + Animation Module + Pitiless Plunderer + Grinding Station
- [T007](#t007): Tarrian's Soulcleaver + Animation Module + Pitiless Plunderer + Umbral Collar Zealot
- [T008](#t008): Tarrian's Soulcleaver + Animation Module + Warren Soultrader + Zulaport Cutthroat
- [T009](#t009): Tarrian's Soulcleaver + Animation Module + Warren Soultrader + Sephiroth, Fabled SOLDIER
- [T010](#t010): Tarrian's Soulcleaver + Walking Ballista + Gravecrawler + Pitiless Plunderer + Warren Soultrader
- [T011](#t011): Tarrian's Soulcleaver + Walking Ballista + Gravecrawler + The Ghoul, Gunslinger
- [T012](#t012): Tarrian's Soulcleaver + Walking Ballista + Pitiless Plunderer + Stridehangar Automaton
- [T013](#t013): Tarrian's Soulcleaver + Walking Ballista + Animation Module + Pitiless Plunderer
- [T014](#t014): Tarrian's Soulcleaver + Walking Ballista + Tortured Existence + Imotekh the Stormlord + Pitiless Plunderer

===endpanel
===endaccordion

===accordion
===panel: The Ghoul, Gunslinger

- [C005](#c005): The Ghoul, Gunslinger + Gravecrawler + Altar of Dementia
- [C010](#c010): The Ghoul, Gunslinger + Gravecrawler + Ashnod's Altar
- [C019](#c019): The Ghoul, Gunslinger + Gravecrawler + Blasting Station
- [C022](#c022): The Ghoul, Gunslinger + Gravecrawler + Carrion Feeder
- [C034](#c034): The Ghoul, Gunslinger + Gravecrawler + Umbral Collar Zealot
- [T011](#t011): Tarrian's Soulcleaver + Walking Ballista + Gravecrawler + The Ghoul, Gunslinger

===endpanel
===endaccordion

===accordion
===panel: The Ooze

- [C017](#c017): The Ooze + Stridehangar Automaton + Ashnod's Altar
- [C026](#c026): The Ooze + Clock of Omens + Stridehangar Automaton
- [C042](#c042): The Ooze + Stridehangar Automaton + Krark-Clan Ironworks
- [C046](#c046): The Ooze + Stridehangar Automaton + Phyrexian Altar
- [C075](#c075): The Ooze + Clock of Omens + Stridehangar Automaton + Grinding Station
- [C113](#c113): The Ooze + Animation Module + Ashnod's Altar
- [C114](#c114): The Ooze + Animation Module + Krark-Clan Ironworks
- [C119](#c119): The Ooze + Animation Module + Pitiless Plunderer + Phyrexian Altar

===endpanel
===endaccordion

===accordion
===panel: Tortured Existence

- [C024](#c024): Imotekh the Stormlord + Clock of Omens + Tortured Existence
- [C038](#c038): Tortured Existence + Phyrexian Altar + Imotekh the Stormlord
- [C052](#c052): Tortured Existence + Pitiless Plunderer + Imotekh the Stormlord + Altar of Dementia
- [C070](#c070): Tortured Existence + Pitiless Plunderer + Imotekh the Stormlord + Blasting Station
- [C072](#c072): Tortured Existence + Pitiless Plunderer + Imotekh the Stormlord + Carrion Feeder
- [T014](#t014): Tarrian's Soulcleaver + Walking Ballista + Tortured Existence + Imotekh the Stormlord + Pitiless Plunderer

===endpanel
===endaccordion

===accordion
===panel: Ultron the Annihilator

- [C014](#c014): Ultron the Annihilator + Nim Deathmantle + Ashnod's Altar
- [C039](#c039): Ultron the Annihilator + Nim Deathmantle + Krark-Clan Ironworks
- [C098](#c098): Ultron the Annihilator + Nim Deathmantle + Phyrexian Altar + Pitiless Plunderer

===endpanel
===endaccordion

===accordion
===panel: Umbral Collar Zealot

- [C032](#c032): Gravecrawler + Pitiless Plunderer + Umbral Collar Zealot
- [C034](#c034): The Ghoul, Gunslinger + Gravecrawler + Umbral Collar Zealot
- [C047](#c047): Pitiless Plunderer + Umbral Collar Zealot + Stridehangar Automaton
- [C099](#c099): Out of the Tombs + Skullclamp + Pitiless Plunderer + Umbral Collar Zealot
- [C118](#c118): Super Shredder + Animation Module + Pitiless Plunderer + Umbral Collar Zealot
- [T007](#t007): Tarrian's Soulcleaver + Animation Module + Pitiless Plunderer + Umbral Collar Zealot

===endpanel
===endaccordion

===accordion
===panel: Walking Ballista

- [T010](#t010): Tarrian's Soulcleaver + Walking Ballista + Gravecrawler + Pitiless Plunderer + Warren Soultrader
- [T011](#t011): Tarrian's Soulcleaver + Walking Ballista + Gravecrawler + The Ghoul, Gunslinger
- [T012](#t012): Tarrian's Soulcleaver + Walking Ballista + Pitiless Plunderer + Stridehangar Automaton
- [T013](#t013): Tarrian's Soulcleaver + Walking Ballista + Animation Module + Pitiless Plunderer
- [T014](#t014): Tarrian's Soulcleaver + Walking Ballista + Tortured Existence + Imotekh the Stormlord + Pitiless Plunderer

===endpanel
===endaccordion

===accordion
===panel: Warren Soultrader

- [C003](#c003): Warren Soultrader + Aetherflux Reservoir + Gravecrawler
- [C033](#c033): Warren Soultrader + Gravecrawler + Sephiroth, Fabled SOLDIER
- [C035](#c035): Warren Soultrader + Gravecrawler + Zulaport Cutthroat
- [C048](#c048): Warren Soultrader + Stridehangar Automaton + Sephiroth, Fabled SOLDIER
- [C049](#c049): Warren Soultrader + Zulaport Cutthroat + Stridehangar Automaton
- [C050](#c050): Metalwork Colossus + Warren Soultrader + Pitiless Plunderer + Aetherflux Reservoir
- [C051](#c051): Metalwork Colossus + Warren Soultrader + Aetherflux Reservoir + Stridehangar Automaton
- [C100](#c100): Out of the Tombs + Skullclamp + Warren Soultrader + Sephiroth, Fabled SOLDIER
- [C101](#c101): Out of the Tombs + Skullclamp + Warren Soultrader + Zulaport Cutthroat
- [C121](#c121): Marionette Apprentice + Warren Soultrader + Gravecrawler
- [C122](#c122): Marionette Apprentice + Warren Soultrader + Stridehangar Automaton
- [T008](#t008): Tarrian's Soulcleaver + Animation Module + Warren Soultrader + Zulaport Cutthroat
- [T009](#t009): Tarrian's Soulcleaver + Animation Module + Warren Soultrader + Sephiroth, Fabled SOLDIER
- [T010](#t010): Tarrian's Soulcleaver + Walking Ballista + Gravecrawler + Pitiless Plunderer + Warren Soultrader

===endpanel
===endaccordion

===accordion
===panel: Workshop Assistant

- [C060](#c060): Glaring Fleshraker + Ashnod's Altar + Junk Diver + Workshop Assistant
- [C062](#c062): Glaring Fleshraker + Ashnod's Altar + Myr Retriever + Workshop Assistant
- [C065](#c065): Imotekh the Stormlord + Junk Diver + Workshop Assistant + Ashnod's Altar
- [C067](#c067): Imotekh the Stormlord + Myr Retriever + Workshop Assistant + Ashnod's Altar
- [C084](#c084): Glaring Fleshraker + Junk Diver + Workshop Assistant + Krark-Clan Ironworks
- [C086](#c086): Glaring Fleshraker + Myr Retriever + Workshop Assistant + Krark-Clan Ironworks
- [C090](#c090): Imotekh the Stormlord + Junk Diver + Workshop Assistant + Krark-Clan Ironworks
- [C092](#c092): Imotekh the Stormlord + Myr Retriever + Workshop Assistant + Krark-Clan Ironworks

===endpanel
===endaccordion

===accordion
===panel: Zulaport Cutthroat

- [C035](#c035): Warren Soultrader + Gravecrawler + Zulaport Cutthroat
- [C049](#c049): Warren Soultrader + Zulaport Cutthroat + Stridehangar Automaton
- [C101](#c101): Out of the Tombs + Skullclamp + Warren Soultrader + Zulaport Cutthroat
- [T008](#t008): Tarrian's Soulcleaver + Animation Module + Warren Soultrader + Zulaport Cutthroat

===endpanel
===endaccordion

===endpanel
===endaccordion

===accordion
===panel: Archive — Missing Cards

These historical configurations require at least one card absent from the supplied decklist. IDs and original instructions are preserved.

**Archived C076 — missing: spine of ish sah**

<a id="c076"></a>
===accordion
===panel: C076: Spine of Ish Sah + Imotekh the Stormlord + Krark-Clan Ironworks + Cloud Key

[[symbol:b]]

Cards Required:
- [[Spine of Ish Sah]]
- [[Imotekh the Stormlord]]
- [[Krark-Clan Ironworks]]
- [[Cloud Key]]

Prerequisites:
- All permanents are on the battlefield.
- Cloud Key has "Artifact" chosen.
- Enough resources are available to begin the loop.

Steps:
1. Sacrifice Spine to KCI for [[symbol:2]]; resolve its return-to-hand trigger.
2. Imotekh creates two Necrons because Spine left the graveyard. Sacrifice both to KCI for [[symbol:4]], making [[symbol:6]] total.
3. Cast Spine for [[symbol:6]] with Key/Inspector, [[symbol:5]] with Anvil, or [[symbol:7]] with Fleshraker. The Fleshraker version needs a prior [[symbol:1]] buffer; its Spawn then restores that buffer after the cast.
4. Resolve Spine's destruction and repeat. To keep looping after opposing targets run out, target your own Spine with its ETB trigger and sacrifice it to KCI in response.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Spine/Imotekh/KCI/reducer on battlefield; Key names Artifact. Generate six, recast Spine for six: neutral. Use self-target/sacrifice ordering to continue after opposing targets run out.

===endpanel
===endaccordion

**Archived C078 — missing: spine of ish sah**

<a id="c078"></a>
===accordion
===panel: C078: Spine of Ish Sah + Sculpting Steel + Krark-Clan Ironworks + Cloud Key

[[symbol:c]]

Cards Required:
- [[Spine of Ish Sah]]
- [[Sculpting Steel]]
- [[Krark-Clan Ironworks]]
- [[Cloud Key]]

Prerequisites:
- Spine of Ish Sah, Krark-Clan Ironworks, and the reducer are on the battlefield.
- Sculpting Steel is in hand.
- Cloud Key has "Artifact" chosen.

Steps:
1. Cast Sculpting Steel and have it enter copying the real Spine; its ETB destruction ability triggers.
2. Sacrifice Steel-as-Spine to KCI for [[symbol:2]]. Its copied self-return trigger returns the Steel card from graveyard to hand.
3. Recast Steel for [[symbol:2]] with Key/Inspector or [[symbol:1]] with Anvil. With Fleshraker, pay [[symbol:3]] and recover the extra [[symbol:1]] from the cast-generated Spawn's own ability.
4. Repeat. Target Steel-as-Spine with its own destruction trigger and sacrifice it in response when needed to preserve the engine.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Real Spine/KCI/reducer on battlefield, Steel in hand; [[symbol:2]] seed. Steel costs two, KCI returns two, neutral. Key names Artifact.

===endpanel
===endaccordion

**Archived C079 — missing: spine of ish sah**

<a id="c079"></a>
===accordion
===panel: C079: Spine of Ish Sah + Imotekh the Stormlord + Krark-Clan Ironworks + Foundry Inspector

[[symbol:b]]

Cards Required:
- [[Spine of Ish Sah]]
- [[Imotekh the Stormlord]]
- [[Krark-Clan Ironworks]]
- [[Foundry Inspector]]

Prerequisites:
- All permanents are on the battlefield.
- No additional prerequisites.
- Enough resources are available to begin the loop.

Steps:
1. Sacrifice Spine to KCI for [[symbol:2]]; resolve its return-to-hand trigger.
2. Imotekh creates two Necrons because Spine left the graveyard. Sacrifice both to KCI for [[symbol:4]], making [[symbol:6]] total.
3. Cast Spine for [[symbol:6]] with Key/Inspector, [[symbol:5]] with Anvil, or [[symbol:7]] with Fleshraker. The Fleshraker version needs a prior [[symbol:1]] buffer; its Spawn then restores that buffer after the cast.
4. Resolve Spine's destruction and repeat. To keep looping after opposing targets run out, target your own Spine with its ETB trigger and sacrifice it to KCI in response.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Spine/Imotekh/KCI/reducer on battlefield; Key names Artifact. Generate six, recast Spine for six: neutral. Use self-target/sacrifice ordering to continue after opposing targets run out.

===endpanel
===endaccordion

**Archived C081 — missing: spine of ish sah**

<a id="c081"></a>
===accordion
===panel: C081: Spine of Ish Sah + Sculpting Steel + Krark-Clan Ironworks + Foundry Inspector

[[symbol:c]]

Cards Required:
- [[Spine of Ish Sah]]
- [[Sculpting Steel]]
- [[Krark-Clan Ironworks]]
- [[Foundry Inspector]]

Prerequisites:
- Spine of Ish Sah, Krark-Clan Ironworks, and the reducer are on the battlefield.
- Sculpting Steel is in hand.
- No additional prerequisites.

Steps:
1. Cast Sculpting Steel and have it enter copying the real Spine; its ETB destruction ability triggers.
2. Sacrifice Steel-as-Spine to KCI for [[symbol:2]]. Its copied self-return trigger returns the Steel card from graveyard to hand.
3. Recast Steel for [[symbol:2]] with Key/Inspector or [[symbol:1]] with Anvil. With Fleshraker, pay [[symbol:3]] and recover the extra [[symbol:1]] from the cast-generated Spawn's own ability.
4. Repeat. Target Steel-as-Spine with its own destruction trigger and sacrifice it in response when needed to preserve the engine.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Real Spine/KCI/reducer on battlefield, Steel in hand; [[symbol:2]] seed. Steel costs two, KCI returns two, neutral. Key names Artifact.

===endpanel
===endaccordion

**Archived C082 — missing: spine of ish sah**

<a id="c082"></a>
===accordion
===panel: C082: Spine of Ish Sah + Imotekh the Stormlord + Krark-Clan Ironworks + Glaring Fleshraker

[[symbol:b]]

Cards Required:
- [[Spine of Ish Sah]]
- [[Imotekh the Stormlord]]
- [[Krark-Clan Ironworks]]
- [[Glaring Fleshraker]]

Prerequisites:
- All permanents are on the battlefield.
- Enough resources are available to begin the loop.
- One mana is floating before the seven-mana Spine cast; its cast-generated Spawn restores that buffer afterward.

Steps:
1. Sacrifice Spine to KCI for [[symbol:2]]; resolve its return-to-hand trigger.
2. Imotekh creates two Necrons because Spine left the graveyard. Sacrifice both to KCI for [[symbol:4]], making [[symbol:6]] total.
3. Cast Spine for [[symbol:6]] with Key/Inspector, [[symbol:5]] with Anvil, or [[symbol:7]] with Fleshraker. The Fleshraker version needs a prior [[symbol:1]] buffer; its Spawn then restores that buffer after the cast.
4. Resolve Spine's destruction and repeat. To keep looping after opposing targets run out, target your own Spine with its ETB trigger and sacrifice it to KCI in response.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Direct lethal damage or life loss through the named payoff.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- All named cards on battlefield and one floating seed mana. Six from sacrifices cannot pay seven by itself; the prior one permits casting Spine, and Spawn restores the seed afterward. Direct Fleshraker lethal damage.

===endpanel
===endaccordion

**Archived C087 — missing: spine of ish sah**

<a id="c087"></a>
===accordion
===panel: C087: Spine of Ish Sah + Sculpting Steel + Krark-Clan Ironworks + Glaring Fleshraker

[[symbol:c]]

Cards Required:
- [[Spine of Ish Sah]]
- [[Sculpting Steel]]
- [[Krark-Clan Ironworks]]
- [[Glaring Fleshraker]]

Prerequisites:
- Spine of Ish Sah, Krark-Clan Ironworks, and Glaring Fleshraker are on the battlefield.
- Sculpting Steel is in hand.
- Enough resources are available to begin the loop.

Steps:
1. Cast Sculpting Steel and have it enter copying the real Spine; its ETB destruction ability triggers.
2. Sacrifice Steel-as-Spine to KCI for [[symbol:2]]. Its copied self-return trigger returns the Steel card from graveyard to hand.
3. Recast Steel for [[symbol:2]] with Key/Inspector or [[symbol:1]] with Anvil. With Fleshraker, pay [[symbol:3]] and recover the extra [[symbol:1]] from the cast-generated Spawn's own ability.
4. Repeat. Target Steel-as-Spine with its own destruction trigger and sacrifice it in response when needed to preserve the engine.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Direct lethal damage or life loss through the named payoff.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Real Spine/KCI/Fleshraker on battlefield, Steel in hand; [[symbol:3]] seed. KCI two plus intrinsic Spawn one pay next three. Direct lethal Fleshraker damage.

===endpanel
===endaccordion

**Archived C093 — missing: spine of ish sah**

<a id="c093"></a>
===accordion
===panel: C093: Spine of Ish Sah + Imotekh the Stormlord + Krark-Clan Ironworks + Semblance Anvil

[[symbol:b]]

Cards Required:
- [[Spine of Ish Sah]]
- [[Imotekh the Stormlord]]
- [[Krark-Clan Ironworks]]
- [[Semblance Anvil]]

Prerequisites:
- All permanents are on the battlefield.
- Semblance Anvil has an artifact card exiled with it.
- Enough resources are available to begin the loop.

Steps:
1. Sacrifice Spine to KCI for [[symbol:2]]; resolve its return-to-hand trigger.
2. Imotekh creates two Necrons because Spine left the graveyard. Sacrifice both to KCI for [[symbol:4]], making [[symbol:6]] total.
3. Cast Spine for [[symbol:6]] with Key/Inspector, [[symbol:5]] with Anvil, or [[symbol:7]] with Fleshraker. The Fleshraker version needs a prior [[symbol:1]] buffer; its Spawn then restores that buffer after the cast.
4. Resolve Spine's destruction and repeat. To keep looping after opposing targets run out, target your own Spine with its ETB trigger and sacrifice it to KCI in response.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Anvil imprints artifact. Six generated minus five Spine cost = net one colorless; destruction alone has finite targets, but loop can continue as described in F17.

===endpanel
===endaccordion

**Archived C096 — missing: spine of ish sah**

<a id="c096"></a>
===accordion
===panel: C096: Spine of Ish Sah + Sculpting Steel + Krark-Clan Ironworks + Semblance Anvil

[[symbol:c]]

Cards Required:
- [[Spine of Ish Sah]]
- [[Sculpting Steel]]
- [[Krark-Clan Ironworks]]
- [[Semblance Anvil]]

Prerequisites:
- Spine of Ish Sah, Krark-Clan Ironworks, and the reducer are on the battlefield.
- Sculpting Steel is in hand.
- Semblance Anvil has an artifact card exiled with it.

Steps:
1. Cast Sculpting Steel and have it enter copying the real Spine; its ETB destruction ability triggers.
2. Sacrifice Steel-as-Spine to KCI for [[symbol:2]]. Its copied self-return trigger returns the Steel card from graveyard to hand.
3. Recast Steel for [[symbol:2]] with Key/Inspector or [[symbol:1]] with Anvil. With Fleshraker, pay [[symbol:3]] and recover the extra [[symbol:1]] from the cast-generated Spawn's own ability.
4. Repeat. Target Steel-as-Spine with its own destruction trigger and sacrifice it in response when needed to preserve the engine.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Arbitrarily high spell count from repeated casts.
- Artifact entries/deaths or graveyard events as specified; Ultron adds lethal drain when the repeating artifact-to-graveyard events occur while it is present.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Real Spine/KCI/Anvil on battlefield with artifact imprint, Steel in hand; [[symbol:1]] seed. Spend one and recover two, net one colorless.

===endpanel
===endaccordion

**Archived C111 — missing: yawgmoth, thran physician**

<a id="c111"></a>
===accordion
===panel: C111: Yawgmoth, Thran Physician + Out of the Tombs + Zulaport Cutthroat

[[symbol:b]]

Cards Required:
- [[Yawgmoth, Thran Physician]]
- [[Out of the Tombs]]
- [[Zulaport Cutthroat]]

Prerequisites:
- All three named permanents on the battlefield.
- Your library is empty.
- You control **another nontoken creature** that can be sacrificed and returned from the graveyard.
- Your life total is at least 2.
- No effect prevents creature cards from entering your graveyard or returning to the battlefield.

Steps:
1. Pay 1 life and sacrifice the extra nontoken body to Yawgmoth, choosing no counter target.
2. Resolve Zulaport or Sephiroth's death trigger first, gaining back the life and draining opponents.
3. Resolve Yawgmoth. Out of the Tombs replaces the empty-library draw by returning the sacrificed body.
4. Repeat. The real Sephiroth transforms on its fourth death-trigger resolution; its emblem continues the drain.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Direct lethal damage or life loss through the named payoff.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Empty library, extra nontoken body, life >= 2; Yawgmoth chooses no counter target. Resolve drain first, then replace draw with returning body. Direct lethal drain; no actual draws.

===endpanel
===endaccordion

**Archived C112 — missing: yawgmoth, thran physician**

<a id="c112"></a>
===accordion
===panel: C112: Yawgmoth, Thran Physician + Out of the Tombs + Sephiroth, Fabled SOLDIER

[[symbol:b]]

Cards Required:
- [[Yawgmoth, Thran Physician]]
- [[Out of the Tombs]]
- [[Sephiroth, Fabled SOLDIER]]

Prerequisites:
- All three named permanents on the battlefield, with Sephiroth on its front face initially (or an existing Sephiroth emblem that provides the death trigger).
- Your library is empty.
- You control **another nontoken creature** that can be sacrificed and returned from the graveyard.
- Your life total is at least 2.
- No effect prevents creature cards from entering your graveyard or returning to the battlefield.

Steps:
1. Pay 1 life and sacrifice the extra nontoken body to Yawgmoth, choosing no counter target.
2. Resolve Zulaport or Sephiroth's death trigger first, gaining back the life and draining opponents.
3. Resolve Yawgmoth. Out of the Tombs replaces the empty-library draw by returning the sacrificed body.
4. Repeat. The real Sephiroth transforms on its fourth death-trigger resolution; its emblem continues the drain.

Results:
- Arbitrarily many creature deaths, sacrifice events and creature entries, under the stated prerequisites.
- Direct lethal damage or life loss through the named payoff.
- Mana, life and token surplus: see the accounting note below; repeated production does not always accumulate those resources.

Classification: Unbounded resource loop.

Audit Notes:
- Empty library, extra nontoken body, life >= 2; Yawgmoth chooses no counter target. Resolve drain first, then replace draw with returning body. Direct lethal drain; no actual draws.

===endpanel
===endaccordion

===endpanel
===endaccordion
