<div align="center">
  <a href="https://taterassistant.com">
    <img src="https://raw.githubusercontent.com/TaterTotterson/Tater/main/images/tater-logo-primary.png" alt="Tater AI Assistant" width="440">
  </a>

  <h3>A local-first, self-hosted replacement for Siri and Alexa.</h3>

  <p>
    One assistant for voice, vision, memory, automations, smart-home control, music, messaging, and more—running on hardware you control.
  </p>

  <p>
    <a href="https://taterassistant.com"><img alt="Tater website" src="https://img.shields.io/badge/Website-taterassistant.com-FF7A18?style=for-the-badge"></a>
    <a href="https://github.com/TaterTotterson/Tater"><img alt="Tater repository" src="https://img.shields.io/badge/GitHub-Tater-24292F?style=for-the-badge&logo=github&logoColor=white"></a>
    <a href="https://apps.apple.com/app/little-spud/id6781400718"><img alt="Download Little Spud" src="https://img.shields.io/badge/App_Store-Little_Spud-0D96F6?style=for-the-badge&logo=apple&logoColor=white"></a>
  </p>
</div>

## Meet Tater

[Tater](https://github.com/TaterTotterson/Tater) is an open-source AI platform designed to provide the everyday experience of Siri or Alexa without locking the assistant, its personality, or its data to one cloud ecosystem.

- **Talk naturally from around the home** with dedicated voice satellites, wake words, reply playback, and multiroom audio.
- **Choose the brain** by running models locally with llama.cpp, MLX, or Hugging Face Transformers—or connecting an OpenAI-compatible API.
- **Give the assistant useful context** through memory, awareness, cameras, Face ID, people, event history, and searchable conversations.
- **Make things happen** with automations, smart-home devices, notifications, media playback, and modular integrations.
- **Reach Tater from almost anywhere** through Little Spud, HomeKit, Home Assistant, Discord, Telegram, Matrix, IRC, Meshtastic, macOS, and even an original Xbox.

When Tater is configured with local models and local integrations, voice, vision, memory, and automation can remain on the user's own hardware. Cloud services remain optional for the features that need or benefit from them.

## Start here

| Project | What it does |
| --- | --- |
| [Tater](https://github.com/TaterTotterson/Tater) | The main Spud Hub: AI runtime, WebUI, voice, vision, memory, awareness, automations, music, portals, and device control. |
| [Tater Assistant Website](https://github.com/TaterTotterson/Tater_Assistant-Website) | Source for [taterassistant.com](https://taterassistant.com), including installation and feature documentation. |
| [Little Spud App](https://github.com/TaterTotterson/Little-Spud-App) | Native iOS and Android companion apps for chat, voice, media, notifications, and remote access to a paired Tater hub. |
| [Home Assistant Add-ons](https://github.com/TaterTotterson/hassio-addons-tater) | Packages Tater and its supporting services for installation through the Home Assistant Add-on Store. |

## The Tater ecosystem

### Platform and extensions

| Repository | Role in Tater |
| --- | --- |
| [Tater](https://github.com/TaterTotterson/Tater) | The central assistant and local-first AI platform. |
| [Tater Shop](https://github.com/TaterTotterson/Tater_Shop) | Versioned catalog for Cores, Portals, and Verbas that add capabilities to Tater. |
| [Tater Integrations](https://github.com/TaterTotterson/Tater_Integrations) | Installable device, service, search-provider, media, and external-API integrations. |
| [TaterBench](https://github.com/TaterTotterson/TaterBench) | Repeatable accuracy and performance benchmarks for models used with Tater. |

### Voice satellites, wake words, and hardware

| Repository | Role in Tater |
| --- | --- |
| [Tater Native Firmware](https://github.com/TaterTotterson/Tater-Native-Firmware) | Native voice-satellite firmware for supported embedded hardware. |
| [Tater Linux Satellite](https://github.com/TaterTotterson/Tater-Linux-Satellite) | Voice and persistent-music satellite runtime for Linux computers, Raspberry Pi systems, and robots. |
| [ThirdReality Voice Firmware](https://github.com/TaterTotterson/Tater-ThirdReality-Voice-Firmware) | Tater-native firmware, provisioning, signed OTA updates, and recovery support for the ThirdReality Voice & Music Assistant. |
| [Tater Home Assistant Satellites](https://github.com/TaterTotterson/Tater-Home-Assistant-Satellites) | Lets Tater Native voice satellites also work directly with Home Assistant Assist. |
| [Tater Wake Words](https://github.com/TaterTotterson/Tater-Wake-Words) | Wake-word catalog used by Tater Native satellites. |

### Companion clients and portals

| Repository | Role in Tater |
| --- | --- |
| [Little Spud App](https://github.com/TaterTotterson/Little-Spud-App) | Native mobile companion for iOS and Android. |
| [Little Spud WebUI](https://github.com/TaterTotterson/Little-Spud-WebUI) | Lightweight browser client for chat, voice, media, and local device notifications. |
| [Tater Meshtastic Bridge](https://github.com/TaterTotterson/tater_meshtastic_bridge) | Connects Tater to Meshtastic radios through a host-side Bluetooth LE bridge. |
| [Cortana AI for XBMC4Xbox](https://github.com/TaterTotterson/skin.cortana.ai-xbmc) | Brings Tater chat, recommendations, smart-home control, and modern connected features to the original Xbox. |

### Music, video, and retro media

| Repository | Role in Tater |
| --- | --- |
| [Tater Tube](https://github.com/TaterTotterson/Tater-Tube) | Retro VCR-style frontend for local media, live TV, media servers, and streamed games on Raspberry Pi. |
| [Tater Tube Steam](https://github.com/TaterTotterson/Tater-Tube-Steam) | Linux x86_64 and Steam-oriented port of the Tater Tube experience. |
| [Tater Tube Server](https://github.com/TaterTotterson/tater-tube-server) | Backend for local and NZB/Usenet streaming with hardware transcoding. |
| [Tater Tube Website](https://github.com/TaterTotterson/Tater_Tube-Website) | Website and generated documentation for the Tater Tube ecosystem. |

### Deployment and remote connectivity

| Repository | Role in Tater |
| --- | --- |
| [Home Assistant Add-ons](https://github.com/TaterTotterson/hassio-addons-tater) | Installs Tater and required services on Home Assistant OS and supervised systems. |
| [Tater Tunnel](https://github.com/TaterTotterson/Tater_Tunnel) | Experimental home relay and WireGuard device-VPN system for secure remote connectivity. |
| [Tater Tunnel Website](https://github.com/TaterTotterson/Tater_Tunnel-Website) | Web presence and documentation for Tater Tunnel. |

### Wake-word and model tooling

| Repository | Role in Tater |
| --- | --- |
| [microWakeWord Trainer for Apple Silicon](https://github.com/TaterTotterson/microWakeWord-Trainer-AppleSilicon) | macOS trainer for custom wake words, satellite-capture review, and Tater Native firmware flashing. |
| [microWakeWord Trainer for NVIDIA Docker](https://github.com/TaterTotterson/microWakeWord-Trainer-Nvidia-Docker) | CUDA/Docker workflow for training wake words and preparing Tater Native devices. |
| [micro-wake-word](https://github.com/TaterTotterson/micro-wake-word) | The TensorFlow-based microWakeWord training framework used by the wake-word toolchain. |
| [Piper Sample Generator](https://github.com/TaterTotterson/piper-sample-generator) | Generates synthetic voice samples with Piper for wake-word training. |

## The goal

Tater is being built as an assistant that feels present throughout the home while remaining adaptable and owner-controlled. The hub, satellites, apps, integrations, and media projects are separate repositories so each piece can evolve independently—but together they form one assistant ecosystem.

<div align="center">
  <strong>Start with <a href="https://github.com/TaterTotterson/Tater">Tater</a>, or explore the guides at <a href="https://taterassistant.com">taterassistant.com</a>.</strong>
</div>
