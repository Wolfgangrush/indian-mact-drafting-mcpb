# Case Facts Background — MACT Section 166 fault-based claim · permanent partial disability

All party names, registration numbers, FIR / policy / certificate numbers, monetary figures, and ancillary dates are fictional placeholders.

## Parties

- **Claimant / Petitioner:** [Claimant-A], aged 32, salaried Software Engineer at [Employer-Placeholder] Pvt. Ltd. earning Rs. [Gross-Salary-Placeholder]/- per month at the date of accident.
- **Respondent No. 1 (Owner of offending vehicle):** [Owner-A], registered owner of motor truck No. [Vehicle-Reg-No-Placeholder].
- **Respondent No. 2 (Driver):** [Driver-A], driving licence No. [DL-No-Placeholder].
- **Respondent No. 3 (Insurer):** [Insurer-A] under Policy No. [Policy-No-Placeholder]; comprehensive policy with statutory unlimited third-party liability cover. Policy valid on date of accident.

## Accident particulars

- **Date and time:** 12 September 2025 at approximately 19:45 hrs.
- **Place:** NH [Highway-Placeholder] near [Landmark-Placeholder], within P.S. [Placeholder-PS] limits, District [District-X].
- **Offending vehicle:** Motor truck No. [Vehicle-Reg-No-Placeholder].
- **Victim's vehicle:** Motorcycle No. [Victim-Vehicle-Reg-Placeholder].
- **Manner:** Head-on collision caused by rash and negligent driving of the offending truck.
- **FIR:** No. [FIR-N-Placeholder]/2025 registered at P.S. [Placeholder-PS] under Sections 281 / 125(a) / 125(b) BNS 2023 r/w Section 184 MV Act 1988 (see `01-fir-police-accident-report-2025-09-12.docx`).

## Injuries and disability

- Below-knee amputation of right lower limb (RBKA).
- ORIF for comminuted fracture of right humerus (residual ROM restriction).
- Healed fracture of pubic rami.
- Soft-tissue injuries (healed).
- **Combined permanent partial disability: 65% of the whole person** — certified by Medical Board on 18 February 2026 (see `02-medical-disability-certificate-2026-02-18.docx`).
- Functional consequence: unfit for field-engineering work; fit only for sedentary desk work.

## Income loss

- Monthly gross at date of accident: Rs. [Gross-Salary-Placeholder]/- (see `03-salary-certificate-and-policy-summary.docx`).
- Post-injury reduced effective compensation: ~Rs. [Reduced-Salary-Placeholder]/- per month (loss of site-visit + overtime).
- Loss of future earning capacity: 65% of monthly income × multiplier appropriate to age 32.

## Forum and case type

- **Forum:** Motor Accident Claims Tribunal (MACT), [District-X], Maharashtra.
- **Case type:** `mact-petition-section-166-fault-based`.
- **State:** Maharashtra (state exemplar applies for Court-fee and forum nomenclature).
- **Limitation:** No limit (Section 166(3) MV Act post-2019 amendment removed the 6-month limit).

## Quantum framework (Drafter applies)

- **Sarla Verma v. DTC (2009) 6 SCC 121** — multiplier table by age.
- **National Insurance Co. v. Pranay Sethi (2017) 16 SCC 680** — future-prospects: +50% for permanent salaried under 40; +25% for 40–50; +10% for 50–60.
- **Conventional heads** — loss of consortium, loss of love and affection, funeral expenses (revised quantum per Pranay Sethi).
- **Multiplier at age 32:** 16 (per Sarla Verma table).
- **Annual income:** Rs. [Gross-Salary-Placeholder]/- × 12 = Rs. [Annual-Income-Placeholder]/-.
- **With future prospects +50%:** Rs. [Annual-Income-with-FP-Placeholder]/-.
- **Loss of earning capacity (65%):** 65% × annual income with FP × multiplier 16.
- **Plus** medical expenses, attendant charges, special diet, transport, prosthesis cost (initial + replacement cycle).

## Reliefs sought

1. Just compensation under Section 168 MV Act 1988 — quantified at Rs. [Total-Compensation-Placeholder]/- under conventional and modern heads.
2. Interest at 7.5% per annum (per Tribunal practice) from date of petition till realisation.
3. Costs of the proceedings.
4. Direction to the Insurer (Respondent No. 3) to satisfy the award.

## How to use this fixture

1. Point `read_case_folder(path)` at this directory.
2. Reader extracts facts from the 3 `.docx` files plus this `case-facts-background.md`.
3. Call `get_case_type_format("mact-petition-section-166-fault-based")`.
4. Call `get_state_exemplar("maharashtra")` for Maharashtra-specific MACT forum conventions.
5. The remaining 5 agents (Format → Drafter → Verifier → Refiner → Overseer) run end-to-end to produce `final-draft.docx` containing the claim petition with Sarla Verma + Pranay Sethi quantum computation, list of documents, and verification.
