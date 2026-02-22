# Ania Creators

**Desktop Application for Frame-Based Avatar Creation and Publishing**

Ania Creators is a desktop application for Windows and Linux that lets you build animated `.ania` avatars from image sequences, test them live, and publish them to the Ania Models marketplace. Designed for streamers, content creators, developers, and anyone building an AI-powered assistant.

---

## Give Your AI a Face

Every AI model can have a visible, animated presence. Ania Creators is where that face is built.

Create a character that speaks every AI response, reacts to every input, and gives your assistant a personality you can see. Export the avatar as a `.ania` file, load it in Ania Player, connect to your AI model via n8n, and the full pipeline is live — voice in, animated response out.

> Don't want to build it yourself? Browse creator profiles on [aniamodels.shop](https://aniamodels.shop) and commission a creator to build the avatar for you.

---

## How the Avatar System Works

Ania avatars operate on a two-state, audio-driven frame system:

- **Idle state** — A randomized idle frame sequence plays while no audio is detected.
- **Talk state** — When the configured audio input detects speech, a random talk frame triggers and a talk sequence begins. When speech stops, the avatar transitions back to an idle sequence.

This creates natural, reactive avatar behavior with no real-time rendering overhead, no video pipeline, and no complex rigging.

---

## What is an `.ania` File?

`.ania` is a portable, encrypted avatar format that packages all animation data needed to animate a digital avatar:

- Idle and talk frame sequences
- Animation timing and transition configurations
- Creator metadata and licensing information
- Optional password protection

`.ania` files are compatible with the full Ania ecosystem: desktop player, web player, browser extension, and n8n automation integrations.

---

## Features

### Creation & Animation
- **Visual Frame Studio** — Organize idle and talk frame sequences with full control over order and timing
- **Adjustable Transitions** — Fine-tune timing between idle and talk states
- **Save & Resume** — Save your creation progress and pick up exactly where you left off

### Testing
- **Live Microphone Test** — Speak and see the avatar react in real-time inside the app
- **TTS Test** — Enter text and preview Text-to-Speech output synced to the avatar animation
- **GIF Export** — Generate animated GIFs directly from your avatar sequences

### Output & Publishing
- **Export as `.ania`** — Portable, encrypted avatar format ready for any Ania player
- **Password Protection** — Optionally lock your `.ania` export
- **Chroma Key Preview** — See how your avatar looks with a transparent background before publishing
- **Marketplace Integration** — Publish directly to [aniamodels.shop](https://aniamodels.shop) for free distribution or sale

### General
- **194 Languages** — Full interface localization
- **Cross-Platform** — Windows 10/11 and Linux (Ubuntu 20.04+)

---

## Use Cases

### Streaming & VTubing
Live reactive avatar for Twitch, YouTube, or any streaming platform. Works with OBS via chroma key.

### Video Production
Animated avatar host for tutorials, explainers, YouTube, TikTok, or educational content.

### Chatbots & AI Assistants
Create a visual face for your AI — connect TTS output to the avatar for automated responses via n8n or any automation pipeline.

### Marketplace Publishing
Build avatars and sell them on [aniamodels.shop](https://aniamodels.shop). Manage your public creator profile, set free or paid access, and reach users worldwide.

Skilled creators can also **accept commissions** — individuals and companies looking for a custom branded avatar can browse creator profiles and contact them directly to negotiate. You don't need to know how to create avatars to have one made for you.

---

## Getting Started

### Requirements

| Component | Minimum |
|-----------|---------|
| **OS** | Windows 10/11 or Linux (Ubuntu 20.04+) |
| **Java** | 17 or higher |
| **RAM** | 4GB (8GB recommended) |
| **Storage** | 500MB free |

### Installation

1. Download the latest release from the [Releases](https://github.com/rob-d3v/ania-creators/releases) page
2. **Windows** — Run the `.exe` or `.msi` installer
3. **Linux** — Extract and run `./ania-creators`

### Quick Start

1. **Import frames** — Add your idle and talk images from your image library
2. **Configure sequences** — Define frame order and timing for both states
3. **Test live** — Use the microphone test to see the avatar react to your voice in real-time
4. **Test TTS** — Type text and preview automated speech synced to the avatar
5. **Export or publish** — Save as `.ania` or push directly to the marketplace

---

## Roadmap

- **Android & macOS** — A next-generation mobile and desktop assistant app is in development. Designed to act as a super-intelligent virtual assistant, combining the full Ania ecosystem — avatar, voice, AI, and automation — into a single always-available companion.

---

## The Ania Ecosystem

| Application | Platform | Description |
|-------------|----------|-------------|
| **Ania Creators** *(this)* | Windows, Linux | Avatar creation studio |
| **Ania Player** | Windows, Linux, ARM64 | Desktop avatar player |
| **Ania WebPlayer** | React / Any browser | Web integration library for developers |
| **Ania Browser Extension** | Chrome | Browser-native avatar player |
| **Ania Models** | Web | Marketplace at [aniamodels.shop](https://aniamodels.shop) |

---

## License

Ania Creators is proprietary software. See [LICENSE](LICENSE) for details.

- Free to use for personal and commercial purposes
- Reverse engineering and decompilation prohibited
- Redistribution of modified versions not permitted
- Source code is not publicly available

---

## Support

- **Bug Reports & Feature Requests** — [GitHub Issues](https://github.com/rob-d3v/ania-creators/issues)
- **General Support** — support@aniamodels.shop
- **Marketplace** — [aniamodels.shop](https://aniamodels.shop)

---

For a complete overview of all five products in the Ania ecosystem, see [ECOSYSTEM.md](ECOSYSTEM.md).

---

Created by [robd3v](https://www.linkedin.com/in/robseng/)
