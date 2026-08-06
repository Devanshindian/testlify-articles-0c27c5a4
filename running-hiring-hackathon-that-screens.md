# Hackathon Judging: A Rubric and AI-Use Policy for Hiring

Hackathon judging works as a hiring screen only when you pair the timed build challenge with two things: a weighted scoring rubric and an explicit policy on AI use. Without both, you're measuring judge preference and undisclosed tools, not candidate skill. This guide provides the rubric, the policy, and the calibration steps to make your hackathon assessments fair, defensible, and repeatable.

## What Makes a Hiring Hackathon a Valid Skills Test?

Unlike public prize hackathons or internal innovation events, a hiring hackathon's purpose is producing a defensible skills signal. Because it asks candidates to build features in a realistic environment, it has a strong claim to being classified as a [work sample test](https://testlify.com/hiring-via-job-simulation/) [1]. That classification raises the stakes: the evaluation must withstand scrutiny, not just rank contestants.

## Why Hackathon Judging Without a Plan Fails

Running a hackathon without a structured hackathon judging plan yields scores that reflect the judge, not the work. Without a [defined framework](https://testlify.com/best-practices-for-designing-coding-assessments/), every project’s rating depends on which judge happened to watch it, not on what the candidate actually built [2]. The damage is hidden: one judge accepts a clickable prototype as proof of feasibility, while another demands evidence the idea was pressure-tested against a real workflow constraint. That disagreement stays invisible until judges compare notes side by side, typically during a calibration pass that forces them to score the same submission before live rounds begin [3].

Shared spreadsheets amplify the chaos. Two judges editing the same row, broken averaging formulas, an accidental sort losing everyone’s place: these routine failures hit by the second or third event [4]. When three judges assign scores of 3, 4, and 2 on a criterion, the arithmetic becomes another bottleneck: someone has to check it by hand, introducing averaging errors [5]. The process drifts further from evidence and closer to whoever argues loudest.

The fix begins before any scoring: define exactly what the score is meant to determine. Whether the goal is funding a pilot, spotting a promising concept, or identifying a team to champion internally, the criteria that matter shift with that answer [3]. Skip this step, and the entire judging process drifts into opinion. Once the decision is locked, a rubric can be built backward from it, ensuring every point ties to a defensible outcome, not a guess.

## Hackathon Judging Rubric with Anchored Score Descriptors

To build the rubric, start with the job description and pick 3 to 6 skills the hackathon exercise is meant to test [6]. Lock in criteria and weights before the event [6], then write an [anchor descriptor](https://testlify.com/how-to-evaluate-coding-assessments/) for each score band: Poor (1), Okay (3), and Great (5), so every judge applies the same standard [3]. Below is a sample hackathon judging rubric for a full-stack coding challenge.

| Criterion | Weight | Score 1 (Poor) | Score 3 (Okay) | Score 5 (Great) |
|-----------|--------|----------------|----------------|-----------------|
| Technical Execution | 25% [4] | Code fails to compile or produces incorrect output | Code runs but has poor readability, lacks tests, or contains moderate bugs | Correct, well-architected, includes tests and documentation; maintainable [7] |
| Innovation / Originality | 20% [4] | Solution is copy-pasted without adaptation; no novel element | A standard approach with minor tweaks; no substantial creativity | Novel approach that solves a real constraint and improves feasibility [3] |
| Completeness | 25% | Omits a critical part of required functionality  | Partially complete; missing non-critical features or edge cases  | Addresses all specified requirements and includes thoughtful extras  |
| Instruction Adherence | 20% | Ignores key instructions or submits off-task work  | Follows main instructions but misses a meaningful constraint  | Fully adheres to all explicit instructions and implicit rules  |

## Calibrate Hackathon Judging for Consistent Scores

A written rubric does not produce consistent scores on its own. Grading itself introduces its own systematic distortions, including position bias and verbosity bias. Even a well-built structured scoring approach only correlates moderately with independent human judgment, one widely cited method reached a Spearman correlation of just 0.514 against human graders on a summarization task, an improvement over prior automated methods but still well short of full agreement [8]. Because of these limits, a numeric rubric score functions best as one input to a human decision rather than the decision itself. A rubric-scored hackathon judging result is strongest as one input into a broader comparison rather than the sole basis for a hire.

The first structural defense is independent scoring. Judges should score privately and compare only after every candidate has been rated, so no single opinion anchors the room before the evidence has been examined [3]. Without it, senior or louder voices set the answer before quieter evidence gets weighed [3]. Independent scoring first is what keeps a senior voice in the room from setting the answer before everyone else has looked at the evidence themselves [3]. Because no single rater's judgment is fully reliable even after calibration, panels commonly pair calibration with structural redundancy: a second-reader policy for borderline scores, where another judge reviews the evidence independently before a close decision is finalized [9], plus multiple data points per candidate rather than relying on one judge's read of one artifact [10].

Calibration itself is a discrete step that runs before live hackathon judging opens, separate from writing the rubric. The rubric specifies what "great" looks like for the role, and calibration is where the panel proves everyone applies that specification the same way [11]. Skipping it is where hidden disagreement surfaces later, once it is expensive to fix.

A calibration session works in three moves. First, cover the scoring scale with concrete examples of what each level looks like, fielding questions until the panel uses the same vocabulary for the same behaviors [12]. Second, each judge reviews one or two anonymized sample submissions and scores them against the rubric with no discussion [12]. Third, judges' scores are displayed side by side in a read-only comparison grid after independent entry: no live shared spreadsheet that invites accidental edits or formula breaks. Where two judges gave the same submission a 1 and a 5 on the same criterion, that gap gets examined. The goal is not to force convergence on one score for the practice item. It is to find where the rubric's language is ambiguous and rewrite that language before the panel judges anyone for real [12]. Most teams find one or two criteria need sharper definitions every time they run this [12]. Calibration sessions on real or sample submissions routinely surface disagreement that a rubric's point values alone don't resolve.

The biases calibration is meant to catch are well documented. Judges tend to avoid extreme scores early in a sequence, to "leave room" in case something stronger appears later, producing an order bias where early performances get scored more harshly [13]. Judges are also subject to conformity bias, adapting their scores toward fellow panelists' scores, a pressure that is worse when a panel hasn't had the chance to build trust beforehand [13]. In one measured panel of seven trained judges in a related domain, scores reached an intraclass correlation coefficient of 0.981, evidence that judge training can produce reliable separation between performance levels [14]. That same dataset also showed a systematic national skew: some judges consistently scored harshest while others scored most generously [14], a concrete illustration of why a panel needs calibration rather than an assumption that trained judges will naturally converge. Related literature notes that raters higher in cognitive ability tend toward more severe ratings than their peers, one specific source of the leniency/severity spread calibration is designed to catch [15].

Measuring whether judges actually agree requires formal metrics. Cohen's kappa works for two reviewers; Krippendorff's alpha works when there are more than two raters or missing ratings [8]. Common convention treats an alpha at or above 0.800 as reliable, with 0.667 to 0.800 sometimes acceptable for tentative conclusions depending on the stakes of the decision [8]. In recruiting-specific practice, inter-rater reliability below 0.40 is treated as a signal of inconsistent evaluation, tracked monthly with dips investigated rather than ignored [9].

When two raters cannot agree, averaging the scores is the wrong fix. The right approach is to have each explain their rating using direct evidence from the submission: "the feeling of a score" is not an acceptable justification, only a cited behavior or artifact is [16]. When two reviewers disagree, use adjudication, a resolving discussion or a third reviewer, rather than defaulting to a majority vote or simple average, and track which specific rubric criteria generate the most reviewer-to-reviewer disagreement [17]. A criterion that repeatedly splits reviewers is either ambiguous and needs a rewritten anchor, or is subjective and needs a tighter definition or sub-criteria [17]. Keeping a written adjudication log, documenting the final decision and the reasoning whenever judges disagreed, converts each dispute into precedent: it becomes the playbook for the next ambiguous submission and the source material for the next rubric revision [8].

Calibration is not a one-time pre-event task. After repeated rounds on the same role, average scores tend to drift, either inflating ("everyone's a strong yes") or compressing ("everyone's a 3"), and both directions are bias signals rather than evidence of an improving panel. A recurring quarterly re-calibration session re-anchors scoring [12]. New judges added to a panel after the initial calibration should run an abbreviated version of the same exercise before scoring their first live submission [12]. Practical, low-overhead versions exist for panels that can't add a standing meeting: share three scored sample responses, have each judge rate them independently, then discuss the scores during an already-scheduled team meeting [9].

## Document Scores and Reasoning for Defensible, Auditable Hiring

A rubric is not a one-time artifact. Calibrated rubrics get sharper with each hiring cycle, and the upfront work amortizes across every future hire for that role [18]. But that only happens if the scores and reasoning are captured in a way that lets the hiring team refine them later. Capturing the reasoning behind each score, not just the number, is what makes that refinement possible. Reviewers should provide a short rationale and quote the specific evidence behind low scores, because a low score without a stated rationale is wasted signal [8]. Structuring the task as “explain your reasoning step by step, then conclude with a score” produces more accurate evaluations and leaves an audit trail that shows why a given score was given [19]. Defending a placement decision later requires more than the point total.

Building a scrutiny-proof scoring process means capturing a downloadable, [per-judge breakdown](https://testlify.com/what-is-an-interview-scorecard/) of score detail for every candidate, not just an aggregate leaderboard [4]. That breakdown shows exactly which judge scored which criterion how, so the panel never has to reconstruct reasoning from memory when a decision is challenged. A scoring model that holds up under scrutiny also requires explicit tie-break logic, a conflict-of-interest protocol, and an audit trail for every score [20]. Tools that automatically drop the high and low score per project prevent one outlier judge from silently swinging a shortlist [4].

Finally, give score and decision data a retention period tied to a reason, not an indefinite hold. One hackathon’s schedule kept qualifier scores and feedback through the appeals period, and held anonymous aggregate analytics for up to two years for program improvement [21]. For a hiring hackathon, keep rubric scores and AI-disclosure records long enough to support an appeal or a later “why didn’t we advance this candidate” conversation, and be explicit about the reason each category is retained. With calibrated scoring and auditable records in place, the only missing piece is a clear AI-use policy that preserves the integrity of the skills signal.

## Hackathon AI Use Policy: Tiers & Disclosure

A hiring hackathon without an explicit AI policy is measuring access, not skill. Candidates are already using AI: nearly half of job seekers used ChatGPT to generate resumes or cover letters, and 70% of those reported a higher response rate from employers [22]. Silence does not prevent AI use; it makes it undetected [22]. A hackathon submission is exactly the kind of artifact where that undetected use can mask a candidate’s ability. The tiers below translate the preparation-vs-substitution line into permission, disclosure, and scoring rules, so every submission is built under the same standard.

| Use Category | Permitted? | Disclosure Required? | Notes & Examples |
|---|---|---|---|
| AI-assisted boilerplate/scaffolding generation (e.g., React component scaffolding, Java class templates, REST API setup) [23] | Yes | Full AID disclosure (tool, task, extent, verification) | Boilerplate is commodity work, not the skill being tested. Candidate must verify output. |
| AI-assisted debugging and code review | Yes | Full AID disclosure | AI as an editing/scaffolding layer over the candidate’s own work. |
| AI-assisted feature development where candidate is architect: decomposes problem, directs AI, and verifies output  | Yes | Full AID disclosure (tool, specific tasks, extent, verification) | Candidate exercises the judgment the hackathon exists to test; prohibited if the whole prompt is handed to AI without oversight. |
| AI-generated entire submission or substantial logic without candidate oversight | No | N/A | Presenting AI-authored code as own capability is treated as plagiarism [24]. |
| AI-assisted documentation, write-up, or presentation, editing and polish only (grammar, clarity, formatting) | Yes | Light disclosure (confirm tool, tasks limited to polish, human review) | Editing/polishing use warrants a short confirming line [25]. |
| AI-assisted documentation where AI shapes content or analysis | Yes (with limits) | Full AID disclosure (tool, task, extent, verification) | Deeper AI involvement in the graded write-up requires itemized disclosure, not a generic note [25]. |
| Real-time AI coaching, answer generation, or prompting during live discussions or supervised assessments | No | N/A | Real-time substitution of judgment, a candidate producing a response that is “100% AI and not of their own thought” [26], signals they would shortcut job functions [26]. |
| Impersonation, deepfakes, synthetic voices, identity masking | No | N/A | Misrepresentation of identity. |
| AI use for research, learning, summarization during build phase (e.g., AI-powered documentation search) | Yes | AID disclosure (tool, purpose, extent) | Acceptable if disclosed; mirrors preparation use [27][24]. |
| Disclosure statement completeness (applies to all permitted uses) |, |, | A complete disclosure must name the tool and version/date, the specific task the AI performed, the extent of use (from single check to substantial drafting), and a statement that a human verified the output [25]. A vague or incomplete statement scores lower than an itemized one [25]. |

## AI Use Policy: Detect Undisclosed Use and Score Fairly

A policy that asks candidates to disclose AI use only works if the judging process does not punish them for doing so. Across 16 studies with more than 27,000 participants, texts labeled “written by AI” or “written by a human with AI assistance” received lower ratings than identical text labeled “written by a human”: the “AI disclosure penalty” [28]. The mechanism was perceived authenticity, not lower quality [28]. This means a written policy stating disclosed use “does not disadvantage” a submission [29] can still fail in practice unless judges are explicitly trained against it [29].

Undisclosed use carries a different consequence. Existing employer codes state plainly that failure to disclose, or deliberate misrepresentation, “may result in disqualification from the process” [24]. Real-world hiring policies pair prohibitions with an explicit disqualification warning [30]. Any detected, undisclosed use should trigger a defined point deduction or disqualification, stated in the rubric in advance [30].

Disclosed use, by contrast, is scored on what it reveals about the candidate’s process and judgment. A two-track scoring structure evaluates permitted AI use on execution quality (did the candidate direct, verify, and take ownership of the output) with no blanket penalty for the disclosure itself. The rubric should not ask judges to mark “AI used: yes/no”; it should score the behavior candidates demonstrate around AI, using named bands with observable descriptions. Every criterion needs anchored score bands and an evidence requirement [3], tracing each AI-use score to the specific prompt log, commit history, or disclosure statement that earned it [31].

The live discussion is the real verification step. A conversation verifies that the candidate understands the work behind their submission rather than merely turning in an AI-produced artifact [27]. That discussion, not a separate compliance check, catches undisclosed or misrepresented AI use. Where AI use is itself an evaluated competency (for example, observing how a candidate collaborates with an AI tool), the policy must set clear parameters so candidates know the boundary [27]. Vendors now shift scoring toward how a candidate specifies, verifies, and refines AI output rather than whether they used it [32].

Detection relies on specific tells, not vague suspicion. In written materials, repeated phrases, generic content, formatting inconsistencies, tone shifts, overly complex language, and similarities between multiple submissions are all signals [22]. Technical content that is “structured to score maximally” (volunteered Big-O analysis, STAR-format answers, or textbook citations dropped in) often points to AI assistance rather than organic reasoning [33]. Human-authored solutions typically show incremental decomposition, dead ends, and backtracking, while AI-generated submissions “appear fully formed” without that visible process [33]. A rubric that looks for evidence of iteration (commit history, documented trade-offs, notes on dead ends) therefore detects process gaming and undisclosed substitution without needing a separate compliance probe.

Judges who unconsciously penalize disclosed AI use undermine the entire policy. A rubric that lets judges freely down-score any submission acknowledging AI, without anchored criteria, risks penalizing transparency rather than measuring skill. The fix is to score disclosed behavior against specific bands (verification shown, ownership demonstrated, disclosure format complete) rather than letting a general reaction to “AI was involved” move the score. Calibration sessions must check that judges are not quietly re-introducing the penalty the policy claims not to apply.

Finally, enforcement rests on two distinct mechanisms: attestation and disclosure [22]. An attestation-only tier is effectively a prohibition with an honor-system check; a disclosure tier assumes some AI use is expected and makes the extent and quality of use the scored variable. Where the policy expects disclosure, compliance turns on whether the candidate described what they used and how, not on whether AI touched the work at all. All of this policy work sits on a legal foundation that hiring teams must account for when retaining and disclosing AI-use records.

## AI Use Policy: Disclosure Laws and Audit Trails

Existing law already treats AI-in-hiring disclosure as a baseline obligation. Illinois’ Artificial Intelligence Video Interview Act requires employers to disclose their own AI use [22], a structure that suggests employers could require candidates to do the same [22]. A hackathon’s judging process, where AI-assisted work feeds a scored, comparative evaluation, sits inside that same transparency expectation.

AI-hiring regulation increasingly requires explainable, per-candidate score breakdowns. An auditable AI-use scoring trail, linking each rubric band to specific evidence, gives a hiring team the same defensibility for the AI-use portion of the rubric that regulators expect for the screening process as a whole [34].

Key laws that set these expectations include the Illinois AI Video Interview Act, which mandates specific disclosure and consent before AI is used to analyze candidate video [35], and NYC Local Law 144, which requires annual bias audits and candidate notice for automated employment tools [36].

For data retention, under GDPR, recruitment records for unsuccessful candidates are typically kept 6 to 12 months and then must be deleted or anonymized [37]. AI-use disclosure logs are often limited to 90 days unless a legitimate business need justifies longer retention [38]. Under CCPA, candidate evaluation records may be retained for 4 years from the date the position is filled or the information is received [39]. Aligning hackathon score records and AI-disclosure logs with these timelines keeps your process compliant and audit-ready.

## Frequently asked questions

**Can hackathon scores alone decide who to hire?**

A rubric-scored hackathon result is strongest as one input into a broader comparison, not the sole basis for a hire. Because work sample tests show substantially lower adverse impact when scored on job-linked criteria [40], they provide a defensible signal, but they should be combined with interviews, reference checks, and other evidence to avoid over-relying on a single artifact.

**How do I ensure our hackathon judging process is legally defensible?**

Start by tying each rubric criterion to a job task through a structured analysis, satisfying the content-validity requirements of the Uniform Guidelines [40]. Then document per-judge score breakdowns, explicit tie-break logic, a conflict-of-interest protocol, and an audit trail of every score [20][4]. Finally, retain records for a duration mapped to relevant laws: 90 days for AI-disclosure logs under typical GDPR interpretations, and longer under CCPA. Be ready to produce explainable, per-candidate data [34][38][39].

**What happens if judges penalize candidates who disclose AI use?**

Research shows an “AI disclosure penalty” where disclosed AI-assisted work is rated lower despite identical quality [28], so a written policy promising no disadvantage can still fail in practice. Prevent this by building anchored score bands specifically for AI-use behavior: scoring verification, ownership, and disclosure completeness rather than a blanket AI-used flag [3]. Calibration sessions must then check that judges are not quietly re-introducing the penalty, and any score discrepancy traced to disclosure bias should be corrected [29].

**What should a complete AI disclosure statement include?**

A complete statement names the tool and version/date, the specific task the AI performed, the extent of use (from a single check to substantial drafting), and a verification that a human reviewed the output. Vague or incomplete statements score lower than itemized ones [25], and that disclosure record becomes part of the audit trail linking each AI-use score to concrete evidence [31].

**How often should we recalibrate our judges?**

Recalibrate quarterly: after repeated rounds, average scores tend to drift (inflating or compressing), so a quarterly re-anchoring session resets the scoring standard [12]. New judges added to the panel complete an abbreviated calibration exercise before scoring their first live submission [12]. Track inter-rater reliability monthly; a drop below 0.40 signals inconsistent evaluation that warrants investigation [9].

With a calibrated rubric and an AI-use policy, hackathon judging can produce a shortlist that holds up to scrutiny. Testlify extends that evidence-first logic across your entire hiring process: 3,500+ validated tests, conversational AI interviews, and 20+ proctoring measures that catch undisclosed AI use without treating every candidate like a suspect. Start a free 7-day trial (no credit card required) and see how scored skills change your shortlist.

## Sources

1. https://www.codility.com/assessment-validity/
2. https://taikai.network/en/blog/hackathon-judging
3. https://ai-beavers.com/blog/how-to-judge-hackathon-scoring-criteria
4. https://scorejudge.com/judging-software-for-hackathons/
5. https://leaderboarded.com/blog/posts/hackathon-leaderboard/
6. https://x0pa.com/glossary/work-sample/
7. https://www.shadecoder.com/topics/what-is-coding-challenge-a-practical-guide-for-2025
8. https://www.twine.net/blog/llm-evaluation-rubrics/
9. https://sapia.ai/resources/blog/interview-score-sheet-templates/
10. https://testlify.com/the-role-of-soft-skills-assessment-in-team-collab/
11. https://www.metaview.ai/resources/blog/create-effective-interview-scorecards
12. https://www.pin.com/blog/interview-debrief-guide/
13. https://www.flippeddecisions.com/post/calibration-in-gymnastics-judging
14. https://services.ncl.ac.uk/itservice/research/dataanalysis/advancedmodelling/measureofagreement/
15. https://pmc.ncbi.nlm.nih.gov/articles/PMC5385382/
16. https://www.scu.edu/provost/institutional-effectiveness/assessment/doing-assessment/using-rubrics/
17. https://galileo.ai/blog/calibrate-llm-judge-human-annotations
18. https://www.hiretruffle.com/blog/structured-vs-unstructured-interviews
19. https://kinde.com/learn/ai-for-software-engineering/best-practice/llm-as-a-judge-done-right-calibrating-guarding-debiasing-your-evaluators/
20. https://theinnovationmode.com/hackathon-toolkit
21. https://aihackathon.usaii.org/privacy-policy
22. https://www.klgates.com/Should-Job-Applicants-be-Permitted-to-Use-Artificial-Intelligence-3-27-2024
23. https://techexactly.com/blogs/how-ai-is-eliminating-repetitive-coding
24. https://careers.fidelityinternational.com/working-here-overview/candidate-code-of-conduct-use-of-artificial-intelligence-ai/
25. https://www.editage.com/blog/how-to-write-an-ai-disclosure-statement-examples-and-format-for-journal-articles-and-dissertations/
26. https://www.linkedin.com/posts/angelacroghan_i-recently-encountered-a-company-that-requires-activity-7421989499431194626-cEvE
27. https://www.staffingadvisors.com/blog/how-work-sample-tests-help-you-hire-better/
28. https://behavioraltimes.com/ai-disclosure-penalty/
29. https://aihackathon.usaii.org/terms-of-use
30. https://unchartedcareer.com/research/ai-interview-policies
31. https://www.sopact.com/use-case/competition-judging-software
32. https://www.linkedin.com/pulse/when-your-ai-writes-500-lines-boilerplate-why-thats-useful-crumlish-7bqjc
33. https://aiseptor.com/research/ai-cheating-statistics-2026
34. https://www.hackerearth.com/blog/ai-in-the-hiring-process-benefits-risks-step-by-step-implementation-guide-2026
35. https://www.hr.uillinois.edu/policy/a_i_guidelines_for_hiring_and_employment
36. https://www.warden-ai.com/resources/hr-tech-compliance-nyc-local-law-144
37. https://www.gdprregulation.eu/gdpr-for-recruitment/
38. https://prefactor.tech/blog/data-retention-for-ai-agents-in-regulated-industries
39. https://www.dwkesq.com/ccpa-notice-to-job-applicants/
40. https://www.cogn-iq.org/blog/work-sample-tests/
