---
title: "Age Verification Architecture"
abbrev: "age-arch"
category: info

docname: draft-knodel-age-arch-latest
submissiontype: IETF
number:
date:
consensus: true
v: 3
# area: IAB
# workgroup:
keyword:
 - age verification
venue:
#  group:
#  type:
#  mail:
#  arch:
  github: "mallory/draft-knodel-age-arch"
  latest:

author:
 -
    fullname: Mallory Knodel
    organization: Social Web Foundation
    email: mallory.knodel@nyu.edu
 -
    fullname: Gianpaolo Angelo Scalone
    organization: Vodafone Group
    email: gianpaolo-angelo.scalone@vodafone.com
 -
    fullname: Tom Newton
    organization: Qoria
    email: tom.newton@qoria.com
 -
    fullname: Audrey Hingle
    organization: Exchange Point
    email: audrey.hingle@gmail.com

normative:

informative:
  RFC9505:
  RFC8280:
  DTSP:
    title: "Age Assurance: Guiding Principles and Best Practices"
    author:
      - org: Digital Trust & Safety Partnership
    date: 2023
    target: https://dtspartnership.org/age-assurance-guiding-principles-best-practices/

  FPF-Infographic:
    title: "Unpacking Age Assurance: Technologies and Tradeoffs"
    author:
      - org: Future of Privacy Forum
    date: 2026-02
    target: https://fpf.org/wp-content/uploads/2026/02/FPF-Age-Assurance-v2.0.pdf

  Google-Blog:
    title: "Ensuring a safer online experience for U.S. kids and teens"
    author:
      - org: Google
    date: 2025-07-30
    target: https://blog.google/innovation-and-ai/technology/safety-security/age-assurance-measures-safer-online-kids-teens-us/

  TechLegality:
    title: "Online Platform Regulation and Children's Rights and Safety in a Digital World: A Global Comparative Analysis"
    author:
      - ins: S. Witting
      - ins: L. Berton
      - ins: E. Day
      - org: Tech Legality (commissioned by UNICEF)
    date: 2025-12
    target: https://ee4cc382-be9b-4f25-8d92-aa92d93128f5.filesusr.com/ugd/94468e_1921d31ba90741b3b4a39fc3f710b015.pdf

  UNICEF-Line:
    title: "Drawing a Line in Digital Spaces"
    author:
      - org: UNICEF
    date: 2026
    target: https://www.unicef.org/documents/drawing-line-digital-spaces

  ISO-27566-1:
    title: "Information security, cybersecurity and privacy protection — Age assurance systems — Part 1: Framework"
    author:
      - org: ISO/IEC JTC 1/SC 27
    date: 2025
    target: https://www.iso.org/standard/88143.html

  PublicKnowledge-2026:
    title: "Getting Age Assurance Right: A Risk Based Framework for High-Risk Online Features"
    author:
      - ins: S. Collins
      - org: Public Knowledge
    date: 2026
    target: https://publicknowledge.org/policy/getting-age-assurance-right-a-risk-based-framework-for-high-risk-online-features/

  CDT-Guardian-2026:
    title: "Upload government papers to go online? That may be our new terrifying future"
    author:
      - ins: A. Bhatia
      - org: Center for Democracy & Technology (CDT), in The Guardian
    date: 2026-05-12
    target: https://www.theguardian.com/commentisfree/2026/may/12/website-age-verification-government-identification

  CDT-Guardrails-2025:
    title: "Mitigating Risk to Rights with Age Verification: Privacy-Preserving Guardrails That Should Accompany Deployments of Age Verification Approaches"
    author:
      - ins: A. Bhatia
      - ins: N. Doty
      - org: Center for Democracy & Technology (CDT)
    date: 2025-10-10
    target: https://cdt.org/insights/mitigating-risk-to-rights-with-age-verification-privacy-preserving-guardrails-that-should-accompany-deployments-of-age-verification-approaches/

  PapersPlease-2026:
    title: "Papers, Please: A First Look at Age Verification on the Web"
    author:
      - ins: S. Minocha
      - ins: I. Sheridan
      - ins: H. Oppenheimer
      - ins: P. Pearce
      - ins: M. A. Specter
    date: 2026
    target: https://pearce.prof/papers/age_verification_sp_2026.pdf

  UNICEF-Cert-2025:
    title: "Certification Schemes"
    author:
      - ins: E. Day
      - ins: V. Lerch
      - org: UNICEF Innocenti
    date: 2025
    target: https://www.unicef.org/innocenti/media/11101/file/UNICEF-Innocenti-Certification-Schemes-Case-Study-2025.pdf

  UNICEF-Standards-2025:
    title: "Industry Standards"
    author:
      - ins: E. Day
      - ins: L. Berton
      - org: UNICEF Innocenti
    date: 2025
    target: https://www.unicef.org/innocenti/media/11541/file/UNICEF-Innocenti-Data-Governance-Industry-Standards-2025.pdf

  OHCHR-UN-2026:
    title: "Banning children from social media is not the answer, UN warns – platforms must be made safe by design"
    author:
      - org: UN News / Office of the High Commissioner for Human Rights (OHCHR)
    date: 2026-05-29
    target: https://news.un.org/en/story/2026/05/1167608

  eSafety-AU-2026:
    title: "Social Media Minimum Age: March 2026 Compliance Update"
    author:
      - org: Australian eSafety Commissioner
    date: 2026-03
    target: https://www.esafety.gov.au/about-us/industry-regulation/social-media-age-restrictions#compliance-update-march-2026

  TechPolicyPress-2026:
    title: "Tracking Efforts To Restrict Or Ban Teens from Social Media Across the Globe"
    author:
      - org: Tech Policy Press
    date: 2026-02
    target: https://www.techpolicy.press/tracking-efforts-to-restrict-or-ban-teens-from-social-media-across-the-globe/

  Interface-EU-2026:
    title: "Social Media Age Gating in the EU"
    author:
      - ins: J. Galissaire
      - ins: S. Gomez
      - ins: L-M. Böswald
      - org: Interface
    date: 2026-05
    target: https://www.interface-eu.org/publications/social-media-age-gating-eu

  KGI-AgeAssurance-2026:
    title: "Age Assurance Online: A Technical Assessment of Current Systems and their Limitations"
    author:
      - ins: E. Rescorla
      - ins: Z. Arnao
      - ins: A. Cooper
      - org: Knight-Georgetown Institute (KGI)
    date: 2026-01
    target: https://kgi.georgetown.edu/research-and-commentary/age-assurance-online/
  EFF-Age-Terminology:
    title: "Age Assurance, Estimation, Verification—Oh My! A Guide to the Terminology"
    author:
      - ins: R. Alajaji
      - org: Electronic Frontier Foundation (EFF)
    date: 2025-10
    target: https://www.eff.org/deeplinks/2025/10/age-verification-estimation-assurance-oh-my-guide-terminology

  EFF-FinkeControl-2026:
    title: "Rep. Finke Was Right: Age-Gating Isn’t About Kids, It’s About Control"
    author:
      - ins: R. Alajaji
      - ins: M. Buckley
      - org: Electronic Frontier Foundation (EFF)
    date: 2026-03
    target: https://www.eff.org/deeplinks/2026/03/rep-finke-was-right-age-gating-isnt-about-kids-its-about-control

  EFF-ScienceNotSettled-2026:
    title: "The Science is Not Settled: How Weak Evidence is Fueling a National Push to Ban Social Media for Youth"
    author:
      - ins: R. Alajaji
      - org: Electronic Frontier Foundation (EFF)
    date: 2026-05
    target: https://www.eff.org/deeplinks/2026/05/science-not-settled-how-weak-evidence-fueling-national-push-ban-social-media-youth

  Cloudflare-Families:
    title: "Introducing 1.1.1.1 for Families"
    author:
      - ins: M. Prince
      - org: Cloudflare
    date: 2020-04
    target: https://blog.cloudflare.com/introducing-1-1-1-1-for-families/

  Epic-KWS:
    title: "Welcome to Kids Web Services (KWS)"
    author:
      - org: Epic Games
    date: 2024
    target: https://dev.epicgames.com/docs/kids-web-services/welcome-to-kws

  NIST-IR-7995:
    title: "Face Recognition Vendor Test (FRVT) Performance of Automated Age Estimation Algorithms"
    author:
      - ins: M. Ngan
      - ins: P. Grother
      - org: National Institute of Standards and Technology (NIST)
    date: 2014-03-20
    target: https://nvlpubs.nist.gov/nistpubs/ir/2014/NIST.IR.7995.pdf

  Ganel-2022:
    title: "Biases in human perception of facial age are present and more exaggerated in current AI technology"
    author:
      - ins: T. Ganel
      - ins: C. Sofer
      - ins: M. A. Goodale
    date: 2022
    target: https://doi.org/10.1038/s41598-022-27009-w

  Newman-2022:
    title: "Apple Kills Its Plan to Scan Your Photos for CSAM. Here’s What’s Next"
    author:
      - ins: L. H. Newman
      - org: WIRED
    date: 2022-12-07
    target: https://www.wired.com/story/apple-photo-scanning-csam-communication-safety-messages/

  PrivacyIntl-2018:
    title: "The Sustainable Development Goals, Identity, and Privacy: Does their implementation risk human rights?"
    author:
      - org: Privacy International
    date: 2018-08-29
    target: https://privacyinternational.org/long-read/2237/sustainable-development-goals-identity-and-privacy-does-their-implementation-risk

  UN-HRC-29-32:
    title: "Report of the Office of the United Nations High Commissioner for Human Rights: The Right to Privacy in the Digital Age"
    author:
      - org: United Nations Human Rights Council
    date: 2015
    target: https://undocs.org/A/HRC/29/32

  CDT-2021:
    title: "Apple’s Changes to Messaging and Photo Services Threaten Users’ Security and Privacy"
    author:
      - org: Center for Democracy & Technology (CDT)
    date: 2021-08-05
    target: https://cdt.org/press/cdt-apples-changes-to-messaging-and-photo-services-threaten-users-security-and-privacy

  CDT-2024:
    title: "CDT Files Amicus Brief in Free Speech Coalition v. Paxton, Challenging TX Age Verification Law"
    author:
      - ins: K. Ruane
      - ins: M. Branum
      - ins: N. Doty
      - ins: D. Jain
      - org: Center for Democracy & Technology (CDT)
    date: 2024-09-23
    target: https://cdt.org/insights/cdt-files-amicus-brief-in-free-speech-coalition-v-paxton-challenging-tx-age-verification-law

  RTA:
    title: "RTA Label"
    target: https://www.rtalabel.org

