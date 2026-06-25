# -VLESS-XTLS-Reality-OpenWrt-guide
A practical guide to deploying VLESS + XTLS + REALITY on OpenWrt for stable cross-border network relay. Covers protocol deep-dives, MTU/Mux optimization, and full-stack troubleshooting.
📖 **閱讀完整指南（繁體中文 v1.3）**：[`guide-v1.3.zh-CN.md`](./guide-v1.3.zh-CN.md)

---

## 🌍 Language Note

The complete guide is currently written in **Chinese (Simplified)**.  
**We warmly welcome translations!** If you'd like to translate it into English or any other language, please see the [Contributing](#contributing) section below.

---

## Who Is This For?

- Users inside mainland China who need stable, unfiltered access to the global internet.
- OpenWrt router owners (or those ready to flash) with basic Linux familiarity.
- Network enthusiasts interested in the VLESS + XTLS + REALITY protocol stack and real‑world optimization.

## What's Inside

- **Protocol deep‑dive** – Why VLESS, XTLS, and REALITY were chosen, and how they work together.
- **Server & client configuration** – Fully working examples with every parameter explained.
- **Low‑level link optimization** – MTU tuning, Mux disabling, DNS anti‑timeout measures.
- **IPv6 dual‑stack priority forwarding** – Bypass congested IPv4 routes using native IPv6.
- **Full‑stack troubleshooting** – Tables covering everything from firmware flashing to TLS handshake failures.

## Getting Started

1. **Read the guide** → [`guide-v1.3.zh-CN.md`](./guide-v1.3.zh-CN.md) (Chinese)
2. **Grab the example server config** → [`config-examples/config-server.json`](./config-examples/config-server.json)
3. **Deploy on your OpenWrt router** following the step‑by‑step instructions.

## Contributing

We ❤️ contributions! Here's how you can help:

### 🌐 Translation

We are actively looking for translators to bring this guide to:
- **English**
- **Japanese**
- **Korean**
- … and any other language.

If you'd like to translate:
1. Open an **Issue** with the title `[i18n] Translation for <language>` to let others know you're working on it.
2. Fork the repo, create your translated `.md` file (e.g., `guide-v1.3.en.md`).
3. Submit a **Pull Request** – we'll review and merge it promptly.

### 🐛 Fixes & Improvements

Found a mistake, outdated info, or a smarter way to do things?  
Open an **Issue** or submit a **PR** directly. All technical contributions are appreciated.

## License

This work is licensed under a [Creative Commons Attribution‑ShareAlike 4.0 International License](LICENSE).  
You are free to share and adapt, as long as you give appropriate credit and distribute under the same license.

---

*Happy tunneling!* 🚀
