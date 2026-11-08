# LOOPCHii Twin Examination Protocol

Version 0.1 research proposal

A model can fit the setting where it was studied and fail somewhere else. Suppose a digital twin was tested indoors and is now proposed for use outdoors during a heat event. What evidence supports that particular change in context? Who bears the consequence if the model is wrong? Who can reopen the decision?

LOOPCHii proposes a portable evidence record for those questions. The record describes one claimed use and gives an independent reviewer a way to request evidence, hold a finding for review, and see when it needs to be reconsidered.

## Ten disclosures

1. **Context of use.** State the intended decision, population, environment, and time horizon together. Identify each studied combination and the evidence for use in another setting.
2. **Provenance.** Identify the model version, input sources, assumptions, and the people or systems that can act on its output.
3. **Decision uncertainty.** Describe what an error could do to each affected party. Give the evidence for that estimate and name what remains uncertain.
4. **Staleness.** Record when the evidence was reviewed, which state it described, and which changes or dates trigger a recheck.
5. **Circularity.** Show whether earlier model outputs influenced the records later used to evaluate or train the model.
6. **Reversibility.** State who can correct or reverse an affected decision, under what conditions, and within what time.
7. **Contest path.** Give an affected person a way to obtain the decision record and reach someone who can reopen it. Where available, report how often reviews led to corrections and what was counted.
8. **Tail behavior.** Describe tested edge cases, relevant groups with sparse evidence, and known failures.
9. **Evidence boundary.** Link each supported claim to its source and version. List unsupported claims explicitly.
10. **Dependencies.** Identify which downstream decisions and records need review if the finding changes.

A change in prediction after a context shift is a measured difference. An unchanged prediction can also be appropriate. An examiner considers the expected response, the evidence for it, and the specific decision before interpreting either result. A provenance path can show a reason to investigate feedback. Establishing what caused an outcome takes separate evidence.

This is a research proposal. It carries no clinical decision authority, certification, or regulatory endorsement.