--- abstract

This document describes solution-agnostic and technology-neutral schema for how various intermediaries can gate content and services based on age. The analysis of the architecture is done along two dimensions: the efficacy of permitting or restricting access based on age, and the privacy cost of doing so. The document concludes with recommendations as well as critical privacy, security and human rights considerations.

--- middle

# Background

Our goal is to describe the technical difficulties in any age-gating mechanism such that it is effective and does not introduce security and privacy risks as well as contravene human rights. We also hope to show that age verification mechanisms are wholly technical solutions that are separate from, albeit often motivated by, the means of protecting young people online.

Prior focus on child safety has led to robust trust and safety measures taken by large user platforms whereby content and behaviour moderation became industry standard. Its phases: Define, detect, evaluate, enforce, appeal, educate. This cycle ensures that criminal and unlawful content is taken down. Platforms and services with user generated content can also use this cycle to ensure content or behavior that violates platform terms of service.

In parallel, network operators have for many years implemented forms of age-based access control that rely on content categorization or DNS-level filtering rather than on the collection of personal data. In several jurisdictions, ISPs are required to offer or enforce filtering systems that restrict access to adult or otherwise unsuitable content for minors. These systems typically work by classifying destination domains or content types into broad categories—such as adult, gambling, or violence—and allowing or blocking them according to the subscriber’s or guardian’s chosen policy. Because they do not require identity documents or individual profiling, such network-assisted methods can provide a baseline of child protection with substantially lower privacy risk. These approaches cannot replace service-level moderation or legal accountability, nor should they be standalone solutions outside of parental controls or family management settings.

