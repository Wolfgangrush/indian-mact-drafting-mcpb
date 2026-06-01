# Sample Cases — Reviewer Examples

Three anonymised MACT fact patterns. All party names are placeholders.

## Example 1 — Section 166 fault-based compensation petition (Maharashtra)

> *"Draft a compensation petition under Section 166 MV Act 1988 before the MACT at [DISTRICT-X] (Maharashtra) for the permanent partial disability claim of [CLAIMANT] aged 32. Accident dated 2025-09-12, vehicle owned by [OWNER], driven by [DRIVER], insured with [INSURER] under policy No. [POL-N]. Claimant was a salaried IT professional earning ₹[SUM-X] per month, suffered 65% disability. Apply Sarla Verma + Pranay Sethi multiplier framework. Prayer: ₹[SUM-Y] total compensation under conventional heads."*

Tool sequence: list_case_types → get_case_type_format("mact-petition-section-166-fault-based") → list_states → get_state_exemplar("maharashtra") → get_pleading_base → draft → save_draft_as_docx

## Example 2 — Section 164 lump-sum no-fault (Karnataka)

> *"Draft a no-fault claim under Section 164 MV Act (2019 amendment) before the MACT at Bengaluru (Karnataka) for the dependents of deceased [DECEASED], age at death 28. Accident dated 2026-01-05, fixed compensation ₹5,00,000 under Section 164. Claimants: widow [WIDOW] aged 25 and minor child aged 2. Bypass fault inquiry."*

Tool sequence: list_case_types → get_case_type_format("mact-petition-section-164-lump-sum") → list_states → get_state_exemplar("karnataka") → get_pleading_base → draft → save_draft_as_docx

## Example 3 — Section 173 HC appeal against MACT award (Tamil Nadu)

> *"Draft an appeal under Section 173 MV Act to the Madras High Court against the MACT, Chennai award dated 2026-02-10 in MCOP No. [MCOP-N]/2024. Grounds: inadequate quantum (MACT applied wrong multiplier age-bracket per Sarla Verma table), failure to add future-prospects 50% under Pranay Sethi, no addition for loss of consortium / love and affection / funeral expenses. Prayer: enhancement of award + interest."*

Tool sequence: list_case_types → get_case_type_format("mact-appeal-section-173-to-high-court") → list_states → get_state_exemplar("tamil-nadu") → get_pleading_base → draft → save_draft_as_docx

## Notes for the reviewer

- Placeholders only (`[CLAIMANT]`, `[OWNER]`, `[DRIVER]`, `[INSURER]`, `[POL-N]`, `[SUM-X]`, `[MCOP-N]`, etc.). No real client data.
- No external API keys / accounts required.
- `save_draft_as_docx` requires `pandoc`.
- Three-layer privacy firewall applies throughout.
