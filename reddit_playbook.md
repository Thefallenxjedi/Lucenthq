# The Reddit Distribution Playbook

Reddit is the ultimate testing ground. It has highly segmented communities for all three of our target ICPs (`r/webdev`, `r/SaaS`, `r/ProductManagement`). It is also incredibly hostile to marketers. 

If we go into these subreddits and spam "Try LucentHQ!", we will be banned instantly. 

This playbook outlines exactly how we infiltrate these communities organically by providing extreme value, and how we run paid ads to scientifically test which of our three ICPs converts the cheapest.

---

## Part 1: Organic Infiltration (How to not get banned)

Redditors hate marketing, but they absolutely love "war stories" and technical deep dives. Our organic strategy relies entirely on **Educational Teardowns**.

### The Tactical Approach:
1.  **Lead with the Horror Story:** Do not mention Lucent. Start by describing a terrifying problem (e.g., "We had a silent React hydration error that tanked checkout conversion by 14% and Sentry missed it completely.")
2.  **Explain the Manual Fix:** Detail exactly how hard it was to find the bug manually (e.g., "I had to write custom SQL queries and manually scrub through 40 hours of PostHog recordings.")
3.  **The "Ah-ha" Pivot (The Soft Pitch):** Explain the realization that this process should be automated by AI. *"I realized humans shouldn't be watching videos. We built a script that feeds the DOM mutations into an LLM to flag rage clicks automatically."*
4.  **The CTA in the Comments:** Do not link to the landing page in the main post. Let people ask "How did you build that script?" or "Is this available?" Then, reply with the link to LucentHQ in the comments.

**Target Subreddits for Organic Posts:**
*   `r/webdev`
*   `r/reactjs`
*   `r/SaaS`
*   `r/startup`

---

## Part 2: The Paid CPA Test (Ad Copy & Creative)

We are running three cheap ad campaigns simultaneously. The goal is not to get rich; the goal is to see which demographic yields the lowest Cost Per Acquisition (CPA). 

### Ad Group 1: Enterprise Engineers
*   **Target Subreddits:** `r/programming`, `r/webdev`, `r/javascript`
*   **The Angle:** Alert fatigue and the gap between Error Tracking and Visual Proof.
*   **Headline 1:** Sentry tells you the code broke. We show you the exact video of the user breaking it.
*   **Headline 2:** Stop manually scrubbing through PostHog recordings. Let an AI QA engineer watch them for you.
*   **Body Copy:** You don't have time to reproduce vague support tickets. LucentHQ is an AI observability layer that watches every session and automatically writes a Jira ticket with reproduction steps the moment a user hits friction.

### Ad Group 2: Series A Founders
*   **Target Subreddits:** `r/SaaS`, `r/startups`, `r/Entrepreneur`
*   **The Angle:** Code velocity, replacing QA, and saving money on compute.
*   **Headline 1:** You can't afford a QA team. So we built an AI to watch your session replays for you.
*   **Headline 2:** Move fast and break things (without breaking your retention).
*   **Body Copy:** Shipping fast means bugs slip through. LucentHQ acts as your automated QA team, catching silent frontend errors and UX friction before your users churn. Plus, with our "AI Credits" model, you get generous free recording and only pay for the AI when you need it. 

### Ad Group 3: Product Managers
*   **Target Subreddits:** `r/ProductManagement`
*   **The Angle:** Independence from engineering bottlenecks.
*   **Headline 1:** Stop begging engineers to pull data just to prove a user flow is confusing.
*   **Headline 2:** Instantly prove UX friction without writing a single line of SQL.
*   **Body Copy:** You *know* the checkout flow is broken, but you don't have the data. LucentHQ's AI watches your session replays and automatically surfaces the exact moments users get stuck, generating undeniable proof for your engineering team. 

---

## The Success Metric
We let this run for 7 days with a budget of $50/day per Ad Group. 
*   If `r/webdev` gets signups at $10/user, and `r/SaaS` costs $45/user, we instantly pivot 100% of our company GTM focus toward Enterprise Engineering. We let the data decide our fate.
