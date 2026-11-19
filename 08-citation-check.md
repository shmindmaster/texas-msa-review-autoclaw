# Independent citation check: Texas MSA review package

Checked 2026-11-19, independently of AutoClaw's own audit (`05-citation-audit.md`). Every item was read in its primary source:

* Statutes: the Texas Legislature's statute file server (`tcss.legis.texas.gov/resources/<CODE>/htm/...`), which statutes.capitol.texas.gov serves from, and bill text on capitol.texas.gov.
* Cases: full opinion text from the Harvard Caselaw Access Project, which scans the official reporters (`static.case.law`).
* Federal statute: Cornell LII.

I re-read Marsh, Sheshunoff and Reyes myself.

**Result:** the audit lists 35 items: 20 statutes, 11 cases and 4 claims that a law or case doesn't exist.

* **3 are wrong.**
* **17 need a correction or caveat.**
* **15 are correct as written.**

The audit covers every citation in the playbook, redline and memo; none is missing from it.

## Wrong: fix before anything is shared

| # | Citation | Problem | Fix |
|---|---|---|---|
| 1 | Marsh USA Inc. v. Cook, 354 S.W.3d 764 (Tex. 2011), cited in Playbook NCO-3, Redline R-1 and Memo (non-compete row) | The package says the opposite of what the case holds. Marsh **rejected** Light's requirement that the consideration "give rise" to the interest in restraining competition, calling it "not anchored in the text of the Act." The test is that the consideration must be **reasonably related** to a protectable interest such as goodwill; stock options were enough. No case reviewed says "confidential information alone is not enough." | Rewrite NCO-3: "The consideration need not give rise to the interest being protected; it must be reasonably related to an interest the Act protects, such as goodwill or confidential information (Marsh). An express disclaimer that the covenant is not tied to any such interest removes the link the Act requires." Delete "confidential information alone is not enough." |
| 2 | Alex Sheshunoff Mgmt. Servs., L.P. v. Johnson, **124 S.W.3d 313 (Tex. 2003)**, in Playbook NCO-3 | Wrong citation. 124 S.W.3d 313 is a page inside *Mabrey v. SandStream, Inc.* (Tex. App.–Fort Worth 2003), an unrelated case. | **209 S.W.3d 644 (Tex. 2006).** The holding as described (an employer's later-performed promise, such as providing confidential information, can support a covenant) is correct for the 2006 decision. |
| 3 | Storage & Processors, Inc. v. Reyes, 134 S.W.3d 190 (Tex. 2004), cited for "conspicuousness is a question of law," in Playbook IND-2, Redline R-2 and Memo (indemnity row) | Reyes does not hold that. It extends fair notice to waivers in non-subscriber benefit plans and treats actual knowledge as an affirmative defense. | Cite **Dresser, 853 S.W.2d at 509** for "compliance with fair notice is a question of law." Reyes may stay for "the court has resisted expanding fair notice beyond extraordinary risk-shifting." |

## Correction or caveat needed

| # | Citation | What to change |
|---|---|---|
| 4 | Tex. Bus. & Com. Code ch. 552 / § 552.001 (TRAIGA) | HB 149 enacted a new Subtitle D, "Artificial Intelligence Protection," with **chapters 551–554**. Chapter 552 and § 552.001 ("deployer," "developer") are correct, but don't present chapter 552 as the whole Act. Cite § 551.001 for "artificial intelligence system." The effective date of Jan. 1, 2026 is confirmed. |
| 5 | Tex. Fin. Code ch. 303 (memo, usury) | Chapter 303 is titled **"Optional Rate Ceilings,"** not the maximum-rate chapter. The general 10% ceiling is **ch. 302, § 302.001(b)**. Cite both, or ch. 302 alone. |
| 6 | Tex. Ins. Code § 151.102 | It voids indemnity for the indemnitee's "negligence or fault," statutory breach or breach of contract, not only its "own negligence." It applies only through **§ 151.101**, where the indemnitor has insurance subject to the chapter, and has exceptions in **§§ 151.103 and 151.105**. On scope: § 151.001(5) covers "maintenance of … [an] improvement to … real property." Equipment fixed to the building could qualify, so keep the item flagged for an attorney. |
| 7 | Tex. Civ. Prac. & Rem. Code ch. 127 | The official title is "Indemnity Provisions in Certain Mineral Agreements." "Oilfield Anti-Indemnity Act" is a popular name only. |
| 8 | Tex. Bus. & Com. Code § 15.52 (and § 15.50(a)) | The 2025 amendment (S.B. 1318, eff. Sept. 1, 2025) added § 15.501. Section 15.52 now preempts other law for the criteria in §§ 15.50 **and 15.501** and for the § 15.51 procedures and remedies, and § 15.50(a) now opens "subject to … Section 15.501." Mention the current text. |
| 9 | Tex. Bus. & Com. Code ch. 541 | The codified chapter is titled "Consumer Data Protection." "Texas Data Privacy and Security Act" is the name from H.B. 4 (88th Leg.). § 541.055(e) took effect Jan. 1, 2025; the rest took effect July 1, 2024. |
| 10 | Light v. Centel, 883 S.W.2d 642 (Tex. 1994) | Correct as cited, but say that Sheshunoff (2006) relaxed its timing rule and Marsh (2011) rejected its "give rise" prong. |
| 11 | Mann Frankfort v. Fielding, 289 S.W.3d 844 (Tex. 2009) | Correct as cited. Its restatement of Light's "give rise" prong was later displaced by Marsh. |
| 12 | Crim Truck & Tractor v. Navistar, 823 S.W.2d 591 (Tex. 1992) | Crim is a special-relationship holding about franchises. For the general rule that no duty of good faith is implied in ordinary contracts, add **English v. Fischer, 660 S.W.2d 521 (Tex. 1983)**. I did not read English myself; check it before relying on it. |
| 13 | DeSantis v. Wackenhut, 793 S.W.2d 670 (Tex. 1990), with In re AutoNation, 228 S.W.3d 663 (Tex. 2007) | Both are correct. DeSantis applies Texas law through a Restatement § 187 analysis on its facts; the override isn't automatic. AutoNation enforced a Florida forum clause in a Texas non-compete. Note the tension: the governing-law and venue points cut different ways. |
| 14 | In re Prudential, 148 S.W.3d 124 (Tex. 2004) | Correct. The waiver must be knowing and voluntary; in that case there was a commercial lease, a bold caption and tenants with counsel. |
| 15 | Negative claim: no Texas Supreme Court case on fair notice for limitation-of-liability clauses | The claim is plausible but couldn't be proven without a citator. Add **Green Int'l, Inc. v. Solis, 951 S.W.2d 384 (Tex. 1997)**: Dresser is "explicitly limited to releases and indemnity clauses," and conspicuousness doesn't apply to no-damages-for-delay clauses. Also say some courts of appeals have applied fair notice to limitation clauses. |
| 16 | Negative claim: no Texas B2B auto-renewal notice statute | Confirmed by searching all 28 codes. The 2025 subscription bills (SB 838, HB 2859, HB 860) died in committee and were consumer-only. Special sessions and the Administrative Code were not searched. |

## Correct as written (15)

* **Business & Commerce Code:** Tex. Bus. & Com. Code §§ 15.51(c), 26.01(b)(6), 272.001 and 521.053 (250 residents; AG notice within 30 days).
* **Civil Practice & Remedies Code:**
  * § 15.020 ($1 million threshold)
  * §§ 38.001–.002 (2021 amendment H.B. 1578)
  * ch. 134A (S.B. 953, 83rd Leg.)
  * §§ 134A.002, 134A.003 and 134A.004
* **Other statutes:** Tex. Prop. Code ch. 28, and 18 U.S.C. § 1833(b).
* **Cases:** Ethyl Corp. v. Daniel Constr. Co., 725 S.W.2d 705 (Tex. 1987); Dresser Indus. v. Page Petroleum, 853 S.W.2d 505 (Tex. 1993).
* **TRAIGA effective date:** Jan. 1, 2026.

The 17 caveat items break down as follows:

* **8 statutes:** ch. 552, § 552.001, Fin. Code ch. 303, Ins. Code § 151.102, CPRC ch. 127, § 15.52, § 15.50(a) and ch. 541.
* **6 cases:** Light, Mann Frankfort, Crim, DeSantis, AutoNation and Prudential.
* **3 negative claims:** the limitation-of-liability case, the B2B auto-renewal statute, and the reach of ch. 151 to equipment maintenance.

## Fixes applied (2026-11-19)

Every fix above has been applied in new `-v2` files. The originals are unchanged.

* **`02-texas-baseline-playbook-v2.md`**
  * NCO-2: § 15.52 amended in 2025.
  * NCO-3: Marsh rewritten; Sheshunoff 209 S.W.3d 644; Light and Mann Frankfort caveats.
  * IND-2: Dresser at 509; Reyes's actual holding.
  * IND-3: §§ 151.001(5), 151.101, 151.103 and 151.105.
  * GOV-1: DeSantis § 187 analysis.
  * GOV-2: AutoNation; the New York forum clause is likely to be enforced, so strike it in negotiation.
  * REN-1 and PAY-1: English v. Fischer.
  * PAY-1: Fin. Code § 302.001(b).
  * LOL-1: Green Int'l v. Solis.
  * DATA-1: TRAIGA chs. 551–554, § 551.001; ch. 541 title.
  * Closing notes: ch. 127 official title; Green Int'l.
* **`03-redline-v2.md`** and **`03-redline-v2.docx`**:
  * the same citation fixes in R-2 (Reyes, § 151.101), R-3 (forum clause), R-4, R-6 and R-7 (English v. Fischer), R-8 (TRAIGA, ch. 541) and the jury-waiver note (Prudential standard)
  * all 25 tracked insertions and 17 tracked deletions in the Word file are preserved
* **`04-risk-memo-v2.md`**, **`.docx`** and **`.pdf`**:
  * the same fixes in the issues table and the attorney list (§ 151, Green Int'l, TRAIGA chapters, Fin. Code § 302.001(b) and ch. 303)
  * the PDF is 2 pages

Also checked in the primary source while applying the fixes: English v. Fischer, 660 S.W.2d 521 (Tex. 1983), and Green Int'l, Inc. v. Solis, 951 S.W.2d 384 (Tex. 1997), including the quoted words.

A scan of all v2 files finds none of the old errors: 124 S.W.3d 313, the "give rise" wording, "confidential information alone is not enough", a bare ch. 552, ch. 303 as the maximum-rate chapter, and the old jury-waiver wording.

Not changed: `01-fictional-msa` (it has no citations), `05-citation-audit.md` (this file replaces it) and `06-process-notes.md`.

Not legal advice. This is a citation check of fictional demo material.
