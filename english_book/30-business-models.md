# Chapter 30: Common Business Models Explained in Plain English

To be a great data scientist, you need to understand how your company makes money. This shapes what questions matter, what metrics to track, and how to talk to business people. This chapter explains the main business models in simple English.

**For each model you get:** a simple definition, an example company, the vocabulary used to discuss it, and one data-science angle **[DS]**.

---

## 1. B2B (Business-to-Business)

**What it is:** A company sells to other companies, not to ordinary people.

**Example:** Salesforce sells software to businesses. SAP sells systems to large firms.

**Vocabulary:** client, account, contract, deal size, sales cycle, procurement, enterprise, seat (a paid user).

**[DS] angle:** In B2B, you often have fewer customers but each is worth a lot. Data science focuses on account health, expansion (selling more to existing clients), and predicting which deals will close.

## 2. B2C (Business-to-Consumer)

**What it is:** A company sells directly to individual people.

**Example:** Netflix, Spotify, Amazon (retail), Zalando.

**Vocabulary:** user, customer, consumer, conversion, basket, sign-up, retention.

**[DS] angle:** B2C usually means huge numbers of customers. Data science focuses on personalisation, recommendations, conversion rates, and churn across millions of users.

## 3. B2B2C (Business-to-Business-to-Consumer)

**What it is:** A company sells through another business to reach the final consumer.

**Example:** A payments company (like Adyen) provides technology to shops, and the shops serve consumers.