Relatively new are proposals to protect children via age gate. Age gating in the analog world is typically enforced at the point of action, sale or entry through hard document checks at liquor stores, as one example. Replicating age gating in the online world has encountered consistent tensions between accuracy and privacy, often reducing the problem to one of feasibility. Often, online age verification has taken the form of requiring websites to show a prompt to the user to self-declare their age or birthdate before they can gain access to content or services. Similar to the aims of this document, advocacy groups have since evaluated deployed age-assurance systems against accuracy, availability, and circumvention. [KGI-AgeAssurance-2026] Other existing frameworks cut this differently—for example, by categorizing methods as declaration, inference, estimation, or verification [FPF-Infographic], or as identity-document verification, age estimation, and self-declaration [DTSP]—and arrive at a similar conclusion that no single method or category fits every context. Standards bodies and civil-society organizations have likewise proposed frameworks for reasoning about these systems, including a formal ISO framework for age assurance systems [ISO-27566-1] and a risk-tiered approach to when high-assurance methods are warranted at all [PublicKnowledge-2026].

Some services, websites, or apps require uploading hard documents to verify identity, just as some services, websites or apps require payment with a credit card. These often create an illusion for policy makers that users could be required by any service to require sharing of the same hard documents or credit card details in order to verify age at scale, both for all users and for a wide variety of platforms and services. However any such system is expensive, difficult to scale, and introduces data protection liability and privacy risks to users— including potential data breaches or the exclusion of users who do not possess traditional identity documents but who would otherwise be lawful users. Hard document identity review in the context of general-use platforms like social media unnecessarily scales the risk of privacy, access, and equity harms from requisite age gating for all users on all apps all the time. These are not hypothetical harms: journalists, LGBTQIA+ people, and others relying on anonymity have already had identifying documents linked back to their online activity through breaches of age-verification providers. [CDT-Guardian-2026]

Many age verification methods conflict with data-protection frameworks and data minimization principles and pose serious safety, data security, and privacy risks. As such risks will be present in nearly all alternative methods of age verification, an overview of this category of risk will be of some benefit, while we leave method-specific commentary to the security, privacy and human rights considerations sections. Requiring all users on all platforms to submit verifiable credentials can create large, sensitive data troves in centralized intermediaries that are vulnerable to breaches, fraud, or misuse. Once compromised, this information is difficult—if not impossible—to secure again. Compounding these concerns, precise location—required to determine compliance with jurisdiction-specific laws—is implicitly inferred in all methods, adding another layer of sensitive data to the name and age information being collected, processed, and stored.

From an operational and architectural perspective, centralizing or repeatedly exchanging such verification data may also create systemic risks to resilience, security, and interoperability. Large-scale credential exchanges or cross-border look-ups introduce new attack surfaces and potential points of failure within authentication or content-delivery paths.

## Terminology

Language matters because it shapes how we think about these systems. "Assurance" is less official than "verification" and "estimation" admits inherent imprecision. [EFF-Age-Terminology]

**Age Verification** – Process of confirming a user’s age using an authoritative or verifiable source (e.g., government ID, credential, or trusted record).

**Age Assurance** – Broader set of methods providing confidence about a user’s age or age range without requiring formal identity verification.

**Age-gating** \- refers to age-based restrictions on access to online services. Age gating can be required by law or voluntarily imposed as a corporate decision.

**Age Estimation** \- Instead of asking you directly, the system *guesses* your age based on data it collects about you.

**Self-Attestation** – User-declared statement of age or date of birth without third-party validation.

**Guardian Attestation** – Verification performed or consent provided by a parent or legal guardian on behalf of a minor.

**Intermediary** – Any actor between the user and a service, including device OS, application platform, content-delivery system, resolver, or network operator.

**Service-Level Age Control** – Mechanisms enforced by online platforms or applications (e.g., login requirements, content gating, or age tokens).

**Network-Assisted Age Control** – Privacy-preserving measures implemented at or near the connectivity layer, such as DNS or policy-based content filtering, typically based on user or guardian preference and without identity collection.

**On-Device Assurance** – Local verification or estimation methods executed on the user’s device (e.g., age-range inference, parental settings) where data does not leave the device.

**Credential Provider** – Entity that issues, stores, or validates user credentials used for age verification or assurance.

**Data Minimization** – Principle that personal data should be limited to what is necessary for a specific, explicit purpose (per frameworks such as GDPR).

**Privacy-Preserving Signaling** – Exchange of metadata or tokens between system components to enforce policy without exposing personal identifiers.

**Shared-Responsibility Model** – Architectural approach in which service, device, and network layers each contribute to age-appropriate access control within their scope, reducing centralization and single points of failure.

**Circumvention** – Any attempt by users or systems to bypass or falsify age-related controls or policies.

**Jurisdictional Compliance** – Ability of a system to align with local or national laws defining age-related content or access restrictions.

# Analysis of age gating methods

In this section, we analyse methods along two dimensions: efficacy and privacy. Efficacy asks whether a mechanism works: is it feasible to operate at the scale required, is it durable against circumvention, and is it accurate. Privacy asks what a mechanism costs even when it works as intended: what it discloses beyond age, to whom, and for how long. We make each explicit here before describing individual methods below.

Efficacy should also reflect cooperation across layers—service, device, and network—so that no single actor bears full responsibility or control of user data. Feasibility has two components: operational feasibility, whether the system can run at the latency and scale required without forcing harmful centralization; and population feasibility, or availability—what fraction of the people a method is meant to serve can actually produce what it demands. A method with excellent operational feasibility can still fail on availability, as when a government-ID check works flawlessly for ID-holders but simply cannot assess the substantial number of people who lack one; we treat that as a feasibility failure rather than an accuracy one, since it is a question of coverage rather than measurement error. Circumvention may occur not only by users but also through weak or misaligned intermediaries; distributing enforcement across independent layers limits large-scale bypass. Accuracy, for those a method can assess at all, is not a single number: methods trade off a false-accept rate against a false-reject rate, and are usually tunable along that curve—for example, a facial age-estimation system can lower its false-accept rate by requiring an estimate well clear of the threshold age, at the cost of a higher false-reject rate for people who are in fact old enough. Differential accuracy—whether that trade-off lands worse for some populations than others—is part of this same accuracy question. Recourse and remedy—who is responsible and what happens when a determination is wrong, a method proves infeasible, unavailable, or unadopted, a control is circumvented, or data is breached—is not a category of its own, but a question of accountability applied wherever the above fail.

