---
description: Flow of Verified.
---

# 🔃 Frontend Flow

{% content-ref url="1.-verified.md" %}
[1.-verified.md](1.-verified.md)
{% endcontent-ref %}

{% content-ref url="verified.md" %}
[verified.md](verified.md)
{% endcontent-ref %}

{% content-ref url="flagged.md" %}
[flagged.md](flagged.md)
{% endcontent-ref %}

{% content-ref url="unknown-greater-than-register.md" %}
[unknown-greater-than-register.md](unknown-greater-than-register.md)
{% endcontent-ref %}

<img src="../.gitbook/assets/file.excalidraw.svg" alt="" class="gitbook-drawing">

## **Search:**

After the user pastes an `ERC20` address, the following happens:\


1. Verified App checks `ERC20` address for **Soulbound-NFT Certificates**.
2. The results are shown as one of three things:
   1. The address is verified ✔️
   2. The address is flagged :exclamation:
   3. The address is unknown and may be verified/flagged.

### **View **<mark style="color:red;">**flagged**</mark>**/**<mark style="color:green;">**verified**</mark>** addresses:**

Display a list of verified or flagged addresses

### **Print `ERC115` Soulbound-NFT:**

Links the user to Etherscan- Flagged or Verified Soulbound-NFT.