**Vocabulary:** partner, end user, platform, intermediary, white-label (selling under another brand's name).

**[DS] angle:** You may analyse data across two layers — the business partners and their end customers — and you might not directly own the consumer relationship.

## 4. D2C (Direct-to-Consumer)

**What it is:** A brand that traditionally sold through shops now sells straight to people online, skipping the middleman.

**Example:** A mattress brand or razor brand selling only through its own website.

**Vocabulary:** direct channel, cut out the middleman, brand loyalty, customer acquisition cost.

**[DS] angle:** Because you own the whole customer relationship, you get rich first-party data — great for personalisation and lifetime-value modelling.

## 5. SaaS / Subscription model

**What it is:** Software as a Service. Customers pay a regular fee (monthly or yearly) to use software online, instead of buying it once.

**Example:** Slack, Zoom, Microsoft 365, Spotify (subscription side).

**Vocabulary a data scientist MUST know:**
- **MRR (Monthly Recurring Revenue):** predictable revenue each month from subscriptions.
- **ARR (Annual Recurring Revenue):** the yearly version (roughly MRR × 12).
- **Churn:** the rate at which customers cancel. (Your bread and butter.)
- **Retention:** the opposite of churn — customers who stay.
- **Net revenue retention (NRR):** how revenue from existing customers grows or shrinks over time, including upgrades and cancellations.
- **ARPU (Average Revenue Per User):** revenue divided by number of users.
- **CAC (Customer Acquisition Cost):** what it costs to win a customer.
- **LTV (Lifetime Value):** total revenue expected from a customer over time.
- **LTV:CAC ratio:** a health check — value of a customer vs cost to get them.

**[DS] angle:** SaaS is the classic home of churn prediction, expansion modelling, usage analysis, and forecasting MRR. Nearly everything in this book's data examples fits here.

## 6. Marketplace model

**What it is:** A platform that connects buyers and sellers but doesn't own the product itself. It takes a cut of each transaction.

**Example:** Airbnb (guests + hosts), Uber (riders + drivers), eBay, Booking.com.

**Vocabulary:**
- **Two-sided market:** you must attract both buyers and sellers (supply and demand).
- **Take rate:** the percentage the platform keeps from each transaction.
- **GMV (Gross Merchandise Value):** the total value of everything sold on the platform.
- **Liquidity:** enough buyers and sellers for deals to happen easily.
- **Network effects:** more users make the platform more valuable for everyone.

**[DS] angle:** You balance two sides — matching supply and demand, pricing, and predicting whether both sides stay active. GMV and take rate drive revenue.

## 7. Freemium

**What it is:** The basic product is free; you pay for premium features.

**Example:** Spotify (free with ads → paid), Dropbox (free storage → paid for more), LinkedIn.

**Vocabulary:** free tier, paid tier, upgrade, conversion (free → paid), paywall.

**[DS] angle:** A key question is which free users will convert to paid. You model conversion and find the features or moments that push users to upgrade.

## 8. Advertising model

**What it is:** The product is free to users; the company makes money by showing ads.

**Example:** Google Search, Meta (Facebook/Instagram), YouTube (ad side).

**Vocabulary:** impressions, clicks, CTR (click-through rate), CPM (cost per thousand impressions), CPC (cost per click), ad inventory, targeting.

**[DS] angle:** Data science powers ad targeting, ranking, and bidding. Metrics revolve around engagement and ad performance.

## 9. Licensing

**What it is:** A company charges others to use its intellectual property, brand, or technology.

**Example:** ARM licenses chip designs; Disney licenses characters for toys.

**Vocabulary:** licence fee, royalty, intellectual property (IP), licensee, terms.

**[DS] angle:** Less common for data science, but you might forecast royalty revenue or analyse how licensed products perform.

## 10. Franchise

**What it is:** A company lets independent owners run branches under its brand and system, for a fee and a share of revenue.

**Example:** McDonald's, Subway.

**Vocabulary:** franchisee (the owner), franchisor (the brand), franchise fee, royalty.

**[DS] angle:** You might analyse performance across locations to spot best practices and predict which sites will succeed.

## 11. E-commerce

**What it is:** Selling physical or digital goods online.

**Example:** Amazon, Zalando, Bol.com.

**Vocabulary:** cart, checkout, conversion rate, average order value (AOV), fulfilment, returns, basket abandonment.

**[DS] angle:** Recommendations, demand forecasting, pricing, and reducing cart abandonment are core data science tasks.

## 12. Aggregator

**What it is:** A platform that gathers many options in one place, making it easy to compare and choose.

**Example:** Booking.com (hotels), Skyscanner (flights), Just Eat / Takeaway (restaurants).

**Vocabulary:** listings, comparison, commission, supply, ranking.

**[DS] angle:** Ranking and search relevance are central — showing the best options first drives bookings.

## 13. On-demand / gig economy

**What it is:** Services delivered quickly when the customer wants them, often using independent workers.

**Example:** Uber, Deliveroo, Bolt.

**Vocabulary:** gig worker, on-demand, supply-demand matching, surge pricing, ETA.

**[DS] angle:** Real-time matching, demand prediction, and dynamic pricing are heavy data science areas.

## 14. Platform vs pipeline businesses

This is a useful distinction to understand.

- **Pipeline business:** creates a product and sells it in a straight line — make, then sell. (Example: a car maker, a traditional software company.)
- **Platform business:** creates value by connecting groups and letting them interact. (Example: Airbnb, App Store.)

**Vocabulary:** value chain (pipeline), ecosystem and network effects (platform).

**[DS] angle:** Platforms generate interaction data (who connects with whom), enabling network analysis and matching. Pipelines focus more on production, demand, and sales data.

---

## How to talk about business models at work

- "We're a SaaS business, so our north star is reducing churn and growing MRR."
- "Because we're a marketplace, we have to keep both sides — supply and demand — healthy."
- "Our freemium model means the key question is what converts free users to paid."
- "As a B2B company, each account is high-value, so retention really matters."

Understanding the model helps you ask the right questions: for SaaS, "what drives churn?"; for a marketplace, "where's the supply-demand imbalance?"; for advertising, "what lifts engagement?"

---

**Chapter 30 summary.** Knowing your company's business model tells you what matters. SaaS lives on recurring revenue and churn; marketplaces balance two sides; advertising runs on engagement; freemium hinges on conversion. Learn the vocabulary for your model, and you'll speak the same language as the business people you support — which makes your data science far more valuable.
