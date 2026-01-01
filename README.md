# VoiceChatUtilities

This plugin allows you to perform multiple actions on an entire channel (move, mute, disconnect, etc.)

![Screenshot](https://user-images.githubusercontent.com/60252259/224880206-9f923f0c-9939-4e1b-81ad-70167f0ee6d4.png)

## Features

- Disconnect all users from a voice channel
- Mute/unmute all users in a voice channel
- Deafen/undeafen all users in a voice channel
- Move all users to another voice channel
- Configurable rate limiting to avoid API limits

## Installation

1. Enable the plugin in Vencord's settings
2. Right-click a voice channel and select "Voice Tools"

## Configuration

- **Wait After**: Amount of API actions to perform before waiting (to avoid rate limits) (default: 5)
- **Wait Seconds**: Time to wait between each action (in seconds) (default: 2)

## Usage

Right-click any voice or stage channel and select "Voice Tools" from the context menu. You'll see options to:
- Disconnect all users
- Mute/unmute all users
- Deafen/undeafen all users
- Move all users to another voice channel

The plugin automatically handles rate limiting to prevent hitting Discord's API limits.

## AI Disclaimer

This plugin was developed with assistance from **Cursor.AI** (Cursor's AI coding assistant). The AI was used to help with code generation, debugging, documentation, and implementation. While AI assistance was utilized, all code and features were reviewed and tested to ensure quality and functionality.

## License

Unlicense
