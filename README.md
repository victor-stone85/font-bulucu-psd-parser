# Font Bulucu v1.0.0 - PSD font parser 2026

> **Font Bulucu is a browser-based PSD font parser that lets you inspect text layers, typography settings, and font information from PSD files without launching Photoshop.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/victor-stone85/font-bulucu-psd-parser?style=flat-square)](https://github.com/victor-stone85/font-bulucu-psd-parser)

---

<p align="center">
  <a href="https://victor-stone85.github.io/font-bulucu-psd-parser/">
    <img src="https://img.shields.io/badge/Download-Font%20Bulucu%20Latest-brightgreen?style=for-the-badge" alt="Download Font Bulucu">
  </a>
</p>

> **[Direct Download - Font Bulucu v1.0.0](https://victor-stone85.github.io/font-bulucu-psd-parser/)**

---

[Download Latest Build](https://victor-stone85.github.io/font-bulucu-psd-parser/)

---

## What Font Bulucu Does

Font Bulucu is aimed at anyone who needs to examine typography inside PSD files without depending on Photoshop itself. In the browser, it reads text layers and presents font names, styling data, and more advanced text properties in a format that is straightforward to review and pass along.

It is a strong fit for scanlation work, typography verification, and fast PSD checks where font recognition is important. With drag-and-drop inspection, exportable output, and panel integration options, it works well both as a standalone utility and inside embedded setups.

---

## Capabilities

- Reads PSD text layers directly in the web interface
- Operates without opening Photoshop
- Detects font names and typography settings
- Flags faux bold and faux italic
- Accepts PSD files via drag and drop
- Exports TypeR JSON output and font lists
- Supports both standalone and embedded panel use
- Offers dark and light themes

---

## Getting Started

Download or clone the repository, then open the web app in your browser.

    git clone https://github.com/victor-stone85/font-bulucu-psd-parser.git
    cd REPO

If you are using the published build, open the latest web package from the download link and load a PSD file to begin analysis.

---

## How to Use It

1. Open Font Bulucu in your browser.
2. Drop a PSD file into the workspace, or select one with the file picker.
3. Inspect the parsed text layers, detected fonts, and typography details.
4. Export the output as TypeR JSON or as a font list when needed.

For embedded use, run the tool in the supported panel environment and connect it to the PSD source you want to review.

---

## Settings

Font Bulucu stores its preferences in the web app and panel environment, so no separate desktop config file is needed.

Common settings include:

- Theme preference for dark or light mode
- Export format selection
- Embedded panel behavior
- Input workflow preferences for PSD analysis

If you are deploying it in an integrated environment such as Nextcloud, configure the host platform according to your local setup.

---

## Requirements

- A modern web browser
- PSD files with text layers to analyze
- Access to local storage or the hosting environment for saved preferences
- Optional panel integration environment for embedded use
- Optional TypeR-compatible workflow if you plan to export JSON data

---

## Frequently Asked Questions

**Does it require Photoshop?**  
No. Font Bulucu is built to inspect PSD text layers without opening Photoshop.

**What kinds of details does it show?**  
It can identify font names, typography settings, and faux bold or faux italic styling.

**Can I use it inside another panel or platform?**  
Yes. The project includes standalone and embedded panel integration support, including Nextcloud-oriented use cases.

**How do I update it?**  
Use the latest published build from the download link, or pull the newest source if you are running it locally.

**Where are the settings stored?**  
Settings are handled within the app or the hosting environment, depending on whether you use it standalone or embedded.

**What should I do if a PSD does not parse correctly?**  
Check that the file contains supported text layers and try again with a fresh upload or drag-and-drop import.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
