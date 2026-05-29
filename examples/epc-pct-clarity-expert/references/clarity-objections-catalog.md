# Catalog of Clarity Objections

Each entry: **What it is → Why it's objected → How EPO handles it → How to fix → Cross-references**

The catalog follows the structure of **EPO Guidelines F-IV** (Examination of Clarity), updated through the 2024 edition. Where Boards of Appeal case law refines or contradicts the Guidelines, the case law prevails.

---

## 1. Relative & Vague Terms

### "substantially", "about", "approximately", "essentially"

**What it is**: linguistic softeners attached to a parameter or feature.

**Why objected**: the boundary between in-scope and out-of-scope embodiments is undefined.

**EPO position**: Guidelines F-IV-4.6.1 — accepted if (a) the field has an established convention, (b) the description gives a clear definition, or (c) the term is unavoidable and does not impair clarity in context.

**Fix**:
- Replace with a numeric tolerance ("±5%", "within 10%")
- Define the term in the claim ("substantially means within 10 vol%")
- Delete it entirely if the parameter alone is meaningful

**Case law**: T 728/98 (parameter functional definition), T 860/93, T 337/95 (approximately).

---

### "thin", "thick", "strong", "weak", "small", "large", "high", "low"

**What it is**: comparative adjectives without a reference frame.

**Why objected**: the comparison anchor is missing — thin compared to what?

**EPO position**: Guidelines F-IV-4.6 — these terms must have a meaning that "in the relevant art is sufficiently well established".

**Fix**:
- Replace with numeric range ("thickness 0.5–2.0 mm")
- Reference an industry standard (with care — see §7 below)
- Recast as functional ("of a thickness sufficient to withstand pressure P", **only** if function is well-defined and reproducible)

---

### "preferably", "such as", "for example", "in particular"

**What it is**: optional or exemplifying language inside the body of a claim.

**Why objected**: it introduces uncertainty as to whether the feature is required.

**EPO position**: Guidelines F-IV-4.9 — strongly discouraged in the body of a claim. Acceptable in the description, but in the claim it makes the scope ambiguous.

**Fix**:
- Delete the optional language; the broader claim already covers the example
- Or move the optional embodiment to a dependent claim

---

## 2. Result to Be Achieved

**What it is**: a claim defining the invention by the **effect** sought rather than by features producing it. Example: "A composition that lowers blood pressure" or "A method that improves engine efficiency by at least 5%".

**Why objected**: the claim covers any means of achieving the result, including means not disclosed and not enabled — uncontrollable scope.

**EPO position**: Guidelines F-IV-4.10 — **objectionable** unless the result-style wording is the only practical way to define the invention **and** the result is measurable and reproducible.

**Fix**:
- Add the structural / process features producing the result
- If genuinely characterised by effect, give a measurable test (method, conditions, threshold)
- Consider whether this is also an Art. 83 sufficiency problem (often is)

**Case law**: T 68/85, T 1173/97 (computer programs), T 939/92.

---

## 3. Parameters

### Unusual parameters

**What it is**: a parameter not commonly used in the field, or constructed for the invention.

**Why objected**: prior-art search is impeded; novelty becomes nearly unfalsifiable.

**EPO position**: Guidelines F-IV-4.11 — the claim may be objected to under Art. 84 **and** novelty effectively cannot be assessed. The applicant must justify the parameter and provide a clear method of measurement.

**Fix**:
- Convert to a standard parameter where possible
- Provide a complete measurement protocol (method, conditions, equipment, reproducibility)
- Be aware: the EPO may also raise an Art. 83 sufficiency objection

**Case law**: **T 0094/82**, **T 728/98**, T 0276/06, T 1845/14.

### Multi-step / derived parameters

**What it is**: a parameter requiring several intermediate calculations or measurements, possibly with implicit choices (e.g. specific instrument calibrations).

**Why objected**: different reasonable interpretations lead to different values.

**Fix**: spell out every step, every instrument, every condition. If the parameter can yield different values depending on choices, fix the choices in the claim.

---

## 4. Functional Features

**What it is**: features defined by what they **do** rather than what they **are** ("means for X-ing", "configured to perform Y").

**Why objected**: open-ended scope; may cover not-yet-invented means.