Privacy asks what a method costs beyond whether it works. Two questions recur across the methods below: what does the method disclose to a verifying party beyond age itself, and how long is that information—or the infrastructure built to hold it—retained; and, given that people and code are imperfect, how severe is the exposure if that data is breached. The latter is a function of both privacy exposure and the feasibility choices above—a method that centralizes look-ups compounds the severity of any breach.

The subsections below are organized by trust anchor—the entity or artifact that stands behind an age claim—rather than by concrete technical method. A government-issued credential, a party with direct verified knowledge, an assurance intermediary of varying confidence, and an inference from behavioural or biometric signals each root the claim differently, even when the same underlying method (a document scan, a facial estimate, a linked account) is put to use in more than one of them. This means the categories below overlap: a given method can recur across sections depending on who invokes it and what they are vouching for. We use this framing because it surfaces where a technical solution can or cannot actually reinforce the trust anchor it is meant to serve, and where the anchor itself is doing less work than assumed.

## Age credentials

The State issues the credentials that are “ground truth,” however none provide age as the singular datum, thereby disclosing more data about the user than is specific to the mandate to verify age. Examples of the provisioning of credentials include: Issuance of a birth certificate; Issuance of a passport; Teens: Issuance of a driver’s licence (though only in the US would this be for a u18); Issuance of a social insurance number / SSN / generic international name (no birthdate).

A significant fraction of people do not hold any of these documents at all—undocumented immigrants, unbanked individuals, and people without a fixed address chief among them. For them a credential-based check does not produce a wrong answer so much as no answer: it cannot assess them, which we treat as a feasibility (availability) limitation rather than an accuracy one. [KGI-AgeAssurance-2026]

Other hard documents that risk being less accurate include credit card (no birthdate but demonstrates banked eligibility) or student ID (not standardized, often no birthdate but gives approximation through education level).

Even in digital form, such as national eID or mobile driving-licence systems, these credentials typically replicate the underlying physical document and so expose more information than necessary—though, as discussed below, selective-disclosure and zero-knowledge-proof (ZKP) variants of digital credentials are a meaningful exception, capable of disclosing only a minimal attribute such as "over 18" rather than the full record.

On the privacy dimension, most of these documents were designed for other purposes, and their disclosure copies far more than an age datum into whatever system receives it. Unlike the issuing state's own systems, a receiving service or third party rarely publishes a retention policy for that copy, and the more centralized that intake becomes, the more severe a breach of it would be.

## Age verification

Age verification is performed when a guardian, the service or third party has direct, verified knowledge of the credential and assures a service of age. Hard document review would require the disclosure of documents containing a wide variety of sensitive information. This information would not be limited to a users’ age and would include data not necessary to determine whether or not a user should be permitted to use a social media platform (e.g., address, credit card number, etc.). Requiring such disclosures of all users would create substantial security and privacy concerns (e.g., risk of data breaches, exposure of additional personal information to platforms themselves).

For credentials both physical and digital, unless they are coupled with selective-disclosure or verifiable zero-knowledge proof (ZKP) techniques. Using intermediaries at the device, service, or network layer to handle only minimal attributes (“over 16,” “over 18”) can preserve regulatory trust while limiting personal-data exposure. Verification frameworks could also rely on distributed attestations or policy-based tokens issued by trusted intermediaries, enabling services to confirm age eligibility without persistent identifiers or central repositories.

Moreover, determined users may still falsify credentials or exploit systemic workarounds, undermining the effectiveness of these measures. Minors and adults alike may migrate to other extra jurisdictional platforms for comparable features rather than share the credentials required to clear a higher bar for age verification.

Even where ZKP or minimal-attribute techniques limit what is disclosed, retention remains a live question: a verifier that logs a token exchange, or a jurisdiction that requires an audit trail, may keep records well past the moment of verification, and the severity of any resulting breach scales with how centralized that record-keeping becomes.

Considerations for various intermediaries of age include the following.

A guardian who is accountable for the child assures the child’s age. This can be limiting for those with nontraditional family structures, wards of the state, and also assumes guardianship duties are always performed in the best interest of the child.

A jurisdiction or a governmental agency to be the arbiter of whether a citizen or resident would be allowed to have access to the internet or access specific websites and services. This would have both process and political consequences.

KYC (know-your-customer laws in countries that define certain industries as sensitive, such as banks, telecoms, etc) could theoretically be extended to any industry including social media, education platforms or blogging websites. However, doing so would blur the line between financial compliance and social regulation, embedding surveillance logics into general internet use. It could also make access to general-use and basic communication services contingent on a financial transaction framework, which not all internet-accessible platforms and services provide.

Operating system–level verification shifts responsibility to device vendors and app ecosystems. While this potentially removes redundancy for users who already have a trust relationship with these intermediaries, this approach would concentrate power in a few private actors. The few OS or app ecosystems could incentivize and or be required to facilitate wider-spread age data requests from apps. They could also be in a position to determine or enforce access across wider categories of apps or content beyond characteristics such as age. Such centralization would raise competition, transparency, and accountability concerns, particularly where OS providers operate globally but respond to local regulatory pressures.

Other third-party intermediaries or age verification services could offer modular, privacy-preserving verification as a service layer. Yet without strong oversight and interoperability standards, these actors could create new forms of data brokerage, fragmentation, or lock-in. Their economic incentives—to monetize verification or analytics—may conflict with users’ social and cultural rights, especially if pricing or access varies across regions. Measurement of deployed age verification on the web bears this out: a small number of third-party providers account for the large majority of observed deployments, and at least one leading provider has been found to collect government-ID scans, selfies, and payment data while sharing information with additional, less-visible parties beyond the contracted provider. [PapersPlease-2026]

