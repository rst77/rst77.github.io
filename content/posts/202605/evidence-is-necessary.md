+++
authors = ["Renato Teixeira"]
title = "Evidence is necessary. In software engineering, it is also difficult"
date = "2026-05-04"
description = "A critical reflection on evidence-based software engineering and the responsibility of applying academic research to real-world technology decisions."
tags = [
    "LegacyModernization",
    "SoftwareArchitecture",
    "TechnologyDecisionMaking",
    "EvidenceBasedSoftwareEngineering",
    "SoftwareEngineering"
]
categories = [
    "Modernization",
]
series = ["Modernization"]
+++

![Conceito de Engenharia de Software Baseada em Evidências](/images/202605/ev.png)


In the previous article, I argued that software engineering has normalized important decisions made on grounds that are far too fragile. **Hype, market pressure, personal conviction, sophisticated language, and adoption anxiety** still occupy too much space in a field that likes to present itself as engineering. But there is an easy — and dangerous — answer to this criticism: “then just follow the evidence.” It would be great if it were that simple. It is not. And perhaps one of the greatest forms of maturity we can develop in software engineering is precisely to recognize this tension: **we need more evidence, but producing, interpreting, and applying evidence in software is much more difficult than we usually admit**.

This difficulty does not make evidence less important. **It makes our responsibility greater.** The idea of evidence-based software engineering comes from an analogy with evidence-based medicine. In medicine, a doctor does not decide only based on intuition: they must combine the best available evidence, their clinical experience, and the patient’s values and circumstances. This point is fundamental, because the doctor does not relate to evidence in an abstract way. They are facing a specific patient, with specific symptoms, a specific history, specific risks, and their own values. Evidence matters, but it needs to be interpreted in light of that patient’s reality.

When one doctor talks to another doctor, they can discuss studies, treatments, effects, risks, and protocols. But the clinical decision does not end in the conversation between specialists. It returns to the patient. In software, the situation is less clean. When we decide to adopt a technology, change an architecture, introduce a development method, or modernize a legacy system, there is rarely a single “patient” in front of us. **The patient is distributed:** it appears in the developers who will have to maintain the solution, in the operators who will respond to incidents, in the customers who will suffer downtime, in the business areas that depend on the system, in the executives who assume the risk, in the budgets that will be consumed, and in the future systems that will inherit the consequences of the decision.

In medicine, the doctor integrates evidence with the patient’s condition. In software engineering, we need to integrate evidence with an ecosystem of stakeholders, constraints, interests, dependencies, and risks. And that changes everything. Because if the patient is distributed, **the risk is also distributed. The cost is distributed. The responsibility is distributed. The consequences are distributed.** That is why, in software, it is not enough to ask: **“does this technique work?”** The real question is usually more uncomfortable: **“does it work for whom, in which context, with which team, under which constraints, for how long, and with which side effects?”** That is a much more difficult question — and a much more honest one.

## The first problem: software depends too much on human skill

One of the central difficulties of evidence in software engineering is that methods, practices, and tools rarely operate on their own. **They depend on people.** And people are not simple variables. Think about practices such as code review, TDD, pair programming, DevOps, microservices architecture, observability, refactoring, platform engineering, or incremental modernization. None of them “works” in the abstract. They work — or fail — when executed by specific people, with specific levels of experience, in specific teams, inside specific cultures, under specific pressures.

This means that the same practice can generate very different results in different contexts. A mature team can use microservices to increase autonomy, scalability, and speed of evolution. Another team can use microservices to create a distributed monolith, more expensive, more fragile, and harder to operate. **The practice is the same. The result is not.** The problem is not only in the technique. It is in the combination of technique, skill, context, and execution. This is where much of the technical discussion becomes naive: we ask whether a certain practice “is good” or “is bad,” as if we were evaluating a chemical substance with stable properties.

But software engineering practices do not behave that way. **A practice can be powerful in mature hands and dangerous in unprepared hands.** It can be appropriate in one organization and disastrous in another. It can solve a local problem and create a systemic problem. Human skill is not a detail; it is part of the phenomenon. And that makes evidence harder to produce. It also makes certainty more suspicious.

## The second problem: the lifecycle hides the consequences

The second major challenge is that, in software, many decisions only reveal their real consequences over time. An architecture may look elegant at the beginning. A framework may accelerate the first few months. A process may improve local indicators. A migration may produce immediate gains. A tool may impress in a proof of concept. But **software does not live in a proof of concept**. Software lives in maintenance, integration, incident response, requirement changes, team turnover, reduced budgets, audits, and continuous operation. That is where many decisions show their true cost.

This is a critical point: **a technique can produce a good immediate result and still worsen the final outcome of the system over the lifecycle**. The opposite can also happen: a decision may seem slower at the beginning, but better preserve the ability for future evolution. This distance between immediate effect and long-term consequence makes evidence in software especially difficult. How do we isolate the impact of an architectural decision made today on the reliability of a system two years from now? How do we know whether success came from the tool, the team, the context, the leadership, the investment, the operational maturity, or simply from a fortunate combination of factors?

