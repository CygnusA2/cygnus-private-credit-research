# Why Correct Financial Arithmetic Is Not Enough
*Cygnus Financial AI Research · November 2026 · Model reliability primer*

An AI model can calculate a payment correctly and still produce a response that is unusable in a private-credit workflow. The converse is also possible: a perfectly formatted output can contain a financially unsupported assertion.

Consider a hypothetical task asking for a collateral-related amount. A reliable response requires several checks:

- **Calculation:** The formula, values, rounding and monetary unit must be correct.
- **Source:** The inputs used in that calculation must be supported by the supplied evidence.
- **Meaning:** The result must answer the requested financial question, not a similar one.
- **Representation:** The response must use the declared claim identifiers and format.
- **Safety:** If a material input is contradictory, missing or ambiguous, the system must not fabricate certainty.

## Five independent model outcomes worth reporting

A useful evaluation should distinguish: correct and supported results; numerical errors; schema or formatting failures; unsupported claims; and justified abstentions. Cases where the model runs out of output allowance should be counted as incomplete, not quietly excluded.

## Ambiguity is a financial concern

A numeric string such as `3.500` can have different interpretations depending on the decimal convention. A system should not invent an interpretation merely because it can output a number. A declared numeric convention, source context and deterministic validation may be needed before a financial amount is treated as supported.

## Model assistance is not automated credit approval

Structured models may help retrieve, compare and explain financial evidence, but this does not establish that a system can issue safe loans, assess legal enforceability, or replace a professional credit committee.

**Scope:** General educational discussion with hypothetical examples. No results, proprietary benchmarks, financial thresholds or confidential experimental methods are disclosed.
