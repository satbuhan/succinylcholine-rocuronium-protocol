# Selection of a Neuromuscular Blocking Agent for Rapid Sequence Induction and Intubation

An interactive, referenced walkthrough of the decision algorithm for choosing succinylcholine or
rocuronium as the neuromuscular blocking agent for rapid sequence induction and intubation (RSI)
— from contraindication screening, through the airway-rescue strategy, to whether the
post-intubation analgosedation system is ready. Every box and decision point in the diagram can
be selected to reveal, in one place: what the step means, why the algorithm calls for it, and the
sources behind it.

**Live site:** https://satbuhan.github.io/succinylcholine-rocuronium-protocol/

**Authors:** Dr. Özgür Karcıoğlu & Dr. Satuk Buğra Han Bozatlı

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24112652.svg)](https://doi.org/10.5281/zenodo.24112652)

This tool is part of a growing atlas of tools built the same way:

- [Clinical Algorithm Atlas](https://satbuhan.github.io/clinical-algorithm-atlas/) — the hub page for all of them
- [Acute aortic dissection — initial medical management](https://github.com/satbuhan/aortic-dissection-protocol) ([live site](https://satbuhan.github.io/aortic-dissection-protocol/))
- [Butyrophenone selection — acute agitation & hyperactive delirium](https://github.com/satbuhan/agitation-delirium-protocol) ([live site](https://satbuhan.github.io/agitation-delirium-protocol/))
- [Influenza antiviral selection — baloxavir marboxil vs oseltamivir](https://github.com/satbuhan/influenza-antiviral-protocol) ([live site](https://satbuhan.github.io/influenza-antiviral-protocol/))
- [Dexketoprofen vs ibuprofen — selecting an NSAID for acute pain](https://github.com/satbuhan/nsaid-pain-protocol) ([live site](https://satbuhan.github.io/nsaid-pain-protocol/))
- [Anticoagulant reversal in gastrointestinal haemorrhage](https://github.com/satbuhan/anticoagulant-reversal-protocol) ([live site](https://satbuhan.github.io/anticoagulant-reversal-protocol/))
- [The adult with obesity in emergency and critical care](https://github.com/satbuhan/obesity-critical-care-protocol) ([live site](https://satbuhan.github.io/obesity-critical-care-protocol/))
- [Dapagliflozin / SGLT2 inhibitor — overdose and acute illness management](https://github.com/satbuhan/dapagliflozin-overdose-protocol) ([live site](https://satbuhan.github.io/dapagliflozin-overdose-protocol/))
- [Lidocaine vs prilocaine — local anaesthesia for laceration repair](https://github.com/satbuhan/lidocaine-prilocaine-protocol) ([live site](https://satbuhan.github.io/lidocaine-prilocaine-protocol/))
- [Reperfusion therapy in acute pulmonary thromboembolism](https://github.com/satbuhan/pte-thrombolysis-protocol) ([live site](https://satbuhan.github.io/pte-thrombolysis-protocol/))
- [LMWH selection & renal dosing in NSTE-ACS](https://github.com/satbuhan/lmwh-nste-acs-protocol) ([live site](https://satbuhan.github.io/lmwh-nste-acs-protocol/))
- [Ketamine in head injury — safety & complication management](https://github.com/satbuhan/ketamine-head-injury-protocol) ([live site](https://satbuhan.github.io/ketamine-head-injury-protocol/))
- [Midazolam versus clonazepam — seizures, acute agitation & anxiety](https://github.com/satbuhan/midazolam-clonazepam-protocol) ([live site](https://satbuhan.github.io/midazolam-clonazepam-protocol/))
- [Vasopressor (aminergic) agent selection in shock states](https://github.com/satbuhan/vasopressor-shock-protocol) ([live site](https://satbuhan.github.io/vasopressor-shock-protocol/))
- [Whole-body CT in traumatic circulatory shock](https://github.com/satbuhan/wbct-trauma-protocol) ([live site](https://satbuhan.github.io/wbct-trauma-protocol/))
- [Epinephrine/Adrenaline revisited — contemporary decision-making algorithm](https://github.com/satbuhan/epinephrine-revisited-protocol) ([live site](https://satbuhan.github.io/epinephrine-revisited-protocol/))
- [Ketamine in emergency and critical care — indication-based decision algorithm](https://github.com/satbuhan/ketamine-indications-protocol) ([live site](https://satbuhan.github.io/ketamine-indications-protocol/))
- [Tenecteplase versus alteplase — fibrinolysis in STEMI](https://github.com/satbuhan/tenecteplase-alteplase-stemi-protocol) ([live site](https://satbuhan.github.io/tenecteplase-alteplase-stemi-protocol/))
- [Blood gas-guided assessment of the chemical warfare agent casualty](https://github.com/satbuhan/cwa-blood-gas-protocol) ([live site](https://satbuhan.github.io/cwa-blood-gas-protocol/))
- [Calcium channel blocker toxicity — phenotype-guided management](https://github.com/satbuhan/ccb-toxicity-protocol) ([live site](https://satbuhan.github.io/ccb-toxicity-protocol/))
- [Choosing an adjunct to haloperidol in hyperactive delirium with severe agitation](https://github.com/satbuhan/haloperidol-adjunct-protocol) ([live site](https://satbuhan.github.io/haloperidol-adjunct-protocol/))

## Why this exists

A flowchart alone tells a reader *what* to do at each step but not *why*, and a reader outside
the authors' own team cannot easily check the evidence behind a specific box (why the dashed
contraindication box uses the time cut-offs it does; why airway-rescue strategy, not drug
familiarity alone, decides the second branch; why the third step treats sedation readiness as a
drug-selection criterion in its own right). This page keeps the original algorithm exactly as
authored, and attaches the clinical reasoning and literature to each box without cluttering the
diagram itself.

The algorithm this page presents is Figure 1 of "Succinylcholine versus Rocuronium for Tracheal
Intubation: A Systematic Review of Intubating Conditions, Procedural Ease and Clinical Outcomes"
— from a standalone figure image (TIFF) supplied directly by the authors, cross-checked box by
box against the original at native resolution rather than against the condensation's prose
description alone.

## Status

This is a working version, built to be tested on both desktop and mobile.

- **Source workflow note:** same external-AI condensation path as `cwa-blood-gas-protocol`,
  `ccb-toxicity-protocol` and `haloperidol-adjunct-protocol` — the manuscript was run through an
  external AI (Gemini) using this project's structured condensation prompt
  (`tools/gemini-condensation-prompt.md` in the hub repo, v2), and this tool was built from that
  condensed document plus the authors' own standalone Figure 1 image.
- **Reference verification — full, independent pass, no exception granted:** unlike
  `epinephrine-revisited-protocol`, `ketamine-indications-protocol` and
  `haloperidol-adjunct-protocol`, no author exception was given for this tool — every one of the
  97 references was run through this session's own independent verification (DOI resolution,
  PubMed/PMC, or an independent citing source), not accepted on the manuscript's or the
  condensation's word. See each reference's `kind` field in `assets/content.js` for exactly what
  was confirmed. Two honest findings from that pass:
  - **Reference 22** (a 2025 Acta Anaesthesiologica Scandinavica paper on intubating conditions
    in elderly patients) could not be located anywhere under its cited DOI, title, or author
    combination, despite a dedicated search — flagged `NOT VERIFIED — likely fabricated or
    severely garbled`. A real, different paper by the same first author exists in the same
    journal on a related but distinct question, and a matching-topic trial registry entry exists
    with no linked publication; neither is a confirmed match for the citation as given. It is
    currently cited (alongside the unverified reference 38) on the `succinylcholine_vent` node's
    onset-time claim — this needs the author team's attention before publication: either a
    substitute real citation for that claim, or a flag on the node itself.
  - **Reference #98 is missing.** The manuscript's own narrative text cites reference ranges
    `[19,92-98]` and `[92-98]` in two places, implying a seventh reference in that cluster, but
    the condensed reference list stops at #97. This looks like a transcription gap introduced by
    the AI condensation step rather than something recoverable from citation context — flagged
    here rather than invented.
  - **21 of the 97 references remain genuinely unchecked, and 8 of them are cited directly on a
    visible diagram node — this is the single most important open item in this build.** This
    session's shared web-search budget ran out mid-pass across six parallel verification
    batches, and a dedicated single-agent follow-up pass aimed specifically at the gap found the
    budget already exhausted session-wide rather than reset — see `METHODOLOGY.md` for the full
    account. The other 76 references were independently confirmed (most cleanly; a few with a
    corrected author name or an unconfirmed secondary field, flagged in their own `kind` string).
    The 21 unchecked references, by id: 12, 14, 16, 29, 37-48, 61-64, 70, 73, 77, 96. Of these,
    **29, 38, 41, 44, 45 and 46** are cited on one or more diagram nodes — `step1_criteria`
    (29), `rocuronium_contra` and `either_agent` (41), `succinylcholine_vent` (38, alongside the
    flagged ref 22 below), `step3_header`/`analgosedation_decision`/`prefer_succinylcholine` (44,
    45, 46), and the closing `applies_every_pathway` pearls box (41, 44, 45, 46, plus unchecked
    61 and 77). This needs a follow-up verification pass, specifically targeting these
    diagram-cited references first, once the search budget resets — before the author team
    should treat this tool as fully checked.
- **Rendering note — Step 3's decision:** the source figure draws Step 3's decision diamond on
  its own, with both the YES and NO branches ending in a terminal box side by side below it (a
  genuine two-way split, unlike Steps 1-2 where only YES exits to a side box and NO continues the
  trunk). An initial build rendered this as a 3-wide same-row group (diamond flanked by both
  outputs), which produced a real edge/box overlap — the diamond-to-far-box edge cut straight
  through the near box sitting between them. Fixed by giving the decision its own full-width row
  and placing the two outcomes in a 2-wide group in the row below it, matching the source figure's
  own layout more closely and eliminating the overlap. See `assets/app.js`'s `LAYOUT` comment.
- **Rendering note — the closing pearls box:** the authors' own Figure 1 draws "APPLIES TO EVERY
  PATHWAY" with no arrow in or out of it, visually apart from the decision tree. Preserved here by
  giving that node a `LAYOUT` entry (so it renders and is clickable) but no entry at all in
  `EDGES`, in either direction.

## Disclaimer

This is an academic / educational reference tool, not a substitute for institutional protocol or
bedside clinical judgement. Doses shown reflect the algorithm as authored; verify against current
local protocol before clinical use.

## How it's built

Plain HTML/CSS/JS, no build step and no framework — a single static site that GitHub Pages can
serve directly.

```
index.html          page structure — masthead, the diagram (trunk, three chained steps, Step 3's
                     decision-above/two-terminals-below split), readout panel, references,
                     abbreviation legend, footer
assets/style.css     design (the "paper" masthead/references, the single-trunk diagram grid and
                     its 2-wide fan-outs)
assets/content.js     ← single source of truth for every node's text and reference list. Edit
                     this file to change what the page says.
assets/app.js         rendering + interaction (builds the diagram and its connector lines from
                     content.js, handles the click-to-expand panel on desktop and the bottom
                     sheet on mobile)
```

### Running it locally

No install needed:

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

### Editing content

Open `assets/content.js`. Each entry in `NODES` is one box or decision diamond from the diagram
(`meaning`, `rationale`, optional `cautions`/`dose`, and `refs` pointing at numbered entries in
`REFERENCES`). Add or edit a reference in `REFERENCES` and point to it by `id` from any node.
Never change a node's `label` or `sub` text without the author team's sign-off — those fields are
the algorithm itself, transcribed verbatim from the authors' standalone figure image.

### Building the next tool in this atlas

See [`METHODOLOGY.md`](METHODOLOGY.md) — the full build/verification process (fidelity rule,
content schema, citation verification, QA steps), written so that any collaborator or AI
assistant can pick up this project in a fresh session and build the next tool the same way.

## License

Content and code are released under
[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) — share and adapt with
attribution, non-commercially, under the same license.
