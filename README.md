
## [About](https://spacebar.chat)

Spacebar/server is a Discord backend re-implementation and extension.
We aim to reverse engineer and add additional features to the Discord backend, while remaining completely backwards compatible with existing bots, applications, and clients.

This repository contains:

- [API Request/Response Types](/src/schemas)
- [Spacebar HTTP API Server](/src/api)
- [WebSocket Gateway Server](/src/gateway)
- [HTTP CDN Server](/src/cdn)
- [WebRTC Server](/src/webrtc)
- [Utility and Database Models](/src/util)
- [Spacebar Admin API (C#)](/extra/admin-api) (Emma [it/its]@Rory& was here)

## [Documentation](https://docs.spacebar.chat)

And with documentation on how to set up your own server [here](https://docs.spacebar.chat/setup/server), docs to set up either client [here](https://docs.spacebar.chat/setup/clients/), and docs about bots [here](https://docs.spacebar.chat/setup/bots/)

## [Contributing](https://docs.spacebar.chat/contributing/)

## Clients

You _should_ be able to use any client designed for Discord.com to connect to a Spacebar instance.
However, some incompatibilities still exist between Spacebar and Discord. For this reason, not every client will connect.  
We recommend using [Fermi](https://fermi.chat/login?instance=https%3A%2F%2Fspacebar.chat) as a solid starting point on your adventure in the SpaceBar!
