# Modit Engine

### A small, code-first 3D game engine built on LuaJIT and Raylib, with sandboxed modding built in.

![Status](https://img.shields.io/badge/Status-Alpha-e4ad29?style=flat-square&labelColor=0E0E0E)
![Platforms](https://img.shields.io/badge/Platforms-Windows-green?style=flat-square&labelColor=0E0E0E)
![Language](https://img.shields.io/badge/Language-LuaJIT-blue?style=flat-square&labelColor=0E0E0E)
![License](https://img.shields.io/badge/License-Apache--2.0-555?style=flat-square&labelColor=0E0E0E)

<a href="https://modit.dev"><img src="https://img.shields.io/badge/🌐_Website-modit.dev-4dcbc2?style=for-the-badge&logoColor=white" alt="Website" /></a>
<a href="https://discord.gg/QQ7yarSE5U"><img src="https://img.shields.io/badge/_Discord-Join-4dcbc2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
<a href="https://ko-fi.com/case"><img src="https://img.shields.io/badge/_Ko--fi-Support-4dcbc2?style=for-the-badge&logo=kofi&logoColor=white" alt="Ko-fi" /></a>

## What it is

Modit is for writing a game as plain Lua, with nothing between you and LuaJIT and Raylib.

- **Familiar structure.** A client, server and shared split like FiveM, with exports for cross-mod interop.
- **Modding when you want it.** Optional, sandboxed, and available to client-only and multiplayer games alike.
- **Headless servers.** Dedicated server support is working in early alpha.
- **A built-in editor** for creating and running projects.

## Repositories

| Repository | What's in it |
| :--- | :--- |
| [modit](https://github.com/modit-engine/modit) | The core engine runtime, editor, and tooling. |
| [modit-demos](https://github.com/modit-engine/modit-demos) | Collection of demo projects showcasing Modit. |

## Why Open Source?

Modit is built by a solo developer to power my own UGC game. 

It's open-source under MIT for transparency and community adoption-**a better engine means a better game.** 

- **Core Engine:** I have a clear roadmap for the runtime, so **core PRs aren't being accepted just yet** while the architecture settles. 
- **Editor & Tooling:** I love a code-first approach. If you want to hack on the editor, build developer tools, or share ideas/suggestions, you are more than welcome!

## Help and security

Questions and bug reports are best on [Discord](https://discord.gg/QQ7yarSE5U) or in the issue tracker of the relevant repo.

Found a sandbox escape or another security problem? Please email [security@modit.dev](mailto:security@modit.dev) instead of posting it publicly.

---

Built by Case ([CaseIRL](https://github.com/CaseIRL)). Licensed under MIT.