**EPO position**: Guidelines F-IV-4.5 — permitted only where (a) a structural definition is not reasonably possible, (b) the function is clearly defined, and (c) the skilled person can readily identify means performing the function without inventive effort.

**Fix**:
- Pair the function with at least one structural anchor in the independent claim ("a heating element configured to …")
- Provide multiple structural embodiments in the description
- Avoid pure means-plus-function unless field convention supports it (electronics: gentler treatment; mechanical: stricter)

**Case law**: T 68/85, T 401/95, T 1067/97, T 728/98.

---

## 5. Trademarks

**What it is**: a feature defined by reference to a commercial product name (e.g. "Teflon®").

**Why objected**: the chemical/physical content of a trademarked product can change over time without notice; the claim scope drifts.

**EPO position**: Guidelines F-IV-4.8 — trademarks are **discouraged**. If used, the trademark must denote a product with consistent, well-defined composition; the description must spell out the relevant properties.

**Fix**:
- Replace with the chemical name or the relevant physical property
- If the trademark is unavoidable (truly known by no other name), define the composition in the claim

---

## 6. Optional Features in the Claim Body

**What it is**: language like "and optionally further comprising X", "optionally heated to Y°C".

**Why objected**: the claim is read both with and without the optional feature; scope is technically the same as the broader claim, so the language is at best redundant (conciseness) and at worst unclear.

**EPO position**: Guidelines F-IV-4.9 — **delete** optional language. The broader claim already covers the embodiment without the optional feature. The narrower embodiment with the optional feature belongs in a dependent claim.

**Fix**: split into independent + dependent claims.

---

## 7. References to External Documents / Standards

**What it is**: claim referring to "ISO 9001", "DIN 4768", "ASTM D-1234" or to an internal cross-reference to "Figure 3 of the description".

**Why objected**:
- External standards change over time → scope drift
- Internal references to drawings/description breach Rule 43(6) EPC ("claims shall not, except where absolutely necessary, rely on references to the description or drawings")

**EPO position**:
- Standards: permitted only if (a) the standard is referenced with edition/date, (b) it is publicly accessible at the priority date, and (c) it is necessary
- Internal references: only where the technical feature cannot be defined verbally otherwise (e.g. complex geometry shown in a drawing)

**Fix**:
- Cite standards with version: "according to ISO 9001:2015"
- Avoid "see figure 3" — convert the geometric content into claim language or recite the measurement method

---

## 8. "Spirit of the Invention" / "the Invention" wording

**What it is**: claim contains language like "wherein, in the spirit of the invention", or independent claim says "the invention provides …".

**Why objected**: doesn't define a feature; circular.

**EPO position**: Guidelines F-IV-4.10 — disallowed.

**Fix**: rewrite around the actual features. Reserve "the invention" for the description.

---

## 9. Disclaimers

**What it is**: a negative limitation excluding subject-matter from a claim ("wherein X is not …").

**Why objected**: disclaimers can be unclear about what is excluded; they can also breach Art. 123(2) if not disclosed.

**EPO position**: Two types:
- **Disclosed disclaimers** — based on a positively disclosed embodiment; generally OK
- **Undisclosed disclaimers** — added during prosecution to restore novelty over accidental anticipation, or to disclaim Art. 53/54(3) subject-matter; permitted only under strict conditions per **G 1/03** and **G 2/03** (Enlarged Board, 2004) as refined by **G 1/16** (2017)

**Clarity dimension**: the disclaimer must be clear in its boundary. Vague disclaimers ("excluding any embodiment that …") attract objection.

**Case law**: G 1/03, G 2/03, G 2/10, G 1/16.

---

## 10. Reference Signs

**What it is**: numbers in parentheses in the claim, like "a piston (12)".

**EPO position**: Required by Rule 43(7) EPC where drawings exist. **Reference signs do not limit the claim** (Rule 43(7), final sentence) — they are aids to reading.

**Practitioner note**: not a clarity issue per se. Pitfall: if reference signs are missing where Rule 43(7) requires them, the EPO issues a formalities objection.

---

## 11. Inconsistencies

**What it is**: contradiction or mismatch between (a) independent and dependent claim, (b) claims and description, (c) different parts of the description.