In many jurisdictions, regulated entities such as banks or telecommunications operators already perform age or identity checks under audited privacy frameworks. Extending such existing infrastructures with additional privacy-preserving layers could bridge regulatory and technical feasibility.

Verifiers should be held accountable in systems where they are disclosed information (no matter how privacy preserving). Those presenting proofs should have a way to report or contest a request or determination made within these systems. Especially in the case of denial of access. Treating the user as the only potentially hostile party would ignore the power dynamics in jurisdictions where age verification is mandatory. Also, verifiers should be held to a standard of reporting and registration of their scope of collection. Especially in countries where age verification systems are being developed in tandem with digital ID systems. Existing certification and industry-standards efforts—such as the US COPPA Safe Harbor program, EU-aligned Europrivacy certification, and the UK's Age-Appropriate Design Certification Scheme [UNICEF-Cert-2025]—illustrate what such accountability structures can look like in practice, though they also show the risk of regulatory capture and uneven adoption when standards bodies are dominated by industry participants [UNICEF-Standards-2025].

## Age assurance

Age assurance is an umbrella term often used to describe the various methods whereby the user, a guardian, the service, third party, or age verification service assures the service of age to the direct, or verified knowledge of the credential to various degrees of confidence.

Age assurance can be performed by any of the age verification intermediaries listed in the previous section.

The user can self-attest, which is status quo for almost every service at this time. Self-attestation sits at the low end of both dimensions: it costs almost nothing in exposure or retention, since no verifying party receives more than a claimed birthdate, but it is correspondingly weak on accuracy. Every other intermediary described in this section improves on that accuracy only by taking on some combination of exposure, retention, or a parent-child relationship to verify—and, as the COPPA/GDPR consent chain below shows, that combination compounds rather than substitutes for the underlying data collection.

A guardian can attest and be a legal guarantor to their children like Facebook Messenger Kids. This mechanism also serves to ensure a user is in fact a child, and not an adult impersonating a child.

Connecting new users to parents’ accounts, COPPA “requires those operators to obtain verifiable consent from the children's parents before collecting, using, or disclosing children's personal information” and under GDPR they must “obtain this consent from a parent and make reasonable efforts to verify the identity of that parent.” [Epic-KWS]

An additional concern is that this measure proliferates rather severely user data, risking feasibility. Rather than minimizing data not just about the child but for the parent, this requires all parents to first verify their age (invoke recursion analysis). Verifiable consent is then required in addition to verifying a parent-child relationship between users, all of which invoke hard document review.

Non-state institutional or contract-bound intermediary like a court-appointed guardian, a school or an employer. The linking of undergraduate and professional emails as methods by which social media platforms could increase the accuracy of their age verification processes fall short because these are typically only given to individuals of undergraduate or professional age, eg o18. At the same time requiring an undergraduate or professional email is likely to exclude a substantial number of adults. Users aged 13-17 who have not begun attending undergraduate institutions or working in professional environment will be unable to create accounts on the platform as a result Additionally, users from lower-income backgrounds, homeschool settings, or international markets where educational institutions do not provide email addresses will be irrationally excluded. Such an arbitrary and discriminatory outcome would amount to an unreasonable limit on access.

The service itself could perform age verification, age estimation or age assurance via the user directly or a third party, eg guardian.

## Age estimation

Some examples of age estimation or inference of age have been proposed to use a variety of behavioural and context-specific signals, not all of which users explicitly opt in to. There are general concerns that the use of user data for the purposes of age estimation can contravene data privacy frameworks that limit data usage to specific consent structures. Nonetheless we elaborate a couple of mechanisms here:

The behaviour of a user on a platform, including who they are friends with or what kind of content they engage in can provide some clues as to their age. However this data is limited to what service providers know about these users and is not as accurate for younger users since statistically there are fewer ways for the platform to know that its estimation is accurate. In deployment, this typically pairs behavioral signal-based estimation with a dispute mechanism: a user who disputes their estimated age may be asked to submit a government-ID photo or a live selfie instead, shifting from inference to verification only for the subset of users the initial estimate could not confidently place. [Google-Blog]

Biometric signals are considered age estimation rather than age assurance or verification because it’s not rooted in authoritative or ground truth. Biometric methods such as image or video facial scans are accompanied by a variety of flaws that prevent it from being a reasonable alternative. First, facial analysis technology is notoriously unreliable in estimating age, especially for teenagers, whose facial features change rapidly and vary widely. [NIST-IR-7995] These tools can also misclassify users depending on factors such as lighting, ethnicity, or facial expression [Ganel-2022]. Because faces near a threshold age (e.g., 18) are hard to distinguish from one week to the next, deployments typically apply a buffer, only accepting estimates significantly above the threshold; this reduces the false-accept rate but necessarily increases the false-reject rate for people who are in fact old enough, illustrating that facial estimation does not have one accuracy figure so much as a chosen point on that trade-off. [KGI-AgeAssurance-2026]

Both approaches also carry a distinct privacy profile: behavioural profiling repurposes data a platform already holds, so no new category of data is created, but a facial or video scan introduces biometric data—among the most sensitive categories under most data-protection frameworks—that must be retained, however briefly, to perform the estimation. Unlike a breached password or token, a breached biometric cannot be reissued.

## Other

There are perhaps other more indirect ways of achieving age appropriate use of online content and services. Perhaps broadly we could refer to these as market and content-based solutions.

Market: The prohibition of advertising, marketing, or subscriptions targeting children under the allowed age supports harm reduction while preserving privacy by disincentivizing children from joining platforms. This is realizable through regulatory action and addresses risk without compelling platforms to surveil or profile young– or any– users by disallowing the acceptance of payments for advertisements to children under the allowed ages.

At the infrastructure level, network or payment intermediaries can also enforce such prohibitions through category-based or transaction-type filtering that does not require user profiling. These methods are enforceable through consumer protections and guardrails that exist in the financial sector.

