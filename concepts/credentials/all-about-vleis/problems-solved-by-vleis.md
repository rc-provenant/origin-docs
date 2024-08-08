---
description: why vLEIs were invented, and what problems they solve
---

# Need

The lock icons in our browser address bar supposedly prove who we're talking to online:

<figure><img src="../../../.gitbook/assets/amazon-lock-icon.png" alt=""><figcaption></figcaption></figure>

However, massive frauds driven by smishing and phishing attacks, and the debacle of Elon Musk's blue checkmark program, both prove one thing: _the world has a problem with organizational identity_. Billions of dollars are lost because innocent victims mistake scammers for a reputable company. It's a problem for them, it's a problem for the company whose reputation is abused, and increasingly, it's a problem for government regulators.

This is not news. The G20's Regulatory Oversight Committee reached this conclusion after the financial collapse of 2008-2010, and formed an international non-profit called [GLEIF](https://gleif.org). They charged GLEIF to create a reliable, unique identifier for legal entities that do international business — the legal entity identifier or LEI — and to offer exactly one LEI to each legal entity. An LEI now tell us which identity is under discussion, and it's useful all over the world. When we reference a company named "Provenant", we mean [the organization identified by LEI 984500983AD71E4FBC41 on GLEIF's website](https://search.gleif.org/#/record/984500983AD71E4FBC41):

<figure><img src="../../../.gitbook/assets/Provenant LEI record.png" alt=""><figcaption></figcaption></figure>

But by itself, an LEI is only half a solution. Scammers can reference an LEI just as easily as the LEI's true owner can.

What completes the solution is a digital credential that provides cryptographic proof of an association between a party in cyberspace and a legal entity and its LEI, in the physical and legal world. This is the purpose of vLEIs. Organizations that use vLEIs properly are almost impossible for a scammer to impersonate. vLEIs thus protect an organization's reputation, and its customers.
