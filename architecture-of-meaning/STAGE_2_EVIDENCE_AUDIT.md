# Stage 2 — Evidence and Provenance Audit

Status: **initiated; evidence review pending**.

## Baseline
- Canonical Research Atlas v2: **85 nodes, 409 edges**.
- Eight edge types: AXIS, STORY, PROBLEM, COMPARISON, CONTEXT, INTERPRETATION, TYPOLOGY, ANALOGY.
- **409/409 edges currently carry confidence = unverified.** This is not a verdict that all are false; it means the current reconstructed ledger does not supply edge-specific independently checked evidence.
- Structural integrity is distinct from factual, textual, philosophical, and historical validity.
- The 100-node extension remains separate from this canonical registry.

## Review protocol
For each edge, retain its ID and original labels. Record:
1. **Claim**: the exact relationship asserted, avoiding stronger claims than the ledger makes.
2. **Source provenance**: original Atlas ledger entry and any cited primary/secondary source.
3. **Primary text**: precise passage/edition/translation, where applicable.
4. **Source support**: direct / contextual / disputed / absent / not yet examined.
5. **Interpretation**: distinguish the text's wording from scholarly inference.
6. **Alternative readings**: plausible competing interpretations and their sources.
7. **Confidence**: high / medium / low / unverified, with a written justification.
8. **Evidence class**: textual observation / historical claim / philosophical argument / psychological interpretation / metaphysical analogy / scientific hypothesis.
9. **Review state**: not started / in progress / supported / disputed / insufficient evidence.
10. **Reviewer notes**: unresolved questions, citation gaps, and proposed follow-up.

## Safeguards
- Never mark a link verified solely because the JSON is structurally valid or the Research Atlas mentions it.
- Never turn an analogy into empirical evidence.
- Preserve all original records; add review annotations in separate files.
- Maintain version history and distinguish original from derived annotations.
- Do not start theological debate interpretation until the user explicitly authorizes that analysis.

## Immediate deliverables
- A machine-readable 409-row review ledger.
- A reproducible QA script to validate IDs, endpoints, and review coverage.
- A dashboard that distinguishes graph structure from evidence completeness.
- Source-by-source citation checks, followed by interpretive assessment.

## Stage 2 completion criteria
Every edge reviewed, every claim classified, every citation independently checked where obtainable, and unresolved items explicitly listed. No blanket verification by assumption.
