# The 101st Day Epilogue
## What Happens After the Campaign Ends

> "Shipping is where the profit goes to die."

Most guides stop at "Congratulations, you're funded!" This is where the real operations begin. The 101st day is the first day your backers stop caring about your story and start caring about their package.

---

## Table of Contents
1. [The "Money-In" Period](#1-the-money-in-period-days-114)
2. [The Backer Survey (Data Harvest)](#2-the-backer-survey-the-data-harvest)
3. [Manufacturing & QC Execution](#3-manufacturing--qc-execution)
4. [The Global Logistics Puzzle](#4-the-global-logistics-puzzle)
5. [Post-Delivery Support & Second Wave](#5-post-delivery-support--the-second-wave)
6. [The Uncomfortable Truth](#6-the-uncomfortable-truth)

---

## 1. The "Money-In" Period (Days 1–14)

Platforms take roughly 14 days to process funds.

### Failed Payment Protocol
Roughly 3-5% of credit cards will fail.
- **Action:** Direct message every "Dropped Backer" via platform messaging.
- **Window:** 48-hour deadline to update payment info before losing Early Bird spot.
- **Reality:** ~50% of dropped backers will recover. The rest are gone.

### Net Payout Calculation
Your actual budget is NOT the total funded amount:

| Deduction | Percentage |
|---|---|
| Platform fee | ~5% |
| Payment processing | ~3-5% |
| Failed payments | ~3-5% |
| **Effective net** | **~85-89% of gross** |

Plan your manufacturing budget against the **net**, not the headline number.

---

## 2. The Backer Survey (The Data Harvest)

**Do not** use the platform's native survey for complex products. Use a dedicated **Pledge Manager** (BackerKit, PledgeManager, or equivalent).

### What You Collect
- Shipping addresses (validated)
- Color/size/variant selections
- Add-on upsells (this is your last chance to increase AOV)

### The "Shipping Gap" Strategy
If you didn't charge shipping during the campaign → charge it now.
- **Why:** Protects against fluctuating freight costs.
- **Timing:** Do this within 30 days of campaign close while excitement is high.

### VAT/Tax Collection
**Critical for EU/UK/AU backers:**
- Collect VAT/GST at survey stage
- Failure to do this = "Customs Nightmares" where backers refuse delivery or demand refunds
- Use a VAT compliance service (e.g., Taxamo, Zonos) if shipping to 10+ countries

---

## 3. Manufacturing & QC Execution

### The Sample Lock
Never start mass production until you have a **Golden Sample** in hand that is 100% identical to the final product.

Refer to: [Quality-Control-Deep-Dive.md](./Quality-Control-Deep-Dive.md) for the full QC protocol.

### Weekly Production Updates
Even if there is no news — tell the backers.

Examples:
- "The molds are being cooled."
- "The fabric has arrived at the warehouse."
- "AQL inspection is scheduled for next Tuesday."

**The Rule:** Silence = Anxiety = Refund requests.

### The 10% Buffer
Always order **10% more stock** than needed for backers:
- Shipping damages (~2-3%)
- Lost packages (~1-2%)
- DOA (Dead on Arrival) replacements (~1-2%)
- Future warranty claims

This is not waste — it's insurance.

---

## 4. The Global Logistics Puzzle

### Warehouse Strategy

| Volume | Strategy | Pros | Cons |
|---|---|---|---|
| **Low** (< 500 units) | Ship from one central hub (HK or home country) | Simple, one relationship | Slow delivery, high per-unit shipping |
| **High** (500+ units) | Regional hubs (USA, EU, Asia) | Fast delivery, lower customs friction | Complex, multiple 3PL relationships |

### 3PL Integration
Ensure your Third-Party Logistics provider integrates with your Pledge Manager so:
- Tracking numbers are generated automatically
- Backers get shipping notifications without manual work
- You have real-time visibility into fulfillment progress

### The Weight Trap
Always weigh your **final packaging** with the product and **all inserts** before setting shipping prices.

A product that weighs 480g might seem safe in the "under 500g" tier. Add the manual, the thank-you card, and the protective foam → suddenly it's 520g and you're in the next price bracket.

> **Field Note:** "In the Baggizmo campaign, shipping a box is one price, but shipping a box with an extra accessory can sometimes double the weight category. A 100g mistake costs $10,000 across 1,000 backers."

---

## 5. Post-Delivery Support & The Second Wave

### The 30-Day Warranty
Define a clear policy **before** products ship:
- What qualifies as DOA (Dead on Arrival)
- Response time commitment (e.g., 48 hours)
- Replacement vs. refund criteria
- Who pays return shipping

### The Second Wave of Sales
The campaign ending is not the end. It's a transition:

1. **Indiegogo InDemand** — Migrate immediately. Captures late-comers at full retail.
2. **Shopify / Direct Store** — Build while fulfilling. Use backer unboxing content as social proof.
3. **The Momentum Effect** — When backers start receiving products and posting photos → organic traffic spikes. Be ready to capture it.

---

## 6. The Uncomfortable Truth

Most crowdfunding "success stories" gloss over the post-campaign reality:

- **20-30% of your margin** will be consumed by logistics you didn't plan for.
- **Customer support volume** peaks 2-4 weeks after first deliveries (not during the campaign).
- **Your reputation** is built in the fulfillment phase, not the funding phase. A campaign that funds $500K but delivers late with quality issues is a failure. A campaign that funds $50K and delivers on time with quality is a launchpad.

This is why we build the fulfillment architecture **before** launch, not after. The 101st day shouldn't be a surprise — it should be the execution of a plan that was ready on Day 0.

---

## The Post-Campaign Checklist

- [ ] Net payout calculated (after all fees and failed payments)
- [ ] Pledge Manager live within 14 days of close
- [ ] VAT/GST collection configured for international backers
- [ ] Golden Sample approved before mass production order
- [ ] 10% buffer stock ordered
- [ ] 3PL selected and integrated with Pledge Manager
- [ ] Final packaging weighed with all inserts
- [ ] 30-Day warranty policy documented
- [ ] InDemand or Shopify pre-order page ready for migration
- [ ] Weekly backer update cadence scheduled

---

*Juric OS — Operations Architecture | Proof Before Promise™*
