# ConnectSafely Inc. (EIN 47-3168168) — 990 Filing Analysis

## Summary

ConnectSafely Inc. is a 501(c)(3) internet safety nonprofit based in Palo Alto, CA, founded in 2015. It is publicly known to receive funding from Meta, Google, Amazon, Microsoft, Snapchat, TikTok, Roblox, Discord, Comcast, and other tech companies. Despite this, **no tech company name appears anywhere in any of its ten years of IRS Form 990 filings (2015-2024)**, and the organization has used an unusual revenue classification scheme that effectively shields all donor identities from public disclosure.

**Source data:** IRS Form 990 XML e-filings downloaded from ProPublica Nonprofit Explorer for all ten filing years (2015-2024). Object IDs: 202501349349311580, 202400869349300625, 202341309349302794, 202221329349305277, 202140719349301614, 202031299349300448, 201900739349300025, 201810409349301426, 201710629349300101, 201640789349300534.

---

## Finding 1: Revenue Misclassification Pattern (2015-2023)

For nine consecutive years (2015-2023), ConnectSafely reported **$0 in Contributions/Grants (Part I, Line 8)** and classified all donor revenue as **"Program Service Revenue"** (Part VIII) with the description **"Donations"** and NAICS business code **611710** (Educational Support Services).

This is taxonomically unusual. "Donations" are, by definition, contributions — they should be reported on Line 1h (Contributions/Grants), not as program service revenue. Program service revenue typically covers fees charged for services rendered, not gifts from supporters.

The consequence: because all income is classified as "program service revenue" rather than "contributions," **Schedule B (Schedule of Contributors) was never triggered**. Schedule B requires disclosure of contributors who gave more than $5,000 or 2% of total contributions. With $0 reported in contributions, there are no contributions to trigger the threshold.

Yet on **Schedule A** (Public Charity Status test), these same amounts are treated as **"Gifts, Grants, Contributions Received"** for the 170(b)(1)(A)(vi) public support calculation. The organization passes the 33-1/3% public support test using revenue it classifies as "not contributions" on the main return but "contributions" on the support schedule.

| Year | Contributions (Line 1h) | Program Svc Rev ("Donations") | Sched B Filed? |
|------|------------------------|-------------------------------|----------------|
| 2015 | $0 | $316,722 | No |
| 2016 | $0 | $409,648 | No |
| 2017 | $0 | $435,583 | No |
| 2018 | $0 | $296,725 | No |
| 2019 | $0 | $449,592 | No |
| 2020 | $0 | $373,813 | No |
| 2021 | $0 | $370,500 | No |
| 2022 | $0 | $935,025 | No |
| 2023 | $0 | $612,632 | No |
| **2024** | **$703,602** | **$0** | **Yes** |

**In 2024, the classification abruptly reversed.** All revenue was reported as Contributions/Grants ($703,602) with $0 in Program Service Revenue. This triggered Schedule B for the first time — but Schedule B contributor names are **redacted** in the public copy of 501(c)(3) filings (only the IRS sees the full version).

**Bottom line:** For nine years, ConnectSafely classified what its own filing calls "Donations" as program service revenue rather than contributions, avoiding Schedule B disclosure entirely. When the classification was corrected in 2024, the Schedule B names are still redacted under the c(3) exemption.

---

## Finding 2: Known Supporters vs. 990 Disclosure

ConnectSafely's own website and press releases publicly list its supporters. From Safer Internet Day press releases and the connectsafely.org/about-us/supporters/ page:

**Confirmed supporters (various years):**
- Amazon / Amazon Kids
- Comcast
- Discord
- Google
- Meta (formerly Facebook)
- Meet Group
- Microsoft
- NCTA — The Internet & Television Association
- OpenAI
- Roblox
- Snapchat / Snap
- TikTok
- Trend Micro
- Twitch
- Twitter
- ZEPETO

The Tech Transparency Project confirmed Meta has funded ConnectSafely since at least 2017, and ConnectSafely CEO Larry Magid stated the organization "advises and receives support from Facebook." ConnectSafely is listed as a member of Meta's Safety Advisory Council, receiving honorariums.

