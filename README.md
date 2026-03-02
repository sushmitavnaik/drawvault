# DrawVault: Construction Loan Draw Management Platform

A product case study demonstrating PM skills: Problem discovery, user research, product design, and business strategy.

---

## Table of Contents
1. [The Problem](#the-problem)
2. [Market Opportunity](#market-opportunity)
3. [The Solution](#the-solution)
4. [How It Works](#how-it-works)
5. [Business Model](#business-model)
6. [Go-to-Market Strategy](#go-to-market-strategy)
7. [Competitive Analysis](#competitive-analysis)
8. [Why DrawVault Wins](#why-drawvault-wins)
9. [Portfolio Lessons](#portfolio-lessons)

---

## The Problem

### Current State: The 13-Day Draw Cycle

In construction development, the **construction loan draw process** is where money actually moves. On a $100M project with $1M+ monthly draws, developers must coordinate documents from 50+ vendors (contractors, suppliers, subcontractors) before the bank will approve each draw.

**The current workflow:**
1. Developer requests invoices + lien waivers from vendors (email chaos)
2. Developer's team manually compiles documents (8-15 hours)
3. Developer submits to bank (often incomplete)
4. Bank finds 2-4 missing documents (more email back-and-forth)
5. Developer resubmits
6. Bank finally approves
7. **Total time: 13 days**

### Economic Impact

On a single $1M draw at 6% annual interest:
- **Each day of delay = $2,740 in unnecessary interest**
- **13-day cycle = $35,620 in wasted interest per draw**

For a large developer managing 5 concurrent $100M projects with 10-15 draws each:
- **Total annual cost: $1.8M - $2.7M in preventable interest**
- **Plus 450-900 hours annually of team time spent on coordination** (worth $45-90K in labor)

**Total waste per large developer: $2-3M per year**

### Where the Friction Actually Is

Research shows:
- **49% of contractors pay subcontractors before receiving draw funds from bank** (living off cash flow)
- **"Incomplete submissions are the #1 cause of draw delays"** (Land Gorilla, 2024)
- **Average time to compile a draw package: 20-25 hours per draw**
- **Document error rate: 15-30%** (invoices, lien waivers, amounts don't match)

### Root Cause

It's not the bank's process that's slow. **It's vendor coordination.**

Developers are juggling:
- 50+ vendors submitting documents via email, WhatsApp, carrier pigeon
- No single source of truth (documents scattered across Gmail, shared folders, Slack)
- Manual tracking (spreadsheets, often outdated)
- Lots of back-and-forth (missing signatures, incomplete info, wrong forms)

---

## Market Opportunity

### Target Market

**Primary:** Mid-market real estate development firms
- 50-500 employees
- Managing $100M-$500M in concurrent development projects
- 5-15 active projects at any time
- Processing 40-100 construction draws per year

**Secondary:** Construction lenders (banks, hard money lenders)
- Want to process borrower draws faster
- Frustrated by incomplete submissions
- Would incentivize borrowers to use cleaner processes

### Market Size (TAM)

**US Market:**
- ~1,200 active real estate development firms
- Average $100-300M in annual project volume per firm
- Average 50-100 draws per year per firm
- Total draws processed annually: 60,000-120,000 in US alone

**Current spending per developer:**
- CoStar subscriptions: $36-60K/year
- Consultant fees: $100-600K/year (if using for all deals)
- Internal labor costs: $1-2M/year (40-50 people × 10-20% of time on draw coordination)
- **Total: $1-3M per large developer annually on draw-related costs**

**TAM Calculation:**
- 1,200 development firms × $1.5M average annual waste = **$1.8B TAM**

---

## The Solution

### Core Value Proposition

**"Turn a 13-day draw cycle into 8 days. Manage 50+ vendors on one platform instead of email chaos."**

DrawVault is a **vendor portal + developer dashboard + bank visibility** platform that:

1. **Vendors submit once** (invoices + lien waivers digitally, in 5 minutes)
2. **Developers approve in one place** (not email threads, spreadsheets, or chasing vendors)
3. **Banks see the complete package** (no surprises, no back-and-forth)
4. **Missing documents are automatically flagged** (system tells you what's needed)
5. **Draw approval is 3-5 days faster**

### Key Features (MVP)

**Vendor Portal:**
- Simple form: Upload invoice PDF + select lien waiver type
- Auto-generated lien waiver (state-specific, correctly formatted)
- E-signature for lien waiver
- Takes vendor 5 minutes to complete

**Developer Dashboard:**
- Real-time view of all vendor submissions
- Submission status for each vendor (✓ approved, ⚠️ flagged, ✗ missing)
- One-click approval/rejection workflow
- Automated reminders to missing vendors
- Budget reconciliation (compare invoices to contract amounts)

**Bank Portal:**
- Read-only access to all documents
- See what's ready vs. what's missing
- One-click approval (no email back-and-forth)

**Document Automation:**
- PDF export of complete draw package
- Organized: Cover sheet + all invoices + all lien waivers
- Audit trail: Who approved what, when

---

## How It Works

### The Draw Cycle with DrawVault

**Day 1: Milestone Completion**
- GC completes foundation milestone
- Developer clicks "Create Draw" in DrawVault
- System auto-populates vendor list and expected amounts
- Automated emails sent to vendors: "Submit your invoice + lien waiver"

**Days 1-2: Vendor Submission**
- Vendors log into DrawVault portal
- Submit invoice (PDF) + sign lien waiver (e-signature)
- System validates: Invoice readable, lien waiver signed, amount reasonable
- Status shows in developer dashboard instantly

**Days 2-3: Developer Review & Approval**
- Developer sees dashboard: "7 of 9 vendors submitted"
- Reviews each invoice and lien waiver (takes 1-2 hours)
- Flags if amount is unusual (system highlights this)
- Approves complete submissions one-click
- Sends automated reminders to missing vendors

**Days 3-5: Bank Review & Approval**
- Bank logs into portal, sees complete package
- All documents organized, all vendors listed
- Bank approves in 4-6 hours (vs. 5-7 days of manual review)
- Can ask questions directly in platform (not email)

**Result:**
- **8-day cycle** (vs. 13-day baseline)
- **Developer saves 15-25 hours** per draw
- **Bank saves 5-7 days** of back-and-forth
- **Vendors submit once, not chased via email**

---

## Business Model

### Revenue Model: Per-Project SaaS

**Pricing by project size:**
- **Small project (<$25M):** $500/month
- **Medium project ($25-100M):** $1,000/month
- **Large project ($100M+):** $2,000/month

**Why this works:**
- Larger projects = more vendors = more value from consolidation
- Aligns with developer's project budget
- Easy to understand and sell

### Unit Economics (Year 1 Target)

**Assumptions:**
- Average project: $150M
- Average price: $1,200/month
- Average project length: 18 months (3 draws per project, then complete)
- LTV: $1,200 × 18 months = $21,600 per project

**Customer acquisition:**
- Broker referral partnerships: CAC $2-5K
- Lender requirements (no CAC): $0
- Average CAC: $3K

**LTV/CAC Ratio:** $21,600 / $3,000 = **7.2x** (excellent, typical SaaS is 3x)

**Year 2 Projections:**
- Target customers: 50 active projects
- ARR: $1,200/mo × 50 projects × 12 months = **$720K**
- Gross margin: 75% (software scales, minimal per-customer cost)

---

## Go-to-Market Strategy

### Phase 1: Founder Sales (Months 1-3)
- Direct outreach to developers in network
- Position as "MVP beta test"
- Offer free/discounted access in exchange for feedback
- Goal: 2-3 paying beta customers with real projects

### Phase 2: Broker Channel (Months 3-6)
- Partner with commercial real estate brokers (JLL, Cushman & Wakefield, etc.)
- Pitch: "Your clients waste $175K/year on draw coordination. Introduce them to DrawVault. We'll pay you 10% annual referral fee."
- Why it works: Brokers maintain developer relationships and want to provide value

### Phase 3: Lender Channel (Months 6-12)
- Approach construction lenders (banks, hard money)
- Pitch: "Your borrower packages are incomplete. Recommend DrawVault. You approve 3-5 days faster. Save ~$2,500/loan in operational cost."
- Pricing: Per-loan license or borrower pays
- Why it works: Banks have direct relationships with 100+ borrowers; one recommendation reaches many developers

### Distribution Advantage
Unlike most SaaS tools that require direct sales, DrawVault has:
- **Natural advocates:** Banks incentivized to recommend (faster approvals)
- **Network effect:** Vendors use across multiple projects
- **Switching cost:** Once dev team is in the system, switching is friction

---

## Competitive Analysis

### Existing Solutions & Why They Miss the Mark

| Competitor | Focus | Why It Fails |
|---|---|---|
| **Rabbet** | Lender-side automation | Developers use reluctantly (not vendor-focused) |
| **Land Gorilla** | Lender portal + borrower interface | Lender-first design; developer portal is an afterthought |
| **Siteline** | Vendor-side (subs + suppliers) | Solves vendor problem, not developer coordination problem |
| **Built** | Payment processing + lien waivers | Focused on ACH automation; doesn't solve submission workflow |
| **Oracle Textura** | Enterprise solution | $50K+/year; built for mega-projects only |
| **Northspyre** | Comprehensive draw management | Expensive ($50K+/year), complex, enterprise-focused |

### The Gap in the Market

Most tools are either:
1. **Lender-focused** → Developers use reluctantly
2. **Vendor-focused** → Don't solve developer coordination
3. **Payment-focused** → Don't solve submission workflow
4. **Enterprise-expensive** → Too costly for mid-market

**DrawVault fills the gap:** Developer-centric vendor submission + approval + bank visibility.

---

## Why DrawVault Wins

### 1. Solves the #1 Draw Delay Factor
**Problem:** "Incomplete submissions are the #1 cause of draw delays"  
**Solution:** DrawVault flags missing documents automatically. Vendors can't submit incomplete forms.

### 2. High Willingness to Pay
- Developers waste $2-3M/year on draw coordination
- Saving $13K per draw + 20 hours of team time = $1,000-2,000/month WTP
- ROI: 6-month payback

### 3. Distribution Built-In
- Not selling to 1,000 SMBs (expensive)
- Selling to 50-100 large developers + banks (relationship-driven)
- Banks incentivized to recommend (faster approvals = happy borrowers)

### 4. Data Moat
- Every draw processed teaches us what works
- Over time: Learn which vendors submit cleanly, which lien waiver formats work, which invoices have issues
- AI can predict/flag issues before they slow down draws
- Competitors can't replicate without years of data

### 5. Network Effects
- Vendors submit once, reuse across multiple projects
- Bank recommends to 100+ borrowers
- Switching cost increases (becomes integrated into workflow)

---

## Portfolio Lessons

### What This Case Study Demonstrates

**Product Thinking:**
- ✅ Deep problem understanding (quantified the cost)
- ✅ Clear target customer (mid-market developers, not everyone)
- ✅ Realistic solution (not over-engineered)
- ✅ Business model alignment (pricing matches customer value)

**Market Understanding:**
- ✅ TAM analysis ($1.8B market)
- ✅ Competitive positioning (clear differentiation)
- ✅ Distribution strategy (multiple channels, each with economics)
- ✅ Go-to-market roadmap (phased approach)

**Strategic Thinking:**
- ✅ Trade-offs made consciously (MVP scope, MVP pricing)
- ✅ Defensible moat (data advantage over time)
- ✅ Scalability path (from 2-3 customers → 50+ → national)
- ✅ Risk mitigation (hybrid approach: no-code validation before full build)

### What I Did NOT Do

- ❌ Didn't design a "perfect" product (MVP focuses on core)
- ❌ Didn't build a working app (waste of time without customer validation)
- ❌ Didn't try to solve for all real estate types (start with apartments, expand later)
- ❌ Didn't try to go national (Austin-only MVP, then expand)

**This is the discipline of a good PM:** Ruthless prioritization. Ship the core, learn from market, iterate.

---

## Next Steps

If I were to build this:

1. **Month 1:** Validate the problem
   - Interview 10 developers on $100M+ projects
   - Confirm time waste (20-25 hours per draw?)
   - Confirm willingness to pay ($1K-2K/month?)

2. **Month 2:** Build MVP
   - Hire one solid full-stack engineer ($30-50K)
   - Focus on vendor portal + developer approval + bank visibility
   - 8-10 weeks of build

3. **Month 3:** Close beta customers
   - Get 2-3 real projects live
   - Measure time savings (goal: 8 days vs. 13)
   - Get testimonials: "We saved $X, Y hours per draw"

4. **Month 4+:** Scale
   - Approach lenders with proof-of-concept
   - Broker partnerships
   - Raise seed funding if metrics are strong

---

## Resources & Links

- **Prototype:** [Add link to Figma prototype here]
- **Pitch Deck:** [Add link to investor pitch deck here]
- **Landing Page:** [Add link to landing page here]

---

## Questions?

This case study was created as a portfolio project to demonstrate product thinking, market analysis, and strategic planning.

If you have questions about the product, strategy, or approach, feel free to reach out.

---

*Last updated: February 2024*
