# Chapter 6: Data & Technical Work (Data-Scientist Special)

This chapter is for your daily technical life: stand-ups, sprint reviews, pipelines, and model deployment. These phrasal verbs describe what happens to data, jobs, and systems. Learn them well — you will hear and say them many times a day. Simple, correct use here makes you sound like a confident engineer.

---

#### plug in
- **Meaning:** to connect one thing to another (a tool, a value, a data source).
- **Examples:**
  - Plug the new data source into the pipeline.
  - We plugged the API into the dashboard.
  - Just plug in your numbers and run it.
- **Mini-scenario:**
  - **Lead:** Can we use the fresh data?
  - **You:** Yes, I'll plug it into the model this afternoon.
- **Formal alternative:** integrate / connect
- **Indian-English pitfall:** "Plug in" (connect) vs "plug into." Both work; "plug X into Y" is common for data.

#### feed in
- **Meaning:** to supply data into a system.
- **Examples:**
  - We feed in the daily logs.
  - The sensor feeds data in every second.
  - Feed the training set in first.
- **Mini-scenario:**
  - **Colleague:** How does the model get updated?
  - **You:** We feed in new records every night.
- **Formal alternative:** input / supply
- **Indian-English pitfall:** "Feed in" data, not "feed the data inside." Keep it simple: "feed in."

#### pull (data)
- **Meaning:** to get data from a source.
- **Examples:**
  - I'll pull the numbers from the database.
  - Can you pull last month's sales?
  - We pull data via the API.
- **Mini-scenario:**
  - **Manager:** Do you have the figures?
  - **You:** I'll pull them from the warehouse now.
- **Formal alternative:** extract / retrieve
- **Indian-English pitfall:** "Pull data from [source]." Don't say "pull out the data" unless you mean remove it.

#### clean up
- **Meaning:** to fix errors and tidy data.
- **Examples:**
  - I need to clean up the raw data.
  - We cleaned up the duplicates.
  - The dataset needs cleaning up.
- **Mini-scenario:**
  - **Lead:** Is the data ready to model?
  - **You:** Almost — I just need to clean it up.
- **Formal alternative:** cleanse / preprocess
- **Indian-English pitfall:** "Clean up the data," not "clean the data up and up." Note: "data cleaning" is the noun form.

#### filter out
- **Meaning:** to remove unwanted items.
- **Examples:**
  - Filter out the test accounts.
  - We filtered out negative values.
  - Let's filter out the noise.
- **Mini-scenario:**
  - **You:** The results look strange.
  - **Colleague:** Did you filter out the bots?
- **Formal alternative:** exclude / remove
- **Indian-English pitfall:** "Filter out" (remove) vs "filter" (narrow down). "Out" stresses removal.

#### strip out
- **Meaning:** to remove specific parts completely.
- **Examples:**
  - Strip out the personal details.
  - We stripped out the HTML tags.
  - Strip out empty columns.
- **Mini-scenario:**
  - **Lead:** We can't share names.
  - **You:** I'll strip out all the personal data first.
- **Formal alternative:** remove / eliminate
- **Indian-English pitfall:** "Strip out" is stronger than "filter out" — it means fully take away, often for cleaning or privacy.

#### merge in
- **Meaning:** to combine one dataset into another.
- **Examples:**
  - Merge in the customer table.
  - We merged in the location data.
  - Merge the new rows in carefully.
- **Mini-scenario:**
  - **Colleague:** We need region info too.
  - **You:** I'll merge in the region table on customer ID.
- **Formal alternative:** join / combine
- **Indian-English pitfall:** "Merge in" (add data) is close to the SQL "join." Say "merge X in on [key]."

#### roll back
- **Meaning:** to return a system to an earlier version.
- **Examples:**
  - We rolled back the release.
  - Roll back to the last stable model.
  - They rolled back the change after the error.
- **Mini-scenario:**
  - **Lead:** The new model is worse in production.
  - **You:** Let's roll back to the previous version.
- **Formal alternative:** revert / restore
- **Indian-English pitfall:** "Roll back" (undo a deploy) is two words as a verb; "rollback" is one word as a noun.

#### back up (data)
- **Meaning:** to make a safety copy.
- **Examples:**
  - Back up the database nightly.
  - Did you back up the results?
  - We back up everything to the cloud.
- **Mini-scenario:**
  - **Manager:** What if we lose the file?
  - **You:** No worries — we back it up every night.
