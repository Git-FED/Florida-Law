# FLHSMV Site Study — Full Study of flhsmv.gov

Studied: Monday, November 23, 2026. 18 workers, one per site section. About 400 page reads (some pages counted twice across sections; unique pages lower). Primary source only: flhsmv.gov pages themselves.

**Method caveat, read first:** flhsmv.gov rate-limited the study heavily. Many direct `browser.open` calls returned HTTP 429 (and a few 403). Per the brief, those were NOT retried; the affected pages were read from search-indexed copies of the exact same flhsmv.gov URLs and are flagged as such inside each section file. Facts from a live full-page open are the strongest; facts from an indexed copy are labelled. A live re-check of the 429'd pages is still worthwhile.

**How this file is organized:** Part 0 below is the corrections section — what this study changes in the Florida law reference (`~/workspace/your_files/florida-traffic-law-reference.md`). Parts 1–18 are the section studies, in the same order as the section files in `~/workspace/flhsmv-study/`.

---

# Part 0 — Corrections to the Florida Law Reference

These are the findings from this FLHSMV study that change, confirm, or put in doubt what the earlier Florida law sweep wrote. The most important one is #1.

## 1. Lifetime traffic-school limit: 5 vs 8 — the reference's "8" is now IN DOUBT (top correction)

The earlier sweep wrote, as a top correction, that the lifetime limit is **8**, verified verbatim from the 2024 Florida Statutes § 318.14(9) text ("may not make more than eight elections within his or her lifetime"), and that the July 1, 2024 amendment raised it from 5 to 8 while FLHSMV pages saying 5 were stale.

This study found the opposite on FLHSMV's **current** pages, confirmed by four independent workers:

- Driver Improvement Schools page, BDI page, Traffic Citations page, and Driving Records FAQ all say **FIVE** elections in a lifetime.
- The Driving Records FAQ expressly attributes 5 to **§ 318.14(9), effective July 1, 2024**.
- The "8" survives only in the legacy Driver Improvement Courses FAQ (dicfaqa.html) and a stale search-indexed copy of the BDI page (one worker saw the BDI page itself show "eight" in a search-index crawl vs "five" in the full-page read).
- The MyDMV worker adds: the current statute/FLHSMV records page says **5 lifetime / once per 12 months (eff. July 1, 2024)**, while the older FLHSMV BDI page and the Palm Beach Clerk still say 8, and an older FLHSMV FAQ says 5-in-10-years.

So two readings of the July 1, 2024 amendment now exist: the earlier sweep's worker read the statute as 8; FLHSMV's current pages read the same amendment as 5. **This is unresolved and must not be asserted either way until someone opens the current § 318.14(9) text live on leg.state.fl.us / Online Sunshine and quotes it.** The reference file's "8" claim should be downgraded to "disputed — FLHSMV's current pages say 5, an earlier statute read said 8, live re-check required."

**For Git-FED personally this changes nothing:** he has 1 election on file, so he is eligible under either limit. It matters only for the reference's accuracy.

## 2. § 316.238 failure to dim — CONFIRMED: moving, 3 points, $60 base fine

FLHSMV's own Appendix C UTC violation/points table (PDF, revised April 2, 2025) lists: "316.238 HEADLIGHTS - FAIL TO DIM — M, m, 3, 60, 195" — M = moving infraction, 3 points, $60 base fine, violation code 195, covering (1)(a) fail to dim for oncoming traffic (within 500 feet) and (1)(b) fail to dim from the rear (within 300 feet). This confirms the reference's § 316.238 findings from FLHSMV itself. Note: no other FLHSMV page names § 316.238 or the $60 fine — FLHSMV defers all fine amounts to the clerk; the $60 on FLHSMV's fee schedule is the D-6 reinstatement fee, a different $60.

## 3. 30-day election window and once-in-12-months — CONFIRMED on multiple FLHSMV pages

BDI must be elected within 30 days of the citation; notify the clerk before attending; pay the fine/fees in that window. Once in any 12-month period. For the Oct 24, 2026 ticket the election window ends today, Monday, November 23, 2026.

## 4. "$7 fee" — NOT on any FLHSMV page

FLHSMV says only "pay an election fee" — amount unstated, clerk-set. The only $7.00 on flhsmv.gov is the motorcycle endorsement fee, a different fee. The $7 election/affidavit fee exists at county clerks (Broward, Charlotte, Okaloosa), not on FLHSMV. The reference should stop citing FLHSMV for the $7 figure.

## 5. Completion window — wrong frame in the reference

The reference says "complete within 90 days of election." FLHSMV says the course must be completed within **60–90 days FROM THE CITATION date**, court-set; the Driver Improvement Schools page says only "within the court-required time period." The MyDMV worker adds the deadline varies by county (Palm Beach 90 days, Lee 60 days). Broward's own clerk page (earlier verification) says 90 days from the election date — that is the Broward-specific rule and is the one that governs Git-FED's Broward ticket, but the reference should not present "90 days from election" as the statewide FLHSMV rule.

## 6. D6 suspension — $60 fee confirmed; no FLHSMV day-count found

- The $60 D6 reinstatement fee is **confirmed on FLHSMV's fee schedule** and on a sanction help page.
- No FLHSMV page states the 10-day clerk notice / 20-day effective timing. That timing rests on Fla. Stat. § 318.15(1)(a) (and the same structure in § 322.245), as the earlier sweep found. FLHSMV pages say only "suspended indefinitely" until the court is satisfied — silent, not contradictory.
- D6 stays on the driving record 1 year after reinstatement, then 2 more years as a correspondence entry.
- Clearance is electronic from the county, then the reinstatement fee is paid at any service center or by phone (850) 617-3000. No hardship license for traffic-citation/court suspensions.

## 7. 180-day hearing — confirmed in statute, deadline computed

Fla. Stat. § 318.15(1)(c): a hearing on the underlying infraction can be requested within 180 days after the date of the violation. For the Oct 24, 2026 ticket that is **Thursday, April 22, 2027**. Caveat: this is a hearing on the infraction, not on the suspension, and no FLHSMV page states the 180-day window — it exists only in the statute.

## 8. $8 vs $10 driving record — CONFIRMED, with the key detail

FLHSMV fee schedule: 3-year record $8, 7-year/complete/certified $10. The $8 3-year record shows **only guilty dispositions** — it does NOT show adjudication-withheld or school-election entries. Only the $10 complete record shows all guilty + adjudication-withheld dispositions, including school-election correspondence entries (retained 75 years). This confirms the reference. The portal's Driver License Check shows the verbatim line "You are currently eligible to elect traffic school."

## 9. FR / insurance — $150–$500 range confirmed; SR-22 probably not required for a pure lapse

- Minimum coverage: $10,000 PIP + $10,000 PDL, continuous through the registration period. Insurers must report cancellations/new policies within 10 days (§ 324.0221).
- A lapse suspends both driver license and registration. Reinstatement fee **$150–$500** (range only on FLHSMV pages). The $150 figure for a first offense is consistent with the bottom of that range (and with the $150/$250/$500 tier split in § 324.0221(3) as reported by secondary sources — the tier split appears on no FLHSMV page opened).
- "Coverage on file before the suspension date prevents the suspension" is verified in substance on FLHSMV pages. The Dec 7, 2026 date itself is from Git-FED's own record, not checkable on public FLHSMV pages.
- SR-22 is required by FLHSMV for crash FR cases only; no SR-22 is mentioned for a plain insurance-cancellation lapse — do not assume one is needed.
- Terminology caution: FLHSMV calls the lapse action a suspension; Git-FED's "FR-CANCELLATION" label should be checked against the FR sanction number/case type (FR100/200/700/800/900) on his Notice of Suspension.
- Do not confuse the fee schedule's general "Suspensions $45.00" fee with the FR $150–$500 range — two different fees.

## 10. New facts not in the reference

- **Sept 4, 2026 FLHSMV data breach:** an international cybercriminal organization accessed FLHSMV records via a Plant City Police Dept user's credentials improperly stored on a personal device; driver license / motor-vehicle data including document images potentially accessed, no evidence of misuse; FLHSMV offers 1 year Sontiq/TransUnion credit monitoring + $1M identity theft insurance; notice under § 501.171 F.S.; FAQ at flhsmv.gov/data-breach.
- **No 2026 legislation summary exists on FLHSMV.** The Legislation Summaries page lists years only through 2022 and was last updated ~2021.
- **Only 2026 rule change found:** driver license exams in English only, effective Feb 6, 2026 (announced Jan 30, 2026).
- **DETS 6-hour course:** since Aug 1, 2025, under-18 first-time drivers must take the 6-hour Driver Education Traffic Safety (DETS) course, not TLSAE; TLSAE is now the 4-hour course for over-18 first-time drivers. Pre–Aug 1, 2025 TLSAE completions grandfathered for 1 year.
- **March 24, 2026 scam alert:** counterfeit court notices demanding payment for traffic/toll violations with fake case numbers, suspension threats, and QR codes. FLHSMV: "will never contact you via text message demanding payment or threatening suspension or arrest."
- **Move Over expansion** (any roadside vehicle with hazards/flares/signage) dates to Jan 1, 2025, not 2026.
- **Crash reports:** $10.00 per report (§ 321.23) + $2.00 non-refundable convenience fee per online transaction; max 10 reports per transaction; reports take up to 10 days to become available; online downloads must be completed within 48 hours; reports confidential for 60 days after filing; self-report form HSMV 90011S within 10 days for crashes not requiring a law-enforcement report.
- **Vision standards discrepancy on FLHSMV's own pages:** General Information says below 20/40 → eye-specialist referral; Vision Standards puts the Form 72010 trigger at 20/50 or worse. Both recorded verbatim, unreconciled.
- **New 2026 credential** (Sept 30, 2026): Castillo de San Marcos front, Discovery shuttle back, nearly double the fraud-protection measures; no replacement required.
- **80+ renewal:** 6-year term (vs 8 years under 80), vision test at every renewal.
- **FHP trooper pay:** $60,000 in academy, $62,400 after graduation, +$5,000/yr in Broward/Miami-Dade/Monroe/Palm Beach; academy ~28–29 weeks.

## 11. Items the reference should stop attributing to FLHSMV

- The $7 election fee (clerk fee, not FLHSMV).
- The $60 citation base fine for § 316.238 (FLHSMV defers fines to the clerk; the Appendix C table is the only FLHSMV source and it is a UTC table, not a fine schedule).
- "90 days from election" as a statewide completion rule (FLHSMV says 60–90 days from citation, court-set).
- The 180-day hearing window (statute only, no FLHSMV page states it).
- The 10-day / 20-day D6 timing (statute only, FLHSMV silent).

---

# FLHSMV Study — Section 01: Education Courses

Study date: 2026-11-23. All facts below are from flhsmv.gov / services.flhsmv.gov pages only, unless a line is explicitly marked as a non-FLHSMV source (used only to explain where a claim comes from when FLHSMV is silent). Page crawl dates are the dates shown by the browser tool for each page read; they are not live-verification dates.

## 1. Pages studied

### 1A. Opened and read in full (browser.open)

| # | Page | URL | Crawl date shown |
|---|------|-----|------------------|
| 1 | Education & Courses (hub) | https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/ | 2026-10-29 |
| 2 | Driver Improvement Schools | http://flhsmv.gov/driver-licenses-id-cards/education-courses/driver-improvement-schools/ | 2026-03-25 |
| 3 | What is Basic Driver Improvement (BDI) + approved providers | https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/driver-improvement-schools/basic-driver-improvement-bdi-find-approved-listing-bdi-course-providers/ | 2025-01-30 |
| 4 | What is Advanced Driver Improvement (ADI) + approved providers | https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/driver-improvement-schools/advanced-driver-improvement-adi-find-approved-listing-adi-course-providers/ | 2026-03-27 |
| 5 | What is TLSAE + approved providers | https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/driver-improvement-schools/traffic-law-substance-abuse-education-tlsae-find-approved-listing-tlsae-course-providers/ | 2026-11-05 |
| 6 | Driver Education Traffic Safety (DETS) | https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/driver-improvement-schools/driver-education-traffic-safety-dets/ | 2026-10-29 |
| 7 | Licensed DUI Programs in Florida | https://flhsmv.gov/driver-licenses-id-cards/education-courses/dui-and-iid/licensed-dui-programs-florida/ | 2026-03-26 |
| 8 | DUI Program Service Fees | https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/dui-and-iid/dui-program-service-fees/ | 2026-01-16 |
| 9 | DELAP Overview | https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/driver-education-licensing-assistance-program-delap-overview/ | 2026-01-16 |
| 10 | Motorcycle Rider Education & Endorsements | http://flhsmv.gov/driver-licenses-id-cards/motorcycle-rider-education-endorsements/ | 2026-07-12 |
| 11 | Motorcycle FAQs | https://www.flhsmv.gov/driver-licenses-id-cards/motorcycle-rider-education-endorsements/faqs/ | 2026-06-13 |
| 12 | Third Party Administrator Program | https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/third-party-administrator-program/ | 2026-01-16 |
| 13 | Driver Improvement Courses FAQ (legacy page) | http://www.flhsmv.gov/ddl/dicfaqa.html | 2026-01-05 |
| 14 | Questions About Driving Records | https://flhsmv.gov/driver-licenses-id-cards/general-information/questions-about-driving-records/ | 2026-08-06 |
| 15 | Fees | https://www.flhsmv.gov/fees/ | 2026-10-26 |
| 16 | A to Z Guide | https://flhsmv.gov/a-to-z-guide/ | 2026-11-04 |

### 1B. Read via search-result text only (browser.open returned HTTP 429 rate-limit; not re-attempted per instruction)

| Page | URL | What the search text established |
|------|-----|----------------------------------|
| Traffic School Completion Check | https://services.flhsmv.gov/trafficschoolcompletioncheck/studentSearchPage.aspx | Lookup by driver license no., certificate no., citation no., or court order no. for driver improvement (basic, advanced, traffic collision avoidance) courses; by DOB + last 4 of SSN / alien registration no. / other identifying no. for first-time driver (TLSAE) courses. Stated purpose: "verifying that a Driver School Course has been taken." |
| Traffic Citations | http://www.flhsmv.gov/FHP/traffic/ | 30-day election window; 18% fine reduction on BDI election; 5-times lifetime limit; mandatory-school offense list; hearing option. |
| Commercial Driving Schools Overview | https://www.flhsmv.gov/ddl/comschool.html | Definitions of commercial driving schools vs driver improvement course providers; ADI/BDI/TLSAE/SCDI roles. |
| How Do I Start a Commercial Driving School? | https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/commercial-driving-schools/start-commercial-driving-school/ | Ch. 488, F.S. licensing; $250 payment ($200 license fee + $50 non-refundable application fee); instructor: 32-hour DITC new / 8-hour refresher, $25 application fee, no suspensions/revocations/cancellations/disqualifications for 3 years prior. |
| How Do I Become a Driver Improvement Course Provider? | https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/commercial-driving-schools/become-driver-improvement-course-provider/ | Course classes: ADI s. 322.291, BDI s. 318.1451, TLSAE s. 322.095, Mature Driver Discount Insurance (SCDI) s. 627.0652; FLHSMV has 90 days to review/respond per s. 120.60(1), F.S. |
| What are 3 crashes in 3 years… | https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/driver-improvement-schools/3-crashes-3-years-complete-requirement/ | 12 hours ADI + 4 hours behind-the-wheel + extended road test; 90 days from conviction or license cancellation. |
| Mature Driver Discount Insurance Courses | http://www.flhsmv.gov/ddl/mature_discount.html | s. 627.0652, F.S.; 55+; discount at insurer's discretion, typically 3 years. |
| DELAP Providers list | https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/driver-education-licensing-assistance-program-delap-overview/driver-education-licensing-assistance-program/ | Approved DELAP administrators by county; completions include TLSAE curriculum; contact FLHSMV 850-617-3682. |
| Safety Course Locations (motorcycle) | https://flhsmv.gov/driver-licenses-id-cards/motorcycle-rider-education-endorsements/safety-course-locations/ | County-by-county FRTP sponsor list; courses offered BRC, BRC2, 3WBRC, S/TEP. |
| Traffic Citations / Court Suspensions (sanctions help) | https://www.flhsmv.gov/wp-json/wp/v2/pages/40220 (page text via search) | Failure to pay / failure to comply / failure to complete school = license suspended indefinitely; reinstatement fee if applicable; clearance via court updating FLHSMV electronically. |
| Clearing Court Suspensions (DLCheck help) | https://services.flhsmv.gov/DLCheck/SanctionHelpPages/Sanction03Help.aspx | "Your driving privilege HAS BEEN SUSPENDED for failing to pay traffic tickets in the time allowed. A $60.00 reinstatement fee is required." |

### 1C. A-to-Z Guide entries relevant to this section (from the guide index)

Advanced Driver Improvement Course; Basic Driver Improvement Course; Commercial Driver Schools (CDL); Driving Courses; Driving Schools; Driving Schools (Requirements needed to open a driving school); DUI; Mature Drivers; Motorcycle Endorsements; Motorcycle Rider Training Program; Senior Drivers; TLSAE; Traffic Schools; Traffic School Completion Check; Behind the Wheel Training; Elder Drivers / GrandDriver / Florida GrandDriver.

## 2. Hub page: Education & Courses

- "If you would like to elect to take the Basic and Advance Driver Improvement Courses, you must make the decision within 30 days of receiving the traffic citation."
- "All new drivers will need to complete the Traffic Law and Substance Education course before applying for a license in Florida."
- "An insurance discount can be available for those who are over 55 years old and take the Mature Driver Discount course."
- "Completion of the Basic RiderCourse® (BRC) is required for all those who wish to obtain a 'Motorcycle Also' endorsement or 'Motorcycle Only' license."
- DELAP providers "conduct Class E examinations, including the Traffic Law & Substance Abuse (TLSAE) curriculum requirement, for high school-enrolled students who want to obtain a learner's or Class E driver license."
- TPA: FLHSMV "uses a web-based application for the administration of Class E Knowledge and Driving Skills Exams called the Automated Driver License Testing System (ADLTS)."

## 3. Driver Improvement Schools (main page)

### 3.1 General information — how completion is reported (most important operational fact in this section)

- "All course providers electronically report all Florida Department of Highway Safety and Motor Vehicles (FLHSMV)-approved school completions to the FLHSMV. Please allow 24 to 72 hours for school completions to be posted."
- "FLHSMV does not accept paper certificates for any licensing purpose."
- "If a driver has been ordered by a court to attend a driver improvement school, they must notify the court once they have completed the school and also provide the necessary documentation to the court."
- TLSAE: "The course provider will electronically submit course completion information to the FLHSMV, which will be accessible at all driver license issuing offices. A physical copy of the course completion certificate is not required when obtaining a license."

So: provider → FLHSMV electronically (24–72 hours to post); paper certificates are NOT accepted by FLHSMV for licensing — but the driver is still separately responsible for proving completion to the COURT (see §4).

### 3.2 Basic Driver Improvement (BDI)

- Eligibility: "If a driver receives a non-criminal moving violation and does not have a commercial driver license, they may elect to attend a FLHSMV-approved basic driver improvement school once every 12 months or a total of five times within their lifetime."
- Election window: "Drivers must voluntarily elect to attend basic driver improvement school within 30 days of the traffic citation. If an election is not made, their right to elect school is forfeited and points are assessed."
- Payment: "Within the 30-day window, the driver must pay the fine and fees for the traffic citation. Upon payment, drivers should also notify the court if they are electing to attend basic driver improvement school. If the fee is not paid within 30 days, their license will be suspended for failure to pay."
- Completion: "Drivers must complete the traffic school course within the court-required time period. If the court-required time is not met, their license will be suspended for failing to attend course."
- Proof: "Drivers must provide required proof of course completion and documentation of the paid fines and fees to the court. It is the driver's responsibility to meet the court reporting requirements."
- **Course hours: the BDI page as read does NOT state a number of hours.** (The 4-hour figure is stated on FLHSMV only for TLSAE and for the 3-crashes behind-the-wheel component — see §§5, 7. Do not cite FLHSMV as the source for "4-hour BDI" from these pages.)
- BDI page (separate page, §4) adds ineligibility: election in preceding 12 months; five elections in a lifetime; CDL holder; cited for 30+ mph over the posted speed limit.

### 3.3 Mandatory school requirements

- Drivers with a valid Florida license convicted of these offenses (s. 322.0261, F.S., in Florida, or ss. 322.24 / 322.44 in another state) are REQUIRED to attend a basic driver improvement course: failure to obey a traffic control signal; failure to obey a steady red light; failure to stop for a school bus; racing on the highway; racing on the highway – spectator; reckless driving.
- "Drivers have 90 days from the citation date to complete the required school or the driving privilege will be canceled. The license will remain canceled until the school requirement is completed."
- Note the word is "canceled" here, not "suspended."

### 3.4 Advanced Driver Improvement (ADI)

- "Drivers must complete an Advanced Driver Improvement (ADI) course if their driver license was suspended in Florida for accumulation of points, as a habitual traffic offender (non-DUI related), or by court order."
- Point-suspension thresholds: "12 points within 12 months (30 day suspension); 18 points within 18 months (3 month suspension); or 24 points within 36 months (1 year suspension)."
- **Course hours: the ADI page as read does NOT state a number of hours.** The 12-hour figure for ADI appears only on the 3-crashes page (§7).

### 3.5 Three Crashes within Three Years

- "Requires drivers who have been convicted of, or plead nolo contendere (no contest) to a third traffic offense that caused a crash within 36 months to complete a FLHSMV approved driver improvement course."
- "This course must include behind-the-wheel training and an assessment of driving ability."
- Commercial driving schools "Provide the 4-hour behind the wheel training as part of the 3 crashes in 3 years per section 322.0261(1)(c), Florida Statutes."

### 3.6 Wireless Communications Device Course

- "If a driver receives a citation while using a wireless communications device in a handheld manner in a school or work zone, they may elect to attend a FLHSMV wireless communications device course."
- "For a first offense a driver may choose to participate in a wireless communications device safety program to avoid fines, fees and the assessment of points."
- "Drivers must provide proof of course completion and documentation to the court in the county where they received the citation."

### 3.7 Mature Driver Discount Course

- "Drivers who are 55 years of age or older can complete a Mature Driver (Senior Citizen) Discount course that is approved by FLHSMV. Upon successful completion of the course, the driver can provide the completion certificate to their insurance company for an insurance discount. The amount of the discount is at the discretion of each insurance company and will typically last for three years as long as the driver: (1) Is not involved in a crash for which the insured is cited; and (2) Is neither convicted, nor pleads guilty or nolo contendere (no contest) to a moving violation."
- Statute cited on the Mature Driver page: s. 627.0652, F.S. No course-hours figure is stated on the FLHSMV pages read.

### 3.8 Third Party Driver License Knowledge Exams

- Knowledge exams through FLHSMV-approved third-party providers; students of all ages in-person proctored; under-18 online proctored by parent/legal guardian.
- "Upon completion of a driver license exam through an approved provider, completion information is automatically submitted by the provider to FLHSMV, and this information is available at all driver license/tax collector offices."
- Random re-test: per s. 322.56(3)(b)(e), F.S., a customer who passes the learner license exam(s) through an approved provider "may be randomly selected for a no-fee, mandatory re-test without prior notice. Once a re-test with a passing score is completed in a driver license or tax collector office, the learner license will be issued. A failed mandatory re-test will require a re-exam fee be collected at the next exam attempt."
- "There is a license issuance fee for the learners license credential (card)."

## 4. Basic Driver Improvement — dedicated page

- "In order to qualify for a Basic Driver Improvement (BDI) course to eliminate the assessment of points, drivers must voluntarily elect this option within 30 days (section 318.14 (4), Florida Statutes) from the citation date and, prior to attending the course, drivers must inform the clerk of court in the county where the citation was issued of this election. Drivers must also pay an election fee to the clerk of court in the county where the citation was issued. Drivers may not elect to take the BDI, in lieu of points, after the initial 30-day period from the citation date."
  - Note: an "election fee" is named, but NO dollar amount is given anywhere on this page or any other FLHSMV page read.
- "Options for satisfying a traffic citation will be listed on the back of the citation. Drivers are required to choose one of the three options within 30 days of the citation date."
- BDI is mandatory when cited for: electing BDI instead of points; a crash in which the driver was at fault and anyone was transported to the hospital; two crashes within a two-year period with property damage greater than $500; or conviction of passing a stopped school bus, racing, highway racing – spectator, reckless driving, or running a red light.
- Benefits of electing + completing BDI: "Points may not be added to the driver license record and adjudication of guilt is withheld." Ineligibility: election in preceding 12 months; "Made five elections in a lifetime"; CDL; cited for 30+ mph over limit.
- "Civil penalty (Fine) will be reduced" (no percentage stated on this page; the 18% figure is on the Traffic Citations page, §8).
- Insurance: "Insurance companies cannot impose or request an additional premium, cancel a policy, or issue a non-renewal notice on any insurance policy or contract because of any traffic infraction when adjudication has been withheld and no points have been assessed for a traffic infraction unless the traffic infraction involved a traffic crash in which the insurer was at fault and the insurance company incurred a loss."
- Point table (if the driver pays or is adjudicated guilty instead): "Moving Violations — 3 points; Speeding 15 m.p.h or less over posted speed — 3 points; Speeding more than 15 m.p.h. over posted speeds — 4 points; Passing stopped school bus — 4 points; Moving violation (non-speeding) resulting in a crash — 4 points; Unlawful speed resulting in a crash — 6 points; Reckless driving (criminal traffic violation) — 4 points; Leaving scene of crash with damage — 6 points; Littering — 3 points; Violation of child restraint laws — 3 points."
- Point suspension restated: "12 points within 12 months, 18 points within 18 months or 24 points within 36 months" → license suspended.
- Ages 15–17: learner's license must be held at least 12 months without a traffic conviction before applying for Class E; "Any driver under the age of 18 who accumulates six or more points within a 12 month period is automatically restricted to driving for 'Business Purposes Only' for one year. If additional points are accumulated, the restriction is extended by 90 days for every additional point received."

## 5. TLSAE and DETS (first-time drivers)

### TLSAE — 4-hour course
- "Drivers who are over the age of 18 and have never held — or do not have in their possession — a driver license from any other state, country or jurisdiction, must complete a 4-hour Traffic Law and Substance Abuse Education (TLSAE) course before applying for a license in Florida."
- "DELAP courses offered by some county school boards may substitute for this requirement."
- "Drivers under 21 years of age who have received a notice of suspension for driving with a blood alcohol level (BAL) of .02 to .05 must complete a TLSAE course in order to reinstate their driver license on a hardship. A hardship license is a license restricted to 'business' or 'employment' purposes only."
- All first-time drivers must take and pass TLSAE; a successful DELAP student is exempt.

### DETS — 6-hour course (new, replaces TLSAE for minors)
- "As of August 1, 2025, individuals who are under 18 years old and have never held a driver license from any other state, country or jurisdiction must complete a 6-hour DETS course before applying for a license in Florida."
- "Driver Education Traffic Safety (DETS) is a 6-hour course, approved by FLHSMV and which meets or exceeds the Florida Department of Education (FDOE)/Traffic Safety-Classroom 1900300 course version description."
- Course may be delivered in-person or online.
- Grandfathering: does NOT affect applicants under 18 who already hold a valid out-of-state license transferring to Florida; individuals who already obtained a Florida learner's license prior to August 1, 2025; individuals under 18 who completed TLSAE prior to August 1, 2025 — "allowed to use their TLSAE course completion certificate for one-year after the completion date" (page text: "for one-year after the" — sentence truncated in the crawl). Individuals under 18 who complete TLSAE on or after August 1, 2025 must take DETS unless enrolled in FDOE Traffic Safety Classroom 1900300/1900310 or a DELAP course.
- DELAP / FDOE 1900300 and 1900310 courses may substitute.

## 6. Driver Improvement Courses FAQ (legacy page, http://www.flhsmv.gov/ddl/dicfaqa.html)

This is the page that CONTRADICTS the current pages (see §11). Its statements, verbatim as read:

- Eligible: "Any driver charged with a moving or non-moving traffic violation that would result in points assessed to their driving record." Exclusions: "All criminal violations" and "Drivers who hold a Commercial Driver License (CDL) regardless of the type of vehicle they are driving at the time of the violation."
- On completion: "Adjudication is withheld (not convicted of the violation) per section 318.14, Florida Statutes; No points will be assessed against the driver license for the violation; and Insurance companies cannot impose an additional premium or refuse to renew a policy for motor vehicle insurance solely because the insured committed a non-criminal traffic infraction" (exceptions: second infraction within 18 months; third infraction within 36 months; exceeding the speed limit by more than 15 mph).
- Fine cost: "Contact the traffic division of the clerk of court in the county where the citation was received to determine the exact cost of the civil fine." FLHSMV does not publish the fine amount.
- How to elect: "at a clerk's office in the county where the citation was received, or if the officer provided an envelope when issuing the citation drivers may use it to indicate the intent to attend a driver improvement course. Read the affidavit attached to the envelope for information and instructions."
- Cost of course: "Drivers are responsible for the cost of the driver improvement course." (No price; providers set it.)
- Proof: "It is the driver's responsibility to present the completion certificate to the clerk's office in the county where the citation was issued."
- Completion window: "Once the clerk is notified of a driver's intent to attend a course, they have between 60 and 90 days from the date of the citation to complete the course and present proof of completion to the clerk of court in the county where the citation was issued." — i.e. 60–90 days FROM THE CITATION DATE, county-specific, NOT a flat 90 days from election.
- Failure to complete: "A person who elects to attend a driver improvement course and has paid the civil fine, but fails to attend the school within the time specified by the court is considered to have admitted to the infraction and is adjudicated as guilty. In this case, the person must pay the clerk of court the amount deducted from their fee because of the election to attend a course, and a processing fee of up to $18. No additional penalties or court costs are imposed. The clerk of court will notify the DHSMV of the person's failure to attend the driver improvement course and points for the violation are then added to the individual's driving record."
- Frequency: "Drivers can choose to attend a driver improvement course once in any 12-month period and no more than eight times in a lifetime." ← THE "8" FIGURE (see §11).
- Irrevocability: "Once the affidavit is signed and recorded by the court, drivers may not choose the school option again for 12 months and all payments are forfeited."

## 7. Three Crashes in Three Years (dedicated page, via search text)

- Applies to an operator convicted of, or pleading nolo contendere to, a traffic offense giving rise to a crash under s. 322.0261(1)(c), F.S.
- Drivers at fault in three crashes within a three-year period must: "Complete 12 hours within an approved FLHSMV Advanced Driver Improvement course" + "Complete four hours of behind-the-wheel training from a FLHSMV-approved, Florida licensed commercial driving school (CDS)" + "Pass an extended road test with a driver license examiner or tax collector licensing agent."
- "Failure to complete these requirements within 90 days of the conviction will result in a license cancellation."
- "Additional crashes will result in more requirements and penalties."
- This is the ONLY FLHSMV page found that states the ADI course length (12 hours).

## 8. Traffic Citations page (FHP/traffic, via search text)

- "Customers who are issued a Uniform Traffic Citation have the option to pay the citation, contest the citation or take a driver improvement course. Customers have 30 days to make this election with the clerk of court listed on the citation. Failure to elect within 30 days may result in additional fines along with a suspension of the driving privilege."
- Option 3 (elect a driver improvement course): "Customers who receive a traffic citation may be eligible for an 18% reduction in citation fees and points may be withheld if they take a driver improvement course. After 30 days from the date of the citation, if a customer has not elected to take a driver improvement course, they are no longer eligible to elect. A customer may only elect to take a driver improvement course five times within their lifetime."
- Steps: "1. Contact the Clerk of Court. Within 30 days of receiving your traffic citation, you must contact the Clerk of the Court in the county where your citation was issued to elect to take a Basic Driver Improvement Course. 2. Pay the citation. By electing to attend the Basic Driver Improvement Course, the traffic citation fine is reduced by 18%. In addition, each Clerk of the Court imposes appropriate court cost. 3. Submit the certificate of completion. Upon completion of the Basic Driver Improvement Course, you must take the certificate of completion to the Clerk of Court where you made the election."
- Mandatory school in addition to the fine if convicted of: passing a school bus; racing; reckless driving; running a red light; traffic control device.
- Points breakdown is on the Points & Suspensions page (other section's scope).

## 9. DUI Programs

- Oversight: FLHSMV Bureau of Motorist Compliance; authority Ch. 15A-10, F.A.C. (certify instructors, investigate complaints, evaluate effectiveness).
- "DUI programs are non-profit organizations required to provide drug and alcohol education to DUI offenders to satisfy judicial and driver licensing requirements." They provide "education, psycho-social evaluation and treatment referral services."
- Level I (first-time offenders): "a minimum of 12 hours of classroom instruction incorporating informative and interactive educational techniques."
- Level II (multiple offenses): "a minimum of 21 hours of classroom time using primarily interactive educational techniques in a group setting. The average class size may not exceed 15 students for Level II." "Treatment from a Department of Children and Families (DCF)-licensed treatment provider is often used in conjunction with the Level II DUI class."
- Standardized fees (as of October 1, 2023): Level I registration $330 (includes $5 Driver Risk Inventory-DRI); Level II registration $495 (includes $5 DRI). Reassignments: Level I 1st within 90 days $40, 2nd $75, 3rd $153, any reassignment more than 90 days after enrollment $275, reassignment for coming under the influence $275; Level II 1st within 90 days $60, 2nd $120, 3rd $238, more than 90 days after enrollment $420, under the influence $420. Evaluation reassignment 1st within 90 days $75, 2nd $153; Evaluation Only $75; out-of-state evaluation $150; DRI $5; Reinstatement Review Inventory-RRI $5; Special Supervision Services application $332 (includes $25 eligibility screening + $15 State Assessment Fee + $40 urinalysis + $5 DRI); periodic update $55 ($65 with ignition interlock review); reschedule $55; FDLE background check $25; annual state assessment $15; blood test for alcohol $30; IID 1st violation appointment $25, 2nd violation appointment + case management $55, 2nd/subsequent monthly appointment $45, 3rd/subsequent appointment + treatment referral $55, rescheduling $25, treatment referral DRI re-test $5; transfer fee $25; copy fee $10; bad checks $30; administrative refund fee $25; referral to different treatment agency $15; treatment verification form $10. Driving-record fees: Florida TML $15, MVR $16, FDLE $25, out-of-state cost + $1.
- Note: the DUI pages still carry a "Due to COVID-19, services and hours may be impacted" notice.

## 10. DELAP

- "The Driver Education Licensing Assistance Program (DELAP) allows high school driver education programs to provide Class E driver license exam services to minors enrolled in these classes."
- Only DOE-approved driver education courses may participate: instructional personnel must be DOE-certified teachers with a Driver Education endorsement; school must be in a public or private secondary education program; courses must follow the DOE curriculum framework and student performance standards approved by the local school board's pupil progression plan.
- Curriculum frameworks: Driver Education/Traffic Safety—Classroom 1900300; Driver Education/Traffic Safety—Classroom and Laboratory 1900310.
- "Students who complete their driver license exams through approved DELAP courses in public or private schools will have their results entered into the FLHSMV's records systematically or by their driver education teacher. Exam results will be used for the issuance of a learner's or Class E driver license. However, the FLHSMV or tax collector licensing agent may test any student on a random basis before issuing a driver license."
- DELAP completions include the TLSAE curriculum requirement; DELAP is a substitute for TLSAE (and, since Aug 1, 2025, for DETS for under-18s).
- Approved DELAP administrators list is county-by-county (high schools); FLHSMV contact 850-617-3682.

## 11. Motorcycle Rider Education & Endorsements

- Endorsement required to operate any two- or three-wheel motorcycle with engine over 50 cc; "anyone driving a motorcycle without an endorsement is violating the law." No one under 16 may legally operate motorcycles, mopeds, motor-driven cycles, motorized scooters or electric helper-motor bicycles on Florida roads.
- "New motorcyclists must take and pass the Basic RiderCourse (BRC) or Basic RiderCourse updated (BRCu) through a FRTP authorized Sponsor before they can have the motorcycle endorsement added to their license, per section 322.12(5)(a), Florida Statutes."
- "Upon completing the Basic RiderCourse (BRC), Basic RiderCourse updated (BRCu), 3-Wheel Basic RiderCourse (3WBRC) or the Sidecar/Trike Education Program (S/TEP) for endorsement, the Sponsor will submit your results electronically to the Department." An endorsement fee is required to add the endorsement.
- Endorsement deadline: "After successfully passing the RiderCourse, you must obtain your endorsement within (1) year. If the endorsement has not been obtained during the one (1) year grace period, the course completion card as well as the 'PASS' waiver status is considered invalid and you must complete another RiderCourse before the endorsement can be added."
- Steps to obtain endorsement: hold at least a valid Class E operator's license; complete BRC/BRCu with an authorized Sponsor; visit a driver license or tax collector office, provide proper ID, pay required endorsement fees.
- Motorcycle Only license: at least 16; if under 18, hold a Learner's License for one year with no traffic convictions; pass the same knowledge test as Class E; complete BRC/BRCu; license restricted to "Motorcycles Only."
- BRC enrollment minimum: at least 16 years old and hold at least a Learner's Driver License; basic knowledge of traffic laws, road signs, general road rules.
- 3WBRC: three-wheel, two-track vehicle only; endorsement shows "S" Restriction; minimum 16 + Learner's License; bring own 3-wheel motorcycle or written permission, proof of liability insurance, own helmet and protective gear.
- S/TEP: limits rider to motorcycles with more than two wheels or attached sidecar ("S" endorsement/restriction); Learner's License required; own motorcycle/permission, helmet/gear, liability insurance proof.
- Fees (Motorcycle FAQ + Fees page): "The costs include the $7.00 endorsement fee, plus a license fee (see fees for original, renewals, duplicates, and replacement license), and $6.25 if applying at a county tax collector office. In addition to these costs, you will need to pay the course provider for the required motorcycle safety course." Endorsement, once added, "is good for life."
- Reciprocity: out-of-state motorcycle endorsements reciprocated EXCEPT Alabama — Alabama licenses with a motorcycle endorsement are reciprocated only if an MSF BRC completion card is presented. Out-of-state/military BRC, 3WBRC, S/TEP completion cards accepted if not more than one (1) year old.
- Other courses (FAQ): Basic Bike Bonding RiderCourse (BBBRC) — "a five to six hour course"; BRC2 — "a one-day course" for experienced endorsed riders; Advanced RiderCourse (ARC) — "a one day advanced course"; Returning Rider BRC (RRBRC) — refresher for returning riders; Ultimate Bike Bonding RiderCourse (UBBRC) — "a partial day course" of police-style precision riding.
- Mopeds/scooters 50cc or less: no motorcycle endorsement needed, but operator must be at least 16 and hold at least a regular Class E or Motorcycle Only license.

## 12. Third Party Administrators (TPA)

- ADLTS (Automated Driver License Testing System), vendor Solutions Thru Software: "produces a timed, 60 minute, 50-question test which is created within the system by randomly selecting questions from the ADLTS question bank consisting of approximately 800 different questions. The exam is administered to the student via computer. ADLTS stores and scores the test and provides results directly to FLHSMV."
- TPAs can also administer the Class E Driving Skills Exam via a computer tablet (required); "The tablet automatically scores the exam upon completion and provides results directly to FLHSMV." "ADLTS provides real-time test results."
- Authority: Chapter 322.56, F.S.; Rule 15A-1, F.A.C. Assistance: 850-617-2421, TPA-assistance@flhsmv.gov.
- To become a TPA (search-text summary): application for authority; business model summary; contract; certificate of incorporation/fictitious name; commercial general liability insurance ($1,000,000 each occurrence / $2,000,000 aggregate, with 30-day cancellation notice to FLHSMV); automobile liability if company vehicles used ($10,000 PIP / $20,000 PDL / $10,000 BIL); workers' comp if more than one employee; performance bond $200,000 per service; hold-harmless endorsement; employees must hold a valid Class E license with no cancellations/suspensions/revocations for at least 3 years prior and no more than three chargeable crashes or Ch. 316 violations in any consecutive 3-year period.

## 13. Commercial Driving Schools & Course Providers

- "Commercial Driving Schools and Driver Improvement Courses provide education about driving skills, traffic laws, road safety or substance abuse. Commercial Driving Schools teach behind-the-wheel skills for drivers of non-commercial vehicles such as cars, small trucks, SUV's and vans to prepare drivers to take the Class E skills test. Driver improvement course providers teach programs that allow an individual to retain their driving privilege, earn a license for the first time or obtain an insurance discount."
- ADI = course for point suspension or non-DUI Habitual Traffic Offender; BDI = course for clerk election in lieu of points or mandatory attendance; TLSAE = never-licensed drivers; Senior Citizen Discount Insurance (SCDI) = over 55.
- To open a behind-the-wheel school: licensed under Chapter 488, F.S.; school license + certified instructor required. Application: $250 payment ($200 license fee + $50 non-refundable application fee). Instructor: 32-hour Driving Instructor Training Course (DITC) for new instructors, 8-hour DITC refresher for certified instructors, or DPAS for temporary certification; instructor application fee $25 non-refundable; no suspensions/revocations/cancellations/disqualifications for 3 years prior to application.
- "There are no independent traffic schools in Florida; a school must have a contract with a driver improvement course provider that has been approved by FLHSMV." Two options: contract with an approved provider, or develop a course for FLHSMV approval.
- To become a course provider: course must be approved by FLHSMV before use in Florida; provider is the legal entity owning the copyright. Classes: ADI s. 322.291, BDI s. 318.1451, TLSAE s. 322.095, SCDI s. 627.0652. "According to section 120.60(1), F.S., FLHSMV has 90 days to review and respond to the completed submission upon receipt." Contact Driver-Education@flhsmv.gov.

## 14. Fees relevant to education courses (from FLHSMV Fees page)

- Endorsements: $7.00. (This is the motorcycle endorsement fee — see §11. It is NOT a traffic-school election fee.)
- D-6 Suspension – DHSMV: $60.00.
- Suspensions (general): $45.00; Revocations: $75.00; Disqualification: $75.00; Administrative fee for alcohol/drug-related offenses: $130.00.
- Knowledge retest $10.00; Skill retest $20.00; Original Class E (includes Learner's) $48.00; Renewal Class E $48.00; Replacement license $25.00; Late fee $15.00; DUI program fee (assessed by the program) $15.00; Interlock fee (assessed by vendor) $12.00.
- Additional $6.25 service fee may apply to any credential issued in a tax collector office.
- Driver history records: 3-year $8.00; 7-year, complete or certified $10.00.
- NO traffic-school election fee and NO per-violation citation fine amount appears on the FLHSMV Fees page. FLHSMV repeatedly directs drivers to the clerk of court for the exact civil fine.

## 15. D6 suspensions and driving-record retention (from Questions About Driving Records + sanctions help pages)

- "D-6 suspensions (failure to comply) once cleared, remain on the record 1 year from the reinstatement date and are then converted to a correspondence entry for 2 more years. Once this D6 entry converts to a correspondence entry it does not appear on 3- or 7-year driver records (transcripts)." On a complete record the correspondence entry DOES appear.
- "Citation dispositions of adjudication withheld clerk of court (called school elections) are retained for 75 years with only allowed up to 5 in a lifetime) and for compliances, 75 years (only allowed up to 3 in a lifetime). See sections 318.14(9) and (10), Florida Statutes."
- Adjudication withheld (clerk of court) = "the person made election to complete a driver improvement school in lieu of receiving points and completed the course or person elected to enter a plea of nolo contendere and provide proof of compliance."
- Correspondence entry also exists for "adjudication withheld-clerk of court (the person made school election when not eligible or made the election but did not complete the course)."
- Court-suspension help pages: failure to pay a fine → license "suspended indefinitely"; failure to comply with / appear at a traffic summons → "suspended indefinitely"; failure to complete a court-ordered driver improvement school, or school election made but driver did not attend / was not eligible → "suspended indefinitely." Clearing requires satisfying the court, the county updating FLHSMV electronically, then paying a reinstatement fee if applicable (D6 reinstatement $60.00 per §14; DLCheck help page: "$60.00 reinstatement fee is required" for failure to pay traffic tickets). D-6 clearance form with stamped court seal is acceptable documentation; allow 48 hours after payment for the court update, 3–5 days after faxing a clearance form.

## 16. Traffic School Completion Check

- Purpose: "verify that a Driver School Course has been taken."
- Search by driver license number, certificate number, citation number, or court order number (driver improvement — basic, advanced, traffic collision avoidance); or by date of birth + last four of SSN / alien registration number / other identifying number (first-time driver / TLSAE).
- The tool itself was not opened successfully (HTTP 429 rate-limit on two attempts); facts above are from the search-indexed copy of the services.flhsmv.gov page.

## 17. FLAG — contradictions with Muse3's claims about Git-FED's OTR case

Git-FED's ticket (per task brief): Oct 24, 2026, failure to dim headlights, Fla. Stat. 316.238, moving violation, 3 points, $60 base fine. Muse3's claims checked below. Election deadline on that citation date would be Nov 23, 2026 (30 days from Oct 24).

### FLAG 1 — LIFETIME LIMIT: 8 vs 5 — CONFIRMED CONTRADICTION, INSIDE FLHSMV ITSELF
Muse3 claimed: lifetime limit 8 per Fla. Stat. 318.14(9).
FLHSMV current pages say FIVE:
- Driver Improvement Schools page: "once every 12 months or a total of five times within their lifetime."
- BDI page (direct open, crawled 2025-01-30): ineligibility includes "Made five elections in a lifetime."
- Traffic Citations page: "A customer may only elect to take a driver improvement course five times within their lifetime."
- Questions About Driving Records: "Effective July 1, 2024, Florida Statute 318.14(9), provides that a person may make no more than five traffic school elections within their lifetime and once in a twelve-month period." AND the retention note: school-election adjudications withheld "are retained for 75 years with only allowed up to 5 in a lifetime."
FLHSMV pages saying EIGHT:
- Driver Improvement Courses FAQ (legacy dicfaqa.html, crawled 2026-01-05): "Drivers can choose to attend a driver improvement course once in any 12-month period and no more than eight times in a lifetime."
- The search-indexed copy of the BDI page (322-day-old crawl) says "Made eight elections in a lifetime" — while the direct open of the SAME BDI URL (2025-01-30 crawl) says five. The page was evidently updated from 8 to 5 and the search index still holds the old text.
- A third, older variant also exists in the search index: "one time within a 12-month period and no more than five times within a 10-year period" (general FAQ).
Verdict: Muse3's "8" matches FLHSMV's stale legacy FAQ and the old cached BDI text, but CONTRADICTS the current Driver Improvement Schools page, the current BDI page, the Traffic Citations page, and the Driving Records FAQ — which expressly attributes the FIVE limit to s. 318.14(9) effective July 1, 2024. The current FLHSMV position is 5, not 8. The clerk of court in the county of citation is the authority that will enforce whichever limit; Git-FED must not rely on 8.

### FLAG 2 — "$7 FEE" — NOT VERIFIABLE ON ANY FLHSMV PAGE; LIKELY A CLERK FEE, AND $7.00 ON FLHSMV IS SOMETHING ELSE
Muse3 claimed: affidavit + payment + $7 fee.
- FLHSMV BDI page says only: "Drivers must also pay an election fee to the clerk of court" — NO amount stated anywhere on any FLHSMV page read.
- FLHSMV FAQ says only: "Contact the traffic division of the clerk of court … to determine the exact cost of the civil fine" and "Drivers are responsible for the cost of the driver improvement course."
- The ONLY "$7.00" on FLHSMV in this study is the MOTORCYCLE ENDORSEMENT fee (Fees page: "Endorsements $7.00"; Motorcycle FAQ: "The costs include the $7.00 endorsement fee…"). That is a different fee for a different thing.
- Non-FLHSMV corroboration (county clerks, for context only — NOT FLHSMV): Charlotte County Clerk: "additional $7.00 School election fee"; Okaloosa County Clerk: "an additional $7.00 affidavit fee"; Broward: "$7.00 driving school affidavit fee." So a $7 election/affidavit fee is real at several clerks, but it is a COUNTY clerk fee, varies by county, and is NOT stated on flhsmv.gov. Muse3's claim is plausible but unsourced on FLHSMV and risks conflation with the $7 motorcycle endorsement fee.

### FLAG 3 — "COMPLETION WITHIN 90 DAYS OF ELECTION" — FLHSMV SAYS 60–90 DAYS FROM THE CITATION DATE, COURT-SET
Muse3 claimed: completion within 90 days of election.
- FLHSMV Driver Improvement Schools page: "Drivers must complete the traffic school course within the court-required time period." No fixed number.
- FLHSMV FAQ: "they have between 60 and 90 days from the date of the citation to complete the course and present proof of completion to the clerk of court" — measured FROM THE CITATION DATE, and the exact number within 60–90 is set by the county ("Please consult with the traffic division in the clerk's office in the county where the citation was issued for their exact requirements").
- Non-FLHSMV context: Okaloosa County Clerk gives 90 days from election/payment; Charlotte County gives 60 days from payment date. Both differ from "90 days of election" as a universal rule.
- Verdict: "90 days from election" is NOT an FLHSMV rule. On FLHSMV's own text the window is court-set, 60–90 days from citation. For an Oct 24, 2026 citation that means completion/proof due sometime between Dec 23, 2026 (60 days) and Jan 22, 2027 (90 days) — the clerk sets the exact date.

### FLAG 4 — 30-DAY ELECTION — CONFIRMED
Muse3 claimed: election within 30 days of the citation. CONFIRMED on four FLHSMV pages: hub page; Driver Improvement Schools ("within 30 days of the traffic citation… right to elect school is forfeited and points are assessed"); BDI page ("within 30 days (section 318.14 (4), Florida Statutes) from the citation date… may not elect… after the initial 30-day period"); Traffic Citations ("Customers have 30 days to make this election… After 30 days… no longer eligible to elect"). For the Oct 24, 2026 citation: deadline Nov 23, 2026.

### FLAG 5 — ONCE IN 12 MONTHS — CONFIRMED
Muse3 claimed: once in 12 months. CONFIRMED everywhere, including the legacy FAQ ("once in any 12-month period") and the Driving Records FAQ ("once in a twelve-month period"). Also: "Once the affidavit is signed and recorded by the court, drivers may not choose the school option again for 12 months and all payments are forfeited."

### FLAG 6 — D6 SUSPENSION TIMING — PARTLY CONFIRMED, NO FLHSMV DAY-COUNT FOUND
- Confirmed: failure to pay the fine/fees within 30 days → "their license will be suspended for failure to pay" (Driver Improvement Schools page); failure to complete within the court-required time → "license will be suspended for failing to attend course"; court-suspension pages: failure to pay / failure to comply / failure to complete school → license "suspended indefinitely."
- NOT found on any FLHSMV page read: a specific number of days after the deadline before the D6 posts, or a D6 effective-date rule. D6 timing is driven by the clerk of court notifying FLHSMV. Reinstatement after a D6: $60.00 (Fees page: "D-6 Suspension – DHSMV $60.00"; DLCheck help: "$60.00 reinstatement fee is required" for failure to pay traffic tickets).
- D6 record retention (Driving Records FAQ): once cleared, a D-6 stays on the record 1 year from reinstatement, then converts to a correspondence entry for 2 more years; it then does not appear on 3- or 7-year records but DOES appear on a complete record.

### FLAG 7 — FINES: 18% REDUCTION CONFIRMED; $60 BASE FINE AND 316.238 NOT FOUND ON FLHSMV
- Confirmed: electing BDI reduces the citation fine by 18% (Traffic Citations page, twice: "eligible for an 18% reduction in citation fees" / "the traffic citation fine is reduced by 18%. In addition, each Clerk of the Court imposes appropriate court cost"). Failure to complete: repay the deducted amount + a processing fee of up to $18, adjudicated guilty, points added.
- NOT found: no FLHSMV page in this section lists a $60 base fine for failure to dim headlights, or any per-violation fine schedule. FLHSMV defers all fine amounts to the clerk of court. A site search for "316.238" on flhsmv.gov returned NO results. The "$60" figure that DOES appear on FLHSMV is the D-6 reinstatement fee ($60.00), not a citation fine — do not confuse the two.
- 3 points: CONSISTENT but generic — BDI point table: "Moving Violations — 3 points." No FLHSMV page found ties 3 points specifically to s. 316.238 failure to dim.

### FLAG 8 — AFFIDAVIT — CONFIRMED IN FORM, NOT IN FLHSMV DETAIL
- FLHSMV FAQ: elect at the clerk's office, "or if the officer provided an envelope when issuing the citation drivers may use it to indicate the intent to attend a driver improvement course. Read the affidavit attached to the envelope for information and instructions." So an affidavit/envelope mechanism exists, but FLHSMV gives no affidavit form, no filing detail, and no fee — all of that is the clerk's.

### FLAG 9 — COURSE HOURS FOR BDI/ADI — FLHSMV PAGES DO NOT STATE THEM
- BDI page: no hours stated. ADI page: no hours stated. The hours FLHSMV DOES state: TLSAE 4 hours; DETS 6 hours; DUI Level I minimum 12 hours, Level II minimum 21 hours; 3-crashes ADI 12 hours + 4 hours behind-the-wheel; ADLTS knowledge exam 60 minutes / 50 questions; motorcycle BBBRC 5–6 hours, BRC2 one day, ARC one day, UBBRC partial day. Any claim that BDI is a "4-hour course" or ADI a "12-hour course" as a general rule is not sourced from the FLHSMV BDI/ADI pages themselves (the 12-hour ADI figure is sourced only from the 3-crashes context).

## 18. Gaps and limitations of this section

- Two browser.open attempts failed with HTTP 429 (Traffic School Completion Check; Traffic Citations page) and were not retried per instruction; those pages are covered from search-indexed text only (§1B).
- Commercial Driving Schools Overview, 3-Crashes page, Mature Driver Discount page, DELAP providers list, and Wireless Communications Device Course dedicated page were covered from search text, not full opens.
- FLHSMV crawl dates on several pages are months old (e.g. BDI page crawl 2025-01-30; legacy FAQ crawl 2026-01-05). The 5-vs-8 discrepancy may reflect a site update that propagated unevenly; the Driving Records FAQ is the only page that dates the change ("Effective July 1, 2024").
- No FLHSMV page in this section was found for: s. 316.238, failure-to-dim fines/points, or a traffic-school election fee amount.
# FLHSMV Study — Section 02: Driver Licenses & ID Cards — General

Study date: 2026-11-23. Source: flhsmv.gov only (facts below are from FLHSMV pages as
retrieved; see Method note). No non-FLHSMV source is used for a fact except where
explicitly labelled "task brief" or "third-party summary, not FLHSMV".

## Method note — read this first

- Directly opened and read in full via browser.open:
  - https://www.flhsmv.gov/driver-licenses-id-cards/
  - https://www.flhsmv.gov/driver-licenses-id-cards/general-information
- A parallel batch of four further browser.open calls (Renew or Replace, REAL ID,
  Fees, What-to-Bring FAQ) then failed with upstream HTTP 429 (rate limit) after
  3 attempts each, and per instruction those exact opens were NOT retried. Facts
  for those four pages below therefore come from the search engine's indexed
  extracts of the same flhsmv.gov pages (verbatim snippets returned by
  browser.search), not from a fresh full-page open. They are labelled
  "[search extract]" in the page list. Crawl dates shown are the search tool's
  "Last Crawl" dates, not a fresh verification.
- Subpages for teen drivers, driver improvement / traffic school, locations,
  ID cards / designations, and the new credential were likewise covered via
  search extracts of flhsmv.gov pages (same caveat). No FLHSMV fact below is
  invented; where a page was only seen as an extract, that is stated.
- Pages on suspensions/revocations, medical review, mature driver, CDL detail
  and commercial handbooks are linked from the hub but are OUT of this
  section's core scope except where noted; they belong to companion sections.

## Page list — every URL studied

| # | Page | URL | How read | Crawl / update note |
|---|---|---|---|---|
| 1 | Driver Licenses & ID Cards (hub) | https://www.flhsmv.gov/driver-licenses-id-cards/ | browser.open, full (85 lines) | Crawled 2026-10-29 |
| 2 | General Information | https://www.flhsmv.gov/driver-licenses-id-cards/general-information | browser.open, full (237 lines) | Crawled 2025-12-09 |
| 3 | Renew or Replace Your Florida Driver License or ID Card | https://www.flhsmv.gov/driver-licenses-id-cards/renew-or-replace-your-florida-driver-license-or-id-card/ | search extract [browser.open 429-blocked] | Last crawl 319 days before 2026-11-23 search; page "last updated 991 days ago" per search |
| 4 | REAL ID | https://www.flhsmv.gov/driver-licenses-id-cards/real-id/ | search extract [browser.open 429-blocked] | Last crawl 26 days before 2026-11-23 search; updated 55 days ago |
| 5 | Fees | https://www.flhsmv.gov/safety-center/driver-licenses/fees/ (also https://www.flhsmv.gov/fees/) | search extract [browser.open 429-blocked] | Last crawl 28–341 days before searches; "last updated 1858 days ago" per search |
| 6 | What to Bring (hub) | http://www.flhsmv.gov/driver-licenses-id-cards/what-to-bring | search extract | Last crawl 357 days before search |
| 7 | What to Bring — Frequently Asked Questions | https://www.flhsmv.gov/driver-licenses-id-cards/what-to-bring/frequently-asked-questions/ | search extract [browser.open 429-blocked] | Last crawl 350 days before search |
| 8 | What to Bring — Immigrant | https://www.flhsmv.gov/driver-licenses-id-cards/what-to-bring/immigrant | search extract | Last crawl 353 days before search |
| 9 | What to Bring — Canadian | https://www.flhsmv.gov/driver-licenses-id-cards/what-to-bring/canadian/ | search extract | Last crawl 10 days before search |
| 10 | Licensing Requirements for Teens / GDL Laws / Driving Curfews | https://www.flhsmv.gov/driver-licenses-id-cards/licensing-requirements-teens-graduated-driver-license-laws-driving-curfews | search extract | Last crawl 312 days before search |
| 11 | Traffic Laws for Florida Teens | https://www.flhsmv.gov/driver-licenses-id-cards/licensing-requirements-teens-graduated-driver-license-laws-driving-curfews/traffic-laws-florida-teens/ | search extract | Last crawl 35 days before search |
| 12 | Driver Improvement Schools | http://flhsmv.gov/driver-licenses-id-cards/education-courses/driver-improvement-schools/ | search extract | Last crawl 243 days before search |
| 13 | Basic Driver Improvement (BDI) — what it is / approved providers | https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/driver-improvement-schools/basic-driver-improvement-bdi-find-approved-listing-bdi-course-providers/ | search extract | Last crawl 322 days before search |
| 14 | Driver Improvement Courses FAQ | http://www.flhsmv.gov/ddl/dicfaqa.html | search extract | Last crawl 322 days before search |
| 15 | Traffic Citations | http://www.flhsmv.gov/FHP/traffic/ | search extract | Last crawl 314 days before search |
| 16 | Education & Courses | https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/ | search extract | Last crawl 25 days before search |
| 17 | Florida's NEW Driver License and ID Card | https://www.flhsmv.gov/driver-licenses-id-cards/newdl/ | search extract | Last crawl 21 days before search; updated 32 days ago |
| 18 | Designation Fees & Required Documentation | https://www.flhsmv.gov/driver-licenses-id-cards/newdl/designation-fees/ | search extract (URL as returned, trailing ")" in one result is a search artefact) | Last crawl 322 days before search |
| 19 | New Resident — Welcome to Florida! | https://www.flhsmv.gov/new-resident/ | search extract | Last crawl 11 days before search |
| 20 | Locations — Broward County (representative county page) | https://www.flhsmv.gov/locations/broward/ | search extract | Last crawl 7 days before search |
| 21 | Locations — Indian River County | https://www.flhsmv.gov/locations/indian-river/ | search extract | Last crawl 13 days before search |
| 22 | Locations — Alachua County | https://www.flhsmv.gov/locations/alachua | search extract | Last crawl 347 days before search |
| 23 | Locations — Putnam County | http://www.flhsmv.gov/offices/putnam.html | search extract | Last crawl 351 days before search |
| 24 | Renew/replace legacy URL (redirect target cited in search) | https://www.flhsmv.gov/ddl/replace.html | search extract only (URL from search results) | — |

Hub-linked pages NOT opened in this section (named on the hub, for companion
sections / follow-up): Driver License Check, Suspensions & Revocations, Medical
Review, Mature Driver. Their hub summaries are recorded in §1 below.

## 1. Hub overview — Driver Licenses & ID Cards

From https://www.flhsmv.gov/driver-licenses-id-cards/ (full read):

- **Driver License Check:** "can be used to review the status of certain items
  connected to your driver license (e.g. driver status and driver improvement
  school eligibility) or to update your social security number or insurance
  information. Parents may also access the driving history of their child with
  this system."
- **General Information:** "The Division of Motorist Services has driver license
  service centers located throughout the state. Depending on your location the
  office may offer services on a walk-in or appointment only basis. Drivers may
  also be eligible to renew or replace a driver license online at MyDMV Portal."
- **Renew or Replace Your License:** "Customers must renew their Florida driver
  license or ID card every eight years. The expiration date is listed on the
  credential. Florida driver license and ID card holders may renew their
  credential up to 18 months in advance of the expiration date."
  (See §5 for the conflicting 12-month ID-card figure on the Renew page itself.)
- **Suspensions & Revocations:** covers reinstatement after suspension/revocation
  for unpaid traffic tickets, failure to comply or appear at a traffic summons,
  failure to complete a court-ordered driver improvement course, inadequate
  vision, habitual traffic offender status, delinquent child support, and more.
- **Medical Review:** concerned-citizen reporting of a family member/friend whose
  medical condition may make them unsafe; mission "is not to prevent an
  individual with a medical condition from driving, but to assure the condition
  does not interfere with the safe operation of a motor vehicle."
- **Federal Real ID Act:** "became effective nationwide on May 11, 2008. Florida
  began issuing REAL ID compliant credentials after January 1, 2010. Because
  Florida is a REAL ID compliant state, Florida driver licenses and ID cards are
  accepted nationwide as official identification for domestic air travel and
  access to military bases and most Federal facilities."
- **Teen Drivers:** Graduated Driver Licensing (GDL) laws "outline limits and
  restrictions for new drivers, ages 15, 16 and 17."
- **Mature Driver:** "an education and awareness campaign designed to educate the
  public about the effects of age on driving ability."
- **New Driver License & ID Card:** "Starting in August 2017, the Florida
  Department of Highway Safety and Motor Vehicles will begin issuing a new, more
  secure Florida driver license and ID card."

## 2. General information — tests

From General Information (full read):

- Tests "are given at driver license service centers and may or may not be
  required for the driver license or ID card you seek."
- **Hearing:** drivers who are deaf or cannot hear conversation in a normal tone
  are "restricted to driving with an outside rearview mirror which should be
  mounted on the left side of the vehicle, or wearing of a hearing aid."
- **Vision:** "Vision testing, using an eye machine located on the counter, is
  conducted in all driver license service centers. Individuals with visual
  acuity readings below 20/40 are referred to an eye specialist. Color
  blindness will not cause any special condition for licensing."
- **Knowledge Exam:** "50 multiple choice questions about traffic laws and
  traffic signs. To prepare, review the Florida Driver License Handbook. Class E
  knowledge examinations are available in Arabic, Chinese, English, Haitian
  Creole, Russian and Spanish."
- **Driving Test (Class E Skills Exam):** "You must provide a vehicle for the
  skills exam. The vehicle must have a valid tag, proof of insurance and pass a
  vehicle inspection. During the skills exams, the examiner/agent will observe
  your ability to control the vehicle and how well you obey traffic laws."
- **Photo requirements:** Fla. Stat. §322.142(1) requires a full facial photo /
  digital image; 6 CFR §37.17 REAL ID photo standards apply (even lighting,
  face crown-to-chin and ear-to-ear visible and shadow-free, no veil/scarf/
  headdress obscuring features, no eyewear obstructing iris/pupil, no dark
  eye-socket shadows where avoidable, no "hot spots").
- Handbooks (driver license, motorcycle, CDL) are available free at service
  centers and may be returned for re-use; digital copies on the Handbooks and
  Manuals page.
- CDL applicants: "the commercial driver license is a professional license with
  more testing requirements than other licenses" — obtain a study manual before
  testing.
- **International Driving Permit:** accepted in over 150 countries, translates a
  US license into 10 foreign languages, valid up to one year from issue, must be
  accompanied by a valid US driver license at all times; AAA was selected for
  authorisation.
- Statutes cited on the page: §§322.54, 322.57 (classes/endorsements); §§322.12,
  322.221 (examinations); §322.16 (restrictions); §322.051 (ID cards); §322.095(1)
  (name/ID requirements; also TLSAE course requirement); §322.08 (SSN);
  §§322.21, 322.17, 322.051 (fees); §322.03(1)(B) (surrender / valid-in-Florida
  only); §322.13 (examiner / re-examination); §§322.32, 322.33, 322.212 (false
  application / suspension); §316.614(4) (seat belts); §320.02 (registration).

## 3. License classes, learner's license, endorsements

From General Information (full read):

### Class E — minimum age 16
- "Any non-commercial motor vehicles with Gross Vehicle Weight Rating less than
  26,001 pounds, including passenger cars, 15-passenger vans including the
  driver, trucks or recreational vehicles and two or three-wheel motor vehicles
  50 cc or less, such as mopeds or small scooters."
- Farmers and drivers of authorised emergency vehicles exempt from CDL must
  obtain a Class E license.
- Exam requirements: road rules, road signs, driving, vision, hearing.
- New resident exchanging a valid out-of-state license: vision and hearing tests
  only.
- Under 18 and unmarried: application must be signed by a parent or legal
  guardian; step-parents may not sign unless they have legally adopted the
  applicant.
- Teens for Class E must: hold learner's license for 12 months; incur no traffic
  convictions; be certified by a parent/guardian for at least 50 hours
  behind-the-wheel training, at least 10 hours at night.
- "Teens issued a traffic citation can elect to attend a traffic driving school
  to avoid a conviction."

### Learner's License — minimum age 15
- Any Class E vehicle driven by a person 15, or persons learning to drive.
- Exams: road rules, road signs, vision, hearing. Same parental-signature rule
  as Class E (under 18, unmarried; step-parent only if legally adopted).

### Motorcycle endorsement — minimum age 16
- All first-time customers adding a motorcycle endorsement must complete a
  department-approved Motorcycle Safety Education Course.
- FAQ [search extract]: new motorcyclists must take and pass the Basic RiderCourse
  (BRC) or BRC updated (BRCu) through an FRTP-authorized sponsor before the
  endorsement can be added, per §322.12(5)(a); after passing, obtain the
  endorsement within 1 year by visiting a driver license / tax collector office,
  with proper ID and endorsement fees.
- Moped: no motorcycle endorsement required for Class E or higher; passengers
  under 16 must wear approved protective headgear; a moped tag is required; PIP
  insurance is not required.
- Scooters 50 cc or less: must be street legal (brake lights, headlight, mirror
  per Ch. 316, tag/title/registration) and operated by a person with Class E or
  higher.
- On the credential: motorcycle endorsements are not spelled out on the front;
  "motorcycle-also" and "motorcycle-only" are shown as "A" or "O" in the
  endorsement field on the front, and as "A-MTRCL Also" / "O-MTRCL Only" on the
  back (New DL page).

### Class A (CDL) — minimum age 18
- Commercial motor vehicles — trucks or truck combinations with GVWR 26,001 lbs
  or more, provided the towed vehicle is more than 10,000 lbs.
- Exams: general knowledge, combination vehicle, air brakes, applicable
  endorsement exams, vision 20/40 in each eye, hearing (must hear a whisper),
  pre-trip, basic skills, driving.
- Drivers under 21: restricted to intrastate operation only.

### Class B (CDL)
- Straight trucks with GVWR 26,001 lbs or more.
- Exams: general knowledge, air brakes if applicable, vision 20/40 in each eye,
  hearing (must hear a whisper), pre-trip, basic skills, driving. Under 21:
  intrastate only. (Note: the page's Class B/C exam lists confusingly add
  "(not required for Class C)" to pre-trip/basic skills — recorded verbatim.)

### Class C (CDL)
- Vehicles transporting placardable amounts of hazardous materials, or vehicles
  designed to transport more than 15 persons including the driver with GVWR
  under 26,001 lbs.
- Exams: as Class B (general knowledge, air brakes if applicable, vision 20/40
  each eye, hearing a whisper, pre-trip, basic skills, driving). Under 21:
  intrastate only.

### Teen / GDL detail (Teen pages, search extracts)
- Learner's license requirements: at least 15; signed/notarized Parental Consent
  Form if under 18 (step-parents may not sign unless legally adopted); proof of
  Driver Education Traffic Safety (DETS) course completion; pass vision and
  hearing tests; pass Class E Knowledge Exam — 50 multiple-choice questions,
  passing score 80% (40 of 50); provide identity / SSN / residential-address
  documents.
- Class E (teens): at least 16; hold learner's license at least 12 months or
  until 18, whichever first; parent/guardian/responsible adult 21+ certifies 50
  hours' driving, 10 at night (Certification of Minor Driving Experience Form);
  no moving violation convictions for one year from learner's issuance (or one
  moving violation with adjudication withheld); pass Class E Driving Skills Test.
- Curfews: learner's — daylight hours for first 3 months, until 10 p.m. after
  3 months, always accompanied by a licensed driver 21+; age 16 license — 6 a.m.
  to 11 p.m. unless to/from work or accompanied by a licensed driver 21+; age 17
  license — 5 a.m. to 1 a.m. on the same exception.
- Moving conviction while on a learner's license extends the 1-year hold by one
  year from the conviction date or until age 18, whichever first (§322.161).
  School-attendance non-compliance can suspend the privilege (§322.091).
  Zero tolerance under 21: BAC .02%+ = immediate 6-month suspension, 1 year on
  second offense; refusal = 12 months first, 18 months second (§322.2616).
  6+ points in 12 months for a minor = automatic "Business Purposes Only"
  restriction for 12 months or until 18, extended 90 days per additional point.
  Parent/guardian who signed consent can rescind and cancel the license
  (§322.10). Tobacco/nicotine possession conviction: learner's revoked minimum
  30 days (§322.056).

### New residents
- Must obtain a valid Florida driver license within 30 days of establishing
  residency (lived in state more than 6 consecutive months = resident for this
  purpose). Applications in person; vision test given; may be eligible for a
  license without a written or road test (out-of-state reciprocity; other-country
  licences may still require TLSAE, written exam and/or driving test).

## 4. Documents needed — "What to Bring" / REAL ID

From What to Bring hub + Immigrant / Canadian pages + REAL ID page (search
extracts):

- REAL ID Act effective nationwide 2008; Florida began issuing REAL ID-compliant
  credentials 1 January 2010. Compliant cards carry a star in the upper right
  corner. After 7 May 2025 TSA only accepts licenses/ID cards with the star as
  airport ID (a US passport is an alternative); REAL ID also required for
  military bases and most federal facilities.
- Customers MUST visit an office with original documents if: applying for a
  first license/ID; current credential expires and has no star; or they legally
  changed name since last issuance. Name-change documents must show the full
  trail from birth name to current name; if the final certificate shows both
  birth and current names, only it is needed.
- Once identity documents are provided, they need only be provided again if
  information changes (name, address) — per REAL ID Act.
- **Three things, first in-office issuance after 1 Jan 2010:** original documents
  validating (1) identity, (2) Social Security Number, (3) residential address.
- **US citizens — primary identity (one):** valid unexpired US passport; original
  or certified birth certificate; Consular Report of Birth Abroad; Certificate
  of Naturalization (DHS); Certificate of Citizenship. If current name differs
  from the primary document, also bring court-ordered name change, marriage
  certificate (court-issued) and/or divorce decree (court-issued), showing a
  clear trail.
- **Non-citizens — primary identity:** valid unexpired Permanent Resident Card
  I-551 (lawful permanent residents); valid passport + US visa with I-94; DHS
  document showing lawful presence.
- **Both citizens and non-citizens:** Social Security card or proof of SSN; and
  two documents showing principal residence.
- **Immigrants (detail):** (1) Primary ID — original of one: valid alien
  registration receipt card (green card, I-551); I-551 stamp in passport or on
  I-94; immigration judge's order with A-number granting asylum + valid
  passport; I-797 with A-number granting asylum + valid passport; or I-797 /
  other USCIS form with A-number approving refugee status + valid passport.
  (2) Proof of SSN — original of one, with complete name and complete SSN:
  Social Security card (current name), W-2 (not handwritten), pay check/stub,
  SSA-1099, any 1099 (not handwritten). Customers without an SSN: see What to
  Bring FAQ. (3) Proofs of residential address — two different documents with
  Florida residential address (printouts/faxes acceptable); current FL license/ID
  may NOT be used as proof of address; out-of-state / US-territory addresses no
  longer accepted for Class E / ID applicants. Examples: deed / mortgage /
  monthly mortgage statement / residential rental-lease agreement; Florida
  vehicle registration or title; utility bill (water, gas, electricity, cell
  phone, cable) dated within last 60 days; auto payment booklet (within 60
  days); employer documentation (W-2, 1099, paycheck stub within 60 days);
  sexual offender/predator/career offender certification of address + FDLE form
  (within 60 days). A person with no address document in their own name may have
  the person they reside with complete a Certification of Address form plus two
  proofs listed on that form.
- **Canadians:** primary ID is an original valid Canadian passport; without it, a
  USCIS document establishing legal presence is also required. SSN and address
  proofs as for immigrants. Canadian non-immigrants are NOT eligible for a
  commercial learner's permit or CDL.
- **CLP/CDL holders:** must present two proofs of Florida residential address in
  their own name, from the page's List A / List B (e.g. List A: recent lease /
  rental agreement, term 6+ months, in the driver's name).
- **First-time original license applicants (FAQ):** must provide two forms of ID,
  proof of date of birth, proof of residential address, and proof of SSN; non-US
  citizens must present proof of legal presence. First-time applicants must also
  complete a 4-hour Traffic Law and Substance Abuse Education (TLSAE) course and
  pass a written exam, vision test and driving test. A vision test is required
  for all original issuances.
- Documents are scanned into the record and returned immediately after the
  transaction.

## 5. REAL ID — new credential design

From REAL ID page + New DL page (search extracts):

- **2026 redesign:** "On September 30, 2026, FLHSMV began issuing a newly
  designed Florida driver license and identification card that incorporates the
  Florida gator into the REAL ID star in the top righthand corner of all cards"
  (REAL ID page). The New DL page says the redesign "pays homage to Florida's
  rich history," was available at all service centers statewide on 30 Sept 2026
  (one line says 29 Sept 2026 — minor internal date discrepancy, see Flags),
  and would be accessible for online orders through MyDMV Portal by early
  November / end of November 2026 (two different phrasings on the same page).
- "This new design does not require Florida residents to replace their existing
  driver license or identification card."
- Credentials for customers under 21 display a red box on the front indicating
  the date until which the customer will be under 21.
- **Designations on the credential:** lifetime sportsman's, boater, freshwater,
  saltwater and hunting licences; Veteran; organ donor; deaf/hard of hearing;
  developmentally disabled. (See §7 for fees.)
- The earlier (Aug 2017 / Aug 2020–present) credential is described on the same
  New DL page with "Issue dates: August 2020 – Present" — i.e. the page covers
  both the 2020 design and the Sept 2026 redesign.

## 6. Renew or replace — periods, online renewal, replacements

From Renew or Replace page (search extract) + hub + Fees/MyDMV material:

- **Validity:** renew every 8 years; expiration date is on the credential.
  Class E for citizens/immigrants: 8 years under age 80, 6 years over 79.
  ID cards: after age 14, valid 8 years; ages 5–14, valid 4 years.
  Non-immigrant credentials: issued for the period approved by USCIS; word
  "TEMPORARY" appears in red on the front, lower right margin.
- **Early renewal:** driver license up to 18 months in advance of expiration.
  ID card: the Renew page says 12 months in advance; the hub says 18 months
  for "driver license and ID card holders" — flagged in §10.
- **Online renewal (MyDMV Portal):** offered every other renewal period — if the
  last renewal was online/by mail/by phone, the next must be in person. The
  department must verify the customer's SSN to renew/replace online. Services
  via MyDMV Portal: renew a driver license; update address; replace a lost or
  stolen credential; register/update emergency contact information. Credential
  arrives by mail within 2–3 weeks; $2.00 processing/convenience fee per online
  transaction (non-refundable); emailed confirmation receipt available.
  FLHSMV's 2019 release: 3.76 million transactions completed through MyDMV Portal
  in the prior year; MyFlorida is the mobile app for registration renewals only
  (not a license app).
- **Replacement / duplicate (lost, stolen, update):** "Drivers can replace their
  driver license or ID card prior to its expiration if the credential is lost,
  stolen or they need to make an update." Fee: $25.00 (see §7).
- **Address change:** "If there is a change of address, Florida driver license or
  ID card holders have 30 days to update their address on the credential."
  US citizens may do an address change online or in person. General Information
  page: "Florida law requires residents, within 30 days of changing their name
  or address, to obtain a replacement license. The incorrect license must be
  surrendered to the Division."
- **Name change:** must update name with the Social Security Administration first,
  then present an original or certified court order / marriage certificate when
  applying to change the name on the credential. (General Information: non-US
  citizen requirements differ — page links to a separate non-citizen section,
  not reproduced here.)
- **Late renewal:** a $15.00 late fee applies (fee schedule). No delinquency
  grace period is stated on the pages studied; do not assume one.

## 7. Fees — full FLHSMV fee schedule (driver license portion)

From Fees page (search extract; "Fees for driver license and motor vehicle
services are established in Florida Law"):

| Fee | Amount |
|---|---|
| Original Class E (includes Learner's license) | $48.00 |
| Original / Renewal Commercial Driver License | $75.00 |
| Original School Board Commercial Driver License | $48.00 |
| Renewal Class E | $48.00 |
| Renewal School Board Commercial Driver License | $48.00 |
| Replacement license | $25.00 |
| Late fee | $15.00 |
| Endorsements (each) | $7.00 |
| Knowledge retest | $10.00 |
| Skill retest | $20.00 |
| Identification Cards (Original, Renewal & Replacement) | $25.00 |
| Administrative fee, alcohol/drug-related offenses | $130.00 |
| D-6 Suspension — DHSMV | $60.00 |
| Disqualification | $75.00 |
| Revocations (+ admin fee if alcohol/drug related) | $75.00 |
| Suspensions (+ admin fee if alcohol/drug related) | $45.00 |
| Court-ordered child support suspension | $60.00 |
| Dept. of Revenue child support suspension | $45.00 |
| Worthless check suspension | $55.00 |
| Filing fee, hardship hearing | $12.00 |
| Filing fee, formal/informal review | $25.00 |
| DUI program fee (assessed by the program) | $15.00 |
| Interlock fee (assessed by the vendor) | $12.00 |
| Driver history records, 3-year | $8.00 |
| Driver history records, 7-year (complete or certified) | $10.00 |
| Crash reports | $10.00 |

- **Tax-collector surcharge:** "An additional $6.25 service fee may apply to any
  credential issued in a tax collector office." Veterans who provided / previously
  provided evidence of veteran status are NOT charged the $6.25 fee in a tax
  collector office for transactions marked with an asterisk in the schedule
  (original/renewal Class E and CDL, replacement, retests, ID cards).
- **Replacement free to veterans only when adding the "Veteran" designation.**
- **Payment:** state-operated (FLHSMV) service centers accept American Express,
  MasterCard and Discover; accepted cards may vary at County Tax Collector
  offices — contact the office in advance.
- **Online:** $2.00 convenience fee per MyDMV Portal transaction.
- **New-resident page confirms:** initial Class E (incl. learner's) $48.00,
  CDL Class A $75.00, endorsements $7.00 each, ID card $25.00, most tax
  collector offices add $6.25.
- **Designation fees (Designation Fees page):** Deaf/Hard of Hearing — issuance
  fees + $1 ($3 total to add with no other changes), no documentation; 
...[truncated 6151 chars]# 03 — Suspensions & Revocations (flhsmv.gov)

Study date: Monday, November 23, 2026. Sources are FLHSMV pages only, except where
a fact is explicitly marked as coming from the Florida Statutes text itself
(Fla. Stat. §§ 318.15, 322.245, 322.27, 316.238), which the FLHSMV pages
implement but do not quote in full. Where an FLHSMV page does not state a
number, this file says so rather than filling it in.

## 1. Pages studied

| # | Page | URL | How read |
|---|------|-----|----------|
| 1 | Driver Licenses & ID Cards (hub) | https://www.flhsmv.gov/driver-licenses-id-cards/ | browser.open, full page (85 lines) |
| 2 | A to Z Guide | https://flhsmv.gov/a-to-z-guide/ | browser.open, full page (608 lines); entries used: Suspensions (Driver License), Revocations (Driver Licenses), DUI, Points (Driver License), Vision (Driver License), Ignition Interlock, Medical Card, Traffic School Completion Check, Pay a Traffic Ticket |
| 3 | Driver License Suspensions and Revocations (hub) | https://www.flhsmv.gov/driver-licenses-id-cards/driver-license-suspensions-revocations/ | Search-indexed full text (search result). Direct browser.open of this URL returned HTTP 429 (rate limit) at time of study; content below is from the indexed copy, not a live open |
| 4 | Traffic Citations or Court Suspensions | https://flhsmv.gov/driver-licenses-id-cards/driver-license-suspensions-revocations/traffic-citations-court-suspensions/ | browser.open, full page (76 lines, crawled 2025-07-23) |
| 5 | Other Common Suspensions and Revocations | https://www.flhsmv.gov/driver-licenses-id-cards/driver-license-suspensions-revocations/other-suspensions-revocations/ | Search-indexed full text. Direct browser.open returned HTTP 403 once and HTTP 429 after; content below is from the indexed copy, not a live open |
| 6 | Fees (fee schedule) | https://www.flhsmv.gov/fees/ | Search-indexed full text (fee table reproduced verbatim in §3) |
| 7 | Driver Improvement Schools / ADI / BDI | https://flhsmv.gov/driver-licenses-id-cards/education-courses/driver-improvement-schools/ and https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/driver-improvement-schools/basic-driver-improvement-bdi-find-approved-listing-bdi-course-providers/ | Search-indexed text |
| 8 | Traffic Citations | http://www.flhsmv.gov/FHP/traffic/ (Traffic Citations page) | Search-indexed text |
| 9 | Questions About Driving Records | https://flhsmv.gov/driver-licenses-id-cards/general-information/questions-about-driving-records/ | Search-indexed text |
| 10 | Impaired Driving | https://www.flhsmv.gov/safety-center/driving-safety/impaired-driving/ and http://www.flhsmv.gov/safety-center/be-responsible-dont-drink-and-drive/ | Search-indexed text |
| 11 | Ignition Interlock Device (IID) FAQs | https://flhsmv.gov/driver-licenses-id-cards/education-courses/dui-and-iid/ignition-interlock-device-iid-faqs/ | Search-indexed text |
| 12 | Ignition Interlock Program | https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/dui-and-iid/ignition-interlock-program/ | Search-indexed text |
| 13 | Involved in a Crash? (Financial Responsibility) | https://flhsmv.gov/insurance/involved-in-a-crash/ | Search-indexed text |
| 14 | Uninsured Motorist Rate | https://www.flhsmv.gov/insurance/uninsured-motorist-rate/ | Search-indexed text |
| 15 | DLCheck sanction help pages (services.flhsmv.gov) — Clearing Court Suspensions; Clearing Failure to Pay Support – Court Ordered; Clearing Court Financial Obligations; Clearing Revocation – Failure to Submit Vision Report; Clearing Revocation – Failure to Submit Medical Report; Clearing Suspension – Worthless Check | https://services.flhsmv.gov/DLCheck/SanctionHelpPages/Sanction03Help.aspx, Sanction13Help.aspx, Sanction10Help.aspx, Sanction27Help.aspx, Sanction30Help.aspx, Sanction08Help.aspx | Search-indexed text |
| 16 | Bureau of Administrative Reviews (county office pages, e.g. Leon, Escambia, Charlotte) | https://www.flhsmv.gov/offices/leon.html etc. | Search-indexed text |
| 17 | Medical Review (hub blurb, Driver Licenses & ID Cards page §1) | https://www.flhsmv.gov/driver-licenses-id-cards/ | browser.open (see §1 above) |

**Access note:** during this study the FLHSMV site rate-limited direct page
opens (HTTP 429) and returned one HTTP 403 on the Other Suspensions page.
Pages 3, 5–16 above were therefore read from the search engine's indexed
copies of the FLHSMV pages, not from live opens. Their wording is quoted
from those indexed copies. A live re-open is recommended before any of these
facts are used in a filing or a payment decision.

## 2. What the hub pages say (overview)

- The Driver Licenses & ID Cards hub describes the Suspensions & Revocations
  page as covering "reinstating a driver license after being suspended or
  revoked due to unpaid traffic tickets, failure to comply or appear at a
  traffic summons, failure to complete a court-ordered driver improvement
  course, inadequate vision, being a habitual traffic offender, being
  delinquent in child support and more."
- The Suspensions and Revocations hub repeats that list and adds "point
  suspensions," and links out to three sub-pages: Financial Responsibility
  suspensions, DUI and Ignition Interlock Device (IID) revocations, and
  Medical or Vision revocations or suspensions.
- FLHSMV's own definition (Driving Records FAQ): "Revocation – the
  termination of a driving privilege. Suspension – the temporary withdrawal
  of a driving privilege."

## 3. Reinstatement fees (FLHSMV fee schedule, https://www.flhsmv.gov/fees/)

Verbatim from the FLHSMV fee table ("Fees for driver license and motor
vehicle services are established in Florida Law"):

| Fee type | Amount |
|---|---|
| Suspensions | $45.00 |
| Revocations (additional administrative fee shown above required if alcohol or drug related) | $75.00 |
| Administrative Fee for alcohol and drug related offenses | $130.00 |
| D-6 Suspension – DHSMV | $60.00 |
| Disqualification | $75.00 |
| Court Ordered Child Support Suspension | $60.00 |
| Department of Revenue (DOR) Child Support Suspension | $45.00 |
| Worthless Check Suspension | $55.00 |
| Filing Fee for hardship hearing | $12.00 |
| Filing Fee for Formal/Informal review | $25.00 |
| DUI program fee (assessed by the program) | $15.00 |
| Interlock Fee (assessed by the vendor) | $12.00 |

Notes from the schedule and the sanction help pages:

- The D6 fee is **$60 per suspension** — the court-financial-obligations
  help page states the arithmetic explicitly: "2 failures to pay court
  financial obligations suspensions = $60.00 x 2." The child-support help
  page gives the same pattern: two court-ordered child support suspensions
  = $120.00, three = $180.00.
- DUI revocation reinstatement is therefore $75 + $130 = $205 in FLHSMV
  fees before DUI school, treatment, IID and FR-44 costs (fee schedule
  amounts; the $205 total is arithmetic on the two listed fees).
- The fee schedule does **not** list a separate "$150–$500" line; the
  $150–$500 figure for failure to maintain PIP/PDL insurance appears on
  the Financial Responsibility pages (§8 below), not in the fee table.
- A $6.25 service fee "may apply to any credential issued in a tax
  collector office."
- Mail-in clearance processing: "Allow ten business days for processing"
  (Traffic Citations or Court Suspensions page); the sanction help pages
  say mailed items clear "within 7-10 days of receipt by DHSMV."

## 4. Traffic citations / court suspensions (D6) — the core page

Source: Traffic Citations or Court Suspensions page, read in full. **Every
item below is FLHSMV wording, paraphrased only for brevity.**

- **Failure to Pay a Fine:** "A driver license will be suspended
  indefinitely if the driver fails to pay a traffic fine." Clear by
  contacting the traffic court in the county where the citation was issued
  and satisfying the citation requirements; some courts allow online
  payment by credit card. "Once the court requirements have been met, the
  county will update the department electronically with the clearance
  information. You may then present a reinstatement fee, if applicable, to
  any Florida driver license service center or call 850-617-3000 to pay the
  reinstatement fee over the phone."
- **Failure to Comply with or Appear at a Traffic Summons:** "A driver
  license will be suspended indefinitely if the driver fails to comply with
  or appear at a traffic summons." Same clearance route (county traffic
  court, then electronic clearance, then reinstatement fee in person or by
  phone at 850-617-3000).
- **Failure to Complete Driver Improvement School:** "A driver license will
  be suspended indefinitely if the driver fails to complete a court-ordered
  driver improvement school, or if a school election was made for a citation
  but the driver did not or was not eligible to attend." Same clearance
  route.
- **Clearing a Traffic Citation Received in Another State:** "Any unpaid
  citation reported by another state will result in the suspension of a
  Florida driver license." Clear with a paid receipt bearing the court seal
  of the county where the citation was received, plus a reinstatement fee,
  if applicable, at any Florida driver license service center; or mail proof
  + fees to Bureau of Motorist Compliance, P.O. Box 5775, Tallahassee,
  Florida 32314-5775, checks/money orders payable to the Division of
  Motorist Services, including your Florida driver record number. Allow ten
  business days.
- **Clearing a Court Financial Obligation:** "A driver license will be
  suspended indefinitely if a person fails to pay a court financial
  obligation related to certain criminal offenses." Clear by satisfying the
  court, then "present proof of satisfaction in the form of an affidavit
  within 30 days, along with all applicable reinstatement fees, to any
  Florida driver license service center." Out-of-state residents may mail
  the affidavit + fee to the Bureau of Motorist Compliance address above.
  The sanction help page adds the affidavit must state one of: the
  obligation is satisfied in full or all payments currently due under a
  payment plan have been made; a written payment agreement has been entered
  into; or the court has ordered reinstatement.
- **Hardship:** "Note: Traffic citations or court suspensions are not
  eligible to be considered for a hardship license." (Bold note at the top
  of the page.)
- **Status check:** "You may obtain the suspending citation information
  online or check the status of your clearance by using our Online Driver
  License Check."

**What the FLHSMV page does NOT state:** the page gives no day counts at
all — no clerk-notification deadline, no effective-date delay, no hearing
deadline. The 10-day / 20-day / 180-day numbers in §10 below come from the
statute text, not from any FLHSMV page read in this study.

## 5. Points suspensions

Source: FLHSMV Driver Improvement Schools / ADI pages and BDI page.

- "To be suspended for points, a driver accumulates: 12 points within 12
  months (30 day suspension); 18 points within 18 months (3 month
  suspension); or 24 points within 36 months (1 year suspension)."
- "Drivers must complete an Advanced Driver Improvement (ADI) course if
  their driver license was suspended in Florida for accumulation of points,
  as a habitual traffic offender (non-DUI related), or by court order."
- Points are assessed for moving violations where an adjudication of guilt
  is found.
- BDI election: "drivers must voluntarily elect this option within 30 days
  (section 318.14(4), Florida Statutes) from the citation date and, prior
  to attending the course, drivers must inform the clerk of court in the
  county where the citation was issued of this election." After the initial
  30-day period, a driver may not elect BDI in lieu of points.
- Traffic school election limits (Driving Records FAQ): "a person may make
  no more than five traffic school elections within their lifetime and once
  in a twelve-month period" (effective July 1, 2024, Fla. Stat. 318.14(9)).
  An older FAQ line says "one time within a 12-month period and no more
  than five times within a 10-year period" — the 5-in-a-lifetime rule is
  the newer (July 1, 2024) statement on the same FLHSMV site.
- Under 18: six or more points within 12 months = automatic restriction to
  "Business Purposes Only" for one year (or until age 18, whichever first);
  each additional point extends the restriction 90 days.
- Traffic Citations page: customers have **30 days** to elect (pay, contest,
  or take a driver improvement course) with the clerk of court listed on
  the citation. "Failure to elect within 30 days may result in additional
  fines along with a suspension of the driving privilege." Paying the civil
  penalty is a conviction and points are assessed. Electing BDI reduces the
  fine by 18%.
- Points retention (Driving Records FAQ): D-6 suspensions, once cleared,
  "remain on the record 1 year from the reinstatement date and are then
  converted to a correspondence entry for 2 more years. Once this D6 entry
  converts to a correspondence entry it does not appear on 3- or 7-year
  driver records (transcripts)." Citation dispositions of guilty generally
  have a 3- to 5-year retention; more serious violations vary (10 years, 15
  years, etc.).

## 6. Habitual Traffic Offender (HTO)

Source: Other Common Suspensions and Revocations page.

- "A Habitual Traffic Offender is a person who has accumulated fifteen
  moving violations in which points were assessed in five years, or three
  major violations in five years."
- Major offenses listed (list truncated in the indexed copy; items seen):
  driving while license suspended or revoked; DUI, DWI or other alcohol
  related convictions; failure to stop and render aid in the event of a
  motor vehicle crash; [further items not visible in the indexed copy].
- "If a person is determined to be a Habitual Traffic Offender, an
  individual's driver license will be revoked for five years."
- "After one year from the effective date of the revocation, a driver may
  apply for a hardship license through their local Administrative Reviews
  Office. To obtain a hardship license, the driver must submit proof of an
  Advanced Driver Improvement (ADI) school completion and pay a
  reinstatement fee, along with any other applicable license fees."
- After the revocation period expires, full reinstatement is by paying a
  reinstatement fee, along with any other applicable license fees, at any
  Florida driver license service center (additional suspensions may require
  additional clearance requirements).

## 7. Child support delinquency

Source: Other Common Suspensions and Revocations page + DLCheck sanction
help pages.

- "Delinquency in child support can result in an indefinite suspension of
  driving privilege."
- Department of Revenue-ordered: call 850-488-5437 or visit the Department
  of Revenue's website. Once requirements are met, DOR "will update the
  Department of Highway Safety and Motor Vehicles electronically with the
  clearance information. You may then present a reinstatement fee for each
  suspension, if applicable, to any Florida driver license service center."
- Court-ordered: "a driver may bring a court affidavit showing proof of
  compliance within 30 days, along with a reinstatement fee for each
  suspension, if applicable, to any Florida driver license service center."
  (Fee: $60 court-ordered, $45 DOR-ordered, per the fee schedule §3.)
- "Note: Child support delinquency suspensions are not eligible to be
  considered for a hardship license."
- The sanction help page adds: the court affidavit "must be dated within 30
  days of reinstatement"; mailed clearances take 7–10 days.

## 8. Financial Responsibility (insurance) suspensions

Source: Involved in a Crash? page; Uninsured Motorist Rate page; Suspensions
hub link.

- Florida No-Fault Law requires $10,000 PIP and $10,000 PDL throughout the
  registration period. "Failure to maintain the required insurance coverage
  may result in suspension of the registrant's driver license/registration
  and a reinstatement fee of $150 – $500."
- Crash with injuries, at-fault driver charged with a moving violation and
  without full liability coverage ($10,000/$20,000/$10,000 + $10,000 PIP):
  must (1) purchase and maintain those minimum limits plus an SR-22 filing
  for three years from the designated suspension date (insurer must certify
  the SR-22 to the department); (2) obtain releases from the other parties
  or post a security deposit in the amounts on the suspension notice; and
  (3) pay a $15 reinstatement fee, if applicable.
- Crash, property damage only, at-fault owner without compulsory coverage
  ($10,000 PDL + $10,000 PIP): must (1) obtain releases or post a security
  deposit; (2) purchase $10,000 PIP/$10,000 PDL insurance or surrender the
  Florida plate and registration; and (3) pay a $150 – $500 reinstatement
  fee, if applicable.
- Final judgment (Fla. Stat. § 324.121): "Final judgments submitted to our
  department are immediately enforced and the at-fault party's license,
  tags, and registrations are suspended for 20 years or until the judgment
  is satisfied."
- Crash reporting: Fla. Stat. § 316.065 requires the driver in a crash
  involving injury/death or at least $500 estimated vehicle/property damage
  to immediately contact local law enforcement.
- Business customers: if a Notice of Suspension's requirements are not met
  before the original suspension date on the notice, a reinstatement fee is
  required; once payment is processed the stop is removed immediately.

## 9. DUI suspensions / revocations and Ignition Interlock

Source: FLHSMV Impaired Driving pages; IID FAQs; IID Program page; Other
Common Suspensions page; fee schedule.

- "For any DUI conviction, your driver license will be revoked for a
  minimum of 180 days."
- "If you refuse to take a required roadside test at the time of arrest,
  your license will be automatically suspended for one year."
- "Fines for DUI can range from $500 to $5,000 with mandatory DUI school
  education. Penalties can also include an ignition interlock device,
  community service, probation or imprisonment. DUI convictions must remain
  on your record for 75 years."
- DUI revocation periods by history (as summarized on FLHSMV-linked
  material in the indexed copies): first offense without bodily injury,
  minimum 180 days up to 1 year; first offense with bodily injury, minimum
  3 years; second within 5 years, minimum 5 years (hardship eligible after
  1 year); second 5+ years after first, minimum 180 days up to 1 year;
  third within 10 years of second, minimum 10 years (hardship eligible
  after 2 years); third 10+ years after second, minimum 180 days up to 1
  year; fourth offense, permanent revocation (per the indexed summary;
  verify against the live DUI page before relying on the 4th-offense line).
- IID required periods: first conviction — if court ordered; first
  conviction with BAL 0.15 or above, or minor in car — at least 6 months;
  second conviction — at least 1 year; second with BAL 0.15+ or minor in
  car — at least 2 years; third conviction — at least 2 years; four or more
  convictions (condition of hardship license) — at least 5 years.
- "In order for time to count toward your restriction, an IID 'P'
  restriction must be placed on the driving record and license reinstated."
  IID time begins the day the "P" restriction is issued. A driver must have
  an IID installed in a vehicle they own and/or routinely operate; "There
  is no reinstatement provision for people who do not own and/or routinely
  operate a vehicle."
- IID alcohol threshold: 0.025 BAL if convicted after July 1, 2013; 0.050
  BAL if convicted before July 1, 2013.
- IID program applies to those arrested and convicted of DUI after
  July 1, 2002, upon eligibility for reinstatement of a permanent or
  restricted license.
- DUI school fees (FLHSMV DUI Program Service Fees, as of October 1,
  2023): Level I registration $330; Level II registration $495 (each
  includes $5 Driver Risk Inventory).
- Hardship / administrative review: the Bureau of Administrative Reviews
  (BAR) handles hardship licenses, Formal Review – DUI, and Waiver of
  Formal Review (1st DUI only). Forms may be submitted by email without
  visiting a BAR office. Filing fees per the fee schedule: formal/informal
  review $25; hardship hearing $12.

## 10. Medical / vision suspensions and revocations

Source: Driver Licenses & ID Cards hub (Medical Review blurb); DLCheck
sanction help pages for vision/medical revocations; FLHSMV-linked vision
standards material in the indexed copies.

- Medical Review mission (hub): "not to prevent an individual with a
  medical condition from driving, but to assure the condition does not
  interfere with the safe operation of a motor vehicle." Any physician,
  person, or agency may report a driver who may be unsafe due to a medical
  condition; reports must be based on medical conditions/symptoms, not age.
- Failure to submit a required vision report: "Your driving privilege has
  been revoked for failure to submit a required vision report." Clear by
  providing a Report of Eye Exam completed by an eye specialist. Fastest:
  take it to a local driver license office. Or fax to (850) 617-3917 or mail
  to DDL-BDI, 2900 Apalachee Parkway MS 87, Tallahassee, FL 32399-0570;
  clears within 7–10 days of receipt. Include name and driver license
  number.
- Failure to submit a required medical report: privilege "is due to be
  revoked" / "has been revoked for not submitting a required medical
  report." Contact the Medical Review Section at (850) 617-3814 for
  instructions.
- Vision standard (FLHSMV vision material): minimum visual acuity 20/70 in
  either eye or both eyes together, with or without corrective lenses,
  where vision cannot be improved; if one eye is blind or 20/200 or worse,
  the other must reach 20/40. To pass screening outright: 20/40 or better
  in each eye. Field of vision minimum 130 degrees horizontal.
- Medical review process (county tax collector mirror of the FLHSMV page):
  driver is notified in writing that they are under medical review and must
  provide medical information from their physician within 45 days; the
  information goes to the Medical Advisory Board for review and
  recommendation; if approved, the driver may be required to take a
  re-examination and/or submit a follow-up medical report.
- Age 80+ renewal vision requirements are a separate A-to-Z entry
  ("Renewing – Age 80 & Older – Vision Requirements") and were not opened
  in this section.

## 11. Other revocations on the Other Common Suspensions page

- **Violation (not DUI-related) resulting in death or serious bodily
  injury:** license suspended for up to one year for a non-DUI citation
  conviction (including adjudication withheld) that resulted in death or
  serious bodily injury. Hardship license available through the local
  Administrative Reviews Office with proof of ADI school completion plus a
  reinstatement fee and any other applicable license fees; hardship
  restricts driving to employment/business purposes only. After the
  suspension period expires, full reinstatement on payment of a
  reinstatement fee plus other applicable fees at any driver license service
  center.
- **Chapter 893 – Drug Related Offense:** license suspended for at least
  one year for a conviction of possession or sale of, trafficking in, or
  conspiracy to possess, sell or traffic a controlled substance. Hardship
  license may be applied for after six months from the effective date of
  the revocation, with proof of Licensed DUI Program school completion plus
  a reinstatement fee and other applicable fees. Full reinstatement after
  the revocation period expires on payment of a reinstatement fee plus
  other applicable fees at any driver license service center.

## 12. Hearing rights and deadlines found on FLHSMV pages

- **DUI administrative suspension (FLHSMV BAR process):** a driver may
  request a Formal Review – DUI or file a Waiver of Formal Review (1st DUI
  only) through the Bureau of Administrative Reviews; forms can be emailed.
  The 10-day deadline to request a formal/informal review after a DUI
  administrative suspension is stated in Fla. Stat. § 322.2615 and in
  third-party summaries of the FLHSMV process; **no FLHSMV page read in
  this study states the 10-day DUI review deadline in its own text.**
  Filing fee for a formal/informal review: $25 (fee schedule).
- **Hardship hearing filing fee:** $12 (fee schedule).
- **D6 / traffic-citation suspensions:** no hearing right or deadline is
  stated anywhere on the FLHSMV pages read. See §13 for the statute text.
- **Child support (non-IV-D):** the obligor has 20 days after the notice
  is mailed to pay, enter a written payment agreement, file a petition to
  contest, or show a qualifying exemption (Fla. Stat. § 61.13016 — statute
  text, not an FLHSMV page).

## 13. FLAG CHECK — Muse3's claims about Git-FED's OTR case

Claims to test (ticket: Oct 24, 2026, failure to dim headlights,
Fla. Stat. § 316.238, moving violation, 3 points):

1. "D6 suspension is NOT instant at midnight after the deadline — clerk
   must notify FLHSMV within 10 days of failure and suspension is
   effective 20 days after the order."
2. "A hearing can be requested within 180 days."
3. "Reinstatement fee $60."

**Verdict: NO CONTRADICTION FOUND on any FLHSMV page. Claims 1 and 3 are
directly supported; claim 2 is supported by the statute text, not by any
FLHSMV page.**

Evidence:

- **Claim 3 ($60) — CONFIRMED on FLHSMV itself.** Fee schedule:
  "D-6 Suspension – DHSMV $60.00." The DLCheck sanction help page for
  court suspensions also states: "A $60.00 reinstatement fee is required"
  for failing to pay traffic tickets in the time allowed.
- **Claim 1 (10 days / 20 days) — CONFIRMED by the governing statute,
  consistent with FLHSMV pages.** Fla. Stat. § 318.15(1)(a): "If a person
  fails to comply with the civil penalties provided in s. 318.18 within the
  time period specified in s. 318.14(4), fails to enter into or comply with
  the terms of a penalty payment plan with the clerk of the court ...,
  fails to attend driver improvement school, or fails to appear at a
  scheduled hearing, the clerk of the court shall notify the Department of
  Highway Safety and Motor Vehicles of such failure within 10 days after
  such failure. Upon receipt of such notice, the department shall
  immediately issue an order suspending the driver license and privilege to
  drive of such person effective 20 days after the date the order of
  suspension is mailed in accordance with s. 322.251(1), (2), and (6)."
  The FLHSMV pages are consistent (they say only "suspended indefinitely"
  and never say "instant" or "at midnight"); they simply do not state the
  10-day/20-day numbers themselves. The same 10-day clerk notice +
  20-days-after-mailing structure appears in Fla. Stat. § 322.245 for
  failure to comply with court directives (clerk notice "not later than 5
  days after such failure" for the warning notice to the driver, 30 days to
  comply + delinquency fee up to $25, then clerk notifies the department
  within 10 days, suspension effective 20 days after the order is mailed).
- **Claim 2 (180-day hearing) — CONFIRMED by the statute, NOT stated on
  any FLHSMV page read.** Fla. Stat. § 318.15(1)(c): "A person who is
  charged with a traffic infraction may request a hearing within 180 days
  after the date upon which the violation occurred, regardless of any action
  taken by the court or the department to suspend the person's driving
  privilege, and, upon request, the clerk must set the case for hearing."
  For the Oct 24, 2026 violation, 180 days after the violation date is
  **Thursday, April 22, 2027**. Note the clock runs from the *violation
  date*, not from the suspension date — and it is a right to request a
  hearing on the underlying infraction, not a right to a hearing on the
  suspension itself. No FLHSMV page read in this study mentions this
  180-day window; a reader relying only on FLHSMV pages would not find it.
- **Ticket classification — CONSISTENT.** Fla. Stat. § 316.238(2): "A
  violation of this section is a noncriminal traffic infraction, punishable
  as a moving violation as provided in chapter 318." Dimming distances:
  within 500 feet of an oncoming vehicle; within 300 feet when following.
  The 3-point figure: Fla. Stat. § 322.27 assigns 3 points to a moving
  violation not otherwise assigned a higher value ("any other moving
  violation — 3 points"). **No FLHSMV page read in this study lists
  § 316.238 or its point value by name** — the FLHSMV point tables seen
  list thresholds and categories, not a per-statute table. The 3-point
  claim is therefore consistent with the statute's default but is
  **not verified from an FLHSMV page**.
- **Related dates for this ticket:** the 30-day election window (pay,
  contest, or elect driver improvement) from the Oct 24, 2026 citation date
  ends **Monday, November 23, 2026** (today). BDI election must also be
  made within 30 days of the citation date and the clerk notified before
  attending the course.
- **D6 record retention:** an unreinstated D6 "shall remain on the records
  of the department for a period of 7 years from the date imposed"
  (§ 318.15(1)(a)); once cleared, FLHSMV's records FAQ says it stays on
  the record 1 year from reinstatement, then converts to a correspondence
  entry for 2 more years and no longer appears on 3- or 7-year records.
- **Reinstatement path for this ticket if a D6 were imposed:** satisfy the
  court (pay / payment plan / comply), obtain a certificate of compliance
  from the court, present it with the $60 nonrefundable service charge
  (§ 318.15(2)) to a driver license office, or pay the charge to the clerk
  or an authorized licensing agent. No hardship license is available for a
  traffic-citation/court suspension (FLHSMV page note).

**Gaps / cautions for the parent agent:**

- The FLHSMV Suspensions hub and Other Suspensions page could not be
  opened live (429/403 at study time); their content above comes from
  indexed copies. Re-open live before relying on the HTO major-offense
  list (truncated in the indexed copy) and the 4th-DUI permanent
  revocation line.
- The 180-day hearing right and the 10-day/20-day D6 timing are statute
  text, not FLHSMV page text. FLHSMV pages neither confirm nor contradict
  them; they are silent.
- The $60 D6 fee is the only one of the three claims stated on an FLHSMV
  page itself.
# 04 — Teen Drivers & Graduated Licensing (flhsmv.gov)

Source: Florida Department of Highway Safety and Motor Vehicles (FLHSMV), flhsmv.gov.
Method: direct `browser.open` reads of the pages below where possible, plus
verbatim flhsmv.gov search-result excerpts for pages that returned HTTP 429 on
re-open. Every fact below comes from an flhsmv.gov page (or its official
search excerpt); no third-party site was used for facts. See "Verification
notes / gaps" at the end for the three pages affected by the 429 limit.

## Pages studied

| # | Page | URL |
|---|---|---|
| 1 | Driver Licenses & ID Cards (hub — "Teen Drivers" section) | https://www.flhsmv.gov/driver-licenses-id-cards/ |
| 2 | A to Z Guide (entries: Graduated License – Under Age 18; Learner License/Permit; Learner's License Test Online; Parents of Teen Drivers; Parental Access to Minor Driving History; Teen Drivers; Test for Learner's License; TLSAE; Written Test for Learner's License Online) | https://flhsmv.gov/a-to-z-guide/ |
| 3 | Teen Drivers | https://www.flhsmv.gov/driver-licenses-id-cards/teen-drivers/ |
| 4 | Licensing Requirements for Teens, Graduated Driver License Laws and Driving Curfews (parent page) | https://www.flhsmv.gov/driver-licenses-id-cards/licensing-requirements-teens-graduated-driver-license-laws-driving-curfews |
| 5 | Traffic Laws for Florida Teens (subpage of #4) | https://www.flhsmv.gov/driver-licenses-id-cards/licensing-requirements-teens-graduated-driver-license-laws-driving-curfews/traffic-laws-florida-teens/ |
| 6 | Class E Knowledge Exam & Driving Skills Test (subpage of #4) | https://www.flhsmv.gov/driver-licenses-id-cards/licensing-requirements-teens-graduated-driver-license-laws-driving-curfews/class-e-knowledge-exam-driving-skills-test/ |
| 7 | Required Forms for Teens (subpage of #4) | https://www.flhsmv.gov/driver-licenses-id-cards/licensing-requirements-teens-graduated-driver-license-laws-driving-curfews/required-forms-teens/ |
| 8 | What is TLSAE / approved TLSAE course providers | https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/driver-improvement-schools/traffic-law-substance-abuse-education-tlsae-find-approved-listing-tlsae-course-providers/ |
| 9 | Driver Education Traffic Safety (DETS) | https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/driver-improvement-schools/driver-education-traffic-safety-dets/ |
| 10 | Fees (fee schedule — learner's/Class E fees) | https://www.flhsmv.gov/fees/ |
| 11 | License Classes, Endorsements & Designations (Class E learner's conditions; under-21 curfews) | https://flhsmv.gov/driver-licenses-id-cards/general-information/license-classes-endorsements-designations/ |
| 12 | Driver License Check / Parental Access to Minor Driving History | https://services.flhsmv.gov/DLCHECK/ (linked from the hub; described on flhsmv.gov) |

A-Z entries "Parents of Teen Drivers" and "Parental Access to Minor Driving
History" point at pages #4/#7 and #12 respectively; no separate standalone
"Parents of Teen Drivers" article text was returned — the content lives on
the teen-licensing parent page, the Required Forms page, and Driver License
Check. The old URL http://www.flhsmv.gov/teens/ appears in search results
as a legacy redirect to the current teen pages.

## 1. Graduated Driver Licensing (GDL) — the framework

- GDL laws "allow young drivers to safely gain driving experience under
  lower-risk conditions before obtaining full driving privileges" and
  "outline limits and restrictions for new drivers, ages 15, 16 and 17."
- "In 1996, Florida became the first state to enact GDL laws and since then
  every state has adopted the GDL program in some capacity." (Teen Drivers page)
- "It is important for teens and their parents to understand these laws and
  obey them."

### GDL table (as published on flhsmv.gov)

| License type | Hours | Notes |
|---|---|---|
| Learner's License | Daylight hours for first 3 months after license issued; until 10 p.m. after 3 months | ALWAYS accompanied by a licensed driver 21+. Must hold for a minimum of 12 months or until 18th birthday, whichever comes first. Required 50 hours of supervised driving, 10 of which must be at night. |
| Driver License — 16 years old | Driving only allowed between 6 a.m. and 11 p.m. | Unless driving to or from work OR accompanied by a licensed driver 21+. |
| Driver License — 17 years old | Driving only allowed between 5 a.m. and 1 a.m. | Unless driving to or from work OR accompanied by a licensed driver 21+. |

Statutes cited on the page for the table:
- 322.1615(1) — minimum age of 15 required for learner's license
- 322.161(1)(a) — minimum duration to hold a learner's license
- 322.05(1) — minimum age of 16 for Class E license
- 322.05(2)(a) — learner's license required for 12 months
- 322.05(3) — required supervised driving for 50 hours, 10 at night
- 322.16(2) — nighttime driving restrictions for 16
- 322.16(3) — nighttime driving restrictions for 17

## 2. Learner's license — requirements (age 15)

Requirements for teens obtaining a Florida learner's license (parent page):

- Must be at least 15 years old.
- If under 18, must have a signed/notarized Parental Consent Form
  (step-parents may not sign unless they have legally adopted the minor child).
- Proof of Driver Education Traffic Safety (DETS) course completion
  (current wording; see §3 — older versions of the same page said TLSAE).
- Pass a vision and hearing test — testing is conducted in a service center.
- Pass the Class E Knowledge Exam (see §6).
- Must provide documents to establish proof of identity, proof of Social
  Security number, and proof of residential address
  (flhsmv.gov/WhatToBring for the list of acceptable documents).

### Learner's license restrictions

- ALWAYS accompanied by a licensed driver age 21 or older.
- The accompanying licensed driver must occupy the closest seat to the right
  of the driver (front passenger seat) — stated on the License Classes page.
- Daylight hours only during the first 3 months from the original issue
  date; until 10:00 p.m. thereafter.
- Must hold the learner's license for a minimum of 12 months or until the
  18th birthday, whichever comes first.
- Learner's license covers motor vehicles less than 8,000 pounds
  (License Classes page).
- Learner drivers are NOT allowed to operate motorcycles (also stated as
  "not allowed to operate motorcycles, mopeds, or go-peds" in county
  summaries — on flhsmv.gov itself the stated ban is motorcycles).
- 50 hours of supervised driving required, 10 of which must be at night,
  certified before the Class E license (see §4).

## 3. DETS vs TLSAE — the course requirement (important change)

This is the most consequential current fact in the section, and flhsmv.gov
is in transition between the two courses:

### DETS — for drivers under 18 (current rule)

- "As of August 1, 2025, individuals who are under 18 years old and have
  never held a driver license from any other state, country or jurisdiction
  must complete a 6-hour DETS course before applying for a license in
  Florida."
- DETS = Driver Education Traffic Safety, a 6-hour course approved by
  FLHSMV, meeting or exceeding the Florida Department of Education (FDOE) /
  Traffic Safety-Classroom 1900300 course version description.
- DELAP courses offered by some county school boards, and FDOE Traffic
  Safety Classroom 1900300 and 1900310 courses, may substitute. Contact the
  local school board for further information.
- The course can be delivered in person or online.
- Grandfathering — this change does NOT affect:
  - applicants under 18 who already hold a valid out-of-state license
    transferring to Florida;
  - individuals who already obtained a Florida learner's license prior to
    August 1, 2025;
  - individuals under 18 who completed the TLSAE course prior to August 1,
    2025 — grandfathered in and allowed to use their TLSAE course
    completion certificate for one year after the completion date.
  - Individuals under 18 who do not obtain a Florida driver license within
    that year will be required to take the new DETS course.
  - Individuals under 18 who complete a TLSAE course on or after
    August 1, 2025 will need to take the DETS course, unless enrolled in an
    FDOE Traffic Safety Classroom 1900300/1900310 course or a DELAP course.
- Authorized DETS providers listed on the page include, among others:
  Safe2Drive, $4 DETS by a NiSE Company, Defensive Driver Institute,
  DriversEd.com (IASI), Aceable, Florida Educational Driving School,
  DriveSafeToday, Florida Virtual School (FLVS), Driver Training
  Associates, OnlineDriversEd.com (DLC), Florida Online DETS,
  12 Dollar Cheap and Simple, Cheapest in Florida, Metro Traffic School,
  National Highway Safety Administration, DriverEducators.com,
  American Safety Council, 2Cool Traffic School, Spider Driver's Ed,
  $5 Dollar Traffic School, Get Drivers Education, American Safety
  Institute LLC, I Drive Safely, DetsCourse.com, Highway Traffic School,
  AAA Driver Training. (Full table with phone numbers is on the DETS page.)

### TLSAE — for drivers over 18 (and legacy)

- "Drivers who are over the age of 18 and have never held — or do not have
  in their possession — a driver license from any other state, country or
  jurisdiction, must complete a 4-hour Traffic Law and Substance Abuse
  Education (TLSAE) course before applying for a license in Florida."
- DELAP courses offered by some county school boards may substitute.
- "Drivers under 21 years of age who have received a notice of suspension
  for driving with a blood alcohol level (BAL) of .02 to .05 must complete
  a TLSAE course in order to reinstate their driver license on a hardship."
  A hardship license is restricted to "business" or "employment" purposes only.
- The Class E Knowledge Exam page still states the general rule:
  "Customers must complete a TLSAE course before applying for a license in
  Florida if they have never been issued a driver license in any state or
  country" — this is the older general wording; the DETS page is the
  authoritative current rule for under-18 applicants.
- All first-time drivers must take and pass the TLSAE course per the Driver
  Improvement Schools page, with DELAP/high-school driver education
  students exempt (DELAP teaches the drug and alcohol training).
- Approved TLSAE providers listed include, among others: American Safety
  Council, National Highway Safety Administration, Defensive Drivers
  Institute, Traffic Safety Institute, Drive Safe Inc., SPIDER Driver's Ed
  by IMPROV, Florida Association of DUI Programs, Drug Alcohol Traffic
  Awareness, Wise Traffic School, Online Traffic Education, Florida
  Educational Driving School, TLSAE by the National Institute for Safety
  Education, Deedal Studio, Driver Training Associates Inc., National
  Traffic Safety Institute, Safe2Drive, DriversEd.com, 4 Dollar Cheap and
  Simple, American Safety Institute LLC, South Florida Safety Program,
  DriverEducators.com LLC, 12 Dollar Florida Driver, Highway Traffic
  School, $5 Dollar Traffic School, Easy Florida Drivers Ed, I Drive
  Safely, DriveSafeToday, Online Drivers Ed, Aceable Drivers Ed for Mobile
  and Web, Too Cool Traffic School, Lowest Price Traffic School,
  CyberActive Inc., Best Price Traffic School, Cheapest in Florida,
  Get Drivers Education. (Full table with phone numbers is on the TLSAE page.)
- Course providers electronically report completions to FLHSMV; completion
  information is accessible at all driver license issuing offices.

## 4. Class E driver license — requirements (age 16)

Requirements for teens obtaining a Florida driver license:

- Must be at least 16 years old.
- Must hold learner's license for at least one year (12 months) OR reach
  age 18, whichever comes first.
- A parent, legal guardian, or responsible adult over 21 years old must
  complete the Certification of Minor Driving Experience Form, certifying
  the driver has 50 hours of driving experience, of which 10 hours must be
  at night. (FLHSMV provides a Practice Log Sheet to track the hours.)
- NO moving violation convictions for one year from learner's license date
  of issuance (OR may have one moving violation as long as adjudication
  was withheld).
- Must pass the Class E Driving Skills Test (see §6).
- Must provide documents needed to establish proof of identity, proof of
  Social Security number, and proof of residential address if not
  previously provided (flhsmv.gov/whattobring).
- After passing the Driving Skills Test, the customer may surrender their
  learner's license at their local service center to receive their Class E
  driver license.

### Curfews once licensed (Class E, under 18)

- Age 16: driving only allowed between 6 a.m. and 11 p.m., unless driving
  to or from work OR accompanied by a licensed driver 21+ (who occupies the
  front passenger seat, per the License Classes page).
- Age 17: driving only allowed between 5 a.m. and 1 a.m., unless driving to
  or from work OR accompanied by a licensed driver 21+.
- At 18, the GDL nighttime restrictions end (learner's hold also ends at
  the 18th birthday, whichever comes first).

### Passenger limits

- **No numeric passenger limit for teen drivers is stated anywhere on the
  flhsmv.gov teen pages studied.** Florida's GDL, as published by FLHSMV,
  restricts hours and supervision, not passenger count.
- The only passenger guidance on the Teen Drivers page is safety advice,
  not a legal limit: "Keep passengers at a minimum. Extra passengers can
  be distracting for an inexperienced teen driver. Never try to fit more
  people in the car than you have seat belts for them to use." And:
  "Always buckle up and make sure all your passengers buckle up, too."
- The one hard passenger rule in this section is the supervision rule:
  a learner must have a licensed driver 21+ in the front passenger seat,
  and a 16/17-year-old driving outside curfew hours must be accompanied by
  a licensed driver 21+ in the front passenger seat (or be driving to/from
  work).

## 5. Parental consent, parental control, and required forms

### Parental Consent Form (71142)

- Required for a minor child to obtain a learner's license.
- Step-parents may not sign unless they have legally adopted the minor child.
- Customers under 18 who are not married must have their parent or legal
  guardian sign their license application in front of the driver license
  examiner/agent or a notary public. Married minors must show a certified
  marriage certificate. Emancipated minors must show a certified court order.
- A foster parent, authorized representative of a residential group home,
  or a guardian ad litem may sign for the minor if the minor is enrolled
  in licensed out-of-home care.
- Related forms in the FLHSMV forms list: 71142C Non-Parent or Non-Legal
  Guardian Consent Form (Under 18 – Learner's License); 71142SP Spanish
  version.

### Parent can rescind / cancel the license

- "The parent or guardian who signs the Parental Consent Form can rescind
  responsibility for the minor's driving privilege and cancel their
  license." (Section 322.10, Florida Statutes.)
- To cancel: the signer must write a letter to FLHSMV requesting to
  withdraw consent, including the minor driver's complete name, date of
  birth, and driver license number. Mail or fax to:
  Department of Highway Safety and Motor Vehicles, Bureau of Motorist
  Compliance, Division of Motorist Services, 2900 Apalachee Parkway,
  Tallahassee, FL 32399-0575; Fax: (850) 617-3939.

### Other required forms for teens

- Parent/Guardian On-line Test Proctoring Form (71144): required if the
  minor completed the Class E Knowledge Exam online through a third party
  administrator. Must be completed and signed in the presence of a driver
  license examiner, or notarized if the parent/guardian will not be present.
  (Spanish: 71144SP.)
- Certification of Minor Driving Experience Form (71143): required for a
  minor to obtain a driver license. Must be completed and signed in the
  presence of a driver license examiner, or notarized if the parent/guardian
  or other responsible adult over 21 will not be present. Certifies at
  least 50 hours of driving experience, of which 10 hours were at night.
  (In the forms list, 71143 is titled "Parent Consent Form (Under 18 –
  Driving Test)"; Spanish: 71143SP.)

### Parental access to a minor's driving history

- Via Driver License Check: "Parents may also access the driving history
  of their child with this system."
- To access a child's (under 18) driving history: enter the teen's driver
  license number; after the record is retrieved, enter the last four digits
  of the driver's Social Security Number and the date of birth to view the
  driving history. (services.flhsmv.gov/DLCHECK/)

## 6. Testing requirements

### Class E Knowledge Exam (for the learner's license)

- 50 multiple-choice questions about Florida traffic laws, safe driving
  practices, and identifying traffic controls.
- To pass: answer 40 out of 50 correctly, i.e. score 80 percent.
- Available in Arabic, Chinese, English, Haitian Creole, Russian, and
  Spanish.
- Preparation: study the Official Florida Driver License Handbook and take
  the Class E Knowledge Practice Test.
- Testing options:
  - In person: at a service center.
  - Online/classroom: any applicant under 18 can take the Class E
    Knowledge Exam online through approved third party administrators.
    A Parent Proctoring Form is required for online tests, and must be
    notarized or signed in the presence of a driver license examiner.
    On passing through a registered third party administrator, exam
    information is automatically submitted to FLHSMV and available at all
    driver license offices.
  - DELAP: many high school driver education classes are authorized to
    provide the Class E Knowledge Exam through DELAP; results are entered
    into FLHSMV's test records by the driver education teacher. Contact
    the local high school to determine if it participates.
- Random mandatory re-test: Section 322.56(3)(b) and (e), Florida Statutes —
  a customer who passes the Class E Knowledge Exam or Driving Skills Test
  through an authorized third party administrator may be randomly selected
  for a no-fee mandatory re-test without prior notice. After a re-test with
  a passing score is completed in a driver license or tax collector office,
  the driver license will be issued. A failed mandatory re-test will
  require a re-exam fee at the next exam attempt.

### Class E Driving Skills Test (for the Class E license)

- To qualify: must hold the learner's license for one year (12 months)
  from the issuance date or must be 18 years old.
- Consists of a series of maneuvers to determine the applicant's ability
  to safely operate a motor vehicle.
- Testing options: at a service center; with a driver license exam provider
  or third party administrator (results auto-submitted to FLHSMV); or
  through DELAP high school driver education classes.
- Same random mandatory re-test rule applies (322.56(3)(b) and (e)).
- Test vehicle requirements: must have a valid registration, proof of
  insurance, and pass a basic vehicle inspection by the examiner. The test
  will NOT be given if the examiner finds: defective/inoperable horn,
  rear-view mirror, directional signals, steering wheel, brakes, tires,
  brake lights or tail lights; no windshield wipers on the driver's side;
  no operable headlights; cracked/broken glass hindering visibility;
  expired tag; vehicle has no doors; front doors do not open from inside
  and outside; vehicle does not have stationary seats; vehicle does not
  permit the driver to give hand signals when required; Jeep-type vehicles
  without framed canvas or metal doors held by hinges and door latch;
  does not meet bumper height requirements; or a low-speed vehicle
  (top speeds of 20–25 mph).
- No other passengers are permitted during the exam, unless a language
  interpreter is necessary.
- Maneuvers performed:
  - Three Point Turn — turn car around in a 20–40 foot space.
  - Approach of Crossing — get in the proper lane and look in each direction.
  - Yield Right-of-Way — allow pedestrians to cross, pull over and stop for
    emergency vehicles, don't enter an intersection where you will interfere
    with other traffic.
  - Straight-In Parking — vehicle centered inside the space, no part
    extending into the traffic lane.
  - Parking on a Grade — proper parking uphill and downhill, with and
    without a curb.
  - Stop Quickly — make a quick, safe stop when instructed.
  - Backing — back 50 feet at a slow speed while looking to the rear; do
    not use the rear-view mirror or rear-view camera monitor.
  - Obey Stop Signs — complete stop before the stop line or crosswalk.
  - Obey Traffic Signals — proper lane, approach at a speed allowing a stop.
  - Signal and Turn — signal the turn for the last 100 feet (hand or
    mechanical signals).
  - Passing — look ahead and behind to make sure passing is safe.
  - Stay in Proper Lane — drive in the right lane except on a one-way street.
  - Follow at a Safe Distance — minimum following distance of four seconds.
  - Use Proper Posture — both hands on the steering wheel, no elbow in the window.
- The examiner/agent explains any mistakes after the exam. Customers who
  fail are asked to study or practice before returning for a re-test.

### Vision and hearing tests

- Vision and hearing tests are conducted in a service center as part of
  the learner's license application. (The General Information page lists
  road rules, road signs, vision, and hearing exams for the learner's
  license; Class E adds the driving test.)

## 7. Traffic laws that apply specifically to minors — penalties

From "Traffic Laws for Florida Teens":

| Rule | Consequence | Statute |
|---|---|---|
| No moving violation convictions for one year from learner's license date of issuance | If the minor receives a moving traffic conviction while holding a learner's license, the one-year holding period is extended for one year from the date of the conviction or until age 18, whichever happens first | §322.161, F.S. |
| Compliance with school attendance | If the minor is not in compliance with school attendance, driving privilege can be suspended, or the minor may be ineligible to obtain a license until providing proof of having attended school for 30 consecutive days | §322.091, F.S. |
| Zero tolerance (under 21) | Blood alcohol level of .02% or more: license immediately suspended for 6 months. Second offense: 1-year suspension. Refusal to submit to testing: 12-month suspension (first offense), 18 months (second offense) | §322.2616, F.S. |
| 6+ points within 12 months | Driver license automatically restricted to "Business Purposes Only" for 12 months or until age 18, whichever happens first. Additional points during the restricted period extend the restriction 90 days for each additional point | (cited on page; see note below) |
| Parent rescinds consent | License canceled (see §5) | §322.10, F.S. |
| Convicted of tobacco / nicotine possession | Learner's license revoked for a minimum of 30 days | §322.056, F.S. |

Note: the "6+ points" item on the Traffic Laws page does not carry a
visible statute citation in the extracted text; the Teen Drivers page
states the same rule ("If teens get six or more points on their license
within 12 months, their license is restricted to 'Business Purposes Only'
for one year").

## 8. Fees (from the FLHSMV fee schedule)

- Original Class E license, **including learner's license: $48.00**.
- Renewal Class E: $48.00. Replacement license: $25.00. Late fee: $15.00.
- Endorsements: $7.00 each.
- Knowledge retest: $10.00. Skill retest: $20.00.
- An additional $6.25 service fee may apply to any credential issued in a
  tax collector office. (Veterans who provide / have provided evidence of
  veteran status are not charged the $6.25 service fee in a tax collector
  office for the asterisked transactions, which include Original Class E.)
- ID card (original, renewal, replacement): $25.00.
- Fees are established in Florida law; the full schedule is at
  https://www.flhsmv.gov/fees/

## 9. First-time driver rules (summary — under 18 vs 18+)

- **Under 18, never licensed anywhere:** 6-hour DETS course (since
  Aug 1, 2025; TLSAE completed before that date grandfathered for 1 year),
  parental consent, vision/hearing test, Class E Knowledge Exam (50
  questions, 80% to pass), learner's license at 15, 12-month hold + 50
  supervised hours (10 at night), no moving-violation convictions for a
  year, Class E Driving Skills Test, Class E license at 16.
- **18 or older, never licensed anywhere:** 4-hour TLSAE course before
  applying (per the TLSAE page and the Class E exam page).
- **Under 18 with a valid out-of-state license transferring to Florida:**
  DETS change does not apply; a new resident under 18 exchanging a valid
  out-of-state license is required to pass vision and hearing tests only
  (General Information page), with parental signature if under 18 and
  unmarried.
- DELAP / high-school driver education can substitute for the classroom
  course requirement and can administer both the Knowledge Exam and the
  Driving Skills Test.

## 10. Teen driver safety tips (Teen Drivers page — advice, not law)

- Before driving: always buckle up and make sure all passengers buckle up;
  keep passengers at a minimum; never fit more people than there are seat
  belts.
- The page also notes, in its safety-center context, that as of May 5, 2024
  over 205,000 Florida teens ages 15–19 were driving with a learner's
  license, and lists 2023 top teen citations including operating without
  proof of insurance (8,465), operating without a driver license (8,296),
  learner license violation (8,160), failure to display driver license
  (5,713), and operating with an obscured/defaced/no tag (4,875).
  (From the "100 Deadly Days of Summer" safety page, which republishes the
  teen licensing requirements.)

## Verification notes / gaps

- Direct `browser.open` reads succeeded for: the Driver Licenses & ID Cards
  hub, the A to Z Guide, Traffic Laws for Florida Teens, Class E Knowledge
  Exam & Driving Skills Test, Required Forms for Teens, the TLSAE providers
  page, and the DETS page.
- Direct `browser.open` returned HTTP 429 (rate limit) for: the teen
  parent page
  (`.../licensing-requirements-teens-graduated-driver-license-laws-driving-curfews`),
  the Teen Drivers page (`.../teen-drivers/`), the Fees page
  (`https://www.flhsmv.gov/fees/`), and the License Classes page. Facts
  attributed to those four pages above come from flhsmv.gov's own indexed
  search excerpts of those exact URLs, and are consistent across multiple
  independent excerpts (e.g. the GDL table appears identically on the parent
  page, the Teen Drivers page, and the Traffic Laws page, which WAS read
  directly). A live re-check of those four URLs is still worthwhile.
- No FLHSMV page studied states a numeric passenger limit for teen
  drivers; do not add one from other sources.
- The older Class E exam page still describes TLSAE as the universal
  first-time-driver course, while the newer DETS page (Aug 1, 2025 rule)
  and the current parent page require DETS for under-18 applicants. The
  DETS rule is the current one for teens; the TLSAE wording on the exam
  page appears not yet updated.
- The "Traffic Laws for Florida Teens" page spells the statute reference
  "Section 322.161, Florida Statutues" [sic] — typo is on the FLHSMV page.
# 05 — Mature / Senior Drivers (GrandDriver)

Section of the flhsmv.gov study. All facts below come from flhsmv.gov pages
opened directly with `browser.open` or from the search-indexed text of
flhsmv.gov pages, and are labeled as such. No fact is taken from a
third-party site. Where a figure (e.g. course hours) appears only in
provider or secondary material, it is flagged and kept out of the
FLHSMV-verified facts.

## 1. What "Mature Driver" and "GrandDriver" are on flhsmv.gov

- **Florida GrandDriver is the Mature Driver campaign.** The GrandDriver
  hub URL
  (`/driver-licenses-id-cards/florida-granddriver/`) resolves to the
  **Mature Driver** page; both URLs return the same text. The A-to-Z guide
  lists the topic under six separate entries: Elder Drivers, Florida
  GrandDriver, GrandDriver, Mature Drivers, Older Drivers, Senior Drivers.
- **Mature Driver page, verbatim summary:** "Mature Driver is an
  education and awareness campaign designed to educate the public about
  the effects of age on driving ability and to encourage drivers to make
  appropriate choices to maximize personal safety and the safety of
  Florida's communities."
- **Scope stated on the page:** "With the increase in Florida's
  population growth of drivers over 65, it is important to educate them,
  their caregivers, and medical professionals about the resources
  available for older drivers. The Department of Highway Safety and Motor
  Vehicles (FLHSMV) partners with other state agencies to promote
  information for and outreach to mature drivers to help them continue
  to drive safely. There are also resources for those looking to make a
  safe transition from driving."
- **Key age anchor on the page: 65.** The campaign is framed around the
  growth in drivers over 65. No other age threshold appears on the
  Mature Driver landing page itself.
- **No specific safe-driving tips list** appears in the text of the
  Mature Driver landing page as retrieved. The practical, tips-style
  content lives in the CarFit subpage (Section 5).

## 2. Mature Driver Discount course — insurance discount at 55+

Source: FLHSMV page "Mature Driver Discount Insurance Courses"
(`flhsmv.gov/ddl/mature_discount.html`), text as indexed in search;
direct open of this page was rate-limited (429) during this pass, see
Gaps.

- **Legal basis:** Section 627.0652, Florida Statutes.
- **Age:** drivers **55 years of age or older**.
- **What it is:** a Mature Driver (Senior Citizen) Discount course
  approved by FLHSMV. On successful completion the driver gives the
  completion certificate to their insurance company for an insurance
  discount.
- **Discount amount:** at the discretion of each insurance company.
  FLHSMV does not set a percentage.
- **Duration:** the discount "will typically last for three years as
  long as the driver" meets the conditions (the indexed text cuts off
  at that clause; the standard statutory conditions are no at-fault
  accident and no moving-violation conviction — see note below).
- **Approved providers listed on the FLHSMV page** (partial list as
  indexed): National Safety Council – Coaching the Mature Driver;
  AARP Driver Safety Program; AAA – Safe Driving for Mature Operators;
  American Safety Council; American Safety Institute, LLC – Senior
  Driving Course; I Drive Safely – Online Mature Driver Course;
  Traffic Safety Institute; DriverEducators.com; DriveSafeOnline.org
  Florida Mature Driver Course; Road Review; Wise Traffic School;
  Defensive Drivers Institute; Cheap Mature Driver; $4 Mature Driver
  by A NiSE Co; $5 Dollar Traffic School; 10 Dollar Florida Senior;
  Online Mature Driver by Improv Comedy Club; Traffic School Online –
  Mature Driver; Florida Educational Driving School Online Senior
  Driver Discount Course; Defensive Drivers Discount (Broward,
  Hillsborough, Miami-Dade, Orange and Palm Beach counties).
- **Corroboration from FLHSMV's Education & Courses page** (indexed
  text; direct open rate-limited): "An insurance discount can be
  available for those who are over 55 years old and take the Mature
  Driver Discount course."
- **Course hours — NOT stated on the FLHSMV pages retrieved.**
  FLHSMV-approved providers describe the course as about 6 hours,
  self-paced. Treat "6 hours" as a provider figure, not an FLHSMV
  figure, until the FLHSMV discount page is opened directly.
- **FLHSMV course cost:** no price is stated on the FLHSMV pages
  retrieved; providers set their own prices.

## 3. Vision testing for older drivers

Source: FLHSMV "Vision Standards" page (`flhsmv.gov/vision/`), opened
directly. The A-to-Z "Bad Driver, Reporting" link also resolves to
this same Vision Standards page.

### Minimum vision standards (apply to all ages)

- Minimum visual acuity: **20/70 in either eye or both eyes together,
  with or without corrective lenses** (if vision cannot be improved).
- If one eye is blind or **20/200 or worse**, the other eye must be
  **20/40 or better**.
- Minimum horizontal field of vision: **130 degrees** uninterrupted.
  Applicants below that must submit a Goldmann Kinetic III-4e (or
  equivalent) or a Humphrey Esterman program field chart.
- **Telescopic lenses are not permitted** to meet Florida minimum
  vision requirements, regardless of the acuity reading. Customers
  wearing telescopic lenses are issued a field revocation order for
  "inadequate vision."

### Age-80 vision rule

- **Drivers over 80 years of age** must submit FLHSMV Vision
  Examination **Form 72119** (Mature Driver Vision Test) when renewing
  their driver license, **or** take the vision test at their local
  driver license office.
- Form 72119 must be completed by a **Florida licensed physician** or
  by a licensed physician at a **federally established veterans'
  hospital**.
- At an office, the vision test is given at **no additional charge**
  (per the renewal-80 guidance summarized from FLHSMV; the Vision
  Standards page itself states the office-test option without a fee
  figure).

### Report of Eye Exam — Form 72010

- Used when a driver has **not met minimum Florida vision standards**,
  or is eligible to renew by mail but must provide proof of meeting
  minimum standards.
- If visual acuity is **20/50 or worse in either eye** (with or
  without corrective lenses), the eye specialist must complete Form
  72010.
- The exam may be done by a licensed ophthalmologist, optometrist, or
  physician.

## 4. Renewal rules for seniors

Sources: FLHSMV "Driver Licenses & ID Cards" hub and "Renew or
Replace Your Florida Driver License or ID Card" pages, opened
directly; FLHSMV Vision Standards page; Florida Statute s. 322.18
for the age-80 term (see sourcing note).

- **Standard renewal period: every eight years.** "Customers must
  renew their Florida driver license or ID card every eight years.
  The expiration date is listed on the credential."
- **Renew early:** driver license holders may renew **up to 18 months
  in advance** of the expiration date; ID card holders 12 months in
  advance.
- **Age 80 renewal period: six years.** Under s. 322.18, F.S., a
  licensee who is at least 80 at renewal is issued a license expiring
  6 years after the month of expiration of the license being renewed
  (vs. 8 years for those under 80). FLHSMV's own renewal-80 summary
  states the same split (79 and younger: 8 years; age 80: 6 years).
  *Sourcing note: the dedicated FLHSMV page "Renewing – Age 80 &
  Older – Vision Requirements" (listed in the A-to-Z guide) was not
  directly opened in this pass; the 6-year figure is confirmed by the
  statute text and by FLHSMV's summary as quoted in secondary
  coverage. Re-open that FLHSMV page to close the gap.*
- **Vision test at every renewal from age 80.** Drivers 80 and older
  must pass a vision test at each renewal — at a driver license office
  or, for online/mail renewal, by submitting Form 72119 completed by
  a Florida-licensed physician/optometrist or VA physician.
  (FLHSMV Vision Standards page; s. 322.18(5).)
- **Online renewal is every other renewal period.** "Florida offers
  an online convenience renewal service for customers every other
  renewal period." A customer must go into an office if they used the
  online convenience service on their last renewal.
- **MyDMV Portal:** online renewals arrive by mail within **2–3
  weeks**; a **$2.00 processing fee** is assessed per online
  transaction.
- **No senior-specific renewal fee** appears on the FLHSMV pages
  studied; the renew page refers readers to the fees page for amounts.
- **No road test or written test at renewal** is required by any
  FLHSMV page studied. No FLHSMV page in this section mentions a
  driving test as part of a standard senior renewal; re-examination
  arises only through the Medical Review process (Section 6).

## 5. Safe-driving resources for older drivers — CarFit

Source: FLHSMV "CarFit for Older Drivers" page
(`/driver-licenses-id-cards/mature-driver/carfit-older-drivers/`),
opened directly.

- **What it is:** an educational program developed by the **American
  Society on Aging** in collaboration with **AAA, AARP and the
  American Occupational Therapy Association**. It lets older adults
  check how well their personal vehicles "fit" them.
- **Why it matters (FLHSMV text):** "As we age, changes in our
  vision, flexibility, strength, range of motion and even height may
  make us less comfortable and reduce our control behind the wheel."
- **How it works:** drivers find a Florida CarFit event and schedule
  an appointment online or by phone. At the event a team of trained
  technicians and/or health professionals works with the driver while
  the driver stays in the car. **CarFit staff will not make any
  changes to the driver's personal vehicle**, though they may
  recommend adjustments.
- **Time:** a CarFit event takes **about 30 minutes** from drive-in
  to departure.
- **Checklist covered at a CarFit check-up:**
  - a clear line of sight over the steering wheel;
  - distance between the driver and the steering wheel;
  - seat comfort;
  - properly adjusted head restraints;
  - access and ease of use between gas and brake pedals;
  - proper adjustment and comfort of seatbelt.
- The program also provides information on community-specific
  resources that can enhance safety as a driver and/or increase
  mobility in the community.

## 6. When a license review can be requested — Medical Review

### Who can report, and on what basis

Sources: FLHSMV "Medical Review" hub and "Report An Unsafe Driver"
pages, opened directly.

- **Mission:** "The mission of the Medical Review program is not to
  prevent an individual with a medical condition from driving, but to
  assure the condition does not interfere with the safe operation of a
  motor vehicle."
- **Any physician, person, or agency** may report an applicant or
  licensed driver who may not safely operate a motor vehicle due to a
  medical condition. FLHSMV also receives referrals from courts,
  doctors, law enforcement, other state agencies, driver license
  personnel, and concerned relatives or citizens.
- **Referrals must be based on medical conditions or symptoms that
  could affect safe driving — not the age of the driver.** Age alone
  is not a basis for a report.
- **Report requirements:** the report must be made **in writing**,
  giving the **full name, date of birth, address, and a full
  description of the alleged physical or mental disability** that
  could affect driving ability, for any person **over 15 years of
  age**. "If information is missing or not included it will
  invalidate the form."
- **Form:** the **Medical Referral Form (HSMV 72190, English /
  72190sp Spanish)** should be used.
- **Confidentiality and immunity:** medical reporting is confidential
  under **section 322.126, Florida Statutes**, and "no civil or
  criminal action may be brought against any physician, person, or
  agency for providing this information." Reports are used only to
  determine the qualifications of the individual to operate a motor
  vehicle.

### The review process and timelines

Source: FLHSMV "The Medical Review Process" page
(`/driver-licenses-id-cards/florida-granddriver/medical-reporting-medical-review-process/`),
opened directly.

1. FLHSMV receives notification from a court, doctor, law
   enforcement, another state agency, or a concerned relative or
   citizen; a decision is made whether to initiate a review.
2. If questionable, an investigation is performed to assure the
   validity of the complaint.
3. If a review is necessary, the driver is **notified in writing**
   that they are under medical review and must provide medical
   information from their physician **within 45 days**.
4. The medical information is forwarded to the **Medical Advisory
   Board** for review and recommendation.
5. If approved, the driver may be required to take a **re-examination**
   and/or submit a **follow-up medical report** as a condition of
   licensure.
6. If the driver has a medical condition that affects safe operation
   and records indicate a risk to public safety, the driving
   privilege will be denied.
7. **Decision deadline:** Florida law requires FLHSMV's decision to
   be rendered **within 90 days of receipt of all requested medical
   information** from the applicant or licensed driver. The driver is
   then notified in writing.
8. **Reconsideration:** the driver may, at any time, provide
   additional or updated medical information or a **Certified Driver
   Evaluation by a Certified Driver Rehabilitation Specialist** for
   reconsideration by the board.

### Medical Review Program contact (from HSMV Form 72190)

- Bureau of Motorist Compliance, Medical Review Program, Neil
  Kirkman Building, MS 86, Tallahassee, Florida 32399-0500.
- Telephone: (850) 617-3814. Fax: (850) 617-3944.
- Form 72190 lists these conditions as check-boxes: seizures, severe
  cardiac condition, stroke, loss of consciousness, uncontrollable
  diabetes, dementia/memory deficits, psychiatric disturbance,
  drug/alcohol addiction, severe visual deficit, sleep disorder, other.

## 7. Forms for older drivers

Source: FLHSMV "Forms for Older Drivers" page
(`/driver-licenses-id-cards/florida-granddriver/forms-for-older-drivers/`),
text as indexed in search; direct open was rate-limited (429) in
this pass.

| Form | Use (FLHSMV wording) |
|---|---|
| **HSMV 72190** (English) / **72190sp** (Spanish) — Medical Reporting Form | Report a driver whose ability is questionable. |
| **HSMV 72119** — Mature Driver Vision Test | Drivers over 80 must submit this vision examination form when they renew. |
| **HSMV 72010** (English) — Report of Eye Exam | Use when you have not met minimum Florida vision standards, or are eligible to renew by mail but must provide proof of meeting minimum standards. |

## 8. Pages studied

| # | Page | URL | How read | Last crawl shown |
|---|---|---|---|---|
| 1 | Driver Licenses & ID Cards (hub) | https://www.flhsmv.gov/driver-licenses-id-cards/ | Opened directly | 2026-10-29 |
| 2 | A to Z Guide | https://flhsmv.gov/a-to-z-guide/ | Opened directly | 2026-11-04 |
| 3 | Mature Driver | https://www.flhsmv.gov/driver-licenses-id-cards/mature-driver/ | Opened directly | 2026-01-16 |
| 4 | Florida GrandDriver (hub) | https://www.flhsmv.gov/driver-licenses-id-cards/florida-granddriver/ | Opened directly — resolves to Mature Driver page, same text | 2025-06-08 |
| 5 | CarFit for Older Drivers | https://www.flhsmv.gov/driver-licenses-id-cards/mature-driver/carfit-older-drivers/ | Opened directly | 2026-01-16 |
| 6 | Vision Standards | http://www.flhsmv.gov/vision/ | Opened directly | 2026-01-05 |
| 7 | Vision Standards (alt URL) | https://www.flhsmv.gov/driver-licenses-id-cards/general-information/medical-visual-problems/ | Opened directly — same Vision Standards text | 2025-05-31 |
| 8 | Medical Review (hub) | https://www.flhsmv.gov/driver-licenses-id-cards/medical-review/ | Opened directly | 2026-06-16 |
| 9 | Report An Unsafe Driver | https://www.flhsmv.gov/driver-licenses-id-cards/medical-review/report-an-unsafe-driver/ | Opened directly | 2026-01-15 |
| 10 | The Medical Review Process | https://www.flhsmv.gov/driver-licenses-id-cards/florida-granddriver/medical-reporting-medical-review-process/ | Opened directly | 2026-01-14 |
| 11 | Renew or Replace Your Florida Driver License or ID Card | https://www.flhsmv.gov/driver-licenses-id-cards/renew-or-replace-your-florida-driver-license-or-id-card/ | Opened directly | 2026-01-16 |
| 12 | Mature Driver Discount Insurance Courses | http://www.flhsmv.gov/ddl/mature_discount.html | Search-indexed FLHSMV text only (direct open rate-limited) | Indexed, last crawl ~341 days before retrieval |
| 13 | Forms for Older Drivers | http://www.flhsmv.gov/driver-licenses-id-cards/florida-granddriver/forms-for-older-drivers/ | Search-indexed FLHSMV text only (direct open rate-limited) | Indexed, last crawl ~315 days before retrieval |
| 14 | Education & Courses | https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/ | Search-indexed FLHSMV text only (direct open rate-limited) | Indexed, last crawl ~25 days before retrieval |

A-to-Z entries that point into this section: Elder Drivers,
Florida GrandDriver, GrandDriver, Mature Drivers, Older Drivers,
Senior Drivers, Renewing – Age 80 & Older – Vision Requirements,
Bad Driver (Reporting), Vision (Driver License).

## 9. Key facts at a glance

- **55+**: eligible for the Mature Driver Discount course; insurance
  discount at insurer's discretion, typically 3 years (s. 627.0652,
  F.S.).
- **65+**: the population the Mature Driver / GrandDriver campaign is
  framed around.
- **80+**: license renews every **6 years** (vs. 8 years under 80);
  **vision test at every renewal**; Form 72119 or office vision test.
- **Vision floor:** 20/70 either eye or both together; 20/40 in the
  good eye if the other is blind/20/200 or worse; 130° field of
  vision; no telescopic lenses.
- **Renewal timing:** up to 18 months early; online renewal every
  other cycle; MyDMV Portal $2.00 fee, credential in 2–3 weeks.
- **Medical review:** anyone (physician, person, agency) may report
  in writing on Form 72190 — but only on medical condition/symptoms,
  never age alone; report is confidential under s. 322.126, F.S.
- **Review clock:** driver has **45 days** to supply physician
  information; FLHSMV must decide within **90 days** of receiving all
  requested medical information.
- **CarFit:** free vehicle-fit check for older drivers, ~30 minutes,
  six-point checklist, staff make no changes to the vehicle.

## 10. Gaps and items not verified in this pass

- Three FLHSMV pages were read only from search-indexed text because
  direct opens hit the fetcher's rate limit (429) and were not
  retried: the Mature Driver Discount page, Forms for Older Drivers,
  and Education & Courses. Re-open directly to confirm current text,
  the full discount-duration conditions, and the approved-provider
  table.
- The dedicated FLHSMV page "Renewing – Age 80 & Older – Vision
  Requirements" (A-to-Z entry) was not located by a verbatim URL in
  this pass and was not opened; the 6-year term is confirmed via
  s. 322.18, F.S., and FLHSMV's summary as quoted elsewhere, but the
  FLHSMV page itself should be opened to close this.
- Course length ("about 6 hours") and discount percentages (often
  quoted as 5–10% or 3–10%) come from providers/secondary sources,
  not from any FLHSMV page retrieved; FLHSMV states only that the
  amount is at each insurer's discretion.
- No FLHSMV page studied states a renewal fee figure for seniors or
  any senior fee discount; the renew page defers to the fees page.
- The Mature Driver landing page carries no itemized safe-driving
  tips list; CarFit is the only hands-on safety program page found
  under Mature Driver in this pass.
- No FLHSMV page studied gives a phone number for the GrandDriver
  program itself; the only program phone captured is the Medical
  Review Program's (850) 617-3814.
# 06 — Commercial Driving (CDL) — flhsmv.gov

**Study date:** 2026-11-23
**Scope:** Commercial Driver Licenses, CDL Requirements, CDL Handbook, CDL Medical Certification, CDL Medical Self-Certification, Commercial Motor Carriers, IFTA, IRP, Commercial Vehicle Enforcement.
**Source rule:** Facts below are only those stated on flhsmv.gov pages (full-page reads or FLHSMV search-indexed text). Where FLHSMV did not state a figure on the pages studied, that is recorded as **not found on FLHSMV**, not filled in from FMCSA or other sources.

**Method / access note:** The two starting pages were read in full. The main CDL page, Commercial Motor Vehicle Drivers hub, CDL Enforcement page, and License Classes page were read in full via browser.open. Direct browser.open attempts for the CDL Medical Certification page, the Fees page, the Hazmat page, and the IRP page failed at the time of study (one 403, then 429 rate-limiting) and were **not** retried, per instruction. Facts for those four topics below therefore come from FLHSMV text returned by site-restricted search (flhsmv.gov snippets), not from a full page read, and are marked as such. A live-browser re-check is recommended for those four pages before relying on them.

---

## 1. What counts as a Commercial Motor Vehicle (CMV)

From the CDL Enforcement page, citing s. 322.01, Florida Statutes:

> "Commercial motor vehicle" means any motor vehicle or motor vehicle combination used on the streets or highways, which:
> 1. Has a gross vehicle weight rating of **26,001 pounds or more**;
> 2. Is designed to transport **more than 15 persons, including the driver**; or
> 3. Is transporting hazardous materials and is required to be placarded in accordance with 49 C.F.R. part 172, subpart F.

Note the passenger threshold differs by context on FLHSMV pages: the CMV definition and Class C description use "more than 15 persons including the driver" in some places and "16 or more people including the driver" in others (see §3). Both formulations appear on FLHSMV; they describe the same boundary (16+).

## 2. Who must hold a CDL — s. 322.54, Florida Statutes

From the CDL Enforcement page:

- **Class A:** any person who drives a motor vehicle combination having a GVWR or GVW of **26,001 pounds or more**, if the GVWR/GVW of the vehicle being towed is **more than 10,000 pounds**. A valid Class A holder may, subject to restrictions and endorsements, drive any class of motor vehicle in Florida.
- **Class B:** any person (except a Class A holder) who drives a motor vehicle having a GVWR or GVW of **26,001 pounds or more**. This includes towing a vehicle of 10,000 pounds or less. A valid Class B holder may, subject to restrictions and endorsements, drive any class except the type for which a Class A is required.
- **Class C:** any person (except a Class A or B holder) who drives a motor vehicle with a GVWR of **less than 26,001 pounds** and who is required to obtain an endorsement under s. 322.57(1)(b), (1)(c), or (1)(e). A valid Class C holder may, subject to restrictions and endorsements, drive any class except the types for which a Class A or B is required.

## 3. CDL classes A / B / C

From the Commercial Driver License page and the License Classes, Endorsements & Designations page:

| Class | FLHSMV definition |
|---|---|
| **A** | Trucks or truck combinations with a GVWR of **26,001 lbs or more**, provided the towed vehicle/unit is **more than 10,000 lbs**. |
| **B** | Straight trucks (and buses) with a GVWR of **26,001 lbs or more**. |
| **C** | Vehicles transporting placardable amounts of hazardous materials, **or** vehicles designed to transport **16 or more people including the driver** (elsewhere: "more than 15 persons including the driver"), with a GVWR of **less than 26,001 lbs**. |

## 4. Basic eligibility — "Do I need a CDL?"

From the Commercial Driver License page and the Commercial Motor Vehicle Drivers hub:

- All CDL applicants are required to have an **Operator's License**, pass the **vision requirements**, and pass **knowledge and skills tests**.
- Applicants must be **at least 18 years of age**. If under 21, they are **restricted to intrastate operation only**.
- Applicants must be a **Florida resident**.
- **Proof of Florida residency for CLP and CDL applicants** — an original CDL or Commercial Learner's Permit (CLP) applicant must present **one** of:
  - A current Florida Class E Driver License or Florida ID card held for **more than six (6) consecutive months**;
  - A lease agreement in the customer's name in place for **more than six (6) consecutive months**;
  - A current residential mortgage in the customer's name, signed **more than six (6) months ago**;
  - A current residential deed in the customer's name, signed **more than six (6) months ago**;
  - A Florida Voter Registration Card;
  - A statement of domicile pursuant to s. 222.17, F.S.;
  - A homestead tax exemption filing on property in this state.
- **Knowledge tests** are offered in multiple languages and may be taken orally in English or Spanish, **with the exception of the hazardous materials test**. **Skills tests must be conducted in English. Interpreters may not be used** during the administration of any tests.
- **CDL expired for one year or more:** customers with CDL licenses expired for one year or more will be required to complete and pass **all applicable CDL knowledge and skills exams** to obtain a new "Original" CDL.

### Out-of-state and military CDLs

- Florida will **reciprocate an out-of-state or a Canadian** commercial driver license. However, an out-of-state applicant with a hazmat endorsement will have to **reapply for a hazmat endorsement**, including a background check, appropriate tests and fees.
- **Military / prior military:** to be issued a CDL on military experience, the customer must (a) pass all required knowledge and endorsement tests for the class/endorsements applied for, and (b) present the **Certification for Waiver of Skill Test for Military Personnel** form completed by their commanding officer or designee while on active duty or **within 90 days of separation** from service, to be exempt from skills tests. The process must be completed and the CDL issued **within 120 days of separation** from service.

## 5. Entry Level Driver Training (ELDT) — effective February 7, 2022

From the Commercial Driver License page (FMCSA ELDT notice):

- Effective **February 7, 2022**, FMCSA Entry Level Driver Training regulations set the baseline training requirements for entry-level commercial drivers. Training requirements must be **verified prior to taking a skills test**, except for drivers taking the knowledge exam to obtain a hazardous materials endorsement for the first time, in which case requirements must be verified **prior to taking the exam**.
- ELDT applies to those applying to:
  - Obtain a **Class A or Class B CDL for the first time**;
  - **Upgrade an existing Class B CDL to a Class A CDL**; or
  - Obtain a **School Bus (S), Passenger (P), or Hazardous Materials (H) endorsement for the first time**.
- If a driver holds a CLP issued **before February 7, 2022**, ELDT is not required as long as the driver obtains a CDL **before the CLP expires**.
- Florida will allow applicants to be **scheduled** for a CDL skills test before completing ELDT / before the Training Provider Registry (TPR) is updated, but the ELDT requirements **must be met before taking the test**.

## 6. Endorsements

From the Commercial Driver License page ("What are Endorsements?") and the License Classes page. An endorsement is a special authorization permitting a driver to drive certain types of vehicles, transport certain types of property, or a certain number of passengers. The following can be placed on Class A, B, or C CDLs:

| Code | Endorsement | FLHSMV description |
|---|---|---|
| **H** | Placarded Hazmat | Passed the required written test; will transport placarded hazardous materials. |
| **N** | Tank Vehicles | Passed the required written test; will drive tank vehicles. License Classes page: tank vehicle designed to transport any liquid or gaseous material with designed capacity of **1,000 gallons or more**. |
| **P** | Passengers | Passed the required written **and skills** test; will drive passenger vehicles. A passenger vehicle is any vehicle designed to transport **more than 15 persons including the driver**. |
| **S** | School Bus | Passed the required written **and skills** test; will transport pre-primary, primary or secondary school students from home to school, from school to home, or to and from school-sponsored events (does not include a bus used as a common carrier). The **P endorsement is also required**. |
| **T** | Double/Triple Trailers | Passed the required written test; will drive double or triple tractor-trailer vehicles. **Triple trailers are not allowed on Florida roads.** |
| **X** | Placarded Hazmat & Tank Vehicles | Issued to those who qualify for **both H and N**. |

## 7. CDL restrictions (selected, CDL-relevant)

From the License Classes, Endorsements & Designations page (current standard, added on/after 2019, with pre-2019 code in parentheses):

- **L** (was 1) — No Air Brake Equipped CMV: restricts a CDL holder from operating any commercial vehicle with air brakes.
- **K** (was 2) — CDL Intrastate Only: the CDL holder is limited to operating a commercial vehicle **within the state of Florida**.
- **O** (was 5) — No Tractor-Trailer CMV: restricts a CDL holder from operating a Class A tractor-trailer vehicle.
- **M** (was 6) — No Class A Passenger Vehicle.
- **N** (was 7) — No Class A or B Passenger Vehicle.
- **Q** — No Class A School Bus Vehicle.
- **R** — No Class A or B School Bus Vehicle.
- **9** (was K) — Hearing Aid (CDL): driver must wear a hearing aid during operation.
- No longer issued as of **10/06/17**: (CDL) Bus Only (was 3); CMV < 26,001 lbs GVWR (was 4). These remain valid on previously issued credentials but are no longer added to new issuances.

## 8. Exemptions from the CDL requirement — s. 322.53, Florida Statutes

From the CDL Enforcement page and the License Classes page (wording varies slightly between the two pages; both lists are reproduced here):

- Drivers of **authorized emergency vehicles** (License Classes page: equipped with extraordinary audible warning devices that display red or blue lights and on call to respond to emergencies).
- **Military personnel** driving vehicles operated for military purposes / military vehicles.
- **Farmers** transporting agricultural products, farm supplies, or farm machinery to or from their farms and **within 150 miles of their farms**, if the vehicle is not used in the operations of a common or contract motor carrier (License Classes page: transporting farm supplies or farm machinery, or agricultural products to or from the first place of storage or processing or directly to or from market, within 150 miles of their farm).
- Drivers of **covered farm vehicles**, as defined in s. 316.003, F.S., if operated in accordance with s. 316.302(3), F.S.
- Drivers of **recreational vehicles**, as defined in s. 320.01, F.S. (License Classes page: recreational vehicles used for recreational purposes).
- Drivers who operate **straight trucks** (single units), as defined in s. 316.003, F.S., and who are transporting **exclusively their own tangible personal property, which is not for sale**.
- **Employees of a publicly owned transit system** limited to moving vehicles for maintenance or parking purposes exclusively within the restricted-access confines of a transit system's property.

Note: farmers and drivers of authorized emergency vehicles who are exempt from a CDL must obtain a **Class E** driver license (License Classes page).

### Covered Farm Vehicles (CVE page)

From the Covered Farm Vehicles page (via search): as of **July 1, 2019**, Florida adopted FMCSA regulatory exemptions for Covered Farm Vehicles and their drivers. A straight truck or articulated (combination) CMV is a Covered Farm Vehicle when operated per 49 CFR 390.5 and 390.39 (interstate) and ss. 316.003(15) and 316.302(3), F.S. (intrastate). Eligibility requires, among other things: transporting agricultural commodities, livestock, machinery, or supplies to/from a farm or ranch; if GVW/GVWR (whichever greater) is **26,001 pounds or less**, anywhere in Florida or the US; if **more than 26,001 pounds**, anywhere in Florida and, across state lines, only **within 150 air miles** of the farm/ranch; operated by the farm/ranch owner/operator, employee, or family member; always carrying a Covered Farm Vehicle designation certificate; not transporting placardable hazmat; not in for-hire motor carrier operation.

## 9. Testing requirements by class

From the Commercial Driver License page (knowledge + skills per class) and the General Information page (exam detail):

**All classes — skills tests:** Pre-trip Vehicle Inspection; Basic Vehicle Control; On-road Test.

| Class | Knowledge tests | Skills tests |
|---|---|---|
| **A** | General Knowledge; Combination Vehicles; Air Brakes (if applicable — most Class A vehicles are equipped with air brakes but not all); applicable endorsement exams | Pre-trip; Basic Vehicle Control; On-road |
| **B** | General Knowledge; Air Brakes (if applicable); applicable endorsement exams | Pre-trip; Basic Vehicle Control; On-road |
| **C** | General Knowledge; Air Brakes (if applicable); applicable endorsement exams | Pre-trip; Basic Vehicle Control; On-road |

General Information page, Class A exam detail: minimum age 18; General Knowledge test; Combinations vehicle test; Air brakes; applicable endorsement exams; **Vision — 20/40 in each eye**; **Hearing — must hear a whisper**; Pre-trip; Basic skills; Driving. Note: drivers under 21 restricted to intrastate operation only.

FLHSMV notes the CDL is "a professional license with more testing requirements than other licenses" and advises applicants to obtain a study manual before testing. Handbooks (driver, motorcycle, CDL) are available at local driver license service centers at **no charge** and may be returned for re-use; digital copies via the Handbooks and Manuals page.

## 10. CDL Handbook

- The A to Z Guide lists **CDL Handbook** under C, linking to the FLHSMV Handbooks and Manuals (resource-center/handbooks-manuals) page.
- The Commercial Driver License page directs applicants to "Review the CDL Handbook."
- **Not verified in this study:** the handbook's contents, edition date, or PDF URL were not opened/read (the handbooks page itself was not among the pages successfully opened). Do not cite handbook contents from this study.

## 11. Medical certification and self-certification

*Source status: the CDL Medical Certification page itself returned 403 on direct open; facts below are from FLHSMV text returned by site-restricted search for that page, plus the CDL Self-Certification System page (services.flhsmv.gov/CDLMedCert). Re-verify by full page read.*

From the FLHSMV "CDL Medical Information" page:

- Federal Motor Carrier Safety Regulations require **all** CDL holders to certify with the State's Driver License Agency in **one of the four categories** below **prior to the issuance or renewal of a CDL**.
- Those certifying in **non-excepted interstate or non-excepted intrastate** commerce (**Category A or C**) must also ensure their **medical examiner certificate (Med Card) is on file** with the state issuing agency and that it **remains current**.
- **Failure to maintain a valid Med Card will result in denial of issuance or renewal of the CDL. Failure to maintain a current valid Med Card on file may result in CDL disqualification.**
- **NOTE: The requirement for the Medical Examiner to transmit DOT Medical Exam information electronically took effect on June 23, 2025.**

### The four self-certification categories

1. **Category A — Non-excepted Interstate:** I operate or expect to operate in interstate commerce and am required to maintain federal medical certification. **(Med Card Required)**
2. **Category B — Excepted Interstate:** I operate or expect to operate in interstate commerce, but engage exclusively in operations that qualify for exception from the requirement to maintain federal medical certification.
3. **Category C — Non-excepted Intrastate:** I operate or expect to operate only in intrastate commerce and am required to meet State of Florida medical certification requirements. **(Med Card Required)**
4. **Category D — Excepted Intrastate:** I operate or expect to operate only in intrastate commerce, but engage exclusively in operations that qualify for exception from State of Florida medical certification requirements.

### Key rules stated on the page

- CDL holders **can no longer claim exemption** from medical certification requirements because they are not currently operating in non-excepted interstate or intrastate commerce. If not specifically included in Category B or D, they **must maintain their medical certification or downgrade to a non-commercial license**.
- If you self-certify in an exempt category (B or D) and later change to a non-exempt type of operation (A or C), you **must recertify** in the appropriate category.
- Drivers **not eligible to certify in Category A** include drivers **under 21** and drivers with certain medical conditions who do not have a federally issued medical variance. Drivers self-certifying in Category C who are not eligible for Category A will have **restrictions to intrastate commerce** placed on their CDL.
- FAQ: "I recently renewed my license and was required to provide medical certification at that time. My CDL is valid until 2022, but my Med Card expires in 2019. Will I be required to submit a new Med Card before my next renewal?" — **Yes.** You are required to maintain current medical documentation on file. Failure to do so may result in CDL disqualification.
- FAQ: Once the Med Card is provided to the driver license agency, will the driver still need to carry it? — **No.** Once the medical provider has submitted the Med Card electronically to FMCSA, the driver is not required to carry a Med Card. FLHSMV suggests carrying it for **at least 15 days** after submission to ensure the driver record has been updated.
- All CDL holders required to have a valid medical certificate must comply with Part 383; the regulations provide **no exceptions to service members on active deployment**.

### Medical exam interval — NOT stated on FLHSMV pages studied

No FLHSMV page studied in this section states a medical exam / Med Card validity interval (e.g. 2 years / 24 months). FLHSMV states only that the Med Card must be kept **current** and on file. Do **not** attribute a 2-year interval to FLHSMV from this study.

### Self-certification online

- The A to Z Guide lists **CDL Medical Self-Certification Online**, linking to **services.flhsmv.gov/CDLMedCert/**.
- The CDL Self-Certification System page states the system allows CDL holders to meet the federal self-certification requirements **without needing to go to a driver license office**, and may be used only if the holder has a **valid Florida CDL** (if unsure, check Driver License Check first).

### CDL Help Desk (medical)

From a 2019 FLHSMV technical advisory (DL19-021 / RS/TL19-016, Hurricane Dorian relief): customers with CDL disqualifications for "Failed to File Medical Certification" were directed to the **CDL Helpdesk at (850) 617-2581** (fee-waiver review) and **(850) 617-2606** (expedited medical certification processing). These numbers are from that advisory; the Contact Us page separately lists **Customer Service (CDL Help Desk) 850-617-2606**.

## 12. Hazmat endorsement

*Source status: the Hazmat Information page returned 429 on direct open; facts below are from FLHSMV text returned by site-restricted search. Re-verify by full page read.*

- The federal **USA PATRIOT Act** requires CDL holders to pass a **national background check administered by the Department of Homeland Security, Transportation Security Administration (TSA)** before their licenses may be endorsed for transport of hazardous materials.
- **Fingerprinting and the application process:** an application fee of **$91** will be charged to cover costs of the background check process, **in addition to** the standard issuance fee for the CDL and for each endorsement.
- FLHSMV provides an online check for **Pending Hazmat Endorsement Applications** and a list of hazmat fingerprinting locations by county.
- Out-of-state applicants with a hazmat endorsement must reapply for it (background check, tests, fees) — see §4.

## 13. Disqualifications

### What FLHSMV pages studied actually state

- **Failure to maintain a current valid Med Card on file may result in CDL disqualification** (CDL Medical Information page; also the FAQ answer above).
- The Fees page lists a **Disqualification** fee of **$75.00** (see §14) — this is the reinstatement/administrative fee associated with a disqualification, as listed in the fee schedule.
- A 2019 technical advisory references CDL disqualifications effective August 30, 2019 or after for **"Failed to File Medical Certification"**, with a reinstatement-fee waiver available on review by the CDL Helpdesk in the Dorian-relief circumstances.

### Disqualification periods — NOT found on FLHSMV pages studied

**No disqualification period (e.g. 60 days, 120 days, 1 year, lifetime) was stated on any FLHSMV page studied in this section.** The CDL Enforcement, Commercial Driver License, Medical Information, and Fees pages as read/indexed do not list disqualification durations or the specific offenses that trigger them. Do not cite disqualification periods from this study; they would need the FLHSMV disqualification/suspension page or Chapter 322, F.S., which was outside the pages successfully read.

## 14. Fees (CDL-relevant)

*Source status: the Fees page returned 429 on direct open; figures below are from the FLHSMV Fees page text returned by site-restricted search. Re-verify by full page read.*

From the FLHSMV **Fees** page ("Fees for driver license and motor vehicle services are established in Florida Law"):

| Fee | Amount |
|---|---|
| Original / Renewal **Commercial Driver License** | **$75.00** |
| Original School Board Commercial Driver License | $48.00 |
| Renewal School Board Commercial Driver License | $48.00 |
| Original Class E (includes Learner's license) — for comparison | $48.00 |
| Renewal Class E — for comparison | $48.00 |
| Replacement license | $25.00 |
| Late fee | $15.00 |
| **Endorsements** | **$7.00** |
| Knowledge retest | $10.00 |
| Skill retest | $20.00 |
| **Disqualification** | **$75.00** |
| Revocations | $75.00 |
| Suspensions | $45.00 |
| Administrative fee for alcohol and drug related offenses | $130.00 |

Notes on the fee schedule: an additional **$6.25 service fee** may apply to any credential issued in a tax collector office. Veterans who provide / have previously provided evidence of veteran status will **not** be charged the $6.25 service fee in a tax collector office for transactions marked with an asterisk (which includes Original/Renewal CDL). The FAQ page confirms the CDL renewal cost as **$75.00** (vs $48 Class E) and states: "If you have a Commercial Driver License (Class A, B, or C) your license must be renewed, because **we cannot extend commercial licenses**."

Also from the Fees page: **Commercial Motor Vehicle Surcharge on vehicles 10,000 lbs or more — $10.00**.

## 15. Commercial Motor Carriers — IRP and IFTA

### International Registration Plan (IRP)

*Source status: the IRP page returned 429 on direct open; facts below combine the fully-read Commercial Motor Vehicle Drivers hub with FLHSMV search text for the IRP page. Re-verify by full page read.*

- IRP is a **reciprocal agreement** authorizing the **proportional registration** of commercial motor vehicles among the jurisdictions (states) in which the vehicles operate. If a truck operates in multiple jurisdictions, the owner must **annually report mileage** in each state and registration fees are paid **proportionately based on mileage** in each state — paid to just **one jurisdiction, the base jurisdiction / base state**.
- Vehicle owners are required to register under IRP if their vehicle(s):
  - Is **over 26,000 pounds** gross vehicle weight (GVW); **or**
  - Has **three or more axles, regardless of weight**; **or**
  - Is a power unit and trailer whose **combined GVW is in excess of 26,000 pounds**; **and**
  - Is part of a declared fleet that operates in Florida and **at least one other IRP jurisdiction**.
- IRP member jurisdictions: the **lower 48 states, the District of Columbia, and the 10 Canadian provinces**.
- **Base jurisdiction:** where motor carriers may register if they meet physical-location requirements, their vehicles accrue part of their mileage there, and it is where they maintain (or can make available) fleet operating records. To use Florida as base jurisdiction, the carrier must have an **established place of business in Florida** — a physical structure owned/leased by the applicant, open for business and staffed during regular business hours by one or more persons employed by the carrier on a permanent basis for general management (not independent contractors/service agents). Carriers without such a place of business may still use Florida as base jurisdiction if they (or an officer) are a **Florida resident**. All applicants must provide **three forms of proof** of established place of business or Florida residency.
- **IRP credentials:** for each registration year, Florida issues an **apportioned license plate and a cab card** (proof of registration).
- A vehicle with GVW under 26,000 lbs (or combination) may still be required to register as apportioned or obtain a valid IRP trip permit if conducting interstate commerce (e.g. operating from out of state but conducting point-to-point commerce in Florida).

### International Fuel Tax Agreement (IFTA)

- IFTA is also a **reciprocal agreement** among states. It simplifies fuel tax reporting for interstate motor carriers by allowing them to file **one quarterly report** to their base jurisdiction, rather than filing separately in each jurisdiction travelled.
- To obtain an IFTA license using Florida as base jurisdiction, the carrier must:
  - Have **qualified vehicle(s)** (commercial motor vehicle(s) as defined for IRP purposes);
  - Have an **established place of business in Florida** from which motor carrier operations are performed;
  - **Accrue some miles in Florida**;
  - **Maintain in Florida, or make available in Florida, the operating records** of the fleet; and
  - **Operate in at least one other IFTA member jurisdiction**.
- **IFTA license application:** to establish an IFTA account in Florida, an **Application for International Fuel Tax Agreement** and accompanying **decal order form** must be completed. Applicants must provide business name and **Federal Employer Identification Number (FEIN)**. The IFTA account business name should match the name used to obtain U.S. DOT operating authority and the name/FEIN on IRS Form 2290. IFTA accounts belonging to the same person/business with a Florida IRP account should use the **same name and FEIN** on both accounts.
- **IFTA decals:** jurisdictions must issue **one set of decals for each qualified vehicle** in the fleet. Decals are **account-specific, not vehicle-specific**. Licensees are responsible for maintaining operating records and filing taxes in Florida for all vehicles to which decals are affixed. **IFTA decals expire on December 31st of each year.**
- Application/decals by mail to: Bureau of Commercial Vehicle and Driver Services, 2900 Apalachee Parkway, Mail Stop 62, Tallahassee, FL 32399-0626; assistance at **(850) 617-3711**.

### IRP / IFTA temporary permits

- **Florida Temporary Trip Permit (IRP):** out-of-state carriers operating an apportionable vehicle in Florida with a non-IRP registration from another jurisdiction must purchase a Florida trip permit **prior to entering Florida**, and it must remain with the vehicle while in the state. Valid for **ten (10) days**, costs **$30.00**. Available online via the FLHSMV Commercial Vehicle Permit Portal (effective Oct 29, 2021) or from the Bureau of Commercial Vehicle and Driver Services at **(850) 617-3711**, weekdays 8:00–4:30. A **$2.00 non-refundable convenience fee** applies to all commercial vehicle trip and fuel permit options in the portal; once placed, an order cannot be cancelled.
- **IFTA Temporary Fuel Use Permit:** carriers operating an IFTA-qualified vehicle must purchase a Florida fuel permit prior to entering Florida. IRP registrants who do not maintain an IFTA account must obtain a Florida temporary fuel use permit **each time** their vehicles operate in Florida.
- **Hunter Permits:** out-of-state owner-operators not maintaining IRP registration in their own name and between lease agreements may obtain a Hunter Permit to move their empty truck/truck tractor while searching for employment; Florida recognizes valid Hunter permits from other jurisdictions. Florida Hunter Permits are valid for **ten (10) days** for a fee of **$5.00** (contact Bureau of Commercial Vehicle and Driver Services, (850) 617-3711).
- Temporary permits (IRP trip / IFTA fuel) are valid for a **maximum of 10 days** (permit portal).

### IRP/IFTA audit services

- Florida-based IFTA licensees / IRP registrants must keep **detailed records** of operations in each jurisdiction, used to report distance travelled (IRP renewal) and distance travelled plus fuel purchased and placed in propulsion tanks (IFTA quarterly tax return). Florida is required to **verify** distance and fuel as reported; audits follow IRP and IFTA audit standards.

## 16. Commercial Motor Carriers (FAQs) / Commercial Vehicle Information

- The A to Z Guide lists **Commercial Motor Carriers (FAQs)** and **FAQs on Trucking/Commercial Motor Carriers** and **Trucking/Commercial Motor Carriers** under C/F/T. The Commercial Motor Vehicle Drivers hub is the landing page for the carrier topics (IRP, IFTA, audit services, third-party testing).
- **Not verified in this study:** a standalone Commercial Motor Carriers FAQ page was not successfully opened/read; its specific Q&As are not recorded here.

## 17. Commercial Vehicle Enforcement (CVE)

From the Office of Commercial Vehicle Enforcement page (via search) and related CVE pages:

- The **Office of Commercial Vehicle Enforcement (CVE)**, within the Florida Highway Patrol, is the **Governor's designated lead agency responsible for commercial vehicle operations in Florida**.
- **Enforcement authority:** Florida Statutes give any CVE Trooper authority to require the driver of any commercial vehicle to **stop and submit to an inspection** and to enforce the state's traffic laws, with emphasis on violations committed by commercial vehicles.
- **New Entrant Safety Audits and Compliance Reviews:** New Entrant Safety Audits are **educational audits** to make sure new carriers understand the regulations and have adequate safety management controls. After the initial audit, carriers should be prepared for additional audits — **compliance reviews** — at any point; these are conducted **onsite at the carrier's principal place of business** and are more detailed and comprehensive than the New Entrant Safety Audit.
- **Citations and DataQ:** A Commercial Motor Vehicle Citation (Uniform Commercial Citation, UCC) may be protested with the **Commercial Motor Vehicle Review Board**, which may cancel, modify, or sustain the penalty. The Review Board will not hear a protest unless the penalty has been **timely paid**. The **DataQ** system is used to fix incorrect or duplicated information in the FMCSA database, most commonly to request removal/correction of violations from roadside inspections.
- **Emergency declarations:** Federal and State emergency declarations (President, Governors, FMCSA) trigger temporary suspension of certain federal safety regulations, including **Hours of Service**, for motor carriers/drivers engaged in emergency relief.
- **Troop J** oversees CVE operations for Florida's southern region (Troops C, D, E, F, L), six districts (DeLand, Orlando, Fort Myers, Tampa, West Palm Beach, Miami), **122 sworn and 10 non-sworn members**. Troopers enforce FMCSA regulations and Florida laws on commercial vehicle load, size, weight, fuel tax, hazardous material safety, traffic regulations, driver licensing, and vehicle registrations.
- **Contact:** Commercial Vehicle Enforcement **850-617-2280**; Commercial Carrier IFTA/IRP Help Desk **850-617-3711** (Contact Us page).

### Florida USDOT Numbers

From the Florida USDOT Numbers page (via search):

- Florida has adopted many FMCSA regulations for property and passenger carriers (ss. 316.302 and 316.70, F.S.).
- By law, a company must register for a **USDOT Number** and display it on all CMV power units and intermodal equipment chassis. Registration via FMCSA (fmcsa.dot.gov/registration; FMCSA toll-free 800-832-5660).
- All companies must **update their registration every two years**, regardless of whether information changed, operations ceased, or the business closed.
- **Penalties (Florida):**
  - s. 316.3026, F.S. — Violation of an Out-of-Service Order: **$10,000 and 3rd Degree Felony**.
  - s. 316.302(11), F.S. — CMV Falsely Displaying a USDOT Number: **1st Degree Misdemeanor**.
  - s. 316.3025(3)(d)(2), F.S. — Failing to Register: **$500.00 penalty**.
  - s. 316.3025(3)(a), F.S. — Failing to Properly Display: **$50 penalty**.
- Exemptions include 49 CFR 390.3(f); s. 316.302(2)(e) (agriculture/horticulture/forestry during harvest seasons); s. 316.302(2)(f) (vehicles with declared GVW under 26,001 lbs transporting property not requiring placards).

### Electronic Logging Devices (ELD)

From the ELD page (via search):

- The ELD rule became a final rule **December 16, 2015**, effective **February 16, 2016**, compliance date **December 18, 2017** for interstate drivers. FHP / CVE began enforcing the ELD mandate for **intrastate drivers on December 31, 2019**.
- Intrastate property carriers not transporting placardable hazmat need not comply with ELD / hours-of-service supporting-document requirements (49 CFR parts 385, 386, 390, 395) **until December 31, 2019**, per s. 316.302, F.S.

### Unified Carrier Registration (UCR)

From the UCR page (via search): the Unified Carrier Registration Act became effective **January 1, 2007**, replacing Single State Registration (repealed December 31, 2006). **Florida does not participate in UCR**, but it affects for-hire and private carriers operating outside Florida; Florida-based carriers that must register should register with a participating state where they have an office or the participating state nearest their principal place of business.

## 18. Third-party CDL testing and CDL schools

From the Commercial Motor Vehicle Drivers hub and the CDL Third Party Testing page (via search):

- The **CDL & Third Party Testing Unit** provides oversight of CDL skills testing in Florida through management of state-certified **Third Party Administrators** and **Third Party Testers**, to promote honest and ethical conduct and compliance with applicable policies, laws, and regulations.
- FLHSMV is responsible for compliance with FMCSA Regulation **49 CFR Part 383** and **Chapter 322, Florida Statutes**, by monitoring all Third Party Administrators and Third Party Testers who administer the CDL skills test.
- **Third Party Administrator:** a company contracted by FLHSMV (e.g. a company that provides its own testing).
- **Third Party Tester:** an individual worker certified by FLHSMV to administer the CDL skills test on behalf of the administrator.
- Administrator application requirements include: minimum qualifications; prequalifying application; insurance requirements; surety bond requirements; Public Records Policy 9.03; FAQs. Tester requirements include: minimum qualifications; prequalifying application; knowledge test requirements; fingerprint-based background check; FAQs.
- The A to Z Guide lists **State Skill Test Sites (CDL)** and **Third Party Skill Test Sites (CDL)**; the underlying site lists were not opened/read in this study.
- **Commercial Driving Schools Providing Behind the Wheel Training:** FLHSMV publishes a county-by-county list (Alachua through Volusia, incl. Broward, Duval, Hillsborough, Miami-Dade, Orange, Palm Beach, Pinellas, etc.) of schools with name, address, and phone. Individual school entries were not transcribed in this study.
- Forms relevant to CDL: **71048** Commercial Driver License Form; **71054** Certification for Waiver of Skill Test for Military Personnel; **77067** Application for Authority to Conduct Third Party Driver License Testing.

## 19. Key numbers — quick reference (all FLHSMV-stated)

| Fact | Value |
|---|---|
| CMV / Class A / B GVWR threshold | **26,001 lbs or more** |
| Class A towed-vehicle threshold | **more than 10,000 lbs** |
| Class C GVWR ceiling | **less than 26,001 lbs** |
| Passenger-vehicle threshold | **more than 15 persons incl. driver** (16+) |
| IRP applicability threshold | **over 26,000 lbs** GVW (note: 26,000, not 26,001, for IRP) |
| IRP: 3+ axles | regardless of weight |
| Farmer exemption radius | **within 150 miles** of farm |
| Covered farm vehicle, >26,001 lbs, interstate | **within 150 air miles** of farm/ranch |
| Minimum CDL age | **18**; under 21 = intrastate only |
| Residency proof holding period | **more than 6 consecutive months** |
| Military skill-test waiver window | form within **90 days** of separation; CDL issued within **120 days** of separation |
| CDL expired ≥1 year | re-take **all** knowledge + skills exams |
| ELDT effective | **February 7, 2022** |
| Medical examiner electronic transmission | effective **June 23, 2025** |
| Carry Med Card after electronic submission | suggested **at least 15 days** |
| Tank endorsement capacity | **1,000 gallons or more** |
| Triple trailers in Florida | **not allowed** |
| CDL original / renewal fee | **$75.00** |
| Endorsement fee | **$7.00** |
| Knowledge retest / Skill retest | **$10.00 / $20.00** |
| Disqualification fee (fee schedule) | **$75.00** |
| Hazmat background-check application fee | **$91** (+ CDL issuance + endorsement fees) |
| Tax collector service fee | **$6.25** (waived for veterans on *-marked transactions) |
| IRP temporary trip permit | **$30.00, 10 days** |
| Hunter permit | **$5.00, 10 days** |
| Permit portal convenience fee | **$2.00**, non-refundable |
| IFTA decals expire | **December 31** each year |
| USDOT registration update | **every two years** |
| Out-of-Service Order violation (FL) | **$10,000, 3rd Degree Felony** |
| Failing to register (USDOT) | **$500**; failing to properly display **$50** |
| Vision (Class A exam detail) | **20/40 in each eye**; hearing: must hear a whisper |
| CDL Help Desk | **(850) 617-2606**; IFTA/IRP Help Desk **(850) 617-3711**; CVE **850-617-2280**; CDL Retest Help Line **850-617-2707** |

## 20. Gaps / not found on FLHSMV pages studied

1. **Disqualification periods** (durations by offense) — not stated on any page studied. Needs the FLHSMV suspension/disqualification page or Chapter 322, F.S.
2. **Medical exam validity interval** (e.g. 24 months) — not stated on FLHSMV pages studied; FLHSMV says only "maintain current."
3. **CDL Handbook contents / edition / PDF URL** — handbook page not opened.
4. **Commercial Motor Carriers FAQ standalone page** — not opened/read.
5. **State / Third Party Skill Test Site lists** — listed in A to Z Guide but not opened/read.
6. **Full-page verification pending** for: CDL Medical Certification, Fees, Hazmat Information, IRP (direct opens failed: 403/429). Facts for those topics above rest on FLHSMV search-indexed text and should be re-verified by a full page read.
7. **CLP (Commercial Learner's Permit) details** beyond residency proof and the pre-Feb 7, 2022 ELDT carve-out — no standalone CLP page was read in this section.

---

## Page list — every URL studied

### Read in full via browser.open

1. https://www.flhsmv.gov/driver-licenses-id-cards/ — Driver Licenses & ID Cards hub (landing page; no CDL-specific content beyond navigation).
2. https://flhsmv.gov/a-to-z-guide/ — A to Z Guide; C-section entries: CDL Handbook; CDL Medical Certification Requirements; CDL Medical Self-Certification Online; CDL Requirements; Commercial Driver Licenses (CDL); Commercial Driver Schools (CDL); Commercial Motor Carriers (FAQs); Commercial Vehicle Enforcement; Commercial Vehicle Information. Also: Hazmat Endorsements; IFTA Manual; IRP Manual; Medical Card (CDL); Medical Self-Certification for CDL Holders; Motor Carrier Compliance; Office of Commercial Vehicle Enforcement; Self-Certification System for CDL Holders; State Skill Test Sites (CDL); Third Party Skill Test Sites (CDL); Trucking/Commercial Motor Carriers.
3. https://www.flhsmv.gov/ddl/com — Commercial Driver License (main CDL page: ELDT notice, Do I need a CDL, residency proof, Class A/B/C requirements, out-of-state/military CDL, endorsements H/N/P/S/T/X).
4. https://www.flhsmv.gov/driver-licenses-id-cards/commercial-motor-vehicle-drivers/ — Commercial Motor Vehicle Drivers hub (CDL summary, IRP, IFTA, IRP/IFTA Audit Services, Third Party Administrator/Tester requirements).
5. https://www.flhsmv.gov/florida-highway-patrol/commercial-vehicle-enforcement/safety-enforcement/cdl-enforcement/ — CDL Enforcement (CMV definition s. 322.01; CDL requirement s. 322.54; exemptions s. 322.53).
6. https://www.flhsmv.gov/driver-licenses-id-cards/general-information-draft__trashed/license-classes-endorsements-designations/ — License Classes, Endorsements & Designations (Class E/A/B/C, CDL exemptions, restriction codes, endorsement codes H/N/P/S/T/X). Note: URL contains `general-information-draft__trashed`; the live canonical URL per search is https://flhsmv.gov/driver-licenses-id-cards/general-information/license-classes-endorsements-designations/ — content identical in search results.

### Studied via FLHSMV search-indexed text (direct open failed: 403 / 429 — see method note)

7. https://www.flhsmv.gov/driver-licenses-id-cards/commercial-motor-vehicle-drivers/commercial-driver-license/cdl-medical-certification/ — CDL Medical Information / CDL Medical Certification Requirements (four categories A–D, Med Card on file, June 23, 2025 electronic transmission, 15-day carry suggestion, FAQ).
8. https://www.flhsmv.gov/safety-center/driver-licenses/fees/ — Fees (CDL $75, endorsements $7, retests $10/$20, disqualification $75, $6.25 tax-collector fee, $10 CMV surcharge).
9. https://www.flhsmv.gov/driver-licenses-id-cards/commercial-motor-vehicle-drivers/commercial-driver-license/hazmat-information/ — Hazmat Information (TSA background check, $91 application fee).
10. https://www.flhsmv.gov/driver-licenses-id-cards/commercial-motor-vehicle-drivers/international-registration-plan/ — International Registration Plan (apportionable vehicles, base jurisdiction, credentials, member jurisdictions). Note trailing-slash variant: `.../international-registration-plan/.`
11. https://www.flhsmv.gov/driver-licenses-id-cards/general-information — General Information (Class A/B/C exam requirements, vision 20/40, hearing whisper, handbooks free, CDL as professional license).
12. https://www.flhsmv.gov/driver-licenses-id-cards/commercial-motor-vehicle-drivers/commercial-driver-license-third-party-testing/ — Commercial Driver License Third Party Testing (49 CFR Part 383 / Ch. 322 oversight, Administrator vs Tester definitions).
13. https://www.flhsmv.gov/driver-licenses-id-cards/commercial-motor-vehicle-drivers/temporary-trip-permits/ — Temporary Trip Permits ($30 / 10 days; Hunter $5 / 10 days).
14. https://www.flhsmv.gov/driver-licenses-id-cards/commercial-motor-vehicle-drivers/international-fuel-tax-agreement/license-application/ — IFTA License Application (FEIN, decals, Dec 31 expiry, Bureau address).
15. https://www.flhsmv.gov/florida-highway-patrol/commercial-vehicle-enforcement/safety-enforcement/florida-usdot-numbers/ — Florida USDOT Numbers (biennial update, penalties $10,000 / $500 / $50).
16. https://www.flhsmv.gov/florida-highway-patrol/commercial-vehicle-enforcement/about/covered-farm-vehicles/ — Covered Farm Vehicles (July 1, 2019 adoption, 150 air miles).
17. https://www.flhsmv.gov/florida-highway-patrol/specialized-areas/commercial-vehicle-enforcement — Office of Commercial Vehicle Enforcement (CVE mission, inspection authority, New Entrant audits, UCC/DataQ, emergency declarations).
18. https://www.flhsmv.gov/florida-highway-patrol/commercial-vehicle-enforcement/safety-enforcement/electronic-logging-devices/ — Electronic Logging Devices (Dec 18, 2017 interstate; Dec 31, 2019 intrastate).
19. https://www.flhsmv.gov/florida-highway-patrol/commercial-vehicle-enforcement/about/unified-carrier-registration/ — Unified Carrier Registration (effective Jan 1, 2007; Florida does not participate).
20. https://www.flhsmv.gov/driver-licenses-id-cards/cdl-behind-wheel-training/ and https://www.flhsmv.gov/ddl/drivingschools/ — Commercial Driving Schools Providing Behind the Wheel Training (county-by-county school list).
21. https://services.flhsmv.gov/CDLMedCert/ — CDL Self-Certification System (online self-certification without an office visit; valid Florida CDL required).
22. https://www.flhsmv.gov/contact-us/ — Contact Us (CDL Help Desk 850-617-2606; IFTA/IRP Help Desk 850-617-3711; CDL Retest Help Line 850-617-2707; CVE 850-617-2280).
23. https://www.flhsmv.gov/driver-licenses-id-cards/what-to-bring/frequently-asked-questions/ — Frequently Asked Questions (CDL renewal $75; commercial licenses cannot be extended).
24. https://vendorservices.flhsmv.gov/IcfsPermits/en/Home/Landing — FLHSMV Commercial Vehicle Permit Portal (IRP/IFTA temporary permits, $2 convenience fee, max 10 days).
25. https://www.flhsmv.gov/resources/forms/ — Forms (71048 CDL Form; 71054 Military Skill Test Waiver; 77067 Third Party Testing Authority).
# 07 — Motorcycles (FLHSMV Study)

**Scope:** Motorcycle licensing, rider education, endorsements, safety courses, the Florida Rider Training Program (FRTP), and the "Ride Proud, Dress Loud" conspicuity campaign on flhsmv.gov.
**Study date:** 2026-11-23. All facts below are from flhsmv.gov pages only. Page crawl dates shown are the dates the fetch tool reported for each page.

---

## 1. Pages studied

| # | Page | URL | Status |
|---|------|-----|--------|
| 1 | Education & Courses (parent page; Motorcycle Rider Education & Endorsements blurb) | https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/ | Read in full (crawled 2026-10-29) |
| 2 | A to Z Guide (index entries: Motorcycle Endorsements, Motorcycle Handbook, Motorcycle Rider Training Program) | https://flhsmv.gov/a-to-z-guide/ | Read in full (crawled 2026-11-04) |
| 3 | Motorcycle Rider Education & Endorsements (main page) | http://flhsmv.gov/driver-licenses-id-cards/motorcycle-rider-education-endorsements/ | Read in full (crawled 2026-07-12) |
| 4 | FAQs (Motorcycle Rider Education & Endorsements) | https://www.flhsmv.gov/driver-licenses-id-cards/motorcycle-rider-education-endorsements/faqs/ | Read in full (crawled 2026-06-13) |
| 5 | Safety Course Locations | https://flhsmv.gov/driver-licenses-id-cards/motorcycle-rider-education-endorsements/safety-course-locations/ | Read in full (crawled 2026-11-05) |
| 6 | Forms (Motorcycle Rider Education & Endorsements) | https://www.flhsmv.gov/driver-licenses-id-cards/motorcycle-rider-education-endorsements/forms/ | Read in full (crawled 2026-01-16) |
| 7 | Useful Safety Links | https://www.flhsmv.gov/driver-licenses-id-cards/motorcycle-rider-education-endorsements/useful-safety-links/ | Read in full (crawled 2026-01-16) |
| 8 | Motorcycle Safety Awareness (Safety Center) | https://www.flhsmv.gov/safety-center/motorcycle-safety/ | Read in full (crawled 2026-01-05) |
| 9 | License Classes, Endorsements & Designations (motorcycle endorsement codes) | https://flhsmv.gov/driver-licenses-id-cards/general-information/license-classes-endorsements-designations/ | Read in full (crawled 2026-06-24) |
| 10 | Ride Proud, Dress Loud (conspicuity campaign page) | https://www.flhsmv.gov/driver-licenses-id-cards/motorcycle-rider-education-endorsements/ride-proud-dress-loud/ | NOT directly opened — direct fetch rate-limited (HTTP 429) at time of study. Full page text captured via flhsmv.gov search result; facts in §7 are from that flhsmv.gov text. |
| 11 | Handbooks & Manuals (Motorcycle Handbook / MSF Rider Handbook listing) | https://flhsmv.gov/resources/handbooks-manuals/ | NOT opened — direct fetch rate-limited (HTTP 429) at time of study. See §8 gap note. |

---

## 2. When a motorcycle endorsement is required

- To operate **any two- or three-wheel motorcycle whose engine is more than 50 cc**, you must have a motorcycle endorsement on your driver license or hold a "Motorcycle Only" license.
- "Anyone driving a motorcycle without an endorsement is violating the law."
- **No one under 16** may legally operate or be licensed to operate any of the following on Florida roads, streets or highways: motorcycles, mopeds, motor-driven cycles, motorized scooters, or electric helper-motor bicycles (s. 316.003(47) F.S., as cited on the main page; the FAQ cites s. 316.003(2) F.S.).
- Vehicles **50 cc or less** are not motorcycles under driver-license law (s. 322.01(26), F.S.), so no motorcycle endorsement is needed per s. 322.03(4), F.S. — but to operate them on streets/roadways you must be at least 16 and hold at least a regular Class E operator's or "Motorcycle Only" driver license, because they still fall under the definition of "motor vehicles."
- A bicycle propelled by human power plus an electric helper-motor that **cannot go faster than 20 mph on level ground** is exempt from the driver-license definition of motor vehicle and requires no driver license (must be at least 16).
- Learner's license holders **are not allowed to operate motorcycles** (License Classes page).

## 3. Basic RiderCourse (BRC) — the mandatory course

- **New motorcyclists must take and pass the Basic RiderCourse (BRC) or Basic RiderCourse updated (BRCu)** through a FRTP-authorized Sponsor before the motorcycle endorsement can be added to their license, per **s. 322.12(5)(a), Florida Statutes**.
- **BRC enrollment minimums:** at least **16 years old** and hold at least a **Learner's Driver License**. Applicants "should have a basic knowledge of traffic laws, road signs and general 'road rules'."
- Most Motorcycle Safety Foundation (MSF) courses for beginner to experienced riders in Florida are provided by FLHSMV **Florida Rider Training Program (FRTP)-authorized Sponsors** (course providers). Courses cover strategies/techniques for managing the riding environment and avoiding crashes, plus on-cycle riding sessions. FLHSMV states crash studies show rider-course graduates have lower injury and fatality rates than untrained riders.
- After completing BRC, BRCu, 3WBRC, or S/TEP for endorsement, **the Sponsor submits results electronically to the Department**.
- **One-year deadline:** after successfully passing the RiderCourse, you must **obtain the endorsement within one (1) year**. If not obtained within the one-year grace period, the course completion card and the "PASS" waiver status are considered invalid and you must complete another RiderCourse before the endorsement can be added.

## 4. Steps to obtain a "Motorcycle Also" endorsement

1. Hold at least a valid **Class E operator's driver license**.
2. Complete the **Basic RiderCourse (BRC) or Basic RiderCourse updated (BRCu)** motorcycle safety course with an authorized Sponsor.
3. Obtain the endorsement **within 1 year** of passing (see §3).
4. Visit a driver license office or tax collector office that issues driver licenses, inform them you completed the course, provide proper ID, and pay the required endorsement fees. Your Class E license will then be issued with a motorcycle endorsement.

## 5. Steps to obtain a "Motorcycle Only" driver license

1. Be at least **16 years old**; if under 18, hold at least a Learner's License for **one year with no traffic convictions**. (FAQ wording: if over 18, hold a Learner's License.)
2. Pass the **same knowledge test as for a regular Class E** operator's driver license.
3. Complete the **Basic RiderCourse (BRC) or Basic RiderCourse updated (BRCu)** with an authorized Sponsor.
4. Visit a driver license office or tax collector office, provide proper ID, and pay the required endorsement and license fees. The license is issued **restricted to operating "Motorcycles Only."**

## 6. Endorsement codes — "Motorcycle Also" vs "Motorcycle Only"

From the License Classes, Endorsements & Designations page:

| Code | Descriptor | Meaning |
|------|-----------|---------|
| **A** | A–MTRCL Also | **Motorcycle Also:** allows a rider holding a valid Florida driver license to operate a motorcycle, in addition to any other motor vehicles for which they are already licensed. |
| **O** | O–MTRCL Only | **Motorcycle Only:** specifies that a rider is restricted to operating a motorcycle only. |

- On the **previous credential**, the words "MOTORCYCLE ALSO" or "MOTORCYCLE ONLY" were spelled out on the front of the license under the expiration date.
- On the **new credential** (available in select locations starting August 2017), motorcycle endorsements are no longer spelled out on the front. They are designated by an **"A" or "O" in the endorsement field ("END")** on the front of the card, and by **"A-MTRCL Also" or "O-MTRCL Only"** on the back of the card in the endorsement field ("END").
- **Endorsement never expires:** "No, once the endorsement is added to the license, it is good for life."
- Class E itself covers two- or three-wheel motor vehicles **50 cc or less**, such as mopeds or small scooters.

### Fees (from the FAQ page)

- **$7.00 endorsement fee**, plus a license fee (original, renewal, duplicate, or replacement license fee as applicable), plus **$6.25 if applying at a county tax collector office**. Tax collector offices charge an additional $6.25 for driver license transactions.
- The course provider's fee for the required motorcycle safety course is separate and paid to the provider.
- For context, the general FAQ cited elsewhere in the study notes a renewal fee of $48 plus $7 for the motorcycle endorsement (from the Class E FAQ page, not the motorcycle FAQ).

## 7. Three-wheel and sidecar/trike endorsement ("S" restriction)

- To be endorsed for a **three-wheel motorcycle or sidecar motorcycle**: hold at least a Class E license; complete the **3-Wheel Basic RiderCourse (3WBRC)** or **Sidecar/Trike Education Program (S/TEP)**; go to a driver license/tax collector office with proper ID and pay fees; the license is issued with the **"S" Restriction**.
- **3WBRC:** for a three-wheel, two-track vehicle only; for endorsement ("S" Restriction will be reflected on the license). Minimums: at least 16, hold at least a Learner's Driver License, basic knowledge of traffic laws/road signs/road rules. Some Sponsors can provide a 3-wheel training motorcycle; otherwise bring your own 3-wheel motorcycle or written permission to use another privately owned one. Must provide **proof of liability insurance** on the 3-wheel motorcycle used and **your own helmet and protective riding gear**.
- **S/TEP:** can be taken by the unendorsed rider for endorsement, but limits the rider to operating a motorcycle with more than two wheels or an attached sidecar ("S" endorsement/restriction). Minimums: hold at least a Learner's Driver License; bring your own motorcycle or written permission to use another privately owned sidecar/trike; provide your own helmet and protective riding gear; provide proof of liability insurance on the sidecar/trike used.
- **You do NOT need S/TEP to ride a trike if you already hold a "Motorcycle Also" endorsement** — a "Motorcycle Also" endorsement also covers three-wheeled motor vehicles.
- Completing a basic or experienced rider safety course **may entitle a motorcyclist to insurance premium discounts**.

## 8. Reciprocity — out-of-state and military

- Florida **reciprocates** a motorcycle endorsement from **any state except Alabama**, U.S. territories and possessions (including Panama Canal Zone if issued prior to January 1, 2000), **Canada, France, Germany, Taiwan**, and the **U.S. military** — the motorcycle course is not required.
- **Alabama exception:** an Alabama license with a motorcycle endorsement is reciprocated **only if a Motorcycle Safety Foundation (MSF) Basic RiderCourse (BRC) completion card is presented** with it (FAQ: card not more than one year old, or it is considered invalid).
- Florida **accepts out-of-state or military rider-course completion cards** (not more than 1 year old) and waives testing to add endorsements: MSF **Basic RiderCourse (BRC)** and **3-Wheel Basic RiderCourse (3WBRC)**; Evergreen Safety Council's **Sidecar/Trike Education Program (S/TEP)**.
- **Stationed outside Florida:** complete the MSF BRC, 3WBRC, or ESC S/TEP through any branch of the military service, then return to a Florida driver license or tax collector office with required documents and pay applicable fees, or obtain a license in the state of current residence.

## 9. Other MSF courses offered (from the FAQ page)

| Course | What FLHSMV says |
|--------|------------------|
| **Basic RiderCourse 2 (BRC2)** | One-day course for **experienced riders who already have a motorcycle endorsement** who want to refresh/enhance skills. Covers more riding strategies for traffic hazards; cornering, braking, swerving. Participants provide their own motorcycle, proof of insurance, and protective riding equipment. |
| **Advanced RiderCourse (ARC)** | One-day advanced course for skill building/enhancement. Challenges the rider's ability to recognize risky behavior and choose a different course of action; good decisions and risk offset, plus a new skill set to increase safety margin. |
| **Returning Rider Basic RiderCourse (RRBRC)** | For riders who have ridden previously but have not actively ridden for some time and want to refresh skills and gain more knowledge of risk/risk management. **Not** for a first-time rider. |
| **Basic Bike Bonding RiderCourse (BBBRC)** | 5–6 hour course for the **new rider** to enhance skills on the training bike and gain confidence in newly learned skills. |
| **Ultimate Bike Bonding RiderCourse (UBBRC)** | Partial-day course of **police-style precision riding**, targeting low speed and tight turns. |

- Course codes appearing in the Safety Course Locations listings: **BRC, BRC2, 3WBRC, S/TEP, ARC, RRBRC, BBBRC (listed as "BBRC" for one St. Augustine provider), UBBRC, MSRC**. An asterisk note on that page reads "*Courses with an asterisk are for endorsement.*"

## 10. Safety Course Locations (FRTP authorized Sponsors)

- The Safety Course Locations page lists providers **by county** (Alachua, Bay, Bradford, Brevard, Broward, Charlotte, Citrus, Clay, Collier, Columbia, Duval, Escambia, Flagler, Hernando, Hillsborough, Jefferson, Lake, Lee, Leon, Manatee, Marion, Martin, Miami-Dade, Monroe, Okaloosa, Orange, Osceola, Palm Beach, Pasco, Pinellas, Polk, Putnam, Sarasota, Seminole, St. Johns, Volusia) with city, provider name, phone number, website link, and courses offered.
- Counties with **no providers listed** on the page as read: Bradford, Collier, Jefferson, Leon, Manatee, Monroe (empty tables).
- Provider mix includes Harley-Davidson dealership schools (e.g., Space Coast, Alligator Alley, Bert's Black Widow/Barracuda, Adamec, Orlando, Daytona, Seminole), colleges (Florida State College Jacksonville North Campus, Withlacoochee Technical College), and independents (Motorcycle Training Institute, Inc. 877-308-7246; SafeRide.com 352-589-7233; Joe's Motorcycle Training 813-300-6824; Sunstate Motorcycle Training; Adventure Rider Training, Inc.).
- Full county-by-county table is on the page itself; see URL in §1, row 5.

## 11. FRTP — Florida Rider Training Program

- The **Florida Rider Training Program (FRTP)** is FLHSMV's program administering MSF rider courses through **authorized Sponsors** (course providers).
- Legal basis cited on the Forms page: **s. 322.0255, Florida Statutes** (establishes the motorcycle program) and **Chapter 15A-12, Florida Administrative Code** (requirements of sponsors and RiderCoaches under FLHSMV/FRTP oversight and regulatory authority).
- **Forms page (FRTP administration):**
  - RiderCoach Mentor Form — HSMV 77079
  - RiderCoach Intern Form — HSMV 77078
  - RiderCoach Personal Information & Qualifications — HSMV 77122
  - RiderCoach Apprentice Program Application (RCAP) — HSMV 77058
  - FRTP Rules of Professional Conduct — completed annually by potential and active FRTP Recognized RiderCoaches
  - FRTP Quality Assurance Audit Form — HSMV 92786, used by FRTP Regional Coordinators on Quality Assurance Visits
  - FRTP Sponsor Information Update Form — to notify FRTP of address/contact/phone changes
  - Curricula Offerings — Requirements for Rider Education Responsibility Program (RERP) Sponsors: many MSF curricula require additional RiderCoach training and special range recognition; sponsors must contact FRTP before implementing a new course.

## 12. "Ride Proud, Dress Loud" — Motorcycle Conspicuity Campaign

- FLHSMV and FRTP endorse **"Ride Proud, Dress Loud,"** a statewide **Motorcycle Conspicuity Campaign**, plus public-awareness education for motorists to **look twice**, "as motorcyclists are everywhere." The initiatives are ongoing and focus on promoting motorcycle visibility and safety to reduce fatalities on Florida roadways.
- Rationale stated on the page: lacking the structural safety advantages of an automobile or truck, motorcyclists are more likely to suffer severe injury or death in a crash; research suggests motorcyclists who make themselves more visible/conspicuous are less likely to have their right-of-way violated by other vehicles.
- **Motorcyclist apparel safety tips (from the campaign page):**
  - Wear clothing that is protective **and visible** during all hours of the day.
  - Inconspicuous black clothing "may be in fashion" but offers little visibility; gray, beige, and other neutrals are also difficult to detect.
  - One of the easiest and most effective ways to be seen is **brightly colored upper-torso clothing**.
  - Reflective decals/materials on clothing increase visibility.
  - Make the bike more visible: buy a brightly colored bike from the factory; paint an existing dark bike a brighter color or add eye-catching frontal bodywork; use unique lighting such as **high beams during the day**; strategically placed magnetic reflector strips for detection in the dark.

## 13. Rules of the road, safety, insurance, helmets (Safety Center + FAQ)

- Motorcycle and moped drivers have the **same rights and duties** as drivers of motor vehicles.
- **Helmet/eye protection:** under Florida law, motorcyclists must wear **eye protection** and **U.S. DOT-compliant protective headgear/helmet**. Motorcyclists **over 21** may ride without a helmet **only if they have proper insurance coverage**.
- All persons operating motorcycles must wear eye protection; passengers should wear it for safety but are **not required by law** to do so.
- Motorcycles and mopeds **may not be operated on bicycle paths or foot paths**.
- **Tips for motorists (Safety Center):** never share a lane with a motorcycle (rider is entitled to the entire lane); watch for motorcycles before pulling into an intersection or changing lanes; a motorcycle's speed is hard to gauge — it may appear farther away than it is; do not follow too closely (motorcycles can stop more quickly); riders often slow by down-shifting/rolling off the throttle without activating the brake light; never pass a motorcyclist with only a few feet of space (wind gust can cause loss of control); when being passed by a motorcycle, maintain lane position and do not increase speed; maintain a **four-second buffer zone**, more in bad weather, gusty wind, wet/icy roads, bad road conditions, and railroad crossings.
- **Insurance:** insurance is **not required to register** motorcycles. However, if a motorcycle operator is charged in a crash with injuries, the owner/owner-operator is financially responsible for bodily injury and property damage to others. If no liability coverage was in effect, bodily injury/property damage liability insurance must be purchased and kept for **three years** to avoid license and tag/registration suspension or to reinstate after suspension.
- **Passengers:** Florida law does not set a minimum age for motorcycle passengers (other laws such as endangering a minor may apply).
- **Motorized scooters:** small two- or three-wheel vehicles (stand or sit, electric or gas, T-shaped handlebar steering) **cannot be legally operated on public roadways, sidewalks, or bicycle paths**; check city/county ordinances.
- **Mopeds:** operators have the same rights and duties as motor vehicle operators and can receive citations; see the motorcycle operator's manual for moped laws.
- **Titling:** motor scooters meet the definition of motorcycle (s. 320.01(27), F.S.) and must be titled and registered if operated on state roads (ss. 319.21(1), 320.02(1), F.S.). A motor-driven cycle over 50 cc with pedals is classified **MC (motorcycle)**, not a moped. Motorcycles 50 cc or less are **not** exempt from odometer disclosure requirements.

## 14. Useful Safety Links (organizations FLHSMV links)

- **American Motorcyclist Association (AMA)** — protects/promotes motorcyclists' interests, serves members' needs.
- **Motorcycle Safety Foundation (MSF)** — developer of the Rider Education and Training System (MSF RETS); promotes lifelong learning for motorcyclists and professional development for certified RiderCoaches.
- **NHTSA Motorcycle Safety Information** — education, enforcement, outreach, legislation; promotes rider education/licensing, reducing impaired motorcycling, motorist awareness, helmet use.
- **Snell Memorial Foundation** — helmet safety standards research, education, testing, development (founded 1957).
- **State Motorcycle Safety Association (SMSA)** — National Association of State Motorcycle Safety Administrators.
- **Ride Proud Dress Loud** — the FLHSMV/FRTP statewide Motorcycle Conspicuity Campaign.

## 15. Motorcycle Handbook

- The main motorcycle page and the Safety Center page both refer readers to the **motorcycle operator's manual / Florida Motorcycle Handbook** for rules, responsibilities, and safe-operation techniques (beginner and experienced riders). The A-to-Z Guide lists "Motorcycle Handbook" as its own entry.
- The handbook is published as the **Motorcycle Safety Foundation Rider Handbook** and listed on FLHSMV's Handbooks & Manuals page (flhsmv.gov/resources/handbooks-manuals/). **Gap:** that page was not directly opened during this study (fetch rate-limited, HTTP 429), so the exact current handbook title/edition/link on flhsmv.gov was not verified first-hand. Older FLHSMV editions were form **HSMV 71905** ("Florida Motorcycle Handbook," includes moped information) — that form number comes from archived handbook copies, not from a page read in this study, and should be re-verified against the live Handbooks page.

## 16. Gaps / not verified in this study

1. **Ride Proud, Dress Loud page** — direct open failed (HTTP 429 rate limit); facts in §12 come from the full flhsmv.gov text returned in a search result, not a direct page read. Re-open to confirm.
2. **Handbooks & Manuals page** — not opened (same 429); current Motorcycle Handbook title/edition/link unverified (§15).
3. **A-to-Z "Motorcycle Rider Training Program" link target** — the A-to-Z text gives no URL in the fetched copy; presumed to be the main Motorcycle Rider Education & Endorsements page (§1, row 3), but not confirmed by following a live link.
4. **Course fees charged by providers** — FLHSMV does not publish a set course price; fees are set by each Sponsor and paid to the provider.
5. Provider website links on the Safety Course Locations page were not followed (external sites, out of scope).
# 08 — Insurance & Financial Responsibility (FR)

**Study date:** Monday, November 23, 2026
**Scope:** FLHSMV pages on auto insurance, no-fault PIP, Financial Responsibility suspensions, FR cancellation, reinstatement fees, SR-22, and updating insurance information.
**Starting points (per brief):** https://www.flhsmv.gov/driver-licenses-id-cards/ and https://flhsmv.gov/a-to-z-guide/

**Method note:** Every fact below is taken from an flhsmv.gov page that was either opened in full with `browser.open` or returned verbatim in a `browser.search` snippet from flhsmv.gov. Facts from non-FLHSMV sources are labelled **SECONDARY** and are never presented as FLHSMV facts. Two FLHSMV pages returned HTTP 429 (rate limit) and were **not** retried; they are listed as gaps in §9.

---

## 1. Pages studied

| # | Page | URL | How read | Crawl date shown |
|---|------|-----|----------|------------------|
| 1 | Driver Licenses & ID Cards (hub) | https://www.flhsmv.gov/driver-licenses-id-cards/ | Opened in full | 2026-10-29 |
| 2 | A to Z Guide | https://flhsmv.gov/a-to-z-guide/ | Opened in full | 2026-11-04 |
| 3 | Florida Financial Responsibility and Insurance Program (FRIP) | https://www.flhsmv.gov/frip/ | Opened in full | 2026-01-16 |
| 4 | Involved in a Crash? | https://flhsmv.gov/insurance/involved-in-a-crash/ | Opened in full | 2026-05-01 |
| 5 | Uninsured Motorist Rate | https://www.flhsmv.gov/insurance/uninsured-motorist-rate/ | Opened in full | 2026-10-22 |
| 6 | Business Customers (insurance) | https://www.flhsmv.gov/insurance/business-customers/ | Opened in full | 2026-01-16 |
| 7 | Self-Insurance | https://www.flhsmv.gov/insurance/self-insurance/ | Opened in full | 2026-01-16 |
| 8 | MyDMV Portal | https://www.flhsmv.gov/motorist-modernization/mydmvportal/ | Opened in full | 2026-11-16 |
| 9 | Fees (fee schedule) | https://www.flhsmv.gov/fees/ | Opened in full | 2026-10-26 |
| 10 | Driver License Check (MyDMV Portal) | https://mydmvportal.flhsmv.gov/home/en/publicweb/dlcheck/ | Opened in full | 2026-11-05 |
| 11 | Other Common Suspensions and Revocations | https://www.flhsmv.gov/driver-licenses-id-cards/driver-license-suspensions-revocations/other-suspensions-revocations/ | Search snippet only (FLHSMV) — full open returned 429, not retried | crawled ~2026-01 |
| 12 | Contact Us | https://www.flhsmv.gov/contact-us | Search snippet only (FLHSMV) | crawled ~2025 |
| 13 | Electronic Services | https://www.flhsmv.gov/motor-vehicles-tags-titles/license-plates-registration/electronic-services/ | Search snippet only (FLHSMV) | crawled ~2026-11 |
| 14 | Self-Insurance — Firm, Partnership, Association or Corporation | https://www.flhsmv.gov/insurance/self-insurance/firm/ | Search snippet only (FLHSMV) | crawled ~2026-01 |
| 15 | Insurance (auto) — A-to-Z entry | listed in A-to-Z Guide under "I" as "Insurance (auto)" | Link target is the main insurance index (see §9 gap) | — |
| 16 | Main insurance index | https://www.flhsmv.gov/insurance/ | **NOT READ — open returned HTTP 429, not retried** | — |

Related FLHSMV material cited in snippets: RS-01 Motor Vehicle Procedure Manual (registration/insurance verification), DLCheck Sanction Help pages on services.flhsmv.gov (court suspensions, $60/$45 fees — different sanction types, see §6).

---

## 2. Florida no-fault PIP insurance requirements

FLHSMV states the requirement identically on several pages:

- **Minimum coverage: $10,000 Personal Injury Protection (PIP) and $10,000 Property Damage Liability (PDL)**, required "throughout the motor vehicle registration period" for motor vehicles registered in Florida. (Uninsured Motorist Rate page; Involved in a Crash? page, property-damage section.)
- The requirement applies to **every vehicle with a current Florida registration** — the Business Customers page triggers the department's letter when a vehicle "has a valid Florida registration and no other active Florida policy is reported by another insurance company."
- **Proof of Florida insurance is required to register** a vehicle. Per procedure RS-01 (FLHSMV Motor Vehicle Procedure Manual, search snippet): proof is **not** required for self-propelled vehicles with fewer than four wheels, trailers, mobile homes, motorcycles, or government-owned vehicles; registration "must be refused if the owner does not submit proof of insurance or if proof cannot be obtained."
- Insurers must furnish uniform proof-of-purchase cards (paper or electronic) showing the insurer name, coverage identification number, and the vehicle's make, year, and VIN. (RS-01.)
- The department enforces **Chapters 627 and 324, Florida Statutes** (FRIP page), working with the Department of Financial Services and the Office of Insurance Regulation (OIR). OIR regulates the business of insurance; FLHSMV handles compliance/enforcement of coverage.
- **Bodily injury liability (BIL) is NOT part of the basic no-fault minimum.** BIL ($10,000 per person / $20,000 per crash) is required only in the Financial Responsibility (crash) context — see §5. Do not confuse the $10,000 PIP / $10,000 PDL everyday minimum with the $10,000/$20,000/$10,000 crash requirement.

---

## 3. How FLHSMV finds out: insurer reporting (10 days)

- Per §324.0221, F.S. (FRIP page), insurers authorized to issue Florida motor vehicle policies must report:
  - **Policy cancellation or nonrenewal to the department within 10 days** after the processing date or the effective date of the cancellation/nonrenewal, **whichever is later**.
  - **New policy issuances to the department within 10 days.**
- "All licensed insurance companies who report to FLHSMV provide the policy initiation or cancellation electronically." (Business Customers page.)
- The department sends a letter notifying the owner to provide the required insurance coverage information when:
  - the insurer reports a cancellation or removal of a vehicle from a policy, **or**
  - a registration was renewed, transferred, or originally issued and the insurer **denied** the coverage provided at the transaction, **and**
  - the vehicle has a valid Florida registration and no other active Florida policy is reported by another insurer.
- A verification letter can also be triggered by a crash or by a citation for driving without proof of insurance. (Business Customers page.)

---

## 4. FR suspension for lapsed / cancelled insurance

- **What is suspended:** "Failure to maintain the required insurance coverage may result in suspension of the registrant's driver license/registration." (Uninsured Motorist Rate page.) The suspension therefore hits **both the driver license and the registration/plate**, not the license alone.
- **Trigger:** the insurer's cancellation report plus no replacement Florida policy on file.
- **Notice:** FLHSMV sends a letter / Notice of Suspension with an **original suspension date** printed on it. The Business Customers page is explicit about the consequence of timing: "If you have received a Notice of Suspension regarding an insurance case and the requirements have not been met **prior to the original suspension date** indicated on the Notice of Suspension received, a reinstatement fee is required."
  - The converse is the key operational fact: **meet the requirements before the original suspension date and no reinstatement fee is due** (and, by the same logic, the suspension does not take effect). This is corroborated by the Involved in a Crash? FAQ: take proof "to your nearest driver license and motor vehicles service center or Tax Collector's office **so your driving privilege is not suspended**."
- **Avoiding suspension without buying insurance:** surrender the Florida tag and registration. FLHSMV's stated alternatives when insurance is cancelled:
  - No longer own the vehicle and do not anticipate transferring the tag: surrender the Florida tag at a driver license and motor vehicle service center or tax collector office.
  - Vehicle inoperable or otherwise not being driven on public roadways: **"you must surrender the Florida tag and registration immediately upon cancelling the Florida insurance."**
  - Moved to another state but kept the Florida tag: register in the new state of residence — "For a vehicle to maintain a Florida registration, it must be insured in Florida."
  - For a crash case: "Purchase $10,000 PIP/$10,000 PDL insurance **or surrender the Florida plate and registration**." (Involved in a Crash?, property-damage section.)
- **Duration of a plain lapse suspension:** FLHSMV's own pages opened for this study **do not state a maximum duration** (e.g. "up to three years") for an insurance-cancellation lapse. The 3-year figure on FLHSMV pages applies to **crash-related** FR suspensions (§5). **SECONDARY** sources citing §324.0221 state a lapse suspension lasts until proof of coverage is provided, up to three years — treat as unverified against FLHSMV until the FR case pages (§9) are read.
- **"FR Sanction" number:** the Notice of Suspension carries an FR Sanction (case) number; "the first digit in this number tells you what kind of case you have" (per Pinellas County Tax Collector's FLHSMV-linked suspensions page — **SECONDARY**, but it links to FLHSMV FR100 / FR200 / FR700 / FR800 / FR900 case pages). The case number is required to pay a reinstatement fee online (Business Customers page).

---

## 5. Crash-related Financial Responsibility (the tougher track)

From **Involved in a Crash?** (FLHSMV, opened in full):

### 5.1 Crash reporting threshold
- §316.065, F.S.: a driver in a crash involving injury or death, or at least **$500** estimated vehicle/property damage, must immediately contact local law enforcement.

### 5.2 Crashes involving injuries (at-fault driver charged with a moving violation + injuries/possible injuries noted)
Required coverage at the time of the crash:
- Bodily injury liability **$10,000 per person / $20,000 per crash**
- Property damage liability **$10,000 per crash**
- Personal injury protection **$10,000 per person per crash**

If the owner/driver did **not** have this coverage, FLHSMV requires:
1. Purchase and maintain minimum limits of **$10,000/$20,000/$10,000** insurance **and an SR-22 filing (certification of liability insurance) for three years from the designated suspension date**. The insurance company must certify the SR-22 filing with the department.
2. Obtain releases from the other parties for property damages and/or bodily injuries, **or** post a security deposit with the department in the amounts listed on the suspension notice.
3. Pay a **$15 reinstatement fee**, if applicable.

### 5.3 Crashes involving property damage only (moving violation + damage, no injuries)
Required coverage at the time of the crash:
- **$10,000 PDL** per crash and **$10,000 PIP** per person per crash.

If the owner did **not** have this coverage, FLHSMV requires:
1. Obtain releases from the other parties for vehicle/property damages, **or** post a security deposit in the amounts listed on the crash report.
2. Purchase **$10,000 PIP / $10,000 PDL** insurance **or surrender the Florida plate and registration**.
3. Pay a **$150 – $500 reinstatement fee**, if applicable.

### 5.4 Final judgment
- §324.121, F.S.: FLHSMV may suspend the license of an at-fault party when a court renders a judgment involving a crash.
- Once a final judgment is rendered and **30 days** has expired from the judgment date, send a certified copy of the judgment + the crash report to: Bureau of Motorist Compliance, 2900 Apalachee Parkway, Room B260F, MS-87, Tallahassee, FL 32399-0585.
- Final judgments submitted to the department are **immediately enforced**; the at-fault party's license, tags, and registrations are suspended for **20 years or until the judgment is satisfied**.

### 5.5 Insurance-information requests after a crash
- §324.242(2), F.S.: the other party's insurance information is released only to a person involved in the crash, their attorney, or a representative of the insurer of anyone involved.
- Form HSMV 83392 (Insurance Request Form) + complete crash report (front and back), mailed/faxed to Customer Service Correspondence Center, 2900 Apalachee Parkway, Room A216, MS 99, Tallahassee, FL 32399-0585, Fax 850-617-5216. Allow **10 working days** after receipt for processing.
- Related forms: HSMV 74014 (Release in Full of All Claims), HSMV 74036 (Agreement of Repayment).

---

## 6. Reinstatement fees — exact FLHSMV figures

### 6.1 What FLHSMV's insurance pages actually say
- **Insurance lapse / failure to maintain PIP/PDL: reinstatement fee of $150 – $500.** (Uninsured Motorist Rate page, verbatim. Same range on Involved in a Crash?, property-damage section: "Pay a $150 – $500 reinstatement fee, if applicable.")
- **Crash with injuries: $15 reinstatement fee**, if applicable. (Involved in a Crash?, injuries section.)
- FLHSMV's insurance pages **do not break the $150–$500 range into tiers** anywhere in the pages opened for this study.

### 6.2 The $150 / $250 / $500 tier split — NOT on FLHSMV pages
- **SECONDARY** sources (LegalClarity, Maru Insurance, All Laws Decoded), all citing §324.0221(3), F.S., give the tiering as: **1st reinstatement $150; 2nd reinstatement within 3 years $250; 3rd or subsequent within 3 years $500**; the fee resets to $150 after 3 years without a second reinstatement. This is **consistent** with FLHSMV's $150–$500 range (the $150 first-offense figure is the bottom of FLHSMV's own range) but the tier split itself was **not verified on any FLHSMV page** in this study. Do not cite the tier split as an FLHSMV statement.
- **SECONDARY** (same sources): after a lapse reinstatement, proof of coverage must be maintained for **2 years** from reinstatement. Also not stated on the FLHSMV pages opened here.

### 6.3 FLHSMV fee schedule — the $45 trap (FLAG)
- The FLHSMV **Fees** page (opened in full) lists, under Driver License Fees: **"Suspensions … $45.00"**, plus D-6 Suspension $60.00, Court Ordered Child Support Suspension $60.00, DOR Child Support Suspension $45.00, Revocations $75.00, Worthless Check Suspension $55.00, and a $130.00 administrative fee for alcohol/drug-related offenses.
- **The $45 "Suspensions" fee on the fee schedule is a general suspension reinstatement fee. It is NOT the Financial Responsibility insurance reinstatement fee ($150–$500).** The fee schedule does not list the $150–$500 FR range at all. Anyone quoting "$45" for an insurance-lapse reinstatement is conflating two different fees.
- Other FLHSMV fee facts from the same schedule: original/renewal Class E $48.00; replacement license $25.00; late fee $15.00; knowledge retest $10.00; skill retest $20.00; ID cards $25.00; an additional $6.25 service fee may apply to credentials issued in a tax collector office. MyDMV Portal transactions carry a **$2.00 convenience fee** (FLHSMV 2019 notice, search snippet).

### 6.4 Paying the FR reinstatement fee
- Business route (Business Customers page): pay online at https://fdohsamvcsrfl.tylerportico.com/payments/billsearch/ — requires the **Financial Responsibility case number** from the Notice of Suspension letter, plus an email address for the receipt and cardholder name, billing address, security code, expiration date, and billing ZIP (all must match the card).
- If the payment portal returns "We apologize, we cannot find what you are looking for," FLHSMV lists four possible causes: (1) wrong FR sanction number; (2) the insurance company has not yet updated FLHSMV's database — contact the insurer and ask it to report coverage electronically; (3) clearing requirements not yet met (e.g. plate surrender or proof of non-ownership still outstanding) — provide documents to a driver license office or tax collector service center, which can then provide the payment link; (4) the FR sanction number has already been cleared.
- "Once a payment has been processed the stop is removed from the vehicle that is associated with the Financial Responsibility sanction **immediately**. Once the stop has been removed you may be eligible to renew the registration online at MyDMVPortal.gov or by visiting a tax collector's office." (Business Customers page.)
- By phone: **850-617-3000** (24/7 automated system — check driver license, update insurance, pay reinstatement fee after paying ticket, check vehicle record). In person: any Florida driver license service center / tax collector office.
- Mail timelines from DLCheck sanction-help pages (court sanctions, for comparison only): mailed clearances take **7–10 days** from receipt by DHSMV.

---

## 7. SR-22 requirements

- **What an SR-22 is (FLHSMV wording):** "an SR-22 filing (certification of liability insurance)" — a certification filed by the insurance company with the department proving the driver carries the required liability coverage. It is **not** itself an insurance policy; the insurer files it.
- **When FLHSMV requires it (per pages opened):**
  - **Injury crash, at-fault, no full liability coverage:** SR-22 with 10/20/10 coverage for **three years from the designated suspension date**. (Involved in a Crash?, §5.2 above.)
  - **Plain insurance cancellation / lapse (FR7-type case):** **no SR-22 is mentioned anywhere on the FLHSMV insurance pages opened.** The stated cures are: insurer reports current Florida coverage, or buy PIP/PDL coverage, or surrender the plate/registration, plus the $150–$500 fee if the suspension has already taken effect.
- **SECONDARY** (Manatee County Tax Collector FR-case guides, which mirror FLHSMV practice): an FR2 case (citation — failure to provide proof of insurance) requires PIP/PDL certified by an SR-22 for **two years** from the SR-22 certificate effective date if the driver did not have coverage on the offense date; an FR5 point suspension requires BIL/PDL certified by an SR-22 for **three years**. These are tax-collector pages, not FLHSMV pages — flagged as secondary, and the FR-case pages on flhsmv.gov itself were not reached (§9).
- **Submission formats (secondary):** electronic filing by the insurer (fastest), paper original from the agent, or fax/email with coversheet. Insurance cards or policies are **not** accepted in place of an SR-22 where one is required.
- **No FR-44 on FLHSMV insurance pages opened:** FR-44 (DUI-related, higher limits) is not mentioned on any page in this section; do not import it into an FR insurance-lapse case.

---

## 8. How to update insurance information

FLHSMV offers four routes (converging across the pages opened):

1. **Online — MyDMV Portal / Driver License Check (DLCheck).**
   - MyDMV Portal (https://www.flhsmv.gov/motorist-modernization/mydmvportal/): account-based; "Update your automobile insurance information to clear existing sanctions" is a listed portal service. Customers create a secure account verified against FLHSMV records; if verification fails, visit a local office.
   - Driver License Check (https://mydmvportal.flhsmv.gov/home/en/publicweb/dlcheck/): **no account needed** (Express Service). Enter the driver license number; the check shows status and can be used "to update your social security number or insurance information" (Driver Licenses hub). The FLHSMV menu of online services states: "**Online insurance update** — Use Driver License Check to update your insurance information for your fr case." You will need your **FR Sanction number** from the Notice of Suspension letter (secondary source: ShunIns guide to the FLHSMV process).
   - If DLCheck shows "VALID," FLHSMV says it means the department "has already received information and cleared your record" and "You may disregard any notice you received."
2. **By phone — automated system:** **(850) 617-2000** (Customer Service Center; representatives Mon–Fri, 8:00 a.m.–5:00 p.m. EST) and **850-617-3000** (24/7 self-service: check driver license, update insurance, pay reinstatement fee after paying ticket). MyDMV Portal login issues: **850-617-3803**.
3. **By mail:** respond to the FLHSMV letter with proof of insurance; general correspondence address: Bureau of Motorist Compliance, 2900 Apalachee Parkway, Tallahassee, FL 32399-0585 (Room B260F, MS-87 for crash/FR matters; Room A216, MS 99 for insurance-information requests).
4. **In person:** any Florida driver license and motor vehicle service center or tax collector office, with physical proof of insurance. General customer-service contact: (850) 617-2000.
- **Insurer route (usually automatic):** insurers report policy initiation/cancellation electronically within 10 days (§3). If FLHSMV's database still shows no coverage after you bought a policy, FLHSMV's own advice is: "Please contact your insurance company and request they report the coverage electronically to the department." (Business Customers page.)
- **Proof of insurance — acceptable forms:** insurance card, policy, or binder listing PIP and PDL coverage (per the FR-case process described in secondary tax-collector guides consistent with FLHSMV practice); if FLHSMV already received and denied submitted insurance, a letter on insurer letterhead with company/agent contact info, company name, policy number, policy period, company code, vehicle(s) insured, level of coverage (including PIP and PDL), and name of insured.
- **Stops clear in 1–3 business days** for registration renewal after a stop is removed (Electronic Services page, search snippet); the FR stop itself is removed **immediately** once a reinstatement payment processes (§6.4).

---

## 9. Self-insurance (for completeness)

- Per §324.171, F.S., FLHSMV may issue a certificate of self-insurance to qualified individuals or entities. **"If an individual qualifies to be self-insured, they are financially responsible, this is NOT an insurance policy."**
- Surety bonds were removed as a means of obtaining self-insurance effective **July 1, 2013**.
- Firm/partnership/association/corporation requirements (search snippet): certified audited financial statement showing net unencumbered worth of **$40,000 for the first vehicle and $20,000 for each vehicle thereafter** (no excess liability insurance required), or $40,000 for the first vehicle plus an annually formulated additional amount per vehicle with an excess liability policy of $25,000 / $50,000 / $100,000 combined single limits. Certificate limits: 10/20/10 plus PIP per §627.733(3)(b), F.S. Only Florida-registered/leased vehicles are covered.
- Submit to: Fax 850-617-3938; email selfinsurance@flhsmv.gov; mail Bureau of Motorist Compliance, 2900 Apalachee Parkway, MS-98, Tallahassee, FL 32399-0585, Attn: Self Insurance. **Allow up to 30 days** to process; incomplete documentation is denied and must be resubmitted.

---

## 10. Uninsured Motorist Rate (context)

- The uninsured motorist rate "measures the total number of non-commercial vehicles registered but not insured in Florida with at least the minimum coverage of PIP/PDL insurance." (FRIP page; Uninsured Motorist Rate page.)
- **SECONDARY** (Maru Insurance, citing FLHSMV data as of Oct. 4, 2026): 5.06% of Florida registrations without PIP/PDL. Not verified on an FLHSMV page in this study.

---

## 11. Penalties for driving uninsured — what FLHSMV actually says vs. what it does not

**On FLHSMV pages opened:**
- License **and** registration/plate suspension for failure to maintain PIP/PDL; reinstatement fee $150–$500.
- Crash track: SR-22 for 3 years, releases or security deposit, $15 or $150–$500 fee depending on crash type; final judgment: 20-year suspension or until satisfied.
- No FLHSMV page in this section states a court fine for driving uninsured, a jail penalty, or a points assessment for an insurance lapse. No FLHSMV page here states whether a hardship license is available for FR suspensions.

**SECONDARY claims (not FLHSMV-verified, include only with attribution):**
- No hardship/temporary license is available while an insurance-related suspension is active (LegalClarity, All Laws Decoded, citing §324.0221).
- Driving on a suspended license after 30 days can lead to plate seizure on a stop (LegalClarity, citing §324.051 practice).
- A 30-day window to respond applies to **crash** FR suspensions (§324.051: suspension 30 days after FLHSMV receives the crash report unless the driver is found exempt). This 30-day rule is for crash cases, **not** for insurance-cancellation cases — do not apply it to a lapse case.

---

## 12. FLAG — Git-FED's situation

**His record (per brief, from his own license check — NOT from FLHSMV public pages):** FR-CANCELLATION effective **December 7, 2026**, arising from cancelled Root PIP insurance. Brief's working claims: (a) if coverage is on file before Dec 7 the suspension never takes effect; (b) reinstatement fee $150 first offense.

### Verified / consistent
| Claim | FLHSMV verification | Verdict |
|---|---|---|
| Root (or any insurer) reports a PIP cancellation to FLHSMV | Insurers must report cancellation/nonrenewal **within 10 days** (§324.0221; FRIP page). A Root cancellation is exactly the trigger the Business Customers page describes. | **CONSISTENT — mechanism verified** |
| Minimum coverage he must restore | **$10,000 PIP + $10,000 PDL**, continuous through the registration period. | **VERIFIED on FLHSMV pages** |
| If coverage is on file before the suspension date, the suspension never takes effect and no fee is due | Business Customers page: a reinstatement fee is required only if "the requirements have not been met **prior to the original suspension date**." Involved in a Crash? FAQ: bring proof "so your driving privilege is not suspended." DLCheck: a "VALID" result means FLHSMV "has already received information and cleared your record." | **VERIFIED in substance.** The Dec 7, 2026 date itself is from his own record and cannot be checked on public FLHSMV pages. |
| $150 reinstatement fee, first offense | FLHSMV pages state the range **$150–$500** only; $150 is the bottom of that range. The $150 / $250 / $500 tier split is from §324.0221(3) via secondary sources, not from an FLHSMV page opened here. | **CONSISTENT, not directly FLHSMV-verified at tier level.** No contradiction found. |
| Fix it online via MyDMV Portal / DLCheck | MyDMV Portal lists "update your automobile insurance information to clear existing sanctions"; DLCheck offers "online insurance update … for your fr case." | **VERIFIED** |
| Surrendering the plate is an alternative to re-insuring | FLHSMV: surrender tag + registration immediately upon cancelling insurance if the vehicle is no longer owned / inoperable / moved out of state. | **VERIFIED** |

### Flags / cautions
1. **"FR-CANCELLATION" wording — terminology caution.** FLHSMV's insurance pages call the insurance-lapse action a **suspension** (of license and registration). On FLHSMV pages, "cancellation" refers to the **policy** being cancelled by the insurer, and license "cancellation" is a separate action under §322.22 (application/eligibility grounds). The label on his record most likely reflects the FR case type on the Notice of Suspension. **The controlling document is his Notice of Suspension: its FR Sanction number (first digit = case type: FR100 / FR200 / FR700 / FR800 / FR900 per the FLHSMV-linked case index) and its stated original suspension date determine exactly which track he is on.** Do not assume the label alone tells the whole story.
2. **SR-22 is probably NOT required for his case — do not assume it is.** On FLHSMV pages, SR-22 is required for crash-related FR cases (3 years, 10/20/10) and, per secondary tax-collector guides, for citation (FR2) and point-suspension (FR5) cases. A plain PIP-cancellation lapse is cured by coverage on file, plate surrender, or the fee — no SR-22 is mentioned for it on FLHSMV. If his FR case turns out to be crash- or citation-based rather than a pure lapse, the SR-22 analysis changes completely.
3. **The $45 fee-schedule figure is a trap.** If anyone quotes $45 to clear this, that is the general "Suspensions" fee on the FLHSMV fee schedule (§6.3), not the FR insurance reinstatement fee ($150–$500). Paying $45 would not clear an FR insurance case.
4. **Deadline discipline.** The operative date is the **original suspension date on his Notice of Suspension (Dec 7, 2026, per his record)**. Coverage must be **reported electronically by the insurer** and on file with FLHSMV before that date — buying a policy is not enough if the insurer has not reported it within its 10-day window. If the portal says the sanction cannot be found, FLHSMV's own troubleshooting is: wrong FR number, insurer has not updated the database yet, or clearing requirements (e.g. plate surrender) are still outstanding.
5. **Corroborating real-world example (non-FLHSMV source, for pattern only):** a FLHSMV "Notice of Intent to Suspend and Final Order" dated **November 17, 2026**, posted publicly Nov 20, 2026, set suspension effective **December 2, 2026** after People's Trust reported a policy cancellation, and stated that obtaining Florida insurance before Dec 2 clears the record via MyDMVPortal.flhsmv.gov. Same notice structure, same cure-before-date logic, different driver/insurer/date. It corroborates the mechanism but is not Git-FED's notice.
6. **His Dec 7 date vs. the 30-day crash rule:** do not import the 30-day crash-suspension window (§324.051) into this lapse case. The lapse timeline is driven by the insurer's 10-day report and the date printed on his own Notice of Suspension.

### Contradictions found
| # | Contradiction | Resolution |
|---|---|---|
| C1 | **consultingtimes.com** (secondary) claims a 30/60/90-day schedule for lapsed insurance with $25 "probationary" and "$500 after 90 days" fees, plus a 30-day duty to notify DHSMV. | **Contradicts FLHSMV.** No FLHSMV page states any 30/60/90-day fee schedule or $25 FR fee. FLHSMV's figures are $150–$500 (insurance pages) and the insurer's 10-day reporting duty. Disregard the consultingtimes.com schedule. |
| C2 | **FLHSMV Fees page: "Suspensions $45.00"** vs. **FLHSMV insurance pages: "$150 – $500."** | **Not a true contradiction — two different fees.** $45 is the general suspension reinstatement fee on the fee schedule; $150–$500 is the FR insurance reinstatement range. Flagged here because the two numbers sit on the same department's site and are easily conflated. |
| C3 | **Third-party $150 / $250 / $500 tier split** vs. **FLHSMV range-only ($150–$500).** | **No contradiction; granularity gap.** The tier split (secondary, citing §324.0221(3)) fits inside FLHSMV's range, with $150 first offense at the bottom. The $150 first-offense claim is therefore consistent with FLHSMV but not directly confirmed by an FLHSMV page. |
| C4 | **Third-party "suspension up to three years" for a lapse** vs. **FLHSMV pages silent on lapse duration.** | **Unresolved gap, not a contradiction.** FLHSMV states 3 years only for crash SR-22 cases. The lapse duration was not found on any FLHSMV page opened; it needs the FR case pages (§9). |

**Bottom line for Git-FED:** nothing on FLHSMV's pages contradicts the brief's two working claims. Coverage on file before Dec 7, 2026 should prevent the suspension from taking effect with no fee due; if it does take effect, the FLHSMV-stated fee range is $150–$500, with $150 as the first-offense figure per the statute as reported by secondary sources. The two things to verify from his own paperwork (not from public FLHSMV pages) are the FR Sanction number/case type on his Notice of Suspension and confirmation via DLCheck that the new coverage is actually on file before Dec 7.

---

## 13. Gaps / pages not reached

1. **Main insurance index, https://www.flhsmv.gov/insurance/** — `browser.open` returned HTTP 429 (rate limit); per instruction the request was not retried. Its sub-links (individual customers, FR case pages) could not be enumerated from the live page. The A-to-Z "Insurance (auto)" entry points here.
2. **Other Common Suspensions and Revocations** (full text) — same 429 block; only the search-snippet portion (Financial Responsibility Suspensions heading, child-support and death/serious-injury sections) was captured.
3. **FR case pages FR100 / FR200 / FR700 / FR800 / FR900** — linked from the Pinellas County Tax Collector suspensions page to flhsmv.gov, but their exact FLHSMV URLs were not returned by search and were not opened. These are the pages that would state, per case type, the exact cure steps, SR-22 duration, and fee for a lapse case like Git-FED's.
4. **Fee-tier split ($150/$250/$500) and 2-year post-reinstatement proof period** — stated only by secondary sources citing §324.0221; not found on any FLHSMV page opened.
5. **Maximum duration of a plain insurance-lapse suspension and hardship-license availability for FR suspensions** — not stated on any FLHSMV page opened; secondary sources say up to 3 years and no hardship license, respectively.
6. **RS-36 Insurance Verification procedure** — referenced by RS-01 but not opened; it governs registration-time insurance verification, including the 20-day suspension trigger when an insurer denies coverage given at registration (per secondary reporting of RS-36, rev. April 2025).
7. Page crawl dates are search-engine crawl dates (Jan–Nov 2026), not FLHSMV "last updated" stamps; the FRIP, Business Customers, and Self-Insurance pages show crawl dates of January 2026 and may predate 2026 changes. Treat fee/range figures as current per the live pages as crawled, and re-check DLCheck/MyDMV Portal for the operative numbers on Git-FED's own case.

---

## 14. Key numbers — quick reference (all FLHSMV unless marked SECONDARY)

| Item | Figure |
|---|---|
| Minimum PIP | **$10,000** |
| Minimum PDL | **$10,000** |
| BIL for crash FR cases | **$10,000 per person / $20,000 per crash** |
| Insurer report of cancellation/new policy | **within 10 days** |
| FR reinstatement fee (lapse / property-damage crash) | **$150 – $500** |
| FR reinstatement fee, 1st / 2nd / 3rd+ within 3 yrs | **$150 / $250 / $500 (SECONDARY, §324.0221(3))** |
| FR reinstatement fee (injury crash) | **$15, if applicable** |
| General suspension fee (fee schedule — NOT the FR fee) | **$45.00** |
| SR-22 duration, injury crash | **3 years from suspension date** |
| SR-22 duration, citation/point cases | **2 years / 3 years (SECONDARY)** |
| Final judgment suspension | **20 years or until satisfied** |
| Final judgment submission window | **30 days after judgment date** |
| Crash report threshold (police notification) | **$500 damage or any injury/death** |
| Insurance-info request processing | **10 working days** |
| Self-insurance processing | **up to 30 days** |
| Self-insurance net worth (firm) | **$40,000 first vehicle + $20,000 each additional** |
| MyDMV Portal convenience fee | **$2.00** |
| Customer Service | **(850) 617-2000** (Mon–Fri 8 a.m.–5 p.m. EST); automated **850-617-3000** (24/7); portal login help **850-617-3803** |
| Stop removal after reinstatement payment | **immediate** |
| Registration renewal after stop cleared | **1–3 business days** (system update) |
# 09 — Points, Violations & Driver Improvement

**Study:** flhsmv.gov (Florida Dept. of Highway Safety and Motor Vehicles)
**Section scope:** the point system, point-suspension thresholds, Basic vs Advanced Driver Improvement courses, election rules and limits, court-ordered vs voluntary school, point treatment after school, bad-driver reporting, driving privileges.
**Date of research:** November 23, 2026. All facts below come only from flhsmv.gov pages (full-page reads unless marked "search snippet"). Crawl dates shown are the dates the fetched copies were crawled, as reported by the fetch tool.

---

## 1. Pages studied

| # | Page | URL | How read |
|---|------|-----|----------|
| 1 | Driver Licenses & ID Cards (landing) | https://www.flhsmv.gov/driver-licenses-id-cards/ | Full page |
| 2 | A to Z Guide | https://flhsmv.gov/a-to-z-guide/ | Full page |
| 3 | What is Basic Driver Improvement (BDI) and how do I find the approved listing of BDI course providers? | https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/driver-improvement-schools/basic-driver-improvement-bdi-find-approved-listing-bdi-course-providers/ | Full page (crawled 2025-01-30) |
| 4 | Driver Improvement Schools (overview) | http://flhsmv.gov/driver-licenses-id-cards/education-courses/driver-improvement-schools/ | Full page (crawled 2026-03-25) |
| 5 | What is Advanced Driver Improvement (ADI) and how do I find the approved listing of ADI course providers? | https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/driver-improvement-schools/advanced-driver-improvement-adi-find-approved-listing-adi-course-providers/ | Full page (crawled 2026-03-27) |
| 6 | Traffic Citations | http://www.flhsmv.gov/FHP/traffic/ | Full page (crawled 2026-01-13) |
| 7 | Driver Improvement Courses FAQ | http://www.flhsmv.gov/ddl/dicfaqa.html | Full page (crawled 2026-01-05) |
| 8 | What are 3 crashes in 3 years and how do I complete this requirement? | https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/driver-improvement-schools/3-crashes-3-years-complete-requirement/ | Full page (crawled 2026-01-16) |
| 9 | Education & Courses (landing) | https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/ | Full page (crawled 2026-10-29) |
| 10 | Driver License Suspensions and Revocations (landing) | https://www.flhsmv.gov/driver-licenses-id-cards/driver-license-suspensions-revocations/ | Full page (crawled 2026-11-16) |
| 11 | Other Common Suspensions and Revocations | https://www.flhsmv.gov/driver-licenses-id-cards/driver-license-suspensions-revocations/other-suspensions-revocations/?ref=filter%2Fresourcetype%2Fall | Search snippet (direct fetch returned HTTP 403) |
| 12 | Report An Unsafe Driver | https://www.flhsmv.gov/driver-licenses-id-cards/medical-review/report-an-unsafe-driver/ | Full page (crawled 2026-01-15) |
| 13 | Medical Review (landing) | https://www.flhsmv.gov/driver-licenses-id-cards/medical-review/ | Search snippet |
| 14 | Appendix C — Uniform Traffic Citation violation/points table (PDF, REVISED 4-2-2025) | https://www.flhsmv.gov/pdf/courts/utc/appendix_c.pdf | Full PDF text (crawled 2026-03-25) |
| 15 | Teen Drivers | https://www.flhsmv.gov/driver-licenses-id-cards/teen-drivers/ | Search snippet |
| 16 | Clearing Failure to Complete Traffic Collision Avoidance Course (services.flhsmv.gov sanction help page) | https://services.flhsmv.gov/DLCheck/SanctionHelpPages/Sanction15Help.aspx | Search snippet |

**Not retrievable:** the standalone "Points & Suspensions" page referenced by the Traffic Citations page ("A breakdown of points can be found on our Points & Suspensions page") — its URL was not exposed in any fetched page text or search result, so the point table in §2 below is taken from the BDI page, which reproduces it in full under the heading "The Point System." The A-to-Z entries "Points (Driver License)" and "Violations – Points" likewise point to that same BDI-page table in the indexed copies.

---

## 2. The point system — points per violation

Source: BDI page, section "The Point System" (full-page read).

> "Points are assessed for moving violations where an adjudication of guilt is found, which can cause the loss or restriction of driving privileges. If too many points are accumulated during a certain period of time (12 points within 12 months, 18 points within 18 months or 24 points within 36 months), your license will be suspended."

Point table as published on the BDI page ("If you choose to pay the civil penalty or are adjudicated guilty by a judge, your driver record will be assessed as follows"):

| Violation | Points |
|---|---|
| Moving violations (general) | 3 |
| Speeding 15 m.p.h. or less over posted speed | 3 |
| Speeding more than 15 m.p.h. over posted speeds | 4 |
| Passing stopped school bus | 4 |
| Moving violation (non-speeding) resulting in a crash | 4 |
| Unlawful speed resulting in a crash | 6 |
| Reckless driving (criminal traffic violation) | 4 |
| Leaving scene of crash with damage | 6 |
| Littering | 3 |
| Violation of child restraint laws | 3 |

Notes from Appendix C (the FLHSMV Uniform Traffic Citation table, revised 4-2-2025) that refine the table:

- "Any moving violation with points, excluding speeding, resulting in a crash = 4 points."
- Littering while using a motor vehicle (s. 403.413(4), misdemeanor) receives 3 points "regardless of whether adjudication was withheld" [see 322.27(3)(d)9].
- Citations for violations not found in Appendix C get violation code 380 (noncriminal) or 383 (criminal).
- Red-light camera and school-bus camera violations carry 0 points (Appendix C: 316.074(1) red-light camera, "M m 0 158 547"; this 0-point treatment also appears in the BDI-page-era guidance, not on the BDI page itself).
- Non-moving violations carry 0 points (Appendix C classification: N = non-moving infraction, points column 0 throughout).

### Drivers under 18

> "Any driver under the age of 18 who accumulates six or more points within a 12 month period is automatically restricted to driving for 'Business Purposes Only' for one year. If additional points are accumulated, the restriction is extended by 90 days for every additional point received."
> (BDI page; same rule on Teen Drivers page, citing s. 322.161, Fla. Stat.: restriction lasts 12 months or until age 18, whichever happens first.)

---

## 3. Point-suspension thresholds (12 / 18 / 24)

Identical wording on the BDI page, the ADI page, and the Driver Improvement Schools overview:

- **12 points within 12 months — 30-day suspension**
- **18 points within 18 months — 3-month suspension**
- **24 points within 36 months — 1-year suspension**

BDI page: "If too many points are accumulated during a certain period of time (12 points within 12 months, 18 points within 18 months or 24 points within 36 months), your license will be suspended."

---

## 4. Basic Driver Improvement (BDI) — election rules

### Who can elect, and how

Source: BDI page (full read) and Driver Improvement Schools overview (full read).

- "In order to qualify for a Basic Driver Improvement (BDI) course to eliminate the assessment of points, **drivers must voluntarily elect this option within 30 days** (section 318.14 (4), Florida Statutes) from the **citation date and, prior to attending the course**, drivers must inform the clerk of court in the county where the citation was issued of this election. Drivers must also pay an election fee to the clerk of court in the county where the citation was issued."
- "**Drivers may not elect to take the BDI, in lieu of points, after the initial 30-day period from the citation date**."
- "Options for satisfying a traffic citation will be listed on the back of the citation. Drivers are required to choose one of the three options within 30 days of the citation date."
- Overview: "Drivers must voluntarily elect to attend basic driver improvement school within 30 days of the traffic citation. If an election is not made, their right to elect school is forfeited and points are assessed."
- Overview: "Within the 30-day window, the driver must pay the fine and fees for the traffic citation. Upon payment, drivers should also notify the court if they are electing to attend basic driver improvement school. If the fee is not paid within 30 days, their license will be suspended for failure to pay."
- Traffic Citations page: "Customers who are issued a Uniform Traffic Citation have the option to pay the citation, contest the citation or take a driver improvement course. Customers have 30 days to make this election with the clerk of court listed on the citation. Failure to elect within 30 days may result in additional fines along with a suspension of the driving privilege."
- Education & Courses landing: "If you would like to elect to take the Basic and Advance Driver Improvement Courses, you must make the decision within 30 days of receiving the traffic citation."

### Benefits of electing and completing BDI

BDI page:

- "Points may not be added to the driver license record and adjudication of guilt is withheld."
- "Civil penalty (Fine) will be reduced."
- "Insurance companies cannot impose or request an additional premium, cancel a policy, or issue a non-renewal notice on any insurance policy or contract because of any traffic infraction when adjudication has been withheld and no points have been assessed for a traffic infraction unless the traffic infraction involved a traffic crash in which the insurer was at fault and the insurance company incurred a loss."

Traffic Citations page: "Customers who receive a traffic citation may be eligible for an **18% reduction in citation fees** and points may be withheld if they take a driver improvement course." / "By electing to attend the Basic Driver Improvement Course, the traffic citation fine is reduced by 18%. In addition, each Clerk of the Court imposes appropriate court cost."

FAQ: "When a driver completes a driver improvement course to satisfy a violation: Adjudication is withheld (not convicted of the violation) per section 318.14, Florida Statutes; No points will be assessed against the driver license for the violation; and Insurance companies cannot impose an additional premium or refuse to renew a policy for motor vehicle insurance solely because the insured committed a non-criminal traffic infraction. Exceptions include: A second infraction within 18 months; A third infraction within 36 months; or Exceeding the speed limit by more than 15 mph."

### Who may NOT elect BDI

BDI page — "Drivers may not make an election to attend a BDI course if they have":

- "Made an election to attend a BDI course in the preceding 12 months;"
- "Made **five** elections in a lifetime;" (see §8 — this is the disputed figure)
- "A Commercial Driver License (CDL); or"
- "Been cited for going 30 mph above the posted speed limit."

FAQ exclusions add: "All criminal violations" and "Drivers who hold a Commercial Driver License (CDL) regardless of the type of vehicle they are driving at the time of the violation."

### Completion deadline and failure to complete

- FAQ: "Once the clerk is notified of a driver's intent to attend a course, they have **between 60 and 90 days from the date of the citation** to complete the course and present proof of completion to the clerk of court in the county where the citation was issued."
- Overview: "Drivers must complete the traffic school course within the court-required time period. If the court-required time is not met, their license will be suspended for failing to attend course."
- FAQ: "A person who elects to attend a driver improvement course and has paid the civil fine, but fails to attend the school within the time specified by the court is considered to have admitted to the infraction and is adjudicated as guilty. In this case, the person must pay the clerk of court the amount deducted from their fee because of the election to attend a course, and **a processing fee of up to $18**. No additional penalties or court costs are imposed. The clerk of court will notify the DHSMV of the person's failure to attend the driver improvement course and points for the violation are then added to the individual's driving record."
- FAQ: "Once the affidavit is signed and recorded by the court, drivers may not choose the school option again for 12 months and all payments are forfeited."

### Course-completion reporting

- Overview: "All course providers electronically report all FLHSMV-approved school completions to the FLHSMV. Please allow **24 to 72 hours** for school completions to be posted." / "FLHSMV does not accept paper certificates for any licensing purpose."
- Overview / Traffic Citations: the driver must still provide proof of completion and documentation of paid fines/fees to the court/clerk; "It is the driver's responsibility to meet the court reporting requirements." (Traffic Citations: "Upon completion of the Basic Driver Improvement Course, you must take the certificate of completion to the Clerk of Court where you made the election.")
- BDI is a 4-hour course: the Traffic Collision Avoidance Course sanction help page (services.flhsmv.gov) instructs drivers to "complete a state-approved 4-hour basic driver improvement course."

---

## 5. Mandatory BDI (court-ordered / conviction-triggered school)

### Mandatory school offenses — s. 322.0261

Overview, "Mandatory School Requirements": "Drivers with a valid Florida driver license who have been convicted of the following offenses in Florida per section 322.0261, Florida Statutes or in another state (sections 322.24 and 322.44, Florida Statutes), are required to attend a basic driver improvement course."

- Failure to obey a traffic control signal
- Failure to obey a steady red light
- Failure to stop for a school bus
- Racing on the highway
- Racing on the highway – spectator
- Reckless driving

> "Drivers have **90 days from the citation date** to complete the required school or the driving privilege will be canceled. The license will remain canceled until the school requirement is completed."

Traffic Citations page (same list, as convictions requiring a course "in addition to the fine"): passing a school bus; racing; reckless driving; running a red light; traffic control device.

### Other mandatory-BDI triggers (BDI page)

"A BDI course is mandatory when cited for one of the following reasons":

- Electing to attend BDI school instead of having points assessed from a citation;
- Drivers who were cited for a crash in which they were found at fault and resulted in anyone being transported to the hospital;
- Drivers with two crashes within a two-year period that resulted in property damage greater than $500; or
- Drivers convicted of: passing a school bus when it displayed a stopped signal; racing on a highway; highway racing – spectator; reckless driving; or running a red light.

### Court-ordered school generally

Overview: "If a driver has been ordered by a court to attend a driver improvement school, they must notify the court once they have completed the school and also provide the necessary documentation to the court."

---

## 6. Advanced Driver Improvement (ADI)

ADI page and overview, identical wording:

> "Drivers must complete an Advanced Driver Improvement (ADI) course if their driver license was suspended in Florida for accumulation of points, as a habitual traffic offender (non-DUI related), or by court order."

Point thresholds repeated on the ADI page: 12 points within 12 months (30 day suspension); 18 points within 18 months (3 month suspension); 24 points within 36 months (1 year suspension).

- ADI is a **12-hour** course: the "3 crashes in 3 years" page requires drivers to "Complete 12 hours within an approved FLHSMV Advanced Driver Improvement course."
- Commercial Driving Schools overview: "ADI is the course customers complete if they received a point suspension or are a non-DUI Habitual Traffic Offender. BDI is the course customers complete if they made an election with the Clerk of Court to attend a BDI course instead of receiving points for a citation, or if they were ordered to mandatorily attend a BDI course."

### BDI vs ADI — summary

| | Basic Driver Improvement (BDI) | Advanced Driver Improvement (ADI) |
|---|---|---|
| Length | 4 hours | 12 hours |
| When used | Voluntary election within 30 days of citation to avoid points; or mandatory after listed convictions/crashes | After a point suspension, as a non-DUI habitual traffic offender, or by court order |
| Effect | No points assessed; adjudication withheld; fine reduced 18% | Required step to retain/regain driving privilege after suspension; does not itself erase points already assessed |
| Election limits | Once in 12 months; lifetime cap disputed — see §8 | No election; imposed, not chosen |

---

## 7. Three crashes in three years / other related requirements

"3 crashes in 3 years" page: drivers at fault in three crashes within a three-year period (convicted of, or pled nolo contendere to, a traffic offense giving rise to a crash under s. 322.0261(1)(c)) must:

- Complete 12 hours within an approved FLHSMV Advanced Driver Improvement course;
- Complete four hours of behind-the-wheel training from a FLHSMV-approved, Florida licensed commercial driving school (CDS);
- Pass an extended road test with a driver license examiner or tax collector licensing agent.
- "Failure to complete these requirements within **90 days** of the conviction will result in a license cancellation."
- "Additional crashes will result in more requirements and penalties."

Overview: the 3-crashes course "must include behind-the-wheel training and an assessment of driving ability."

### Habitual Traffic Offender (HTO)

Other Common Suspensions and Revocations page (search snippet):

> "A Habitual Traffic Offender is a person who has accumulated **fifteen moving violations in which points were assessed in five years, or three major violations in five years**." Major offenses include driving while license suspended or revoked; DUI/DWI or other alcohol related convictions; failure to stop and render aid in the event of a motor vehicle crash; driving a commercial motor vehicle while disqualified; manslaughter in which a motor vehicle was involved; any felony in the commission where a motor vehicle is used. "If a person is determined to be a Habitual Traffic Offender, an individual's driver license will be **revoked for five years**."

### Other suspension/revocation context (Driving Privileges)

- Suspensions and Revocations landing page: reinstatement information covers "unpaid traffic tickets, failure to comply or appear at a traffic summons, point suspensions, being a habitual traffic offender, child support delinquencies and more."
- Other Common Suspensions: child support delinquency can result in an indefinite suspension (not eligible for a hardship license); a non-DUI violation resulting in death or serious bodily injury draws a suspension of up to one year; a Chapter 893 drug-related conviction draws a suspension/revocation of at least one year.

---

## 8. ⚠️ FLAG — Lifetime election limit: FLHSMV contradicts itself, and contradicts Muse3's "8"

**Muse3's claim (to be checked):** traffic school may be elected once in 12 months, with a **lifetime limit of 8** per Fla. Stat. 318.14(9).

**What FLHSMV actually says — exact quotes:**

Three FLHSMV pages say **FIVE** in a lifetime:

1. **BDI page (full-page read):** "Drivers may not make an election to attend a BDI course if they have: — Made an election to attend a BDI course in the preceding 12 months; — **Made five elections in a lifetime**; — A Commercial Driver License (CDL); or — Been cited for going 30 mph above the posted speed limit."
2. **Driver Improvement Schools overview (full-page read, crawled 2026-03-25):** "If a driver receives a non-criminal moving violation and does not have a commercial driver license, they may elect to attend a FLHSMV-approved basic driver improvement school **once every 12 months or a total of five times within their lifetime**."
3. **Traffic Citations page (full-page read, crawled 2026-01-13):** "**A customer may only elect to take a driver improvement course five times within their lifetime.**"

One FLHSMV page says **EIGHT** in a lifetime:

4. **Driver Improvement Courses FAQ (full-page read, crawled 2026-01-05):** "Drivers can choose to attend a driver improvement course **once in any 12-month period and no more than eight times in a lifetime**."

**Additional wrinkle:** the search-index snippet of the BDI page itself (same URL as #1, different crawl) reads "Made **eight** elections in a lifetime" — i.e., even the BDI page has carried both numbers in different crawls. The full-page read obtained for this study says five; the search snippet says eight.

**Verdict on the flag:** Muse3's "lifetime limit 8 per Fla. Stat. 318.14(9)" matches only the FAQ page (and an older crawl of the BDI page). It is **contradicted by three FLHSMV pages** — the BDI page itself, the Driver Improvement Schools overview, and the Traffic Citations page — which all say **five**. The 5-vs-8 figure is an unresolved internal FLHSMV contradiction; the majority of current FLHSMV pages, including the most recently crawled overview (2026-03-25), say five. Anyone relying on the "8" figure should verify against the clerk of court / current statute before acting.

**The other Muse3 claims check out against FLHSMV pages:**

- "Once in 12 months" — **CONFIRMED** on all four pages above.
- "Election within 30 days of citation" — **CONFIRMED** (BDI page, overview, Traffic Citations, Education & Courses landing; cites s. 318.14(4)).
- "Failure to dim headlights is a moving violation worth 3 points" — **CONFIRMED** (see §9).

---

## 9. The Git-FED ticket: Fla. Stat. 316.238, failure to dim headlights

Ticket as given: Oct 24, 2026, Fla. Stat. 316.238 (failure to dim headlights).

FLHSMV Appendix C (Uniform Traffic Citation table, REVISED 4-2-2025), exact lines:

> "316.238 HEADLIGHTS - FAIL TO DIM **M m 3 60 195**"
> "(1)(a) Fail dim headlights/improper adjustment **M m 3 60 195**"
> "(1)(b) Fail dim lights from rear **M m 3 60 195**"

Appendix C key: **M = Moving infraction**; m = fines/fees mailable within 30 calendar days; **3 = 3 points**; **60 = $60 base fine**; 195 = violation code.

So on FLHSMV's own citation table, a 316.238 failure-to-dim ticket is a **moving violation carrying 3 points** with a $60 base fine — **Muse3's claim is confirmed exactly**.

Related Appendix C entries for context:

- 316.2385, low-beam headlights — fail to use during fog/smoke/rain/twilight hours: M, 3 points, $60, code 436.
- 316.237, multiple-beam equipment standards (improper adjustment/distribution, beam indicator): N (non-moving), 0 points, $30, code 137 — i.e., equipment defects under 316.237 are non-moving, while the failure-to-dim conduct under 316.238 is moving.

**Application to the Oct 24, 2026 ticket (per FLHSMV pages only):**

- It is a non-criminal moving violation, so BDI election is in principle available: elect within 30 days of the citation date (i.e., by Nov 23, 2026), notify the clerk of court in the county of issuance before attending, pay the fine/fees (with the 18% election reduction), complete the 4-hour BDI course within the court-set window (60–90 days from citation per the FAQ), and submit proof to the clerk. Result if completed: no points assessed, adjudication withheld.
- Barriers that would block election (BDI page): a BDI election in the preceding 12 months; having already used the lifetime cap (five per most FLHSMV pages, eight per the FAQ — see §8); holding a CDL; or being cited for 30+ mph over the limit (not applicable to 316.238).
- If the election is not made within 30 days, the right to elect is forfeited and the 3 points are assessed on payment/conviction.

---

## 10. Point reduction after school — what FLHSMV actually says

FLHSMV does **not** describe BDI as removing or reducing points already on a record. Its framing is preventive only:

- Electing and completing BDI means "points may not be added to the driver license record and adjudication of guilt is withheld" — the points for that citation are never assessed in the first place.
- No FLHSMV page in this section describes a mechanism to subtract points already assessed (e.g., no "−3 points for completing school" rule). ADI after a point suspension is a reinstatement/retention requirement, not a point eraser.
- Points already assessed stand until they age off the record under the point-system windows (12/18/36 months for suspension purposes).

---

## 11. Reporting a bad driver / unsafe driver

A-to-Z entries "Bad Driver, Reporting" and "Reporting a Bad Driver" lead to the Medical Review program, not a general bad-driving hotline:

- "Florida law authorizes any physician, person, or agency to report to FLHSMV an applicant or licensed driver who may not safely operate a motor vehicle due to a medical condition. These referrals must be based on medical conditions or symptoms that could affect safe driving and **not the age of the driver**."
- "The report must be made in writing, giving the **full name, date of birth, address, and a full description of the alleged physical or mental disability** that could affect the driving ability of any person over 15 years of age. If information is missing or not included it will invalidate the form. The Medical Referral Form (**72190** English / 72190 Spanish) should be used to report these concerns."
- "Medical reporting is **confidential under section 322.126, Florida Statutes**, and no civil or criminal action may be brought against any physician, person, or agency for providing this information."
- FLHSMV receives referrals from courts, doctors, law enforcement, other state agencies, driver license personnel and concerned relatives or citizens.

---

## 12. Gaps and caveats

1. **Lifetime cap unresolved (see §8).** FLHSMV says five on three pages and eight on one page (FAQ); the BDI page itself has shown both numbers in different crawls. Do not rely on either number without checking the clerk of court / current statute.
2. **"Points & Suspensions" standalone page not retrievable.** Traffic Citations links to it, but its URL was not exposed in fetched text or search results; the point table here comes from the BDI page instead. The A-to-Z "Points (Driver License)" and "Violations – Points" entries resolve to the same BDI-page content in indexed copies.
3. **Other Common Suspensions page** could only be read via search snippet (direct fetch returned HTTP 403); HTO and related facts from it are marked as snippet-sourced.
4. **Fetch dates vary.** The BDI full-page read is from a 2025-01-30 crawl while the overview is from 2026-03-25; the 5-vs-8 discrepancy may partly reflect page updates over time. The most recently crawled pages (overview 2026-03-25, suspensions landing 2026-11-16) are the freshest copies obtained.
5. **No FLHSMV page in this section states a reinstatement fee for point suspensions**; that figure ($45) appears only on third-party sites and was not recorded here.
6. This section is FLHSMV pages only. Statute text (Fla. Stat. §§ 318.14, 322.26, 322.27, 322.291, 316.238) was not used as a source except where FLHSMV pages themselves cite it.
# 10 — Vehicle Registration & Titles (flhsmv.gov)

**Source:** Florida Department of Highway Safety and Motor Vehicles — https://flhsmv.gov/ and https://flhsmv.gov/a-to-z-guide/
**Study date:** 2026-11-23. All facts below are taken only from flhsmv.gov pages listed in §12 (page text as crawled by the browser tool, plus search-result excerpts where a page could not be re-opened — see Notes & Gaps). No fees, deadlines or penalties are invented; where FLHSMV states a rule without a dollar figure, that is recorded as such.
**Scope:** Vehicle Registration, Titles, Duplicate Registration, Duplicate Title, Electronic Lien & Title (ELT), Disabled Parking Permits, Dealers, Importing Vehicles, Boat (Vessel) Registration and Titles, Address Change — plus the directly linked Fees schedule, MyDMV Portal / MyFlorida app, License Plates & Registration FAQ, and New Resident title/registration rules.

---

## 1. Overview — how FLHSMV organises this area

- The hub page is **Motor Vehicles, Tags & Titles** (`/motor-vehicles-tags-titles/`). Its sections are: Liens & Titles; License Plates & Registration; Dealers, Installers, Manufacturers, Distributors, and Importers; For Commercial Motor Vehicle Drivers; Vessels; Military & Veterans Information; Disabled Person Parking Permits; Fraud; Motorist Modernization; Public Records Request; Make an Appointment.
- Motor-vehicle work is done in person at county tax collector / license plate agent / motor vehicle service centres (400+ locations statewide, per the hub page), or online via **MyDMV Portal** (`mydmvportal.flhsmv.gov`) and the **MyFlorida** mobile app. Initial registrations must be done in person (see §2).
- The A-to-Z Guide (`/a-to-z-guide/`) lists the in-scope entries under their letters: Address Change on Vehicle Registration, Driver License or ID card; Auto Dealers; Boat Registration and Titles; Costs for License, Tag or Title; Dealer Handbook; Dealers; Disabled Parking Permits; Disabled Parking Abuse Complaint Form; DMV Procedures Manual; Duplicate Registration; Duplicate Title; Electronic Lien & Title; Fees; Importing Vehicles; License Plates; Motor Vehicle Check; Moving to Florida; New to Florida; Print your electronic Title; Registration (Motor Vehicle); Registration (Motor Vehicle Tag) Fees; Renew Vehicle Registrations, Driver Licenses or ID Cards Online; Selling a Vehicle; Specialty License Plates; Tag Fees; Title Fees; Title (Motor Vehicle); Vehicle Fees; Vehicle History; Vessels. The A-to-Z page itself is an index only — each entry links out to the pages studied below.

## 2. Vehicle registration — general rules

From **Motor Vehicle Registrations** (`/motor-vehicles-tags-titles/license-plates-registration/motor-vehicle-registrations/`):

- A vehicle must have a valid registration to operate on Florida roads.
- Vehicles with out-of-state registrations must be registered **within 10 days** of the owner becoming employed, placing children in public school, or establishing residency.
- A complete registration consists of:
  - a metal plate (number must match the registration and decal), attached per §320.38, Florida Statutes;
  - a registration certificate in the possession of the operator or carried in the vehicle at all times (§320.0605);
  - a registration decal (validation decal) affixed in the square provided in the upper right-hand corner of the Florida license plate.
- This complete set is evidence of having paid the registration taxes and fees.
- **Hope Scholarship:** on/after 1 Oct 2018, when purchasing/registering a motor vehicle qualifying for the Hope Scholarship Program, the owner may designate **$105 per vehicle** to an eligible nonprofit scholarship-funding organisation (or the amount of state sales tax due, if less). The dealer, county tax collector or private tag agent remits the contribution; the form is the Hope Scholarship Contribution Election Form, submitted by mail with the Application for Certificate of Title With/Without Registration and payment of sales tax.

### 2.1 Initial registration

- **$225 Initial Registration Fee** must be paid when the owner does not have a license plate, or a record of a license plate registered in their name for a vehicle they previously owned (in Florida), to transfer to a newly acquired vehicle.
- An initial registration must take place **in person** at a local service centre at the time of titling, submitting:
  - proof of identity (required for all owners);
  - proof of Florida insurance;
  - a completed Application for Certificate of Title With/Without Registration (**HSMV form 82040**).
  - "Some situations may require additional documentation."
- **Exemption from the $225 fee:** per the License Plates & Registration FAQ, if a license plate is not registered to a replacement vehicle, the plate must be turned in to a local office to prevent a driver license suspension; when an old plate is turned in, the registration is stamped "canceled", and this may be used to exempt the $225 Initial Registration fee when a replacement vehicle is registered.

### 2.2 Renewal — periods, deadlines, channels

- Customers may renew for **one or two years** and may renew **up to three months in advance** of the registration expiration.
- Vehicle registrations **expire at midnight on the first owner's birth date**, unless the owner is a business. (Heavy trucks: see §2.5.)
- **Online (MyDMV Portal):** one- or two-year renewals; duplicate registration certificate if lost. The customer must provide personal identifying information of the owner to log in. If FLHSMV cannot verify valid insurance, **no registration will be issued online or in person**. All online electronic payments are charged a **$2.00 processing fee** in addition to the total transaction. Registrations should arrive by mail within **7–10 business days**; an emailed confirmation receipt (customer must select "yes", enter an email address and click "Send Email Confirmation" on the payment confirmation page) may be used as proof of payment until it arrives. If 20 calendar days have passed without receipt, inquire about a lost-in-transit replacement at a local service centre or by calling Customer Service **(850) 617-2000**. If unable to renew online, go to a local service centre or call (850) 617-2000.
- **Mobile app (MyFlorida):** renew up to **five vehicles and/or vessels at once**, for one or two years, with only one processing fee. Requires the license plate or VIN. If valid insurance cannot be electronically verified, no registration will be issued on the app. Offers: one-/two-year renewals, duplicate registration certificate if lost, Motor Vehicle Information Check and information regarding registration stops; payment by credit card or checking account. A **$4.00 processing fee** per transaction for credit-card payments, or **$3.75** for checking-account payments. Customers receive a digital document to use until the registration arrives in the mail. **No address changes can be made on the mobile app.** The app is free via iTunes and Google Play; it is an authorised payment & service provider for FLHSMV, operated by PayIt.
- **Renewal notices:** per the FAQ, Florida Statutes do not require the department to provide renewal notices; notices are provided as a courtesy, and a county may elect not to send one. A notice may also get lost in the mail — the owner remains responsible for renewing on time.

### 2.3 Delinquent (late) renewal — penalty

From the Motor Vehicle Registrations page, §320.07(4)(a), Florida Statutes:

- A **delinquent registration fee** is imposed on any customer who fails to renew registrations of motor vehicles and mobile homes **beginning on the eleventh calendar day of the month succeeding the month in which the renewal registrations were due**.
- The statute "specifically requires the delinquent fee to be imposed on any applicant who fails to renew a registration before the end of the month in which renewal registration is due."
- Note on the page: "registrations are only valid until midnight on the registrant's birthday."

| License tax | Delinquent fee |
|---|---|
| up to $25.00 | $5.00 |
| $25.01 to $50.00 | $10.00 |
| $50.01 to $100.00 | $15.00 |
| $100.01 to $400.00 | $50.00 |
| $400.01 to $600.00 | $100.00 |
| $600.01 and higher | $250.00 |

### 2.4 Registration holds / blocks

- Per the License Plates & Registration FAQ (§320.02(12), Florida Statutes): registration or re-registration is **withheld** on any motor vehicle if the owner or co-owner has a suspension against their driver license. Fines and violations must be paid regardless of which co-owner committed the violation.
- A license plate **cannot be given or transferred to someone else** (§320.0609(1)(a)): the registration, license plate and certificate of registration are issued to and remain in the name of the owner of the vehicle registered. Exception: a **personalised** license plate may be transferred to a vehicle owned or co-owned by the plate owner (see RS-27).
- MyFlorida can be used to pay FDOT registration holds (per the MyFlorida app page, myfloridaapp.flhsmv.gov).

### 2.5 Heavy trucks

- Registration renewal date for heavy trucks weighing **5,000–7,999 pounds** was changing to a renewal period based on the owner's birth month (unless the owner is a business). Customers renewing a heavy-truck registration expiring Dec 2020 had the option to extend to their birth month in 2021 or an additional year to birth month 2022; Jan–Jun birthdays could pay a prorated amount for 1–18 months, Jul–Dec birthdays a prorated amount for 7–24 months. (This is dated transitional material on the page; the birth-month basis is the stated end state.)
- **HVUT (Heavy Vehicle Use Tax):** an annual federal highway tax on certain heavy motor vehicles (trucks, truck tractors, buses) using public highways; applies only to vehicles with a taxable gross weight of **55,000 pounds or more**. §320.02(7) requires motor carriers to provide proof of payment or exemption from HVUT on motor vehicles with a gross vehicle weight of 55,000 lbs or more before a registration is issued.
- Acceptable proof of payment: (1) a stamped-received IRS Form 2290, Schedule 1 returned by the IRS (original must be viewed by the clerk, who copies it and returns the original; "DO NOT MAIL THE IRS FORM 2290 AND PAYMENT TO THE DEPARTMENT"); (2) a copy of IRS Form 2290, Schedule 1 plus proof of payment (credit/debit receipt or front and back of cancelled check); (3) the original or a copy of the electronically filed IRS Form 2290, Schedule 1 (shows a watermark "Received XX/XX/XXXX"). Motor carriers with 25+ vehicles subject to HVUT must report electronically to the IRS.
- Acceptable proof of exemption: a copy of a stamped-received IRS Form 2290, Schedule 1, Part II for vehicles over 55,000 lbs travelling less than 5,000 miles, an agricultural vehicle travelling less than 7,500 miles, or qualified blood-collector vehicles.
- FLHSMV contact given on the page for HVUT/DMV requirements: (850) 617-3711 / (850) 617-2000.
- **Leased / for-hire registrations cost more:** §320.08(6)(a) — motor vehicles "For Hire" with passengers pay a $17.00 flat fee plus $1.50 per cwt (100 pounds); §320.08(6)(b) — "For Hire" with passengers and over [9] pay $17.00 flat fee plus $2.00 per cwt.

## 3. Registration fees (base vehicle tax)

From the **Fees** page (`/safety-center/driver-licenses/fees/` — "Fees for driver license and motor vehicle services are established in Florida Law"). The figures below are the **base vehicle tax only; other statutory fees apply**. Registration use, license-plate type and class code determine the fee; class code is determined by vehicle weight, body type, vehicle type and registration use.

| Vehicle | Base fee |
|---|---|
| Motorcycles | $10.00 |
| Moped | $5.00 |
| Antique motorcycle | $7.50 |
| Antique automobile | $7.50 |
| Automobiles, net weight up to 2,499 lbs | $14.50 |
| Automobiles, 2,500–3,499 lbs | $22.50 |
| Automobiles, 3,500 lbs or more | $32.50 |
| Autocycle | $10.00 |
| Trucks, net weight up to 1,999 lbs | $14.50 |
| Trucks, 2,000–3,000 lbs | $22.50 |
| Trucks, 3,001–5,000 lbs | $32.50 |
| Goat Truck | $7.50 |
| Antique Truck | $7.50 |
| Heavy Truck 5,001–5,999 lbs | $60.75 |
| Heavy Truck 6,000–7,999 lbs | $87.75 |
| Heavy Truck 8,000–9,999 lbs | $103.00 |
| Heavy Truck 10,000–14,999 lbs | $118.00 |
| Heavy Truck 15,000–19,999 lbs | $177.00 |
| Heavy Truck 20,000–26,000 lbs | $251.00 |
| Heavy Truck 26,001–34,999 lbs | $324.00 |
| Heavy Truck 35,000–43,999 lbs | $405.00 |
| Heavy Truck 44,000–54,999 lbs | $773.00 |
| Heavy Truck 55,000–61,999 lbs | $916.00 |
| Heavy Truck 62,000–71,999 lbs | $1,080.00 |
| Heavy Truck 72,000 lbs or more | $1,322.00 |
| Heavy Truck/Tractor, 150-mile radius | $324.00 |
| Heavy Truck/Tractor (Agriculture, 150 miles) | $87.75 |
| Heavy Truck/Tractor | $324.00 |
| Semitrailers, per registration year | $13.50 |
| Semitrailers, permanent registration | $68.00 |
| Special Purpose Vehicles | $44.00 |
| School Buses | $41.00 |
| Wrecker | $41.00 |
| Other Wreckers 10,000–14,999 lbs | $118.00 |
| Other Wreckers 15,000–19,999 lbs | $177.00 |
| Other Wreckers 20,000–25,999 lbs | $251.00 |
| Other Wreckers 26,000–34,999 lbs | $324.00 |
| Other Wreckers 35,000–43,999 lbs | $405.00 |
| Other Wreckers 44,000–54,999 lbs | $772.00 |
| Other Wreckers 55,000–61,999 lbs | $915.00 |
| Other Wreckers 62,000–71,999 lbs | $1,080.00 |
| Other Wreckers 72,000 lbs or more | $1,322.00 |
| Hearse or ambulance | $40.50 |
| Motor vehicles for hire (under 9 passengers) | $17.00 + $1.50 per cwt |
| Motor vehicles for hire (over 9 passengers) | $17.00 + $2.00 per cwt |
| Trailers for private use (under 500 lbs) | $6.75 |
| Trailers for private use (over 500 lbs) | $3.50 + $1.00 per cwt |
| Trailers for hire (under 2,000 lbs) | $3.50 + $1.50 per cwt |
| Trailers for hire (over 2,000 lbs) | $13.50 + $1.50 per cwt |
| Recreational Vehicles (5th wheel) | $27.00 |
| Recreational Vehicles (camping trailer) | $13.50 |
| Recreational Vehicles (under 4,500 lbs) | $27.00 |
| Recreational Vehicles (over 4,500 lbs) | $47.50 |
| Dealer and Manufacturer License Plate | $17.00 |
| Exempt/Official License Plates | $4.00 |
| Locally Operated Motor Vehicles for hire | $17.00 + $2.00 per cwt |
| Transporter | $101.25 |
| Commercial Motor Vehicle Surcharge, vehicles 10,000 lbs or more | $10.00 |
| Original/Replacement License Plate Fee | $28.00 |
| Initial Registration Fee | $225.00 |

Other registration-related amounts appearing on the Fees page / fee chart (Fees-02, `/pdf/proc/fees/Fees-02.pdf`, Rev 06.22): Advanced Replacement $2.80; Air Pollution Control Fee $1.00; Decal Mail Fee $0.85; Decal Fee $1.00; FRVIS (Florida Real Time Vehicle Information System) $0.50; Emergency Medical Services Trust Fund Fee $0.10; Custom Motor Vehicle flat tax $7.50; Exempt License Plate Fee $4.00; Fleet License Plate additional fees — manufacturing (one time) $1.50, management (annual) $2.00.

## 4. Titles — general

From **Liens and Titles** (`/dmv/title_register.html`, also at `/motor-vehicles-tags-titles/liens-and-titles/`):

- A certificate of title, electronic or paper, is the **proof of ownership** of a vehicle, mobile home or vessel in Florida.
- Most vehicles, mobile homes and vessels must be titled, **except** mopeds, motorized bicycles, and trailers weighing less than 2,000 pounds.
- You must apply for a title in your name when you **purchase** a vehicle/mobile home/vessel, **bring one into Florida from another state or country**, or when **ownership changes**.
- **To obtain a title, at minimum:**
  - proof of identity — a driver license or ID card from any state, or a passport; must be current and valid;
  - proof of ownership — a Manufacturer's Certificate of Origin or out-of-state title;
  - a completed Application for Certificate of Title With/Without Registration (**HSMV form 82040**);
  - fees for sales tax and title. If a license plate is purchased, valid Florida insurance and registration fees are also required.
- **Two owners:** ownership may be joined by "**and**" or "**or**". Joined by "and": owners share equal responsibility; both must be present, designate a power of attorney, or have the title signed by each owner as seller to transfer it out of their names. Joined by "or": either owner may take individual responsibility, and either may be present or sign a bill of sale to transfer it out. If "or"-joined owners split and one wants their name removed, that owner becomes the seller and the second owner the purchaser in the transfer section; a new title is issued.
- **Power of attorney:** a general or limited power of attorney may be given to a third party to handle title and registration; FLHSMV provides a limited Power of Attorney for a Motor Vehicle, Mobile Home, or Vessel (**HSMV form 82053**).
- **Lien (definition):** a lienholder (bank, dealership, etc.) has a secured interest in a vehicle, mobile home or vessel in the form of a debt due to the lienholder. The lienholder's information is placed on the paper or electronic certificate of title in addition to the owner's information, and the lienholder stays listed until the lien is paid/fully satisfied and the lienholder has filed a lien satisfaction with FLHSMV.

### 4.1 Title fees

From the Fees page. All fees are for **electronic titles**; add **$2.50** service and handling fee when a paper title will be printed. An additional **$2 lien recording fee** may also apply.

| Title transaction | Fee |
|---|---|
| Original — New | $77.25 |
| Original — Used | $85.25 |
| Transfer / Duplicate | $75.25 |
| Lien Only (no transfer of ownership) | $74.25 |
| Fast Title | $10.00 (additional) |
| For-hire Vehicle Title | $56.25 |
| Late Title Fee | $20.00 |
| Re-inspection fee | $20.00 |

### 4.2 Transferring a title / buying or selling a vehicle

- A paper title is needed to transfer ownership to a buyer in a private sale; FLHSMV recommends conducting the sale and transfer in a Florida county tax collector's office or motor vehicle service centre "to ensure your name is removed from the vehicle ownership record" (Paper Liens and Titles page).
- You do **not** need to request a paper title before trading a vehicle in at a Florida dealership. If the title is in paper format, take it with you when trading in at a dealership.
- If the title status is paper but you no longer possess it, a duplicate paper title must be requested at a county tax collector's office or service centre.
- The Liens and Titles / Paper Titles pages link onward to "Buying or Selling a Vehicle?" (consumer-education page) — that page was not separately opened in full; see §12 gaps.

### 4.3 New residents / vehicles brought into Florida (incl. from another country)

From **New Resident — Welcome to Florida!** (`/new-resident/`):

- A new Florida resident must obtain a valid Florida driver license **within 30 days** of establishing residency, and must obtain Florida insurance and **title and register vehicle(s), vessel(s) and mobile home(s) within 10 days** of establishing residency.
- **With a lien:** if the out-of-state title is held by an out-of-state lienholder, contact the lienholder to request the title be transferred to Florida. Whether or not the lienholder transfers it, the vehicle must still be registered. If the lienholder refuses, get the refusal in writing on letterhead and bring it to a motor vehicle service centre to apply for registration. If the lienholder agrees, visit a local motor vehicle service centre to complete form 82040.
- **Without a lien** — bring a packet containing: proof of identity (all owners); proof of Florida insurance; original out-of-state title; a completed form 82040 signed by ALL owners; and verification of physical inspection of the VIN, completed on form 82040 or on Vehicle Identification Number and Odometer Verification (**HSMV form 82042**). The VIN must be physically inspected and verified by one of: a law enforcement officer; a military police officer; a licensed Florida dealer; or a county tax collector employee or Division of Motorist Services compliance examiner (at any local service centre offering motor vehicle services). Special circumstances may require additional documentation.
- The Liens and Titles page states the same trigger for imported vehicles generally: a title application is required when bringing a vehicle, mobile home or vessel into Florida **from another state or country**. No separate consumer "Importing Vehicles" page with additional import-specific steps was found on flhsmv.gov; the A-to-Z "Importing Vehicles" entry resolves to the title/registration and manufacturer-importer-distributor licensing material (§9).

## 5. Duplicate registration

- There is **no standalone "Duplicate Registration" page** on flhsmv.gov found in this study. The A-to-Z entry is served by:
  - **MyDMV Portal** — "Registration Replacement/Duplicate" is listed under both Business Customer Transactions and Registration & Title Transactions; Express Motor Vehicle Renewal also offers quick renewal options for parking permit and registration renewals without an account.
  - **Motor Vehicle Registrations page** — "Obtain a duplicate registration certificate if the customer's registration certificate is lost" is offered both via MyDMV Portal online renewal and via the MyFlorida app.
  - **County service-centre pages** — renewals/replacements for a registration, tag, title or boat/vessel/trailer are handled at a Motor Vehicle Service Center or via MyDMV Portal.
- No separate duplicate-registration fee is stated on the pages studied (the Fees page lists an Original/Replacement License Plate Fee of $28.00, which is a plate fee, not a duplicate-registration-certificate fee).

## 6. Duplicate title

### 6.1 Duplicate paper title

From **Paper Liens and Titles** (`/motor-vehicles-tags-titles/liens-and-titles/paper-liens-and-titles/`):

- If a paper title has been lost, stolen or damaged, a duplicate paper title can be obtained. The owner must mail or take the following to a Florida county tax collector's office or service centre:
  - completed Application for Duplicate or Lost in Transit Reassignment for a Title Certificate (**HSMV form 82101**);
  - proof of identity — a driver license or ID card from any state, or a passport; must be current and valid;
  - payment for the duplicate title fee (Fees page: Transfer/Duplicate title fee **$75.25** for an electronic title; add $2.50 if a paper title is printed).
- If the original paper title is found after a duplicate has been issued, the original is **no longer valid**; it should be destroyed or forwarded to FLHSMV.
- **Outstanding lien:** per procedure TL-05 (Duplicate and Lost in Transit Certificates of Title, `/pdf/proc/tl/tl-05.pdf`, rev. 08/25), when there is an outstanding lien on record, **only the lienholder** may apply for a duplicate certificate of title.
- **Lost in transit:** under §319.29(3), Florida Statutes (quoted in TL-05), if a certificate issued by the department is lost in transit and not delivered, the owner or lienholder may apply for reissuance **within 180 days** of the date of issuance, with **no additional fee**.
- **Duplicate via MyDMV Portal:** "Title Duplicate" is a listed Registration & Title Transaction in MyDMV Portal; the duplicate electronic title can be printed via "Print Electronic Title".

### 6.2 Duplicate vessel title

- Per the Vessels FAQ (search excerpt): the owner must properly complete and submit an application for duplicate title plus a fee of **$11** to the local tax collector or license plate agent office; the duplicate title is mailed within **five working days** of receipt of the application. (Vessel titling fees in §10 differ from motor-vehicle title fees — $5.25 electronic / $7.75 paper / $11 expedited.)

## 7. Electronic Lien & Title (ELT) and paper liens/titles

### 7.1 Electronic titles

From **Electronic Liens and Titles (ELT)** (`/motor-vehicles-tags-titles/liens-and-titles/elt/`):

- An electronic title provides the same information as a paper title and requires the same documents when applying. Title documents/applications for electronic titles are handled the same as paper titles. Electronic titles are maintained in FLHSMV's database under §319.24, Florida Statutes; the record stays in the database until a paper title is requested for selling a vehicle or transferring title to another state or country.
- **Electronic liens:** lien notifications and satisfactions are transmitted electronically between FLHSMV and the lienholder. When an electronic lien is satisfied, the title remains electronic until a paper title is requested.
- ELT benefits stated: reduced title fraud; reduced chances of a lost title; faster notification of lien satisfaction; reduction in storage of title documents; access to expedited title printing; better customer service; reduced costs.
- ELT providers/participants: see FLHSMV's Authorized Service Providers page for lien satisfaction and how the ELT system works; dealers and other organisations can become ELT participants as outlined there.

### 7.2 Converting an electronic title to paper

- Owners with electronic titles **and no lien** can convert to a paper title through MyDMV Portal for **$4.50**. The converted paper title is mailed to the address on the owner's motor vehicle record; paper titles are generally received within **3–4 weeks**.
- **Titles cannot be printed at home**, and cannot be picked up at a county tax collector's office or service centre after a title transaction completed online.
- By mail to the county tax collector: photocopy of a valid picture ID; written request to have the electronic title (with no lien) printed; print electronic title fee payment of **$2.50**. Once printed, paper titles are mailed by standard mail, typically received within 3–4 weeks.
- In person (fast title): a title printed and provided the same day in an expedited manner is a **fast title**, requested in person only, issued/printed the same day, with an additional **$10 fee**. Available at a Florida county tax collector's office or service centre.
- FLHSMV encourages owners to maintain titles electronically.

## 8. Disabled parking permits

From **Disabled Person Parking Permits** (`/dmv/disabled_pkg.html`) and its FAQ (`/motor-vehicles-tags-titles/disabled-person-parking-permits/frequently-asked-questions/`):

- Authority: **§320.0848, Florida Statutes** — permits for long-term and short-term mobility impairments and for those certified as legally blind by an optometrist. Permits may be issued to driver license and ID card holders.
- **Two categories:**
  - **Permanent** — long-term mobility impairments, or certified legally blind. Valid for **four years** and must be renewed by the permit holder's birthdate. **No fee.**
  - **Temporary** — short-term mobility impairments, for **up to six months** as specified by a certifying medical authority. **$15 fee.** If the need exceeds six months, an additional temporary permit may be issued; if applied for within 12 months of issuance of the first permit, **no additional fee** is required. Temporary permits are nonrenewable — customers must re-apply for a new temporary permit on expiration (visitors page).
- **Application:** form **HSMV 83039**, Application for Disabled Person Parking Permit, completed and signed by a certifying medical authority; the authority must sign **within 12 months** prior to submitting the application. Also bring a copy of the Florida driver license or ID card. Completed forms and documentation must be presented to a motor vehicle service centre. (FAQ: submit form 83039 "signed by a certifying medical authority within the last 12 months" to the local motor vehicle service center, "with appropriate payment for temporary permits only".)
- **Certifying medical authorities:** a physician licensed under Ch. 458 (medical practice), Ch. 459 (osteopathic medicine) or Ch. 460 (chiropractic medicine); a podiatric physician licensed under Ch. 461; an optometrist licensed under Ch. 463 (sight only); an advanced practice registered nurse licensed under Ch. 464 under the protocol of a licensed physician as above; a physician assistant licensed under Ch. 458 or Ch. 459; or a similarly licensed physician from another state, if the application is accompanied by documentation of that physician's licensure in the other state and form 83039 signed by the out-of-state physician verifying knowledge of Florida's eligibility guidelines.
- **Replacement (lost/stolen):** form **HSMV 83146**, Application for Replacement License Plate, Validation Decal or Parking Permit, must also be provided. If the permit was issued more than 12 months before being lost/stolen, a valid form Letter 27-333 (or equivalent) may be submitted in lieu of form 83039. Per the Fees-02 chart: 4-year replacement fee **$15.00**.
- **Use rules:** the permit must only be used by the permit holder; the holder must have their Florida driver license or ID card on hand when using it; it must hang from the rear-view mirror with the permit number visible from the front when parked, and must not hang while the vehicle is in motion; it must have a valid yellow registration decal attached to both sides; it must display on one side the holder's driver license or ID card number, or the authorised organisation's FEID number.
- **Fees (Fees-02 chart):** Disabled Person Parking Permit fees — free (base); 4-year initial additional or renewal fee $1.00 (chart shows a split distribution totalling $13.50: $3.50 Highway Safety Operating Trust Fund, $9.00 Transportation Disadvantaged Trust Fund, $2.50 issuing agency — figures as printed on the chart); 4-year replacement fee $15.00.
- **Visitors:** Florida recognises plates/permits displaying the international symbol of accessibility issued by any state or foreign country. If the permit/plate does not display an international symbol of accessibility, visitors must obtain a Florida temporary disabled parking permit — fee **$15**. Apply in person or by mail at a motor vehicle service centre with completed form 83039 signed by the customer and certifying authority (out-of-country visitors may provide a copy of their current parking permit issued by their country of residence) plus acceptable identification.
- **Veterans:** there is **no fee** for a permanently disabled parking permit (Disabled Parking Permits for Veterans, `/military/disabled-parking-permits-for-veterans/`); apply with form 83039 at a local motor vehicle service centre.
- **Wheelchair license plate:** fee **$28** in addition to other applicable registration fees. To obtain one, submit form **HSMV 83007** (Application for International Wheelchair License Plate) or form 83039 to a motor vehicle service centre.
- **Abuse/complaints:** misuse or fraudulent acquisition can be reported on the Disabled Parking Abuse Complaint Form (A-to-Z entry); complaints go to the Fraud Analysis Unit, 2900 Apalachee Parkway, Rm B360, MS-64, Tallahassee, FL 32399.
- Questions: local motor vehicle service centre or FLHSMV Customer Service Call Center **(850) 617-2000**.

## 9. Dealers, manufacturers, distributors, importers

From **Dealers, Installers, Manufacturers, Distributors, and Importers** (`/dmv/dealer.html`) and the **Motor Vehicle, Recreational Vehicle and Mobile Home Dealer/Broker Licenses** page:

- The FLHSMV **Bureau of Dealer Services** issues and renews licenses for **more than 15,000** motor vehicle, auction, salvage, wholesale, mobile home, recreational vehicle dealers and manufacturers, distributors and importers each year (the hub page prints "15,0000" — a typographical error on the site). The bureau also licenses mobile home installers and monitors the construction and installation of mobile homes. It has offices throughout the state.
- **Who needs a dealer license:** any entity that buys, sells, offers for sale, displays for sale or deals in **three or more motor vehicles within any 12-month period**; or in **one or more mobile home or recreational vehicles within any 12-month period**. Governing law: §§320.27, 320.77 and 320.771, Florida Statutes; Florida Administrative Codes 15C-7.003 and 15C-7.004.
- **Pre-license requirements:**
  1. Locate the nearest compliance examiner (locations page → county → Motorist Services Regional Offices). Location/display-space/office requirements for motor vehicle dealers: FAC 15C-7.003; for mobile home and RV dealers: §§320.77 and 320.771 (320.77(3)(g)(h)(i), 320.771(3)(g)(h)(i)).
  2. Obtain a Federal Employer Identification Number (FEIN) from the IRS.
  3. Obtain a sales tax number from the Florida Department of Revenue.
  4. Complete a pre-licensing dealer training class from an FLHSMV-approved dealer training school.
  5. Obtain electronic fingerprinting for all officers of the dealership from an FDLE-approved service provider.
- **License requirements (application):**
  1. Submit completed application (**form 86056**) with required documents and fee to the regional office responsible for the dealership. Dealer FAQ states the fee is **$300 for each main location**, payable to DHSMV.
  2. Proof of Garage Liability Insurance — minimum **$25,000 combined single-limit liability** (bodily injury and property damage) plus **$10,000 personal injury protection**. Independent, auction and wholesale applicants may instead submit a general liability policy coupled with a business automobile policy with the same minimums. **Salvage dealers are exempt** from this requirement.
  3. Original surety bond — **form 86020** (motor vehicle dealers), **form 86019** (RV dealers), **form 86018** (mobile home dealers). Dealer FAQ states the motor-vehicle bond amount is **$25,000**.
  4. Irrevocable letter of credit in lieu of the surety bond (form 86057 motor vehicle; form 86058 mobile home).
  5. Proof of registration of the business entity and fictitious name, if any, with the Florida Division of Corporations.
  6. Copy of dealer-training completion certificate from a department-approved Dealer Training School.
  7. Copy of a lease agreement.
  8. Proof of electronic fingerprinting from an FDLE service provider (attach the receipt). Fingerprints cost **$54.25 per person** (Dealer FAQ).
- **Training length (Dealer FAQ):** 8 hours for franchise dealers; **16 hours** for VI, VA, VW and SD license types (independent, auction, wholesale, salvage).
- **Dealer FAQ — other points:**
  - Franchise dealers must be authorised by a manufacturer via a franchise agreement to sell that brand; proof must be provided to the department.
  - FLHSMV does **not** license entities that meet the definition of a "motor vehicle broker" (§320.27(1)(c)(5) and (1)(d)).
  - Mobile home dealers may sell RVs at their licensed location if they submit proof of garage liability insurance at the stated minimums (§320.771(8)).
  - A mobile-home dealer with an RV endorsement may transact in RVs with a motor vehicle auction; mobile home dealers must register their salesperson(s) with FLHSMV (form 84045; §320.77(9)).
  - A licensed RV dealer may transact in RVs with a motor vehicle auction, and may sell at retail/wholesale a motor vehicle acquired in exchange for an RV sale if incidental to the principal RV business; but may not buy a motor vehicle for resale unless also licensed as a motor vehicle dealer.
  - Wholesale dealers are exempt from display requirements (no retail sales), are **not allowed to use dealer plates**, and may sell only to licensed dealers or auctions (§320.27(1)(c)(3)).
  - Licensed auction dealers are not permitted to retail to the public; only licensed dealers or bona-fide employees authorised by the dealership may bid at an auction.
  - A licensed dealer dealing exclusively in mobile homes does **not** get the benefit of dealer license plates.
  - Dealer and Manufacturer License Plate (registration fee schedule): **$17.00**.
- **Forms and resources (dealer licensing):** HSMV 86056 (dealer license application + instruction booklet); 86072 (modification to dealer license); 86720 (renewal application for MV/MH/RV dealers); 86020/86019/86018 (surety bonds); 86057/86058 (irrevocable letters of credit); Dealer Handbook; FLHSMV regional offices; FLHSMV-approved dealer training schools; NMVTIS (§319.30 — notification requirements for dealers/purchasers dealing in derelict or salvage vehicles).
- **Manufacturers, importers, distributors (incl. "Importing Vehicles" as a business):** a manufacturer, importer or distributor license is required to conduct business for the distribution and sale of motor vehicles, RVs or mobile homes in Florida. Application **form 84256** (with checklist) to the Bureau of Dealer Services, Dealer License Section, plus: current financial statement; surety bond or irrevocable letter of credit of **$50,000** for mobile home manufacturers; surety bond of **$10,000** for RV manufacturers, distributors or importers; copy of product warranty; list of authorised Florida dealers; license fee of **$300** for Motor Vehicle Manufacturer/Importer/Distributor and **$340** for Mobile Home Manufacturer and RV Manufacturer/Importer/Distributor (checks payable to FLHSMV); copies of preparation/delivery charge agreements; warranty labour rates and parts agreements; Articles of Incorporation/Organization and Operating or Partnership Agreement; photos of the vehicle(s) with specifications; copy of fictitious name registered with the Secretary of State (sunbiz.org); copy of Division of Corporations certification of current registration; Manufacturer's Statement of Origin. Applicants may not engage in business until all licensing requirements are met — doing so violates §320.61, Florida Statutes, and title work will not be processed.
- **Manufacturer's Statement of Origin (MSO):** required under §§319.21 and 319.23; must contain the NHTSA-registered manufacturer name, NHTSA-assigned VIN, NCIC line-make, year, and the licensed manufacturer/distributor/importer name (signed, city/state) at the bottom and the licensed franchise dealer or customer name/address in the middle. Two-stage vehicles need two MSOs (first states "incomplete", second states "completed" with its own line-make, carrying forward the VIN); both must be provided for proper title and registration. MSO samples are on pages 16–28 of form 84256.
- **Other dealer-area pages:** Licensed Mobile Home Installers (licensing required to install manufactured homes in Florida); Dealer Training School licensure; Private Rebuilt Vehicle Inspection Providers — under §319.141, FLHSMV implements a program in Miami-Dade County for rebuilt inspection services by private-sector participants (PRVIP, "currently being developed" on the page); Authorized Service Providers (ELT).

## 10. Boat (vessel) registration and titles

From **Vessel Titling and Registrations** (`/motor-vehicles-tags-titles/vessels/vessel-titling-registrations/`):

- **All motorized vessels** operating on Florida's public waterways must be titled and registered. Ch. 328, Florida Statutes, designates FLHSMV as responsible for issuing vessel registrations and titles. Applications must be filed at a county tax collector or license plate agent office. Owners may register a vessel for **one year or two years**.
- A purchaser of a new or used vessel has **30 days** to title and register it; during that period the owner must have proof of the date of purchase aboard the vessel. **Operating an unregistered vessel after 30 days is a second-degree misdemeanor.**
- **Exemptions from titling:** vessels operated/used/stored exclusively on private lakes and ponds; vessels owned by the U.S. Government, the State of Florida or its political subdivisions; non-motor-powered vessels under 16 feet; federally documented vessels; a vessel already covered by a registration number in full force and effect under a federally approved numbering system of another state or the U.S. Coast Guard (in a state without a federally approved system), if not located in Florida for more than 90 consecutive days; vessels from a country other than the U.S. temporarily used/operated/stored in Florida for not more than 90 days; amphibious vessels issued a vehicle title by FLHSMV; vessels used only for demonstration, testing or sales-promotional purposes by a manufacturer or dealer.
- **Exemptions from registration:** vessels operated/used/stored exclusively on private lakes and ponds; vessels owned by the U.S. Government; vessels used exclusively as a ship's lifeboat; non-motor-powered vessels under 16 feet; non-motor-powered canoe, kayak, racing shell or rowing scull regardless of length. (Vessels FAQ: non-motor-powered vessels under 16 ft need neither registration nor title; non-motor-powered canoes/kayaks/racing shells/rowing sculls over 16 ft must be titled but not registered.)
- **Applying for a vessel title:** a vessel not exempt from titling must be titled at the same time it is registered. Documents (bring titling fee + documents to a tax collector/license plate agent):
  - New vessel — Manufacturer's Certificate of Origin (MCO) or equivalent statement of builder; if purchased in a state that does not require an MCO, proof of ownership is an executed dealer's bill of sale. Proof of ownership must include a complete vessel description: manufacturer's name, year, type, hull material, propulsion, fuel, use, hull identification number and length.
  - Used vessel currently titled in FL — Florida title accurately completed for transfer to purchaser.
  - Used vessel currently titled out of state — out-of-state title accurately completed for transfer.
  - Used vessel from a state that does not require title — current registration from that state and a bill of sale from the current registrant (with the same complete description).
- **Vessel titling fees** (in addition to registration fees and any sales tax): **$5.25** (electronic title), **$7.75** (paper title) or **$11** (expedited/fast title); additional **$1** to record each existing lien; additional **$4** titling fee for vessels previously registered outside Florida.
- **Applying for vessel registration:** file with the county tax collector or license plate agent; establish proof of ownership (executed bill of sale, builder's contract, manufacturer's statement of origin, federal marine document, or another document acceptable to FLHSMV). If the vessel must be titled, the title must be issued before the registration.
- **Vessel registration fees** (Fees page: subject to a $2.25 service fee and a $0.50 FRVIS fee, not included; other statutory and county fees may apply):

| Class | Length | Registration fee | Reduced fee (EPIRB/PLB) | Optional county fee |
|---|---|---|---|---|
| A-1 | less than 12 ft | $5.50 | $2.95 | $1.75 |
| A-2 | 12 to less than 16 ft | $16.25 | $11.00 | $7.13 |
| 1 | 16 to less than 26 ft | $28.75 | $20.40 | $13.37 |
| 2 | 26 to less than 40 ft | $78.25 | $57.50 | $38.13 |
| 3 | 40 to less than 65 ft | $127.75 | $94.95 | $62.88 |
| 4 | 65 to less than 110 ft | $152.75 | $113.40 | $75.38 |
| 5 | 110 ft or more | $189.75 | $141.15 | $93.88 |
| Dealer | — | $25.50 | — | $11.75 |

  - Reduced fees under §328.72(18) apply to a recreational vessel equipped with an Emergency Position Indicating Radio Beacon (EPIRB) or where the owner possesses a Personal Locator Beacon (PLB). The page states the reduced fees were "effective July 1, 2016 through June 30, 2017 only for those who register in an office" — that date window is as printed on the page and appears stale; the Fees page still lists the unreduced fees above. The hub page also notes that since 1 July 2016 a customer who owns a recreational vessel with an EPIRB, or a recreational vessel and a PLB, is eligible for a registration fee reduction on an original or renewal registration.
  - Registration fees also include a **$2.25 service fee** and **$0.50 FRVIS fee**, not included in the table above.
  - **Commercial:** an additional **$50** commercial vessel license fee is required of all non-residents or aliens unless specifically exempted by statute. A vessel primarily used for harvesting saltwater/freshwater fish and products from state waters for sale is a commercial vessel (§379.361); a saltwater products license is required for those harvesting over the recreational bag limit, selling, or harvesting with certain gear. Changing classification (recreational ↔ commercial) with a current registration: submit form HSMV 87015 and the certificate of registration to a county tax collector/license plate agent; a non-resident changing to commercial pays the additional $50.
  - Optional county fee is retained by the county of registration. Counties charging it: Broward, Charlotte, Collier, Dade, Hardee, Hillsborough, Lee, Manatee, Martin, Monroe, Palm Beach, Pinellas, Polk, Sarasota and Volusia.
- **Sales tax (vessels):** if sales tax on the total purchase price has not been paid at registration, it must be paid with the registration and titling fees; if paid, provide the receipt. Dealer purchase: sales tax due on vessel, motor (inboard or outboard), trailer and all accessories. Casual (non-dealer) sale: sales tax due on vessel, inboard motor and trailer; an outboard motor and accessories may be exempt if separately itemised and priced on the bill of sale.
- **Homemade vessels:** initial title/registration application at the county tax collector/license plate agent. If under 16 ft, forms HSMV 82040 and HSMV 87002 plus the $5.25/$7.75/$11 titling fee, plus length-based registration fee and any sales tax.
- **Abandoned vessels:** Florida has no salvage law giving a finder ownership. As a title state, Florida requires a transfer of vessel title from owner to purchaser for legal ownership. Taking an abandoned vessel without first getting a title is theft and could result in fines or jail time. Under §705.103, a finder wanting to claim/title an abandoned vessel must first report it to a law enforcement officer; the agency collects a fee to investigate and determine the owner; if unclaimed, the agency may transfer it to the finder with a bill of sale and evidence of the investigation, and the finder then applies to FLHSMV for title in their name.
- **Visitors / out-of-state vessels:** Florida recognises valid registration certificates/numbers issued to visiting boaters for **90 days**; an owner intending to use the vessel in Florida longer than 90 days must register it with a county tax collector/license plate agent (may retain the out-of-state number if planning to return home within a reasonable period). Out-of-state registration certificates/numbers for vessels owned by military personnel on active duty in Florida are valid until their expiration date, then must be registered and titled in Florida.
- **Boating safety (Vessels FAQ):** Florida has no boating license; to operate a motorized vessel of 10 horsepower or greater, anyone born on or after 1 January 1988 must complete an approved boating safety course and obtain a Boating Safety Education Identification Card from the FWC, valid for life.
- **Nonprofit exemption (Vessels FAQ):** a 501(c)(3) nonprofit is exempt from vessel registration fees for a marine boat trailer used exclusively for nonprofit activities, on presentation of its IRS Determination Letter at a motor vehicle service centre.

## 11. Address change, online services, and key forms

### 11.1 Address change

- There is no standalone address-change page for vehicles found in this study. Per every county service-centre page and the A-to-Z entry: to change an address on a **registration, tag, title or boat/vessel/trailer**, see a Motor Vehicle Service Center or visit **MyDMV Portal**. To change an address on a driver license, see a Driver License Service Center or visit MyDMV Portal.
- **Name change** (for contrast, same pages): to change a name on a registration, tag, title or boat/vessel/trailer, see a Motor Vehicle Service Center (in person only — no online route stated).
- In MyDMV Portal, "Residential and Mailing Address Update" is listed under View or Update Personal Information. **No address changes can be made on the MyFlorida mobile app** (Motor Vehicle Registrations page).

### 11.2 Online services (MyDMV Portal)

From **MyDMV Portal** (`/motorist-modernization/mydmvportal/`): a quick, convenient way for eligible Florida driver license/ID holders and businesses to access many driver license and motor vehicle services online at any time. Customers must create a secure MyDMV Portal account by verifying their identity against FLHSMV records; if verification fails, they are notified and must visit a local office.

Registration & title transactions available in MyDMV Portal:
- Print Electronic Title; Title Duplicate; No Longer Owned; Registration Renewal; Registration Replacement/Duplicate; Specialty Plate Voucher; Plate and/or Decal Replacement.
Business-customer transactions additionally include: Bulk Driver License Record Request; Subscription Services; Fleet Maintenance; Request Additional Parking Permit; Parking Permit Replacement/Duplicate; Parking Permit Renewal (plus the registration/title items above).
Parking Permit Transactions: Request Additional Parking Permit; Parking Permit Replacement/Duplicate; Parking Permit Renewal.
Express services (no MyDMV Portal account needed, limited information): Driver License Check; **Motor Vehicle Check** (registration inquiries); **Express Motor Vehicle Renewal** (quick renewal options for parking permit and registration renewals); Emergency Contact Information.

### 11.3 Key forms named on the pages studied

| Form | Use |
|---|---|
| HSMV 82040 | Application for Certificate of Title With/Without Registration (MV / MH / VS versions) |
| HSMV 82042 | Vehicle Identification Number and Odometer Verification |
| HSMV 82050 | Notice of Sale and/or Bill of Sale for a Motor Vehicle, Mobile Home, Off-Highway Vehicle or Vessel |
| HSMV 82053 | Power of Attorney (limited) for a Motor Vehicle, Mobile Home, or Vessel |
| HSMV 82101 | Application for Duplicate or Lost in Transit Reassignment for a Title Certificate |
| HSMV 82150 | Application and Notice of Interest — Electronic Lien and Title Process |
| HSMV 82152 | Application for Surviving Spouse Transfer of Title |
| HSMV 82260 | Lien Satisfaction |
| HSMV 82363 | Application for Salvage Title / Certificate of Destruction |
| HSMV 83007 | Application for International Wheelchair License Plate |
| HSMV 83039 | Application for Disabled Person Parking Permit |
| HSMV 83146 | Application for Replacement License Plate, Validation Decal or Parking Permit |
| HSMV 83363 | Vehicle/Mobile Home/Vessel refund request (per county pages; email MVRefunds@flhsmv.gov) |
| HSMV 86056 | Application for a License as a Motor Vehicle, Mobile Home or Recreational Vehicle Dealer |
| HSMV 86057 / 86058 | Irrevocable letter of credit (motor vehicle / mobile home dealer) |
| HSMV 86018 / 86019 / 86020 | Surety bonds — mobile home / RV / motor vehicle dealer |
| HSMV 86072 | Modification to dealer license |
| HSMV 86720 | Renewal application for MV/MH/RV dealers |
| HSMV 87002 | Homemade vessel (with 82040, if under 16 ft) |
| HSMV 87015 | Vessel change of classification (recreational ↔ commercial) |
| HSMV 84256 | Manufacturer/Importer/Distributor or Mobile Home Manufacturer license application (with checklist; MSO samples pp. 16–28) |
| HSMV 82002 | Initial Registration Fee Exemption Affidavit |
| HSMV 82026 / 82033 | Application for Bonded Title Affidavit / Title Surety Bond for a Motor Vehicle |

(Forms list compiled from the FLHSMV Forms page, `/resources/forms/`, as returned in search results, and the pages above.)

## 12. Pages studied — full list with URLs

| # | Page | URL |
|---|---|---|
| 1 | Home | https://flhsmv.gov/ |
| 2 | A to Z Guide | https://flhsmv.gov/a-to-z-guide/ |
| 3 | Motor Vehicles, Tags & Titles (hub) | https://flhsmv.gov/motor-vehicles-tags-titles/ |
| 4 | Motor Vehicle Registrations | https://www.flhsmv.gov/motor-vehicles-tags-titles/license-plates-registration/motor-vehicle-registrations/ |
| 5 | Fees (fee schedule) | https://www.flhsmv.gov/safety-center/driver-licenses/fees/ |
| 6 | Fees-02 Motor Vehicle, Mobile Home Registration Fees and Flat Tax Distribution Chart (PDF, Rev 06.22) | https://www.flhsmv.gov/pdf/proc/fees/Fees-02.pdf |
| 7 | Liens and Titles | https://www.flhsmv.gov/dmv/transfer.html (also canonical https://www.flhsmv.gov/motor-vehicles-tags-titles/liens-and-titles/) |
| 8 | Electronic Liens and Titles (ELT) | https://www.flhsmv.gov/motor-vehicles-tags-titles/liens-and-titles/elt/ |
| 9 | Paper Liens and Titles | https://flhsmv.gov/motor-vehicles-tags-titles/liens-and-titles/paper-liens-and-titles/ |
| 10 | Duplicate and Lost in Transit Certificates of Title — Procedure TL-05 (PDF, rev. 08/25) | https://www.flhsmv.gov/pdf/proc/tl/tl-05.pdf |
| 11 | Disabled Person Parking Permits | http://www.flhsmv.gov/dmv/disabled_pkg.html |
| 12 | Disabled Person Parking Permits — Frequently Asked Questions | https://www.flhsmv.gov/motor-vehicles-tags-titles/disabled-person-parking-permits/frequently-asked-questions/ |
| 13 | Disabled Person Parking Permits for Florida Visitors | https://www.flhsmv.gov/motor-vehicles-tags-titles/disabled-person-parking-permits/disabled-person-parking-permits-for-florida-visitors/ |
| 14 | Disabled Parking Permits for Veterans | https://www.flhsmv.gov/military/disabled-parking-permits-for-veterans/ |
| 15 | Wheelchair License Plate | https://www.flhsmv.gov/motor-vehicles-tags-titles/disabled-person-parking-permits/wheelchair-license-plate/ |
| 16 | Dealers, Installers, Manufacturers, Distributors, and Importers (hub) | http://www.flhsmv.gov/dmv/dealer.html |
| 17 | Motor Vehicle, Recreational Vehicle and Mobile Home Dealer/Broker Licenses | http://flhsmv.gov/motor-vehicles-tags-titles/dealers-installers-manufacturers-distributors-importers/mv-rv-mh-dealer-broker-licenses/ |
| 18 | Dealer FAQ | https://www.flhsmv.gov/safety-center/consumer-education/consumer-complaints/dealer-faq/ |
| 19 | Motor Vehicle, Recreational Vehicle, and Mobile Home Dealers FAQ | https://www.flhsmv.gov/motor-vehicles-tags-titles/dealers-installers-manufacturers-distributors-importers/mv-rv-mh-dealer-broker-licenses/mv-rv-mh-dealers-faqs/ |
| 20 | Dealer Forms and Resources | https://www.flhsmv.gov/motor-vehicles-tags-titles/dealers-installers-manufacturers-distributors-importers/mv-rv-mh-dealer-broker-licenses/forms-and-resources/ |
| 21 | Motor Vehicle and Recreational Vehicle Manufacturer, Importer and Distributor or Mobile Home Manufacturer License | https://www.flhsmv.gov/motor-vehicles-tags-titles/dealers-installers-manufacturers-distributors-importers/mv-rv-manufacturer-importer-distributor-mh-manufacturer-license/ |
| 22 | Manufacturer's Statement of Origin (MSO) | https://www.flhsmv.gov/motor-vehicles-tags-titles/dealers-installers-manufacturers-distributors-importers/mv-rv-manufacturer-importer-distributor-mh-manufacturer-license/manufacturers-statement-origin-mso/ |
| 23 | Vessel Titling and Registrations | https://flhsmv.gov/motor-vehicles-tags-titles/vessels/vessel-titling-registrations/ |
| 24 | Vessels — Frequently Asked Questions | https://www.flhsmv.gov/motor-vehicles-tags-titles/vessels/frequently-asked-questions/ |
| 25 | Commercial Vessels | https://www.flhsmv.gov/motor-vehicles-tags-titles/vessels/vessel-titling-registrations/commercial-vessels/ |
| 26 | License Plates & Registration — FAQ | https://www.flhsmv.gov/motor-vehicles-tags-titles/license-plates-registration/faq/ |
| 27 | MyDMV Portal | https://www.flhsmv.gov/motorist-modernization/mydmvportal/ |
| 28 | MyFlorida app (official FLHSMV app) | https://myfloridaapp.flhsmv.gov/ |
| 29 | New Resident — Welcome to Florida! | https://www.flhsmv.gov/new-resident/ |
| 30 | Forms (index) | https://www.flhsmv.gov/resources/forms/ |
| 31 | National Motor Vehicle Title Information System (NMVTIS) | https://www.flhsmv.gov/motor-vehicles-tags-titles/liens-and-titles/nmvtis/ |
| 32 | Contact Us (incl. disabled-parking complaint mailing address) | https://www.flhsmv.gov/contact-us/ |

Pages 1–11, 16–17, 23, 26–27 were read in full via browser.open. Pages 6, 10, 12–15, 18–22, 24–25, 28–32 were covered via flhsmv.gov search-result excerpts (their URLs are verbatim from search results); five of them (12, 18, 21, 13, 15) could not be re-opened in full because the browser tool returned HTTP 429 (rate limit) at the end of the session — see Notes & Gaps.

## 13. Key facts at a glance

- **Renewal:** 1 or 2 years; up to 3 months early; expires midnight on the first owner's birthday (business owners excepted).
- **Initial registration fee:** $225 (unless transferring a plate already in the owner's name; turning in an old plate can exempt it on a replacement vehicle).
- **Late renewal penalty:** delinquent fee from the 11th calendar day of the month after the due month — $5 / $10 / $15 / $50 / $100 / $250 by license-tax band (§320.07(4)(a)).
- **Online fees:** MyDMV Portal $2.00 per electronic payment; MyFlorida app $4.00 (credit card) or $3.75 (checking) per transaction, up to 5 vehicles/vessels at once.
- **Registration base tax:** automobiles $14.50 / $22.50 / $32.50 by weight; motorcycles $10; original/replacement plate $28.
- **Titles:** Original New $77.25; Original Used $85.25; Transfer/Duplicate $75.25; Lien Only $74.25; Fast Title +$10; Late Title Fee $20; paper-title printing +$2.50; lien recording +$2.
- **Duplicate title:** form 82101 + valid ID + fee; only the lienholder may apply if a lien is outstanding; lost-in-transit reissue free within 180 days; original becomes void once a duplicate issues.
- **ELT:** electronic title = same info/documents as paper; lien notices/satisfactions transmitted electronically; convert e-title to paper online $4.50 (3–4 weeks by mail), by mail $2.50, in person fast title +$10 same day; titles cannot be printed at home.
- **Disabled parking:** permanent permit free, valid 4 years, renew by birthdate; temporary permit $15, up to 6 months, second permit within 12 months free; form 83039 signed by a certifying medical authority within the last 12 months; replacement also needs form 83146; wheelchair plate +$28.
- **Dealers:** license required at 3+ motor vehicles or 1+ MH/RV in 12 months; application form 86056, $300 per main location; $25,000 surety bond (form 86020); $25,000 garage liability + $10,000 PIP; fingerprints $54.25/person; training 8 hrs (franchise) / 16 hrs (independent/auction/wholesale/salvage).
- **Manufacturers/importers/distributors:** form 84256; license $300 (MV) / $340 (MH, RV); bonds $50,000 (MH manufacturer) / $10,000 (RV manufacturer/distributor/importer); must not do business before licensing (§320.61).
- **Vessels:** must title + register within 30 days of purchase; unregistered operation after 30 days is a second-degree misdemeanor; 1- or 2-year registration; title $5.25 e / $7.75 paper / $11 fast (+$1 per lien, +$4 if previously registered out of state); registration $5.50–$189.75 by length class (+$2.25 service, +$0.50 FRVIS); commercial non-resident fee +$50.
- **New residents:** FL driver license within 30 days of residency; title/register vehicles within 10 days; out-of-state vehicles need VIN verification (form 82040 or 82042).
- **Address change:** on a registration/tag/title/vessel/trailer — Motor Vehicle Service Center or MyDMV Portal (not the MyFlorida app).

## 14. Notes & gaps

1. **No standalone pages found** for "Duplicate Registration", "Duplicate Title", "Address Change" (vehicle) or "Importing Vehicles" as consumer pages. Those A-to-Z entries resolve to the Motor Vehicle Registrations page, MyDMV Portal, the Paper Liens and Titles page, county service-centre pages, and (for importing) the Liens & Titles page plus the manufacturer/importer/distributor licensing page. This is a finding about the site's structure, not a failure to look: the A-to-Z index was read in full and each in-scope entry was traced.
2. **Browser rate limit:** the final batch of five page opens (Disabled Permits FAQ, Dealer FAQ, Manufacturer/Importer/Distributor License, Visitors Disabled Permits, Wheelchair License Plate) returned HTTP 429 from the browser tool and were not re-attempted (per tool guidance). Facts from those five pages in this file come from flhsmv.gov search-result excerpts, not a full page read; they are flagged by their presence in §12's coverage note.
3. **Stale-looking dates on FLHSMV pages:** the vessel EPIRB/PLB reduced-fee window is printed as "July 1, 2016 through June 30, 2017 only for those who register in an office", and the heavy-truck birth-month transition is framed around Dec 2020 — both are reproduced as printed, not updated. The Fees page crawl was dated 2025-12-17 and the Fees-02 chart is Rev 06.22; fee figures should be re-checked against the live Fees page before being quoted as current.
4. **"Buying or Selling a Vehicle?"** consumer-education page is linked from the Liens & Titles and Paper Titles pages but was not opened in full in this session; its contents are not summarised here.
5. **Typo on FLHSMV's site:** the dealer hub prints "more than 15,0000" dealers/manufacturers licensed per year; read as 15,000.
6. Customer Service number repeated across pages: **(850) 617-2000**. MyDMV Portal is at mydmvportal.flhsmv.gov; the Motor Vehicle Check is at services.flhsmv.gov/MVCHECKWEB/.
# 11 — Crash Reports & Crash Data

**Study date:** November 23, 2026
**Scope:** How to obtain a Florida crash report, who can request one, fees, online vs. mail vs. in-person requests, crash data/statistics pages, and what information a report contains. All facts below come from flhsmv.gov pages (or FLHSMV-hosted documents). Where a fact comes from the Florida Statutes that FLHSMV's own pages cite, that is noted.

**Method note:** Direct page fetches of several flhsmv.gov pages were rate-limited (HTTP 429) during this study. The main Traffic Crash Reports page, the Crash Report Purchasing portal, the Crash and Citation Reports page, and the Live Traffic Crash report page were therefore read through the search index's cached copies of those exact flhsmv.gov URLs. The Crash Dashboard page was opened directly (it is a JavaScript app and returns header text only). Nothing in this section is sourced from a third-party site except where explicitly flagged.

---

## 1. The main page: Traffic Crash Reports

**URL:** http://www.flhsmv.gov/html/crashreport.html
(Also referenced under a newer path as http://www.flhsmv.gov/florida-highway-patrol/traffic-crash-reports/)

FLHSMV states it is **the state's official repository for crash records**. The page (and the Florida Crash Portal it links to) covers three things: purchasing a crash report, reporting a crash, and accessing Florida crash data.

### 1.1 Buy a crash report — online (Florida Crash Portal)

- **Governing law:** Section 316.066, Florida Statutes, governs the completion and subsequent distribution of traffic crash reports.
- **Availability / waiting period:** Traffic crash reports **may take up to 10 days to become available**. Law enforcement agencies have 10 days to submit crash reports, so search results may not contain reports on crashes that occurred within the last 10 days.
- **Fee:** **$10.00 per report**, per section 321.23, Florida Statutes. **Fees apply to anyone requesting a report.**
- **Convenience fee:** An additional **$2.00 convenience fee per payment transaction** applies to online purchases (non-refundable). One report online therefore costs $12.00 total.
- **Transaction limit:** Customers are limited to a **maximum of 10 reports per transaction**.
- **Delivery:** Once purchased, reports become **available online immediately** and **must be downloaded within 48 hours** of the request. A download link is sent to the email address provided at the time of request. Reports are provided as a **ZIP file containing PDF files**.
- **Portal URLs:** FloridaCrashPortal.gov; the purchasing service itself is at https://services.flhsmv.gov/crashreportpurchasing/crashreport ("Buy Florida Crash Reports").
- **Portal search:** The portal offers three search methods — by report/case number, by VIN, or by last name of a driver/vehicle owner involved (third-party walkthroughs of the live portal; the FLHSMV pages themselves do not spell out the search fields). Eligibility must be confirmed first: within the first 60 days the requester states their connection to the crash and provides a driver license number.

### 1.2 Buy a crash report — by mail or in person

- A **signed statement is required** to receive a crash report by mail or in person (HSMV Form 94010, Sworn Statement for Crash Report — see §2 below).
- **10 or fewer records:** Requests may be fulfilled at the **FHP Troop Station nearest to where the crash occurred**.
- **More than 10 records:** The request must include a request letter detailing the crash report(s) requested, a signed statement for each crash report requested, and payment, mailed to:

  > Florida Department of Highway Safety and Motor Vehicles
  > Crash Records
  > 2900 Apalachee Parkway, MS 28
  > Tallahassee, FL 32399

- **Payment by mail:** Check or money order made out to **"FLHSMV."** Payment must be included with the request.
- **Processing time by mail:** **4–6 weeks** to receive the record.
- **Phone:** Crash Reports/Records — **(850) 617-3416, Option 5** (FLHSMV Contact Us page). Public-records/data requests: (850) 617-3416, Option 1.

### 1.3 Report a crash (driver self-report)

- FLHSMV provides a downloadable **Driver Report of a Traffic Crash** form (HSMV Form 90011S, "Driver Report of Traffic Crash (Self Report) / Driver Exchange of Information").
- A completed self-report can be emailed to **SelfReportCrashes@flhsmv.gov** (or mailed to the Crash Records address above).
- **When a self-report is required:** Under section 316.066(1)(e), the driver of a vehicle involved in a crash resulting in damage to a vehicle or other property **which does not require a law enforcement report** must submit a written report to the department **within 10 days after the crash**, on a department-approved form.
- **When a law-enforcement report is required:** A Florida Traffic Crash Report, Long Form must be completed and submitted to the department **within 10 days after an investigation is completed** by the investigating officer, for a crash that resulted in death, personal injury, or any indication of complaints of pain or discomfort by any party or passenger. For other crashes on public roadways, the officer completes a short-form crash report or provides a driver exchange-of-information form.
- **⚠️ Threshold discrepancy (flagged, not FLHSMV-verified):** FLHSMV's pages still reflect the older **$500** apparent property-damage threshold for notifying law enforcement. Third-party legal sources state the threshold rose to **$2,000** for crashes on or after October 1, 2026 (ch. 2026-39, SB 488, amending s. 316.065). This could not be confirmed on an FLHSMV page during this study and should be re-checked live.

---

## 2. Who can request a crash report — the 60-day confidentiality rule

Traffic crash reports are **exempt from public disclosure** except for parties involved in the crash and other specific parties outlined in section 316.066, Florida Statutes.

- **For 60 days after the date the report is filed**, crash reports that reveal the identity, home or employment telephone number or home or employment address of, or other personal information concerning the parties involved are **confidential and exempt** from public disclosure (s. 316.066(2)(a)).
- **Within that 60-day period**, a report may be made immediately available only to:
  1. a party involved in the crash;
  2. the legal representative of a party involved;
  3. a licensed insurance agent of, an insurer of, or an insurer to which coverage has been applied for by, a party involved;
  4. a person under contract to provide claim or underwriting information for a qualifying insurer;
  5. a victim services program representative;
  6. a federal, state, or local governmental agency, or a private person/entity acting on behalf of such an agency in carrying out its functions;
  7. radio or television stations licensed by the FCC and newspapers qualified to publish legal notices (ss. 50.011 & 50.031) — with specified personal information redacted; and
  8. a third party acting on behalf of a person or entity listed above, for disclosure only to that person or entity.
- **Condition for access within 60 days:** the person must present a valid driver license or other photographic identification / proof of status demonstrating their qualification, and file a written **sworn statement** (HSMV Form 94010) stating that information from the crash report will **not be used for any commercial solicitation of accident victims**.
- **After 60 days:** crash reports may be made available to any person or entity in accordance with the permissible uses in the federal Driver's Privacy Protection Act (DPPA), 18 U.S.C. § 2721(b), including its resale/redisclosure requirements. (Form 94010, Section Two.)
- **Form:** HSMV Form **94010, Sworn Statement for Crash Report** (Rev. 03/2023); an accessible version, 94010-ADA, also exists. The form is listed on FLHSMV's Forms page.

---

## 3. Fees

| Item | Fee | Source |
|---|---|---|
| Crash report (copy) | **$10.00 per report** | s. 321.23, Fla. Stat.; FLHSMV Traffic Crash Reports page and Crash Portal |
| Online convenience fee | **$2.00 per transaction** (non-refundable) | FLHSMV Crash Portal |
| Maximum per online transaction | 10 reports | FLHSMV Crash Portal |

- **A-to-Z Guide entry "Crash Report Fees"** points to the same crash-report fee information above; no separate FLHSMV fees page for crash reports was found.
- **Related statutory fees (from s. 321.23 as cited by FLHSMV, not separately confirmed on an FLHSMV page):** homicide report copy $25.00; uniform traffic citation copy $0.50; crash photographs priced by size/finish (e.g., 5″×7″ color $1.00 / black & white $0.75; 8″×10″ color $1.50 / B&W $1.00). Information is furnished without charge to local, state, or federal law enforcement agencies for investigative purposes.

---

## 4. What information is in a crash report

Per section 316.066(1)(b), which FLHSMV's pages cite as governing the reports, the **Florida Traffic Crash Report, Long Form** must include:

1. the **date, time, and location** of the crash;
2. a **description of the vehicles** involved;
3. the **names and addresses of the parties involved**, including all drivers and passengers, and identification of the vehicle in which each was a driver or passenger;
4. the **names and addresses of witnesses**;
5. the **name, badge number, and law enforcement agency** of the officer investigating the crash;
6. the **names of the insurance companies** for the respective parties involved.

Each party must also provide the officer with **proof of insurance**, which is documented in the crash report. The short-form report contains the same core items (date/time/location, vehicle descriptions, parties, witnesses, officer, insurers) but, per FLHSMV's crash manual as cited in third-party summaries, does not require a narrative or diagram.

FLHSMV's Forms page lists the report forms themselves:
- **90010S:** Florida Traffic Crash Report (with 90010S(E) Event, 90010S(N/D) Narrative, and 90010S(V/P) Vehicle/Person variants)
- **90011S:** Accident Self Report

---

## 5. Crash data and statistics

### 5.1 Crash and Citation Reports & Statistics page

**URL:** https://www.flhsmv.gov/resources/crash-citation-reports/

FLHSMV states it "collects data and conducts research in order to provide lawmakers, partners and stakeholders, the media, and citizens with important facts and valuable information related to public safety and motor services," and compiles and analyzes traffic and safety data and emerging trends. When using information from these reports, FLHSMV asks that it be credited to "The Florida Department of Highway Safety and Motor Vehicles" or "FLHSMV."

The page hosts two report families:
- **Traffic Crash Facts** (annual reports by year; "Quick Statistics"; ADA versions for recent years)
- **Annual Uniform Traffic Citation Statistics** (2011–2023, plus 2003–2010)

### 5.2 Traffic Crash Facts (annual report)

- **Latest editions found:** 2023 (https://www.flhsmv.gov/pdf/crashreports/crash_facts_2023.pdf, 133 pages, closeout date January 8, 2025) and 2024 (https://www.flhsmv.gov/pdf/crashreports/2024-Crash-Report.pdf, 131 pages, closeout date January 22, 2026).
- **Coverage:** Statistics are extracted from law-enforcement reports of traffic crashes involving a motor vehicle that meet the criteria in s. 316.066. FLHSMV notes the statistics are **subject to change** as new and updated crash reports are received after the closeout date, and that summary totals may not match sub-tables.
- **Contents (2023 edition):** §1 Summary and Notes (data definitions, statistics summary, motoring environment); §2 Drug and Alcohol Statistics; §3 Person Involved Statistics (helmet use, safety restraints, injury levels by vehicle type, drivers in crashes); §5 Traffic Crash History by County (crash and injury history by county).
- **Headline 2023 figures (Traffic Crash Statistics Summary):** 395,175 total codable crashes; 679,482 drivers involved; 1,083 average crashes per day; mileage death rate 1.41 per 100 million VMT; 3,162 fatal crashes; 3,375 fatalities; 12,456 incapacitating-injury crashes; 15,399 incapacitating injuries; 151,957 other-injury crashes; 236,886 other injuries; 227,600 property-damage-only crashes; 5,132 alcohol-confirmed crashes; 553 drug-confirmed crashes; 9,548 motorcycle crashes and 621 motorcycle fatalities.
- **Headline 2024 figures (statewide row, as printed in the 2024 report):** 381,423 total crashes; 3,098 fatalities; 246,426 total injuries; 2,891 fatal crashes.

### 5.3 Florida Crash Dashboard

**URL:** https://www.flhsmv.gov/traffic-crash-reports/crash-dashboard/

- Public, interactive dashboard providing **up-to-date, general crash statistics in visual format with graphs and charts**.
- Users can **filter by year, county, or pre-selected crash types**; covers all traffic crashes reported by law enforcement that meet long-form requirements, on all public roadways.
- **Refresh:** data refreshes **monthly**; it takes agencies up to 90 days to report crashes, so recent periods are incomplete.
- The page itself is a JavaScript application; a direct text fetch returned only the site header, so the dashboard's on-screen labels could not be captured in this study.

### 5.4 Other crash-data access (per the Traffic Crash Reports page, "Crash Data" section)

- **FLHSMV Crash Facts page** — see §5.2.
- **FLHSMV Florida Crash Dashboard** — see §5.3.
- **Signal 4 portal:** governmental agencies and their contractors can obtain access to the Signal 4 portal (detailed crash-data analytics; access is restricted, not public).
- **Media requests** for additional data should be submitted to the **Office of Communications**.
- **Public records requests** for additional data should be submitted to **CrashRecords@flhsmv.gov** (also by phone at (850) 617-3416, Option 1).

---

## 6. Live Traffic Crash & Road Condition Report

**URL:** https://trafficincidents.flhsmv.gov/SmartWebClient/Home.aspx
(A-to-Z Guide entry: "Live Traffic Crash & Road Condition Report")

- **Purpose:** live, map-based report of active FHP traffic incidents — crashes, roadblocks, roadway hazards, and road condition reports.
- **Update frequency:** reports are **updated every five minutes**.
- **Coverage limit:** incidents located **within city limits may not show** on the map, since it is not common practice for FHP to work incidents inside city limits. If no incidents appear in an area, either FHP has not received a call or FHP is not currently working incidents there.
- **Not archived:** crash information from the Live Traffic Crash and Road Condition Report **is not archived and cannot be retrieved for review or statistical purposes**. The page directs users to the Traffic Crash Report page to request a crash report.
- The page also restates the 60-day confidentiality rule (s. 316.066, as amended effective June 5, 2001) and links out to FDOT real-time traffic volume/speed maps, construction projects, Florida traffic information, Florida 511, and Turnpike updates (links leave the FLHSMV/FHP site).

---

## 7. A-to-Z Guide entries relevant to this section

From https://flhsmv.gov/a-to-z-guide/ (letter C, L, P, T):

- **Crash Reports**; **Crash Report Fees** (both under C)
- **Live Traffic Crash & Road Condition Report** (under L)
- **Publications (Crash and Citation Reports)** (under P)
- **Traffic Citation Statistics**; **Traffic Crash Facts** (under T)
- **Uniform Traffic Citation Stats** (under U)

---

## 8. Page list — every URL studied

| # | URL | What was found |
|---|---|---|
| 1 | https://flhsmv.gov/ | Homepage; text extract showed press releases only, no crash content surfaced |
| 2 | https://flhsmv.gov/a-to-z-guide/ | Index entries: Crash Reports, Crash Report Fees, Traffic Crash Facts, Live Traffic Crash & Road Condition Report, Publications (Crash and Citation Reports), Traffic Citation Statistics, Uniform Traffic Citation Stats |
| 3 | http://www.flhsmv.gov/html/crashreport.html | **Traffic Crash Reports** — main page: $10 fee, $2 convenience fee, 10-report max, 10-day availability, 48-hour download, ZIP/PDF delivery, mail/in-person rules, self-report form, Crash Data section (read via search-index cache; direct fetch rate-limited 429) |
| 4 | http://www.flhsmv.gov/florida-highway-patrol/traffic-crash-reports/ | Newer-path reference to the Traffic Crash Reports page (cited by Miami-Dade County; not directly opened) |
| 5 | https://services.flhsmv.gov/crashreportpurchasing/crashreport | **Buy Florida Crash Reports** portal: $10 + $2 per transaction, max 10 per transaction, 48-hour download, 10-day submission window (read via search-index cache; direct fetch rate-limited 429) |
| 6 | https://www.flhsmv.gov/traffic-crash-reports/crash-dashboard/ | **Crash Dashboard** — public interactive crash statistics; opened directly, JS app (header text only in fetch) |
| 7 | https://www.flhsmv.gov/resources/crash-citation-reports/ | **Crash and Citation Reports & Statistics** — Traffic Crash Facts by year, Uniform Traffic Citation Statistics, credit line (read via search-index cache; direct fetch rate-limited 429) |
| 8 | https://www.flhsmv.gov/pdf/crashreports/crash_facts_2023.pdf | **Florida Traffic Crash Facts Annual Report 2023** — 133 pp., closeout Jan 8, 2025; 395,175 crashes, 3,375 fatalities (read via search-index cache) |
| 9 | https://www.flhsmv.gov/pdf/crashreports/2024-Crash-Report.pdf | **Florida Traffic Crash Facts Annual Report 2024** — 131 pp., closeout Jan 22, 2026; 381,423 crashes, 3,098 fatalities (URL via third-party citation of the FLHSMV PDF) |
| 10 | https://trafficincidents.flhsmv.gov/SmartWebClient/Home.aspx | **Live Traffic Crash & Road Condition Report** — updates every 5 min, city-limit incidents may not show, not archived (read via search-index cache) |
| 11 | https://www.flhsmv.gov/contact-us/ | Crash Reports/Records phone (850) 617-3416 Option 5; FloridaCrashPortal.gov (read via search-index cache) |
| 12 | https://www.flhsmv.gov/resources/forms/ | Forms 90010S (Florida Traffic Crash Report + variants), 90011S (Accident Self Report), 94010 (Sworn Statement for Crash Report) (read via search-index cache) |
| 13 | https://www.flhsmv.gov/pdf/forms/94010.pdf | HSMV Form 94010, Sworn Statement for Crash Report (referenced; contents confirmed via the form text in search results) |
| 14 | https://www.flhsmv.gov/pdf/forms/90011s.pdf | HSMV Form 90011S, Driver Report of Traffic Crash (referenced; contents confirmed via search results) |

---

## 9. Gaps and things to verify live

1. **Direct fetch failures:** The main crash report page, the purchasing portal, the Crash and Citation Reports page, and the Live Traffic page were all read from search-index caches because direct fetches returned HTTP 429 (rate limit). A live re-check of those four URLs would confirm the text is current.
2. **Crash Dashboard contents:** The dashboard is a JavaScript app; its on-screen filters, charts, and labels could not be captured by text fetch. Needs a live browser check.
3. **$500 vs. $2,000 property-damage threshold:** FLHSMV pages appear to still show $500; statute sources say $2,000 from October 1, 2026. Needs a live check of the current FLHSMV crash page.
4. **"Crash Report Fees" A-to-Z entry:** No separate fees page was found; it resolves to the same $10/$2 fee information on the crash report page.
5. **2024 Crash Facts PDF:** The 2024 report URL was confirmed only through a third-party page citing the FLHSMV PDF, not through a direct FLHSMV index entry in this study.
# 12 — DUI: Programs, Penalties & Ignition Interlock

Source: flhsmv.gov only. All facts below were read directly from FLHSMV pages
listed in the Page List. Where FLHSMV publishes a summary, the pages carry this
disclaimer: "This summary was prepared by the Department of Highway Safety and
Motor Vehicles (FLHSMV) and should be used for reference only. Please refer to
the full text of any laws referenced below for complete and comprehensive legal
information."

## 1. What a DUI is under Florida law (FLHSMV)

- DUI is one offense, proved by impairment of normal faculties by alcohol,
  chemical substances, or controlled substances, or by an unlawful blood
  alcohol or breath alcohol level of **0.08 or above**. The penalties upon
  conviction are the same regardless of how the offense is proven.
- Driving while impaired by drugs is illegal and subject to the same penalties
  as driving while impaired by alcohol.
- Possession of an open alcoholic beverage container in a vehicle (in motion
  or stopped) by the driver and/or passenger(s) is a violation of Florida law.
- The legal drinking age in Florida is 21. Anyone under 21 in possession of
  alcohol can be cited for a second-degree misdemeanor.

## 2. Licensed DUI Programs

### Oversight and purpose

- FLHSMV's **Bureau of Motorist Compliance** provides administrative oversight
  for licensed DUI programs statewide.
- **Chapter 15A-10, F.A.C.** gives FLHSMV authority to certify instructors,
  investigate complaints, and evaluate program effectiveness.
- DUI programs are **non-profit organizations** required to provide drug and
  alcohol education to DUI offenders to satisfy judicial and driver licensing
  requirements.
- Programs must provide three services: **education, psycho-social evaluation,
  and treatment referral**.

### The two course levels

| Level | Who | Minimum classroom time |
|---|---|---|
| Level I | First-time offenders | **12 hours** of classroom instruction, informative and interactive techniques |
| Level II | Persons with multiple offenses | **21 hours** of classroom time, primarily interactive techniques in a group setting; average class size may not exceed **15 students** |

- Level II focuses on the problems of the repeat offender and treatment
  readiness; the majority of students are referred to treatment.
- Treatment from a **Department of Children and Families (DCF)-licensed**
  treatment provider is often used in conjunction with the Level II DUI class.

### County coverage

- The Licensed DUI Programs page lists the licensed program(s) serving every
  Florida county, grouped by judicial-circuit service area (e.g. North Central
  Florida Safety Council for Alachua/Bradford/Dixie/Gilchrist/Levy/Union;
  Northeast Florida Safety Council for the Jacksonville-area counties; DUI
  Counterattack Hillsborough, Inc. for Hillsborough; Suncoast Safety Council
  for Pinellas; Florida Safety Council for Brevard and Orange/Osceola/Seminole).
- The page carries a COVID-19 notice that services and hours may be impacted
  and directs users to check with the provider.

### DUI Program Service Fees (standardized fees as of October 1, 2023)

| Fee type | Amount |
|---|---|
| Level I registration (includes $5 Driver Risk Inventory–DRI) | **$330** |
| Level II registration (includes $5 DRI) | **$495** |
| Driver Risk Inventory (DRI), added to Level I and II registration | $5 |
| Reinstatement Review Inventory (RRI) | $5 |
| Level I — 1st course reassignment within 90 days of enrollment | $40 |
| Level I — 2nd course reassignment within 90 days | $75 |
| Level I — 3rd course reassignment within 90 days | $153 |
| Level I — any course reassignment more than 90 days after enrollment | $275 |
| Level I — any reassignment for coming to DUI services under the influence | $275 |
| Level II — 1st course reassignment within 90 days of enrollment | $60 |
| Level II — 2nd course reassignment within 90 days | $120 |
| Level II — 3rd course reassignment within 90 days | $238 |
| Level II — any course reassignment more than 90 days after enrollment | $420 |
| Level II — any reassignment for coming to DUI services under the influence | $420 |
| Level I or II — 1st evaluation reassignment within 90 days of enrollment | $75 |
| Level I or II — 2nd evaluation reassignment within 90 days of enrollment | $153 |
| Evaluation only (not associated with enrollment in the complete program) | $75 |
| Evaluation for any out-of-state program | $150 |
| Driving record, Florida — TML (optional charge for the client) | $15 |
| Driving record, Florida — MVR (optional charge for the client) | $16 |
| Driving record, Florida — FDLE (optional charge for the client) | $25 |
| Driving record, out-of-state ($1 above actual cost, which varies) | Cost + $1 |
| Transfer fee | $25 |
| Copy fee | $10 |
| Bad checks | $30 |
| Administrative refund fee | $25 |
| Processing a referral to a different treatment agency | $15 |
| Treatment verification form | $10 |

### Special Supervision Services (SSS) fees

| Fee type | Amount |
|---|---|
| SSS application fee (includes $25 eligibility screening + $15 State Assessment Fee + $40 urinalysis + $5 DRI) | **$332** |
| SSS periodic update | $55 |
| SSS periodic update with ignition interlock review | $65 |
| SSS periodic update reschedule fee | $55 |
| SSS FDLE criminal background check | $25 |
| SSS annual State Assessment Fee | $15 |
| SSS blood test for alcohol | $30 |

### Ignition interlock violation appointments (charged through the DUI program)

| Fee type | Amount |
|---|---|
| IID 1st violation — appointment | $25 |
| IID 2nd violation — appointment + case management plan development | $55 |
| IID 2nd or subsequent violation — monthly appointment | $45 |
| IID 3rd or subsequent violation — appointment + treatment referral | $55 |
| IID rescheduling fee | $25 |
| IID treatment referral — DRI re-test (if none in last 6 months) | $5 |

## 3. How to become a licensed DUI program

- FLHSMV is authorized to license and regulate DUI programs under
  **section 322.292, Florida Statutes**. Programs must be licensed under the
  standards in **chapter 15A-10, F.A.C.**
- Applicants must submit a completed **Application for Licensure to Conduct a
  Driving Under the Influence (DUI) Program (form HSMV 77035)**, with all
  required documents listed on pages 4 and 5 of the application, to:

  > Florida Department of Highway Safety and Motor Vehicles
  > Attn: Bureau of Motorist [Compliance]
  > 2900 Apalachee Parkway, Room A202, Mail Stop 98
  > Tallahassee, FL 32399-0500

- Once the application documents are received, FLHSMV gives written notice to
  the appropriate **chief judge** and all licensed programs operating within
  the judicial circuit where the organization applied.
- FLHSMV consults with the chief judge to determine if a need for an
  additional program exists in the area, and considers whether the addition
  would result in improved service for the number of clients currently served
  within the circuit.
- Criteria considered when reviewing an application:
  - Increased number of classes and locations for services offered by the
    applicant program.
  - Services and fees currently offered by the applicant program and any
    existing DUI program.
  - Number of DUI clients currently served and historical trends in client
    numbers within the circuit.
  - Availability, accessibility, and service history of any existing DUI
    program services.
  - The applicant program's service history.
  - Availability of resources, including personnel, demonstrated management
    capability, and capital and operating expenditures by the applicant.
  - Improved services to minority and special-needs clients.
- FLHSMV directs applicants to review chapter 15A-10, F.A.C., in its entirety
  for all DUI program requirements.
- Related form: **HSMV 77054**, Driving Under the Influence Programs Complaint
  form (for complaints against a DUI program).

## 4. DUI penalties (as stated on FLHSMV pages)

From the FLHSMV Impaired Driving page:

- For **any DUI conviction**, the driver license will be revoked for a
  **minimum of 180 days**.
- If you **refuse to take a required roadside test** at the time of arrest,
  your license will be **automatically suspended for one year**.
- Fines for DUI can range from **$500 to $5,000**, with mandatory DUI school
  education.
- Penalties can also include an ignition interlock device, community service,
  probation, or imprisonment.
- **DUI convictions must remain on your record for 75 years.**

## 5. Administrative suspension and the Bureau of Administrative Reviews

- FLHSMV's **Bureau of Administrative Reviews (BAR)** offices handle hardship
  license applications and DUI formal reviews. County office listings show BAR
  hearing-request forms for: **Hardship License**, **Formal Review – DUI**, and
  **Waiver of Formal Review – 1st DUI only**.
- A hardship license / formal review request can be made without visiting a
  BAR office: complete the correct form and submit it via email to the local
  BAR office.
- A hardship license restricts driving to **employment or business purposes
  only** (stated on the Other Common Suspensions and Revocations page for
  comparable suspensions; see also section 6).
- Hardship-license process, as described on FLHSMV's suspensions/revocations
  pages: apply through the local Administrative Reviews Office, submit proof
  of the required school completion, and pay a reinstatement fee plus any other
  applicable license fees. Additional suspensions may require additional
  clearance requirements.
- Note: child support delinquency suspensions are **not** eligible for a
  hardship license.

## 6. Ignition Interlock Device (IID) Program

### Who must have one and when

- **Section 316.193, Florida Statutes**, mandates IIDs on the vehicles of
  certain persons convicted of DUI.
- The IID program affects those arrested and convicted of DUI **after
  July 1, 2002**, upon eligibility for reinstatement of a permanent or
  restricted driver license.
- An IID is also required when a driver convicted of DUI applies for a
  restricted license for work or business purposes, as authorized in
  **section 322.271, Florida Statutes**.
- If a person is otherwise eligible, a driver license is issued with a
  **"P" restriction** indicating an IID is required. The required time period
  for an IID **begins on the day the "P" restriction is issued**.
- An individual with an open DUI sanction mandating an IID who wishes to
  reinstate their license must have an IID installed **prior to license
  reinstatement**.

### Required IID durations by conviction

| DUI conviction | Ignition interlock required |
|---|---|
| First conviction | If court ordered |
| First conviction, BAL 0.15 or above, or minor in car | At least **6 months** |
| Second conviction | At least **1 year** |
| Second conviction, BAL 0.15 or above, or minor in car | At least **2 years** |
| Third conviction | At least **2 years** |
| Four or more convictions (condition of hardship license) | At least **5 years** |

### How the clock runs, and reinstatement

- Restriction time does **not** begin once the IID is installed. Time counts
  only once the IID "P" restriction is placed on the driving record and the
  license is reinstated. Customers must visit a driver license service center
  or tax collector office after installation to have the "P" restriction added.
- To reinstate, the customer must have an IID installed in a vehicle they own
  and/or routinely operate. There is **no reinstatement provision** for people
  who do not own and/or routinely operate a vehicle.
- A customer may present a court order or other documentation to a local DHSMV
  Bureau of Administrative Reviews (BAR) office for consideration of whether
  an IID is required.
- Most courts electronically report DUI convictions to FLHSMV. The court order
  should reflect both the time of the suspension and the IID requirement;
  FLHSMV advises verifying with the clerk of court that the electronic
  reporting includes the IID requirement.

### Device operation and thresholds

- IID alcohol threshold: **0.025 BAL** if convicted after July 1, 2013;
  **0.050 BAL** if convicted before July 1, 2013. Anything above the threshold
  will not allow the vehicle to start. By court order, judges may require a
  lower threshold.
- Rolling retest: up to **3 minutes** to give a breath sample before the alarm
  sounds.
- The IID will **never** shut off a vehicle while someone is driving.
- Accuracy: the IID is re-calibrated at each **monthly service visit**; a
  diagnostic test is performed each time the IID is powered on.
- Anti-circumvention features include humming while blowing, humidity reading,
  power disconnect reading, and rolling retest.

### What counts as a violation

- Any two breath test results above the mandated BAL upon initial startup;
- any refusal to submit to a required rolling retest (missed test);
- any rolling retest above the mandated BAL; or
- any evidence of equipment tampering.
- If a customer receives a violation letter, they must contact a licensed DUI
  program serving the county where they live, work, or attend school
  **within 10 days of the date of the letter** to schedule an appointment. The
  DUI program reviews IID use with the customer and discusses the
  circumstances of the notification.
- Mouthwash containing alcohol can register on the device. If the level is high
  enough to prevent starting, rinse with water and wait for the **5-minute
  retest**; passing the retest identifies the first test as latent alcohol.
  Failure to take and/or pass the retest results in a violation.

### Removing the IID early

- Customers must **surrender their license** before a provider will remove an
  IID. They may go to a driver license office or tax collector office and
  request to voluntarily surrender the license, receive proof of surrender,
  and present it to the provider.
- If the IID is removed prior to the expiration date on the restriction,
  customers may be required to **start their restriction time over without
  credit for past compliance**.

### Employer vehicles, registration, and other drivers

- If the customer meets IID requirements, holds a valid license with a "P"
  restriction, and has **written permission from the employer**, they may
  operate the employer's vehicle for job-related purposes without the IID. The
  permission letter must be kept with the vehicle and shown to law enforcement
  if stopped.
- A customer required to have an IID **can** register a vehicle and secure a
  license plate without a driver license — but if there are outstanding
  insurance, child support, or failure-to-pay (D6) suspensions, the plate
  cannot be issued until those suspensions are cleared.
- Anyone who drives the vehicle must use the IID to start and operate it.

### Out of state / moving / changing providers

- If a customer moves out of state, the IID requirement follows them if they
  hold a Florida license; Florida will not clear the driver record until all
  requirements are met. Contact an IID provider to coordinate installation and
  service out of state.
- Dual residents can use IID service centers in both states if the same
  provider is used in both states or the in-state provider coordinates with
  the out-of-state provider.
- To change providers, contact the new provider; it may work with the previous
  provider or instruct the customer how to complete the transfer. The customer
  is responsible for returning the previous provider's equipment unless
  otherwise instructed. Approved IID providers must maintain a service center
  in each judicial circuit within Florida.

### Approved IID service providers (7 vendors)

Providers must meet 15A-9.007, F.A.C., National Highway Traffic Safety
Administration Standards, and section 316.1938, Florida Statutes.

| Provider | Contact | Approved device |
|---|---|---|
| LifeSafer | 855-527-1598 | L250 |
| Low Cost Interlock, Inc. | 844-276-0554 | LCI-777 |
| Intoxalock | 844-612-3952 | 1001A |
| Smart Start | 800-880-3394 | SSI 2030 |
| RoadGuard Interlock (services by Nationwide Interlock) | 866-694-6099 | Draeger Interlock 7000 |
| Alcohol Detection Systems (ADS) | 888-205-1834 | Determinator 2 DM-909 |
| ALCOLOCK | 866-837-8646 | Alcolock LR |

- FLHSMV and the seven IID vendors offer discounts for IID services beginning
  **September 1, 2020**, after FLHSMV found cost was the most pervasive
  barrier to compliance. Eligibility, discounts, and terms are set by each
  vendor; contact vendors directly.
- Indigent guideline: if the court determines the convicted person is unable
  to pay for IID installation, the court may order that a portion of the fine
  paid for a section 316.193 violation be allocated to defray the cost of
  installation.
- Note: SkyFine clients should contact one of the IID vendors above and say
  they are a SkyFine customer to transition to a new device.

### Related FLHSMV fee-schedule items

- Administrative fee for alcohol and drug related offenses: **$130.00**
- Revocations (additional administrative fee shown above required if alcohol or
  drug related): **$75.00**
- Suspensions (additional administrative fee shown above required if alcohol or
  drug related): **$45.00**
- Filing fee for hardship hearing: **$12.00**
- Filing fee for formal/informal review: **$25.00**
- DUI program fee (assessed by the program): **$15.00**
- Interlock fee (assessed by the vendor): **$12.00**
- An additional **$6.25** service fee may apply to any credential issued in a
  tax collector office.

## 7. Teens & young adults with DUIs (zero tolerance, under 21)

- Drivers under 21 with a blood alcohol level of **0.02 percent or more** will
  have their license immediately suspended for **six months** (first offense,
  administrative action).
- A second offense results in a **one-year** suspension.
- A first offense for refusal to submit to a breath, urine, or blood test
  results in a **12-month** suspension; a second offense results in an
  **18-month** suspension.
- Statutory reference given on the page: section **322.2616**, Florida
  Statutes.

## 8. DUI in the suspensions/revocations index

- FLHSMV's "Other Common Suspensions and Revocations" page lists "Driving
  Under the Influence (DUI) and Ignition Interlock Device (IID) revocations"
  as a linked topic alongside Financial Responsibility suspensions and
  medical/vision revocations or suspensions.
- That page also documents the hardship-license pattern used across
  suspensions/revocations: apply through the local Administrative Reviews
  Office, submit proof of the required school completion, pay a reinstatement
  fee plus other applicable license fees; a hardship license restricts driving
  to employment or business purposes only. Examples on the same page: HTO
  revocation is 5 years, hardship application after 1 year (with ADI school
  completion); a Chapter 893 drug-offense suspension is at least 1 year,
  hardship application after 6 months (with Licensed DUI Program school
  completion).

## Gaps / not verified from FLHSMV pages in this pass

- **Per-offense revocation periods (2nd/3rd/4th conviction):** FLHSMV's
  Impaired Driving page states only the 180-day minimum revocation for any DUI
  conviction. The dedicated FLHSMV "DUI and Ignition Interlock Device (IID)
  revocations" subpage is linked from the Other Common Suspensions and
  Revocations page, but its URL was not exposed by the site's text-fetch
  rendering and did not surface in web search, so its per-offense revocation
  table could not be read in this pass. Do not fill it in from law-firm or
  statute sites; re-check that FLHSMV subpage directly.
- **Administrative suspension at arrest (BAL vs. refusal lengths, 10-day
  review deadline, 30/90-day hardship waiting periods):** not stated on the
  FLHSMV pages opened in this pass, beyond the 1-year automatic suspension for
  refusing a roadside test. The BAR office listings confirm Formal Review–DUI
  and Waiver of Formal Review (1st DUI only) forms exist, but the deadlines
  and suspension lengths were not verified from FLHSMV text here.
- **A-to-Z "DUI" landing page:** the A-to-Z Guide lists a DUI entry, but the
  text rendering did not expose its target URL, so it could not be opened
  separately; its content is presumed to point at the DUI-and-IID pages above.
- **Fees page crawl note:** the DUI Program Service Fees page states fees "as
  of October 1, 2023"; the page copy available was last crawled 2026-01-16.
  Confirm current fees before quoting them as live.

## Page List (every URL studied)

1. https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/ — Education & Courses hub; "Florida Licensed DUI Programs" summary (education, psycho-social evaluation, treatment referral; becoming a licensed program).
2. https://flhsmv.gov/a-to-z-guide/ — A to Z Guide; entries for "DUI" (D section) and "Ignition Interlock" (I section).
3. https://flhsmv.gov/driver-licenses-id-cards/education-courses/dui-and-iid/licensed-dui-programs-florida/ — Licensed DUI Programs in Florida: Bureau of Motorist Compliance oversight, Ch. 15A-10 F.A.C., non-profit programs, Level I (12 hrs) / Level II (21 hrs, max 15 students), DCF treatment, county-by-county program directory.
4. https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/dui-and-iid/dui-program-service-fees/ — DUI Program Service Fees, standardized fees as of October 1, 2023 (full table in section 2).
5. https://flhsmv.gov/driver-licenses-id-cards/education-courses/dui-and-iid/become-dui-program/ — How to Become a DUI Program: s. 322.292 F.S., Ch. 15A-10 F.A.C., form HSMV 77035, Tallahassee mailing address, chief-judge consultation, review criteria.
6. https://www.flhsmv.gov/driver-licenses-id-cards/education-courses/dui-and-iid/ignition-interlock-program/ — Ignition Interlock Program: s. 316.193 F.S., post–July 1, 2002 applicability, "P" restriction, 7 approved providers/devices, court reporting, indigent guidelines, IID duration chart.
7. https://flhsmv.gov/driver-licenses-id-cards/education-courses/dui-and-iid/ignition-interlock-device-iid-faqs/ — IID FAQs: duration chart, "P" restriction clock, no-vehicle rule, employer-vehicle exception, thresholds 0.025/0.050 BAL, violation definition, 10-day violation-letter deadline, early-removal surrender rule, out-of-state rules.
8. http://www.flhsmv.gov/safety-center/be-responsible-dont-drink-and-drive/ — Impaired Driving: DUI definition (0.08), penalties (180-day minimum revocation, 1-year refusal suspension, $500–$5,000 fines, mandatory DUI school, 75-year record retention).
9. http://flhsmv.gov/driver-licenses-id-cards/education-courses/dui-and-iid/teens-young-adults-duis/ — Teens & Young Adults with DUIs: zero tolerance 0.02, 6-month/1-year suspensions, refusal 12-month/18-month, s. 322.2616 F.S.
10. https://www.flhsmv.gov/driver-licenses-id-cards/driver-license-suspensions-revocations/other-suspensions-revocations/?ref=filter%2Fresourcetype%2Fall — Other Common Suspensions and Revocations: DUI/IID revocations link, hardship-license pattern, HTO and Ch. 893 examples.
11. https://www.flhsmv.gov/fees/ — Fees: $130 alcohol/drug admin fee, $75 revocation, $45 suspension, $12 hardship hearing filing fee, $25 formal/informal review filing fee, $15 DUI program fee, $12 interlock fee.
# Section 13 — MyDMV Portal & Online Services (flhsmv.gov)

Study date: November 23, 2026. All facts below are from FLHSMV pages unless marked otherwise.
Source note: flhsmv.gov rate-limited direct page fetches during this study (HTTP 429 on
two attempts). Pages marked "opened directly" were read in full via browser.open; pages
marked "via search index" were read from the search engine's indexed copy of the FLHSMV
page itself (flhsmv.gov text, not a third-party summary). Third-party pages are cited
only where flagged as such and are never presented as FLHSMV fact.

## 1. What the MyDMV Portal is

- "MyDMV Portal is a quick and convenient way for eligible Florida driver license and
  identification (ID) card holders and businesses to access and request many driver
  license and motor vehicle services online at any time."
- Portal home: https://mydmvportal.flhsmv.gov/Home/en/Account/Landing
- FLHSMV's own description page calls it "the official online renewal site for the
  FLHSMV" (press release, March 6, 2019).
- FLHSMV also offers the MyFlorida mobile app for motor-vehicle/vessel registration
  renewals (up to five vehicles/vessels in one transaction, one processing fee).

## 2. Account setup (how to get in)

Per the FLHSMV MyDMV Portal page (opened directly):

- "Customers must create a secure MyDMV Portal account by verifying their identify
  with our records. If unsuccessful, customers will receive notification and will
  need to visit a local office for service."
- FLHSMV has produced a series of how-to videos showing customers how to access each
  service (linked from the portal page; video embed on the page).
- Account creation (per the FLHSMV "Creating a MyDMV Account" flyer, hosted on a tax
  collector site, describing the official portal flow — third-party host, FLHSMV
  content): go to mydmvportal.flhsmv.gov, click "Login to MyDMV Portal," agree to the
  Driver Privacy Protection Act terms, click "Enroll Now," complete Account
  Verification (individual or business), affirm a perjury statement, answer four (4)
  qualifying identity questions correctly within a time limit, enter an email address,
  then click the confirmation link in the email within 24 hours.
- Help lines (FLHSMV Contact Us page, via search index):
  - Login / account access issues: 850-617-3803
  - Navigating the portal / completing a transaction: 850-617-2000
  - Customer Service Center reps: Monday–Friday, 8:00 a.m.–5:00 p.m. EST, 850-617-2000
  - Self-service phone line 24/7: 850-617-3000
- Account creation itself is free. Online transactions carry a non-refundable $2.00
  convenience/processing fee, and once an online order is placed it cannot be
  cancelled (GoRenew / services.flhsmv.gov, via search index).

## 3. What can be done online in the MyDMV Portal (account required)

From the FLHSMV MyDMV Portal page (opened directly), services are grouped as:

### Driver License (DL) & ID Card transactions
- Commercial Driver License (CDL) Renewal
- CDL Replacement
- Commercial Learner's Permit (CLP) Replacement
- DL/ID Renewal
- DL/ID Replacement
- Downgrade DL/CDL to a DL/ID Card
- Identification (ID) Card Renewal
- Identification (ID) Card Replacement

### Parking Permit transactions
- Request Additional Parking Permit; Parking Permit Replacement/Duplicate; Parking
  Permit Renewal

### Registration & Title transactions
- Print Electronic Title; Title Duplicate; No Longer Owned; Registration Renewal;
  Registration Replacement/Duplicate; Specialty Plate Voucher; Plate and/or Decal
  Replacement

### Business Customer transactions
- Bulk Driver License Record Request; Subscription Services; Fleet Maintenance; plus
  the parking-permit, title and registration items above

### Submit or Request Documents
- Administrative Hearing Request; Driver License Record Request; Obtain a Clearance
  Letter

### View or Update Personal Information
- Citation Inquiry; Emergency Contact Information; Parental Access of Minor Driving
  History; Residential and Mailing Address Update; Sanction and Stop Inquiry; Social
  Security Number Update; Withdraw Parental Consent

## 4. Express Services — no MyDMV Portal account needed

From the FLHSMV MyDMV Portal page (opened directly): "The following services remain
available without a MyDMV Portal account, however, the information that can be viewed
is limited."

- **Driver License Check** — check your driver license status
- **Motor Vehicle Check** — assistance with registration inquiries
- **Express Motor Vehicle Renewal** — quick renewal options for parking permit and
  registration renewals
- **Emergency Contact Information** — add emergency contact information

## 5. Driver License Check (DL Check) — the free status tool

URLs (both live, same tool):
- https://services.flhsmv.gov/dlcheck/ (opened directly — entry form only)
- https://mydmvportal.flhsmv.gov/home/en/publicweb/dlcheck/

What it is, per FLHSMV (Driver Licenses & ID Cards hub page, via search index):
- "The Driver License Check system can be used to review the status of certain items
  connected to your driver license (e.g. driver status and driver improvement school
  eligibility) or to update your social security number or insurance information.
  Parents may also access the driving history of their child with this system."

What the tool does / shows (FLHSMV pages + a captured DL Check results page):
- Entry: enter your Florida driver license number (example format Z123-456-78-901-0,
  with or without hyphens) and retype the CAPTCHA code. No account, no fee.
- Free: "You may review the current status of your driver license online at no cost
  by using our Online Driver License Check." (Questions About Driving Records)
- The results page shows: license status (VALID / expired / suspended / revoked),
  license class (e.g. Class E), expiration date, Restrictions / Endorsements /
  Designations ("None on Record" where applicable), Effective Insurance Cancellation
  Suspensions, and Court Suspension(s) — Court Requirements Not Met.
- **Traffic school eligibility: the results page states "You are currently eligible
  to elect traffic school."** (Captured DL Check results page text, via search index;
  the line appears verbatim on the results page.)
- The DL Check menu offers, from the same session: Online Insurance Update, Driving
  School Eligibility Check, Social Security Number Update, Parental Access of Minor
  Driving History, and Driver License and ID Card Tracking System.
- "When you check your driver license status by entering the number above, if it
  displays 'VALID,' it simply indicates the FLHSMV has already received information
  and cleared your record. You may disregard any notice you received and print the
  response as your latest official receipt from the FLHSMV."
- The results page states: "The status of your license is the result of the
  infractions on your driver record. This is not an official driver record. For
  information on how to obtain an official driver record, visit MyDMV Portal."
- Per the FLHSMV Contact Us page, DL Check self-service options also include: make an
  appointment; check driver license; online insurance update; driving school
  eligibility check; Social Security number update; replace or renew a DL or ID card.
- For a parent: enter the teen's (under 18) driver license number; after the record
  is retrieved, enter the last four digits of the driver's Social Security number and
  the date of birth to view the driving history.
- Out-of-state/country renewal by mail: "use our Driver License check tool where you
  can enter your Florida driver license number, check the status of your driver
  license and if eligible download a renewal application." (FLHSMV FAQ)

## 6. Online insurance update

- Per the FLHSMV "Menu of Common Online Services" page (via search index):
  "Online insurance update — Use Driver License Check to update your insurance
  information for your fr case." ("fr case" = financial responsibility case.)
- The insurance update is offered on the Driver License Check results page after
  entering the license number (FLHSMV DL Check menu, via search index).
- The 2019 FLHSMV press release confirms: "Customers can check the status of their
  Florida driver license and provide online insurance updates through the
  department's DL Check."

## 7. Social Security number update

- Per the FLHSMV "Menu of Common Online Services" page: "Online Social Security
  number update — Use Driver License Check to update your social security number on
  your driving record if you have been requested to do so by DHSMV."
- SSN update is also offered on the DL Check results page.
- For online DL/ID renewal or replacement, "the department must verify a customer's
  Social Security number. If the department is unable to verify, the customer must
  follow up with the Social Security Administration." (Renew or Replace page)

## 8. Driver License and ID Card Tracking System

- Listed in the FLHSMV A-to-Z Guide as "Driver License and ID Card Tracking System"
  (also "ID Card and Driver License Tracking System," "Online order (ID card or
  Driver License) tracking/status," "Status of Your Driver License or ID Card Order,"
  "Tracking your Driver License or ID Card Order," "Where is my ID card or Driver
  License?").
- It is reached as a link from the Driver License Check menu (FLHSMV DL Check menu,
  via search index): "Driver License and ID Card Tracking System."
- Purpose: check the status of an ordered DL/ID card, including whether and when it
  was mailed. (Third-party description consistent with the tool's name and placement;
  the live tracker requires entering the DL number, so its full results screen could
  not be captured in text form — see Limitations.)
- Related FLHSMV guidance: if a renewed card has not arrived after 30 days, use the
  Driver License Check / ID Tracking System to see whether and when the card was
  mailed; if it shows mailed but was never received, request a replacement through
  the portal ($25).

## 9. Traffic School Completion Check

- A-to-Z Guide entry: "Traffic School Completion Check."
- FLHSMV tool at services.flhsmv.gov/TrafficSchoolCompletionCheck/ (URL seen in a
  tax-collector help page describing the official tool — third-party host). It is
  searchable by driver license number, certificate number, citation number, or court
  order number (per a legal-guide summary of the FLHSMV tool — third-party).
- Course providers electronically report all FLHSMV-approved school completions to
  FLHSMV; "FLHSMV does not accept paper certificates for any licensing purpose."
  (Driver Improvement Schools page, via search index)

## 10. Driver license / ID card renewal online — rules

From the FLHSMV "Renew or Replace Your Florida Driver License or ID Card" page
(via search index) and the Driver Licenses hub:

- Renew every eight years (six years if age 80+). DL holders may renew up to 18
  months before expiration; ID card holders up to 12 months before expiration.
- Online renewal is a "convenience renewal service for customers every other renewal
  period. Visit MyDMV Portal to see if you are eligible."
- Online services: renew a driver license; update the address on a DL or ID card;
  replace a lost or stolen credential.
- Replacement triggers: change of address (30 days to update the credential);
  name change (must update name with the Social Security Administration first, then
  present an original or certified court order or marriage certificate).
- Delivery: "Customers using MyDMV Portal should receive their credential in the mail
  within 2-3 weeks from the transaction." (Renew page) — see Contradiction #3: the
  FLHSMV FAQ says 7–10 business days.
- New credential design (Sept. 30, 2026): the redesigned DL/ID "will be accessible
  for online orders through MyDMVPortal.flhsmv.gov by early November" / "available
  for online renewals at MyDMV Portal by the end of November 2026." Existing valid
  credentials do not need to be replaced early.

## 11. ID card renewal online

- ID card renewal and replacement are both offered in the MyDMV Portal (DL/ID
  Renewal; Identification (ID) Card Renewal; Identification (ID) Card Replacement).
- A-to-Z Guide entry: "Identification Cards (Original, Replacement or Renewal
  Online)."
- ID cards: original, renewal and replacement are $25.00 regardless of age. Children
  ages 5–14 are eligible for an ID card, valid four years; after age 14, ID cards are
  valid eight years. (FLHSMV FAQ, via search index)
- Same identification / proof-of-legal-presence requirements as a driver license.
- ID card holders may renew 12 months in advance of expiration.

## 12. What REQUIRES an in-person visit

From the Renew or Replace page and FLHSMV's July 19, 2024 press release (identical
list in both), customers must go into an office if:

- The customer used the online convenience service on their last renewal
- The customer is not REAL ID compliant
- The customer is getting a Florida driver license or ID card for the first time
- The customer holds a commercial driver license (CDL)
- The license has the word "TEMPORARY" printed on it
- The customer wishes to update their photo
- The customer changes their name using an original or certified court order or
  marriage certificate
- The customer wishes to add or remove a designation or has a court order to update
  their credential

Other in-person triggers from FLHSMV pages:
- MyDMV Portal identity verification fails (account creation unsuccessful) → visit a
  local office.
- SSN cannot be verified by the department → follow up with the Social Security
  Administration (and, if still unresolved, in person).
- Address change online: the new address must be backed by two proofs of address
  shown at the next in-person issuance (per a tax-collector summary of the portal
  flow — third-party; FLHSMV's own rule states address changes may be done online
  or in person for U.S. citizens).
- Name changes cannot be handled online at all.

## 13. Fees (FLHSMV official fee schedule — opened directly)

From https://www.flhsmv.gov/fees/ (opened directly, crawled 2026-10-26):

Driver license fees:
- Original Class E (includes Learner's license): $48.00
- Original / Renewal Commercial Driver License: $75.00
- Renewal Class E: $48.00
- Replacement license: $25.00 (free to veterans only when adding the "Veteran"
  designation)
- Late fee: $15.00
- Endorsements: $7.00
- Knowledge retest: $10.00; Skill retest: $20.00
- Identification Cards (Original, Renewal & Replacement): $25.00
- Reinstatement: Suspensions $45.00; Revocations $75.00; D-6 Suspension $60.00;
  Disqualification $75.00; plus $130.00 administrative fee for alcohol/drug-related
  offenses where applicable
- An additional $6.25 service fee may apply to any credential issued in a tax
  collector office (veterans exempt from the $6.25 on starred transactions).

Record / publication fees (same page):
- Crash Reports: $10.00
- **Driver History Records (3-year): $8.00**
- **Driver History Records (7-year, complete or certified): $10.00**
- Exemplified record: $15.00 (per statute; listed in fee summaries)

Online surcharge:
- MyDMV Portal: $2.00 non-refundable convenience/processing fee per transaction.
  So an on-time Class E renewal online totals $50.00 ($48 + $2); at a tax collector
  it totals $54.25 ($48 + $6.25). A $25 replacement is $27.00 online.
- MyFlorida app registration renewals: $4.00 processing fee by credit card, $3.75 by
  checking account (2019 press release; may be dated).

## 14. Driving records: what each version shows (OTR-relevant)

From FLHSMV "Questions About Driving Records" (via search index — full Q&A text):

How to obtain a record:
- Review current license status free via Online Driver License Check.
- Purchase your own 3-year, 7-year, or complete driver record through the MyDMV
  Portal.
- Also available in person at any driver license service center, a clerk of court
  office that provides the service, or a private vendor; or by mail with the Driver
  License Record Request Form + fee to the Bureau of Records.
- Mail address on the FLHSMV page: Bureau of Records, 2900 Apalachee Parkway,
  MS 52, Tallahassee, Florida 32399-0575. Checks/money orders payable to the
  Division of Motorist Services. Allow ten business days for processing.
  (See Contradiction #4: other FLHSMV-adjacent material gives P.O. Box 5775,
  Tallahassee, FL 32314-5775.)

What is on the 3-year and 7-year records:
- Driver license/ID card issuances, exams passed, driver education.
- **Guilty dispositions of traffic violations only**, within 3 or 7 years of the
  disposition date.
- Crash entries when a traffic citation was issued as a direct result of the crash
  (same retention as the associated guilty disposition).
- **All** open suspensions, revocations, cancellations, disqualifications.
- Suspensions/revocations/cancellations/disqualifications cleared within 3 or 7
  years of the date the record is run (unless purged).
- D-6 suspensions (failure to comply), once cleared, remain on the record 1 year
  from reinstatement, then convert to a correspondence entry for 2 more years. Once
  converted, the D-6 entry **does not** appear on 3- or 7-year records.
- **Adjudication-withheld dispositions — including traffic school elections — do NOT
  appear on the 3-year or 7-year record.**

What is on the complete record:
- Driver license/ID card issuances, exams passed, driver education.
- **All guilty dispositions AND adjudication withheld dispositions** of traffic
  violations on the entire record, unless retention is met and the entry purged.
- Crash entries as above.
- **All** open or closed suspensions, revocations, cancellations, disqualifications.
- D-6 correspondence entries **do** appear on a complete record.
- **Correspondence entry indicating adjudication withheld–clerk of court (the
  person made school election when not eligible or made the election but did not
  complete the course).**
- Department-approved correspondence.

What "adjudication withheld" means (FLHSMV page):
- A person elected to complete a driver improvement school and provided proof of
  completion to the court in lieu of receiving points; OR
- A person elected to enter a plea of nolo contendere and provided proof of
  compliance; OR
- The judge or traffic magistrate withheld adjudication.

Election limits (FLHSMV page, current):
- Effective July 1, 2024, Florida Statute 318.14(9): **no more than five traffic
  school elections within a lifetime, and once in a 12-month period.** Florida
  violations only; the election is made through the Florida court in the county
  where the citation was issued.
- CDL holders are not eligible to elect driver improvement school to avoid points,
  regardless of vehicle.
- Citation dispositions of adjudication withheld–clerk of court (school elections)
  are retained **75 years** (up to 5 in a lifetime); compliances 75 years (up to 3
  in a lifetime). Fla. Stat. 318.14(9) and (10).
- Election mechanics (Driver Improvement Schools / BDI pages): the driver must
  voluntarily elect within **30 days** of the citation date, pay the fine and fees,
  and notify the clerk of court in the county of citation before attending the
  course. If no election is made in 30 days, the right to elect is forfeited and
  points are assessed. If the fine is not paid within 30 days, the license is
  suspended for failure to pay. The course must be completed within the
  court-required time period.
- Benefit of electing and completing BDI: points are not added, adjudication of
  guilt is withheld, and the civil penalty (fine) is reduced (18% reduction per
  statute/school guidance).

## 15. FLAG — OTR case relevance (Git-FED)

Verified against FLHSMV pages:
1. **DL Check shows traffic school eligibility — CONFIRMED.** FLHSMV's own hub page
   says DL Check reviews "driver status and driver improvement school eligibility,"
   and a captured DL Check results page carries the verbatim line "You are currently
   eligible to elect traffic school."
2. **$8 3-year vs $10 complete record — CONFIRMED on FLHSMV's own fee schedule**
   (flhsmv.gov/fees): 3-year $8.00; 7-year, complete or certified $10.00.
3. **What each shows about elections — CONFIRMED, and it is the key point:** the
   $8 3-year record shows ONLY guilty dispositions — it does NOT show
   adjudication-withheld dispositions, i.e. it does NOT show a traffic school
   election. The $10 complete record shows ALL guilty AND adjudication-withheld
   dispositions, including the clerk-of-court school-election correspondence entry,
   retained 75 years. **Anyone who buys only the $8 3-year record will not see a
   traffic school election on it; the $10 complete record is the one that shows it.**
4. **Election history lives in the portal/DL Check, not on the 3-year record.**
   Eligibility is checked free in DL Check; the full election history is on the
   complete record (or in the MyDMV Portal's Citation Inquiry / record view).

NOT verifiable from public FLHSMV pages — do not present as FLHSMV-verified:
5. **"Currently eligible with 1 election on file (ticket A0GF9RE, Palm Beach
   court)" — NOT VERIFIED.** This is a claim about Git-FED's personal DL Check /
   portal result. FLHSMV's public pages confirm the tool shows eligibility and
   confirm elections are recorded per citation/county, but no public page can show
   his election count, a ticket number, or a court. That can only be confirmed by
   logging into DL Check / MyDMV Portal with his own driver license number. Also
   note: the captured DL Check results page shows the eligibility sentence but does
   NOT show an election count or ticket numbers on the results screen — whether the
   live results page lists past elections/counts could not be established from the
   public pages read. Treat the "1 election" figure as his own portal output, not
   as an FLHSMV-published fact.
6. **Lifetime election limit contradiction — FLAGGED (see Contradiction #1).** The
   current limit (5 lifetime / once per 12 months, eff. July 1, 2024) directly
   affects how many elections Git-FED has left if he has 1 on file — but older
   FLHSMV material still says 8 lifetime, and the Palm Beach County Clerk still
   says 8. If his matter turns on the count, use the current statute (5), not the
   stale pages.

## 16. Contradictions / discrepancies flagged

1. **Lifetime traffic-school election limit: 5 vs 8.**
   - Current FLHSMV "Questions About Driving Records" and "Driver Improvement
     Schools" pages: max **five** elections in a lifetime, once in 12 months,
     effective July 1, 2024, Fla. Stat. 318.14(9).
   - Older FLHSMV BDI page (flhsmv.gov/ddl/bdis.html): drivers may not elect if
     they "have made eight elections in a lifetime."
   - Older FLHSMV FAQ: "one time within a 12-month period and no more than five
     times within a 10-year period."
   - Palm Beach County Clerk of Court traffic school page (mypalmbeachclerk.com,
     third-party): "You may not have attended traffic school more than eight times
     within your lifetime."
   - Resolution: the 5-lifetime / once-per-12-months rule is the current statute
     (July 1, 2024). The 8-lifetime and 5-in-10-years figures are stale and still
     live on FLHSMV/clerk pages. Flag for the OTR case: confirm which limit the
     court/FLHSMV is applying.
2. **Course completion deadline after election: county variation, not stated on
   FLHSMV pages.** Palm Beach Clerk: complete within 90 days of election. Lee
   County Clerk: complete within 60 days of election. FLHSMV's own pages say only
   "within the court-required time period."
3. **Credential delivery time: 2–3 weeks vs 7–10 business days.** The Renew or
   Replace page says MyDMV Portal customers "should receive their credential in
   the mail within 2-3 weeks"; the FLHSMV new-DL FAQ says "your new credential
   arrives in the mail within 7-10 business days."
4. **Bureau of Records mailing address: two versions.** FLHSMV Questions About
   Driving Records page: 2900 Apalachee Parkway, MS 52, Tallahassee, FL 32399-0575.
   Other FLHSMV-adjacent material (and the FLHSMV press/guide summaries): P.O. Box
   5775, Tallahassee, FL 32314-5775. Both are FLHSMV Bureau of Records addresses;
   use the street/MS-52 address from the FLHSMV page itself.
5. **Outdated fee figures in old statute text.** The 2003 text of Fla. Stat.
   322.20 lists $2.10 (3-year) / $3.10 (7-year) record fees. Current FLHSMV fee
   schedule is $8 / $10. Do not use the statute's 2003 dollar figures.
6. **A-to-Z Guide is a link index, not content.** The A-to-Z page lists entries
   (Driver License Check, Tracking System, etc.) but the fetched copy exposes no
   destination URLs; the destinations had to be established from the pages
   themselves and search results.
7. **"Online insurance update" scope is narrow.** FLHSMV's menu says it is for
   "your fr case" (financial responsibility case) — it is not a general insurance
   update for every driver; it is tied to FR/suspension clearance.

## 17. Limitations of this study

- Two direct page fetches returned HTTP 429 (rate limit) and were not retried:
  the "Questions About Driving Records" page and the "Renew or Replace" page.
  Their full text was instead captured from the search index of those exact FLHSMV
  URLs; the content quoted is FLHSMV's own wording, but the pages were not opened
  directly in this run.
- The live, logged-in parts of the system (MyDMV Portal account pages, DL Check
  results after entering a license number, the Tracking System results screen,
  the Traffic School Completion Check results screen) cannot be read without a
  real driver license number and login. What those screens show beyond the
  captured results-page text (e.g. whether DL Check lists an election count or
  ticket numbers) is therefore not established here.
- The MyDMV Portal "how-to" videos were not watched; only their existence on the
  portal page is recorded.

## 18. Page list — every URL studied

| # | Page | URL | How read |
|---|------|-----|----------|
| 1 | FLHSMV home | https://flhsmv.gov/ | Opened directly (press-release list only; nav links not exposed in fetch) |
| 2 | A to Z Guide | https://flhsmv.gov/a-to-z-guide/ | Opened directly, full index |
| 3 | MyDMV Portal | https://www.flhsmv.gov/motorist-modernization/mydmvportal/ | Opened directly, full page |
| 4 | Driver License Check (entry form) | https://services.flhsmv.gov/dlcheck/ | Opened directly |
| 5 | Driver License Check (portal) | https://mydmvportal.flhsmv.gov/home/en/publicweb/dlcheck/ | Via search index (menu + results-page text) |
| 6 | MyDMV Portal login / landing | https://mydmvportal.flhsmv.gov/Home/en/Account/Landing | Via search index + account-creation flyer |
| 7 | Renew or Replace Your Florida Driver License or ID Card | https://www.flhsmv.gov/ddl/replace.html | Via search index (direct open 429'd, not retried) |
| 8 | Driver Licenses & ID Cards hub | https://www.flhsmv.gov/driver-licenses-id-cards/driver-licenses/ | Via search index |
| 9 | General Information (DL & ID) | https://www.flhsmv.gov/driver-licenses-id-cards/general-information | Via search index |
| 10 | Questions About Driving Records | https://flhsmv.gov/driver-licenses-id-cards/general-information/questions-about-driving-records/ | Via search index (direct open 429'd, not retried) |
| 11 | Fees | https://www.flhsmv.gov/fees/ | Opened directly, full schedule |
| 12 | Frequently Asked Questions (What to Bring) | https://www.flhsmv.gov/driver-licenses-id-cards/what-to-bring/frequently-asked-questions/ | Via search index |
| 13 | Driver Improvement Schools | http://flhsmv.gov/driver-licenses-id-cards/education-courses/driver-improvement-schools/ | Via search index |
| 14 | Basic Driver Improvement (BDI) FAQ | http://www.flhsmv.gov/ddl/bdis.html | Via search index |
| 15 | Florida DHSMV Menu of Common Online Services | https://www11.flhsmv.gov/ | Via search index |
| 16 | Contact Us | https://www.flhsmv.gov/contact-us/ | Via search index |
| 17 | Florida's NEW Driver License and ID Card | https://www.flhsmv.gov/driver-licenses-id-cards/newdl/ | Via search index |
| 18 | New DL FAQ | https://flhsmv.gov/driver-licenses-id-cards/newdl/faq/ | Via search index |
| 19 | FLHSMV Urges Customers to Use Official Resources (press release, Mar 6, 2019) | https://www.flhsmv.gov/2019/03/06/FLHSMV-urges-customers-to-use-official-resources-for-driver-license-and-motor-vehicle-services/ | Via search index |
| 20 | DL number-change legislation (press release, Jul 19, 2024) | http://www.flhsmv.gov/2024/07/19/flhsmv-implements-legislation-requiring-driver-licenses-and-identification-card-numbers-to-change/ | Via search index |
| 21 | GoRenew / Virtual Office lobby | https://services.flhsmv.gov/virtualoffice/Lobby.aspx | Via search index |
| 22 | Traffic School Completion Check | https://services.flhsmv.gov/trafficschoolcompletioncheck/studentSearchPage.aspx | Via third-party reference to the official tool |
| 23 | Captured DL Check results page (TownNews PDF of the live tool output) | https://bloximages.chicago2.vip.townnews.com/lagniappemobile.com/content/tncms/assets/v3/editorial/3/b4/3b4b4c83-0ebb-43c2-87fb-a9db61573827/6a1a00f947d6b.pdf.pdf | Via search index |

Third-party pages consulted only to corroborate FLHSMV facts (not FLHSMV sources):
Palm Beach County Clerk traffic school page (mypalmbeachclerk.com); Lee County
Clerk traffic FAQ (leeclerk.org); Manatee County Tax Collector help center
(taxcollector.com / zendesk); LEETC MyDMV Portal pages and account-creation flyer
(leetc.com); LegalClarity driving-record guides; DMV USA Florida status page;
Tickettoro / dmvfloridaappointment / dmvappointmentflorida driving-record guides.
# FLHSMV Study — Section 14: Forms, Handbooks & Manuals

Source: Florida Department of Highway Safety and Motor Vehicles (FLHSMV), flhsmv.gov.
All facts below come only from FLHSMV pages read directly (via browser.open) or from
FLHSMV page text returned by web search. Nothing is taken from third-party DMV sites.
Study date: 23 November 2026. Page crawl dates as shown by the browser tool are noted
where available.

## 1. How FLHSMV organises forms, handbooks and manuals

- There are two central hub pages under **Resources**:
  - **Forms** — https://www.flhsmv.gov/resources/forms/
  - **Handbooks & Manuals** — https://www.flhsmv.gov/resources/handbooks-manuals/
- The **A to Z Guide** (https://flhsmv.gov/a-to-z-guide/) is the site-wide index for
  this section. Its relevant entries are: CDL Handbook; Dealer Handbook; DMV Procedures
  Manual; Driver Handbook; Florida Dealer Handbook; Florida Driver Handbooks; Forms;
  Handbook for Florida Drivers; IFTA Manual; IRP Manual; Motorcycle Handbook;
  Publications (Handbooks & Manuals); Publications (Driver and Vehicle Reports);
  Publications (Crash and Citation Reports); Publications (Cabinet & Legislature Reports).
- The Forms page is **sorted by form number**. Forms marked with an asterisk (\*)
  "may be filled out online and then printed."
- Form numbers are grouped by series (see §4). The main Forms page covers driver
  licence, motor vehicle / vessel title and registration, licence plate, dealer,
  manufacturer, and IRP/IFTA forms in one list.
- IRP and IFTA have their own separate "Forms, User Guides, & Tutorials" pages
  (see §3.5), and dealers have a separate "Forms and Resources" page (see §3.4).
- Handbooks are free: FLHSMV's General Information page states driver licence
  handbooks, motorcycle handbooks and commercial driver licence handbooks "are
  available at local driver license service centers. There is no charge for handbooks
  and they may be returned for re-use. To download a digital copy, visit our
  Handbooks and Manuals page."

## 2. Handbooks & Manuals — the hub page

URL: https://www.flhsmv.gov/resources/handbooks-manuals/
(Page crawled 2026-11-01.)

The page lists exactly four publications under "Resources":

| Publication | Versions / sub-items listed on the page |
|---|---|
| **Florida Driver's Handbook** | English (with "Study Guide Answer Locations"); Español; Kreol |
| **Florida CDL Handbook** | English (with "Supplement For Modernized Version"); Spanish |
| **Florida Motorcycle Operator Handbook** | (single item, no language variants listed) |
| **Motor Vehicle Procedures Manual** | (single item; this is the DMV Procedures Manual — see §3.3) |

The same page also carries a "What to take with you to the Driver License Office"
checklist: proof of identification (birth certificate or US Passport; a certified
copy is acceptable if the original is unavailable); proof of Social Security number
(original Social Security card or W-2); two proofs of residential address (e.g. home
utility, cable or home telephone bill); proof of name change if applicable (marriage,
divorce or court order); Parent/Guardian On-line Test Proctoring Form, signed in the
presence of a driver licence examiner or notarised if the parent/guardian will not be
present; Parental Consent Form – Minor Driver Applicant Form (if under 18 and not
married, one parent or legal guardian must sign; step-parents may not sign unless
they have legally adopted the applicant). It also states: "No additional certificates
needed! Once you complete a Traffic Law and Substance Abuse Education course through
a registered provider your completion information is automatically submitted to our
department… Paper certificates are no longer required at the driver license office."

### 2.1 Florida Driver's Handbook (Official Florida Driver License Handbook)

- The study guide for the Class E knowledge exam. FLHSMV's General Information
  page states the Knowledge Exam is "50 multiple choice questions about traffic laws
  and traffic signs. To prepare, review the Florida Driver License Handbook."
  Class E knowledge examinations are available in Arabic, Chinese, English, Haitian
  Creole, Russian and Spanish (per the General Information page).
- Available in English, Spanish (Español) and Haitian Creole (Kreol) on the
  Handbooks & Manuals page, plus a "Study Guide Answer Locations" document under
  the English version.
- A FLHSMV press release (19 Oct 2020) describes the department's podcast
  *3PointTurn* as "designed to supplement the Florida Driver Handbook" — 12 episodes
  with Florida Highway Patrol members discussing topics from personal responsibility
  to situations on Florida roadways — and advises: "For safe driving tips and
  techniques, download the official Florida Driver License Handbook."
- The A to Z Guide lists it three ways: "Driver Handbook", "Florida Driver
  Handbooks" and "Handbook for Florida Drivers" — all pointing to the same handbook.

### 2.2 Florida CDL Handbook

- The study manual for the Commercial Driver License. Listed in English (with a
  "Supplement For Modernized Version") and Spanish.
- FLHSMV's General Information page warns: "Customers applying for a commercial
  driver license should consider that the commercial driver license is a professional
  license with more testing requirements than other licenses. If you wish to apply
  for a commercial driver license, please obtain a study manual before testing."
  and "For more information on commercial driver licenses, please refer to the
  department's handbook."

### 2.3 Florida Motorcycle Operator Handbook

- Listed on the Handbooks & Manuals page as "Florida Motorcycle Operator Handbook"
  (the A to Z Guide calls it "Motorcycle Handbook"; the Safety Center calls it the
  "Florida Motorcycle Handbook").
- FLHSMV's Motorcycle Rider Education & Endorsements page: "The motorcycle
  operator's manual contains valuable information for both beginner and experienced
  motorcyclists on techniques to operate a motorcycle safely." A motorcycle
  endorsement (or a "Motorcycle Only" licence) is required to operate any two- or
  three-wheel motorcycle with an engine over 50 cc.
- FLHSMV's Motorcycle Safety Awareness page: "Learn more about motorcycle rules
  and responsibilities by downloading the Florida Motorcycle Handbook."

### 2.4 Motor Vehicle Procedures Manual (DMV Procedures Manual)

- Listed on the Handbooks & Manuals page as "Motor Vehicle Procedures Manual";
  the A to Z Guide calls it "DMV Procedures Manual".
- Its own landing page: https://flhsmv.gov/motor-vehicles-tags-titles/motor-vehicle-procedure-manual/
  (confirmed to exist via search; the page itself could not be re-opened in this
  session because the browser tool returned HTTP 429 rate-limit errors — see §6.)
- It is a set of numbered procedures for tax-collector, licence-plate-agent and
  FLHSMV staff, organised in series. The series codes attested on FLHSMV pages
  and in FLHSMV procedure PDFs are:
  - **TL — Title and Lien** (e.g. TL-01 identification/signature requirements;
    TL-02 power of attorney; TL-05 duplicate and lost-in-transit certificates of
    title; TL-08 sales and use tax; TL-10 original title; TL-11 transfer of title).
    TL-05 (rev. 08/25) states its purpose: "to assist employees of the tax
    collector, license plate agent, and Florida Highway Safety and Motor Vehicles
    (FLHSMV) in processing applications for duplicate and lost in transit
    certificates of title," under Section 319.29(1), Florida Statutes.
  - **RS — Registration** (e.g. RS-01 Overview of Motor Vehicle Registration
    Requirements and Documents, rev. 12/25, 58 pages, under Chapter 320, Florida
    Statutes; its stated purpose is "to assist employees of the tax collector,
    license plate agent, and the Florida Department of Highway Safety and Motor
    Vehicles (FLHSMV) in issuing and renewing license plates." RS-01 cross-references
    RS-08, RS-12, RS-13, RS-14, RS-15, RS-16, RS-17, RS-19, RS-21, RS-22, RS-23,
    RS-25, RS-26, RS-27, RS-28, RS-29 and RS-32.)
  - **VSTL — Vessel Titles** and **VSRS — Vessel Registrations** (e.g. VSTL-01
    signature requirements/identity affidavits, merged with TL-01; VSTL-05 duplicate
    and lost-in-transit certificates of title, merged with TL-05; VSTL-06 vessel
    titling exemptions; VSTL-09 homemade vessel titling requirements; VSTL-20
    transfer of certificate of title involving guardianship, under Chapter 744,
    Florida Statutes; VSTL-25/VSTL-28/VSTL-29, rev. 03/2026 and 7/2024).
  - **TA — Technical Advisory** (named as a series in dealer-training material
    citing the DMV Procedure Manual).
- The Procedures Manual landing page tabulates, for each procedure, the procedure
  name, procedure number and revision date (e.g. VSTL-01, 11/03/22; VSTL-04,
  01/05/24; VSTL-09, 9/16/2024; VSTL-17, 03/2026). Many vessel procedures are
  marked "(merged with TL-xx)".

### 2.5 Florida Dealer Handbook (Florida Motor Vehicle, Mobile Home and Recreational Vehicle Dealers' Handbook)

- Listed in the A to Z Guide as both "Dealer Handbook" and "Florida Dealer Handbook".
- Full title attested in the handbook itself: *Florida Motor Vehicle, Mobile Home
  and Recreational Vehicle Dealers' Handbook*, issued by the Department of Highway
  Safety and Motor Vehicles, Division of Motorist Services.
- Stated purpose (from the handbook's introduction): "to assist potential
  applicants, as well as, those licensed as motor vehicle, mobile home and
  recreational vehicle dealers, manufacturers, importers and distributors in
  understanding dealer licensing requirements and processes," and as "a reference
  guide to focus on manufacturer, importer, distributor and dealer operational
  obligations, responsibilities and the requirements set forth in Chapters 317, 319,
  and 320, Florida Statutes, Florida Administrative Code, and procedures of the
  Department of Highway Safety and Motor Vehicles, Division of Motorist Services,
  and other state agencies." It is issued by the Bureau of Dealer Services,
  Division of Motorist Services.
- The FLHSMV dealer "Forms and Resources" page lists "Dealer Handbook" as a
  resource alongside dealer forms (see §3.4). A dealer-services reference cited the
  handbook PDF at https://www.flhsmv.gov/pdf/dealerservices/dealerhandbook.pdf —
  that URL was seen only in a third-party (tax collector) document, not on an
  FLHSMV page opened in this session, so it is recorded here as unverified.

### 2.6 IFTA and IRP manuals

- **IFTA Trucking Manual — Form 85920.** Listed on the main Forms page and on
  the IFTA "Forms, User Guides, & Tutorials" page.
- **How to Calculate the IFTA Tax Return — Form 85800.** Listed on the main
  Forms page and on the IFTA page.
- **IRP Trucking Manual — Form 85500.** Listed on the main Forms page and on
  the IRP "Forms, User Guides, & Tutorials" page.
- The A to Z Guide lists "IFTA Manual" and "IRP Manual" as separate entries.
- A Florida DOT trucking FAQ confirms the same numbers: "You may also access the
  IRP TRUCKING MANUAL (Form HSMV 85500) at www.flhsmv.gov" and "the IFTA TRUCKING
  MANUAL (Form HSMV 85920) at www.flhsmv.gov."
- The IRP and IFTA pages also list user guides and video tutorials (see §3.5).

## 3. Forms — where to find them and what they are

### 3.1 Main Forms page

URL: https://www.flhsmv.gov/resources/forms/ (page crawled 2026-11-02).
Complete list as read, sorted by form number; "\*" = fillable online, then print.
Spanish variants carry an "SP" suffix. The full list is reproduced in §4.

How to download: each form number on the page links to its PDF (HSMV form).
Forms marked \* may be filled out online and then printed. The page itself gives
no per-form purpose text — purposes below are taken from the form titles and,
where stated, from the dedicated FLHSMV pages cited.

### 3.2 Key driver-licence forms (71xxx–78xxx series)

- **71048** Commercial Driver License Form.
- **71054** Certification for Waiver of Skill Test for Military Personnel.
- **71061** Military Insurance Affidavit.
- **71120 / 71120SP** Certification of Address (Spanish: Certificación de Dirección).
- **71141** Driver's License Hazardous Materials Endorsement Application.
- **71142 / 71142SP** Parent Consent Form (Under 18 – Learner's License)\* — required
  for a minor to obtain a learner's licence (Required Forms for Teens page).
  **71142C** Non-Parent or Non-Legal Guardian Consent Form (Under 18 – Learner's
  License)\*.
- **71143 / 71143SP** Parent Consent Form (Under 18 – Driving Test)\* — the
  Certification of Minor Driving Experience Form; certifies the minor has at least
  50 hours of driving experience, 10 at night (Required Forms for Teens page).
- **71144 / 71144SP** Parent Proctoring Form — Parent/Guardian On-line Test
  Proctoring Form; required if the minor completed the Class E Knowledge Exam
  online through a third-party administrator (Required Forms for Teens page).
- **72010** Report of Eye Exam\* — used when the driver has not met minimum
  Florida vision standards, or is eligible to renew by mail but must prove vision
  standards are met (Forms for Older Drivers page).
- **72034** Request for Eligibility Review.
- **72068** Identity Theft/Driver License Fraud Report Form\*.
- **72077** Release From Incarceration Form\*.
- **72111** Prism Form.
- **72119** Mature Driver Vision Test — drivers over 80 must submit this vision
  examination form when renewing (Forms for Older Drivers page).
- **72120** Application For Driver License Developmental Disability Designation
  and/or Motor Vehicle Registration Safe Designation.
- **72190 / 72190SP** Report a Driver Whose Ability is Questionable — "Use this
  form to report a driver whose ability is questionable" (Forms for Older Drivers
  page; also listed in the A to Z Guide via Disabled Parking Abuse Complaint Form
  entries).
- **72201** FRTP Rules of Professional Conduct\* (Florida Rider Training Program).
- **72360** Medical Release Form. **72423** Medical Report. **72480** Alcohol and
  Drug Usage Form. **72481** Mental Status Examination Form. **72997** Medical
  Advisory Board Recommendation Form.
- **72862 / 72862SP** Worthless Check Clearance. **72870 / 72871** Student
  Notification for Driving Eligibility for Licensure / for Home Education Program
  (Spanish versions 72835SP / 72836).
- **73209** Criminal Justice Information Request form\*.
- **73644 / 73644SP** Driver License Refund Request\*.
- **74007** Security Deposit Refund Request. **74010** Court Authority to Reinstate
  (failure to meet financial obligations suspension). **74014 / 74014SP** Release in
  Full of All Claims\*. **74034 / 74034SP** Judgment Consent Form\*. **74036 /
  74036SP** Agreement for Release and Monthly Repayment Note\*. **74038 / 74038SP**
  Satisfaction of Judgment\*. **74039** Authorization to Pay Security\*.
- **75710** Red Light Camera. **75720** Request for Local Hearing Form – School
  Zone Speeding Violations. **75730** Request for Local Hearing Form – School Bus
  Camera Violations. **75954** Florida Uniform Traffic Citation Transmittal Form\*.
- **77035** Application for Licensure to Conduct a Driving Under the Influence
  (DUI) Program. **77054** Driving Under the Influence Programs Complaint form.
- **77058** RiderCoach Apprentice Program Application (RCAP)\*. **77066** Ignition
  Interlock Medical Evaluation Form. **77067** Application For Authority to Conduct
  Third Party Driver License Testing.
- **77071S** Vehicle Registration Application for Commercial Driving School\*.
  **77072S** Commercial Driving School Student Contract. **77073S** Application for
  an Instructor or Agent Certificate for Commercial Driving School\*. **77074S**
  License Application for Commercial Driving School.
- **77078** RiderCoach Intern Form\*. **77079** RiderCoach Mentor Form\*.
  **77122** RiderCoach Personal Information & Qualifications\*.
- **78015** Worthless Check Hardship Hearing Form. **78065** Application for
  Formal or Informal review of Driver License. **78306** Application for Hardship
  or Administrative Hearing.

### 3.3 Key motor-vehicle / vessel forms (80xxx–83xxx series)

Most-used title and registration forms:

- **82040 MV / 82040 MH / 82040 VS** Application for Certificate of Motor Vehicle
  Title / Mobile Home Title / Vessel Title (one form number, three versions).
- **82042** Vehicle Identification Number and Odometer Verification\*.
- **82050** Notice of Sale and/or Bill of Sale for a Motor Vehicle, Mobile Home,
  Off-Highway Vehicle or Vessel\*.
- **82053** Power of Attorney\*.
- **82101** Application for Duplicate or Lost in Transit/Reassignment Title for a
  Motor Vehicle, Mobile Home or Vessel Title Certificate\* (the form TL-05 requires
  for duplicate titles).
- **82152** Application for Surviving Spouse Transfer of Title\*.
- **82260** Lien Satisfaction\*.
- **82363** Application for Salvage Title/Certificate of Destruction\*.
- **82002** Initial Registration Fee Exemption Affidavit\*. **82012** Application
  for Certificate of Destruction\*. **82026** Application For Bonded Title
  Affidavit\*. **82033** Title Surety Bond for a Motor Vehicle\*. **82039**
  Application for Multiple Certificate of Titles With/Without Registration\*.
- **83039** Disabled Parking Placard\*. **83040** Application for Expectant Mother
  Parking Permit\*. **83043** Personalized License Plate\*. **83045** Application
  for Registration of a Street Rod, Custom Vehicle, Horseless Carriage or Antique
  (Permanent)\*. **83046** (listed as 83146) Application for Replacement license
  plate, validation decal or parking permit\*. **83101** Missing License Plate,
  Decal or Placard Affidavit\*. **83330** Florida Insurance Affidavit\*.
  **83363** Application for License Plate or Decal Refund\*. **83390** Application
  for Sunscreening Medical Exemption\*.
- **83416** Request for Division of Motor Vehicle/Vessel Forms\* — the form used
  to request DMV forms themselves.
- Mobile/manufactured home forms: **80122** Application for Suspected or Reported
  Title and Registration Fraud\*; **81032** Application for Florida Certification
  of Mobile/Manufactured Home Installation Component or Product\*; **81095**
  MH/RV Complaint Registration Form; **81401** Manufactured/Mobile Home Installer
  License Application\*; **81402** Installer Performance Bond; **81404** Mobile Home
  Installation Decal Order Form\*; **81406** Application/Affidavit for Duplicate
  Mobile Home Installer License; **81407** Affidavit for Replacement of Lost Mobile
  Home Installer Decals.

### 3.4 Dealer / manufacturer forms (84xxx–86xxx series) and the dealer Forms and Resources page

- Dealer "Forms and Resources" page:
  https://www.flhsmv.gov/motor-vehicles-tags-titles/dealers-installers-manufacturers-distributors-importers/mv-rv-mh-dealer-broker-licenses/forms-and-resources/
  It lists: HSMV **86056** Application for a license as a motor vehicle, mobile
  home or recreational vehicle dealer (with instruction booklet); HSMV **86072**
  Modification to dealer license; HSMV **86720** Renewal application for motor
  vehicle, mobile home, or recreational vehicle dealers; the Dealer Handbook;
  FLHSMV regional offices; and FLHSMV-approved dealer training schools offering
  pre-licensing classes and continuing education for independent motor vehicle
  dealers.
- Main Forms page, dealer series: **84003** Receipt and Certificate of Disposal
  for Obsolete License Plates; **84013** Vehicle Purchase Record\*; **84014**
  Vehicle Sales Record\*; **84016** Temporary Tag Record\*; **84019** Application
  and Claim To Recover Compensation from the Mobile Home and Recreational Vehicle
  Trust Fund\*; **84026** Assignment of Claim/Suit\*; **84045** Registration of
  Mobile Home Dealer's Salesperson(s)\*; **84050** Application for Dealer License
  Reprint\*; **84058** Vehicle Air Pollution Control Statement\*; **84061**
  Declaration Affidavit For A Motor Vehicle Which Will Be Titled and Registered In
  Another State or Country\*; **84200** Application for A Temporary "Supplemental"
  License for An Off-Premises Sale by A Motor Vehicle, Mobile Home or Recreational
  Vehicle Dealer\*; **84256** Application for a License as a Motor Vehicle or
  Recreational Vehicle Manufacturer, Importer, or Distributor or a Mobile Home
  Manufacturer\*; **84490 / 84491** Statement of Builder (+ Additional Sheet)\*;
  **84901** Complaint Affidavit\*.
- **86009** Application for Temporary Exemption. **86018 / 86019 / 86020** Surety
  Bonds for Mobile Home Dealer / Recreational Vehicle Dealer / Motor Vehicle
  Dealer\*. **86029** Application for Reciprocal Inspection Exemption. **86050 /
  86051** Surety Bonds for Mobile Home Manufacturer / Recreational Vehicle
  Manufacturer or Van Converter\*. **86056** Application for License as a Motor
  Vehicle, Mobile Home, or Recreational Vehicle Dealer\*. **86057 / 86058 / 86059**
  Irrevocable Letters of Credit (Motor Vehicle Dealer / Mobile Home Dealer /
  Mobile Home Manufacturer)\*. **86060** Statement of Intent to Relinquish a Dealer
  License\*. **86072** Modification to Dealer License for Licensed Motor Vehicle,
  Mobile Home, or Recreational Vehicle Dealers\*. **86218** Renewal Application:
  Mobile Home Manufacturer or Recreational Vehicle Manufacturer, Importer, or
  Distributor\*. **86219** Renewal Application: Motor Vehicle Manufacturer,
  Importer, or Distributor\*. **86720** Renewal Application Motor Vehicle, Mobile
  Home, or Recreational Vehicle Dealers\*.

### 3.5 IRP / IFTA forms, manuals, guides and tutorials (85xxx series)

Two dedicated pages, both titled "Forms, User Guides, & Tutorials":

- IFTA:
  https://www.flhsmv.gov/driver-licenses-id-cards/commercial-motor-vehicle-drivers/international-fuel-tax-agreement/forms-and-manuals/
  (page crawled 2026-01-15)
- IRP:
  https://www.flhsmv.gov/driver-licenses-id-cards/commercial-motor-vehicle-drivers/international-registration-plan/forms-and-manuals/
  (page crawled 2026-01-11)

Shared rules stated on both pages: "If choosing to use paper forms: IRP/IFTA
forms may be completed electronically (PDF fillable). However, they cannot be
saved online. After entering the required information, be sure to print before
exiting, and then sign. Blank forms may also be printed for completion by hand."
"Some forms must be signed by the actual carrier (account holder) and in some
cases, require notarization." "Customers can upload forms into the Interstate
Carrier Filing System (ICFS) with the exception of notarized forms. Notarized
originals must be submitted to the Bureau of Commercial Vehicle and Driver
Services at the address indicated on the document." IRP/IFTA Customer Service
Center: weekdays (850) 617-3711, 8:00 AM–4:30 PM EST.

IFTA Forms & Manuals: **85008** IFTA License Application (Form)\*; **85010** IFTA
Decal Re-order Form; **85800** How to Calculate the IFTA Tax Return (Manual);
**85920** IFTA Trucking (Manual); **85921** IFTA Tax Return and Schedule 1\*.
IRP Forms & Manuals: **85900** IRP Application (Form); **85100** Replace Plate,
Cab Card, or Correct DOT Number (Form)\*; **85500** IRP Trucking (Manual).
Forms usable for both IRP and IFTA: **85017** Record Keeping Agreement (Form)\*;
**85041** Change of Address (Form)\*; **96440** IRP/IFTA Power of Attorney and
Instructions. Also listed on the main Forms page: **85057** IRP Lease Agreement
Information Form\*.
Guides and tutorials on both pages: IFTA User Guide; IRP User Guide; Enterprise
User Guide; E-File Quick Reference Guide Index (IFTA page); ICFS video tutorials —
IFTA Quarterly Tax Return, IRP Fleet Renewal Part 1, IRP Fleet Renewal Part 2.
The IRP page notes webinars: "Check back with us for upcoming webinars on IRP &
IFTA transactions."

### 3.6 Other specialised form collections on flhsmv.gov

- **Required Forms for Teens**:
  https://www.flhsmv.gov/driver-licenses-id-cards/licensing-requirements-teens-graduated-driver-license-laws-driving-curfews/required-forms-teens/
  — 71144 (online test proctoring), 71142 (parental consent, learner's licence),
  71143 (certification of minor driving experience, driver licence). See §3.2.
- **Forms for Older Drivers**:
  http://www.flhsmv.gov/driver-licenses-id-cards/florida-granddriver/forms-for-older-drivers/
  — 72190 (report a driver whose ability is questionable), 72119 (mature driver
  vision test, over-80 renewal), 72010 (report of eye exam). See §3.2.
- **Disabled parking abuse / handicap parking complaint forms**: the A to Z Guide
  lists "Disabled Parking Abuse Complaint Form", "Handicap Parking Abuse Complaint
  Form" and "Parking Permit Complaint Form" as entries (these point to complaint
  forms; the main Forms list carries the related 83007/83039 placard and plate
  applications).
- **Publications (reports)**: the A to Z Guide's "Publications" entries point to
  the Resource Center reports pages, not to forms — Driver and Vehicle Reports &
  Statistics (https://www.flhsmv.gov/resource-center/driver-and-vehicle-reports/),
  Cabinet and Legislature Reports & Statistics
  (https://www.flhsmv.gov/resourcecenter/cabinet-and-legislature-reports/), and
  Documents & Publications / Inspector General audit reports
  (http://flhsmv.gov/resources/open-government/office-of-inspector-general/documents-publications/).
  These are statistical/audit publications, not handbooks or blank forms, and are
  outside this section's core scope; noted here only because the A to Z Guide
  groups them under "Publications".

## 4. Complete Forms list (main Forms page, as read 23 Nov 2026)

Sorted by form number. "\*" = may be filled out online and then printed.
Spanish variants are indented under the English form.

**71xxx — Driver licence (general, military, minors, medical):**
71048 Commercial Driver License Form; 71054 Certification for Waiver of Skill
Test for Military Personnel; 71061 Military Insurance Affidavit; 71120
Certification of Address; 71120SP Certificación de Dirección; 71141 Driver's
License Hazardous Materials Endorsement Application; 71142\* Parent Consent Form
(Under 18 – Learner's License); 71142C\* Non-Parent or Non-Legal Guardian Consent
Form (Under 18 – Learner's License); 71142SP Formulario A de Consentimiento
Paterno (Bajo 18 años – Licencia de Aprendiz); 71143\* Parent Consent Form (Under
18 – Driving Test); 71143SP Formulario B de Consentimiento Paterno (Bajo 18 años –
Examen Práctico); 71144 Parent Proctoring Form; 71144SP Supervisión del Padre de
la Prueba en Línea del CARNET de Conducir de un Menor de Edad.

**72xxx — Medical, vision, fraud, hearings:**
72010\* Report of Eye Exam; 72034 Request for Eligibility Review; 72068\*
Identity Theft/Driver License Fraud Report Form; 72077\* Release From Incarceration
Form; 72111 Prism Form; 72119 Mature Driver Vision Test; 72120 Application For
Driver License Developmental Disability Designation and/or Motor Vehicle
Registration Safe Designation; 72190 Report a Driver Whose Ability is
Questionable; 72190SP Denuncie a un Conductor Cuya Habilidad es Cuestionable;
72201\* FRTP Rules of Professional Conduct; 72360 Medical Release Form; 72423
Medical Report; 72480 Alcohol and Drug Usage Form; 72481 Mental Status
Examination Form; 72835SP Notificación a Estudiante sobre Elegibilidad para
Conducir para Licenciarse; 72836 Notificación a Estudiante para Programa de
Educación en el Hogar; 72862 Worthless Check Clearance; 72862SP Compensación o
Pago de Cheques Sin Fondos; 72870 Student Notification for Driving Eligibility for
Licensure; 72871 Student Notification for Home Education Program; 72997 Medical
Advisory Board Recommendation Form.

**73xxx–78xxx — Records, financial responsibility, citations, DUI, schools, hearings:**
73209\* Criminal Justice Information Request form; 73644\* Driver License Refund
Request; 73644SP Solicitud de Reembolso en Cartera de Conducir; 74007 Security
Deposit Refund Request; 74010 Court Authority to Reinstate (Failure to meet
financial obligations suspension); 74014\* Release in Full of All Claims; 74014SP\*
Formulario para la Exoneración de Daños a la Propiedad/Lesiones; 74034 Judgment
Consent Form; 74034SP\* Formulario de Consentimiento de la Demanda; 74036\*
Agreement for Release and Monthly Repayment Note; 74036SP\* Acuerdo de
Exoneración Y Nota de Pagos Mensuales; 74038\* Satisfaction of Judgment; 74038SP\*
Formulario Para la Satisfaccion de la Demanda; 74039\* Authorization to Pay
Security; 75710 Red Light Camera; 75720 Request for Local Hearing Form – School
Zone Speeding Violations; 75730 Request for Local Hearing Form – School Bus Camera
Violations; 75954\* Florida Uniform Traffic Citation Transmittal Form; 77035
Application for Licensure to Conduct a Driving Under the Influence (DUI) Program;
77054 Driving Under the Influence Programs Complaint form; 77058\* RiderCoach
Apprentice Program Application (RCAP); 77066 Ignition Interlock Medical Evaluation
Form; 77067 Application For Authority to Conduct Third Party Driver License
Testing; 77071S\* Vehicle Registration Application for Commercial Driving School;
77072S Commercial Driving School Student Contract; 77073S\* Application for an
Instructor or Agent Certificate for Commercial Driving School; 77074S License
Application for Commercial Driving School; 77078\* RiderCoach Intern Form; 77079\*
RiderCoach Mentor Form; 77122\* RiderCoach Personal Information & Qualifications;
78015 Worthless Check Hardship Hearing Form; 78065 Application for Formal or
Informal review of Driver License; 78306 Application for Hardship or Administrative
Hearing.

**80xxx–82xxx — Fraud, mobile homes, titles:**
80122\* Application for Suspected or Reported Title and Registration Fraud; 81027\*
Assignment of Judgment; 81032\* Application for Florida Certification of
Mobile/Manufactured Home Installation Component or Product; 81095 MH/RV Complaint
Registration Form; 81401\* Manufactured/Mobile Home Installer License Application;
81402 Installer Performance Bond; 81404\* Mobile Home Installation Decal Order
Form; 81406 Application/Affidavit for Duplicate Mobile Home Installer License;
81407 Affidavit for Replacement of Lost Mobile Home Installer Decals; 82002\*
Initial Registration Fee Exemption Affidavit; 82012\* Application for Certificate
of Destruction; 82013 Certificate of Destruction (Sample only — do not fill out);
82026\* Application For Bonded Title Affidavit; 82033\* Title Surety Bond for a
Motor Vehicle; 82039\* Application for Multiple Certificate of Titles With/Without
Registration; 82040 MV Application for Certificate of Motor Vehicle Title; 82040 MH
Application for Certificate of Mobile Home Title; 82040 VS Application for
Certificate of Vessel Title (plus a linked Hope Scholarship Program Contribution
Election – Florida Department of Revenue form); 82042\* Vehicle Identification
Number and Odometer Verification; 82048\* Vehicle Identification Number and
Repossession Notice to Subsequent Lienholder; 82050\* Notice of Sale and/or Bill of
Sale for a Motor Vehicle, Mobile Home, Off-Highway Vehicle or Vessel; 82052
Electronic Signature Agreement; 82053\* Power of Attorney; 82054\* Application for
Original or Replacement Title Validation Sticker for an Off Highway Vehicle; 82078\*
Notification of Dispute of Registration Fees Paid to a Dealer for a Motor Vehicle;
82082\* Off-line Issuance of a Pre-printed Temporary License Plate; 82083\*
Application to Become an Authorized EFS Agent/Change of Certified Service
Provider; 82084\* Dealer Plates for Heavy Trucks for Demonstration Purposes; 82089\*
Insurance Company Motor Vehicle or Vessel Release Statement; 82090 Insurance
Company Motor Vehicle Statement of Fact; 82091\* Reassignment Supplement to a
Certificate of Title; 82092\* Reassignment Document for an Electronic Certificate
of Title; 82100\* Affidavit for Change/Alteration of Body; 82101\* Application for
Duplicate or Lost in Transit/Reassignment Title for a Motor Vehicle, Mobile Home
or Vessel Title Certificate; 82103\* Affidavit for Change of Motor (MV manufactured
prior to 1955); 82105 Certified Official Weight Affidavit; 82109\* Application for
Retirement of a Mobile Home Certificate of Title; 82137\* Application for Derelict
Motor Vehicle Certificate and Request to Cancel Title; 82139\* Application for
Notice of Lien/Reassignment of Lien or Notice to First Lienholder of Subsequent
Lien; 82150\* Application and Notice of Interest – Electronic Lien and Title
Process; 82152\* Application for Surviving Spouse Transfer of Title; 82161
Application for Judgment Lien on Motor Vehicle or Vessel; 82175\* Dealer
Non-Delivery Affidavit; 82191 Notice Or Discharge Of Repossession Recovery
Attempt; 82192\* Notice to Surrender Motor Vehicle/Vessel; 82195\* Dealer Request
for Registration Stop; 82260\* Lien Satisfaction; 82363\* Application for Salvage
Title/Certificate of Destruction; 82498\* Application for Notification of Dispute
on a Wrecker Operator's Lien for a Motor Vehicle, Mobile Home or Vessel; 82993\*
Application for Separate Odometer Disclosure Statement and Acknowledgment; 82994
Application for Motor Vehicle Dealer Title Reassignment Supplement (Sample only —
do not fill out); 82995 Application for Motor Vehicle Power of Attorney/Odometer
Disclosure (Sample only — do not fill out); 82996\* Application for Motor Vehicle
Dealer/Auto Auction or Customer Odometer Affidavit; 82997 Application for
Authorization as a Private Rebuilt Motor Vehicle Inspection Facility.

**83xxx — Licence plates, decals, permits, refunds:**
83000\* Sample License Plate Request Form; 83007\* Application for A Disabled,
Disabled Veteran or Motorcycle International Wheelchair Symbol License Plate;
83016 Tax Collectors Mailing List; 83020\* Application for Front End License
Plates; 83030\* Application for U.S. Reserve or Florida National Guard License
Plate; 83034\* Application for Ex-Prisoner of War, Purple Heart, Medal of Honor,
Pearl Harbor Survivor, US Paratrooper, Operation Iraqi Freedom, Operation Enduring
Freedom, Gold Star, Veteran of the United States Armed Forces, Combat Infantry
Badge, Combat Action Badge, Combat Medical Badge, Vietnam War Veteran, Korean War
Veteran, Silver Star, Distinguished Service Cross, Navy Cross, Air Force Cross,
Operation Desert Shield Veteran, Operation Desert Storm Veteran, Combat Action
Ribbon, Distinguished Flying Cross, Woman Veteran, Air Force Combat Action Medal,
Navy Submariner, World War II Veteran; 83036\* Notice of Reassignment of Permanent
Florida Governmental Agency License Plate; 83039\* Disabled Parking Placard; 83040\*
Application for Expectant Mother Parking Permit; 83041\* Application for Amateur
Radio License Plate; 83043\* Personalized License Plate; 83045\* Application for
Registration of a Street Rod, Custom Vehicle, Horseless Carriage or Antique
(Permanent); 83060\* Registration of Vehicle with Out-Of-State Lien; 83065\*
Application for Transporter License Plate; 83080\* Eligibility Affidavit for Motor
Vehicle Registration; 83081\* Application for a Press (PRES) License Plate; 83088
Temporary 90 Day Employment (Sample only — do not fill out); 83090\* Application
by Florida Motor Vehicle Mobile Home or Recreational Vehicle Dealer for Temporary
Plates; 83091\* Application for Temporary License Plate; 83101\* Missing License
Plate, Decal or Placard Affidavit; 83109\* Application for Legislative License
Plate; 83110\* Application for Registration of a Motor Vehicle for Agricultural
(Restricted), Horticultural (Restricted), or "Goat" License Plate; 83140 License
Plate Rate Chart; 83145 Personalized License Plate Fee Schedule; 83146\*
Application for Replacement license plate, validation decal or parking permit;
83330\* Florida Insurance Affidavit; 83345 Certificate of Deposit Power of
Attorney; 83351 Cash On Delivery Unpaid Fees; 83363\* Application for License
Plate or Decal Refund; 83390\* Application for Sunscreening Medical Exemption;
83416\* Request for Division of Motor Vehicle/Vessel Forms.

**84xxx–86xxx — Dealer, manufacturer, surety bonds:**
84003 Receipt and Certificate of Disposal for Obsolete License Plates; 84013\*
Vehicle Purchase Record; 84014\* Vehicle Sales Record; 84016\* Temporary Tag
Record; 84019\* Application and Claim To Recover Compensation from the Mobile Home
and Recreational Vehicle Trust Fund; 84026\* Assignment of Claim/Suit; 84045\*
Registration of Mobile Home Dealer's Salesperson(s); 84050\* Application for
Dealer License Reprint; 84058\* Vehicle Air Pollution Control Statement; 84061\*
Declaration Affidavit For A Motor Vehicle Which Will Be Titled and Registered In
Another State or Country; 84200\* Application for A Temporary "Supplemental"
License for An Off-Premises Sale by A Motor Vehicle, Mobile Home or Recreational
Vehicle Dealer; 84256\* Application for a License as a Motor Vehicle or
Recreational Vehicle Manufacturer, Importer, or Distributor or a Mobile Home
Manufacturer; 84490\* Statement of Builder; 84491\* Statement of Builder
(Additional Sheet); 84901\* Complaint Affidavit; 85008\* International Fuel Tax
Agreement, Florida Application; 85010 IFTA Decal Re-order Form; 85017\*
Recordkeeping Agreement for FLORIDA Based Carriers Registered Under the IRP and
IFTA; 85041\* IRP/IFTA Address Change Form; 85057\* IRP Lease Agreement
Information Form; 85100\* Application to Replace an Apportioned License Plate
and/or CAB Card; 85500 IRP Trucking Manual; 85800 How to Calculate the
International Fuel Tax Agreement Quarterly Tax Return; 85900 International
Registration Plan, Florida Application; 85920 IFTA Trucking Manual; 85921\*
International Fuel Tax Agreement, Florida Tax Return; 86009 Application for
Temporary Exemption; 86018\* Surety Bond, Mobile Home Dealer; 86019\* Surety Bond,
Recreational Vehicle Dealer; 86020\* Surety Bond, Motor Vehicle Dealer; 86029
Application for Reciprocal Inspection Exemption; 86050\* Surety Bond, Mobile Home
Manufacturer; 86051\* Surety Bond, Recreational Vehicle Manufacturer or Van
Converter; 86056\* Application for License as a Motor Vehicle, Mobile Home, or
Recreational Vehicle Dealer; 86057\* Florida Motor Vehicle Dealer Irrevocable
Letter of Credit; 86058\* Florida Mobile Home Dealer Irrevocable Letter of Credit;
86059\* Florida Mobile Home Manufacturer Irrevocable Letter of Credit; 86060\*
Statement of Intent to Relinquish a Dealer License; 86072\* Modification to Dealer
License for Licensed Motor Vehicle, Mobile Home, or Recreational Vehicle Dealers;
86218\* Renewal Application: Mobile Home Manufacturer or Recreational Vehicle
Manufacturer, Importer, or Distributor; 86219\* Renewal Application: Motor Vehicle
Manufacturer, Importer, or Distributor; 86720\* Renewal Application Motor Vehicle,
Mobile Home, or Recreational Vehicle Dealers.

Note on the tail of the list: the direct read of the Forms page returned lines
0–402 (through form 86060). The remaining entries (86072, 86218, 86219, 86720)
were confirmed from FLHSMV Forms-page text returned by web search and from the
FLHSMV dealer Forms and Resources page (86072, 86720). Any further entries after
86720, if the live page has any, were not verified in this session.

## 5. Where to download — summary

- **All blank forms:** the Forms hub, https://www.flhsmv.gov/resources/forms/ —
  one page, sorted by form number, each entry linking to its PDF. Forms marked \*
  are fillable online, then printed (they cannot be saved online, per the IRP/IFTA
  pages' statement of the same rule for those forms).
- **All handbooks/manuals:** the Handbooks & Manuals hub,
  https://www.flhsmv.gov/resources/handbooks-manuals/ — Florida Driver's Handbook
  (English / Español / Kreol + Study Guide Answer Locations), Florida CDL Handbook
  (English + Supplement For Modernized Version / Spanish), Florida Motorcycle
  Operator Handbook, Motor Vehicle Procedures Manual. Print copies of the driver,
  motorcycle and CDL handbooks are free at local driver licence service centres
  and may be returned for re-use.
- **Dealer handbook and dealer forms:** the dealer Forms and Resources page
  (URL in §3.4) and the main Forms page (84xxx–86xxx series).
- **IRP/IFTA forms, manuals, user guides and video tutorials:** the two "Forms,
  User Guides, & Tutorials" pages (URLs in §3.5); paper forms are PDF-fillable but
  cannot be saved online — print before exiting, then sign; notarised originals go
  to the Bureau of Commercial Vehicle and Driver Services, and other forms can be
  uploaded into ICFS. IRP/IFTA help: (850) 617-3711, weekdays 8:00 AM–4:30 PM EST.
- **Motor Vehicle Procedures Manual procedures:** the Procedures Manual landing
  page (URL in §2.4); individual procedures are PDFs under
  https://www.flhsmv.gov/pdf/proc/ (e.g. /pdf/proc/rs/rs-01.pdf,
  /pdf/proc/tl/tl-05.pdf, /pdf/proc/ves/vstl/vstl-20.pdf — each attested in search
  results for FLHSMV procedure PDFs).
- **Teen forms:** Required Forms for Teens page (URL in §3.6). **Older-driver
  forms:** Forms for Older Drivers page (URL in §3.6).

## 6. Pages studied (page list)

| # | Page | URL | How read / status |
|---|---|---|---|
| 1 | Home | https://flhsmv.gov/ | browser.open, 2026-11-21 crawl; press-release headlines only — no forms/handbook content on the home page text returned |
| 2 | A to Z Guide | https://flhsmv.gov/a-to-z-guide/ | browser.open, full 608-line read; source of the section's entry list |
| 3 | Forms | https://www.flhsmv.gov/resources/forms/ | browser.open, lines 0–402 read (through 86060); tail (86072–86720) confirmed via FLHSMV search-result text |
| 4 | Handbooks & Manuals | https://www.flhsmv.gov/resources/handbooks-manuals/ | browser.open, full 45-line read |
| 5 | IFTA — Forms, User Guides, & Tutorials | https://www.flhsmv.gov/driver-licenses-id-cards/commercial-motor-vehicle-drivers/international-fuel-tax-agreement/forms-and-manuals/ | browser.open, full 47-line read |
| 6 | IRP — Forms, User Guides, & Tutorials | https://www.flhsmv.gov/driver-licenses-id-cards/commercial-motor-vehicle-drivers/international-registration-plan/forms-and-manuals/ | browser.open, full 39-line read |
| 7 | Motor Vehicle Procedures Manual (landing page) | https://flhsmv.gov/motor-vehicles-tags-titles/motor-vehicle-procedure-manual/ | Not directly opened — browser.open returned HTTP 429 (rate limit) on repeated attempts; contents evidenced from FLHSMV search-result text (procedure table with names, numbers, revision dates) and FLHSMV procedure PDFs RS-01, TL-05, VSTL-20 |
| 8 | Dealer Forms and Resources | https://www.flhsmv.gov/motor-vehicles-tags-titles/dealers-installers-manufacturers-distributors-importers/mv-rv-mh-dealer-broker-licenses/forms-and-resources/ | Not directly opened — same 429 rate limit; contents evidenced from FLHSMV search-result text (86056, 86072, 86720, Dealer Handbook, training schools) |
| 9 | Required Forms for Teens | https://www.flhsmv.gov/driver-licenses-id-cards/licensing-requirements-teens-graduated-driver-license-laws-driving-curfews/required-forms-teens/ | FLHSMV search-result text (71142, 71143, 71144 + purposes) |
| 10 | Forms for Older Drivers | http://www.flhsmv.gov/driver-licenses-id-cards/florida-granddriver/forms-for-older-drivers/ | FLHSMV search-result text (72190, 72119, 72010 + purposes) |
| 11 | General Information (driver licences) | https://www.flhsmv.gov/driver-licenses-id-cards/general-information | FLHSMV search-result text (handbook free at service centres; Class E exam = 50 questions; study the handbook) |
| 12 | Motorcycle Rider Education & Endorsements | http://flhsmv.gov/driver-licenses-id-cards/motorcycle-rider-education-endorsements/ | FLHSMV search-result text (operator's manual contents; endorsement requirement) |
| 13 | Motorcycle Safety Awareness | https://www.flhsmv.gov/safety-center/motorcycle-safety/ | FLHSMV search-result text (download the Florida Motorcycle Handbook) |
| 14 | Dealer Handbook PDF (text) | https://www.flhsmv.gov/pdf/dealerservices/dealerhandbook.pdf | Handbook text (title, purpose, Bureau of Dealer Services) via search; PDF URL itself cited only in a third-party document — flagged unverified in §2.5 |
| 15 | Procedure PDFs RS-01, TL-05, VSTL-20 | https://www.flhsmv.gov/pdf/proc/rs/rs-01.pdf; https://www.flhsmv.gov/pdf/proc/tl/tl-05.pdf; https://www.flhsmv.gov/pdf/proc/ves/vstl/vstl-20.pdf | FLHSMV search-result text (purposes, legal authority, revision dates) |
| 16 | Documents & Publications / Resource Center reports pages | https://www.flhsmv.gov/resource-center/driver-and-vehicle-reports/; https://www.flhsmv.gov/resourcecenter/cabinet-and-legislature-reports/; http://flhsmv.gov/resources/open-government/office-of-inspector-general/documents-publications/ | FLHSMV search-result text; noted only to distinguish report publications from handbooks/forms (§3.6) |

## 7. Gaps and caveats

- The browser tool rate-limited (HTTP 429) partway through the session: the
  Forms page tail (lines 402–489), the Motor Vehicle Procedures Manual landing
  page, and the dealer Forms and Resources page could not be opened directly.
  Their contents are reported from FLHSMV page text returned by web search, and
  are flagged as such above. A follow-up direct read of those three pages would
  close the gap, particularly to confirm whether any form entries follow 86720.
- Exact PDF download URLs for individual handbooks were not shown on the
  Handbooks & Manuals page text returned; only the hub page and the handbook
  names/languages are attested. Do not cite handbook PDF filenames from
  third-party sites as FLHSMV facts.
- The Forms page gives form titles only, not per-form instructions; purposes
  stated in §3 are limited to what the titles and the dedicated FLHSMV pages
  (teens, older drivers, IRP/IFTA) actually say.
# 15 — Florida Highway Patrol (FHP)

**Study scope:** flhsmv.gov — Florida Department of Highway Safety and Motor Vehicles (FLHSMV), Florida Highway Patrol division.
**Studied:** 23 November 2026.
**Sources:** https://flhsmv.gov/ and https://flhsmv.gov/a-to-z-guide/ (both opened in full), plus the FHP pages listed in §9 below.

## Method note — read this first

- The FLHSMV homepage and the A to Z Guide were opened directly with `browser.open` and read in full.
- Direct `browser.open` calls to individual FHP subpages then failed repeatedly with upstream HTTP 429 ("exceeded the maximum number of requests allowed within a given time frame"). Those opens were **not** retried, per the rate-limit instruction.
- The subpage facts below were therefore gathered from the search index's full-text rendering of each flhsmv.gov page (including the site's own WordPress JSON copies of the pages, e.g. `wp-json/wp/v2/pages/...`, which reproduce the page content verbatim) and from FLHSMV press releases on flhsmv.gov. Every fact below is traceable to a flhsmv.gov URL in §9.
- One exception is flagged in §5: the text of §321.24, Florida Statutes (the Auxiliary's statutory basis) is **not** on flhsmv.gov; it is cited there only as outside corroboration and is labelled as such. All other facts are from flhsmv.gov.
- BeATrooper.com is FHP's own recruitment site, linked from flhsmv.gov (A to Z Guide: "Career Opportunities (FHP)" → http://beatrooper.com/; "Beatrooper.com"). Its requirements/salary figures are included in §4 as the linked recruitment source.
- Where the search index showed two different figures for the same thing (e.g. academy length 28 vs 29 weeks; recruit pay $4,166.67/mo vs $5,000/mo), both are reported with their source context rather than silently reconciled.

---

## 1. What FHP is and what it does

### Identity

- FHP is a division of FLHSMV and "Florida's largest state law enforcement agency." Its troopers are known as **"Florida's Finest."**
- FLHSMV mission (department-wide): *"Providing Highway Safety and Security Through Excellence in Service, Education, and Enforcement."* Department vision: *"A Safer Florida."*
- FHP core values / motto: **Courtesy, Service, Protection** — rendered on the About FHP page as "COURTESY * SERVICE * PROTECTION."
- FHP's own statement of purpose (About FHP): "The FHP strives to achieve our core values of courtesy, service and protection. It is our job to help ensure the safety and welfare of millions of Florida's residents and visitors each day."
- Troopers "promote safety and enforce laws that keep Floridians and visitors safe. They are national leaders in traffic safety, as well as combatting human smuggling, human trafficking, and narcotic trafficking" (FLHSMV, 6 April 2023, naming of the new Colonel).
- The iconic **black-and-tan** uniform and patrol vehicle: "Since 1939 FHP has been synonymous with black and tan, in uniform and vehicle."

### Size and workload

- Authorized strength (About FHP): **1,982 sworn positions and 503 non-sworn positions, for a total of 2,485 full-time employees.** Press releases round this to "nearly 2,000 State Troopers" / "nearly 2,500 FHP Members, both sworn and non-sworn."
- Workload (About FHP): "Today we patrol over 43,200,000 miles and investigate over 176,000 crashes annually."
- FLHSMV as a whole has "more than 4,000 members" serving "in all of Florida's 67 counties."

### History (About FHP and History of the Florida Highway Patrol)

- **1939:** FHP established when then-Governor Fred P. Cone, member of the Executive Board of the Department of Public Safety, made a motion to establish the Florida Highway Patrol. The 1939 session of the Florida Legislature passed Chapter 19551, Florida Statutes, creating the State Department of Public Safety and the Division of the Florida Highway Patrol.
- First training academy held in **Bradenton with 40 students**, under Director Reid and (then) Captain Kirkman.
- Pre-history on the History page: 23 November 1931, Attorney General Cary D. Landis ruled it was the State Road Department's duty to maintain state roads and enforce the laws preserving them; 12 weight inspectors were hired — "the beginning of state law enforcement in Florida." 26 April 1934: the Traffic Enforcement Division could enforce Florida Motor Vehicle Law; 1 May 1934 it was instructed to enforce all Florida traffic laws. In 1937 Governor Cone abolished the Traffic Enforcement Division in a cost-saving move (the "Old Scholtz Patrol"). In July 1936 Major H. N. Kirkman had been appointed Chief of the State Road Department, Traffic Enforcement Division; Kirkman was appointed the first Commander of FHP on 1 October 1939.
- The Department of Public Safety was reorganized and renamed the Department of Highway Safety and Motor Vehicles in 1970 (per the FHP history summary; the About page dates the Patrol itself to 1939).

### Leadership (Troop Boundaries & Information page)

- **Director:** Colonel Gary L. Howze, 850-617-2300. Named 15th Colonel of FHP on 6 April 2023 by FLHSMV Executive Director Dave Kerner; he served with FHP from 1990 until 2019, when he became Director of Law Enforcement, Victim Services, and Criminal Justice Programs for the Florida Attorney General. "With over 30 years of experience."
- **Deputy Directors:** Lieutenant Colonel Robert "Bob" Chandler, Lieutenant Colonel Mark Brown, Lieutenant Colonel Joseph "Cory" Harrison — all 850-617-2300.
- **Regional Commanders:** Chief Jeffrey Dixon, Special Services Command, 850-617-2351; Chief Troy Thompson, Commercial Vehicle Enforcement, 850-617-2351; Chief John Gourley, North Florida Operations, 850-617-2351; TBA, Central Florida Operations, 407-737-2300; Chief Matthew Williams, South Florida Operations, 941-751-8355.
- Headquarters: Neil Kirkman Building, 2900 Apalachee Parkway, Tallahassee, FL 32399; main number 850-617-2300.

### Troop structure (Troop Boundaries & Information)

Twelve troops, A–L (plus the two CVE troops I and J, §7):

| Troop | Commander (as listed) | Phone | HQ / area |
|---|---|---|---|
| A | Major Warren Fast | 850-873-7020 | Panama City |
| B | Major Andrew Litzell | 386-758-0515 | Lake City — "Gateway to Florida"; 9 counties of the I-75 corridor: Columbia, Suwannee, Hamilton, Alachua, Dixie, Gilchrist, Levy, Lafayette, Marion; 107 sworn and 10 non-sworn members; districts Lake City, Gainesville, Ocala; Cross City sub-district |
| C | Major Richard Benton | 813-558-1800 | Tampa |
| D | Major Mark Castleberry | 407-737-2300 | Orlando |
| E | Major Ellery Collado | 305-470-2500 | Miami |
| F | Major William Harris | 239-344-1730 | Bradenton / Ft. Myers |
| G | Major Steven Harris | 904-695-4000 | Jacksonville — 9 counties of Northeast Florida: Baker, Bradford, Clay, Duval, Flagler, Nassau, Putnam, St. Johns, Union; districts Jacksonville, St. Augustine, Special Operations |
| H | Major Jeffrey Bissainthe | 850-410-3046 | Tallahassee |
| I | Major Erick McGuire | 850-617-3010 | CVE North — oversees commercial vehicle enforcement for the northern region encompassing Troops A, B, G and H |
| J | Major Thomas Pikul | 239-225-9606 | CVE South — oversees commercial vehicle enforcement for the southern region encompassing Troops C, D, E, F and L |
| K | Major Roger Reyes | 305-234-2240 | Florida's Turnpike |
| L | TBA | 561-357-4040 | Lake Worth — 6 counties in Southeast Florida: Broward, Palm Beach, Martin, St. Lucie, Indian River, Okeechobee; districts Davie, Lake Worth, Fort Pierce |

- Each troop page links "Live Road Conditions in this Area," "Looking for a Crash Report," and "Station Phone Numbers and Addresses."
- FHP station locations page lists stations by city with address, phone, county and troop, e.g. Bradenton 5023 53rd Ave. E., 941-751-8350 (Troop F); Jacksonville 7322 Normandy Blvd., 904-695-4000 (Troop G); Miami 1011 NW 111th Ave., 305-470-2500 (Troop E); Orlando 11059 International Drive, 407-737-2300 (Troop D); Panama City 6030 County Road 2321, 850-873-7020 (Troop A); Pensacola 150 W. Stumpfield Rd., 850-484-5000 (Troop A); Tallahassee HQ, Neil Kirkman Building, 2900 Apalachee Parkway, 850-617-2300; Training Academy, 75 College Dr., Suite 221-FHP, Havana, FL 32333-4695, 850-558-4250.
- **Public Affairs Officers** (Office of Public Affairs / "Meet the Team"): one per troop, e.g. Troop A TBD, 850-445-5258; Troop B Lt. Josh Seay, (386) 754-6286, JoshuaSeay@flhsmv.gov; Troop C Sgt. Steve Gaskins, (813) 215-1867; Troop D Lt. Tara Crescenzi, (407) 797-2707; Troop E Lt. Alejandro Camacho, (305) 308-0586; Troop F Lt. Gregory S. Bueno, (239) 225-9605; Troop G Sgt. Dylan Bryan, (904) 693-5070; Troop H Cpl. Patricia Jefferson-Shaw, (850) 410-3046; Troops I/J (CVE) Sgt. Denise Meredith, (407) 264-3235, DeniseMeredith@flhsmv.gov; Troop L Lt. Indiana Miranda, (954) 308-5929. Each troop also has FHP Instagram and X accounts (e.g. FHP Panhandle, FHP Tampa, FHP Orlando, FHP Miami).

### Contact — FHP

- General FHP headquarters: 850-617-2300.
- Dial **\*FHP (\*347)** from a mobile phone to reach FHP — used for the Desk Trooper Program (see §8) and to report crashes / request a trooper.
- Commercial Vehicle Enforcement: 850-617-2280 (FLHSMV Contact Us page); CVE compliance questions: (407) 264-3210.
- Recruitment: BeATrooper@flhsmv.gov; Recruitment Coordinator 1-850-617-2315.
- Mailing address for trooper applications/transcripts: Florida Highway Patrol, Background, Recruitment and Selection, 2900 Apalachee Parkway, MS 49, Tallahassee, FL 32399.
- **\*FHP is also the number shown in the A to Z Guide** ("*FHP" entry) — the guide lists it as a standalone FHP entry.

---

## 2. Specialized areas

About FHP summarizes: "In addition to Patrol Operations, the Florida Highway Patrol has many specialized areas. The Office of Commercial Vehicle Enforcement conducts data driven enforcement and educational programs to improve the safety of commercial motor vehicles. The Criminal Interdiction Unit consists of specially trained troopers that are strategically assigned throughout the state in order to interdict criminal activity. The Bureau of Criminal Investigations and Intelligence includes specific programmatic areas related to organized crime, terrorism, domestic security, gangs, criminal interdiction, dignitary protection, critical infrastructure protection, and biometric recognition and analysis. Additional specialized areas include recruitment, public affairs, honor guard, aviation, and more."

### 2.1 Bureau of Criminal Investigations and Intelligence (BCII)

- **Page:** https://www.flhsmv.gov/florida-highway-patrol/specialized-areas/bureau-of-criminal-investigations-and-intelligence-bcii/
- Led by a Bureau Commander holding the rank of Major, who serves as FHP's Chief Investigator. BCII is a component of the agency's Special Services Command.
- **6 operational components:** 2 regionally dispersed Investigative Operations Sections (North & South), each led by a Section Commander holding the rank of Captain; the Intelligence and Analysis Section, led by the Chief of Intelligence; the Strategic Operations Unit; the Case Management and Investigative Coordination Unit; and the Executive Transportation Section.
- Programmatic areas: organized crime, terrorism, domestic security, gangs, criminal interdiction, transportation of Florida's Lieutenant Governor, critical infrastructure protection, and biometric recognition and analysis.
- **Investigations conducted:** auto theft, commercial vehicle and cargo theft, heavy equipment theft, identity theft, driver's license fraud, title fraud, odometer fraud, and other criminal activity related to FLHSMV / FHP authorities. Works closely with local, state, and federal partners.
- **Strategic Operations Unit:** comprised of the Office of Criminal Interdiction and the Office of Homeland Security; manages and coordinates homeland security operations, criminal interdiction operations and the agency's canine program; coordinates FHP's statewide law enforcement task force participation.
- **Intelligence and Analysis Section:** headquartered in Tallahassee; "Intelligence is raw criminal or terrorist-related [information] that has been vetted and analyzed to provide meaningful and trustworthy actionable knowledge to law enforcement decision makers about complex criminality, criminal enterprises, criminal extremists, and terrorists." Retains primary responsibility for all intelligence-related issues, including analysis, operations, training, compliance, and policy.
- **Investigative Management and Coordination Unit:** headquartered in Tallahassee; the central repository for all case files and records of the BCII.
- FHP Policy Manual, Chapter 22 (Investigations), lists BCII-related policies: Investigative Responsibilities 22.01; Victim/Witness Assistance 22.02; Criminal Intelligence 22.03; Bureau of Criminal Investigations and Intelligence and Investigative Task Forces 22.04; Vice, Drugs, and Organized Crime 22.05; Legal Process 22.07; Missing Endangered Persons 22.08; Domestic Violence Intervention 22.09; Interviews/Interrogations/Polygraph Rooms 22.12.

### 2.2 Criminal Interdiction Unit (CIU) — the Contraband Interdiction Program

- **Page:** https://www.flhsmv.gov/florida-highway-patrol/specialized-areas/criminal-interdiction-unit/ — this is the page the A to Z Guide's "Contraband Interdiction Program" entry points to.
- "The Criminal Interdiction Unit (CIU) consists of specially trained troopers designated as felony officers and canine handlers. These troopers are strategically assigned throughout the state to patrol the interstate system and other highways in order to interdict drug couriers and other criminal activity."
- "The CIU assists other federal, state, and local law enforcement agencies in the detection and apprehension of drug traffickers and other criminal offenders that utilize the roadways of Florida. The CIU is an active participant in various enforcement operations coordinated by the Florida Office of Drug Control."
- Equipment: "sophisticated drug detection equipment such as fiber optic scopes, drug detection devices, electronic measuring devices, dual-purpose canines, and various other tools."
- **2024 results (CIU page):** seized 3,061 pounds of marijuana, 336 pounds of cocaine, 2.1 pounds of heroin, 434 pounds of methamphetamine, over $2 million in U.S. currency, and more than $279 million in total seized contraband; another 567 pounds of other types of illegal drugs and prescription medications; over 200 weapons seized; 948 persons arrested and 2,122 felony charges.
- **2022 results (FLHSMV press release, 27 March 2023):** 1,025 felony arrests on 2,187 felony charges; over 5,000 pounds of narcotics confiscated and currency valued at $110,400,681 (including over $5 million in U.S. currency); 204 weapons seized; smuggling of 148 undocumented immigrants inhibited, across Florida's 67 counties. Most-seized drug by gross weight was marijuana; 722 pounds of cocaine and 649 pounds of other drugs (fentanyl, oxycodone, xylazine, ecstasy/molly, among others) were confiscated.
- CIU training: "undergoes regular, intensive training to stay up to date on tactics used by criminals, such as how to uncover hidden compartments in vehicles or how to spot human trafficking/smuggling. CIU's K-9 unit requires five months of initial training, following by more rigorous work to make an effective team. CIU has also been trained on how to provide first-aid training to K-9s." (2023 release.)
- Other CIU work cited in the 2023 release: finding murderers with in-state and out-of-state warrants; recovering stolen merchandise; uncovering identity and Social Security theft; halting diesel fuel theft and discovering gas scams; rescue efforts and traffic control during Hurricane Ian and other disasters. Three major joint operations in Escambia, Sumter, and Columbia counties in 2022.
- **K-9s:** the CIU page profiles individual dogs, e.g. K-9 Cain (donated by a South Florida family; drug training/certification in Gainesville in 2006 with Trooper Chris Ellis; team with felony officer Trooper Harrison from July 2006; through I-10 traffic stops helped seize 194 lbs of cannabis valued at $174,600, $189,660 in U.S. currency, and 7 kilos of cocaine valued at $168,000); K-9 Jewels (entered service March 2002 at 18 weeks; drug certified July 2003; partners Troopers Jimmie Davis and Jason Lemery; assisted seizures of over 1,600 pounds of marijuana, 175 pounds of cocaine/cocaine base, $1.5 million in U.S. currency, plus methamphetamine, heroin, anabolic steroids, weapons, stolen property, and the arrest of over 175 individuals — total value approx. $6.8 million; retired 30 November 2007 for medical reasons); K-9 Major (began 23 October 1989; K-9 Patrol and Drug Detection schools March 1990; handler Trooper Mike Smith, Troop G Jacksonville; seized approx. $100,000 in illegal drugs in Northeast Florida; killed in the line of duty 29 November 1990 when struck by a passing vehicle during a roadside vehicle search; listed on the FHP Memorial, End of Watch 11/29/90).
- **B.I.T.E. Back / Operation Safe Highways:** B.I.T.E. (Border Integrity Trafficking Enforcement) Back Operations are a collaborative effort of the Florida National Guard Counterdrug Task Force, FDLE, and local sheriff's offices to prevent illegal narcotics and contraband, human smuggling, and human trafficking from entering Florida communities. Operation Safe Highways was initiated in 2022 at the direction of Governor Ron DeSantis. Example — Operation Bite Back, St. Johns and Flagler Counties (August 2024 press release): 3-day operation, 69 traffic stops, 8 arrests, 28 felony charges, 22 drug charges, 10 misdemeanor charges; seizures included fentanyl 0.7 g ("enough to kill 350 people"), cocaine 4 g, marijuana 27,620 g, 4 firearms, 100 g other drugs, $12,500 currency; total assets $599,230. By November 2023 the B.I.T.E. program was credited with recovery of over 8 pounds of fentanyl ("representing the lives of over 1.8 million Floridians"), almost 30 pounds of cocaine, over 80 pounds of methamphetamine, 42 arrests for human smuggling, and over 60 fugitives off the street.
- **Criminal Alien Apprehension Team (CAAT):** a newer FHP unit in the news on the homepage — on 29 October 2026 CAAT troopers in Boca Raton arrested Jean S. Dorisca, 48, wanted in Osceola County on a felony warrant for three counts of vehicular homicide in a 2024 crash that killed three motorists. (Homepage press release, 2 November 2026.)

### 2.3 Honor Guard

- **Page:** https://www.flhsmv.gov/florida-highway-patrol/specialized-areas/honor-guard/
- "The Florida Highway Patrol's (FHP) Statewide Honor Guard is comprised of up to 51 sworn FHP members from across the state of Florida."
- Mission: represent FHP with a well-trained ceremonial unit to render honor, respect, preserve traditions, promote esprit-de-corps, instill pride and perform ceremonial duties for Troopers killed in the line of duty; attend funeral ceremonial duties for in-state and out-of-state officers killed in the line of duty; act as a clearinghouse for the Department and Division regarding ceremonial protocol matters; perform other functions as deemed appropriate by the Colonel.
- Commander (as listed): Captain Nathan Stidham, Honor Guard Commander, November 2025 – Present; Lt. Daniel Wagner, Assistant Honor Guard Commander – Administration; Lt. Tara Crescenzi, Assistant Honor Guard Commander – Special Operations. Regional team leaders are listed for Northern, Central, and Southern regions.

### 2.4 Other specialized areas named on flhsmv.gov

- Recruitment, public affairs, aviation (About FHP, "additional specialized areas include recruitment, public affairs, honor guard, aviation, and more").
- FHP Policy Manual (https://www.flhsmv.gov/florida-highway-patrol/about-fhp/fhp-policy-manual/) — chapters include Complaints and Discipline (Ch. 8), Inspections (Ch. 9), Use of Control and Weapons (Ch. 10), Arrest Related Procedures (Ch. 11), Evidence/Property incl. Contraband Seizures 12.03 (Ch. 12), Reports and Records incl. Drug Interdiction Reporting Form 13.02 (Ch. 13), Operational Procedures incl. Traffic Crash Investigations 17.04, Enforcement Policy 17.06, Driver's License and Vehicle Inspection Checkpoints 17.07, Comprehensive Roadside Safety Checkpoints 17.08 (Ch. 17), Motorcycles (Ch. 19), Infectious Diseases (Ch. 21), Investigations (Ch. 22).

---

## 3. Office of Commercial Vehicle Enforcement (CVE)

- **Page:** https://www.flhsmv.gov/florida-highway-patrol/specialized-areas/commercial-vehicle-enforcement (also the legacy URL http://www.flhsmv.gov/fhp/CVE/).
- "Within the Florida Highway Patrol resides the Office of Commercial Vehicle Enforcement. The Office of Commercial Vehicle Enforcement (CVE) is the Governor's designated lead agency responsible for commercial vehicle operations in Florida."
- The CVE section contains general information such as the CVE Mission, CVE History, Covered Farm Vehicles, Unified Carrier Registration, and various Manuals and Forms.
- "The Office of Commercial Vehicle Enforcement conducts data driven enforcement and educational programs to improve the safety of commercial motor vehicles." (About FHP.)
- **Authority:** "Current Florida Statutes gives any CVE Trooper the authority to require the driver of any commercial vehicle operated to stop and submit to an inspection and enforce the traffic laws of this state with an emphasis on violations committed by commercial vehicles."
- **Organization:** managed and supervised by a Chief headquartered in Tallahassee. Two troops — Troop I (north) and Troop J (south) — with 12 district/sub-district offices throughout the state, responsible for conducting commercial vehicle enforcement as well as other patrol duties. (CVE Office Locations page.)
  - CVE Headquarters: Chief Troy Thompson, 2900 Apalachee Parkway, MS 45, Tallahassee, FL 32399.
  - Troop I HQ: Major Erick McGuire (ErickMcGuire@flhsmv.gov), Neil Kirkman Building, 2900 Apalachee Parkway, MS 45, Tallahassee, FL 32399, (850) 617-3010. Offices: Pensacola, Panama City, Lake City, Tallahassee, Jacksonville, Ocala.
  - Troop J HQ: Major Thomas Pikul (ThomasPikul@flhsmv.gov), Turkey Lake Service Plaza, Bldg. 5318, P.O. Box 613069, Ocoee, FL 34761, (239) 225-9606. Offices: Orlando, Deland, Tampa, Fort Myers, Palm Beach, Miami.
  - Example district offices: Pensacola District, Captain Matthew Blansit, 6025 Old Bagdad Highway, Milton, FL 32583, (850) 564-2179 (counties Escambia, Okaloosa, Santa Rosa, Walton); Panama City Sub-District, Lt. Jonathan Strickland, 6030 CR 2321, Panama City, FL 32404, (850) 767-3665 (Bay, Calhoun, Gulf, Holmes, Jackson, Washington); Lake City District, Captain Kevin Pace, 1109 South Marion Avenue, MS 2105, Lake City, FL 32025.
  - Also: CVE Compliance Investigations (Captain Charles Smalley), CVE Hazardous Material Enforcement, CVE Training Section.
- **Contacts:** general/compliance questions (407) 264-3210; Commercial Vehicle Enforcement (FLHSMV Contact Us) 850-617-2280; CDL Help Desk 850-617-2606; Commercial Carrier IFTA/IRP Help Desk 850-617-3711; Commercial Driver License Retest Help Line 850-617-2707.
- **New Entrant Safety Audits and Compliance Reviews:** "New Entrant Safety Audits are educational audits used by the Office of Commercial Vehicle Enforcement to make sure new carriers understand the regulations and have adequate safety management controls in place." Compliance reviews "are conducted onsite at the carrier's principal place of business and are more detailed and comprehensive than the New Entrant Safety Audit."
- **Citations and DataQs:** a Commercial Motor Vehicle Citation is also known as a Uniform Commercial Citation (UCC); a recipient "has the option to protest this civil penalty with the Commercial Motor Vehicle Review Board." "The DataQ system is used to [fix] incorrect or duplicated information in the FMCSA database and is most commonly used to request the removal or correction of violations incurred during roadside inspections."
- **Weight Enforcement** (https://www.flhsmv.gov/florida-highway-patrol/commercial-vehicle-enforcement/safety-enforcement/weight-enforcement/): "The primary purpose of the Office of Commercial Vehicle Enforcement (CVE) Weight Enforcement program is to protect highway system pavement and structures (bridges) from excessive damage due to overweight vehicles. CVE Troopers enforce state and federal laws that regulate the weight of vehicles operating on the Florida's highways." Penalty: "$.05 per pound for all weight over the legal weight for the vehicle." The page gives maximum gross weight tables by distance between first and last axles, and a Specialty Gross Weight table for dump trucks, concrete mixing trucks, waste collection/disposal trucks, and fuel oil/gasoline trucks operated as a single unit.
- **Operations:** CVE routinely conducts inspections "to ensure commercial vehicles traveling Florida roadways operate safely." Example — Operation Airbrake (statewide unannounced brake check, April 2023, in support of the Commercial Vehicle Safety Alliance's "Operation Airbrake" program, "dedicated to improving commercial vehicle brake safety throughout North America by reducing the number of highway crashes caused by faulty braking systems"): 550 commercial vehicles checked, subject to Level 1 inspections including brakes, tire pressure, load security, lights, logbook, and driver license. CVE also runs the Drug Interdiction Assistance Program (DIAP) with the DEA, FDLE and sheriff's offices (2017 example, Troop J, Fort Myers: 327 traffic stops, 100 citations, 100 commercial vehicle inspections).
- **Multi-state work:** FHP joined partner agencies in Operation Saturday Night Fever (October 2026 press release), "a coordinated overnight commercial motor vehicle enforcement initiative focused on improving roadway safety" across state lines.
- Related A to Z entries: "Commercial Vehicle Enforcement," "Commercial Motor Carriers (FAQs)," "Commercial Vehicle Information," "FAQs on Trucking/Commercial Motor Carriers," "Office of Commercial Vehicle Enforcement," "Trucking/Commercial Motor Carriers."

---

## 4. How to become a trooper — BeATrooper.com and the FHP Training Academy

The A to Z Guide routes all FHP recruiting through **BeATrooper.com**: "Career Opportunities (FHP)" → http://beatrooper.com/; "Beatrooper.com"; "Recruits (FHP)"; "Training Academy (FHP)." The application portal is the FHP Applicant Tracking System at https://services.flhsmv.gov/ATS/ATSApplicant/home, and the contact is BeATrooper@flhsmv.gov.

### 4.1 Minimum qualifications (BeATrooper.com — State Trooper and Requirements pages)

- United States citizen.
- High school graduate or equivalent (high school diploma or GED required).
- Minimum **19 years old** at time of application; **no maximum age restriction**.
- Valid driver's license; willing to accept an initial assignment anywhere in Florida.
- **Plus one of the following:**
  - One year of law enforcement experience (sworn or non-sworn); **or**
  - Two years of public contact experience; **or**
  - Two years of active continuous U.S. military service with an honorable discharge; **or**
  - Completed 30 semester hours or 45 quarter hours of college credit from an accredited college or university.
- Employment preference is given to qualified applicants who have completed **60 semester-hours or 90 quarter-hours** of college course work at an accredited college or university.
- **Minimum physical requirements:** weight in proportion to height (weight chart on the site); vision correctable to 20/30 in each eye with 140-degree field of vision; normal color distinguishing capabilities; successfully complete Physical Abilities Test; medical exam.

### 4.2 Salary and benefits (BeATrooper.com)

- **$60,000 annually** as a Basic Recruit or Transitional Recruit while in the Florida Highway Patrol Academy. Recruits are compensated **$4,166.67 per month** (per the Requirements page; see note below).
- **$62,400 upon successfully graduating** the Florida Highway Patrol Academy.
- **$5,000 bonus** for those not certified in Florida.
- **Additional $5,000 annually** if working in Broward, Dade (Miami-Dade), Monroe, or Palm Beach counties (Competitive Area Differential Salary).
- Benefits: paid vacations, holidays, sick leave and military leave; extensive health and life insurance options; deferred compensation plan; non-contributory retirement plan; education salary incentive pay. "All uniforms and an annual cleaning allowance, equipment and weapons are provided. Members are also afforded a take-home patrol car privilege."
- Note on a discrepancy in the site's own pages: the Requirements page says recruits are paid $4,166.67/month (= $50,000/yr), while the State Trooper page says $60,000/yr in the academy. The $60,000 / $62,400 figures are the ones on the State Trooper page and are consistent with the 2022 FLHSMV announcement that "Florida Highway Patrol troopers received a base pay increase to $50,000" (that 2022 figure is now superseded on BeATrooper.com). Report the $60,000 / $62,400 figures as current; the $4,166.67/month line appears to be an older figure left on the Requirements page.

### 4.3 Application steps (FHP Applicant Tracking System, services.flhsmv.gov)

- Begin the application in the ATS portal; forms requiring a notary's signature must be signed and notarized (FHP states it is unable to notarize the forms). All requested forms/documents must be completed and uploaded to the task section of the application; failure to have forms and notarizations completed "could result in your affidavit being placed in an inactive status."
- **Mail all sealed official college transcripts to:** Florida Highway Patrol, Background, Recruitment and Selection, 2900 Apalachee Parkway, MS 49, Tallahassee, FL 32399.
- **Before PAT testing:** visit your physician (Medical Doctor) and have the Florida Highway Patrol Medical Release Form completed by your physician. A Licensed Practical Nurse or equivalent completing the form "will NOT satisfy the requirement."
- **CJBAT:** "You will need to take and pass the Criminal Justice Basic Abilities Test (CJBAT) for Law Enforcement Officer. You will not be assigned to a Background Investigator until your CJBAT results have been received. You must provide proof through email to BeATrooper@flhsmv.gov of a passing score. The Florida Highway Patrol DOES NOT administer this test. The CJBAT (or FBAT) must be scheduled and paid by you."
  - Exemptions: former Florida-certified or out-of-state-certified officers may qualify; any applicant with an associate degree or higher from an accredited college OR a U.S. veteran discharged/released under honorable conditions is exempt; anyone who took and passed the CJBAT for Law Enforcement Officer within the last four (4) years, or who is certified as a law enforcement officer in Florida, need not retake it.

### 4.4 The Training Academy

- **Page:** FHP Training Academy (flhsmv.gov) — "Since the first class began in 1939, The Florida Highway Patrol Training Academy has had a long-standing tradition of transforming men and women into the State Troopers you see patrolling Florida's roadways."
- **Basic Recruit Class: 28 weeks** (Academy page) — the 154th Basic Recruit Class is described in a July 2025 press release as **29 weeks / 770 hours** (began 13 January 2025; "rigorous 29 weeks of training, equivalent to 770 hours"). The BeATrooper pages say "approximate 28–29 week training academy." Curriculum: classroom and hands-on learning in legal issues, interpersonal communications, crime scene and criminal investigations, DUI and crash investigations, traffic stops; plus **6 weeks of rigorous training in the high liability areas** of firearms, defensive tactics, first aid and vehicle operations.
- Military-style training, "designed to be both mentally and physically tough."
- Recruits **must reside on campus** while at the academy, follow strict rules/protocols, remain on academy grounds during the work week, and are released on most weekends.
- Recruits are **full-time employees from the moment they arrive**: salary and benefits start at the academy, and **full room and board is provided** for the duration of training.
- **Transitional Recruit Class (TRC):** for officers already certified in Florida or in other states. The 154th BRC graduated alongside TRC XX in July 2025; the 12 TRC graduates "were already Florida certified law enforcement officers that attended an eight-week transitional academy tailored specifically for officers that have already been certified." TRC XXII (March 2026) was for "law enforcement officers already certified in Florida or in other states with less than two years of experience," completing "more than 320 hours of advanced training." BeATrooper.com says Florida-certified officers receive "eight–nine weeks of Transitional Law Enforcement Training."
- **Lateral Recruit Class (LRC):** requires **at least two years of prior law enforcement experience**; out-of-state certified officers accepted after their certifications are transferred to Florida. Examples: LRC 17 (24 graduates), LRC 18 (13), LRC 19 (17).
- **After graduation:** new troopers are placed with a certified Field Training Officer (FTO) at their duty station and work with the FTO for **10 to 14 weeks** before being released to solo duty.
- **Upcoming classes (March 2026 press release):** 156th Basic Recruit Class — 14 September 2026; 24th Transitional Recruit Class — 21 September 2026. "FHP is seeking dedicated men and women who are ready to serve, protect, and uphold these standards of excellence."
- Recent graduations: 32 recruits (20 from 154th BRC + 12 from TRC XX), 18 July 2025; 15 troopers, TRC XXII, March 2026 (5 U.S. military veterans: Army, Navy, Marine Corps).
- Academy address: FHP Training Academy, 75 College Dr., Suite 221-FHP, Havana, FL 32333-4695, 850-558-4250 (station list).
- Apply at www.beatrooper.com — "You will also find great information such as history, steps to the academy, upcoming classes and a virtual tour."

### 4.5 Other FHP careers

- FHP's authorized non-sworn establishment is 503 positions. The non-sworn roles named on flhsmv.gov include **State Law Enforcement Dispatcher (SLED)** — the "Duty Officer of the Quarter" recognition is for SLEDs (e.g. Robin Hudak, Erica Reilly, Kristin Kelskey, Graham Graczyk, 2022); SLED of the Year and Civilian of the Year are named at the annual awards banquet (2022: SLED Erica Reilly, Lake Worth Regional Communications Center; Civilian of the Year Vic Thomas, General Headquarters).
- Department-wide careers (non-FHP): https://www.flhsmv.gov/careers/ ("Career Opportunities (HSMV)") — business administration, customer service, information technology, and public safety.

---

## 5. FHP Auxiliary

- **A to Z Guide entries:** "Auxiliary, FHP" → http://www.fhpa.info/ and "FHP Auxiliary."
- **FLHSMV's own description** (Patrol Support page, https://www.flhsmv.gov/florida-highway-patrol/patrol-support/): "The Florida Highway Patrol Auxiliary is a professionally trained, all volunteer, law enforcement organization dedicated to providing direct assistance and operational support to the Florida Highway Patrol. The unit is responsible for promoting public safety for the citizens and visitors of Florida."
- The same Patrol Support page describes the **Florida Highway Patrol Advisory Council** as "an organization comprised of business, professional, and community leaders throughout the state."
- The Auxiliary's own site is www.fhpauxiliary.com (per its social posts; the A to Z Guide links the older domain fhpa.info). The Auxiliary's Facebook page (Florida Highway Patrol Auxiliary) posts quarterly recognitions, e.g. "Auxiliary Officer for the 1st Quarter of 2026" (Trooper Ledbetter and Trooper Martin, Troop G), on behalf of Lt. Colonel Danny Barber and the FHP Command.
- **Statutory basis — NOT a flhsmv.gov source, flagged as such:** §321.24, Florida Statutes (per FindLaw / Florida Senate bill analysis) authorizes the FHP director to establish the Auxiliary from volunteers; members serve under the direction and supervision of the director and FHP members; after individual approval by the director and completion of an approved firearms course, auxiliary members, while serving under supervision, "shall have the power to bear arms and make arrests" and have the same protection and immunities as regularly employed highway patrol officers; total auxiliary membership is limited to 5 times the number of regularly employed highway patrol officers authorized by law; no member may be required to serve on any duty without consent; duties are limited to assisting FHP in its regularly constituted duties; an auxiliary officer retiring after a minimum of 20 years' service may be presented with a complete uniform including badge, service handgun if issued, and an ID card marked "RETIRED."
- **Duties and entry (per the Florida Senate's 2007 staff analysis of the Auxiliary, corroborating the FLHSMV description — also not flhsmv.gov):** the FHPA was established in 1957; Auxiliary Troopers assist FHP in daily duties including patrolling streets and highways, providing timely assistance to disabled motorists, participating in vehicle equipment and license checkpoints, operating the FHP Breath Alcohol Testing Unit (BAT mobile), participating in specialized details, and responding to natural disasters and other emergencies. At that time over 400 Auxiliary Troopers served in sworn (auxiliary law enforcement) or non-sworn (support service) roles; in 2006 members volunteered 169,005 hours (average 36 hours/month). Candidates had to make a formal application, pass the Basic Aptitude Test for law enforcement, undergo a physical examination and thorough background investigation, pass a polygraph, be a U.S. citizen, be at least 19, hold a high school diploma/GED, and possess a valid Florida driver's license; training was at a state-approved training center. **Use the FLHSMV Patrol Support description as the authoritative flhsmv.gov fact; treat the Senate figures as dated corroboration only.**

---

## 6. Trooper recognition and the FHP Memorial

### Member Recognition / Trooper of the Year

- **Page:** https://flhsmv.gov/florida-highway-patrol/member-recognition/trooper-of-the-year/ (A to Z: "Awards, FHP Trooper Recognition" → https://www.flhsmv.gov/florida-highway-patrol/member-recognition/)
- The Trooper of the Year award was created in **1965 by the Florida Petroleum Council** (now sponsored by the Florida Petroleum Council / American Petroleum Council) "to recognize Florida Highway Patrol Troopers for the work they do each day to ensure A Safer Florida." It is awarded to a deserving member "for their courage, service, and protection, to ensure the safety and well-being of Floridians and visitors," for acts of heroism or exceptional performance of duties.
- The index page lists winners by year from 2025 back to 1965, with individual pages per year (e.g. 2025, 2024, 2023, 2022, 2021, 2020, 2019 … 1999, 2004, 2011).
  - **2025 Trooper of the Year: Trooper David Kitchen** (Troop G/Jacksonville area). On 14 July 2024 at ~5:45 p.m., the Jacksonville Regional Communications Center broadcast a BOLO for a reckless driver southbound on I-75 in Alachua County; Trooper Kitchen attempted a stop, the suspect fled into Marion County, the pursuit ended after the suspect's vehicle struck multiple victim vehicles; the suspect resisted, gained control of a firearm, and Trooper Kitchen used deadly force, then immediately rendered aid to the suspect.
  - **2022 Trooper of the Year: Trooper Toni Schuck** (Troop J, South Florida CVE) — the fourth female trooper to earn the honor; recognized for stopping a wrong-way driver during the Skyway 10K run; also received the Medal of Valor and was named CVE Member of the Year and Trooper of the Month (March 2022); honored at the 7th annual FHP awards banquet in Orlando, where 64 FHP members were recognized. 1st Runner-up: Trooper Konner Achors (Troop G); 2nd Runner-up: Cpl. Jacob Moore and Trooper Matthew Davis (Troop A). Other 2022 honors: SLED of the Year Erica Reilly; Civilian of the Year Vic Thomas; Criminal Investigator of the Year Tyler Sheinberg; Instructor of the Year Trooper Kevin Brown; CIU Team of the Year Sgt. William Young, Trooper Nathaniel Cabe, and K-9 Kane; Hurd-Smith Award winner Trooper Scott Mills (181 DUI arrests; the award is named after two troopers killed by drunk drivers).
  - **2020 Trooper of the Year: Trooper Horlkins Saget** (recognized by Governor DeSantis and the Cabinet, 21 December 2021); also 2020 Trooper of the Year page profiles Trooper Curtis Vaughn (pursuit of a stolen vehicle/wrong-way driver on US 41, Citrus County, 28 April 2019; PIT maneuver after being shot at).
  - **1999 Trooper of the Year: Trooper Neil P. Moore, Troop K** — lifesaving actions at a traffic crash scene; also received the Medal of Valor, "the Florida Highway Patrol's most distinguished award."
  - **2004 Trooper of the Year: Trooper Sean Brammer** — quick response and CPR that saved a teenage boy's life.
- Other recognition pages: 2022 Duty Officers of the Quarter (SLEDs), and the annual awards banquet.

### FHP Memorial

- **Page:** https://flhsmv.gov/florida-highway-patrol/fhp-memorial/ (A to Z: "Trooper Memorial").
- Lists troopers killed in the line of duty by name and End of Watch date, from Royston E. Walker (8/31/36) and Luther P. Daniel (12/5/41) through the most recent listed: Joseph Bullock (2/5/20), Lazaro R. Febles (8/14/21), Brian J. Pingry (9/18/21), and Zachary Fink (02/02/24). Also lists K-9s: K-9 Beau (9/5/87) and K-9 Major (11/29/90).
- Selected entries: Halley C. Strickland 1/8/54; Edwin J. Gasque 10/26/61; Sherman L. Scott, Jr. 1/3/65; Ronald G. Smith 12/23/73; Charles E. Campbell 11/16/74; Kenneth E. Flynt 1/1/76; Phillip A. Black 2/20/76; Richard D. Howell 8/2/76; Bradley S. Glascock 8/4/77; Elmer C. Barnett, III 2/14/78; Alvin V. Kohler 9/19/78; Robert P. McDermon, Sr. 4/11/81; Robert L. Pruitt 7/13/81; Milan D. Hendrix 6/1/89; James H. Fulford, Jr. 2/1/92; Kimberly A. Hurd 7/16/92; Donald E. Jennings 6/30/95; Saxton R. Jones 5/1/95; Robert G. Smith 7/26/97; James B. Crooks 5/19/98; George A. Brown, III 4/27/04; Darryl L. Haywood 10/2/04; Nicholas G. Sottile 1/12/07.

---

## 7. Public safety programs and campaigns

### School bus safety ("Bus Safety")

- **A to Z:** "Bus Safety" and "School Bus Safety" → the FLHSMV Child Safety / School Bus Safety page (https://www.flhsmv.gov/safety-center/vehicle-consumer-and-child-safety/child-safety/school-bus-safety/ — URL shown in the A to Z JSON).
- "Florida school buses carry precious cargo — our children." In 2022 there were almost 3,000 crashes involving school buses (also: "In 2022, there were a total of 119,903 children ages 0 to 17 involved in a crash in Florida … resulting in 1,220 serious bodily injuries and 156 fatalities").
- **Law:** motorists must stop when approaching a school bus stopped with red lights flashing and STOP arms extended, and remain stopped until the road is clear of children AND the stop arm is withdrawn. All drivers in either direction on a two-way street must stop; on a highway divided by a paved median, all drivers in either direction must stop; the only exception is a raised barrier (e.g. concrete divider) or at least five feet of unpaved space separating the lanes.
- **Penalties doubled as of 1 January 2021** for failing to stop for a school bus and for passing a stopped school bus on the side where children enter and exit.
- Using a wireless communications device in a handheld manner while driving in a designated school crossing, school zone, or active work zone is against the law.
- FLHSMV/FHP run an annual August Child Safety Awareness Month / back-to-school campaign with FDOT, FLDOE, Florida School Boards Association, Florida Sheriffs Association, Florida Police Chiefs' Association and AAA–The Auto Club Group. 2023 FLDOE survey of school bus operators: approximately **11,224 illegal passes** across the state during the 2022–2023 school year. 2024 legislation (HB 0657 / SB 0766) authorized local jurisdictions to operate school zone speed detection systems and school bus passing infraction detection systems.
- Child-restraint law (cited in the same campaign): seat belts/child restraints required for drivers, all front-seat passengers, and all children under 18; children age 5 and under must be in a crash-tested, federally approved child restraint device. "In 2020, nearly 50% of child passengers killed in vehicle crashes in Florida were not wearing any type of restraint — a 127% increase from 2019."

### Arrive Alive, Move Over, and enforcement campaigns

- **Arrive Alive:** FHP's data-driven statewide enforcement campaign "seeking to reduce fatal and serious bodily injury crashes on Florida's roadways," revitalized January 2017 (per the FY 2016–17 Annual Performance Report).
- **Move Over Law:** A to Z entry; FLHSMV/FHP press release 28 October 2026: a trooper was seriously injured after a driver failed to Move Over in an active work zone (SB State Road 429, mile marker 6, Bay Lake, Orange County, 27 October 2026, ~9:12 p.m.); "FHP urges motorists to Move Over to protect those who protect us."
- **"Stuff the Charger" food drive:** FHP's annual holiday food drive with local organizations — non-perishable food donations to feed families in need (press release 2 November 2026).
- **Holiday travel safety:** FLHSMV and FHP "Ask Motorists Not to 'Wing It' and Arrive Alive This Holiday Season" (10 November 2026) — smart driving decisions and vehicle preparedness for Thanksgiving travel.
- **National Pedestrian Safety Month:** FLHSMV and FHP join public safety partners statewide every October (1 October 2026 release).
- **Desk Trooper Program:** drivers in minor crashes on Central Florida Expressway Authority's 125 miles of tolled roads can video-chat with an FHP trooper instead of waiting at the scene; dial \*347 (\*FHP) to reach a dispatcher who assesses eligibility. (Reported in the press coverage linked in search; the \*FHP number itself is the A to Z entry.)
- **"Share the Road" (Cars and Trucks):** CVE works "with the public to educate and raise awareness during statewide campaigns such as 'Share the Road'" (CVE brake-check release).

### Customer Survey (FHP)

- **A to Z:** "Customer Survey (FHP)" and "Survey (Customer) FHP."
- The "Florida Highway Patrol Citizen Survey" link appears in the site-wide header/footer area of flhsmv.gov pages (it is rendered at the top of the FHP Station Locations page and other FHP pages). No dedicated survey page with its own content/questions was retrievable in this study — the survey itself is served as a linked form (FLHSMV's customer-feedback survey is noted in external library guides as using Research.net software, accessed from a drop-down on the FLHSMV homepage). **Gap:** the survey questions, URL, and response mechanism were not verified from a live flhsmv.gov page in this pass; the parent agent should have the live browser open the "Florida Highway Patrol Citizen Survey" link from any FHP page footer to capture it.

---

## 8. Key facts — at a glance

- Established 1939; first academy Bradenton, 40 students; motto Courtesy, Service, Protection; "Florida's Finest"; black-and-tan.
- Authorized: 1,982 sworn + 503 non-sworn = 2,485; patrols 43.2M miles/yr; investigates 176,000+ crashes/yr.
- Director: Colonel Gary L. Howze II (15th Colonel, named 6 April 2023), 850-617-2300; HQ Neil Kirkman Building, 2900 Apalachee Parkway, Tallahassee, FL 32399.
- 12 troops A–L; Troops I and J are Commercial Vehicle Enforcement (north/south).
- Become a trooper: 19+, U.S. citizen, HS diploma/GED, valid license, plus 1 yr law-enforcement experience OR 2 yrs public-contact work OR 2 yrs active military (honorable) OR 30 semester / 45 quarter college hours. Apply at BeATrooper.com / BeATrooper@flhsmv.gov; CJBAT required (FHP does not administer it); PAT with physician-completed medical release; transcripts to MS 49, Tallahassee.
- Pay: $60,000 in academy; $62,400 after graduation; $5,000 bonus if not Florida-certified; +$5,000/yr in Broward, Miami-Dade, Monroe, Palm Beach.
- Academy: ~28–29 weeks (154th BRC: 29 weeks / 770 hours), live-in, room and board provided, paid from day one; TRC 8–9 weeks / 320+ hours for already-certified officers; LRC needs 2+ yrs experience; then 10–14 weeks with an FTO.
- Next classes (per March 2026 release): 156th BRC 14 Sept 2026; 24th TRC 21 Sept 2026.
- CVE: Governor's designated lead agency for commercial vehicle operations; Troops I/J, 12 district/sub-district offices; weight penalty $0.05/lb over legal weight; New Entrant Safety Audits; DataQ; UCC protest to Commercial Motor Vehicle Review Board.
- CIU: felony officers + canine handlers statewide; 2024: $279M+ total contraband seized, 948 arrested, 2,122 felony charges; 2022: $110.4M, 1,025 felony arrests, 5,000+ lbs narcotics, 204 weapons.
- BCII: Chief Investigator is a Major; 6 components; covers organized crime, terrorism, gangs, domestic security, dignitary protection (Lt. Governor transport), critical infrastructure, biometrics; investigates auto/cargo/heavy-equipment theft, identity theft, license/title/odometer fraud.
- Auxiliary: all-volunteer, professionally trained; direct assistance and operational support to FHP; est. 1957 (per Senate analysis); external site fhpa.info / fhpauxiliary.com.
- Trooper of the Year: awarded since 1965 (Florida Petroleum Council); 2025: Trooper David Kitchen; 2022: Trooper Toni Schuck (4th female recipient).
- Memorial: troopers listed from 1936 (Royston E. Walker) to 2024 (Zachary Fink), plus K-9 Beau and K-9 Major.
- School buses: stop for red lights + STOP arm, both directions unless a raised barrier or ≥5 ft unpaved median separates traffic; penalties doubled 1 Jan 2021; ~3,000 school-bus crashes in 2022; ~11,224 illegal passes in 2022–23 school year.
- Contact: FHP HQ 850-617-2300; \*FHP (\*347) from a mobile; CVE 850-617-2280 / compliance (407) 264-3210; recruitment 1-850-617-2315, BeATrooper@flhsmv.gov.

---

## 9. Page list — every URL studied

### Opened directly and read in full
1. https://flhsmv.gov/ — FLHSMV homepage (press releases: Thanksgiving "Arrive Alive" 10 Nov 2026; "Stuff the Charger" food drive 2 Nov 2026; CAAT arrest of most-wanted fugitive 2 Nov 2026; trooper injured in Move Over work-zone crash 28 Oct 2026; multi-state strike force / Operation Saturday Night Fever 2 Oct 2026; National Pedestrian Safety Month 1 Oct 2026).
2. https://flhsmv.gov/a-to-z-guide/ — A to Z Guide (all FHP entries used as the link map for this section).

### Studied via the search index's full-text rendering of the flhsmv.gov page (browser.open returned HTTP 429 for these; content verified against the site's own WordPress JSON copies where available)
3. https://www.flhsmv.gov/florida-highway-patrol/about-fhp/ — About FHP (history, size, specialized areas summary, values).
4. http://www.flhsmv.gov/fhp/History/ — History of the Florida Highway Patrol.
5. https://flhsmv.gov/florida-highway-patrol/troop-boundaries-information/ — Troop Boundaries & Information (director, deputies, regional and troop commanders).
6. https://www.flhsmv.gov/florida-highway-patrol/troop-boundaries-information/troop-g/ — Troop G page.
7. https://www.flhsmv.gov/florida-highway-patrol/troop-boundaries-information/troop-l — Troop L page.
8. https://www.flhsmv.gov/florida-highway-patrol/troop-boundaries-information/troop-b/ — Troop B page (via wp-json pages/3591).
9. https://www.flhsmv.gov/florida-highway-patrol/contact-fhp/fhp-station-locations — FHP Station Locations (also legacy http://www.flhsmv.gov/fhp/misc/fhpstations.htm).
10. https://www.flhsmv.gov/florida-highway-patrol/contact-fhp/office-of-public-affairs/ — Office of Public Affairs / Meet the Team (PAOs by troop).
11. https://www.flhsmv.gov/florida-highway-patrol/specialized-areas/bureau-of-criminal-investigations-and-intelligence-bcii/ — BCII.
12. https://www.flhsmv.gov/florida-highway-patrol/specialized-areas/criminal-interdiction-unit/ — Criminal Interdiction Unit (Contraband Interdiction Program).
13. https://www.flhsmv.gov/florida-highway-patrol/specialized-areas/criminal-interdiction-unit/k-9-cain/ ; /k-9-jewels/ ; /k-9-major/ — CIU K-9 profiles.
14. https://www.flhsmv.gov/florida-highway-patrol/specialized-areas/commercial-vehicle-enforcement — Office of Commercial Vehicle Enforcement (also http://www.flhsmv.gov/fhp/CVE/).
15. http://www.flhsmv.gov/fhp/CVE/ (CVE Office Locations) — CVE office locations, Troops I/J, district offices, contacts.
16. https://www.flhsmv.gov/florida-highway-patrol/commercial-vehicle-enforcement/safety-enforcement/weight-enforcement/ — Weight Enforcement.
17. https://www.flhsmv.gov/florida-highway-patrol/about-fhp/fhp-policy-manual/ — FHP Policy Manual (chapter list).
18. https://www.flhsmv.gov/florida-highway-patrol/specialized-areas/honor-guard/ — Honor Guard; plus /honor-guard-commanders/ and /current-team-leaders/.
19. https://www.flhsmv.gov/florida-highway-patrol/patrol-support/ — Patrol Support (Advisory Council; Auxiliary description).
20. https://flhsmv.gov/florida-highway-patrol/member-recognition/trooper-of-the-year/ — Trooper of the Year index; plus https://www.flhsmv.gov/florida-highway-patrol/member-recognition/ (Member Recognition landing), /2025-trooper-of-the-year/, /2022-trooper-of-the-year/, /2020-trooper-of-the-year/, /2004-trooper-of-the-year/, /1999-trooper-of-the-year/, /2011-trooper-of-the-year/, /2022-duty-officers-of-the-quarter/.
21. https://flhsmv.gov/florida-highway-patrol/fhp-memorial/ — FHP Memorial.
22. https://www.flhsmv.gov/safety-center/vehicle-consumer-and-child-safety/child-safety/school-bus-safety/ — School Bus Safety (A to Z "Bus Safety" / "School Bus Safety" target; content via wp-json pages/1720).
23. https://www.flhsmv.gov/contact-us/ — Contact Us (CVE 850-617-2280; CDL Help Desk; IFTA/IRP Help Desk).
24. https://www.flhsmv.gov/working-at-flhsmv/career-opportunities/ — Career Opportunities (HSMV).
25. https://services.flhsmv.gov/ATS/ATSApplicant/home — FHP Applicant Tracking System (application instructions, CJBAT, PAT, transcripts).

### Linked recruitment site (linked from flhsmv.gov A to Z Guide)
26. https://beatrooper.com/career-opportunities/state-trooper/ — State Trooper (minimum qualifications, benefits, salary).
27. https://beatrooper.com/requirements/ — Requirements (age, education, preference, paid training, starting salary).
28. http://beatrooper.com/ — BeATrooper.com home (A to Z "Career Opportunities (FHP)" and "Beatrooper.com" target).

### FLHSMV press releases on flhsmv.gov used for dated facts
29. https://www.flhsmv.gov/2023/04/06/florida-highway-patrol-names-new-colonel/ — Colonel Gary L. Howze II named 15th Colonel.
30. https://www.flhsmv.gov/2023/03/27/florida-highway-patrol-criminal-interdiction-unit-seized-over-110000000-in-contraband-in-2022/ — CIU 2022 results.
31. https://www.flhsmv.gov/2024/08/01/operation-bite-back-multi-agency-task-force-recovers-over-500000-in-assets-including-narcotics-firearms-and-currency/ — Operation Bite Back.
32. https://www.flhsmv.gov/2023/11/06/multi-agency-strikeforce-nets-over-250k-in-seized-assets-65-felony-charges-and-20-drug-charges-while-hosting-inaugural-b-i-t-e-back-operator-training-with-out-of-state-law-enforcement/ — B.I.T.E. Back totals.
33. https://www.flhsmv.gov/2025/07/18/florida-highway-patrol-celebrates-graduation-of-32-new-recruits/ — 154th BRC + TRC XX graduation (29 weeks / 770 hours; FTO 10–14 weeks).
34. https://www.flhsmv.gov/2026/03/06/florida-highway-patrol-congratulates-the-graduation-of-transitional-recruit-class-xxii/ — TRC XXII; upcoming 156th BRC 14 Sept 2026, 24th TRC 21 Sept 2026.
35. https://www.flhsmv.gov/2023/02/27/skyway-savior-florida-highway-patrol-trooper-toni-schuck-becomes-4th-female-trooper-of-the-year/ — 2022 Trooper of the Year.
36. https://www.flhsmv.gov/2023/04/20/florida-highway-patrol-commercial-vehicle-enforcement-unit-conducts-unannounced-brake-check-inspections-statewide/ — CVE Operation Airbrake.
37. https://www.flhsmv.gov/2024/08/01/flhsmv-promotes-safe-start-to-the-new-school-year-with-awareness-campaign-focused-on-child-safety/ — back-to-school / school bus campaign 2024.
38. https://www.flhsmv.gov/2023/08/01/flhsmv-prioritizes-education-and-awareness-of-child-safety-this-august/ — Child Safety Awareness Month 2023.
39. https://www.flhsmv.gov/2022/12/28/florida-department-of-highway-safety-and-motor-vehicles-highlights-major-accomplishments-of-2022/ — 2022 accomplishments incl. trooper pay increase to $50,000 (now superseded — see §4.2 note).
40. https://flhsmv.gov/pdf/cabinetreports/agencyannualreport2017.pdf — FY 2016–17 Annual Performance Report (Arrive Alive revitalization; CVE DIAP).

### Outside flhsmv.gov — used only where flagged, not as flhsmv.gov facts
- http://www.fhpa.info/ and https://www.fhpauxiliary.com — FHP Auxiliary external sites (linked from the A to Z Guide).
- https://codes.findlaw.com/fl/title-xxiii-motor-vehicles/fl-st-sect-321-24/ and Florida Senate SB 558 (2007) staff analysis — §321.24 F.S. text and Auxiliary history/duties (§5, flagged).

## Gaps / items for a live-browser follow-up
- **Customer Survey (FHP):** the "Florida Highway Patrol Citizen Survey" link is present in FHP page headers/footers, but its destination form/questions were not retrievable in this pass. Open it live from any FHP page.
- **FHP Training Academy page** (fhp-training-academy): content captured via the site's WordPress JSON; a live open would confirm the current class dates and virtual tour link.
- **Auxiliary:** flhsmv.gov itself says little beyond the one-paragraph Patrol Support description; the Auxiliary's own site (fhpa.info / fhpauxiliary.com) holds the join requirements. Not pursued further because it is outside flhsmv.gov.
- **Salary discrepancy:** BeATrooper.com's Requirements page still shows $4,166.67/month for recruits vs $60,000/yr on the State Trooper page; worth a live check of beatrooper.com/requirements.
# Section 16 — News, Safety Campaigns & Press Releases (flhsmv.gov)

Study date: November 23, 2026. All facts below come from flhsmv.gov pages only
(read directly with browser.open, or from the search index's copies of
flhsmv.gov pages where a direct open returned a stale cache or was blocked).
No facts are taken from news outlets, blogs, or other agencies.

## Method and limits

- Homepage read directly: https://flhsmv.gov/ (crawled Nov 21, 2026) — the
  freshest source; its six featured releases are all dated Oct 1 – Nov 10, 2026.
- Press-release archive: https://www.flhsmv.gov/media/press-releases/ — direct
  opens returned stale cached copies (Jan 2026 crawl for page 1; Dec 2025 crawl
  for page 3, "Page 3 of 62"). The search index holds a fresher copy
  ("Page 3 of 66", crawled ~Nov 5, 2026) listing Jan–Mar 2026 releases; that
  fresher listing is used for the Jan–Mar chronology and is marked as such.
- One direct open failed: the Nov 10, 2026 holiday release at
  https://www.flhsmv.gov/2026/11/10/flhsmv-and-fhp-ask-motorists-not-to-wing-it-and-arrive-alive-this-holiday-season/
  returned HTTP 403 (access denied) on Nov 23, 2026. Its facts below come from
  the flhsmv.gov homepage excerpt and the search index's copy of the same
  flhsmv.gov page, not from a live open.
- "Driving Down Fatalities" does not appear as an FLHSMV campaign name anywhere
  in the pages studied; FLHSMV's umbrella initiative is "Arrive Alive"
  (see below). Do not attribute "Driving Down Fatalities" to FLHSMV.
- No 2026 edition was found of: the February hit-and-run ("Stay at the Scene")
  release (latest: Feb 3, 2025), the May Share the Road release (latest:
  May 6, 2025), National Teen Driver Safety Week (latest release: Oct 15,
  2023; teen-drivers page still cites Oct 20–26, 2024), or the Impaired
  Driving Annual Report (latest on site: Jan 31, 2025). Absence from the
  indexed pages is not proof no such release exists; it means none surfaced
  in this study.

## 1. The newsroom

- News hub / Office of Media Communications: https://www.flhsmv.gov/news/
  The Communications Office "develop[s] and execute[s] statewide public
  safety campaigns," manages the department brand and social media, and
  produces press releases. Media inquiries: hsmv-info@flhsmv.gov, 850-617-3102.
  Crash reports: FLHSMV traffic crash portal, $10.00 per report per
  s. 321.23, Florida Statutes; max 10 reports per transaction; $2.00
  convenience fee per transaction; reports may take up to 10 days.
  Crash reports are governed by s. 316.066, Florida Statutes. Victim names
  are not provided in releases.
- Press-release archive: https://www.flhsmv.gov/media/press-releases/
  (66 pages as of the Nov 2026 index copy; 62 pages in the older cached copy).
  Releases are published in English and Spanish.

## 2. 2026 press-release chronology (news, in date order)

### January 7, 2026 — Move Over Month
"FLHSMV Urges Drivers to 'Move Over' to Protect Those Who Protect Us."
January is Move Over Month. Restates the Move Over law (s. 316.126, Florida
Statutes) and the Jan 1, 2025 expansion to any vehicle parked roadside with
hazard lights flashing, emergency flares, or visible emergency signage.
"Violating the Move Over law will result in a fine, fees, and points on your
driving record." (Archive page 3 of 66 listing; also carried on FLHSMV's
GovDelivery bulletin.)

### January 30, 2026 — Driver license exams in English only (RULE CHANGE)
"FLHSMV Announces Driver License Exams to Be Administered in English Only."
"Beginning Friday, February 6th, all driver license knowledge and skills
examinations will be administered exclusively in English. This change applies
to all driver license classifications, including exams administered orally."
"Language translation services will no longer be permitted for knowledge or
skills examinations, and any printed exams in languages other than English
will be removed for use." FLHSMV updated its driver license testing system
statewide to implement the change.
URL: https://www.flhsmv.gov/2026/01/30/flhsmv-announces-driver-license-exams-to-be-administered-in-english-only/

### March 3, 2026 — Never Drive Impaired (March safety campaign)
"FLHSMV and FHP Announce March Safety Campaign to Prevent Impaired Driving
on Florida Roadways." Throughout March, FLHSMV and FHP emphasize the dangers
and consequences of impaired driving. Campaign hub: FLHSMV.gov/impaired.
Executive Director Dave Kerner: "Through the Never Drive Impaired campaign,
we are reminding drivers that safety begins long before they start the car.
Plan ahead, make responsible decisions, and remember that you only have one
life — protect it." The five primary indicators of impairment listed:
slowed reaction time; limited short-term memory functions; decreased
hand-eye coordination; weakened concentration; difficulty perceiving time
and distance.
URL: https://www.flhsmv.gov/2026/03/03/70463/

### March 24, 2026 — Scam alert: counterfeit court notices (see OTR flag, §6)
"FLHSMV Warns Motorists of New Scam Alert." Ongoing fraudulent scheme using
counterfeit court notices falsely claiming to originate from Florida county
courts and related judicial offices, asserting outstanding traffic or toll
violations and demanding immediate payment. The fake notices may include
references to Florida Statutes and fabricated case numbers; threats of
license suspension, registration holds, or default judgment; QR codes
directing recipients to unauthorized payment portals; unsolicited "hearing
dates" or instructions to remit funds immediately. "These communications are
not issued by any Florida court, clerk's office, or state agency."
"REMEMBER: FLHSMV will never contact you via text message demanding payment
or threatening suspension or arrest." Advice: do not click links; do not
share personal or financial information; report to the Federal Trade
Commission and local law enforcement immediately.
URL: https://www.flhsmv.gov/2026/03/24/flhsmv-warns-motorists-of-new-scam-alert
(Release dated March 23, 2026 on the FLHSMV GovDelivery bulletin;
listed March 24, 2026 in the press archive.)

### March 2026 — other archive items (Jan–Mar, from archive page 3 of 66)
- "FHP and U.S. Border Patrol Arrests 15 Criminal Illegal Aliens in
  Targeted Detail"
- "Officer Involved Shooting in Miami-Dade County"
- "Florida Highway Patrol Congratulates the Graduation of Transitional
  Recruit Class XXII"
- "MEDIA ADVISORY — Funeral Service for FHP Trooper Michael Diego"
- "ICYMI: Attorney General James Uthmeier Charges Six in Organized Cargo
  Theft Ring Responsible for 33 Thefts, $7.8 Million in Losses Across Florida"

### April 1, 2026 — Distracted Driving Awareness Month
"Florida Kicks Off Distracted Driving Awareness Month with Statewide Call
for Safer Roads." April is National Distracted Driving Awareness Month;
FLHSMV, FHP and partners urge drivers to "Put It Down and Focus on the
Road." (See campaign page, §3.)
URL: https://www.flhsmv.gov/2026/04/01/florida-kicks-off-distracted-driving-awareness-month-with-statewide-call-for-safer-roads/

### October 1, 2026 — National Pedestrian Safety Month
"FLHSMV Celebrates National Pedestrian Safety Month." Every October FLHSMV
and FHP join public safety partners statewide to recognize National
Pedestrian Safety Month. "Throughout October, your Florida State Troopers
and public safety partners will be reminding both drivers and pedestrians
to stay alert, make safe choices, and do their part to prevent crashes."
Notes increased pedestrian activity, including children, as Halloween
approaches. Points to FLHSMV's Pedestrian Safety webpage for tips.
URL: https://www.flhsmv.gov/2026/10/01/flhsmv-celebrates-national-pedestrian-safety-month/

### October 2, 2026 — Multi-state commercial-vehicle strike force
"Florida Highway Patrol Participates in Multi-State Strike Force Operation."
FHP joins partner agencies in sharing results of Operation Saturday Night
Fever, "a coordinated overnight commercial motor vehicle enforcement
initiative focused on improving roadway [safety]." Described as
"coordinated enforcement across state lines strengthens commercial motor
vehicle safety through overnight operation." (Only the deck/summary was
available in the sources consulted; enforcement totals were not shown.)

### October 27–28, 2026 — Trooper seriously injured, Move Over failure
"Trooper Seriously Injured After Driver Fails to Move Over in Active Work
Zone" (Oct 28, 2026). Crash Tue Oct 27, 2026, ~9:12 p.m., southbound
State Road 429 at mile marker 6, Bay Lake, Orange County. A 2026 Toyota
Tundra in the outside lane approached an active construction zone; a
marked FHP patrol car was stationary with emergency lights activated as
part of a lane-closure operation. "The driver of the Toyota Tundra failed
to move over, despite the visible emergency lights and the active work
zone warnings. The front of the truck collided with the rear of the
Trooper's vehicle." Driver: 53-year-old man from Davenport, transported to
Celebration Hospital with non-life-threatening injuries. Trooper sustained
serious injuries, airlifted to HCA Osceola Regional Medical Hospital,
stable condition. "This crash remains under investigation and charges are
pending." Release restates the Move Over law and the Jan 1, 2025 expansion.
URL: https://www.flhsmv.gov/2026/10/28/trooper-seriously-injured-after-driver-fails-to-move-over-in-active-work-zone/

### November 2, 2026 — Most-wanted fugitive arrested
"FHP Arrests Most Wanted Fugitive Charged in 2024 Crash That Killed Three
Motorists." On Thu Oct 29, 2026, FHP's Criminal Alien Apprehension Team
(CAAT) arrested Jean S. Dorisca, 48, in Boca Raton, wanted in Osceola
County on a felony warrant for three counts of vehicular homicide
stemming from a 2024 crash.

### November 2, 2026 — Stuff the Charger food drive
"FHP Marks the Season of Giving with its 'Stuff the Charger' Food Drive."
Annual drive collecting non-perishable food donations Nov 1–30 at every
FHP troop headquarters statewide, including FLHSMV General Headquarters
in Tallahassee, plus local FHP stations. Items in greatest need: canned
goods (canned meats, vegetables, fruits, soups); dried goods (stuffing,
boxed potatoes, rice, cornbread mix, grits, cereal, oatmeal); other goods
(nuts, peanut butter, evaporated milk, bottled water, broth). Run with
local partner organizations fighting hunger.
Standing page: https://www.flhsmv.gov/news/community-outreach/stuffthecharger/

### November 10, 2026 — Holiday Arrive Alive campaign ("Don't Wing It")
"FLHSMV and FHP Ask Motorists Not to 'Wing It' and Arrive Alive This
Holiday Season." Campaign runs "beginning now through the end of the year,"
educating motorists on impaired driving, hit-and-run awareness, and
vehicle readiness. Executive Director Dave Kerner: "Arriving safely to
your destination is a personal and deliberate choice. Please remember to
buckle up, slow down, and Arrive Alive always because the greatest gift is
making it home safely to the people who matter most." FHP Colonel Gary
Howze: "Never drive impaired. Never drive distracted and Arrive Alive."
Statistics cited (Thanksgiving 2025, five-day Wed–Sun travel period):
7,331 crashes, 45 fatalities; most crashes on the Wednesday before
Thanksgiving, fewest on Thanksgiving Day. November–December 2025: more
than 1,000 crashes involved alcohol, drugs, or both.
URL: https://www.flhsmv.gov/2026/11/10/flhsmv-and-fhp-ask-motorists-not-to-wing-it-and-arrive-alive-this-holiday-season/
(Direct open returned HTTP 403 on Nov 23, 2026; facts from the flhsmv.gov
homepage excerpt and the search index's copy of this flhsmv.gov page.)

## 3. Safety campaigns — the annual calendar and standing pages

FLHSMV runs a monthly public-safety campaign cycle, each with a standing
Safety Center page, press release, and social/print media kits. Confirmed
2026 editions: January Move Over; March Never Drive Impaired; April Put It
Down (distracted driving); October Pedestrian Safety Month; November–
December Safe Holiday Travel / Arrive Alive. Recurring campaigns with no
2026 edition found in this study: February hit-and-run / Stay at the Scene;
May Share the Road; summer travel / 100 Deadly Days of Summer (teen);
National Teen Driver Safety Week (October); Child Safety Month (August).

### Arrive Alive (umbrella initiative)
Page: https://flhsmv.gov/safety-center/arrivealive/
"Arrive Alive is the first statewide data-driven traffic safety initiative
that unifies all of Florida's public safety agencies and partners." FLHSMV
is the state agency responsible for collecting, maintaining and reporting
Florida's official crash, traffic citation and driver & vehicle data; FHP
"leads and implements the state's traffic safety and education initiatives
through participation in numerous national and state education and
enforcement campaigns." "Due to its geography, increasing population and
thriving tourism industry, the state of Florida consistently ranks as one
of the highest traffic fatality states in the nation."

### Move Over, Florida!
Page: https://www.flhsmv.gov/safety-center/driving-safety/move-over/
(read directly, crawled Oct 27, 2026)
- Law: move over a lane for emergency, service, utility, and disabled
  vehicles stopped on the roadside, or slow to 20 mph below the posted
  limit if it is not safe to move over; slow to 5 mph when the posted
  limit is 20 mph or less.
- Expansion: "As of January 1, 2025, Florida's Move Over law has been
  expanded to include any vehicle parked on the side of the road with
  hazard lights flashing, emergency flares, or visible emergency signage.
  Even disabled vehicles or a vehicle with a flat tire is protected under
  the law."
- History: law introduced 1971 (yield to emergency vehicles); added to
  s. 316.126, Florida Statutes, in 2002; utility and sanitation vehicles
  added 2014; road/bridge maintenance and construction vehicles with
  warning lights added 2021 (effective July 2021); disabled vehicles
  added 2024, effective Jan 1, 2025.
- Who violates most: "Statistically the most likely to violate the Move
  Over Act are drivers aged 20-29."
- 2024 data: 205 crashes and more than 17,500 citations for failing to
  move over in Florida. (2022, for comparison: 170 crashes, more than
  14,000 citations.)
- Penalty: "Violating the Move Over law will result in a fine, fees, and
  points on your driving record."
- FLHSMV teaches the Move Over Act to new/young drivers in the driver
  handbook and includes Move Over questions on the driver exam.
- Resources: crash and citation data dashboards, video playlist, audio
  PSAs (15- and 30-second, English and Spanish), social media kit.
- Podcast: 3PointTurn Ep. 5 covers the Move Over law.

### Put It Down: Focus on the Road (distracted driving)
Page: https://www.flhsmv.gov/safety-center/driving-safety/distracted-driving/
(read directly, crawled Oct 22, 2026)
- "Distracted driving is anything that takes your hands off the wheel,
  your eyes off the road or mind off driving." Three types of distraction;
  texting requires all three, "making it one of the most dangerous of
  distracted driving behaviors."
- "Even a focused driver going 50 mph will travel nearly the length of a
  football field before coming to a complete stop."
- Law: "In 2019, the Wireless Communications While Driving law changed
  enforcement of the ban on texting while driving from a secondary offense
  to a primary offense, which allowed law enforcement to stop a vehicle
  solely for using a wireless communications device while driving." Law
  took effect July 1, 2019; warning-only enforcement Oct 1–Dec 31, 2019,
  citations after that. Also "prohibits using a wireless communications
  device in a handheld manner in school and active work zones."
  Statute: s. 316.305, Florida Statutes.
- Historical stat cited in the 2023 campaign release: "53,596 distracted
  crashes resulted in 268 deaths" in the prior year (2022).
- Advice: pull over to a safe location and put the car in Park to text;
  use Do Not Disturb / Driving Focus; FHP uses every traffic stop as a
  "teachable moment" on distracted driving.

### Never Drive Impaired
Page: https://www.flhsmv.gov/safety-center/driving-safety/impaired-driving/
(also http://flhsmv.gov/safety-center/driving-safety/impaired)
- "One in three fatal crashes are the result of impairment" (2025 release).
  "From 2013 to 2023, impaired driving fatalities represented 34.21% of
  total fatalities." "From 2016–2023, drug-impaired drivers caused 128,426
  crashes, killing 8,900 people."
- "In 2024, over 10% of impaired driving crashes occurred in March, making
  it the month with the highest number of impaired driving crashes."
  March also has the highest crash rate of the year overall (St. Patrick's
  Day, Spring Break, Daytona Bike Week).
- Five signs of impairment: slowed reaction time; limited short-term
  memory; decreased hand-eye coordination; weakened concentration;
  difficulty perceiving time and distance.
- Penalties stated on the page: "For any DUI conviction, your driver
  license will be revoked for a minimum of 180 days." "Fines for DUI can
  range from $500 to $5,000 with mandatory DUI school education." DUI
  arrest can mean "expensive fines, license revocation and jail time."
- Campaign history: March 2024 message "Impairment is No Illusion"
  (target ages 18–39; ~9.5 million impressions, 1M+ engagements; press
  release viewed by 14,000+). 2025 message: "Drive Sober or Game Over."
  2026 message: "You Only Have One Life."
- Impaired Driving Annual Report (s. 381.989, Florida Statutes): annual
  report on marijuana/cannabis-related citations and crashes, due January
  31 each year to the Governor, Senate President, and House Speaker.
  Latest on site: January 31, 2025.
- 2024 crash data (By the Numbers): 4,814 alcohol-confirmed crashes,
  271 confirmed fatalities; 450 drug-confirmed crashes, 316 confirmed
  fatalities; 272 drug & alcohol-confirmed crashes, 231 confirmed
  fatalities.

### Pedestrian Safety
Page: https://www.flhsmv.gov/safety-center/driving-safety/pedestrian-safety
(updated ~Oct 2026; crawled 3 days before this study)
- "Pedestrians have the highest fatality rate among all road users in
  Florida."
- 2025: 12,760 pedestrian-related crashes, "an increase for the fifth
  consecutive year." Fatalities and serious bodily injuries (SBIs) "continued
  downward for a third year in a row": 652 fatalities (down from 706 in
  2024) and 1,348 SBIs, "the second lowest total in the last seven years."
- Full table (crashes / fatalities / SBIs): 2019: 9,752 / 735 / 1,526;
  2020: 8,107 / 712 / 1,262; 2021: 9,552 / 847 / 1,450; 2022: 10,160 / 937 /
  1,541; 2023: 10,276 / 779 / 1,431; 2024: 12,223 / 706 / 1,354;
  2025: 12,760 / 652 / 1,348.
- 2025 pattern: top months Dec, Nov, Oct; most crashes on Friday;
  peak time 6 p.m. 2024: 12,223 crashes, "a nearly 19% increase from 2023."
- March, October and December have the most pedestrian crashes; danger
  rises noon–11 p.m., and Friday/Saturday are the most hazardous days
  (2023 release). "85% of pedestrian fatalities occur during the early
  morning, late afternoon, and evening" (2024 release).
- FLHSMV joins NHTSA in recognizing October as National Pedestrian
  Safety Month.

### Share the Road
- Annual May campaign (motorcycles, bicycles, pedestrians, commercial
  motor vehicles). Latest release found: May 6, 2025, "When Sharing the
  Road, We Share Responsibility" — no 2026 edition found.
- 2024 data (May 2025 release): over 200 bicyclists killed, over 950
  seriously injured; over 700 pedestrians killed, over 1,400 seriously
  injured; over 600 motorcyclists killed, over 2,000 seriously injured;
  nearly 70 CMV drivers/passengers killed, 200 seriously injured; all
  other road users in CMV crashes suffered "almost five times as many
  fatalities and over four times as many serious injuries" as CMV
  occupants.
- 2023 data (May 2024 release): CMVs involved in over 47,000 crashes,
  340 deaths, almost 1,000 SBIs; motorcycles: 9,522 crashes, 604 deaths,
  2,123 SBIs; bicycles: 7,129 crashes, 211 deaths, 800+ SBIs;
  pedestrians: 10,000+ crashes, 779 deaths, 1,393 SBIs.
- Bicyclists aged 16 and under are required to wear a helmet.
- Podcast: 3PointTurn Ep. 9 covers Share the Road.

### Hit-and-run / Stay at the Scene
- Annual February campaign. Latest release: Feb 3, 2025, "Should I Stay
  or Should I Go? The Fear Factor Behind Hit-and-Run Crashes" — no 2026
  edition found.
- 2021 data (Feb 2022 release): 108,155 hit-and-run crashes, up 17% vs
  2020; fatalities up 18% (304), SBIs up 20% (1,176). 169 of the 304
  hit-and-run fatalities were pedestrians and 45 were bicyclists (70%).
  2020: 92,263 crashes, 257 fatalities.
- 2020–2022: ~74% of hit-and-run fatalities were vulnerable road users
  (another FLHSMV figure puts it at 83.74%).
- 2024 (By the Numbers): 97,902 hit-and-run crashes, 246 fatalities
  (7.73% of all traffic fatalities).
- The Nov 10, 2026 holiday campaign includes hit-and-run awareness
  messaging.

### Teen driver safety
- Page: https://www.flhsmv.gov/driver-licenses-id-cards/teen-drivers/
  FLHSMV joins NHTSA in recognizing National Teen Driver Safety Week each
  October. Page still cites Oct 20–26, 2024; no 2026 release found.
- 2024 (By the Numbers): 82,447 teen crashes (ages 15–19); 102 teen
  driver fatalities; 38 teen passenger fatalities; 55% of fatal teen
  crashes daytime (6 a.m.–7 p.m.), 45% nighttime (7 p.m.–6 a.m.).
- "100 Deadly Days of Summer" page: as of May 5, 2024, over 205,000
  Florida teens ages 15–19 held a learner's license. Top 2023 teen
  citations: no proof of insurance (8,465); no driver license (8,296);
  learner license violation (8,160); failure to display driver license
  (5,713); obscured/defaced/no tag (4,875).
- Podcast: 3PointTurn Ep. 1 (personal responsibility for new/teen
  drivers).

### Child safety
- Page: https://www.flhsmv.gov/safety-center/driving-safety/child-safety/
  Covers school bus safety, safety belts and child restraints, pedestrian
  safety, car and driveway safety, teen driver safety, plus campaign
  resources and data.
- Hot-car law: leaving a child in a vehicle is a second-degree misdemeanor,
  fine up to $500; if the child is injured, a third-degree felony. Vehicle
  interior can heat up 20 degrees in 10 minutes; a child's body temperature
  rises 3–5x faster than an adult's; heatstroke can occur at 57°F outside.
  Good-Samaritan rescue protected by s. 768.139, Florida Statutes.
- April 10, 2025 release: "State Leaders Raise Awareness About the Dangers
  of Hot Cars" (FLHSMV, DCF, State Surgeon General). No 2026 child-safety
  release found.

### Safe Holiday Travel / Thanksgiving
- Pages: https://www.flhsmv.gov/safety-center/driving-safety/holidaytravel/holiday-safety/
  and .../thanksgiving-holiday-safety/ (updated ~Nov 9, 2026).
  Tips: never drive impaired; limit distractions; slow down (speeding
  kills); allow extra travel time; check tires/vehicle; buckle up every
  passenger. Report intoxicated/aggressive drivers or request help:
  *FHP (*347). Florida speed limit "will never be over 70 mph."
- Thanksgiving week 2024 (Nov 2024 release): 7,308 crashes, 43 fatalities
  over the 5-day period. Thanksgiving week 2025 (Nov 2026 release): 7,331
  crashes, 45 fatalities.
- Campaign resources page includes a social media kit, Safe Holiday Travel
  checklist/videos, and Tow to Go (AAA/Budweiser free rides, 1-855-2-TOW-2-GO).

### Other Safety Center areas noted
- Vehicle Safety hub: https://flhsmv.gov/safety-center/vehicle-safety/
  (Buckle Up Florida; maintaining a road-ready vehicle; recalls; tire
  safety). "Buckle Up Florida, It's the Law!" — a seat-belt ticket "could
  be costly."
- 3PointTurn podcast: https://www.flhsmv.gov/safety-center/podcasts/
  — "A Safer Florida" driver-safety podcast, supplement to the Florida
  Driver License Handbook. Episodes: 1 Personal Responsibility, 2 Driving
  Safety, 3 Arrive Alive, 4 Stay at the Scene, 5 Move Over, 6 Choice vs.
  Consequence, 7 Strange Situations, 8 Safe Holiday Travel, 9 Share the Road.
- Community outreach: https://www.flhsmv.gov/news/community-outreach/
  (includes Stuff the Charger).
- Consumer warnings: phone solicitation warning —
  https://www.flhsmv.gov/safety-center/consumer-education/safety-warnings/phone-solicitation-warning/
  — FHP does not endorse solicitation; troopers are prohibited by law from
  soliciting; questionable calls can be checked with the Division of
  Consumer Services, 800-435-7352.

## 4. Statewide crash/citation statistics cited in news and campaign pages

From FLHSMV "By the Numbers" 2024 (June 2025):
- Total crashes: 702,162; fatal crashes: 2,962; people killed: 3,184.
- FHP worked 167,963 crashes (23.92%); troopers investigated 106,647 of
  381,210 codable crashes (27.98%). Crashes occur most frequently Friday
  at 4 p.m.
- Speeding citations: 741,019. Total citations issued in 2024: over
  3 million; 14,091 commercial-vehicle citations; 5,900 CMV drivers placed
  out of service. (2024 citation numbers preliminary, as of June 2025.)
- Hit-and-run: 97,902 crashes, 246 fatalities. Pedestrian fatalities 701
  (22.02% of all fatalities); motorcycle fatalities 589 (18.50%); bicycle
  fatalities 207 (6.50%); CMV crashes 46,651, 315 fatalities (9.89%).
- Alcohol-confirmed crashes 4,814 (271 fatalities); drug-confirmed 450
  (316 fatalities); drug & alcohol 272 (231 fatalities).
- Teen crashes (15–19): 82,447; 102 teen driver fatalities; 38 teen
  passenger fatalities.

## 5. 2026 law and rule changes announced (summary)

1. Driver license exams in English only — effective February 6, 2026
   (announced Jan 30, 2026). All knowledge and skills exams, all license
   classifications, including oral exams; no interpreters, no non-English
   printed exams. The only 2026 rule change found in the news/campaign
   pages.
2. Move Over law expansion — effective January 1, 2025 (not a 2026 change,
   but the version of the law cited in every 2026 Move Over item): any
   vehicle parked roadside with hazards/flares/emergency signage is
   protected, including disabled vehicles and flat tires. Penalty unchanged
   in 2026 statements: fine, fees, and points (s. 316.126).
3. No 2026 change found in these pages to: traffic-school (Basic Driver
   Improvement) rules, point assessments, fine amounts, or ticket-payment
   deadlines. The Wireless Communications While Driving law (primary
   offense for texting while driving, s. 316.305) dates to July 1, 2019
   and was not changed in 2026 per these pages.

## 6. FLAGS for Git-FED's OTR traffic case

### FLAG 1 — Scam alert directly targets traffic-case drivers (Mar 24, 2026)
FLHSMV's March 24, 2026 release warns of counterfeit court notices
claiming unpaid traffic or toll violations and demanding immediate payment,
with fabricated case numbers, threats of license suspension / registration
holds / default judgment, and QR codes to unauthorized payment portals.
"FLHSMV will never contact you via text message demanding payment or
threatening suspension or arrest." Anyone working a traffic case should
treat any text/QR-code payment demand as fraud, not click links, not share
personal or financial information, and report to the FTC and local law
enforcement. This is a warning, not a law change; it does not alter how a
real OTR case is paid or resolved.

### FLAG 2 — No 2026 change to traffic school, points, fines, or deadlines found
Nothing in the 2026 press releases or safety campaign pages announces a
change to Basic Driver Improvement / traffic school eligibility, point
values, fine schedules, or ticket deadlines. Do not assume any 2026
FLHSMV news item changed OTR case handling. The one 2026 rule change
found (English-only license exams, Feb 6, 2026) concerns license testing,
not traffic citations or OTR cases.

### FLAG 3 — Context, not a change: enforcement posture in 2026 releases
The 2026 releases show heavier holiday enforcement messaging (Arrive Alive
through year-end; FHP "will be on patrol keeping our highways safe this
holiday season") and a Move Over crash that seriously injured a trooper
(Oct 27, 2026, SR 429). Move Over violations still carry "a fine, fees,
and points" per FLHSMV's own 2026 statements. No new penalty amounts
were published in these pages.

## 7. Page list — every URL studied

### Homepage / newsroom (read directly)
1. https://flhsmv.gov/ — homepage; six featured releases Oct 1–Nov 10, 2026
   (read Nov 23, 2026; page crawled Nov 21, 2026)
2. https://www.flhsmv.gov/news/ — Office of Media Communications
   (read directly; crawled Mar 24, 2026)
3. https://www.flhsmv.gov/media/press-releases/ — press-release archive
   (read directly; cached copy crawled Jan 16, 2026, latest item Oct 2, 2025)
4. https://www.flhsmv.gov/media/press-releases/page/2/ — archive p. 2
   (read directly; cached copy crawled Sep 29, 2025, "Page 2 of 62",
   Feb–Mar 2025 items)
5. https://www.flhsmv.gov/media/press-releases/page/3/ — archive p. 3
   (read directly; cached copy crawled Dec 9, 2025, "Page 3 of 62",
   Jan–Feb 2025 items). Fresher index copy ("Page 3 of 66", crawled
   ~Nov 5, 2026) used for Jan–Mar 2026 items:
   https://www.flhsmv.gov/media/press-releases/page/3/?ref=tiempo-latino-1.ghost.io

### 2026 press releases (via flhsmv.gov homepage / search index of flhsmv.gov)
6. https://www.flhsmv.gov/2026/01/30/flhsmv-announces-driver-license-exams-to-be-administered-in-english-only/
7. https://www.flhsmv.gov/2026/03/03/70463/ — March Never Drive Impaired campaign
8. https://www.flhsmv.gov/2026/03/24/flhsmv-warns-motorists-of-new-scam-alert
   (URL confirmed in third-party citation of the FLHSMV release; full text
   also on FLHSMV's GovDelivery bulletin
   https://content.govdelivery.com/accounts/FLHSMV/bulletins/40fa1ec)
9. https://www.flhsmv.gov/2026/04/01/florida-kicks-off-distracted-driving-awareness-month-with-statewide-call-for-safer-roads/
10. https://www.flhsmv.gov/2026/10/01/flhsmv-celebrates-national-pedestrian-safety-month/
11. https://www.flhsmv.gov/2026/10/28/trooper-seriously-injured-after-driver-fails-to-move-over-in-active-work-zone/
12. https://www.flhsmv.gov/2026/11/10/flhsmv-and-fhp-ask-motorists-not-to-wing-it-and-arrive-alive-this-holiday-season/
    (direct open HTTP 403 on Nov 23, 2026; facts from flhsmv.gov homepage
    and search-index copy)
- Nov 2, 2026 releases ("FHP Arrests Most Wanted Fugitive…"; "FHP Marks
  the Season of Giving with its 'Stuff the Charger' Food Drive") and the
  Oct 2, 2026 release ("Florida Highway Patrol Participates in Multi-State
  Strike Force Operation") were read on the flhsmv.gov homepage; their
  dated flhsmv.gov URLs were not returned by the tools and are not
  reproduced here rather than guessed.

### Safety campaign / Safety Center pages (read directly unless noted)
13. https://www.flhsmv.gov/safety-center/driving-safety/move-over/ — Move Over, Florida! (read directly)
14. https://www.flhsmv.gov/safety-center/driving-safety/distracted-driving/ — Put It Down: Focus on the Road (read directly)
15. https://flhsmv.gov/safety-center/arrivealive/ — Arrive Alive (search-index copy)
16. https://www.flhsmv.gov/safety-center/driving-safety/impaired-driving/ — Never Drive Impaired (search-index copy; also http://flhsmv.gov/safety-center/driving-safety/impaired)
17. https://www.flhsmv.gov/safety-center/driving-safety/pedestrian-safety/ — Pedestrian Safety (search-index copy; updated ~Oct 2026)
18. https://www.flhsmv.gov/safety-center/driving-safety/holidaytravel/holiday-safety/ — Holiday Safety (search-index copy)
19. https://www.flhsmv.gov/safety-center/driving-safety/holidaytravel/thanksgiving-holiday-safety/ — Thanksgiving Safety (search-index copy)
20. https://FLHSMV.gov/safety-center/driving-safety/holidaytravel/campaign-resources/ — Safe Holiday Travel campaign resources (search-index copy)
21. http://flhsmv.gov/safety-center/vehicle-safety/ — Vehicle Safety (search-index copy)
22. http://www.flhsmv.gov/safety-center/driving-safety/child-safety/ — Child Safety (search-index copy)
23. https://www.flhsmv.gov/safety-center/child-safety/car-driveway-safety/ — Car and Driveway Safety (search-index copy)
24. https://www.flhsmv.gov/driver-licenses-id-cards/teen-drivers/ — Teen Drivers (search-index copy)
25. https://www.flhsmv.gov/safety-center/driving-safety/safe-summer-travel/100-days-of-summer — 100 Deadly Days of Summer (search-index copy)
26. https://www.flhsmv.gov/safety-center/podcasts/ — 3PointTurn podcast (search-index copy)
27. https://www.flhsmv.gov/news/community-outreach/stuffthecharger/ — Stuff the Charger (search-index copy)
28. https://www.flhsmv.gov/news/community-outreach/ — Community Outreach (search-index copy)
29. https://www.flhsmv.gov/safety-center/consumer-education/safety-warnings/phone-solicitation-warning/ — Phone Solicitation Warning (search-index copy)

### Earlier releases / reports cited for context and statistics
30. https://www.flhsmv.gov/2025/01/02/its-your-move-flhsmv-urges-the-public-to-take-proactive-steps-for-safety-during-januarys-move-over-public-safety-campaign/ (Jan 2025 Move Over)
31. https://FLHSMV.GOV/2025/03/03/impaired-driving-drive-sober-or-game-over/ (Mar 2025 impaired)
32. https://www.flhsmv.gov/2025/04/02/distracted-driving-a-triple-threat/ (Apr 2025 distracted)
33. https://www.flhsmv.gov/2025/05/06/when-sharing-the-road-we-share-responsibility/ (May 2025 Share the Road)
34. https://www.flhsmv.gov/2025/10/02/florida-recognizes-national-pedestrian-safety-month (Oct 2025 pedestrian)
35. https://www.flhsmv.gov/2024/11/12/flhsmv-reminds-you-to-arrive-alive-this-holiday-season/ (Nov 2024 holiday)
36. https://www.flhsmv.gov/2024/11/01/flhsmv-fhp-launch-annual-stuff-the-charger-food-drive-to-help-support-floridians-in-need/ (Nov 2024 Stuff the Charger)
37. https://www.flhsmv.gov/2025/11/10/floridas-stuff-the-charger-campaign-returns-to-help-neighbors-in-need/ (Nov 2025 Stuff the Charger)
38. https://www.flhsmv.gov/2023/04/04/it-all-can-wait-flhsmv-launches-distracted-driving-awareness-campaign/ (Apr 2023 distracted; 53,596 crashes / 268 deaths stat)
39. https://www.flhsmv.gov/2022/02/02/hit-and-run-crashes-on-florida-roads-rise-in-2021-flhsmv-urges-drivers-to-stay-at-the-scene/ (Feb 2022 hit-and-run)
40. https://www.flhsmv.gov/pdf/cabinetreports/ImpairedDrivingEducationCampaign_013125.pdf — Impaired Driving Annual Report, Jan 31, 2025
41. https://www.flhsmv.gov/pdf/opengov/by-the-numbers_feb-24.pdf — By the Numbers 2024 (June 2025)
42. https://www.flhsmv.gov/2020/01/03/when-you-see-flashing-lights-move-over-florida-its-the-law-2/ (Jan 2020 Move Over)
43. https://www.flhsmv.gov/2022/01/03/flhsmv-reminds-florida-drivers-of-move-over-law (Jan 2022 Move Over)
44. https://www.flhsmv.gov/2023/10/02/flhsmv-encourages-floridians-to-take-the-first-step-towards-pedestrian-safety-during-national-pedestrian-safety-month/ (Oct 2023 pedestrian)
45. https://www.flhsmv.gov/2023/10/15/flhsmv-fhp-recognize-national-teen-driver-safety-week-in-florida/ (Oct 2023 teen week)
46. https://www.flhsmv.gov/2022/03/01/flhsmv-public-safety-partners-launch-never-drive-impaired-campaign/ (Mar 2022 impaired; 800 deaths stat)
47. https://flhsmv.gov/2024/05/01/traffic-is-no-ones-jam-share-the-road-and-allow-everyone-to-travel-safely-together/ (May 2024 Share the Road)
48. https://www.flhsmv.gov/2023/11/11/fhp-trooper-hit-by-driver-while-assisting-with-lane-closure-for-active-construction-zone/ (Nov 2023 trooper struck)
# 17 — Medical Review & Driver Fitness (flhsmv.gov)

Study of the Florida Department of Highway Safety and Motor Vehicles (FLHSMV)
Medical Review program, vision standards, hearing standards, unsafe-driver
reporting, re-examination, and resulting license restrictions.
All facts below are taken from flhsmv.gov pages (main site and the
services.flhsmv.gov Driver License Check help pages), as opened or retrieved
2026-11-23. Anything sourced only from a search snippet, or not found on the
pages studied, is flagged as such. No facts from third-party sites are used.

## Summary in brief

- **Mission:** not to keep a person with a medical condition from driving,
  but to assure the condition does not interfere with safe operation of a
  motor vehicle.
- **Reports** may come from any physician, person, or agency; they must be
  based on medical conditions or symptoms, **not on the driver's age**, and
  are confidential under s. 322.126, Florida Statutes.
- **Process:** written notice to the driver → medical information from the
  driver's physician due **within 45 days** → Medical Advisory Board review
  → FLHSMV decision **within 90 days** of receiving all requested medical
  information → written notice of the outcome.
- **Vision (FLHSMV pages):** minimum acuity **20/70** in either eye or both
  eyes together, with or without corrective lenses (if vision cannot be
  improved); if one eye is blind or 20/200 or worse, the other eye must be
  **20/40 or better**. Minimum horizontal field of vision **130 degrees**.
  Below **20/40** in the General Information page = referral to an eye
  specialist; the Vision Standards page puts the Form 72010 trigger at
  **20/50 or worse** in either eye (see "Two referral thresholds" note).
- **Hearing (non-commercial):** a driver who is deaf or cannot hear
  conversation in a normal tone of voice is restricted to driving with an
  outside rearview mirror on the left side of the vehicle, or wearing a
  hearing aid. CDL applicants must hear a whisper and have 20/40 in each eye.
- **Re-examination:** can include the Extended Road Test (ERT) — the regular
  road test given three times in succession, each graded independently.
- **No hardship license** if driving privilege is denied/revoked for medical
  reasons by the Medical Advisory Board.
- **Failure to submit** a required medical or vision report leads to
  revocation of the driving privilege.

## 1. The Medical Review program — mission and scope

Source: Medical Review landing page and the Driver Licenses & ID Cards hub.

- "Do you have a family member or friend whose medical condition may make
  them an unsafe driver? As a concerned citizen, you may see behaviors and
  symptoms of medical conditions that may indicate someone is unsafe to
  drive."
- "The mission of the Medical Review program is not to prevent an individual
  with a medical condition from driving, but to assure the condition does not
  interfere with the safe operation of a motor vehicle."
- "Florida law authorizes any physician, person, or agency to report an
  applicant or licensed driver who may be unsafe to operate a motor vehicle
  due to a medical condition to FLHSMV."
- "These referrals must be based on medical conditions or symptoms that could
  affect safe driving and not the age of the driver."
- FLHSMV receives referrals from "courts, doctors, law enforcement, other
  state agencies, driver license personnel and concerned relatives or
  citizens."
- "Medical Reporting is confidential under section 322.126, Florida Statutes,
  and no legal action can be taken against the person submitting the report."

## 2. When a review is triggered

Source: "The Medical Review Process" (Florida GrandDriver section).

- FLHSMV acts "when the FLHSMV receives notification from a court, doctor,
  law enforcement, another state agency, or a concerned relative or citizen."
- A decision is made whether to initiate a review of the driver.
- "If questionable, an investigation is performed to assure the validity of
  the complaint."
- If a review is necessary, the driver is notified in writing that they are
  under medical review.

No FLHSMV page studied lists a fixed set of qualifying diagnoses as automatic
triggers. The Medical Referral Form (HSMV 72190) lists the conditions a
reporter may check (see §3): seizures, severe cardiac condition, stroke, loss
of consciousness, uncontrollable diabetes, dementia/memory deficits,
psychiatric disturbance, drug/alcohol addiction, severe visual deficit, sleep
disorder, or "other."

## 3. How to report an unsafe driver

Source: "Report An Unsafe Driver" page; Medical Referral Form HSMV 72190
(form content via FLHSMV PDF, retrieved as a search snippet — see page list).

- "Florida law authorizes any physician, person, or agency to report to
  FLHSMV an applicant or licensed driver who may not safely operate a motor
  vehicle due to a medical condition."
- Referrals must be based on medical conditions or symptoms, not age.
- "The report must be made in writing, giving the full name, date of birth,
  address, and a full description of the alleged physical or mental disability
  that could affect the driving ability of any person over 15 years of age."
- "If information is missing or not included it will invalidate the form."
- "The Medical Referral Form (72190 English / 72190 Spanish) should be used
  to report these concerns."
- "Reports will only be used to determine the qualifications of the
  individual to operate a motor vehicle on Florida's highways."
- "Medical reporting is confidential under section 322.126, Florida Statutes,
  and no civil or criminal action may be brought against any physician,
  person, or agency for providing this information."
- The reporter's name and signature are required for the report to be
  investigated (per Form 72190).
- Form 72190 condition checkboxes: Seizures; Severe Cardiac Condition;
  Stroke; Loss of Consciousness; Uncontrollable Diabetes; Dementia/Memory
  Deficits; Psychiatric Disturbance; Drug/Alcohol Addiction; Severe Visual
  Deficit; Sleep Disorder; Other — plus a written explanation of each area
  marked and how the reporter knows the individual.
- Mail the completed form to: Bureau of Motorist Compliance, Medical Review
  Program, Neil Kirkman Building, MS 86, Tallahassee, Florida 32399-0500.
  Telephone: (850) 617-3814. Fax: (850) 617-3944.
- Per the Medical Review FAQ, the medical referral form may be faxed to the
  Medical Review Section at 850-617-3944. No FLHSMV page studied offers an
  online/email submission route for this form.

## 4. What happens after a report — the Medical Review Process

Source: "The Medical Review Process" page and the Medical Review FAQ.

Step by step, as FLHSMV states it:

1. Notification received (court, doctor, law enforcement, another state
   agency, concerned relative or citizen).
2. Decision whether to initiate a review; if questionable, an investigation
   to assure the validity of the complaint.
3. If a review is necessary, the driver is notified **in writing** that they
   are under medical review and "required to provide medical information from
   their physician **within 45 days**."
4. The medical information is forwarded to the **Medical Advisory Board**
   for review and recommendation.
5. Outcomes:
   - "If approved, the driver may be required to take a re-examination
     and/or submit a follow-up medical report as a condition of licensure."
   - "However, if the driver has a medical condition that affects their
     ability to safely operate a motor vehicle and their records indicate
     they pose a risk to public safety, their driving privilege will be
     denied."
6. "Florida law requires that FLHSMV's decision be rendered **within 90
   days of receipt of all requested medical information** from the applicant
   or licensed driver."
7. "Once a decision is made, the applicant or licensed driver is notified in
   writing."
8. Reconsideration: "The driver may, at any time, provide additional or
   updated medical information or a Certified Driver Evaluation by a Certified
   Driver Rehabilitation Specialist for reconsideration by the board."

Additional FAQ facts:

- Outcome notification is in writing.
- **Hardship license:** "Due to safety concerns, a hardship license is not
  an option for individuals that have had their driving privilege denied for
  medical reasons." The driver may at any time submit additional/updated
  medical information or a Certified Driver Evaluation by a Certified Driver
  Rehabilitation Specialist for reconsideration by the Medical Advisory
  Board (MAB).
- **Extensions:** granted on a case-by-case basis; contact the Medical Review
  Section at 850-617-3814 to determine eligibility.
- **Forms:** available online on the FLHSMV forms page; the driver must
  download, print, and complete ALL forms indicated on the letter mailed from
  the Medical Review Section. The letter may require additional information
  beyond the forms.
- **Fax numbers:** Medical Review Section 850-617-3944; Vision Section
  850-617-3936.
- **Vision form follow-up:** the follow-up time frame for a Report of Eye
  Exam is determined by the driver's eye specialist, and the Vision Section
  follows that guidance. Vision-form extensions are case-by-case via the
  Vision Section at 850-617-3810.

## 5. Vision standards

Source: "Vision Standards" page (flhsmv.gov/vision/) and "General
Information" page.

### Minimum standards (Vision Standards page)

- "To acquire a driver's license in the State of Florida, a customer must
  pass a vision test to determine if they meet the mandatory minimum vision
  standards."
- "The minimum visual acuity standard is **20/70 in either eye or both eyes
  together with or without corrective lenses (if vision cannot be
  improved)**. However, if one eye is blind or **20/200 or worse**, the other
  eye must be **20/40 or better**."
- "Applicants who do not meet the required minimum of **130 degrees of
  uninterrupted horizontal field of vision** must submit either a Goldmann
  Kinetic III-4e or equivalent, or a Humphrey Esterman program field chart."
- "Customers are not permitted to use telescopic lenses to meet Florida
  minimum vision requirements regardless of the acuity reading. Customers
  wearing telescopic lenses will be issued a field revocation order for
  'inadequate vision'."
- "Color blindness will not cause any special condition for licensing"
  (General Information page).

### Two referral thresholds on FLHSMV's own pages — note the discrepancy

- General Information page: "Individuals with visual acuity readings
  **below 20/40** are referred to an eye specialist." Vision testing uses "an
  eye machine located on the counter" in all driver license service centers.
- Vision Standards page: "If your visual acuity is **20/50 or worse in
  either eye (with or without corrective lenses)** your eye specialist must
  complete this Form 72010."
- Both statements are quoted verbatim from FLHSMV pages; the study does not
  reconcile them. The 20/40 figure is the in-office screening referral
  threshold; the 20/50 figure is the threshold the Vision Standards page
  attaches to the Report of Eye Exam (Form 72010).

### Vision forms

- **Report of Eye Exam, Form 72010:** "For original licenses, and at the
  time of each renewal license, your eyesight will be tested by the driver
  license examiner designated by the department or by a licensed
  ophthalmologist, optometrist, or physician using FLHSMV Report of Eye Exam
  Form 72010." Trigger per the Vision Standards page: visual acuity 20/50 or
  worse in either eye, with or without corrective lenses. Per "Forms for Older
  Drivers": use Form 72010 "when you have not met minimum Florida vision
  standards, or you are eligible to renew by mail but must provide proof that
  you have met minimum Florida vision standards."
- **Mature Driver Vision Test, Form 72119:** "Drivers over 80 years of age
  must submit FLHSMV Vision Examination Form 72119 when renewing their
  driver license or take the vision test at their local driver license
  office. Form 72119 must be completed by a Florida licensed physician or by
  a licensed physician at a federally established veterans' hospital."
- **Out-of-state doctors:** the Report of Eye Exam (Form 72010) "may be
  completed by an out of state doctor. However, the Mature Vision Form
  (FLHSMV 72119) must be completed by a Florida licensed physician or by a
  licensed physician at a federally established veterans' hospital" (FAQ).
- **Field charts:** Goldmann Kinetic III-4e (or equivalent) or Humphrey
  Esterman program, for applicants below the 130-degree field minimum.

### Drivers 80 and older

- Per the Vision Standards page and "Forms for Older Drivers": drivers over
  80 must submit Form 72119 when renewing, or take the vision test at their
  local driver license office.
- The A-to-Z Guide lists "Renewing – Age 80 & Older – Vision Requirements"
  as its own entry. The FLHSMV pages opened for this section did not state a
  renewal-term length (e.g. six vs. eight years) for drivers 80+, so no term
  length is recorded here as an FLHSMV fact.

## 6. Hearing standards

Source: "General Information" page; "License Classes, Endorsements &
Designations" page.

- **Non-commercial applicants:** "Drivers applying for a license who are
  deaf or cannot hear conversation spoken in a normal tone of voice, are
  restricted to driving with an outside rearview mirror which should be
  mounted on the left side of the vehicle, or wearing of a hearing aid."
- Hearing is a required exam element for Class E and Learner's License
  applicants. A new resident exchanging a valid out-of-state license for a
  Florida license "will be required to pass the vision and hearing tests
  only."
- **Commercial (CDL) Classes A, B, and C:** "Vision – 20/40 in each eye"
  and "Hearing – must hear a whisper."
- **Restriction codes (hearing-related):** Hearing Aid — code K on licenses
  issued before 2019, code 9 on licenses issued on/after 2019; the FLHSMV
  table describes it as a CDL restriction requiring the driver to wear a
  hearing aid during operation. Outside Rearview Mirror — code B before 2019,
  code F from 2019; an outside rearview mirror must be affixed to the left
  side of any vehicle driven by a driver with this restriction.
- **Designation:** "Deaf/Hard of Hearing" is a designation shown on Florida
  driver licenses and ID cards.

Note: no FLHSMV page studied gives a decibel or audiometric threshold for
non-commercial hearing; the stated test is functional (conversation in a
normal tone of voice; whisper for CDL).

## 7. Re-examination requirements

Source: "The Medical Review Process" page; Medical Review FAQ.

- After Medical Advisory Board review, an approved driver "may be required
  to take a re-examination and/or submit a follow-up medical report as a
  condition of licensure."
- **Extended Road Test (ERT):** "The extended road test (ERT) is the regular
  road test given three times in succession. The three road tests are
  considered one exam; however, each test is graded independently, and each
  test must be passed to proceed to the next. It is given to drivers that
  have a medical condition that may affect their ability to drive safely. Due
  to the length of the ERT, subtle loss of physical and/or mental skills
  needed for safe driving can be better identified. This longer observation
  time also allows the tester more time to access fatigue, distraction, and
  weakness caused by continuous and repetitive actions."
- Statutory footing cited on the General Information page includes
  s. 322.221, F.S. (License Examinations) and s. 322.13, F.S. (Examiner and
  Re-examination Authority). The FLHSMV pages studied do not spell out the
  re-examination's other components (knowledge/road-signs/vision retests)
  beyond the ERT description above.

## 8. License restrictions that can result

Source: "License Classes, Endorsements & Designations" page (restriction
table, pre-2019 letter codes → 2019-and-later codes); Vision Standards and
General Information pages.

Restrictions relevant to medical/vision/hearing fitness:

| Restriction (new code / pre-2019 code) | What it requires |
|---|---|
| Corrective Lenses (B / A) | Driver must wear contact lenses or glasses to meet vision requirements. |
| Outside Mirror (F / B) | An outside rearview mirror must be affixed to the left side of any vehicle driven. |
| Hearing Aid (9 / K) | CDL: driver must wear a hearing aid during operation. |
| Medical Alert Bracelet (3 / X) | Driver must wear a medical alert bracelet while operating a motor vehicle. |
| Limited to Daylight Only (G / E) | Driver limited to daylight driving only. |
| No Manual Transmission (4 / F) | Driver restricted from operating a standard transmission vehicle. |
| Power Steering (5 / G) | Driver limited to vehicles with power steering. |
| Directional Signals (6 / I) | Driver may not operate a vehicle without functioning turn signals. |
| Grip on Steering Wheel (7 / J) | Driver limited to a vehicle with a grip or knob affixed to the steering wheel. |
| Left Foot Accelerator (8 / N) | Driver required to use a left foot accelerator. |
| Business Purposes Only (1 / C) | Driving limited to what is necessary to maintain livelihood, including to/from work, necessary on-the-job driving, educational purposes, to/from church, or medical purposes. |
| Limited to Employment (H / D) | Driving limited to/from work and necessary on-the-job driving. |
| Limited Other Restriction (I / S) | Other restriction. |

- Other restrictions in the same table (CDL equipment/passenger limits,
  Probation Interlock) are not medical-fitness restrictions and are listed
  only for completeness in the source table.
- **Designations** (not restrictions) relevant here: Deaf/Hard of Hearing;
  Insulin Dependent ("INSULIN DEP").
- If vision cannot be improved to meet the standards, the Vision Standards
  page states the applicant "will not be issued a driver license or will have
  their driver license revoked" only in the underlying rule text — the
  FLHSMV Vision Standards page itself states the telescopic-lens consequence
  (field revocation order for "inadequate vision") and the minimum standards;
  denial where "records indicate they pose a risk to public safety" is stated
  on the Medical Review Process page (see §4).
- The Driver Licenses & ID Cards hub lists "inadequate vision" among the
  reasons a license might be suspended or revoked, with details on the
  Suspensions & Revocations pages.

## 9. Failure to submit a required report — revocation

Source: services.flhsmv.gov Driver License Check sanction help pages,
retrieved as search snippets (full pages not opened — browser rate-limited
at the end of the study; see page list).

- **Failure to submit a medical report:** "Your driving privilege is due to
  be revoked for not submitting a required medical report" / (after the fact)
  "has been revoked for not submitting a required medical report." Instruction
  given: "Please contact the Medical Review Section at (850) 617-3814 for
  instructions to help us update your record and avoid the revocation" / "...
  to help us update your record and clear the revocation."
- **Failure to submit a vision report:** "Your driving privilege is due to be
  revoked for failure to submit a required vision report. Please provide a
  Report of Eye Exam completed by an eye specialist so we can update your
  record and the revocation can be avoided." Fastest service: take the Report
  of Eye Exam to a local driver license office. To clear within 7–10 days of
  receipt by DHSMV, fax to (850) 617-3917 or mail to DDL-BDI, 2900 Apalachee
  Parkway MS 87, Tallahassee, FL 32399-0570. Include name and driver license
  number. "After 7-10 days, you may verify your record has been updated" via
  the Driver License Check.
- The Suspensions & Revocations hub links to a "Medical or Vision revocations
  or suspensions" page; its URL was not returned in the crawls used for this
  section and the page was not opened (see gaps).

## 10. Related programs (context, not Medical Review itself)

- **Mature Driver** (hub page under Driver Licenses & ID Cards): "With the
  increase in Florida's population growth of drivers over 65, it is important
  to educate them, their caregivers, and medical professionals about the
  resources available for older drivers." FLHSMV "partners with other state
  agencies to promote information for and outreach to mature drivers to help
  them continue to drive safely. There are also resources for those looking
  to make a safe transition from driving."
- **Florida GrandDriver:** the section of the site under which the Medical
  Review Process page and the Forms for Older Drivers page sit.
- **CDL medical certification** is a separate program (federal motor carrier
  rules; self-certification categories; Medical Examiner's Certificate / Med
  Card). It is distinct from the Medical Review program for non-commercial
  drivers and is covered only as a boundary note here.

## 11. Contacts

All from FLHSMV pages studied:

- Medical Review Section: (850) 617-3814; fax (850) 617-3944
- Vision Section: (850) 617-3810; fax (850) 617-3936
- Vision report fax (Driver License Check help page): (850) 617-3917
- Mail (Medical Review): Bureau of Motorist Compliance, Medical Review
  Program, Neil Kirkman Building, MS 86, Tallahassee, FL 32399-0500
- Mail (vision report clearance): DDL-BDI, 2900 Apalachee Parkway MS 87,
  Tallahassee, FL 32399-0570

## 12. Page list — every URL studied

Opened in full with browser.open on 2026-11-23 (crawl dates shown are the
dates the search/crawl index reported for each page):

1. https://www.flhsmv.gov/driver-licenses-id-cards/ — Driver Licenses & ID
   Cards hub. Medical Review teaser + mission statement (quoted §1);
   Suspensions & Revocations teaser naming "inadequate vision" as a
   suspension/revocation cause. Crawled 2026-10-29.
2. https://flhsmv.gov/a-to-z-guide/ — A to Z Guide. Entries relevant here:
   "Bad Driver, Reporting"; "Mature Drivers"; "Medical Card (Commercial
   Driver Licenses)"; "Medical Self-Certification for CDL Holders";
   "Renewing – Age 80 & Older – Vision Requirements"; "Reporting a Bad
   Driver"; "Vision (Driver License)"; "Vision (FHP)". Note: in the text
   retrieved, the M section showed no standalone "Medical Review" line (only
   Mature Drivers / Medical Card / Medical Self-Certification); the Medical
   Review pages themselves exist under /driver-licenses-id-cards/medical-review/.
   Crawled 2026-11-04.
3. https://www.flhsmv.gov/driver-licenses-id-cards/medical-review/ — Medical
   Review landing page. Mission, who may report, not-age-based referrals,
   referral sources, s. 322.126 confidentiality. Crawled 2026-06-16.
4. https://www.flhsmv.gov/driver-licenses-id-cards/medical-review/report-an-unsafe-driver/
   — Report An Unsafe Driver. Written-report requirements, over-15 age floor,
   invalid-if-incomplete rule, Form 72190, confidentiality / no civil or
   criminal action. Crawled 2026-01-15.
5. https://www.flhsmv.gov/driver-licenses-id-cards/florida-granddriver/medical-reporting-medical-review-process/
   — The Medical Review Process. Notification sources, validity
   investigation, written notice, 45-day medical-information deadline,
   Medical Advisory Board, re-examination / follow-up report, denial for
   public-safety risk, 90-day decision rule, written outcome notice,
   reconsideration route. Crawled 2026-01-14.
6. https://www.flhsmv.gov/driver-licenses-id-cards/medical-review/medical-review-frequently-asked-questions/
   — Medical Review FAQ. Fax numbers, extensions, forms online, written
   outcome notice, no hardship license after MAB denial, Extended Road Test
   definition, vision-form follow-up timing, out-of-state doctor rules for
   Forms 72010 vs 72119, Vision Section extension contact. Crawled
   2026-01-05.
7. http://www.flhsmv.gov/vision/ — Vision Standards. 20/70 minimum acuity;
   blind/20/200 eye → other eye 20/40; 20/50-or-worse Form 72010 trigger;
   130-degree field minimum and field-chart types; telescopic lenses banned
   with "inadequate vision" field revocation; Form 72119 for over-80 renewal.
   Crawled 2026-01-05.
8. https://www.flhsmv.gov/driver-licenses-id-cards/general-information —
   General Information. Hearing rule (deaf / cannot hear normal conversation
   → left outside mirror or hearing aid); vision below 20/40 → eye
   specialist referral; color blindness no special condition; vision/hearing
   exams required per class; CDL 20/40-each-eye + must-hear-a-whisper;
   out-of-state exchange = vision and hearing tests only; statutes cited
   include ss. 322.12, 322.221, 322.16, 322.13. Crawled 2025-12-09.
9. https://flhsmv.gov/driver-licenses-id-cards/general-information/license-classes-endorsements-designations/
   — License Classes, Endorsements & Designations. Full restriction table
   (pre-2019 → 2019 codes) including Corrective Lenses, Outside Mirror,
   Hearing Aid (CDL), Medical Alert Bracelet, Daylight Only, and adaptive
   equipment restrictions; Deaf/Hard of Hearing and Insulin Dependent
   designations. Crawled 2026-06-24.
10. https://www.flhsmv.gov/driver-licenses-id-cards/mature-driver/ — Mature
    Driver. Over-65 education/outreach mission, state-agency partnerships,
    safe-transition resources. Crawled 2026-01-16.
11. http://www.flhsmv.gov/driver-licenses-id-cards/florida-granddriver/forms-for-older-drivers/
    — Forms for Older Drivers. Form 72190 (report a driver), Form 72119
    (over-80 renewal vision test), Form 72010 (not met vision standards /
    mail renewal proof). Crawled 2026-01-12.
12. https://www.flhsmv.gov/pdf/forms/72190.pdf — Medical Referral Form HSMV
    72190 (via FLHSMV PDF). Condition checkboxes, reporter signature
    requirement, mailing address/phone/fax. Retrieved as a search snippet,
    not a full page open.

Retrieved as search snippets only (full open blocked by a browser rate limit
at the end of the study — 429 from the browser service; not retried):

13. https://services.flhsmv.gov/DLCheck/SanctionHelpPages/Sanction30Help.aspx
    and /Sanction31Help.aspx — Clearing Revocation, Failure to Submit Medical
    Report (due to be revoked / has been revoked; contact Medical Review
    (850) 617-3814).
14. https://services.flhsmv.gov/DLCheck/SanctionHelpPages/Sanction26Help.aspx
    and /Sanction27Help.aspx — Clearing Revocation, Failure to Submit Vision
    Report (Report of Eye Exam; fax (850) 617-3917; mail DDL-BDI; 7–10 day
    clearance; verify via Driver License Check).
15. https://www.flhsmv.gov/driver-licenses-id-cards/driver-license-suspensions-revocations/
    — Driver License Suspensions and Revocations hub (referenced from the
    Driver Licenses hub; states it links to a "Medical or Vision revocations
    or suspensions" page). Full open attempted at end of study, blocked by
    the same 429 rate limit; its contents are not recorded here beyond the
    search-snippet description.

## 13. Gaps and things NOT established from flhsmv.gov pages studied

- The "Medical or Vision revocations or suspensions" subpage linked from the
  Suspensions & Revocations hub: URL not returned by the crawls and page not
  opened (browser 429 at end of study). Its specific reinstatement steps for
  medical/vision revocations are therefore not recorded here.
- Renewal-term length for drivers 80+ (six vs. eight years): not stated on
  any FLHSMV page opened for this section; not recorded as an FLHSMV fact.
- No FLHSMV page studied gives a decibel/audiometric hearing threshold for
  non-commercial drivers, a list of automatically disqualifying diagnoses, or
  Medical Advisory Board membership numbers — only the functional tests and
  process steps quoted above.
- The 20/40 (General Information) vs. 20/50 (Vision Standards) referral
  figures both appear verbatim on FLHSMV pages; the study records both and
  does not reconcile them.
- CDL medical certification (self-certification categories, Med Card) is a
  separate program and was not studied in depth here.
# Section 18 — FRAUD, IDENTITY THEFT & MISCELLANEOUS (catch-all)

FLHSMV study, worked 2026-11-23. Scope: A-to-Z Guide entries NOT covered by other
sections — About Us, Agency Mission/Vision/Values, Annual Report, Legislation
Summaries, Laws Affecting Traffic and Motor Vehicles, Driver Privacy Protection,
Identity Theft, Driver License Fraud, Driver License/ID Card Tracking, HSMV Related
Links, Contact Information, Americans With Disabilities Act Notice, Grievance
Procedure, Career Opportunities (HSMV), Customer Survey, plus fraud-adjacent
entries found while working (Motor Vehicle Fraud: odometer / title / vehicle
cloning, NMVTIS, BCII, Cyber Security-adjacent 2026 data breach, new 2026 credential).

## Method note — read this first

- Starting point opened in full with `browser.open`: https://flhsmv.gov/a-to-z-guide/
  (crawled 2026-11-04). The full A-to-Z entry list is reproduced in §9.
- Direct `browser.open` also succeeded for exactly two more pages:
  - https://www.flhsmv.gov/safety-center/consumer-education/fraud/
  - https://www.flhsmv.gov/privacy-statement/driver-privacy-protection-act/
- Every other direct `browser.open` attempt in this session returned HTTP 429
  ("exceeded the maximum number of requests allowed within a given time frame",
  upstream, after 3 attempts) — including the Legislation Summaries page, the
  Department Overview page, the Careers page, and the Identity Theft / Driver
  License Fraud sub-page. Those opens were NOT retried.
- All other facts below come from the search index's cached copies of flhsmv.gov
  pages (each search result carries its own "Last Updated / Last Crawl" stamp,
  quoted in the page list in §9). They are flhsmv.gov wording, but NOT live
  re-verified in this session. Anything sourced elsewhere is labelled
  NON-FLHSMV in §8 and must not be counted as an FLHSMV fact.
- No fact in this file was invented. Where a page could not be opened or found,
  that is stated as a gap rather than filled in.

## 1. Identity Theft & Driver License Fraud

### 1.1 Fraud hub — what FLHSMV says

Source: https://www.flhsmv.gov/safety-center/consumer-education/fraud/
(opened directly; crawled 2026-01-16). The hub has exactly two sections:

- **Identity Theft & Driver License Fraud Protection** — "Driver license fraud
  is a crime. Anyone suspected of committing driver license fraud may be charged
  with any of a number of violation of state and/or federal law. Find out more
  about protecting yourself and reporting identity theft and driver license
  fraud." (link: "Read More")
- **Motor Vehicle Fraud Protection** — "FLHSMV is committed to educating
  consumers on safe car-buying practices. Purchasing a vehicle is a major
  investment and many consumers may not be aware of all of the ways they can
  protect themselves against fraudulent dealers or vehicle sales. Consumers
  should do as much research as possible to protect that investment. If it
  seems too good to be true, it probably is." (link: "Read More")

The Identity Theft sub-page is:
https://flhsmv.gov/safety-center/consumer-education/fraud/identity-theft-driver-license-fraud/
— its URL is confirmed by a third-party page quoting it, but the page itself
could NOT be opened in this session (429, see Method note). Its full on-page
content is therefore a GAP, not recorded here.

### 1.2 How to report / get flagged — FLHSMV form and units

- **Form HSMV 72068 — Identity Theft/Driver License Fraud Report Form.**
  Listed on FLHSMV's Forms page
  (https://www.flhsmv.gov/resources/forms/) as "72068: Identity Theft/Driver
  License Fraud Report Form". This is the form for reporting identity theft /
  driver license fraud to FLHSMV.
- **Form HSMV 80122 — Application For Suspected or Reported Title and
  Registration Fraud.** Listed on the same Forms page; used for motor-vehicle
  (title/registration) fraud — see §2.
- **Fraud Analysis Unit** — FLHSMV unit named on the Contact Us page as the
  recipient for disabled-parking-permit misuse/fraud complaints, by mail to:
  Fraud Analysis Unit, 2900 Apalachee Parkway, Rm B360, MS-64, Tallahassee,
  FL 32399.
- **Motor Vehicle Fraud Unit** — separate unit for title/registration fraud,
  §2.3. Do not confuse the two units: Fraud Analysis Unit = driver-license /
  disabled-parking fraud; Motor Vehicle Fraud Unit (Room B361/MS69) =
  title/registration fraud.
- **FHP Bureau of Criminal Investigations and Intelligence (BCII)** —
  https://www.flhsmv.gov/florida-highway-patrol/specialized-areas/bureau-of-criminal-investigations-and-intelligence-bcii/
  — "conducts investigations into auto theft, commercial vehicle and cargo
  theft, heavy equipment theft, identity theft, driver's license fraud, title
  fraud, odometer fraud, and other criminal activity related to [FLHSMV/FHP]
  authorities", working "closely with local, state, and federal partners".
  Led by a Bureau Commander holding the rank of Major; 6 operational
  components, including 2 regionally dispersed Investigative Operations
  Sections (North & South), an Intelligence and Analysis Section, a Strategic
  Operations Unit, a Case Management and Investigative Coordination Unit, and
  the Executive Transportation Section. Its Investigative Management and
  Coordination Unit (Tallahassee) is the central repository for all BCII case
  files and records.

### 1.3 Protect-your-identity tips (FLHSMV wording, via indexed copy)

FLHSMV's "Protect Your Identity" tips, as carried on FLHSMV pages and quoted
in the search index:

- Destroy (shred) all old licenses and identification cards once you renew and
  receive your replacements.
- Driving record — every year purchase a copy of your driving record to review
  for tickets not issued to you.
- Mailbox — do not leave mail in mailbox overnight and/or stop your mail when
  away from home.
- Secure important documents — when not needed lock up extra credit cards,
  social security card and passport.
- New checks — pick up at bank rather than having them mailed.
- Paid bills — do not leave paid bills in mailbox, instead drop off at post
  office.
- Social Security number — do not give it out when asked; inform merchants
  you want to use other identity.
- Shred paperwork with personal information and financial information before
  putting it in the garbage.
- Report a stolen Florida driver license to local law enforcement; a copy of
  the police report can get the replacement fee waived (per FLHSMV guidance
  quoted on third-party pages — see §8).

## 2. Motor Vehicle Fraud (odometer, title, vehicle cloning)

Source hub: https://www.flhsmv.gov/safety-center/consumer-education/fraud/motor-vehicle-fraud/

### 2.1 Three main types

FLHSMV names three main types of motor vehicle fraud:

1. **Odometer fraud** — changing or altering the mileage reading on a vehicle
   to falsely reflect lower mileage.
2. **Title fraud** — altering a vehicle title to misrepresent the true
   condition of a vehicle, or providing false information to obtain a vehicle
   title.
3. **Vehicle cloning** — an elaborate scheme involving stolen vehicle
   identification numbers, counterfeit VIN tags and fraudulent documents.

### 2.2 Odometer fraud

Source: https://www.flhsmv.gov/safety-center/consumer-education/fraud/motor-vehicle-fraud/odometer-fraud-warning/

- "Verify Before You Buy": before purchasing a pre-owned vehicle, visit the
  FLHSMV Motor Vehicle Information Check and verify the odometer reading.
- Penalties: it is a felony to tamper with, adjust, alter, set back,
  disconnect, or fail to connect the odometer of a motor vehicle to reflect a
  lower mileage than the vehicle has actually been driven. It is also illegal
  to knowingly provide a falsified odometer statement. When these laws are
  violated, title fraud and grand theft, both felonies, are also added to the
  list of arrest charges. "These violations each carry a fine as much as
  $5,000 and/or five years in prison."
- Impact (NHTSA estimate quoted by FLHSMV): more than 450,000 vehicles are
  sold each year with false odometer readings, costing U.S. vehicle buyers
  over $1 billion in increased costs. Further loss to the consumer may
  include increased sales tax (inflated sales price), increased insurance cost
  (lower mileage), increased maintenance/repair costs, and decreased vehicle
  safety.
- Prevention tips: look for wear on brake/gas pedal pads or recent replacement
  of the pads; loose screws around the dashboard; wear and tear on seats, or
  new seat cover installation (a low-mileage vehicle should not have excessive
  wear); if the car has less than 20,000 miles, it should not have a
  replacement set of tires; ask to see maintenance records and the original
  owner manual; consider having the vehicle inspected by a reputable mechanic
  of your choosing.
- Reporting: if you have fallen victim to odometer fraud, or have information
  on an operation/incident where odometer fraud is being committed, complete
  form HSMV 80122 (Suspected or Reported Title and Registration Fraud) and
  mail, fax or email it with all supporting documents to the Motor Vehicle
  Fraud Unit (§2.3).

### 2.3 Title fraud

Source: https://www.flhsmv.gov/safety-center/consumer-education/fraud/motor-vehicle-fraud/title-fraud/

- "Title fraud occurs when a person alters a vehicle title to misrepresent
  the true condition of a vehicle or provides false information to obtain a
  vehicle title, including forgery."
- "Consumers should never keep their title in the vehicle."
- Before purchasing: if the title is paper, check for signs of tampering
  including erasure marks or misspellings; if electronic, visit the FLHSMV
  Motor Vehicle Information Check; compare the VIN on the vehicle to the VIN
  on the title — they must match; verify the seller's information on their
  driver license or ID card to ensure it matches the name on the title.
- Reporting: complete form HSMV 80122, Suspected or Reported Title and
  Registration Fraud. Mail, fax or email the completed form and all supporting
  documents to: Motorist Services Support, Motor Vehicle Fraud Unit,
  Room B361/MS69, Neil Kirkman Building, Tallahassee, FL 32399;
  Phone: 850-617-2907; Fax: 850-617-3952; Email: dmv-enforcement@flhsmv.gov.

### 2.4 Vehicle cloning

Source: https://www.flhsmv.gov/safety-center/consumer-education/fraud/motor-vehicle-fraud/vehicle-cloning/

- "Vehicle cloning is an elaborate scheme involving stolen vehicle
  identification numbers (VIN), counterfeit VIN tags and fraudulent
  documents."
- Impact: if you buy a cloned vehicle and its true pedigree is discovered,
  the car will be confiscated, leaving you responsible for any outstanding
  loans.
- NMVTIS: the National Motor Vehicle Title Information System, a U.S.
  Department of Justice database, links state motor vehicle departments
  together; when a vehicle title is applied for, the database should alert
  motor vehicle offices that the number is already in use.
- Tips: verify the vehicle VIN through the department's Motor Vehicle
  Information Check; analyze the ownership pattern for any new or late model
  vehicle with no lien holder; get a copy of the vehicle's history report;
  check the VIN plate on the dashboard for evidence of tampering including
  scratches or other damage; look for incorrect spellings on paperwork like
  vehicle titles; trust your instincts — if the deal sounds too good to be
  true, walk away; beware a car sold for substantially less than comparable
  makes and models.
- If you have reason to believe your vehicle was cloned, contact local law
  enforcement or file a complaint with the local FLHSMV Regional Office using
  the Complaint Affidavit on the FLHSMV website.
- NMVTIS page: https://www.flhsmv.gov/motor-vehicles-tags-titles/liens-and-titles/nmvtis/
  — AAMVA advocates uniform standards through NMVTIS; it is designed to
  protect consumers from fraud and unsafe vehicles and to keep stolen vehicles
  from being resold. Legal basis quoted: Anti Car Theft Act of 1992 (Title II
  required DOT to implement NMVTIS) and Anti Car Theft Improvements Act of
  1996 (signed July 2, 1996). NMVTIS information is available to
  jurisdictions; federal, state and local law enforcement; insurance carriers;
  and other prospective purchasers (individuals, auction companies, used car
  dealers).

### 2.5 Enforcement example (FLHSMV news, Dec 1, 2023)

- "Former Car Dealer Arrested After Traffic Stop Reveals Two Stolen Cadillac
  Escalades" (FLHSMV, December 1, 2023): FHP troopers on I-75 in Sumter
  County stopped a 2018 Cadillac Escalade for excessive speed and a tag
  violation; VINs had been tampered with/swapped/cloned to reflect a 2020
  Escalade; the vehicle was stolen from Pennsylvania; a second Escalade
  (2022, stolen from Clearwater, FL, June 2023) was found "re-vinned" at the
  driver's closed Tampa dealership (Champa Bay Auto Brokers, first licensed
  April 2022, closed April 2023). Driver Yajaira Martinez, 39, of Riverview,
  arrested on Grand Theft of a Motor Vehicle (1 count, felony, F.S.S.
  812.014.2c6) and Possess Vehicle with Altered Numbers (1 count, felony,
  F.S.S. 319.33.1d).

## 3. September 2026 data breach — the biggest 2026 fraud/identity item on flhsmv.gov

This is the single most important 2026 finding in this section. Two FLHSMV
pages, plus FLHSMV's own substitute notice:

- FAQ page: https://www.flhsmv.gov/data-breach/
- Statement: https://www.flhsmv.gov/2026/09/11/flhsmv-releases-statement-on-data-breach/
  ("FLHSMV Releases Statement on Data Breach", September 11, 2026)

Facts, in FLHSMV's words:

- "On September 4, 2026, FLHSMV learned of a data breach conducted by an
  international cybercriminal organization. The Department promptly mitigated
  the breach, launched an investigation, and issued required notification to
  state authorities."
- Cause: "A criminal actor gained unauthorized access to a department system.
  The access was acquired using the credentials from an employee of a local
  Florida law enforcement agency, who improperly stored the credentials on an
  electronic device." The September 11 statement specifies: "a single Plant
  City Police Department user's credentials that were improperly housed on the
  employee's personal electronic device."
- Status: "The data breach was quickly mitigated and no further breach has
  occurred or is ongoing." / "There is no evidence of ongoing unauthorized
  access."
- Data potentially affected: "driver license and motor vehicle data, to include
  document images, and other personal information." The FAQ: "driver licenses
  data, motor-vehicle information, document images, and other personal
  information may have been accessed."
- Misuse: "At this time, FLHSMV has no evidence indicating that information
  has been misused." / "Based on the current investigation, the Department has
  no evidence that any information has been misused."
- Notification: FLHSMV sent letters to current driver license / ID card
  holders potentially impacted, and issued a substitute notice under Section
  501.171, F.S., because it may not have current mailing addresses for
  impacted customers who no longer hold a valid Florida driver license or ID
  card or who previously had a vehicle titled in Florida. Required notice of
  the security breach was also provided to the Office of the Attorney General
  pursuant to section 501.171, F.S.
- Remedy offered: FLHSMV "partnered with Sontiq, Inc., a TransUnion company,
  to offer complimentary identity and credit monitoring services and $1 million
  identity theft insurance for 1 year" to impacted individuals (FAQ: "one year
  of complimentary credit monitoring services to the individuals impacted").
- Investigation partners: Florida Digital Service and Florida Department of Law
  Enforcement; "an ongoing criminal investigation" — "Information in this FAQ
  may be updated as additional facts become available."
- FLHSMV-recommended precautions: review account statements and credit
  reports for suspicious activity; monitor financial and online accounts;
  consider placing a fraud alert or security freeze with major credit bureaus;
  use FTC resources at https://www.identitytheft.gov/databreach; free credit
  report from each nationwide consumer-reporting agency via
  http://www.AnnualCreditReport.com or 1-877-322-8228.
- Credit bureau numbers given in the notice: Equifax 800-525-6285; Experian
  888-397-3742; TransUnion 800-680-7289.
- Breach contact: Email customerinquiry@flhsmv.gov; Website and FAQs:
  FLHSMV.gov/DataBreach; FLHSMV Office of Communications: HSMV-INFO@FLHSMV.GOV.

## 4. Driver Privacy Protection (DPPA)

Source: https://www.flhsmv.gov/privacy-statement/driver-privacy-protection-act/
(opened directly; crawled 2026-07-25).

- "Under Florida law, motor vehicle, driver license and vehicular crash record
  information are public information. The Driver Privacy Protection Act,
  18 United States Code, Section 2721, keeps your personal information private
  by limiting those who can have it."
- "The department automatically blocks personal information in all motor
  vehicle and driver license records that we maintain. You do not need to do
  anything to have your personal information protected."
- Personal information covered by DPPA: social security number, driver license
  or identification card number, name, address, telephone number, and medical
  or disability information in motor vehicle / driver license records.
  Additionally, emergency contact information and email addresses are
  restricted pursuant to Section 119.0712(2), Florida Statutes.
- Information NOT covered by DPPA (public): non-personal information such as
  vehicular crash records, driving violations and driver status information.
  (Corroborated on the Questions About Driving Records page: "Personal
  information protected by DPPA does not include date of birth, driving
  violations, and driver status.")
- Getting your own record's personal information: fully complete, sign and
  mail the request form to the address on the form — driver record request:
  Form 90511; motor vehicle record request: Form 90510.
- Getting someone else's personal information: only if you meet an exemption
  covered by law; exemptions are listed on the request forms; include the
  appropriate exemption in the space provided on the form.
- Who can access your personal information: law enforcement agencies (to carry
  out their functions); plus other individuals/companies that meet an
  exemption, e.g. auto manufacturers (recalling vehicles/parts); government
  agencies or private companies (to verify accuracy of personal information);
  towing companies (to notify owners of towed/impounded vehicles); companies
  like bus lines verifying information on their commercial drivers; any person
  or agency you have given written permission.
- Statutes cited on the page: Florida Statute 119.0712(2); Federal Statute
  18 USC 2721.
- Related FLHSMV page: Record Production Fact Sheet,
  https://www.flhsmv.gov/privacy-statement/record-production-fact-sheet/ —
  FLHSMV "does not allow data to be distributed through its MOUs" for bulk
  distribution for surveys/marketing/solicitations (federal DPPA exemption 12),
  a more stringent policy than the federal minimum; "Unless explicitly
  permitted by law, requesting parties never receive highly restricted personal
  information including an individual's photo, social security number, medical
  or disability information"; produced records cannot be used for marketing;
  every requesting party must submit the DPPA exemption it relies on and
  individually certify or enter into a Memorandum of Understanding (MOU);
  an independent third-party audit is required on or before the first
  anniversary of an MOU, plus Annual Certification Statements in years 2-3.
- High-risk block: Florida Statute 119 allows certain individuals in sworn or
  high-risk positions (e.g. law enforcement officers, judges, other public
  officials) to have their address and date of birth blocked, making this
  information exempt from DPPA upon request using form 96020.
- GoRenew warning (services.flhsmv.gov): personal information on that site is
  protected by 18 U.S.C. 2721-2725 et seq. (DPPA) and Section 119.0712(2), F.S.;
  accessing personal information for anyone other than yourself without
  specific written permission may subject you to criminal prosecution or civil
  liability.

## 5. About the agency — About Us / Mission / Vision / Values

Source: https://flhsmv.gov/about/department-overview/ (could NOT be opened
directly in this session — 429; facts below from the search-indexed copy,
last crawl 80 days before 2026-11-23).

- **Mission:** "Providing Highway Safety and Security through excellence in
  service, education and enforcement." (Rendered on the overview page as
  "Our mission is to provide highway safety and security through excellence
  in service, education and enforcement.")
- **Vision:** "A Safer Florida"
- **Values:** SERVICE by exceeding expectations; INTEGRITY by upholding the
  highest ethical standards; COURTESY by treating everyone with dignity and
  respect; PROFESSIONALISM by inspiring confidence and trust; INNOVATION by
  fostering creativity; and EXCELLENCE IN ALL WE DO!
- Core mission execution: "the issuance of driver licenses, vehicle tags, and
  titles and the operation of the Florida Highway Patrol" (FLHSMV boilerplate
  on press releases).
- Scale (2022 FLHSMV release): "FLHSMV's more than 4,000 members serve in
  all of Florida's 67 counties". 2019 release: "more than 20 million Florida
  residents and over 120 million annual visitors".
- Department Overview page sections: Department Goals and Organization
  (Agency Goals; Organization Chart; Statement of Agency Organization and
  Operation), plus links to Notice Under the ADA and Open Government/Public
  Records.
- Executive Director: Dave Kerner (named as FLHSMV Executive Director on
  the Resources page, https://www.flhsmv.gov/resources/, and in 2023 press
  releases, e.g. the July 5, 2023 SB 1718 release: "FLHSMV and its division of
  the Florida Highway Patrol are prepared to strictly enforce Senate Bill
  1718," said Executive Director Dave Kerner).
- Social: Facebook https://www.facebook.com/FLHSMV/, X https://x.com/FLHSMV,
  Instagram https://www.instagram.com/flhsmv/,
  YouTube https://www.youtube.com/c/flhsmvgovasaferflorida.
- 50th anniversary: "This year, the FLHSMV celebrates its 50th anniversary
  and its Division of the Florida Highway Patrol (FHP) commemorates its 80th
  year" (2019 release — i.e. FLHSMV founded 1969, FHP 1939).

## 6. Legislation Summaries & Laws Affecting Traffic and Motor Vehicles

### 6.1 The Legislation Summaries page — STALE, no 2026 summary found

- Page: https://www.flhsmv.gov/resources/cabinet-and-legislature-reports/legislation-affecting-traffic-and-motor-vehicle-laws/
  (A-to-Z also gives the variant
  https://www.flhsmv.gov/resource-center/cabinet-and-legislature-reports/legislation-affecting-traffic-and-motor-vehicle-laws/)
- Page text: "The following is a summary of legislative changes related to
  traffic and motor vehicle laws that were enacted during the Legislative
  Sessions." Complete copies of bills may be obtained from the Department of
  State, the distribution offices of the Florida House and Senate, independent
  reporting agencies, or the Florida Legislature website (www.leg.state.fl.us).
- **Year table on the page runs 2022, 2021, 2020, 2019, 2018, 2017, 2016,
  2015, 2014, 2013, 2012, 2011, 2010, 2009, 2008, 2007, 2006, 2005, 2004,
  2003, 2002, 2001 — NO 2023, 2024, 2025 or 2026 entry is listed.** The search
  result for the page was "Last Updated: 1817 days ago" (i.e. circa late 2021).
  The page could NOT be opened directly in this session (429), so this is
  from the indexed copy — but the year list is explicit in that copy.
- Consequence: **FLHSMV publishes no 2026 legislation summary on this page
  as indexed.** Any 2026 law change must be found elsewhere on flhsmv.gov
  (press releases, handbooks, Appendix C) — see §6.2 and the OTR flag in §7.

### 6.2 Law changes that ARE visible on flhsmv.gov (2024–2026, relevant to drivers)

These are not from a legislation-summary page; each is stated on another
FLHSMV page. Statute numbers are FLHSMV's own citations.

- **Traffic school elections — lifetime cap (effective July 1, 2024).**
  Florida Statute 318.14(9): "a person may make no more than five traffic
  school elections within their lifetime and once in a twelve-month period."
  For Florida violations only; election made through the Florida court in the
  county where the citation was received. Florida CDL holders are NOT eligible
  to elect driver improvement school to avoid points, regardless of whether
  the violation was committed in a commercial motor vehicle. Source: Questions
  About Driving Records page,
  https://flhsmv.gov/driver-licenses-id-cards/general-information/questions-about-driving-records/
  (also repeated on the BDI page).
- **Basic Driver Improvement (BDI) election mechanics.**
  Source: http://www.flhsmv.gov/ddl/bdis.html — to qualify for BDI to eliminate
  points, drivers must VOLUNTARILY elect within 30 days (s. 318.14(4), F.S.)
  from the citation date and, prior to attending the course, inform the clerk
  of court in the county where the citation was issued. Drivers may NOT elect
  BDI in lieu of points after the initial 30-day period. Options for satisfying
  a citation are listed on the back of the citation; drivers must choose one
  of the three options within 30 days of the citation date. If a driver elects
  and completes BDI: points may not be added, adjudication of guilt is
  withheld, civil penalty (fine) is reduced, and insurers cannot impose/request
  an additional premium, cancel a policy, or issue a non-renewal notice solely
  because of the infraction (unless it involved a crash where the insurer was
  at fault and incurred a loss). BDI is mandatory when cited for certain
  reasons (list truncated in indexed copy). Source: Driver Improvement Courses
  FAQ, http://www.flhsmv.gov/ddl/dicfaqa.html — once the clerk is notified of
  intent, the driver has between 60 and 90 days from the citation date to
  complete the course and present proof of completion to the clerk. Failure to
  attend within the time specified = admitted to the infraction, adjudicated
  guilty, must pay the clerk the amount deducted because of the election plus a
  processing fee of up to $18; the clerk notifies DHSMV and points are added.
  Note a conflict in FLHSMV's own indexed text: the BDI page/FAQ variously
  says "no more than eight times in a lifetime" (older FAQ text) while the
  Driving Records page says "no more than five traffic school elections within
  their lifetime" effective July 1, 2024 under 318.14(9). The 5-lifetime figure
  is the newer, statute-dated one; the 8-times figure appears to be superseded
  text still on the older FAQ page. Flagged, not resolved.
- **Point system (FLHSMV BDI page).** Points assessed for moving violations
  where adjudication of guilt is found; suspension at 12 points within 12
  months, 18 points within 18 months, or 24 points within 36 months. Schedule
  quoted: moving violations 3 points; speeding 15 mph or less over posted
  speed 3 points; speeding more than 15 mph over posted speeds 4 points. Any
  driver under 18 who accumulates 6+ points within 12 months is automatically
  restricted to "Business Purposes Only" for one year; each additional point
  extends the restriction by 90 days.
- **Record retention (Driving Records page).** Citation dispositions of guilty
  — most non-moving/moving violations 3- to 5-year retention; more serious
  violations 10 years, 15 years, etc. depending on severity. Adjudication
  withheld — clerk of court (school elections) retained 75 years (only up to
  5 in a lifetime); compliances 75 years (only up to 3 in a lifetime), per
  ss. 318.14(9) and (10), F.S.
- **Speeding >30 mph over: no traffic school election.** Appendix C (Uniform
  Traffic Citation), revised 9-2-2025:
  https://www.flhsmv.gov/pdf/courts/utc/APPENDIX_C_Rev%209-2-2025.pdf —
  "Drivers charged with exceeding posted speed limit by more than 30 mph will
  not be permitted to elect traffic school [see 318.14(9)]". Also: "Any moving
  violation with points, excluding speeding, resulting in a crash = 4 points";
  infractions resulting in a crash causing death of another — $1,000 fine,
  6 months suspension; causing serious injury — $500 fine, 3 month suspension.
  Appendix C also carries the note "*NOTE* Repealed July 1, 2025 per Senate
  Bill 1662" against one listed statute (the statute number is not legible in
  the indexed copy — do not cite it as a specific repeal without checking the
  PDF).
- **Move Over law expanded (effective January 1, 2025).** FLHSMV press
  release Oct 28, 2026: "As of January 1, 2025, Florida's Move Over law has
  been expanded to include any vehicle parked on the side of the road with
  hazard lights flashing, emergency flares, or visible emergency signage. Even
  disabled vehicles or a vehicle with a flat tire is protected." Vehicles must
  move over a lane for emergency, service, utility and disabled vehicles, or
  slow to 20 mph below the posted limit if not safe to move over. Violation =
  fine, fees, and points. In 2025 there were 215 crashes and more than 17,300
  citations for failing to move over. Statute: s. 316.126, F.S.
- **Pedestrian failure to yield (Oct 1, 2026 release).** "If motorists fail to
  yield, they face a minimum citation of $164 and three points on their driver
  license — it is the law."
- **School bus passing (FLHSMV School Bus Safety page).** As of January 1,
  2021, penalties for failing to stop for / passing a stopped school bus
  doubled: moving violation; mandatory basic Driver Improvement Course upon
  conviction; 4 points; minimum fine $265, or $465 if passing on the side
  where children enter and exit. Cameron Mayhew Act (July 1, 2017): passing a
  stopped school bus causing serious bodily injury or death — 120 hours
  community service in a trauma center/hospital; victim impact panel or
  FLHSMV-approved driver improvement course; 6 points; license suspension
  minimum 1 year; $1,500 fine.
- **New credential design (2026).** See §6.3.
- **Driver license / ID card numbers (2024 legislation).** FLHSMV, July 19,
  2024: on July 31, 2024 FLHSMV began implementing legislation amending
  Florida Statute 322.14(1)(a), requiring the distinguishing numbers assigned
  to a driver license or ID card to include at least four randomly generated
  numbers.
- **Invalid out-of-state licenses (SB 1718, effective July 1, 2023).**
  Governor DeSantis / FLHSMV, July 5, 2023: driver licenses issued exclusively
  to undocumented immigrants in other states are invalid in Florida as of
  July 1, 2023, per SB 1718; FLHSMV published a list of invalid out-of-state
  license classes; the bill also prohibits issuance of a driver license to
  anyone who does not provide proof of lawful presence in the U.S.

### 6.3 New 2026 driver license / ID card design (fraud-protection angle)

- Press release Sept 29, 2026:
  https://www.flhsmv.gov/2026/09/29/florida-launches-newly-designed-driver-licenses-and-identification-cards/
  and page https://www.flhsmv.gov/driver-licenses-id-cards/newdl/
- Beginning Wednesday, September 30, 2026, FLHSMV began issuing a newly
  designed Florida driver license and ID card; announced by Governor Ron
  DeSantis at a Florida Cabinet meeting. Available at service centers statewide
  Sept 30; available for online orders through MyDMVPortal.flhsmv.gov by early
  November 2026 (the newdl page later says "by the end of November 2026" for
  online renewals — two dates appear on FLHSMV pages; both are recorded).
- Residents are NOT required to replace existing credentials; currently valid
  credentials remain valid until they expire and will be phased out over time.
- Design: front background Castillo de San Marcos (St. Augustine, oldest
  masonry fortress in the continental U.S.); Florida's orange as the "O" in
  "Florida"; manatee bottom left; Florida gator incorporated into the REAL ID
  star (top right). Back: Space Shuttle Discovery (39 missions, 365 days in
  space, final landing in Florida March 9, 2011) and the motto "Let Us Alone"
  from Florida's first unofficial flag.
- Fraud protection: "nearly double the fraud protection measures compared to
  the previous design, including redundant data, tactile security features,
  ultraviolet (UV) ink and optically variable features"; plus an image of the
  state seal as an enhanced security feature, and a "Temporary Non-Domiciled"
  marking for CDLs and Commercial Learner's Permits.
- Designations carried on the credential: lifetime sportsman's, boater,
  freshwater, saltwater and hunting licenses; Veteran, organ donor, deaf/hard
  of hearing, and developmentally disabled.
- Resources: flhsmv.gov/newDL.

## 7. ⚠️ FLAG — OTR traffic case (Git-FED): what this section does / does not change

**No 2026 legislation summary affecting traffic school, points, fines or
deadlines was found on flhsmv.gov.** The Legislation Summaries page as indexed
lists years only through 2022 and was last updated circa 2021 (§6.1). That is
itself the finding: FLHSMV's own legislation-summaries hub does not carry a
2026 entry to check against the OTR case.

What FLHSMV pages DO currently state, and which therefore govern unless a
newer statute says otherwise (all from §6.2 — verify against the clerk of court
for the specific citation, this is not legal advice):

1. **Traffic school elections are capped at FIVE in a lifetime and once in a
   12-month period** (s. 318.14(9), effective July 1, 2024). If Git-FED has
   already used elections, the remaining count matters — FLHSMV's Driving
   Records page says school-election adjudication-withheld entries are retained
   75 years.
2. **Election deadline is 30 days from the citation date**, and the clerk of
   court in the county of the citation must be told BEFORE attending the
   course. After 30 days, no BDI election in lieu of points.
3. **Completion window is 60–90 days from the citation date** (per the clerk's
   specification). Missing it = adjudicated guilty, points added, plus the
   deducted amount and up to an $18 processing fee.
4. **No traffic school election if charged with exceeding the speed limit by
   more than 30 mph** (s. 318.14(9), per Appendix C rev. 9-2-2025).
5. **Points if adjudicated guilty / paid without election:** 3 points for a
   moving violation, 3 for speeding ≤15 mph over, 4 for speeding >15 mph over;
   suspension at 12/12 mo, 18/18 mo, 24/36 mo.
6. **CDL holders cannot elect traffic school to avoid points** — check whether
   this touches Git-FED (Lyft driving is not a CDL, but the rule is on the
   page).
7. **No 2026 change to any of the above was found on flhsmv.gov.** The 2025
   items found (Move Over expansion Jan 1, 2025; SB 1662 repeal July 1, 2025
   noted in Appendix C without a legible statute number) do not touch traffic
   school/points/fines for an ordinary citation. The Sept 4, 2026 data breach
   (§3) is an identity-theft exposure item, not a traffic-law change — but if
   Git-FED's license data was in the breach population, the Sontiq monitoring /
   $1M insurance offer and the fraud-flag route (§1) are the relevant
   follow-ups.

## 8. Miscellaneous

### 8.1 Annual Report / Cabinet & Legislature Reports

- Annual Report (A-to-Z) points to:
  https://www.flhsmv.gov/resources/cabinet-and-legislature-reports/
  (also mirrored at https://www.flhsmv.gov/resourcecenter/cabinet-and-legislature-reports/).
- The Cabinet and Legislature Reports & Statistics hub says: "The Florida
  Department of Highway Safety and Motor Vehicles collects data and conducts
  research in order to provide lawmakers, partners and stakeholders, the media,
  and citizens with important facts and valuable information related to public
  safety and motor services. The Department compiles and analyzes traffic and
  safety data and emerging trends, and disseminates this research — as well as
  public safety expertise — to support public safety education efforts and
  policy decisions." Credit line requested: "The Florida Department of Highway
  Safety and Motor Vehicles" or "FLHSMV".
- Hub contents listed: Quarterly Reports; Legislative Budget Request; Texting
  While Driving Report; Cabinet Agenda; Long Range Program Plan; Impaired
  Driving Report; Agency Annual Report; Legislative Summaries; Red Light Camera
  Program Analysis; Seat Belt Violation Reports; Capital Improvement Program;
  Revenue Reports; School Zone Speed Detection Systems and School Bus Passing
  Infraction Detection Systems; one-time reports (Private Rebuilt Report,
  Certificate of Title Report, Vehicle Registration Holds Report); By the
  Numbers.
- The only Annual Performance Report copies surfaced in search are old PDFs:
  FY 2016–2017
  (https://www.flhsmv.gov/pdf/cabinetreports/agencyannualreport2017.pdf) and
  FY 2015–2016. No current-year (FY 2024–25 / 2025–26) annual report figures
  were obtained in this session — GAP. The 2016–17 report's contents page
  lists: Facts and Figures; News and Accomplishments; Revenue Information;
  Budget by Division; Performance Measures and Standards; Purchases Made.
  Its figures are preliminary calendar-year 2016 data as of September 27, 2017
  — do not use them as current.

### 8.2 Contact Information

Source: https://www.flhsmv.gov/contact-us/ (indexed copy; last crawl 94 days
before 2026-11-23). Headquarters: Neil Kirkman Building, 2900 Apalachee
Parkway, Tallahassee, FL 32399 (Audit Services: MS 58, phone 850-617-2910,
fax 850-617-3934).

- Customer Service Center: (850) 617-2000, Monday–Friday 8:00 a.m.–5:00 p.m.
  EST. Be prepared to provide driver license number, Social Security number,
  title or VIN.
- 24/7 phone self-service: 850-617-3000 (check driver license; check vehicle
  record; new resident information; first license information — requires DL
  number, SSN, title or VIN).
- Online self-service (DLCheck): make an appointment; check driver license;
  online insurance update; driving school eligibility check; Social Security
  number update; replace/renew a Florida driver license or ID card.
- MyDMV Portal: replace/renew registration for a motor vehicle or vessel, or
  obtain a paper title. MVCheckWeb: vehicle information check.
- Driver License Check tool: mydmvportal.flhsmv.gov/home/en/publicweb/dlcheck
  — enter DL number (e.g. Z123-456-78-901-0, with or without hyphens); "VALID"
  means FLHSMV has received information and cleared the record.
- Commercial vehicles: CDL Help Desk (Customer Service) 850-617-2606;
  Commercial Carrier IFTA/IRP Help Desk 850-617-3711; CDL Retest Help Line
  850-617-2707; Commercial Vehicle Enforcement 850-617-2280.
- Crash Reports/Records (purchase copies): 850-617-3416, Option 5; online at
  FloridaCrashPortal.gov (fees apply).
- Dealer licensing (mobile homes, RVs, automobiles): 850-617-3003.
- FHP Bureau of Criminal Investigations and Intelligence: 850-617-2302.
- IRP/IFTA: 850-617-3711. Mobile Homes Construction: 850-617-2808. Mobile
  Homes Installers: 850-617-3004.
- Driver record questions: Customer Service (850) 617-2000 or the Driver
  License Check tool; record requests via the Questions About Driving Record
  page; motor vehicle / vessel / mobile home record requests via form 90510.
- Email form option: https://flhsmv.service-now.com/csp.
- Compliment a trooper / praise an employee: Employee Praise
  (services.flhsmv.gov/EmployeePraise).
- Local contacts listed: Bureau of Administrative Reviews; Clerk of Court;
  County Tax Collector; Driver License; Florida Highway Patrol; Motor Vehicle.
- Public records custodian (s. 119.12(1)(b), F.S.): Custodian of Public
  Records, Office of General Counsel, FLHSMV, 2900 Apalachee Pkwy, Room A432,
  MS 02, Tallahassee, FL 32399. Media requests: Office of Communications,
  2900 Apalachee Parkway, MS 44, Tallahassee, FL 32399. Inspector General:
  InspectorGeneral@flhsmv.gov, 850-617-3104.
- Open Government page: http://www.flhsmv.gov/resource-center/open-government/
  — Annual Regulatory Plans FY 2021–22 through FY 2025–26 are listed there;
  FLHSMV maintains driver license, motor vehicle and related databases queried
  and updated at "more than 400 locations throughout the state".

### 8.3 Americans With Disabilities Act Notice

Source: https://www.flhsmv.gov/ada-notice/ (indexed copy).

- "In compliance with the Americans with Disabilities Act ('ADA'), the
  Department of Highway Safety and Motor Vehicles (FLHSMV) will not
  discriminate against qualified individuals with disabilities in its services,
  programs, or activities."
- FLHSMV has TWO ADA coordinators: an Internal ADA Coordinator (employee /
  employment issues) and an External ADA Coordinator (customer, public, or
  facility related issues).
- Employment: FLHSMV does not discriminate on the basis of disability in
  hiring or employment practices and complies with all regulations promulgated
  by the U.S. Equal Employment Opportunity Commission.
- Effective Communication: upon request, FLHSMV will attempt to provide
  services so persons with disabilities can participate equally, including sign
  language interpreters, documents in Braille, and other ways of making
  information accessible to people with speech, hearing, or vision impairments.
- Modifications to Policies and Procedures: FLHSMV will make reasonable
  modifications to programs to ensure equal opportunity to participate.
- Requests: anyone who requires an auxiliary aid/service for effective
  communication, or a modification of policies to participate in FLHSMV
  service, should contact the office manager as soon as possible but no later
  than 48 hours before the scheduled event.
- Limit: the ADA does not require FLHSMV to take action that would
  fundamentally alter the nature of its programs/services or impose an undue
  financial burden.
- Complaints — direct to:
  - Employee and Employment Issues: Internal ADA Coordinator, Neil Kirkman
    Building Room A417, 2900 Apalachee Parkway, Tallahassee, FL 32399,
    850-617-3202.
  - Facility Related Issues: External ADA Coordinator, Neil Kirkman Building
    Room A102, 2900 Apalachee Parkway, Tallahassee, FL 32399, 850-617-3161.
- Related: FLHSMV complies with Title VI of the Civil Rights Act of 1964
  (prohibits discrimination on the basis of race, color, or national origin —
  stated on the Contact Us page).

### 8.4 Grievance Procedure Under the ADA

- The A-to-Z Guide lists "Grievance Procedure Under the Americans with
  Disabilities Act" as its own entry. **No FLHSMV-specific grievance-procedure
  page or text was returned by search in this session, and the entry's target
  URL was not confirmed** — the A-to-Z JSON fragment available in search
  results was truncated before the G section's links. GAP: do not assume the
  procedure's deadlines/steps. What IS confirmed on flhsmv.gov is the
  complaint routing in §8.3 (the two ADA coordinators, with rooms and phone
  numbers) — a grievance/complaint about accessibility goes to the Internal
  coordinator (employment) or External coordinator (customer/facility).
  The ADA Notice page itself is the closest confirmed FLHSMV source.

### 8.5 Career Opportunities (HSMV) / Working at FLHSMV

- Careers hub: https://www.flhsmv.gov/careers/ ; Career Opportunities page:
  https://www.flhsmv.gov/working-at-flhsmv/career-opportunities/ (neither could
  be opened directly — 429; facts from indexed copies).
- "Our people are at the heart of everything we do. We offer an array of
  employment opportunities including business administration, customer service,
  information technology, and public safety." / "If you would like a career
  where your talents can have a positive impact in the lives of all Floridians
  and visitors to this state, come work with us!"
- Working at FLHSMV: "you are not just an employee. You are a member of an
  agency that has one vision: A Safer Florida. You are an integral part of a
  team that is committed to serving, educating, and assisting those who live
  and visit our beautiful and diverse state." Values section repeats the
  mission/vision/values in §5.
- Veterans: https://www.flhsmv.gov/working-at-flhsmv/veteran-resources/ —
  "More than 20% of FLHSMV's members are veterans"; FLHSMV aims to be "one of
  the most veteran-friendly departments in Florida". Veterans' preference is
  given to eligible persons applying to open, competitive Career Service
  vacancies (and promotional preference in some situations). FHP SkillBridge
  internship (DoD SkillBridge, last 180 days of service, via Veterans
  Florida). FHP Training Academy has an approved non-college degree and
  on-the-job training program for VA GI Bill benefits. FLHSMV Veterans
  Employee Resource Group / Veterans Advocate Office. (2019: 800+ veterans,
  ~20% of workforce; 2023 event: "over 700 Veterans statewide, making up over
  18%" — figures vary by year; use the Veteran Resources page's "more than
  20%" as the current statement.)
- FHP careers are separate: BeATrooper.com / Career Opportunities (FHP) in
  the A-to-Z — FHP section, not this section.

### 8.6 Customer Survey (FHP)

- A-to-Z entries "Customer Survey (FHP)" and "Survey (Customer) FHP" point
  to the FHP Surveys page: http://flhsmv.gov/florida-highway-patrol/fhp-surveys/
- Page contents (indexed copy): **FHP Citizen Survey**, and a **CALEA
  Accreditation Public Comment Portal** — "The purpose of this public portal
  is to receive comments regarding an agency's compliance with CALEA
  standards, engagement in the service community, delivery of public safety
  services, and overall candidacy for accredited status." No survey questions
  or results were obtained in this session — GAP (page not opened, 429).

### 8.7 HSMV Related Links / Other Agencies / Other States

- A-to-Z has four overlapping entries: "HSMV Related Links", "Links to HSMV
  related sites", "Other useful links to HSMV related sites", "Useful links to
  HSMV related sites", plus "Other Agencies/Departments" and "All State Motor
  Vehicle, Driver License and Highway Patrol (State Police) Agencies" /
  "Other State Motor Vehicle, Driver License and Highway Patrol (State Police)
  Agencies".
- **No standalone "HSMV Related Links" page was returned by search, and no
  target URL was confirmed for any of the four link-list entries.** GAP.
- What IS confirmed:
  - Other-states page: https://www.flhsmv.gov/otherstates/ — "All 50 states
    and Washington, DC have websites with motor vehicle information for
    consumers. Some states have separate agencies for driver licensing,
    vehicle registration and highway patrol (State Police)."
  - Locations page (https://www.flhsmv.gov/locations/) covers local driver
    license and motor vehicle service centers, Bureau for Administrative
    Reviews, FHP stations, Clerk of the Court offices and motorist services
    regional offices, by county; FLOW mobile offices; self-service kiosks
    (provided/maintained by Intellectual Technology, Inc.).
  - Resources page: http://www.flhsmv.gov/resources — Executive Director
    Dave Kerner; FLHSMV social links (above, §5).
  - External sites named on FLHSMV pages in this section: Florida Legislature
    www.leg.state.fl.us (bill copies); FloridaCrashPortal.gov; MyDMVPortal
    (mydmvportal.flhsmv.gov); AnnualCreditReport.com; identitytheft.gov/databreach;
    Florida Relay Service 1-800-955-8771 (TDD) / 1-800-955-8770 (Voice).

### 8.8 Other A-to-Z entries swept in this section

Entries in the A-to-Z that fall in this catch-all and were checked, with
outcome:

- **Cyber Security** (A-to-Z, C section): no standalone FLHSMV cyber-security
  page was returned by search. The closest 2026 material is the September 2026
  data breach (§3) and the Motorist Modernization pages. GAP — page/URL not
  confirmed.
- **Open Government / Public Records**: see §8.2 (custodian, regulatory
  plans FY 2021–22 to FY 2025–26).
- **Employee Praise / Kudos to an HSMV Employee / Thank an HSMV Employee /
  Praise an HSMV Employee**: services.flhsmv.gov/EmployeePraise — named on
  Contact Us under "Compliment a Trooper". No further detail obtained.
- **Cabinet Agendas**: listed under Cabinet and Legislature Reports (§8.1);
  no separate detail obtained.
- **Quarterly Reports**: hub page
  https://www.flhsmv.gov/resources/cabinet-and-legislature-reports/quarterly-reports/
  — listed, not opened (429). No quarterly figures recorded.
- **Stolen Driver License/ID**: A-to-Z entry; no standalone FLHSMV page text
  obtained — covered in substance by §1 (report to local law enforcement;
  Form 72068; fraud flag). GAP on a dedicated page.
- **Driver License/ID Card Tracking System** (also "ID Card and Driver License
  Tracking System", "Online order tracking/status", "Status of Your Driver
  License or ID Card Order", "Tracking your Driver License or ID Card Order",
  "Where is my ID card or Driver License?"): no dedicated FLHSMV tracking
  page text was obtained in this session. What FLHSMV does publish: the
  **Driver License Check** tool (mydmvportal.flhsmv.gov/home/en/publicweb/dlcheck,
  §8.2) for license validity/status, and MyDMV Portal for online orders. The
  "tracking" entries appear to resolve to those tools. GAP — dedicated
  tracking-page wording not verified.
- **Alerts/News, Press Releases, News Releases**: covered only where cited
  above (Sept 29, 2026 new credential; Sept 11, 2026 breach statement;
  Oct 1, 2026 pedestrian safety; Oct 28, 2026 Move Over; Dec 1, 2023 cloned
  Escalades; July 5, 2023 SB 1718). No general news-index facts recorded.
- **Nov 18, 2026 system outage** (NON-FLHSMV-page note, for context only):
  social posts on Nov 18, 2026 reported FLHSMV acknowledging "degradation of
  services affecting our driver license and motor vehicle issuance system"
  (ORION network). This was NOT verified on flhsmv.gov itself in this session
  and is not counted as an FLHSMV fact.

## 9. Page list — every URL studied, with what was found

| # | URL | How studied | What was found |
|---|---|---|---|
| 1 | https://flhsmv.gov/a-to-z-guide/ | browser.open, full read (608 lines, crawled 2026-11-04) | Full A-to-Z entry list; source of all entry names and several target URLs embedded in the page's JSON (see §9.1) |
| 2 | https://www.flhsmv.gov/safety-center/consumer-education/fraud/ | browser.open, full read (17 lines, crawled 2026-01-16) | Fraud hub: 2 sections only (ID theft/DL fraud; motor vehicle fraud), §1.1 |
| 3 | https://www.flhsmv.gov/privacy-statement/driver-privacy-protection-act/ | browser.open, full read (48 lines, crawled 2026-07-25) | DPPA, §4 |
| 4 | https://www.flhsmv.gov/privacy-statement/record-production-fact-sheet/ | search-indexed copy | MOU/audit rules, marketing ban, §4 |
| 5 | https://flhsmv.gov/safety-center/consumer-education/fraud/identity-theft-driver-license-fraud/ | search only — direct open 429 | URL confirmed; page content NOT obtained — GAP |
| 6 | https://www.flhsmv.gov/safety-center/consumer-education/fraud/motor-vehicle-fraud/ | search-indexed copy | 3 fraud types, §2.1 |
| 7 | https://www.flhsmv.gov/safety-center/consumer-education/fraud/motor-vehicle-fraud/odometer-fraud-warning/ | search-indexed copy | Odometer fraud, §2.2 |
| 8 | https://www.flhsmv.gov/safety-center/consumer-education/fraud/motor-vehicle-fraud/title-fraud/ | search-indexed copy | Title fraud, §2.3 |
| 9 | https://www.flhsmv.gov/safety-center/consumer-education/fraud/motor-vehicle-fraud/vehicle-cloning/ | search-indexed copy | Vehicle cloning, §2.4 |
| 10 | https://www.flhsmv.gov/motor-vehicles-tags-titles/liens-and-titles/nmvtis/ | search-indexed copy | NMVTIS, §2.4 |
| 11 | https://www.flhsmv.gov/florida-highway-patrol/specialized-areas/bureau-of-criminal-investigations-and-intelligence-bcii/ | search-indexed copy | BCII investigations incl. ID theft/DL fraud, §1.2 |
| 12 | https://www.flhsmv.gov/data-breach/ | search-indexed copy | Sept 4, 2026 breach FAQ, §3 |
| 13 | https://www.flhsmv.gov/2026/09/11/flhsmv-releases-statement-on-data-breach/ | search-indexed copy | Breach statement Sept 11, 2026, §3 |
| 14 | https://www.flhsmv.gov/resources/cabinet-and-legislature-reports/legislation-affecting-traffic-and-motor-vehicle-laws/ | search-indexed copy — direct open 429 | Year table 2022–2001 only; no 2023–2026; last updated ~1817 days before search, §6.1 |
| 15 | https://www.flhsmv.gov/resourcecenter/cabinet-and-legislature-reports/ | search-indexed copy | Reports hub contents, §8.1 |
| 16 | https://www.flhsmv.gov/resources/cabinet-and-legislature-reports/ | search-indexed copy (A-to-Z Annual Report target) | Same hub as #15 (variant path) |
| 17 | https://www.flhsmv.gov/resources/cabinet-and-legislature-reports/quarterly-reports/ | search result only (title) | Listed, not read — GAP |
| 18 | https://www.flhsmv.gov/pdf/cabinetreports/agencyannualreport2017.pdf | search-indexed copy | FY 2016–17 Annual Performance Report (old), §8.1 |
| 19 | https://flhsmv.gov/about/department-overview/ | search-indexed copy — direct open 429 | Mission/vision/values, §5 |
| 20 | https://www.flhsmv.gov/careers/ | search-indexed copy — direct open 429 | Careers hub, §8.5 |
| 21 | https://www.flhsmv.gov/working-at-flhsmv/career-opportunities/ | search-indexed copy | Career Opportunities, §8.5 |
| 22 | https://www.flhsmv.gov/working-at-flhsmv/veteran-resources/ | search-indexed copy | Veteran resources, §8.5 |
| 23 | https://www.flhsmv.gov/ada-notice/ | search-indexed copy | ADA Notice, §8.3 |
| 24 | https://www.flhsmv.gov/contact-us/ | search-indexed copy | Contact Us, §8.2 |
| 25 | http://www.flhsmv.gov/resource-center/open-government/ | search-indexed copy | Open Government / public records, §8.2 |
| 26 | http://flhsmv.gov/florida-highway-patrol/fhp-surveys/ | search-indexed copy | FHP Citizen Survey + CALEA portal, §8.6 |
| 27 | https://www.flhsmv.gov/otherstates/ | search-indexed copy (via A-to-Z JSON) | Other-states links, §8.7 |
| 28 | https://www.flhsmv.gov/locations/ | search-indexed copy | Office locations / FLOW / kiosks, §8.7 |
| 29 | http://www.flhsmv.gov/resources | search-indexed copy | Resources page, Exec. Director Dave Kerner, §5/§8.7 |
| 30 | https://flhsmv.gov/driver-licenses-id-cards/general-information/questions-about-driving-records/ | search-indexed copy | Traffic school 5-lifetime cap; DPPA; retention, §4/§6.2/§7 |
| 31 | http://www.flhsmv.gov/ddl/bdis.html | search-indexed copy | BDI election 30 days, points, §6.2 |
| 32 | http://www.flhsmv.gov/ddl/dicfaqa.html | search-indexed copy | Driver Improvement FAQ, 60–90 days, §6.2 |
| 33 | https://www.flhsmv.gov/pdf/courts/utc/APPENDIX_C_Rev%209-2-2025.pdf | search-indexed copy | Appendix C rev. 9-2-2025; >30 mph no school; SB 1662 repeal note, §6.2 |
| 34 | https://www.flhsmv.gov/2026/09/29/florida-launches-newly-designed-driver-licenses-and-identification-cards/ | search-indexed copy | New credential Sept 30, 2026, §6.3 |
| 35 | https://www.flhsmv.gov/driver-licenses-id-cards/newdl/ | search-indexed copy | New DL/ID page, §6.3 |
| 36 | https://www.flhsmv.gov/driver-licenses-id-cards/newdl/faq/ | search-indexed copy | Credential FAQ (fraud features history), §6.3 |
| 37 | https://www.flhsmv.gov/2026/10/01/flhsmv-celebrates-national-pedestrian-safety-month/ | search-indexed copy | Pedestrian $164 + 3 points, §6.2 |
| 38 | https://www.flhsmv.gov/2026/10/28/trooper-seriously-injured-after-driver-fails-to-move-over-in-active-work-zone/ | search-indexed copy | Move Over expansion Jan 1, 2025; 215 crashes / 17,300+ citations in 2025, §6.2 |
| 39 | https://www.flhsmv.gov/safety-center/child-safety/school-bus-safety/ | search-indexed copy | School bus penalties, §6.2 |
| 40 | https://www.flhsmv.gov/2023/07/05/icymi-governor-ron-desantis-announces-list-of-invalid-out-of-state-driver-licenses-issued-to-undocumented-immigrants/ | search-indexed copy | SB 1718, July 1, 2023, §6.2 |
| 41 | http://www.flhsmv.gov/2024/07/19/flhsmv-implements-legislation-requiring-driver-licenses-and-identification-card-numbers-to-change/ | search-indexed copy | s. 322.14(1)(a), 4 random numbers, July 31, 2024, §6.2 |
| 42 | https://www.flhsmv.gov/resources/forms/ | search-indexed copy | Forms list: 72068, 80122, §1.2 |
| 43 | https://mydmvportal.flhsmv.gov/home/en/publicweb/dlcheck | search-indexed copy | Driver License Check tool, §8.2 |
| 44 | https://www.flhsmv.gov/wp-json/wp/v2/pages/6957 | search-indexed copy (A-to-Z JSON) | Embedded A-to-Z target URLs, §9.1 |
| 45 | https://www.flhsmv.gov/2023/06/14/flhsmv-fhp-celebrate-veterans-at-8th-annual-veterans-recognition-day-event/ | search-indexed copy | 700+ veterans / 18%, Exec. Director Kerner quote, §8.5 |

### 9.1 A-to-Z target URLs confirmed from the page's own JSON (search-indexed copy of wp-json page 6957)

- About Us / Agency Mission/Vision/Values → https://www.flhsmv.gov/about/department-overview/
- Americans With Disabilities Act Notice → https://www.flhsmv.gov/ada-notice/
- Annual Report → https://www.flhsmv.gov/resources/cabinet-and-legislature-reports/
- Laws Affecting Traffic and Motor Vehicles / Legislation Summaries →
  https://www.flhsmv.gov/resource-center/cabinet-and-legislature-reports/legislation-affecting-traffic-and-motor-vehicle-laws/
- All State Motor Vehicle… Agencies → https://www.flhsmv.gov/otherstates/
- Kudos to an HSMV Employee → https://services.flhsmv.gov/EmployeePraise/
- Cabinet Agendas → https://www.flhsmv.gov/resources/cabinet-and-legislature-reports-es/ (Spanish-path variant as indexed; treat as unconfirmed)

## 10. Gaps and items NOT verified in this session (do not present as found)

1. Identity Theft / Driver License Fraud sub-page full text (429 on direct open).
2. Legislation Summaries page live state (429); indexed copy says years through 2022 only.
3. Department Overview, Careers pages live state (429); indexed copies used.
4. Grievance Procedure Under the ADA — no FLHSMV page/text found; target URL unconfirmed.
5. HSMV Related Links (and its 3 duplicate link-list entries) — no standalone page/URL confirmed.
6. Driver License/ID Card Tracking System dedicated page — not verified; only DL Check tool + MyDMV Portal confirmed.
7. Customer Survey (FHP) questions/results — page not opened.
8. Current-year Annual Report figures — only FY 2015–16 / 2016–17 PDFs surfaced.
9. Cyber Security standalone page — not found.
10. Stolen Driver License/ID dedicated page — not found as a standalone page.
11. Fraud Section email/phone and Fraud Analysis Unit phone (850-617-2405 / 850-617-2010) — see §11; NOT verified on flhsmv.gov directly in this session.

## 11. Supplementary contacts — NON-FLHSMV sources, do NOT count as FLHSMV facts

These appear in third-party documents citing FLHSMV and are included only so
the parent can verify them against FLHSMV directly; they were NOT confirmed on
a flhsmv.gov page in this session:

- Fraud Section email fraud@flhsmv.gov and phone 1-850-617-2405 (Collier County
  Sheriff's Office news release, Sept 12, 2019, "Be Aware Of Fraudulent Driver
  License Renewal", citing FLHSMV; also repeated in an Oct 30, 2026 social post).
- GoRenew unauthorized-access reports: GoRenewSupport@FLHSMV.gov or
  1-850-617-2010 (same Collier release).
- Fraud Analysis Unit phone 850-617-2010 (multiple third-party DMV guides).
- Florida Identity Theft Victim Kit (State of Florida / FloridaCommerce):
  steps are (1) report to the fraud departments of Equifax, Experian,
  TransUnion and place a fraud alert; (2) contact creditors' fraud departments;
  (3) contact bank/financial institution; (4) report to local law enforcement —
  under s. 817.568, F.S., the report may be filed where the offense occurred or
  where you reside; (5) file a complaint with the FTC Identity Theft
  Clearinghouse, 1-877-IDTHEFT / 877-438-4338; (6) flag your Florida driver
  license — FLHSMV Fraud Section will place a flag at your request "regardless
  of whether your Florida Driver's License has been compromised", phone
  (850) 617-2405, written request to DDL/BDI – Fraud Section, Room A327, Neil
  Kirkman Building, Tallahassee, FL 32399-0570; if the thief actually used your
  information to secure a Florida DL/ID, FLHSMV will conduct a fraud
  investigation, initiated by the DHSMV Identity Theft Report Form (Form
  72068); (7) Florida Attorney General fraud hotline 1-866-9-NO-SCAM
  (1-866-966-7226); FDLE Compromised Identity Review (fingerprint comparison)
  also referenced. The kit is a Florida state document, not a flhsmv.gov page,
  and its phone/address details are older — verify before use.
