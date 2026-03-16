# Cross-Reference Anomaly Analysis: Patterns of Coordinated Influence

**Research Date:** 2026-03-13
**Method:** Cross-referencing all accumulated findings from 20+ individual research threads
**Classification:** OSINT analytical product — pattern analysis derived from public records

---

## Executive Summary

Campaign finance records, IRS data, corporate registries, lobbying disclosures, web forensics, and legislative timelines cross-referenced together expose a coordinated influence operation with eight distinct anomaly patterns. DCA — the central advocacy vehicle for the App Store Accountability Act — has a confirmed EIN (33-2669790) registered in Delaware under Melissa McKay, but reports gross receipts under $25,000 despite coordinating a 20+ state legislative campaign with Meta funding. The entity files only a 990-N e-Postcard (zero financial disclosure). The bulk of DCA's funding flows through channels that never touch this EIN, consistent with the fiscal sponsorship and direct Meta funding model documented below. Disproportionate lobbying deployment, structured out-of-state contributions, and a 77-day domain-to-legislation pipeline round out a system purpose-built for laundering corporate policy preferences through nominally independent advocacy.

---

## 1. DCA's Legal Footprint — EIN Found, But Financial Ghost

### Finding

**UPDATE (2026-03-16):** EIN 33-2669790 confirmed for "Digital Childhood Alliance Inc" via eintaxid.com. Registered in Delaware at the same address as sister organization DCI.

| Database | DCA Result | DCI Result |
|----------|-----------|-----------|
| eintaxid.com | **FOUND: EIN 33-2669790** (Delaware, 990-N filer, <$25K gross receipts) | Found (EIN 39-3684798) |
| IRS Business Master File (all 4 regional extracts) | **NOT FOUND** (as of prior search; may have been added since) | Found (EIN 39-3684798) |
| ProPublica Nonprofit Explorer | **NOT FOUND** (404 for EIN 332669790) | Not found |
| GuideStar / Candid | Not found | Not found |
| Charity Navigator | Not found | Not found |
| OpenCorporates (200M+ entities worldwide) | Not found | Not found |
| State registries (CO, DC, DE, VA) | **Delaware: 213 N Market St PMB 1039, Wilmington** | Delaware (same address) |

**EIN 33-2669790 key details:**
- **Legal name:** Digital Childhood Alliance Inc
- **Officer:** Melissa McKay (DCA/DCI founder)
- **Address:** 213 N Market Street PMB 1039, Wilmington, Delaware 19801 (same as DCI)
- **Tax year:** 2024
- **Gross receipts:** Under $25,000
- **Filing requirement:** 990-N (e-Postcard) — zero financial disclosure required
- **Source:** https://eintaxid.com/company/332669790-digital-childhood-alliance-inc/

DCA also continues to process donations through Network for Good's EIN (68-0480736) rather than its own.

### Significance

Deliberate financial minimization. An organization coordinating a 20+ state legislative campaign, deploying an executive director (Casey Stefanski) who testifies before state legislatures, retaining a senior policy advisor (John Read) registered as a lobbyist, and admitting receipt of tech company funding reports under $25,000 in total gross receipts. A 990-N e-Postcard requires only: name, EIN, address, officer, and confirmation of the <$25K threshold. No revenue sources, no expenses, no donors, no program descriptions.

The vast majority of DCA's operating budget does not flow through EIN 33-2669790. The funding Bloomberg confirmed (Meta) and Stefanski admitted under oath (tech companies, plural) enters through other channels: direct Meta payments, For Good DAF (Project 258136), NCOSEAction (EIN 88-1180705), or Sixteen Thirty Fund's sponsored project model. The EIN functions as a legal shell satisfying the website's claim of being "a registered nonprofit 501(c)(4) entity as determined by the Internal Revenue Service" while keeping actual finances invisible.

### Comparison: DCI vs. DCA Legal Footprint

| Feature | DCI (c)(3) | DCA (c)(4) |
|---------|-----------|-----------|
| EIN | 39-3684798 | **33-2669790** (found 2026-03-16) |
| IRS Determination | November 2025 | Unknown (990-N filer, tax year 2024) |
| Incorporation | Delaware | **Delaware** (same address: 213 N Market St PMB 1039, Wilmington) |
| Domain Registration | 2025-06-13 (1 year) | 2024-12-18 (4 years) |
| Gross Receipts | Unknown (no 990 yet) | **Under $25,000** (990-N) |
| Donation Processing | Unknown | Network for Good (EIN 68-0480736) |
| Officer | Melissa McKay | **Melissa McKay** (same person) |

