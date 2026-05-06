<hgroup>
	<h1>Interledger Fellowship Application (2026-05): Charles Iliya Krempeaux</h1>
	<p>by Charles Iliya Krempeaux, B.Sc.</p>
</hgroup>

# AssetFlow: Fediverse-Native Payments and Asset Transfer

## Abstract

The Fediverse can connect people all across the world in meaningful ways — and through that we can make a more just, equitable and sustainable world.

***Fediverse-native payments* can help people exchange value as seamlessly as they exchange ideas** — enabling more direct, accessible, inclusive, and resilient economic relationships that support a more equitable and open digital commons, while advancing **economic inclusion** and delivering broader **societal benefit**.

**Fediverse-native payments** open the door to forms of commerce that are not mediated by centralized gatekeepers — allowing people to build livelihoods, support their families, and participate in the global economy on their own terms.
This shifts economic power away from a handful of powerful corporations and toward the communities and individuals who create value in the first place.
Thus protecting their livelihoods by reducing risk brought on by dependence on these gatekeepers, and their arbitrary account suspensions or shifting platform policies.

**Fediverse-native payments** are also a way of future-proofing the digital economy at a moment of profound technological shift.
We are at the beginning of a new era of *human–computer interaction*, defined by AI-powered agents that can act, decide, and transact on behalf of individuals — giving rise to what can be understood as **agentic commerce**.
Today, a small number of companies are already competing to control the infrastructure and interfaces through which these agents will operate.
If that control consolidates, we risk recreating the same concentration of power that has defined previous generations of the Internet — with a handful of corporations mediating access, extracting value, and setting the rules.
**Fediverse-native payments**, by contrast, offer an open, interoperable commerce layer that agents can use without reliance on centralized gatekeepers — ensuring that this next phase of the Internet remains pluralistic, competitive, and aligned with the interests of the people and communities it serves.

**Fediverse-native payments** have the potential to be as transformative as **mobile money** was across parts of Africa, where services like M-Pesa dramatically expanded financial access for millions who had been excluded from traditional banking systems.
Just as mobile money used simple mobile phones and local agent networks to bring millions of unbanked people into basic financial services, Fediverse-native payments use of Social Web infrastructure lets anyone who can communicate also send, receive, and earn money directly.
This lowers barriers for underbanked or excluded communities, reduces dependence on gatekeeper platforms that can restrict access or change rules arbitrarily, and enables more resilient, peer-to-peer economic participation where individuals and small communities can take part in global commerce on their own terms.

This vision is being realized through a project called **AssetFlow**, which aims to bring **Fediverse-native payments** into practice.

**AssetFlow** will leverage **Interledger** technologies to enable open, interoperable value exchange across networks, aligning financial interaction with the same principles of openness and decentralization that underpin the Fediverse.

## Objective

The deliverables of the **AssetFlow** project is:

* **AssertFlow specification** — defined in terms of the Fediverse technology suite of *acct-URI*, *ActivityPub*, *ActivityStreams*, *Ed25519*, *Fediverse IDs*, *JSON-LD*, *WebFinger*, etc, and how *Interledger* technologies are used
* **AssetFlow SDK** (open-source) for Go, PHP, Ruby, TypeScript
* **AssetFlow integration** (patch) for Mastodon, Pixelfed, Loops, PeerTube, WriteFreely

And, through this, the ability for `@alice@example.com` to send funds to `@bob@host.example` just by using his Fedivese ID — without having to deal with or even know about Bob's IBAN, sort-code, account-number, routing-number, etc.

## Fellow

I am **Charles Iliya Krempeaux, B.Sc.**, a **product leader**, a **engineering leader**, and **founder** working at the intersection of **payments**, **identity**, and the **Social Web**.

My background includes **banking**, **fintech**, **payments infrastructure**, **compliance** (**AML**, **KYC**, **PEP**), and **social-media platforms**, with a focus on building systems that support trust, interoperability, and user agency.

I am a **Fediverse developer**, organizer of **FediCon**, and an active advocate for the **Social Web and open, decentralized infrastructure**.

My formal academic background is in **computer science**, **mathematics**, **artificial intelligence** (**AI**), and **cryptography**, which informs my systems-oriented approach to building financial and social technologies.

**Selected career highlights**:

