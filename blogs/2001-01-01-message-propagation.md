---
title: "Message Propagation"
url: "/systems/filecoin_blockchain/message_pool/message_syncer/"
date: "2001-01-01"
feed_url: "https://spec.filecoin.io/index.xml"
---
Message Propagation State stable Theory Audit n/a Edit this section section-systems.filecoin_blockchain.message_pool.message_syncer The message pool has to interface with the libp2p pubsub GossipSub protocol. This is because messages are propagated over GossipSub the corresponding /fil/msgs/ topic. Every Message is announced in the corresponding /fil/msgs/ topic by any node participating in the network.
