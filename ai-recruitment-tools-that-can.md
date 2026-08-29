# AI Recruitment Tools Ranked by Bias-Audit Survivability

Legal has one question about the AI recruitment tools you want to buy, and it is not about features. Can you show this thing does not reject one group of candidates far more often than another? The vendor's deck says the model reduces bias. That is a sentence, not evidence, and a plaintiff's lawyer will pull it apart first.

This comparison ranks five platforms hiring teams get asked about by name: Pymetrics, Eightfold AI, HireVue, iCIMS and Workday. The test is not which one screens candidates best. It is which one has published something you could forward to legal without flinching.

## Quick answer

None of these five platforms has a clean audit record. Pymetrics comes closest, because it gave outside researchers real access and let them publish whatever they found. Eightfold published its New York City audit in full, then said plainly that the result does not make its model bias-free. HireVue has been audited twice and shows almost none of it, while iCIMS shows its summary only to customers who ask for it. Workday has published nothing at all while it defends a discrimination case, so ask for the audit before you sign, because an audit only ever proves what it was pointed at.

## How We Ranked These AI Recruitment Tools for Audit Survivability

Surviving an audit means three things at once, and most vendors manage one of them. An outside party has tested the tool and the result is public. The vendor will say what its score actually weighs. And no live lawsuit sits there undercutting whatever the audit found.

