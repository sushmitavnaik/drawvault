# DrawVault: Construction Loan Draw Management Platform

A product case study demonstrating PM skills: Problem discovery, user research, product design, and business strategy.

---

## Table of Contents
1. [The Problem](#the-problem)
2. [Market Opportunity](#market-opportunity)
3. [The Solution](#the-solution)
4. [Interactive Prototype](#-interactive-prototype)
5. [How It Works](#how-it-works)
6. [Business Model](#business-model)
7. [Go-to-Market Strategy](#go-to-market-strategy)
8. [Competitive Analysis](#competitive-analysis)
9. [Why DrawVault Wins](#why-drawvault-wins)
10. [Portfolio Lessons](#portfolio-lessons)

---

## The Problem

### Current State: The 13-Day Draw Cycle

In construction development, the **construction loan draw process** is where money actually moves. On a $100M project with $1M+ monthly draws, developers must coordinate documents from 50+ vendors (contractors, suppliers, subcontractors) before the bank will approve each draw.

**The current workflow:**
1. Developer manually emails 50+ vendors requesting invoices + lien waivers
2. Vendors submit documents via email, WhatsApp, or shared folders (chaos)
3. Developer's team manually compiles documents (8-15 hours)
4. Developer submits incomplete package to bank
5. Bank finds 2-4 missing documents, asks for resubmission
6. Developer chases vendors again for missing docs
7. Developer resubmits
8. Bank finally approves
9. **Total time: 13 days**

### Economic Impact

**Operational Costs of the 13-Day Delay:**

For a single $1M draw:
- Construction project paused waiting for funds (equipment sitting idle, crews waiting)
- Contractors can't pay subcontractors on time (cash flow disruption down the supply chain)
- Developer pays out of pocket to keep work moving, then waits for reimbursement

For a large developer managing 5 concurrent $100M projects with 10-15 draws each:
- **450-900 hours annually spent on draw coordination** (worth $45-90K in labor)
- **Delays cascade:** Each day without funds = equipment costs, crew downtime, subcontractor payment delays
- **Operational disruption:** Projects fall behind schedule, costs increase, cash flow tightens

**Total waste per large developer: $500K-2M per year** (labor + operational disruptions)

### Where the Friction Actually Is

Research shows:
- **49% of contractors pay subcontractors before receiving draw funds from bank** (living off cash flow)
- **"Incomplete submissions are the #1 cause of draw delays"** (Land Gorilla, 2024)
- **Average time to compile a draw package: 20-25 hours per draw**
- **Document error rate: 15-30%** (invoices, lien waivers, amounts don't match)

### Root Cause

It's not the bank's process that's slow. **It's vendor coordination.**

Developers are juggling:
- 50+ vendors submitting documents via email, WhatsApp, shared folders
- No single source of truth (documents scattered across Gmail, shared folders, Slack)
- Manual tracking (spreadsheets, often outdated)
- Lots of back-and-forth (missing signatures, incomplete info, wrong forms)
- Chasing vendors every month for the same documents

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

**"Centralize vendor submissions. Eliminate email chaos. Get paid 5 days faster."**

DrawVault is a **vendor portal + developer dashboard + bank visibility** platform that:

1. **Developers build vendor rosters once** (assign contractors to projects)
2. **Monthly invitations go out automatically** (one click to send to all project vendors)
3. **Vendors who have work submit in 5 minutes** (invoice + signed lien waiver)
4. **Vendors without work that month do nothing** (no follow-up needed)
5. **Developer reviews the complete package in one place** (organized, automated, flagged for issues)
6. **Bank approves same day** (complete package, all documents ready)
7. **Loan is released** (faster cash flow for everyone)

### Key Features (MVP)

**Developer Dashboard:**
- Create projects and assign vendor rosters
- One-click monthly draw invitations
- Real-time vendor submission tracking ("8 of 12 vendors submitted")
- Review submitted documents (invoice + lien waiver)
- Flag issues or request changes
- Finalize and submit package to bank

**Vendor Portal:**
- Receive monthly draw invitation (email + link)
- One-time login (or stay logged in)
- If you have work this month: Upload invoice PDF + fill/sign lien waiver
- If no work this month: Ignore (no follow-up)
- Submit in 5 minutes
- Get confirmation

**Bank Portal:**
- View all pending draws
- Click to review complete package
- All invoices and lien waivers organized by vendor
- Approve or request additional info
- Release funds with one click

**Document Automation:**
- PDF export of complete draw package
- Organized: Cover sheet + all invoices + all lien waivers
- Auto-generated state-specific lien waiver forms
- Audit trail: Who approved what, when

---

## 🎬 Interactive Prototype

Experience DrawVault from 3 different user perspectives:

| User Type | Prototype Link | Flow Summary |
|-----------|---|---|
| **👷 Vendor** | <a href="https://www.figma.com/proto/XTC8J4t3K5trqody4UITAb/DrawVault-Prototype?node-id=1-2&t=P0P4vN2oS9e8Ab48-1" target="_blank">Start here →</a> | Receive invite → Upload invoice & lien waiver → Submit → Done |
| **👨‍💼 Developer** | <a href="https://www.figma.com/proto/XTC8J4t3K5trqody4UITAb/DrawVault-Prototype?node-id=38-55&t=P0P4vN2oS9e8Ab48-1" target="_blank">Start here →</a> | Manage vendors → Send invites → Review submissions → Finalize → Submit to bank |
| **🏦 Bank** | <a href="https://www.figma.com/proto/XTC8J4t3K5trqody4UITAb/DrawVault-Prototype?node-id=32-36&t=P0P4vN2oS9e8Ab48-1" target="_blank">Start here →</a> | View pending draws → Review package → Approve → Release funds |

**How to use:** Click any link above, then use the play button (▶️) to navigate through the flow. Each journey takes 2-3 minutes.

---

## How It Works

### The Monthly Draw Cycle

**Setup (One-time per project):**
- Developer logs into DrawVault
- Creates project: "Acme Tower - Foundation Phase"
- Adds vendor roster from their database (GC, Plumber, Electrician, Concrete supplier, etc.)

**Step 1: Developer Initiates Monthly Draw (Day 1)**
- Developer clicks "Create New Draw" for Acme Tower
- Selects month: "February 2026"
- Clicks "Send Invitations to All Vendors"
- System automatically sends emails to all 12 project vendors with unique submission link

**Step 2: Vendor Submission Window (Days 1-7)**
- **Vendors WITH work this month:**
  - Receive email with submission link
  - Log into vendor portal (5 minutes)
  - Upload invoice PDF (work completed)
  - Fill out and e-sign lien waiver form
  - Click "Submit"
  - Get confirmation: "✓ Your submission has been received"
- **Vendors WITHOUT work this month:**
  - Receive email but ignore it (no action needed)
  - Developer's dashboard automatically shows them as "Inactive this month"

**Developer's Dashboard (Day 1-7):**
- Real-time tracking: "Submission Status: 8 of 12 vendors submitted"
- Shows which vendors submitted, which are inactive, which are missing
- Can send automated reminders to vendors who haven't submitted

**Step 3: Developer Review & Finalization (Days 7-12, ~5 days)**
- Developer logs in and reviews only the vendors who submitted (8 submissions)
- For each vendor:
  - Verifies invoice matches scope of work
  - Checks lien waiver is properly signed
  - Flags any discrepancies or unusual amounts
  - Approves or requests additional info
- Once all documents are verified, clicks "Finalize Draw Package"
- System creates organized PDF package: Cover sheet + 8 invoices + 8 lien waivers
- Developer clicks "Submit to Bank"

**Step 4: Bank Review & Approval (Days 12-15)**
- Bank receives notification that new draw package is ready
- Bank logs in to bank portal
- Reviews complete draw package:
  - All invoices organized by vendor
  - All lien waivers present and signed
  - No missing documents
  - Coverage checklist: ✓ All invoices ✓ All liens ✓ No new liens on property
- Bank can approve in 4-6 hours (vs. 5-7 days of manual email back-and-forth)
- Bank clicks "Approve Draw"
- Loan amount for the month is released to developer

### Before vs. After DrawVault

**Before (13-day cycle):**
- Manual vendor emails (3-5 hours)
- Documents scattered across email/Slack/drives
- Spreadsheet tracking (outdated)
- Chasing missing docs (8-10 hours)
- Bank manual review (5-7 days)
- Multiple resubmissions
- $35K+ in interest costs per draw

**With DrawVault (8-day cycle):**
- One-click invitations (5 minutes)
- Organized digital portal
- Real-time submission tracking
- No chasing (vendors submit by deadline or aren't included)
- Bank approves same day (4-6 hours)
- One submission to bank
- Zero additional interest costs

### Key Workflow Advantages

✓ **Flexible vendor participation** - Only vendors with work that month submit  
✓ **Deadline enforcement** - Submit by date or you're not included in draw  
✓ **No wasted follow-up** - Inactive vendors don't get chased  
✓ **Organized packages** - Bank sees everything instantly  
✓ **Reduced errors** - Auto-generated forms prevent common mistakes  
✓ **Faster cash flow** - Lenders approve complete packages same day  
✓ **Audit trail** - Everything tracked who approved what and when  

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
- Average project length: 18 months (typical construction timeline)
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
- Measure: Time saved per draw, vendor satisfaction

### Phase 2: Broker Channel (Months 3-6)
- Partner with commercial real estate brokers (JLL, Cushman & Wakefield, etc.)
- Pitch: "Your clients waste $175K/year on draw coordination. Introduce them to DrawVault. We'll pay you 10% annual referral fee."
- Why it works: Brokers maintain developer relationships and want to provide value
- Target: 5-10 broker partnerships

### Phase 3: Lender Channel (Months 6-12)
- Approach construction lenders (banks, hard money)
- Pitch: "Your borrower packages are incomplete. Recommend DrawVault. You approve 3-5 days faster. Save ~$2,500/loan in operational cost."
- Pricing: Per-loan license or borrower pays
- Why it works: Banks have direct relationships with 100+ borrowers; one recommendation reaches many developers
- Target: 3-5 major lenders

### Distribution Advantage
Unlike most SaaS tools that require direct sales, DrawVault has:
- **Natural advocates:** Banks incentivized to recommend (faster approvals = happy borrowers)
- **Network effect:** Vendors use platform across multiple projects
- **Switching cost:** Once developer team is using the system, switching is friction
- **Low churn:** Developers can't leave without disrupting monthly cash flow

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

**DrawVault fills the gap:** Developer-centric vendor submission + approval + bank visibility, affordable for mid-market.

---

## Why DrawVault Wins

### 1. Solves the #1 Draw Delay Factor
**Problem:** "Incomplete submissions are the #1 cause of draw delays"  
**Solution:** DrawVault eliminates incomplete submissions by automating vendor invitations, tracking submissions in real-time, and organizing everything before it goes to the bank.

### 2. High Willingness to Pay
- Developers waste $500K-2M/year on draw coordination
- Saving $45-90K annually in labor + operational efficiency = $1,000-2,000/month WTP
- ROI: 6-month payback
- Lenders save $2,500+ per draw in operational costs

### 3. Distribution Built-In
- Not selling to 1,000 SMBs (expensive)
- Selling to 50-100 large developers + key bank relationships (relationship-driven)
- Banks incentivized to recommend (faster approvals = happy borrowers)
- Brokers incentivized (referral fees)

### 4. Data Moat
- Every draw processed teaches us what works
- Over time: Learn which vendors submit cleanly, which lien waiver formats work by state, which invoices have issues
- AI can predict/flag issues before they slow down draws
- Competitors can't replicate without years of data

### 5. Network Effects
- Vendors submit to the platform across multiple projects
- Bank recommends to 100+ borrowers
- Developer can't leave without disrupting cash flow
- Switching cost increases over time

---

## Portfolio Lessons

### What This Case Study Demonstrates

**Product Thinking:**
- ✅ Deep problem understanding (quantified the cost, identified root cause)
- ✅ Clear target customer (mid-market developers, not enterprise, not SMBs)
- ✅ Realistic solution (solves the actual workflow, not over-engineered)
- ✅ Business model alignment (pricing matches customer value)
- ✅ Attention to flexibility (vendors without work aren't burdened)

**Market Understanding:**
- ✅ TAM analysis ($1.8B market)
- ✅ Competitive positioning (clear differentiation from existing solutions)
- ✅ Distribution strategy (multiple channels, each with aligned incentives)
- ✅ Go-to-market roadmap (phased approach, realistic timelines)
- ✅ Unit economics (LTV/CAC ratio shows viability)

**Strategic Thinking:**
- ✅ Trade-offs made consciously (MVP scope, pricing strategy)
- ✅ Defensible moat (data advantage over time, switching costs)
- ✅ Scalability path (from 2-3 customers → 50+ → national)
- ✅ Risk mitigation (validate problem before building, focus on biggest pain point)
- ✅ User psychology (understanding when vendors work vs. don't)

---

## Next Steps

If I were to build this:

1. **Month 1:** Validate the problem
   - Interview 10 developers on $100M+ projects
   - Confirm time waste (20-25 hours per draw?)
   - Confirm willingness to pay ($1K-2K/month?)
   - Interview 2-3 banks about approval time and pain points

2. **Month 2:** Build MVP
   - Hire one solid full-stack engineer ($30-50K)
   - Focus on: vendor portal + developer dashboard + bank portal
   - 8-10 weeks of build

3. **Month 3:** Close beta customers
   - Get 2-3 real projects live
   - Run 3-5 real monthly draws through the system
   - Measure: time saved per draw, vendor submission rate, bank approval time
   - Get testimonials: "We saved $X, Y hours per draw"

4. **Month 4+:** Scale
   - Approach 5 lenders with proof-of-concept
   - Partner with 2-3 brokers
   - Raise seed funding if metrics are strong

---

## Resources & Links

- **Interactive Prototype:** See links above in "Interactive Prototype" section
- **Pitch Deck:** [Add link to investor pitch deck]
- **Landing Page:** [Add link to landing page]

---

## Questions?

This case study was created as a portfolio project to demonstrate product thinking, market analysis, and strategic planning.

If you have questions about the product, strategy, or approach, feel free to reach out.

---

*Last updated: March 2025*