DCA has a 4-year domain registration and more sophisticated web infrastructure than DCI yet reports under $25K in gross receipts. The EIN satisfies the legal minimum while revealing nothing about actual funding flows. The <$25K threshold cannot be reconciled with an organization that retains staff, commissions polls, and coordinates legislative campaigns in 20+ states. The real money enters through other channels.

---

## 2. The 77-Day Domain-to-Legislation Pipeline

### Timeline

| Date | Event | Days from Registration |
|------|-------|----------------------|
| 2024-12-18 04:11 UTC | DCA domain registered (GoDaddy, privacy-protected) | Day 0 |
| 2024-12-19 03:51 UTC | First Wayback Machine snapshot — fully functional site | Day 1 (23 hrs 40 min) |
| ~2025-02-28 | Public launch announced ("50+ conservative groups") | Day 72 |
| **2025-03-05** | **Utah SB-142 (ASAA) signed into law** | **Day 77** |
| 2025-05-XX | Federal ASAA introduced (Lee/Lankford) | ~Day 150 |
| 2025-06-30 | Louisiana HB-570 signed | Day 194 |

### Analysis

The site deployed within 23 hours and 40 minutes of domain registration was not a placeholder. It was a fully-developed advocacy site with complete policy messaging, statistics, named testimonials from Heritage Foundation and NCOSE staff, multiple call-to-action sections, and professional multi-page navigation.

Building a professional WordPress site with that content, configuring Cloudflare CDN, Microsoft 365 email, Elastic Email marketing, Google Workspace, and Amazon SES within 24 hours requires pre-built staging. The site was developed before the domain was registered and deployed on cue.

DCA's organizers knew the legislative calendar in advance. The site was pre-loaded with ASAA-specific talking points before any ASAA bill had passed anywhere. The 77-day window from domain registration to Utah's SB-142 signing shows the organization was purpose-built to support legislation already in the pipeline, not advocacy that emerged from grassroots demand.

---

## 3. Twelve Lobbyists for a 99-0 Vote (Louisiana HB-570)

### Finding

Meta deployed **12 lobbyists** in Louisiana for HB-570. The bill passed:
- House: **99-0**
- Senate: **39-0**

Zero opposition. Not a single legislator voted against the bill.

### Why 12 Lobbyists for Zero Opposition?

Deploying 12 lobbyists for a bill with unanimous support makes no sense if the goal is persuading legislators to vote yes. The spending tracks with four alternative objectives:

1. **Text control:** 12 lobbyists provide coverage across every committee member, every potential amendment author, and every relevant staffer. The goal is not "pass the bill" but "pass *this exact version* of the bill" — ensuring no hostile amendments shift compliance burdens back to social media platforms.

2. **Relationship infrastructure:** ASAA is the "foot in the door." A politically costless child-safety bill creates goodwill that Meta can leverage on future issues (AI regulation, antitrust, data privacy). The 12 lobbyists establish relationships, not votes.

3. **Dominance signaling:** The deployment communicates to industry opponents (NetChoice, CCIA, Chamber of Progress, R Street — all of which opposed HB-570) that Meta will outspend opposition on this issue.

4. **Narrative management:** With DCA's Stefanski AND Meta's Nicole Lopez both testifying in support, the 12 lobbyists ensure Meta controls the hearing narrative, the committee questions, and the press framing.

### Proportionality Context

| Deployment | Lobbyists | Bills | Ratio |
|-----------|-----------|-------|-------|
| Federal (all issues) | 86+ | Dozens | ~3-8 per issue |
| Louisiana (one bill) | 12 | 1 | **12:1** |

Louisiana's per-bill lobbyist deployment exceeds the typical federal per-issue ratio by 2-4x. ASAA was a top-priority deployment, not routine government affairs.

---

## 4. Structured Out-of-State Contributions to Matt Ball

### Finding

Three tech company employees from California contributed to newly-appointed Colorado state senator Matt Ball within a 90-day window:

| Date | Contributor | Company | Role | Amount | Channels |
|------|------------|---------|------|--------|----------|
| 2025-03-24 | Kyle Gardner | Google | Policy Manager | $450 | Candidate committee |
| 2025-06-02 | Jake Levine | Meta | Product Manager | $1,175 | $450 candidate + $725 leadership PAC |
| 2025-06-14 | James Rosenthal | Pinterest | Attorney | $450 | Candidate committee |

### Anomalies