These are not the biggest names in [recruiting AI tools](https://testlify.com/top-ai-recruiting-tools-for-improved-hiring-process/). They are the ones compliance and legal ask about by name when a purchase order lands on someone's desk. Between them they automate the parts of hiring a recruiter used to do by hand: sourcing candidates, screening resumes, scheduling interviews, and running the interview itself. Speed is how all of it gets sold, and a shortlist that arrives by Friday is a useful thing to buy.

Plenty of familiar tools sit outside this ranking, and not because they are any safer. Sourcing engines built on semantic search, and scheduling and messaging chatbots like Paradox, have published no equivalent audit result either. Read that absence as a finding rather than a clean record.

Every score below traces to something a vendor published, an outside party tested, or a court filed. None of it comes from marketing copy, because copy is free and an audit is not. Where a vendor has published nothing, the table says so and stops there. Silence is not a clean record, and reading it as one is the mistake this comparison argues against.

| Tool, best evidence first | Published audit evidence | Legal exposure |
|---|---|---|
| Pymetrics | Outside audit, findings public | None named |
| Eightfold AI | Local Law 144 audit published in full | None named |
| HireVue | Two audits, summaries only | FTC complaint from a privacy group |
| iCIMS | Says audits exist, publishes none | None named |
| Workday | None published | Active collective action |

## 1. Pymetrics: The Bias Audit That Went Furthest, Except on Score Reuse

Pymetrics sells a set of 12 short games built on cognitive science experiments. They measure things like risk tolerance and how fast someone learns a rule, and a candidate plays them instead of sending a resume. The company marketed the product as entirely bias free. That is a very large claim, and it is why the audit that followed matters.

Rather than treat outside researchers as intruders picking at a locked box, Pymetrics handed them access to the platform. The team worked under a university grant and was paid up front, so nobody could argue the fee shaped the finding. They also held the right to publish whatever they saw, whether Pymetrics liked the result or not.

The auditors read the source code and ran the scoring themselves rather than accepting a report on trust. Every demographic group's selection rate landed above the federal line, and no demographic data had entered the training pipeline at all. This is the rare case where the evidence and the marketing claim meet.

One finding kept it short of a clean record. Pymetrics reused an applicant's score for up to 330 days, so a result produced for one employer could resurface at another company months later. That second employer never got a fresh test against its own applicants, and probably never knew to ask. Put the question to any vendor plainly: do you recycle scores across clients, and for how long?

## 2. Eightfold AI's NYC Local Law 144 Audit, and What It Didn't Prove

Eightfold's matching model ranks candidates against a role from inside the hiring workflow. New York City's [Local Law 144](https://testlify.com/new-york-city-bias-audit/) says a tool like that has to be audited by an outside party first. Eightfold went through that audit, then applied the same standard everywhere its model runs, not only where the city could reach it.

The audit was not a spot check. It drew on more than 29 million candidate assessments recorded between January 2024 and December 2025, using demographic details candidates had volunteered. Eightfold then published the whole thing rather than a summary, including every number, every group and every finding. A reviewer can open it and check the arithmetic without asking anyone's permission.

Most vendors leave the next part out. Eightfold says the audit does not certify its matching model as bias-free, and that no audit can make that claim. That is a vendor telling you where its own evidence stops, which is worth more than a warranty nobody can honour. The result says nothing about candidates who never shared their demographics, and nothing about bias the tested categories miss.

## 3. HireVue Under NYC Local Law 144: What the Audits Withhold

HireVue films a candidate answering set questions, then scores how they said it as well as what they said. Its own chief industrial-organizational psychologist, Nathan Mondragon, told the Washington Post that facial movements alone can account for 29% of a candidate's employability score [1]. The recruiter reading the shortlist sees one clean number, with no way of knowing how much of it came from a face.

HireVue has commissioned more audits than anyone else in this ranking. Two came from O'Neil Risk Consulting and Algorithmic Auditing in 2021, and neither was ever released in full [2]. That is the difference between being audited and being able to prove it.

What the public can read is a summary, and only after handing over personal information and agreeing not to reproduce it [2]. Try walking that into a procurement review. You cannot forward it, you cannot quote it, and nobody can check whether the scope covered the roles you hire for.

So the most audited tool here is not the most defensible one. A regulator asking what the model weighs will not accept the answer that an auditor once looked and was satisfied.

## 4. iCIMS: The Audits It Says Exist, But Won't Show You

iCIMS is a large hiring platform with AI switched on in several places, and coverage does not attach to the company as a whole. It attaches to the features an employer has turned on. iCIMS reviewed its own Talent Cloud tools and concluded that one of them, Candidate Ranking using Role Fit, counts as an [automated employment decision tool](https://testlify.com/hr-glossary/algorithmic-accountability/).

That distinction is your exposure, not a technicality. Two companies can buy the same platform, switch on different modules, and end up with different obligations. You find out which side of the line you are on by inventorying what your recruiters actually enabled.

iCIMS says it commissioned outside bias audits of Candidate Ranking in November 2022 and November 2023, and that both came back favourable. It also says it gives the audit summary to customers on request, which is another way of saying it has never published one. No methodology, no scoring breakdown, no demographic numbers.

Read that combination carefully, because it is easy to round off in either direction. An unpublished audit is not the same as no audit, and no audit is not the same as a demonstrated pass. If you are evaluating iCIMS, ask for the summary before anything is signed.

## 5. Mobley v. Workday: The Lawsuit With No Bias Audit

Derek Mobley is an African American man over 40 with a disability. He says he applied for more than 100 jobs at employers running Workday's screening platform and was rejected by every one, often with no human opening the application [3]. He sued the vendor rather than the employers.

The case has since grown well past one applicant. On May 16, 2025, Judge Rita Lin granted conditional certification of a collective action covering everyone aged 40 and over who applied through the platform since September 2020 and was denied a recommendation. No verdict has been reached, and Workday has not been found to have done anything.

Here is what Workday has to set against that. No published bias-audit results, no Local Law 144 disclosure summary, and no adverse-impact outcomes for its AI hiring functions exist in public. Its own recruiting pages, meanwhile, advertise unbiased candidate grading.

That combination is why Workday sits last. You are asked to accept a fairness claim with no public evidence behind it, while a court decides whether the tool screened out people over 40.

## How the Four-Fifths Rule Decides Whether a Tool Passed

Every audit above rests on the same piece of arithmetic, so here is what it does. The four-fifths rule, also called the 80% rule, is the federal test regulators use to flag [adverse impact](https://testlify.com/hr-glossary/disparate-impact/) [4]. Work out what share of each group was hired, divide the lowest by the highest, and anything under 0.80 needs investigating.

A worked example makes it concrete. Take 135 applicants who all sit the same written test, 72 of them non-minority and 63 minority. Seven of the first group and three of the second get hired, a selection rate of 9.7% against 4.8%. Divide one by the other and the ratio is about 0.495, well under the line, which reads as adverse impact against minority applicants.

Now cut those same 135 people by sex instead of race. On that split the ratio lands near 0.91 and the tool passes. Same candidates, same test, same day, opposite verdict.

This is why a vendor saying it passed the audit is an incomplete sentence. Passed on which cuts, and on samples big enough to mean anything? A published audit lets you check. A summary that reports a pass and stops there does not, and that gap separates the top of this ranking from the bottom.

## Which of These AI Hiring Tools Fits the Risk You're Managing

No platform wins across the board, because each one fails in a different place. The useful question is which risk you are managing first: proof you can hand to legal, a lawsuit you want no part of, or a scoring model nobody outside the vendor has ever seen.

- **Documented evidence with the fewest caveats:** Pymetrics. Outside researchers tested it and published what they found, and the only gap is score reuse.
- **An audit you can open and read:** Eightfold AI. The full results are public, and the vendor is honest about their limits.
- **Audit activity rather than transparency:** HireVue. Two commissioned audits, neither released in full, so the evidence stays out of reach.
- **A thin public record:** iCIMS, and any vendor like it. Demand the audit first, and ask which modules count as covered tools.
- **Live litigation you want no part of:** Workday. Nothing published, and a collective action still running.

One caution before you take any pass at face value. New York City's own guidance says a bias audit reports defined outcome metrics, and does not prove the tool is fair in every job or every decision. It was never designed to be a fairness certificate.

So put the audit request in the procurement conversation, not in the follow-up email after the purchase order clears. Ask for the summary, the demographic breakdowns, and the date the model last changed. A vendor with the evidence sends it over that afternoon.

For the wider question of what keeps an assessment itself fair, we have a full guide to [building bias out of employment assessments](https://testlify.com/ensure-bias-free-employment-assessments/).

## Building the Evidence Trail Yourself

The pattern across every one of these AI recruitment tools is the same: the audit evidence is thin, and even a clean pass only covers what it was pointed at. A hiring process you can defend needs job-related evidence built in from the start, not a certificate filed after somebody complains.

At Testlify, we build assessments validated by I/O psychologists, checked for adverse impact, and documented for [EEOC](https://www.eeoc.gov/laws/guidance/questions-and-answers-clarify-and-provide-common-interpretation-uniform-guidelines) compliance. Explore our [3,500+ assessments](https://testlify.com/) to see what evidence-based screening looks like before a regulator ever asks for proof.

## Frequently asked questions

**Which AI tool is best for recruitment?**

No single platform wins outright. Pymetrics has the most complete published audit evidence, Eightfold says its own audit does not certify the model as bias-free, and Workday is defending a live discrimination case.

**How to use AI tools for recruitment?**

Read the vendor's published audit evidence before you sign, then keep a trained person reviewing every score instead of letting the system auto-reject anyone. Treat the audit as a yearly renewal.

**Does NYC Local Law 144 apply if my company isn't based in New York?**

Yes, if the candidate lives in one of the five boroughs. Coverage follows where the candidate lives, not where your company is headquartered, and it still applies to a fully remote role.

**Is an ATS the same thing as an AI recruitment tool?**

No. An applicant tracking system moves candidates through the hiring workflow. An AI recruitment tool scores or ranks them. Workday and iCIMS do both, which is why buyers often miss the scoring part.

**What's the difference between AI recruitment tools and skills-based assessments?**

AI recruitment tools score resumes, video or chat automatically to rank people. Skills-based assessments test candidates on the actual work, marked against a fixed rubric, which leaves evidence that is easier to defend.

## Sources

1. https://www.brookings.edu/articles/for-some-employment-algorithms-disability-discrimination-by-default/
2. https://epic.org/documents/comments-of-epic-on-the-eeocs-draft-strategic-enforcement-plan-for-2023-2027/
3. https://www.shrm.org/topics-tools/news/technology/workday-ai-lawsuit-wake-up-call-hr
4. https://www.eeoc.gov/laws/guidance/questions-and-answers-clarify-and-provide-common-interpretation-uniform-guidelines
