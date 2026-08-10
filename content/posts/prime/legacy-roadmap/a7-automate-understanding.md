+++
authors = ["Renato Teixeira"]
title = "Before automating change, automate understanding"
date = "2026-06-26"
description = "The promise of automation in legacy systems is seductive. But without understanding, it may only accelerate the production of new problems."
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

![Antes de automatizar a mudança automatize o entendimento](/images/ml/part7.jpg)

*Series: The Legacy Roadmap — Part 7*

Read Part 1 [Legacy is not age. It is dependency](/posts/a1-legacy-is-not-age), Part 2 [Legacy systems survive because they still matter](/posts/a2-survive-because-matter), Part 3 [The risk of changing is visible. The risk of not changing is not always visible](/posts/a3-the-risk-of-changing-is-visible), Part 4 [When software becomes part of the organization](/posts/a4-when-software-becomes-organization), Part 5 [Postponed modernization is also a decision](/posts/a5-postponed-modernization-is-a-decision) and Part 6 [When the system only works because someone still remembers](/posts/a6-when-system-works).

In the previous article, I addressed a risk that is often underestimated in legacy systems: **the system only works because someone still remembers**. In many environments, an essential part of the operation is not formalized in documentation, tests, diagrams, or recorded architectural decisions. It is in the memory of people who learned, over years, how to keep the machinery running. When this knowledge becomes too concentrated, modernization becomes riskier, slower, and more dependent on prior investigation.

Now we arrive at an inevitable topic: **automation**. More specifically, automation and artificial intelligence applied to legacy system modernization. The promise is seductive. If we have old systems, poorly documented code, hidden rules, low understanding, and a shortage of specialists, then automated tools could accelerate analysis, document code, suggest refactorings, identify dependencies, generate tests, support migration, decompose monoliths, and perhaps even transform entire applications into more modern architectures. All of this has value. But there is an important trap: **automating change before understanding the system may only accelerate the production of new problems**.

This is the thesis of this article: in legacy systems, the most valuable automation does not begin with transformation. It begins with understanding.

## The easy promise: transform faster

The industry likes promises of acceleration. Migrate faster. Refactor faster. Document faster. Generate code faster. Decompose faster. Modernize faster. This discourse is understandable, especially in environments where legacy systems accumulate years of delay, dependency, cost, and frustration. When the organization finally decides to act, it is natural to want to recover lost time.

The problem is that speed alone does not solve a poorly understood problem. If the organization does not know exactly which business rules are preserved in the system, which dependencies are critical, which integrations are fragile, which processes were shaped by the software, and which behaviors are intentional or accidental, accelerating change may only move this ignorance somewhere else. The new technology may be born carrying old confusion, now with a more modern appearance.

Automation can move code. It can suggest structure. It can generate preliminary documentation. It can identify patterns. It can support tests. It can point out dependencies. But it does not know, by itself, what is essential to the business, what is historical residue, what is a critical rule, what is a regulatory exception, what is a tolerated workaround, and what is behavior that no one should repeat. Without context, automation can be fast, but not necessarily wise.

And legacy systems do not forgive fast decisions based on shallow understanding.

## The question is not “what can the tool do?”

When a new tool appears, especially when it involves AI, the first question is usually: “what can it do?”. This question is natural, but insufficient. In legacy system modernization, the most important question should be: **which uncertainty does this tool help us reduce?**

This change in question changes the conversation. Instead of evaluating automation only by its ability to generate artifacts, we evaluate its contribution to decision quality. Does it help us understand the system better? Does it help map dependencies? Does it help recover business rules? Does it help identify areas of risk? Does it help reveal invisible couplings? Does it help compare alternatives? Does it help make explicit what previously depended only on the memory of specialists?

If the answer is yes, automation is contributing to modernization in a mature way. If the answer is only “it generates code,” “it creates documentation,” “it converts to another language,” or “it suggests an architecture,” we need to be careful. These results can be useful, but they only gain value when connected to a broader diagnosis. Otherwise, the organization may confuse the automatic production of artifacts with a real increase in understanding.

In legacy systems, a good tool is not only the one that does more things. It is the one that helps the organization decide better.

## Automating without understanding can create a new black box

One of the most serious risks of automation in legacy systems is the creation of a new black box. The organization already has a system it does not fully understand. It uses a tool to transform it quickly. It receives a new structure, new components, new services, new documentation, new tests, and perhaps a new architecture. But if the process is not accompanied by validation, explanation, traceability, and participation from those who know the domain, the result may only be a more recent black box.

The old black box was difficult because there were years of accumulated decisions, incomplete documentation, tacit knowledge, and invisible dependencies. The new black box may be difficult for another reason: it was generated by an automated process that the organization does not fully understand, with implicit decisions that no one discussed, abstractions that seem correct but were not validated, and artifacts that create a sense of control without necessarily producing real control.

This does not mean rejecting automation. It means using it with maturity. Automation should increase transparency, not only speed. It should help explain, not only convert. It should expand investigative capacity, not replace judgment. It should reduce opacity, not cover it with a new technological layer.

