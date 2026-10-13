# Influencer Ad & Conversion Performance Dashboard

A consolidated reporting dashboard built with **HTML** and **Tailwind CSS v4** designed for an influencer partnering with multiple brands across **Instagram**, **TikTok**, and **YouTube**.

---

## 🌟 Executive Answers to Core Business Questions

| Core Question | Consolidated Dashboard Answer | Metric / Insight |
| :--- | :--- | :--- |
| **1. How much money am I generating in commissions?** | **€8,070.00** this month (+18.4% MoM) | 15% fixed commission on €53,800 gross sales |
| **2. Which products are generating the most revenue?** | **Product B (€120.00)** | Generated **€21,000.00 gross** and **€3,150.00 in commissions** (175 units sold) |
| **3. How well are my ads converting?** | **3.87% click-to-sale** (0.35% reach-to-sale) | 705 total sales from 18,200 clicks across 201,000 unique reach |
| **4. Which platforms are generating the best return?** | **TikTok** with **9.5x ROAS** (Commission / Ad Cost) | Generated €2,385 commission on €250 production/ad cost |
| **5. What is the engagement rate by platform & product?** | **TikTok leads at 7.2%**, followed by IG (5.4%) and YouTube (4.1%) | **Product A** drove the highest engagement rate (6.8%) |

---

## 💼 Business Context & Product Economics

The influencer promotes 3 core partner products on a **fixed 15% commission model**:

- **Product A (Glow Skincare Routine)**:
  - Retail Price: **€50.00**
  - Commission per Sale (15%): **€7.50**
  - Units Sold: **320 units** (Volume Leader)
  - Gross Sales: **€16,000.00** | Total Commission Earned: **€2,400.00**
  - Conversion Rate: **3.76%**
- **Product B (CreatorPro Audio Kit)**:
  - Retail Price: **€120.00**
  - Commission per Sale (15%): **€18.00**
  - Units Sold: **175 units**
  - Gross Sales: **€21,000.00** (Revenue Leader) | Total Commission Earned: **€3,150.00** (Commission Leader)
  - Conversion Rate: **2.82%**
- **Product C (ErgoFlow Desk Pad Set)**:
  - Retail Price: **€80.00**
  - Commission per Sale (15%): **€12.00**
  - Units Sold: **210 units**
  - Gross Sales: **€16,800.00** | Total Commission Earned: **€2,520.00**
  - Conversion Rate: **3.88%** (Conversion Leader)

---

## 📐 Dashboard Architecture: 3 Organised Blocks

### 1️⃣ Top Block: Main Outcome Indicators (KPIs)
- **Influencer Commission**: €8,070.00 (+18.4% MoM, 80.7% towards €10k monthly target)
- **Gross Brand Sales**: €53,800.00 across 705 total customer orders (ASP: €76.31)
- **Ad Conversion Rate**: 3.87% click-to-sale (0.35% reach-to-sale, 9.05% CTR)
- **Unique Audience Reach**: 201,000 accounts reached (942,000 total ad impressions)
- **Secondary Efficiency Metrics**: Average Commission/Sale (€11.45), Net Profit (€7,070 at 87.6% margin), Audience NPS (78/100).

### 2️⃣ Middle Block: "Drivers" (What Explains the Outcome)
- **Driver 1: Conversion by Stage (Sales Funnel)**:
  - Tracks Impressions (942k) → Reach (201k) → Link Clicks (18.2k) → Add-to-Cart (2,180) → Paid Sales (705).
- **Driver 2: Performance by Platform (ROI & Channels)**:
  - Side-by-side comparison between Instagram (€3,930 comm., 8.7x return), TikTok (€2,385 comm., 9.5x return, 7.2% engagement), and YouTube (€1,755 comm., 5.9x return).
- **Driver 3: Performance by Product**:
  - Highlights the contrast between volume leadership (Product A: 320 units), revenue leadership (Product B: €21,000), and conversion efficiency (Product C: 3.88%).
- **Driver 4: Activity & Interaction Quality**:
  - Visual breakdown of 38 content assets and 125,930 interactions (Likes, Comments, Shares, Saves).

### 3️⃣ Bottom Block: Operational Details & Real-Time Alerts
- **Real-Time Alerts & Anomaly Monitor**:
  - 🟢 *Conversion Spike*: TikTok Reel #4 viral boost (+240% conversions for Product B).
  - 🟡 *Conversion Drop Warning*: Sunday Instagram Story link tap-through dip.
  - 💡 *Opportunity*: Product A + C bundle recommendation (+€950/mo potential).
  - ℹ️ *Stock / Link Health*: 100% affiliate links active and verified.
- **Table 1: Products Performance**: Prices, commission rates, units sold, sales, commissions, conversion rates.
- **Table 2: Social Media Platforms**: Posts, reach, engagement, clicks, conversions, commission, costs, ROAS.
- **Table 3: Recent Sponsored Campaigns**: Content titles, formats, products, reach, clicks, sales, commission, performance grades.
- **Strategic Roadmap**: 3 actionable next steps for the influencer's upcoming month.

---

## 🛠️ Technology Stack & Compliance

- **Pure HTML5** semantic structure
- **Tailwind CSS v4** via the official browser CDN script:
  ```html
  <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
  ```
- **Custom CSS** (`styles.css`) for fine-grained media queries, custom scrollbars, and print stylesheets
- **Zero Frameworks**: No React, Vue, or heavy dependencies
- **Mobile-First Responsive Design**: Optimized across mobile (`<640px`), tablet (`640px - 1024px`), and desktop (`>1024px`).
