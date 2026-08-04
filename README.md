# Filecoin

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
