# 🦋 Menelaus

*A native iOS AI client built around your models, your providers, and your data\.*

![Swift](https://img.shields.io/badge/Swift-6.2-orange)
![Platform](https://img.shields.io/badge/platform-iOS-0A84FF)

## Table of Contents

- [What is Menelaus?](#what-is-menelaus)
- [Features](#features)
- [AI Providers](#ai-providers)
- [Privacy](#privacy)
- [Installation](#installation)
- [Sideloading Support](#sideloading-support)
- [Development](#development)
- [Support](#support)

## What is Menelaus?

Menelaus is a native SwiftUI chat client for iOS that lets you use your own AI providers and local models without being tied to a single service\.

It supports cloud providers through your own API keys, custom endpoints, and on\-device GGUF models through llama\.cpp\.

## Features

- 🤖 Multi\-provider AI with model profiles and custom endpoints
- 🔑 BYOK — provider credentials remain under your control
- 🧠 Local GGUF models through llama\.cpp
- 🌐 Web search, URL fetching, and an interactive WebKit browser
- 📁 Menelaus Files with create, read, edit, search, rename, and delete tools
- 🧪 Sandboxed JavaScript and Python runtimes
- 💻 Linux\-like terminal powered by SwiftBash
- 📦 Archives, PDFs, code search, charts, calculations, conversions, and weather
- 🗂️ Projects with shared context, pages, databases, and project memory
- 🧠 Conversation memory and chat search
- 📝 Artifacts with a persistent gallery and version history
- 🎙️ Voice mode, dictation, speech synthesis, and Siri/App Shortcut support
- 🕶️ Incognito chats
- 🔧 Configurable tool calling, model profiles, UI customization, and local storage controls

## AI Providers

Menelaus supports:

- OpenAI
- Anthropic
- Gemini
- OpenRouter
- xAI
- Mistral
- NVIDIA NIM
- Ollama
- Custom endpoints

Custom providers can use compatible OpenAI, Anthropic, or Gemini protocols\.

On\-device models use GGUF files through llama\.cpp and do not require an API key or network connection\.

## Privacy

Menelaus does not collect analytics, usage statistics, or crash reports\.

For cloud conversations, messages are sent directly to the provider you have configured using your API key\. Menelaus does not operate or host those third\-party AI services\.

Local models run on the device\.

## Installation

Menelaus is currently distributed outside the App Store\.

The recommended installation methods are:

- [SideStore](https://sidestore.io/)
- [LiveContainer](https://github.com/LiveContainer/LiveContainer)

### SideStore

1. Follow the official [SideStore installation guide](https://docs.sidestore.io/docs/installation)\.
2. Install and configure SideStore on your device\.
3. Download the latest Menelaus IPA from GitHub Releases\.
4. In SideStore, import the Menelaus IPA and install it\.
5. Keep SideStore configured so the app can be refreshed when required\.

### LiveContainer

1. Install the official [LiveContainer](https://github.com/LiveContainer/LiveContainer)\.
2. Follow the [LiveContainer installation guide](https://livecontainer.github.io/docs/installation)\.
3. Configure JIT\-Less mode as required\.
4. Import the Menelaus IPA into LiveContainer\.
5. Launch Menelaus from LiveContainer\.

Always use official builds of SideStore and LiveContainer\.

## Sideloading Support

Other sideloading methods may work with Menelaus, but **SideStore and LiveContainer are the only recommended and supported methods**\.

We recommend not using other sideloaders\. Compatibility and troubleshooting cannot be guaranteed for them\.

For Menelaus\-specific support, contact the maintainer directly:

**Discord: ****`skywalker_1401`**

Please do not contact the SideStore or LiveContainer developers about Menelaus bugs or feature issues\. They maintain separate projects and are not responsible for Menelaus\.

For problems with SideStore or LiveContainer themselves, use their official documentation and support channels\.

## Development

Menelaus is written in Swift and uses SwiftUI, SwiftData, WebKit, and Apple’s native frameworks\.

The project currently uses a single\-file source build for the main application implementation\.

Several capabilities are provided by dedicated libraries and runtimes, including:

- llama\.cpp for on\-device models
- SwiftBash for the Linux\-like terminal
- Pyodide for Python execution
- Highlightr for syntax highlighting
- WhisperKit for speech recognition

## Is this open-source?
Not at the moment, I do have plans to open-source some parts of it!

## Is Menelaus fully completed?
No, infact I’d say it’s less than 30% complete! This is an early beta so I’d like to see everyone’s opinions!
---

*Built and maintained by skywalker\.*
