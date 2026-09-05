# AI Recruitment Tools That Can Survive a Bias Audit

You are one signature away from putting an AI screening tool in front of every applicant your company sees. Sooner or later, someone on the executive team will ask whether it discriminates. Most AI recruitment tools on the market cannot answer that question. Nobody outside the vendor has been allowed to check.

A bias audit is what closes the gap. It measures whether a hiring tool selects one group at a much lower rate than it selects another. No other document answers the question in writing. Five tools are compared here on that single thing: what each one has published, and what you would have to prove yourself.

## TL;DR

- Eightfold AI is the pick for a compliance-led buyer, because it is the only tool here whose bias audit a regulator could read in full without your help.
- The employer answers for a biased hiring decision, not the vendor, so choosing a tool with no published audit means you carry the exposure alone.
- Run the four-fifths rule on your own funnel before you trust or blame any vendor: any group selected at below 0.80 of your top group's rate needs investigating.
- Ask for the audit report itself, the auditor's name and the impact ratios by sex and race before you sign. A missing audit is not a passing one.

## The Four Kinds of AI Hiring Tools, and What Each One Decides

Start by naming what you actually bought. A bias audit measures decisions, not software. Four kinds of [AI hiring tools](https://testlify.com/top-ai-powered-recruitment-tools-changing-the-hiring-game/) show up in most stacks: resume screeners, matching engines, video-interview scorers, and skills assessments. Each one makes a different call about a candidate. So you have to examine each one separately, even when one contract covers all four.

The screener is where the volume sits. An average job posting draws around 500 applications, and the tool ranks every one of them against the job description. Much of that ranking rests on keyword overlap, which is the category's known weakness. Your posting says Rust. Your strongest engineer may describe her work as memory-safe systems programming, and she is gone before a recruiter opens the file.

Matching engines decide which candidates a recruiter ever sees. Video platforms decide how a recorded answer scores. Skills assessments decide what someone can demonstrably do and hand that score to a person. This is not a fringe problem: 88% of organizations already use AI somewhere in hiring. The question is which of these four decisions you have handed to it.

## The Four-Fifths Rule Is the Number Your Audit Turns On

Every audit in this article reports against one test. You can run it yourself on a spreadsheet. For each race, ethnicity and sex group, divide the number of people selected by the number who applied. The group with the highest rate becomes your benchmark. Divide every other group's rate by that benchmark, and you have an impact ratio.

The federal selection guidelines treat any ratio below four-fifths, or 0.80, as evidence of [adverse impact](https://testlify.com/hr-glossary/disparate-impact/). Here is what that looks like on a written screen. Of 72 non-minority applicants, seven passed. Of 63 minority applicants, three passed. That is 9.7% against 4.8%, an impact ratio of 0.49.

A ratio like that starts an inquiry rather than settling one. It tells you where to look, and looking is the step people skip. Run the math separately for every group, because a single hiring round can clear the line comfortably on sex while failing badly on race. If you only ever compute one ratio for the whole funnel, you will learn where your exposure sits from a plaintiff's lawyer instead of from your own data.

## What NYC Local Law 144 Puts on You, Not the Vendor

New York City's Local Law 144 does not ban AI in hiring. It sets three conditions on using a covered tool. You need an independent bias audit within the year before you use it, a public summary of the results, and notice to the candidate. All three belong to the employer. No vendor can take them off your hands.

The law follows the candidate, not your head office, so a single applicant in the five boroughs pulls a Chicago company into scope. The notice has to reach that candidate at least 10 business days before the tool evaluates them. It also has to name what the tool assesses, and how the candidate can ask for an alternative.

The penalties look small until you multiply them. A first violation costs $500. Each further violation runs up to $1,500, counted for every day the non-compliance continues. Missing the audit and missing the notice count as two violations, not one. Publish your summary where a candidate would look for it, which means the careers page, not a policy document three clicks down.

## How to Choose an AI Recruitment Tool You Can Defend

Defensibility is decided at procurement, not by the compliance team a year later. Five things decide it. Only one of them usually appears on a vendor's slide.

The first is the audit report itself, not a summary of it. That report names the independent auditor, states the methodology, and breaks out impact ratios by sex, race and the combinations of the two. A general statement about responsible AI is marketing, not evidence. The second is an explanation attached to every score. When a rejected applicant asks, the recruiter can say why one candidate ranked above another.

The third is where the tool sits in your stack. Ask how it connects to your applicant tracking system. Ask how long setup actually takes. Screening features buried inside a broader HR platform are the ones nobody flags as in scope, and nobody audits what nobody flags. Fourth is what the candidate experiences. Check what they are told, whether they can request an alternative process, and whether the format itself screens out people using assistive technology.

The fifth is money. Under Title VII, the employer answers for adverse impact however the decision was automated. iTutorGroup paid $365,000 in September 2023 to settle an EEOC complaint that its software automatically rejected women aged 55 and over and men aged 60 and over. Read what your contract says about who covers a violation before you read the feature list.

Keeping the assessment itself fair is a separate discipline from vetting the vendor, and we have set out [how to test an employment assessment for fairness](https://testlify.com/ensure-bias-free-employment-assessments/) in full.

## The Five AI Recruitment Tools at a Glance

The five tools separate on transparency before you read a word about their models. A blank in the audit column means no public evidence exists, and missing evidence is not a pass.

| Tool | What it scores | Public audit record | Best for |
|---|---|---|---|
| [Eightfold](https://eightfold.ai/trust/bias-audit-results/) AI | Candidate matching | Named independent auditor, published methodology, ratios by sex, race and intersection | Buyers who must hand a regulator a finished file |
| Pymetrics | Cognitive-science games | Cooperative audit with source-code access, published in full | Buyers who want to see inside the model |
| Testlify | Skills assessments and candidate matching | Independent audit of the matching model, transparency page published | Buyers who want the assessment itself to be defensible |
| HireVue | Recorded video interviews | Two audits, released only as gated summaries | Buyers willing to accept a vendor's account of its own audits |
| Workday | AI screening inside its hiring platform | None published | Organizations already standardized on Workday and ready to audit it themselves |

Each entry below takes one tool and shows what sits behind its row.

## 1. Eightfold AI: The BABL AI Audit Other Vendors Get Measured Against

Eightfold AI matches candidates against open roles. Its matching model carries the closest thing this category has to a reference bias audit. BABL AI, an independent auditing firm, audited that model against Local Law 144's definition of a bias audit [1]. The report does what the law asks and most vendors skip. It reports results for gender, for each of the seven race and ethnicity groups the law names, and for every gender-by-race combination [1].

Copy the independence terms into your own vendor questionnaire. BABL AI's fees were fixed and unrelated to the opinion it delivered [1], which is exactly what you want to confirm before you rely on anyone's audit. The report states its scope as plainly as its results. The opinion covers the matching model. Eightfold's AI Interviewer is audited separately [1]. If you buy the interviewer, you are relying on a different document and should ask to see it.

- **Best for:** a compliance-led buyer who has to hand a regulator a finished file.
- **Audit record:** named independent auditor, fixed fees, published methodology, ratios by sex, race and intersection.
- **Key features:** candidate matching across internal and external talent, with the audited model covering the matching function.

## 2. Pymetrics: Source-Code Access, and the Score Reuse the Audit Exposed

Pymetrics scores candidates through a set of games built on cognitive-science experiments. It has been examined more openly than anything else here. The auditors were handed the source code, tested it by hand, and ran the scoring pipeline themselves. On that basis they confirmed the central claim. The algorithm implements the four-fifths rule. No other vendor in this comparison has allowed that level of access.

That access also turned up something no disclosure covered. The platform reused an applicant's scores for up to 330 days, and it did not limit reuse to the employer whose process generated them. A score earned in one company's funnel could follow a candidate into another company's. Put that question to every vendor you shortlist, because you will not find the answer in a summary.

- **Best for:** a buyer who values verified cooperation over a polished compliance page.
- **Audit record:** cooperative audit with source-code access, findings published in full.
- **Key features:** game-based measures of traits such as risk tolerance, scored by a model that implements the four-fifths rule.

## 3. Testlify: An Independently Audited Matching Model, Published Under Local Law 144

Testlify publishes this article, so read this entry knowing that. An independent auditor audited our matching model on June 16, 2023, and the transparency page setting out that audit is public. The rest of the platform is skills assessment. Candidates earn a score by doing tasks close to the work, not by having traits inferred from a video.

That matters for the second document a regulator asks about. A [bias audit](https://testlify.com/new-york-city-bias-audit/) shows how selection rates compare across groups, while a validation study shows the score relates to performance on the job. Work-sample style tests give you something to defend on that second question. Abstract scoring rarely does.

- **Best for:** a buyer who wants the assessment underneath the screening decision to be the defensible part of the funnel.
- **Audit record:** independent audit of the matching model completed June 16, 2023, with a public transparency page.
- **Key features:** role-based skills assessments built by industrial-organizational psychologists, with matching scored separately from the tests themselves.

## 4. HireVue: Two Bias Audits, Neither One Published in Full

HireVue records candidate interviews and scores them. It draws scrutiny for the weight it has placed on non-verbal signals. The company's chief industrial-organizational psychologist told the Washington Post that facial actions alone could account for 29% of a candidate's score [2]. That is a substantial share of a hiring decision resting on how a face moves during an answer.

Two bias audits of the platform exist, and neither has been released in full. The public gets summaries only. To read one, you hand over personal information and agree not to reproduce any part of it [3]. A summary your own counsel cannot quote is not evidence, and it will not stand up in a discovery request. If you shortlist HireVue, budget for auditing the deployment yourself before you turn it on.

- **Best for:** a buyer who runs high interview volume and is prepared to commission an independent audit.
- **Audit record:** two audits announced, released as gated summaries rather than full reports.
- **Key features:** recorded and structured video interviewing at scale, with scoring that has included analysis of facial action.

## 5. Workday: The Workday AI Lawsuit, and No Published Audit

Workday has published no bias-audit results and no Local Law 144 summary for its AI screening functionality. What is public instead is litigation. In [Mobley v. Workday](https://www.seyfarth.com/news-insights/mobley-v-workday-court-holds-ai-service-providers-could-be-directly-liable-for-employment-discrimination-under-agent-theory.html), the court rejected the argument that the platform is a neutral tool executing whatever criteria an employer sets. It held that Workday can be liable as an agent of the employers using it [4]. That ruling reaches past this one vendor. It is the first serious answer to the defense that the software did it.

The scale is what turns this into a board-level item rather than a procurement footnote. Workday's own filings put roughly 1.1 billion rejected applications inside the period covered by the certified age-discrimination collective. Sign today and you carry the adverse-impact question with no published ratios to point at, so the audit work lands entirely on your team.

- **Best for:** an organization already standardized on Workday that will run, document and publish its own audit.
- **Audit record:** no published bias audit or impact ratios; an active federal discrimination case instead.
- **Key features:** AI screening and candidate ranking built into a full HR platform, which is also where in-scope tools most often go unflagged.

## Which of the Five You Can Actually Defend

None of these tools survives every review. The right pick depends on which constraint you personally carry into it. If your file has to satisfy a regulator without your team filling the gaps, Eightfold AI is the only one here that arrives finished. If you would rather see inside the model than read a compliance page, Pymetrics has allowed more scrutiny than anyone else in the category.

Testlify suits the buyer whose priority is the evidence underneath the score. We hold ourselves to the same demand we make of everyone else: ask for the report, the methodology and the numbers. Treat HireVue and Workday as tools you would have to audit yourself, and price that work into the contract rather than discovering it later.

Whatever you choose, the audit, the published summary and the candidate notice stay yours. Buying a better tool shortens the work. It does not move it.

## What to Put Underneath the Score

Pick the tool whose audit you can read in full. Treat every other one as a tool you will have to audit yourself. That includes ours.

What we can put underneath a hiring score today is evidence that the test relates to the job. Our [3,500+ validated skills assessments](https://testlify.com/) are built by industrial-organizational psychologists. Try them free for seven days, and judge them by the same standard you apply to every other AI recruitment tool.

## Frequently asked questions

**How to use AI tools for recruitment?**

Use them to narrow and order the pool, not to issue rejections. Let the tool rank candidates. A recruiter then reviews a defined band of those candidates and signs off on every advance and every rejection.

**Does an AI recruitment tool need a bias audit outside New York City?**

In practice, yes. Local Law 144 follows the candidate, so one applicant living in the five boroughs pulls you in. Title VII's adverse-impact standard applies nationwide regardless.

**Who pays for a bias audit, the employer or the vendor?**

Usually the employer, because the obligation is the employer's. A vendor-commissioned audit can support your file, but it does not remove your duty to publish a summary and notify candidates.

**Is a bias audit the same as a validation study?**

No. A bias audit compares selection rates across groups. A validation study shows the score actually relates to performance in the role. A tool can clear the 80% line and still predict nothing useful.

## Sources

1. https://eightfold.ai/trust/bias-audit-results/
2. https://www.brookings.edu/articles/for-some-employment-algorithms-disability-discrimination-by-default/
3. https://epic.org/documents/comments-of-epic-on-the-eeocs-draft-strategic-enforcement-plan-for-2023-2027/
4. https://www.seyfarth.com/news-insights/mobley-v-workday-court-holds-ai-service-providers-could-be-directly-liable-for-employment-discrimination-under-agent-theory.html
