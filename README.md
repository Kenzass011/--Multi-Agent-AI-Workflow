# Multi-Agent AI Workflow for iOS

An advanced, production-ready automation hub designed for iOS that acts as a centralized command center for multiple Large Language Models (LLMs) and multi-channel communication. 

This project solves the critical issue of background session expiration in native mobile AI applications by implementing a proprietary, high-performance background session-keeping architecture combined with custom security digital watermarking—all compiled into a single, self-contained shortcut.

## ⚠️ Prerequisites & Official Apps (Wymagania i Aplikacje)

To fully utilize this workflow and all its specialized agents, you **must have the following official apps installed** on your iOS device (links provided below):
* 🧠 **ChatGPT** (OpenAI) — [App Store / Download Link](https://apps.apple.com/pl/app/chatgpt/id6448311069?l=pl)
* 🍊 **Claude** (Anthropic) — [App Store / Download Link](https://apps.apple.com/pl/app/claude-by-anthropic/id6473753684?l=pl)
* 🌐 **Gemini** (Google) — [App Store / Download Link](https://apps.apple.com/pl/app/google-gemini/id6477489729?l=pl)
* 🚀 **Grok** (xAI) — [App Store / Download Link](https://apps.apple.com/pl/app/grok-asystent-ai/id6670324846?l=pl)

## 📥 Download Shortcut (Pobierz skrót)

> [!TIP]
> **[Click here to install Multi-Agent AI Workflow (All-in-One Version)](https://www.icloud.com/shortcuts/5cc1ef85a6994153bc21b2df519ab5e3)**
> 
> *This is the unified version. No additional dependency shortcuts are required.*

## 🚀 Key Features & Architecture

The system is engineered using a modular approach, splitting execution into discrete layers for maximum efficiency:

### 1. Dual-Stage Routing & Security Gateway
Instead of basic shortcut menus, this system uses a premium nested structure protected by ownership verification:
* **Stage 1 (Launch Gate):** A dedicated launch trigger (`Multi-Agent AI Workflow`) that initializes the system.
* **Security & Watermarking Layer:** Implements a native system notification layer (`by 😝𝕶𝖊𝖓𝖟𝖆𝖘𝖘`) serving as an immutable cryptographic-like digital watermark to prevent unauthorized code redistribution.
* **Stage 2 (Operational Dashboard):** An elegant, minimalist UI that dynamically routes user intent to specialized modules.

### 2. High-Performance Session Keeper (The "Ping" Mechanism)
* **The Problem:** Mobile AI client applications frequently terminate active sessions or clear caches when operating in the background, breaking long-running automation tasks.
* **Performance Tweaking:** A custom background task asynchronously pings the core application (e.g., Claude) to force the iOS lifecycle manager to refresh the application state, utilizing optimized IPC transitions to return control instantly without interface rendering lag.

### 3. Multi-Agent AI Sub-Systems
Once an option is selected, the workflow seamlessly bridges your prompt over to the dedicated AI engines based on your needs:
* **Information Retrieval Unit (QA):** Analytical processing across 3 distinct knowledge bases.
* **Conversational Unit:** Continuous dialogue and brainstorming across 3 alternate conversational models.
* **Generative Image Engine:** Text-to-image prompt engineering across 2 separate generation engines.

### 4. Omnichannel Communication Gateway
A custom output routing engine that allows you to instantly push your data or AI-generated content across multiple notification channels:
* Native Cellular Routing (**SMS**)
* Over-The-Top Messaging (**WhatsApp**)
* Professional Reporting (**E-mail**)

## 🛠️ Tech Stack & Concepts

* **Platform:** iOS Shortcuts Environment (Low-Code / Visual Programming)
* **Architecture:** Monolithic All-in-One workflow (Self-contained logic)
* **Security:** Integrated UI/UX Digital Watermarking
* **UX/UI Design:** Modular nested menus with high-contrast system typography
* **Inter-Process Communication:** Deep-linking and system clipboard mapping