- **Formal alternative:** archive / save a copy
- **Indian-English pitfall:** Verb is "back up" (two words); noun is "backup" (one word). "Take a backup" is fine but "make a backup" is more standard.

#### spin up
- **Meaning:** to start a server or environment quickly.
- **Examples:**
  - Spin up a new instance.
  - We spun up a test server.
  - I'll spin up a container for this.
- **Mini-scenario:**
  - **Lead:** We need more compute for training.
  - **You:** I'll spin up a bigger machine.
- **Formal alternative:** provision / launch
- **Indian-English pitfall:** "Spin up" (start a machine) is modern cloud language. The opposite is "spin down" or "shut down."

#### shut down
- **Meaning:** to stop a system or machine.
- **Examples:**
  - Shut down the unused servers.
  - The job shut down cleanly.
  - We shut the pipeline down for maintenance.
- **Mini-scenario:**
  - **Manager:** Costs are high this month.
  - **You:** I'll shut down the idle instances.
- **Formal alternative:** stop / terminate
- **Indian-English pitfall:** Verb "shut down" (two words); noun "shutdown" (one word). Don't say "shut off" for servers — that's for taps and lights.

#### scale out
- **Meaning:** to add more machines to handle more load.
- **Examples:**
  - We scaled out to ten nodes.
  - Scale out during peak hours.
  - The system scales out automatically.
- **Mini-scenario:**
  - **Lead:** Traffic is doubling next week.
  - **You:** We can scale out to handle it.
- **Formal alternative:** scale horizontally / expand capacity
- **Indian-English pitfall:** "Scale out" (add machines) vs "scale up" (make one machine bigger). They mean different things in engineering.

#### log in / log out
- **Meaning:** to enter or leave a system with your account.
- **Examples:**
  - Log in with your work account.
  - I got logged out automatically.
  - Log out when you finish.
- **Mini-scenario:**
  - **Colleague:** I can't see the dashboard.
  - **You:** Try logging out and logging back in.
- **Formal alternative:** sign in / sign out
- **Indian-English pitfall:** Verb "log in" (two words); noun/adjective "login" (one word). Say "log in to the system," not "login to."

#### time out
- **Meaning:** to stop because too much time passed.
- **Examples:**
  - The request timed out.
  - The job timed out after an hour.
  - The connection keeps timing out.
- **Mini-scenario:**
  - **Lead:** Why did the query fail?
  - **You:** It timed out — the table is too big.
- **Formal alternative:** exceed the time limit / expire
- **Indian-English pitfall:** Verb "time out" (two words); noun "timeout" (one word). "It timed out," not "it did timeout."

#### crash out
- **Meaning:** to fail suddenly with an error.
- **Examples:**
  - The script crashed out at row 5,000.
  - The app crashed out on start-up.
  - It crashed out with a memory error.
- **Mini-scenario:**
  - **You:** The training run stopped.
  - **Colleague:** Did it finish or crash out?
- **Formal alternative:** fail / terminate unexpectedly
- **Indian-English pitfall:** "Crash out" (fail) is informal. In a report, write "the job failed" or "the process terminated with an error."

#### kick off (a job)
- **Meaning:** to start a process or task.
- **Examples:**
  - Kick off the nightly job.
  - I kicked off the training run.
  - Let's kick off the batch process.
- **Mini-scenario:**
  - **Lead:** Are we ready to retrain?
  - **You:** Yes, I'll kick it off now.
- **Formal alternative:** start / trigger / initiate
- **Indian-English pitfall:** "Kick off" (start) is common for both meetings and jobs. Don't say "kick start" unless you mean give extra energy.

#### churn out
- **Meaning:** to produce a lot, quickly.
- **Examples:**
  - The pipeline churns out reports daily.
  - We churned out ten models this week.
  - It churns out predictions in seconds.
- **Mini-scenario:**
  - **Manager:** How fast can we get results?
  - **You:** Once it's set up, it churns them out automatically.
- **Formal alternative:** produce / generate
- **Indian-English pitfall:** "Churn out" (produce a lot) is different from "churn" (customers leaving). Same word, different sense — context decides.

#### run on
- **Meaning:** to operate using a certain resource or system.
- **Examples:**
  - The model runs on GPUs.
  - Our stack runs on the cloud.
  - It runs on Python 3.11.
- **Mini-scenario:**
  - **Colleague:** What powers the training?
  - **You:** It runs on four GPUs.
- **Formal alternative:** operate on / be powered by
- **Indian-English pitfall:** "Run on [resource]." Don't confuse with "run out" (finish supply) or "run into" (meet a problem).

