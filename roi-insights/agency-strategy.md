# ROI Insights — Agency Partner Program Strategy

**Status:** Draft planning document. Not integrated with the rest of the brand yet — we're exploring.

---

## 1. The market reality

### The headline statistic

**75% of marketers say their measurement systems fail to deliver the rigor, timeliness, trust, and efficiency they need.** That's the IAB State of Data 2026 report. Not a startup's positioning slide — the Interactive Advertising Bureau saying the entire industry's measurement infrastructure is broken.

Only 30% of CMOs feel confident measuring ROI accurately (Gartner). Only 41% of marketing organizations use attribution modeling at all (Salesforce 2025). An estimated 10–30%+ of marketing spend is wasted due to insufficient measurement.

This is the gap ROI Insights was built to fill. The question is: what role do agencies play in filling it?

### The current agency reporting market is broken in specific, exploitable ways

The research paints a clear picture. There are roughly a dozen tools in the marketing reporting category. They share the same architecture, the same pricing model, and the same blind spots. Agencies hate them in the same ways — which means those complaints are structural, not cosmetic. You can't fix them by adding features to the existing model. You have to change the model.

---

## 2. What agencies are actually saying

### The five structural complaints

These come from G2 reviews, Reddit threads (r/agency, r/PPC, r/marketing, r/SEO), Capterra reviews, and industry surveys. I've grouped them by root cause, not symptom.

#### Complaint 1: "The data connections break constantly"

This is the #1 complaint across every tool. AgencyAnalytics, Whatagraph, DashThis — users report integrations disconnecting, data going stale for 2–3 days, metrics that don't match source platforms. One agency owner described a junior employee whose entire job was "human API" — manually verifying that what the dashboard showed matched what the platform showed.

**Root cause:** These tools pull data via API connectors to third-party platforms. They have no direct access to the tracking layer. When Google changes an API, when Meta adjusts a data model, the pipe breaks and agencies can't fix it. They wait for the vendor to update the connector.

**The ROI Insights angle:** ROI Insights doesn't pull from platforms — it sits underneath them. The measurement layer captures the data as it happens, independent of any platform's API. If Google changes their API, the data is already in the measurement layer. This is a structural advantage, not a feature comparison.

#### Complaint 2: "The pricing model punishes growth"

AgencyAnalytics charges $20/client/month on top of the base subscription. For an agency with 15 clients, that's $300/month just in surcharges. At 50 clients: $1,000/month. At 100 clients: $2,000/month. This is the pricing model that agencies hate most — the tool gets more expensive as the agency succeeds.

DashThis charges per dashboard and data source. Swydo charges per active data source ($4.50/source at mid-tier). Even "unlimited" plans from tools like Databox scale cost with data sources.

**The real cost:** A verified G2 review on DashThis: "the cost can add up quickly if you need a lot of dashboards." A Reddit agency owner: "we're paying $1,200/month for AgencyAnalytics and I can't justify it to my partners."

**Root cause:** These tools charge per-client because their infrastructure costs scale with data volume. Each client dashboard is a separate instance that pulls from separate API connections. The pricing model reflects the architecture.

**The ROI Insights angle:** The free core layer changes the economics. If every client gets measurement infrastructure for free, the agency's cost isn't in data collection — it's in the premium features on top. Different pricing axis entirely.

#### Complaint 3: "It takes 20–40 hours a month just to do reporting"

Across Reddit, multiple agency owners report spending 8–10 hours per month *per client* on manual data aggregation. At typical agency rates ($100–150/hour), that's $400–$1,500 per client per month in lost productivity. For a 10-client agency, up to $15,000/month in opportunity cost.

One agency owner on Reddit described hiring three full-time employees just for reporting. Another had a junior staffer whose title was essentially "human API between platforms."

A separate study found agencies spend **31 hours per week** on report creation. Not analysis. Not strategy. Just pulling numbers into a format the client can read.

**Root cause:** Most agencies are still using spreadsheets. The tools that exist either don't pull from all the right sources, or they require so much manual configuration per client that they don't save the hours they claim to.

**The ROI Insights angle:** The weekly Advisor Briefing replaces the manual report. Plain English. No dashboard configuration. No "just one more chart" scope creep. The agency can still do custom reporting, but the baseline is automated.

