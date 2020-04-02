
# Contributing to Pariyatti Software

## Overview

Please read this document thoroughly and clarify any doubts before making contributions. There are three main points of consideration this document covers. They are all interconnected. The first is a **_long-term vision_**. It is important to make decisions in the context of Pariyatti (the organization and its resources) surviving for a very long time... well beyond our own lives. The second is **_selfless service_**. Give your time to Pariyatti software projects because you want to serve others --- to help the people of the world while they walk the path. The last, and perhaps most important, is **_sila_** (ethics). While giving Dhamma Service, always do your utmost not only to maintain your own sila but to ensure no action of yours causes another person to break their sila.


## Long-term Support

It is important for all contributors to keep in mind the nature of Pariyatti projects. 2500 years of literature is likely to experience a very long software support cycle --- rather unlike those seen in common software projects. (Some help conceptualizing this exponential timescale is provided in the following section, "Time".) For this reason, a key point must always be kept in mind:

> Always defer to long-term Pariyatti staff for any major decision and for the ultimate responsibility of stewardship of artefacts.

"Artefacts" here refers both to the physical and the digital. Examples of very important long-term artefacts include things like: email accounts, web service accounts, passwords, security keys, and privacy-sensitive documents. Always provide access to such artefacts to multiple Pariyatti staff members to limit bus factor and reduce friction.

In addition to the stewardship of artefacts, we as contributors to Pariyatti software must consider how our design, technical, and architectural decisions affect the longevity of what we create. Preference will generally be given to stable, high-quality tools with broad (preferably open) support across varying systems and geographies. Some examples are provided below, in the section "Tool Choices".


## Time

The normal timescales of a standard software project remain extant in Pariyatti software projects: Initial development will happen in iterations --- some perhaps as short as one week, some perhaps as long as multiple months. Continued development, in the standard open source model, will proceed on the order of years. Along with this, maintenance will occur over a time period of years-to-decades.

Beyond this, however, we must imagine the longer timescales on which this software will continue to live. In the coming decades, computing devices and software methods will both change greatly and Pariyatti software must change with them. Computing itself is a relatively young discipline but already "software archeology" exists as a sub-discipline. It will be helpful if we anticipate these longer timescales and contextualize our contributions to Pariyatti by planning for the times after our contributions (and lives) are finished --- and who will steward our contributions after we are no longer here to guide them.

Whether choosing a hardware platform, an operating system, a service provider, a shrink-wrapped software package, or a programming language/framework, always take a moment to consider the various exponential timescales within which that choice must survive.


## Naming

> There are two hard problems in Computer Science: (1) Cache Invalidation and (2) Naming Things.

It will be very important to converge on meaningful and universally-understood names for all layers of Pariyatti's software architecture. To prevent confusion it will be helpful for all contributors (users, project managers, operations staff, designers, and developers) to share a common language. To this end, each project may have a `GLOSSARY.md` in its root directory. This repository also contains a global glossary:

https://github.com/pariyatti/agga/blob/master/GLOSSARY.md


## Quality

In general, the intersection of (1) very long timeframes and (2) volunteer-built software means we should lean toward "safe" technologies. "Safe" will often mean boring. When introducing a new technology, prefer simple tools with a strong history. There will always be trade-offs. Please document them in an [Architectural Decision Record (ADRs)](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions). Similarly, document all internal architectural decisions with ADRs.


## The Service Paradox

In the wonderful book [_For The Benefit of Many_](https://store.pariyatti.org/For-the-Benefit-of-Many-Pariyatti-Edition-Vipassana), Goenkaji repeatedly emphasizes the concept of selfless service. It can be difficult to give Dhamma Service without agitating the ego. When serving at a Centre for work periods and courses one can keep one's own ego in check by remaining anonymous: clean when no one is looking, serve students humbly, etc.

Software projects make this aspect a bit difficult. As Dhamma Servers, we do not want to spread our names all over our work. At the same time, a completely anonymous software project is impossible --- stewardship and accountability are both very important in software.

For this reason, please always use your real name (and your personal GitHub account) when contributing to a Dhamma software project. But in doing so, try always to remember that your contributions are contributions of parami: to help others, not to boost ego.


## Tool Choices

Across Pariyatti's technical projects we will have a few repeated tool choices to make: licenses, shrink-wrapped software, data formats/protocols, online services, programming languages, programming frameworks, and programming toolchains. Let us deal with each of these individually:

### Licenses

Where possible, always release Pariyatti's software contributions to society _in the open_. If it is suitable to the project, Free Software licenses (AGPL, GPL, etc.) prevent Pariyatti's work from being misused and prevent its consumers from breaking their own sila. Where it is not possible to use a Free Software license, a permissive license (MIT, BSD, MPL, etc.) may be used.

_Why Free Software Licenses:_ The example of the animal trade may be helpful. When one realizes that killing any creature harms Dhamma, one may choose to avoid consuming meat or products made of animal flesh. However, what one _produces_ is of even greater importance to maintaining sila --- not to buy, sell, or work with flesh or meat. In this same way, it is important to consume ethical software but it is much more important to produce ethical software. Free and open software is ethical to produce; closed-source software is not.

### Shrink-Wrapped Software

Wherever possible, prefer Free Software (or open source software) for ethical reasons. Viewing our sila as three-dimensional encourages us to participate in an environment where hindrances to sila are removed not only for us, but for others. The ethics of Free Software are complex but all of the ideas in this document are covered within them: longevity and sustainability, an exponential perspective of time for the human species, clarity (naming), quality, and selfless service.

It is very likely that new ethical concerns will emerge in the future. Some examples include standardized protocols and encrypted network data. When a clear ethical choice emerges, please add it to this document so Dhamma Servers can take that concern into account while they give service.

### Data Formats/Protocols

Wherever possible, prefer open data formats and protocols. For similar reasons as preferring Free Software, open data ensures the longevity of that data and its utility to Pariyatti. Closed data formats and closed protocols can potentially lock Pariyatti's data away from Pariyatti itself --- such unnecessary complications waste dana (donations of time and money).

### Online Services

Be very careful when selecting online services. As above, prefer services built on Free Software. Where Free Software is not possible to consume, prefer open protocols. Changing from one online service to another should be a relatively simple process --- this will use less dana and fewer of Pariyatti's resources. Always ensure that when Pariyatti makes use of an online service such a service protects user privacy (meditator or not) with the utmost integrity.

### Programming Languages

Prefer stable programming languages with a wide installed base and broadly available toolchain.

### Programming Frameworks

Frameworks may require more research than languages. Try to answer, to the best of your ability, the likelihood that the framework you are choosing will remain extant in 10 - 20 years. Frameworks with a mature evolution and an emphasis on high-quality releases and backward compatibility should be preferred to new and exciting technology.

### Programming Toolchains

As much as possible, do not restrict the tools of Dhamma Servers: do not dictate operating systems, development environments, or text editors. Not all Dhamma Servers have access to the same hardware and software and (as of this writing, Jan 2020) most software development toolchains are modular, flexible, and cross-platform.

### Why GitHub?

For the time-being, we have chosen GitHub as a code repository. Although GitHub itself is not open source (yet), it is presently the de facto repository for collaborative open source projects. GitLab (and BitBucket, though it's not open source) are also options but it is less likely that Dhamma Servers will have a GitLab account. Git (as a data storage format) retains a full history of modifications, making it very easy and open to export. Should we choose to move Pariyatti's repositories from GitHub to GitLab in the future, no historical data will be lost.
