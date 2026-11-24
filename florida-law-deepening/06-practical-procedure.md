# Practical Procedure — Florida Traffic Law (Deepening 06)

**Built:** Mon Nov 23, 2026.
**Scope:** The procedure Git-FED actually needs, step by step. This file ADDS to `~/workspace/your_files/florida-traffic-law-reference.md` (Parts 1 and the FLHSMV addendum) and `~/workspace/your_files/flhsmv-site-study.md` — it does not repeat them. Statute text, point values, fine components, the 30-day deadline math, the school-election rules, and the OTR guarantee rules already established there are cited by pointer, not restated.
**Sources:** Primary sources only — browardclerk.org, flhsmv.gov / services.flhsmv.gov, leg.state.fl.us (Online Sunshine), flsenate.gov, offtherecord.com, and FLHSMV's own UTC Procedures Manual (rev. Dec 2022, hosted as a PDF on floridalel.info). No blogs, law-firm pages, or AI summaries were used as sources.
**Method note:** The Broward Clerk traffic page, the Broward case-search page, the OTR live KB pages, and the FLHSMV DLCheck sanction-help pages were opened live on Nov 23, 2026. The FLHSMV sanction-help pages show a crawl date of Jan 16, 2026 in the browser tool; their text is quoted as read. Where a fact could not be verified live it is flagged **UNVERIFIED** below. The statute text controls over clerk/agency web pages wherever they disagree.
**This is a research reference, not legal advice.**

---

# A. How to read a Florida Uniform Traffic Citation, line by line

## A.1 What the paper in your hand is

- The Florida Uniform Traffic Citation (UTC) is the statewide form FLHSMV prepares and supplies to every traffic enforcement agency. It "contains a notice to appear, is issued in prenumbered books," and must be consistent with the state traffic court rules and FLHSMV procedures. — Fla. Stat. § 316.650(1)(a), https://www.leg.state.fl.us/statutes/index.cfm?App_Mode=Display_Statute&Search_String=&URL=Ch0316/Sec650.htm (2003 text via search; current text same in substance)
- The officer must file the court copy with the court having jurisdiction (or transmit it electronically) **within 5 days after issuance**. — § 316.650(3)(a); FLHSMV UTC Procedures Manual § 4(d), rev. Dec 2022, https://www.floridalel.info/documents/FLHSMV_UTC_Manual_2022.pdf
- The form comes in copies: Part One (white) is the complaint retained by the court; Part Two (white) is the abstract of court record; Part Three (blue) is the DHSMV record; Part Four (yellow) is the summons — **your copy**; Part Five (pink) is the officer/agency copy. For a standard (non-DUI) citation there are three copies. — UTC Manual § 5.1 (DUI distribution; same copy structure described for the standard form in § 4 and Diagram 2)
- The reverse side of your (yellow) copy tells you the options available when responding to a violation that does not require a court appearance. — UTC Manual § 5.1(d)
- Since June 18, 2021, paper citations for non-criminal offenses must come with a tear sheet titled "Payment Plan Option for Civil Penalties." — UTC Manual § 4, note after field 118
- **There is no separate "deadline" box printed on the citation form itself.** The deadline comes from the statute (§ 318.14(4): pay or elect within 30 days) and from the words on your ticket/mailer ("must comply within 30 days"). The controlling fields are the offense date and the fine amount — see A.3.

## A.2 Field by field (field numbers are FLHSMV's own, from UTC Manual § 4.1)

### Top of the form — who, where, when