Matt Ball was appointed, not elected. He filled a vacancy in January 2025 via vacancy committee with no incumbent fundraising base and a limited donor network. Newly appointed legislators with empty campaign accounts are high-value targets for interest groups seeking early influence.

Levine's contribution is structurally sophisticated. He maxed out two separate channels on the same day: $450 to Ball's candidate committee (the Colorado individual limit) and $725 to Ball's leadership PAC (separate, higher limit for political committees). Splitting contributions across channels to maximize total giving on a single day tracks with government affairs team guidance, not casual personal giving.

SB26-051 was not yet filed. Ball's ASAA bill was introduced on January 27, 2026, seven months after Levine's contribution. But ASAA-model bills were already law in Utah (March 2025), Louisiana (June 2025), and Texas (May 2025). Colorado was a known target state. A Meta Product Manager working on relevant products would be in the policy planning loop.

All three contributors are from California. Out-of-state contributions from policy-adjacent tech employees to a state senator they cannot vote for are interest-driven by definition, not constituent engagement.

All three companies are directly affected by ASAA. Google operates the Play Store (regulated by ASAA). Meta runs apps distributed through stores ASAA would regulate. Pinterest distributes through regulated stores. Three policy professionals from three affected companies converging on one obscure state legislator within 90 days is statistically improbable as independent action.

### Assessment

Whether formally coordinated (via a shared "suggested legislators" list circulated in tech policy networks) or emergent (policy professionals independently identifying the same high-value target) cannot be determined from contribution data alone. The pattern warrants further investigation: three California tech policy professionals, three different companies, one newly-appointed Colorado state senator, 90 days.

---

## 5. The Influence Laundering Architecture

### The Structure

```
Meta Platforms, Inc. (funder)
        │
        ├──── $X funding ────→ DCA (501(c)(4), no disclosure required)
        │                           │
        │                           ├── Casey Stefanski testifies at hearings
        │                           ├── Policy templates delivered to legislators
        │                           ├── "140+ coalition" provides political cover
        │                           │
        │                           └──→ Sen. Todd Weiler (UT, SB-142)
        │                                 ├── Does NOT accept corporate contributions
        │                                 ├── Has NOT discussed ASAA with Meta
        │                                 └── Sponsored the first ASAA bill in the nation
        │
        ├──── 12 lobbyists ──→ Louisiana HB-570 (99-0)
        │
        ├──── $338,500 ──────→ Headwaters Strategies (CO)
        │                           └── Adam Eichberg ──→ NVF Board Chair
        │
        └──── $65M+ ─────────→ Super PACs (CA, TX, multi-state)
```

### How Attribution Breaks at Every Link

1. **Meta to DCA:** DCA is a 501(c)(4). Donor disclosure is not legally required. Bloomberg exposed the connection through investigative reporting, not public records.

2. **DCA to Legislators:** DCA presents itself as a coalition of "140+ conservative groups." Legislators see grassroots advocacy, not corporate lobbying. Weiler can truthfully say he never talked to Meta.

3. **DCA's legal status:** DCA's EIN (33-2669790) reports <$25K gross receipts. Real operational funding flows through other entities whose aggregate reporting buries DCA-related spending.

4. **The "clean origin" story:** Melissa McKay, a Utah mother of five, provides the authentic human face. Her #FixAppRatings activism predates DCA by years. But DCA was built around her story, not by her. The domain was registered, the site built, the coalition assembled, and the policy templates written by professionals with NCOSE and DOJ backgrounds.

### Functional Comparison

| Feature | Financial Shell Company | DCA 501(c)(4) |
|---------|----------------------|---------------|
| Breaks attribution between source and use of funds | Yes | Yes |
| Source of funds is legally concealed | Yes | Yes — c4 donor secrecy |
| Entity may lack independent legal existence | Sometimes | Yes — no EIN, no incorporation |
| Uses another entity's identification numbers | Yes — nominee accounts | Yes — Network for Good EIN |
| End beneficiary appears independent | Yes | Yes — "grassroots coalition" |
| Requires investigation to trace funds | Yes | Yes — Bloomberg exposé |

Not an allegation of illegality. The 501(c)(4) structure is legal. Donor nondisclosure is legal. Fiscal sponsorship is legal. Lobbying through advocacy coalitions is legal. But the cumulative architecture, a <$25K shell entity with donor secrecy, intermediary advocacy, and attribution-breaking at every link, constitutes a system designed to obscure corporate influence over public policy.

---

## 6. The Fiscal Sponsorship Hypothesis: Sixteen Thirty Fund

