# Article 84 EPC — Deep Dive

## Text

> **Article 84 — Claims**
>
> The claims shall **define the matter** for which protection is sought. They shall be **clear and concise** and be **supported by the description**.

(EPC, 17th edition, 2020)

## Structural Reading

Article 84 imposes four interlocking requirements:

| Requirement | Operative test |
|---|---|
| **Defining function** | The claim must consist of **features**, not aspirations, problems, or effects |
| **Clarity** | The skilled person must know the scope from the claim alone |
| **Conciseness** | No unnecessary repetition; reasonable number of claims |
| **Support** | The full claim breadth must be commensurate with the description |

Each is independently violable. An objection may attack any one or several.

---

## 1. The Defining Function

The claim must **define the matter for which protection is sought**. This rules out:

- **Problem statements** in the claim ("A device for solving the problem of …" — the problem is not a feature)
- **Pure effects** without structural / functional features ("A composition having anti-bacterial effect" — fine only if the effect can be tied to a measurable, reproducible feature)
- **Statements of intention** ("intended to be used for …" — see Rule 43(1) on use claims)
- **"Spirit of the invention"** wording in the body of the claim (EPO Guidelines F-IV-4.10)

What it permits (and indeed requires):
- **Structural features** (a physical part, a chemical compound)
- **Functional features** when structural definition is genuinely impractical (see §5 below)
- **Process steps** in method claims
- **Use claims** for second medical use, Swiss-form having been replaced by EPC 2000 format (Art. 54(5) EPC)

---

## 2. Clarity (the heart of Art. 84)

### 2.1 Test

> Can the skilled person, reading the claim and applying their common general knowledge as of the filing date, determine **which embodiments fall within the scope and which do not**?

If yes → clear. If no → unclear.

### 2.2 The "claim stands alone" doctrine

For Art. 84 clarity examination, the claim is read **without recourse to the description** to resolve ambiguity. This is **different** from Art. 69 interpretation (used for infringement), which expressly uses the description and drawings.

**Exception to "stands alone"**: where a term has a special meaning explicitly defined in the description, and the claim uses that term consistently, the definition can be considered. But practitioners should **bring the definition into the claim** rather than rely on the description.

### 2.3 Categories of unclear language (cross-ref: clarity-objections-catalog.md)

1. **Relative / vague terms** ("substantially", "about", "approximately", "thin", "strong")
2. **Result to be achieved** (an effect described instead of features producing it)
3. **Parameters** — unusual, multi-step, or unmeasurable parameters
4. **Functional features** — when a structural definition is reasonably available
5. **Trademarks** — fluid product identity over time
6. **Optional features in the body** ("preferably", "such as", "for example" within a claim)
7. **References to external documents** ("according to standard ISO XXXX") — outdated standards drift
8. **"Spirit of the invention" / "the invention"** language
9. **Inconsistencies** between independent claim and dependent claims, or between claims and description

### 2.4 The "essential feature" test (a clarity flavour)

Per the EPO Guidelines F-IV-4.5: an independent claim must contain **all features essential** to defining the invention. Omission of an essential feature → clarity objection under Art. 84, even if every word in the claim is itself clear.

> Example: claim to "A laser cutter" without any laser feature → unclear because the essential feature is missing, even though each word is clear.

### 2.5 Categories of products and processes — special clarity rules

- **Product-by-process** claims (Rule 43(3); Guidelines F-IV-4.12) — the product must be definable independently; the process is only acceptable if no other definition is possible. The product's **structural identity** is what is claimed, not the process.
- **Use claims** — Rule 43(2)(d); second medical use under Art. 54(5)
- **Reach-through claims** — claiming compounds defined only by an unrelated biological target → typically refused as unclear and as lacking support

---

## 3. Conciseness

### 3.1 Scope of the requirement

Conciseness applies to **both**:
- **Per claim** — no unnecessary repetition of features within a single claim
- **Set of claims** — no unnecessary multiplicity of claims covering the same subject-matter

EPO practice tolerates a reasonable number of claims (no fixed upper limit), but:
- Multiple **independent claims of the same category** are restricted by Rule 43(2) EPC (a/b/c exceptions)
- Excess claims attract claims fees beyond 15 (Rule 45 EPC)

### 3.2 Objection patterns

- **Repetition of subject-matter** across independent claims
- **Catalog-style alternatives** ("wherein X is selected from A, B, C, D, … [hundreds]" without functional rationale)
- **Markush groups** that are excessive in scope without commensurate support
- **Cascade of trivial dependent claims** (claims merely restating preferred ranges with no inventive value)

### 3.3 Distinguishing conciseness from added matter

