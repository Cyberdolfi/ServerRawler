<div align="center">
  <h1>ServerRawler</h1>
  <p>A high-performance Minecraft server scanner written in Rust</p>
</div>

---

<div align="center">
  <a href="https://rust-lang.org/"><img src="https://img.shields.io/badge/rust-gray?style=for-the-badge&logo=rust&logoColor=orange" alt="Rust"/></a>
  <a href="https://mysql.com/"><img src="https://img.shields.io/badge/mysql-gray?style=for-the-badge&logo=mysql&logoColor=orange" alt="MySQL"/></a>
  <a href="https://www.jetbrains.com/"><img src="https://img.shields.io/badge/jetbrains-gray?style=for-the-badge&logo=jetbrains&logoColor=orange" alt="JetBrains"/></a>
  <br>
  <a href="https://discord.gg/m4hhckJe4v"><img src="https://img.shields.io/discord/1421594734442319996.svg?style=for-the-badge&logo=discord&logoColor=orange&label=discord&color=orange" alt="Discord"/></a>
  <a href="https://github.com/Cyberdolfi/ServerRawler/releases/"><img src="https://shields.io/github/downloads/cyberdolfi/serverrawler/total?style=for-the-badge&label=github%20downloads&color=orange&logo=github&logoColor=orange" alt="GitHub Downloads"/></a>
</div>

---

> [!NOTE]
> Languages:  
> [**[🇩🇪] Deutsch**](./README_de.md)  
> [**[🇬🇧] *English***](./README.md)

> [!IMPORTANT]
> This project is currently in early alpha!
> The first beta release is coming soon...

---

The **ServerRawler** by Cyberdolfi is a Minecraft server scanner (or crawler – however you want to call it),  
that tries to find as many servers as it can.

---

## ✨ Features
- ⏰ Optimized for high performance
- 📝 Supported protocols:
  - Minecraft **Ping** protocol
  - Minecraft **Query** protocol
  - Minecraft **Join** protocol
- 🔷 Control and monitoring via Discord bot
- 🔥 Easy to install and configure
- 💾 Saves data in a MySQL database

## ⏳ Planned
- 💾 SQLite support
- 🛜 Proxy support
- 🟢 Stable release

---

### 📑 What data does it save?
- MotD
- Max./Online players
- Online players (with **Username** and **UUID**)
- Plugins
- Mods
- Online mode
- Whitelist (only when the server is cracked)
- Server version and software
- ... and much more!

---

## 🚫 How to prevent your server from being scanned

### Use description:
You can add `§b§d§f§d§b` to the end of your server's description by changing the `server.properties` file.  
This change is invisible to the client and won't change the appearance of your server's description *in most cases*.

If the server is discovered again in the future, it will be automatically excluded **and removed from the database**.

More information can be found in the documentation.

---

## 📥 Installation
> Installation instructions will be available in the Wiki soon.

---

## 📜 License

This project is licensed under the [MIT License](./LICENSE).

---

## 🤝 Contributing

* Found a bug? → [Create an issue](https://github.com/Cyberdolfi/ServerRawler/issues)
* Have ideas or suggestions? → Join my [Discord](https://discord.gg/4wHFzBjDTY "Discord")

---

> [!WARNING]
> This tool is intended for educational and research purposes only.  
> The authors are not responsible for any misuse of this tool.  
> Only publicly accessible data exposed by the Minecraft server protocols is collected.  
> Scanning servers without permission may violate terms of service or local laws.