#### Complaint 4: "The dashboard shows what happened, not what it means"

This is the deepest complaint and the one that points to the category problem. Every reporting tool displays data. None of them interpret it. An agency owner on Reddit: "My client doesn't care about impressions. They want to know if their phone is ringing."

Another agency reported that after implementing a comprehensive 30-page monthly report, client retention *decreased*. The reports confused clients. Information overload without interpretation is worse than no information.

A G2 review on Whatagraph: "Presentation is great. Lots of bugs." On Klipfolio: "Good product. Doesn't provide much customization." These are surface complaints masking a deeper one: **the dashboard is the product, but the dashboard isn't the answer.** The answer is "is this working?"

**Root cause:** Reporting tools are visualization layers. They don't have AI that reads the data and produces a narrative. They show charts; they don't draw conclusions.

**The ROI Insights angle:** This is the core differentiator. The weekly Advisor Briefing is a plain-English summary with action steps. It doesn't show you data — it tells you what the data means. AI reads your calls, scores your leads, and delivers a narrative. This is not a reporting tool with AI sprinkled on top. This is a measurement layer that produces answers, not charts.

#### Complaint 5: "I can't prove my value to clients"

This is the agency-specific version of complaint 4. Agencies need to show clients that the $3,000–$12,000/month they're spending on marketing is producing more than $3,000–$12,000/month in value. But they're stuck showing impression counts and click-through rates because that's what the tools give them.

One article found agencies reporting as low as **6.7% margins** after factoring in all the unbilled reporting, communication, and meeting hours. The agency business model gets squeezed between what clients will pay and what reporting costs to deliver.

**Root cause:** Agencies can't prove their value because the measurement tools aren't built to measure value — they're built to display platform data. Cost per lead requires connecting ad spend to lead events across multiple platforms, and most tools don't do that.

**The ROI Insights angle:** This is what ROI Insights gives agencies that nothing else gives them. A tool that lets them literally prove, with real numbers, what their work produces. "Here's your cost per lead. Here's which channel is producing. Here's what changed this week." That's an agency's retention engine, not a reporting cost center.

---

## 3. The competitive landscape

### The current reporting tool market (what agencies use today)

| Tool | Starting Price | Pricing Model | Key Complaint |
|------|---------------|---------------|---------------|
| **AgencyAnalytics** | $59/mo (grows to $349+) | Per-client surcharge ($20/client) | Data connections break; pricing explodes at scale |
| **Whatagraph** | $286/mo | Per-account tiers | Expensive; limited customization |
| **DashThis** | $54/mo (grows to $739+) | Per-dashboard + per-data-source | "Cost adds up quickly" (verified G2 review) |
| **Swydo** | $69/mo | Per active data source ($4.50/source) | Complexity; source-count pricing |
| **Databox** | $99/mo | Per-data-source scaling | Costs increase with more data sources |
| **Klipfolio** | $180/mo | Per-dashboard | "Lots of bugs" (verified G2 review) |
| **Supermetrics** | €37/mo | Per-connector | Not a dashboard — a data pipeline |
| **Looker Studio** | Free | Free (Google ecosystem) | Complex setup; not agency-friendly |
| **Reporting Ninja** | $20/mo | Flat fee, all features | Newer; smaller integration list |

### What's missing from every single one

None of these tools do **cost per lead**. They display platform metrics. They don't tie ad spend to lead events. They don't connect Google Ads spend to call tracking to CRM to booked jobs. They show you what Google Ads says happened. They don't tell you what *actually* happened.

None of these tools provide **AI-driven narrative interpretation**. The best they do is anomaly detection — "this metric changed by X%." They don't write a plain-English summary that says "here's what's working, here's what isn't, here's what to do about it."

None of these tools are **independent of platforms**. They pull from platforms. Their data is only as good as the platform's API. When the platform changes, the data breaks.

None of these tools are built on a **free core measurement layer**. You pay before you measure.

### Where ROI Insights sits on the map

ROI Insights is not in the reporting tools category. It's not a dashboard product. It's a measurement layer. The reporting tools are visualization layers that sit on top of platform data. ROI Insights sits underneath the platforms and captures the data independently.

This is a different category. The category doesn't have a name yet, which is both the challenge and the opportunity. "Measurement layer" is the closest we have.

---

