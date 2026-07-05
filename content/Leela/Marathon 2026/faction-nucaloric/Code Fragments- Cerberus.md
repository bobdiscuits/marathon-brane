---
type: leela
game: "[[Marathon 2026]]"
group: faction-nucaloric
subhub_model: faceted
facets: [factions, nucaloric]
volume-id: codex/factions/nucaloric/contracts.md::4
source_url: https://marathon.karnemir.com/codex/factions/nucaloric/contracts#h.i6ml9hat13tt
words: 131
canon-status: source
tags: [leela, verbatim, factions, nucaloric]
---

# Code Fragments: Cerberus

ANALYZING…  

FILE TYPE: Reconstructed Code Fragments 

PERIOD: Present Day 

TOPIC: Hostile UESC operations 

SUMMARY: Code fragments from a damaged UESC unit's command module, containing orders for hostile ground operations on Tau Ceti IV. Orders appear to originate from a previously unidentified AI, "Cerberus." Annotated by ONI.

\===================================================================   

  

[AUTHORIZATION] Cerberus 

  

[IF] 

  

     timestamp > 2787 

     [AND]  

     query: contagion = true 

  

[THEN]

  

     [EXECUTE] data: harvest 

     [EXECUTE] data: purge

     [IMPLANT] CHORDODES [1]

  

[ELSE IF] 

  

     timestamp > 2787 

     [AND] 

     cID: NuCal = true 

  

[THEN]

  

     [EXECUTE] data: aggregate

     [EXECUTE] data: purge 

     [IMPLANT] TRIOXYS [2]

  

[ELSE] 

  

     [EXECUTE] patrol 

  

[END IF] 

  

[1] UESC cyberwarfare program targeting end user who attempts to access the purged data. Updating cyberwarfare procedures. 

  

[2] UESC parasite program compromising WEAVEworm integrity. Updating shell firmware to resist hostile implantation.

  

\=================================================================== 

TYPE: TEXT [X]; AUDIO [  ]

---
*— everything above is 1:1 source · from [[Mirror/codex/factions/nucaloric/contracts|contracts]] · [karnemir ↗](https://marathon.karnemir.com/codex/factions/nucaloric/contracts#h.i6ml9hat13tt)*

<!-- CITEDBY:START -->
### Cited by
[[Cerberus]] · [[NuCaloric]]
<!-- CITEDBY:END -->
