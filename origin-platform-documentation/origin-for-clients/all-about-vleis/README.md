# All about vLEIs

A vLEI is a special category of [digital credential](../../../glossary.md#digital-credential) that's used to create strong identity for organizations and their staff members. See [Problems solved by vLEIs](problems-solved-by-vleis.md) and [Types of vLEIs](types-of-vleis.md) for details.

## The vLEI journey

When an organization wants to get and begin using vLEIs, it must provide formal answers to certain questions that are intended to guarantee internal alignment and very strong security:

1. Who will the org work with to get its vLEIs?

This question is answered by choosing a [QVI](types-of-vleis.md#qvi-vleis) that has the software and expertise to help. Choosing a QVI wisely can make the rest of the process much easier. Different QVIs charge different fees for their services. It is possible to switch QVIs partway through the journey, but it is not convenient. You can find a listing of QVIs in Origin's [Service provider directory](../service-provider-directory.md) or by contacting [qvi@gleif.org](mailto:qvi@gleif.org).&#x20;

2. Who is empowered to make vLEI-related decisions and incur vLEI-related, contractual accountability on behalf of the org?

This person is called a _Designed Authorized Representative_, or _DAR_, by GLEIF. Essentially, they act as a trusted project coordinator. The answer to the DAR question must be given to the QVI that's facilitating issuance, and it must be backed by strong evidence as described in GLEIF's governance framework. The CEO of a company could be the DAR, or the CEO could designate a manager in the legal or IT department to function as the company's DAR. The DAR undergoes strong NIST-IAL2 identity verification.

3. Who will participate in a committee that jointly manage's the org's cryptographic identity?

With internet domains, an IT employee typically works with a registrar to register the domain. With vLEIs, the standard is much higher. Unless a company is a sole proprietorship where only one person can practically participate, GLEIF requires companies to have multiple members of this committee. The committee uses business rules to decide what constitutes a valid decision of the committee, such as "A majority is always required." The DAR articulates to the QVI its desired members of this committee.

People nominated by the DAR for this role are called _Legal entity Authorized Representatives_, or _LARs_. LARs undergo strong [NIST-IAL2](https://pages.nist.gov/800-63-3-Implementation-Resources/63A/ial2remote/) identity verification, and each LAR receives a cryptographic wallet that they will use to manage at least the keys associated with this job.

Once LARs are ready, the QVI and the LARs attend a ceremony. At this ceremony, the QVI supervises the creation of a cryptographic multisig group that represents the committee and its decision-making policies. The QVI then issues an LE vLEI, a copy of which is held by each member of the committee. This LE vLEI cannot be used directly except by the committee as a group, functioning under whatever decision-making policies it chose for itself. However, the committee can use the LE vLEI to delegate authority that is much easier to use (e.g., to individual employees or to automated processes that represent the org).

4. Who will receive OOR vLEIs?

See [this discussion](types-of-vleis.md#oor-vlei) about which corporate officers might need this type of credential. Anyone at an org can propose someone to receive an OOR, but LARs must approve. They do this by acting as a committee to issue to the QVI an auth credential documenting their organization's intent. Also, evidence of the person's role must satisfy GLEIF requirements. The QVI does the issuance.

5. Who will receive ECR vLEIs, and who will issue them?

Anybody who is affiliated with a company but who does not have a role matching the OOR profile is eligible to receive an ECR. See [this discussion](types-of-vleis.md#ecr-vlei) for details. Either the QVI or the org itself can be the issuer. QVIs can help orgs learn the process.

6. What maintenance is needed?

The relationships between organizations and people are dynamic. Policies change. Companies merge or divest. Keys get compromised. All of these events may require maintenance of an organization's vLEIs.

vLEIs never expire. However, the LEI on which a vLEI is based has to be renewed regularly, re-attesting to the correctness of the metadata about the legal entity. If an LEI lapses, all of the organization's vLEIs must be revoked by the QVI. Therefore, it is important for the organization to keep its LEI registration current. This is the minimum required maintenance for vLEIs.

If a person leaves an org, any OOR or ECR vLEI they hold should be revoked. If the org changes its mind about the makeup or approval policies of the committee of its LARs, cryptographic operations can formalize the changes.

In general, whoever approved the creation of an approval is also the party (or the committee of individuals) that must effect the changes.





