---
title: "Retrieval Peer Resolver"
url: "/systems/filecoin_markets/retrieval_market/retrieval_peer_resolver/"
date: "2001-01-01"
feed_url: "https://spec.filecoin.io/index.xml"
---
Retrieval Peer Resolver State stable Theory Audit n/a Edit this section section-systems.filecoin_markets.retrieval_market.retrieval_peer_resolver The peer resolver is a content routing interface to discover retrieval miners that have a given Piece. It can be backed by both a local store of previous storage deals or by querying the chain. // PeerResolver is an interface for looking up providers that may have a piece type PeerResolver interface { GetPeers(payloadCID cid.Cid) ([]RetrievalPeer, error) // TODO: channel }