**None of these companies appear anywhere in any of the ten 990 filings.** No donor, supporter, sponsor, or partner is named in any schedule or narrative.

---

## Finding 3: $100,000 Annual Grant to Unnamed UK Organization

Starting in 2022, ConnectSafely has made a consistent annual foreign grant to an unnamed organization in the United Kingdom:

| Year | Amount | Method | Recipient |
|------|--------|--------|-----------|
| 2022 | $97,500 | Wire | UK org — "To support an international organization with similar goals" |
| 2023 | $100,000 | Wire | UK org — "To support an international organization with similar goals" |
| 2024 | $100,000 | Wire | UK org — "To support an international organization with similar goals" |

The recipient is never identified. This is approximately 13-15% of annual revenue flowing to a single unnamed foreign entity. No foreign grants were made prior to 2022.

**Possible candidates:** The UK Internet Watch Foundation (IWF), the UK Safer Internet Centre, or Childnet International — all operate in the same internet safety space. This could also be connected to the global Safer Internet Day network (coordinated from Belgium/UK). Further investigation could narrow this down.

---

## Finding 4: Financial Profile and Revenue Trends

### 10-Year Revenue Summary

| Year | Total Rev | PSR "Donations" | Other Rev | Total Exp | Net Assets | Magid Comp | Kochan Comp |
|------|-----------|-----------------|-----------|-----------|------------|------------|-------------|
| 2015 | $316,801 | $316,722 | $0 | $334,511 | $234,927 | $105,417 | $75,000 |
| 2016 | $409,729 | $409,648 | $0 | $318,974 | $325,682 | $115,000 | $81,000 |
| 2017 | $944,031 | $435,583 | $508,063* | $360,515 | $909,198 | $141,250 | $87,750 |
| 2018 | $297,209 | $296,725 | $0 | $321,188 | $885,219 | $137,500 | $90,000 |
| 2019 | $450,073 | $449,592 | $0 | $358,956 | $976,336 | $162,500 | $90,000 |
| 2020 | $419,506 | $373,813 | $39,810** | $370,465 | $1,025,377 | $157,500*** | $95,413*** |
| 2021 | $411,714 | $370,500 | $41,045** | $338,530 | $1,098,561 | $161,437 | $93,588 |
| 2022 | $938,843 | $935,025 | $0 | $475,379 | $1,562,025 | $166,031 | $117,996 |
| 2023 | $653,869 | $612,632 | $0 | $601,038 | $1,614,856 | $208,293 | $129,839 |
| 2024 | $784,500 | $0 (reclassified) | $0 | $673,139 | $1,726,217 | $218,708 | $143,693 |

\* "Class action suit" — likely a cy pres award from a tech privacy settlement
\** PPP loan forgiveness (classified as UBI in 2020, exempt income in 2021)
\*** Reported as compensation from "related organizations" — the only year with this anomaly

### Notable patterns:
- **Revenue concentration:** 5-year support test shows large lump sums rather than broad-based small donations. Consistent with a handful of large corporate donors.
- **2017 spike:** Entirely explained by $508,063 "class action suit" — a cy pres recipient award. Underlying revenue was ~$436K.
- **2022 spike:** $935,025 — the highest "Donations" year. No explanation in filings. May correspond to increased tech company contributions following the Meta/Messenger Kids expansion.
- **Persistent surplus:** Net assets grew from $235K (2015) to $1.73M (2024). The organization accumulated ~$1.5M in reserves on $400-900K annual revenue.
- **Two full-time employees only:** Magid and Kochan are the entire operation. Combined comp rose from $180K (2015) to $362K (2024).

---

## Finding 5: Governance Weaknesses

Across all ten filing years, ConnectSafely consistently reports:

- **No whistleblower policy**
- **No document retention policy**
- **No formal compensation process for CEO** (CompensationProcessCEOInd = 0)
- **No formal compensation process for other officers** (CompensationProcessOtherInd = 0)
- **No independent financial audit** (despite $1.7M in assets)
- **No annual disclosure by covered persons**
- **No regular monitoring/enforcement of conflict of interest policy**