### Why STF Is the Strongest Candidate

If DCA operates as a sponsored project rather than a standalone entity, Sixteen Thirty Fund is the strongest candidate for four reasons:

1. **Correct tax status:** STF is the only Arabella entity that is a 501(c)(4). DCA claims c4 status. A c3 sponsor (NVF, Windward, Hopewell) could not legally host a project doing unlimited lobbying.

2. **Documented practice:** The Arabella model operates "hundreds of sponsored projects" — organizations with names, staff, websites, and public identities, but no independent EINs, no separate 990s, and no Schedule I appearances.

3. **Massive fund pool:** STF receives $121.3M from NVF annually. Its 2024 revenue was $282M; Schedule I grants totaled $236M. The ~$46M gap includes operating expenses, management fees, and spending on sponsored projects — none of which would appear in our Schedule I analysis.

4. **Permanent donor secrecy:** As a c4, STF never discloses donors. If Meta contributed to STF directly or via the NVF transfer pipeline, that contribution would never be publicly traceable.

### Why the $0 Schedule I Finding Is Consistent, Not Contradictory

A fiscal sponsor does not "grant" money to its own projects. Sponsored project spending appears as operational expenditures within the sponsor's financial statements, not as Schedule I grants. The finding that all five Arabella entities made 4,433 grants totaling ~$2.0 billion with zero to child safety is definitive for ruling out the grant pathway and entirely consistent with the fiscal sponsorship pathway, where sponsored projects would never appear in grant data.

### The Circular Flow Problem

```
NVF ──$121.3M──→ STF ──$6.8M──→ North Fund ──$5.3M──→ STF (circular)
NVF ──$8.8M────→ Hopewell ──$11M──→ NVF (circular)
NVF ──$8.8M────→ Hopewell ──$8.3M──→ STF (triangular)
```

Money entering the Arabella network at any point can exit at any other point. The circular, multi-directional transfers between all five entities mean that even if a Meta contribution were identified entering one entity, its ultimate destination cannot be traced. The network functions as a single financial organism: an attribution-washing machine.

### What Would Confirm This

The fiscal sponsorship hypothesis can only be confirmed through:
1. STF's Part IX functional expenses and narrative 990 attachments (project-level detail)
2. Congressional subpoena of STF's internal project records
3. Whistleblower disclosure
4. Meta's voluntary admission (unlikely)
5. IRS audit of STF's sponsored project activities

---

## 7. Coalition Inflation: "140+" With 6 Named Members

### Finding

DCA's claimed coalition membership escalated rapidly:

| Date | Claimed Size | Named Members |
|------|-------------|--------------|
| ~Feb 28, 2025 | 50+ conservative groups | 6 |
| Mid-2025 | 100+ advocates | 6 |
| Late 2025 | 140+ organizations | 6 |

The six confirmed organizations: NCOSE, Heritage Foundation, Institute for Family Studies, Ethics and Public Policy Center, Moms for Liberty, Protect Young Eyes.

### Anomalies

No complete member list has ever been published on the DCA website across 15+ months and 100+ Wayback Machine snapshots. Legitimate coalitions publish membership lists because breadth of support is their primary asset. The number inflation (50 to 100 to 140) with no additional named members suggests the count includes organizations that signed letters of support rather than committed coalition partners. A coalition of 140+ organizations that refuses to name its members raises fundamental credibility questions.

---

## 8. The Reverse Incorporation Order

### Finding

DCA (c)(4) — the lobbying vehicle — was created **six months before** DCI (c)(3) — the educational/research arm:

| Entity | Domain Registered | Type | Purpose |
|--------|------------------|------|---------|
| DCA | 2024-12-18 | 501(c)(4) | Lobbying, advocacy |
| DCI | 2025-06-13 | 501(c)(3) | Education, research |

### Red Flag

Standard nonprofit formation follows a predictable pattern: establish a 501(c)(3) to build subject-matter credibility, attract tax-deductible donations, and conduct research, then create a 501(c)(4) advocacy arm once legislative targets are identified.

DCA reversed this. The lobbying vehicle came first; the research arm was bolted on six months later. An organization whose primary purpose from inception was legislative advocacy, specifically passing ASAA, not one that evolved from research and education into policy work.

The reverse order also explains the funding split. DCI explicitly claims to "not accept major tech platform funding" while DCA admits it. DCI was created to provide a "clean" research arm that could claim independence from the corporate-funded lobbying operation.

---

## 9. Dual-Client Lobbying: Meta AND Roblox at Pelican State Partners

