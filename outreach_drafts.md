# Outreach drafts (2026-10-01)

CORRECTION 2026-10-03: the WellDev paragraphs below were rewritten. The earlier text claimed LLM agents and a 43% triage reduction; the user confirmed there is no AI component and the work is a tool-integration pipeline. The 43% is a reduction in false-positive vulnerability notifications versus the previous bot, not LLM triage time; it is left out of the drafts until you give the baseline, sample and period. The 'benchmarked Renovate, Snyk and DefectDojo' sentence was also removed until you confirm it.

Before sending: read the abstract of each cited paper and replace the [BRACKET] with one specific, honest sentence or question. Attach the cleaned CV. Do not claim anything you did not do. Send from your own address.

## 1. Kangjie Lu (University of Minnesota), kjlu@umn.edu

Page says: "I'm looking for Ph.D. students, a postdoc, and visiting students." Recent relevant papers on his page: "Break to Adapt: Knowledge-Based Updates of Breaking Dependencies in JavaScript" (FSE'26), "APILOT: Improving the Security and Usability of LLM Code Suggestions via Outdated API Mitigation" (ACSAC'25).

**Subject:** Prospective PhD student (Fall 2027): dependency updates and software supply-chain security

Dear Professor Lu,

I am a software engineer in R&D at WellDev (Bangladesh) and I am applying to CS PhD programs for Fall 2027. I am writing because your recent work on updating breaking dependencies ("Break to Adapt", FSE'26) and outdated-API mitigation (APILOT, ACSAC'25) is close to a problem I work on every day.

At WellDev I assembled a pipeline from open-source tools that tracks both security findings and routine dependency updates across our repositories: Trivy and Renovate run in GitHub Actions, CycloneDX SBOMs go to Dependency-Track, and findings are aggregated in DefectDojo. I did not write the tools; I built the integration. [BRACKET: one specific question or observation about Break to Adapt, e.g. how breaking-change knowledge could be reused for security advisories.]

Background: B.Sc. in CSE from KUET (CGPA 3.64/4.00); Best Paper Award at IEEE NCIM 2023 (a computer-vision paper, so outside security); two years as a university lecturer supervising thesis and final-year project groups; a merged fix to polyscan, a static-analysis tool for Rust code (PR #132); IELTS 7.5.

Your page says you are looking for PhD students. Are you planning to take a student for Fall 2027, and would you be open to a short call? My CV is attached and my site is https://raiyanislam.netlify.app.

Best regards,
Md. Raiyanul Islam

(Before sending: the resume has a typo "Co Contributed" for polyscan. PR #132 is verified merged (2026-09-12); fix the resume wording to match.)

## 2. Jamie Davis (Purdue), davisjam@purdue.edu, https://davisjam.github.io/

His Purdue profile lists him as Assistant Professor in **Electrical and Computer Engineering**, not CS. Projects listed: software supply chain security (theories, measurements, runtime defenses, PKI), third-party cyber threat hunting, regex DoS elimination, fuzzing. Topic areas include DevSecOps. No recruiting statement on the profile page, so ask.

**Subject:** Prospective PhD student (Fall 2027): software supply-chain security and DevSecOps

Dear Professor Davis,

I am a software engineer in R&D at WellDev (Bangladesh) applying to PhD programs for Fall 2027. Your work on software supply-chain security and DevSecOps matches what I do in industry, and I would like to learn whether your group could be a fit.

At WellDev I assembled a pipeline from open-source tools that tracks both security findings and routine dependency updates: Trivy and Renovate in GitHub Actions, CycloneDX SBOMs in Dependency-Track, findings aggregated in DefectDojo. I did not write the tools; I built the integration. [BRACKET: one specific observation or question about a recent paper of yours on supply-chain security, after reading it.]

Background: B.Sc. in CSE from KUET (CGPA 3.64/4.00); Best Paper Award at IEEE NCIM 2023 (a computer-vision paper); two years as a lecturer supervising thesis groups; IELTS 7.5.

Two questions: do you expect to take a PhD student for Fall 2027, and would you advise applying through ECE or CS for work with you? My CV is attached and my site is https://raiyanislam.netlify.app.

Best regards,
Md. Raiyanul Islam

## Rules for the rest
- Send Lu and Davis first, this week. Follow up once after 7 to 10 days; do not follow up twice.
- One email per professor, 150 to 250 words, one specific paper, one clear ask.
- Log every send in phd_tracker.csv (prof_N_email_status).
- Gulli is WellDev's previous internal notification bot (user, 2026-10-03); the new pipeline replaced it. In emails say 'the previous internal bot', not 'Gulli'. OpenCVE is real (attached to DefectDojo) and may be mentioned. Never mention LLM triage, RAG or function calling: no AI component was built (user, 2026-10-03). The 43% figure may be used ONLY as 'false-positive vulnerability notifications fell 43% compared with the previous bot', and only after you can state the baseline, sample and period (user, 2026-10-03).
