# What is Findy?

![SSI-logo](https://raw.githubusercontent.com/TrustNetFI/FIndy/master/img/SSI-logo.png)

Findy stands for Finnish Indy network, a locally governed and run decentralised identity ledger. Its target is to enable pilot use cases and services with use of self-sovereign identifiers in Finland. 

A decentralised identity ledger consists of a limited set of public, permissioned nodes that when run together as a decentralised system are responsible for 
- running the cryptographic consensus algorithm that provides non-repudiation of public identifiers
- catering the discovery of public decentralised identifiers (DIDs) and their related public statement documents (DID documents)
- hosting the public credential definitions and schemas that are used by any of FIndy's overlaying pilot use cases
- enabling privacy-preserving tools (revocation accumulators) for revocation checks

The Findy ledger, run first as a test network and sandbox for pilots will be operated and coordinated by local legal entities that i) commit to maintain the network and its nodes along the initial Findy governance rules under development during 2019-20, and ii) agree to work in good faith towards setting up a joint, long-term ledger infrastructure project that stands responsible for operating the distributed ledger. Entities are expected to cover their own operational and development related costs. Result of the first phase will mature eventually with a production ledger for commercial use, potentially with a different name. 

Operations are facilitated by Findy consortium, whose members commit to running the ledger operations according to above principles and later according to their roles and liabilities defined in the Findy's future governance rulebook. Findy has in its initial phase a nominated Board consisting of the founding member representatives and potential Board-nominated executive, legal and technical Advisers. Consortium has an open Consortium Agreement and it accepts and welcomes new additional members according to the agreement's basic approval rules. For more information on consortium terms, or to register your interest in Findy community, contact [markus.hautala@tieto.com](smtp://markus.hautala@tieto.com), Tel. [+358 40 182 4299](tel:+358-40 182 4299‬). 

From technical standpoint the Findy ledger is based on open source decentralised ledger technology from Linux Foundation’s [Hyperledger Indy](https://www.hyperledger.org/projects/hyperledger-indy) project. Technicalities of compatible Wallet apps and so called Agents are a topic the Findy community will document out in 2020.

# Findy as a Sandbox
Findy’s intention is to enable joint R&D testing of public-private self-sovereign identity service concepts in a safe sandbox environment. Sandbox comes with two versions - lightweight development ledger (‘dev-sandbox’) and access controlled test ledger (‘test-sandbox’). Services can include publishing identifiers and related data to ledger, issuing verifiable credentials, or providing access control to data sources (such as data behind an API) through end user wallet/agent services. 

A sandbox ledger is operational since April 2019. The community welcomes parties interested to provide an Indy ledger node or other technical network role (issuer, verifier, agent or agency) onto the community to onboard. 

All Sandbox nodes are supposed to function as consensus validators (also known as Stewards in Sovrin terminology) and MUST agree to lightweight governance rules set in future sandbox governance package (see below). 

Due to existing circumstances with pseudonymous identifiers of natural persons and new privacy regulation in EU (General Data Protection Regulation, 2016/679) legal entities that choose to be present on the permanent test ledger with their public identifier (DID) or will be writing information to the ledger through their Agents are expected to be cautious in use of the ledger for storing permanent identifiers, and adhere to a specific code of conduct when testing their services in the Sandbox. 

Open-to-all development ledger will be reset infrequently, so it's intended for quick testing, not for hosting permanent pilots with their data.

<!--
Findy does not initially provide a wallet/agent or agency project, service developers are for starters referred to the Aries agent community's [code assets](https://github.com/hyperledger/aries) and development tools recommended therein.
-->

# Findy as a Production Ledger
Future Production Ledger will be scaled technically to be robust and secure enough for public, commercial SSI services. Thus, it will have stringent uptime and SLA requirements and business liabilities set for the operators of its validator nodes. Governance will follow the future Findy Operational Governance Rulebook.


# Governance Agreements
FIndy Governance Framework will specify governance agreements for a) **business and legal** and b) **operative and technical governance** of the ledger infrastructure operations, agent providers and cloud agencies, separate agreements package being used for Sandbox and Production environments. Former will be lightweight and promote easy access to building pilots, but will define a liability for gross misuse of the environment.

Web links to the rulebooks and legal agreements will be added to this document as they become available. Rulebook work defining the agreements is starting in second half of 2019. 

Specific Governance Agreements can be applied for various services in need of domain-specific (vertical) governance agreements, that would control individual trust roles and semantic data models of domain-specific verifiable credentials. When such services use the ledger infrastructure of Findy they need to ensure compliance with the underlying (baseline) infrastructure governance rules, and this is enforced within the role specific agreements. Initial list of agreements below is indicative only.


## Sandbox Governance

Findy Consortium Agreement (Findy CA and General Rules of the Sandbox) - TBA

<!--
[Business and Legal Agreement Draft 2019](https://github.com/TrustNetFI/FIndy/blob/master/Docs/Sandbox-FIndy-Business-and-Legal-Agreement.md)
-->

<!--
[Technical Steward Agreement Draft 2019](https://github.com/TrustNetFI/FIndy/blob/master/Docs/Sandbox-FIndy-Technical-Agreement.md)
-->

## Production Governance

Business and Legal Entity Agreement (Findy Network Rulebook) - TBA

Findy Steward Agreement  - TBA
Findy Agency Agreement - TBA
Findy Edge Agent Agreement - TBA



<!-- 
## Welcome to GitHub Pages
You can use the [editor on GitHub](https://github.com/TrustNetFI/FIndy-pages/edit/master/README.md) to maintain and preview the content for your website in Markdown files.
Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.
### Markdown
Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for
```markdown
Syntax highlighted code block
# Header 1
## Header 2
### Header 3
- Bulleted
- List
1. Numbered
2. List
**Bold** and _Italic_ and `Code` text
[Link](url) and ![Image](src)
```
For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
### Jekyll Themes
Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/TrustNetFI/FIndy-pages/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.
### Support or Contact
Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
-->