In software, causality rarely appears clean. **It comes mixed.** And when the consequence finally appears, we often have already forgotten the chain of decisions that produced it. That is why so many organizations learn poorly from their own experience: they remember the result, but they do not understand the dynamics that led to it.

## The third problem: context is not accessory

There is an implicit phrase in many technical discussions that we should abandon: **“it worked there, so it should work here.”** That phrase is seductive. It is also dangerous. In software engineering, **context is not scenery; context is part of the decision**. A practice that worked in a big tech company with highly specialized teams, organizational autonomy, mature infrastructure, and a consolidated engineering culture may not work the same way in a traditional company with critical legacy systems, restricted budget, supplier dependency, and low tolerance for incidents.

A strategy that made sense in a native digital product may be inadequate for a financial institution with decades of integrations, regulatory constraints, and business knowledge distributed across old systems. A technology that shined in a laboratory may silently fail in operation. This does not mean we cannot learn from other contexts. We can and should. But **learning is not copying. Learning is translating.** And translation requires understanding.

The problem is that the industry often confuses evidence with a success story. A company presents a case. A vendor turns it into a narrative. An event turns it into a reference. A market turns it into a trend. And suddenly, a highly contextualized experience becomes a universal prescription. **This is not robust evidence. It is storytelling with good lighting.**

## The fourth problem: we share successes better than failures

There is an important cultural difference here. In medicine, there are more developed mechanisms for adverse events, side effects, and failures to feed the body of collective knowledge. The idea is not only to celebrate the treatment that worked, but also to learn from what produced unexpected consequences. In software, we often do the opposite: **we publish successes, celebrate successful migrations, show the final architecture, present the gains, and turn the journey into a talk.**

But the side effects rarely appear with the same clarity. Few organizations publicly say that a technology adoption increased operational complexity. Few explain that migrating to a new architecture created invisible dependencies. Few admit that a tool promised as an accelerator became another layer of lock-in. Few share that a “successful” modernization transferred cost to future maintenance. Not because people are necessarily dishonest, but because **the market rewards success narratives**. Failures are treated as competitive weakness, not as a contribution to collective learning.

And this impoverishes the available evidence. As a field, we learn too much from polished presentations and too little from the real side effects of our decisions. Perhaps software engineering still needs to learn one simple thing: **there is no collective maturity without shared memory of mistakes**.

## The fifth problem: evidence does not replace judgment

There is another risk: turning the defense of evidence into a new form of naivety. **Evidence is not an oracle.** It does not decide for us, it does not eliminate ambiguity, it does not remove trade-offs, it does not make context irrelevant, and it does not turn engineering into a recipe. An evidence-based decision is not an automatic decision; it is a more responsible decision. Evidence helps reduce arbitrariness, qualify the conversation, compare alternatives, expose uncertainties, and separate knowledge from preference. But we still need to judge.

And judging well requires accepting that some decisions will continue to be made under uncertainty. This is not a failure. It is the nature of the field. The difference is that there is an enormous distance between **deciding under uncertainty** and **deciding without foundation**. The first is inevitable. The second is negligence disguised as pragmatism.

## What this means for those starting in the field

For beginners in the field, this discussion may seem abstract. It is not. It appears every day in simple decisions: which framework to learn, which practice to adopt in the team, which architecture to defend, which tool to recommend, which trend to follow, which legacy system to criticize, which solution to consider modern. Perhaps the most important advice is this: **be suspicious of answers that are too fast for problems that are too contextual**.

When someone says that a practice is obviously better, ask: **better in which context?** When someone says that a technology is the future, ask: **the future of which problem?** When someone says that everyone is adopting it, ask: **with which results?** When someone says this is the market standard, ask: **based on what evidence?** These questions do not make you less practical. They make you less manipulable. And in an industry driven by strong narratives, this is an important technical competence.

## The difficulty of evidence is not an excuse

The fact that evidence is difficult in software does not justify deciding any way we want. On the contrary. Precisely because evidence is difficult, we should be **more careful, more explicit about our assumptions, more honest about our uncertainties, more critical of fads, more attentive to long-term effects, more willing to learn from failures, and more rigorous when generalizing success stories**.

The alternative to imperfect evidence should not be performative conviction. It should be a more humble, more structured, and more conscious decision-making practice. Perhaps maturity in software engineering is not about pretending that we know with certainty what works. Perhaps it is about **building better ways to ask, observe, compare, and decide — even when certainty remains partial**.

Because evidence in software is difficult. But important decisions without evidence are costly. And, in the end, perhaps this is the central point:

> **A mature engineering discipline is not one that eliminates uncertainty.**  
> **It is one that refuses to use uncertainty as an excuse to decide poorly.**

<br>

---

<br>
   
This article is based on *Evidence-Based Software Engineering*, by Barbara A. Kitchenham, Tore Dybå, and Magne Jørgensen, presented at ICSE 2004. The paper proposes that software engineering decisions should integrate the best available research evidence, practical experience, and human values, while also recognizing the specific difficulties of producing and applying evidence in software contexts.

Reference: https://www.simula.no/research/evidence-based-software-engineering