Rather than continuous geolocation, minimal-exposure signaling between networks and services could meet jurisdictional needs without tracking individuals. Networks maintain awareness of user location and applicable jurisdiction through routing, addressing, and service-delivery functions. This contextual knowledge could support privacy-preserving determination of the user-to-jurisdiction link, avoiding the need for continuous device-level geolocation. However there are implications for enforcement at the network level given the broad surface available for network level censorship capability on a per-user basis.

Content moderation more broadly is the commitment of services and platforms to ensure online experiences are fit for purpose, given the intended user base. For example certain k-12 educational websites with user generated content are certainly engaged in some strong degree of content moderation because the platform is for learning in schools, and not, say, popular culture or entertainment.

Each of these approaches sits toward the low-privacy-cost end of the spectrum described above: market-based and network-level filtering are designed to avoid new data collection altogether, trading some effectiveness for that privacy floor.

# Enforcement

Once age has been determined to a satisfactory degree, it’s important to interrogate the means by which content or a service is either accessible or not. This happens solely at the service level. In this section we expand on what happens once the service has obtained age assurance, or age verification if it has been party to hard documentation directly.

Enforcement is not a one-time determination. Long-standing, existing users who predate any age check pose a genuine question of how to obtain accurate age information retroactively, without simply re-running the same intrusive checks on an already-established user base. A related question arises as users age: how someone can "age up" in a platform over time, retaking full control of their account and data without ongoing parental or guardian oversight once they are no longer a minor.

It is generally important to note that the very definition of “adult content” is not universal. Material that one jurisdiction or culture classifies as adult—such as partial nudity, depictions of smoking, or the use of firearms—may be considered artistic, commercial, or sporting content elsewhere. As a result, even a compliant service might not be aware that some of its material would qualify as adult under another legal framework. This variability underscores the need for proportional, interoperable signaling systems rather than rigid or global classifications. Comparative regulatory analysis across jurisdictions confirms this divergence extends beyond content classification to the underlying regulatory philosophy itself—from safety-by-design co-regulation to rights-based frameworks to content-control-oriented approaches—cautioning against transplanting one jurisdiction's regime into another without adaptation. [TechLegality]

Platforms and services enforce by limiting access or visibility of certain categories of content based on the verified age attribute of a user or account. This can take several forms: hard blocks on sign-up, “shadow” restrictions such as hiding posts from underage accounts, or algorithmic filtering that reduces exposure to sensitive material. Enforcement at the service level can also include requiring a logged-in session tied to an attested age, but this raises issues around traceability, persistent identifiers, and the erosion of anonymous access to lawful content. Where the same attestation, token, or credential is reused to satisfy multiple services' enforcement requirements, this traceability compounds into cross-platform tracking: rather than minimizing the information any one service holds, it spreads the same underlying data across platforms and enables correlation of a user's activity across otherwise unrelated services.

Devices enforce by interpreting or acting on signals from applications, browsers, or operating systems to restrict or permit access. For instance, parental-control settings or OS-level content ratings can automatically block apps or sites flagged as adult. Device-level enforcement is often marketed as a privacy-preserving solution because it happens locally, but it can also centralize control in a few proprietary ecosystems and create dependency on vendor-defined “age ratings.” This can entrench cultural biases or commercial interests rather than reflect nuanced or localized standards.

Some considerations for networks that enforce age gating may be instructive for any system design as well, though content moderation at this lower network layer tends to be objectionable [RFC9505]:

* There exist internet standards for any service to signal to the user that it is adult-only. Any device, including web browsers, can elect to confirm this signal. It would be recommended to require all services that disallow users under a specific age to use this standard to use the “restricted to adults” label and that the OS, browser and app levels heed this signal [RTA]. Adoption remains marginal today—on the order of a few thousand sites among the web's top one million [PapersPlease-2026]—suggesting voluntary signaling alone is insufficient without device or browser-level enforcement. This should also be paired with self-attestation methods. Enforced by an ISP would be network level censorship.
* Similar signaling could extend to DNS or resolver functions, where privacy-preserving flags indicate that a domain hosts age-restricted material. [Cloudflare-Families] Such information can guide optional filtering at the user or guardian’s request without content inspection or identity disclosure.

There is a view that common, interoperable approaches across service, device, and network layers could lower compliance costs and align incentives for safer adoption. However this lowering of barriers to implementation would be considered a negative if age-gating is considered a form of disenfranchisement and censorship, or if the age-gating capabilities are applied to additional attributes of end users.

## Types of Platforms and Services

Age-assurance mechanisms cannot be applied uniformly across the Internet. Different platforms handle user data, content, and legal obligations in distinct ways, and therefore require proportionate, context-aware approaches. Enforcement can occur at several layers: core infrastructure and access networks may provide category-level controls; devices and browsers can interpret standardized labels; and services can apply context-specific age checks. Aligning these layers reduces redundancy and risk while maintaining privacy.

The most visible and contested area is that of **general-use platforms**—social-media, messaging, gaming, and app-distribution ecosystems that mix adult and minor audiences. These platforms collect large volumes of user data and operate globally, making privacy, feasibility, and jurisdictional diversity critical design challenges. In some jurisdictions, regulations already mandate the blocking or restriction of specific platforms for under-age users—for example, Australia's under-16 social-media ban, in effect since December 2025, which had removed or restricted several million accounts within its first few months of enforcement [eSafety-AU-2026]. Similar or proposed measures are under consideration across a majority of EU member states [Interface-EU-2026] and a growing number of jurisdictions globally [TechPolicyPress-2026]. Such measures highlight both the policy urgency and the architectural complexity of enforcing age-based restrictions at scale.

**General-use platforms** can be grouped by how users interact and how moderation and access controls are applied:
- **Social-interaction platforms** (e.g., video-sharing, live streaming) — rely heavily on user-generated content and recommendation algorithms; enforcement combines self-attestation, parental tools, and service-level moderation.
- **Communication platforms** (e.g., messaging, forums) — enable private or semi-private exchanges; assurance must function without content inspection, typically through account-level or device-level signaling.
- **Gaming and virtual-world platforms** — include in-app purchases and chat; controls combine guardian consent, payment-based age hints, and optional network-assisted filtering for external links.
- **App stores and distribution platforms** — act as aggregation points that enforce developer compliance and propagate uniform age labels or assurance tokens to downstream services.

