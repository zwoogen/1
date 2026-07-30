# VGIC Default Tone & Positions — Full Verification Report

**Source corpus:** 297 public regulatory filings listed at vgicouncil.org/filings, spanning January 6, 2020 – July 29, 2026. Filings were downloaded, text-extracted, and indexed in `filings_index.csv`; raw documents and paired `.txt` extractions are in `/filings`. This report synthesizes patterns across the full corpus and cites representative filings by date and title; it does not reproduce large verbatim passages from any single filing.

---

## 1. Who VGIC Is (as the record shows it)

The Vehicle-Grid Integration Council (VGIC) is a 501(c)(6) membership-based trade association/advocacy organization. Its standard self-description, used verbatim or near-verbatim across dozens of non-CPUC filings (e.g., *Massachusetts Draft 2022-2024 Energy Efficiency Plan Comments*, July 9, 2021; *New Hampshire EV Charging Programs Initial Comments*, March 21, 2023), is:

> "The Vehicle-Grid Integration Council (VGIC) is a 501(c)(6) [membership-based advocacy group / trade association / nonprofit member-based association] committed to advancing the role of electric vehicles (EVs) and vehicle-grid integration (VGI) through policy development, education, outreach, and research."

Membership figures cited in sworn testimony grew steadily across the record: "13 member companies" (Sept. 2021 testimony), "19 members" (April 2022), "25 members" (Dec. 2022), "33 members" (2023 testimony). Recurring members named in signature blocks, coalition letters, and "Leadership Circle" listings include EV OEMs (American Honda, Ford, General Motors, Nissan, Stellantis, BMW, Tesla, Rivian) and VGI/charging technology and service providers (Nuvve, Fermata Energy, The Mobility House, Enel X, WeaveGrid, Wallbox, ChargePoint, Enphase, Sunrun, Siemens, Greenlots).

Staff authorship traces an organizational arc: Ed Burgess (Policy Director → Senior Policy Director) is the primary signatory 2020–2024; Zach Woogen appears from 2020 as Policy Specialist/Manager, becomes Senior Policy Manager (2023), Interim Executive Director (mid-2024), and Executive Director (2025–2026); Albert Tapia serves as Policy Analyst (2022–2024); Steve Letendre, PhD joins as Senior Advisor in late 2025, authoring most non-California filings from that point forward. This progression — a two-person CPUC-focused shop becoming a multi-state advocacy organization with an Executive Director and dedicated non-CA staff — tracks the organization's geographic and substantive expansion described in Section 4.

---

## 2. Recurring Rhetorical Style and Tone

### 2.1 Opening conventions

VGIC's filings split into two structural families, and each has a fixed opening pattern:

- **California Public Utilities Commission (CPUC) formal filings** (comments, reply comments, briefs, testimony) open with the standard CPUC caption block ("BEFORE THE PUBLIC UTILITIES COMMISSION OF THE STATE OF CALIFORNIA," the relevant Rulemaking/Application number and filing history) followed by an all-caps title restating the filing type and subject (e.g., "COMMENTS OF THE VEHICLE-GRID INTEGRATION COUNCIL ON THE PROPOSED DECISION..."). See nearly any CPUC filing, e.g. *CA Dynamic Rate Pilot Expansion Staff Proposal Comments*, Sept. 25, 2023.
- **CPUC advice letter responses/protests** are addressed as business letters to the "CPUC Energy Division Tariff Unit," invoking General Order 96-B, and open "Re: Response/Protest of the Vehicle-Grid Integration Council to Advice Letter [#] of [Utility]" (e.g., *SCE Establishment of Rule 29 Pursuant to AB 841 Advice Letter Response*, March 18, 2021).
- **Non-CPUC filings** (other state commissions, CEC dockets, federal RFIs) open with a short "Introduction" that states the proceeding/docket and then inserts VGIC's standard self-description boilerplate (Section 1) before turning to substance. This format is consistent from VGIC's earliest multi-state filings (2021 Massachusetts DPU comments) through its most recent (2026 New Mexico, Connecticut, New Jersey filings).

### 2.2 Closing conventions

