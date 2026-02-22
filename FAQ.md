# Frequently Asked Questions — Ania Creators

## General

### What is Ania Creators?
Ania Creators is a desktop application for Windows and Linux for building `.ania` animated avatars. You organize idle and talk frame sequences, test them live with your microphone or TTS, and export or publish the result to the Ania Models marketplace.

### Is it free?
Yes. Ania Creators is free to download and use.

### Do I need an internet connection?
An internet connection is required to publish avatars to the marketplace and to authenticate your account. Offline creation, testing, and local export all work without internet.

---

## Avatar Creation

### What images can I use?
You can import standard image formats (PNG, JPG, etc.) as individual frames for idle and talk sequences.

### How does the animation system work?
Ania avatars use two states:

- **Idle** — A randomized idle frame sequence plays while no audio is detected.
- **Talk** — When the configured audio input detects speech, a random talk frame triggers and a talk sequence begins. When speech stops, the avatar returns to an idle sequence.

Both states use randomized frame selection to keep movement from feeling mechanical or repetitive.

### Can I create GIFs from my avatar?
Yes. Ania Creators has a built-in GIF exporter.

### Can I test TTS before exporting?
Yes. The TTS test lets you type text and preview speech-synced animation inside the app before committing to an export.

### Can I test the avatar with my microphone?
Yes. The live microphone test lets you speak directly and watch the avatar react in real-time inside Ania Creators.

### Can I save my progress and continue later?
Yes. Creation sessions can be saved and resumed at any point.

---

## Export & Marketplace

### What is an `.ania` file?
An encrypted, portable avatar package containing all animation data. Works across all Ania players and integrations (desktop player, web player, browser extension, n8n).

### Can I password-protect my export?
Yes. Optional password protection is available when exporting a `.ania` file.

### How do I publish to the marketplace?
From within Ania Creators, use the integrated marketplace panel to submit your avatar to [aniamodels.shop](https://aniamodels.shop). You set whether it's free or paid.

### Can I sell my avatars?
Yes. Define your price through your creator profile. Sales are managed via the marketplace.

### Will my avatar be available immediately after publishing?
Submissions go through an administrator review process before becoming publicly listed.

---

## Technical

### What are the system requirements?
- Windows 10/11 or Linux (Ubuntu 20.04+)
- Java 17 or higher
- 4GB RAM (8GB recommended)
- 500MB free storage

### Does it integrate with OBS?
The chroma key preview lets you verify how your avatar looks with a transparent background before publishing — the same output used in OBS and similar tools.

### Where do `.ania` files get used?
- Ania Desktop Player (Windows, Linux, ARM64)
- Ania WebPlayer (React)
- Ania Browser Extension (Chrome)
- n8n Ania integration

---

## Support

### How do I report a bug?
Open an issue on [GitHub](https://github.com/rob-d3v/ania-creators/issues).

### Where do I get help?
Email: support@aniamodels.shop

### Where is the marketplace?
[aniamodels.shop](https://aniamodels.shop)
