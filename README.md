# clouders
develop from *localhost*, even unplugged. Once you have it, deploy for real at scale.

## Goals

* Lower prototyping and development costs for either single or multi cloud solutions
* Enable developing big, from local infrastructure
* Allow to integrate services from different cloud providers
* Use either a devbox, a home made cluster or a professional box
* Ease transitioning from development to real operating environments (unplanned)

> Please join us in a new or ongoing [Discussion](https://github.com/luisgizirian/clouders/discussions)

We want to enable software developers and architects to think big and walk from idea to prototype without having to leave their box. Mature and reliable designs, often transcend the limits of a single region or cloud provider. Such solutions are hard to put together from the comfort of *locahost*, leading to compromise on taken desicions.

Picture this: a multitenant e-commerce solution must be put in place, on a muti-region and multi-cloud fashion, supporting from multiple vendors:

* multiple public IPs, DNS services
* RDBMS and NOSQL data stores
* microservices
* caching
* messaging
* storage, cdn

To name a few of the involved solutions. We're told to pick two different cloud providers (to provide high availability) that will be complemented with an on-premise piece. Our journey begins here, where the options are too many and its difficult to plan and prototype without comprising to subscription trials and abandoning local development for cloud provider specifics.

**We want to live in a world where, from the comfort of our devbox, we may pick relevant *public API matching services* from different providers, and develop potentially world class solutions by using these API matching implementations to power our ideas.**

## Services
No need to open up specifics for each cloud provided service offering. A *public matching API* with a custom implementation should be enough to provide a close to reality offering that a developer can use to code its idea without leaving its devbox, getting a working prototype.
