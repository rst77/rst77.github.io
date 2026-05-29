+++
authors = ["Renato Teixeira"]
title = "The risk of changing is visible. The risk of not changing is not always visible"
date = "2026-05-29"
description = "In legacy systems, the risk of change is visible. But the risk of remaining is often invisible. This asymmetry distorts decisions. Responsible modernization requires making both risks explicit and choosing consciously."
tags = [
    "LegacyModernization",
    "SoftwareArchitecture",
    "DigitalTransformation",
    "TechnicalDebt",
    "SoftwareEngineering"
]
categories = [
    "Modernization",
]
series = ["Modernization"]
+++

![image](/images/ml/part3.png)


*Series: The Legacy Roadmap — Part 3*

Read Part 1 [Legacy is not age. It is dependency](/posts/a1-legacy-is-not-age) and Part 2 [Legacy systems survive because they still matter](/posts/a2-survive-because-matter)

In the first two articles of this series, I began to build a thesis that I consider central to any serious conversation about legacy system modernization. First, I argued that **legacy is not age, it is dependency**. Then, I argued that **legacy systems survive because they still matter**. They remain because they sustain critical operations, preserve business rules, carry accumulated knowledge, and offer a form of predictability that, although imperfect, is often considered safer than the uncertainty of a replacement.

Now we need to enter a more uncomfortable part of the conversation: **risk**.

Modernizing is risky. That is true. But remaining is risky too. And perhaps one of the biggest problems in legacy environments is precisely the difference in visibility between these two risks. The risk of change appears clearly: budget, schedule, operational impact, data migration, downtime, regressions, integration failures, user resistance, political pressure, and the possibility of public failure. The risk of remaining, on the other hand, is usually more silent. It accumulates in absent documentation, tacit knowledge, dependency on key people, progressive obsolescence, increased complexity, invisible costs, operational fragility, and gradual loss of the ability to evolve.

The organization sees the risk of touching the system better than the risk of staying still. And this asymmetry distorts decisions.

## The false neutrality of not changing

There is a very common belief in corporate environments: if we do not touch it, we do not take risks. This belief seems prudent, but it is incomplete. In legacy systems, **not changing is also a form of decision**. It may even be a legitimate decision. There are moments when maintaining, stabilizing, encapsulating, or postponing a structural intervention is the most responsible choice. The problem begins when permanence is treated as neutrality, and not as a decision with costs, risks, and consequences.

When an organization decides not to modernize, it does not freeze the system in time. The environment continues to change. The business changes. Regulation changes. Volumes change. User expectations change. Integrations change. Vendors change. The skills available in the market change. Internal teams change. The system may continue executing the same code, but the world around it does not remain the same.

This is one of the great traps of legacy: apparent stability can hide real deterioration. A system may continue working every day and, even so, be becoming less sustainable every month. The absence of crisis does not mean the absence of risk. Many times, it only means that the organization has still managed to absorb the risk through workarounds, manual effort, operational heroism, and dependency on experienced people.

The problem is that this type of stability charges interest.

## The risk of change has an owner. The risk of permanence spreads.

A modernization project usually has a name, budget, sponsor, schedule, indicators, and owners. If it fails, someone will be charged. If it is delayed, someone will have to explain. If it costs more than expected, someone will have to justify it. The risk of change, therefore, is visible and personalizable. It appears in committees, presentations, business cases, executive meetings, and mitigation plans.

The risk of permanence is different. It rarely has a single owner. It spreads across the organization. It appears in small productivity losses, in difficult integrations, in recurring incidents, in rework, in dependency on specialists, in delays of new initiatives, in limitations that the business has already learned to accept, in opportunities that are no longer explored because “the system does not allow it.”

This difference changes everything. Deciding to change exposes the decision-maker. Deciding not to change protects the decision-maker in the short term, because the cost of inaction is usually diffuse, gradual, and shared. Modernization that fails becomes an event. Deterioration that advances becomes the landscape.

