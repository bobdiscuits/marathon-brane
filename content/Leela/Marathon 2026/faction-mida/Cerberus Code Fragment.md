---
type: leela
game: "[[Marathon 2026]]"
group: faction-mida
subhub_model: faceted
facets: [factions, mida]
volume-id: codex/factions/mida/contracts.md::4
source_url: https://marathon.karnemir.com/codex/factions/mida/contracts#h.urgoqgv23p0s
words: 176
canon-status: source
tags: [leela, verbatim, factions, mida]
---

# Cerberus Code Fragment

ANALYZING…  

FILE TYPE: Reconstructed Code Fragments  

PERIOD: Present Day 

TOPIC: UESC Mission Priorities 

SUMMARY: Code fragments from a UESC unit's command module, containing orders related to target identification and containment on Tau Ceti IV. Orders originate from AI, "Cerberus." Annotated by ONI.

\=================================================================== 

  

[AUTHORIZATION] CERBERUS  

  

initiating order revision…  

  

[IF]  

  

     scan: area == COMPROMISE  

     [AND]  

     query: target == HOSTILE

     [AND] 

     query: target != BIOSYNTH; UNREGISTERED 

     query: target != FAUNA; KNOWN 

     query: target != UNIT; MALFUNCTION

  

[THEN]  

     classify target: NUNAMNIR [1]

     revise priority direct: MANUNGAL [2]

     [LOOP]      

     target status = protocol: ASTROBLEME [3]

     [UNTIL] 

     target status == CONTAINED  

  

[ELSE]  

  

     [EXECUTE] standard patrol  

  

[END IF]  

  

[1] An unknown threat classification used by the UESC. In the event a detected hostile is not a Runner, native Tau Ceti IV wildlife, or a malfunctioning UESC unit, Cerberus orders it should be classified as "Nunamnir." 

  

[2] A priority directive used across UESC operations. Refers to containment procedures intended to avoid destruction of highly dangerous targets. 

  

[3] An unknown protocol classification. Related to above containment procedures.

  

\=================================================================== 

TYPE: TEXT [X]; AUDIO [  ]

---
*— everything above is 1:1 source · from [[Mirror/codex/factions/mida/contracts|contracts]] · [karnemir ↗](https://marathon.karnemir.com/codex/factions/mida/contracts#h.urgoqgv23p0s)*

<!-- CITEDBY:START -->
### Cited by
[[Cerberus]] · [[Runners]] · [[Subject01]] · [[Tau Ceti IV]]
<!-- CITEDBY:END -->
