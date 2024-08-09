---
description: ways you can use vLEIs, once you have them
---

# Uses

Here are some ways to use vLEI credentials:

* You can present them to remote parties to prove things about your organization or yourself. (In Origin's Hold view, select Present.)
* You can [act as a verifier](https://github.com/GLEIF-IT/vlei-verifier), confirming the validity of and the data within the vLEIs of others.
* In an interaction, you can use them to prove that your organization and/or people with specific roles in your organization are participating.
* You can use them in conjunction [with ordinary digital signatures](../../../tasks/what-it-means-to-sign-with-a-vlei.md#simple-mode) on files, email attachments, social media posts, and similar things.
* You can use them to sign XBRL for regulatory compliance purposes. See the XBRL signing application on Origin.
* You can associate them with your [SPF/DKIM/DMARC](https://www.cloudflare.com/learning/email-security/dmarc-dkim-spf/) solution to increase the security of your corporate email solution.
* You can create and issue new credential types, chain them to vLEIs, and verify them. For example, you could build solutions on top of:
  * [face-to-face credentials](https://github.com/provenant-dev/public-schema/blob/main/face-to-face/index.md), documenting a personal, non-remote interaction you've had with another human so they can prove they are not an AI
  * [proof-of-control credentials](https://github.com/provenant-dev/public-schema/blob/main/proof-of-control/index.md), showing that a person or org controls an email address, a social media handle, a phone number, DNS records, or similar resources
  * [generalized cooperative delegation credentials](https://github.com/provenant-dev/public-schema/blob/main/gcd/index.md), authorizing a person or org to act in your behalf under carefully described constraints
  * [award credentials](https://github.com/provenant-dev/public-schema/blob/main/award/index.md), conferring official recognition of various kinds on someone else

Today, many of these operations require custom code to be written, because shrink-wrapped products with the right features are still being developed. We expect the ecosystem to mature rapidly in coming months. Ask your QVI or another service provider for help.
