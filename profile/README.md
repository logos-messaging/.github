# Welcome to Logos Messaging GitHub 👋

Logos Messaging is the messaging stack of the [Logos](https://logos.co) project — a unified, privacy-by-default decentralized technology stack. 

We build the protocols and libraries that move messages between people, devices, and applications without depending on centralized servers, surveillance infrastructure, or single points of failure.

## Quick links

| | |
|---|---|
| Website | [logos.co](https://logos.co) |
| Builder Hub | [build.logos.co](https://build.logos.co) |
| Specifications | [lip.logos.co](https://lip.logos.co) |
| Roadmap | [roadmap.logos.co/messaging](https://roadmap.logos.co/messaging) |
| Forum | [forum.logos.co](https://forum.logos.co) |
| Discord | [discord.gg/logosnetwork](https://discord.gg/logosnetwork) |
| X | [@Logos_network](https://x.com/Logos_network) |
| Logos GitHub org | [github.com/logos-co](https://github.com/logos-co) |

## What's in here

Logos Messaging is composed of two complementary layers, both designed to run standalone or as modules inside the broader Logos stack.

### Logos Delivery

The transport layer. A peer-to-peer messaging network with DoS protection via RLN (Rate Limiting Nullifiers). Any application can use it to send and receive messages over an open, censorship-resistant network.

| Repository | Description |
|---|---|
| [`logos-delivery`](https://github.com/logos-messaging/logos-delivery) | Reference Nim implementation — the network's main node |
| [`logos-delivery-compose`](https://github.com/logos-messaging/logos-delivery-compose) | Run a node with `docker-compose` |

### Logos Chat

The chat layer. A protocol and library that provides 1:1 and group conversations with end-to-end encryption using de-MLS - everything an application needs to add private chat without rolling its own protocol.

| Repository | Description |
|---|---|
| [`libchat`](https://github.com/logos-messaging/libchat) | Logos Chat library (Rust) |

### Specs & project management

| Repository | Description |
|---|---|
| [`specs`](https://github.com/logos-messaging/specs) | Protocol specifications (published specs migrate to [lip.logos.co](https://lip.logos.co)) |
| [`pm`](https://github.com/logos-messaging/pm) | Roadmap, milestones, and deliverables — see the [public roadmap](https://roadmap.logos.co/messaging) |
| [`awesome-logos-delivery`](https://github.com/logos-messaging/awesome-logos-delivery) | Community-curated list of resources and projects |

## Get involved

Logos is built in the open by a global community of contributors. Whether you're building applications on top of Logos Messaging, contributing to the protocols themselves, or running a node — there's a place for you.

- **Build something.** The [Logos Builder Hub](https://build.logos.co) has guides for using the [Delivery Module API](https://github.com/logos-co/logos-delivery-module) and the [Chat Module API](https://github.com/logos-co/logos-chat-module) from your own application.
- **Run a node.** Spin up Logos Delivery with [docker-compose](https://github.com/logos-messaging/logos-delivery-compose) and join the testnet.
- **Pick up an issue.** Browse `good first issue` labels across our repositories, or check the [Logos contribute portal](https://contribute.logos.co/).
- **Ask questions.** The fastest way to get an answer is [Discord](https://discord.gg/logosnetwork). Longer-form discussion happens on the [forum](https://forum.logos.co).

## A note on naming

Logos Messaging was previously known as **Waku**. You will still see the legacy names in code, branches, and older issues:

- **Logos Delivery** ← *Waku, nwaku, nim-waku, logos-messaging-nim*
- **Logos Chat** ← *Chat SDK, ChatSDK, nim-chat-poc*

The migration is happening gradually. Please use the current names in new code, documentation, and external communications.

---

*Logos Messaging is part of the broader [Logos](https://logos.co) stack.
