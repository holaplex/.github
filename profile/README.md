
<p align="center">
  <img src="img/holaplex-avatar.png" width="250px" />
</p>

<h2 align="center">The best way to experiment & explore with NFTs.</h2>

The Holaplex Hub provides a collection of loosely coupled microservices that make it easy to launch NFT campaigns, mint digital collectibles, run loyalty programs, and more. With Hub and developer APIs, no matter what industry you're in, you can explore the possibilities of NFTs.

## Getting Started

Visit our docs site at [https://docs.holaplex.com](https://docs.holaplex.com) to read useful guides and review our API reference.

## Services Catalogue

Hub is a collection of loosely coupled microservices that emit and process messages through a shared Redpanda cluster, a Kafka compatible streaming data platform. The services also expose their own GraphQL API that are stitched together into a single API endpoint using Apollo Federated Router.

- [Hub Console](https://github.com/holaplex/hub) - User-friendly management console for interacting with the Hub API, built with Next.js and TypeScript. 

- [Hub NFTs](https://github.com/holaplex/hub-nfts) - Multi-chain minting and indexing of NFT campaigns. Leverages the Redpanda platform for inter-service communication. 

- [Hub Orgs](https://github.com/holaplex/hub-orgs) - Catalogue of all organizations, projects, and memberships for Hub.

- [Hub Treasuries](https://github.com/holaplex/hub-treasuries) - Creates crypto wallets using Fireblocks and submits blockchain transactions using Hub custodial wallets.

- [Hub Customers](https://github.com/holaplex/hub-customers) - Manages customer references that receive a treasury for storing crypto wallets.

- [Hub Permissions](https://github.com/holaplex/hub-permissions) - Contains all permission relationships for the Hub, leveraging Ory Keto for ACL, RBAC, and other access models.

- [Hub Identities](https://github.com/holaplex/hub-identities) - Manages all identities for Hub. Provides a GraphQL API for interacting with Ory Kratos, the identity server.

- [Hub Credentials](https://github.com/holaplex/hub-credentials) - Allows creation of API credentials for Hub. Provides a GraphQL API for interacting with Ory Hydra.

- [Hub Webhooks](https://github.com/holaplex/hub-webhooks) - Receives webhook events as Hub resources change, using Svix webhooks service.

- [Hub Credits](https://github.com/holaplex/hub-credits) - Allows users to pay for blockchain transactions and storage without needing tokens. Users can purchase credits using a credit card.

- [Hub Messages](https://github.com/holaplex/hub-messages) - Listens for events emitted by services and sends emails to users using Postmark when applicable.

## Starter Projects 

Kick off your Hub journey with these ready-to-use project templates designed to help you learn and experiment with the Holaplex Hub API.

- [Hub Starter Template](https://github.com/holaplex/hub-starter) - A opinionated application template for building any product using Hub.

  Includes:
    - Web framework - NextJS
    - Users and sessions - NextAuth
    - Holaplex client and types
    - API server - GraphQL Apollo
    - Styles - Tailwind



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

## Open Source

Holaplex is dedicated to open-source development. All of our services have been publicly available since the start and are licensed under the GNU Affero General Public License v3.0, promoting transparency and community collaboration.
