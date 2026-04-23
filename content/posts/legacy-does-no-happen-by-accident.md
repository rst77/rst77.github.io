+++
authors = ["Renato Teixeira"]
title = "Legacy Does Not Happen by Accident: What Lehman Still Teaches Us About Software Evolution"
date = "2026-04-14"
description = "This text provides a strategic analysis of Lehman’s Laws of Software Evolution, reframing legacy systems not as accidents, but as the inevitable result of successful adaptation that requires continuous structural discipline."
tags = [
    "LegacyModernization",
    "EnterpriseArchitecture",
    "SoftwareEngineering",
    "SoftwareEvolution",
    "MeirLehman",
    "SoftwareLifecycle"
]
categories = [
    "Modernization",
]
series = ["Modernization"]
+++

Legacy does not emerge as an isolated failure, nor as a simple consequence of age. In most important systems, it is the result of continuous adaptation under real pressures: new requirements, operational constraints, accumulated decisions, and the constant need to remain useful in a changing environment. 

That is why **Meir Lehman’s (1980)** article remains so valuable to me. It does not treat software as a static artifact, but as something shaped by ongoing evolution. And for that reason, I believe it deserves to be much better known by those who work in the day-to-day practice of IT.

What makes the article so important is that it helps build a more mature understanding of software maintenance, evolution, and modernization. Instead of treating legacy as merely “old technology,” Lehman explains why change is inherent to software that lives in the real world, and why that same change gradually creates structural tension. 

For me, the most educational parts of the article are still the first two laws.

---

### 1. The law of continuing change
Lehman’s first law states that a program in use, one that reflects some external reality, must undergo continuing change or it becomes progressively less useful. He also makes clear that this process continues until it becomes more cost-effective to replace the system with a recreated version.

This is one of the most important lessons any IT professional can learn.

Useful systems do not remain still, because the environment they serve does not remain still. Business priorities change. Users change. Regulations change. Infrastructure changes. Integration needs change. Operational expectations change. Once software becomes part of a living environment, it must evolve with that environment.

This sounds obvious, but many poor decisions still come from the silent expectation that an important system can be built, deployed, and then remain adequate with only limited effort. Lehman dismantles that illusion.

That is why I see this law as deeply educational. It teaches that modernization is not simply about replacing old platforms, rewriting applications, or moving to the cloud. Modernization begins with accepting that software in production is exposed to continuous pressure for change.

### 2. The law of increasing complexity
Lehman’s second law is equally important. As a program evolves through continuing change, its complexity increases unless explicit work is done to maintain or reduce it.

This is one of the most honest descriptions of what happens to real systems over time.

Every fix, every adjustment, every exception, every new integration, every operational workaround leaves a mark. And when those marks accumulate without enough architectural discipline, the system becomes harder to understand, harder to test, more expensive to change, and more dangerous to evolve. Lehman even describes the temptation to implement change upon change upon change, until the system becomes more complex, stiffer, and more resistant to further change.

That is an essential teaching.

Growing complexity does not necessarily mean the system failed. In many cases, it means the opposite: the system survived, remained valuable, and absorbed years of real business demands. The problem is not change itself. The problem is change without sustained structural care.

That is why this second law remains so educational in practice. It reminds us that there is no continuous evolution without structural cost. No useful long-lived system escapes this tension. And when that cost is ignored for too long, the system enters the familiar zone where response slows down, change becomes expensive, testing becomes stressful, and modernization starts to look bigger and riskier than it should.

---

### What these two laws teach together
When I read Lehman, I see these two laws as a foundation for understanding software evolution.

* **The first teaches:** if a system is useful, it will need to change.
* **The second teaches:** if it changes continuously, its structure will tend to deteriorate unless someone actively works against that trend.

Taken together, these two ideas explain a great deal of what we still face in enterprise IT. They explain why core systems become legacy even when they remain relevant. They explain why modernization should not be treated as a rare event, but as a permanent capability. They explain why architecture cannot be only an initial design concern. And they explain why maintenance is not a secondary phase of software engineering, but a central part of the economic and technical life of software. 

Lehman explicitly argues that change must be planned and controlled, and that the economic evaluation of a system should consider total lifetime costs rather than only its initial development cost.

---

### The other laws matter too
Although I consider the first two laws the most immediately educational for practitioners, the remaining laws also add important perspective.

* **Lehman’s third law (fundamental law of program evolution):** argues that software evolution follows an underlying dynamics that makes the process statistically regular and, to some extent, self-regulating. This matters because it suggests that evolution is not just a sequence of isolated local decisions, but a broader process with observable patterns.
* **The fourth law (conservation of organizational stability):** points to an invariant work rate during the active life of a program. In practice, this is a reminder that software evolution is shaped not only by code, but by organizational capacity and limits. More pressure or more people do not automatically produce proportionally more effective change.
* **The fifth law (conservation of familiarity):** suggests that the content of successive releases tends to remain statistically constrained. That is another powerful idea for practitioners: systems and organizations can only absorb so much change at a time without destabilizing themselves.

Even when read briefly, these laws reinforce the same broader lesson: software evolution is not arbitrary. It has patterns, constraints, and consequences that should be understood as part of engineering practice.

---

### Why this article still matters
What I value most in Lehman’s article is that it educates without oversimplifying. It treats software as a technical, organizational, and economic phenomenon at the same time. And that remains extremely relevant.

While we now talk about cloud, microservices, platform engineering, observability, large-scale refactoring, and AI-assisted development, Lehman still reminds us of something more fundamental: software in real use must evolve, and that evolution carries structural cost. Ignoring either side of that equation leads to poor judgment.

That is why I believe this text deserves to circulate much more widely among IT practitioners. Before debating the next technology trend, it is worth understanding the nature of the problem that accompanies every important long-lived system: the inevitability of change, and the equally inevitable tendency toward growing complexity.

For anyone working with legacy systems, few combinations are as clarifying as that.

Legacy does not happen by accident. And the more seriously we understand that, the better we can modernize with judgment.