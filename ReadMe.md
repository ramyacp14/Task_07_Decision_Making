# Syracuse Women’s Lacrosse 2025 – Decision Report

**Purpose:** To provide coaching and athletic staff with evidence-based recommendations, supported by verified player statistics and ethical process documentation, to guide team development decisions for the upcoming season.

---

## Executive Summary:

This report analyzes the 2025 Syracuse Women’s Lacrosse season using verified statistics from 32 athletes. The goal is to transform an earlier AI-generated narrative into a decision report that is transparent, reproducible, and ethically sound.

**Key Findings:**

* The team scored 347 total points (235 goals, 112 assists) across 19 games.
* Offensive leaders: Emma Muchnick (34 goals), Angela Beardsley (46 assists).
* Defensive standout: Coco Vandiver (40 caused turnovers).
* High efficiency: Olivia Adamson (55.6% shooting).
* Clutch performance: Caroline Trinkaus (4 game-winning goals).
* Balanced two-way play: Joely Caramelli (20 points, 23 ground balls, 11 CT).
* Defensive gap: Opponents scored 337 points, signaling vulnerability in backline play.

**Recommendations (by risk tier):**

* **Low risk (Operational):** Provide targeted conditioning for defensive unit; emphasize late-game stamina training.
* **Medium risk (Investigatory):** Conduct controlled analysis of defensive schemes, trial alternative formations.
* **High risk (Strategic/Personnel):** Evaluate recruitment or reassignment for defensive specialists; requires HR/legal oversight.

**Confidence Level:** Moderate. Findings are based on official SU statistics with cross-validation. Bootstrapped checks confirmed consistency in reported effects.

---

## Background & Decision Question

**Stakeholders:** Syracuse Women’s Lacrosse coaching staff, athletic director, and performance analysts.
**Decision Context:** How to strengthen defensive performance and sustain offensive efficiency for 2026.
**Risk Level:** Medium–high, as decisions affect team outcomes, player development, and potentially recruitment.

---

## Data & Methods (Brief)

* **Dataset:** Syracuse University Lacrosse 2025 statistics (32 players).
* **Metrics:** Goals, Assists, Shooting %, Caused Turnovers, Ground Balls, Game Outcomes.
* **Validation:** Cross-checked via Task 05 notebook and official CSV.
* **LLM Tools:** GPT-4o used for narrative draft (see Appendix A). NotebookLM used for fact-checking wording.
* **Reproducibility:** All code and prompts archived; random seeds logged in analysis notebook.

---

## Findings (with Uncertainty)

* Team’s +10 goal differential (347–337) indicates marginal dominance; bootstrap simulations suggest 95% CI \[6, 15].
* Shooting efficiency: Adamson’s 55.6% holds under resampling (±3% CI).
* Defensive turnovers: Vandiver’s 40 CT significant vs. team median of 12 (p < 0.05, Mann–Whitney).
* Potential bias: Statistics do not account for opponent strength; missing context may inflate certain player metrics.

---

## Recommendations (Tiered)

* **Operational (Low risk):**

  * Introduce late-game stamina drills for defense.
  * Recognize and reward efficiency leaders (Adamson, Trinkaus).

* **Investigatory (Medium risk):**

  * Pilot defensive scheme changes in scrimmages.
  * Collect advanced defensive metrics (e.g., opponent shooting zones).

* **High Stakes (High risk):**

  * Explore recruitment or reassignment for specialized defenders.
  * Requires compliance review and coordination with HR/athletics governance.

---

## Ethical / Legal Concerns

* **Data provenance:** Official SU stats — low privacy risk, as data are public.
* **Bias:** Metrics may under-represent off-ball contributions or intangible play.
* **LLM use:** All generated text clearly labeled; human verification applied.
* **Legal:** Personnel recommendations (recruitment/reassignment) must go through HR and NCAA compliance.

---

## Next Steps & Validation Plan

* Collect additional data on defensive breakdowns.
* Run sensitivity analysis removing top scorers to test offensive robustness.
* Conduct fairness review: Ensure recommendations don’t disproportionately affect under-represented subgroups.
* Archive code, datasets, and LLM transcripts in shared repo.

---

## Appendices

* **Appendix A:** Raw LLM Outputs (LLMResponses.docx).
* **Appendix B:** Verified script [HeyGen video] (https://app.heygen.com/videos/bfd67633f59644bf80eedcceff917f37)
* **Appendix C:** Code & Notebook seeds (playerperformance.ipynb).
* **Appendix D:** Data lineage (data/Player\_Stats.csv → analysis → video script).

