---
description: Flow of Verified.
---

# 🔃 Frontend Flow

{% content-ref url="1.-verified.md" %}
[1.-verified.md](1.-verified.md)
{% endcontent-ref %}

## **Search:**

After the user pastes an address, the following happens:\


1. A web3 call is made and the address metadata is returned.
2.  The results are shown as one of three things:

    ✔️ The address is verified\
    :exclamation: The address is flagged, or\
    :grey\_question: The address is unknown, optionally register it.

{% content-ref url="verified.md" %}
[verified.md](verified.md)
{% endcontent-ref %}

{% content-ref url="flagged.md" %}
[flagged.md](flagged.md)
{% endcontent-ref %}

<img src="../.gitbook/assets/file.excalidraw.svg" alt="" class="gitbook-drawing">

{% content-ref url="unknown-greater-than-register.md" %}
[unknown-greater-than-register.md](unknown-greater-than-register.md)
{% endcontent-ref %}

### **View all verified/flagged addresses:**

Display a list of verified or flagged addresses

### **Print `ERC1155` Soulbound NFT:**

Links the user to Flagged or Verified Soulbound NFT on EtherScan.
