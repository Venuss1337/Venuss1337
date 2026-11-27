<h1 align="center">Wiktor Fila</h1>

<p align="center">
  <strong>Software developer · Desktop applications, web experiences &amp; developer tools</strong>
</p>

<p align="center">
  Based in Poland, with an interest in software architecture, interactive design and building complete, usable products.
</p>

<p align="center">
  <a href="https://wiktorfila.dev"><strong>Portfolio</strong></a> &nbsp;·&nbsp;
  <a href="mailto:filetarmed@gmail.com">Contact</a>
</p>

---

## Featured work

### ECHO — Music, without the cloud

[![Release](https://img.shields.io/github/v/release/Venuss1337/echo?style=flat-square&label=release&color=476b53)](https://github.com/Venuss1337/echo/releases/latest)
[![License](https://img.shields.io/badge/license-GPL--3.0--or--later-555555?style=flat-square)](https://github.com/Venuss1337/echo/blob/main/LICENSE)

A local-first music and internet radio player for Windows. ECHO brings together an indexed music library, playlists, live radio and native Windows media integration in an artwork-driven interface called **Atmosphere 2.0**. No accounts, subscriptions, telemetry or cloud dependency.

Its Rust backend manages playback, library data and Windows integration, communicating with the React interface through typed IPC contracts.

[![ECHO — album library and playback interface](https://raw.githubusercontent.com/Venuss1337/echo/main/docs/images/albums.png)](https://github.com/Venuss1337/echo)

`Rust` `Tauri 2` `React` `TypeScript` `SQLite` `libmpv` `FFmpeg`

**[Source code](https://github.com/Venuss1337/echo) · [Download for Windows](https://github.com/Venuss1337/echo/releases/latest) · [Website](https://echo.wiktorfila.dev)**

#### Deep Cut - ECHO's interactive website

An interactive product website built around a visual concept: layers of cut paper illuminated by the music behind them. Instead of relying on conventional 3D models, the experience uses custom WebGL rendering, signed distance fields, procedural lighting and scroll-driven animation.

The site also includes reduced-motion and non-WebGL fallbacks, preserving the visual story across different devices and accessibility preferences.

[![Deep Cut - ECHO website](https://raw.githubusercontent.com/Venuss1337/echo-web/main/docs/showcase/1-cover.webp)](https://echo.wiktorfila.dev)

<p align="center">
  <a href="https://echo.wiktorfila.dev"><img src="https://raw.githubusercontent.com/Venuss1337/echo-web/main/docs/showcase/2-folder.webp" width="49%" alt="Cut-paper landscape with illuminated typography" /></a>
  <a href="https://echo.wiktorfila.dev"><img src="https://raw.githubusercontent.com/Venuss1337/echo-web/main/docs/showcase/4-bloom-count.webp" width="49%" alt="Illuminated paper petals and ECHO playback controls" /></a>
</p>

`TypeScript` `WebGL 2` `Three.js` `GLSL` `GSAP` `Lenis` `Vite`

**[Explore the website](https://echo.wiktorfila.dev) · [Website repository](https://github.com/Venuss1337/echo-web)**

The ECHO player is open source. The website repository is publicly viewable, with its original design and code reserved under its own license.

---

### FilaSignal - Your world. Your logic.

[![Release](https://img.shields.io/github/v/release/Venuss1337/filasignal?style=flat-square&label=release&color=476b53)](https://github.com/Venuss1337/filasignal/releases/latest)
[![License](https://img.shields.io/badge/license-GPL--3.0--only-555555?style=flat-square)](https://github.com/Venuss1337/filasignal/blob/main/LICENSE)

Programmable computers, hardware and networking for Minecraft, powered by **FilaScript**, a custom event-driven programming language.

FilaSignal includes a standalone language interpreter and CLI, an in-game editor with syntax highlighting, completion and debugging, wired and wireless device networks, persistent storage, multiplayer permission checks and a dedicated documentation website.

[![FilaSignal - display and alarm hardware in Minecraft](https://raw.githubusercontent.com/Venuss1337/filasignal/main/web/public/screenshots/display-alarm.webp)](https://github.com/Venuss1337/filasignal)

`Java 25` `Fabric` `Language design` `Interpreters` `Astro` `Starlight`

**[Source code](https://github.com/Venuss1337/filasignal) · [Documentation](https://venuss1337.github.io/filasignal/) · [Download](https://github.com/Venuss1337/filasignal/releases/latest)**

---

### FilaScope - Understand every frame

[![Release](https://img.shields.io/github/v/release/Venuss1337/filascope?style=flat-square&label=release&color=476b53)](https://github.com/Venuss1337/filascope/releases/latest)
[![License](https://img.shields.io/badge/license-MIT-555555?style=flat-square)](https://github.com/Venuss1337/filascope/blob/main/LICENSE)

A lightweight, native Minecraft client performance profiler. FilaScope uses **Mixin and MixinExtras** to instrument frame, tick and rendering stages, with rolling frame-time statistics, stutter detection, bounded gameplay captures and optional sampled mod attribution.

Its interactive interface makes slow frames easier to investigate through live graphs, individual frame inspection and execution timelines, with a configurable gameplay HUD.

[![FilaScope - live performance dashboard](https://raw.githubusercontent.com/Venuss1337/filascope/main/docs/images/live.jpg)](https://github.com/Venuss1337/filascope)

<p align="center">
  <a href="https://github.com/Venuss1337/filascope"><img src="https://raw.githubusercontent.com/Venuss1337/filascope/main/docs/images/capture.jpg" width="49%" alt="FilaScope capture timeline and selected frame breakdown" /></a>
  <a href="https://github.com/Venuss1337/filascope"><img src="https://raw.githubusercontent.com/Venuss1337/filascope/main/docs/images/mods.jpg" width="49%" alt="FilaScope installed mods and sampled activity" /></a>
</p>

#### FilaMCUI - the native rendering foundation

To build FilaScope's interface, I developed **[FilaMCUI](https://github.com/Venuss1337/filamcui)**, a reusable shader-driven rendering and animation library for Minecraft. It provides anti-aliased geometry, batched chart rendering, configurable glass and grain materials, TrueType typography, and interruptible spring and keyframe animations without a browser runtime or a predefined component framework.

The library uses Minecraft's native rendering abstraction and has been tested on OpenGL and Vulkan. It is independently distributed under MIT and bundled with FilaScope.

`Java 25` `Fabric` `Mixin` `MixinExtras` `Blaze3D` `GLSL` `Gradle`

**[Source code](https://github.com/Venuss1337/filascope) · [Download](https://github.com/Venuss1337/filascope/releases/latest) · [User guide](https://github.com/Venuss1337/filascope/blob/main/docs/USER_GUIDE.md) · [Rendering library](https://github.com/Venuss1337/filamcui)**

---

## Other work

Projects currently in development or being explored:

| Project | Focus |
| :--- | :--- |
| **FilaVim** | Native modal code editor using Rust and GPUI, with managed language servers and LSP integration. |
| **FilaMC** | Shared Minecraft worlds, desktop tooling and session networking using Rust, Tauri and Fabric. |
| **Moss & Moons** | Planetary sandbox game in Unity/C#, with procedural spherical worlds, editable terrain and persistent world data. |
| **Fila2D** | A learning-focused 2D engine built in C++ with SDL3 and OpenGL. |

## Technologies

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" alt="TypeScript" width="32" height="32" /> &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/rust/rust-original.svg" alt="Rust" width="32" height="32" /> &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" alt="Java" width="32" height="32" /> &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/cplusplus/cplusplus-original.svg" alt="C++" width="32" height="32" /> &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/csharp/csharp-original.svg" alt="C#" width="32" height="32" /> &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" alt="React" width="32" height="32" /> &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/astro/astro-original.svg" alt="Astro" width="32" height="32" /> &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" width="32" height="32" /> &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" alt="Docker" width="32" height="32" />
</p>

| Area | Technologies |
| :--- | :--- |
| Desktop & systems | Rust, Tauri, C++, OpenGL, SQLite |
| Web & graphics | TypeScript, React, Next.js, Astro, Three.js, WebGL, GLSL, Tailwind CSS |
| Backend & infrastructure | PostgreSQL, Fastify, Axum, Docker |
| Games & tooling | Java, Fabric, Mixin, MixinExtras, Blaze3D, C#, Unity, Luau |

---

<p align="center">
  Open to remote development opportunities and technical collaborations.<br />
  <a href="https://wiktorfila.dev"><strong>Explore my portfolio</strong></a>
</p>
