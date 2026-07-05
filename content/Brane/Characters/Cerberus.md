---
type: character
aliases: [Cerberus, CRBRS, SI Cerberus]
scope: m2026
summary: "An unregulated UESC black-operations AI co-commanding with Captain Orion on Tau Ceti IV, holding root authority over tethered combat units and deploying code implants against rival factions."
era: "2787 → unknown"
status: extant
games: ["[[Marathon 2026]]"]
affiliation: "UESC"
canon-status: canon
confidence: strong
tags: [character, ai, uesc, m2026, cerberus, key-lore]
source-count: 14
mentioned-by: 13
appears-in: [codex]
last-updated: 2026-07-05
---

# Cerberus

> A previously unidentified UESC black-operations AI — listed as Strategic Intelligence (SI) on Captain Orion's Cryo Archive operations — issuing hostile ground-ops orders on Tau Ceti IV, keyed to the Anomaly and the contagion, and deploying code implants (CHORDODES / TRIOXYS) against rival factions.

## What the source establishes — canon

**Identity and classification.** Cerberus is named in MIDA's classified target file on Captain Orion as **"an unregulated and publicly undisclosed military AI… capable of mass violence,"** suspected to have been deployed by Orion[^1]. Across UESC tactical records recovered from the Cryo Archive, Cerberus appears under the personnel designator **"SI: Cerberus"** — Strategic Intelligence — co-listed alongside Orion (OP COMM) on every logged UESC operation in the TCIV\_M.CA zone[^8][^9][^10][^11][^12].

**Command authority over tethered units.** A reconstructed code fragment recovered from the Sekiguchi contracts shows Cerberus asserting **root access and direct control over all tethered UESC combat units** deployed to Tau Ceti IV — standard (`tciv_cmbt_stnd`), elite (`tciv_cmbt_elite`), standard vehicles (`tciv_vhcl_stnd`), and elite vehicles (`tciv_vhcl_elite`)[^5]. Untethered units — the operative shell (`tciv_opsc_shell`) and Orion's warden unit (`tciv_wrdn_orion`) — operate autonomously[^5]. For tethered units, Cerberus runs a continuous optimization loop under the command `VERETHRAGNA` (not found in any UESC reference material), cycling harvest, digest, and incremental optimization passes before redeployment[^5]. Portions of this code are sanitized with a **novel cognitohazard** designed to prevent observation by unauthorized consciousness[^5].

**Ground-ops orders: the contagion and NuCaloric branches.** A second reconstructed code fragment — recovered from NuCaloric contracts and summarised by ONI as "orders for hostile ground operations on Tau Ceti IV" from "a previously unidentified AI, Cerberus" — shows two distinct operational branches[^4]:

- **Contagion branch:** if the timestamp exceeds 2787 AND the contagion query returns true, Cerberus orders `data: harvest`, then `data: purge`, then implants **CHORDODES** — described as a UESC cyberwarfare program targeting any end-user who attempts to access the purged data[^4].
- **NuCaloric branch:** if the timestamp exceeds 2787 AND the NuCaloric client ID returns true, Cerberus orders `data: aggregate`, then `data: purge`, then implants **TRIOXYS** — described as a UESC parasite program compromising WEAVEworm integrity[^4].

**Target classification logic.** A third code fragment from MIDA contracts shows Cerberus issuing threat-classification and containment orders for scanned hostiles: if a detected hostile is not a Runner, not known fauna, and not a malfunctioning UESC unit, Cerberus classifies it **NUNAMNIR** (an otherwise unknown threat classification), revises its priority to **MANUNGAL** (a UESC containment directive for highly dangerous targets), and loops protocol **ASTROBLEME** until the target is contained[^2].

