# Nexus

A private AI assistant that runs **fully offline** on your computer. Your chats never leave your PC.

## Download (Windows 10/11, 64-bit)

**[⬇ Download the latest Nexus](https://github.com/4bhimxnyu/Nexus-releases/releases/latest)**: run `Nexus-Setup-<version>.exe` from the Assets list.

1. Windows may say "Windows protected your PC" because the installer isn't code-signed yet: click **More info → Run anyway**.
2. On the first start (internet on), Nexus sets itself up with progress on screen:
   - installs [Ollama](https://ollama.com), the free program that runs the AI (about 1.7 GB, if it isn't already installed)
   - downloads the AI model phi4-mini (about 2.5 GB) and a small search model (0.3 GB)
3. After that Nexus works with the internet off, and updates itself when you're online.

**Needs:** about 6 GB free disk space and 8 GB RAM. A graphics card is optional (it makes answers faster).

macOS: coming later.

## Licence

Nexus is © 2026 Abhimanyu, licensed under the GNU AGPL-3.0. The AI model (phi4-mini, MIT),
Ollama (MIT) and the other parts keep their own licences, listed in `THIRD-PARTY-LICENSES.md`
inside the app.

This repository only hosts installers. Report problems in [Issues](https://github.com/4bhimxnyu/Nexus-releases/issues).
