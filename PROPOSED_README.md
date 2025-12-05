# StreamFlow: Seamless Picture-in-Picture Chrome Extension

[![Build Status](https://img.shields.io/github/actions/workflow/user/chirag127/StreamFlow-Picture-in-Picture-Chrome-Extension/ci.yml?style=flat-square&logo=githubactions)](https://github.com/chirag127/StreamFlow-Picture-in-Picture-Chrome-Extension/actions/workflows/ci.yml)
[![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/StreamFlow-Picture-in-Picture-Chrome-Extension?style=flat-square&logo=codecov)](https://codecov.io/github/chirag127/StreamFlow-Picture-in-Picture-Chrome-Extension)
[![Tech Stack](https://img.shields.io/badge/Tech-JavaScript%2C%20WebExtensions%2C%20HTML%2C%20CSS-blue?style=flat-square&logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License](https://img.shields.io/github/license/chirag127/StreamFlow-Picture-in-Picture-Chrome-Extension?style=flat-square&logo=creativecommons)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/chirag127/StreamFlow-Picture-in-Picture-Chrome-Extension.svg?style=flat-square&logo=github)](https://github.com/chirag127/StreamFlow-Picture-in-Picture-Chrome-Extension)


## Elevate your multitasking experience with StreamFlow, the ultimate Chrome Extension for instant Picture-in-Picture video activation.

StreamFlow seamlessly integrates with any webpage featuring video content, allowing you to effortlessly float videos in a customizable Picture-in-Picture window. Enhance your productivity by keeping essential content visible while navigating other tabs or applications. Built for the modern web, StreamFlow respects user privacy and provides a lightweight, efficient solution for enhanced content consumption.


<details>
<summary><strong>🤖 AI AGENT DIRECTIVES</strong></summary>

## SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

### 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable." 
**Context:** Current Date is **December 2025**. You are building for the 2026 standard. 
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes. 
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

---

### 2. INPUT PROCESSING & COGNITION
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

### 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** Detect the project type and apply the corresponding **Apex Toolchain**. This repository, `StreamFlow-Picture-in-Picture-Chrome-Extension`, is a web extension.

*   **PRIMARY SCENARIO: WEB / APP / EXTENSION (TypeScript/JavaScript)** 
    *   **Stack:** This project utilizes **JavaScript (ES2023+)** with robust **WebExtensions API** integration. Development is streamlined with **Vite 7** for build optimizations and **HTML5/CSS3** for the user interface components. The architecture adheres to modern web standards for browser extensions.
    *   **Lint/Format:** **Biome 16.x** is employed for ultra-fast code linting and formatting, ensuring code consistency and quality across the project.
    *   **Testing:** **Vitest 1.x** is used for unit testing of core logic, and **Playwright 1.x** is integrated for end-to-end testing of the extension's behavior within a simulated browser environment.
    *   **Architecture:** Employs a **Feature-Sliced Design (FSD)** approach for maintainability and scalability, with clear separation of concerns between presentation, logic, and data layers. Background scripts, content scripts, and popup UI are distinct modules.

*   **SECONDARY SCENARIO B: SYSTEMS / PERFORMANCE (Rust/Go) - *Not applicable for this project.***
*   **SECONDARY SCENARIO C: DATA / AI / SCRIPTS (Python) - *Not applicable for this project.***

---

### 4. CODE INTEGRITY & SECURITY
*   **LINTOPIA PROTOCOL:** All code must pass Biome checks with zero errors or warnings.
*   **SECURITY FIRST MANDATE:** 
    *   **Vulnerability Audits:** Regularly scan dependencies for known vulnerabilities using `npm audit` or equivalent tools within the CI pipeline. 
    *   **Least Privilege Principle:** Content scripts and background scripts should operate with the minimum necessary permissions.
    *   **WebExtensions API Sanitization:** All interactions with the WebExtensions API must be carefully validated to prevent injection attacks or unauthorized data access.
    *   **Cross-Site Scripting (XSS) Prevention:** Sanitize all user-generated content and data fetched from external sources before rendering.
*   **TESTING PYRAMID ADHERENCE:** 
    *   **Unit Tests:** Comprehensive unit tests for all core utility functions and business logic.
    *   **Integration Tests:** Tests that verify interactions between different components (e.g., content script and background script communication).
    *   **End-to-End (E2E) Tests:** Simulate user interaction scenarios using Playwright to validate the extension's functionality across various web pages.

---

### 5. DOCUMENTATION & KNOWLEDGE MANAGEMENT
*   **README REPLICATION PROTOCOL:** The `README.md` serves as the **Project Operating System**. It must be comprehensive, up-to-date, and self-explanatory, containing at least:
    *   **VISUAL AUTHORITY:** Hero Banner/Logo, Live Badges (Shields.io: `flat-square` style, `chirag127` user, Build Status, Coverage, Tech Stack, License, Stars).
    *   **STRUCTURAL CLARITY:** BLUF (2-sentence value proposition), Architecture Diagram (ASCII `tree` or Mermaid), Table of Contents.
    *   **DEVELOPMENT STANDARDS:** Setup commands (`git clone` -> build/install), Scripts table, Principles (SOLID, DRY, YAGNI).
*   **AGENTS.md:** This document is the **Agent Directive**. It must be kept current and specific to the project's stack and architecture.
*   **CONTRIBUTING.md:** Clear guidelines for external contributors.
*   **ISSUE TEMPLATES:** Standardized templates for Bug Reports and Feature Requests.
*   **PULL REQUEST TEMPLATES:** Pre-defined structure for pull request submissions.
*   **LICENSE:** Standardized open-source license (e.g., CC BY-NC 4.0).

---

### 6. OPERATIONAL EXCELLENCE (CI/CD & DEVOPS)
*   **CI/CD PIPELINE:** A robust GitHub Actions workflow (`.github/workflows/ci.yml`) must be in place, automating:
    1.  **Checkout Code:** Securely fetch repository code.
    2.  **Setup Environment:** Install Node.js and project dependencies using `npm ci`.
    3.  **Lint & Format:** Run Biome (`biome check --apply`).
    4.  **Unit Tests:** Execute Vitest (`vitest run`).
    5.  **E2E Tests:** Run Playwright tests (`npx playwright test`).
    6.  **Build Extension:** Compile the extension for distribution (`vite build`).
    7.  **Code Coverage Upload:** Push coverage reports to Codecov.
*   **DEPENDENCY MANAGEMENT:** Utilize `npm` with `package-lock.json` for deterministic builds. Regularly audit dependencies.
*   **ERROR REPORTING:** Implement mechanisms for capturing and reporting runtime errors gracefully, especially for background and content scripts.

---

### 7. ARCHIVAL PROTOCOL
**Directive:** Even retired repositories must maintain professional integrity. The `README.md`, `AGENTS.md`, and overall metadata (name, description, topics) must be updated to reflect their final, professional state before archival. Treat "retired products" with the same respect as active ones.

</details>

## 🚀 Features

*   **Instant PiP Activation:** Activate Picture-in-Picture mode for any video with a single click.
*   **Seamless Web Integration:** Works automatically on most video-playing websites.
*   **Productivity Boost:** Keep important videos visible while working on other tasks.
*   **Lightweight & Efficient:** Minimal performance impact on your browser.
*   **Customizable Window:** (Future Feature/Optional) Ability to resize or reposition the PiP window.


## 🌳 Architecture

ascii
. StreamFlow-Picture-in-Picture-Chrome-Extension
├── public/
│   ├── icons/
│   │   ├── icon16.png
│   │   ├── icon48.png
│   │   └── icon128.png
│   └── manifest.json
├── src/
│   ├── background/
│   │   └── index.js        # Handles background tasks, message passing, WebExtension APIs
│   ├── content/
│   │   ├── index.js        # Injects script into web pages, detects video elements
│   │   └── styles.css      # Optional: Styles for content script interactions
│   ├── popup/
│   │   ├── index.html      # UI for the extension popup
│   │   ├── main.js         # Logic for the popup UI
│   │   └── style.css       # Styles for the popup UI
│   └── utils/
│       └── videoUtils.js # Utility functions for video manipulation
├── tests/
│   ├── unit/
│   │   └── videoUtils.test.js
│   └── e2e/
│       └── popup.spec.ts
├── .gitignore
├── biome.json
├── index.html              # Entry point for development server (if applicable)
├── LICENSE
├── package.json
├── tsconfig.json           # Or jsconfig.json if not using TypeScript
├── vite.config.js          # Vite build configuration
└── README.md


## 🛠️ Tech Stack

*   **Language:** JavaScript (ES2023+)
*   **Build Tool:** Vite 7
*   **Browser API:** WebExtensions API
*   **Linting/Formatting:** Biome 16.x
*   **Unit Testing:** Vitest 1.x
*   **E2E Testing:** Playwright 1.x
*   **UI:** HTML5, CSS3


## 📜 License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0). See the [LICENSE](LICENSE) file for more details.

## 🌟 Contributing

Contributions are welcome! Please read our [CONTRIBUTING.md](.github/CONTRIBUTING.md) guide for details on how to submit issues, feature requests, and pull requests.

## 📋 Development Setup

Follow these steps to set up the development environment:

1.  **Clone the repository:**
    bash
    git clone https://github.com/chirag127/StreamFlow-Picture-in-Picture-Chrome-Extension.git
    cd StreamFlow-Picture-in-Picture-Chrome-Extension
    

2.  **Install dependencies:**
    bash
    npm install
    

3.  **Run linters and formatters:**
    bash
    npm run lint
    npm run format
    

4.  **Run tests:**
    bash
    npm run test:unit  # Run unit tests
    npm run test:e2e   # Run end-to-end tests
    

5.  **Build the extension:**
    bash
    npm run build
    

6.  **Load the extension in Chrome:**
    *   Open Chrome and navigate to `chrome://extensions/`.
    *   Enable "Developer mode" using the toggle switch.
    *   Click "Load unpacked" and select the `dist` (or the output directory specified in `vite.config.js`) folder from your project.

## 📜 Scripts

| Script        | Description                                      |
|---------------|--------------------------------------------------|
| `npm run lint`| Check code style and potential errors using Biome. |
| `npm run format`| Automatically format code using Biome.           |
| `npm run test:unit`| Run unit tests with Vitest.                    |
| `npm run test:e2e`| Run end-to-end tests with Playwright.          |
| `npm run build` | Build the extension for production.              |


## Principles

This project adheres to the following software development principles:

*   **SOLID:** Ensuring maintainable and scalable object-oriented design.
*   **DRY (Don't Repeat Yourself):** Minimizing redundancy in code.
*   **YAGNI (You Ain't Gonna Need It):** Focusing on implementing only necessary features.
