# Related Provisions — Art. 83, Art. 123(2), Art. 69

Article 84 EPC does not exist in isolation. It interacts with three other provisions in ways every practitioner must master: **Art. 83** (sufficiency), **Art. 123(2)** (added matter), **Art. 69** (scope of protection). Each interaction is a frequent source of office-action complexity and litigation.

> Article references throughout are to the EPC (17th edition, 2020) and the corresponding Guidelines for Examination (March 2024 edition).

---

## Article 83 EPC — Sufficiency of Disclosure

### Text
> "The European patent application shall **disclose the invention in a manner sufficiently clear and complete for it to be carried out by a person skilled in the art**."

### Standard
The skilled person, with the application as filed plus common general knowledge, must be able to **carry out the invention across the full scope claimed**, without undue burden, by way of routine experimentation.

### Where it overlaps with Art. 84

| Issue | Art. 83 lens | Art. 84 lens |
|---|---|---|
| Broad claim, narrow disclosure | Can the skilled person reproduce across the breadth? | Is the breadth supported by the description? |
| Functional features | Can the function be reproduced? | Is the function clearly defined? |
| Unusual parameters | Is the measurement reproducible? | Is the parameter clear? |
| Result-to-be-achieved | Can the result be reproduced? | Is the result a measurable feature? |
| Reach-through claims | Can the skilled person identify all encompassed compounds? | Is the scope defined? |

**Practitioner rule**: when an objection is about **reproducibility across breadth**, it is properly Art. 83. When it is about **definitional precision**, it is Art. 84. The EPO frequently raises both in the same communication.

### Guidelines: F-III (Sufficiency) and F-IV-6 (Support — the Art. 84 support arm)

### Leading case law
- **T 0409/91** — broad claim, narrow disclosure: both Art. 83 + Art. 84 support
- **T 0435/91** — same
- **T 0939/92** — generic claims with one example
- **T 1329/04** — biotech functional claim insufficient and unsupported
- **T 0727/95** — functional definition needs enabling disclosure
- **G 1/03** point 2.5 — observed the close relationship between Art. 84 support and Art. 83

### Response strategy where both raised
1. Address Art. 83 first (the harder ground; can require fresh examples or compelling reasoning)
2. Art. 84 support typically follows: if you've shown reproducibility across breadth, you've shown support