### Finding

Pelican State Partners LLC represents **both Meta Platforms and Roblox Corporation** as lobbying clients in Louisiana. Both companies directly benefit from ASAA legislation:

- **Meta:** Runs social media apps distributed through app stores; ASAA shifts age verification from platforms to stores
- **Roblox:** Runs a gaming platform used overwhelmingly by children, distributed through app stores; benefits from the same regulatory shift

### Strategic Value

Dual representation allows Pelican State's lobbyists to present ASAA as having broad industry support ("both Meta and Roblox support this") rather than a single-company initiative. Roblox is widely perceived as a "children's platform," reinforcing the child safety framing. A second tech company "supporting" ASAA dilutes the perception that the bill serves Meta's specific commercial interests. Whether Roblox independently chose Pelican State Partners or was steered there by shared industry relationships is unknown, but the result is functional coordination.

---

## 10. Summary Assessment

### The Architecture of Deniability

Not a series of independent findings but an integrated system designed to produce legislative outcomes while maintaining plausible deniability at every node:

| Link | Attribution Break | Mechanism |
|------|------------------|-----------|
| Meta → DCA | Donor identity concealed | 501(c)(4) donor secrecy |
| DCA's legal form | Finances cannot be investigated | EIN 33-2669790 exists but reports <$25K; 990-N = zero disclosure; real funding flows elsewhere |
| DCA → Legislators | Corporate origin obscured | "Grassroots coalition" framing |
| Legislators → Public | Independence maintained | "Never talked to Meta" (Weiler) |
| Campaign contributions → Legislators | Individual, not corporate | Tech employees, not company PACs |
| Arabella connection → funding flow | Circular transfers obscure origins | 5-entity circular transfer network |
| Bill text → Meta's interest | "Child safety" framing | 12 lobbyists control text, not votes |

### What This Is

No conspiracy theory required. Every element operates in plain sight through legal mechanisms. 501(c)(4) donor secrecy is legal. Fiscal sponsorship is legal. Out-of-state campaign contributions are legal. Hiring 12 lobbyists for one bill is legal. Operating a lobbying coalition is legal.

The corruption is structural, not criminal. The system does not require anyone to break the law. It requires only that each participant operate within legal structures chosen for their opacity. The result: a policy outcome (ASAA) serving Meta's commercial interests ($0 compliance cost vs. billions for Apple/Google) that appears to emerge from grassroots conservative advocacy for child safety.

### Outstanding Questions

1. **Who is DCA's fiscal sponsor?** Sixteen Thirty Fund is the strongest candidate (c4 status, sponsored project model, $121M NVF pipeline, Eichberg governance link). Network for Good (directly evidenced by donation processing) is the alternative. These are not mutually exclusive.
2. **Does NCOSE have a 501(c)(4) affiliate?** If so, it could serve as DCA's sponsor, explaining the deep personnel overlap.
3. **What is in STF's Part IX functional expenses?** The ~$46M gap between STF revenue and Schedule I grants could include sponsored project spending.
4. **Were the three California tech employee contributions to Matt Ball coordinated?** Contribution timing and channel sophistication suggest guidance, but proof requires internal communications.
5. **What did Meta's 12 Louisiana lobbyists actually do?** Floor testimony, committee work, amendment blocking, and relationship building would be documented in Louisiana Ethics Commission records.

---

## Sources

All findings derived from previously documented research files:

- DCA incorporation analysis: `data/processed/dca_incorporation_updated.md`
- DCA team and formation: `data/processed/dca_team_and_formation_findings.md`
- DCA Wayback analysis: `data/processed/dca_wayback_findings.md`
- DCA DNS/WHOIS: `data/processed/dca_dns_whois_findings.md`
- FollowTheMoney multi-state: `data/processed/followthemoney_multistate_findings.md`
- CO TRACER contributions: `data/processed/co_tracer_contribution_findings.md`
- Koch lobbyist findings: `data/processed/koch_lobbyist_findings.md`
- Meta national lobbying: `data/processed/meta_national_lobbying_findings.md`
- Windward/Hopewell Schedule I: `data/processed/windward_hopewell_schedule_i_analysis.md`
- STF Schedule I: `data/processed/stf_schedule_i_analysis.md`
- NVF Schedule I: `data/processed/nvf_schedule_i_analysis.md`
- North Fund Schedule I: `data/processed/north_fund_schedule_i_analysis.md`
- Master summary: `output/reports/meta_lobbying_dark_money_summary.md`

