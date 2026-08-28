# Video Interview Platform That Stops Deepfakes and Proxies

Fake applicants are getting hired at scale, and Gartner expects one in four job profiles worldwide to be fake by 2028. The DOJ charged one person for placing 68 stolen US IDs into jobs at 309 US firms [1], [1]. Those firms paid out $5 million in wages to people who were never there. Most video interview platforms say they check who the applicant is, but few say how, so here are six, judged on what they actually publish.

## Quick answer

Most video interview platforms mix up two things: AI video scoring judges what someone says, while an ID check proves who is saying it. To stop a skilled faker you need three layers: lock the camera path, protect what it sends, and spot fake video. Four vendor claims fall apart on their own: ISO 30107-3, deepfake artifact spotting, a secure SDK, and active liveness. The best setups pair machine flags with a person who reads every flag.

Match the checks to the job. High-access roles get all three layers. A first screen can skip the ID check if a later stage does it.

## Deepfakes and Proxy Candidates Are a Proven Hiring Threat

A [proxy candidate](https://testlify.com/proxy-interview/) is someone paid to sit the interview or the test in place of the real applicant. The goal is to land a job under a name that is not theirs. It is fraud, and the record on it is now public.

The DOJ charged one person for helping North Korean workers use 68 stolen US IDs and win work at 309 US firms [1], [1]. The list took in Fortune 500 names, plane makers and media groups. One ring alone drew $5 million in wages and left victims with $3 million in cleanup and legal bills.

The rest of the damage, in numbers:

| What it costs you | Amount |
|---|---|
| One insider fraud case | $701,500  |
| Each OFAC breach | From $50,000  |
| Recruiters who have watched a stand-in turn up | 31%  |

Vendors write down very little of this. One review of more than 80 video interview platforms scored them on ease of use and how well they plug into your ATS. Clean hiring, ID checks and fraud spotting were not in the rubric at all,.

We cover the layered checks that catch a stand-in on a live call in our full guide to [preventing impostors in video interviews](https://testlify.com/prevent-impostors-in-video-interviews/).

## What Vendors Mean When They Say They Check ID

Vendors stick the words "identity verification" on anything from a webcam snapshot to a real document check with a face match. The phrase on its own tells you nothing.

Start by pulling apart the two things they blur. AI video scoring reads the transcript and the way someone speaks, so it judges the answer, not the person [2]. It hands your reviewers the highlights to sort. A faked entry that scores well can move on with nobody looking.

Four vendor claims deserve a straight challenge:

- "We are ISO 30107-3 certified" covers photos and masks, not a feed pushed straight into the app.
- "Our model spots deepfake artifacts" looks only at the picture, so a virtual camera never shows up.
- "Our SDK is a secure boundary" assumes a wall that attackers take apart.
- "We use active liveness" (blink, turn your head) fails when the whole feed is fake.

A serious vendor spells out the full stack: lock the camera path, protect what it sends, and add fake-media spotting on top. Outside lab tests tell a real control from good copy, such as CEN/TS 18099 for virtual cameras and iBeta Level 3 for spoofing. Testers attack these systems on purpose to find where they break.

## How We Chose: The Six Platforms at a Glance

We judged each one on what it puts in writing. A platform that protects your hiring names its controls: live or passive liveness, ID document checks, face match, deepfake spotting, or AI conversation review. A feature nobody publishes does not count.

| Platform | Best for | ID checks built in | Price |
|---|---|---|---|
| HireVue | Structured scoring at scale | None published  | From $35,000/yr  |
| [Spark Hire](https://support.sparkhire.com/hc/en-us/articles/39488633780379-AI-for-One-Way-Video-Interviews-Overview-for-recruiters-and-managers) | Small teams, recorded screens | None published  | $249/mo  |
| Willo | EU data rules, high volume | Outside add-on only  | Not published |
| VidCruiter | Hiring the rules govern | ID check plus proctoring  | From $5,000/yr  |
| [Hireflix](https://hireflix.com/en/pricing) | Fast first-round screens | Passive selfie only | $75-$150/mo [3] |
| Testlify | Fraud checks inside the test | Face match, watching, human review  | Not published |

Two of the six put ID controls in writing. The rest expect you to check somewhere else.

## HireVue: Strong Scoring, No ID Checks

HireVue is the enterprise standard for [structured video interviews](https://testlify.com/how-to-score-video-and-audio-interview-responses/), scoring what people say and how they say it. It publishes no ID controls at all, so it is strong on judging answers and weak on fraud.

Everyone gets the same questions, the same scoring guide and a timed recording,. The top tier adds role-based tests, games and coding tests. What it never checks: an ID document, a face match against the live person, liveness, browser lockdown, or a stand-in.

The legal side matters here. HireVue paid $3.75 million to settle a class lawsuit over taking face maps and voiceprints from Illinois applicants with no written consent. It dropped face-expression scoring back in 2020. A judge gave that deal early approval on June 25, 2026, and the message is plain: tell people what you collect.

Essentials starts at $35,000 a year, with live and recorded interviews but no AI screening,. Enterprise runs $50,000 to $145,000 and adds AI screening, bias audits and FedRAMP. Scored video is what the new state AI hiring laws aim at, so this one carries the biggest legal load.

## Spark Hire: Recorded Screening for Small Teams

Spark Hire serves more than 7,000 firms, mostly small and mid-size teams with lean hiring staff,. You get recorded and live interviews, AI summaries and scoring, skills tests, auto reference checks and 40+ ATS links,. Most buyers are live inside 30 days. At $249 a month billed yearly, there is no cap on jobs or users.

It plays answers back in 50+ languages, sums up the key points, and scores them against skills like how well someone talks and gets things done [2], [2],. Tested on more than 68,000 entries, those scores match human raters over 90% of the time.

None of it proves the face on camera applied for the job. There is no liveness check and no face match against a document. For a first screen where a background check or an in-person final round catches it later, that gap is fine. For hiring the rules govern, plug it elsewhere.

## Willo: Recorded Screening Built for EU Data Rules

Willo runs recorded interviews only, on servers in Europe, built around GDPR. That removes the legal homework of proving a US-hosted tool meets [EU data rules](https://testlify.com/how-do-recruitment-platforms-handle-gdpr-compliance/). Data at rest is encrypted with AES-256, and transfers run under the EU-US Data Privacy Framework. It holds ISO 27001 and is GDPR compliant.

It handles 18 languages  and scales to 20,000 applicants in one hiring round, which suits staffing firms screening at speed. There are no live interviews, which sets it apart from the rest of this list.

You get screen lockdown and AI flags for cheating, but ID checking is an outside add-on rather than built in. That works when someone else does the check later.

## VidCruiter: For Hiring That Has to Pass an Audit

You can shape VidCruiter more than any other tool here, which is why it turns up in government, schools and hiring the rules govern. Elections BC, Australia's Prime Minister & Cabinet, K-12 districts and colleges all use it.

It runs live and recorded interviews with the rating guide sitting in the screen. Extra modules cover skills tests, auto reference checks, audio-only interviews and proctoring. Proctoring checks ID before the test, watches for tab switching, blocks copy and paste, and records the session for later audit. The same questions and scoring for every applicant cut bias at scale.

It starts at $5,000 a year, billed per module by usage, and your cost moves with hiring volume, the modules you turn on and how much setup help you need. Going live takes 4 to 8 weeks, and your team will need training. Pick it when your process is set by rules and has to be written down, not when speed is the point.

## Hireflix: One-Way Video Interviews Without the Friction

Hireflix drops the login and the scheduling so more people finish. You get a link and answer on your own phone, in your own time. The only ID step is a passive selfie, with no prompts and no gestures. That trades proof for finish rates.

The trade pays. Passive selfies finish above 95% [4], against 60% when you make people blink and turn on cue [4]. Screening time drops by up to 60% next to a phone screen. It costs $75 to $150 a month by company size, with no per-answer charges [3].

What it will not do is prove the face matches the document, or catch a deepfake or a stand-in. Use it when the ID check happens later, in a background check or a live final round.

## Testlify Builds Proctoring and ID Checks Into the Test

Testlify puts skills tests, AI interviews and [live proctoring](https://testlify.com/live-proctoring/) in one flow, with ID checks running the whole way through. The fraud checks are built in, not bolted on after.

Face detection, photo ID checks, AI-help detection, full-screen enforcement, tab and copy-paste watching, live room checks and session recording all sit inside the test. Everything lands in one place: one recording, one question log, one profile, all for your reviewers.

It checks who the person is before the test starts, watches how they behave during it, then hands your team any flagged session with the video and the event log. A person makes the final call, so a wrong flag never rejects an honest applicant.

## Match Your Checks to the Role Risk

One set of checks for every role is the wrong answer. A call-centre screener and an engineer with live system access do not need the same proof. The best setups turn controls on in three levels, by how much access the job carries.

Level 1, on every test: browser lockdown, webcam capture and IP watching. These catch casual cheating and cost honest applicants nothing. A clean session needs no review at all.

Level 2, where the test decides the hire: live face match, how the person behaves, and flags on odd answer timing. The trigger is access, not job title. If the test score and the interview scorecard disagree, look harder before you make an offer.

Level 3, a person reads the flags. They watch the recording, weigh the odd moment against the whole session, then choose: pass, retest or reject. One flag should raise the bar, not end the process. Several together should trigger a closer check, and a confidence score is a triage signal, not a verdict,.

For the full buying checklist behind these levels, read our guide to choosing an [AI proctoring solution](https://testlify.com/ai-proctoring-solution/).

## What to Demand From a Vendor in Writing

[A useful RFP](https://testlify.com/hr-glossary/request-for-proposal-rfp/) splits the sales claim from what you will actually run. Ask for proof against your roles, your data, your decision rule and your legal line. Get these in writing before you sign.

1. Run a full session live: different devices, a dropped line, a failed ID check, a disputed flag, peak load.
2. Show how the risk score is worked out, and whether you can move the threshold,.
3. Tie every flag to a timestamp and the video, in one record with camera, audio, screen and event logs,.
4. Say who watches: the machine, a person, or both.
5. List the auto flags: face gone, a second person, ID mismatch, extra screens, banned apps, virtual setups.
6. Say what happens after a flag, and write the rule for a failed result. A dropped line is not cheating.
7. Show proof it works on roles like yours, not one general accuracy number.
8. In the contract: no training on your data, a deletion date, limits on who else sees it, and who pays if it goes wrong. Your BIPA duties (the Illinois law on face and voice data) cannot be handed off.

A machine flag plus a human check is still the strongest control there is.

## What Fraud Checks Cost

Most teams get the best return by pairing cheap process fixes with paid tools on the interviews that matter. Camera-on rules, an ID check and some training cost almost nothing. Platform tools charge per interview and grow with volume. Full face-and-behaviour fraud tools earn their price on senior, high-access roles, where a bad hire costs you lost work, legal risk and a second search,.

You cannot build the case from published numbers. It rests on what one case costs you and how much access the role carries. Fraud in a call-centre seat wastes money. Fraud in an engineer's seat means the wrong person holds the logins.

Budget $15,000 to $40,000 for setup. If you hold face or voice data, you also need a full-time IT person on data protection. Set your response levels around business impact, not the vendor's confidence score. One odd answer earns a better follow-up question, not a verdict.

This is a change to how you hire, not just a video interview platform you buy.

## Scale your controls to role risk

The safest hiring stacks machine flags on top of human review, set by role risk. Testlify builds proctoring and ID checks into the test itself, so nothing sits in a separate tool and every flag points at evidence. We surface anything odd while the test runs and leave the final call to you, so a wrong flag never rejects an honest applicant. Start with our [assessment platform](https://testlify.com/) to pair skills testing with built-in proctoring.

## Frequently asked questions

**What is the best video interviewing platform?**

It depends on the role and your legal load. HireVue is best at structured scoring, VidCruiter at hiring the rules govern, Testlify at fraud checks built into the test. Match the checks to how much access the job carries.

**What is a proxy candidate?**

Someone paid to sit the interview or the test in place of the real applicant. The person on camera is not the person you hire. It is fraud, and it targets jobs with money or access behind them.

**Can deepfakes pass a video interview?**

A good one can beat a basic liveness check. Stopping it takes three layers: lock the camera path, protect what it sends, and spot fake media. One layer on its own fails.

**Do video interview platforms prevent cheating?**

Most offer browser lockdown and webcam capture, which catch the obvious. They differ a lot on face match and flagging odd behaviour. Mid-level flags beat nothing, but only a human review stops it.

**When do you need identity verification in hiring?**

For jobs with access: an engineer, a finance seat, anyone holding systems. Check ID and watch the session. A first screen can skip it if a background check or in-person final round covers it later.

## Sources

1. https://www.justice.gov/opa/pr/arizona-woman-sentenced-17m-information-technology-worker-fraud-scheme-generated-revenue
2. https://support.sparkhire.com/hc/en-us/articles/39488633780379-AI-for-One-Way-Video-Interviews-Overview-for-recruiters-and-managers
3. https://hireflix.com/en/pricing
4. https://www.miteksystems.com/blog/beyond-deepfake-detection-building-resilient-identity-systems
