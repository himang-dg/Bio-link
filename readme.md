<a id="top"></a>

<div align="center">

# 🔗 Bio Link

A sleek, modern **bio link page** with glassmorphism design, animated backgrounds, and dynamic link rendering — built with **pure HTML, CSS & JavaScript**.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-%F0%9F%9A%80-blue?style=for-the-badge)](https://bio-himang.netlify.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

</div>

<hr/>
<div align="center">
<h3>💸 Support me 💰</h3>
<table align="center">
  <tr>
     <td align="center">
      <a href="https://paypal.me/DogGhozt" target="_blank">
        <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/paypal/default.svg" width="52" height="40" alt="paypal logo" />
      </a>
    </td>
    <td align="center">
  <a href="https://tako.id/himang" target="_blank">
    <img src="https://img.icons8.com/?size=100&id=13013&format=png&color=000000" width="52" height="40" alt="buy me a coffee" />
  </a>
</td>
  </tr>
</table>
</div>
<hr/>



## ✨ Features

- 🎨 **Glassmorphism UI** — frosted glass cards with subtle borders and backdrop blur
- 🌌 **Animated Background Mesh** — floating gradient blobs with smooth drift animation
- 📱 **Fully Responsive** — looks great on mobile, tablet, and desktop
- ⚡ **Dynamic Link Rendering** — all links are rendered from a simple JS config file
- 🎭 **30+ Platform Icons** — built-in SVG icons for popular platforms (GitHub, YouTube, Instagram, Discord, TikTok, etc.)
- 🖌️ **Per-Link Theming** — each link card gets its own color scheme based on the platform
- ✅ **Verified Badge** — animated profile badge with glow effect
- 🔧 **Easy to Customize** — just edit `public/link.js` to add/remove/reorder links
- ♿ **Accessibility** — respects `prefers-reduced-motion`, semantic HTML
- 🚀 **Zero Build Required** — no framework, no bundler, just open `index.html`



## 🚀 Demo

[🔗 Live Demo — bio-link-himang](https://bio-himang.netlify.app/)

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Semantic structure |
| Vanilla CSS | Glassmorphism, animations, responsive layout |
| Vanilla JavaScript | Dynamic link rendering, SVG icon system |
| Google Fonts (Inter) | Modern typography |

## 📦 Project Structure

```
Bio-link/
├── index.html          # Main page (HTML + CSS + JS)
├── public/
│   └── link.js         # Link configuration file
├── package.json
└── readme.md
```

## ⚙️ Installation & Usage

### Quick Start (No Build)

1. Clone the repository:
   ```bash
   git clone https://github.com/himang-dg/Bio-link.git
   cd Bio-link
   ```

2. Open `index.html` in your browser — that's it! 🎉

### Customize Your Links

Edit `public/link.js` to add, remove, or reorder your links:

```javascript
const links = [
  { type: 'website',   label: 'Portfolio',  url: 'https://yoursite.com' },
  { type: 'github',    label: 'GitHub',     url: 'https://github.com/you' },
  { type: 'instagram', label: 'Instagram',  url: 'https://instagram.com/you' },
  { type: 'youtube',   label: 'YouTube',    url: 'https://youtube.com/@you' },
  // ... add more links here!
];
```

### Supported Platforms

<details>
<summary>Click to see all 30+ supported platforms</summary>

| Platform | Type Key |
|---|---|
| Website / Portfolio | `website` |
| Facebook | `facebook` |
| Instagram | `instagram` |
| Twitter / X | `twitter` |
| YouTube | `youtube` |
| GitHub | `github` |
| TikTok | `tiktok` |
| Telegram | `telegram` |
| Pinterest | `pinterest` |
| LinkedIn | `linkedin` |
| Spotify | `spotify` |
| Discord | `discord` |
| Dribbble | `dribbble` |
| Medium | `medium` |
| PayPal | `paypal` |
| Twitch | `twitch` |
| WhatsApp | `whatsapp` |
| Threads | `threads` |
| Roblox | `roblox` |
| Steam | `steam` |
| Snapchat | `snapchat` |
| Kick | `kick` |
| LINE | `line` |
| Shopee | `shopee` |
| Tokopedia | `tokopedia` |
| Saweria | `saweria` |
| Trakteer | `trakteer` |
| Ko-fi | `kofi` |
| Email | `email` |
| Marketplace | `marketplace` |
| Buy Me a Coffee | `coffee` |
| Generic Link | `link` |

> 💡 If a `type` is not recognized, it will fallback to the generic link icon 🔗

</details>

## 🎨 Customization

| What | Where |
|---|---|
| Links & Labels | `public/link.js` |
| Profile photo, name, bio | `index.html` → `<section class="profile">` |
| Colors & theme | `index.html` → `:root` CSS variables |
| Background blobs | `index.html` → `.bg-blob-*` classes |
| Footer text | `index.html` → `<footer>` |

## 🤝 Contributing

Feel free to fork this repository and contribute by submitting a pull request.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

<p align="right">
  <a href="#top">
    <img src="https://img.icons8.com/?size=100&id=114041&format=png" alt="Back to top" width="70" height="70">
  </a>
</p>
