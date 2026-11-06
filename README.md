<!--
author:   ICoBC - International Council on Badges and Credentials
email:    info@icobc.net
version:  1.0.0
language: en
narrator: UK English Female
comment:  A two-hour self-paced course that helps staff who design, assess or verify credentials to explain how AI works, where it is used in recognition, what the EU AI Act asks of them and which working rules keep its use trustworthy.
@style
:root { --icobc-navy:#02375B; --icobc-orange:#F78222; --icobc-cyan:#5DCAE7; --icobc-lime:#B1CF37; --icobc-mist:#F1F5F8; --icobc-line:#D8E2E9; --icobc-muted:#4F6576; }
body { font-family: "Open Sans", Arial, sans-serif; }
h1, h2, h3, h4 { color: var(--icobc-navy); }
a { color: var(--icobc-navy); }
table th { background: var(--icobc-mist); color: var(--icobc-navy); }
blockquote { border-left: 4px solid var(--icobc-orange); background: var(--icobc-mist); padding: 8px 16px; }
@end
-->

# AI Literacy for Recognition Work

**What staff who design, assess or verify credentials need to know about AI.**

Course ID: ICB-F07 | ICoBC Credentialing Skills Framework (ICSF), skill AIRC "Trustworthy AI in recognition" | VRITE pillar: Trustworthiness | Level L1 "Contribute" | Stage K "Knowledge"

## About this course

**Who it is for.** This course is for people who work with credentials and are now meeting AI in that work. It suits:

- L&D and corporate academy leads
- HR, talent acquisition and mobility staff
- Programme and micro-credential leads
- Learning designers and teaching staff
- Quality, registry and admissions staff
- Professional bodies and sector associations
- ICoBC Lead Reviewers and ICoBC Accredited Partners

You need no prior knowledge. You do not need to be a technical person.

**What the skill means at this level.** In ICSF terms, at level L1 "Contribute" and stage K "Knowledge", you explain how AI is used in learning and recognition, its limits, and your own responsibilities. The stage asks you to understand concepts, rules, standards and the reasons behind them. You can explain and recognise.

**Learning outcomes.** When you finish, you can:

1. Explain in plain terms how generative AI and other AI systems produce outputs and where they fail.
2. Identify uses of AI across the credential lifecycle: content, assessment support, skills inference, verification and agents.
3. Describe the AI literacy duty under the EU AI Act and why AI in education and employment decisions is treated as high-risk.
4. Apply basic rules for responsible use: human review, documentation, data protection and disclosure.

**Workload.** About 2 hours of self-paced learning. The file covers the self-paced part. Where a live or workshop element would help, you find it in a facilitator note.

**How it is assessed.** A knowledge check of 10 scenario and concept questions at the end. You pass with at least 7 correct answers.

**Badge.** "AI Literacy for Recognition Work (Knowledge, L1)", alignment code ICSF-AIRC-L1-K. Evidence: passed knowledge check.

| Outcome | Module | How it is assessed |
|---|---|---|
| 1. Explain how AI systems produce outputs and where they fail | How AI systems produce outputs | Module quiz; final knowledge check, questions 1 to 3 |
| 2. Identify uses of AI across the credential lifecycle | AI across the credential lifecycle | Module quiz; final knowledge check, questions 4 to 5 |
| 3. Describe the EU AI Act literacy duty and the high-risk logic | The EU AI Act in brief | Module quiz; final knowledge check, questions 6 to 7 |
| 3 and 4. Recognise risks and link them to the Act | Risks: bias, fabrication, privacy, over-reliance | Module quiz; final knowledge check, questions 8 to 9 |
| 4. Apply basic rules for responsible use | Working rules for your team | Module quiz; final knowledge check, question 10 |

> A note on what the badge shows. The badge records that you passed a knowledge check. It does not show that you can do a particular job, and it is not legal advice.

<details>
<summary>Facilitator notes</summary>

**Optional live element (45 to 60 minutes).** Run a short workshop after the self-paced part. Ask each team to bring one real AI use case from their own work. In small groups they place it on the risk grid from Module 2 and name the working rule from Module 5 that applies. End with a plenary round: each group names one rule they will start using this month. Do not ask participants to share personal data or real earner records.

</details>

## How AI systems produce outputs

### What an AI system is

An AI system takes an input and produces an output such as a text, a score, a label, a ranking or a prediction. It does this by following patterns that it learned from data, not by following a list of rules that a person wrote step by step.

Most of the tools you meet in recognition work are machine learning systems. A developer collects many examples, runs a training process, and the system adjusts millions or billions of internal numbers (called parameters) until its outputs fit the examples well. After training, the system applies what it learned to new inputs.

Two terms help here:

- **Training:** the phase in which the system learns patterns from data.
- **Inference:** the phase in which a trained system produces an output for a new input. Whenever you type a request and get a reply, the system is performing inference.

Different AI systems do different jobs. A **classifier** sorts inputs into groups, for example "complete" or "incomplete" for a document. A **ranking system** orders items, for example candidates by match score. A **prediction system** estimates a value, for example the likelihood that a learner completes a programme. A **generative system** creates new content, for example text, images or audio.

All of these systems are statistical. They give you a likely answer based on patterns. They do not hold a guarantee of truth.

### How generative AI writes text

A large language model (LLM) is a generative system trained on very large amounts of text. Its core task is simple to state: given the text so far, predict which small piece of text, called a token, is likely to come next. A token may be a whole word, part of a word or a punctuation mark.

The model repeats this step again and again. Each new token is added to the text, and the model predicts the next one. A fluent paragraph is the result of many such small predictions.

Some practical consequences follow:

- The model produces text that looks plausible. Plausible and correct are different properties, and the model is trained to optimise the first.
- The same prompt can give different answers on different attempts, because the system chooses among likely tokens with some randomness.
- The model does not look facts up in a database unless it has been connected to one. Without such a connection, it reproduces patterns from training.
- The model has no awareness of whether its answer is true. It does not "know" it is guessing.

Many products add extra layers around the model, for example a search step that retrieves documents and puts them in the prompt. This can improve accuracy on some tasks, but the model still writes the final text by prediction, so the output still needs checking.

### Where AI systems fail

Knowing the typical failure modes is the most useful part of AI literacy. Five matter for recognition work.

1. **Fabrication (often called hallucination).** The system states something false in a confident tone, such as an invented reference, an accreditation that does not exist or a wrong date. It happens because the system generates plausible text.
2. **Bias.** Training data reflects past decisions and past inequalities. A system trained on them can reproduce or amplify unfair patterns, for example by rating some groups lower.
3. **Out-of-date or missing knowledge.** A model only knows what was in its training data. Rules, frameworks and regulations change, and the model may describe an old position as current.
4. **Poor handling of context.** A system may not understand the local setting: the rules of your programme, the meaning of a national qualification level, or the intent behind an answer.
5. **Inconsistency.** Small changes in wording or order can change the output. Two staff members asking the same question may receive different answers.

Notice what these have in common. They are normal behaviour of a pattern-based system, not rare accidents. This is why the working rules in Module 5 assume that outputs need human review.

<svg viewBox="0 0 800 450" width="100%" role="img" xmlns="http://www.w3.org/2000/svg">
  <title>From input to output in an AI system, and where it can fail</title>
  <desc>A left-to-right flow: training data feeds a trained model, a user prompt enters the model, and an output leaves it. Below the flow, three failure points are labelled: fabrication, bias and out-of-date knowledge. A final box says a human checks the output.</desc>
  <rect x="0" y="0" width="800" height="450" fill="#FFFFFF"/>
  <rect x="30" y="40" width="160" height="80" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="110" y="75" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#02375B">Training data</text>
  <text x="110" y="98" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">past examples</text>
  <rect x="320" y="40" width="160" height="80" rx="6" fill="#02375B" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="75" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#FFFFFF">Trained model</text>
  <text x="400" y="98" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#FFFFFF">predicts patterns</text>
  <rect x="610" y="40" width="160" height="80" rx="6" fill="#5DCAE7" stroke="#02375B" stroke-width="2"/>
  <text x="690" y="75" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#02375B">Output</text>
  <text x="690" y="98" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">text, score, label</text>
  <line x1="190" y1="80" x2="316" y2="80" stroke="#02375B" stroke-width="2"/>
  <polygon points="320,80 310,74 310,86" fill="#02375B"/>
  <line x1="480" y1="80" x2="606" y2="80" stroke="#02375B" stroke-width="2"/>
  <polygon points="610,80 600,74 600,86" fill="#02375B"/>
  <rect x="320" y="170" width="160" height="50" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="400" y="200" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#02375B">Your prompt</text>
  <line x1="400" y1="170" x2="400" y2="124" stroke="#02375B" stroke-width="2"/>
  <polygon points="400,120 394,130 406,130" fill="#02375B"/>
  <text x="400" y="270" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#02375B">Where it can fail</text>
  <rect x="40" y="290" width="220" height="60" rx="6" fill="#F78222" stroke="#02375B" stroke-width="2"/>
  <text x="150" y="325" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#02375B">Fabrication</text>
  <rect x="290" y="290" width="220" height="60" rx="6" fill="#F78222" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="325" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#02375B">Bias in data</text>
  <rect x="540" y="290" width="220" height="60" rx="6" fill="#F78222" stroke="#02375B" stroke-width="2"/>
  <text x="650" y="325" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#02375B">Out-of-date knowledge</text>
  <rect x="240" y="375" width="320" height="50" rx="6" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="406" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#02375B">A person checks the output</text>
</svg>

### Why the output reads so well

Many people trust AI output because it is fluent. Fluency is a property of how the system writes, and tells you nothing about accuracy. A short, confident paragraph may be wrong in one key detail. Staff who verify credentials need to hold two ideas together: AI tools can save time on drafting and sorting, and they can state falsehoods in perfect grammar.

A simple habit helps. Before you rely on an AI output, ask three questions:

1. What was this system built to do?
2. What data or sources did it use, and could they be wrong or old?
3. Who checks the result before it affects a person?

**Worked example: An assistant invents an accreditation**

*University context.* A programme lead at a university asks a general AI assistant to draft a short description of a partner college for a credit-transfer agreement. The draft says the college is "accredited by a national quality agency since 2015" and names the agency. The text reads well. A quality officer checks the claim against the official register and finds no such entry. The assistant generated a plausible statement. The programme lead removes the sentence, adds only facts taken from the register, and records in the file that an AI tool helped with the first draft.

*Corporate academy context.* An academy lead at a company asks an AI assistant for the typical learning hours of a named external certificate. The assistant gives a precise number. The lead compares it with the certificate provider's own published description and finds a different figure. The lead uses the provider's figure and notes that the AI figure was wrong.

What the two cases show: the output was fluent, specific and false. Only a check against an authoritative source caught it.

**Practice activity: Trace the failure**

Think of one task in your own work where someone could use a generative AI tool, for example drafting a course description, summarising evidence or answering an applicant's question. Write down:

1. The input the tool would receive.
2. One thing in the output that could be false, biased or out of date.
3. The authoritative source you would use to check it.

Keep your notes. You will reuse them in Module 5.

<details>
<summary>Facilitator notes</summary>

Ask participants to swap their notes in pairs. The partner names one further failure mode from the list of five that the writer did not mention. Collect three examples on a shared board. Remind the group that nobody should paste personal data into a public tool for this exercise.

</details>

### Check your understanding

**Question 1.** What does a large language model do at its core when it writes text?

[( )] It looks up each fact in a verified database and copies it.
[(X)] It predicts which small piece of text is likely to come next, again and again.
[( )] It follows a fixed list of grammar and fact rules written by editors.
[( )] It searches the web in real time and quotes the best page.

[[?]] Think about the word "token" and what the model is trained to optimise.
****
The model repeatedly predicts the next token from the text so far. This produces plausible text, but plausible is not the same as true. Some products add search or databases around the model, but the writing itself is still prediction.
****

**Question 2.** An AI assistant states that a training provider holds a specific accreditation. Which action is best before you use that statement?

[( )] Use it, because the assistant sounded confident.
[( )] Ask the assistant to confirm, because it will repeat the true answer.
[(X)] Check the claim against the official register or the provider's own published information.
[( )] Use it only if the sentence is grammatically correct.

[[?]] Confidence and grammar are not evidence.
****
Fabrication is a normal failure mode of generative systems. Asking the same tool to confirm its own statement does not provide independent evidence. Check an authoritative source.
****

**Question 3.** Which of these is an example of bias as an AI failure mode?

[( )] The tool gives different wording on two attempts.
[( )] The tool does not know about a regulation published last month.
[(X)] A tool trained on past decisions rates some groups of applicants lower for reasons linked to past inequalities.
[( )] The tool invents a reference that does not exist.

[[?]] Look for the option that links the training data to unfair patterns.
****
Bias arises when training data reflects earlier inequalities and the system reproduces them. Different wording on repeated attempts is inconsistency, a missing regulation is out-of-date knowledge, and an invented reference is fabrication.
****

## AI across the credential lifecycle

### The lifecycle and its AI touchpoints

A credential has a lifecycle with three broad phases. Staff **issue** it (design, content, issuing), they **assess** the evidence behind it, and others **verify** it later. AI can touch every phase. The graphic below shows the main touchpoints. In this module we look at five groups of use: content, assessment support, skills inference, verification and agents.

<svg viewBox="0 0 800 450" width="100%" role="img" xmlns="http://www.w3.org/2000/svg">
  <title>AI touchpoints across issue, assess and verify</title>
  <desc>Three connected columns labelled Issue, Assess and Verify, each with example AI touchpoints. Issue lists content drafting and skills inference. Assess lists assessment support and feedback. Verify lists verification checks and agents. A navy circle with three open arcs below the columns represents recognition and trust.</desc>
  <rect x="0" y="0" width="800" height="450" fill="#FFFFFF"/>
  <rect x="30" y="30" width="230" height="40" rx="6" fill="#5DCAE7" stroke="#02375B" stroke-width="2"/>
  <text x="145" y="56" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#02375B">Issue</text>
  <rect x="285" y="30" width="230" height="40" rx="6" fill="#5DCAE7" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="56" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#02375B">Assess</text>
  <rect x="540" y="30" width="230" height="40" rx="6" fill="#F78222" stroke="#02375B" stroke-width="2"/>
  <text x="655" y="56" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#02375B">Verify</text>
  <rect x="30" y="90" width="230" height="60" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="145" y="126" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="15" fill="#02375B">Content drafting</text>
  <rect x="30" y="165" width="230" height="60" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="145" y="201" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="15" fill="#02375B">Skills inference</text>
  <rect x="285" y="90" width="230" height="60" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="400" y="126" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="15" fill="#02375B">Assessment support</text>
  <rect x="285" y="165" width="230" height="60" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="400" y="201" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="15" fill="#02375B">Feedback drafting</text>
  <rect x="540" y="90" width="230" height="60" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="655" y="126" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="15" fill="#02375B">Verification checks</text>
  <rect x="540" y="165" width="230" height="60" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="655" y="201" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="15" fill="#02375B">AI agents</text>
  <line x1="145" y1="240" x2="145" y2="270" stroke="#D8E2E9" stroke-width="2"/>
  <line x1="400" y1="240" x2="400" y2="270" stroke="#D8E2E9" stroke-width="2"/>
  <line x1="655" y1="240" x2="655" y2="270" stroke="#D8E2E9" stroke-width="2"/>
  <line x1="145" y1="270" x2="655" y2="270" stroke="#D8E2E9" stroke-width="2"/>
  <line x1="400" y1="270" x2="400" y2="300" stroke="#D8E2E9" stroke-width="2"/>
  <circle cx="400" cy="360" r="38" fill="#02375B"/>
  <path d="M 362 360 A 38 38 0 0 1 438 360" fill="none" stroke="#B1CF37" stroke-width="4" transform="translate(0,-14) scale(1,1)"/>
  <path d="M 436 332 A 54 54 0 0 1 436 388" fill="none" stroke="#F78222" stroke-width="4"/>
  <path d="M 380 408 A 54 54 0 0 1 350 322" fill="none" stroke="#5DCAE7" stroke-width="4"/>
  <text x="400" y="365" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#FFFFFF">Trust</text>
  <text x="400" y="438" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">Each touchpoint needs human oversight to protect trust</text>
</svg>

### Content, assessment support and skills inference

**Content.** Learning designers and teaching staff use generative AI to draft learning outcomes, descriptions of badges, quiz items, learner feedback templates and course text. The risk is low to moderate if a competent person reviews every item. The main failure modes are fabrication (a wrong standard or reference), generic content that does not fit your context, and outcomes that do not match the assessment. Review for accuracy and fit is the control.

**Assessment support.** AI can help to draft assessment tasks, mark scheme starting points, feedback comments or to give practice questions to learners. It can also appear on the earner side: learners use generative AI to help write assignments. This raises the question of assessment integrity. Detection tools that claim to tell whether a text was written by AI are not a reliable basis for decisions about a person. They can produce false positives and false negatives. Sound practice is to design assessments that capture the learner's own performance, for example observed tasks, oral questions or process evidence, and to state clearly what AI use is allowed.

**Skills inference.** Some HR and learning software infers skills from CVs, job descriptions, learning records or work activity. It maps text to a skills taxonomy and may rate how likely it is that a person has a skill. This is common in HR software and is an emerging practice. It can help with search and mobility suggestions. If its output is used to decide about hiring, promotion, task allocation or termination, it may fall under the high-risk category of the EU AI Act (see Module 3). The inferred skill is a statistical guess, not evidence of competence. Treat it as a lead for a person to follow up.

<!-- VERIFY: Confirm the current classification of skills-inference tools used in employment decisions against the final published AI Act text and any Commission guidance. -->

### Verification and agents

**Verification.** Verification means checking that a credential is genuine, current and issued by a recognised body. AI can help here by reading documents, comparing names and dates, flagging inconsistencies or routing a case to the right team. This can speed up registry and admissions work. The risk is that a system wrongly flags a genuine credential or passes a forged one. Verification decisions affect a person's access to study or work, so a staff member should take the final decision, particularly where an AI flag would lead to a refusal. Cryptographic proof, such as a digitally signed credential, is a separate technical means of checking authenticity. AI is not a substitute for it.

**Agents.** An AI agent is a system that does not only answer one question but takes a sequence of steps towards a goal, often using tools such as email, a database or a web browser. For example, an agent might collect evidence from several systems, fill in a form and send a message. Agents can save effort, and they also multiply the risk, because an early error can pass through several steps before anyone sees it, and the agent may act on systems that hold personal data. Good practice is to limit what an agent may access, require approval before it takes irreversible actions, and keep a log of what it did.

### A simple risk grid

The grid below helps teams to sort uses of AI. It is a thinking tool, not legal advice. The legal test is in the EU AI Act and in your own legal advice.

<svg viewBox="0 0 800 450" width="100%" role="img" xmlns="http://www.w3.org/2000/svg">
  <title>Grid of AI uses rated low risk, check or high-risk</title>
  <desc>Three columns. Low risk lists drafting internal notes and summarising public documents. Check lists generating learner feedback and drafting badge descriptions. High-risk lists scoring applicants, ranking candidates for promotion and deciding admission or credential award without human decision.</desc>
  <rect x="0" y="0" width="800" height="450" fill="#FFFFFF"/>
  <rect x="30" y="30" width="230" height="50" rx="6" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="145" y="62" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="17" fill="#02375B">Low risk</text>
  <rect x="285" y="30" width="230" height="50" rx="6" fill="#5DCAE7" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="62" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="17" fill="#02375B">Check</text>
  <rect x="540" y="30" width="230" height="50" rx="6" fill="#F78222" stroke="#02375B" stroke-width="2"/>
  <text x="655" y="62" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="17" fill="#02375B">High-risk</text>
  <rect x="30" y="100" width="230" height="80" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="145" y="135" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Drafting internal</text>
  <text x="145" y="155" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">meeting notes</text>
  <rect x="30" y="195" width="230" height="80" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="145" y="230" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Summarising public</text>
  <text x="145" y="250" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">policy documents</text>
  <rect x="285" y="100" width="230" height="80" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="400" y="135" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Drafting badge</text>
  <text x="400" y="155" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">descriptions</text>
  <rect x="285" y="195" width="230" height="80" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="400" y="230" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Drafting learner</text>
  <text x="400" y="250" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">feedback comments</text>
  <rect x="540" y="100" width="230" height="80" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="655" y="135" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Ranking candidates</text>
  <text x="655" y="155" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">for hiring</text>
  <rect x="540" y="195" width="230" height="80" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="655" y="230" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Scoring applicants</text>
  <text x="655" y="250" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">for admission</text>
  <text x="145" y="310" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">No decision about a person</text>
  <text x="400" y="310" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">Human review of every output</text>
  <text x="655" y="310" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">Affects access to study or work</text>
  <rect x="30" y="350" width="740" height="60" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="400" y="386" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="15" fill="#02375B">The more a use affects a person's access to study or work, the more control it needs</text>
</svg>

**Worked example: Sorting four uses on the grid**

*Training provider context.* A registry team at a training provider lists four AI uses it is considering: (a) a tool that drafts reminder emails to learners about deadlines, (b) a tool that suggests feedback comments for tutors to edit, (c) a tool that scores written applications and ranks applicants for a limited number of places, and (d) a tool that reads uploaded certificates and flags possible forgeries for staff to examine.

The team sorts them. Use (a) is low risk: no decision about a person. Use (b) goes to "check": a tutor reviews every comment before it goes to a learner. Use (c) is high-risk: it influences who gets access to education. Use (d) goes to "check" with a strong human step, because a wrong flag could harm a genuine applicant. Where a flag could lead to refusal, a staff member decides.

*Corporate academy context.* An HR department considers a tool that infers skills from employee profiles and suggests internal moves. Suggestions that only help employees to explore options sit at "check". If managers use the ranking to choose who gets a promotion or a role, the use moves towards high-risk and needs the controls in Module 5 and legal review.

**Practice activity: Place your own uses**

List three AI uses that are in your team already or that colleagues have proposed. Place each in the grid: low risk, check or high-risk. For each, write one sentence that explains why. For any "high-risk" item, name the person who would take the final decision.

<details>
<summary>Facilitator notes</summary>

Print the grid or draw it on a board. Give each group five sticky notes with real uses. After placing them, ask groups to find the use that caused most disagreement and explain what extra fact would settle it, for example "who sees this output" or "does it influence a decision about a person". Keep the discussion on facts about the use, not on a named tool.

</details>

### Check your understanding

**Question 4.** A university registry wants to use AI to read uploaded certificates and flag possible forgeries. Which approach reflects good practice?

[( )] The tool refuses a credential automatically whenever it raises a flag.
[(X)] The tool flags cases and a staff member examines them and takes the decision.
[( )] The tool replaces digital signatures and other technical checks of authenticity.
[( )] The tool decides without a log, to protect privacy.

[[?]] Think about who should decide when a flag could lead to a refusal.
****
Verification affects a person's access to study or work. AI may help by flagging and routing, but a person should decide, and the tool does not replace technical authenticity checks or the need for a record of what happened.
****

**Question 5.** An HR team uses software that infers skills from employee profiles. Managers plan to use the ranking to decide who gets a promotion. What is the best description of this use?

[( )] Low risk, because the software only reads existing data.
[( )] Always forbidden, whatever the controls.
[(X)] It may be high-risk, because it feeds a decision about a person in employment, so it needs legal review and strong human oversight.
[( )] Outside any rules, because skills inference is an emerging practice.

[[?]] Consider what the output is used for, not how the software works.
****
Skills inference is an emerging, common feature of HR software. When its output feeds employment decisions, it may fall under the high-risk category. It is not automatically forbidden, and it is not outside the rules because it is new.
****

## The EU AI Act in brief

### Why this law matters for recognition staff

The EU AI Act (Regulation (EU) 2024/1689) is the European Union's main law on AI. It sets rules for the development and use of AI systems in the EU market. It uses a risk-based approach: the higher the risk to people's rights and safety, the stricter the rules.

You do not need to be a lawyer to benefit from knowing its outline. Staff in education, training and HR use AI in areas that the Act treats with special care. This module gives a short, plain-language overview. It is not legal advice. For decisions in your organisation, use your legal or data protection team.

Status as of November 2026; check before publishing.

### The AI literacy duty

The Act contains a duty on AI literacy. In short, providers and deployers of AI systems must take measures to ensure, as far as possible, a sufficient level of AI literacy among their staff and others who operate or use AI systems on their behalf. The level should fit people's knowledge, experience, training and the context in which the systems are used.

Three points help to read this duty:

- **It applies to the organisation.** The duty sits with the provider or the deployer. A deployer is an organisation that uses an AI system under its own authority, for example a university or a company using AI software in its work.
- **It is proportionate.** A person who only drafts internal notes with an assistant needs different knowledge from a person who configures a screening tool.
- **It needs a record.** The text does not prescribe a specific certificate. Organisations normally show what they did, for example training, guidance and who took part. A course like this one can form part of such a record, and it does not alone prove compliance.

<!-- VERIFY: Check the exact wording and current application date of the AI literacy provision against the official text of Regulation (EU) 2024/1689 and any amendment through the Digital Omnibus on AI. -->

### Why education and employment are treated as high-risk

The Act sorts AI systems into levels of risk. Some practices are prohibited. Some systems are "high-risk" and must meet detailed requirements. Some have transparency duties, for example telling people that they are interacting with AI. Many others face few specific obligations.

High-risk systems are listed in Annex III of the Act. Two areas matter greatly for recognition work:

- **Education and vocational training.** Examples include AI used to decide on access or admission, to evaluate learning outcomes, to assess the appropriate level of education a person will receive, or to monitor prohibited behaviour during tests.
- **Employment, workers' management and access to self-employment.** Examples include AI used to recruit or select people, to filter applications, to decide on promotion or termination, to allocate tasks or to monitor and evaluate performance.

The reasoning is the same in both areas. These decisions shape a person's life chances: a place on a programme, a qualification, a job. The person affected often cannot see how the system works and cannot easily challenge it. Errors and bias can repeat at scale. For this reason the Act asks for risk management, data quality, documentation, transparency, human oversight, accuracy and robustness for high-risk systems.

Most obligations fall mainly on the **providers** who build such systems and, in different ways, on the **deployers** who use them. As a deployer, an education provider or an HR department typically needs to use the system as instructed, assign human oversight to competent people, keep logs, watch for problems and inform affected people where the Act requires it.

### Timing and the Digital Omnibus

Timing of the high-risk obligations has been under discussion in the EU. Under the Digital Omnibus on AI (AI Omnibus), a provisional agreement reached on 7 May 2026 sets the application of Annex III high-risk obligations from 2 December 2027, and of obligations for Annex I product-embedded systems from 2 August 2028. These dates depend on the final published text. Check the final legal text and official guidance before you plan.

Status as of November 2026; check before publishing.

<!-- VERIFY: Confirm that the AI Omnibus was adopted and published in the Official Journal and that the dates 2 December 2027 (Annex III) and 2 August 2028 (Annex I) are unchanged in the final text. -->

A practical point follows. Even if some obligations apply later, good practice does not need to wait. Human review, documentation and careful choice of tools are sensible now, and they prepare your team for the dates.

<svg viewBox="0 0 800 450" width="100%" role="img" xmlns="http://www.w3.org/2000/svg">
  <title>Risk levels in the EU AI Act and where recognition work sits</title>
  <desc>A stepped pyramid of four levels: prohibited practices at the top, high-risk systems, transparency duties, and minimal obligations at the base. Education and employment decisions are labelled as examples at the high-risk level.</desc>
  <rect x="0" y="0" width="800" height="450" fill="#FFFFFF"/>
  <rect x="300" y="30" width="200" height="70" rx="6" fill="#F1F5F8" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="62" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#02375B">Prohibited</text>
  <text x="400" y="84" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">unacceptable practices</text>
  <rect x="230" y="115" width="340" height="80" rx="6" fill="#F78222" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="148" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#02375B">High-risk</text>
  <text x="400" y="172" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">strict requirements before and during use</text>
  <rect x="160" y="210" width="480" height="70" rx="6" fill="#5DCAE7" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="242" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#02375B">Transparency duties</text>
  <text x="400" y="264" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">for example telling people they deal with AI</text>
  <rect x="90" y="295" width="620" height="70" rx="6" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="327" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#02375B">Minimal specific obligations</text>
  <text x="400" y="349" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">AI literacy duty still applies to organisations</text>
  <rect x="590" y="125" width="190" height="60" rx="6" fill="#FFFFFF" stroke="#D8E2E9" stroke-width="2"/>
  <text x="685" y="150" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Education and</text>
  <text x="685" y="170" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">employment decisions</text>
  <line x1="570" y1="155" x2="588" y2="155" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="410" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">Simplified overview. Check the Regulation for the full rules.</text>
</svg>

**Worked example: A scoring tool at a college and at a company**

*College context.* A college wants to buy software that scores applicants to an oversubscribed programme and produces a ranked list. The admissions lead asks three questions. Does the tool help to decide access to education? Yes, so it is in the area treated as high-risk. Who builds it, and what documentation and instructions does the provider give? The college asks for them. Who will oversee its use? The lead names two trained admissions officers who can question and override the ranking, and asks the data protection officer to check the personal data involved.

*Corporate context.* A talent acquisition team considers an AI feature that filters applications and ranks candidates. The head of talent recognises recruitment as an employment use, so she involves legal and data protection staff, asks the provider for documentation, keeps a human recruiter in every shortlisting decision and records that the team has had AI literacy training.

In both cases the AI literacy duty is met in part by staff understanding the tool, and the high-risk logic leads the teams to ask for documents and keep humans in charge.

**Practice activity: Four questions for any tool**

Choose one AI tool or feature that your organisation uses or might use. Answer in writing:

1. Does it influence access to education or training, or a decision about recruitment, promotion, task allocation or termination?
2. Who is the provider, and what documentation have you received?
3. Who in your team has the role of human oversight, and what training do they have?
4. Where would you record what you did and why?

<details>
<summary>Facilitator notes</summary>

Invite a data protection or legal colleague for a 15-minute question session. Ask participants to send questions beforehand. Stress that the course gives a general overview and that organisation-specific decisions need qualified advice. Remind the group that dates and details may change and should be checked against the published text.

</details>

### Check your understanding

**Question 6.** What does the AI literacy duty in the EU AI Act ask of organisations that provide or deploy AI systems?

[( )] That every employee passes one specific national exam.
[(X)] That they take measures to ensure, as far as possible, a sufficient level of AI literacy among staff and others who use AI on their behalf, fitted to the context.
[( )] That they stop using generative AI until a regulator gives permission.
[( )] That they publish the source code of every AI system they use.

[[?]] The duty is proportionate and sits with the organisation.
****
The duty asks for measures that give staff and others a sufficient level of AI literacy, adjusted to their knowledge, role and the context of use. It does not set one exam, ban generative AI or require publishing source code.
****

**Question 7.** Why are AI systems used for admission to education or for recruitment treated as high-risk?

[( )] Because they are always more accurate than people.
[( )] Because they use large amounts of electricity.
[(X)] Because such decisions shape a person's life chances, the person often cannot see or challenge how the system works, and errors or bias can repeat at scale.
[( )] Because they are new.

[[?]] Think about the effect on the person, not the technology.
****
The Act treats these uses as high-risk because of their effect on people's access to education and work, the difficulty of challenging an automated result, and the scale at which bias or error can spread.
****

## Risks: bias, fabrication, privacy, over-reliance

### Bias and fairness

AI systems learn from past data. If that data records unequal treatment, or leaves out some groups, the system may repeat and sometimes amplify the pattern. In recognition work, three situations deserve attention.

First, **selection and ranking tools**. A system trained on past successful candidates may favour profiles similar to those candidates. People with different routes into study or work, for example those with prior learning gained informally, may rank lower without any link to their ability.

Second, **language and accent**. Tools that assess written or spoken language may perform worse for some groups, such as people who write in a second language or use a regional variety.

Third, **proxy data**. Even if a tool does not use protected characteristics, other data such as postcode, school name or gaps in employment can stand in for them.

What can staff do? Ask the provider what data was used and how fairness was tested. Compare the tool's results across groups where you are allowed to do so. Keep a person in the loop who can spot odd patterns. Give people a way to ask for human review. Bias is not a fault you remove once. It needs monitoring over time.

### Fabrication and assessment integrity

Fabrication was introduced in Module 1. In recognition work it can harm in specific ways: an invented reference in a course design, a false claim about a provider's status, or a summary of evidence that contains a statement the learner never made.

Assessment integrity is the second side of this risk. Learners and candidates can use generative AI to produce work. Providers sometimes try to solve this with AI detection tools. Detection tools are not a reliable basis for decisions about a person. They make errors in both directions, and a false accusation can do real harm. Treat a detector result at most as a prompt for a conversation, never as proof. Better controls are in the design of the assessment: tasks that need personal reflection or local context, observed performance, oral discussion of the work, staged submissions that show a process, and clear rules about what AI use is allowed and how to disclose it.

### Privacy and data protection

Using AI tools often means sending data to a service. In recognition work this data can include names, dates of birth, identification documents, grades, employment history, health information shared for adjustments, and free-text feedback. Under the EU General Data Protection Regulation (GDPR), such personal data needs a legal basis, must be used for a clear purpose, should be limited to what is needed, and must be kept secure. People also have rights, for example to information and access, and rights relating to certain automated decisions.

Four questions guide daily practice:

1. **Is personal data going into the tool?** If you do not need it, leave it out. Use anonymised or invented examples to test.
2. **Where does the data go?** Find out from your organisation whether the tool is approved, where data is stored and whether the provider may use it to train its models.
3. **Is there a legal basis and a purpose?** Your data protection officer can advise.
4. **Does the tool take or strongly influence a decision about a person?** If so, extra safeguards apply, and you should involve your data protection and legal colleagues.

Do not paste earner records, identity documents or confidential evidence into a public AI tool that your organisation has not approved.

### Over-reliance

Over-reliance means accepting AI output without proper checking. It builds up quietly. A tool is right ten times, the team relaxes, and the eleventh error passes unnoticed. This is sometimes called automation bias: the tendency to trust a machine's suggestion over one's own judgement or contrary evidence.

Signs of over-reliance include reviewers who approve in seconds, no record of corrections, staff who cannot explain how a recommendation arose, and skills that fade because the tool does the work. Controls include regular spot checks of a sample of outputs, rotating reviewers, keeping a record of how often humans change the AI result, and training that reminds staff that they, not the tool, are responsible for decisions.

There is also a wider effect on trust. Credentials work because people believe that a badge or certificate means what it says. If AI use is hidden or sloppy, that belief can weaken. The VRITE pillar of Trustworthiness asks organisations to earn that belief with rigour and openness.

<svg viewBox="0 0 800 450" width="100%" role="img" xmlns="http://www.w3.org/2000/svg">
  <title>Four AI risks and the control for each</title>
  <desc>Four boxes in a row, each pairing a risk with a control: bias with monitoring and human review, fabrication with checking against authoritative sources, privacy with data minimisation and approved tools, over-reliance with spot checks and clear responsibility.</desc>
  <rect x="0" y="0" width="800" height="450" fill="#FFFFFF"/>
  <rect x="30" y="40" width="170" height="60" rx="6" fill="#F78222" stroke="#02375B" stroke-width="2"/>
  <text x="115" y="76" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#02375B">Bias</text>
  <rect x="220" y="40" width="170" height="60" rx="6" fill="#F78222" stroke="#02375B" stroke-width="2"/>
  <text x="305" y="76" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#02375B">Fabrication</text>
  <rect x="410" y="40" width="170" height="60" rx="6" fill="#F78222" stroke="#02375B" stroke-width="2"/>
  <text x="495" y="76" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#02375B">Privacy</text>
  <rect x="600" y="40" width="170" height="60" rx="6" fill="#F78222" stroke="#02375B" stroke-width="2"/>
  <text x="685" y="76" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#02375B">Over-reliance</text>
  <line x1="115" y1="100" x2="115" y2="150" stroke="#02375B" stroke-width="2"/>
  <line x1="305" y1="100" x2="305" y2="150" stroke="#02375B" stroke-width="2"/>
  <line x1="495" y1="100" x2="495" y2="150" stroke="#02375B" stroke-width="2"/>
  <line x1="685" y1="100" x2="685" y2="150" stroke="#02375B" stroke-width="2"/>
  <rect x="30" y="150" width="170" height="130" rx="6" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="115" y="185" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Test results across</text>
  <text x="115" y="205" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">groups, keep human</text>
  <text x="115" y="225" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">review and a route</text>
  <text x="115" y="245" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">to appeal</text>
  <rect x="220" y="150" width="170" height="130" rx="6" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="305" y="185" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Check claims against</text>
  <text x="305" y="205" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">official sources, do</text>
  <text x="305" y="225" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">not rely on detectors</text>
  <text x="305" y="245" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">for decisions</text>
  <rect x="410" y="150" width="170" height="130" rx="6" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="495" y="185" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Share the minimum</text>
  <text x="495" y="205" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">data, use approved</text>
  <text x="495" y="225" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">tools, ask your data</text>
  <text x="495" y="245" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">protection officer</text>
  <rect x="600" y="150" width="170" height="130" rx="6" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="685" y="185" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Spot checks, rotate</text>
  <text x="685" y="205" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">reviewers, log</text>
  <text x="685" y="225" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">changes, name who</text>
  <text x="685" y="245" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">is responsible</text>
  <text x="400" y="330" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#02375B">Orange: risk. Lime: control.</text>
  <text x="400" y="360" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">Every control keeps a person accountable for the result.</text>
</svg>

**Worked example: An integrity alert and an uploaded transcript**

*University context.* A teaching assistant at a university runs a learner's essay through an AI detection tool. It reports a high probability of AI writing. The assistant remembers that detection tools are not a reliable basis for decisions. Instead of accusing the learner, the assistant invites the learner to a short conversation about the essay's argument and sources. The learner explains the work in detail and shows draft notes. No misconduct is recorded. The programme lead then reviews the course's assessment design and adds a short oral component.

*Corporate academy context.* A HR officer wants an AI assistant to summarise an employee's uploaded transcript and performance notes for a mobility decision. The notes contain health information about adjustments. The officer checks with the data protection officer, learns that the public tool is not approved for personal data, and uses the approved internal tool with only the fields needed. The officer reads the summary against the source documents, finds that it has attributed a course to the wrong year, and corrects it before the file goes to the panel.

**Practice activity: Risk spotting**

Read this short case and write a list of the risks you can find: *"A programme team uses an AI tool to screen portfolios of prior learning. The tool was trained on portfolios from past successful applicants. Staff paste whole portfolios, including ID scans, into a free online assistant to speed things up. Reviewers approve the AI scores in about ten seconds each. A rejected applicant asks why."*

For each risk, name the matching control from the graphic. Then compare with a colleague.

<details>
<summary>Facilitator notes</summary>

Expected points: bias from training on past successful portfolios; privacy breach through ID scans in a free tool; over-reliance shown by ten-second approvals; missing explanation and human review route for the rejected applicant, and possible high-risk use because it affects access to education. Ask the group to rank the risks by how quickly they would act on each.

</details>

### Check your understanding

**Question 8.** A detection tool reports that a learner's work is "92 per cent likely AI-generated". What is the most appropriate use of this result?

[( )] Treat it as proof and record misconduct.
[( )] Share it with the learner's employer.
[(X)] Treat it, at most, as a reason to talk with the learner and look at other evidence, because detection tools are not a reliable basis for decisions.
[( )] Re-run the tool until it gives a lower figure.

[[?]] Consider false positives and the harm of a wrong accusation.
****
AI detection tools make errors in both directions and cannot support a decision about a person on their own. A conversation, drafts and assessment design give better evidence.
****

**Question 9.** A recruiter pastes candidates' full CVs, including contact details, into a free public AI assistant that the organisation has not approved. Which risk is most directly raised?

[( )] Fabrication only.
[( )] Over-reliance only.
[(X)] Privacy and data protection, because personal data goes to a service without approval, a clear legal basis or a check of where it is stored.
[( )] No risk, because CVs are public documents.

[[?]] Think about where the data goes and who approved it.
****
Sharing personal data with an unapproved tool raises data protection issues under the GDPR. Staff should share the minimum data, use approved tools and ask the data protection officer when unsure.
****

## Working rules for your team

### Four rules and why they work

The risks in Module 4 are manageable with a small set of habits. These rules suit a team at L1, where you contribute to good practice by following and supporting agreed rules. Your organisation may have more detailed policies. Follow those where they exist.

**Rule 1: Human review.** A competent person checks AI output before it affects a learner, candidate or credential. The reviewer needs enough knowledge to spot errors, the time to do it and the authority to change or reject the output. For decisions about a person, such as admission, award of a credential, recruitment or promotion, a human takes the decision and can explain it. A quick click on "approve" is not review.

**Rule 2: Documentation.** Keep a short record of how you use AI in work that matters. A useful record says which tool and version you used, for what purpose, what data went in, what a person checked and changed, and who approved the result. Documentation supports accountability, helps colleagues to repeat good practice, and helps you to answer questions from earners, auditors or regulators. It also supports the AI literacy duty, because it shows what measures the organisation took. Keep records proportionate: a draft badge description needs a line, a scoring tool needs more.

**Rule 3: Data protection.** Use only approved tools for work involving personal data. Share the minimum needed. Prefer anonymised or invented data for testing. Do not paste identity documents, health information or confidential evidence into public tools. If unsure, ask your data protection officer before you start, not after.

**Rule 4: Disclosure.** Be open about AI use where it matters to the people affected. Tell earners when AI helps to assess or give feedback on their work. Say how AI was used in credential design or evidence review if a reader would reasonably want to know. Where AI-generated content goes to the public, label it as the law or your policy requires. State clearly to learners what AI use is allowed in their own work and how they should disclose it. Disclosure builds trust and gives people a chance to question a result.

### Putting the rules into daily practice

A few practical habits make the rules easy to follow.

- **Before you start:** ask whether the task involves a decision about a person, and whether personal data will go into the tool. If both answers are no, you can usually proceed with normal care. If either is yes, check your organisation's policy and involve the right colleague.
- **While you work:** treat every output as a draft. Check names, dates, numbers, references and claims against authoritative sources.
- **Before you finish:** note what you did, say what a person checked, and disclose AI use where it matters.
- **When something goes wrong:** report it to your lead or data protection officer. A wrong output that reached a learner, or data sent to an unapproved tool, should be raised early. A blame-free reporting habit helps the whole team to learn.

A short note on tone: these rules are meant to support good work, not to stop it. AI tools can save time on drafting, sorting and summarising. The rules keep the time saving and protect the people on the receiving end.

<svg viewBox="0 0 800 450" width="100%" role="img" xmlns="http://www.w3.org/2000/svg">
  <title>Four working rules for responsible AI use</title>
  <desc>A navy circle in the centre labelled Responsible use, with four labelled boxes around it: human review above, documentation to the right, data protection below and disclosure to the left. A lime arc, an orange arc and a cyan arc surround the circle.</desc>
  <rect x="0" y="0" width="800" height="450" fill="#FFFFFF"/>
  <circle cx="400" cy="225" r="70" fill="#02375B"/>
  <text x="400" y="222" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#FFFFFF">Responsible</text>
  <text x="400" y="244" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#FFFFFF">use</text>
  <path d="M 330 150 A 100 100 0 0 1 470 150" fill="none" stroke="#B1CF37" stroke-width="5"/>
  <path d="M 500 190 A 100 100 0 0 1 500 260" fill="none" stroke="#F78222" stroke-width="5"/>
  <path d="M 345 300 A 100 100 0 0 1 305 200" fill="none" stroke="#5DCAE7" stroke-width="5"/>
  <rect x="300" y="20" width="200" height="60" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="400" y="56" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#02375B">1. Human review</text>
  <rect x="580" y="195" width="190" height="60" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="675" y="231" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#02375B">2. Documentation</text>
  <rect x="300" y="370" width="200" height="60" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="400" y="406" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#02375B">3. Data protection</text>
  <rect x="30" y="195" width="190" height="60" rx="6" fill="#F1F5F8" stroke="#D8E2E9" stroke-width="2"/>
  <text x="125" y="231" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#02375B">4. Disclosure</text>
  <line x1="400" y1="80" x2="400" y2="130" stroke="#02375B" stroke-width="2"/>
  <line x1="580" y1="225" x2="520" y2="225" stroke="#02375B" stroke-width="2"/>
  <line x1="400" y1="370" x2="400" y2="320" stroke="#02375B" stroke-width="2"/>
  <line x1="220" y1="225" x2="280" y2="225" stroke="#02375B" stroke-width="2"/>
</svg>

**Worked example: A team agrees its rules**

*Training provider context.* A programme lead at a training provider has a team of four learning designers who use an approved AI assistant to draft quiz items for a micro-credential. The lead sets four team rules on one page. Review: a subject expert checks every item for accuracy and fit to the outcome. Documentation: the designer writes one line in the course file, with date, tool and reviewer. Data protection: no learner data goes into the tool. Disclosure: the course page notes that AI helped to draft items and that experts reviewed them. A year later, an external reviewer asks how AI was used, and the team answers from its records in minutes.

*Corporate academy context.* An academy lead at a company allows managers to use an approved AI assistant to draft feedback for participants in a leadership programme. The lead sets the rules: managers edit every draft and must be able to explain each comment, no health or private information goes into the tool, a note in the programme handbook explains that AI may help to draft feedback, and the academy keeps a short log. One manager notices that the tool wrote a comment about "culture fit" that reflected a stereotype. The manager deletes it and reports the pattern to the lead, who adds a line to the guidance.

**Practice activity: Write your team's one-page rules**

Using your notes from earlier modules, write a one-page set of rules for your own team. For each of the four rules, write one sentence that says what a team member does, and one sentence that says who checks. Add one line on what to do when something goes wrong. Share the draft with a colleague and ask them what is missing.

<details>
<summary>Facilitator notes</summary>

Run this as a 30-minute workshop. Teams draft the one-page rules, swap with another team, and the receiving team acts as a sceptical auditor: "How would I know you followed this?" Invite revisions. Close by asking each team to name the single rule they expect to be hardest to follow and why. Remind participants that organisational policy overrides the draft. Suggest sending the drafts to the person who owns your AI policy.

</details>

### Check your understanding

**Question 10.** Which description best fits real human review of AI output?

[( )] A manager clicks "approve" on each AI score within seconds.
[( )] A reviewer reads only the first sentence of each output.
[(X)] A competent person with the time and authority to change the result checks the output against sources before it affects anyone.
[( )] The AI tool reviews its own output and reports "no errors found".

[[?]] Review needs knowledge, time and authority.
****
Human review means a competent person who can question and change the result and takes responsibility for it. Fast approval clicks and self-checks by the same tool do not provide that.
****

**Question 11.** A learning designer used an approved AI assistant to draft badge descriptions, and a colleague reviewed them. Which record best supports accountability?

[( )] No record, because the final text is correct.
[(X)] A short note of the date, the tool, the purpose, what the reviewer checked and changed, and who approved the result.
[( )] A copy of every prompt typed by every staff member for the last five years.
[( )] A statement that AI was not used.

[[?]] Records should be proportionate and useful.
****
A short, proportionate record shows how AI was used and who took responsibility. It helps with audits, supports the AI literacy duty and lets colleagues repeat good practice.
****

**Question 12.** A college uses AI to give first-draft feedback on learners' practice tasks, and tutors edit it before sending. What does the disclosure rule suggest?

[( )] Say nothing, because tutors edit the feedback.
[(X)] Tell learners that AI helps to draft feedback and that tutors review it.
[( )] Tell only the inspectors.
[( )] Tell learners only if they complain.

[[?]] Disclosure builds trust and lets people question results.
****
Where AI use matters to the people affected, openness is a working rule. Learners can then understand how feedback was produced and who is responsible for it.
****

## Assessment and badge

### Final knowledge check

The final knowledge check has 10 questions. They cover all four learning outcomes and include scenario items set in a university, college or training provider and in a corporate academy or HR department.

**How it works.** Answer every question. Each has four options and exactly one correct answer. You see an explanation after you answer. You may review the modules and retake the check.

**Pass rule.** You pass with at least 7 of 10 questions correct, and at least one correct answer in each of the four learning outcomes.

**Badge evidence.** The evidence submitted for the badge "AI Literacy for Recognition Work (Knowledge, L1)" (alignment code ICSF-AIRC-L1-K) is the passed knowledge check, recorded by the Kursbibliothek.

**Rubric.**

| Learning outcome | Not yet | Meets the standard |
|---|---|---|
| 1. Explain how AI systems produce outputs and where they fail | Describes AI as a source of facts, or cannot name typical failures | Explains next-token prediction in plain terms and names failures such as fabrication, bias, out-of-date knowledge and inconsistency |
| 2. Identify uses of AI across the credential lifecycle | Cannot place uses in the lifecycle or confuses their risk | Identifies uses in content, assessment support, skills inference, verification and agents, and sorts them by risk |
| 3. Describe the AI literacy duty and the high-risk logic | Confuses the duty or the reasons for the high-risk status | States the literacy duty in plain terms and explains why education and employment decisions are treated as high-risk |
| 4. Apply basic rules for responsible use | Accepts AI output without checks or shares personal data freely | Chooses human review, documentation, data protection and disclosure in the right situations |

**Question 1.** A learning designer asks a general AI assistant for the typical learning hours of a named external certificate. It gives a precise number. How should the designer treat it?

[( )] As reliable, because it is precise.
[( )] As reliable, because the assistant has read all certificates.
[(X)] As a possible fabrication, to be checked against the certificate provider's published information.
[( )] As reliable if the assistant repeats it when asked again.

[[?]] Precision does not equal accuracy.
****
Generative systems produce plausible, often precise-looking statements that can be false. Repeating the same answer does not give independent evidence. Check an authoritative source.
****

**Question 2.** Which statement explains in plain terms how a large language model produces a paragraph of text?

[( )] It retrieves a stored paragraph that matches the question.
[( )] It runs a checklist of facts and writes only verified sentences.
[(X)] It predicts the next small piece of text many times in a row, based on patterns learned in training.
[( )] It copies the most popular web page on the topic.

[[?]] The core task is prediction.
****
An LLM generates text by repeatedly predicting likely next tokens. This explains why output can be fluent and still wrong.
****

**Question 3.** A hiring tool was trained on the profiles of past successful employees and now ranks candidates from non-traditional routes lower, although their ability is similar. Which failure mode does this show?

[( )] Fabrication.
[(X)] Bias reflecting patterns in the training data.
[( )] Out-of-date knowledge.
[( )] Inconsistency between two prompts.

[[?]] Look for the link between past data and unfair results.
****
A system trained on past decisions can reproduce earlier patterns and disadvantage groups that were under-represented or treated differently.
****

**Question 4.** A university registry wants an AI tool to speed up checks of uploaded certificates. Which design is most consistent with good practice?

[( )] The tool refuses any credential it flags, without staff involvement.
[( )] The tool replaces all technical checks of authenticity.
[(X)] The tool flags and routes cases, and a staff member examines the flagged credential and takes the decision.
[( )] The tool works without any record of what it did.

[[?]] Who should decide when a flag could lead to a refusal?
****
Verification affects a person's access to study or work. AI can help by flagging and routing, a person decides, and a record of the process is kept.
****

**Question 5.** A corporate academy's software infers employees' skills from their profiles. The HR department wants to use the output to choose who gets a role. Which statement is most accurate?

[( )] The inferred skills are verified evidence of competence.
[( )] The use is outside any regulation, because skills inference is new.
[(X)] The output is a statistical estimate, and using it for employment decisions may be high-risk, so it needs human decision-making, documentation and legal review.
[( )] The use is fine if managers do not tell employees about it.

[[?]] An inference is not evidence, and the use affects employment.
****
Skills inference gives statistical guesses. When the output feeds employment decisions, the use may fall under the high-risk category and calls for strong controls.
****

**Question 6.** What does the AI literacy duty in the EU AI Act ask of an organisation that deploys AI systems?

[( )] That it stops using AI until it receives a licence.
[( )] That each employee takes a named national exam.
[(X)] That it takes measures to ensure, as far as possible, a sufficient level of AI literacy among staff and others who use AI on its behalf, fitted to their role and the context.
[( )] That it publishes its AI policies in every EU language.

[[?]] The duty is proportionate and sits with the organisation.
****
The duty asks for measures that give staff and others an adequate level of AI literacy, adjusted to knowledge, experience and context of use.
****

**Question 7.** A college plans to use software that scores applicants and ranks them for limited places. Why is this use treated as high-risk under the EU AI Act?

[( )] Because it is expensive.
[( )] Because it uses a language model.
[(X)] Because it influences access to education, a decision that shapes a person's life chances and that the person may find hard to understand or challenge.
[( )] Because it was developed outside the EU.

[[?]] Focus on the effect on the applicant.
****
The Act lists AI used for access and admission to education among its high-risk areas, because of the impact on people and the difficulty of challenging automated results.
****

**Question 8.** A tutor at a training provider receives a detector report that says a learner's essay is probably AI-written. What is the most defensible next step?

[( )] Record misconduct, because the report is a score.
[( )] Ignore the report and never discuss AI with learners.
[(X)] Talk with the learner about the work, look at drafts and other evidence, and use the report at most as a prompt, because detection tools are not a reliable basis for decisions.
[( )] Run the essay through several detectors and choose the majority result.

[[?]] Detection tools make errors in both directions.
****
Detector scores cannot support a decision on their own. A conversation and other evidence are fairer, and assessment design can reduce the problem.
****

**Question 9.** An HR officer wants an AI assistant to summarise an employee file that contains health information about adjustments. Which action best protects privacy?

[( )] Paste the whole file into a free public assistant to save time.
[( )] Remove the employee's name only and paste everything else.
[(X)] Check with the data protection officer, use an approved tool, share only the fields needed, and check the summary against the source.
[( )] Skip any check, because the summary is only internal.

[[?]] Approved tool, minimum data, advice before starting.
****
Personal and health data need a legal basis, a clear purpose, minimal use and a secure, approved environment. The officer should also verify the summary against the source documents.
****

**Question 10.** A team uses an approved AI assistant to draft badge descriptions. Which set of practices best applies the four working rules?

[( )] Publish the drafts at once, keep no record and do not mention AI.
[( )] Have the tool review its own drafts, keep no record and tell nobody.
[( )] Let any staff member approve drafts quickly, record only the final text and mention AI only if asked.
[(X)] A subject expert reviews each draft, a short note records the tool, purpose and reviewer, no personal data goes into the tool, and the course page states that AI helped to draft the text.

[[?]] Match review, documentation, data protection and disclosure.
****
The correct option applies human review, documentation, data protection and disclosure together. The other options skip one or more of the rules.
****

## Sources and further reading

Status as of November 2026; check before publishing.

Only sources that are established official texts, standards bodies or framework owners are listed. Check each for the current version before you rely on it. Search for the title on the publisher's official website.

- **Regulation (EU) 2024/1689 of the European Parliament and of the Council of 13 June 2024 laying down harmonised rules on artificial intelligence (Artificial Intelligence Act).** Official text published in the Official Journal of the European Union and available through EUR-Lex.
- **Digital Omnibus on AI (AI Omnibus).** Proposal and legislative process of the European Commission, European Parliament and Council. Provisional agreement of 7 May 2026, with Annex III high-risk obligations applying from 2 December 2027 and Annex I product-embedded systems from 2 August 2028. Check the final published text. <!-- VERIFY: Confirm adoption, publication and final dates. -->
- **Regulation (EU) 2016/679 (General Data Protection Regulation).** Official text available through EUR-Lex.
- **European Commission, AI Office and AI Act pages.** Official guidance and Q and A material on the AI Act, including material on AI literacy. Check the current guidance on the European Commission website.
- **DigComp 3.0, the European Digital Competence Framework for Citizens.** Published by the European Commission. Relevant for earner-facing courses and alignment with citizen digital competence.
- **ICoBC Credentialing Skills Framework (ICSF).** Skill AIRC "Trustworthy AI in recognition", published by ICoBC (info@icobc.net).
- **ISO/IEC 42001, Artificial intelligence management system.** International standard published by ISO and IEC, relevant to organisational AI governance.
- **ISO/IEC 23894, Artificial intelligence guidance on risk management.** International standard published by ISO and IEC.
- **NIST AI Risk Management Framework (AI RMF 1.0).** Published by the National Institute of Standards and Technology, United States.
- **OECD AI Principles.** Published by the Organisation for Economic Co-operation and Development.
- **UNESCO, Recommendation on the Ethics of Artificial Intelligence.** Adopted by UNESCO member states in 2021.

This course gives general information for learning purposes. It is not legal advice, and completing it does not prove competence in any job role.
