# mobile-game-client-reference
Technical notes about mobile game clients, compatibility and client-side customization.
# Mobile Game Client Reference

This document provides general technical notes about modified mobile game clients, platform compatibility, and the distinction between local client changes and remote game services.

## What Is a Game Client?

The game client is the application installed on the player's device.

It handles many functions that users interact with directly, including:

- Graphics
- Menus
- Controls
- Camera behavior
- Visual assets
- Interface elements
- Certain performance settings

A modified client may provide additional control over some of these functions.

Players looking for a practical example can review the **[BSD Brawl client reference](https://bsd-brawl.org/)** for information about its client-side features and supported platforms.

## Client Versus Server

Online games normally distribute responsibilities between the local client and remote infrastructure.

The client is responsible for presenting and rendering much of the experience.

Remote systems normally remain responsible for important online and account-related information.

This architecture explains why changing something locally does not automatically alter the corresponding server-side state.

## Modified Client Versus Private Server

A modified client primarily changes software running on the player's device.

A private server generally creates or recreates part of the remote server environment.

These are technically different approaches even though both may casually be described as game modifications.

## Compatibility Considerations

Before using a third-party client, check:

- Operating-system version
- Device architecture
- Available memory
- Free storage
- Graphics capability
- Application version
- Package source

Compatibility can also change after updates to the original game or operating system.

## Security Considerations

Unofficial software deserves additional caution.

Users should review package sources and requested permissions before installation and consider carefully whether to use an important account containing valuable progress or purchases.

## Summary

Understanding the division between client-side and server-side responsibilities provides useful context when researching any modified online game client.
