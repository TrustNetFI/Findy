# What is FIndy?

![SSI-logo](https://raw.githubusercontent.com/TrustNetFI/FIndy/master/img/SSI-logo.png)

FIndy stands for Finnish Indy network, a locally governed and run decentralised ledger. Its target is to enable pilot use cases and services with use of self-sovereign identifiers in Finland. Operation of the ledger is facilitated by FIndy community, whose members commit to running the ledger operations according to their roles and liabilities. 

A decentralised identity ledger consists of a limited set of public, permissioned nodes that when run together as a decentralised system are responsible for 
- running the cryptographic consensus algorithm that provides non-repudiation of public identifiers
- catering the discovery of public decentralised identifiers and their related public statement documents
- enabling privacy-preserving tools (revocation accumulators) for revocation checks

The FIndy ledger, run first as a test network and sandbox for pilots, appended eventually with a production version for commercial use potentially with a different name, will be operated and coordinated by local legal entities that i) commit to maintain the network and its nodes along the initial FIndy governance rules under development during 2018, and ii) agree to work in good faith towards setting up a joint, long-term ledger infrastructure project that stands responsible for operating the distributed ledger. 

From technical standpoint the ledger is based on open source decentralised ledger technology from Linux Foundation’s [Hyperledger Indy](https://www.hyperledger.org/projects/hyperledger-indy) project. Whilst no infrastructure project exists in the industry yet, the [TrustNet project](http://trustnet.fi/) is facilitating agile coordination and governance materials creation for FIndy during 4Q of 2018. 

For more information or to register your participation in setting up FIndy, contact [harri.honko@tut.fi](smtp://harri.honko@tut.fi), Tel. [+358 40 5331437](tel:+358-40-5331437).

Test version of the ledger is assumed to be operational by 3-4 December 2018, at Slush 2018, and target is to release a public web site and PR about FIndy at that time.


# FIndy as a test sandbox
FIndy’s first realisation is intended to enable joint R&D testing of industry and public sector origin SSI service concepts in a safe Sandbox environment. Services can be dealing with publishing identifiers and related data to ledger, issuing verifiable credentials, or providing access control to data sources (such as data behind an API) through end user wallet services.

All FIndy nodes in the test network are supposed to function as consensus validators (also known as Stewards in Sovrin terminology) and therefore need to agree to the governance rules set in agreements package known as Sandbox FIndy Trust Framework. 

Due to existing circumstances with pseudonymous identifiers of natural persons and new privacy regulation in EU (General Data Protection Regulation, 2016/679) entities that choose to be present on the ledger with their public identifier (DID) or will be writing information to the ledger through their Indy agent are expected to be cautious in use of the ledger for storing permanent identifiers, and adhere to a specific code of conduct when testing their services in the Sandbox.

FIndy does not provide a wallet/agent project, service developers are here referred to the Indy community and development tools available therein.


# FIndy as a production ledger
Future production version is going to be scaled technically to be robust and secure enough for public, commercial SSI services. Thus, it will have stringent uptime and SLA requirements and business liabilities set for the operators of production ledger nodes. The Production ledger governance agreements, ‘FIndy Production Trust Framework Agreements’ will be developed during 2019-20.


# Governance agreements
FIndy Trust Framework will specify governance agreements for a) **business/legal** and b) **technical** governance of the ledger infrastructure operations, separate agreements package being used for Sandbox and Production environments. 

Web links to the agreements will be added below as they become available. 

Specific Trust Framework Agreements can be applied for various services in need of domain specific (vertical) trust agreements, that would control trust roles and semantic models of domain specific credentials. When such services use the ledger infrastructure of FIndy they need to ensure their use is compliant with the underlying infrastructure’s governance.

## Sandbox governance - Sandbox FIndy Trust Framework

[Business and Legal Agreement Draft 2018](https://github.com/TrustNetFI/FIndy/blob/master/Docs/Sandbox-FIndy-Business-and-Legal-Agreement.md)

[Technical Agreement Draft 2018](https://github.com/TrustNetFI/FIndy/blob/master/Docs/Sandbox-FIndy-Technical-Agreement.md)

## Production governance

Business and Legal Agreement - N/A

Technical Agreement - N/A


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