---
title: "GossipSub"
url: "/algorithms/gossip_sub/"
date: "2001-01-01"
feed_url: "https://spec.filecoin.io/index.xml"
---
GossipSub State stable Theory Audit done Edit this section section-algorithms.gossip_sub Messages and block headers alongside the message references are propagated using the libp2p GossipSub router. In order to guarantee interoperability between different implementations, all filecoin full nodes must implement and use this protocol. All pubsub messages are authenticated and must be syntactically validated before being propagated further.