## 4. The market gap: what agencies need that doesn't exist

### The gap in one sentence

**Agencies need a way to prove, with real numbers, that their work produces value — without spending 20–40 hours a month building reports from broken data connections.**

### The gap broken down

1. **Measurement, not reporting.** Agencies don't need another dashboard. They need a measurement system that tells them and their clients what's working and what isn't. The dashboard is the delivery mechanism, not the product.

2. **Cost per lead, not impression counts.** The one number that matters to a home services client: "What did each lead cost me?" Nobody in the reporting tool space answers this. They show ad spend. They show click counts. They don't connect spend to leads.

3. **Independence from platforms.** Agencies need data they can trust regardless of what Google, Meta, or any other platform reports. Platform-reported metrics are inherently optimistic and incomplete.

4. **Narrative, not just data.** Clients don't read 30-page reports. They read a paragraph that says "here's the bottom line." Agencies need that paragraph generated automatically.

5. **Pricing that doesn't punish growth.** Agencies should make more money as they add clients, not pay escalating tool costs. The tool should scale with the agency's success, not against it.

6. **Proof of agency value.** The agency's core retention problem is proving they're worth the retainer. A tool that generates a weekly "here's what your agency accomplished this week" summary is fundamentally a retention tool disguised as a measurement tool.

---

## 5. The agency partner program — structural options

### The core principle

**ROI Insights is a measurement layer. It is not an agency. It is not a replacement for an agency. It makes agencies more valuable, not less necessary.**

This is not a positioning trick. It's the structural reality of the product. ROI Insights measures. Agencies manage. The tool tells the agency and their client what's working. The agency makes decisions based on that information. The tool makes the agency look smarter and more accountable, not redundant.

### Option A: The free-everywhere model (most aggressive)

**Structure:**
- Every client gets the free measurement layer. Period. No agency program needed.
- The agency dashboard (client roll-up view) is free for agencies.
- Agencies can offer clients Professional or Business upgrades — the agency gets a rev share on upgrades (20–30%).
- The agency doesn't pay ROI Insights anything for measurement infrastructure.

**Why this works:**
- It's the most aggressive penetration strategy. Zero friction for agencies to start using it.
- It positions ROI Insights as infrastructure, not software. Like Google Analytics — you don't pay for it because it's part of the internet. ROI Insights is part of the marketing stack.
- It creates lock-in through data. Once an agency has 20 clients on ROI Insights, the data history is irreplaceable.
- The rev share gives agencies a financial incentive to upgrade clients, but they don't have to.

**Risk:**
- Revenue comes entirely from end-client upgrades. If upgrade rates are low, this model doesn't sustain itself.
- Requires high volume to work. This is a market-share play.

**Revenue math:**
- 100 agencies × 15 clients average × 10% upgrade rate × $400/yr average = $60,000/yr
- 1,000 agencies × 15 clients × 10% upgrade × $400/yr = $600,000/yr
- 5,000 agencies × 15 clients × 10% upgrade × $400/yr = $3,000,000/yr

This only works at scale. The free tier has to be genuinely useful enough that agencies adopt it en masse, and the upgrade path has to be compelling enough that a meaningful percentage of their clients convert.

### Option B: Agency tier with client benefits (balanced)

**Structure:**
- Client roll-up dashboard is free for agencies with 3+ clients on ROI Insights.
- Agencies get 3 free months of Professional tier for each new client they onboard.
- After 3 months, the client decides whether to stay on Professional (paid) or drop to Free.
- Agency earns 15–25% rev share on all client upgrade revenue, ongoing.
- Premium agency tier ($99/mo?) unlocks: white-label reporting, agency-branded weekly briefings, priority support, multiple team seats.

**Why this works:**
- The 3-month free Professional window gives clients time to see the value before paying.
- The agency dashboard is gated behind having 3+ clients — creates a natural incentive for agencies to onboard multiple clients.
- The rev share is ongoing, so agencies have a permanent financial incentive to keep clients on paid tiers.
- The premium agency tier monetizes agencies directly (small amount, high value).

**Risk:**
- The 3-month window might not be enough time for clients to see enough value to convert.
- The agency premium tier needs to be genuinely worth $99/mo to not feel like a tax.

### Option C: Agency as channel partner (traditional)