* Founding CTO of **Koho Financial**, where I built Canada’s first neo-bank, now used by ~5% of all Canadians
* Early engineer at the social-media company **Hootsuite**, contributing to its early scale
* Head of engineering at **Trulioo**, working on global identity verification systems
* Principal software engineer at **Electronic Arts** (**EA**)
* Founding engineer of a startup acquired by **Microsoft**
* Contributor to the **WHATWG** standards working group
* Co-author of a software engineering book

## De-Risk

Why am I uniquely positioned to build this‽

I am building **AssetFlow** based on my experience in **banking**, **fintech**, **payments infrastructure**, **identity systems**, and **social platforms**.

I am a veteran technologist in these areas, with a deep understanding of how these industries and technologies work.
As well as a knowhow of how to navigate the regulatory environments in which they exist.

I have already successfully created services in this space, now used by millions of people:

* the **neo-bank** *Koho* — the largest fintech in Canada
* the **identity verification service** (IVS) *Trulioo* — one of the two major IVSes in Canada

**I.e., I literally created both a *neo-bank* and a *identity verification service* from scratch.**

The **AssetFlow** project directly sits at the intersection my existing compentancies.
And, is similar to work I have previously done and led in banking, identity verification, and large-scale social systems.

* As the founding CTO at Koho I led architecture and engineering of **regulated** consumer financial systems at **national scale** — which is directly relevant to designing compliant, interoperable payment flows in AssetFlow
* As the head of engineering at Trulioo I built global identity verification infrastructure — this informs AssetFlow’s approach to resolving identity (Fediverse IDs) into financial endpoints
* As a contributor to WHATWG standards I have experience in cross-organizational protocol design — which is relevant to defining interoperable Fediverse-native payment standards
* As someone with a formal background in cryptography I have experience applying cryptography — which is relevant to creating Fediverse-native payment standards that bring the safety and secuity that proper use of cryptography brings
* As an engineer at social-media Hootsuite I build systems that can handle social-media at scale — which is relevant to designing a Fediverse-native payment system that can scale.

The technical and regulatory components of **AssetFlow** are all areas where I have shipped production systems at scale.

**These all significantly reduce execution risk for this proposal.**

## Need

The **Internet**, the **Web**, and **social-media** have become central venues for **commerce**.
They are not just places where people connect — **they are economies** where creators, businesses, and workers earn income, build livelihoods, and support their families.

Yet participation in these economies is increasingly mediated by a small number of powerful platforms.

For creators, relying on services like YouTube, TikTok, or Instagram creates structural vulnerability: access to audiences — and therefore income — can be lost overnight due to account suspensions, policy changes, or opaque moderation decisions.
Entire channels or stores can disappear without recourse, severing critical economic relationships.

Even peer-to-peer marketplaces such as eBay or Facebook Marketplace extend this dependency.
Sellers face sudden restrictions, delisting, or reduced visibility through opaque ranking and enforcement mechanisms. Access to buyers and income streams remains controlled by platform policies and algorithms, reinforcing reliance on centralized intermediaries even in systems that appear decentralized.

This fragility extends to the broader Web.
Large marketplaces like Amazon, Alibaba, and eBay can remove products or sellers unilaterally.
Search and discovery are shaped by companies like Google, Apple, and Meta. Payments rely on networks like Visa, Mastercard, and PayPal, while cloud infrastructure from providers such as AWS or Shopify underpins much of the digital economy. Policy or pricing changes at any of these points can have wide-reaching effects.

Taken together, this concentration of power limits economic agency and reduces the resilience of online livelihoods.
**All social commerce should not be controlled by a small number of powerful corporations.**

## Impact

**AssetFlow** introduces a payments layer that can operate natively within the Fediverse, allowing creators and communities to exchange value within the same environments where social interaction already occurs.

More specifically, it allows Fediverse IDs (such as `@alice@example.com` and `@bob@host.example`) to be the source and destination of a money transfer, without having to be deal with the lower-level payment rail details.
I.e., it allows `@alice@example.com` to send money to `@bob@host.example` without having to deal with Bob's IBAN, sort-code, account-number, routing-number, etc.
All she needs is his Fediverse ID (`@bob@host.example`).

This reduces reliance on platform-specific monetization systems used by services such as YouTube, TikTok, Meta, etc.

