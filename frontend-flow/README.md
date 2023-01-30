---
description: Flow of the ERC20 Address verification made by Open Information.
---

# Frontend Flow

**Search:**\
After the user pastes a `ERC20` address, the following happens:\
1\. Verified App checks `ERC20` address for **Soulbound-NFT Certificates**.\
2\. The results are shown as one of three things:
  - The adresss is verified ✔️
  - The address is flagged :exclamation:
  - The address may be verified/flagged.\
\
**Top**<mark style="color:red;">**flagged**</mark>**/**<mark style="color:green;">**verified**</mark>**:** \
Load Balanced, [graphing-db.md](../backend/graphing-db.md "mention") query via [scala.md](../backend/scala.md "mention") for all flagged addresses (loaded in chunks, on scroll).\
\
**Print ERC752 Verified NFT:**\
Links the user to Etherscan flagged or verified Soulbound-NFT.\
