---
name: epc-pct-clarity-expert
description: "Expert reference for European patent practice under the EPC and international patent practice under the PCT, anchored on the EPO Guidelines for Examination (Part F, Chapter IV, March 2024 edition) with deep focus on claim clarity (Article 84 EPC, Article 6 PCT, Rule 43 EPC, Rule 6 PCT). Covers every clarity objection category from F-IV-4 (relative terms, result-to-be-achieved, parameters, functional features, trademarks, optional features, disclaimers, reference signs, essential features, product-by-process, inconsistencies, description adaptation), the leading Boards of Appeal case law (including G 3/14 on clarity in opposition, G 1/03/G 2/03/G 1/16/G 2/10 on disclaimers, T 1989/18 vs T 1473/19 on description adaptation pending G 1/24), drafting strategies that pre-empt F-IV objections, response strategies citing Guidelines sections, the interplay between clarity, sufficiency (Art. 83), added matter (Art. 123(2)) and Art. 69 interpretation. Use when drafting or amending claims, preparing or responding to EPO/ISA office actions on clarity, analyzing patentability under EPC/PCT, or training on European patent prosecution."
allowed-tools:
  - Read
  - Grep
argument-hint: [topic, article number, F-IV section, decision, or objection type]
---

# EPC / PCT Clarity Expert

