---
title: "Sector Recovery"
url: "/systems/filecoin_mining/sector/sector-recovery/"
date: "2001-01-01"
feed_url: "https://spec.filecoin.io/index.xml"
---
Sector Recovery State reliable Theory Audit wip Edit this section section-systems.filecoin_mining.sector.sector-recovery Miners should try to recover faulty sectors in order to avoid paying the penalty, which is approximately equal to the block reward that the miner would receive from that sector. After fixing technical issues, the miner should call RecoveryDeclaration and produce the WindowPoSt challenge in order to regain the power from that sector. Note that if a sector is in a faulty state for 42 consecutive days it will be terminated and the miner will receive a penalty.
