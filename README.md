<div align="center">
  <a href="https://taterassistant.com">
    <img src="https://raw.githubusercontent.com/TaterTotterson/Tater/main/images/tater-logo-primary.png" alt="Tater AI Assistant" width="440">
  </a>

  <h3>Private AI, personal media, and connected-home software—running on hardware you control.</h3>

  <p>
    Tater combines a local Siri/Alexa alternative with Tater Tube: a self-hosted media server and a family of modern TV players for your own movies, shows, music, and channels.
  </p>

  <p>
    <a href="https://taterassistant.com"><img alt="Tater website" src="https://img.shields.io/badge/Website-taterassistant.com-FF7A18?style=for-the-badge"></a>
    <a href="https://tatertube.tv"><img alt="Tater Tube website" src="https://img.shields.io/badge/Tater_Tube-tatertube.tv-FF7A18?style=for-the-badge"></a>
    <a href="https://github.com/TaterTotterson/Tater"><img alt="Tater repository" src="https://img.shields.io/badge/GitHub-Tater-24292F?style=for-the-badge&logo=github&logoColor=white"></a>
    <a href="https://github.com/TaterTotterson/Tater-Tube-Player"><img alt="Tater Tube Player repository" src="https://img.shields.io/badge/GitHub-Tater_Tube_Player-24292F?style=for-the-badge&logo=github&logoColor=white"></a>
  </p>

  <p>
    <a href="https://tatertotterson.github.io/TaterBench/"><img alt="View TaterBench results" src="https://img.shields.io/badge/TaterBench-Model_Results-FF7A18?style=for-the-badge&logo=githubpages&logoColor=white"></a>
    <a href="https://apps.apple.com/app/little-spud/id6781400718"><img alt="Download Little Spud" src="https://img.shields.io/badge/App_Store-Little_Spud-0D96F6?style=for-the-badge&logo=apple&logoColor=white"></a>
    <a href="https://play.google.com/store/apps/details?id=com.tatertotterson.littlespud.android"><img alt="Download Little Spud on Google Play" src="https://img.shields.io/badge/Google_Play-Little_Spud-34A853?style=for-the-badge&logo=googleplay&logoColor=white"></a>
  </p>
</div>

## One owner-controlled ecosystem

Tater and Tater Tube bring private AI, smart-home control, and personal media
together on hardware you control.

### Tater Assistant

