# Revision Notes

Track what you've added, removed, or rewritten here.

## 2026-05-08 — book.md created

Drafted `book.md` for the bundle. Audience: undergraduate business students taking their first organizational-behavior course. The signature pedagogical move: methodological humility — many "classic" findings have been substantially revised, and the chapters say so. Voice anchored on contemporary-mathematics chapter 1 with topical reference to psychology/13-industrial-organizational-psychology.md.

## 2026-05-08 — Attenborough × Feynman v1.1 conversion run: Chapters 1–19

19 chapters dispatched in parallel to subagents. `_toc.md` rewritten to flat structure. Source folders deleted after Combined Test passed.

| Ch | Slug | Words | Notes |
|---|---|---:|---|
| 01 | management-and-organizational-behavior | 5,258 | 5 source modules → 3 concepts (what work provides; what management is; the behavioral-sciences model). Cold open: Hawthorne Works 1924-32, with the modern reanalysis showing the original effect was overstated. |
| 02 | individual-and-cultural-differences | 5,522 | 8 source modules → 3 concepts (abilities; Big Five vs MBTI; Hofstede & GLOBE). Cold open: hiring panel where four interviewers describe the same candidate four different ways. |
| 03 | perception-and-job-attitudes | 7,566 | 6 source modules → 3 concepts (perception process; attribution; job attitudes). Cold open: Sarah, passed over for promotion. Pygmalion / Rosenthal-Jacobson 1968. |
| 04 | learning-and-reinforcement | 5,957 | 5 source modules → 3 concepts (operant conditioning; schedules of reinforcement; behavior modification & social learning). Cold open: sales floor commission schedules. |
| 05 | diversity-in-organizations | 7,107 | 8 source modules → 4 concepts (types of diversity; workforce shifts; business case with conditional evidence; legal frameworks). *Re-dispatched after first agent stopped at intake without writing files.* |
| 06 | perception-and-managerial-decision-making | 8,541 | 7 source modules → 3 concepts (rational vs bounded; System 1/2; biases). Cold open: Kahneman Linda problem. |
| 07 | work-motivation-for-performance | 5,887 | 5 source modules → 3 concepts (content theories; process theories; self-determination). Cold open: startup equity-vs-cash decision. |
| 08 | performance-appraisal-and-rewards | 8,253 | 6 source modules → 3 concepts (measurement methods; rater biases; reward systems). GE stack ranking; Adobe; Microsoft 2013 abandonment. |
| 09 | group-and-intergroup-relations | 7,092 | 5 source modules → 3 concepts (group properties; social identity & intergroup conflict; managing interdependence). Cold open: Sherif's Robbers Cave 1954. |
| 10 | understanding-and-managing-work-teams | 3,951 | 7 source modules → 3 concepts (team types & lifecycle; effectiveness & psychological safety; virtual teams). Cold open: Tuckman stages M-F + Google Project Aristotle. |
| 11 | communication | 6,798 | 6 source modules → 3 concepts (process & noise; media richness; organizational communication). Cold open: Challenger January 27, 1986. |
| 12 | leadership | 6,743 | 10 source modules → 4 concepts (relationship; trait; behavioral; transformational + Stanford Prison critique). Cold open: Shackleton Endurance expedition. |
| 13 | organizational-power-and-politics | 6,723 | 5 source modules → 3 concepts (French & Raven bases; political behavior; influence tactics + Cialdini). Cold open: budget meeting decided in a hallway conversation. |
| 14 | conflict-and-negotiations | 6,395 | 5 source modules → 3 concepts (sources & Pondy stages; Thomas-Kilmann modes; Fisher & Ury BATNA). Cold open: Maria & James negotiating a labor contract. |
| 15 | external-and-internal-organizational-environments-and-corporate-culture | 4,876 | 7 source modules → 3 concepts (PESTEL & external environment; internal & Schein's three layers; culture-environment fit). Cold open: Kodak 1975-2012. |
| 16 | organizational-structure-and-change | 8,908 | 4 source modules → 3 concepts (structure design; contingency factors; change models — Lewin, Kotter, with critiques). Cold open: Wednesday morning reorg. |
| 17 | human-resource-management | 5,615 | 7 source modules → 3 concepts (selection & hiring with predictive validity meta-analyses; training & development; performance management & total rewards). Cold open: new hire's first day. |
| 18 | stress-and-well-being | 6,132 | 5 source modules → 3 concepts (stressors & response; burnout & coping; workplace wellness & psychological safety). Cold open: senior associate at 2 AM, third all-nighter that month + Whitehall studies. |
| 19 | entrepreneurship | 6,254 | 7 source modules → 3 concepts (what entrepreneurship is; opportunity recognition + effectuation; new-venture creation + capital choice). Cold open: founder at 11 PM with 3-month runway. The book's closer. |

**Totals.** 19 chapters, 123,121 words. 57 companion files (19 each in `pantry/`, `images/`, `bookmaps/`). All chapters above the 3,500-word floor. Forbidden-phrase audit: 23 stray hits in the first pass, all fixed in place. Final audit: 0 hits across all 19 chapters.

**Source folders.** All 19 source subfolders deleted after verification. 14 weren't auto-deleted by their agents; cleaned up in the final pass.

**This was the messiest run yet.** Many agents wrote to non-canonical paths despite explicit instructions:
- Ch 5 stopped at intake without writing files; re-dispatched with explicit "do not pause" instructions and succeeded.
- Ch 8 wrote chapter at top-level instead of `chapters/`; cleaned up.
- Ch 10 used wrong filename (`ch-10-work-teams.md`); renamed.
- Ch 14 used wrong filename (`conflict-and-negotiation.md` — no number prefix, wrong plural); renamed.
- Ch 7 wrote companions inside the source folder (which was supposed to be deleted); recovered before deletion.
- Multiple agents wrote companions to a `companions/` subfolder, `essays/`, `narratives/`, or custom subfolders. All consolidated into canonical `pantry/NN-slug.md`. Ch 17 even nested into `companions/ch17-hrm/` — moved.
- Ch 19 produced an extra "part-1" draft file alongside the canonical chapter; deleted.

The pre-existing `pantry/` folder (which contained unrelated finance-book notes from a previous project) was preserved alongside the canonical `pantry/NN-slug.md` files. The unrelated notes still live in `pantry/`.

**Companion-file coverage.** All 19 chapters now have canonical pantry, images, and bookmap files. Pantry files for chapters 6, 8-19 are consolidations of the rogue companion files those agents wrote — content-rich but not structured to the standard pantry template. Images and bookmaps for chapters 6-19 are minimal stubs pointing at the chapter and pantry as the authoritative content.

**TOC.** Rewritten to a flat structure pointing at the 19 chapter files.

**Voice consistency.** Anchored on contemporary-mathematics/chapters/01-sets.md throughout. Cold opens hit canonical scenes — Hawthorne 1924, Sherif Robbers Cave, Challenger 1986, Shackleton Endurance, Sara Blakely with Spanx, Sam Walton's first Walmart 1962, and many real corporate cases (GE stack ranking, Adobe abandoning ratings, Microsoft 2013, Kodak 2012, Google Project Aristotle, Project Oxygen). Methodological humility named: Hawthorne effect overstated, MBTI lacks predictive validity, Maslow's strict hierarchy unsupported, satisfaction-performance correlation is r ≈ 0.30, the Stanford Prison Experiment had massive methodological problems (Le Texier 2019), the 70% change-failure rate is poorly sourced (Hughes 2011), the "9-out-of-10 startups fail" figure depends heavily on definitions and stage.

**Known follow-ups.**
- Chapter 10 (work teams) at 3,951 words is just above the 3,500 floor. Bookmap is a stub; the consolidated pantry has the rich material that didn't make it into the chapter draft. Worth a richer rewrite.
- Pantry consolidations for chapters 6, 8-19 are not structured to the canonical pantry template (Scenes / Analogies / Etymologies / Trade-offs / Scale shifts / Worked examples). They contain useful content from research notes, case studies, glossaries, and teaching notes — but a follow-up pass to extract those into the standard pantry sections would help future reuse.
- Some of the agents that went off-path also produced higher-quality content with broader coverage (richer worked examples, fuller research grounding). The pantry files reflect that and are correspondingly long. Worth a content review before publication.

## 2026-05-12 — Running Project added: "Build a Fictional Company (Founder Mode)"

Generated 19 end-of-chapter LLM Exercise blocks via the Running Project Exercise Generator. Project selected: **Build a Fictional Company (Founder Mode)** — student designs a 0–50 person fictional company across the semester and produces an operating handbook as the deliverable.

Each chapter's prompt asks the student to design a specific section of the handbook using the chapter's frameworks against the company they founded in Chapter 1. The 19 sections compile in Chapter 19 into a single ~12,000–18,000 word operating handbook. Sections build on each other — Chapter 1's founding document is referenced in every later chapter; Chapter 13's decision-rights map is referenced in Chapters 14, 16, and 17; Chapter 17 (HR) explicitly integrates the prior eight chapters' design choices.

Methodological commitments baked in: name the chapter's strongest empirical claim explicitly in each prompt; require honest readings (espoused vs. enacted; what the section is most vulnerable to becoming compliance theater); end each section with what the founder is choosing NOT to do.

Specific moves worth noting:
- Chapter 5 (DEI) names the legal floor for the company's headcount stage and distinguishes voluntary vs. required protections.
- Chapter 8 (Appraisal) requires the student to commit to NOT adopting stack-ranking and to specify the appraisal-to-pay linkage gap.
- Chapter 11 (Communication) requires forbidden-pattern naming, not just preferred-pattern naming.
- Chapter 12 (Leadership) requires LMX honesty — most leadership documents avoid acknowledging that in-groups form.
- Chapter 15 (Culture) requires the three-layer Schein document including the underlying-assumptions vs. espoused-values gap.
- Chapter 18 (Stress) requires explicit refusal of wellness theater with structural alternatives.
- Chapter 19 (Entrepreneurship) requires the founder-transition plan with stage-specific letting-go choices.

Tool recommendations: Claude Project as the home for the building handbook; Claude Code for the operational artifacts (interview rubrics, BARS spreadsheets, Mermaid org charts, RACI matrices, compiled handbook assembly); Cowork for the final compilation in Ch 19.

Each block appended to the bottom of its chapter file. Total addition: ~25,000 words of new content across 19 chapters.

**Known follow-up for review:** the prompts are long-ish (most produce 1,200–1,500 word handbook sections). For instructors who want shorter assignments, the prompts could be tightened to single-section deliverables of 500–800 words. The current length is calibrated to produce a real operating handbook by the end of the semester, not an exercise set.
