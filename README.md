# LensForPBIP 🔍

[![GitHub Release](https://img.shields.io/github/v/release/artklas/LensForPBIP?style=flat-square&color=blue)](https://github.com/artklas/LensForPBIP/releases)
[![Platform](https://img.shields.io/badge/platform-Windows-lightgrey?style=flat-square)](https://github.com/artklas/LensForPBIP/releases)
[![License](https://img.shields.io/badge/license-Freeware-green?style=flat-square)](LICENSE.txt)

**Document, analyze, visualize, and edit Power BI Projects—all in one tool.**

Microsoft's move to the PBIP (Power BI Project) format is a massive leap forward for version control. However, reviewing changes or auditing complex models by looking at raw `.tmdl` or `.json` files is tedious and prone to error. More than that, creating comprehensive documentation of your entire data model, analyzing dependencies, and visualizing relationships typically requires significant manual effort or custom scripts.

**LensForPBIP solves this.** With one click, it parses your local PBIP folder and generates complete documentation of your data model, DAX measures, and report relationships. Analyze, visualize, and export your model—all through a clean, navigable interface with no code required. It's a standalone utility built to make the lives of BI developers easier.

---

## 📑 Table of Contents

- [Preview](#️-preview)
- [Features](#-features)
- [Download & Install](#-download--install)
- [Windows SmartScreen](#️-a-note-on-windows-smartscreen)
- [Quick Start](#-quick-start)
- [License & Usage](#️-license--usage)

---

## 🖼️ Preview

### Landing Page
Select your PBIP project folder and get instant documentation.

![Landing Page](docs/screenshots/landing_page.png)

---

### Documentation
#### Overview
Get a bird's-eye view of your project with key statistics and an Export Center.

![Overview](docs/screenshots/overview.png)

---

### Semantic Model
#### Data Sources
View data source connections, M code, and transformation pipelines.

![Data Sources](docs/screenshots/data_sources.png)

#### Tables
Browse table schemas with column properties and data types.

![Tables](docs/screenshots/tables.png)

#### Measures
Inspect DAX expressions, folder organization, and copy-to-clipboard.

![Measures](docs/screenshots/measures.png)

#### Measures (Edit Mode)
Create, edit, and delete measures directly. Includes Quick Measures Library and Time Intelligence Wizard.

![Measures Edit Mode](docs/screenshots/measures_edit_mode.png)

#### Model View
Visualize your data model relationships with an interactive, draggable diagram.

![Model View](docs/screenshots/model_view.png)

---

### Report
#### Pages & Visuals
Audit page hierarchy, visual types, and field mappings.

![Pages & Visuals](docs/screenshots/pages_visuals.png)

---

### Tools
#### Model Analyzer
Find unused tables, columns, and measures that may be bloating your model.

![Model Analyzer](docs/screenshots/model_analyzer.png)

#### Dependency Analyzer
Visualize measure and column dependencies as an interactive graph. Trace DAX lineage and identify circular references.

![Dependency Analyzer](docs/screenshots/dependency_analyzer.png)

---

## ✨ Features

### 📊 Semantic Model Documentation
| Feature | Description |
|---------|-------------|
| **Data Sources** | View data source connections, M code, and transformation pipelines |
| **Tables & Columns** | Browse table schemas with column properties and data types |
| **Measures** | Inspect DAX expressions with syntax highlighting & quick copy |
| **Model View** | Interactive relationship diagram with drag, zoom, and export |

### 📄 Report Analysis
| Feature | Description |
|---------|-------------|
| **Pages & Visuals** | Audit page hierarchy, visual types, and field mappings |
| **Visual Filters** | See which filters are applied to each visual |

### 🛠️ Developer Tools
| Feature | Description |
|---------|-------------|
| **Model Analyzer** | Identify unreferenced tables, columns, and measures |
| **Dependency Analyzer** | Interactive DAX lineage graph with circular reference detection |
| **Edit Mode** | Create, edit, and delete measures directly from the UI |
| **Quick Measures Library** | Pre-built measure templates (YoY, Running Total, etc.) |
| **Time Intelligence Wizard** | Generate common time intelligence calculations |
| **Display Folder Manager** | Organize measures into nested display folders |

### 📥 Export Options
- **Full Documentation**: Export as HTML or DOCX with customizable sections
- **Data Export**: Export to Excel (.xlsx) or JSON with selectable components
- **Model View Snapshot**: Export the relationship diagram as SVG or PNG

---

## 📥 Download & Install

### 1. Get the Installer
Download the latest `LensForPBIP_Setup.exe` from the [**Releases Page**](https://github.com/artklas/LensForPBIP/releases).

### 2. Run the Setup
Run the executable and follow the standard installation prompts.

---

## 🛡️ A Note on Windows SmartScreen

When you run the installer, you will likely see a blue window saying **"Windows protected your PC."**

**Why is this happening?**  
This is a standard Windows security feature for software that hasn't purchased an expensive "Code Signing Certificate." As a developer releasing this as a free hobby project, I haven't purchased a certificate yet.

**How to proceed:**
1. Click **"More info"**
2. Click **"Run anyway"**

If you are concerned about security, feel free to run the executable in a sandbox or VM first.

---

## 🚀 Quick Start

1. **Launch** LensForPBIP
2. **Click "Browse"** or paste the path to your `.pbip` project folder
3. **Click "Generate Documentation"** to load your project
4. **Navigate** through the sidebar to inspect your Model, Measures, and Reports
5. **(Optional)** Export the documentation for your records

---

## ⚖️ License & Usage

**LensForPBIP is Freeware.**

I built this tool to help with my own Power BI workflows and decided to share it with the community.

| ✅ Allowed | ❌ Prohibited |
|-----------|--------------|
| Personal use | Redistribution |
| Educational use | Modification |
| Commercial business purposes | Reverse engineering |
| | Selling this software |

For the full legal details, please read the [EULA](LICENSE.txt).

---

<p align="center">
  <strong>Copyright © 2026 Lens For PBIP. All Rights Reserved.</strong>
</p>

<p align="center">
  <a href="https://github.com/artklas/LensForPBIP">View on GitHub</a> •
  <a href="https://github.com/artklas/LensForPBIP/releases">Download Latest Release</a>
</p>
