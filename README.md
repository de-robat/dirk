<p align="center">
  <img src="https://github.com/swarmfund/dirk/blob/master/imgs/logo.png" title="ÐIRK"><br />
  <strong>ÐIRK - Ðecentralized Identity & Reputation Kernel</strong>
</p>

## Background
Nobody will argue that there is a **growing need for secure and "valuable" digital identities**. Through the use of blockchain technologies, we now have the possibility to deliver exactly that on a public or private decentralized ledger. Some initiatives in this direction have been relatively successful, although none seem to have been able to reach a larger audience. So what have they been missing? In our opinion, most decentralized identity solutions today lack a proper identity valuation system. What makes you take care of your digital identity? Well, the reputation that you have built with it, on many different layers, for many different purposes. Building reputation takes time, sometimes years or longer, so you won't discard it so easily.

## Reputation platform
ÐIRK promises to deliver an online platform where decentralized identities are closely tied to an advanced reputation system, **targeting not only people, but also objects**, programs, artificial entities, and so on. Think about the Internet of Things. Wouldn't it be great if, for example, when you would like to buy a car, you could open an app and check its reputation report (e.g. of all major components used to build that car)? Before you even buy the car, you could see which parts could cause problems after a predictable amount of time. This is of course just one example of the countless applications one could think of.

For all these applications, ÐIRK aims to offer a decentralized platform where identities can be registered and maintained, and reputations can be managed by an advanced set of tools, equipped with many layers of functionality, **specifically designed for multi-purpose use**. 

## Ðecentralized identity
First of all, it should be possible to define your own classes of blockchain identities. In other words, through an API call, it should be possible to register a new identity class, while determining which fields that class will have. At the same time, it should be possible to define whether those fields are optional or mandatory, if and what kind of encryption will be used for storing their values, and if they can have only one or multiple values. In case of the latter, extra flags should be allowed to be set, differentiating the values for various purposes. Furthermore, it should be possible to set the visibility of each field by rules, distinguishing between public and private, in general and under certain conditions linked to the fields defined in its class. To make a person belong to a certain group would then be implemented by creating a "Group" identity class and a "Group" field for the "Person" identity class. That field could have multiple values, which could be used in a rule to determine whether or not to show a certain field for people belonging to certain groups.

When blockchain identities are created, they can be for real persons (having name, nickname, phone, e-mail, address, ...), but as well as for machines, for example. Or for machines parts. Even for software or software modules. It really doesn't matter, as reputation can be built in every scenario.

"Proof of Identity" is not relevant for ÐIRK, as it can be entirely managed outside of the kernel, by the party who has defined the identity class. Images (or files) on the other hand, could be managed externally, or by another decentralized platform like IPFS or Storj.

## Ðecentralized reputation
As with identity, it should also be possible to define your own classes of blockchain reputation. Compared to identities, reputation always has an embedded "value" field. Initial value can be set upon creation (so it can be low or high, depending on the creator's discretion). Afterwards, values can be changed by so-called "modifiers", who, optionally, can be triggered by "events". Modifiers are defined within the kernel, while types of events can be defined through API calls.

Work needs to be put in the definition of the kernel's reputation modifiers. Their effect can be as simple as adding to or subtracting from the reputation's value, but more complex algorithms can be thought of. Advanced computational algorithms, based on an extended set of parameters, will increase the interest in using the kernel.

## Roadmap
We will start with a detailed analysis of the kernel's requirements. Decisions about must-haves and nice-to-haves will have to be made for the alpha release. After a thorough peer review, a proposal for ÐIRK's architecture can be written down. Afterwards, a technological framework will be put together. The decision to use an already existing smart contract platform like Ethereum, or to build an entirely new blockchain for ÐIRK's specific purposes, has not yet been made. Once a clear development path has been defined, the entire team will start implementing the MVP. Building a custom (lightweight) blockchain will not necessarily slow down the development process.

After having reached a first release candidate, it is thought wise to organise a code sprint with a larger team of developers. Not only will we get a lot of feedback on the work already delivered, but in a short time we might be able to implement even a couple of extra valuable features. Obviously, a code review of both the release candidate and the code sprint result are of utmost importance, especially checking the code for logical errors, like inconsistencies in concurrent process outputs. After fine-tuning, a second release candidate will be prepared and properly tested before being offered for implementation into Swarm Fund.

In summary:
* Stage 1: Object Model
* Stage 2: Technological Framework
* Stage 3: First Development Cycle
* Stage 4: Code Sprint (at [Schloss Heinrichshorst](http://www.heinrichshorst.com))
* Stage 5: Second Development Cycle
* Stage 6: Code Review & Testing
* Stage 7: Alpha Release

## Trust Currency
ÐIRK will be first used as the "Trust Currency" platform for Swarm Fund.

Trust Currency is a critical part of the Swarm Fund implementation as it creates a second layer of accountability that preserves system trust. In other words, it creates an incorruptible layer of data that then is queryable for particular use cases. This multi-layered incentive model is a core part of Swarm intelligence models and implements formally the [stigmergic](https://en.wikipedia.org/wiki/Stigmergy) elements found in other natural systems. In the Swarm Fund case, it is particularly applied to people soliciting and deploying funds, so that they cannot easily be scammed, and to provide the correct system incentives for positive behavior.

![TrustGraph](https://github.com/swarmfund/dirk/blob/master/imgs/trustgraph.png)

As Swarm Fund ultimately envisions this trust layer as having an independent existence and to be shared by multiple development partners, ÐIRK is the perfect platform for implementing the Trust Currency component.

## More info
**Dirk von Heinrichshorst**
* [dirk@heinrichshorst.com](mailto:dirk@heinrichshorst.com)
* +49 (0)3936 397763
