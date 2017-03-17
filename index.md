---
layout: default
title: BitcoinEC
---

# FAQ

**Why are you creating a separate project instead of developing this as part of the Bitcoin Unlimited project?**

We originally discussed developing a minimal patchset as part of Bitcoin Unlimited, however members recommended developing the minimal patchset under a separate project.

**Is Bitcoin Unlimited supportive of this project?**

A number of Bitcoin Unlimited members have expressed support for this project as it can potentially bring Emergent Consensus to a wider userbase.

**Why are you making a patchset on top of Core?**

Recent events have shown that Bitcoin Unlimited is not stable enough to be used in production without significantly more testing and code review in addition to major changes in how the project is managed, by building a patchset on top of Core we are able to bring Emergent Consensus to a stable production ready codebase.

**What version of Bitcoin Core will this be based off of?**

This will be based off of the latest stable version of Bitcoin Core which is currently 0.14.

**Will BitcoinEC include SegWit?**

Yes, we feel that too much of the industry has invested in SegWit to try and oppose it at this point, it may not be perfect but it's been tested for a while and there don't appear to be any major technical issues.

**What about the Witness Discount, isn't that a huge economic change to Bitcoin?**

We will have emergent consensus parameters both for the serialized block size and the block weight, this effectively makes the witness discount irrelevant while at the same time being simpler than removing it entirely. It also makes it so that we are compatible with Bitcoin Core initially.

**Will you also have an AD(Accept Depth) parameter like Bitcoin Unlimited?**

Instead of Accept Depth we will implement a warning system to alerts users if they are not on the longest chain. Implementing AD in the way BU has done appears to be fairly complicated and hard to do correctly, a warning system is simple since we only need the block headers for that.

**How can I get involved?**

We have a [public slack](https://bitcoinec.herokuapp.com/) that you can join.