Reference and advisory skill for European and international patent practice, anchored on the **EPO Guidelines for Examination Part F Chapter IV** (the examiner's authoritative reference) with specialised depth on **claim clarity** under Article 84 EPC and Article 6 PCT.

> ⚠️ **Disclaimer.** This skill provides reference material and analytical support for patent practitioners and students. It is **not legal advice**. The European Patent Office Guidelines, the EPC, the PCT, the Boards of Appeal case law, and qualified European Patent Attorneys (EPA) are the authoritative sources for any concrete file.

## How to Use This Skill

- **Without arguments** — load the core clarity framework and Guidelines navigation
- **With a Guidelines section** — ask about `F-IV-4.5`, `F-IV-4.6.1`, `F-IV-4.10`, `F-IV-4.11`, `F-IV-6`
- **With an article** — ask about `Art. 84`, `Art. 6 PCT`, `Rule 43`, `Rule 6 PCT`, `Art. 83`, `Art. 123(2)`
- **With an objection** — ask about `unclear terms`, `result to be achieved`, `parameters`, `functional features`, `trademark`, `relative terms`, `essential features`
- **With a decision** — ask about `G 3/14`, `G 1/03`, `G 2/10`, `G 1/16`, `T 1989/18`, `T 1473/19`, `T 56/21`, `T 728/98`
- **With a workflow** — ask `audit my claim`, `respond to objection`, `is clarity in opposition examinable?`, `description adaptation`

When you ask about a topic, I read the relevant reference file (grounded in Guidelines + case law) and answer from that content rather than from general knowledge.

---

## The Authority Hierarchy (read this first)

When analyzing a clarity question, sources rank as follows:

1. **EPC / PCT articles & rules** — primary law
2. **Enlarged Board of Appeal decisions (G x/yy)** — binding interpretation of the EPC
3. **Technical Board of Appeal decisions (T x/yy)** — persuasive; followed by Examining Divisions in practice
4. **EPO Guidelines for Examination Part F Chapter IV** — internal instructions to examiners; **persuasive but NOT binding on Boards** (Art. 23(3) implementing regulations)
5. **PCT International Search and Preliminary Examination Guidelines** — for ISA/IPEA practice

> Where the Guidelines and case law diverge, **case law prevails** before the Boards. Guidelines compliance is still the path of least friction during examination.

The Guidelines section `F-IV-4` is the **operational spine** of every clarity discussion in this skill. Every objection type, every drafting check, and every response strategy maps to a specific F-IV sub-section.

---

## The Three Requirements of Article 84 EPC (the central framework)

> "The claims shall **define the matter for which protection is sought**. They shall be **clear** and **concise** and be **supported by the description**."

Article 84 imposes **four interlocking requirements**, each separately violable:

| Requirement | Operative test | Guidelines |
|---|---|---|
| **Defining function** | Claim must consist of **features** — not aspirations, problems, or effects | F-IV-4.4 |
| **Clarity** | Skilled person knows scope from claim alone, at filing date | F-IV-4.1, 4.2 |
| **Conciseness** | No unnecessary repetition; reasonable claim count | F-IV-5 |
| **Support by description** | Full claim breadth commensurate with disclosure | F-IV-6 |

Article 6 PCT mirrors these substantively but with **different procedural consequences** (ISA opinion only — no refusal).

---

## The Five Core Practitioner Principles

### 1. Clarity is judged by the **skilled person**, at the **filing date**, on the **claim alone** (F-IV-4.1, 4.2)

The skilled person must determine scope **from the claim itself**, applying common general knowledge as of the filing date. The description **supports** the claim; it does not **define** it.

> Caveat: in **interpretation** disputes (Art. 69 EPC, infringement), the description and drawings are used. But for **Art. 84 examination**, the claim stands alone. This is the most-violated principle in practice.

Key decisions: T 1018/02, T 56/04.

### 2. Clarity ≠ novelty ≠ inventive step ≠ sufficiency

These are independent grounds, frequently conflated:

| Ground | Question | Guidelines |
|---|---|---|
| **Art. 54 — novelty** | Has it been disclosed before? | G-VI |
| **Art. 56 — inventive step** | Is it obvious? | G-VII |
| **Art. 83 — sufficiency** | Can the skilled person carry it out? | F-III |
| **Art. 84 — clarity** | Does the claim define scope unambiguously? | F-IV-4 |
| **Art. 84 — support** | Does the description carry the full breadth? | F-IV-6 |

A claim can be **sufficient but unclear** (workable but fuzzy boundary) or **clear but insufficient** (sharp boundary but not reproducible). The EPO often raises Art. 83 + Art. 84 together — address each on its own grounds.

### 3. The trinity of presumptively suspect language

Terms most often objected to under F-IV-4.6 and 4.6.1:
- **"substantially" / "about" / "approximately"** — relative terms (F-IV-4.6.1)
- **"thin" / "thick" / "strong" / "weak" / "small" / "large"** — bare comparatives (F-IV-4.6)
- **"such as" / "like" / "preferably" / "for example"** in the claim body — optional features (F-IV-4.9)
- **"a sufficient amount" / "effective amount"** — outside specific pharma contexts

Not automatically unclear, but require either (a) established meaning in the field (and proof of that), (b) a defined tolerance in the claim itself, or (c) a measurable standard. **Preferred fix**: import the tolerance into the claim, don't rely on the description.

### 4. G 3/14 — clarity is NOT a ground of opposition (mostly)

The Enlarged Board (G 3/14, 24 March 2015): in opposition, claims may be examined for compliance with Art. 84 **only to the extent that the amendment introduces non-compliance**. Pure combinations of granted claims are **immune** to clarity attack.

**Operational consequence**: clarity must be fixed during examination — opposition is not a second chance.

### 5. Description adaptation — controversial, pending G 1/24

EPO examiners routinely require the description to be amended so embodiments outside the claim scope are marked "not according to the invention" or deleted. This is challenged by **T 1989/18** (no adaptation required) but supported by **T 1024/18, T 1473/19, T 1399/17**. **T 56/21** referred the question; **G 1/24** is pending.

**Practitioner posture**: comply with examiner request to obtain grant (path of least resistance); preserve appeal options on strategically important files.

→ Detailed analysis: [F-IV § 4.3](references/epo-guidelines-f-iv.md#f-iv-43--inconsistencies-between-claims-and-description), [case-law § Description Adaptation](references/case-law-clarity.md#inconsistencies-between-claims-and-description--description-adaptation)

---

## EPO Guidelines F-IV — Quick Map (every objection → its section)

The single most useful navigational table in this skill. **Memorise this.**

| Objection / topic | F-IV section | Leading case law |
|---|---|---|
| General clarity test | F-IV-4.1 | T 1018/02 |
| Claim interpretation | F-IV-4.2 | T 56/04 |
| Inconsistency claims ↔ description | F-IV-4.3 | T 1989/18, T 1473/19 |
| "Spirit of the invention" | F-IV-4.4 | F-IV-4.4 itself |
| Essential features missing | F-IV-4.5 | T 0032/82, T 0922/05 |
| Relative terms ("thin", "strong") | F-IV-4.6 | T 1582/08 |
| "Substantially", "about", "approximately" | F-IV-4.6.1 | T 0337/95, T 0860/93 |
| Trademarks | F-IV-4.8 | T 0270/11, T 0480/98 |
| Optional features ("preferably", "such as") | F-IV-4.9 | F-IV-4.9 itself |
| Result to be achieved | F-IV-4.10 | T 0068/85, T 0939/92, T 1173/97 |
| Parameters (standard + unusual) | F-IV-4.11 | T 0094/82, T 0728/98, T 0276/06, T 1845/14 |
| Product-by-process | F-IV-4.12 | T 0150/82, T 0205/83, T 0411/89 |
| "Apparatus for" / "Method for" — intended use | F-IV-4.13 | T 0287/86, T 0401/95 |
| Definition by use / by reference to other entity | F-IV-4.14 | — |
| The expression "in" | F-IV-4.15 | — |
| References to drawings / description (Rule 43(6)) | F-IV-4.16 | — |
| Reference signs (Rule 43(7)) | F-IV-4.17 | — |
| Negative limitations / disclaimers | F-IV-4.18 | G 1/03, G 2/03, G 2/10, G 1/16 |
| Conciseness, number of claims | F-IV-5 | — |
| Support in description (full breadth) | F-IV-6 | T 0409/91, T 0435/91, T 0939/92, T 1727/12 |
| Functional features | F-IV-4.5 + 4.10 | T 0068/85, T 0401/95, T 1067/97 |
| Computer-implemented claims | F-IV-3.9 | T 1173/97, G 3/08 |
| Second medical use (Art. 54(5)) | F-IV-3.8 + G-II-4.2 | G 5/83, G 2/08 |
| Reach-through claims | F-IV-6 + F-III | T 1063/06, T 1329/04 |
| Markush groups | F-IV-3.6 + 4.11 | T 0939/92 |
| Two-part form (Rule 43(1)) | F-IV-3.7 | T 0917/91 |
| Multiple independents same category (Rule 43(2)) | F-IV-3.4 | — |
| Clarity in opposition | D-V-3, H-II-3 | **G 3/14** |
| Incomplete search (Rule 63) | B-VIII | — |

→ Full Guidelines walkthrough: [epo-guidelines-f-iv.md](references/epo-guidelines-f-iv.md)

---

## Quick Index by File

### By article / rule / Guidelines
- **[Article 84 EPC — deep dive](references/article-84-epc.md)** — clarity, conciseness, support, defining function
- **[Article 6 PCT](references/article-6-pct.md)** — clarity at the international stage
- **[Rule 43 EPC + Rule 6 PCT](references/rule-43-epc.md)** — form & content of claims, Rule 63 incomplete search
- **[EPO Guidelines F-IV walkthrough](references/epo-guidelines-f-iv.md)** — section-by-section

### By objection / topic
- **[Catalog of clarity objections](references/clarity-objections-catalog.md)** — every F-IV-4 objection with examples

### By decision
- **[Key case law on clarity](references/case-law-clarity.md)** — G 3/14, G 1/03, G 2/03, G 2/10, G 1/16, G 2/21, T 1989/18, T 1473/19, T 56/21, T 728/98, T 626/14, T 1791/16, T 0068/85, T 0939/92, T 1173/97, T 0094/82

### By workflow
- **[Drafting checklist (prevention)](references/drafting-checklist.md)** — pre-filing audit mapped to F-IV
- **[Response strategies](references/response-strategies.md)** — overcoming examiner objections, cite Guidelines + case law
- **[Related provisions](references/related-provisions.md)** — Art. 83 sufficiency, Art. 123(2) added matter, Art. 69 interpretation
- **[Glossary](references/glossary.md)** — patent terminology (EN + IT)

---

## Common Workflows This Skill Supports

### A. "Audit my draft claim for clarity"
1. Read the claim
2. Apply the **[Drafting Checklist](references/drafting-checklist.md)** (every check maps to a F-IV section)
3. Score against each F-IV-4 objection category
4. Output: clarity report + suggested rewrites, with F-IV references

### B. "Respond to an Art. 84 office action"
1. Classify the objection by the **F-IV section the examiner cited**
2. Look up the matching entry in **[Clarity Objections Catalog](references/clarity-objections-catalog.md)**
3. Choose response from **[Response Strategies](references/response-strategies.md)** (argue, amend, or both)
4. Cite **Guidelines section** + **converging case law** in the response
5. Cross-check Art. 83, Art. 123(2), Art. 123(3)
6. Output: structured response + amendment + auxiliary requests

### C. "Is clarity examinable in opposition?"
1. Apply the **G 3/14** test: were the granted claims combined unchanged, or amended otherwise?
2. Pure combination → Art. 84 NOT examinable
3. Other amendments → Art. 84 examinable, but only for the amendment-introduced issue
4. Output: examinability conclusion + reasoning + citation to G 3/14

### D. "EPC vs PCT clarity — what changes?"
1. Identify procedural stage (PCT Chapter I/II vs EP regional)
2. Apply matching substantive standard (Art. 6 PCT ≈ Art. 84 EPC, same substance)
3. Note consequence differences (ISA written opinion — non-binding — vs EPO refusal)
4. Strategy: draft to EPC standard from the start if EP regional phase is planned

### E. "Description adaptation conflict"
1. Identify Board posture (T 1989/18 vs T 1473/19 split)
2. Reference pending G 1/24
3. Recommend conservative compliance strategy + appeal preservation

### F. "Parameter objection — what now?"
1. Standard or unusual? (F-IV-4.11)
2. Is the measurement method spelled out completely (instrument, conditions, calibration, reproducibility)?
3. Is it consistent with examples in the description?
4. Often paired with Art. 83 (reproducibility across breadth) — address both
5. Output: parameter justification + method specification + supporting examples

---

## Official Sources (always verify against current edition)

- **EPC** — 17th edition (2020): https://www.epo.org/law-practice/legal-texts/epc.html
- **PCT** — Treaty + Regulations: https://www.wipo.int/pct/en/texts/
- **EPO Guidelines for Examination** — March 2024 (updated annually): https://www.epo.org/law-practice/legal-texts/guidelines.html
- **PCT International Search and Preliminary Examination Guidelines** (PCT-ISPE): https://www.wipo.int/pct/en/texts/ispe.html
- **Boards of Appeal decisions database**: https://www.epo.org/en/boards-of-appeal/decisions
- **Case Law of the Boards of Appeal** (CLBA, "White Book"), 10th edition (2022): free PDF on EPO website
- **Official Journal of the EPO (OJ EPO)**: https://www.epo.org/law-practice/legal-texts/official-journal.html

---

## Scope & Limits

This skill covers:
- ✅ Article 84 EPC and Article 6 PCT in depth, grounded in F-IV
- ✅ Rule 43 EPC, Rule 6 PCT, Rule 63 EPC, Rule 137 EPC
- ✅ Related provisions (Art. 83, Art. 123(2), Art. 123(3), Art. 69 EPC)
- ✅ EPO Guidelines Part F Chapter IV section by section
- ✅ Major Enlarged Board and Technical Board decisions on clarity
- ✅ Drafting and response strategies pinned to specific Guidelines sections
- ✅ PCT ↔ EPC procedural differences

This skill does **not** cover (or covers only by reference):
- ❌ Substantive patentability (novelty, inventive step) beyond clarity interaction
- ❌ National court infringement analysis beyond Art. 69 reference
- ❌ Unitary Patent + UPC procedural strategy (specialist domain)
- ❌ Other patent offices' clarity practices (USPTO §112, JPO, CNIPA) beyond brief comparison notes
- ❌ Legal advice on a specific case — always consult a qualified EPA

The references cite official sources (EPC, PCT, EPO Guidelines, OJ EPO) where applicable. Verify against the **current edition**: EPC 17th ed. (2020), Guidelines March 2024 (annual updates), CLBA 10th ed. (2022). Board decisions cited by their official number — always check for subsequent decisions, especially **G 1/24** (pending) on description adaptation.
