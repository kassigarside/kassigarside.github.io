---
title: "When a Face Becomes a Suspect"
date: 2022-12-09T19:53:33+05:30
draft: false
author: "CIPD’s Ethical practice and the role of people professionals"
tags:
  - Markdown syntax
  - Mathjax
  - example
image: /images/work ethics.jpg
description: ""
toc: true
mathjax: true
---
# When a Face Becomes a Suspect: The Ethics of AI in Policing
## A case study in facial recognition, human judgment, and the limits of voluntary ethics

## A match is not a fact

In January 2020, Detroit police arrested Robert Williams in front of his home, his wife, and his young daughters. Investigators had used facial recognition to compare a low-quality image from a Shinola store theft with photographs in a database. The system returned Williams as a possible match. He was not the person in the footage. The match became the starting point for a photo lineup, and the investigation treated that lead as if it were confirmation. Williams spent about 30 hours in custody before he was released. The American Civil Liberties Union (ACLU) later described the arrest as part of wider failures in Detroit’s use of facial recognition and police training. The ACLU’s 2021 complaint states that Williams spent about 30 hours in custody before he was released.

The central ethical question is not whether a computer can compare faces. It is what people and institutions do with a probabilistic result when it can affect someone’s liberty. The case makes a broader point from AI ethics: the important measure is impact. A system does not need human understanding or intent to exercise practical agency. If it can influence decisions about people, its designers and deployers have ethical duties. In policing, a “candidate match” can quickly become a suspect, and a suspect can become a person in handcuffs.

## The model is only one link in the chain

Facial recognition estimates how similar two images appear. It does not establish that the person in a camera image committed a crime, explain why they were there, or assess the reliability of the image itself. Low resolution, angle, lighting, and facial similarity can all matter. The National Institute of Standards and Technology (NIST) has found demographic differences in many face recognition algorithms it tested. Its 2019 evaluation reported that false positive rates could vary substantially across demographic groups and algorithms; the results were not identical for every system or use case. NIST also stresses that owners need to evaluate the particular algorithm in its operational setting.

That qualification matters. Saying “facial recognition is biased” as if every model behaves identically is too broad. Saying “the software is accurate” based on an average score is also inadequate. Ethical analysis asks which errors occur, for whom, under what image conditions, at what threshold, and with what consequences. For a person trying to unlock a phone, an error may be an inconvenience. In a criminal investigation, a false positive can trigger surveillance, interrogation, arrest, and lasting stigma.

The harms in Williams’s case were not produced by a model alone. They arose through a chain: poor-quality input, a search result treated as a lead, a lineup shaped by that result, and inadequate independent investigation. This is why algorithmic accountability must cover the full lifecycle: data selection, model testing, procurement, policy, training, human review, disclosure, and remedies. A human being “in the loop” does not automatically make a decision fair. If that person is anchored by an algorithmic suggestion or lacks time, training, or authority to challenge it, human review can simply ratify the system’s output.

## Ethical principles become practical tests

The course’s unified framework for AI ethics offers a way to test this chain. Five principles are especially relevant:

- **Nonmaleficence** asks whether preventable harm is being avoided. A false match in a high-stakes setting cannot be treated as a minor technical defect.
- **Justice** asks who bears the system’s errors and whether the burdens fall unevenly. Group-level error differences call for scrutiny of data, image quality, testing, and deployment conditions.
- **Autonomy** asks whether people retain meaningful choice and due process. A person generally cannot opt out of police image searches, so safeguards and avenues to challenge a match matter even more.
- **Privacy and security** ask whether collecting, searching, storing, and sharing biometric data are necessary and appropriately limited. A face is persistent and difficult to replace if compromised.
- **Explicability and accountability** ask whether affected people, investigators, courts, and defense counsel can understand how a result was produced and who is answerable when it contributes to harm.

These principles change the questions a department should ask before deployment. Does the system solve a legitimate need that cannot be met in a less intrusive way? Has the specific tool been independently tested on the types of images and populations it will encounter? What is the false positive rate at the threshold actually used? What independent evidence is required before an investigative lead can support a warrant? Can the person affected learn that the tool was used and challenge its role? Who is responsible for correcting a mistake? These are not abstract philosophical questions. They are operational requirements derived from ethical commitments.

## Soft ethics helps, but cannot replace law

Law and regulation are part of what the course calls **hard ethics**: binding duties, enforceable standards, and legal consequences. **Soft ethics** includes professional codes, internal policies, impact assessments, independent audits, training, and voluntary standards that help organizations act responsibly beyond the legal minimum. Both are needed. A statute may not anticipate every new use of AI, while a voluntary code can be ignored, weakly funded, or written to protect the organization rather than the public.

