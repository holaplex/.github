
<p align="center">
  <img src="img/holaplex-avatar.png" width="250px" />
</p>

<h2 align="center">The best way to experiment & explore with NFTs.</h2>

The Holaplex Hub provides a collection of loosely coupled microservices that make it easy to launch NFT campaigns, mint digital collectibles, run loyalty programs, and more. With Hub and developer APIs, no matter what industry you're in, you can explore the possibilities of NFTs.

## Getting Started

Visit our docs site at [https://docs.holaplex.dev](https://docs.holaplex.dev) to read useful guides and review our API reference.

## Services Catalogue

Hub is built on a shared [Redpanda](https://redpanda.com/), which is a streaming data platform that is compatible with Kafka. Each of the services within the Hub has its own [GraphQL API](https://graphql.org/), which means that there are multiple APIs to interact with. However, these APIs are stitched together using the [Apollo Federated Router](https://www.apollographql.com/docs/router/) to form a single API endpoint. This makes it easier for developers to interact with the Hub without having to deal with multiple APIs separately. The use of the Redpanda cluster ensures that the messages emitted and processed by the Hub are reliable and scalable.

- [Hub Console](https://github.com/holaplex/hub) - A user-friendly management console for interacting with the Hub API.
- [Hub NFTs](https://github.com/holaplex/hub-nfts) -  Enables the minting and indexing of NFT campaigns on multiple blockchains, with support for cross-chain interoperability.
- [Hub Orgs](https://github.com/holaplex/hub-orgs) - Catalogs all organizations, projects, and memberships for the Hub, enabling easy management of your team and NFT campaigns.
- [Hub Treasuries](https://github.com/holaplex/hub-orgs) - Allows the creation of custodial wallets using Fireblocks, as well as the submission of blockchain transactions using Hub custodial wallets.
- [Hub Customers](https://github.com/holaplex/hub-customers) - Offers customer references that receive a treasury for storing crypto wallets, enabling easy management of customer data and resources.
- [Hub Permissions](https://github.com/holaplex/hub-permissions) - Manages all permission relationships for the Hub, leveraging Ory Keto for easy access control and delegation of authority.
- [Hub Identities](https://github.com/holaplex/hub-identities) - Manages all identities for the Hub, with a GraphQL API for Ory Kratos. This allows for easy management of user accounts and authentication.
- [Hub Credentials](https://github.com/holaplex/hub-credentials) - Enables the creation of API credentials for Hub, with a GraphQL API for Ory Hydra. This allows for secure and easy integration of external applications with the Hub API.
- [Hub Webhooks](https://github.com/holaplex/hub-webhooks) - Receive webhook events as Hub resources change, using the Svix webhooks service. This enables easy integration with external systems and services, and enables real-time updates of Hub resources.

## Starter Projects 

Kick off your Hub journey with these ready-to-use project templates designed to help you learn and experiment with the Holaplex Hub API.


- [Hub Starter Mint](https://github.com/holaplex/hub-starter-mint) - A beginner-friendly application using Hub, featuring a basic minting page to help you get started.  

   Showcases:
    - Custodial wallet per user
    - Minting drops to custodial wallet
    - Single drop minting page

- [Scavenger Hunt Starter](https://github.com/holaplex/hub-starter-scavenger) - A sample scavenger hunt application built using Hub, designed to showcase how you can build engaging NFT experiences and activations.

  Showcases: 
    - Custodial wallet per user
    - Minting drops to custodial wallet
    - Displaying all drops associated to a project
    - Displaying ownership status of a drop




## Reference Projects

A few reference project that demonstrate how to work with Hub to create unique NFT campaigns.

- [Eluvio SxSW Scavenger Hunt](https://github.com/holaplex/eluvio-sxsw) - During the SxSW 2023 event, Holaplex collaborated with Eluvio to host a scavenger hunt where participants scanned access badges using NFC to collect NFT keys. These keys unlocked the viewing of a video demo of the Holaplex Hub.

  Showcases:
    - Custodial Wallets
    - NFT Edition minting through API
    - Token gated content

## Open Source

Holaplex is dedicated to open-source development. All of our services have been publicly available since the start and are licensed under the GNU Affero General Public License v3.0, promoting transparency and community collaboration.
