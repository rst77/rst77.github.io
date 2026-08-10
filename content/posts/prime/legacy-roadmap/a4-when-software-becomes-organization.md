+++
authors = ["Renato Teixeira"]
title = "When software becomes part of the organization"
date = "2026-06-05"
description = "Part 4 of The Legacy Roadmap series: examining how legacy software becomes embedded in organizational routines and shapes business processes."
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

![Quando o software vira parte da organização](/images/ml/part4.jpg)


*Series: The Legacy Roadmap — Part 4*

Read Part 1 [Legacy is not age. It is dependency](/posts/a1-legacy-is-not-age), Part 2 [Legacy systems survive because they still matter](/posts/a2-survive-because-matter) and Part 3 [The risk of changing is visible. The risk of not changing is not always visible](/posts/a3-the-risk-of-changing-is-visible)

In the first three articles of this series, I built a line of reasoning about legacy systems that moves away from the most superficial reading of the topic. First, I argued that **legacy is not age, it is dependency**. Then, I argued that **legacy systems survive because they still matter**. Next, I addressed the asymmetry between two risks that are rarely discussed with the same honesty: **the risk of changing, which is usually visible, and the risk of not changing, which often accumulates silently**.

Now we need to move into an even more difficult point: there are situations in which the legacy system stops being just an application used by the organization and becomes part of the very way the organization works. It does not merely execute processes; it shapes processes. It does not merely store rules; it defines how certain rules are interpreted. It does not merely support business areas; it conditions the way these areas work, decide, prioritize, and resolve exceptions. When this happens, modernization stops being only a technical intervention. It becomes an organizational intervention.

This is the topic of this article: **when software becomes part of the organization**.

## It is not just code coupling

In software engineering, we are used to talking about coupling. Coupling between modules, services, databases, integrations, layers, components, and APIs. This vocabulary is necessary, but insufficient when we talk about deeply embedded legacy systems. In many cases, the problem is not only in technical coupling. It is in the coupling between the system and the operation. Between the code and the process. Between the screen and the routine. Between the business exception and the person who knows how to resolve it. Between the architecture and the history of the organization.

This type of coupling does not fully appear in diagrams. It appears in phrases such as: “this has always been done this way,” “do not touch that routine,” “this rule is not documented, but the team knows,” “this report is bad, but finance depends on it,” “this integration is fragile, but everyone adapted,” “if this process stops, no one knows how to do it manually.” These are signs that the system has stopped being just software and has started to participate in the real operating structure of the company.

The problem is that this embeddedness is usually invisible to those who look only from the outside. An architect may observe an old application and see a poorly designed architecture. A manager may see high maintenance cost. A vendor may see a migration opportunity. An engineering team may see technical debt. Everyone may be right, and still be seeing only one part of the phenomenon. What may not be visible is that the application also carries routine, culture, exception, memory, authority, and operational dependency.

## The system as the mold of the process

In the ideal world, software should support well-defined business processes. First we would understand the process, then we would build the system to support it. In practice, after years or decades, this relationship is often reversed. The process begins to adapt to the system. The organization learns to operate within the limitations of the application. What the system allows becomes the official flow. What the system does not allow becomes a workaround. What was temporary becomes routine. What was an exception becomes part of the operational culture.

This inversion is one of the strongest marks of embedded legacy systems. The system is no longer just a representation of the business; it becomes one of the elements that defines the business itself. Entire areas may organize their way of working around screens, batches, schedules, integrations, reports, mandatory fields, performance limitations, and historical behaviors of the application. Over time, the company may no longer even remember whether a process exists because it makes sense for the business or because, at some point, it was the only way to operate within the system’s constraints.

This point is dangerous because a poorly understood modernization may try to “improve” a system without realizing that it is touching a process the entire organization has learned to follow. Changing a screen may change a routine. Changing a rule may break a commercial exception. Changing an integration may affect a relationship with a partner. Changing a processing window may affect accounting closing, service, billing, or compliance. In embedded systems, small technical changes can have large organizational consequences.