Nearly every filing in the corpus — across all seven years and every jurisdiction — closes with a two-part convention:
1. A brief appreciation/forward-looking sentence, almost always some variant of: *"VGIC appreciates the opportunity to [submit/provide] these [comments/reply comments] and looks forward to further collaboration with the Commission and stakeholders on this [initiative/proceeding]."* This phrase (or a close paraphrase substituting the specific utility/agency name) appears in the great majority of the 297 filings, making it VGIC's single most identifiable stylistic signature.
2. "Respectfully submitted" (CPUC filings) or "Sincerely"/"Respectfully submitted" (letters to other agencies), followed by the author's name, title, "Vehicle-Grid Integration Council," and contact information.

### 2.3 Register and rhetorical habits

- **Collaborative-advocate register, not adversarial-litigant register.** Even in filings captioned "Protest" or containing blunt disagreement, VGIC frames itself as a technical stakeholder helping regulators reach a better outcome, not as an opponent. Disagreement is stated directly but briefly, then followed by constructive alternative recommendations.
- **Emphasis is signaled lexically, not typographically, in most filings** — "VGIC strongly supports," "VGIC strongly recommends," "VGIC strongly urges," "VGIC strongly opposes" — with "strongly" reserved for positions VGIC treats as high-priority. A secondary, more assertive convention appears in select filings: short position statements rendered in ALL CAPS as de facto subheadings (e.g., "VGIC STRONGLY OPPOSES PG&E'S ASSERTION THAT A RULE 21 INTERCONNECTION AGREEMENT IS NECESSARY TO PARTICIPATE IN ELRP GROUP A.5," Nov. 16, 2021 reply comments; "VGIC RECOMMENDS THE COMMISSION ADOPT A MORE SPECIFIC SET OF ALM DEFINITIONS AND TECHNICAL REQUIREMENTS," Dec. 5, 2022).
- **Hedged, deferential verbs dominate:** "VGIC believes," "VGIC recommends," "VGIC respectfully requests," "VGIC appreciates." Even reply comments correcting a utility's stated position typically use "VGIC believes [utility] is mistaken" rather than accusatory language.
- **Heavy use of footnoted legal/technical citation** — CPUC decisions, advice letters, prior VGIC comments, other parties' comments, technical standards (UL 1741, IEEE 1547) — reflecting a policy-technical rather than political voice.
- **Recurring framing vocabulary:** "no-regrets" (recommendations framed as low-risk/low-cost improvements regardless of how a proceeding resolves), "voluntary" and "carrot rather than a stick" (opposing mandates in favor of incentives, especially for Automated Load Management), "technology-neutral," "narrowly tailored," "grid resource"/"flexible load resource" (framing EVs as an asset to the grid rather than merely a source of new demand).
- **Addressing regulators:** Consistently deferential and procedural — "Dear Sir or Madam," "Hon. [Name], Secretary," acknowledgment of specific ALJs/Commissioners by name and citation to the specific ruling being responded to.
- **Addressing utilities:** Direct but professional even when disagreeing; utilities are referred to by name and specific advice letter/exhibit number rather than characterized generally.

---

## 3. Core Substantive Positions by Topic

### 3.1 Dynamic rates / V2G export compensation

VGIC consistently favors dynamic, cost-reflective rate structures (day-ahead, real-time pricing) over static demand charges, and consistently pushes for export compensation that reaches non-Net-Energy-Metering, non-Qualifying-Facility EV and V2G resources at or near marginal cost. Representative positions: support for PG&E's day-ahead real-time pricing pilot design (2021–2022 dockets); a 2025 push ("VGIC strongly urges the Commission to modify the PD to explicitly direct the IOUs to offer dynamic export compensation for non-NEM, non-QF customer resources and aggregations," Aug. 14, 2025 comments) that continued into 2026 briefing on SCE's dynamic rate application, where VGIC's closing position was that "the Commission should require SCE to include dynamic export compensation based on unscaled marginal costs" (July 1, 2026 opening brief). VGIC also consistently pushes for **dual participation** — allowing customers to be on a dynamic rate *and* enroll in demand response/emergency programs — treating utility arguments against dual participation as barriers to be dismantled rather than settled policy.

### 3.2 Interconnection standards (Rule 21 and equivalents)

