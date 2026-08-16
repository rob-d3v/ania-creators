# Ania Creators

**Desktop Application for Frame-Based Avatar Creation and Publishing**

Ania Creators is a desktop application for Windows and Linux that lets you build animated `.ania` avatars — from your own image sequences, from a video, or from a single reference image using AI — test them live, and publish them to the Ania Models marketplace. Designed for streamers, content creators, developers, and anyone building an AI-powered assistant.

---

## Give Your AI a Face

Every AI model can have a visible, animated presence. Ania Creators is where that face is built.

Create a character that speaks every AI response, reacts to every input, and gives your assistant a personality you can see. Export the avatar as a `.ania` file, load it in Ania Player, connect to your AI model via n8n, and the full pipeline is live — voice in, animated response out.

> Don't want to build it yourself? Browse creator profiles on [aniamodels.shop](https://aniamodels.shop) and commission a creator to build the avatar for you.

---

## How the Avatar System Works

Ania avatars operate on a three-state, audio-driven frame system:

- **Idle state** — A randomized idle frame sequence plays while no audio is detected.
- **Talk state** — When the configured audio input detects speech, a random talk frame triggers and a talk sequence begins. When speech stops, the avatar transitions back to idle.
- **Action state** — A named custom animation defined by the creator. Actions interrupt idle or talk instantly and play to completion. Each avatar can have unlimited actions, and an action can also move the player window and carry its own lip-sync data.

This creates natural, reactive avatar behavior with no real-time rendering overhead, no video pipeline, and no complex rigging.

---

## What is an `.ania` File?

`.ania` is a portable, encrypted avatar format that packages all animation data needed to animate a digital avatar:

- Idle and talk frame sequences
- Custom action sequences with creator-defined names, plus optional window movement and lip-sync data
- Animation timing and transition configurations
- Creator metadata and licensing information
- Optional password protection

`.ania` files are compatible with the full Ania ecosystem: desktop player, web player, browser extension, and n8n automation integrations.

---

## Features

### Creation & Animation
- **Visual Frame Studio** — Organize idle, talk, and action frame sequences with full control over order and timing
- **Action Definition** — Define as many custom actions as you want at import time, each with a unique name
- **Window Movement** — An action can move the player window: direction, speed, start delay, early end, return to origin, reverse on re-trigger
- **Lip Sync** — Auto-detected mouth keyframes per action, with adjustable intensity, responsiveness, and sustain
- **Adjustable Transitions** — Fine-tune timing between idle and talk states
- **Save & Resume** — A searchable, sortable save library: overwrite a save in place, duplicate one, and recover deleted saves from the trash folder

### From a Video
- **Video Import** — Bring in one clip or a whole batch and cut the frame sequences straight from the footage
- **Automatic Idle/Talk Split** — Mouth tracking (works even under background music) or audio voice activity, with fallback between them
- **Timeline Tools** — Ranges, markers, frame removal, frame transfer between sequences, inversion, boomerang loops
- **Background Handling** — Automatic plate detection per clip, manual colour, eyedropper, or fully transparent — stated once and applied across the batch
- **Zoom Correction** — Cancel a generator's zoom drift so the character stays put

### From a Single Image (AI)
- **Ania Auto Creator** — A guided wizard that turns one reference image into a complete avatar: it generates a video per state, you review and approve each one, and the approved takes are cut into frames and imported
- **Model Choice** — Pick the image-to-video model per job, with current prices quoted live
- **Custom States** — Generate any named action alongside idle and talk
- **Resilient Runs** — Approved videos are written to disk at review time, and a run survives an app restart

### Testing
- **Live Microphone Test** — Speak and see the avatar react in real-time inside the app
- **TTS Test** — Enter text and preview Text-to-Speech output synced to the avatar animation
- **Action Test** — Trigger any defined action and preview it directly inside the app
- **GIF Export** — Generate animated GIFs directly from your avatar sequences

### Output & Publishing
- **Export as `.ania`** — Portable, encrypted avatar format ready for any Ania player
- **Password Protection** — Optionally lock your `.ania` export
- **Chroma Key Preview** — See how your avatar looks with a transparent background before publishing
- **Marketplace Integration** — Publish directly to [aniamodels.shop](https://aniamodels.shop) for free distribution or sale, with uploads sent straight to storage and resumed after a network drop

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
Create a visual face for your AI — connect TTS output to the avatar for automated responses via n8n or any automation pipeline. Define actions that the AI can trigger in response to specific events.

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
2. **Windows** — Run the `AniaCreatorsSetup.exe` installer
3. **Linux** — Install the `.deb` package, or extract and run `./ania-creators`

### Quick Start

1. **Bring in your material** — Import idle, talk, and action images from your library (defining sequence type and name at import), import a video and cut the sequences out of it, or hand the Auto Creator a single reference image
2. **Configure sequences** — Define frame order and timing for all states
3. **Test live** — Use the microphone test to see the avatar react to your voice in real-time
4. **Test actions** — Trigger each action and preview it directly in the app
5. **Test TTS** — Type text and preview automated speech synced to the avatar
6. **Export or publish** — Save as `.ania` or push directly to the marketplace

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
