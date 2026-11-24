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