Beyond these mixed-audience environments, several **specialized domains** require tailored approaches:
- **Adult-only or restricted-commerce services** — need high-assurance verification with minimal data disclosure and interoperable signaling.
- **Governmental and public-sector services** — are identity-bound by default within existing eID or authentication frameworks.
- **Essential-rights services** (banking, health, education, news) — must remain broadly accessible and minimize friction.
- **Core Internet infrastructure** (connectivity, routing, DNS, encryption) — should stay neutral and privacy-preserving, supporting only optional, user- or guardian-selected signaling.
- **Context-dependent or borderline material** — content such as artistic nudity, tobacco, or weapons varies by culture and law; enforcement should rely on localized policy mapping rather than global content bans.

### Summary of assurance levels and enforcement layers by platform type {#assurance-summary-table}

| Platform / Service Type | Typical Assurance Level | Primary Enforcement Layer | Notes |
|---|---|---|---|
| **Core Internet infrastructure** (connectivity, DNS, encryption) | None or optional self-attestation | Network / device | Remains neutral; may support user-selected, privacy-preserving signaling. |
| **Governmental & public-sector services** | Verified identity (strong assurance) | Service / eID framework | Age linked to legal identity under statutory controls. |
| **Essential-rights services** (banking, health, education, news) | Minimal assurance or self-attestation | Service / device | Broad accessibility required; avoid discrimination or exclusion. |
| **General-use: social-interaction platforms** | Self-attestation + parental / service moderation | Service / device | User-generated content; mixed audiences. |
| **General-use: communication platforms** | Account- or device-level assurance | Device / service | Private exchanges; no content inspection. |
| **General-use: gaming & virtual-world platforms** | Guardian consent + contextual assurance | Service / device / network | Includes in-app purchases and chat; external-link filtering possible. |
| **General-use: app stores / distribution** | Developer / publisher age labels | Service | Aggregation point enforcing consistent age metadata. |
| **Adult-only or restricted-commerce services** | High-assurance verification (document / token-based) | Service / device | Minimal data disclosure; interoperable signaling to networks. |
| **Context-dependent or borderline content** | Variable; localized policy mapping | Device / network / service | Classification differs across jurisdictions (e.g., nudity, tobacco, weapons). |

Categorizing platforms in this way clarifies that age-assurance methods—ranging from no assurance to self-attestation to high-assurance verification—must vary by context and by age group. A layered, proportionate framework enables compliance and safety objectives to be met without excessive data collection or centralized control.


# Concluding recommendations

* Reducing harm to children on the internet requires an incremental, all-hands approach and cannot be solved by age verification alone. A holistic approach would embrace privacy by design and data minimization principles that protect children as well as adults from platform overreach.

* If lawmakers are in a position to outlaw internet services for users of ages under 18 years old, they are in a position to define new credentialing systems that are fit for purpose rather than rely on hard documentation meant for operating automobiles, crossing national borders or social services entitlements.

* Introducing additional age-based signup requirements would risk harm to user privacy and free expression for all users of the web, not just to children, but especially to children.

* To date, jurisdictions around the world are considering various potential age-gating alternatives to mitigate potential safety risks to children without negatively impacting all social media users and without unduly compromising user privacy have reported evidence that advanced technical approaches to verify and assure age are currently infeasible or have significant downsides as compared to status quo approaches of self-reporting.

* Any mandate of age verification effectively regulates all users, rather than companies, to clear a compliance bar in which they must verify their age to the service to use an app. This approach does not address the central thrust of the problem statement, which seems to be that social media companies build platforms that are inclusive to children. Age assurance also regulates all users but has a lower bar and reduced friction for compliance making it a more inclusive choice overall.

* Content moderation of user generated content by platforms and services continues to be an established and effective way to ensure unlawful and disallowed content and behaviour is detected or reported and actioned with proper recourse and remedy mechanisms in the case of overreach.

* A more resilient approach may rely on a plurality of mechanisms operating at different layers of the Internet architecture—service, device, and network—each limited in scope and aligned with privacy-by-design principles. In this model, no single actor holds or processes all user information; rather, complementary methods (for example, self-attestation, trusted-service assurance, or privacy-preserving network-assisted filtering) can contribute to age-appropriate access control according to local regulation and user choice. Such diversity of methods can improve overall robustness and inclusiveness while reducing dependence on any single trust anchor. Contradicting data-protection principles like minimization means that if widely implemented without such safeguards, age-verification systems could still result in mass data collection on both adults and children, with far-reaching implications for user privacy and safety. Any deployment should be proportional and narrowly tailored to the specific harm it targets, rather than a blanket requirement applied uniformly regardless of risk. [CDT-Guardrails-2025]

* Age gating naturally puts a barrier to entry on a given site, and publishers who have spent significant effort optimising their sites for ease of use are now being asked to pay a third party to turn away a share of their customers—both legitimate and otherwise. The economic argument for a publisher to simply ignore the law is strong, particularly where a law is enacted in a jurisdiction where that publisher has no legal entity. In the often-cited example of pornography, this dynamic is likely to produce many more non-compliant sites than compliant ones, and non-compliant sites are likely to be non-compliant in other ways too—for example, failing to age-gate their own content creators.

# Security considerations

In general the cross-platform and over-the-wire exchange of information described in nearly all of the architectural choices above implicate security risks due to the complexity of the requirements, cooperation between several different parties and the expectation that this would be done at scale, for all users, not– perhaps naively assumed– just for youth.

When security tools are considered services that need age-gating such as in proposals to not allow youth to use end-to-end encryption this puts them at great risk and would never be supported by security considerations. Nor would age-gating of encryption be possible without some kind of intervention akin to backdooring encryption.

Hard document review – If instantiated, such measures would require the collection, processing, storage and securing of sensitive personal data from all users, including minors, which increases the risk of harm in the case of data breaches. [PrivacyIntl-2018] This processing and storage are vectors for mass and targeted surveillance by any State jurisdiction party to the UN Convention on Cybercrime.

