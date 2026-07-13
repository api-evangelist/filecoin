---
title: "Stacked DRG - Offline PoRep Circuit Spec"
url: "/algorithms/porep-old/stacked_drg_circuit/"
date: "2001-01-01"
feed_url: "https://spec.filecoin.io/index.xml"
---
Stacked DRG - Offline PoRep Circuit Spec State Theory Audit Edit this section section-algorithms.porep-old.stacked_drg_circuit Stacked DRG PoRep is based on layering DRG graphs LAYERS times. The data represented in each DRG layer is a labeling based on previously labeled nodes. The final labeled layer is the SDR key, and the ‘final layer’ of replication the replica, an encoding of the original data using the generated key.
