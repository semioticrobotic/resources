# Working In Public
Nadia Eghbal

## Introduction

Begin from the premise that contemporary open source developers suffer not from lack of project contributions but from *too many* of them.

> That many open source developers suffer from a lack of support is indisputable.

Eghbal initially focused on lack of funding for open source projects (cf. *Roads and Bridges*); "in the absence of additional reputational or financial benefits, maintaining code for general public use quickly becomes an unpaid job you can't quit"

> The cycle looks something like this: Open source developers write and publish their code in public. They enjoy months, maybe years, in the spotlight. But, eventually, popularity offers diminishing returns. If the value of maintaining code fails to outpace the rewards, many of these developers quietly retreat to the shadows. 

The goal of this work is to begin an analysis of open source production with different premises:

> The default hypothesis today is that, faced with growing demand, an open source "maintainer"—the term used to refer to the primary developer, or developers, of a software project—needs to find more contributors. [...] I started to see the problem is not that there's a dearth of people who want to contribute to an open source project, but rather that there are too many contributors—or they're the wrong kind of contributors. [...] But what if we start from the premise that things are as they should be? I decided to revisit the diagnosis, treating these symptoms as a starting point, instead of applying the only prescription—more participation—that we had.

A significant difference is that today most code is developed and deployed modularly; software projects aren't as monolithic as they once were:

> In contrast to big, monolithic software projects that give rise to persistent communities, npm packages are designed to be small and modular, which leads to fewer maintainers per project and a transitory relationship with the code they write. Viewed in this light, the lack of contributors today reflects an adaptation to changing environmental circumstances, wherein the relationship between a maintainer, contributors, and users is lighter, more transactional. 

This impacts the role of the maintain, too:

> The role of a maintainer is evolving. Rather than coordinating with a group of developers, these maintainers are defined by the need for curation: sifting through the noise of interactions, such as user questions, bug reports, and feature requests, which compete for their attention. [...] The problem facing maintainers today is not how to get more contributors but how to manage a high volume of frequent, low-touch interactions.

Analyses of various online platforms are also useful in this context, as platforms like GitHub (and GitLab) bring the same dynamics, logics, and economics to bear on the work of code creation:

> Rather than the users of forums or Facebook groups, GitHub's open source developers have more in common with solo creators on Twitter, Instagram, YouTube, or Twitch, all of whom must find ways to manage their interactions with a broad and fast-growing audience.

## Chapter 03: Roles, incentives, and relationships

This chapter examines the economics of open source production and distribution. Open source seems perplexing and counterintuitive because it contravenes so much received economic wisdom.

For example, Coase's theory of the firm:

> Previously, our understanding of how and why people make things was modeled after Ronald Coase's theory of the firm, which proposes that firms (i.e., companies, organizations, and other institutions with centralized resources) naturally emerge as a way to reduce transaction costs in the market. Coase would've told us that only companies make software because, from a coordination standpoint, managing the resources required to pull off such a feat would be most efficiently handled within the same organization.

Open source production seems to transcend traditional organizational boundaries, relations, or financial incentives. So another tack is to treat open source projects as commons (cf. Elanor Ostrom). This frame seems a more productive lens for understanding open source economically (that is, how they self-organize and self-govern to optimize resources).

> Ostrom's work on the commons helps us understand the conditions in which people produce software *collaboratively*: the clubs and federations of open source.

This model is (for critics like Benkler), a "third way" to organize and optimize resources: not a market, not a firm.

Community participants are often **intrinsically motivated** to engage in the work; "intrinsic motivation is the currency of the commons" (Eghbal); harnessing and channeling this energy/currency requires **modularity** and **granularity** (breaking large projets into smaller, more manageable pieces, and create discrete workstreams or projects without need for much preexisting knowledge). **Lower coordination costs** aid this (that is, lower costs of overhead, maintaining and orchestrating the work, quality control, integration, etc.).

> A maintainer's biggest coordination costs come from reviewing and merging new contributions, so there's an incentive to keep these costs low. When the costs of coordination outpace the benefits, the commons breaks down as a useful production model.

But not all open source projects really look or operate like a commons (e.g., "stadiums" as described in Chapter 02):

> Without the safety net of the commons, stadiums need to organize their work differently. Decentralized communities prioritize work based on *abundance* of attention: encouraging new contributors, developing governance processes, and improving engagement and retention. But a creator prioritizes work based on *scarcity* of attention: saying no to contributions, closing out issues, reducing user support. While the commons is tasked with resolving *coordination* issues, creators are defined by the need for *curation*.

Platforms like GitHub homogenize an otherwise variegated, heterogeneous federation of unconnected communities and spaces online; they produce a sense of "context collapse" (cf. Wesch)

> Today, most developers transact casually with one another, across projects, with low context and little skin in the game. These developments present a challenge to Ostrom's definition of a commons, and, by extension, to our current working theories about how and why open source software is produced.

Casual contributions to open source projects are today more commonplace, and the so-called "casual contributor" is a persona many open source projects and maintainers must determine how to handle.

> They only want to know enough to get their contribution merged. Their primary interest is personal, and it's the maintainer's job to figure out how to weigh the contributor’s needs against those of the project.

Casual contributors are *self-oriented* (they're working almost solely to fix something that's impacting or of interest to them) rather than *community-oriented*.

## Chapter 04: The work required by software

Two observations guide this chapter:

* software is never really finished (may be feature-complete, but in order to keep running it almost always requires ongoing maintenance)
* once software finds users, it can't easily disappear (someone is going to use it for a long time)

## Details

Citation:  
Eghbal, N. (2020). Working in public: The making and maintenance of open source software. San Francisco, CA: Stripe Press.

Online:  
https://press.stripe.com/working-in-public

Last updated:  
2024-05-13