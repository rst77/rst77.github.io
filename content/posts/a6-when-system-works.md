+++
authors = ["Renato Teixeira"]
title = " When the system only works because someone still remembers"
date = "2026-06-19"
description = "Postponing modernization may reduce short-term risk, but it often accumulates complexity, dependency, and future fragility."
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

![image](/images/ml/part6.jpg)

*Series: The Legacy Roadmap — Part 6*

Read Part 1 [Legacy is not age. It is dependency](/posts/a1-legacy-is-not-age), Part 2 [Legacy systems survive because they still matter](/posts/a2-survive-because-matter), Part 3 [The risk of changing is visible. The risk of not changing is not always visible](/posts/a3-the-risk-of-changing-is-visible) and Part 4 [When software becomes part of the organization](/posts/a4-when-software-becomes-organization).

In the previous articles of this series, I addressed some ideas that help change the way we look at legacy systems. First, I discussed that **legacy is not age, it is dependency**. Then, I argued that **legacy systems survive because they still matter**. Next, I addressed the asymmetry between the risk of changing and the risk of remaining. In the fourth article, I deepened the concept of entanglement: the moment when software stops being only an application and starts to participate in the way the organization itself functions.

Now we need to address a direct consequence of this scenario: modernization is often not explicitly rejected. It is simply postponed. There is not necessarily a formal decision saying “we will not modernize.” What often exists is a sequence of reasonable, justifiable, and even technically defensible postponements in the short term. An adjustment here, an integration there, a new layer around the system, an emergency fix, an operational exception, a postponement to the next budget cycle. Little by little, the organization does not decide to maintain or modernize. It simply continues.

This is the central point of this article: **postponed modernization is also a decision**. Even when no one records it that way. Even when there are no meeting minutes. Even when there is no formal sponsor of permanence. Even when everyone agrees, in theory, that the system needs to evolve. To postpone is to decide to carry the risks, costs, and limitations of the current state for longer.

## Postponement rarely seems irrational at first

It is important to begin carefully: not every postponement is irresponsible. In critical legacy systems, postponing an intervention can be a legitimate choice. There are moments when operational risk is too high, available knowledge is insufficient, the budget does not support a safe transition, or the business has no window to absorb a structural change. In these cases, temporarily maintaining the system, stabilizing the environment, reducing immediate risks, and better preparing the diagnosis can be a mature decision.

The problem begins when postponement stops being a temporary strategy and becomes a permanent mode of management. The organization starts treating each cycle of postponement as an exception, but the sum of these exceptions becomes a pattern. There is always a reason to wait a little longer. The next quarter will be better. The next platform will be more mature. The next leadership will have more appetite. The next budget will allow a more structured approach. The next incident may finally justify the change. Meanwhile, the system continues to accumulate complexity, dependency, and opacity.

This is the danger of decision postponement: it rarely presents itself as negligence. It presents itself as prudence. And, many times, it starts as prudence indeed. But prudence without periodic review becomes inertia. And inertia, in legacy systems, usually charges dearly.

## The comfortable language of permanence

Permanence rarely defends itself with a brutal phrase like “we do not want to change.” It usually appears in more acceptable expressions: “this is not the moment,” “the system still serves us,” “the risk is high,” “we have other priorities,” “the business cannot stop,” “we need to evaluate better,” “let’s wait for the next version,” “we do not have enough people,” “this goes into the next cycle,” “if it is not broken, do not touch it.”

Some of these phrases may be true. The system may, in fact, still serve the business. The risk may, in fact, be high. The business may, in fact, have no window for a structural change. The point is not to ridicule these justifications. The point is to ask what happens when they are repeated for years. At some point, the language of prudence begins to function as a mechanism for protecting inaction.

This language is comfortable because it avoids immediate conflict. It does not require the organization to face the most difficult question: **what is the cost of continuing to postpone?** It is easier to discuss the risk of a new project than to calculate the silent erosion of the ability to evolve. It is easier to point out the danger of a migration than to assume the accumulated cost of fixes, exceptions, dependency on specialists, and limitations that the business has already learned to work around.

Postponement feeds on this asymmetry: the risk of change needs to be justified; the risk of permanence is usually tolerated.

## Palliative solutions are useful until they become architecture

