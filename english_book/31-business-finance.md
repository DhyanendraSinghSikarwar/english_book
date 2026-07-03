# Chapter 31: Business & Finance Vocabulary for Data Scientists

Business people talk in money and metrics. To be taken seriously and to make your work matter, you need to understand and use their language. This chapter explains the finance and business terms a data scientist meets most, in plain English.

---

## 1. Core performance metrics

**KPI (Key Performance Indicator):** a number the business watches closely to measure success. Example: "Churn rate is our main KPI this quarter."

**ROI (Return on Investment):** how much value you get back compared to what you spent. "This project has a strong ROI — it costs €50K and saves €500K."

**North star metric:** the single most important number that captures the value you deliver to customers. For Spotify it might be "time spent listening."

**Conversion rate:** the percentage of people who take a desired action (sign up, buy). "We improved the conversion rate from 2% to 3%."

**Benchmark:** a standard to compare against. "Our accuracy beats the industry benchmark."

## 2. Money words: revenue, profit, margin

These are often confused. Learn the difference clearly:

- **Revenue (or "top line"):** all the money coming in from sales, before any costs. "We generated €10M in revenue."
- **Cost:** the money spent to run the business.
- **Profit (or "bottom line"):** what's left after costs. Profit = Revenue − Costs. "After costs, profit was €2M."
- **Margin:** profit as a percentage of revenue. "We run a 20% margin." A high margin means the business keeps more of each euro earned.
- **Gross margin vs net margin:** gross is before overheads (like rent and salaries); net is after everything.

**Why it matters [DS]:** When you say a model "increases revenue," people may ask about the margin — extra sales that cost a lot to fulfil may not add much profit. Knowing the difference makes you sound sharp.

## 3. Spending words: CAPEX, OPEX, burn, runway

- **CAPEX (Capital Expenditure):** money spent on long-term assets (buildings, big equipment).
- **OPEX (Operating Expenditure):** day-to-day running costs (salaries, cloud bills, rent). "Our cloud costs are OPEX."
- **Run rate:** projecting current performance forward. "At the current run rate, we'll hit €12M this year."
- **Burn rate:** how fast a company spends its cash (common in startups). "The startup's burn rate is €200K a month."
- **Runway:** how long the money will last at the current burn. "We have 18 months of runway."

## 4. Stakeholder and value language

These words help you connect your technical work to business value.

- **Business impact:** the real-world effect of your work. "The business impact is €2M saved a year."
- **Value proposition:** the core promise of value to the customer. "Our value proposition is saving time."
- **Cost-benefit:** weighing what something costs against what it delivers. "Let's do a cost-benefit analysis before building it."
- **Trade-off:** giving up one thing to gain another. "There's a trade-off between speed and accuracy."
- **Return / payback:** what you get back, and how long until you break even. "The payback period is six months."
- **Stakeholder:** anyone with an interest in the project (managers, clients, other teams). "Let's align with the stakeholders first."

**Using them [DS]:**
- "The model has a clear business impact: it reduces churn, worth about €1M a year."
- "There's a trade-off here — a more accurate model takes twice as long to run."
- "From a cost-benefit view, automating this pays for itself in three months."

## 5. Talking money in Europe

- **Currency:** the eurozone uses euros (€); the UK uses pounds (£). Say "two point three million euros" or write "€2.3M."
- **Decimal and thousands separators differ (important):** many European countries use a comma for decimals and a dot/space for thousands. "€1.000.000,50" means one million euros and fifty cents in Germany. When in doubt, write it out or label clearly. (See Chapter 15.)
- **Say big numbers clearly:** "€2.3 million," "half a million euros," "around €50K." Avoid the Indian "lakhs" and "crores" — Europeans don't use these units. One lakh = 100,000; one crore = 10 million, but always convert: say "€1 million," not "€1 crore."
- **Example:** "The project delivered €2.3 million in savings" — clear, correctly formatted, no lakhs/crores.

## 6. Strategy and planning words

- **Pivot:** to change direction or strategy. "The company pivoted from ads to subscriptions."
- **Roadmap:** the plan of what will be built and when. "This feature is on the roadmap for Q4."
- **Quarter (Q1–Q4):** the business year is split into four three-month quarters. "We'll launch in Q3."
- **Fiscal year (FY):** a company's financial year, which may not match the calendar year. "FY2026 ends in March."
- **Headcount:** the number of employees. "We're adding two to headcount next quarter."
- **Bandwidth:** how much capacity or time someone has. "I don't have the bandwidth for another project this sprint."
- **Scope:** what is (and isn't) included in a project. "That's out of scope for this phase."
- **Scope creep:** when a project quietly grows beyond its original plan.
- **Milestone:** an important checkpoint in a project.
- **Deliverable:** a concrete output you're expected to produce.

## 7. Growth and market words

- **Market share:** the portion of a market a company holds.
- **TAM (Total Addressable Market):** the full size of the market opportunity.
- **Growth rate:** how fast something is increasing, usually as a percentage.
- **Scalability:** whether something can grow without breaking. "Is this solution scalable?"
- **Unit economics:** whether each sale/customer is profitable on its own.
- **Churn / retention / acquisition:** losing, keeping, and gaining customers (see Chapter 30).

## 8. Putting it together — a data scientist speaking "business"

Weak (pure tech): "The model has an AUC of 0.89 and I optimised the hyperparameters."

Strong (business-aware): "The model correctly flags about 85% of at-risk customers. If sales act on those flags, we estimate it protects around €1M in annual revenue. The main trade-off is that it needs monthly retraining, which is a small OPEX cost."

The second version connects your work to money and decisions. That's what gets projects funded and gets you promoted.

---

## Common Indian-English pitfalls with business vocabulary

- **"Lakhs" and "crores"** → always convert to millions: "€2 million," not "20 lakhs" or "2 crores."
- **"Revenue" vs "profit"** — don't use them interchangeably; they're different (see above).
- **"Costing" (as a noun for cost)** → "cost." "What's the cost?" not "What's the costing?"
- **"Turnover"** — in British English this means revenue (total sales); in American English "turnover" often means staff leaving. In Europe, "turnover" usually = revenue, but clarify if unsure.
- **"Do the budgeting"** → "prepare the budget" / "plan the budget."
- **"Salary hike"** → "pay rise" (UK) / "raise" (US). "Hike" for salary is Indian English.

---

**Chapter 31 summary.** Learn the language of money — revenue vs profit vs margin, CAPEX/OPEX, KPIs and ROI — and the strategy words like roadmap, scope, and bandwidth. Always translate your technical results into business impact and euros (never lakhs or crores). A data scientist who speaks business fluently is far more influential than one who speaks only in accuracy scores.
