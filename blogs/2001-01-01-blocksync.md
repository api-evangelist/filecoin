---
title: "BlockSync"
url: "/algorithms/block_sync/"
date: "2001-01-01"
feed_url: "https://spec.filecoin.io/index.xml"
---
BlockSync State stable Theory Audit n/a Edit this section section-algorithms.block_sync Name: Block Sync Protocol ID: /fil/sync/blk/0.0.1 BlockSync is a simple request/response protocol that allows Filecoin nodes to request ranges of Tipsets from each other, when they have run out of sync, e.g., during downtime. Given that the Filecoin blockchain is extended in Tipsets (i.e., groups of blocks), rather than in blocks, the BlockSync protocol operates in terms of Tipsets.
