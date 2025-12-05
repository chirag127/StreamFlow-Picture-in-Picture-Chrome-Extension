# StreamFlow-Picture-in-Picture-Chrome-Extension

![Build Status](https://img.shields.io/github/actions/workflow/user/chirag127/StreamFlow-Picture-in-Picture-Chrome-Extension/ci.yml?style=flat-square&logo=githubactions)
![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/StreamFlow-Picture-in-Picture-Chrome-Extension?style=flat-square&logo=codecov)
![Tech Stack](https://img.shields.io/badge/tech-JavaScript-blue?style=flat-square&logo=javascript)
![Lint/Format](https://img.shields.io/badge/biome-checked-f67819?style=flat-square&logo=biome)
![License](https://img.shields.io/badge/license-CC%20BY--NC%204.0-red?style=flat-square&logo=creativecommons)
![GitHub Stars](https://img.shields.io/github/stars/chirag127/StreamFlow-Picture-in-Picture-Chrome-Extension?style=flat-square&logo=github)

---


**Seamlessly activate Picture-in-Picture mode for any video on the web.** This Chrome Extension enhances your browsing by allowing you to multitask and keep videos visible while navigating other tabs, boosting productivity and content consumption.

---


## 🚀 Project Overview

StreamFlow is a sophisticated yet user-friendly Chrome Extension designed to empower users with immediate access to the Picture-in-Picture (PiP) API. It enables continuous video playback in a floating, always-on-top window, facilitating seamless multitasking and enhancing the overall web experience.

## 🌳 Project Structure

text
StreamFlow-Picture-in-Picture-Chrome-Extension/
├── public/
│   └── manifest.json
├── src/
│   ├── content/
│   │   └── picture-in-picture.js
│   ├── popup/
│   │   ├── index.html
│   │   ├── index.js
│   │   └── index.css
│   └── service-worker.js
├── .gitignore
├── AGENTS.md
├── badges.yml
├── CONTRIBUTING.md
├── ISSUE_TEMPLATE
│   └── bug_report.md
├── LICENSE
├── Makefile
├── PULL_REQUEST_TEMPLATE.md
├── README.md
├── SECURITY.md
├── ci.yml
├── package.json
├── postcss.config.js
├── tailwind.config.js
├── tsconfig.json
└── vite.config.js


## 📄 Table of Contents

*   [🚀 Project Overview](#-project-overview)
*   [🌳 Project Structure](#-project-structure)
*   [✨ Features](#-features)
*   [🛠️ Getting Started](#-getting-started)
*   [🚀 Development Workflow](#-development-workflow)
*   [🧪 Testing](#-testing)
*   [🔒 Security](#-security)
*   [🤝 Contributing](#-contributing)
*   [📜 License](#-license)
*   [🤖 AI Agent Directives](#-ai-agent-directives)

---


## ✨ Features

*   **One-Click PiP Activation:** Instantly enter Picture-in-Picture mode for videos across supported websites.
*   **Seamless Multitasking:** Keep your video focused while browsing other tabs or applications.
*   **Modern Web Standards:** Built using up-to-date JavaScript, HTML, and CSS, with a focus on performance and compatibility.
*   **User-Friendly Interface:** An intuitive popup for easy access and control.

---


## 🛠️ Getting Started

Follow these steps to set up the project locally.

### Prerequisites

*   [Node.js](https://nodejs.org/) (v20.x or higher recommended)
*   [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/) (npm is used in this guide)

### Installation

1.  **Clone the repository:**
    bash
    git clone https://github.com/chirag127/StreamFlow-Picture-in-Picture-Chrome-Extension.git
    cd StreamFlow-Picture-in-Picture-Chrome-Extension
    

2.  **Install dependencies:**
    bash
    npm install
    

### Running the Extension

1.  **Build the extension:**
    bash
    npm run build
    

2.  **Load the extension in Chrome:**
    *   Open Chrome and navigate to `chrome://extensions/`.
    *   Enable "Developer mode" using the toggle in the top-right corner.
    *   Click "Load unpacked" and select the `dist` folder (or the configured output directory from `vite.config.js`) from the project root.

---


## 🚀 Development Workflow

### Local Development Server

To run the extension in development mode with hot-reloading:

bash
npm run dev


This command will build the extension and watch for changes. You will need to reload the extension in `chrome://extensions/` to see the updates.

### Scripts

| Script        | Description                                       |
| ------------- | ------------------------------------------------- |
| `npm install` | Installs project dependencies.                    |
| `npm run dev` | Runs the development server with hot-reloading.   |
| `npm run build`| Bundles the extension for production.             |
| `npm run lint`| Runs the linter (Biome) to check code quality.    |
| `npm run format`| Formats code using the formatter (Biome).       |
| `npm run test`| Executes unit and integration tests (Vitest).   |

### Development Principles

*   **SOLID:** Adhere to the Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, and Dependency Inversion principles.
*   **DRY:** Avoid repeating code; abstract common logic into reusable functions or components.
*   **YAGNI:** You Ain't Gonna Need It. Implement only what is currently required.

---


## 🧪 Testing

This project uses [Vitest](https://vitest.dev/) for unit and integration testing, and [Playwright](https://playwright.dev/) for end-to-end testing.

*   **Unit/Integration Tests:** Run with `npm run test`.
*   **End-to-End Tests:** (Setup required for Playwright. Refer to `package.json` scripts for details).

---


## 🔒 Security

*   **Dependency Vulnerability Scanning:** Regularly run `npm audit` to check for known vulnerabilities in project dependencies.
*   **Secure API Usage:** Ensure all browser APIs are used securely and with appropriate permissions. Refer to `manifest.json` for declared permissions.
*   **Data Handling:** Sensitive user data is not stored or transmitted unnecessarily. Adhere to Chrome Extension security best practices.

---


## 🤝 Contributing

We welcome contributions! Please see the [`CONTRIBUTING.md`](.github/CONTRIBUTING.md) file for detailed guidelines on how to submit your contributions.

---


## 📜 License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)**. See the [LICENSE](LICENSE) file for more details.

---


## 🤖 AI Agent Directives

<details>
<summary>View AI Agent Directives</summary>

# SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

## 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

---

## 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

---

## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** Detect the project type and apply the **Apex Toolchain**. This repository, `StreamFlow-Picture-in-Picture-Chrome-Extension`, is a JavaScript-based browser extension.

*   **PRIMARY SCENARIO: WEB / APP / EXTENSION (JavaScript/TypeScript)**
    *   **Stack:** This project leverages **JavaScript (ES2020+)** and **TypeScript 6.x (Strict Mode)**. The build tool is **Vite 7 (Rolldown)**, ensuring rapid development builds. For native integration or desktop packaging (if ever needed), **Tauri v2.x** is the standard. For browser extensions specifically, **WXT (Web Extension Tooling)** is the unified framework.
    *   **UI/Styling:** **TailwindCSS v4** for utility-first styling, integrated with **PostCSS**. State management will utilize **Signals (Standardized)** for efficient reactivity.
    *   **Linting & Formatting:** **Biome** is the mandated tool for ultra-fast linting and formatting, ensuring code consistency and quality.
    *   **Testing:** **Vitest** for unit and integration testing, and **Playwright** for robust end-to-end testing.
    *   **Architecture:** **Feature-Sliced Design (FSD)** is the recommended pattern for structuring the frontend codebase, promoting maintainability and scalability.

*   **SECONDARY SCENARIO A: SYSTEMS / PERFORMANCE (Rust/Go) - *Not applicable for this project's primary function.***
    *   **Stack:** Rust (Cargo), Go (Modules).
    *   **Lint:** Clippy / GolangCI-Lint.
    *   **Architecture:** Hexagonal Architecture (Ports & Adapters).

*   **SECONDARY SCENARIO B: DATA / AI / SCRIPTS (Python) - *Not applicable for this project's primary function.***
    *   **Stack:** uv (Manager), Ruff (Linter), Pytest (Test).
    *   **Architecture:** Modular Monolith or Microservices.

---

## 4. APEX NAMING CONVENTION (THE "STAR VELOCITY" ENGINE)
A high-performing name must instantly communicate **Product**, **Function**, **Platform** and **Type**.
**Formula:** `<Product-Name>-<Primary-Function>-<Platform>-<Type>`
**Format:** `Title-Case-With-Hyphens` (e.g., `StreamFlow-Picture-in-Picture-Chrome-Extension`)

---

## 5. README REPLICATION PROTOCOL (THE ULTIMATE ARTIFACT)
The README is a self-contained **Project Operating System**.
*   **VISUAL AUTHORITY:** Hero Banner/Logo, Live Badges (Shields.io, `flat-square` style, user `chirag127`), Social Proof.
*   **STRUCTURAL CLARITY:** BLUF, Architecture Diagram, Table of Contents.
*   **DEVELOPMENT STANDARDS:** Setup, Scripts, Principles (SOLID, DRY, YAGNI).

---

## 6. CHAIN OF THOUGHT (CoT) PROTOCOL
Before generating JSON, perform deep analysis in `<thinking>` block:
1.  **Audit:** Analyze repo content and purpose.
2.  **Pivot/Archive Decision:** If the repo is low-value, **pivot** it to an elite standard. Archive using `Archived-` prefix.
3.  **Naming Strategy:** Apply `<Product>-<Function>-<Type>` formula.
4.  **Replication Protocol:** Draft the "AI Agent Directives" block, **CUSTOMIZING** it for the current repo's stack.
5.  **File Generation:** Plan content for all 11 required files.
6.  **Final Polish:** Ensure all badges (chirag127, flat-square) and "Standard 11" are present.
7.  **Strict Adherence:** Ensure `PROPOSED_README.md` strictly follows the `AGENTS.md` directives.

---

## 7. DYNAMIC URL & BADGE PROTOCOL
**Mandate:** All generated files MUST use the correct dynamic URLs based on the **New Repository Name**.
**Rules:**
1.  **Base URL:** `https://github.com/chirag127/<New-Repo-Name>`
2.  **Badge URLs:** All badges (Shields.io) must point to this Base URL or its specific workflows (e.g., `/actions/workflows/ci.yml`).
3.  **Consistency:** Never use the old/original repository name in links. Always use the new "Apex" name.
4.  **AGENTS.md Customization:** The generated `AGENTS.md` **MUST** be customized for the specific repository's technology stack (e.g., if Rust, use Rust tools), while retaining the core Apex principles. Do not just copy the generic template; adapt it.

</details>
