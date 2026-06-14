# Filecoin

Filecoin is the world's largest decentralized storage network, providing
cryptographically verifiable storage backed by a global network of storage
providers. Developers access the network through the Glif-hosted Lotus
JSON-RPC API, the Filecoin HTTP REST API, and built-in actor methods exposed
via the Filecoin Virtual Machine (FVM).

## APIs

| API | Base URL | Description |
|-----|----------|-------------|
| Glif Lotus JSON-RPC (mainnet) | `https://api.node.glif.io/rpc/v1` | Full Filecoin and Ethereum-compatible RPC |
| Glif Lotus JSON-RPC (calibration) | `https://api.calibration.node.glif.io/rpc/v1` | Testnet JSON-RPC |
| Filecoin HTTP REST API | `http://127.0.0.1:3453/api/chain/v0` | REST interface for chain, actors, deals |
| Protocol Actor API | via Lotus RPC | Built-in actor methods (FVM) |
| Filecoin Onchain Cloud (Synapse) | `https://filecoin.cloud/` | Programmable on-chain storage |
| Filrep.io Storage Provider API | `https://api.filrep.io/` | Miner reputation and discovery |

## Resources

- [Developer Docs](https://docs.filecoin.io/)
- [Protocol Specification](https://spec.filecoin.io/)
- [RPC Providers](https://docs.filecoin.io/networks-and-tools/networks/mainnet/rpcs)
- [Built-in Actor API Reference](https://docs.filecoin.io/reference/built-in-actors/protocol-api)
- [Filecoin HTTP REST API Spec](https://filecoin-project.github.io/filecoin-http-api/)
- [Glif GitHub](https://github.com/glifio)
- [Filecoin Project GitHub](https://github.com/filecoin-project)
- [Filrep.io](https://filrep.io/)
- [Blog](https://filecoin.io/blog/)
- [Status](https://status.filecoin.io/)

## Profile

- `apis.yml` — APIs.json 0.19 provider profile
- `plans/plans.yml` — Pricing and plan information
- `rate-limits/rate-limits.yml` — Rate limit details
- `finops/finops.yml` — Cost and budget control information
