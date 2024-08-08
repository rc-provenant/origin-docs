---
description: how different digital credential formats relate to one another
---

# Formats

Cryptography can be used to create digital versions of credentials. X509 certificates are a familiar example of first-generation digital credentials.

About a decade ago, work began on a second generation of digital credentials that solves some centralization and maintenance problems. This technology is called _verifiable credentials_, and is associated with [AnonCreds](https://hyperledger.github.io/anoncreds-spec/), the [ISO mobile driver's license spec](https://www.iso.org/standard/69084.html), and the [W3C verifiable credential spec](https://www.w3.org/TR/vc-data-model/). Origin can help support these technologies. However, the focus of Origin is a third generation of digital credentials called [ACDCs](https://trustoverip.github.io/tswg-acdc-specification/).

ACDCs have a richer and more flexible data model than simple VCs. They are more efficient with storage and network, and they are significantly more secure. They support more sophisticated signing, delegation, and revocation patterns. They are post-quantum ready. And they can also be used to create or cite verifiable data chains that are not intended to grant privileges (e.g., provably sourced scientific data or journalism, scholarly citations, financial or legal evidence). Although we might still casually refer to ACDCs as "credentials", ACDCs use cases are much broader.



<figure><img src="../../.gitbook/assets/credentials-and-similar.png" alt=""><figcaption></figcaption></figure>

Because ACDCs are not always issued to an individual human owner who wants privileges, we prefer the generic term _issuee_ rather than _holder_ to describe the party that receives them.
