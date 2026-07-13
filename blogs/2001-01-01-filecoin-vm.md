---
title: "Filecoin VM"
url: "/intro/filecoin_vm/"
date: "2001-01-01"
feed_url: "https://spec.filecoin.io/index.xml"
---
Filecoin VM State reliable Theory Audit n/a Edit this section section-intro.filecoin_vm The majority of Filecoin’s user facing functionality (payments, storage market, power table, etc) is managed through the Filecoin Virtual Machine (Filecoin VM). The network generates a series of blocks, and agrees which ‘chain’ of blocks is the correct one. Each block contains a series of state transitions called messages, and a checkpoint of the current global state after the application of those messages.