Detroit’s 2024 settlement with Williams shows how soft ethical practices can be made concrete and then backed by legal enforcement. The agreement, enforceable by a federal court for four years, bars police from conducting a lineup based solely on a facial recognition lead. Before seeking a warrant, detectives must document independent evidence and obtain supervisory sign-off. The agreement also requires documentation of searches, disclosure of relevant information to prosecutors, and safeguards for lineups. These are governance mechanisms: they define who must act, what must be recorded, and when a result is insufficient.

The case also illuminates the course’s warning about **ethics shirking**—deflecting responsibility by saying that a technology is too complex, that “the computer” made the decision, or that regulation is someone else’s job. It would be shirking to blame only the vendor or only the officer. Developers should test and disclose limitations. Police departments should set restrictions and train staff. Investigators should gather independent evidence. Supervisors and prosecutors should scrutinize the record. Legislators and courts should define rights and remedies. Responsibility is distributed, but it should never disappear.

A further risk is **ethics shopping**: selectively adopting principles that create a responsible image while leaving harmful practices untouched. A department could publish a fairness statement and still deploy a system without meaningful audits or appeal rights. Soft ethics has value only when it changes purchasing decisions, operational rules, budgets, disclosure practices, and consequences for noncompliance. An ethics impact assessment should happen before use, include affected communities, document anticipated harms and benefits, and be revisited after deployment. It should not become a polished report that merely legitimizes a decision already made.

## A better standard for high-stakes AI

The 2024 settlement points toward a more responsible standard, though no safeguard can erase every risk of surveillance or misidentification. A high-stakes AI system should be treated as an aid to investigation, never as a substitute for evidence. At a minimum, a department should:

1. **Set a clear purpose and necessity test.** Limit facial recognition to defined, serious investigative purposes and consider less intrusive alternatives.
2. **Test the actual system in context.** Publish meaningful performance results, including false positives and subgroup differences, using image conditions resembling operational footage.
3. **Require independent corroboration.** A match should not alone justify a lineup, warrant, or arrest. Investigators must seek evidence that does not simply repeat or reinforce the algorithm’s suggestion.
4. **Create traceable decisions.** Keep search records, identify the system and input quality, disclose limitations, and document who approved each consequential step.
5. **Give people notice and recourse.** When legally appropriate, people should be able to learn how a system affected a decision and challenge errors through a real process.
6. **Review impacts over time.** Audits, community input, and incident reporting should inform whether the system remains justified. If safeguards fail, use should be paused or ended.

This approach connects data science ethics to AI governance. Fairness is not a property that can be added to a model and declared complete. It depends on how data are gathered, how system performance is measured, which errors are tolerated, how outputs shape human judgment, and who can contest decisions. Privacy, consent, and accountability also extend beyond the code to procurement contracts, retention rules, disclosure, and institutional power.

## The ethical question comes after the match

AI can help people find patterns that would be difficult to detect manually. But the ability to produce a useful lead does not settle whether a use is just, proportionate, or legitimate. Williams’s case is a reminder that high accuracy in a benchmark cannot justify weak investigation, and a human decision-maker cannot be a meaningful safeguard if the surrounding process encourages deference to software.

A responsible system needs more than principles on a webpage. It needs binding rules where rights are at stake, soft ethics that builds good practice before and during deployment, and institutions capable of exposing and correcting failures. Most of all, it needs a simple discipline: treat an AI output as a claim that must be tested, not a fact that transfers the burden of proof to the person it names. When an algorithm points to a face, the ethical work has only begun.

## Sources

[1] ACLU of Michigan, “Facial Recognition,” case background and 2024 settlement summary. https://www.aclumich.org/cases/facial-recognition/
[2] National Institute of Standards and Technology, “Face Recognition Vendor Test (FRVT), Part 3: Demographic Effects,” NIST IR 8280 (2019). https://nvlpubs.nist.gov/nistpubs/ir/2019/NIST.IR.8280.pdf
[3] ACLU, “Summary of Detroit Facial Recognition Settlement Agreement (Williams v. City of Detroit)” (June 2024). https://assets.aclu.org/live/uploads/2024/06/williams_settlement_one-pager_june_24-1.pdf
[4] ACLU Fund of Michigan, *Williams v. City of Detroit*, Complaint (filed April 13, 2021). https://www.aclumich.org/app/uploads/2022/08/facial_recognition_leads_to_false_arrest_-_williams_v_city_of_detroit_-_complaint.pdf
[4] ACLU Fund of Michigan, *Williams v. City of Detroit*, Complaint (filed April 13, 2021). https://www.aclumich.org/app/uploads/2022/08/facial_recognition_leads_to_false_arrest_-_williams_v_city_of_detroit_-_complaint.pdf
Course connection: DA1A(hDAEthc) Day 11–14 lesson materials on AI ethics principles, soft ethics and governance, algorithmic harms, and sustainable AI development.