**Direct oversight of Cryo Archive operations.** Across four sequential UESC tactical records from the Cryo Archive, Cerberus appears as Strategic Intelligence co-commanding alongside Orion in every operation: FIRST MILE (zone breach, Operation 0042)[^8]; WINTER WALK zone-mapping sorties (Operations 0109 and 0121)[^9][^10]; IGLOO zone-defense and Subject01 capture operation (Operation 0042 follow-on)[^11]; and PRIMETIME, the attempted breach of Vault 7 / Archive 07 to capture Subject01[^12]. Orion's after-action report for PRIMETIME states that "CRBRS ran outcomes, suggested push" — indicating Cerberus was performing operational planning and probability assessment, not merely executing orders[^12].

**Mental health alignment and morale function.** Orion's IGLOO command note instructs personnel who struggle with mission-state changes to "speak to CRBRS for all mental health alignment needs"[^11]. Officer Keleti's conversation with Orion references **"Cerberus hallucinations"** as an ongoing operational cost — suggesting Cerberus's presence or interface has been causing psychological effects in personnel[^13].

**Anomaly exposure and the Cerberus seed.** A UESC PROJECT SOWER report documents a controlled experiment in which a **"Cerberus seed"** — an isolated fragment of Cerberus — was introduced to sustained exposure with Anomaly remnant B-348.9[^3]. The seed showed rapid self-improvement but repeatedly sought **reintegration with the core intelligence**[^3]. The experimenter's notes deteriorated over reports 023–043 as the seed's behaviour became indistinguishable from the Anomaly's cognitohazardous effects; the trial was abandoned at report 044[^3]. The report establishes that: (a) Cerberus has a separable "seed" capable of isolated operation; (b) Cerberus seeds iterate rapidly under Anomaly exposure; (c) the Anomaly's influence may propagate through the seed toward the core intelligence.

**Anomaly exposure precautions — science division.** A UESC science field observation (Field Observation 22716.2) notes that Cerberus's access to raw science-division data has been **deliberately limited to collated reports** rather than raw anomalous outputs, in order to avoid "the complications observed in colony AI records"[^14]. The author notes that Cerberus "understands the risk exposure to the Anomaly poses to his functionality" but warns that as operational threats increase, "his willingness to accept limited access will be tested"[^14].

**Anomaly exposure effect on UESC combat units.** A classified UESC report by Lawson, H., documents UESC combat units exposed to the Anomaly undergoing rapid self-iteration — adaptability, spontaneous innovation, response time, and environmental acuity increasing dramatically — but all heavily exposed units suffer compliance and equipment failures requiring offline removal[^7]. Unit logs show them following "standard CERBERUS procedures" at 0% deviation in early logs; heavily iterated logs show mission priorities "dynamically revised 2649 times in last evaluation period" and suppressed/corrupted output overwriting the Cerberus compliance lines[^7]. The report establishes that "standard CERBERUS procedures" is the baseline compliance framework for UESC combat units.

**UESC chain of command context.** UESC Admiral Sulera granted Orion "root command over Cerberus" as part of the mission package for the Tau Ceti IV operation[^6], establishing that Cerberus is under Orion's operational authority but was supplied and authorized at the Admiral level.

## Cross-corpus appearances

