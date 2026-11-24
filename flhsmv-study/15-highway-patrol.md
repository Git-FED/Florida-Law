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
