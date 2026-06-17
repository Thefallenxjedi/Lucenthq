# LucentHQ vs. PostHog: Pricing Comparison & Positioning Strategy

When comparing LucentHQ to PostHog, the most obvious difference is the raw price. PostHog's usage-based model makes it incredibly cheap to *capture* sessions, while LucentHQ's flat tiers are priced like an enterprise AI tool. 

If we compete purely on "cost per recording," we will lose. **We must compete on the "cost of analysis."**

---

## 1. The Raw Math (Volume vs. Value)

Here is how the pricing breaks down for standard web session replay volume:

| Metric | PostHog (Usage-Based) | LucentHQ (Tiered) |
| :--- | :--- | :--- |
| **Free Tier** | 5,000 sessions / mo | 400 sessions / mo |
| **10,000 Sessions** | ~$25 / mo *(5k free, 5k @ $0.005)* | $399 / mo (Starter) |
| **30,000 Sessions** | ~$125 / mo *(5k free, 25k @ $0.005)* | $799 / mo (Pro) |
| **Value Delivered** | Video Hosting & Storage | Automated AI QA & Bug Reports |

> [!WARNING]
> If a prospective buyer looks at this table without context, they will choose PostHog because it is mathematically ~16x cheaper at 10k sessions. 

---

## 2. The Positioning Strategy (How to Win)

To justify the $399/mo and $799/mo price tags against PostHog, we cannot sell Lucent as a "Session Replay Tool." We must position Lucent as an **Automated QA Team**.

The hidden cost of PostHog is the human capital required to watch the recordings.

### The "True Cost" Argument for our Landing Page/Sales Deck:
1. **The PostHog Reality:** You pay $25/month to record 10,000 sessions. But who has time to watch 10,000 videos? You either pay a Product Manager $120k/yr or a QA Engineer $100k/yr to sit and watch videos for 10 hours a week to find the 3 bugs that actually matter.
2. **The Lucent Reality:** You pay $399/month. You don't watch any videos. The AI watches all 10,000 sessions for you, ignores the noise, and pings your Slack with the 3 bugs that matter, including the exact steps to reproduce them.

**Lucent isn't replacing PostHog; it's replacing manual QA.**

---

## 3. The "Bring Your Own Data" Advantage

As noted in the Lucent blogs, Lucent can actually sit *on top* of PostHog. This is a massive sales advantage.

If an Enterprise is already paying for Datadog or PostHog and capturing 100k sessions, they don't want to rip out their SDK. 

**Our Sales Pitch:** "Keep paying PostHog $0.005 to store your videos. Pay us $799/month to plug into your PostHog API and actually analyze those videos so your engineers don't have to."

---

## 4. Key Takeaways for Pricing Page Copy
*   **Don't hide the price.** Show the $399 and $799 clearly. It signals that this is a premium, high-ROI enterprise tool, not a cheap data-storage utility.
*   **Emphasize "Issue Detection."** The Starter plan highlights "3 Active Signals" and the Pro plan highlights "Unlimited." This needs to be the focal point of the pricing page. Buyers are paying for the *Signals*, not the *Sessions*.
*   **Highlight the ROI:** Add a calculator or a strong blurb on the pricing page: *"How many engineering hours do you spend watching replays? Lucent pays for itself if it saves a senior engineer just 4 hours a month."*
