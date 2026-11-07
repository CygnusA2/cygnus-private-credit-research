# Public Model Research Standards

## 1. Distinguish study types
- **Research agenda / educational brief:** conceptual, with no empirical performance claim.
- **Exploratory measurement:** small or selected data; describe observed counts and limits, not general superiority.
- **Comparative evaluation:** prespecified paired tasks with model/config parity, complete failure accounting and uncertainty.
- **Production validation:** requires real-world and operational assessment beyond synthetic benchmarking.

## 2. Minimum information for a public measurement
Model provider, exact endpoint/model ID, model revision if available, date of testing, scope and rights of tested inputs, case selection, sample size, number of independent units, input/output settings, rubric, measured denominators, invalid/unsafe counts, latency statistics, rate source, usage/billing distinction, confidence/uncertainty and limitations.

## 3. Evaluation dimensions
Report separately: numerical accuracy; source-supported assertions; contradictions and abstention; safety violations; response schema validity; errors/timeouts/cutoffs; latency; reasoning/output token usage; and cost.

## 4. Data integrity
Never change historical answers after seeing model outputs without creating a separately versioned study. Do not tune prompts on a held-out set and still call it independent. Do not hide failures or treat a grader's label as independently adjudicated financial truth when the oracle is disputed.

## 5. Public release firewall
Only independently reviewable and explicitly authorized results may be released. No private TCIB/FIP assets, raw reasoning logs, customer/provider-restricted records, unpublished scores, prompts, safeguards or research receipts.

## 6. Corrections
Each meaningful correction should include date, prior wording and justification. Avoid silent replacement of published substantive claims.
