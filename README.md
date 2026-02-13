# :fire: RedLotus Alt Checker

## :sparkles: New in Update 2.0
*   **:rocket: Massive Performance Overhaul**
> Complete rewrite of the scanning engine. Now utilizes **Memory Mapping** and **Single-Pass Search** for blazing fast execution with minimal RAM usage.
*   **:floppy_disk: Multi-Drive Scanning (A-Z)**
> The tool now scans **ALL fixed drives** connected to the system. This includes both the instant **MFT Scan** and **USN Journal Forensics**.
*   **:mag: Recursive Directory & MFT Integration**
> Directly parses the **Master File Table (MFT)** for instant results across all drives, while maintaining deep recursive scanning for complex folder structures.
*   **:busts_in_silhouette: Massive Client Support**
> Added detection for **Lunar, Badlion, Feather, Meteor, Wurst, Aristois, Impact, LabyMod, LiquidBounce, Prism, Modrinth, ATLauncher, Technic, SKlauncher, PolyMC, CurseForge, MultiMC**, and many others.
*   **:id: UUID Auto-Resolver**
> Checks are no longer just offline! The tool automatically fetches real usernames from **Mojang's API** for any UUIDs found in logs or config files.

---

### :gear: Core Features
*   **:zap: Universal Account Scanner**
> Extracts accounts from **Minecraft** (Java & Launchers), **Steam**, **Discord**, **Hytale**, and **Windows System Users**.
*   **:mag: Smart "Fuzzy" Target Search**
> Uses an intelligent algorithm to find username variations (`TheGamer` / `Th3_G4m3r_01`) and typos that standard searches might miss.
*   **:floppy_disk: Advanced Forensics (USN Journal)**
> Retrieves a detailed history of **deleted and modified Minecraft-related files** over the last 14 days, exposing potential cleaning attempts.
*   **:crossed_swords: Hytale Support**
> Added username detection support for **Hytale** (Launcher logs and configuration files).

### :shield: Privacy & Security
*   **:lock: Privacy First:** No data, logs, or results are ever sent to external servers **(except Mojang API/Fallback for UUID resolution)**. All processing happens locally.
*   **:briefcase: Public Data Only:** We only extract **public display names**. Sensitive data like passwords, emails, or session tokens are **never** accessed or displayed.
*   **:handshake: Ethical Design:** Automated scanning removes the need for manual digging through personal user folders, protecting everyone's privacy.

### :construction: Roadmap
*   **:bricks: Bedrock Edition Support**
> Also planned: Support for **Minecraft Bedrock** is coming soon!

**Download Tool:** https://github.com/ItzIceHere/RedLotusAltChecker/releases/download/RL/RedLotusAltChecker.exe
