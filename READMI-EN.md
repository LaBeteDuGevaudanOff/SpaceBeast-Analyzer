<div align="center">

# SpaceBeast Analyzer

<p>
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-121011?style=for-the-badge&logoColor=E50914&labelColor=121011" />
  <img src="https://img.shields.io/badge/Architecture-x64-121011?style=for-the-badge&logoColor=E50914&labelColor=121011" />
  <img src="https://img.shields.io/badge/Type-Standalone%20Single--File-121011?style=for-the-badge&logoColor=E50914&labelColor=121011" />
</p>

High-performance cross-platform disk space analyzer and comprehensive storage cleanup utility.

**Author:** *La Bête du Gévaudan*  
**Distribution:** Standalone binaries (Portable / Single-File)  
**Supported Platforms:** Windows (x64), Linux (x64)

---

## Overview

**SpaceBeast Analyzer** is a professional-grade storage management utility engineered to visualize disk usage, detect hidden duplicate files, locate dormant data, and optimize file storage.

Distributed as a single, self-contained executable file, it operates 100% offline and requires no external dependencies or pre-installed .NET runtime environments.

---

## Key Features

* **High-Speed Scanning Engine:** Reactive multi-threaded traversal processing hundreds of thousands of files and directories in seconds.
* **Interactive Type Breakdown:** Segmented format distribution bar (graphics, video, audio, documents, archives) with instant one-click file tree filtering.
* **Age Heatmap:** Dynamic color coding based on last modification date (from vibrant green for recent files to bright red for dormant data older than 1 year).
* **Precise Duplicate Finder:** Two-stage detection pipeline (size matching + SHA-256 cryptographic hashing) to pinpoint 100% identical copies with clear Original/Duplicate indicators.
* **Junk Hunter:** Automated detection of temporary files (`.tmp`, `.log`, `.bak`, `.dmp`), cache directories, and empty folders for rapid disk decluttering.
* **Top 100 Files View:** Global flat list displaying the heaviest files across the entire scanned directory tree.
* **Live Search & Sorting:** Instant in-memory filtering and sorting without repetitive disk I/O.
* **Integrated File Operations:**
  * Safe removal to system Trash / Recycle Bin or permanent deletion with real-time tree and graph recalculation.
  * On-the-fly background ZIP archiving with automatic source cleanup to reclaim storage.
  * Native file manager integration with automatic target selection (Windows Explorer / Linux DBus & XDG).
* **Built-in Documentation:** Interactive user manual overlay accessible directly within the application.

---

## Download & Getting Started

Pre-compiled binary releases are available on the **[Releases](../../releases)** page.

### Windows (x64)
1. Download `SpaceBeast-Windows-x64.exe` from the latest release.
2. Run the executable (no installation required).
   > *Note:* If Microsoft Defender SmartScreen appears, click **"More info"** ➔ **"Run anyway"**.

### Linux (x64)
1. Download `SpaceBeast-Linux-x64` from the latest release.
2. Grant execution permissions and launch:
   ```bash
   chmod +x SpaceBeast-Linux-x64
   ./SpaceBeast-Linux-x64
   ```

---

## System Requirements

| Parameter | Requirement |
| :--- | :--- |
| **Operating System** | Windows 10 / 11 (64-bit) or Linux (glibc 2.31+, X11 / Wayland) |
| **Architecture** | x86_64 / amd64 |
| **Dependencies** | None (Self-Contained) |
| **Network** | Fully offline operation |

---

## License & Terms of Use

This software is provided on an **"AS IS"** basis for personal and commercial use.

All rights reserved © **La Bête du Gévaudan**.