#### build on
- **Meaning:** to use existing work as a base for new work.
- **Examples:**
  - We built on last year's model.
  - Build on the existing pipeline.
  - This work builds on her research.
- **Mini-scenario:**
  - **Lead:** Do we start from scratch?
  - **You:** No, we can build on the current version.
- **Formal alternative:** extend / develop further
- **Indian-English pitfall:** "Build on [something]," not "build over." It means to add to a foundation, not to rebuild.

#### iterate on
- **Meaning:** to improve something step by step.
- **Examples:**
  - Let's iterate on the design.
  - We iterated on the model for weeks.
  - Iterate on it until accuracy improves.
- **Mini-scenario:**
  - **Manager:** The first version is rough.
  - **You:** That's fine — we'll iterate on it.
- **Formal alternative:** refine / improve incrementally
- **Indian-English pitfall:** "Iterate on [something]." Very common in agile teams. Don't say "iterate over" for improvement (that means loop through in code).

---

## More data & technical phrasal verbs

#### spin down
- **Meaning:** to stop or shrink compute resources.
- **Examples:**
  - Spin down the cluster after the job.
  - We spun down the extra nodes.
- **Formal alternative:** deprovision / stop
- **Indian-English pitfall:** Opposite of "spin up." Used to save cloud costs.

#### wipe out
- **Meaning:** to completely delete or destroy.
- **Examples:**
  - A bad script wiped out the table.
  - Don't wipe out the raw data.
- **Formal alternative:** erase / delete entirely
- **Indian-English pitfall:** Stronger than "clean up." "Wipe out" means gone for good.

#### drop off
- **Meaning:** to decrease, often sharply.
- **Examples:**
  - Accuracy dropped off after the update.
  - User activity drops off at weekends.
- **Formal alternative:** decline / decrease
- **Indian-English pitfall:** "Drop off" (decline) vs "drop" (a single fall). "Off" shows a trend down.

#### fan out
- **Meaning:** to split one task into many parallel tasks.
- **Examples:**
  - The job fans out across workers.
  - We fan out the requests to speed things up.
- **Formal alternative:** parallelise / distribute
- **Indian-English pitfall:** Technical term in distributed systems; pairs with "fan in" (collect results).

#### hook up
- **Meaning:** to connect systems or tools together.
- **Examples:**
  - Hook up the model to the API.
  - We hooked the dashboard up to live data.
- **Formal alternative:** connect / integrate
- **Indian-English pitfall:** "Hook up" is informal at work. In writing, use "connect" or "integrate."

#### flag up
- **Meaning:** to point out a problem or risk.
- **Examples:**
  - The tests flagged up a data issue.
  - I flagged up the anomaly to the lead.
- **Formal alternative:** highlight / raise
- **Indian-English pitfall:** "Flag up" (raise attention) is common in the UK. In the US, just "flag."

#### zero out
- **Meaning:** to set values to zero.
- **Examples:**
  - Zero out the missing counts.
  - The bug zeroed out the totals.
- **Formal alternative:** reset to zero
- **Indian-English pitfall:** Technical; means set to zero, not delete.

#### fall over
- **Meaning:** (informal, British) for a system to crash or fail.
- **Examples:**
  - The service fell over under load.
  - It falls over when memory runs out.
- **Formal alternative:** crash / fail
- **Indian-English pitfall:** Common British tech slang for a crash. In reports, say "the service failed."

#### ramp up
- **Meaning:** to increase gradually (load, effort, resources).
- **Examples:**
  - We ramped up the batch size.
  - Traffic is ramping up before the launch.
- **Formal alternative:** increase / scale up
- **Indian-English pitfall:** Also used for effort and hiring, not just compute.

#### page through
- **Meaning:** to move through data in chunks (pagination).
- **Examples:**
  - The API pages through results.
  - We page through 10,000 rows at a time.
- **Formal alternative:** paginate
- **Indian-English pitfall:** Technical term for reading data in pages, not skimming a book.

---

**Chapter 6 count: 30 phrasal verbs.** Try these in your next stand-up: "I kicked off the training run," "It timed out, so I'll roll back," and "Once the data's cleaned up, I'll plug it into the model."

---

## Part 1 wrap-up

Across Chapters 1–6 you now have **200+ workplace phrasal verbs**. Don't try to learn all of them at once. Pick five each week, use them in real messages and meetings, and they will stick. Phrasal verbs are the sound of natural spoken English — mastering them is the fastest way to stop sounding like a textbook and start sounding like a colleague.
