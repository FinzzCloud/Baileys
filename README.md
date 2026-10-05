<div align="center">

# @FinzzCloud/baileys

**WhatsApp Web API untuk Node.js** — fork [Baileys](https://github.com/WhiskeySockets/Baileys) dengan fitur tambahan untuk kebutuhan bot: pesan interaktif, AI Rich Response, polling, dll

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
![Node](https://img.shields.io/badge/node-%3E%3D20.0.0-brightgreen)
![Module](https://img.shields.io/badge/type-ESM-blue)

</div>

---

## Tentang

`@FinzzCloud/baileys` adalah fork dari Baileys yang menambahkan fitur-fitur yang tidak ada di Baileys/WhiskeySockets standar, dibangun untuk kebutuhan bot WhatsApp sehari-hari: menu tombol, balasan ala-AI yang kaya format, dan polling hasil survei.

> Dipakai sebagai dependency langsung lewat GitHub:
> ```json
> "@whiskeysockets/baileys": "github:finzzcloud/Baileys"
> ```

## Fitur

- 💬 **Interactive message / tombol** — quick reply, CTA URL, dan native flow button lewat `sendMessage` atau builder `Button`
- 🤖 **AI Rich Response** — balasan terstruktur (teks, kode, tabel) lewat builder `AIRich`
- 📊 **Polling & hasil polling** — buat poll baru, atau kirim snapshot hasil vote (`pollResultMessage`)
- 📱 Mendukung fitur multi-device terbaru WhatsApp
- ⚙️ Mudah diintegrasikan ke bot/plugin berbasis ESM

## Instalasi

```bash
npm install github:finzzcloud/Baileys
```

Support **Node.js >= 20**.