Guardian and parental controls – This approach leaves the responsibility for age verification to parents, which can be fraught in some of the most acute cases of child abuse. [Newman-2022] In short, outside the context of mandatory age verification, these mechanisms can be used as tools for abusive parental or guardian surveillance.

If the surveillance power is given to the state instead, encouraging oversight by a potentially abusive regime is of real concern. Neither state nor parental control addresses in-person abuse of a child and technology can not solve that societal issue.

# Privacy considerations

Privacy is one of the two dimensions used to analyse methods in this document; the exposure, retention, and breach-severity profile of each method is treated directly alongside its description in the Analysis of age gating methods section above. What follows here addresses privacy implications that cut across methods rather than belonging to any one of them, in the context of data-minimization principles such as those in the EU General Data Protection Regulation (GDPR), which requires that personal data be collected only for specific purposes and limited to what is strictly necessary for those purposes.

In general, any mandatory age verification will technically enforce limitations of being anonymous online and the right to access resources on the web without being bound to a general or long term identification process over time, which have implications for human rights.[UN-HRC-29-32]

Location – Many of these approaches would also require collection of precise location information to comply with jurisdiction-by-jurisdiction privacy laws or other requirements. Geolocating users remains an unsolved problem: inaccurate geolocation means people will be unnecessarily excluded or have an incorrect set of laws applied to them, and this problem is likely to get worse as IPv4 fragments further.

Guardian and parental controls – The main concern with these parental controls features is that they enable use but potentially, depending on how they are designed, surveilled use, which may harm children and teens by creating confusion about their privacy and autonomy. On the one hand they may feel a false sense of privacy and that their activities are insulated from the platform, and on the other hand they might self-censor out of concern for the oversight that the parental controls provide their caretakers. These proposals take a narrow view of parent-child relationships and fail to consider the harms as described briefly by CDT: “In particular, LGBTQ youth and children in abusive homes are especially vulnerable to injury and reprisals, including from their parents or guardians, and may inadvertently expose sensitive information about themselves or their friends to adults, with disastrous consequences.” [CDT-2021]


# Human rights considerations

There is also significant agreement amongst the civil liberties and human rights communities that age verification poses more peril than the promise because of, “the ways in which they are often inaccurate; can be circumvented; present privacy and security risks; and may be entirely inaccessible to certain groups, including undocumented immigrants, unbanked individuals, people with disabilities, and others who either do not have access to government ids or who might be more commonly misidentified by biometric technology.” [CDT-2024] This peril is compounded by a contested evidence base: cross-national analyses have not established a consistent, measurable link between social media use and declines in youth well-being, and much of the research relied upon by proponents of youth social-media bans has been criticized for methodological weaknesses that overlook confounding factors such as pre-existing mental health conditions. [EFF-ScienceNotSettled-2026] Human rights bodies have raised similar concerns about blanket bans specifically: they are easily circumvented and can push children toward less-monitored spaces, whereas the harms motivating them more often stem from specific design choices—such as infinite scroll, autoplay, and persistent notifications—that safety-by-design requirements could address more directly than an age gate. [OHCHR-UN-2026] Children's-rights organizations have raised a related but distinct concern: legislative responses are proliferating faster than the evidence base can keep up with, and any framework must weigh child-protection goals alongside these same rights rather than treating them as mutually exclusive. [UNICEF-Line]


The Universal Declaration of Human Rights is fundamental to designing technical means of age-gating but also whether and how these means are implemented [RFC8280]. Prior, we have addressed privacy in the previous section. Additionally are considerations for free expression and free association. Economic, Social and Cultural rights are also important to consider as these include the right to personhood eg hard documents issued by the state; but also how age-gating might impact a variety of aspects of life for young people in the digital age.

## Free expression

Any content gating risks limiting lawful access to information, disproportionately affecting most marginalized people’s ability to engage in political, educational, and artistic discourse. Overbroad implementation risks chilling participation in online spaces that are essential for learning, advocacy, and identity formation, undermining Article 19 of the UDHR. This is not merely hypothetical: age-verification mandates have already been used to restrict lawful youth access to content concerning sexuality, gender identity, and reproductive health under expanded definitions of material "harmful to minors," demonstrating that the practical effect of such mandates can extend well beyond their stated child-safety purpose. [EFF-FinkeControl-2026]

## Free association

Mandatory identity checks for access to online services can deter participation in communities and movements that rely on pseudonymity for safety—such as youth networks, LGBTQ+ forums, or activist groups. This threatens the rights to assembly and association under Articles 20 and 23 of the UDHR by forcing users to trade anonymity for access.

## Social Rights

Right to social security and social protection — Systems may require digital identity or proof-of-age to access benefits, which can exclude those without ID or those in marginalized groups (ICESCR art. 9). Think about kids "in the system" or as "wards of the state" here.

Right to work and just conditions — Young workers might face barriers if age-verification systems are used in hiring or platform work, e.g., gig apps that require invasive ID scans. Kids 14-16 and up can often work in most places in the world, where bossware and other measures are increasingly in place.

Right to health — Age-gating can affect access to online sexual and reproductive health information, mental-health support forums, harm-reduction services, or LGBTQ+ youth resources.

## Cultural Rights

Right to participate in cultural life and access information — Content filters and strict age gates may overblock art, literature, or cultural expression, especially where sexuality or gender diversity is part of culture (ICESCR art. 15).

Scientific progress and its benefits — Excessive identification hurdles can chill participation in online learning, open science communities, or software sharing.

## Economic Rights

Right to education and vocational training — Age verification that requires credit cards, government IDs, or costly processes can exclude minors or low-income students from MOOCs or online courses (ICESCR art. 13).

Right to enjoy the benefits of one’s own creative work — Young creators and small businesses can be locked out of platforms if compliance costs are high or verification is inaccessible. There are a lot of famous kids on the internet making a lot of money from sponsorships and ads and this should be democratized and equally accessible globally.

Non-discrimination in economic life — Systems that assume everyone has a passport, bank account, or biometric record can indirectly discriminate against migrants, refugees, undocumented people, or low-income families.


# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