**Structure:**
- Agencies pay a wholesale rate for client seats (e.g., $15/client/mo for Professional, $75/client/mo for Business).
- Agencies resell to clients at whatever price they want (typically $50–$100/mo for Professional).
- Agency keeps the margin.
- White-label and roll-up dashboard included.
- Minimum client commitment (e.g., 5 clients).

**Why this works:**
- Direct, predictable revenue for ROI Insights.
- Agencies can build ROI Insights into their service packages.
- Traditional model that agencies understand — no education needed.

**Risk:**
- This is essentially the AgencyAnalytics model (minus the per-client surcharge phrasing). It competes on price, not on structural advantage.
- It doesn't leverage the free core layer as a differentiator.
- It competes in the existing category rather than building a new one.

### Option D: Self-hosted / on-premise license (enterprise agency)

**Structure:**
- The agency pays a significant one-time or annual license fee for the right to host ROI Insights on their own infrastructure.
- They receive the full source code (or a deployable artifact) under a strict license agreement.
- They run the measurement layer themselves — data never touches MosierData servers.
- They manage their own client accounts, their own upgrades, their own billing.
- Ongoing: annual license renewal (including updates, security patches, new features). Support tier is separate.

**License fee range (for discussion):**
- $15,000–$25,000/year for up to 50 client seats
- $35,000–$50,000/year for up to 200 client seats
- Enterprise: custom pricing

Alternatively, a one-time perpetual license ($50,000–$150,000) plus annual maintenance/support ($7,500–$15,000/yr). The perpetual model is more traditional but the SaaS-era trend is toward annual licensing — easier to sell, lower upfront barrier.

**Who this is for:**
- Large agencies or agency networks (50+ clients) that want complete data independence.
- Agencies in regulated industries where client data must never leave the agency's infrastructure.
- Agencies that have been burned by SaaS tools shutting down, raising prices, or changing terms.
- Agencies that want to build custom integrations or workflows on top of the measurement layer and need source access to do it.

**Why this works:**
- It's a completely different revenue stream from the SaaS model. A single self-hosted deal ($25K/yr) equals ~52 Professional-tier subscribers — but comes with zero infrastructure cost, zero support burden for individual client setups, and zero churn risk within the license period.
- It serves a market segment the SaaS model can't reach. Some agencies will never put client marketing data on a third-party server, no matter how good the security. This is the only way to serve them.
- The agency becomes deeply committed. Once they host it themselves, integrate it into their workflows, and train their team on it, switching costs are enormous.
- The revenue is predictable and front-loaded. Annual license fees are paid upfront. No monthly churn. No per-client conversion optimization.

**The legal requirements (non-negotiable):**

This is the critical piece. Self-hosting means the agency has the source code. The legal agreement has to be airtight, and it has to be reviewed by an attorney who understands software licensing. Key provisions:

1. **Scope of license.** The license is for the agency's own use with their own clients. It is not a reseller license. The agency cannot sublicense, white-label as their own product, or sell the software to third parties. The license is tied to the legal entity — it doesn't transfer in an acquisition without consent.

2. **No modification / no derivative works.** The agency can configure and integrate, but cannot modify the core source code or create derivative works. If they need modifications, they contract MosierData to do the work. This protects the IP and prevents a fork.

3. **No redistribution.** The agency cannot distribute, share, publish, or make available the source code to any third party. Their clients access the running software through the agency's instance — they never receive the source code.

4. **Audit rights.** MosierData retains the right to audit the agency's use of the software (with reasonable notice) to verify compliance with client seat limits and license terms.

5. **Termination and clawback.** If the license is terminated (non-renewal, breach, etc.), the agency must destroy all copies of the source code and cease operation of the software. The agreement should specify what happens to the agency's client data upon termination — the data belongs to the agency and their clients, not to MosierData, so there needs to be an export provision.

