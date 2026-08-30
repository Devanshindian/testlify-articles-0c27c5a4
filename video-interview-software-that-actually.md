# Video Interview Platform That Stops Deepfakes and Proxies

You are three interviews into a shortlist and the person on your screen answers everything well. What the screen cannot tell you is whether they are the person who turns up on day one. They may be a stand-in who hands the laptop over once the offer clears.

That gap is what vendors mean by identity verification, and almost none of them say what it covers. We looked at six video interview platforms and what each one documents about proving who is on camera. You can then choose on evidence rather than on a marketing page.

## Quick answer

Two different jobs get sold under one phrase. AI video analysis scores how somebody answers. Identity verification proves who is answering.

HireVue and Spark Hire score answers well and document no identity checks at all. Willo and Hireflix leave identity to a background check or a final round. VidCruiter and Testlify run proctoring with an ID check before the session opens. Match the control to the role, not to the budget.

## Deepfakes and Proxy Candidates Are a Documented Hiring Threat

A [proxy candidate](https://testlify.com/proxy-interview/) is a simple trick with an expensive ending. One person sits the interview and answers well. A different person shows up on the payroll. Nobody is looking for the switch, because the process was built to score answers rather than to check who gives them.

### Why deepfakes and proxy candidates are a documented threat

The threat is documented at federal level. The Department of Justice charged Christina Chapman for helping North Korean operatives use 68 stolen American identities. Those operatives took jobs at 309 U.S. companies [1], [1].

Those were not small firms that skipped a step. They ran interviews, checked references, shipped laptops and paid salaries for months. Nobody noticed that the people drawing those salaries were not who they claimed to be.

In Greenhouse's 2026 research, 31% of recruiters said the person who interviewed was not the person who applied. Almost a third. If you ran a hiring round last year, somebody on your panel probably saw this and filed it as a bad connection.

So the question for a vendor is a narrow one. Which identity controls do you document, and where can I read them? The list is short enough to hold in your head.

Liveness detection proves a live human is sitting in front of the camera. An ID document check and a face match tie that human to a name. Deepfake detection looks at the video itself for signs of synthesis. A platform that offers none of these can still be a good interview tool. It is simply not doing this job.

We have set out the full stack of checks that catches a proxy or deepfake candidate in our guide to [preventing impostors in video interviews](https://testlify.com/prevent-impostors-in-video-interviews/).

## How Vendors Hide What 'Identity Verification' Actually Means

AI video analysis transcribes the interview and scores the answers against competencies. It tells you how well somebody communicates, which is useful. It says nothing at all about who was sitting in the chair. A fraudulent candidate who answers well scores well and moves forward.

Identity verification is a stack rather than a feature. A serious vendor describes all three parts: securing the camera path, protecting the payload, and running synthetic-media detection on top. All three matter, because an attacker who feeds a prepared video straight into the browser never touches the camera. Detection that only inspects the picture is looking at a clean picture of a fake person.

So when a sales engineer says the product has identity verification, ask which layer it covers. Ask how you would see the result. If the answer is a webcam snapshot filed beside the recording, that is a photograph, not a control. Write down what you were told.

## How We Compared These Video Interview Platforms

Video interviewing software is a cloud tool for interviewing candidates remotely. Some interviews run live, in a scheduled call. In a one-way interview the candidate records answers to set questions alone, and your team watches later.

We judged these six on one thing above all others: what the vendor documents about proving identity, not what a product page implies. We also noted who each tool is built for, and what it costs to start. A control you cannot afford to switch on protects nobody.

| Platform | Best for | Identity control it documents | Starting price |
|---|---|---|---|
| HireVue | Structured, scored interviewing at scale | None documented  | $35,000/year  |
| Spark Hire | Async screening for small teams | None; the AI reads answers  | $249/month  |
| Willo | High-volume European hiring | Lockdown and flagging; ID via third party  | Not published |
| VidCruiter | Regulated and government hiring | ID check before testing, proctored  | $5,000/year  |
| [Hireflix](https://hireflix.com/en/pricing) | One-way video interviews at speed | Passive selfie liveness only | $75-$150/month [2] |
| Testlify | Assessment with identity built in | Verify, monitor, then human review  | Not published |

Start with the table. The sections below show what each gap costs you.

## HireVue: Structured Assessment, No Identity Verification

HireVue is the enterprise default for structured, scored interviewing, and it is good at that. The AI scores the transcripts, so your panel argues about a rubric instead of a gut feeling.

What it does not do is check who is answering. HireVue documents no ID verification, no face match, no liveness detection and no browser lockdown. Essentials pricing starts at $35,000 a year, so this is a decision about scope rather than budget.

It also carries the heaviest compliance load here. HireVue settled a class action for $3.75 million over collecting facial geometry and voiceprints from Illinois applicants without written consent. Run scored video under a biometric privacy law and you owe candidates a written notice before anyone presses record.

## Spark Hire: The SMB-Friendly Async Option

[Spark Hire](https://testlify.com/testlify-vs-spark-hire-comparison/) is for the team of three with two hundred applicants in the queue. It runs async and live interviews, transcribes the answers and summarises them. It costs $249 a month with unlimited jobs and users, so nobody has to learn a procurement process to buy it.

Its AI reads answers, not identities. There is no liveness check and no face match against a document. The person on the recording is whoever the interview link was forwarded to.

For a first-round screen feeding into a background check and an onsite final, that is a fair risk to take. For a remote engineering hire who never meets anyone in person, it is not.

## Willo: GDPR-First Async Screening, Built for High-Volume European Hiring

Willo answers a legal question rather than a fraud one. Candidate data sits on European servers, encrypted at rest with AES-256. That removes an entire argument with your data protection officer before it starts.

On integrity it goes halfway. Willo locks the browser down and uses AI to flag likely cheating. Identity verification itself is an optional third-party add-on rather than part of the platform. The interview is monitored; the identity is somebody else's job.

That fits a staffing firm screening volume across several countries, where the final round happens face to face. It does not fit a remote hire who finishes onboarding with access to customer records.

## VidCruiter Leads in Configurability for Regulated Hiring

VidCruiter is built for hiring that has to survive an audit. That is why it turns up in government agencies and school districts. You configure the process to match a rule, then show anyone who asks how that rule was applied.

It is one of only two platforms here with proctoring inside the product. ID verification runs before the test starts, and the browser is watched for tab switching. Copy and paste is blocked, and the session is recorded so it can be reviewed afterwards.

Pricing starts at $5,000 a year and bills per module, so you pay for what you switch on. The flexibility has a cost that never appears on the invoice. Somebody has to configure all of it, and know your hiring rules well enough to encode them.

## Hireflix: One-Way Video Interviews Without the Friction

Hireflix optimises for one number: how many candidates finish. There is no login and no scheduling. A link arrives, the candidate answers on their own phone, and the only identity step is a passive selfie.

That choice shows up in the completion rate. Passive liveness clears above 95% [3]. Checks that stop candidates for gestures and multi-step prompts land nearer 60% [3]. Four in ten people walking away is a cost when you have thirty seats to fill.

At $75 to $150 a month [2], it is the cheapest way to run [one-way video interviews](https://testlify.com/hr-glossary/one-way-interviews/) at speed. Be honest about what you bought: a completion machine, with identity handled somewhere else.

## How Testlify Integrates Proctoring and Identity Verification

Testlify puts the identity check inside the assessment rather than beside it. The candidate is verified before the test opens. Behaviour and environment are monitored while they work. Anything unusual surfaces afterwards as a [flagged session](https://testlify.com/anti-cheating-and-proctoring/), with the video and the activity log attached.

That last part matters. A person makes the call, with the evidence in front of them. Automated scoring left to run alone rejects candidates whose connection dropped, or whose flatmate walked in.

Because the proctoring and the assessment are one product, the evidence lands in one record. Six months later, when somebody asks why a candidate was rejected, you can still show them.

## Interview Controls by Role Risk and Cost

There is no single setting that fits all of this. A call-centre screener and an engineer with production access are not the same risk. Run identical controls on both and you either irritate people for nothing, or leave the important role uncovered.

### Best-for scenarios: match platform to role risk

The frameworks that hold up use three tiers, switched on by role risk. Tier one runs everywhere: browser lockdown, webcam capture, basic monitoring. It costs an honest candidate nothing, and it catches the opportunist with a second tab open.

Tier two switches on when the assessment result largely decides the hire. It adds live facial comparison and anomaly detection on how the answers arrive. A finance associate who touches payment systems belongs here, even if the title reads junior. The trigger is access, not rank.

Tier three is a person. A reviewer opens the flagged session, watches it, and weighs the flag against everything else the candidate did. Then they decide: pass, re-test, or disqualify.

This tier is not the optional one. Internet outages produce timing anomalies that look exactly like cheating. A system that rejects on the flag alone turns away honest people all year, and nobody ever finds out.

### The RFP checklist: what to demand in writing

Vendor demos show you the happy path. Ask instead to watch a complete candidate session go wrong. Someone switches devices halfway through, a connection drops, an identity check fails, and the candidate disputes the flag. How the platform behaves in those five minutes is what you are buying.

Then get four things in writing. How the risk score is calculated, and whether you can set the threshold yourself. What a reviewer sees when they open a flag, and whether the evidence is pinned to the moment. What happens after a flag, as a matter of policy. A technical fault and a deliberate violation should not get the same response.

The fourth is who else may touch the recordings, and that one has teeth. Your obligations under a biometric privacy law cannot be handed to a supplier. So the contract must bar retention for model training and require destruction on your schedule. It should also restrict onward disclosure and allocate indemnity [4]. A vendor who will not write that down has told you something useful.

### Cost and defensibility: matching spend to risk

Most of the cheap wins are not products. A camera-on policy and an identity check at offer stage cost nothing. Twenty minutes teaching interviewers what a proxy looks like removes the easy attacks. Do those first.

Then spend selectively. Serious identity tooling earns its money where a bad hire is expensive and the role carries access. It is hard to justify on a seasonal retail round. Budget $15,000 to $40,000 for implementation at the enterprise end. The running cost is a person rather than a licence: somebody reviews flagged sessions, somebody owns the data policy.

The business case is not a published ROI figure. It is one question: what does it cost us if the wrong person holds these credentials for six months? For a call-centre seat, the answer is wasted salary. For an engineer, it is your source code and your customer records.

## Scale your controls to role risk

Layer the controls, and keep a person at the end of the chain. Technical detection catches what a reviewer would miss, and human review means a dropped connection never costs somebody a job.

Testlify builds the identity check into the assessment itself. The flag, the recording and the answer sit in one record your team can defend months later. Start with our [assessment platform](https://testlify.com/) to run skills testing and proctoring in one place.

## Frequently asked questions

**What is the best video interviewing platform?**

Depends on the risk in the role. HireVue for structured scoring, VidCruiter for hiring that must survive an audit, Testlify when identity matters inside the assessment. Match the controls to the access, not to the budget.

**What is a proxy candidate?**

Someone who sits the interview in place of the real applicant. The person you assessed and the person you hired are different people. Proxies target remote roles with good pay and good system access.

**Can deepfakes pass a video interview?**

A good one passes a basic liveness check, yes. Stopping it takes three layers together: securing the camera path, protecting the video payload, and detecting synthetic media. One layer alone gets beaten.

**Do video interview platforms prevent cheating?**

Most catch the obvious kind with browser lockdown and webcam monitoring. They differ on facial comparison, anomaly flagging, and whether a human reviews flags. Skip the human step and you get false rejections nobody hears about.

**When do you need identity verification in hiring?**

When the role carries access: engineering, finance, security, anything remote touching customer data. A first-round screen can skip it if a background check or an in-person final round catches identity later.

## Sources

1. https://www.justice.gov/opa/pr/arizona-woman-sentenced-17m-information-technology-worker-fraud-scheme-generated-revenue
2. https://hireflix.com/en/pricing
3. https://www.miteksystems.com/blog/beyond-deepfake-detection-building-resilient-identity-systems
4. https://lysinski.com/practices/ai-law/facial-recognition-law-illinois/
