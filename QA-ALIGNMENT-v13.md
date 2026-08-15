# QA and Alignment Report — v13

## Outcome

The v13 package is aligned to TGS-2020505315 and ACC-ICT-4001-1.1. It preserves the approved Written Assessment and Oral Questioning instrument types, uses concept-led slides, and places detailed procedures in the Learner Guide and activity packs.

## Assessment traceability

| Criterion | Instrument | Course coverage | Activity evidence |
|---|---|---|---|
| A1 | WA Q1 | Topic 1 — retrieval, migration and master-data controls | Activities 01–02 |
| A2 | WA Q2 | Topic 2 — day-to-day transaction input and controls | Activities 03–06 |
| A3 | WA Q3 | Topic 3 — GST coding, calculation and review | Activities 07–08 |
| A4 | WA Q4 | Topic 4 — financial, ageing and GST reporting | Activities 09–10 |
| K1 | OQ Q1 | Topic 1 — accounting-system types and Xero selection | Activity 01 |
| K2 | OQ Q2 | Topic 2 — integrated information flows | Activity 05 |
| K3 | OQ Q3 | Topic 3 — Singapore tax and record context | Activities 07–08 |
| K4 | OQ Q4 | Topic 3 — GST computations and controls | Activities 07–08 |
| K5 | OQ Q5 | Topics 2 and 4 — specialist software and reports | Activities 06 and 09 |

## Verification completed

- 125-slide PPTX and matching PDF generated from the single-source build.
- No click-by-click activity procedures detected in teaching slides.
- Every slide contains the required course footer and copyright.
- One populated trainer profile; unused generic trainer template removed.
- Editable native PowerPoint charts include reporting dates.
- Learner Guide contains detailed numbered procedures for all ten activities.
- Exactly ten individual `activities/` folders; no learner-facing `labs/` path.
- Every activity includes README, checklist, realistic CSV input and an Excel control/evidence workbook.
- All ten workbooks recalculated successfully: 0 formula errors across 116 formulas.
- Lesson Plan maps the final slide numbers, activity flow and assessment schedule.
- WA and OQ candidate papers plus trainer-only answer keys generated and rendered cleanly.
- Structural courseware QA: 198 checks passed, 0 failed after the final rebuild.
- Independent visual audit completed; identified legacy label and placeholder issues were corrected and re-rendered.

## Command workflow

The requested command sequence was executed using the installed WSQ command definitions and their underlying scripts. No literal `/tms-push-qa` command exists in the installed command set; its intent is satisfied by structural QA, Drive dry-run, TMS dry-run, a secret-safe before snapshot and post-write readback comparison.