That is why, when someone says that “it is just replacing the system,” it is worth asking: replacing the system, or also replacing the way the organization has learned to function?

## The organization also becomes part of the system

Embeddedness does not happen in only one direction. The system begins to shape the organization, but the organization also begins to complete the system. People create manual procedures to compensate for limitations. Teams build auxiliary spreadsheets. Business areas maintain parallel lists. Operators memorize sequences of steps. Support teams learn symptoms. Analysts know shortcuts. Managers know which professionals need to be called when something deviates from the pattern. Little by little, human operation begins to function as an informal extension of the application.

This is one of the reasons why some systems seem more stable than they really are. The system works, but it works because there is a human network around it absorbing its failures, completing its gaps, and translating its behaviors. The software does not deliver alone the entire operation it appears to deliver. Part of the operation is outside it, distributed across people, habits, meetings, parallel controls, spreadsheets, scripts, and tacit knowledge.

This arrangement can be efficient for some time, but it has a cost. It increases dependency on specific people, reduces the traceability of decisions, makes onboarding harder, creates technical succession risks, and makes modernization more uncertain. When the organization does not know where the system ends and where the human workaround begins, any attempt at change becomes a bet.

The question is no longer only “how does the software work?” but rather: **how does the organization make this software work every day?**

## The knowledge that is not in the code

In legacy environments, an important part of the knowledge is not in the documentation, nor in the diagrams, nor in the repositories, nor even in the code in a clearly understandable way. It is in practice. It is in the memory of people who have followed the system for years. It is in decisions that were made under pressure and were never recorded. It is in exceptions that arose because of an important customer, a regulatory rule, an infrastructure limitation, or an operational urgency. It is in old conversations that became permanent behavior.

This knowledge is dangerous because it seems available while people are there. The organization gets used to the presence of specialists who know where to touch, where not to touch, which routine to restart, which integration to observe, which table to consult, which behavior to ignore, and which problem to treat as a serious signal. But when these people leave, move to another area, retire, or simply stop being available, part of the system disappears with them.

The modernization of embedded systems, therefore, cannot begin only with code analysis. It needs to begin with knowledge recovery. Interviews, observation of the operation, incident analysis, log reading, flow mapping, software archaeology, integration review, reconstruction of business rules, and recording of architectural decisions are not bureaucracy. They are risk reduction mechanisms.

Without this, the organization may end up modernizing the visible part of the system and losing precisely what made it essential.

## Legacy as an organizational fossil

Every corporate system carries marks of the time in which it was created. It carries decision structures, organizational divisions, business priorities, technical constraints, governance models, and commitments that made sense at a given moment. Over the years, the organization changes. Departments are reorganized. Products are replaced. Markets evolve. People leave. Strategies change. But the system often preserves traces of the old organization.

In this sense, legacy systems can function as organizational fossils. They preserve, in their architecture and in their rules, traces of how the company thought, decided, and operated in other times. Some of these marks remain useful. Others become rigidity. The problem is that we do not always know how to distinguish one from the other without investigating.

That is why modernization can be so uncomfortable. It does not only reveal technical problems. It reveals old decisions, forgotten dependencies, institutionalized shortcuts, rules that no one knows how to justify, processes that have lost meaning, and conflicts that were hidden inside the system. In some cases, modernizing means opening a technical black box. In others, it means opening an organizational black box.

And not every organization is prepared to discover how much of itself has been deposited inside the software.

## Why diagrams are not enough

Diagrams are important. Reference architectures are important. Technical inventories are important. But, in embedded systems, they rarely tell the whole story. A diagram can show integrations, components, databases, and main flows. It may even indicate relevant technical dependencies. But it will hardly show the fear of the operation, the informal authority of a specialist, the manual routine that closes a gap, the spreadsheet that corrects information, the tacit agreement between areas, or the business exception that no one documented.

