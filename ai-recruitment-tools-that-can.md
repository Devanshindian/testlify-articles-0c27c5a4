# AI Recruitment Tools Ranked by Bias-Audit Survivability

Signing off on AI recruitment tools puts your name behind a promise the vendor can't prove: that the tool reduces bias. New York City's Local Law 144 requires an independent bias audit before you use one of these tools on a New York candidate. Two of the five major platforms compared here have no published bias-audit record at all. One, Workday, is already defending an active [EEOC](https://www.eeoc.gov/laws/guidance/questions-and-answers-clarify-and-provide-common-interpretation-uniform-guidelines)-linked lawsuit with no audit to offset it.

This comparison scores HireVue, Pymetrics, Workday, Eightfold AI, and iCIMS on the same five yardsticks: published bias-audit evidence, AEDT status, four-fifths rule disclosure, litigation record, and scoring transparency. By the end you'll know which one has evidence you could hand to legal.

## Quick answer

None of the five platforms compared here has a fully clean audit record. Pymetrics comes closest, with an independent audit finding no adverse impact aside from one gap around how long it reuses candidate scores, while Eightfold has published Local Law 144 results it says don't prove the model is bias-free. HireVue has commissioned audits but withholds the details from candidates and regulators, and Workday and iCIMS have no public audit at all, with Workday currently defending an EEOC-linked collective action. A passing audit only proves what it tested, so demand the evidence before you sign, not after.

## AI Recruiting Tools at a Glance: Who Has the Audit Evidence?

Three of the five recruiting AI tools compared here, HireVue, Pymetrics, and Eightfold AI, have published bias-audit evidence a compliance team can review before signing. Workday and iCIMS have none, and Workday now carries an active EEOC-linked lawsuit with nothing to offset it.

| Tool | Four-Fifths Rule Disclosure | Published Bias-Audit Evidence | Legal/Regulatory Exposure | Scoring Transparency | AEDT Coverage Clarity |
|---|---|---|---|---|---|
| HireVue | Not disclosed | Two commissioned audits, plus a public Explainability Statement | [EPIC](https://epic.org/documents/comments-of-epic-on-the-eeocs-draft-strategic-enforcement-plan-for-2023-2027/) FTC complaint; accessibility complaint | Partial: withholds scoring specifics | Established as AEDT, scope contested |
| Pymetrics | Disclosed: all groups cleared 80% threshold | Cooperative third-party audit; passed except score reuse | None named | High: findings public | Clear |
| Workday | None published | None published | Active *Mobley v. Workday* EEOC-linked action | Unverified | Undetermined |
| Eightfold AI | Disclosed: passed on every tested group | NYC Local Law 144 audit, demographics published | None named | Moderate: Eightfold says audit doesn't certify bias-free | Partial |
| iCIMS | None published | None published | None named | Unverified | Depends on activated modules |

## 1. Pymetrics: Passed Its Bias Audit, Except for Score Reuse

Pymetrics gave outside researchers full access to its platform, rather than treating them as an adversary probing a locked box. A team from Northeastern University was paid upfront, specifically so no one could argue payment shaped the outcome, and held a contractual right to publish regardless of what they found. Pymetrics got only 30 days to fix any problems before publication.

The auditors manually tested the source code and ran the scoring pipeline themselves. Pymetrics' algorithm cleared the four-fifths rule: every demographic group's selection rate reached at least 80% of the top-scoring group's. Because no demographic data entered the training pipeline, the auditors found no evidence of direct discrimination in the outputs.

One finding kept this short of a clean bill of health. Pymetrics reused applicant scores for up to 330 days. A candidate's score from one employer's assessment could resurface at a different company nearly a year later, with no fresh test run against that employer's own pool. A vendor confident in its fairness record should say plainly whether it reuses scores across clients, and for how long.

## 2. Eightfold AI's NYC Local Law 144 Audit, and What It Didn't Prove

BABL AI conducted Eightfold's Local Law 144 audit, using its own Criterion Audit Framework, a method published in the Proceedings of the 2024 ACM Conference on Fairness, Accountability, and Transparency. Eightfold applied the standard across every market its matching model operates in, not only where the law required it.

The audit drew on more than 29 million candidate assessments from January 2024 to December 2025, using self-declared demographic data. Eightfold published every number, not a summary: results broken down by gender, by Local Law 144's seven race and ethnicity groups, and by every combination of the two. Eightfold passed all three sections tested: disparate impact, internal governance, and risk assessment.

Even so, Eightfold does not call this a clean bill of health. It states directly that the audit does not certify the model as "bias-free," and that no audit can make that claim. The model cleared this threshold on data candidates chose to share. It says nothing about candidates who never disclosed, or bias the tested categories don't capture.

## 3. HireVue Under NYC Local Law 144: What the Audits Withhold

HireVue's video-interview scoring counts as an AEDT under Local Law 144. It films a candidate's responses and scores gestures, tone, and word choice into an "employability score", used for roles from investment banking to accounting [1]. HireVue's own psychologist has said facial actions alone can drive 29% of that score [1].

That model drew a 2019 FTC complaint from the Electronic Privacy Information Center, alleging HireVue marketed the tool as bias-free without a reasonable basis, and that even HireVue itself sometimes could not explain a score [2].

HireVue answered with two audits in 2021, but never released either in full [2], only summaries, gated behind personal information [2]. At least one was scoped to a single use case [2]. A 2023 audit by DCI Consulting checked for race, gender, and intersectional bias. HireVue has since published what it calls the industry's first [AI Explainability Statement](https://testlify.com/hr-glossary/algorithmic-transparency/), but candidates still can't see their own scores or the training data behind them [2].

No fully public, independent audit dataset with disclosed impact ratios exists for HireVue's video scoring. Most audited does not mean most defensible.

## 4. iCIMS Under NYC Local Law 144: No Public Audit Record

iCIMS has no independent bias-audit summary, EEOC finding, or litigation record on public view, in either direction. Coverage under Local Law 144 attaches to specific features, not the whole company. In a November 2024 blog post, iCIMS said only one feature, Candidate Ranking using Role Fit, qualifies as an AEDT; sourcing, chatbots, and interview-question generation don't.

iCIMS says it commissioned third-party audits of Candidate Ranking in 2022 and 2023, both with favorable results, and plans to repeat them annually. But by its own wording, it provides the summary to customers on request rather than publishing it. No methodology or demographic breakdown behind those audits appears anywhere in public view.

An unpublished audit is not the same as no audit, and no audit is not the same as a demonstrated pass. Given how thin Local Law 144 enforcement has proven elsewhere in this comparison, the absence of a public flag on iCIMS reflects weak scrutiny, not a safe tool.

## 5. Workday: Mobley v. Workday, and No Bias Audit

Workday carries the highest legal exposure and the thinnest audit record of the five tools here. No published bias-audit results, Local Law 144 disclosure, or EEOC four-fifths outcomes exist for its AI-driven hiring functions. Its own marketing advertises "unbiased, AI-driven candidate grading" without naming what the model weighs.

The company is defending *Mobley v. Workday* (N.D. Cal.), an EEOC-linked case alleging its screening platform produced disparate impact based on race, age, and disability. Derek Mobley says he applied to more than 100 jobs through Workday's platform and was rejected from every one, often with no human review. In July 2024, the court rejected Workday's claim to be a neutral tool "simply implementing" employer criteria, finding it plausibly participates in the decision itself. On May 16, 2025, Judge Rita Lin certified a collective action under the Age Discrimination in Employment Act covering applicants 40 and over since September 2020.

No verdict has been reached on whether Workday's system actually produced that effect. What the ruling settled: a vendor, not just the employer using its tool, can be named as a defendant in [AI hiring litigation](https://testlify.com/hr-glossary/algorithmic-accountability/). A federal judge separately let Workday shield bias-testing data for one tool behind attorney-client privilege. The closest thing to a public audit, an outside impact-ratio analysis of a different tool, explicitly says it "is not intended to satisfy any customer-specific legal or regulatory obligation".

## The Four-Fifths Rule and NYC Local Law 144: What AI Hiring Tools Must Clear

[Local Law 144](https://testlify.com/new-york-city-bias-audit/) doesn't ban AI in hiring. It makes using an AEDT (automated employment decision tool) conditional on three things: an independent bias audit within the past year, public disclosure of the results, and advance notice to candidates [3]. Coverage depends on where the candidate lives, not where the employer is based. A Texas company screening one New York City applicant is covered.

The four-fifths rule, also called the 80% rule, is the federal test behind that audit. It compares each demographic group's selection rate to the highest-scoring group's; a ratio below 0.80 signals a result worth investigating [4]. It's a screening tool, not a definitive legal test. It ignores sample size, so it can flag a gap that means nothing and miss one that does.

A passing score isn't a fairness certificate. New York's own guidance says an audit "does not prove that the tool is fair in every job, disability context, or decision". That's the gap every score in this comparison sits inside.

## Which AI Recruitment Tool Fits Your Risk Profile

No single platform wins across the board. Match the tool to the risk you're managing first.

- Need the most complete audit evidence: Pymetrics. Its cooperative audit found no adverse impact, though the score-reuse gap keeps it short of clean.
- Need to avoid active litigation: rule out Workday. It's the only tool here with a live EEOC-linked collective action and no audit to offset it.
- Need ATS-embedded matching with some evidence: Eightfold. An outside audit examined its model, though Eightfold itself says that doesn't certify it bias-free.
- Need the most audit activity, not necessarily transparency: HireVue has commissioned two audits but withholds details from candidates and regulators.
- No tool-specific priority: treat iCIMS, and any vendor without a public record, as a demand-the-audit-first situation.

Two of five tools here have no audit record a compliance review could rely on. Ask for the audit before the contract, not after.

## Building the Evidence Trail Yourself

The pattern across the AI recruitment tools compared here is the same: audit evidence is thin. Even a passing score only proves what it was tested against. A defensible hiring process needs job-related evidence from the start, not an audit filed after the fact.

At Testlify, we build assessments validated by I/O psychologists, checked for adverse impact, and documented for EEOC compliance. Explore our [3,500+ assessments](https://testlify.com/) to see what evidence-based screening looks like before a regulator ever asks for proof.

## Frequently asked questions

**Which AI tool is best for recruitment?**

No single platform wins outright. Pymetrics has the most complete published bias-audit evidence, but Workday faces active litigation and Eightfold's audit doesn't certify its model as bias-free. Match the tool to your risk, not one ranking.

**How to use AI tools for recruitment?**

Vet a vendor's published audit evidence before signing, then keep a trained human reviewing every AI-surfaced score instead of auto-rejecting. Treat the audit as a yearly renewal, not a one-time check.

**Does NYC Local Law 144 apply if my company isn't based in New York?**

Yes, if the candidate lives in any of the five boroughs. Coverage depends on where the candidate resides, not your headquarters, even for a fully remote role.

**Is an ATS the same thing as an AI recruitment tool?**

No. An ATS manages the hiring workflow; an AI recruitment tool adds automated scoring or ranking inside it. Workday and iCIMS embed that scoring directly inside their ATS.

**What's the difference between AI recruitment tools and skills-based assessments?**

AI recruitment tools typically score resumes, video, or chat automatically. Skills-based assessments test candidates directly on job-relevant tasks against a fixed rubric, producing evidence that's easier to defend in an audit.

## Sources

1. https://www.brookings.edu/articles/for-some-employment-algorithms-disability-discrimination-by-default/
2. https://epic.org/documents/comments-of-epic-on-the-eeocs-draft-strategic-enforcement-plan-for-2023-2027/
3. https://www.nyc.gov/site/dca/about/automated-employment-decision-tools.page
4. https://www.eeoc.gov/laws/guidance/questions-and-answers-clarify-and-provide-common-interpretation-uniform-guidelines
