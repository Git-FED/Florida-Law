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

