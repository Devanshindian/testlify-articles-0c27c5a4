# Hiring Hackathon Judging: Rubric, Calibration, AI Rule

The demos land, the panel takes notes, and then every judge turns out to have measured something different. A topline report with SHRM Labs found 45.8% of HR and talent acquisition practitioners call their own hiring process inconsistent. A hiring hackathon is a work sample test: real work, scored inside a hiring decision.

A score that changes with the judge is a hire that changes with the judge. Fix the scoring, not the event. Three things decide it: the rubric, a panel that agrees on how to read it, and the rule on AI.

## Quick answer

A hiring hackathon gives you a usable signal only if the scoring exists before the event does. Build the rubric from the job description, not from what the demos happen to show. Use five or six weighted criteria, and write down what a failing, an acceptable and a top submission looks like on each.

Then have judges score practice work privately and compare the numbers, so you can fix any wording two people read differently. Publish the AI rule with the brief: what candidates may generate, what they must disclose, what disqualifies them. Score how well AI was used, not whether it was.

## Your Hackathon Is a Work Sample Test, Not a Demo Day

Ask candidates to build something real in a realistic environment and you have run a [work sample test](https://testlify.com/job-simulation/). It sits inside a hiring decision, so the scoring carries the same legal and practical weight as any other selection test.

That is good news. Work samples show a standardized mean difference of roughly 0.38 between Black and white test-takers, against roughly 1.0 for cognitive ability tests, so the adverse impact risk is far lower (adverse impact is when a hiring step rejects one group at a much higher rate than another). But only if you score on job-linked criteria set in advance, worked out through structured analysis rather than guesswork.

Because the tasks come straight from the job, a rubric also meets the content-validity requirement in the Uniform Guidelines on Employee Selection Procedures (1978). It is a legal argument, not just a fair one.

## The Rubric: Five or Six Criteria, Fixed Weights, One Total

Score five or six criteria, not 10, and fix the weights before the event opens. Standard practice for a work sample is to name in advance the five or six skills the exercise tests, then pick one scale and stick to it. Too many criteria tire the judges and scores drift; too few and you cannot tell what went wrong.

Pull those criteria from the job description, not from what the demos happen to show you. That is the difference between a rubric and a scorecard.

### Weight the Criteria, Then Run the Same Math on Every Candidate

One formula, applied identically to every submission. Score each criterion on a fixed scale, divide by the maximum, multiply by that criterion's weight, and add the results into a total out of 100. Do it in a spreadsheet, then check the ranks look sane before anyone makes a call on them.

Weighting is what stops a candidate who presents beautifully from finishing level with one who built the thing. Here is a working split for a build-style hackathon. Change the percentages to suit the role, keep them adding to 100, and publish them before the event.

| Criterion | What you are scoring | Weight | Score band anchors (1 / 3 / 5) |
|---|---|---|---|
| Technical execution | Code quality, technical difficulty, how much of the demo is real versus faked  | 30% | 1: no working build · 3: works on the happy path · 5: handles edge cases cleanly |
| Problem solving | Understands the problem, sound approach, trade-off analysis, optimization  | 20% | 1: no evidence · 3: one workable approach · 5: weighs alternatives and picks well |
| Feasibility and workflow fit | Whether the build could ship and fits how the team works  | 20% | 1: demo only · 3: shippable with rework · 5: ready to hand off |
| Testing | Common and corner cases, self-correcting bugs  | 15% | 1: none · 3: happy-path tests · 5: corner cases covered |
| Communication | Clarifies, explains the approach, communicates while building  | 10% | 1: cannot explain the build · 3: explains what · 5: explains why |
| Originality | Novelty of the idea, creative use of the theme or tools  | 5% | 1: template output · 3: familiar idea, own execution · 5: an approach a judge would not have thought of |

A 0 sits below the 1 band on every row. It means no evidence at all, not poor work. A missing artifact and a weak one are different findings.

## What a 1, a 3, and a 5 Actually Mean

"Score from 1 to 5" is not a rubric. Judges need written descriptions of what [each point on the scale](https://testlify.com/hr-glossary/what-is-a-behaviourally-anchored-rating-scale-bars/) looks like, like the anchor column in the table above. Vague criteria produce noisy scores however strong the criteria themselves are.

Three anchors hold a five-point scale steady: what a failing submission looks like, what an acceptable one looks like, and what a top one looks like. On a criterion like problem fit, a 1 reads "solves something the brief did not ask for." A 3 reads "addresses the stated problem with an obvious workaround." A 5 reads "handles the stated problem including the edge case named in the brief."

Two and four sit between the written bands. Attach a real example to each anchor, so a 5 means the same thing to every judge instead of whatever that judge privately calls a strong demo.

### Name the Evidence a Score Is Allowed to Rest On

The rubric also has to say what a judge may look at. Only the submission and the stated requirements, or outside knowledge too? Does missing documentation cost points? May a judge credit what a candidate meant to build, or only what shipped?

Tight evidence rules cut disagreement between judges. Decide the edge cases in advance too: a working build that ignores a stated constraint fails on completeness, on instruction adherence, or on both.

Then make judges write. Ask for the reasoning first and the score second, which produces more accurate scoring and leaves a record of why the number landed there. Every low score carries a short rationale quoting the evidence behind it. Without that, you cannot tell later whether the rubric was wrong or the judge was.

## Calibrate the Panel Before Anyone Scores a Real Candidate

Calibration happens before live judging opens, and it is not the same job as writing the rubric. The hackathon judging rubric says what a strong submission looks like; calibration proves every judge reads that description the same way. Skip it and the disagreement does not go away, it just surfaces after a real candidate has been scored.

Run it as one 90-minute session, in this order:

1. **Walk the rubric together:** read out each criterion, its weight and the scale. Take questions until the panel uses the same words for the same behaviors.
2. **Score one or two practice submissions privately:** hand each judge an anonymized sample, past candidate work or a seeded practice build, and let nobody discuss it.
3. **Put every score on one sheet:** all judges' numbers for the same submission, side by side, revealed only once everyone has finished.
4. **Discuss only the outliers:** one judge gave a 2, another gave a 5 on the same criterion, so look at that gap. Leave the rows where everyone landed within a point.
5. **Rewrite the ambiguous wording, not the scores:** you are not trying to agree on the right number for a practice item. You are hunting the sentence two judges read differently, and fixing it before it costs a real candidate.

The private-then-compare order does the work. Without it, the most senior voice in the room sets the answer before anyone else has looked at the evidence. When two judges still cannot agree, make each one point at something the submission actually shows. A feeling is not a justification [1].

### What Calibration Fixes, and What It Will Never Fix

Calibration fixes unwritten standards. It does not make the panel neutral.

Judges hold back extreme scores early, saving room in case something stronger turns up, so the first submissions get marked harder than identical ones seen later. They also drift toward each other's numbers, and that gets worse on a panel that has not built trust before scoring begins.

Structure does narrow the gap. Anchored, structured scoring cuts the Black-White standardized mean difference in ratings from d = 0.56 to roughly d = 0.23. That comes from process design, not bias training, and it is a reduction rather than an erasure.

It narrows the door bias comes through; it does not close it. In a 2012 Yale study in the Proceedings of the National Academy of Sciences, science faculty rated an identical application as more competent when the applicant was labeled male, and offered that person $4,000 more in starting salary. Trained evaluators were not immune.

So treat a calibrated score as an approximation of judgment, not a substitute for it. Two independent readers per submission, plus a second reader on anything borderline, does more for a close call than another round of alignment talk.

## How to Calculate Inter-Rater Reliability, and Fix Splits

Calibration tells you the panel talked. Agreement tells you the rubric worked. Double-score a slice of submissions, commonly 10 to 20 percent, and settle every disagreement rather than letting it pass.

Measure it properly: Cohen's kappa when two judges score the same work, and Krippendorff's alpha (an agreement statistic that copes with more than two raters and missing scores) when the panel is bigger. In recruiting calibration practice, anything below 0.40 is read as inconsistent evaluation, tracked monthly, with dips investigated rather than ignored.

Read the split itself, not only the coefficient. Two judges more than one point apart on the same criterion is your trigger to reconvene [1]. If it keeps happening on the same criterion, the rubric is the problem, not the panel [1].

Two defects cause most of it. Dimensions overlap, so "quality," "impact" and "completeness" partly mean the same thing and judges score them inconsistently. Or the anchors are weak, offering adjectives where they should give a concrete threshold.

Never average a split. Resolve it by discussion or a third reviewer, then log which criterion caused it, the decision, and the reasoning. That log becomes the precedent for the next ambiguous submission and the raw material for your next rubric revision. It is also what you reach for when a placement gets challenged, instead of asking judges to reconstruct their thinking from memory.

### Re-Calibrate on a Schedule, Not Just Before the First Event

Scores drift. After repeated rounds on the same role, averages tend to inflate toward "strong yes" or bunch in the middle, and both are bias signals rather than a sharper panel. A recurring session (quarterly is a reasonable cadence) re-anchors everyone to the written rubric.

You do not need a standing meeting. Send three scored sample submissions by email or chat, have each judge rate them privately, then compare during a meeting you already hold. A judge who joins after the first calibration runs a short version before scoring anything live. Keep the rubric in a shared system, so each round is checked against the document and not against someone's memory of the discussion.

## Set the AI Rule Before Candidates Set It for You

All of that assumes the submission is the candidate's own work. With no stated AI rule, your scores compare tool access, not skill.

Candidates are already using these tools. A 2023 survey found almost half of job seekers were using ChatGPT to write resumes and cover letters [2], and 70% of them reported a higher response rate [2]. Legal guidance on the practice notes employers usually do not spot it [2].

A hackathon submission is where it disappears completely. Code, a build plan and a demo script all look the same whether a person or a model produced them. Your panel cannot separate the candidate's own judgment from generated output unless the submission asks for it directly.

The instinct is to ban it. Some organizations do, making candidates agree to no AI use anywhere in the process, with disqualification if it is detected. Commentators call that extreme, since using AI to sharpen an application is now treated as a basic job-market skill rather than a violation.

What candidates complain about is not the rule. It is that nobody publishes one, so the same behavior reads as too much AI to one judge and too little to the next. State the line.

## What Candidates May Generate, and What Disqualifies

The line that holds up is preparation versus substitution: AI may scaffold commodity work, but it may not produce the thing being judged. Publish that tier with the brief, not after submissions land, because nobody can build to a line they cannot see. Any restriction also needs a nondiscriminatory business reason decided in advance, never applied afterwards because a judge disliked how one team worked [2].

Running several tracks? Set the tier per track and post it on each track's brief [2]. A senior engineering track can carry a stricter no-generation rule than a product or analyst track [2].

### Boilerplate Is Fine. The Feature Code Is the Test.

Boilerplate has a usable test. Delete a block: if a template from the internet could replace it in five minutes, it is boilerplate. If deleting it breaks something only your product does, that is the feature code where the hiring signal lives. Scaffolding is work most engineering teams already treat as commodity, not the skill the assessment exists to measure.

The harder question is who breaks the problem down. AI works well as a fast implementer given clear direction, and falls apart handed a whole scenario at once. A candidate who splits the problem and directs bounded pieces to a tool is showing the judgment you are testing. One who pastes in the brief and submits the output is not.

### The Permitted and Prohibited List

| AI use | Example in a build submission | Policy tier | How judging treats it |
|---|---|---|---|
| Code generators for scaffolding | React component scaffolding: imports, state declarations, prop-types  | Permitted where the brief allows it [3] | Scored normally, no penalty  |
| Repeated setup and wiring | Database connection setup, error-handling wrappers, REST route registration  | Permitted where the brief allows it  | Scored normally, no penalty  |
| Summarizing prior work | AI-assisted write-up of a past project in the submission README  | Permitted  | Never used against the candidate  |
| AI drafting written reasoning for non-timed tasks | Generated design rationale where reflection is what you are assessing  | Disclosable  | Explanation required at the live defense |
| Live prompting during a supervised round | Real-time answer generation in the demo or defense session  | Prohibited [3] | Disqualifying |
| Bypassing test controls | Third-party help on a coding or aptitude test  | Prohibited  | Disqualifying |
| Identity masking | Deepfakes, synthetic voice, or impersonation on a video defense  | Prohibited  | Disqualifying |
| Passing AI-authored substance as your own | Feature code, architecture decisions, or write-ups submitted undisclosed [3] | Prohibited  | Disqualifying |

Two phrases carry over word for word. Say that permitted uses match how people now work and do not disadvantage other candidates. Say that disclosure will never be used against a candidate and only helps you assess the application properly. Keep the rest operational: what must be visible on screen, not what the rules stand for.

## What a Complete AI Disclosure Statement Says

A complete disclosure, the middle tier in that table, names three things: the tool, the task it did, and the human review that followed [4]. Missing one makes it incomplete rather than absent, and your rubric should score it that way. Publishing has already landed on a sentence that transfers to a build submission almost verbatim: "the author(s) used [NAME OF TOOL / SERVICE] in order to [REASON]. After using this tool/service, the author(s) reviewed and edited the content as needed and take(s) full responsibility" [4].

Give it its own mandatory field in the submission form, next to the code and the write-up. Buried in terms-of-service text, it goes unread and unwritten. Two to four sentences is enough. One fixed structure saves both sides work: the candidate stops guessing at phrasing, and the judge knows exactly what to look for.

### Scale the Disclosure to How Much AI Shaped the Build

How much detail you ask for should track how much AI shaped the graded work, not whether it was touched at all. A prose-polishing pass needs one confirming line: "no new content was generated, and all edits were reviewed by the author". AI that wrote or debugged judged logic needs specifics. Which files, which functions, which decisions.

Ask for it category by category rather than as a single checkbox. Use the build-relevant buckets: scaffolding and boilerplate, debugging, code review, and documentation. Each maps to a different part of your rubric, so a judge scoring architecture can see whether AI touched architecture. A candidate who writes "used AI to help" scores lower on this line than one who itemizes where AI entered the build.

### Attestation, Disclosure, and What Happens When They Hide It

[Attesting to no AI use](https://testlify.com/candidate-honesty-policy-and-agreement/) and disclosing AI use are different policies, not two wordings of one [2]. An attestation is a ban on the honor system. A disclosure tier assumes some AI use and makes the extent of it the thing you score.

Write the consequence down before the event. Employer codes already state that failing to disclose, or misrepresenting deliberately, may mean disqualification from the process or a withdrawn offer [3]. Put the matching point deduction or disqualification rule in the rubric in advance.

## Spotting Undisclosed AI Use in a Submission

A policy only holds if you can check it, and the check that works is the live defense conversation, not a detector score. AI produces polished work across a huge range of tasks, so only talking to the candidate shows whether they understand what they handed in. Everything below feeds that conversation.

Patterns to flag before the candidate sits down:

- Repeated phrasing and generic content that never touches the specific task set, plus formatting that shifts inside one submission [2].
- Tone or writing style that changes within a single document, or across a candidate's materials [2].
- Overlap between candidates, where two independent submissions share wording or structure [2].
- A solution that arrives fully formed, with no commit history, no noted dead ends, no documented trade-offs.
- Answers built to score maximally against a known rubric, like complexity analysis volunteered where nobody asked for it.
- Over-documented code, with line-by-line comments human developers rarely write.

None of these is proof. [Detection tools](https://testlify.com/the-ongoing-battle-technology-vs-cheating-in-online-tests/) misfire badly enough that no serious guide treats them as the only indicator of misconduct, and non-native English writers get flagged at higher rates. So turn every tell into a question: "walk me through why you chose this loop structure". What the candidate says next is the evidence you score.

Scoring that conversation is its own discipline, and we cover it in full in [how to score video and audio interview responses](https://testlify.com/how-to-score-video-and-audio-interview-responses/).

## Score How Well AI Was Used, Not Whether It Was

That evidence needs its own line on the rubric, and the line is not "AI used: yes/no." Score how well the candidate directed the model, checked what came back, and built on it.

Practitioners are split. One camp holds that the deliverable is the only thing worth judging and the route there is nobody's business. The problem with that is simple: a score that ignores process rewards whoever had the better tool.

So score the behavior. Give the criterion its own anchored bands and a required evidence component, the same design that keeps every other criterion on your rubric from being gamed. In practice that means separate line items rather than one holistic AI score: prompting and iteration shown, output verified and debugged by the candidate, disclosure complete and specific.

You grade them from the disclosure statement plus whatever process trace the candidate submits, such as a prompt log, git history, or a walkthrough of what they built versus what the model wrote. Most of it is easiest to judge during [the live defense](https://testlify.com/proctored-live-coding-projects/), where you watch the judgment happen. What separates a 5 from a 3 is not tool avoidance. It is who wrote the better specification, made the better architectural call, and debugged more effectively on top of generated output.

### Stop Judges Penalising the Candidates Who Told You the Truth

Disclosure costs the candidate something measurable. Across 16 studies with more than 27,000 participants, text labeled as AI-assisted was rated lower than identical text labeled human-written. Perceived quality did not explain the gap. Authenticity did: the work felt less like it came from a person.

So promising that disclosure will not count against a candidate does not make it true. Anchor the bands, and make every AI-use score name the specific evidence behind it, exactly as the rest of your rubric already does. Otherwise you teach candidates to stop telling you.

## Build the Rubric Before You Book the Venue

The event is the easy part. Hackathon judging holds up when the rubric, the calibrated panel and the AI rule all exist before submissions open.

Testlify covers the screening either side of it. Our [3,500+ validated skills assessments](https://testlify.com/) are written by industrial and organizational psychologists, checked for adverse impact, and scored on the same criteria for every candidate. Start with the role your next hackathon is hiring for, and see what we already test before you write a brief.

## Frequently asked questions

**How many judges do you need on a hiring hackathon panel?**

Enough for two independent reads of every submission, so three to five for most events. A bigger panel adds scheduling cost, not signal. Bring in a third reader only on borderline results.

**Is a hiring hackathon better than a take-home assignment?**

A hackathon shows how someone works and lets you question them live. A take-home costs candidates less time and travel. Pick the hackathon when collaboration and judgment under pressure are the skills you are hiring for.

**Do you have to pay candidates for a hiring hackathon?**

Pay when the event runs long or the work has commercial value. A few hours of assessment work is normally unpaid. A full day deserves a stipend, and never ship a candidate's build without paying for it.

**Should you share hackathon judging scores with candidates?**

Share the criterion-level feedback, not the leaderboard. The rationales your judges already wrote turn into usable feedback with almost no extra work. Keep other candidates' scores private, and say up front what you will share.

## Sources

1. https://www.scu.edu/provost/institutional-effectiveness/assessment/doing-assessment/using-rubrics/
2. https://www.klgates.com/Should-Job-Applicants-be-Permitted-to-Use-Artificial-Intelligence-3-27-2024
3. https://careers.fidelityinternational.com/working-here-overview/candidate-code-of-conduct-use-of-artificial-intelligence-ai/
4. https://www.elsevier.com/about/policies-and-standards/generative-ai-policies-for-journals
