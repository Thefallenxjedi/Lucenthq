# Cost Per Recording Report: LucentHQ vs. PostHog

To accurately position LucentHQ, we need to understand the exact mathematical difference in "Cost Per Recording" compared to PostHog's usage-based tiers. 

PostHog's pricing is extremely aggressive on volume. To win, LucentHQ must emphasize that our cost includes **100% automated AI analysis**, whereas PostHog only covers the storage and hosting of the video.

## 1. Direct Side-by-Side Comparison (10k & 30k Tiers)

To quickly compare the core tiers that LucentHQ offers against PostHog's equivalents:

| Volume Tier | PostHog (Web) | PostHog (Mobile) | LucentHQ |
| :--- | :--- | :--- | :--- |
| **10k Sessions** | $50.00 | $100.00* | **$399.00** |
| **~30k Sessions** | $113.75 *(for 32.5k)* | $227.50 *(for 32.5k)* | **$799.00** *(for 30k)* |

*(Note: PostHog Mobile at 10k calculated using their $0.0100 tier rate).*

---

## 2. Full Pricing Data Breakdown

### PostHog Pricing (Web & Mobile Session Replay)

Here is a direct look at the aggressive scaling of PostHog's usage-based pricing:

<img src="/Users/sourabhk/.gemini/antigravity/brain/0c0e7a90-b5f5-437b-af6a-e26e0f3a8afc/media__1781680155250.png" width="400" alt="PostHog Pricing Screenshot" style="border-radius: 8px; margin-top: 10px; margin-bottom: 20px;" />

| Service Type | Volume Tier | Price per Recording | Total Cost |
| :--- | :--- | :--- | :--- |
| **Session Replay (Web)** | First 5k recordings | Free | $0.00 |
| **Session Replay (Web)** | 10k | $0.0050 / recording | $50.00 |
| **Session Replay (Web)** | 32.5k | $0.0035 / recording | $113.75 |
| **Session Replay (Web)** | 100k | $0.0020 / recording | $200.00 |
| **Session Replay (Web)** | 325k | $0.0017 / recording | $552.50 |
| **Session Replay (Web)** | 500k+ | $0.0015 / recording | $750.00 per 500k |
| | | | |
| **Mobile Session Replay**| First 2.5k recordings | Free | $0.00 |
| **Mobile Session Replay**| 8.75k | $0.0100 / recording | $87.50 |
| **Mobile Session Replay**| 32.5k | $0.0070 / recording | $227.50 |
| **Mobile Session Replay**| 100k | $0.0040 / recording | $400.00 |
| **Mobile Session Replay**| 325k | $0.0034 / recording | $1,105.00 |
| **Mobile Session Replay**| 500k+ | $0.0030 / recording | $1,500.00 per 500k |

### LucentHQ Pricing

| Service Type | Volume Tier | Price per Recording | Total Cost |
| :--- | :--- | :--- | :--- |
| **Starter Plan** | 10k sessions | $0.0399 / session | $399.00 |
| **Pro Plan** | 30k sessions | $0.0266 / session | $799.00 |
| **Enterprise Plan** | Unlimited sessions | Custom | Custom |

---

## 3. How to Justify the Price Difference

Because Lucent's cost per session is roughly **$0.02 to $0.04**, while PostHog is **fractions of a penny**, we cannot sell Lucent as a 1:1 PostHog alternative. 

We must frame the pricing around **Total Cost of Ownership (TCO)**.

### The Sales Narrative:
> *"PostHog charges you fractions of a cent to store a video that you will never watch. Lucent charges you $0.03 to have an AI QA Engineer watch that video for you, analyze the DOM state, and write a Jira ticket when it finds a bug."*

*   **The PostHog Math:** \$50.00 for the software + \$150,000/yr for the engineer to watch the videos.
*   **The Lucent Math:** \$399.00 for the software + \$0 for manual analysis.

### Feature Differentiation for the Pricing Page:
If a user is comparing Lucent to PostHog, they need to see exactly why they are paying a premium. We must clearly list:
1. **Automated AI Issue Detection:** PostHog makes you filter for "rage clicks" manually. Lucent flags them automatically.
2. **Weekly Insights Reports:** Lucent acts like an employee handing you a weekly summary of product health.
3. **No Integration Tax:** Lucent can read PostHog's existing data, meaning companies don't have to choose between the two. They can use PostHog for Analytics and Lucent for Automated AI Bug Catching.
