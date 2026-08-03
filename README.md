# Band Protocol

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

Band Protocol is a cross-chain data oracle platform that aggregates and connects real-world data
and APIs to smart contracts. Built on BandChain, a high-performance Cosmos SDK blockchain with
Tendermint BFT consensus, it enables developers to query price feeds, oracle scripts, data
requests, and verifiable random numbers for use in decentralized applications across multiple
blockchains.

## APIs

- **BandChain REST API** - HTTP access to oracle data, price feeds, validators, accounts, and all Cosmos SDK modules via `https://laozi1.bandchain.org/api`
- **BandChain gRPC API** - Protocol buffer access to all BandChain modules via `https://laozi1.bandchain.org`
- **BandChain Testnet REST API** - Sandbox environment via `https://band-v3-testnet.bandchain.org/api` with faucet
- **BandChain.js SDK** - TypeScript/JavaScript library (`@bandprotocol/bandchain.js`) for querying and transacting
- **PyBand SDK** - Python library (`pyband`) for gRPC-based BandChain interaction
- **Band VRF** - Verifiable random function for on-chain randomness
- **Band Standard Dataset** - Price feed standard for DeFi integrations

## Resources

- [Documentation](https://docs.bandchain.org)
- [API Endpoints](https://docs.bandchain.org/develop/api-endpoints)
- [GitHub](https://github.com/bandprotocol)
- [Block Explorer](https://www.cosmoscan.io/)
- [Discord](https://discord.gg/3t4bsY7)
