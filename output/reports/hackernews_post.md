# Hacker News Submission

**Title:** Show HN: OSINT investigation into who's behind the US age verification bills and why none exempt FOSS

**URL:** https://github.com/upper-up/meta-lobbying-and-other-findings

**Text (plain text, no markdown):**

I spent several months pulling public records on the age verification bills moving through US state legislatures. IRS 990 filings, Senate LD-2 lobbying disclosures, state ethics databases, campaign finance records, corporate registries, Wayback Machine archives. The repo above contains all findings with sources embedded in each file.

The short version:

Six states have introduced or enacted bills defining "Operating System Provider" as anyone who "develops, licenses, or controls" an OS on any general-purpose computing device. California AB-1043 (effective Jan 2027) requires every OS to expose a real-time API broadcasting user age brackets to all installed applications. None of these bills contain any exemption for open-source software, non-commercial projects, or volunteer developers. The EU's Digital Services Act explicitly exempts FOSS through five separate mechanisms. The US versions do not.

Rep. Kim Carver, the sponsor of Louisiana's HB-570, publicly confirmed that a Meta lobbyist brought the legislative language directly to her. The bill as drafted required only app stores to verify ages. Not social media platforms. Meta deployed 12 lobbyists for this bill, which passed 99-0. The lobbyists were there to control the text, not the votes.

Meta's own LD-2 filings with the Senate explicitly list the App Store Accountability Act as a lobbied bill. In the same filing, Meta lobbies on KOSA and COPPA 2.0, which would regulate Meta directly. It supports legislation burdening competitors and works to weaken legislation burdening itself.

The "grassroots" group pushing these bills nationally, the Digital Childhood Alliance, has no EIN in the IRS system and no incorporation record in any state registry I searched. Bloomberg exposed Meta as a funder in July 2025. The same consulting firm (Hilltop Public Solutions) co-leads Meta's $45M super PAC and coordinates DCA's messaging.

I analyzed $2.0 billion in grants across the Arabella Advisors dark money network (4,433 grants, five entities). Zero dollars went to any child safety or tech policy organization. That pathway is ruled out. I also searched 59,736 recipients of DCA's donation processor. Zero matches. DCA's actual funding comes from Meta directly.

Meta's Horizon OS (Quest headsets) has 83% compliance with these mandates. Linux distributions have 14%. Commercial age verification vendors charge $0.10-$2.00 per check via proprietary SDKs incompatible with GPL licensing. A mid-size distro would face $100K-$2M/year in verification fees.

Every finding cites a primary source. Claude Code was used as a research tool for bulk data parsing; methodology disclosure is in the repo. Start with the records, not with my analysis.

---

**Character count of text field: ~1,970 characters (well under 4,000)**
