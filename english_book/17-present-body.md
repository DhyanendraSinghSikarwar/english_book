# Chapter 17: The Body — Presenting Content

The body is where you deliver your message. The danger here is losing the audience: too much detail, no clear flow, or slides full of numbers with no story. This chapter gives you the language to guide people smoothly through your content and to present data clearly — a core skill for a data scientist.

**[DS]** marks data-science-specific language.

---

## 1. Transitions — moving between points

Transitions are short sentences that link one idea to the next. Without them, a presentation feels like a list of random facts. With them, it feels like a journey.

**Moving to the next point:**
- "Moving on to the second point..."
- "That brings me to..."
- "Now that we've seen the problem, let's look at the solution."
- "With that in mind, let's turn to the data."

**Building on what you just said:**
- "This leads directly to my next point."
- "Building on that..."
- "So what does this mean for us?"

**Going deeper:**
- "Let me unpack that a little."
- "Let's look at this more closely."

**How to deliver:** Pause briefly before a transition, and maybe change your position slightly or advance the slide. This signals "new section" to the audience.

## 2. Presenting data and charts (DS-critical)

This is the most important skill in the chapter. Never just show a chart in silence. Guide the audience through it in a fixed order: (1) what it is, (2) how to read it, (3) what to notice, (4) what it means.

**Step 1 — Introduce the chart:**
- "This chart shows churn rate by customer age group."
- "What you're looking at here is our monthly active users over the past year."

**Step 2 — Explain the axes [DS]:**
- "The x-axis represents time, month by month. The y-axis shows the number of active users."
- "Each dot is one customer; the colour shows whether they stayed or left."

**Step 3 — Point out what matters:**
- "As you can see on this slide, there's a clear spike in Q3."
- "Notice how the two lines diverge after March."
- "The important part is here, in the top-right corner."

**Step 4 — Give the takeaway (never skip this):**
- "The key takeaway from this chart is that most churn happens early — in the first 30 days."
- "What this tells us is that our onboarding, not our pricing, is the real problem."

**Full example [DS]:**
> "This chart shows churn rate by month. The x-axis is time; the y-axis is the percentage of customers who left. As you can see, there's a sharp spike here in Q3. The key takeaway is that the spike lines up exactly with our price increase — so pricing is very likely the cause."

**Golden rule:** one chart, one message. If a chart has more than one takeaway, split it into two slides.

## 3. Explaining models to non-technical audiences (DS)

Business people don't want the maths. They want to know what the model does and why they can trust it. Translate.

**Explaining what a model does:**
- "In simple terms, the model learns patterns from past customers to predict which current ones might leave."
- "Think of it as a very fast analyst that has read every customer's history and spotted the warning signs."
- "It's like a weather forecast — it gives us the probability of rain, not a guarantee."

**Explaining accuracy simply:**
- "The model is right about 85% of the time — far better than guessing."
- "For every 100 customers it flags as high-risk, about 80 really are — so the sales team's time is well spent."

**Avoiding jargon:** Instead of "we used a gradient-boosted classifier with hyperparameter tuning," say "we tested several methods and chose the one that predicted best on new data." Save the technical detail for a backup slide or a technical audience.

## 4. Emphasising key points

When something really matters, mark it clearly so it stands out.

- "I want to stress that these results are still preliminary."
- "What's particularly important here is the timing."
- "If you take away one thing from today, let it be this:..."
- "This is the number that matters:..."

**How to deliver:** Slow down. Lower your voice slightly (not louder — quieter often draws more attention). Pause before and after the key point.

## 5. Referring back and forward

This helps the audience connect ideas across your talk.

- "As I mentioned earlier, churn peaks in the first month."
- "I'll come back to this point shortly."
- "Remember that spike we saw? This explains it."
- "We'll return to what to do about this in the final section."

## 6. Handling uncertainty in results (DS)

Data scientists must be honest about uncertainty without sounding unsure of themselves. The trick is to state the limit and the confidence together.

- "The confidence interval suggests the true value is between 8% and 12%."
- "With the caveat that this is based on three months of data, the trend is clearly upward."
- "I'm confident in the direction, though I'd want more data before committing to the exact figure."
- "This is our best estimate given the data we have; it will sharpen as we collect more."

**Why this matters in Europe:** European colleagues, especially in the Netherlands and Germany, respect honesty about limits. Overclaiming ("this model is 100% accurate") damages trust. Stating uncertainty clearly actually makes you more credible.

## 7. Explaining a process or method step by step

- "Let me walk you through how we did this, step by step."
- "First, we collected the data. Then, we cleaned it. Finally, we trained the model."
- "There were three stages to this. Let me take them in order."

**Language for sequences:** first / next / then / after that / finally. Use these words clearly — they act as signposts.

---

## Keeping the audience with you

- **Check in occasionally:** "Is everyone with me so far?" / "Does that make sense before I move on?"
- **Signpost length:** "This is the last of the three findings." (People relax when they know where they are.)
- **Bring it back to them:** "So what does this mean for your team?" Keep connecting the content to the audience's interests.

---

## Common Indian-English pitfalls in the body

- **"As you can see in the graph, it is increasing only."** → "As you can see, it's increasing." (Drop "only.")
- **"I would like to discuss about the results."** → "I'd like to discuss the results." (No "about.")
- **"The same is shown in the next slide."** → "You can see this on the next slide." (Avoid "the same.")
- **"Kindly refer the below chart."** → "Take a look at the chart below." ("Refer to," and avoid "kindly.")
- **"This graph is depicting..."** → "This graph shows..." (Simpler is better.)
- **Speaking too fast:** Many Indian speakers speak quickly when nervous. Slow down — it makes you sound senior and clear. (More in Chapter 20.)

---

**Chapter 17 summary.** The body succeeds when you guide, not just show. Use transitions to link ideas, walk people through every chart in four steps, translate models into plain language, and be honest about uncertainty. Do this and even complex data science becomes easy for anyone to follow.