VGIC is a sustained participant in California's Rule 21 proceedings from the earliest filings in the corpus (2020 V2G-AC Interconnection Subgroup comments) through the new Rule 21 rulemaking opened in 2025–2026. Its consistent position is that interconnection requirements should be proportionate to the actual grid-safety risk of a given configuration: it has repeatedly opposed extending full Rule 21 Interconnection Agreement requirements to one-way (V1G) charging or to isolated/non-grid-parallel backup power systems (e.g., opposing PG&E's position that a Rule 21 IA is required for ELRP Group A.5 participation, Nov. 2021; supporting Ford's 2026 petitions in Colorado and Texas that disabled, non-grid-parallel home backup power systems should not trigger interconnection rules). It supports streamlined, appropriately scoped certification (UL 1741 SA/SB/SC, IEEE 1547) and has opposed utility-specific add-ons it views as duplicative (opposing SCE's proposed third-party testing requirement, Jan. 2020 reply comments). In newer filings (2025–2026) it increasingly pushes for standardized, low, cost-justified interconnection fees and clearer backup-power-specific application portals.

### 3.3 Managed charging / Automated Load Management (ALM)

VGIC supports managed charging and ALM as tools to defer distribution upgrades and manage EV load, but insists these programs remain **voluntary** and incentive-driven — a "carrot rather than a stick" (2021 CPUC comments) — rather than utility-mandated. It has repeatedly pushed for clearer technical definitions and standards for ALM (2022 PG&E EV Charge 2 proceeding) and opposed utilities positioning themselves as the sole authority over ALM design and evaluation (opposing PG&E's proposed sole-authority role, March 2022 testimony). By 2025–2026, VGIC's managed-charging advocacy extends to reviewing utility-run managed charging pilots and reports directly (e.g., New York Joint Utilities' residential managed charging report, mid-2026) and to supporting centralized/orchestrated managed-charging program designs like SCE's ORCHARD program (March 2026), while pushing for those programs to also include dedicated incentives for bidirectional (V2G) hardware, not just managed one-way charging.

### 3.4 Demand response (DR) programs

VGIC treats EV and V2G resources as underused DR assets and consistently advocates for their fuller, easier inclusion in DR and emergency programs, especially California's Emergency Load Reduction Program (ELRP). Recurring asks: allow telematics-based (rather than only hardware-submeter-based) participation and aggregation; permit dual participation between dynamic rates and ELRP/DSGS; extend or preserve EV-specific DR customer groups (e.g., ELRP Group A.5) rather than folding them into generic DR categories or reducing their minimum dispatch/compensation levels. VGIC opposed SCE's 2022 proposal to reduce ELRP compensation to $1/kWh and eliminate minimum dispatch requirements as premature, and opposed PG&E's position that Rule 21 interconnection agreements should gate ELRP eligibility. Its posture is generally to defend and modestly expand existing DR/ELRP structures rather than seek wholesale redesign.

### 3.5 Submetering and EVSE/telematics standards

VGIC supports submetering protocols and telematics-based measurement as parallel, complementary pathways for verifying EV charging/discharging for rate and program participation, consistently arguing that hardware submeters should not be the only accepted method. It has pushed CPUC and New York PSC proceedings toward clarifying technical standards for both approaches. Notably, in New York's 2025 submetering/telematics proceeding, VGIC took a more cautious position than some coalition partners — agreeing a revenue-grade submetering standard should eventually be adopted, but only after residential EV-specific rate designs are authorized, and explicitly declining to support imposing bespoke state-specific telematics accuracy requirements ahead of national standards efforts (Dec. 2025 comments), disagreeing on this point with the Environmental Defense Fund's more prescriptive recommendation (Dec. 22, 2025 reply comments).

### 3.6 Backup power / V2H (vehicle-to-home)

VGIC has consistently championed V2H/V2X backup power as a customer-resiliency benefit worth regulatory accommodation, from its earliest filings (2020 Microgrid/Resiliency Strategies comments recommending a pilot for EVs as backup power) through 2025–2026 advocacy defending Ford's Intelligent Backup Power product against being swept into full interconnection review in Colorado and Texas, and recommending utilities build dedicated backup-power information portals distinct from standard interconnection workflows (2026 Rule 21 reply comments). It frames backup power as a resiliency and public-safety benefit (e.g., PSPS-related use cases in California) as much as a customer economic benefit.

### 3.7 Transportation electrification (TE) funding

VGIC is a consistent advocate for sustained and expanded TE and VGI funding — rebate programs, LCFS holdback fund use for V2G/V2B and resiliency projects, and CEC programs like Demand Side Grid Support (DSGS) and Distributed Electricity Backup Assets (DEBA). It opposed the CPUC's 2024 proposal to pause California's roughly $1 billion TE Rebate Program, arguing paused funding would slow EV adoption and jeopardize state decarbonization goals — a position it reiterated in 2025 as "even more urgent." When state TE/VGI funding programs faced budget threats in 2025, VGIC co-signed direct coalition letters to the California Legislature (June 2025, August 2025, December 2025) urging preservation of DSGS, DEBA, and Cap-and-Invest/GGRF-funded ZEV programs — a notable escalation from administrative-record advocacy to direct legislative outreach.

### 3.8 IRP / grid planning

VGIC's consistent ask across multiple IRP Inputs & Assumptions cycles (2022, 2023, 2025) is that Integrated Resource Planning processes more accurately model VGI/V2G potential rather than treating EVs as pure load. Specific recurring recommendations include modeling scenario terminology reform (moving away from "passive/active" toward explicit V1G/V1G+V2G scenarios), and running higher-V2G sensitivity cases — VGIC has repeatedly requested a "V2G_High" sensitivity ramping V2G potential from near-zero to 90% of V1G potential by 2050. It has specifically pushed for electric school buses to be recognized in IRP and distribution-planning models as an especially strong V2G resource due to predictable dwell times aligning with system peaks. More broadly, it supports extending utility distribution-planning horizons and better incorporating known/forecast EV load into distribution and grid-needs planning.

---

## 4. Who VGIC Supports vs. Pushes Back Against

**Regulators and staff:** VGIC's default posture toward CPUC Energy Division, administrative law judges, and other state commission staff is collaborative and appreciative, even when disagreeing with a specific proposal. It routinely commends staff for process improvements while asking for additional refinements, rather than characterizing proposals as fundamentally flawed.

**Fellow intervenors/coalition partners:** VGIC frequently co-files with — and is functionally aligned with — clean-energy and EV-industry organizations and its own member companies: Advanced Energy Economy, California Energy Storage Alliance (CESA)/CALSSA, ChargePoint, Enel X, Natural Resources Defense Council, Environmental Defense Fund, Interstate Renewable Energy Council (IREC), NY-BEST, Siemens, and EV OEMs/tech vendors including Honda, BMW, GM, Nissan, Ford, Stellantis, Tesla, Nuvve, Fermata Energy, The Mobility House, WeaveGrid, Wallbox, and Enphase. It also aligns with demand-response/DER aggregators (Leap, Voltus, CPower, Renew Home, Sunrun) on dynamic-rate and DR dual-participation questions. Notably, alignment is not automatic: VGIC has disagreed even with allied organizations on specific technical points (e.g., diverging from EDF's telematics accuracy-standard proposal in New York, Dec. 2025).

**Utilities:** VGIC's primary friction is with California's three large investor-owned utilities — Pacific Gas & Electric, Southern California Edison, and San Diego Gas & Electric — on specific implementation details: interconnection-agreement scope, ALM authority and definitions, export-compensation completeness, and DR compensation/dispatch levels. PG&E draws the largest volume of direct pushback across the corpus (interconnection agreement scope for ELRP, sole ALM authority, submetering compliance questions, V2G interconnection form design). SCE draws pushback chiefly on dynamic-rate/export-compensation completeness and proposed DR compensation reductions. Even so, VGIC also frequently supports specific utility proposals it views as beneficial (e.g., supporting PG&E's real-time-pricing motion to consolidate proceedings, Jan. 2021; supporting SCE's ORCHARD managed-charging program, March 2026; ultimately supporting adoption of the SCE Vehicle-to-Grid Rate Proposal settlement it helped negotiate, April 2026) — the relationship is adversarial on discrete issues, not categorically oppositional.

---

## 5. Evolution 2020 → 2026

**Volume and geographic scope grew steadily.** Filing counts by year: 2020 (26), 2021 (38), 2022 (43), 2023 (46), 2024 (52), 2025 (55), 2026 year-to-date through July (37). The 2020–2021 record is almost entirely California CPUC proceedings (Transportation Electrification Framework, Rule 21 working groups, SGIP, Microgrids). Massachusetts DPU comments begin mid-2021; New York PSC and federal RFI comments begin 2021–2022; Michigan, New Hampshire, Illinois, and Colorado filings appear from 2022–2023; Maryland and Texas from 2024; Virginia, Nevada, New Jersey, New Mexico, Connecticut, and Washington DC from 2025–2026. This mirrors membership growth (13 members in 2021 to 33+ by 2023) and staff growth (a two-person shop expanding to include a dedicated non-California Senior Advisor by late 2025).

**Substantive focus shifted from foundational rulemaking participation to implementation and enforcement.** Early filings (2020–2021) focus on establishing baseline rules — V2G-AC interconnection standards, TEF framework sections, ALM definitions. The middle period (2022–2023) shifts toward rate design and program-eligibility fights: export-compensation rate cases, submetering implementation, ELRP eligibility. The later period (2024–2026) is dominated by V2G/V2X-specific advocacy — bidirectional charging equipment rebates, backup-power/V2H standards (including direct engagement in Ford's multi-state home-backup-power declaratory petitions), and, notably, direct participation in negotiating and defending **settlement agreements** on V2G export rates (SCE's Vehicle-to-Grid Rate Proposal settlement, 2025–2026) — a shift from commenting on others' proposals to co-authoring negotiated outcomes.

**Tone has remained essentially constant.** The collaborative, "appreciates the opportunity"/"looks forward to further collaboration" register, the footnote-heavy technical-legal writing style, and the preference for incentive-based/voluntary program design are stable from the earliest 2020 filings through the most recent 2026 filings. What has changed is confidence and specificity: later-period filings more often state VGIC's position in bolded/capitalized topic sentences and more often reference VGIC's own prior comments as precedent ("As discussed in VGIC's reply comments in that proceeding...").

**Leadership transition is a structural throughline.** Ed Burgess is the dominant signatory through 2024; Zach Woogen's title progression (Policy Specialist → Policy Manager → Senior Policy Manager → Interim Executive Director → Executive Director) tracks almost exactly with the organization's 2022–2025 growth phase, and Steve Letendre's 2025 arrival as Senior Advisor coincides with — and appears to enable — the sharp expansion into new states (Virginia, Nevada, New Jersey, New Mexico, Connecticut, DC) in the 2025–2026 filings.

---

## 6. Jurisdictions by Activity

Based on the 297-filing index (jurisdiction assigned from filing titles/proceeding context; see `filings_index.csv`):

| Jurisdiction | Filings | Share |
|---|---|---|
| California | 217 | 73% |
| New York | 30 | 10% |
| Massachusetts | 12 | 4% |
| Maryland | 8 | 3% |
| Federal | 6 | 2% |
| Colorado | 3 | 1% |
| Texas | 3 | 1% |
| Nevada | 3 | 1% |
| Connecticut | 3 | 1% |
| Illinois | 2 | <1% |
| Michigan | 2 | <1% |
| Virginia | 2 | <1% |
| New Mexico | 2 | <1% |
| New Hampshire | 1 | <1% |
| District of Columbia | 1 | <1% |
| New Jersey | 1 | <1% |
| Other/multi-state (Duke Energy, NC) | 1 | <1% |

California dominates the record by a wide margin, consistent with VGIC's origin as a CPUC-focused organization and the CPUC's status as the most active VGI/V2G-related regulatory venue in the country over this period. New York is a distant but clear second, reflecting a sustained multi-year engagement with the New York PSC's EV Supply Equipment and Infrastructure proceeding (Case 18-E-0138) and the Demand Charge Alternatives proceeding (Case 22-E-0236). The remaining states show a pattern of episodic, docket-specific engagement (typically triggered by a specific interconnection rulemaking, V2G/VPP pilot proposal, or utility rate case) rather than sustained ongoing participation — consistent with VGIC's smaller staff footprint outside California and New York.

---

## 7. Methodology Notes and Limitations

- Jurisdiction, filing type, and docket/proceeding fields in `filings_index.csv` were assigned via a rule-based classifier applied to filing titles (and, for docket numbers, filing text) rather than manual review of every filing; a small number of filings (~1%) remain ambiguous (flagged as "Unclear/Multi-state" or "Other/Unclear").
- Substantive positions above are synthesized from full-corpus keyword/pattern searches across all 297 extracted-text files combined with close reading of a stratified sample (opening/closing text of every filing, plus targeted topical passages), not from reading every filing in full; low-frequency or highly idiosyncratic positions in individual filings may not be reflected.
- All filings characterized here are matters of public regulatory record; this report paraphrases and characterizes positions rather than reproducing filing text at length. Readers needing the exact language of a specific position should consult the underlying filing via `filings_index.csv`.
