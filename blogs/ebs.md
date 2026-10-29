---
title: "EBS"
date: 2026-10-08T22:53:58+05:30
draft: false
github_link: "https://github.com/gurusabarish/hugo-profile"
author: "NIST’s AI Risk Management Framework FAQ"
tags:
  - Ethics
  
image: /images/data ethics.jpg
description: ""
toc: 
---



## Anonymous? The Ethics Behind a Course Feedback Survey

A short course survey can look harmless: ten questions, a temporary web link, and a promise that responses will remain anonymous. But the details matter. Participants must log in with their organizational username and password, and the survey asks which course they completed. Those design choices may make it possible to connect a response to a person—even if the survey does not ask for a name.

That possibility creates an ethical problem for participants and for the data analyst expected to turn their answers into recommendations. Executive management wants actionable insights about which courses should be redesigned or updated. That is a reasonable goal, but good intentions do not make every method of collecting or using data appropriate. The survey needs to be honest about what it collects, protect participants from avoidable harm, and produce evidence that is sound enough to guide decisions.

This analysis uses concepts commonly found in data ethics, including privacy, informed consent, confidentiality, data minimization, purpose limitation, re-identification, bias, and accountability. The specific concepts covered in the course may differ, so readers should connect these terms to the course materials where appropriate.
1. What is ethically troubling about the survey design?

The clearest concern is the gap between the promise of anonymity and the requirement to log in. Anonymity means that responses cannot reasonably be linked to the people who provided them. Confidentiality means that identifying information may exist, but it is protected and access to it is restricted. These are not interchangeable.

If the survey system records usernames, login events, timestamps, IP addresses, or other identifying information alongside responses, the responses may be confidential, but they are not anonymous. Even if the analyst cannot see a participant’s name, administrators or system logs may still make a connection possible. The description’s claim that “all answers and the survey itself will remain anonymous” could therefore be misleading unless the organization has verified how the system works and can explain exactly what information it retains.

The request for a course name adds another possible identifier. A course may have only a few participants, or a particular session may be associated with a small team. A response that contains no name can still be identifiable when combined with the course, the time of submission, a role, a location, or a distinctive comment. This is re-identification: identifying someone by combining details that seem harmless in isolation.

That matters because participants may answer differently if they think criticism could be traced back to them. They might avoid mentioning an instructor’s conduct, a safety concern, or a problem with the material. Others might skip the survey altogether. Either way, management receives less candid feedback and a weaker basis for course decisions.

There is also a problem of informed consent. Participants cannot make a meaningful choice about sharing their views if the description makes a promise the system cannot support. Consent should be based on accurate information about what is collected, who can access it, how it will be used, and whether responses can be linked to a participant. Logging in may be necessary to control access or prevent duplicate submissions, but participants should be told if that login can be connected to their answers.

The prompt asking for a course name raises a separate question about data minimization. If the organization only needs to compare feedback across courses, course identification may be justified. But it should collect no more information than necessary to do that. Asking for identifying details—or retaining them by default because the platform makes it easy—can increase risk without improving the analysis.

The assignment also refers to a “sample question,” but no actual survey question is included in the scenario. That limits what can responsibly be said about the wording of a specific question. Still, questions should be reviewed for leading language, double-barrelled wording, unclear scales, assumptions about a participant’s experience, and requests for unnecessary personal details. A question such as “How helpful and engaging was the instructor?” combines two judgments. A participant might find the instructor engaging but not helpful, and a single answer would hide that distinction. Neutral, clear questions produce more useful and fair evidence.
2. What other ethical issues could be present?

Even a properly described, well-secured survey can raise further ethical concerns.

Purpose limitation means using data for the purpose participants were told about. Here, the stated purpose is to identify courses that may need redesign or updating. The organization should not quietly repurpose responses for staff performance reviews, disciplinary decisions, or other high-stakes evaluations. If the purpose changes, participants may need a new explanation and a meaningful choice about whether to take part.

Fairness and bias also deserve attention. Survey results may not represent everyone’s experience. People who feel strongly may be more likely to respond; people with limited time, language barriers, accessibility needs, or concerns about being identified may be less likely to do so. A low response rate or uneven participation across courses can distort comparisons. A course with a small number of responses may appear to have an unusually high or low satisfaction score because one or two participants have a large effect on the average.