When automation produces results that no one can justify, it has not solved the legacy problem. It has only changed its form.

## The first role of automation is to recover knowledge

In legacy environments, knowledge recovery is a critical step. Many times, before deciding whether we will maintain, encapsulate, refactor, rewrite, migrate, or replace, we need to answer basic questions: what does this system really do? Which rules are critical? Which modules concentrate the most dependency? Which integrations sustain essential processes? Which parts of the code are changed more often? Which behaviors are used by business areas? Which routines exist only because of historical exceptions? Which elements can be removed without impact? Which ones cannot be touched without high risk?

Here, automation can be extremely valuable. It can support static code analysis, dynamic execution analysis, dependency extraction, call identification, integration mapping, initial documentation generation, characterization test creation, functionality grouping, module summarization, log exploration, and partial reconstruction of flows. None of these activities eliminates the need for human validation, but all of them can reduce the cost of investigation.

This is an important point: automation does not need to begin with the ambition of transforming everything. It can begin as a reading tool. A way to make the system more visible. A way to help specialists explain what they know, and to help new professionals understand what they still do not know. Automation, in this context, works less as a replacement machine and more as a lens.

And in legacy systems, a good lens can be more valuable than a rushed cutting tool.

## AI as support for archaeology, not as an oracle

Artificial intelligence may play a relevant role in modernization, but we need to avoid two extremes. The first is cynicism: saying that AI is useless in this context. That is false. There are very promising uses in code analysis, assisted documentation, test generation, component classification, rule summarization, support for reverse engineering, and navigation across large technical knowledge bases. The second extreme is fantasy: believing that AI can fully understand complex sociotechnical systems without context, without validation, and without contact with the real operation.

The most useful position is in the middle: AI can be excellent support for software archaeology. It can accelerate the reading of large volumes of code, organize hypotheses, suggest relationships, identify patterns, and produce initial explanations. But these explanations need to be treated as hypotheses, not as truths. In critical systems, the output of a tool should start a conversation, not end it.

This point is especially important because legacy systems carry knowledge that is not always in the code. Part of it is in processes. Part of it is in data. Part of it is in external integrations. Part of it is in manual routines. Part of it is in people’s heads. Part of it is in old decisions that may never have been documented. AI can help find clues, but it does not replace the work of reconstructing meaning together with those who understand the business and the operation.

AI can say “this seems important.” But the organization still needs to answer: important to whom, in which context, with which risk, and with which consequence?

## Tests before transformation

A particularly important use of automation in legacy systems is the creation of characterization tests. Before changing a poorly understood system, it is necessary to capture its current behavior. Not because all current behavior is desirable, but because we need to know what we are changing. In many cases, the system contains rules that no one documented, exceptions that no one fully remembers, and behaviors that business areas consider essential, even if they seem strange from a technical point of view.

Automated tests can help transform observed behavior into evidence. They create a minimum safety net for future interventions. They allow comparison between before and after. They help differentiate intentional change from regression. They make visible what previously depended on manual validation or individual memory. In legacy contexts, this can be more strategic than immediately starting with deep refactoring.

The point is not to test everything before changing. That may be unfeasible. The point is to identify critical flows, sensitive rules, essential behaviors, and areas of higher risk. Automation should help build incremental confidence. Each relevant test reduces opacity a little. Each captured behavior decreases dependency on memories. Each automated validation makes the next change a little less blind.

Modernization without a safety net may seem fast at first. But it usually becomes expensive when side effects start to appear.

## Generated documentation is not understood documentation

Modern tools can generate documentation quickly. They can describe functions, modules, classes, APIs, dependencies, flows, and even suggest explanations about business rules. This is useful. But there is a difference between generated documentation and understood documentation. The first is produced. The second is validated, contextualized, and incorporated into the organization’s practice.

An automatically generated document may seem convincing, but it still needs to be confronted with reality. Does it describe what the code seems to do or what the business really depends on it doing? Does it reflect the current rule or only a historical implementation that no one should preserve anymore? Does it explain why something exists or only repeat its structure? Does it help a team decide or only increase the amount of text available?

In legacy systems, useful documentation needs to answer decision questions. What is critical? What is risky? What is unknown? What needs human validation? What can be removed? What needs to be preserved? What depends on a specific person? What still needs to be investigated?

Automation can help a lot with the first version of this documentation. But maturity lies in the process that comes next: review, validation, prioritization, connection with incidents, association with business rules, integration with ADRs, continuous updating, and real use by the team. Without that, automatic documentation becomes just another artifact that ages quickly.

And we do not need to create new documentary legacies on top of technical legacies.

## Decomposing is not understanding

One of the most common discourses in modernization is decomposition: breaking monoliths, identifying services, separating domains, creating APIs, isolating capabilities. These strategies can be very valuable. But it is important to remember that decomposing technically does not mean understanding conceptually.

A tool can suggest groupings based on code dependencies, calls, shared data, or structural patterns. That helps. But a service should not be defined only by what appears technically grouped. It needs to make sense for the domain, for the business, for the operation, for governance, and for future evolution. Otherwise, the organization may only transform a monolith that is difficult to understand into a distributed set of parts that are equally difficult to govern.

