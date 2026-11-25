# patimweb-labs

Projekte, Werkzeuge und Experimente — dort, wo es nicht um Agenten geht.

## Anwendungen

| Projekt | Was es tut | Stack |
|---|---|---|
| [`hexwerk`](https://github.com/patimweb-labs/hexwerk) | Addon-Manager für World of Warcraft unter Linux: findet Steam/Proton, Faugus, Heroic, Lutris, Bottles und PortProton, verwaltet die Addons aller Client-Versionen | Rust, Tauri 2, Vue 3 |
| [`crosspoint`](https://github.com/patimweb-labs/crosspoint) | 8×8-Mixer für PipeWire/JACK, ohne Kernelmodul | Rust, Web-UI |
| [`wledambilight`](https://github.com/patimweb-labs/wledambilight) | Bildschirmfarben in Echtzeit auf WLED-Streifen, PC-Peripherie (OpenRGB, Razer Chroma), Govee und Nanoleaf | Rust, Tauri 2, Vue 3 |
| [`easymeet`](https://github.com/patimweb-labs/easymeet) | Videokonferenz im Browser über einen eigenen mediasoup-SFU: Chat, Dateien, Screensharing, virtuelle Hintergründe | TypeScript, mediasoup |
| [`wach`](https://github.com/patimweb-labs/wach) | macOS-Menüleisten-App, die den Rechner wachhält und den Abwesend-Status in Chats verhindert | Go, CoreGraphics |
| [`mcp-quiver`](https://github.com/patimweb-labs/mcp-quiver) | Zentrale Bibliothek von MCP-Tools mit einem Client auf jedem Gerät: Zuweisung über Gruppen (Entra ID), ein lokaler Endpunkt, Zugangsdaten bleiben am Gerät | Rust, egui, Vue 3 |

## Sprache und Assistenz

| Projekt | Was es tut | Stack |
|---|---|---|
| `sprechwerk` *(privat)* | Sprach- und Texträume für Vereine, selbst gehostet: ein Container, ein UDP-Port, QUIC mit TLS 1.3, Anmeldung über einen Ed25519-Schlüssel statt Konten | Rust |
| `home-assistant-mistral-voice` *(privat)* | Sprachassistent auf Home Assistant (Umbrel): Mistral Voxtral für STT und TTS mit eigener Stimme, OpenAI-kompatibler Agent, Firmware-Patch für die Lautstärkekurve des Voice PE | Python, ESPHome |

## Bibliotheken

| Projekt | Was es tut | Stack |
|---|---|---|
| [`weppelmann-ui`](https://github.com/Smotherer007/weppelmann-ui) | Gemeinsame Bausteine der Apps: Design-Tokens, Vue-3-Komponenten, Living Styleguide mit Kontrastprüfung | Vue 3, TypeScript |
| [`crtstyleguide`](https://github.com/patimweb-labs/crtstyleguide) | Retro-CRT-Web-Component-Bibliothek | TypeScript, Lit |

## Werkzeuge

| Projekt | Was es tut | Stack |
|---|---|---|
| [`pMapTilesCutter`](https://github.com/patimweb-labs/pMapTilesCutter) | Bilder in Leaflet-/Google-Maps-Kacheln schneiden | TypeScript |
| [`pMapTilesCutterGo`](https://github.com/patimweb-labs/pMapTilesCutterGo) | Go-Port davon (2022, nicht weitergeführt) | Go |
| [`pLarianSaveTools`](https://github.com/patimweb-labs/pLarianSaveTools) | Larian-Savegames entpacken, LSF↔LSX konvertieren | TypeScript |
| [`xsc-patcher`](https://github.com/patimweb-labs/xsc-patcher) | XVI32-`.xsc`-Patchskripte auf Binärdateien anwenden | TypeScript |
| [`xsc-patcher-webui`](https://github.com/patimweb-labs/xsc-patcher-webui) | Web-Oberfläche dafür | TypeScript |
| [`quiver-tools`](https://github.com/patimweb-labs/quiver-tools) | MCP-Tools für mcp-quiver, jedes ein eigenes Programm | Rust |

Auf npm: `@patimweb/crtstyleguide`, `@patimweb/xsc-patcher`, `@patimweb/dos2-savegame-tools`.

---

Stand: 2026-11-16 · 13 Repositories in der Organisation, dazu `weppelmann-ui` im persönlichen Konto
