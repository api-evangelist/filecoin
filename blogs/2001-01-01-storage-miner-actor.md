---
title: "Storage Miner Actor"
url: "/systems/filecoin_mining/storage_mining/storage_miner_actor/"
date: "2001-01-01"
feed_url: "https://spec.filecoin.io/index.xml"
---
Storage Miner Actor State wip Theory Audit done Edit this section section-systems.filecoin_mining.storage_mining.storage_miner_actor Example: Storage Miner Actor State Balance of Miner Actor should be greater than or equal to the sum of PreCommitDeposits and LockedFunds. It is possible for balance to fall below the sum of PCD, LF and InitialPledgeRequirements, and this is a bad state (IP Debt) that limits a miner actor’s behavior (i.e. no balance withdrawals) Excess balance as computed by st.