6. **IP assignment / improvements.** Any improvements, modifications, or customizations the agency makes (even if they shouldn't) are assigned back to MosierData. This prevents the agency from "improving" their way into a competing product.

7. **Confidentiality and trade secrets.** The source code is MosierData's trade secret. The agreement needs strong confidentiality provisions, including employee/contractor access restrictions, data breach notification requirements, and survival of confidentiality obligations after termination.

8. **Indemnification.** The agency indemnifies MosierData against claims arising from the agency's use of the software, including data breaches caused by the agency's infrastructure.

9. **Support and updates.** The agreement defines what support is included (email? phone? SLA?), what updates are included (bug fixes? new features?), and what happens if MosierData discontinues the product (source code escrow provision?).

10. **Non-compete / non-compete-like provisions.** While a direct non-compete may not be enforceable in all jurisdictions, the license agreement should include provisions that prevent the agency from using the source code or knowledge gained from it to build a competing measurement product.

**Technical protections (belt-and-suspenders):**

Legal agreements matter, but they're enforced after a breach. Technical protections prevent or detect breaches in the first place:

- **Code obfuscation / compiled delivery.** Ship a compiled/minified artifact rather than clean, readable source code where possible. For interpreted languages (PHP, Python, JS), deliver obfuscated code with a build step that can't be reversed.

- **License key / activation system.** The software requires a valid license key that's tied to the agency's domain, IP range, or server fingerprint. The key expires with the license term. Without a valid key, the software stops working (graceful degradation — existing data remains accessible but new data stops processing).

- **Periodic license validation.** The software phones home periodically (e.g., weekly) to validate the license. If the license is revoked or expired, the software enters read-only mode. This is standard for on-premise enterprise software and agencies understand it.

- **Client seat enforcement.** The software tracks the number of active client accounts. If the agency exceeds their licensed seat count, the software either blocks new client creation or notifies MosierData (depending on the agreement terms — some agencies prefer automatic overage billing, others prefer a hard cap).

- **Tamper detection.** The software includes integrity checks that detect if the license validation or seat counting code has been modified. If tampering is detected, the software logs it and, after a grace period, enters restricted mode.

- **Watermarking.** The source code includes unique, non-obvious markers tied to the licensee. If the code ever appears in public or in a competing product, the source is traceable.

**How this fits into the overall strategy:**

The self-hosted option isn't for everyone. It's for the top 5–10% of agencies — the ones large enough to need it, sophisticated enough to run it, and willing to pay for independence.

It serves a strategic purpose beyond revenue:
- It signals that ROI Insights is serious infrastructure, not a toy SaaS product. Enterprise agencies don't run their client reporting on $39/mo SaaS tools. A self-hosted option at $25K/yr puts ROI Insights in a different category.
- It creates a ceiling. Agencies that start on the free/cloud version and grow can "graduate" to self-hosted. The path from free → Professional → self-hosted is a natural progression that keeps agencies in the ecosystem as they scale.
- It generates high-margin revenue that funds development of the free and cloud products. One self-hosted deal covers the infrastructure costs for thousands of free-tier users.

**Pricing psychology note:**

$25,000/year sounds like a lot for software. But for an agency with 50 clients, that's $41/client/month — cheaper than AgencyAnalytics at scale, with full data independence. For an agency with 100 clients, it's $21/client/month. The math works in the agency's favor as they grow.

The pitch: "You're already spending $1,200+/month on AgencyAnalytics at your scale. For roughly double that, you own the infrastructure, your data never leaves your servers, and you never pay a per-client surcharge again. At 100 clients, you're saving money."

### Recommended approach: ROI Insights Partner Program

**The name:** ROI Insights Partner. At scale, we'll introduce an "ROI Insights Certified Professional" credential for people who become expert at the platform — this matters once we get volume on assisted setups and agencies need a way to signal competence.

#### Tier 1: Partner (free to join)

**What they get:**
- Client roll-up dashboard: **$29/mo for up to 5 clients.** Once they have 5+ clients with at least one on a paid tier (Professional or Business), the roll-up dashboard fee goes away. The $29 is skin in the game — laughably low, a no-brainer — but it's a transaction. It filters out tire-kickers.
- 20% ongoing rev share on all client Professional and Business upgrades. Every month the client stays, the agency gets paid.
- 3 free months of Professional for each new client they onboard. Client experiences the full product, then chooses to stay (paid) or drop to Free.
- Free measurement layer for every client. Always. No exceptions.

**Why the $29 matters:**
It's not about the money. It's about creating a moment where the agency pulls out a credit card. That small friction separates "I'm curious" from "I'm in." At $29, it's the cheapest tool in their stack by an order of magnitude — intentionally. The psychology is: "It's $29. If it saves me one hour of manual reporting, it paid for itself 5x over."

**Why the fee goes away at 5+ clients:**
Once an agency has five clients on the platform with at least one paying, they're committed. The data is flowing. The weekly briefings are going out. The rev share is active. At that point, the $29 has done its job. Removing it says: "You're a real partner now. The platform pays for itself."

#### Tier 2: Partner Pro ($79/mo)

Everything in Partner, plus:
- **Agency MCP AI Agent Access.** A single MCP configuration for the agency that's partitioned by client — one connection instead of one per client. Connect ChatGPT or Claude to all your clients' data through one interface, with client-level access controls. If any of the agency's clients are on Professional or Business, MCP access is included by default. Partner Pro is for agencies that want MCP before any of their clients upgrade, or want the single-configuration convenience.
- White-label weekly briefings (agency branding instead of ROI Insights branding)
- Priority support
- Co-branded landing page option

#### Tier 3: Self-Hosted ($15K–$50K/yr)

For enterprise agencies. See Option D above for full structure, legal requirements, and technical protections.

#### Call tracking: bring your own

Agencies bring their own call tracking provider. No auto-provisioning. They can use whatever service they want, charge their clients however they want. ROI Insights integrates with the call data — it doesn't own the telecom relationship. This keeps the agency in control of their margins and their vendor relationships.

#### The pricing promise

**No per-client surcharges. Ever.** This is the structural differentiator. The roll-up dashboard is a flat fee that disappears once the agency is committed. The rev share pays the agency, not the other way around. Everything about this pricing model says: "We make money when you succeed, not when you grow."

#### Cross-selling with MosierData

Natural and simple. If an agency needs custom tracking infrastructure beyond what the free tier provides, MosierData can build it. The messaging: "ROI Insights is a MosierData product. For custom tracking and software development, visit mosierdata.com." That's it. No confusion. Two different things, same company, clearly labeled.

---

## 6. Why this pricing model wins

### The per-client comparison

Agency with 20 clients:

| Tool | Monthly Cost |
|------|-------------|
| AgencyAnalytics (mid-tier + 20×$20 surcharge) | ~$500+/mo |
| DashThis (20 dashboards) | ~$350+/mo |
| Whatagraph | $286+/mo (but limited features at base) |
| Swydo (20 clients × multiple sources) | ~$200–$400/mo |
| **ROI Insights Partner (≥5 clients)** | **$0/mo** |
| **ROI Insights Partner Pro** | **$79/mo** |

At 50 clients:

| Tool | Monthly Cost |
|------|-------------|
| AgencyAnalytics | ~$1,200+/mo |
| **ROI Insights Partner (≥5 clients)** | **$0/mo** |
| **ROI Insights Partner Pro** | **$79/mo** |

At 100+ clients (self-hosted comparison):

| Tool | Annual Cost |
|------|-------------|
| AgencyAnalytics (100 clients, mid-tier + surcharges) | ~$28,000+/yr |
| DashThis (100 dashboards) | ~$8,800+/yr |
| **ROI Insights (self-hosted, 100+ seats)** | **$25,000–$35,000/yr** — and the agency owns the infrastructure |

This is not a pricing comparison. This is a different business model entirely.

### The rev share math

Say an agency has 30 clients. 10 upgrade to Professional ($39.95/mo). Agency earns 20% = ~$80/mo. They have 30 clients so the roll-up dashboard is free. If they're on Partner Pro ($79/mo), they're effectively at break-even — the rev share roughly covers the Pro fee.

But that's the wrong way to think about it. These agencies are used to *paying* $500–$1,200+/mo for reporting tools. Instead, they're at $0–$79/mo with an $80/mo rev share stream that grows with every client upgrade. They're not break-even. They're up $400–$1,100+/mo versus what they're paying now, *plus* they have a measurement layer that actually tells them and their clients what's working.

At 50 clients with 15 on Professional: agency earns ~$120/mo in rev share. At 100 clients with 30 on Professional: ~$240/mo. This isn't retirement money — but combined with the $500–$1,200+/mo they're *not* paying AgencyAnalytics, the net swing is $600–$1,400+/mo in the agency's favor.

The real value isn't the rev share. The real value is: the agency can prove their worth to every client, every week, with a plain-English briefing that takes zero hours to produce. That's the retention engine. The rev share is gravy.

---

## 7. Agency pain points this directly addresses

| Agency Pain | How ROI Insights Addresses It |
|------------|------|
| Manual reporting takes 20–40 hrs/month | Weekly Advisor Briefing is automated. Plain English. Zero configuration. |
| Data connections break constantly | Measurement layer sits underneath platforms — doesn't depend on API connectors. |
| Can't prove value to clients | "Here's your cost per lead. Here's which channel produced it. Here's what changed." The exact proof agencies need. |
| Pricing punishes growth | No per-client surcharges. Agency dashboard free. Revenue model is rev share, not per-seat tax. |
| Dashboards show data, not meaning | AI writes the narrative. "What it means," "what to do," "what's working." Not just charts. |
| Clients don't understand reports | Plain English. No jargon. Written for the business owner who doesn't know what a UTM is. |
| Scope creep ("one more chart") | The weekly briefing is standardized. Custom reporting is a separate conversation. |
| Vanity metrics that don't connect to revenue | Everything ties back to leads, calls, and booked jobs. The metrics are business outcomes, not platform metrics. |

---

## 8. Go-to-market

**Timing: Now.** The product is ready. The market is underserved. The pricing model is differentiated. There's no reason to sequence the agency program behind the consumer launch — they launch together. Agencies onboard clients. Clients drive upgrades. The flywheel starts on day one.

### How agencies find out about this

1. **Home services agencies first.** The core ICP is agencies serving HVAC, plumbing, electrical, roofing, and general contractors. These businesses spend $3,000–$12,000/month on marketing. Their clients ask "is this working?" every month. The agency that can answer that question with real numbers keeps the client.

2. **The wedge is the free measurement layer.** "Set up measurement for your client in 5 minutes. They'll see their cost per lead. You'll see all your clients in one dashboard. Free for everyone involved." Agencies bring their own call tracking — no lock-in, no auto-provisioning.

3. **Content strategy:** Knowledge library articles about measurement, attribution, cost per lead — written in Jim's voice, for agencies. LinkedIn posts from the ROI Insights page. Not selling. Teaching.

4. **Direct outreach:** Small to mid-size agencies in home services vertical. They're not using AgencyAnalytics at $500+/mo. They're using spreadsheets. The upgrade from spreadsheet to free measurement layer with a $29 roll-up dashboard is an easy yes.

5. **Partner landing page:** Simple page at roiknowledge.com/partners. Explains the program in plain English. $29/mo, 20% rev share, free measurement for clients. "Join" button. No demo request form. No sales call required.

### The competitive moat

The moat isn't technology — it's the business model. Nobody else is doing free measurement infrastructure with a rev share model because nobody else is architected for it. AgencyAnalytics can't make their core product free because their infrastructure costs scale per-client. ROI Insights can because the measurement layer is the product, not the dashboard.

The second moat is the voice. Jim's voice — direct, no-fluff, real — builds trust with agency owners who are tired of being marketed to. The voice profile is a competitive advantage because it's impossible to copy authentically.

The third moat: the $29 is a pricing signal. It says "we're serious but we're not greedy." No agency owner looks at $29 and thinks "I need to run this by my partners." They swipe the card and move on. Once they're in, the product does the selling.

---

## 9. Decisions made

| Decision | Answer |
|----------|--------|
| Rev share percentage | **20%.** It doesn't need to be higher — agencies are used to paying for reporting tools. Getting paid anything is revolutionary for this category. |
| Roll-up dashboard pricing | **$29/mo for <5 clients. Free at 5+ clients with at least one on a paid tier.** The $29 is skin in the game, laughably low, filters out tire-kickers. |
| Agency MCP access | **Included by default if any client is on Professional or Business. Available as a paid upgrade (Partner Pro, $79/mo) for agencies that want it sooner** — single MCP configuration partitioned by client. |
| Agency premium tier | **Partner Pro at $79/mo.** Includes white-label briefings, priority support, agency MCP access, co-branded landing pages. |
| Call tracking for agencies | **Bring your own.** No auto-provisioning. Agencies control their telecom relationships and margins. |
| Program naming | **ROI Insights Partner.** With "ROI Insights Certified Professional" credential planned for when volume justifies it. |
| Cross-selling MosierData | **Simple reference.** "ROI Insights is a MosierData product. For custom tracking and software, visit mosierdata.com." |
| Go-to-market timing | **Now.** No reason to wait. The product is ready. The market is underserved. The pricing model is differentiated. |

## 10. Open questions (still need decisions)

1. **Minimum commitment:** Should the Partner program require anything beyond the $29? An application? A minimum client count before rev share kicks in? Or is the $29 credit card transaction enough of a gate? The $29 by itself filters out casual tire-kickers while keeping the barrier laughably low for real agencies. My recommendation: no additional requirements. The $29 is the gate. Once they're in, the product proves itself.

2. **$29 or $59?** The exact number matters less than the psychology. $29 is "I don't even need to think about this." $59 is still cheap but crosses into "I should probably check with someone." For a no-brainer, $29 is better. The goal is volume — get agencies on the platform, get their clients measured, let the rev share do the work.

3. **Self-hosted legal review:** Requires attorney review of the license agreement. Key provisions: scope of license, no modification/derivative works, no redistribution, audit rights, termination/clawback, IP assignment of improvements, confidentiality/trade secrets, indemnification, source code escrow, non-compete provisions. Technical protections (license keys, activation, tamper detection, watermarking) need to be designed alongside the legal framework. This is not something to DIY — the source code is the business.

4. **Self-hosted support model:** What SLAs do we offer self-hosted licensees? Is support included in the license fee or separate? What's the escalation path for production outages on infrastructure we don't control?

5. **Self-hosted update cadence:** How often do we ship updates to self-hosted licensees? Do they get new features at the same time as the cloud product, or is there a lag?

6. **Partner Pro price point:** $79/mo is the starting assumption. Is that the right number? At $79, it's roughly the price of one Professional client. For an agency managing 15+ clients, that's negligible. But we should validate with early partners.

7. **"ROI Insights Certified Professional" credential:** When do we introduce this? What's the certification process? Is it free for partners or a separate revenue stream? This becomes relevant once we have enough agency volume that "certified" status carries weight with end clients.

8. **Free Professional months:** Is 3 months the right trial window? Long enough for the client to see weekly briefings and build a habit. Short enough to convert within a quarter. Reasonable starting point — we can adjust based on conversion data.

---

## 11. What happens if we get this right

If the agency program works, ROI Insights becomes the default measurement layer for home services marketing. Not because agencies chose it over AgencyAnalytics in a feature comparison. Because it was free, it worked, and it made them look good to their clients.

The agency that adopts ROI Insights for their clients has:
- A permanent measurement record that survives platform changes, agency changes, and staff turnover
- A weekly plain-English briefing they can forward to clients (or white-label as their own)
- A cost-per-lead number they can point to in every monthly meeting
- A revenue stream from client upgrades
- A structural advantage over agencies still building reports in spreadsheets

The agency that doesn't adopt ROI Insights is still spending 20–40 hours a month pulling data into spreadsheets while their competitor forwards an automated briefing and says "here's exactly what your marketing produced this week."

That's the market dynamic we're creating.

---

## 12. Research sources

- IAB State of Data 2026 report (75% of marketers say measurement systems failing)
- G2 reviews for AgencyAnalytics, Whatagraph, DashThis, Swydo, Klipfolio, Databox (2024–2026)
- Capterra reviews for Swydo, DashThis, AgencyAnalytics (2024–2026)
- PainOnSocial analysis of Reddit r/marketing, r/PPC, r/agency, r/SEO (2025)
- Reporting Ninja agency tools comparison (2026)
- MediaPost agency pricing survey: 33% flat fee, 33% flat + % of spend, 16% % of spend (2025)
- Globital Marketing agency profitability analysis: 6.7% margins, 20–40 hrs/month on reporting (2025)
- MarTech: "The marketing data most companies still fail to measure" (2026)
- Gartner: Only 30% of CMOs feel confident measuring ROI accurately
- Salesforce State of Marketing: Only 41% of marketing orgs use attribution modeling (2025)
- Adverity: Nearly half the data marketers use is incomplete, inaccurate, or out of date
- Sagum: Dashboard paralysis analysis — teams spend 60%+ of time in dashboards instead of acting (2026)
- SaaSFirst: Ad specialists spend 4 days/month making charts instead of driving results (2025)

---

*Draft: May 2026. For discussion, not distribution.*
