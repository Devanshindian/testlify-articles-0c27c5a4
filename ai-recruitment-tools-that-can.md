# AI Recruitment Tools Ranked by Bias-Audit Survivability

Somewhere in your procurement queue sits a contract for one of these AI recruitment tools, and your name goes on the approval line. The deck says the tool reduces bias. If a candidate living in Brooklyn is ever screened by it, a regulator can ask you to prove that sentence, and a deck is not proof.

This comparison scores HireVue, Pymetrics, Workday, Eightfold AI and [iCIMS](https://www.icims.com/blog/how-icims-supports-the-nyc-automated-employment-decision-tools-law/) on the same five yardsticks. Not on features, and not on how a sales team describes the model. On what an outside party has tested and published. By the end you will know which one gives you something you could hand to legal, and which two give you nothing.

## Quick answer

None of these five platforms has a clean audit record. Pymetrics comes closest: outside researchers got real access and found no adverse impact, though the tool reused candidate scores for up to 330 days.

Eightfold published its audit in full, then said plainly that the result does not certify the model as bias-free. HireVue has commissioned the most audits and shares the least about them. Workday and iCIMS have published nothing, and Workday is defending an age-discrimination collective action. Ask for the audit before you sign. Nobody hands it over afterwards.

## How We Scored These AI Recruitment Tools Against NYC Local Law 144

New York City's Local Law 144 is the reason this ranking exists. The law does not ban AI in hiring. It makes using one of these tools conditional on three things: an independent bias audit run within the year before you use it, the results posted where candidates can read them, and advance notice to the candidate. Miss any of the three and the exposure is yours, not the vendor's.

These tools automate candidate sourcing, resume screening and interview scheduling, and they are sold on speed. Not all of them are in scope for an audit, which is why this list is short. A scheduling bot that checks a candidate's availability and books an interview slot, or a chatbot that only logs replies for a person to read later, evaluates nobody, so the audit requirement never reaches it. Automated candidate sourcing sits outside it for the same reason, until it starts ranking the people it surfaces. The moment a tool screens, ranks or scores a person, the law applies.

That does not make the rest of the stack safe. No equivalent published audit exists for Paradox, the scheduling and communication tool, or for other comparable commercial platforms. A sourcing or scheduling tool that has started ranking people needs the same evidence.

The audit turns on the four-fifths rule. An auditor works out how often each demographic group gets selected, divides every group's rate by the best-performing group's rate, and treats anything below 0.80 as a result to investigate. That is a screening test, not a verdict. A tool can clear 0.80 and still be a poor tool, so no single number decides the order below.

Each platform is scored on five things:

- **Published audit evidence:** has an outside party tested the tool, or does the claim rest on the vendor's own word?
- **AEDT status:** does the vendor say whether its product is an [automated employment decision tool](https://testlify.com/hr-glossary/algorithmic-accountability/) under the law?
- **Four-fifths disclosure:** are the impact ratios public, or summarised away?
- **Legal exposure:** is there a live lawsuit or regulatory complaint attached to the tool?
- **Scoring transparency:** does the vendor explain what the score actually weighs?

Where a vendor has published nothing, that is recorded as a gap, never as a pass. Silence is the cheapest thing a vendor can produce, and reading it as a clean record is the mistake this comparison argues against.

## AI Recruiting Tools at a Glance: Who Has the Audit Evidence?

Three of these five recruiting AI tools have published bias-audit evidence a compliance team can read before signing. Two have not. Everything below is the detail behind that.

| Tool | Published audit | Impact ratios disclosed | Legal exposure | Scoring transparency |
|---|---|---|---|---|
| Pymetrics | Cooperative third-party audit, passed | Yes, every group cleared 80% | None named | High |
| Eightfold AI | Local Law 144 audit, published in full | Yes, with demographic breakdowns | None named | Moderate |
| HireVue | Two commissioned audits, summaries only | No | [EPIC](https://epic.org/documents/comments-of-epic-on-the-eeocs-draft-strategic-enforcement-plan-for-2023-2027/) complaint to the FTC | Partial |
| iCIMS | Audits claimed, none published | No | None named, either direction | Unverified |
| Workday | None | No | Active collective action | Unverified |

That table doubles as the ranking. The order is not about which tool screens candidates best. It is about which vendor leaves you holding something checkable when a candidate's lawyer asks how the rejection happened.

## The 5 AI Hiring Tools, Ranked by Audit Survivability

Ranked from the most defensible evidence down to the least. A high place means the vendor handed over something checkable, not that the product is fair.

### First: Pymetrics, the Most Complete Public Audit

Pymetrics sells a suite of 12 games built on cognitive science experiments, scoring traits like risk tolerance and learning ability instead of reading a resume. The company has marketed the product as entirely bias free, exactly the claim an audit exists to test.

What makes this record unusual is the access. Pymetrics let outside researchers work under a grant through Northeastern University, paid them upfront so nobody could argue the fee shaped the finding, and gave them a contractual right to publish whatever they found. The auditors read the source code and ran the scoring pipeline themselves.

The algorithm held up. Every demographic group's selection rate reached at least 80% of the top-scoring group's rate, and no demographic data entered the training pipeline at all.

One finding kept it short of clean. Pymetrics reused an applicant's score for up to 330 days, so a score earned at one employer could resurface at another company almost a year later, with no fresh test against that second pool. Ask any vendor whether it does this.

### Second: Eightfold AI, Published in Full and Honest About the Limit

Eightfold had its matching model audited against Local Law 144 and then did something none of the others did. It published the entire result: every number, every demographic group, every finding, rather than a summary. The audit drew on more than 29 million candidate assessments recorded between January 2024 and December 2025, and the model passed on disparate impact, internal governance and risk assessment alike.

Eightfold also applied that standard everywhere its model runs, not only where New York City required it. The published evidence then covers your applicants in Ohio as well as the ones in Queens.

Then the company undercut its own marketing on purpose. Eightfold states that the audit does not certify the matching model as bias-free, and that no audit can. The model cleared one threshold, on the breakdowns tested, using demographic data candidates chose to share. It says nothing about the candidates who shared none.

### Third: HireVue, the Most Audited and the Least Transparent

HireVue films a candidate answering questions and scores gestures, pose, tone, cadence and word choice into a single employability score. Its own chief industrial-organizational psychologist told the Washington Post that facial actions alone can account for 29% of that score [1]. More than a quarter of whether your team ever meets a candidate can rest on a face the software has decided it likes.

The audits are real. Two were commissioned in 2021, and a later one was run for Local Law 144. What you cannot do is read them. The public gets summaries, and only after handing over personal information and agreeing not to reproduce what they read [2].

That is why the most audited tool here is not the most defensible one. An audit you are contractually barred from quoting is not evidence you can put in front of a regulator. It is a press release wearing a footnote.

### Fourth: iCIMS, Audits It Says Exist and Will Not Show You

iCIMS is the awkward case, because the public record is empty in both directions. The company says it commissioned third-party bias audits of its Candidate Ranking feature in November 2022 and November 2023, both with favorable results, and that it gives customers the summary on request. It has never published one [3].

Where iCIMS has been useful is scope. It reviewed its Talent Cloud AI tools against the law's definition and found that only one feature, Candidate Ranking using Role Fit, qualifies as an AEDT [3]. Sourcing, chatbots and interview-question generation did not. So whether the law reaches your deployment depends on which modules your team switched on, and only your own tool inventory answers that.

An unpublished audit is not the same thing as no audit. It is also not a pass you can rely on. Ask for the summary during procurement.

### Fifth: Workday, Mobley v. Workday and No Audit to Set Against It

Workday sits last because it carries the heaviest legal exposure and the thinnest public record to offset it. No published bias-audit results, no Local Law 144 disclosure summary and no four-fifths outcomes exist for its AI-driven hiring functionality. Its recruiting page still advertises unbiased, AI-driven candidate grading.

Derek Mobley, a Black man over 40 with a disability, says he applied for more than 100 jobs through employers running Workday's screening platform and was turned down by every one, in many cases with no human reading the application. In May 2025 a federal judge granted conditional certification of a collective action under the Age Discrimination in Employment Act, covering everyone 40 and over denied a recommendation through the platform since September 2020. No verdict has landed. What the ruling settled is that the vendor selling the tool can be named, not only the employer using it.

Workday has run bias testing. In 2026 a court agreed the results were relevant evidence of possible bias and still let the company shield them from discovery as attorney-client privilege, because its lawyers had curated the testing [4]. That is the opposite of an audit. An audit is built to be shown.

## Which Tool Fits Your Risk Profile

No platform wins across the board. The right answer depends on the risk you are managing first.

If you need documented evidence with the fewest caveats, Pymetrics is the only tool here with an audit you can read end to end, and you go in already knowing about the score-reuse gap. If you need published evidence inside matching your recruiters already work in, Eightfold fits, as long as you repeat its own caveat back to legal instead of filing the audit as a certificate.

If the job this quarter is avoiding live litigation, rule out Workday and put the reason in writing. If HireVue is on your shortlist, you are buying audit activity rather than audit transparency, and a regulator will ask for the second.

And if you are looking at iCIMS, or any vendor with no public record, treat it as a demand-the-audit-first situation. That absence is the finding, not a formality on the way to a signature.

## What to Demand From an AI Hiring Vendor Before You Sign

A vendor demo will always show a clean score and a candidate flow that works. It will never show proof of fairness. So the diligence happens before signature, while you hold leverage. Ask for three things, in writing:

- A reason attached to every score. Not an aggregate fairness figure. A plain-language answer to why this candidate ranked where they did.
- The evidence behind any accuracy claim. If the deck says 95% accuracy, ask what it was measured against: recruiter clicks, actual hiring outcomes, or a labelled dataset. Those are three different claims and only one is validity.
- A pilot with written pass and fail criteria. Run the tool on a limited pool, decide in advance what a pass looks like, and hold the vendor to it.

Then keep a person in the decision, and give them time to be one. A reviewer who approves an AI recommendation in under 60 seconds per candidate is not exercising judgment, and a court looks at whether the human weighed the case or simply clicked through it. That record is what you end up defending, long after the audit summary expires.

For how one federal court put that kind of record together, see [our S.D.N.Y. hiring story](https://testlify.com/customer-success-stories/us-district-court-sdny/).

## Building the Evidence Trail Yourself

The pattern across these AI recruitment tools is the same. The audit evidence is thin, and even a passing result only proves what it was tested against on the day it ran. A defensible hiring process does not begin with the vendor's audit. It begins with evidence that what you are measuring is part of the job.

At Testlify, we build assessments validated by I/O psychologists, checked for adverse impact, and documented for EEOC compliance. Explore our [3,500+ assessments](https://testlify.com/) to see what evidence-based screening looks like before a regulator ever asks for proof.

## Frequently asked questions

**Which AI tool is best for recruitment?**

No single platform wins. Pymetrics has the most complete published audit evidence, Workday is defending an active collective action, and Eightfold says its own audit does not certify the model as bias-free. Match the tool to your risk.

**How to use AI tools for recruitment?**

Read the vendor's published audit before you sign, not after. Then keep a trained person reviewing every score instead of letting the tool auto-reject anyone, and ask how recently that audit was run.

**Does NYC Local Law 144 apply if my company isn't based in New York?**

Yes, if the candidate lives in one of the five boroughs. Coverage follows where the candidate lives, not where your office sits, and a fully remote role is still covered.

**Is an ATS the same thing as an AI recruitment tool?**

No. An applicant tracking system manages the hiring workflow. An AI recruitment tool adds automated scoring or ranking on top of it. Workday and iCIMS build that scoring straight into their ATS.

**What's the difference between AI recruitment tools and skills-based assessments?**

AI recruitment tools score resumes, video or chat answers to rank people. Skills-based assessments test candidates on job tasks against a fixed rubric, which is far easier to defend in a bias audit.

## Sources

1. https://www.brookings.edu/articles/for-some-employment-algorithms-disability-discrimination-by-default/
2. https://epic.org/documents/comments-of-epic-on-the-eeocs-draft-strategic-enforcement-plan-for-2023-2027/
3. https://www.icims.com/blog/how-icims-supports-the-nyc-automated-employment-decision-tools-law/
4. https://www.insidetechlaw.com/blog/2026/06/behind-the-privilege-shield-safeguarding-ai-bias-testing-data-in-employment-decisions