Every real system needs adjustments. No organization operates only through major structural decisions. Emergency corrections, integration layers, auxiliary scripts, manual routines, encapsulations, APIs around the legacy system, and incremental adaptations are part of the normal life of corporate systems. The problem is not in the palliative solution itself. The problem is in the moment when the palliative solution stops being a bridge and becomes a foundation.

A layer created to gain time can be useful. Ten layers created to avoid a decision can become a new accidental architecture. A temporary script can solve an urgency. A set of temporary scripts can become a parallel operation without governance. An integration created to reduce impact can preserve continuity. A tangle of integrations can turn any future change into an archaeological investigation.

This is a common pattern in legacy environments: the organization does not modernize the core, but creates successive borders to work around its limitations. The original system remains at the center, while new capabilities are coupled around it. This strategy can be intelligent when used with intention, traceability, and exit criteria. But it can become dangerous when it only stacks complexity without reducing structural dependency.

In other words: **the palliative solution is acceptable when it buys time to understand and decide. It becomes a problem when it buys time to avoid deciding.**

## The decision without an owner

A modernization project usually has an owner. It has a sponsor, budget, plan, schedule, committee, metrics, and accountability. If it fails, someone answers for it. Permanence, on the other hand, often has no clear owner. The system continues as it is because it has always been that way. The decision to postpone is distributed among competing priorities, budget constraints, operational fear, lack of consensus, and comfort with the known.

This absence of ownership is one of the reasons why postponement persists. No one presents themselves as responsible for keeping the organization tied to the legacy system. But, in practice, each cycle without a decision reinforces this condition. Responsibility is diluted, while risk accumulates. The cost of a failed modernization is visible and attributable. The cost of prolonged permanence is diffuse and, for that reason, politically easier to absorb.

This creates an important distortion. The manager who approves a modernization assumes an explicit risk. The manager who postpones may seem cautious. But postponement is also a bet: a bet that the system will continue to support the business, that key people will remain available, that vendors will continue to support the technology, that security will remain manageable, that complexity will not cross a critical threshold, and that the business will continue to accept its restrictions.

This bet should be treated as a strategic decision. Many times, it is treated only as the absence of a decision.

## When stability becomes anesthesia

Legacy systems often offer a form of stability. Not necessarily because they are technically healthy, but because they are known. The organization knows where the problems are. It knows which routines require care. It knows which times are sensitive. It knows which people to call. It knows which error messages to ignore and which ones to treat as a serious signal. It knows how to operate within the system’s limitations.

This perceived stability has value. But it can also anesthetize. When the organization lives with a problem for too long, it stops perceiving it as a problem and starts treating it as a characteristic of the environment. Slowness becomes normal. Manual dependency becomes procedure. Rework becomes routine. Integration limitation becomes a business premise. Lack of documentation becomes something that “the team knows.” Difficulty changing becomes justification for not changing.

This process is dangerous because it turns fragility into landscape. And what becomes landscape rarely mobilizes decision. Modernization starts to depend not on a strategic reading, but on a traumatic event: a serious failure, a security incident, regulatory pressure, the departure of a specialist, vendor discontinuity, or a scaling limitation that is impossible to work around.

When the organization only modernizes after pain, the decision is no longer fully strategic. It is reactive.

## Postponement has interest

Postponing modernization can reduce risk in the short term, but it is rarely free. Each postponement tends to carry interest. Interest in complexity. Interest in knowledge loss. Interest in maintenance cost. Interest in dependency on specific people. Interest in hiring difficulty. Interest in vulnerabilities. Interest in architectural rigidity. Interest in opportunities that are no longer explored because the system cannot keep up.

This interest does not always appear in the budget as a clear line item. It appears in delayed initiatives, excessive effort for small changes, increased incidents, rework, insecurity in deployments, long onboarding periods, difficulty testing, dependency on fragile environments, and the need to always involve the same people for any decision. Because it is distributed, it seems smaller than it is. But, over time, it may exceed the cost of the modernization that was postponed.

The problem is that organizations often calculate the cost of change explicitly, but treat the cost of permanence as a normal operational cost. This accounting and mental difference favors inertia. Modernizing seems expensive because the investment appears concentrated. Remaining seems cheaper because the cost dissolves into daily operation.

But diluted cost is not nonexistent cost.

## The fear of past failure

One of the most relevant findings of the research is that decisions about modernization are strongly influenced by organizational memories. Previous projects that failed, wasted investments, traumatic migrations, and unfulfilled technological promises leave marks. These marks shape the perception of risk and make new initiatives harder to approve.

