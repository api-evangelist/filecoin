---
title: "Verifiable Random Function"
url: "/algorithms/crypto/vrf/"
date: "2001-01-01"
feed_url: "https://spec.filecoin.io/index.xml"
---
Verifiable Random Function State incorrect Theory Audit n/a Edit this section section-algorithms.crypto.vrf Filecoin uses the notion of a Verifiable Random Function (VRF). A VRF uses a private key to produce a digest of an arbitrary message such that the output is unique per signer and per message. Any third party in possession of the corresponding public key, the message, and the VRF output, can verify if the digest has been computed correctly and by the correct signer.