And the landscape rarely scares enough to generate a decision.

## Familiarity is not the same as safety

In legacy systems, what is familiar usually feels safe. The team knows where the problems are. The operation knows the critical times. The business knows which processes require care. Users have already learned the deviations. The support team knows the symptoms. Leadership knows which people to call when something important breaks.

This familiarity has value. We should not discard it. It represents accumulated learning, operational memory, and reaction capability. But familiarity can also anesthetize. The longer the organization lives with a limitation, the greater the chance of treating it as a natural part of the environment. What began as an exception becomes routine. What was a workaround becomes process. What was risk becomes habit. What was discomfort becomes culture.

This is where the decision starts to become dangerous. The system does not seem safe because it was objectively assessed as safe. It seems safe because the organization has learned to live with its problems. This is not the same thing.

The more honest question is not “does this system still work?”. The question is: **how much invisible effort is necessary for it to keep working?**

## The fear of change can be rational

It is important to avoid a common caricature: treating every resistance to modernization as ignorance, backwardness, or lack of vision. In many cases, the fear of change is rational. Critical legacy systems are not laboratory toys. They sustain revenue, service, logistics, credit, billing, regulation, production, healthcare, telecommunications, retail, financial services, and operations that cannot simply stop so that a prettier architecture can be implemented.

Those who carry operational responsibility know that a poorly conducted modernization can cause real damage. It can interrupt critical processes, break undocumented business rules, expose data fragilities, generate downtime, destroy tacit knowledge, and produce a new solution that, although technically more modern, does not deliver the same operational reliability as the previous system.

So, yes: changing can be dangerous. The point is not to deny this risk. The point is to stop using this risk as an automatic argument to avoid the conversation about the opposite risk. The fear of change can be rational; the refusal to measure the risk of permanence is not.

## The risk of permanence rarely explodes all at once

The risk of not changing usually manifests progressively. First, an update stops being trivial. Then, an integration starts requiring more effort than it should. Next, a business rule becomes difficult to locate. Then, a key professional leaves the company. Later, the vendor reduces support. Infrastructure becomes more expensive. Security becomes harder to guarantee. The time to deliver new capabilities increases. The business starts avoiding certain initiatives because it knows the system cannot keep up.

None of this, in isolation, seems enough to justify a major decision. Each point can be treated as an exception. Each problem can receive a workaround. Each limitation can be explained as a normal cost of operation. And this is how degradation becomes normalized: not through an immediate collapse, but through a sequence of small concessions that make the system increasingly expensive, more fragile, and less understood.

When a serious failure, a security incident, regulatory pressure, or an unavoidable scaling limitation finally occurs, the organization usually says that “the problem appeared.” But, in many cases, the problem did not appear at that moment. It only became impossible to continue ignoring.

## The question that should be on the table

Every modernization decision should begin with an explicit comparison: **what is the risk of changing and what is the risk of remaining as we are?**

This question seems simple, but it changes the quality of the discussion. It forces the organization to abandon the false idea that there is risk only in transformation. It also prevents modernization from being sold as an obvious solution without losses. Both sides need to be analyzed honestly.

The risk of change includes operational interruption, migration failure, loss of business rules, cost overrun, delay, cultural resistance, functional regression, and technical irreversibility. The risk of permanence includes obsolescence, knowledge loss, dependency on individuals, increased complexity, integration difficulty, vulnerability, productivity decline, strategic limitation, and future inability to respond.

The mature decision is not to choose the path without risk. That path rarely exists. The mature decision is to make explicit which risk the organization accepts carrying, which risk it needs to reduce, which risk is temporarily tolerable, and which risk has become unacceptable.

## Risk is also socially constructed

One of the most interesting findings of my research was observing that risk does not appear only as objective data. It is also socially constructed within the organization. Past experiences, failed projects, operational traumas, internal narratives, the authority of senior professionals, and collective memories influence how change is perceived.

