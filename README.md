# 🤖 Slobos & Mr. Juice Aternos 24/7 Hosting Bot

A Minecraft bot that helps keep an Aternos server online 24/7 by automatically joining it using a Mineflayer-based bot. Perfect for SMPs or small multiplayer servers that shut down when no players are online.

---

## ✨ Features
*   ✅ **Auto-Connect**: Automatically joins your server.
*   ✅ **Infinite Uptime**: Prevents AFK kicks and server shutdowns.
*   ✅ **Smart Reconnect**: Automatically reconnects if the internet drops or server restarts.
*   ✅ **Render-Ready**: Includes "Self-Ping" to run 24/7 for FREE on Render.com.
*   ✅ **Plugin Support**: Compatible with Paper/Spigot/Bukkit (auto-auth included).

---

## 🛠️ Requirements
*   **GitHub Account**
*   **Aternos Server**
*   **Render Account** (for 24/7 hosting)
*   **Common Sense!** 🧠        

---

## 🚀 Setup Guide

We have made setup super easy! Check out the guide below:

[**Detailed Google Doc Guide**](https://docs.google.com/document/d/1Fl0dRzP6O30ehp5-QcaB11IobF8I1JJhKUipzCWiCYA/edit?tab=t.0).

---

## ⚙️ Usage
*   **Start**: Just turn on your Aternos server. The bot will join automatically.
*   **Status**: Visit the Render URL to see a status dashboard.
*   **Chat**: The bot logs chat to the console.

---

## 🔄 Minecraft Version Compatibility
*   The bot can only speak versions supported by `minecraft-protocol`/`minecraft-data` (check `package-lock.json`; currently up to **26.1**).
*   **Recommended**: leave `"version": ""` in `settings.json`. The bot then auto-detects the server version, and if the server is newer than the bot (e.g. right after an Aternos auto-update), it automatically falls back through the newest client versions it supports.
*   **Server updated to a brand-new Minecraft version?** The bot logs a clear `[Version] [!!!]` explanation. Your options until the ecosystem catches up:
    1.  On Aternos, set the server back to the previous version (e.g. **26.2**) — keep ViaVersion + ViaBackwards installed so the bot (and your Bedrock players via Geyser) can join.
    2.  Wait for **ViaBackwards**/**Geyser** to add support for the new version, then update those plugins on Aternos.
    3.  Update this bot (`npm update`, commit, redeploy) once mineflayer/minecraft-protocol support the new version.
*   Want a fixed client protocol anyway? Set `"version": "26.1"` (or any supported version) in `settings.json` — the bot tries auto-detect first, then your pin, then the other supported versions.

---

## ⚠️ Disclaimer
This project is not affiliated with Aternos, Mojang, or Microsoft. Use at your own risk. Misuse may violate platform terms of service. This bot does not bypass Aternos queue limits; it only keeps the server active once it is online.

---

## ❤️ Credits
*   **Slobos (Discord: sloboscc)** — Original creator & idea. (The GOAT 🐐)
*   **Mr.Juice (Discord: Mr.Juice3046)** — Updates, Guide, & Maintenance.

**License**: MIT License
