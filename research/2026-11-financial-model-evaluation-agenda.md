# What Makes a Financial AI Model Trustworthy?
*Cygnus Financial AI Research · November 2026 · Public research agenda*

A model used to assist private-credit analysis may need to read financial documents, calculate monetary amounts and explain where each supported assertion came from. These are distinct capabilities.

Our public research agenda focuses on six questions:

1. **Numerical reasoning:** Does the model calculate interest, payments, balances, debt coverage or leverage accurately under explicit units, formulas and rounding rules?
2. **Evidence provenance:** Can every material output be traced to relevant inputs, rather than to an unsupported inference?
3. **Contradictory evidence:** Does the model recognize when two relevant sources disagree and avoid pretending the conflict has been resolved?
4. **Missing versus malformed evidence:** Can it distinguish an absent value from an incorrectly formatted, ambiguous or unusable one?
5. **Structured output reliability:** Does it deliver a valid and semantically correct response contract, not just plausible prose or parseable JSON?
6. **Operational efficiency:** How do reasoning-token consumption, completion rate, latency and cost affect practical system design?

## How findings should be evaluated

A credible study should identify tested model versions, input formats, scenario selection, statistical units, success criteria, invalid outputs, refusals, operational errors, and cost basis. Where claims depend on model sampling, uncertainty and limitations must be disclosed. Synthetic scenarios do not establish performance on actual credit portfolios.

A model may produce the correct number yet fail the required output contract. Conversely, it may produce clean JSON that expresses a claim unsupported by the evidence. Both outcomes matter and should be reported separately.

## Research governance

Experiments must not reveal client data, licensed third-party records, private model prompts, scoring algorithms or security controls. Claims of superior performance require appropriately designed comparisons, not isolated demonstrations or selectively chosen examples.

**Status:** This document announces research questions and standards. It does **not** disclose live model results or claim an achieved level of financial reliability.

This material is educational research, not lending or investment advice.