The technical map needs to be complemented by a sociotechnical map. It is not enough to ask which systems connect. It is necessary to ask which people depend on them, which processes were shaped by them, which decisions are made from them, which risks are tolerated because of them, and which organizational behaviors emerged to work around their limitations.

This view does not replace engineering. It improves engineering. Because a modernized architecture that ignores the organization tends to fail when it meets the real operation. The design may be correct on paper and still be unviable in context. The system may be technically better and operationally worse. The solution may be modern and, at the same time, inadequate.

Modernization does not fail only because the chosen technology was bad. Many times, it fails because the organization modernized the technical artifact without understanding the social system that kept it alive.

## The mistake of treating embeddedness as resistance

When an organization shows caution toward modernization, it is common for this to be interpreted as resistance to change. Sometimes it is. But not always. In many cases, caution is a symptom of embeddedness. People know, even if they cannot formally explain it, that the system is connected to more things than appear in the documents. They know that there are hidden rules, fragile dependencies, parallel routines, and indirect impacts. They know that the change may touch places no one has mapped.

Calling this simply resistance may be a comfortable way of ignoring important signals. The operation may be communicating risk. The technical team may be communicating lack of understanding. The business may be communicating dependency. The manager may be communicating a legitimate fear of rupture. Not every objection is backwardness. Some objections are poorly structured evidence.

This does not mean the organization should obey every fear. It means it needs to investigate what the fear is trying to protect. Sometimes, it only protects comfort. But, in legacy systems, it often protects knowledge that has not yet been made explicit.

Maturity lies in transforming diffuse resistance into useful information.

## Understand before touching

The main practical consequence of embeddedness is simple: the greater the coupling between system, processes, and people, the greater the prior investment in understanding must be. This may seem obvious, but it is frequently ignored. Pressures related to deadlines, budget, transformation narratives, or technological enthusiasm lead organizations to start changes before understanding what is really at stake.

This is an expensive mistake. Embedded systems do not tolerate rushed interventions well. They require diagnosis, dependency mapping, reconstruction of rules, risk analysis, participation from the operation, observation of real flows, and explicit articulation of tacit knowledge. Modernization can still be incremental, technical, pragmatic, and value-oriented. But it needs to begin with humility: admitting that the system may know more about the organization than the organization itself can explain.

Understanding before touching is not slowness. It is risk reduction. It is the difference between modernizing consciously and merely pushing a change into a structure that no one fully understands.

## Software as part of continuity

When software becomes part of the organization, it also becomes part of continuity. It sustains not only transactions, but routines. Not only data, but interpretations. Not only processes, but operational trust. That is why any change needs to consider what must be preserved during transformation. Continuity is not an excuse for immobility, but it also cannot be treated as a detail.

The mature question is not “how do we remove this system?”. The question is: **how do we evolve what it sustains without destroying what still needs to keep working?** This difference changes everything. Modernization stops being a war against the past and becomes a responsible transition process between what was built, what still matters, and what needs to change.

This point is especially important because many transformation discourses treat legacy as an enemy. But when the system is deeply embedded, attacking legacy without understanding its function may mean attacking the organization’s very ability to operate. Criticism of legacy needs to exist, but it must be accompanied by understanding. Without this, modernization becomes performative rupture.

## Closing

When software becomes part of the organization, modernization stops being only a technical decision. It becomes a decision about processes, people, knowledge, risk, and continuity. The legacy system is not only a set of old components. It can be the place where the organization deposited part of its operational history, its exceptions, its commitments, its limitations, and its real way of functioning.

That is why deeply embedded systems require more than a good target architecture. They require a sociotechnical diagnosis. They require the organization to make visible dependencies that were normalized. They require tacit knowledge to be recovered. They require change to be designed not only to replace technology, but to preserve the ability to operate while transformation happens.

In the next article of the series, I will address a direct consequence of this scenario: **postponed modernization is also a decision**.

Because, when the system is deeply connected to the organization, postponing may seem prudent. But, over time, postponement also becomes architecture.