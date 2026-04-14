# Discord Community Admin Tools (Aka DCAT)

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](#license)
[![Node Version](https://img.shields.io/badge/node-%3E%3D18-339933?style=flat&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Docker](https://img.shields.io/badge/Docker-Supported-2496ED?style=flat&logo=docker&logoColor=white)](#runtime-modes)
[![Windows](https://custom-icon-badges.demolab.com/badge/Windows-0078D6?logo=windows11&logoColor=white)](#compatibility)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)](#compatibility)

DiscordCAT is a modular Discord administration tool for Discord guilds that combines:

- A web panel for setup, status, and operations
- A Discord bot service with split runtime modes
- A desktop launcher (Tauri) for start/stop/restart and runtime control or first setup services

---

## Main Goals

- Manage Discord community tooling from one control surface
- Support both Node and Docker runtime workflows
- Keep user editable data and runtime data separated from source code
- Enable clean release distribution without shipping development source folders

## Runtime Modes

DiscordCAT supports separated execution modes:

- Node mode: bot and panel as Node processes
- Docker mode: bot and panel as split containers (Windows/Linux compose)

This allows independent service control and safer restart flows.

## Requirements

- Node.js 18+
- npm
- Docker (optional but recommended, only for Docker mode)

## Compatibility

- Windows: supported
- Linux: supported
