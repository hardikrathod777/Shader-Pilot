# Shader Pilot

<p align="center">
  <strong>A polished real-time shader workspace for building, tuning, and exploring interactive visual worlds.</strong>
</p>

<p align="center">
  Designed and maintained by <strong>Hardik</strong>
</p>

---

## Overview

Shader Pilot is a focused creative environment for live GLSL experimentation. It brings together shader editing, real-time rendering, world controls, camera-based exploration, session persistence, and reactive audio design in a single workspace built for iteration.

This project is not positioned as a generic demo. It is structured around a more intentional experience: shape a world, tune it visually, move through it, and preserve the result as a reusable session.

## Key Strengths

- Real-time fragment shader editing with immediate feedback
- Control-driven workflows for tuning visual parameters
- Cinematic navigation through cockpit and chase-style views
- Session save and restore support for repeatable experiments
- Reactive sound behavior linked to movement and world state
- Expandable architecture for panels, overlays, and runtime systems

## Feature Summary

| Area | Purpose |
| --- | --- |
| Live Shader Editing | Edit GLSL fragment code and rerun it instantly |
| World Controls | Tune uniforms, ranges, and effect behavior through the UI |
| Navigation | Explore compatible scenes with movement and camera controls |
| Audio System | Drive ambient, melodic, and rhythmic layers from runtime inputs |
| Session Management | Save and restore complete world configurations as JSON |
| Runtime Panels | Manage shader, sound, ship, and system settings in one place |

## Tech Stack

- React 19
- TypeScript
- Vite
- Tailwind utility styling
- `uuid` for generated identifiers

## Repository Structure

```text
shader-pilot/
|-- components/      # UI panels, overlays, controls, canvas, and display elements
|-- context/         # Shared application context and contracts
|-- hooks/           # Main application state and runtime behavior
|-- services/        # External service and helper integrations
|-- sessions/        # Example saved world sessions
|-- App.tsx          # Root application shell
|-- config.ts        # Product feature flags
|-- metadata.json    # App metadata
`-- vite.config.ts   # Vite configuration
```

## Getting Started

### Install dependencies

```bash
npm install
```

### Configure local environment

Create a `.env.local` file in the project root if you want runtime AI features enabled:

```env
GEMINI_API_KEY=Gemini-api-key-here
```

If these values are left empty, the core visual workspace still runs, but AI-assisted actions remain unavailable until configured.

### Start development

```bash
npm run dev
```

### Create a production build

```bash
npm run build
```

### Preview the production build

```bash
npm run preview
```

## Usage

1. Open the workspace and load the active world.
2. Edit shader code and run it to inspect live changes.
3. Adjust controls to refine the look and behavior.
4. Explore the scene with available movement and camera tools.
5. Save the current state as a session when you want to preserve the result.

## Configuration

Primary runtime flags live in [config.ts](/D:/MCP/shader-pilot/shader-pilot/config.ts).

- `EDITMODE`
- `SHOW_SETTINGS_BUTTON`
- `SHOW_SHARE_BUTTON`
- `SHOW_HUD_BUTTON`
- `SHOW_MUTE_BUTTON`
- `ENABLE_AI_FEATURES`

## Contribution

This repository follows a strict contribution standard. Review [CONTRIBUTION.md](/D:/MCP/shader-pilot/shader-pilot/CONTRIBUTION.md) before proposing structural, behavioral, branding, or dependency changes.

## Maintainer

Shader Pilot is maintained by **Hardik**. Project direction, branding, architecture, and merge approval remain under maintainer control.