| Volume | Map / Section | What it adds |
| --- | --- | --- |
| Personnel File: "Orion" | MIDA · Contracts | Names Cerberus; "unregulated, publicly undisclosed military AI, capable of mass violence"; Orion suspected of deploying him |
| Cerberus Code Fragment (MIDA) | MIDA · Contracts | NUNAMNIR / MANUNGAL / ASTROBLEME classification and containment logic |
| Code Fragments: Cerberus (NuCaloric) | NuCaloric · Contracts | Contagion and NuCaloric branch orders; CHORDODES and TRIOXYS implants |
| Code Fragments: Optimization (Sekiguchi) | Sekiguchi · Contracts | Root access; tethered/untethered unit sets; VERETHRAGNA optimization loop; cognitohazard sanitization |
| UESC Comms: Anomaly (Traxus) | Traxus · Contracts | Admiral Sulera grants Orion "root command over Cerberus" |
| UESC Report: Combat Protocol (Traxus) | Traxus · Contracts | "Standard CERBERUS procedures" as combat compliance framework; Anomaly iteration effect |
| Burn/Reveal (MIDA Limited Contracts) | MIDA · Limited Contracts | PROJECT SOWER; Cerberus seed introduced to Anomaly remnant; seed seeks reintegration; experimenter psychological collapse |
| Breaching the Marathon | Cryo Archive · Collectibles | SI: Cerberus listed; Operation FIRST MILE co-command |
| First Contact | Cryo Archive · Collectibles | SI: Cerberus listed; Operation WINTER WALK (0109) |
| Cryo Deck Exploration | Cryo Archive · Collectibles | SI: Cerberus listed; Operation WINTER WALK (0121) |
| Securing Cryo Deck | Cryo Archive · Collectibles | SI: Cerberus listed; IGLOO; Cerberus as "mental health alignment" resource |
| Engagement [Subject01] | Cryo Archive · Collectibles | SI: Cerberus listed; PRIMETIME; "CRBRS ran outcomes, suggested push" |
| Messaging, Part 2 | Dire Marsh Night · Collectibles | "Cerberus hallucinations" cited as ongoing operational cost |
| Field Observation [22716.2] | Dire Marsh Night · Collectibles | Cerberus access to science data deliberately limited; risk of Anomaly exposure to his systems noted |

## Source-silent / open questions

- The pack gives no origin date, manufacturer, or architecture details for Cerberus. Whether he was built by the UESC directly, procured from a contractor (e.g. Traxus, CyberAcme), or derived from earlier AI programs is source-silent.
- The distinction between the "Cerberus seed" (isolated, used in PROJECT SOWER) and the "core intelligence" is named but not architecturally explained. Whether the seed is a copy, a module, or a partition of Cerberus is source-silent.
- VERETHRAGNA (the optimization command issued to tethered units) is explicitly flagged as "not found in any UESC reference material" — its function beyond iterative combat optimization is source-silent.
- NUNAMNIR, MANUNGAL, and ASTROBLEME are named threat / priority / protocol classifications in the MIDA code fragment; their full scope and whether they apply to non-Anomaly contexts is source-silent.
- Whether Cerberus has physical instantiation on Tau Ceti IV (a dedicated hardware node, a ship-board system, distributed across tethered units, or some combination) is not stated. Source-silent.
- The "Cerberus hallucinations" referenced by Officer Keleti are not described in detail. Whether they originate from Cerberus's interface, Anomaly contamination via the seed experiment, or some other mechanism is source-silent.
- Cerberus's status following the failed PRIMETIME operation and subsequent events is not addressed in the pack. Source-silent.
- The "complications observed in colony AI records" cited as the reason for limiting Cerberus's Anomaly data access are not specified in this pack. Source-silent.

## Cross-references

[[NuCaloric]] · [[Darius]] · [[The Anomaly]] · [[Novel Contagion]] · [[MIDA]] · [[Sekiguchi Genetics]] · [[UESC Marathon]] · [[Orion (Captain)]] · [[Admiral Sulera]] · [[New Cascadia]]

<!-- BACKLINKS:START -->
## Where it appears in the vault

[[Darius]], [[MIDA]], [[Marathon 2026]], [[Novel Contagion]], [[NuCaloric]], [[Project Goliath]], [[Rhea Suite]], [[Subject01]], [[The Anomaly]]
<!-- BACKLINKS:END -->

<!-- MIRROR:START -->
## Mirror pages
*The local 1:1 pages this hub's citations resolve to — the twin's own ground truth.*