[Tater](https://github.com/TaterTotterson/Tater) is an open-source AI platform designed to provide the everyday experience of Siri or Alexa while keeping the assistant, its personality, and its data on hardware the user controls.

- **Talk naturally from around the home** with dedicated voice satellites, wake words, reply playback, and multiroom audio.
- **Choose the brain** by running local models with llama.cpp, MLX, Hugging Face Transformers, or another local model server.
- **Give the assistant useful context** through memory, awareness, cameras, Face ID, people, event history, and searchable conversations.
- **Make things happen** with automations, smart-home devices, notifications, media playback, and modular integrations.
- **Reach Tater from almost anywhere** through companion apps, smart-home platforms, messaging services, voice hardware, and even an original Xbox.

Voice, vision, memory, and automation run locally on the user's own hardware.

### Tater Tube

<div align="center">
  <a href="https://tatertube.tv">
    <img src="https://raw.githubusercontent.com/TaterTotterson/Tater-Tube-Player/main/assets/tater-tube-logo-leaning-transparent.png" alt="Tater Tube" width="520">
  </a>
</div>

[Tater Tube Server](https://github.com/TaterTotterson/tater-tube-server) and
[Tater Tube Player](https://github.com/TaterTotterson/Tater-Tube-Player) form a
self-hosted media system for personal movies, television, music, and custom
live channels.

- **Own the server and the library.** Scan local media, use existing artwork and
  NFO metadata, track playback progress, and keep player activity under the
  user's control.
- **Turn a collection into television.** Tube TV builds scheduled channels with
  program guides, channel identities, bumpers, spots, and optional breaks.
- **Watch on the couch.** The unified modern Player targets Steam and Steam
  Deck, Apple TV, Google TV, and Android TV with controller- and remote-first
  interfaces.
- **Adapt playback to the screen.** The Player reports device capabilities so
  the Server can direct play compatible media or convert only what the device
  needs.
- **Keep the personality.** Optional Tater Link features add Tater Picks,
  explanations, and voice briefings, while the original retro Tater Tube
  clients and standalone Linux edition remain active parts of the family.

## Featured projects

### Assistant platform

| Repository | Role in Tater |
| --- | --- |
| [Tater](https://github.com/TaterTotterson/Tater) | The Spud Hub: AI runtime, WebUI, voice, vision, memory, awareness, automations, music, portals, and device control. |
| [Tater Shop](https://github.com/TaterTotterson/Tater_Shop) | Versioned catalog for Cores, Portals, and Verbas that add capabilities to Tater. |
| [Tater Integrations](https://github.com/TaterTotterson/Tater_Integrations) | Installable connectors that let Tater discover, control, and interact with supported devices, platforms, and services. |
| [TaterBench](https://github.com/TaterTotterson/TaterBench) | Repeatable accuracy and performance benchmarks for models used with Tater. |

### Media server and players

| Repository | Role in Tater Tube |
| --- | --- |
| [Tater Tube Server](https://github.com/TaterTotterson/tater-tube-server) | Self-hosted media backend for local libraries, artwork and metadata, playback history, device-aware transcoding, and scheduled Tube TV channels. |
| [Tater Tube Player](https://github.com/TaterTotterson/Tater-Tube-Player) | Unified modern player for Steam and Steam Deck, Apple TV, Google TV, and Android TV. |
| [Tater Tube](https://github.com/TaterTotterson/Tater-Tube) | Original retro VCR-style Raspberry Pi frontend for local media, live TV, media servers, and streamed games. |
| [Tater Tube Steam](https://github.com/TaterTotterson/Tater-Tube-Steam) | Active standalone Linux x86_64 installer for the retro Tater Tube experience, originally developed as a Steam port. |
| [Cortana AI for XBMC4Xbox](https://github.com/TaterTotterson/skin.cortana.ai-xbmc) | Tater chat, recommendations, smart-home control, and connected media features for the original Xbox. |

### Voice and hardware

| Repository | Role in Tater |
| --- | --- |
| [Tater Native Firmware](https://github.com/TaterTotterson/Tater-Native-Firmware) | Native voice-satellite firmware for supported embedded hardware. |
| [Tater Linux Satellite](https://github.com/TaterTotterson/Tater-Linux-Satellite) | Voice and persistent-music satellite runtime for Linux computers, Raspberry Pi systems, and robots. |
| [ThirdReality Voice Firmware](https://github.com/TaterTotterson/Tater-ThirdReality-Voice-Firmware) | Tater-native firmware, provisioning, signed OTA updates, and recovery support for the ThirdReality Voice & Music Assistant. |
| [Home Assistant Satellite Bridge](https://github.com/TaterTotterson/Tater-Home-Assistant-Satellites) | Lets Tater Native voice satellites work directly with Home Assistant Assist. |
| [Tater Wake Words](https://github.com/TaterTotterson/Tater-Wake-Words) | Ready-to-use wake-word catalog with automated requests for users who cannot train their own models. |
| [microWakeWord Trainer for Apple Silicon](https://github.com/TaterTotterson/microWakeWord-Trainer-AppleSilicon) | macOS app for training custom wake words, reviewing satellite captures, and flashing Tater Native firmware. |
| [microWakeWord Trainer for NVIDIA Docker](https://github.com/TaterTotterson/microWakeWord-Trainer-Nvidia-Docker) | CUDA/Docker toolkit for training custom wake words, reviewing satellite captures, and flashing Tater Native firmware. |

### Apps and connected experiences

| Repository | Role in Tater |
| --- | --- |
| [Little Spud](https://github.com/TaterTotterson/Little-Spud-App) | Native iOS and Android companion apps for chat, voice, media, notifications, and remote access. |
| [Little Spud WebUI](https://github.com/TaterTotterson/Little-Spud-WebUI) | Lightweight browser client for connecting to Tater through Spud Link. |
| [Tater Tunnel](https://github.com/TaterTotterson/Tater_Tunnel) | Private, user-controlled remote access for securely reaching a Tater hub and connected devices from outside the home. |
| [Home Assistant Add-ons](https://github.com/TaterTotterson/hassio-addons-tater) | Packages Tater and its supporting services for installation through the Home Assistant Add-on Store. |

<div align="center">
  <a href="https://github.com/TaterTotterson?tab=repositories"><strong>Explore all Tater repositories →</strong></a>
</div>

## The goal

Tater is being built as an owner-controlled home platform: an assistant that
feels present throughout the home and a media system that makes a personal
collection feel at home on every screen. The hub, server, players, satellites,
apps, and integrations live in separate repositories so each piece can evolve
independently while remaining part of one ecosystem.

<div align="center">
  <strong>Start with <a href="https://github.com/TaterTotterson/Tater">Tater</a> or <a href="https://github.com/TaterTotterson/tater-tube-server">Tater Tube Server</a>.</strong><br>
  Explore <a href="https://taterassistant.com">taterassistant.com</a> and <a href="https://tatertube.tv">tatertube.tv</a>.
</div>
