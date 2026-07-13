---
title: "Adding Storage"
url: "/systems/filecoin_mining/sector/adding_storage/"
date: "2001-01-01"
feed_url: "https://spec.filecoin.io/index.xml"
---
Adding Storage State stable Theory Audit wip Edit this section section-systems.filecoin_mining.sector.adding_storage A Miner adds more storage in the form of Sectors. Adding more storage is a two-step process: PreCommitting a Sector: A Miner publishes a Sector’s SealedCID, through miner.PreCommitSector of miner.PreCommitSectorBatch, and makes a deposit. The Sector is now registered to the Miner, and the Miner must ProveCommit the Sector or lose their deposit.