→ Cross-ref: [response-strategies.md § 2.9 Support](response-strategies.md#29--support--breadth-f-iv-6-art-84-support-arm)

---

## Article 123(2) EPC — Added Matter

### Text
> "The European patent application or European patent may not be **amended in such a way that it contains subject-matter which extends beyond the content of the application as filed**."

### Standard — the "gold standard" (G 2/10)
The skilled person, reading the application as filed, must **directly and unambiguously** derive the amended content from what was disclosed (explicitly or implicitly).

### Why this matters for clarity work

**Every clarity amendment is a potential Art. 123(2) trap**:
- Adding a definition from the description into the claim → must be word-for-word or clearly equivalent
- Replacing "substantially planar" with "planar within 5°" → 5° must be disclosed
- Marking embodiments as "not according to the invention" → may need basis if it changes the disclosure
- Importing a parameter method → method must be in the application as filed

### The Art. 84 ↔ Art. 123(2) triangle

| Movement | Risk |
|---|---|
| Add wording to claim from description | Art. 123(2) if not directly derivable as a feature of the invention |
| Generalise a specific feature | Art. 123(2) — "intermediate generalisation" risk |
| Combine features from different embodiments | Art. 123(2) — must be a disclosed combination |
| Delete a feature | Art. 123(2) if the feature was essential to what was disclosed |
| Add ranges | Art. 123(2) if the specific range wasn't disclosed |

### Leading case law
- **G 2/10** (8 April 2011) — gold standard for disclosed disclaimers
- **G 1/03** + **G 2/03** — undisclosed disclaimers
- **G 1/16** — reaffirms two-standard approach
- **T 0288/92** — disclosure of an intermediate generalisation
- **T 0962/98** — combination of features from different embodiments
- **T 1067/97** — basis for added wording in functional language

### Post-grant: Art. 123(3) — extension of protection

In opposition / limitation, amendments cannot **extend the scope of protection** beyond the granted claim. The "Art. 123(2) / 123(3) trap": an amendment may be the only way to fix Art. 123(2) but extend protection (Art. 123(3)), making both compliance impossible → **patent revoked** (G 1/93).

For clarity work in opposition: prefer **deletion** of feature over modification — deletion cannot extend protection.

→ Cross-ref: [response-strategies.md § 2.8 Description Adaptation](response-strategies.md#28--description-adaptation-embodiments-outside-claim-scope-f-iv-43--current-controversy)

---

## Article 69 EPC — Extent of Protection

### Text
> "The **extent of the protection** conferred by a European patent or a European patent application shall be **determined by the claims**. Nevertheless, the **description and drawings shall be used to interpret the claims**."

Plus the **Protocol on the Interpretation of Article 69**:
- Not strict literal interpretation
- Not extension to what was "contemplated" by the patentee
- Fair protection for the patentee + reasonable certainty for third parties
- Equivalents shall be taken into account

### Where this differs from Art. 84

| Provision | Function | When applied |
|---|---|---|
| Art. 84 | **Defining** clarity for examination | EPO examination / opposition / appeal |
| Art. 69 | **Interpreting** scope for protection | National court infringement / UPC / Boards of Appeal in inter partes scope disputes |

**Critical practitioner point**: an Art. 84 objection cannot be answered by Art. 69 reasoning. "The skilled person reading the description would understand X" does not save an unclear claim from Art. 84. Art. 69 applies to **infringement**, not examination.

But **Art. 69 must be kept in mind during drafting**: a claim drafted to barely survive Art. 84 may be interpreted narrowly under Art. 69, reducing infringement leverage. A claim drafted with both in mind has clear features (Art. 84) **and** clear scope contours (Art. 69).

### Doctrine of equivalents

Each national court interprets the "equivalents" clause of the Protocol differently:
- **UK**: post-Actavis v Eli Lilly (2017) test for equivalents
- **Germany**: Schneidmesser questions
- **Netherlands**: pith and marrow approach
- **France**: equivalents accepted with narrow scope
- **Italy**: doctrine of equivalents recognised
- **UPC**: emerging jurisprudence (verify with current UPC case law)

This skill is not the place for national infringement strategy; for that, consult the [Case Law of the Boards of Appeal](https://www.epo.org/law-practice/case-law-appeals.html) for EPO-level guidance and national-court practice resources.

---

## Article 82 EPC — Unity of Invention (brief)

Although not a clarity provision, **lack of unity** sometimes interacts with clarity:
- If a claim is so unclear that the unity examination cannot be performed, the search may be partial (Rule 63 EPC, Guidelines B-VIII).
- Multiple independent claims of the same category (Rule 43(2)) — if not justified, may attract both a unity objection AND a clarity objection on the multiplicity.

---

## Article 54(5) EPC — Second Medical Use (clarity dimension)

For "X for use in the treatment of Y" claims:
- The therapeutic indication must be **specific** — not "treatment of cancer" but "treatment of breast cancer" or even narrower
- The dosage regimen may need to be in the claim if novelty rests on it (per G 2/08)
- Lack of specificity → clarity objection plus often Art. 83 sufficiency

→ Cross-ref: [clarity-objections-catalog.md § 18](clarity-objections-catalog.md#18-second-medical-use-claims)

---

## Practitioner Master-Diagram (decision pathway)

When an objection arrives, route it through this decision tree:

```
Is the objection about… ?
├── Reproducibility of the invention → Art. 83 (sufficiency)
├── Definitional precision of the claim → Art. 84 clarity
├── Match between claim breadth and disclosure → Art. 84 support OR Art. 83 (often both)
├── Whether the amendment adds matter → Art. 123(2)
├── Whether the amendment extends scope post-grant → Art. 123(3)
└── How a competitor's product is interpreted under the claim → Art. 69 (national court, not EPO examination)
```

Treat each as a separate analysis even when the examiner raises them together. Cross-check that your response to one doesn't make another worse.

---

## The Art. 84 / 83 / 123(2) "Triangle of Doom"

A classic prosecution trap:
1. **Original claim** is unclear (Art. 84)
2. **Amendment** clarifies it → but the wording is not in the application as filed (Art. 123(2))
3. **Forced** to keep original wording → Art. 84 stands
4. **Alternative amendment** uses different wording → may not be clear (Art. 84 again)

**Prevention** (most important practitioner discipline):
- At drafting: include multiple terminologies for each concept in the description
- At drafting: include clear definitions of every parameter or unusual term
- At drafting: include intermediate ranges and sub-ranges
- At drafting: include explicit feature combinations
- At amendment: always have the application as filed open and search for the exact wording

---

## See Also

- [Article 84 EPC](article-84-epc.md)
- [Clarity Objections Catalog](clarity-objections-catalog.md)
- [Response Strategies](response-strategies.md)
- [Case Law on Clarity](case-law-clarity.md)
- [EPO Guidelines F-IV](epo-guidelines-f-iv.md)