Decomposition without understanding can generate fragmentation. It can increase operational cost. It can multiply points of failure. It can spread business rules. It can turn internal dependencies into network dependencies. It can create the appearance of modernity without reducing essential complexity.

Before asking “into how many services can we divide this?”, perhaps it is better to ask: **which responsibilities do we really understand? Which boundaries make sense for the business? Which dependencies need to be removed before separation? Which rules need to be recovered before they become contracts?**

Automation can suggest cuts. But the organization needs to understand the scars.

## Automation needs to respect the pace of learning

In legacy systems, it is not enough to ask whether automation is capable of generating a change. It is necessary to ask whether the organization is capable of absorbing the learning produced by that change. This point is often ignored. Tools can accelerate the production of artifacts, but people and organizations have limits of assimilation. A large volume of documentation, alerts, dependencies, refactoring suggestions, or risk reports can paralyze as much as it helps.

Automation needs to be designed in learning cycles. First, make a limited set of dependencies visible. Then validate with specialists. Next, produce tests for critical flows. Then document decisions. Then experiment with a small change. Then measure effects. Then adjust hypotheses. This cycle is more valuable than a large automatic transformation that generates many results and little capacity for interpretation.

The goal is not only to produce more information. It is to produce information that the organization can use to decide better. In legacy environments, too much information without prioritization also becomes noise. And noise does not reduce risk.

Good automation is not the one that only delivers volume. It is the one that improves the next step.

## The danger of automating old biases

Another little-discussed risk is that automation may reproduce biases from the existing system. If the code carries old decisions, bad couplings, obsolete rules, poorly justified exceptions, and structures that no longer make sense, an automated transformation may preserve all of this efficiently. Instead of questioning the past, it may copy it.

This risk is especially important when the organization treats the current system as the complete source of truth. The code is an essential source, but not everything in the code should survive. Some rules need to be preserved. Others need to be discussed. Some need to be eliminated. Some need to be reinterpreted. Some represent critical knowledge. Others represent only historical accidents.

Automating without this discernment can lead to a conservative modernization in the worst sense: technically new, conceptually old. The organization changes language, infrastructure, or architecture, but keeps the same vices, the same ambiguities, and the same limitations. The legacy, in this case, was not modernized. It was repackaged.

Automation needs to be accompanied by an uncomfortable question: **are we preserving value or only reproducing the past?**

## What to automate first

If the organization is facing a poorly understood legacy system, some types of automation are usually more useful at the beginning. Automating technical inventory. Automating dependency collection. Automating coupling analysis. Automating initial documentation extraction. Automating identification of critical flows. Automating log analysis. Automating characterization test creation. Automating detection of dead or rarely used code. Automating correlation between incidents and components. Automating decision records and traceability.

These automations do not seem as glamorous as a complete automatic migration. But they attack the right problem: the lack of understanding. They help transform diffuse perception into evidence. They help reduce dependency on individual memory. They help make the discussion more concrete. They help identify where to change first and where not to touch yet.

After that, transformation automations can gain more space: assisted refactoring, incremental migration, encapsulation, API generation, service extraction, code conversion, support for pipeline creation, test restructuring, and component cleanup. But the order matters. The less understood the system is, the more dangerous it is to begin with structural change.

Automating understanding prepares the ground. Automating change builds on it.

## Automation as governance, not only as a tool

Automation also needs to be understood as part of modernization governance. It is not enough to choose a tool and apply it to the system. It is necessary to define usage criteria, limits, validations, responsibilities, artifacts, metrics, and review cycles. Which automation results will be accepted automatically? Which require human review? Which areas are too critical for automated intervention? How should decisions derived from automated suggestions be recorded? How should we measure whether automation reduced risk or only produced more artifacts?

These questions are important because, in critical systems, automation without governance can become a new source of risk. The organization may accelerate bad decisions, trust too much in unvalidated outputs, generate inconsistent artifacts, or transfer responsibility to the tool. But a tool does not assume responsibility. People and organizations do.

Automation should support decision-making, not replace it. It should expand the team’s capacity, not weaken judgment. It should produce evidence, not only output. It should make the system more understandable, not only more active.

When used this way, it stops being a magical promise and becomes an instrument of maturity.

## Closing

Before automating change, automate understanding. This is the thesis of this seventh article. In legacy systems, the rush to transform can be dangerous when the organization still does not fully understand what the system does, what it sustains, which rules it carries, which dependencies it concentrates, and which knowledge remains invisible.

Automation and AI can be very useful in modernization, but their most important value may not be in quickly replacing one technology with another. It is in helping the organization see better. Recover knowledge. Reduce opacity. Create tests. Map dependencies. Document decisions. Support archaeology. Transform dispersed memory into usable evidence.

When understanding grows, change becomes safer. When change comes before understanding, modernization may only change the shape of the problem.

In the next and final article of the series, I will close this journey by presenting the synthesis of the Legacy Roadmap: **modernizing is not replacing technology; it is governing continuity**.

Because, in the end, technology matters. But the quality of the decision matters first.