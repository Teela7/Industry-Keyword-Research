Research Data Schema
Use a structured data artifact when creating a repeatable report, deck, or audit trail. The usual
filename is data.json, but any explicit equivalent is acceptable.
Purpose
The data artifact is the single source of truth. The report and deck should render from it so that
changing facts, calculations, or sources can regenerate the output.
Minimal Schema
{
  "brief": {
    "topic": "",
    "geography": "",
    "time_horizon": "",
    "audience": "",
    "day_1_answer": "",
    "current_answer": ""
  },
  "sources": [
    {
      "id": "S1",
      "tier": "T1 | T2 | T3 | T4",
      "title": "",
      "publisher": "",
      "date": "",
      "url": "",
      "used_for": "",
      "notes": ""
    }
  ],
  "keywords": [
    {
      "id": "K001",
      "category": "",
      "relationship_strength": "strong | medium | weak-emerging",
      "term": "",
      "definition": "",
      "why_it_matters": "",
      "source_ids": ["S1"]
    }
  ],
  "claims": [
    {
      "id": "C1",
      "claim": "",
      "type": "fact | inference | judgment_call",
      "source_ids": ["S1"],
      "confidence": "high | medium | low",
      "caveat": ""
    }
  ],
  "assumptions": [
    {
      "id": "A1",
      "statement": "",
      "value": "",
      "unit": "",
      "basis": "source_backed | judgment_call",
      "source_ids": ["S1"],
      "sensitivity": ""
    }
  ],
  "calculations": [
    {
      "id": "CALC1",
      "metric": "",
      "formula": "",
      "inputs": [],
      "result": "",
      "unit": "",
      "source_ids": ["S1"],
      "verification_status": "pending | pass | caution | fail"
    }
  ],
  "storyline": {
    "governing_thought": "",
    "pillars": [],
    "action_titles": []
  },
  "verification": {
    "status": "pending | pass | caution | fail",
    "checks": []
  }
}
Data Rules
Store every key number once; reference it elsewhere by ID.
Keep assumptions separate from facts.
Do not mix units inside the same calculation.
Use ranges when precision would be fake.
Mark unsupported but necessary assumptions as judgment_call.
If a claim appears in the executive summary, it must trace to sources, assumptions, or
calculations.
Delivery Artifacts
For larger tasks, produce these files when useful:
data.json: source of truth;
verification.json: skeptical check results;
sources.md: readable source registry;
report.md: text report;
deck HTML/PDF if mckinsey-deck is used.