This is understandable. Organizations learn from previous experiences. The problem is when experience becomes unprocessed trauma. Instead of generating better criteria, it generates blockage. Instead of producing internal evidence, it produces defensive phrases. Instead of helping to decide better, it starts to justify the repetition of the same state.

In this context, the important question is not only “why are we afraid to modernize?”. The more useful question is: **what exactly did we learn from previous attempts?** Was the problem the chosen technology? The scope? The lack of understanding of the legacy system? The absence of sponsorship? The underestimation of complexity? The loss of business rules? The migration strategy? Governance? The relationship with vendors? The lack of evidence?

Without this analysis, the past becomes authority. And the authority of the past can block future decisions even when the context has changed.

## Postponing responsibly is different from postponing through inertia

There is a relevant difference between responsible postponement and inertial postponement. Responsible postponement is explicit, temporary, and conditioned. It declares why modernization will not be done now, which risks are being accepted, which preparatory actions will be executed, which signals will be monitored, and at what moment the decision will be reevaluated. It buys time, but uses that time to reduce uncertainty.

Inertial postponement is different. It does not define clear criteria. It does not create learning artifacts. It does not recover knowledge. It does not measure deterioration. It does not monitor risks. It does not establish triggers. It only pushes the decision forward while maintaining the narrative that the moment has not yet arrived.

This distinction is practical. An organization may consciously decide to postpone a modernization for twelve months, as long as it uses this period to map dependencies, recover business rules, reduce operational risks, record architectural decisions, train people, improve observability, stabilize integrations, and build a realistic transition plan. This is governance.

What does not work is postponing for twelve months and reaching the end of the period knowing exactly the same thing that was known before.

## What should accompany a decision to postpone

If the organization decides to postpone a modernization, this decision should come with some minimum commitments. The first is to make explicit the accepted risk. Postponing does not eliminate risk; it only chooses to carry it for longer. The second is to define reevaluation signals: what events would indicate that permanence has stopped being acceptable? An incident? A cost? The loss of a key professional? A regulatory limitation? An inability to scale?

The third commitment is to produce internal evidence. Recording incidents, dependencies, costs, fragilities, past decisions, coupling points, and documentation gaps helps transform perception into information. The fourth is to reduce dependency on tacit knowledge. If modernization will not be done now, at least the understanding of the system needs to improve. The fifth is to limit the creation of new palliative solutions without traceability. Each workaround must have a justification, an owner, and a review criterion.

These commitments do not make postponement ideal. But they make postponement more honest. The issue is not to prohibit postponement. The issue is to prevent it from continuing to happen without visible cost, without ownership, and without learning.

## The modernization that begins before the project

An important idea is that modernization does not begin only when the formal project is approved. It can begin before that, through the preparation of the decision. Mapping dependencies is already part of modernization. Recovering knowledge is already part of modernization. Making risks explicit is already part of modernization. Documenting decisions is already part of modernization. Improving observability is already part of modernization. Reducing peripheral couplings is already part of modernization.

This view is useful because it removes the organization from the false choice between “doing a large project now” or “doing nothing.” There is an intermediate space: preparing the ground. This space is particularly important in legacy systems because many modernizations fail not because of lack of technology, but because of lack of understanding. The organization enters the project without knowing enough about the system it intends to transform.

If structural modernization still cannot happen, the organization can at least begin to reduce ignorance about its own legacy. And that already changes the quality of the future decision.

## Closing

Postponed modernization is also a decision. This is the thesis of this fifth article. Postponing can be prudent when there is clarity about risks, criteria, and preparatory actions. But it can also be just an elegant way of avoiding a difficult decision. In legacy systems, the boundary between prudence and inertia is not always obvious. That is why it needs to be made explicit.

Postponement becomes dangerous when it preserves stability in the short term at the cost of increasing fragility in the long term. When it buys time without producing understanding. When it reduces immediate political exposure, but increases future technical dependency. When it turns palliative solutions into architecture and limitations into culture.

The mature decision is not to modernize at any cost. It is also not to preserve indefinitely what still works. The mature decision is to know why we are postponing, which risks we are accepting, what we are learning while we postpone, and what signal will make us change position.

In the next article of the series, I will address one of the most critical reasons why postponing becomes so common: **when the system only works because someone still remembers**.

Because, in many legacy environments, the risk is not only in the software. It is in the fact that an essential part of the system lives in the memory of a few people.