# Types of vLEIs

## LE vLEI

The prototypical example of a vLEI is one issued to a legal entity (e.g., a company, government, or non-profit). It declares the LEI of that entity and tells what cryptographic evidence constitutes strong proof of ownership for it. This is the _Legal Entity vLEI_ or _LE vLEI_ for short, and it is top of mind in most vLEI discussions. If you hear someone talking about a vLEI without specifying a type, the LE vLEI is probably what they intend.

## OOR vLEI

Another type of vLEI is issued to people whose roles at an organization include rights or responsibilities that are defined in the legal code where the legal entity is incorporated. For example, in many jurisdictions, a CEO and CFO — and not different corporate roles like Head of Accounting — must sign quarterly reports to government financial regulators. In fulfilling this duty, the CEO and the CFO accept legally mandated accountability for their individual and corporate actions.&#x20;

This is the _Official Organizational Role vLEI_ or _OOR vLEI_ for short. OOR vLEIs are issued to specific individuals who have undergone strong identity assurance, meeting or exceeding the requirements of [NIST IAL2](https://pages.nist.gov/800-63-3-Implementation-Resources/63A/ial2remote/), and whose roles with a company are declared in a way that is legally provable to the public. The roles in a given organization that might need an OOR vLEI are largely defined in the ISO 5009 standard, and are [published on GLEIF's website](https://www.gleif.org/en/about-lei/code-lists/iso-5009-official-organizational-roles-code-list). Some roles that are associated with OOR vLEIs in many jurisdictions include CEO, CFO, Board Chair, Chief Counsel, and Shareholder.

OOR vLEIs chain back to the LE vLEI of the organization with which the individual is associated.

## ECR vLEI

The most abundant type of vLEI is issued to people whose roles at an organization are _defined by the organization itself_, without reference to any legal requirements. These roles are not necessarily _less important_ than OOR roles; they are just _more flexible_. Director of IT, Senior Vice President of Human Resources, Chief Scientist, Product Manager, Quality Assurance Engineer, Senior Detective, Tech Evangelist, and many other job titles are likely to fit into this category.

This is the _Engagement Context Role vLEI_ or _ECR vLEI_ for short. ECR vLEIs are essentially employee credentials, but unlike many other employee credential schemes, they are only issued to individuals who have undergone strong identity assurance, and they chain back to the LE vLEI of the organization with which the individual is associated. This rigor makes them far better sources of proof that an individual with a particular legal identity has a named role at a given organization.

## QVI vLEIs

Who issues all these credentials?

GLEIF defined a certification program for organizations that want to perform issuance under the stringent guidelines of their ecosystem governance framework. Organizations who pass annual certification are called Qualified vLEI Issuers, and are given a Qualified vLEI Issuer vLEI or QVI vLEI for short, to prove this status.

QVIs are the only organizations that are allowed to issue LE vLEIs or OOR vLEIs. QVIs may also issue ECR vLEIs, but legal entities may also issue ECR vLEIs themselves, without a QVI, as long as they follow GLEIF rules when doing so.
