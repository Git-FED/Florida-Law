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
...[truncated 6151 chars]