| Field | What it is | What it means for you |
|---|---|---|
| Citation number | 7 characters. The first six are alphanumeric (a base-36 conversion of a unique FLHSMV number); the 7th character is **P for paper** or **E for electronic**. There is no check digit. | This is the tracking number for everything: the clerk's case search, the Fine Payment portal, and any letter to the court. Enter it with no dashes or spaces. Git-FED's citation AOEYHKE is 7 characters ending in E, i.e. an electronic citation. — UTC Manual § 3.1 |
| County (4) + county code | Full county name where the offense occurred, plus a two-digit county code. Must be filled in even if the offense was inside a city. | This county's clerk owns your case. Broward = the Broward Clerk. — UTC Manual § 4.1 |
| City (6) | City, only if the violation was inside city limits. | Where it happened; does not change which clerk handles it. — UTC Manual § 4.1 |
| Agency number (8) / Agency name (9) | The issuing agency (FHP, police department, sheriff's office, or other). | Who stopped you. The agency's copy of the citation is filed with the court within 5 days. — UTC Manual § 4.1; § 316.650(3)(a) |
| Day of week (10), Offense date (11), Offense time (12–13) | Date in MM/DD/YYYY format; time in HH:MM plus AM/PM (not military time). Future dates are rejected by the system. | **The offense date starts your 30-day clock.** Day 1 is the day after the offense date under the counting rule; the reference file works the math out for Git-FED's Oct 24, 2026 ticket (safe deadline Mon Nov 23, 2026). — UTC Manual § 4.1 |

### Driver section — check this against your license first

| Field | What it is |
|---|---|
| Driver first / middle / last name (14–16), suffix (17) | Name exactly as it appears on the driver license or ID card, in uppercase. |
| Street address (18), address-different box (19), city (20), state (21), ZIP (22) | Your current address as you gave it. Box 19 gets an X if the address differs from the one on your license. |
| Telephone (23) | 10 digits, no hyphens. |
| Birth date (24), race (25), sex (26), height (27) | Identifying information as shown on the license. |
| Driver license number (28), license state (29), license class (30), CDL yes/no (126), license expiration year (31) | Florida license numbers are 13 digits: one letter (first letter of last name) followed by numbers, no embedded spaces. Out-of-state numbers are entered as they appear on that license. |

**Why this section matters:** the address on the citation is where the clerk mails failure-to-comply notices (§ 322.245(1) for the criminal track; the civil track uses the address on file the same way). If the address is wrong or old, notices go to the wrong place and the suspension clock still runs. Broward Clerk: "Changing your address with the U.S. Post Office, or the State Department of Motor Vehicles Office, does not mean your contact information will be updated with the Clerk of Courts office" — you must notify the court in writing, with full name, date of birth, telephone number, case/citation numbers, and signature. — https://www.browardclerk.org/Divisions/TrafficAndMisdemeanor
**If you have no license card:** the officer enters your full name, date of birth, and sex, and your right thumbprint goes on the reverse of the first copy. — UTC Manual § 4.1, note after field 13; § 322.15(2)

### Vehicle section

| Field | What it is |
|---|---|
| Commercial vehicle (32), vehicle year (33), make (34), style (35), color (36) | Year/make/style/color of the vehicle. Left blank for a pedestrian or bicycle. |
| Hazardous material (37) | Yes/no. |
| Vehicle tag number (38), trailer tag (39), tag state (40), tag expiration year (41) | Complete tag number, characters only, no hyphens or spaces (example in the manual: QJR144). |
| 16-passenger vehicle (121), motorcycle (120) | Yes/no flags. |

### Violation section — the charge itself

| Field | What it is | What it means for you |
|---|---|---|
| Violation location (43), distance feet/miles (44–45), direction N/S/E/W (46–49), node (50) | Where the stop happened, described briefly, with distance/direction from a landmark or town. | The location the officer will testify to. Check it against where you actually were. |
| Actual speed (51), posted speed (52) | Mandatory fields for speeding violations only. | The two numbers that fix the speeding tier and fine. |
| Method of arrest (84), speed-measuring device ID (136) | How speed was measured: 0 unknown, 1 visual, 3 radar, 4 aircraft, 5 laser; plus the device serial number. | What the officer must be able to prove at a hearing. |
| Violation checkboxes (55–71, 120–132) | One box per violation type: careless, traffic control device, red light, lane, right-of-way, passing, child restraint, seat belt, equipment, expired tag (under/over 6 months), expired license (under/over 6 months), no valid license, suspended/revoked license, DUI, insurance, school zone, workers present, aggressive driver, and others. | Only the checked box(es) are the charge(s). A second citation for the same stop is flagged in the companion-citation field (42), with the companion number written in the comments box. |
| Other comments (72) | Any other information about the driver, vehicle, companion citation number, or violations. | Read it — the officer's notes live here. |
| State statute indicator (75), Section (76), Sub-section (77) | The chapter + section + subsection of the Florida Statutes you are charged under — e.g. 316.238. | **This is the charge.** The description box next to it is the officer's plain-language version; the statute number controls what law applies, what the points are, and what the base fine is. |
| Crash / property damage / injury / fatal injury (78–83) | Yes/no flags plus an estimated dollar amount of property damage (whole dollars, no decimals). Serious injury and fatal injury cannot both be checked. | A crash flag changes the points (4 instead of 3 for most moving violations) and can make a court appearance mandatory. |
| Court appearance boxes (85–87) | Criminal violation — appearance required; infraction — appearance required; infraction — no appearance required. Only one applies. | **If "no court appearance required" is checked, you do not have a court date — you have a 30-day deadline to pay, elect school, or request a hearing.** If an appearance-required box is checked, there IS a court date and you must appear. |
| Fine amount (115) | The civil penalty for the violation, format 9999.99 (decimal point required). **Left blank for criminal violations.** | **This is the amount the officer wrote — it is the civil penalty for the violation, not necessarily the total you owe.** Court costs and surcharges are added by the clerk under § 318.18. The clerk's total controls; verify it as in Section B. |
| Court date (88), court time (89, 91), court name (90), court address/city/state/ZIP (92–95) | Date/time/place you must appear — zeros or blank if not applicable. | Only filled in when an appearance is required. For a payable civil infraction these fields are blank/zero. |
| Officer rank / first / middle / last name (98–101), badge number (102), officer ID (103), trooper unit (104) | The issuing officer's identity. The citation must be signed by the officer with officer ID and/or badge number. | Who to expect as the witness at a hearing. |
| Officer delivery verification (118) | Checked to show the citation was delivered to you (civil infractions not requiring appearance). For criminal violations or infractions requiring appearance, you must sign the citation; if you refuse, the officer writes "refused" on the signature line. | Your signature on a civil infraction is NOT an admission of guilt — it is delivery verification. |

## A.3 Which fields control the deadline and the fine

1. **The deadline is controlled by the offense date (field 11) + 30 days under § 318.14(4), not by any date printed on the ticket.** There is no "due date" field on the UTC form. Broward Clerk states it plainly: "Civil traffic infractions must be paid within 30 calendar days from the date the citation was issued." — https://www.browardclerk.org/Divisions/TrafficAndMisdemeanor
2. **The fine is controlled by the clerk's total, not the officer's fine-amount field (115).** Field 115 is the civil penalty for the violation; the clerk adds court costs and surcharges under § 318.18 (e.g. $35 court costs for a moving infraction, plus county add-ons). The reference file establishes that no statute states a single total for failure to dim — the controlling amount is on the citation / clerk notice. Verify it as in Section B.
3. **The charge is controlled by the statute fields (75–77), not the plain-language description.** If the statute number and the description disagree, the statute number is what the court and FLHSMV record. (Git-FED's ticket: the OTR case-page label matched § 316.237, but the citation's statute field is what governs — see reference § 2.)
4. **The court-appearance boxes (85–87) control whether you have a court date at all.** "No court appearance required" = no date, 30-day election window. An appearance-required box = a real court date in fields 88–95, and missing it can suspend your license.
5. **The county field (4) controls where you pay, elect school, or request a hearing.** Everything goes to that county's clerk.

## A.4 What to do the day you get the ticket

1. Photograph the front and back of every copy you receive, including the Mailer Information Form and the payment-plan tear sheet.
2. Check the driver and vehicle sections against your license and registration, character by character. Note any error in writing — do not alter the ticket.
3. Circle the offense date, the statute number, the fine amount, and whichever court-appearance box is checked.
4. Write down the 30-day date (offense date + 30 calendar days; the reference file's safe course for an Oct 24, 2026 ticket is Mon Nov 23, 2026) and act before it — pay, elect school, request a hearing, or book an attorney. Do not wait for a mailed reminder; none is guaranteed before the deadline.

---

# B. How to verify a fine total from the Broward Clerk system

## B.1 Before you start

- **Wait for the citation to be entered.** The officer files the court copy within 5 days (§ 316.650(3)(a)), but Broward warns: "On occasion, it may take several weeks before a citation is entered in the Clerk's computer system. If you are unable to locate your citation, you may want to try again at a later time." — https://www.browardclerk.org/Divisions/TrafficAndMisdemeanor
- **Not finding it online does not extend your deadline.** "If the defendant finds that certain case information has not been entered, or if any of these systems are unavailable; it is still the responsibility of the defendant to make a payment or election to the clerk of courts office prior to the due date." Same source. If the citation is not in the system, you can come in person or mail the citation to the Clerk's office "for the purpose of manually entering the citation information into the computer system." Same source.
- **Have ready:** the citation number (7 characters, no dashes or spaces — e.g. AOEYHKE), your full name as printed on the citation, and the offense date.

## B.2 Step 1 — Look the case up (Case Search)

1. Go to the Broward Clerk's public Case Search: https://www.browardclerk.org/Web2/CaseSearchECA/
2. Choose the **Citation Number Search** tab. (The page also offers Party Name Search, Business Name Search, and Case Number Search.)
3. Enter the citation number in the Citation Number field. **Do not enter dashes or spaces. Example given on the page: 1234ABC.** The citation number is a required field. — https://www.browardclerk.org/Web2/CaseSearchECA/
4. Note on that page: "If your citation has not been entered into the Clerk's case management system, it will not appear on the Clerk's website. Also, this search is currently only for Traffic citations. Boating citations must be searched by Party Name." Same source.
5. If the citation search finds nothing, use **Party Name Search** instead: last name and first name are required; record searches are limited to the first 200 results, so refine by court type, middle name, and/or filing date range if there are too many matches. Same source.
6. Open the case from the results. The case record shows the case number, charge, court date (if any), plea or election, disposition, and the fines/costs assessed. (The fields shown are the clerk's case record; the exact on-screen layout of the Web2 portal was not captured in a live read — see the UNVERIFIED note in B.5.)

## B.3 Step 2 — Check the total in the Fine Payment service

1. From the Broward Clerk Traffic and Misdemeanor page (https://www.browardclerk.org/Divisions/TrafficAndMisdemeanor), use the **online Fine Payment service** link. The reference file records that this link resolves to https://www.browardclerk.org/Web2.
2. Search for your case the same way (citation number, no dashes or spaces) and open it. The service shows the **entire amount due** for the case. That figure is the clerk's total: base fine + court costs + surcharges, as assessed.
3. **Online payment is for the entire amount due only.** "This option is only available to pay off the entire amount due. Partial payment can only be made via the online Fine Payment services for cases with established payment plans." — https://www.browardclerk.org/Divisions/TrafficAndMisdemeanor
4. **Processing/transaction fees may apply** when paying online, by mobile app, or at any AMSCOT location. Same source. The fee is charged on top of the amount due; it is not part of the fine.
5. **If a plea of not guilty was entered and the case has not yet gone to court, fines may not be paid through the Internet.** "These fees vary according to the type of violation. The defendant must take payment to a Service Location or send the payment by mail. Late fees may be applied." Same source.
6. **Some violations are not payable online at all.** Citations for failure to carry/display a valid driver license, vehicle registration, or proof of insurance are not payable online — you must present the proof to the Clerk's office. The improper/unsafe equipment (§ 316.610) reduced-fine election is also not payable online. Same source, "Types of Violations" section.

## B.4 How the 18% school-election reduction shows up

- The reduction is statutory: "Any civil penalty that is imposed by s. 318.18(3) must be reduced by 18 percent" on a valid school election. — § 318.14(9) (established in the reference file, § 3).
- FLHSMV's Traffic Citations page states the same in plain language: "By electing to attend the Basic Driver Improvement Course, the traffic citation fine is reduced by 18%." — http://www.flhsmv.gov/FHP/traffic/ (via search-indexed copy in the FLHSMV site study; the live page was 429'd during that study).
- In Broward, the Fine Payment service lets you "pay a Traffic or Misdemeanor fine and, if they choose, elect the option to attend driving school" **in the same transaction**. — https://www.browardclerk.org/Divisions/TrafficAndMisdemeanor
- **UNVERIFIED — how the reduction is displayed:** no primary source opened for this file shows a screenshot or line-item breakdown of the Broward Fine Payment portal, so it is **not verified** whether the portal shows the pre-reduction total with a separate "−18%" line or simply shows the already-reduced total due. What is verified is the rule: when you elect school and pay in the same transaction, the amount charged is the reduced amount; and if you elect school in writing, the election "must be submitted in writing along with full payment and an additional $7.00 driving school affidavit fee." Same Broward source. **Do not assume the $7.00 affidavit fee is also reduced — it is a separate clerk fee, not part of the civil penalty.** If the portal total looks wrong, verify by phone before paying (see B.5).

## B.5 Other ways to verify the total

- **By phone:** "To verify the fine amount due or receive further assistance, please call our general information line at (954) 831-6565, select option 1. This service is available from 8:00 a.m. to 3:30 p.m., Monday - Friday, excluding court holidays." — https://www.browardclerk.org/Divisions/TrafficAndMisdemeanor
- **By mail:** Send Traffic and Misdemeanor fine payments to Clerk of Courts, P.O. Box 14610, Fort Lauderdale, FL 33302-4610. Do not send cash. Make checks or money orders (drawn on a United States bank only) payable to the **Clerk of the County Court**. Same source.
- **In person:** Pay at any Traffic and Misdemeanor service location. Same source.
- **PayIt:** payitbrowardclerk.payitgov.com (website and mobile app) for eligible cases; the app can also search and pay for cases, send due-date reminders, and keep receipts. Same source.
- **AMSCOT:** Cash payments at any Florida AMSCOT location, on eligible cases. Same source.
- **Payment plan:** To set one up you must appear at a service location in person — no one can set one up on your behalf; bring identification. "The processing fee to enter into a payment agreement is $25.00 per case. You must pay by mail or in person with cash, check, or money order." Same source.
- **UNVERIFIED — portal field list:** the Broward Fine Payment portal itself is a dynamic Web2 application; this file did not complete a live transaction in it, so the exact sequence of screens and input fields inside the portal (beyond the citation/case lookup described above) is **not verified** here. The steps above describe what the Clerk's own pages say the service does, not a click-by-click walkthrough of the live portal.
- **Cross-check with FLHSMV:** the FLHSMV Driver License Check (https://mydmvportal.flhsmv.gov/Home/en/PublicWeb/DLCheck) shows license status and suspensions, and the FLHSMV study records that it shows the line "You are currently eligible to elect traffic school." It does **not** show the clerk's fine total — the clerk is the source for the amount due.

## B.6 What the total is made of (so you can spot an error)

The reference file (§ 5) establishes the components: $60 base fine for a moving violation (§ 318.18(3)(a)), $35 court costs for a moving infraction (§ 318.18(12)(a)3), plus smaller add-ons ($2.50, $3 + $2) and a county surcharge of up to $30 for court facilities (§ 318.18(14)(a)). $60 + $35 = $95 before add-ons. Neither $129 nor $166 is a statutory total. If the clerk's total does not reconcile to those components, call (954) 831-6565 option 1 before paying — and remember: **paying the fine in full by itself is a conviction and bars a later school election.** — https://www.browardclerk.org/Divisions/TrafficAndMisdemeanor ("When you elect this option, it is considered a conviction and points may be assessed on your driver license. You will not be allowed to elect the driving school option at a later date.")

---

# C. Broward traffic court process, step by step

## C.1 First, what kind of case is it?

- **Civil traffic infraction** (most tickets, including failure to dim): a non-criminal charge "that can usually be disposed of by payment of a civil penalty or an election to attend a basic driver improvement course. A court appearance is not required, except in cases where the violation involves an accident with serious bodily injury or fatality." — https://www.browardclerk.org/Divisions/TrafficAndMisdemeanor
- **Criminal traffic or misdemeanor charge: a court appearance is required.** Municipal and county ordinance charges also require a court appearance. Same source.
- **Civil infractions have no criminal arraignment.** There is no arraignment hearing for a civil infraction — you choose among the four options below within 30 days. The word "arraignment" on Broward's page appears only for Tri-Rail fare violations ("Appear for arraignment at the location and time indicated on the violation") and smoking violations. Same source. (See also reference § 14.)

## C.2 The four options, within 30 calendar days of the citation

Broward lists exactly four. "Within 30 calendar days from the date you received your citation, you must comply by selecting one of the following options." — https://www.browardclerk.org/Divisions/TrafficAndMisdemeanor

1. **Pay fines and fees in full.** "When you elect this option, it is considered a conviction and points may be assessed on your driver license. You will not be allowed to elect the driving school option at a later date." Same source. This is the guilty plea in practice: § 318.14(4) provides that a person who does not elect to appear must pay within 30 days, and doing so is deemed an admission and waives the hearing right (reference § 14).
2. **Elect driving school (if eligible).** Must be submitted in writing with full payment plus the $7.00 driving-school affidavit fee. Adjudication is withheld, no points if you complete the course within 90 days of election and notify the clerk. Full rules in reference §§ 3, 9, 12.
3. **Request a court hearing.** "You may request to take your ticket to court." See C.3.
4. **Conditional Plea of No Contest and Waiver of Appearance.** "Resolve Civil Traffic Infraction cases that do not involve a traffic crash without making a physical appearance at the courthouse." See C.4.

## C.3 Requesting a hearing and what happens at each stage

### Step 1 — Request it in writing, within 30 days

- "If you choose to contest a Civil Traffic Infraction ticket, you must make your request for a hearing in writing to the Clerk within 30 calendar days of the date of the citation. You will be notified of your court date." — https://www.browardclerk.org/Divisions/TrafficAndMisdemeanor
- A not-guilty plea can be filed **in person, by mail, or via the Florida Courts E-Filing Portal** (www.myflcourtaccess.com). — Same source, "Types of Violations" (Toll/Sunpass section, stating the general filing routes for a not-guilty plea).
- **The 30-day hearing request is not the last chance.** Under § 318.15(1)(c), a person charged with a traffic infraction may request a hearing **within 180 days after the date the violation occurred**, even after a suspension has been imposed, and "upon request, the clerk must set the case for hearing." If the 180th day is a Saturday, Sunday, or legal holiday, the request must be made within 177 days. Broward's page states the same rule for Toll/Sunpass violations: "A person may enter a 'Not Guilty' plea to request a hearing within 30 days and up to 180 days after the violation has been issued. If the 180th day falls on a Saturday, Sunday or legal holiday, the person who is charged must request the hearing within 177 days after the violation. If after 180 days, the defendant may request a hearing by submitting a defendant request order form to the Judge or Hearing Officer for review." Same source. For Git-FED's Oct 24, 2026 ticket, 180 days is Thu Apr 22, 2027 (established in the FLHSMV site study, Part 0 § 7).

### Step 2 — Pretrial conference (Zoom)

- "The case is set for a pretrial conference date and the violator is notified via mail." — https://www.browardclerk.org/Divisions/TrafficAndMisdemeanor (Toll/Sunpass section)
- Broward's hearing page refers to a "scheduled Zoom Pre-Trial Conference Hearing or Infraction Trial (in person) court date," i.e. the pretrial conference is by Zoom and the trial itself is in person. Same source, "Request Court Hearing" section.
- At the pretrial conference the case may be resolved (plea, school, dismissal) or set for trial. **UNVERIFIED:** the Broward pages opened do not spell out what happens at the pretrial conference step by step (who is present, whether the officer attends, what the hearing officer can order there). That detail is not stated on the primary sources read and is flagged unverified rather than filled in from secondary sources.

### Step 3 — Infraction trial (in person)

- The trial is before a judge or civil traffic hearing officer. The infraction must be proved **beyond a reasonable doubt**. — § 318.14(5)–(6) (reference § 14).
- If the infraction is proven, the penalty can be up to $500 ($1,000 for a school/construction zone), driver-improvement school, or both. If it is not proven, no costs or penalties are imposed. — § 318.14(5) (reference § 14).
- The officer is the state's witness; the citation fields in Section A (speed-measuring device, location, statute) are what the officer testifies from.

### If you cannot make a court date, or you missed one

- **Before the date:** "If you have entered a plea of Not Guilty, for a civil traffic case, and are unable to appear for your upcoming scheduled Zoom Pre-Trial Conference Hearing or Infraction Trial (in person) court date, you must contact the Clerk's Office by coming in person, or by mail. You will be required to fill out a civil traffic court Defendant's Request Form, which will be forwarded to the presiding Hearing Officer for further review. If the request is granted, you will be notified by mail of your new court date." — https://www.browardclerk.org/Divisions/TrafficAndMisdemeanor
- **If you fail to appear:** "If you fail to appear on your scheduled court date for a civil traffic violation, the Hearing Officer may issue a suspension of your driver's license." Same source.
- **After a missed date:** "If you missed your court date and wish to schedule a new court date for a Civil Traffic case, you must contact the Clerk's Office in person or in writing, and will be required to fill out a 'Civil Traffic Court Defendant's Request Form'. This request will be forwarded to the presiding Hearing Officer for review. If this request is granted, you will be notified by mail of your new court date. However, the suspension may not be withdrawn until delinquent fees are paid." Same source.
- **Other case types are harsher:** for non-civil-traffic cases, failure to appear can mean the judge issues a warrant for arrest as well as a license suspension. Same source.
- **Out-of-area defendants (criminal traffic/misdemeanor only):** a "plea by mail" option exists for people living outside Broward/Miami-Dade/Palm Beach cited for a criminal traffic or misdemeanor charge — a written letter to the "Honorable Judge of the County Court" with full name, DOB, address, phone, violation date, charge, citation/arrest number, and a self-addressed stamped envelope, stating why you cannot attend and your intention to plead guilty or no contest. "If you are pleading 'not guilty,' you are not eligible for this option and must appear in court." Same source.

## C.4 Conditional Plea of No Contest and Waiver of Appearance

- **What it is:** a written no-contest plea that resolves an eligible civil traffic infraction **without a court appearance and without points** — if the court accepts it, adjudication is withheld. "No court hearing is required. No points will be accessed to your Florida driver license. You will not be found guilty – adjudication will be withheld. You must comply with the court's ruling (e.g., pay fines, attend traffic school, etc.)." — https://www.browardclerk.org/Divisions/TrafficAndMisdemeanor
- **Eligibility:** civil traffic infractions **not involving a traffic crash** and **not requiring a mandatory court appearance** under § 318.19. It does not apply to crash citations or criminal traffic offenses. Same source. The governing order is Administrative Order 2025-33-CO (Seventeenth Judicial Circuit, effective Aug 28, 2025), "Conditional Plea of No Contest in Civil Traffic Infraction Proceedings Not Involving Traffic Crashes." — https://flexlaw.co/court-doc/9570/pdf (search-indexed copy of the administrative order; the order itself is a primary source, the host is a document mirror — flag as search-indexed)
- **Deadline:** file the Conditional Plea with the Clerk **within 30 days of the date of the infraction** (to avoid late fees). If you already filed a timely election to contest, you may still use this procedure by filing a Conditional Plea **no later than 10 days before the scheduled pretrial hearing**. Same administrative order.
- **How to file:** one form per citation. Mail to Broward County Clerk of Court, P.O. Box 14610, Fort Lauderdale, FL 33302-4610, or email to TrafficeClerk@browardclerk.org (spelling as printed on the Broward page). The form itself is at https://web.browardclerk.org/PDF/TrafficandMisdemeanor/ConditionalPleaofNoContest.pdf. The form may also be dropped in the Clerk's drop box at any courthouse location. — Broward page; form PDF via search result.
- **What the form requires:** name, address, telephone, email, date of birth, citation number(s), the charges as you understand them, and your traffic history for the past two years (dates, locations, nature of any adjudication, guilty finding, or withheld adjudication). You swear under penalty of perjury. You state you are not admitting the violation, you ask the court to withhold adjudication so you have no points, and you waive personal appearance and your right to a speedy trial. You may attach a written statement, photos, or other papers. — Conditional Plea form.
- **If the court accepts it:** a disposition order is entered and returned to you without further hearing, and you have a set time to satisfy the penalty imposed. **CONFLICT — UNVERIFIED:** the administrative order summary states 60 days to satisfy the penalty; the form itself states you must "comply with the resolution the Court has imposed within 120 days, or my driver's license may be suspended." Both are quoted from primary documents; which controls is **not resolved** in this file — follow the disposition order you actually receive, and treat the shorter period as the safe one.
- **If the court declines it:** "the court shall [set the matter on a regularly scheduled traffic infraction pretrial docket]" and you choose on the form what happens next: pay the civil penalty within 30 days of the ruling; pay the school civil penalty within 30 days and complete defensive driving school within 60 days of the ruling (certifying you are eligible); or request a court date. — Administrative Order 2025-33-CO; Conditional Plea form.
- **Not the same as the § 318.14(10) nolo / proof-of-compliance election.** That separate election covers listed compliance offenses (no valid license/registration, no insurance proof) with a 3-lifetime limit and proof of compliance to the clerk. Do not confuse the two. (Reference §§ 3, 14.)

## C.5 What "adjudication withheld" means in practice

- **It is not a conviction.** "Withheld adjudication 'is not a conviction.'" — § 318.14(11) (reference § 14).
- **No points.** On a valid school election, "adjudication must be withheld" and "points, as provided by s. 322.27, may not be assessed." — § 318.14(9). On a conditional no-contest plea accepted by the court, adjudication is withheld and no points are assessed. — Broward page.
- **Insurance:** FLHSMV states an insurer cannot impose an additional premium, cancel, or non-renew solely because of a non-criminal traffic infraction when adjudication has been withheld and no points were assessed, unless the infraction involved a crash where the insurer was at fault and incurred a loss. — FLHSMV BDI page (reference § 14; FLHSMV site study § 1.4).
- **It still exists on your record.** A school-election adjudication-withheld entry is retained **75 years** on the complete driving record, and the complete ($10) record — not the $8 3-year record — is the one that shows it. — FLHSMV Questions About Driving Records (reference § 19; FLHSMV site study Part 0 § 8). A withheld adjudication is visible to the court and to FLHSMV; it is not an erasure.
- **It counts toward election limits.** A school election that ends in withheld adjudication still counts as one of your lifetime elections (5 on Broward's page and FLHSMV's current pages; 8 in the 2024 statute text — disputed, see reference § 3 and FLHSMV site study Part 0 § 1) and starts the 12-month clock before you can elect again.
- **A withhold is not automatic at a hearing.** At a contested hearing the hearing officer or judge decides the disposition; withholding is one possible outcome, not a right. The mandatory withhold applies to a valid school election (§ 318.14(9)) and to a valid § 318.14(10) compliance election — not to losing at trial.

---

# D. How OTR-style attorney representation works, end to end

All of this section is from OTR's own published pages (offtherecord.com). OTR states on its attorney terms page: "OTR is not a law firm." The attorneys are independent, licensed lawyers; OTR is the marketplace that matches you to one. — https://offtherecord.com/attorney-terms-and-conditions

## D.1 Booking — what you do

1. **Submit the ticket/case details.** "When a prospective customer submits a ticket and/or case details to OTR our algorithm suggests an independent attorney licensed in the appropriate jurisdiction to handle the matter." The algorithm weighs the attorney's license, fees, success rate with other OTR customers, and customer-service reviews and ratings. You may also request a specific attorney; OTR honors that "as long as the attorney is available and willing to take on the case." — https://offtherecord.com/attorney-terms-and-conditions
2. **You get a quote before you commit.** You are told whether your ticket is eligible for the money-back guarantee at booking, in the booking wizard. — https://offtherecord.com/kb/articles/otr-success-rate-explained
3. **Pay nothing extra beyond the quote.** The legal fee goes to the lawyer; OTR also charges a $10 booking/service fee. The fee "does not include any fine amounts or court fees that you may have to pay depending on how your case is resolved." — https://brochure-devo.offtherecord.com/faq (OTR FAQ, via search; the $10 figure also appears in the reference file § 11 as the OTR service fee) and https://offtherecord.com/kb/articles/how-card-holds-work

## D.2 The moment you book — three things happen at once

"As soon as you complete your booking, three things happen: 1. **You are introduced to your attorney** — Your matched law firm and attorney are revealed immediately. You can see their name, their firm, and their contact information in your case dashboard. 2. **Your attorney is notified** — The law firm receives a notification that they have a new case to review — yours. They will review it during the current or next business day. 3. **The case chat opens** — You can start communicating with your attorney right away through the case chat. You do not have to wait for them to reach out first." — https://offtherecord.com/kb/articles/what-to-expect-after-you-book-a-case-off-the-record

## D.3 The money: pre-authorization hold, not a charge

- When you complete booking, OTR places a **pre-authorization** on your card for your checkout total — quoted legal fee plus the OTR service fee. It shows as a pending charge from OFF THE RECORD; it is not a completed transaction. Your bank sets the funds aside while your attorney reviews your case. — https://offtherecord.com/kb/articles/how-card-holds-work
- The hold lasts **up to 7 days**. If it is not captured within 7 days, your bank releases it automatically. It can also be released earlier — for example, if you cancel, or if OTR support releases it. — Same source.
- **The hold becomes a charge only once your attorney accepts your case.** "Once your attorney accepts your case, the pre-authorization is captured — it converts from a pending hold into a completed charge, and your case moves forward." — Same source.
- **If the hold expires before acceptance** (e.g. the case is reassigned and review runs past 7 days): OTR tries to reauthorize your card; if it cannot reauthorize automatically, it contacts you by email, text, or phone to collect payment; if it cannot collect the funds, the case is canceled. A reauthorization can briefly show as two pending holds; only the new one is active. "If your case is canceled because the hold expired, you are not charged." — Same source.
- **Payment plans:** the down payment works exactly like a full payment (pre-authorization, captured on acceptance); remaining installments are charged right away on their due dates, with no hold. — Same source.

## D.4 Pending review / the acceptance window — one full business day

- The attorney has **one full business day** to accept or decline. "Upon notification from OTR that you have received a case, you have one business day to review and accept (or decline) the case on the OTR platform. If you fail to do so within one business day we may reassign the case to a different attorney." — https://offtherecord.com/attorney-terms-and-conditions
- OTR's own example: book Friday at 1 PM, the window stays open until Monday at 1 PM — weekends do not count. — https://offtherecord.com/kb/articles/otr-cancellation-policy-explained
- During review the attorney may: accept right away; ask you questions first (clarification or additional documents — respond promptly, the faster you respond the faster the case moves); or send a **counter offer** (an adjusted legal fee, a changed money-back guarantee, or both, when the case is more complex than indicated). "You will need to accept the new terms before the attorney proceeds." Nothing moves forward, and you are never charged more or have terms changed, without your express approval. — https://offtherecord.com/kb/articles/what-to-expect-after-you-book-a-case-off-the-record; https://get.offtherecord.com/kb/articles/counter-offers-explained
- "More than 90% of cases are accepted by the first matched attorney. Most clients see their case accepted within hours of booking." — https://offtherecord.com/kb/articles/what-to-expect-after-you-book-a-case-off-the-record

## D.5 Attorney-client relationship — formed only on acceptance

- **"Until they accept, you do not yet have official legal representation — acceptance is the moment the attorney formally agrees to represent you."** — https://offtherecord.com/kb/articles/what-to-expect-after-you-book-a-case-off-the-record
- The reference file (§ 11) records the same rule from OTR's terms: "The attorney-client relationship is not formed until the attorney accepts your case."
- **Practical consequence while pending:** "You are responsible for your case until an attorney accepts it. Booking a case on OTR does not mean you have an attorney yet. Your case still needs to be reviewed and accepted by a law firm. Until that happens, you are responsible for your own court date. Do not assume someone is covering for you until you see that your case has been accepted in the app." — https://staging.offtherecord.com/kb/articles/can-i-still-book-a-case-if-my-court-date-is-tomorrow (staging host of the same OTR KB article; the live-host version was not returned in search — flag as staging-hosted copy of OTR's own text)
- **What to do while waiting:** introduce yourself in the case chat and describe what happened in a few sentences, including the circumstances of the stop and your priorities; upload your driver's license (the attorney may need it to pull your driving/criminal record, or the court may require it with certain filings); upload a clear photo of the front and back of your ticket if you did not do so at booking — "A clear photo of the document is the single most helpful thing you can provide"; verify your email, phone, and mailing address; you can invite case participants (a parent, spouse, or a company/fleet manager) to follow the case and message the firm through the case chat. — https://offtherecord.com/kb/articles/what-to-expect-after-you-book-a-case-off-the-record

## D.6 After acceptance — what the attorney files and does

- **The attorney handles the court side.** "Once you have accepted a case from us you should proceed with representation as you normally would. As such, you, the attorney, are responsible for handling all communication and paperwork with the relevant court. It is your responsibility to file a notice of appearance, request a court date, and to perform other similar tasks. The client should not have to mail their ticket to the court or be asked to do other similar tasks that you can easily do." — https://offtherecord.com/attorney-terms-and-conditions
- **What that means in Broward practice:** the attorney files the notice of appearance and the election/plea with the clerk — in a civil infraction that is the hearing request / not-guilty plea (in person, by mail, or via the Florida Courts E-Filing Portal; see C.3) or the conditional no-contest plea (see C.4), or the school election where that is the strategy. The attorney's filings go through the attorney's own E-Filing Portal account (validated against The Florida Bar member database), so they appear in the attorney's "My Cases," not the client's — an empty "My Cases" on the client's own portal account proves nothing about whether the attorney filed. (Reference § 10.)
- **Typical timeline after acceptance, per OTR:** within 1–2 business days the attorney reviews and accepts and may reach out with initial questions; first 1–2 weeks the attorney researches the case and builds the defense, and may request documents; weeks to months the attorney works the court process — filing motions, attending hearings, negotiating. "Some cases resolve in weeks, others take months." — https://offtherecord.com/kb/articles/what-to-expect-after-you-book-a-case-off-the-record
- **Notification:** the attorney must keep the client informed on the status of the case and, at a minimum, "inform clients about their court date and answer client questions and concerns within one business day," must "accurately report the final outcome of any case you receive from us to the client and log it in the OTR platform," and must use the OTR platform for all transactional communication with the client. — https://offtherecord.com/attorney-terms-and-conditions
- **At resolution** the attorney notifies you of the outcome. "Common outcomes include dismissal, charge reduction, point elimination or reduction, deferral, traffic school, and fine reduction." — https://offtherecord.com/kb/articles/what-to-expect-after-you-book-a-case-off-the-record
- **While the case is ongoing, your record and insurance are not affected.** "A charge does not go on your driving or criminal record until the case is closed and a final judgment is entered." — Same source.
- **You do not have to appear in court** in the usual OTR traffic case — the attorney appears for you. OTR's own reply to a Florida reviewer states: "By hiring us, you never had to appear in court, have the best chance at dismissing your ticket, keep track of hearing dates, or follow up with the clerk. We handled all of that." — https://offtherecord.com/lawyers/fl/attorney-jorge-gonzalez (OTR attorney-profile page, review reply text)
- **UNVERIFIED — the exact filing for a Florida civil infraction:** OTR's pages do not name the specific Florida form or filing (e.g. which plea/election form, or the precise E-Filing submission type) the attorney uses in Broward County. The attorney-terms language quoted above (notice of appearance, request a court date, all court paperwork) is the verified statement; the specific document names are a matter between the attorney and the clerk, and are flagged unverified here rather than guessed.

## D.7 If the attorney declines, withdraws, or no attorney accepts

- **Decline → automatic rematch.** "If the initial attorney declines your case, SmartMatch automatically rematches you with the next best attorney. You do not need to do anything." Each new attorney gets one full business day to review; rematching itself "can take up to one business day." — https://offtherecord.com/kb/articles/what-to-expect-after-you-book-a-case-off-the-record; reference § 11
- **Declining a counter offer** does not end the case — it stays pending while you keep talking to the attorney, request a different attorney, or cancel. If you decline and the attorney decides not to take the case, SmartMatch reassigns; the new attorney's fee may be the same, lower, or higher. — https://get.offtherecord.com/kb/articles/counter-offers-explained
- **Withdrawal after acceptance → reassignment.** "When your attorney withdraws, we handle the reassignment: 1. We identify a new attorney who covers your court and handles your case type. 2. We reassign your case to the new attorney. Your case details and documents stay in your case file, and the new attorney receives everything they need to continue your representation. 3. We notify you once the reassignment is complete, and you can reach your new attorney in the same case chat. In the rare event that no replacement attorney is available for your court and case type, we cancel your case and issue you a full refund." Court dates stay the same; there may be a short transition period while the new attorney reviews the file. "In almost all cases, the reassignment costs you nothing extra" — if the new attorney's fee is higher, OTR covers the difference when the original attorney became unavailable. — https://offtherecord.com/kb/articles/attorney-withdrawal-case-reassignment
- **If no attorney accepts at all:** "If your case goes through all appropriate and available attorneys and none of them accept it, we will cancel your case and issue you a full refund of any fees you paid." — https://offtherecord.com/kb/articles/what-happens-if-an-attorney-declines-your-case

## D.8 Cancellation and refund rules (summary — full rules in reference § 11)

- **Cancel within 1 full business day of booking: you pay nothing, no questions asked.** If only a hold is on your card, the hold is released. If the funds were already withdrawn, you receive a **full refund of everything, including your legal fee and your OTR service fee**. Example: book Friday 1 PM → window open until Monday 1 PM. — https://offtherecord.com/kb/articles/otr-cancellation-policy-explained
- **Window extension:** if you asked a question in the case chat and the attorney has not answered before the window closes, the window is extended until you get an answer; if the answer is not satisfactory you can still cancel at no cost — but once the question is answered you must act quickly (cancel yourself or notify the attorney and OTR support), or the extended window closes and the standard no-refund policy applies. The extension applies only to questions asked **in the case chat**. — Same source.
- **After the window closes:** you can still stop your case at any time, but you will **not** receive a refund of your legal fee, because the attorney may already have started work. — Same source.
- **Time-sensitive cases:** if your court date is in the next day or two, the attorney may ask you to waive the cancellation window so they can start right away. Waiving is always your choice; if you agree, you will not receive a full refund if you later cancel. — Same source.
- **How to cancel:** open your case in the OTR app or website and follow the steps to request a cancellation; if you have trouble, contact OTR support. — Same source.
- **Money-back guarantee (loss, not cancellation):** refunds the **legal fee only** when an eligible case is lost with no improvement in charge, points, or fine; it does not cover court fines, fees, or costs, and the $10 service fee is not covered by the guarantee. The five voiding situations (paying/resolving the case yourself, not responding in time, missing a required court date, not completing required post-resolution steps, refusing a favorable outcome) are in reference § 11. — https://offtherecord.com/kb/articles/otr-success-rate-explained; reference § 11
- **Attorney payment:** Stripe transfers the attorney's full legal fee "no more than 48 hours after you accept a case and send your new client a message through OTR in-app messaging." — https://offtherecord.com/attorney-terms-and-conditions

---

# E. What a D6 suspension notice looks like and the exact reinstatement steps

## E.1 The two different tracks — do not mix them up

There are two separate failure-to-comply suspension paths in Florida law, and the notices and clocks differ:

| | Civil traffic infractions (§ 318.15) — your track | Criminal offenses (§ 322.245) — different track |
|---|---|---|
| Trigger | Failure to comply with the civil penalties in § 318.18 within the time in § 318.14(4); failure to enter into or comply with a penalty payment plan; failure to attend driver improvement school; failure to appear at a scheduled hearing. — § 318.15(1)(a) | Failure to comply with all directives of the court within the time allotted, for a criminal offense listed in § 318.17 or a misdemeanor under ch. 320 or ch. 322. — § 322.245(1) |
| Clerk warning notice | **None specified in § 318.15.** The clerk notifies FLHSMV directly. | The clerk **must mail you a notice of failure** to the address on the citation, **no later than 5 days after the failure**, warning that if you do not comply within **30 days after the date of the notice** and pay a delinquency fee of **up to $25** to the clerk, your license will be suspended. — § 322.245(1) (2020 text via flhouse.gov: https://www.flhouse.gov/Statutes/2020/0322.245/) |
| FLHSMV notice | Clerk notifies FLHSMV of the failure **within 10 days** after the failure. — § 318.15(1)(a) | Clerk notifies FLHSMV **within 10 days** after the 30-day cure period expires without compliance. — § 322.245(3) |
| Suspension effective | FLHSMV "must immediately issue an order suspending the driver license and privilege to drive of such person effective **20 days after the date the order of suspension is provided** in accordance with s. 322.251(1), (2), and (6)." — § 318.15(1)(a) | Same 20-days-after-mailing structure: order effective 20 days after the date the order is mailed per § 322.251(1), (2), and (6). — § 322.245(3) |

**For a civil ticket like Git-FED's, the § 318.15 track applies: no 5-day clerk warning letter and no 30-day cure period are in the statute.** The first paper you may see is the FLHSMV order of suspension itself. That is why the reference file stresses: no suspension is effective at midnight on day 31 — the 30-day deadline is only the failure date; then up to 10 days for the clerk notice, then the order, then 20 more days. (Reference § 4.)

## E.2 What the notice looks like

- **The FLHSMV order of suspension** is issued on receipt of the clerk's notice and is "provided" (mailed) to you under § 322.251(1), (2), and (6) — i.e. mailed to your address on file with FLHSMV. The suspension is effective **20 days after** the date the order is provided/mailed. — § 318.15(1)(a); FLHSMV UTC Manual § 12.1(b): "FLHSMV postdates suspensions 20 days from the date the notification is mailed."
- **UNVERIFIED — specimen contents:** no primary source opened for this file reproduces the full text of an FLHSMV D6 order-of-suspension letter, so the exact wording, headings, and fields on the paper letter are **not verified** here. What the primary sources do establish about what you will see:
  - The FLHSMV Driver License Check (DLCheck) status screen for this sanction reads: "COURT SUSPENSION, COURT REQUIREMENTS MET" (after compliance) and, while suspended: "Your driving privilege **HAS BEEN SUSPENDED** for failing to pay traffic tickets in the time allowed. A $60.00 reinstatement fee is required." — https://services.flhsmv.gov/DLCheck/SanctionHelpPages/Sanction03Help.aspx
  - The DLCheck "pending court suspension" help page tells you what documentation counts: "A **D-6 clearance form** with stamped court seal (provided at the time of payment)" or "A letter from the court stating the ticket number, date of payment and having a stamped court seal." — https://services.flhsmv.gov/DLCheck/SanctionHelpPages/Sanction01Help.aspx
  - FLHSMV's D6 sanction types include: "D6 - FAILED TO APPEAR ON TRAFFIC SUMMONS," "D6 - FAILED TO COMPLETE CT ORDERED SCH," "D6 - SCHOOL ELECTED WHEN NOT ELIGIBLE," "D6 - FAIL TO COMPLY TRAFFIC SUMMONS," "D6 - FAILED TO PAY TRAFFIC FINE (PENALTY)," "D6 - CRIMINAL-FAIL TO PAY," "D6 - CRIMINAL-FAILED TO APPEAR," "D6 - SCH ELECTION MADE FAILED TO ATTEND." — FLHSMV Technical Advisory DL19-021, https://www.flhsmv.gov/pdf/bulletins/2019/DL19-021_RSTL19-016_update.pdf
  - FLHSMV's own summary: the license "will be suspended indefinitely" for failure to pay or comply until court requirements are met. (Reference § 4; FLHSMV site study Part 0 § 6.)
- **Check your status online rather than waiting for mail:** FLHSMV Driver License Check at https://mydmvportal.flhsmv.gov/Home/en/PublicWeb/DLCheck — enter your Florida driver license number. The Manatee County Tax Collector's FLHSMV-derived help page (not a primary source, used here only for the pointer) confirms the same route: "If you don't know in which county you received your citation, visit mydmvportal.flhsmv.gov/Home/en/PublicWeb/DLCheck to locate this information."

## E.3 Timeline, worked end to end (civil track, § 318.15)

1. **Day 0 — offense date.** The citation is issued.
2. **Day 30 — must-comply deadline.** Pay, elect school, or request a hearing. If you do nothing, you have failed to comply. (Reference § 8 for the day-counting; safe deadline for the Oct 24, 2026 ticket is Mon Nov 23, 2026.)
3. **Within 10 days after the failure — clerk notifies FLHSMV.** "The clerk must notify the Department of Highway Safety and Motor Vehicles of such failure within 10 days after such failure." — § 318.15(1)(a)
4. **FLHSMV issues the order of suspension immediately on receipt.** It is effective **20 days after the date the order is provided** under § 322.251. — § 318.15(1)(a)
5. **Effective date — you are suspended from that date until you clear it.** The suspension is indefinite: it lasts until the court requirements are met. There is no fixed end date.
6. **Even after suspension, you can still request a hearing on the underlying infraction within 180 days of the violation date** — § 318.15(1)(c); see C.3. Requesting the hearing does not by itself lift the suspension; you must also satisfy the court requirements (see E.4).
7. **If the failure was a school election you did not complete:** you are deemed to have admitted the infraction and are adjudicated guilty, must repay the 18% reduction plus a processing fee of up to $18, and points are assessed. — § 318.15(1)(b) (reference § 4).

## E.4 Reinstatement, step by step

### Step 1 — Satisfy the court requirements (with the clerk, not FLHSMV)

- Contact the Clerk of Court in the county where the citation was issued. Pay the fine and any late/delinquent fees, or complete whatever the court required (payment plan, school, appearance). — § 318.15(2): no reinstatement until the person complies with a payment plan or with all obligations/penalties under § 318.18.
- **Broward:** pay online (entire amount due), by mail to P.O. Box 14610, Fort Lauderdale, FL 33302-4610, or in person at a Traffic service location; or call (954) 831-6565 option 1, 8:00 a.m.–3:30 p.m. Mon–Fri. If a not-guilty plea was entered and the case has not gone to court, fines may not be paid online — pay in person or by mail. — https://www.browardclerk.org/Divisions/TrafficAndMisdemeanor
- **Keep the D-6 clearance form.** "Be sure to keep the **D-6 clearance form** you will receive when you make your payment." — https://services.flhsmv.gov/DLCheck/SanctionHelpPages/Sanction01Help.aspx
- **If you paid before the suspension's effective date:** the suspension can be avoided entirely. FLHSMV's pending-suspension help page: "The court has not notified us that you have handled this matter. Please provide court documentation so we can update your record and the suspension can be avoided." Acceptable documentation: a D-6 clearance form with stamped court seal, or a court letter stating the ticket number and date of payment with a stamped court seal. Take it to your local driver license office or fax it to (850) 617-3917, with your name and driver license number included; allow 3–5 days for the record to be updated, then re-check DLCheck. — Same source.

### Step 2 — Get the clearance to FLHSMV

- **Broward clearances are electronic.** Broward is on the list of counties from which only electronic clearances are accepted — paper clearance forms are **not** accepted from Broward. The clerk transmits the clearance electronically to FLHSMV (via TCATS/CCIS). — UTC Manual § 12.2; FLHSMV site study Part 0 § 6 ("Clearance is electronic from the county").
- How the manual describes it: when the defendant has satisfied the requirements, "a clearance or reinstatement may be transmitted via TCATS." Two codes exist: **Clearance** — defendant paid the citation after the suspension date, and the court has **not** collected the reinstatement fee of up to $60.00 (code "34," "Court Requirements Met"); **Reinstatement** — the court **has** collected the reinstatement fee of up to $60.00, or the defendant satisfied the court requirement **prior to** the suspension date. — UTC Manual § 12.2
- **Allow 48 hours** after payment, then re-check DLCheck to verify the court has updated your record. "If it has not cleared, fax the D-6 Clearance form to (850) 617-3917 and allow 3-5 days before revisiting this site to verify clearance." — https://services.flhsmv.gov/DLCheck/SanctionHelpPages/Sanction01Help.aspx
- The manual notes FTC processing "may take up to two weeks" and encourages clerks to collect all required fees and reinstate the defendant online through CCIS; if the court does not reinstate through CCIS, it should give the defendant a paper clearance. Processing through TCATS alone "will delay the reinstatement of the defendant's driving privilege." — UTC Manual § 12.2

### Step 3 — Pay the $60 reinstatement fee

- **$60.00, nonrefundable.** "No reinstatement until the person complies … and presents a court certificate of compliance together with a nonrefundable service charge of $60 imposed under s. 322.29." — § 318.15(2). FLHSMV's fee schedule lists: "D-6 Suspension - DHSMV $60.00." — https://www.flhsmv.gov/fees/
- **Where to pay:** "You can pay the reinstatement fee at your local driver license office or send a check for $60.00 made out to DDL to: DDL-BDI, PO Box 5775, Tallahassee, FL 32314-5775." — https://services.flhsmv.gov/DLCheck/SanctionHelpPages/Sanction03Help.aspx
- FLHSMV also lists phone payment at (850) 617-3000 (established in the FLHSMV site study, Part 0 § 6, from the sanctions help pages).
- **Broward Clerk can also reinstate:** the Broward Clerk's Driver License Check page states: "If you have a physical driver license and have resolved all outstanding suspensions, you can reinstate your license through the Clerk of Courts website" and "To reinstate a suspended license using this site, you must have at least one paid Broward County citation, and you must have paid or resolved all outstanding citations and obligations." — https://www.browardclerk.org/Web2/DriverLicenseCheck (via search-indexed copy; the live page notes the reinstatement purchase service was "currently unavailable" at crawl time — check live before relying on it). The Manatee help page (secondary, for the pointer only) describes the same option as "Request that the Clerk of Court reinstate your driver record at the same time you satisfy the court requirements."
- **One $60 fee per D6 suspension.** Each unresolved obligation creates its own D6 suspension; multiple counties or multiple citations mean multiple clearances and multiple $60 fees. (The per-suspension fee is established in the FLHSMV fee schedule and § 318.15(2); the "one fee per suspension" reading is consistent with the FLHSMV child-support sanction page, which charges $60 per suspension — $120 for two, $180 for three — https://services.flhsmv.gov/DLCheck/SanctionHelpPages/Sanction13Help.aspx — but the per-D6 count is **not separately verified** on a primary D6 page and is flagged as such.)
- **Do not confuse the $60 D6 fee with the $45 general suspension fee** on the FLHSMV fee schedule. They are different fees. — https://www.flhsmv.gov/fees/ (FLHSMV site study Part 0 § 9).

### Step 4 — Verify you are reinstated, and do not drive until you are

- Re-check DLCheck (https://mydmvportal.flhsmv.gov/Home/en/PublicWeb/DLCheck) after the 48-hour / 3–5-day windows above. Do not drive on the assumption that payment alone restored you — the clearance must reach FLHSMV and the fee must be paid.
- Driving while the suspension is in effect is a moving violation if unknowing, and a crime if knowing. — § 322.34 (reference § 16).

## E.5 What stays on the record afterward

- **The D6 suspension entry:** "D-6 suspensions (failure to comply) once cleared, remain on the record 1 year from the reinstatement date and are then converted to a correspondence entry for 2 more years. Once this D6 entry converts to a correspondence entry it does not appear on 3- or 7-year driver records (transcripts)." On a complete record the correspondence entry does appear. — FLHSMV Questions About Driving Records (FLHSMV site study § 1.15).
- **An unreinstated suspension** stays on FLHSMV records for 7 years after the date imposed, then is removed. — § 318.15(1)(a) (reference § 4).
- **The underlying disposition stays too.** If the ticket ended in a guilty adjudication (including the school-failure track), that disposition is retained under FLHSMV's retention schedule — most guilty dispositions 3–5 years; school-election adjudication-withheld entries 75 years on the complete record. If it ended in withheld adjudication via a valid school election, the withhold entry is retained 75 years on the complete record but shows no points. — FLHSMV Questions About Driving Records (reference §§ 6, 19).
- **No hardship license for this suspension.** FLHSMV site study Part 0 § 6: "No hardship license for traffic-citation/court suspensions."
- **Re-suspension is possible on the same citation.** If the first suspension is reinstated and the defendant fails again (e.g. a check bounces after paying), the court must fully reinstate the first suspension before transmitting a new one, with a re-issue flag and re-issue date. — UTC Manual § 12.1(c).

---

# Unverified / flagged items (do not assert as fact)

1. **How the 18% reduction is displayed in the Broward Fine Payment portal** (line item vs. already-reduced total). The reduction itself is verified (§ 318.14(9)); the display is not. — § B.4.
2. **Click-by-click field sequence inside the Broward Fine Payment (Web2) portal.** The Clerk's pages describe what the service does; a live transaction was not completed. — § B.5.
3. **What happens step by step at a Broward Zoom pretrial conference** (who attends, what the hearing officer can order there). Not stated on the Broward pages read. — § C.3.
4. **Conditional Plea compliance period: 60 days (administrative order) vs. 120 days (the form itself).** Both quoted; unresolved. Follow the disposition order actually received; treat the shorter period as safe. — § C.4.
5. **Full text/fields of the FLHSMV D6 order-of-suspension letter.** No specimen was found in primary sources. What DLCheck displays and what the D6 clearance form must contain are verified instead. — § E.2.
6. **One $60 fee per D6 suspension (multiple suspensions).** Consistent with the fee schedule and the per-suspension child-support page, but not separately verified on a primary D6 page. — § E.4, Step 3.
7. **Broward Clerk online driver-license reinstatement availability.** The Clerk's page said the purchase service was "currently unavailable" at crawl time. Check live before relying on it. — § E.4, Step 3.
8. **OTR short-notice warning** ("you are responsible for your case until an attorney accepts it") was read on the **staging** host of OTR's KB (staging.offtherecord.com), not the live host. Same OTR text, different host — flag as staging-hosted. — § D.5.
9. **Administrative Order 2025-33-CO** was read via a search-indexed copy on flexlaw.co, a document mirror, not from the Seventeenth Judicial Circuit's own site. The order text is quoted from that copy. — § C.4.
10. **FLHSMV Traffic Citations page 18% language** was read via a search-indexed copy during the FLHSMV site study (the live page 429'd). — § B.4.
11. **UTC Procedures Manual hosting:** the manual is FLHSMV's own publication (Division of Motorist Services, Bureau of Records, rev. Dec 2022), but the copy read was hosted on floridalel.info, not flhsmv.gov. Field numbers and procedures are quoted from that copy. — § A.

---

# Source list (all URLs cited above)

- https://www.browardclerk.org/Divisions/TrafficAndMisdemeanor
- https://www.browardclerk.org/Web2/CaseSearchECA/
- https://www.browardclerk.org/Web2/DriverLicenseCheck
- https://web.browardclerk.org/PDF/TrafficandMisdemeanor/ConditionalPleaofNoContest.pdf
- https://www.floridalel.info/documents/FLHSMV_UTC_Manual_2022.pdf
- https://www.flhsmv.gov/fees/
- https://services.flhsmv.gov/DLCheck/SanctionHelpPages/Sanction01Help.aspx
- https://services.flhsmv.gov/DLCheck/SanctionHelpPages/Sanction03Help.aspx
- https://services.flhsmv.gov/DLCheck/SanctionHelpPages/Sanction13Help.aspx
- https://mydmvportal.flhsmv.gov/Home/en/PublicWeb/DLCheck
- http://www.flhsmv.gov/FHP/traffic/
- https://www.flhsmv.gov/pdf/bulletins/2019/DL19-021_RSTL19-016_update.pdf
- https://www.leg.state.fl.us/statutes/index.cfm?App_Mode=Display_Statute&Search_String=&URL=Ch0316/Sec650.htm
- https://www.flhouse.gov/Statutes/2020/0322.245/
- https://offtherecord.com/attorney-terms-and-conditions
- https://offtherecord.com/kb/articles/what-to-expect-after-you-book-a-case-off-the-record
- https://offtherecord.com/kb/articles/how-card-holds-work
- https://offtherecord.com/kb/articles/otr-cancellation-policy-explained
- https://offtherecord.com/kb/articles/what-happens-if-an-attorney-declines-your-case
- https://offtherecord.com/kb/articles/attorney-withdrawal-case-reassignment
- https://offtherecord.com/kb/articles/otr-success-rate-explained
- https://offtherecord.com/lawyers/fl/attorney-jorge-gonzalez
- https://get.offtherecord.com/kb/articles/counter-offers-explained
- https://staging.offtherecord.com/kb/articles/can-i-still-book-a-case-if-my-court-date-is-tomorrow
- https://brochure-devo.offtherecord.com/faq
- https://flexlaw.co/court-doc/9570/pdf
