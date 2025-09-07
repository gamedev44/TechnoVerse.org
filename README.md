# Techno Verse Companion Website

## Welcome, Operator\!

This is the official companion website for the Techno Verse organization, designed to support our activities within Star Citizen and other related ventures. This portal serves as a centralized hub for operations, communications, and system management, providing a unified and immersive experience for all members and affiliated organizations.

Built with a high-tech, futuristic aesthetic, this project is a fully client-side application designed to be lightweight, fast, and easily deployable on static hosting platforms like GitHub Pages.

## Table of Contents

  * [Core Features](https://www.google.com/search?q=%23core-features)
  * [Project Structure](https://www.google.com/search?q=%23project-structure)
  * [Getting Started](https://www.google.com/search?q=%23getting-started)

## Core Features

This website is divided into several key modules, each accessible from the main navigation bar:

  * **🚀 Loading Screen (`index.html`):** An immersive boot-up sequence that sets the tone before loading the main interface.
  * **🏠 Home Dashboard (`home.html`):** The central hub providing quick access to all major sections, along with live widgets for system uptime and message counts.
  * **📡 Ops Center (`pages/ops/`):** Features a dynamic radar system that scans for simulated player and resource signatures, providing a tactical overview.
  * **💬 Comms Network (`pages/comms/`):**
      * **Encrypted Inbox:** A private, secure messaging interface.
      * **Public Channels:** A directory of themed chat servers for various org activities.
      * **Interactive Channels (`#merc-guild`, `#trade-hub`):** Fully interactive chat rooms with simulated AI operators (powered by Gemini in production) who respond to user messages, creating a lively and engaging environment.
  * **⚙️ System Settings (`pages/system/`):**
      * **UI Customization:** A theme selector with multiple color schemes and a "glass mode" toggle for personalized aesthetics.
      * **System Power:** A 3D animated power switch to simulate system shutdown.
  * **💎 Global UI Elements:**
      * **Persistent Themes:** Your chosen theme and glass mode settings are saved locally for a consistent experience on your next visit.
      * **Holographic Modals:** All navigation and settings are presented in stylish, non-intrusive modal windows.

## Project Structure

The website is organized logically to make navigation and future development straightforward:

```
.
├── index.html              # Main loading screen, redirects to home
├── home.html               # The primary dashboard/homepage
├── pages/
│   ├── ops/                # Operations-related pages (radar, etc.)
│   ├── comms/              # Communications pages (inbox, channels)
│   ├── system/             # System settings and configuration
│   └── channels/
│       └── orgs/
│           ├── mercguild/  # Files for the Mercenary's Guild channel
│           └── tradehub/   # Files for the Trade Hub channel
└── README.md               # This file
```

## Getting Started

As this is a fully client-side project with no backend dependencies, running it locally is simple:

1.  Clone or download the repository.
2.  Open the `index.html` file in your preferred web browser.

The site will initialize and automatically redirect you to `home.html` after the boot-up sequence.