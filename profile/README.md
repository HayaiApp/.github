# 🚀 Hayai - Fast Manga & Novel Reader

<div align="center">
  <a href="https://github.com/HayaiApp/hayai">
    <img src="https://raw.githubusercontent.com/HayaiApp/hayai/master/.github/readme-images/app-icon.webp" alt="Hayai logo" height="200px" width="200px" />
  </a>
</div>

## About Hayai

**Hayai** (早い) means **"fast"** in Japanese — and that's exactly what this project is about. Hayai is a free and open-source manga & novel reader that brings together the best features from the Tachiyomi ecosystem, optimized for speed and built with modern Android technologies.

We created Hayai because we wanted a Tachiyomi fork that prioritized performance, accessibility, and first-class novel support without sacrificing the features manga readers love.

## What We Do

Hayai cherry-picks the best pieces from across the Tachiyomi ecosystem while adding:

- **Performance-first design** - Optimized rendering, async plugin loading, and main-thread offloading
- **Accessibility** - Reduce motion support, proper ARIA/a11y across all screens, proper RTL support  
- **First-class novel support** - Native novel reader with JS plugin runtime (QuickJS), sourcing from LNReader
- **Modern architecture** - Kotlin Coroutines, Compose for UI, Material Design 3, proper state management
- **E-Hentai/ExHentai** - Full browsing, login, metadata, favorites sync, auto-update
- **Smart recommendations** - AniList, MyAnimeList, MangaUpdates, NovelUpdates with content-type awareness
- **Tabbed library** - Alternative continuous-scroll view with per-category swipeable pages

## Key Projects

### 🔹 [Hayai](https://github.com/HayaiApp/hayai)
The main Android application — manga & novel reader

**Latest features:**
- Reduce motion accessibility system
- Tabbed library display option
- Library update report screen  
- Novel reader UX overhaul (auto-scroll, flexible slider positioning, previous-chapter infinite-scroll)
- Recommendation system with content-type badges
- NHentai tag assets for local filtering

### 🔹 [Hayai Nightly](https://github.com/HayaiApp/hayai-nightly)
Automated nightly builds from the latest master branch code

## Quick Links

- **[Hayai Releases](https://github.com/HayaiApp/hayai/releases)** — Download stable, beta, and nightly builds
- **[Issue Tracker](https://github.com/HayaiApp/hayai/issues)** — Report bugs or request features
- **[Contributing Guide](https://github.com/HayaiApp/hayai/blob/master/.github/CONTRIBUTING.md)** — How to contribute code and translations
- **[Changelog](https://github.com/HayaiApp/hayai/blob/master/CHANGELOG.md)** — Detailed release notes and features
- **[LNReader Plugins](https://github.com/LNReader/lnreader-plugins)** — Novel source plugins we support

## Our Values

- **Open Source** — Fully transparent, community-driven development
- **Fast** — Performance optimizations across rendering, loading, and runtime
- **Accessible** — Supporting all users, including those with motion sensitivity or visual impairments
- **Feature-rich** — Best-in-class manga AND novel reading experience
- **Stable** — Reliable, well-tested code with crash reporting and monitoring

## Get Involved

We welcome contributions! Whether you're interested in:

- 💻 **Code** — Fix bugs, add features, optimize performance
- 🌍 **Translation** — Help localize Hayai to your language  
- 🐛 **Testing** — Report bugs and help us improve stability
- 📚 **Documentation** — Improve guides and inline code comments

See our [Contributing Guide](https://github.com/HayaiApp/hayai/blob/master/.github/CONTRIBUTING.md) to get started.

## Tech Stack

- **Language** — Kotlin 2.3+
- **Framework** — Android (API 24+)
- **UI** — Compose, Material Design 3, View-based layouts
- **State** — Kotlin Coroutines, Flow, SQLDelight
- **Plugins** — QuickJS (JavaScript runtime for LNReader novel plugins)
- **Build** — Gradle 8.x, AGP 8.12+

## Credits

Hayai builds on the shoulders of giants:

- **[Tachiyomi](https://github.com/tachiyomiorg/tachiyomi)** / **[Mihon](https://github.com/mihonapp/mihon)** — The original manga reader
- **[TachiyomiJ2K](https://github.com/Jays2Kings/tachiyomiJ2K)** — UI/UX innovations
- **[TachiyomiSY](https://github.com/jobobby04/TachiyomiSY)** — E-Hentai/ExHentai support
- **[Yōkai](https://github.com/null2264/yokai)** — Previous fork we built upon
- **[LNReader](https://github.com/LNReader/lnreader)** — Novel source ecosystem

---

<div align="center">

**Made with ❤️ by the Hayai community**

[Website](https://github.com/HayaiApp/hayai) • [Issues](https://github.com/HayaiApp/hayai/issues) • [Releases](https://github.com/HayaiApp/hayai/releases)

</div>