There are risks in how results are interpreted. A satisfaction score does not, by itself, establish that a course is effective or ineffective. A demanding course may receive lower ratings while teaching important material well. Conversely, a popular course may still leave participants unprepared. If management uses survey scores as the sole basis for redesign, it may reward popularity over learning outcomes or overreact to noisy data. The analyst should distinguish what the responses show from what they cannot prove.

Security and retention matter too. The organization should know where responses and logs are stored, who can access them, how long they are kept, and how they are deleted. Free-text answers can contain names, sensitive experiences, or allegations. Small-group reporting can expose participants even when identifiers have been removed. A promise of anonymity is especially risky if the organization has not checked these practical details.

Finally, there is an issue of accountability. Someone should be responsible for confirming that the survey description is accurate, approving access, managing retention, and reviewing how findings are used. Without clear responsibility, a survey can collect more data than intended and leave participants with no clear way to raise a concern.
3. What should the analyst recommend?

I would recommend that management address both the survey’s wording and its data practices before using the results to make consequential decisions.

Verify the platform’s data flows. Determine whether usernames, timestamps, IP addresses, device data, or other identifiers are stored with responses or can be joined to them. Check administrator access, exports, backups, and system logs—not just the fields visible to the analyst.

Make the description accurate. If the organization cannot ensure that responses are unlinked from identities, replace “anonymous” with a precise explanation. For example, say that access requires login, explain what information the system records, identify who may see it, and describe whether the analysis team receives identifiable data. Do not promise anonymity unless the system and its operating practices support that promise.

Collect only what is needed. Keep the course identifier if it is necessary for course-level analysis, but remove unnecessary identity fields and avoid collecting extra demographic or free-text information without a clear reason. Consider whether responses can be separated from access logs or reported only after they have been aggregated.

Set clear limits on use and access. Tell participants how results will be used, who will receive them, and how long data will be retained. Restrict access to people who need it. Establish that survey responses will not be reused for individual performance management unless participants are clearly informed and that use has been appropriately reviewed.

Review the questions. Have a neutral reviewer check for leading, ambiguous, double-barrelled, or needlessly intrusive questions. Test the survey with a small group to check that questions make sense and that the response options capture meaningful differences.

Report results responsibly. Set minimum group sizes for reporting, suppress results that could identify individuals, and handle free-text comments carefully. Report response counts and limitations alongside averages. Treat small samples as uncertain, and combine survey findings with other relevant evidence—such as learning outcomes, course completion data, and instructor or participant interviews—before recommending a redesign.

Provide a clear contact and review process. Participants should know whom to contact with questions or concerns. Management should assign responsibility for privacy, security, and appropriate use, and review the survey process periodically.

These recommendations help protect participants while improving the quality of the evidence. They also help management avoid mistaking a precise-looking number for a reliable or fair conclusion.
4. What if management rejects the recommendations?

If executives insist that the survey has no ethical or technical issues, I would continue to act professionally and document the basis for my concern. I would explain, in writing, the difference between anonymity and confidentiality, identify the specific data flows that remain unverified, and describe how those gaps could affect participant trust and the validity of the results. I would also offer practical options, such as changing the survey description, limiting access, or reporting only aggregate results.

If the concern remains unresolved, I could consult the organization’s privacy officer, data governance lead, ethics review process, ombudsperson, or legal counsel, depending on the organization’s structure. I would follow established internal escalation channels and retain relevant work records appropriately. I should not alter, conceal, or selectively present findings to make the survey appear safer or more conclusive than it is.

If asked to label the data “anonymous” without evidence, or to use it in a way that could harm participants contrary to the stated purpose, I could decline to make that representation or perform that analysis. I would explain the reason calmly and propose a defensible alternative. Where internal channels fail and the issue appears serious, I could seek confidential advice from an appropriate professional or oversight body, while respecting applicable confidentiality obligations and policies. Public disclosure or sharing identifiable survey data would not be a first response; any further action should be careful, proportionate, and grounded in the organization’s procedures and relevant obligations.

## A better survey makes better decisions

The ethical question is not simply whether management can access useful feedback. It is whether participants understand what they are agreeing to, whether the organization protects their responses, and whether the analysis supports sound decisions. A login requirement does not automatically make a survey unethical. But it does make an unqualified promise of anonymity something that must be checked, not assumed.

The analyst’s responsibility is to make those uncertainties visible and to help management act on evidence without overstating what it can tell them. Clear consent, careful data handling, fair interpretation, and accountable use are not obstacles to course improvement. They are part of doing it well.