# FastMinecart

A lightweight Minecraft mod that makes minecarts significantly faster, turning rails into a viable high-speed transportation option.

- Works in singleplayer and on servers
- Optional server-side-only usage (clients don’t need the mod if the server has it)
- Minimal, focused change: just faster minecarts, no extra mechanics


---

## Features

- **Increased minecart speed**  
  Minecarts travel noticeably faster than vanilla, making rail networks practical for medium- and long-distance travel.

- **Server-side compatible**  
  - Install on the server only: all players benefit without needing the mod.  
  - Install on the client only: works in singleplayer or on servers where you control the client.

- **Simple and unobtrusive**  
  No commands, no configuration, no new items—just faster minecarts.

---

## Installation

### Requirements

- Minecraft Java Edition
- A compatible mod loader (Fabric / Forge / NeoForge, depending on the build you use)
- Matching Minecraft version for the mod JAR you download

### Steps

1. **Install a mod loader**  
   Install Fabric, Forge, or NeoForge for your Minecraft version, depending on which build of FastMinecart you’re using.

2. **Download the mod**  
   Get the latest `FastMinecart-*.jar` from:
   - [Releases](../../releases) in this repository, or  
   - [Modrinth](https://modrinth.com/mod/fast-minecart) (if published there)

3. **Add to your mods folder**  
   - For client:  
     Place the JAR into `.minecraft/mods` (or the equivalent for your launcher/profile).
   - For server:  
     Place the JAR into the server’s `mods` folder.

4. **Launch the game / restart the server**  
   Start Minecraft with the matching mod loader profile, or restart your server. Minecarts should now be faster.

> **Note:**  
> - Client-only installation affects only your own game.  
> - Server-only installation affects all players on that server.  
> - Having it on both client and server is fine; it won’t “stack” speeds.

---

## Usage

There is nothing to configure or toggle:

- Enter a minecart as usual.
- Enjoy significantly faster travel along rails.

If you remove the mod, minecarts return to vanilla speed.

---

## Compatibility

- Designed to be compatible with standard vanilla rails and minecarts.
- Should work alongside most other mods that don’t directly override minecart physics.
- If you notice unusual behavior (e.g., jittery movement on newer versions), try:
  - Updating to the latest FastMinecart build.
  - Testing without other physics- or movement-related mods.

---

## Building from Source

If you want to build or modify the mod yourself:

1. **Clone the repository**
   ```bash
   git clone https://github.com/Aleksei-Spiridonov/FastMinecart.git
   cd FastMinecart
   ```

2. **Open in your IDE**  
   Import the project as a Gradle project (recommended: IntelliJ IDEA or VS Code with Java extensions).

3. **Build the mod**
   ```bash
   ./gradlew build
   ```
   On Windows:
   ```bash
   gradlew.bat build
   ```

4. **Find the built JAR**  
   The compiled mod JAR will be in:
   ```text
   build/libs/FastMinecart-*.jar
   ```

Adjust versions, mappings, or loader targets in the build configuration as needed for your environment.


---
