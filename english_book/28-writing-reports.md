# Chapter 28: Documents & Reports

Reports and documents are where your thinking lives on paper. A clear report makes your analysis persuasive; a muddled one hides good work. This chapter covers executive summaries, data analysis reports, hedging language for findings, and documentation for code — with sentence stems you can reuse.

---

## 1. Executive summaries

An executive summary is a short section at the top of a report that tells a busy reader everything they need in a few lines. Many senior people read only this. Make it count.

**Structure of a strong executive summary:**
1. The situation / question (one line).
2. What you did (one line).
3. The key findings (two or three lines).
4. The recommendation (one line).

**Sentence stems:**
- "This report examines [question]."
- "We analysed [data] to understand [X]."
- "The key finding is that [main result]."
- "We found that [finding 1], and that [finding 2]."
- "Based on this, we recommend [action]."

**Full example [DS]:**
> **Executive summary.** This report examines why customer churn rose in Q3. We analysed 12 months of customer data across 40,000 accounts. The key finding is that 40% of churn occurs in the first month, driven mainly by a poor onboarding experience rather than price. We recommend redesigning the onboarding flow and running a controlled pilot, which we estimate could reduce early churn by up to 20%.

**Rule:** The executive summary should make sense entirely on its own. A reader who reads nothing else should still get the message and the recommendation.

## 2. Data analysis reports — sentence stems

Data reports follow a natural flow: context → method → findings → recommendation. Here are reusable stems for each part.

**Setting context:**
- "The aim of this analysis was to..."
- "We set out to understand..."
- "This work builds on the earlier study of..."

**Describing method:**
- "We used [data] covering the period [X] to [Y]."
- "We applied [method] to..."
- "We compared [A] against [B] to test whether..."

**Presenting findings:**
- "The analysis reveals that..."
- "We observe a strong correlation between [X] and [Y]."
- "The data shows a clear pattern:..."
- "Notably, [finding]."
- "Contrary to expectation, we found that..."

**Quantifying:**
- "This represents an increase of 15% compared to last quarter."
- "Roughly one in three customers..."
- "The effect is small but consistent."

**Recommending:**
- "We recommend that..."
- "Based on these findings, the next step should be..."
- "We suggest prioritising [X] because..."

## 3. Hedging language — being honest about uncertainty

In data science, you rarely have 100% certainty. Good reports show confidence where it's earned and caution where it isn't. This is called hedging. It's not weakness — it's honesty, and European colleagues respect it.

**Words that signal degrees of certainty (from strong to cautious):**

| Certainty | Language |
|---|---|
| Very confident | "The data clearly shows..." / "We are confident that..." / "This demonstrates..." |
| Confident | "The data indicates..." / "This strongly suggests..." |
| Moderate | "This suggests..." / "It appears that..." / "The results point to..." |
| Cautious | "This may indicate..." / "It is possible that..." / "The data hints at..." |
| Very cautious | "We cannot rule out..." / "Early signs suggest, though more data is needed..." |

**Useful hedging stems:**
- "The data suggests X, though we'd want more evidence to be sure."
- "This is likely due to Y, but other factors may contribute."
- "Within the limits of the available data, we conclude that..."
- "These results are preliminary and based on a small sample."
- "Correlation here does not prove causation; a controlled test would confirm it."

**Balance rule:** Don't overclaim ("this proves X") or underclaim so much that your report says nothing. State what you know confidently, flag what you don't, and recommend the next step to close the gap.

## 4. Structuring a longer document

- **Use clear headings** so readers can navigate.
- **Put the conclusion near the top** (executive summary), not just at the end.
- **One idea per paragraph.** Start each paragraph with its main point.
- **Use charts and tables** for data, with a one-line takeaway caption under each.
- **Define terms** the reader may not know, especially technical ones.
- **End with clear next steps** and who owns them.

## 5. Documentation & README language for code

Good documentation helps others (and future you) use your code. Keep it clear and practical.

**A good README structure:**
- **What it does** — one or two sentences.
- **How to set it up** — steps to install and run.
- **How to use it** — a simple example.
- **Inputs and outputs** — what goes in, what comes out.
- **Notes / limitations** — anything to watch out for.

**Useful documentation phrases:**
- "This module cleans and validates the raw customer data."
- "To run the pipeline, execute [command]."
- "The script expects a CSV with the following columns:..."
- "It returns a table of churn scores, one row per customer."
- "Note: the model must be retrained monthly to stay accurate."
- "Known limitation: this does not handle missing dates yet."

**Style tips for docs:**
- Write in the present tense: "This function returns...", not "This function will return..."
- Use the imperative for instructions: "Run the script," "Set the config."
- Be specific: "Takes about 5 minutes on the full dataset" beats "takes a while."
- Keep sentences short. Documentation is scanned, not savoured.

## 6. Comments in code

- Explain **why**, not just **what**. The code shows what; the comment should add the reason.
  - Weak: `# increase x by 1`
  - Strong: `# add 1 to avoid a divide-by-zero when the count is 0`
- Keep comments up to date — a wrong comment is worse than none.
- Write comments in clear, simple English so any teammate can follow.

---

## Common Indian-English pitfalls in reports and docs

- **"The below table shows..."** → "The table below shows..." (word order).
- **"As per the analysis..."** → "According to the analysis..." / "The analysis shows..."
- **"Kindly refer the graph."** → "See the graph below." ("Refer to," and drop "kindly.")
- **"Please find enclosed the report."** → "The report is attached." / "Please find the report attached."
- **"The data is showing increment."** → "The data shows an increase." (Not "increment," which is a code term.)
- **"Same has been updated."** → "This has been updated." (Avoid "same.")
- **"Doing the analysis, we found..."** → "In our analysis, we found..." / "We analysed the data and found..."

---

**Chapter 28 summary.** Strong documents lead with the answer (executive summary), flow logically from context to recommendation, and use honest hedging language to signal how confident you are. For code, write documentation that explains what it does, how to run it, and its limits — in short, simple English. Clear writing makes good analysis persuasive; unclear writing wastes it.
