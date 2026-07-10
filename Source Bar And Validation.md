Use this reference for source quality, traceability, and adversarial checks.
Source Bar
Classify every important source by credibility. Source count is not research quality.
Tier	Source type	Use it for	Caution
T1	First-party sources: pricing pages, financial reports, official databases, product docs, repo data	Pricing, official metrics, product behavior, financial facts	Still check date, scope, and definition
T2	Named research institutions: consulting firms, research firms, industry associations, government/statistical sources	Market size, adoption, benchmark ranges, industry structure	Watch sponsored framing and methodology
T3	Practitioner originals: founder interviews, operator posts, user forums, expert talks, customer reviews	User pain, workflow reality, adoption friction, insider language	Anecdotal unless triangulated
T4	Aggregated or reposted content: media roundups, content aggregators, secondary summaries	Context and lead generation	Do not use stacked URLs to fake depth

Rules:
Pricing data accepts only T1 when possible.
Market-size claims require at least T2 or explicit judgment-call labeling.
User pain must include T3 practitioner or real user language when possible.
Heavy assumptions require two-source verification or a visible "Judgment Call" label.
If a source is stale, say so.
Skeptical Verification
The verifier does not support the conclusion. It tries to overturn it.
Check:
duplicate counting;
unit mismatch;
denominator mismatch;
inconsistent geography or time period;
optimistic conversion rates;
unsupported margin or payback assumptions;
market-size leap from broad category to narrow wedge;
source circularity, where multiple articles cite the same original number;
headline/body mismatch;
$0 executive summary mismatch against decision pages.
Calculation Standards
For every key metric, keep:
formula;
input values;
units;
source IDs;
assumption labels;
result;
sensitivity or range when uncertainty matters;
verification status.
Core metrics to recalculate:
TAM, SAM, SOM;
pricing and ARPU;
gross margin;
CAC/payback if available;
conversion rate;
retention or repeat rate;
ROI or productivity gain;
market share and penetration assumptions.
Verification Output
When producing files, write a separate verification artifact or section:
{
  "checks": [
    {
      "id": "check-001",
      "metric_or_claim": "SOM revenue",
      "status": "pass | fail | caution",
      "issue": "unit mismatch, duplicate count, or unsupported assumption",
      "fix": "what changed",
      "source_ids": ["S1", "S2"]
    }
  ]
}
Do not hide failed checks. If the output still proceeds, label the risk.
