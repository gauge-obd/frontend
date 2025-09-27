<img src="https://github.com/gauge-obd/gauge-graphics/blob/main/logo_assets/black_white.png" alt="Gauge Logo" width="204"/>

# frontend
> React.js automotive diagnostics dashboard for OBD-II streams. Delivers real-time telemetry with AI-driven fault code interpretation, transforming raw parameter IDs into clear, human-readable insights. The frontend emphasizes clarity and interpretability through a minimalist, high-contrast design optimized for accessibility and rapid comprehension.

[**Read the introductory ▸**](https://medium.com/@gaugeobd/introducing-gauge-ai-powered-automotive-diagnostics-made-simple-6257b7bca05f)

[**View the full documentation ▸**](https://github.com/gauge-obd-docs)

[**Try it out on CodeSandbox ▸**](https://codesandbox.io/p/sandbox/BLANK)

[**Read frequently asked questions (FAQ) on the wiki ▸**](https://github.com/gauge-obd/frontend/wiki/Frequently%E2%80%90Asked%E2%80%90Questions)


## Changelog

Gaugeobd's change log and migration guides for major versions live on the repo's
[Github wiki](https://github.com/gauge-obd/frontend/wiki/BLANK).

## Packages

This repository contains multiple projects in the `packages/` directory.

### Libraries

`ui-core` - Foundational React components and styles that provide the base layout, controls, and visual language.

`telemetry-viewer` - Real-time visualization components for rendering OBD-II data streams as gauges, graphs, and status indicators.

## Development

### Prerequisites

- **Node.js v20+** – core runtime for React and tooling  
- **npm v10+** – package manager for dependencies and scripts  
- **Git** – to clone and manage the repository  
- **Modern browser** (Chrome, Firefox, Edge) – required for running the dashboard locally  
- **OBD-II data source** – either:  
  - A physical OBD-II adapter + backend relay server

## Contributing

Looking for places to contribute to the codebase?
First read the [contribution guidelines](https://github.com/gauge-obd/frontend/blob/main/CONTRIBUTING.md)

  - A simulated/mock OBD-II data service for development  