By embedding value exchange into interoperable social protocols, AssetFlow can reduce dependence on centralized intermediaries for payment processing, distribution, and monetization. This may increase resilience for creators whose livelihoods depend on maintaining access to audiences across platform boundaries.

Adoption across Fediverse will start with the 5 initial applications, and then occur incrementally, as each integration expands the set of participants capable of sending and receiving payments.
Over time, this can help address coordination and cold-start challenges common to networked financial systems, where utility increases as more services participate.

As interoperability increases, new forms of social and economic interaction may emerge within the Fediverse, including creator-supported communities, cross-platform commerce, and programmable or contextual payments embedded directly in social activity.

## Economic Inclusion

The current global financial system excludes or marginalizes significant portions of the world’s population.
Barriers such as lack of formal identification, limited access to banking infrastructure, high remittance fees, currency conversion friction, and restrictive account requirements prevent many individuals and communities from fully participating in digital and cross-border economies.

Even for those who are banked, access is often mediated through intermediaries that impose fees, delays, and policy constraints that are not transparent or user-controlled.
This creates a structural divide between those who can participate seamlessly in global digital commerce and those who cannot.

**AssetFlow** is designed to contribute to economic inclusion by lowering these barriers at the protocol level within the Fediverse.

By enabling value exchange through Fediverse identifiers rather than traditional banking identifiers, AssetFlow reduces dependency on specific financial institutions and simplifies participation in global economic activity. A user only needs a Fediverse identity to send or receive value, abstracting away the complexity and exclusivity of legacy financial rails.

Through integration with **Interledger**, AssetFlow can support interoperability across diverse payment networks, including both traditional financial systems and emerging digital wallets. This enables:

* **Lower-cost cross-border transfers**, reducing reliance on high-fee remittance providers
* **Improved access for underbanked and unbanked users**, who may not have access to traditional account-based systems
* **Frictionless micropayments**, enabling new models of participation, tipping, and community support that are not economically viable under card-based fee structures
* **Broader geographic participation**, allowing creators, developers, and communities in the Global South to participate on more equal footing
* **Reduced gatekeeping by platforms and financial intermediaries**, enabling direct economic relationships between individuals

Importantly, this model supports incremental participation.
Users and services can adopt **AssetFlow** without requiring universal coordination or migration, allowing inclusion to grow organically as more Fediverse instances and applications connect to the network.

Over time, this can help shift online economic participation from platform-constrained systems toward open, identity-native financial interactions, where access is determined by connectivity rather than institutional permission.

## Interledger

**AssetFlow** defines Fediverse-native payments in terms of the Fedivese's technology suite:
acct-URI, ActivityPub, ActivityStreams, Ed25519, Fediverse IDs, JSON-LD, WebFinger, etc.

**AssetFlow** uses **Interledger** as its settlement and transport layer for cross-network value exchange.

Within the Fediverse, payments are initiated using familiar identity primitives such as Fediverse IDs (e.g., `@alice@example.com`).
However, these identifiers do not themselves represent payment accounts or financial rails.

To execute a transfer, **AssetFlow** resolves the recipient and sender identities into underlying payment capabilities, and routes the resulting transaction through Interledger protocols.

Interledger provides a network-agnostic way to move value across heterogeneous financial systems.
This allows **AssetFlow** to bridge:

* traditional banking networks
* digital wallets and fintech APIs
* emerging or local payment systems

By separating identity (Fediverse) from settlement (Interledger), **AssetFlow** preserves the social-native model of addressing while leveraging existing global payment infrastructure for execution.

## Project Sustainability

**AssetFlow** is intended as a foundational protocol rather than an application-level service.

Like core Internet protocols such as HTTP or SMTP, its purpose is to establish a minimal, interoperable layer that enables others to build higher-level systems on top of it.

Once deployed, **AssetFlow** is not a centralized system that must be continuously operated or governed as a single product.
Instead, it becomes part of the broader Fediverse and Interledger ecosystem, where:

* new implementations can emerge independently
* infrastructure diversity increases resilience
* innovation can occur without coordination bottlenecks

In this sense, the **AssetFlow** project is designed to “bootstrap” a capability into existence: Fediverse-native value transfer between identities.

Over time, this capability becomes a general-purpose building block for new forms of social and economic interaction across the Open Social Web.
