# :fire: RedLotus Alt Checker
### :sparkles: Latest Major Update
*   **:busts_in_silhouette: Massive Client Support**
> Added detection for **Lunar, Badlion, Feather, Meteor, Wurst, Aristois, Impact, LabyMod, LiquidBounce, Sigma, Prism, Modrinth, ATLauncher, Technic, SKlauncher, PolyMC, CurseForge, MultiMC**, and more.
*   **:id: UUID Auto-Resolver**
> Implemented a smart **UUID Resolver**. The tool automatically fetches real usernames from Mojang's API for any UUIDs found in logs or config files.
> *Note: This means the tool is no longer 100% offline. It connects to Mojang's API and a UUID fallback API for name resolution.*
*   **:mag: Recursive Directory Scanning**
> The scanner now digs deeper!
*   **:crossed_swords: Hytale Support**
> Added username detection support for **Hytale** (Launcher logs and configuration files).
---
### :gear: Core Features
*   **:zap: Universal Account Scanner**
> Automatically extracts accounts from **Minecraft, Steam, Discord, Hytale, and Windows Users**.
*   **:mag: Smart "Fuzzy" Target Search**
> Uses an intelligent algorithm to find username variations (`TheGamer` / `Th3_G4m3r_01`) and typos that standard searches might miss.
*   **:floppy_disk: Advanced Forensics (USN Journal)**
> Retrieves a detailed history of **deleted and modified Minecraft-related files** over the last 14 days, exposing potential cleaning attempts.
### :chart_with_upwards_trend: Performance & Design
*   **:rocket: Deep & Fast:** Scans gigabytes of data in just a few seconds.
*   **:broom: Smart Cleanup:** Automatically filters noise and duplicates, giving you a clean, easy-to-read report sorted by platform.
*   **:bug: Stability:** Fixed minor bugs and glitches reported on specific PC configurations.
### :shield: Privacy & Security
*   **:lock: Privacy First:** No data, logs, or results are ever sent to external servers **(except Mojang API/Fallback for UUID resolution)**.
*   **:briefcase: Public Data Only:** We only extract **public display names**. Sensitive data like passwords, emails, or session tokens are **never** accessed or displayed.
*   **:handshake: Ethical Design:** Automated scanning removes the need for manual digging through personal user folders, protecting everyone's privacy.
### :construction: Roadmap
*   **:bricks: Bedrock Edition Support**
> Planning to implement support for **Minecraft Bedrock** in the near future!
**Download Tool:** https://github.com/ItzIceHere/RedLotusAltChecker/releases/download/RL/RedLotusAltChecker.exe