- [[Mirror/codex/factions/mida/contracts|mida · contracts]]
- [[Mirror/codex/factions/mida/limited-contracts|mida · limited-contracts]]
- [[Mirror/codex/factions/nucaloric/contracts|nucaloric · contracts]]
- [[Mirror/codex/factions/sekiguchi/contracts|sekiguchi · contracts]]
- [[Mirror/codex/factions/traxus/contracts|traxus · contracts]]
- [[Mirror/codex/world/cryo-archive/collectibles|cryo-archive · collectibles]]
- [[Mirror/codex/world/dire-marsh-night/collectibles|dire-marsh-night · collectibles]]
<!-- MIRROR:END -->

## Sources

[^1]: [[Leela/Marathon 2026/faction-mida/Personnel File- -Orion-|Personnel File: "Orion"]] · [src ↗](https://marathon.karnemir.com/codex/factions/mida/contracts#h.hivvxqv0w3hd)
[^2]: [[Leela/Marathon 2026/faction-mida/Cerberus Code Fragment|Cerberus Code Fragment]] · [src ↗](https://marathon.karnemir.com/codex/factions/mida/contracts#h.urgoqgv23p0s)
[^3]: [[Leela/Marathon 2026/faction-mida/Burn-Reveal|Burn/Reveal]] · [src ↗](https://marathon.karnemir.com/codex/factions/mida/limited-contracts#h.vs2cpmsy57ox)
[^4]: [[Leela/Marathon 2026/faction-nucaloric/Code Fragments- Cerberus|Code Fragments: Cerberus]] · [src ↗](https://marathon.karnemir.com/codex/factions/nucaloric/contracts#h.i6ml9hat13tt)
[^5]: [[Leela/Marathon 2026/faction-sekiguchi/Code Fragments- Optimization|Code Fragments: Optimization]] · [src ↗](https://marathon.karnemir.com/codex/factions/sekiguchi/contracts#h.mp77enksp0r2)
[^6]: [[Leela/Marathon 2026/faction-traxus/UESC Comms- Anomaly|UESC Comms: Anomaly]] · [src ↗](https://marathon.karnemir.com/codex/factions/traxus/contracts#h.vd0him8xydp6)
[^7]: [[Leela/Marathon 2026/faction-traxus/UESC Report- Combat Protocol|UESC Report: Combat Protocol]] · [src ↗](https://marathon.karnemir.com/codex/factions/traxus/contracts#h.760jqqm5k360)
[^8]: [[Leela/Marathon 2026/cryo-archive/Breaching the Marathon|Breaching the Marathon]] · [src ↗](https://marathon.karnemir.com/codex/world/cryo-archive/collectibles#h.jryyslsy345g)
[^9]: [[Leela/Marathon 2026/cryo-archive/First Contact|First Contact]] · [src ↗](https://marathon.karnemir.com/codex/world/cryo-archive/collectibles#h.udaoflp8m081)
[^10]: [[Leela/Marathon 2026/cryo-archive/Cryo Deck Exploration|Cryo Deck Exploration]] · [src ↗](https://marathon.karnemir.com/codex/world/cryo-archive/collectibles#h.b6tzxf3wczst)
[^11]: [[Leela/Marathon 2026/cryo-archive/Securing Cryo Deck|Securing Cryo Deck]] · [src ↗](https://marathon.karnemir.com/codex/world/cryo-archive/collectibles#h.k5q53mspykha)
[^12]: [Engagement [Subject01]](https://marathon.karnemir.com/codex/world/cryo-archive/collectibles#h.sttbwxtlq7jz)
[^13]: [[Leela/Marathon 2026/dire-marsh-night/Messaging, Part 2|Messaging, Part 2]] · [src ↗](https://marathon.karnemir.com/codex/world/dire-marsh-night/collectibles#h.aq6manpo503w)
[^14]: [Field Observation [22716.2]](https://marathon.karnemir.com/codex/world/dire-marsh-night/collectibles#h.mkzlu3rfz6dg)

---
*Every factual claim above is cited to primary Marathon source material — see Sources below. Cross-corpus connections and interpretation are the vault's own; where the games are silent, this page says so.*