Board: same 5 members for all 10 years. Three unpaid directors (Hempstead, Blumenfeld, Needle) work 1 hour/week each.

In 2024, officer compensation was 57.5% of total expenses ($387,087 of $673,139).

---

## Finding 6: 2020 Compensation Reporting Anomaly

In 2020 only, officer compensation was reported as paid by **"related organizations"** rather than ConnectSafely directly:
- Magid: $157,500 from related orgs, $0 from ConnectSafely
- Kochan: $95,413 from related orgs, $0 from ConnectSafely

This reverted to normal in 2021. No Schedule R (Related Organizations) was filed. No explanation is provided in Schedule O. This raises the question: what "related organization" paid ConnectSafely's staff in 2020?

---

## Finding 7: Subcontractor Spending

ConnectSafely reports "Subcontractors" as a significant program expense, but never identifies the contractors:

| Year | Subcontractor Expense |
|------|----------------------|
| 2022 | $24,891 |
| 2023 | $46,135 |
| 2024 | $86,505 |

The figure nearly quadrupled in two years, growing from 5.2% to 12.8% of total expenses. No contractor names or descriptions appear in the filing.

---

## Finding 8: Schedule A Support Test Anomaly

The Schedule A public support test creates an internal contradiction:

1. **Part VIII** classifies all revenue as "Program Service Revenue" (not contributions)
2. **Schedule A** treats the same revenue as "Gifts, Grants, Contributions Received" for the 170(b)(1)(A)(vi) test

These cannot both be correct. If the payments are truly program service revenue (fees for services rendered), they should not count as "gifts, grants, contributions" on the support schedule. If they are contributions, they should be reported on Line 1h, which would trigger Schedule B.

The organization passes the 33-1/3% public support test every year (ranging from 68-96%), suggesting the IRS accepts these amounts as public support. But the dual classification allows ConnectSafely to:
1. Qualify as a public charity (Schedule A treats income as contributions)
2. Avoid disclosing contributors (Part VIII treats income as program service revenue)

---

## Relevance to Meta/ASAA Investigation

ConnectSafely is mentioned in the OSINT_TASKLIST as a potential conduit for Meta funding. The 990 analysis reveals:

1. **Meta is a confirmed supporter** (publicly listed, confirmed by TTP reporting), but its contributions are completely invisible in all IRS filings
2. **The revenue classification scheme** effectively shields all donor identities — there is no way to determine Meta's contribution amount from public filings alone
3. **ConnectSafely received NVF grants: UNKNOWN** — NVF's Schedule I analysis found zero grants to ConnectSafely, ruling out that pathway
4. **The 2024 reclassification** may indicate a change in how ConnectSafely structures its tech company relationships, possibly in response to increased scrutiny of tech-funded advocacy groups
5. **The unnamed UK grant** ($100K/year) could be a mechanism for supporting international child safety advocacy aligned with Meta's interests
6. **Larry Magid testified in support of Meta-backed positions** and ConnectSafely was cited in Meta's legal filings opposing state social media regulation

ConnectSafely is not DCA — it has a longer track record, genuine internet safety programming, and publicly discloses its tech company supporters. But its 990 filings demonstrate that even organizations that publicly acknowledge tech funding can structure their IRS reporting to prevent any quantification of that funding from public records.

---

## Files Analyzed

All XML files stored at: `data/raw/connectsafely_990/`
- cs_2015.xml through cs_2024.xml (10 files)
- cs_2017.pdf, cs_2022.pdf, cs_2023.pdf (Cloudflare-blocked, HTML error pages)

## Sources

- ProPublica Nonprofit Explorer: https://projects.propublica.org/nonprofits/organizations/473168168
- Tech Transparency Project: https://www.techtransparencyproject.org/articles/inside-metas-spin-machine-on-kids-and-social-media
- ConnectSafely Supporters Page: https://connectsafely.org/about-us/supporters/
- Safer Internet Day 2022 Press Release (BusinessWire): https://www.businesswire.com/news/home/20220207005147/en/ConnectSafely-Announces-Safer-Internet-Week-2022
- Safer Internet Day 2024 Press Release: https://safer.connectsafely.org/2024-press-release/

