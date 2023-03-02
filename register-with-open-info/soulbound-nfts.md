---
description: The perfect source of truth.
---

# ⛓ Soulbound NFTs

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

## The benefits

The Soulbound non-fungible token (NFT) is a **unique** digital asset that is used by the Open Information movement for certification, verifying information, and flagging malicious actors. It is a specialized type of NFT that is designed to be tamper-proof and resistant to forgery, making it ideal for use in situations where trust and verification are critical.

## `ERC-721` and deviations

To ensure the interoperability of Soulbound NFTs across different platforms and ecosystems, the Open Information movement has adopted the ERC-721 standard with soulbound deviations. ERC-721 is a widely used standard for non-fungible tokens on the Ethereum blockchain, and it provides a set of guidelines and rules for creating and managing NFTs.

{% hint style="info" %}
<mark style="color:blue;">Soulbound NFTs</mark> are irrefutable:

* they can always be openly verified on the blockchain.&#x20;
* They are unique and&#x20;
* cannot be duplicated or transferred.&#x20;
{% endhint %}

The deviations from the ERC-721 standard are the owner's inability to transfer or burn the token from their address. Open Information reserves the sole right to approve the minting or burning of any given address. The contract owner is referred to here as the Open Information Custodian.&#x20;

## Metadata

By using the ERC-721 standard, Soulbound NFTs can also be easily integrated with other applications and platforms that support ERC-721 tokens, expanding their usefulness and potential applications.&#x20;

The standard metadata JSON for an Open Information Verified or Flagged Soulbound NFT:

```json
{
  "image": "https://vrfd.info/[ADDRESS]",
  "external_url": "https://vrfd.info/[ADDRESS]",
  "name": "[ADDRESS || ENS-DOMAIN].VRFD",
  "description": "[ADDRESS] has been [verified || flagged] by Open-Info, with a Souldbound-NFT.",
  "Attributes": [
    {
      "trait_type": "VRFD?",
      "value": "['VRFD 🗸' || 'FLAGGED X']"
    },
    {
      "trait_type": "upvotes",
      "value": "22"
    },
    {
      "trait_type": "downvotes",
      "value": "12"
    }
  ]
}
```

## Source

\[1] See the [Git repository](https://github.com/Open-Info/Soulbound-NFTs) containing the source code of the smart contracts used by Open Information
