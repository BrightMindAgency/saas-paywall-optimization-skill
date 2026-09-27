# 💳 SaaS Paywall Optimization Skill

> **High-converting SaaS & mobile app paywall architecture and CRO playbook based on 7 battle-tested monetization levers.**

Created and maintained by **Stay Bright** & **Bright Mind Agency AB**.

---

## 🌟 Overview

The **SaaS Paywall Optimization Skill** (`saas-paywall-optimization`) is an actionable conversion rate optimization (CRO) playbook designed to elevate mobile and SaaS apps from standard 2–3% conversion benchmarks to high-converting subscription engines.

Built on 7 battle-tested behavioral psychology and pricing levers, this skill guides autonomous AI agents and product teams in auditing, designing, and optimizing paywalls, onboarding checkout funnels, and subscription flows.

---

## 🏗️ The 7 Core Conversion Levers

1. **Anchor High First (Price Anchoring)**
   - Default to the highest-value / annual tier or place it at the top of the stack.
   - Display the annual price broken down to weekly or monthly equivalent (e.g. `$1.90/week` billed annually).
   - Documented impact: Up to **+28% ARR** lift in 14 days without changing incoming traffic.

2. **The 3-Item Feature Checklist (Cognitive Load Reduction)**
   - Strip lengthy 10–15 bullet feature matrices down to strictly 3 high-impact trigger items:
     - **Pain Relief:** The direct solution to their immediate frustration.
     - **Speed/Efficiency Gain:** How it accelerates results.
     - **Exclusive Unlock:** The premium feature or moat.
   - Documented impact: **-40% time on screen**, **+19% conversion lift**.

3. **Reverse Trial vs. Hard Paywall (Experiential Value Realization)**
   - Replace immediate hard paywalls at install with a 3-day reverse trial (full Pro access without upfront credit card).
   - Trigger the paywall on Day 3 precisely when the user completes a core habit-forming loop.
   - Documented impact: **~72% conversion** on Day 3 vs ~8% on Day 1 install paywalls.

4. **Exit-Intent Downgrade Offer (Abandonment Recovery)**
   - Intercept paywall dismissal (`X` close button or back navigation) with an extension modal or lower-tier option.
   - Options: 7-day trial extension, lighter tier downsell ($4.99/mo), or a 40% introductory discount.
   - Documented impact: Recovers **14–18% of abandoning sessions**.

5. **Decision-Point Social Proof (Buyer Hesitation Neutralization)**
   - Place credible ratings, user counts, or testimonials immediately above the primary action button.
   - Format: `★★★★★ 4.9/5 from 12,400+ reviews` or a single hyper-relevant micro-quote.
   - Documented impact: **+23% lift** in checkout completion.

6. **Transparent Risk Reversal (Cancellation Assurance)**
   - Eliminate fear of hidden charges or dark patterns with explicit cancellation copy directly below the primary CTA:
     - *"Cancel anytime in 1 tap from Settings. No questions asked."*
     - *"We'll email you a reminder 2 days before your trial ends."*
   - Documented impact: Reduces payment disputes/chargebacks by **-61%** while raising trial starts by **+31%**.

7. **Personalized Paywall Header (Identity Alignment)**
   - Dynamically populate the paywall hero section with user inputs collected during onboarding.
   - Example: *"Here is your custom Save 5 Hours/Week Plan, Sibbe"*.
   - Documented impact: Personalized headlines convert at up to **2.4x the rate** of generic static headers.

---

## 📐 High-Converting Layout Architecture

```text
┌──────────────────────────────────────────────────────────┐
│  [X] Close (Triggers Exit-Intent Modal)                  │
│                                                          │
│  [Dynamic Personalized Header]                           │
│  "Here is your custom [Goal] Plan for [Name]"            │
│  Subhead: One sentence stating core transformation.      │
│                                                          │
│  ┌────────────────────────────────────────────────────┐  │
│  │  3-ITEM FEATURE CHECKLIST                          │  │
│  │  ✓ Pain Relief: Eliminate [friction point]         │  │
│  │  ✓ Speed/Gain: Achieve [result] in half the time   │  │
│  │  ✓ Exclusive Unlock: Full access to [pro feature]  │  │
│  └────────────────────────────────────────────────────┘  │
│                                                          │
│  ┌────────────────────────────────────────────────────┐  │
│  │  [●] ANNUAL (DEFAULT)  | $99/year ($1.90/wk)       │  │
│  │      [BEST VALUE TAG]  | Save 40%                  │  │
│  │  [○] MONTHLY           | $14.99/month              │  │
│  └────────────────────────────────────────────────────┘  │
│                                                          │
│  ★★★★★ 4.9/5 from 12,000+ active users                   │
│                                                          │
│  ┌────────────────────────────────────────────────────┐  │
│  │  [ START 3-DAY FREE TRIAL / UNLOCK ACCESS ] (CTA)  │  │
│  └────────────────────────────────────────────────────┘  │
│                                                          │
│  "Cancel anytime in 1 tap from Settings. No lock-in."    │
│  "We'll remind you 2 days before trial ends."            │
└──────────────────────────────────────────────────────────┘
```

---

## 💻 Installation

### For Hermes Agent
Clone directly into your local skills directory:
```bash
git clone https://github.com/BrightMindAgency/saas-paywall-optimization-skill.git ~/.hermes/skills/marketing/saas-paywall-optimization
```

### For Claude Code, Cursor, Codex & OpenCode
Add to your project's `AGENTS.md` or `CLAUDE.md`:
```markdown
# Paywall & Monetization Standard
Load and apply the SaaS Paywall Optimization Skill (`saas-paywall-optimization`).
- Anchor high first (Annual tier default)
- Strictly 3 high-impact feature bullets (Pain Relief, Speed Gain, Exclusive Unlock)
- Position social proof directly above primary CTA
- Include clear 1-tap cancellation assurance below CTA
- Intercept dismissal with an exit-intent trial extension or downgrade
```

---

## 🛡️ License
MIT © 2026 Stay Bright & Bright Mind Agency AB.