If a previous modernization failed, the next proposal is already born contaminated by that memory. If a migration generated financial loss, any new initiative will be read with more distrust. If the organization learned that “when you touch it, it breaks,” this phrase starts to function as a kind of informal policy. If the operation depends on people who have known the system for decades, those people’s opinion starts to carry enormous decision-making weight, even when it is not structured as formal evidence.

This is not necessarily bad. Experience matters. Memory matters. Prudence matters. But when these narratives are not made explicit, they stop being learning and start functioning as an invisible blockage. The organization believes it is deciding technically, when in fact it may only be reacting to past experiences that were never rigorously analyzed.

## When risk becomes an excuse

Every organization needs to be prudent. The problem is when prudence becomes sophisticated language for inertia. In legacy environments, this happens frequently. The discourse sounds responsible: “this is not the moment,” “the risk is high,” “the business cannot stop,” “we need to evaluate better,” “the next platform will be more mature,” “let’s wait for the next budget cycle,” “we have other priorities.”

Some of these justifications may be true. The point is that, repeated for long enough, they stop being criteria and become mechanisms of postponement. Modernization is not rejected. It is always moved to later. And later, in legacy systems, usually arrives more expensive.

The necessary question is: are we really reducing risk or only postponing the moment when we will have to face it? Are we gaining maturity or only buying time? Are we preserving stability or turning fragility into routine?

These questions are uncomfortable because they take the decision out of the comfortable territory of intention and place it in the harder territory of responsibility.

## Modernization as a conscious choice of risk

The first principle of the Legacy Roadmap is the **conscious choice of risk**. Before discussing solution, tool, architecture, or vendor, the organization needs to make explicit what type of risk it is willing to assume and what type of risk it must avoid at all costs.

This change of order is important. In many initiatives, the discussion begins with technology and only then tries to justify the risk. The path should be the opposite. First, understand what is at stake. Then, identify dependencies. Next, make risks explicit. Only then discuss technical strategy.

If the organization does not know which risk it accepts, any solution will seem good or bad depending on the narrative of the moment. The same architecture can be seen as bold or reckless; the same migration can be seen as necessary or dangerous; the same permanence can be seen as stability or negligence. Without explicit criteria, the decision becomes hostage to preference, authority, pressure, and fear.

Choosing risk does not mean desiring risk. It means stopping pretending that it does not exist.

## The role of internal evidence

A practical way to reduce this asymmetry is to produce internal evidence. Not all evidence needs to come from an academic article or an external study. The organization can and should build evidence about its own reality: recurring incidents, maintenance costs, delivery time, frequency of regressions, dependency on key people, integration effort, documentation failures, impact of downtime, onboarding time, scaling limitations, and past architectural decisions.

This evidence does not eliminate uncertainty, but it improves the conversation. It allows us to move away from generic statements such as “it is risky to change” or “we need to modernize” and advance toward more useful questions: which risk is measurable? Which risk is perceived? Which risk is growing? Which risk is being normalized? What would change our decision? What signal would indicate that permanence has stopped being acceptable?

Without this kind of reflection, the organization can fall into two extremes: modernizing because of technological anxiety or remaining because of cognitive comfort. Both are bad. The first posture replaces analysis with enthusiasm. The second replaces prudence with attachment.

## Closing

The risk of changing is visible. The risk of not changing is not always visible. This is the thesis of this third article. In legacy systems, change is frightening because it concentrates responsibility, exposes costs, and creates the possibility of explicit failure. Permanence, on the other hand, usually seems safer because its costs are diluted, its signals are normalized, and its consequences accumulate slowly.

Maturity is not in always choosing to change, nor in always choosing to preserve. It is in abandoning the illusion that there is an option without risk. Responsible modernization begins when the organization can put the risk of transformation and the risk of continuity on the same table, treating both with evidence, context, and responsibility.

In the next article of the series, I will deepen one of the reasons why this comparison is so difficult: **when software becomes part of the organization**.

Because, in many cases, modernizing does not mean only changing a system. It means touching the way the organization itself has learned to function.