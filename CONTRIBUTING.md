# Contribution Guide

Thank you for your interest in contributing to **Shader Pilot**.

This project is an interactive shader-based open world simulation experience maintained by **Hardik**. Contributions are welcome when they help improve the visual world, simulation feel, controls, audio, performance, usability, or stability of the project.

## What You Can Contribute

You are welcome to contribute improvements in areas such as:

- shader quality and world visuals
- camera movement and exploration feel
- ship behavior and simulation tuning
- sound design and reactive audio logic
- performance optimization
- bug fixes
- UI and UX improvements
- developer experience and documentation
- session system improvements

## Before You Start

Before working on a contribution:

1. Read the current codebase and understand the part you want to change.
2. Keep your work focused on one clear improvement.
3. Make sure your idea matches the direction of Shader Pilot as an immersive simulation project.
4. Avoid large rewrites unless they are discussed first.
5. Update docs when your change affects behavior, setup, or workflow.

## Project Rules

These rules are strict and should be respected by every contributor:

1. Do not change ownership, branding, credits, or project identity without approval from Hardik.
2. Do not add unnecessary dependencies.
3. Do not commit secrets, API keys, local environment files, build output, or private data.
4. Do not submit unrelated changes in a single pull request.
5. Do not break existing gameplay, shader workflows, session loading, or core controls.
6. Do not reduce readability for the sake of shortcuts or over-engineering.
7. Do not copy generated code into the project without reviewing and understanding it fully.

## Coding Expectations

- Follow the existing React and TypeScript structure already used in the project.
- Keep code readable, maintainable, and easy to reason about.
- Reuse existing state flows, helpers, and UI patterns where possible.
- Prefer small, testable, reversible changes.
- Remove dead code and avoid placeholder implementations.
- Keep naming clear and consistent.

## Shader and Simulation Contributions

If you are contributing to the shader world or simulation systems:

- Preserve the real-time editing workflow.
- Avoid changes that make the world harder to tune or debug.
- Keep controls meaningful and user-friendly.
- If you change uniforms, slider behavior, session shape, or simulation values, explain it clearly in your pull request.
- If your change affects movement, atmosphere, or interaction feel, describe the expected player experience.

## UI and UX Contributions

If you are improving the interface:

- Keep the UI polished and easy to use.
- Do not clutter the workspace with unnecessary controls.
- Maintain consistency across controls, overlays, and settings panels.
- Make changes that help creators explore, edit, and understand the world faster.

## Testing Checklist

Before opening a pull request, make sure you:

1. Run `npm run build`.
2. Check that the app starts correctly.
3. Test the feature or area you changed.
4. Confirm there are no obvious regressions in rendering, controls, sessions, sound, or interaction.
5. Verify that your contribution does not break the main user experience.

## Pull Request Requirements

Every pull request should include:

1. A clear title.
2. A short explanation of what changed.
3. A short explanation of why it was needed.
4. Any known limitation or follow-up note.
5. Enough detail for review if the change affects shaders, controls, sessions, or simulation behavior.

## Pull Requests May Be Rejected If

- they conflict with the direction of the project
- they reduce code quality
- they introduce unnecessary complexity
- they break the simulation or editing workflow
- they include branding or ownership changes without approval
- they are submitted without testing or explanation

## Final Approval

All contributions are reviewed by **Hardik**, who has final authority over merges, project direction, branding, and architecture.
