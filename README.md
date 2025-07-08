# 🌿 BiomeEvolution

**BiomeEvolution** is a Minecraft plugin that turns each biome into a living, responsive ecosystem. Designed for Spigot or Paper servers, this plugin rewards sustainable player behavior and punishes environmental exploitation — transforming how players interact with the world.

---

## 🌱 Features

- 🔄 Dynamic **biome health system** (0–100 scale per biome)
- 📉 Biome health decreases with:
  - Tree destruction
  - Killing passive mobs
  - Excessive block placement
- 📈 Biome health increases with:
  - Tree planting and environmental restoration
  - Player inactivity in that biome
- 🎯 Real gameplay impact:
  - **Healthy biomes** grant buffs (regeneration, speed, etc.)
  - **Degraded biomes** inflict debuffs (hunger, slowness, etc.)
- 💬 `/biomehealth` command to view biome status
- 🎮 BossBar display for local biome health
- 💾 Data saved in YAML config (`biomes.yml`)

---

## ⚙️ Requirements

- Minecraft **1.21**  
- Java **17+** (recommended for modern Spigot/Paper versions)
- [Vault](https://www.spigotmc.org/resources/vault.34315/) *(optional, if economy or permissions integration is added)*

---

## 📦 Installation

1. Download the plugin JAR and drop it into your server’s `/plugins` folder.
2. Restart the server, or if you have PlugManX installed /plugman reload BiomeEvolution
3. Configure the plugin via `plugins/BiomeEvolution/config.yml` (optional).
4. Enjoy a new, immersive survival experience!

---

## 📜 License

This project is open source under the Apache License 2.0 License. See `LICENSE` for more information.

---

## 🤝 Contribute

Pull requests are welcome! If you have suggestions, open an issue or start a discussion — let’s make the Minecraft ecosystem smarter, together 🌍