Cutting down claims for conciseness can risk **added matter (Art. 123(2) EPC)** if the deleted matter would otherwise have supported an interpretation. Conversely, adding language for clarity can also breach Art. 123(2). The triangle conciseness ↔ clarity ↔ added matter is one of the most delicate during prosecution.

---

## 4. Support by the Description

### 4.1 The doctrine

The claims must be **supported** by the description. The full **breadth** of the claim must correspond to what the description **actually discloses** and **enables**.

This is the EPC analogue of "claim scope ≤ disclosure scope":
- A claim covering "any pharmaceutical composition that lowers blood pressure" but described by only two specific compounds is **not supported**.
- A claim covering "a process at any temperature" but with examples only at 80–100 °C may be unsupported.

### 4.2 Support vs sufficiency (Art. 83) — frequently confused

| Doctrine | Question |
|---|---|
| **Art. 84 support** | Does the **description** carry the **full claim breadth**? |
| **Art. 83 sufficiency** | Can the **skilled person** carry out the invention **across the full claim scope** without undue burden? |

In practice they overlap heavily, especially in chemistry and biotech. The EPO often refers to a combined "Art. 83/84" objection where the claim is broader than the disclosure can support **and** the skilled person cannot extrapolate.

**Boards of Appeal trend**: where the objection is really about reproducibility across breadth, it is often correctly framed as **Art. 83** (sufficiency). Pure Art. 84 support is about the **textual match** between claim and description.

### 4.3 Selection inventions

A claim selecting a sub-range from a broader disclosed range raises support questions:
- Is the sub-range disclosed (literally or by clear implication)?
- Is it justified by a technical effect (which engages inventive step, but also support)?

### 4.4 Support and broadening during prosecution

If during examination the claim is **broadened** (e.g. removing a feature), support must still cover the broadened scope. A common pitfall: adding a dependent claim's optional feature into the description, then later trying to broaden the main claim by removing that feature — Art. 123(2) catches this even if clarity does not.

---

## 5. Functional Features (a special case touching all four requirements)

A claim can use functional language ("means for X-ing", "configured to do Y") **only if**:

1. **A structural definition is not reasonably possible** (otherwise the claim is too broad)
2. **The function is reproducibly performable** by the skilled person
3. **The claim is not a "wish list"** of desired effects

**T 68/85** and successors established that purely functional claims are allowed when the function can be clearly understood and reproduced. **T 728/98** sharpens this for parameter-based functional definitions.

**Drafting practice**: pair the functional feature with structural anchors in the dependent claims and description, so the support is unambiguous.

---

## 6. Interaction with Other Provisions

| Provision | Interaction |
|---|---|
| **Art. 54 (novelty)** | If the claim is unclear, novelty cannot be properly assessed — examiner may raise both |
| **Art. 56 (inventive step)** | Vague claim scope can mask non-obviousness; correctness of problem-solution analysis depends on a clear claim |
| **Art. 83 (sufficiency)** | Often overlaps with support; see §4.2 |
| **Art. 123(2) (added matter)** | Amendments to fix Art. 84 frequently risk Art. 123(2) |
| **Art. 123(3) (post-grant scope)** | Amendments in opposition cannot extend protection; clarity fixes by deletion are usually safe |
| **Art. 69 (scope of protection)** | Used for infringement, not Art. 84 examination — but a claim drafted with Art. 69 in mind also tends to be clearer |
| **Rule 43 (claim form)** | Rule 43 prescribes the **form**; Art. 84 the **substance** |

---

## 7. Practitioner Take-Aways

1. **Treat clarity as a binary at filing** — if you can't yourself state precisely what falls in and out, the examiner won't accept it
2. **Bring definitions into the claim**, not into the description — relying on description for disambiguation is fragile
3. **Functional language is acceptable but only where structural language is genuinely insufficient** — don't reach for "configured to" by default
4. **Conciseness is enforced softly but persistently** — clean drafting at filing avoids dozen-page Markush horror at examination
5. **Support and sufficiency travel together** — broad claims need broad disclosure plus broad enablement
6. **Every clarity fix is a potential added-matter trap** — plan amendments around basis in the application as filed
7. **Anticipate G 3/14** — clarity must be fixed during examination, you don't get a second chance in opposition

---

## See Also

- [Article 6 PCT](article-6-pct.md) — international parallel
- [Rule 43 EPC](rule-43-epc.md) — claim form
- [Clarity Objections Catalog](clarity-objections-catalog.md) — every objection type by name
- [Case Law on Clarity](case-law-clarity.md) — G 3/14 and the major Board decisions
- [Drafting Checklist](drafting-checklist.md) — preventive audit
- [Related Provisions](related-provisions.md) — Art. 83, 123(2), 69
