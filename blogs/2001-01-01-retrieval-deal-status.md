---
title: "Retrieval Deal Status"
url: "/systems/filecoin_markets/retrieval_market/deal_status/"
date: "2001-01-01"
feed_url: "https://spec.filecoin.io/index.xml"
---
Retrieval Deal Status State stable Theory Audit n/a Edit this section section-systems.filecoin_markets.retrieval_market.deal_status Example: package retrievalmarket import "fmt" // DealStatus is the status of a retrieval deal returned by a provider // in a DealResponse type DealStatus uint64 const ( // DealStatusNew is a deal that nothing has happened with yet DealStatusNew DealStatus = iota // DealStatusUnsealing means the provider is unsealing data DealStatusUnsealing // DealStatusUnsealed means the provider has finished unsealing data DealStatusUnsealed // DealStatusWaitForAcceptance means 
