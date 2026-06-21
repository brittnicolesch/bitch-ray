# Forensic Risk Triage Queue
**Status:** Queued for Router Processing
**Router Target:** `forensic-risk-triage-router`

This queue holds target candidates extracted from the Master Dossiers and Trumpstein Canvas (`canvas_49dac09f.md`). Each packet is structured to pass FORGE LAW criteria before being routed to specialized sub-skills.

---

## Target 001: The Leon Black / AIPAC / MIT Commitment Funnel
**Candidate Packet:**
- **Identity:** Leon Black Family Foundation, Inc. / Leon Black
- **Source:** `canvas_49dac09f.md` (Leon Black Commitments - CHARITY spreadsheet prepared by R JOSLIN)
- **Timestamp:** Dec 23, 2014
- **Excerpt:** `AIPAC 1,250,000 (500,000) 750,000 250,000 250,000 250,000 Multi-Year` ; `MIT MEDIA LAB 5,000,000 5,000,000 P 4,000,000 1,000,000`
- **Hash:** `SHA256:7zu6_EFTA02371754_pdf` (extracted from raw canvas metadata)
- **Coverage Proof:** Found natively within internal leaked files; FARA/FEC cross-referencing pending.
- **Counterevidence:** Leon Black has claimed to have severed ties with Epstein; MIT claims they were unaware of specific donor origins for certain funds.
- **Forbidden Inference:** We may not declare that these donations were directly ordered by foreign intelligence; we may only note the structural overlap with the `#information-warfare` timeline.
- **Recommended Route:** `osint-corporate-risk-mapper` (Network/Related-Party mapping).

---

## Target 002: The Wexner / C.O.U.Q. / YLK Charity Loop
**Candidate Packet:**
- **Identity:** The Wexner Foundation / C.O.U.Q. Foundation / YLK Charitable Fund
- **Source:** `canvas_49dac09f.md` (Extracts referencing Richard Kahn and Ehud Barak transfers)
- **Timestamp:** 2001 - 2008
- **Excerpt:** `In 2001, Mr. Epstein transferred approximately 9 million USD to the Wexner Foundation. During the years 2004-2006, the Wexner Foundation transferred at least 2.3 million USD to the Israeli former Prime Minister Ehud Barak.` ; `C.O.U.Q. contributed $46 million in stock and other assets to Wexner's YLK Charitable Fund in 2008, just before Epstein started his Palm Beach jail sentence.`
- **Hash:** `SHA256:z7sl_EFTA01463151_pdf`
- **Coverage Proof:** FARA filings and bank transfer logs mentioned in the FBI/DOJ extraction notes.
- **Counterevidence:** Wexner claimed he severed ties with Epstein in 2007 and was defrauded; the $46M transfer could be argued as a "return" of embezzled funds.
- **Forbidden Inference:** We may not declare the $2.3M payment to Barak as an illegal political bribe without corresponding Israeli banking receipts.
- **Recommended Route:** `forensic-legal-engine` (Money laundering and FARA violation issue-spotting).

---

## Target 003: Political PAC Funnels (The South Carolina Vulnerability)
**Candidate Packet:**
- **Identity:** Lindsey Olin Graham Campaign Committee / Turning Point PAC / Buckeye Values PAC
- **Source:** `lindsey_graham_timeline_crosswalk.csv` / `canvas_49dac09f.md`
- **Timestamp:** Sept 1, 2016 - 2019
- **Excerpt:** `On September 1, 2016, Epstein asked to prepare a check to donate $75,00...` ; `He's the best!!! $2600 limit per person to me [REDACTED] (your email should read committee not campa...)`
- **Hash:** `SHA256:pending_fec_pull`
- **Coverage Proof:** Explicit FEC compliance discussions found in internal emails.
- **Counterevidence:** The PAC donations might be legally distinct from direct campaign contributions, offering a "firewall" of deniability for the politicians involved.
- **Forbidden Inference:** We cannot declare that the political flip was *exclusively* due to these specific donations without factoring in the hacked emails / honey-trap blackmail vectors.
- **Recommended Route:** `forensic-legal-engine` (Campaign finance violation checks) AND `osint-corporate-risk-mapper`.
