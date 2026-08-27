# Video Interview Platform That Stops Deepfakes and Proxies

Deepfakes and proxy candidates are infiltrating companies at scale. Gartner projects one in four candidate profiles worldwide will be fake by 2028 [c]. In one documented case, the DOJ charged someone for placing stolen identities at 309 U.S. companies [c], [c]. The cost to victims: $5 million in fraudulent wages alone [c]. Most video interview platforms claim "identity verification" without documenting what that means. This article evaluates six platforms on their documented identity controls so you can choose based on proof.

## Quick answer

Most video interview platforms conflate AI video analysis with identity verification. True identity verification requires a complete stack: securing the camera path, protecting the payload, and detecting synthetic media [c]. Four vendor claims warrant challenge—ISO 30107-3 certification, deepfake artifact analysis, secure SDKs, and active liveness—all fail without full integration [c]; the strongest platforms combine technical detection with human review [c]. Match platform rigor to role risk: high-access roles need all three layers; first-round screening may skip identity verification if later stages cover it.

## Deepfakes and Proxy Candidates Are a Documented Hiring Threat

[Proxy candidates](https://testlify.com/proxy-interview/), people hired to interview in place of the applicant, gain access through identity misrepresentation. In one documented case, the DOJ charged someone for placing 68 stolen identities at 309 U.S. companies [c], [c], which cost $5 million in fraudulent wages and $3 million in victim remediation [c]. A fraudulent hire costs $701,500 on average [c].

Greenhouse found 31% of recruiters had observed a different person at interview than the one who applied [c]. Yet reviews of over 80 video interview platforms omitted identity verification and fraud detection from their evaluation criteria [c], [c]. When vendors claim "identity verification," they rarely document what that actually means.

## How Vendors Hide What 'Identity Verification' Actually Means

AI video analysis (transcription, competency scoring) evaluates how candidates answer, not who they are [c], [c]. A system that scores these dimensions surfaces highlights for reviewers [c]. Neither dimension is an identity control, and fraudulent submissions that score well can advance [c].

Four vendor claims warrant scrutiny:

- "ISO 30107-3 certified" tests face recognition against photographs, not injection resistance [c]
- "Our model detects deepfake artifacts" checks only the image itself, leaving virtual cameras invisible [c]
- "Our SDK is secure" assumes security attackers circumvent through SDK reversal [c]
- "We use active liveness" fails when the entire feed is injected [c]

A serious vendor documents the full defensive stack: securing the camera path, protecting the payload, and detecting synthetic media [c]. Independent lab testing (CEN/TS 18099 for virtual cameras, iBeta Level 3 for spoofing) separates documented capability from vendor prose [c], [c], [c].

## At-a-Glance Comparison Table

| Platform | Best for | Key features | Identity verification | Starting price |
|---|---|---|---|---|
| HireVue | Structured assessment | Standardized questions, AI scoring, psychometric challenges | None documented [c] | $35,000/year |
| Spark Hire | SMB first-round screening | AI transcription, behavioral scoring, 50+ languages | None [c] | $249/month |
| Willo | European high-volume | GDPR-first, 18 languages, 20,000 applicants/cycle | Optional third-party [c] | Contact vendor |
| VidCruiter | Regulated hiring | Live/async, proctoring, ID verification, browser monitoring | Yes, built-in [c] | $5,000/year + per-module |
| Hireflix | High-volume screening | One-way video, passive liveness, 95%+ completion | Passive liveness only [c] | $75 to 150/month |
| Testlify | Integrated fraud prevention | Proctoring, facial comparison, AI anomaly detection, human review | Yes, tiered [c] | Contact vendor |

## HireVue: Structured Assessment, No Identity Verification

[HireVue](https://testlify.com/alternatives/hirevue-2/) enforces consistency through standardized questions, assessment frameworks, and scoring rubrics [c]. Candidates record responses and the AI analyzes transcripts to generate scores [c]. Enterprise tier adds role-based assessments, psychometric challenges, and coding assessments [c].

The platform does not document ID verification, face matching, liveness detection, browser lockdown, or proxy detection [c]. HireVue settled a $3.75 million lawsuit over collecting facial geometry from Illinois applicants without consent [c]. The settlement signals that employers must disclose biometric data collection [c].

Essentials starts at $35,000/year for 2,500 to 7,500 person organizations [c]. Enterprise costs $50,000-$145,000/year and adds AI screening and FedRAMP certification [c]. Choose HireVue for structured hiring where you manage compliance separately.

## Spark Hire: The SMB-Friendly Async Option

Spark Hire serves 7,000+ organizations, primarily small-to-medium businesses [c], [c]. It combines async and live interviews with AI summarization, behavioral assessments, and 40+ ATS integrations [c]. Most customers go live within 30 days [c].

The system transcribes 50+ languages, generates summaries, and scores answers on competencies like Communication and Execution [c], [c]. Validated on 68,000+ submissions, it achieves 90%+ accuracy against human raters [c].

But Spark Hire documents no liveness check, face-match, or identity verification [c]. At $249/month (billed annually), it includes unlimited jobs and users [c]. Choose Spark Hire for high-volume first-round screening where identity verification happens elsewhere (background check, in-person final round, or a live interview with proctoring).

## Willo: GDPR-First Async Screening, Built for High-Volume European Hiring

Willo is built for asynchronous interviews with a Europe-hosted, GDPR-first design [c]. Personal data is encrypted at rest with AES-256 on European servers; it holds ISO 27001 and GDPR compliance [c]. The platform supports 18 languages and scales to 20,000 applicants per cycle [c].

Willo is asynchronous only, with no live interviews. It includes screen lockdown and AI cheating detection but relies on optional third-party ID verification [c]. Choose Willo when compliance and volume matter more than built-in identity controls.

## VidCruiter Leads in Configurability for Regulated Hiring

VidCruiter is the most configurable platform, used by government agencies including Elections BC and Australia's Prime Minister & Cabinet [c]. Government and K-12 districts rely on it for regulated hiring [c].

The platform runs live and pre-recorded interviews with embedded rating guides [c]. Proctoring includes ID verification, browser monitoring, copy/paste prevention, and session recording for audit [c]. Standardized questions reduce interviewer bias at scale, a requirement for auditable hiring [c].

Pricing starts at $5,000/year with usage-based, per-module billing [c]. Implementation takes 4 to 8 weeks and usually requires formal training, reflecting the depth of customization [c]. Choose VidCruiter when your hiring process is prescribed by regulation and must be documented.

## Hireflix: One-Way Video Interviews Without the Friction

Hireflix removes login and scheduling friction to maximize completion rates in first-round screening. Candidates receive a link, answer on their device at their convenience. The only identity step is passive liveness: a selfie with no prompts [c].

Passive liveness achieves completion rates above 95%, versus 60% with active prompts [c]. Screening time drops by up to 60% versus phone screens [c].

Hireflix costs $75 to 150/month with no per-response charges [c]. It does not verify that the person on screen matches identity documents or detect deepfakes and proxies [c]. Choose Hireflix when identity verification happens elsewhere: background check, in-person final round, or live interview with proctoring.

## How Testlify Integrates Proctoring and Identity Verification

Testlify combines skills assessment, conversational AI interviews, and live [proctoring](https://testlify.com/anti-cheating-and-proctoring/) with continuous identity verification into one workflow [c]. Fraud prevention is built in rather than bolted on [c].

The system verifies identity before assessment begins, monitors behavior during the test, and surfaces flagged sessions after with video evidence and activity logs [c]. Face detection, photo verification, AI-assistance detection, full-screen enforcement, tab monitoring, environment checks, and session recording are built in [c].

Testlify uses tiered controls by role risk [c]. Tier 1 runs on every assessment: browser lockdown, basic webcam capture, IP monitoring [c]. Tier 2 adds facial comparison and AI anomaly detection for critical roles [c], and Tier 3 is human review of flagged sessions [c]. Built-in proctoring means all data is single-sourced: one recording, one question log, one profile [c].

## Interview Controls by Role Risk and Cost

The defensible approach isn't a single system applied uniformly. It's a tiered framework matching verification rigor to role access level.

**Tier 1 runs on every assessment:** browser lockdown, webcam capture, IP monitoring [c]. These catch opportunistic cheating without friction for compliant candidates [c].

**Tier 2 activates for roles where assessment directly determines hiring.** Real-time facial comparison, behavioral biometrics, AI anomaly detection [c]. Pair the monitored score with interview scorecards: a candidate whose assessment diverges from interview needs closer review before offer [c].

**Tier 3 is human review of flagged sessions [c].** A reviewer examines the recording, compares the anomaly to the candidate's pattern, and decides: pass, re-test, or disqualify [c]. Internet outages causing timing anomalies should not trigger disqualification without review [c].

**What to demand from vendors:**

- Demonstrate a complete candidate session with interrupted internet, identity failure, and disputed flags [c]
- Explain how risk scores are calculated and thresholds are configurable [c]
- Show how review tools connect each flag to timestamp and evidence [c]
- Consolidate camera, audio, desktop, identity, and event logs into one record [c]
- Clarify the monitoring model: AI-led, human-led, or hybrid [c]
- List automated signals: face disappearing, extra people, identity mismatch, extra displays, virtual environments [c]
- Negotiate contract terms: bar retention for model training, require destruction on your schedule [c]

**Cost and defensibility:** Layering low-cost process improvements with selective technology for high-stakes interviews delivers the best ROI [c]. Basic prevention (camera-on policies, ID verification, training) costs virtually nothing [c]. Platform solutions charge per interview, scaling with volume [c]. Biometric fraud detection justifies higher investment for senior and high-access roles [c].

Budget $15,000 to $40,000 for implementation [c]. Set response thresholds around business impact, not vendor confidence scores [c]. One strange answer prompts a follow-up, not immediate conclusion [c].

For implementation guidance and specific detection tactics, see our guide on [preventing impostors in video interviews](https://testlify.com/prevent-impostors-in-video-interviews/).

## Scale your controls to role risk

The safest hiring processes layer technical detection with human review, matched to role risk in tiers. Testlify integrates proctoring and identity verification into the assessment itself, so no data gets siloed and every flag connects to evidence. We surface suspicious activity during the test and place the final judgment in your hands, preventing false positives from disqualifying honest candidates. Start with our [assessment platform](https://testlify.com/) to combine skills testing with integrated proctoring.

## Frequently asked questions

**What is the best video interviewing platform?**

The best platform depends on role risk and compliance needs. HireVue excels at structured assessment; VidCruiter at regulated hiring; Testlify at integrated fraud prevention. Match rigor to role access level.

**What is a proxy candidate?**

A proxy candidate is a person hired to interview or test in place of the applicant. It's a fraud tactic where someone misrepresents identity to land a job with access or high salary.

**Can deepfakes pass a video interview?**

Professional deepfakes can deceive basic liveness checks. To stop them, platforms need a complete defensive stack: camera-path security, payload protection, and synthetic-media detection. Single-layer checks fail.

**Do video interview platforms prevent cheating?**

Most platforms offer browser lockdown and webcam monitoring. But they differ widely on active detection (facial comparison, anomaly flagging) and human review. Mid-tier detection is better than none; full prevention requires human verification.

**When do you need identity verification in hiring?**

High-access roles (engineering, finance, security) warrant identity verification and continuous monitoring. First-round screening may skip identity checks if later stages (background checks, in-person finals) cover it.

## Sources

