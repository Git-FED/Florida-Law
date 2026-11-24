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
