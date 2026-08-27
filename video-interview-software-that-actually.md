# Video Interview Platform That Stops Deepfakes and Proxies

Gartner projects one in four candidate profiles worldwide will be fake by 2028. Deepfakes and proxy candidates are already infiltrating hiring at scale, and most video interview platforms claim "identity verification" without saying what that means. This article checks six platforms against their documented identity controls, so you can choose based on proof, not marketing.

## Quick answer

Most video interview platforms conflate AI video analysis, which scores answers, with identity verification, which proves identity, and real verification needs three things together: a secured camera path, a protected payload, and synthetic-media detection. Four common vendor claims fall apart against a professional attacker without all three. The strongest platforms pair technical detection with human review of flagged sessions. Match the rigor to the role: high-access roles need full identity verification; first-round screening can skip it if a later stage covers it.

## Deepfakes and Proxy Candidates Are a Documented Hiring Threat

[Proxy candidates](https://testlify.com/proxy-interview/) are people hired to interview or test in place of the real applicant. It's hiring fraud, and it's now documented at state level.

The Department of Justice charged [Christina Chapman](https://www.justice.gov/opa/pr/arizona-woman-sentenced-17m-information-technology-worker-fraud-scheme-generated-revenue) for helping North Korean operatives use 68 stolen U.S. identities to get hired at 309 American companies [1], [1], including Fortune 500 firms and aerospace manufacturers. One scheme alone generated $5 million in fraudulent salaries and cost victim companies $3 million more in remediation and legal fees. A single fraudulent hire costs $701,500 on average, and OFAC sanctions start at $50,000 per violation.

Greenhouse's 2026 research found 31% of recruiters had watched a different person interview than the one who applied. Yet an industry evaluation of over 80 video interview platforms scored them on ease of use and integration. Interview integrity and fraud detection never made the rubric,.

For the specific tactics that catch a deepfake or proxy candidate during a live interview, see our guide on [preventing impostors in video interviews](https://testlify.com/prevent-impostors-in-video-interviews/).

## How Vendors Hide What 'Identity Verification' Actually Means

Vendors attach "identity verification" to anything from a webcam snapshot to real document checks with face matching [2]. Start by separating two things they conflate: AI video analysis scores how a candidate answers; only identity verification proves who they are. That AI can surface highlights for a reviewer to triage, but a fraudulent submission that answers well can still advance without a human ever checking it.

Four vendor claims deserve a direct challenge [3]:

| Vendor claim | Why it isn't enough |
|---|---|
| "ISO 30107-3 certified" | Tests against photos and masks, not injection attacks [3] |
| "We detect deepfake artifacts" | Checks the image only; misses virtual cameras and hooked SDKs  |
| "Our SDK is a secure boundary" | Attackers reverse the SDK itself  |
| "We use active liveness" (blink, turn) | Fails when the whole feed is injected  |

A serious vendor documents all three defenses together: a secured camera path, a protected payload, and synthetic-media detection [3]. Ask for independent lab results: CEN/TS 18099 for virtual-camera detection, iBeta Level 3 for spoofing resistance. That's what separates real capability from prose.

## Video Interview Software Compared at a Glance

Here's how the six platforms in this guide stack up before you read the full write-ups.

| Platform | Starting price | Identity verification | Best for |
|---|---|---|---|
| HireVue | $35,000/yr  | None documented  | Structured, scored assessment |
| Spark Hire | $249/mo  | None documented  | High-volume SMB screening |
| Willo | Custom, EU-hosted  | Optional third-party  | GDPR-first, high-volume screening |
| VidCruiter | $5,000/yr  | ID check in proctoring module  | Regulated, audited hiring |
| Hireflix | $75-$150/mo  | Passive liveness only | One-way video interview screening |
| Testlify | Tiered by role risk  | Built in: face match + AI + human review  | Integrated fraud prevention |

## HireVue: Structured Assessment, No Identity Verification

HireVue is an enterprise-standard platform that scores candidates on what they say and how they say it, through standardized questions and rubrics,. It carries no documented identity verification: no ID check, no live face match, no liveness detection, no deepfake or proxy detection.

That gap has already cost it. HireVue settled a class lawsuit for $3.75 million over extracting facial geometry and voiceprints from Illinois applicants without consent [2]. Scored video assessment is exactly what state AI hiring laws target, which makes this the heaviest compliance load in this guide.

Essentials starts at $35,000 a year and covers live and async interviews, but not AI screening,. Enterprise adds AI screening and FedRAMP certification for $50,000-$145,000 a year. Choose it for structured hiring, not fraud defense.

## Spark Hire: The SMB-Friendly Async Option

Spark Hire serves over 7,000 organizations, mostly small and mid-size businesses with lean hiring teams,. It mixes async and live interviews with AI summarization, scoring, and 40+ ATS integrations,, at a flat $249 a month, unlimited jobs and users.

Its AI transcribes and scores answers across 50+ languages, validated on over 68,000 submissions at above 90% accuracy against human raters,,. But that AI judges answers, not identity. Spark Hire documents no liveness check and no ID match.

That gap is fine for high-volume first-round screening where a background check or in-person final round handles identity. For regulated or fraud-risk roles, verify identity elsewhere.

## Willo: GDPR-First Async Screening, Built for High-Volume European Hiring

Willo runs asynchronous interviews only, hosted primarily on European servers with AES-256 encryption at rest and transfers governed by the EU-U.S. Data Privacy Framework,. It holds ISO 27001 certification and is [GDPR compliant](https://testlify.com/how-do-recruitment-platforms-handle-gdpr-compliance/), and it supports 18 languages across a cycle of up to 20,000 applicants,.

It includes screen lockdown and AI flagging of cheating attempts, but leans on optional third-party ID verification rather than a built-in identity check. That fits teams who verify identity through a background check or an in-person final round, and who want compliance and volume more than integrated identity controls.

## VidCruiter Leads in Configurability for Regulated Hiring

VidCruiter is the most configurable platform here, which is why government agencies, K-12 districts, and other regulated employers use it,. It runs live and pre-recorded interviews with rating guides built into the interface, plus optional modules for skills testing, reference checks, and proctoring.

The proctoring module verifies ID before testing, monitors the browser for tab switching, blocks copy-paste, and records the session for audit. Standardized questions and scoring reduce interviewer bias at the scale regulated hiring demands.

Pricing starts at $5,000 a year, billed per module and usage, and implementation runs 4 to 8 weeks with formal training,. Pick it when your process must be documented for audit, not when speed matters most.

## Hireflix: One-Way Video Interviews Without the Friction

Hireflix strips out login and scheduling friction to maximize completions in [one-way video interview screening](https://testlify.com/hr-glossary/one-way-interviews/). Candidates get a link and answer on their own device. The only identity step is a passive selfie, with no prompts or gestures.

That trade-off pays off in volume: passive liveness completes above 95% of the time [4], against 60% for active-prompt verification [4], and cuts screening time by up to 60% versus phone screens. It costs $75 to $150 a month by company size, with no per-response fees.

What it doesn't do: match the person on screen to an ID, or detect deepfakes and proxies. Use it when identity is verified elsewhere: a background check, an in-person final round, or a proctored live interview.

## How Testlify Integrates Proctoring and Identity Verification

Testlify combines skills assessment, AI interviews, and live proctoring with continuous identity verification in one workflow, instead of bolting fraud checks on afterward. Face detection, photo verification, AI-assistance detection, full-screen enforcement, and session recording all run inside the assessment, so a flag stays attached to its evidence.

It verifies identity before the test, monitors behavior during it, and surfaces flagged sessions with video evidence afterward. Your team makes the final call, so a timing glitch never auto-disqualifies someone.

Controls scale in three tiers by role risk. Tier 1 runs on every assessment: browser lockdown, webcam capture, IP monitoring. Tier 2 adds real-time facial comparison and AI anomaly detection for roles where the score decides the hire. Tier 3 is human review of anything flagged.

## Match Video Interviewing Software Controls to Role Risk

The defensible approach isn't one system applied everywhere. A call-center screener and an engineer with production access need different checks. One flag should escalate a case, not end it; several flags together should trigger verification; a confidence score is a triage signal, not a verdict,,.

Before you sign, get written answers to these:

- Walk through a full session: different devices, dropped internet, a disputed flag, peak volume.
- How is the risk score calculated, and are thresholds configurable, ?
- Does every flag link to a timestamp and its evidence ?
- Is all session data (camera, audio, desktop, identity, logs) in one record ?
- Is review AI-led, human-led, or hybrid, and what happens after a flag, ?
- What validation evidence exists for roles like yours, not generic accuracy claims ?
- Will the contract bar retention for model training and require data destruction on your schedule ?

Your BIPA duties aren't delegable, so that last answer determines your exposure.

## What Fraud Prevention Actually Costs

Fraud prevention has three cost tiers. Basic controls (camera-on policies, ID checks, training) cost almost nothing. Platform features charge per interview and scale with volume. Enterprise-grade biometric and AI detection earns its keep on senior or high-access roles, where a bad hire also costs lost productivity and rehiring,.

Budget $15,000 to $40,000 for implementation, and factor in a full-time IT role if you're handling biometric data,. Fraud in a call-center role wastes hiring spend; fraud in an engineering role hands a stranger real system access. Set your response thresholds around that business impact, not a vendor's confidence score.

## Scale your controls to role risk

The safest hiring processes layer technical detection with human review, matched to role risk in tiers. Testlify builds proctoring and identity verification into the assessment itself, so no data sits siloed and every flag carries its evidence. We surface suspicious activity during the test and leave the final call to you, so a false positive never disqualifies an honest candidate. Start with our [assessment platform](https://testlify.com/) to combine skills testing with integrated proctoring.

## Frequently asked questions

**What is the best video interviewing platform?**

It depends on role risk and compliance needs. HireVue suits structured assessment, VidCruiter suits regulated hiring, and Testlify suits integrated fraud prevention.

**What is a proxy candidate?**

Someone hired to interview or test in place of the real applicant: a fraud tactic used to land jobs with high access or salary.

**Can deepfakes pass a video interview?**

Professional deepfakes beat basic liveness checks. Stopping them needs camera-path security, payload protection, and synthetic-media detection together, not any single check.

**Do video interview platforms prevent cheating?**

Most catch obvious cheating with browser lockdown and webcam monitoring. They differ widely on active detection and human review, which is where prevention lives.

**When do you need identity verification in hiring?**

For high-access roles: engineering, finance, security. First-round screening can skip it if a background check or in-person final round covers it later.

## Sources

1. https://www.justice.gov/opa/pr/arizona-woman-sentenced-17m-information-technology-worker-fraud-scheme-generated-revenue
2. https://trycontrol.app/blog/interview-identity-verification-candidate-guide
3. https://www.duckduckgoose.ai/blog/how-injection-attacks-feed-deepfakes-into-verification
4. https://www.miteksystems.com/blog/beyond-deepfake-detection-building-resilient-identity-systems
