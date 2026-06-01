# Wolfgang Rush — Motor Accident Claims Tribunal Drafting

**MCPB Desktop Extension** for drafting pleadings before Motor Accident Claims Tribunals across India under the Motor Vehicles Act 1988 (as amended by MV Amendment Act 2019).

State-config-aware: 8 priority State exemplars. Designed for Indian advocates using **Claude Desktop App**. Local-execution. Zero data collection.

> *Also available as a Claude Code Plugin:* *[github.com/Wolfgangrush/indian-mact-drafting](https://github.com/Wolfgangrush/indian-mact-drafting)*

---

## Case types (10)

| Case type | Statutory anchor |
|---|---|
| Fault-based petition | MV Act Section 166 |
| Lump-sum no-fault | MV Act Section 164 (2019 amendment) |
| Solatium / hit-and-run | MV Act Section 161 + Solatium Fund Scheme |
| Third-party insurance | MV Act Section 147 |
| Appeal to High Court | MV Act Section 173 |
| Interim compensation application | MACT |
| Claim execution | MACT |
| Collector recovery | MV Act Section 174 |
| MV criminal defence | BNSS 2023 |
| Workmen's compensation | Employee's Compensation Act 1923 |

Sarla Verma + Pranay Sethi multiplier doctrine encoded in the pleading base.

## State exemplars (8 priority States)

`delhi` · `gujarat` · `karnataka` · `kerala` · `maharashtra` · `tamil-nadu` · `uttar-pradesh` · `west-bengal`

## Install

1. Claude Desktop App → **Settings → Extensions → Install Extension**
2. Select `wolfgang-indian-mact-drafting.mcpb`
3. Enable

## System requirements

Claude Desktop App ≥ 0.10.0 · Python ≥ 3.10 · `pandoc` · `pdftotext` (optional)

## Tools

`list_case_types` · `get_case_type_format` · `get_agent_instructions` · `get_pleading_base` · `list_states` · `get_state_exemplar` · `read_case_folder` · `save_draft_as_docx`

## Privacy

Zero data collection. Three-layer privacy firewall. Canonical policy: **<https://wolfgangrush.github.io/privacy/>**


## ⚠️ AI verification disclaimer · 🔒 Pseudonymisation procedure

> **⚠️ AI can make mistakes — please verify the information before filing.**
> Every draft produced by this connector is a STARTING POINT. The Verifier
> agent runs an anti-hallucination firewall and the Overseer agent runs an
> opposing-counsel review, but neither replaces an advocate's independent
> verification of statutory references, citation accuracy, factual fidelity,
> and Registry-formatting compliance with the user's High Court / forum.
> The advocate filing the pleading remains responsible for the contents.
>
> **🔒 Protected by pseudonymisation procedure.** The Reader agent applies a
> domain-specific privacy firewall as the first step of the pipeline — party
> names, addresses, identifying numbers (FIR / CR / Crime / Suit / Diary /
> SLP / lower-court case numbers), PAN / Aadhaar references, financial
> figures, witness names, and statutory-notice references are substituted
> with structural placeholders BEFORE any downstream agent sees the facts.
> The Drafter, Verifier, Refiner, and Overseer agents process placeholders
> only. Real values are re-substituted at the final docx render step on the
> user's local machine. No real identifying data leaves the case folder.

## License

MIT.

## Publisher

**Rushikesh R. Mahajan**, Advocate, Bombay HC Nagpur, publishing as **Wolfgang Rush**. advrushikeshravindramahajan@gmail.com

## Source

<https://github.com/Wolfgangrush/indian-mact-drafting-mcpb>