**Why objected**: the skilled person cannot reconcile the conflicting versions.

**EPO position**: Guidelines F-IV-4.3 — objection raised; description amendment usually required (and see the **description-adaptation controversy** in case-law-clarity.md).

**Fix**:
- Align dependent claims with independent claim language
- Update description: mark out-of-claim embodiments as "not according to the invention" (subject to current case law on this — see T 1989/18 / T 1473/19 / T 56/21)

---

## 12. Open-Ended Ranges

**What it is**: "at least 5%", "at most 10°C", "greater than 100 °C".

**EPO position**: Acceptable per se, but:
- Open-ended ranges in chemistry / pharma frequently raise **support** issues (Art. 84) and **sufficiency** issues (Art. 83) because the disclosure rarely supports the full open-ended scope
- "At least 5%" extending to 100% must be enabled and supported across that range

**Fix**: bound the range where technically meaningful ("between 5% and 50%").

---

## 13. Product-by-Process Claims

**What it is**: defining a product by the process used to make it ("a polymer obtained by process X").

**EPO position**: Guidelines F-IV-4.12 — admissible only if the product cannot be defined otherwise. The product, **not the process**, is what is claimed (the product must be novel, not the process).

**Clarity issue**: if the product is structurally indistinguishable from a known product, the claim lacks novelty regardless of the process. Conversely, "obtained by" vs "obtainable by" — the EPO equates these for novelty; both mean the product itself must be novel.

**Case law**: T 150/82, T 205/83, T 219/83.

---

## 14. Reach-Through Claims

**What it is**: claiming compounds defined only by their interaction with an unrelated target (e.g. "any compound that inhibits enzyme X").

**EPO position**: typically refused under both **Art. 84** (support) and **Art. 83** (sufficiency) — the disclosure does not enable the skilled person to identify all such compounds.

**Case law**: T 1063/06, T 0939/92, T 1329/04 (these are biotech-specific).

---

## 15. Two-Part Form

**What it is**: claim in "characterised in that" form per Rule 43(1)(a-b) EPC: preamble (known features) + characterising portion (new features).

**Clarity dimension**: not directly clarity but procedural. Two-part form is preferred where appropriate (Rule 43(1)). If the preamble misallocates known/new features, the examiner may object.

**Fix**: confirm which features are truly in the closest prior art; do not put genuinely novel features in the preamble.

---

## 16. Markush Groups

**What it is**: a single claim defining alternatives sharing a common structural element (typical in chemistry).

**EPO position**: Permitted under Rule 6.5 PCT / EPO practice if (a) the alternatives share a common structural or functional property, (b) the alternatives are of a similar nature, (c) the group is concise and reasonable.

**Clarity issue**: excessive Markush groups (thousands of compounds) attract Art. 84 conciseness and Art. 83 sufficiency objections.

**Fix**: limit the group to alternatives genuinely supported and enabled by the description.

---

## 17. Computer-Implemented Inventions (CII) — special clarity notes

For CII claims, common clarity pitfalls:
- Claiming "a computer program" without effect (also engages Art. 52 patentable subject-matter)
- Claiming "configured to" without specifying technical effect
- Mixing apparatus and method language

**EPO position**: Guidelines F-IV-3.9, G-II-3.6; case law **T 1173/97**, **G 3/08**.

**Fix**: pair functional language with technical effect; choose category cleanly (apparatus / method / program product per Rule 43(2)(c) EPC).

---

## 18. Second Medical Use Claims

**What it is**: claims to a known substance for a new therapeutic indication.

**EPC 2000 form**: "Substance X for use in the treatment of disease Y" (Art. 54(5) EPC).

**Clarity dimension**: the therapeutic indication must be specific and supported. Vague indications ("for treating a disease") fail clarity.

**Case law**: G 5/83 (Swiss-form, historic), G 2/08 (post-EPC 2000 form).

---

## See Also

- [Article 84 EPC deep dive](article-84-epc.md)
- [Case law on clarity](case-law-clarity.md)
- [Response strategies](response-strategies.md)
- [Drafting checklist](drafting-checklist.md)
- [Related provisions — Art. 83, 123(2), 69](related-provisions.md)
