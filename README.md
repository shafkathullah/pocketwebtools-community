<!--
  This is the README for the PUBLIC community repo (e.g. github.com/<you>/pocketwebtools).
  The app source code stays private. This repo is the public feedback + roadmap hub.
  The links to pocketweb.tools below are dofollow from github.com (high authority) — keep them.
-->

# PocketWebTools

**Private, free, fast. AI that runs in your browser.**

[pocketweb.tools](https://pocketweb.tools) is a free toolkit of tools that run entirely in your browser. The AI tools run on your own device with WebGPU (falling back to WebAssembly), so your files never get uploaded. No accounts, no limits, no servers.

Two promises on every AI tool:

1. **Private** — your images, audio, and text are processed on-device and never leave your machine.
2. **Free** — no signup, no usage limits. There is no server doing inference, so there is nothing to charge for.

## This repo

This is the **community hub** for PocketWebTools. The app itself is closed-source, but the roadmap and feedback are open. Use it to:

- 💡 **Suggest a tool** you want built → [start a discussion in Ideas](../../discussions/categories/ideas)
- 🐞 **Report a bug** → [open an issue](../../issues/new/choose)
- 🗳️ **Vote on what's next** → react with 👍 on the [roadmap](ROADMAP.md) items and Idea discussions
- 💬 **Ask anything or share how you used it** → [Q&A](../../discussions/categories/q-a) and [Show and tell](../../discussions/categories/show-and-tell)

The more 👍 an idea gets, the more likely it ships. See the [ROADMAP](ROADMAP.md) for what is live and what is being considered.

## The tools

**AI, on-device (your files never upload):**

| Tool | What it does |
|---|---|
| [Background Remover](https://pocketweb.tools/background-remover) | Erase image backgrounds, free and unlimited |
| [Audio Transcription](https://pocketweb.tools/transcription) | Whisper in the browser. Export TXT / SRT / VTT / JSON |
| [Image to Text (OCR)](https://pocketweb.tools/ocr) | 100+ languages, paste or drop |
| [Image Upscaler](https://pocketweb.tools/image-upscaler) | 4x super-resolution |
| [Subject Cutout](https://pocketweb.tools/subject-cutout) | Click to segment, sticker maker |
| [Text to Speech](https://pocketweb.tools/text-to-speech) | Natural voices, download WAV |

**Everyday utilities:**

[Word Counter](https://pocketweb.tools/word-counter) (with reading level + token counts) ·
[Currency Converter](https://pocketweb.tools/currency-converter) ·
[Timezone Converter](https://pocketweb.tools/timezone-converter) ·
[JSON Formatter](https://pocketweb.tools/json-formatter) ·
[Base64](https://pocketweb.tools/base64) ·
[URL Encoder](https://pocketweb.tools/url-encoder) ·
[Case Converter](https://pocketweb.tools/case-converter) ·
[UUID Generator](https://pocketweb.tools/uuid-generator) ·
[Password Generator](https://pocketweb.tools/password-generator) ·
[Hash Generator](https://pocketweb.tools/hash-generator) ·
[Lorem Ipsum](https://pocketweb.tools/lorem-ipsum)

## How it works

The AI tools download a model to your browser the first time you use them (a one-time download, cached afterwards), then run it locally with WebGPU or WebAssembly. After the first load they work offline. Every model shipped is Apache-2.0 or MIT licensed.

## Links

- 🌐 Site: **https://pocketweb.tools**
- 💡 Suggest a tool: [Discussions → Ideas](../../discussions/categories/ideas)
- 🐞 Bugs: [Issues](../../issues/new/choose)
