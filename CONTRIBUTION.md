# Contribution Guide

This repository is maintained by **Hardik**. Contributions are welcome only when they respect the product direction, code quality bar, and repository rules below.

## Non-Negotiable Rules

1. Do not change project ownership, naming, credits, or branding without explicit approval from Hardik.
2. Do not add, remove, or replace dependencies unless the change is necessary and clearly justified.
3. Do not commit secrets, API keys, local environment files, build artifacts, or personal configuration data.
4. Do not rewrite major architecture, folder structure, shader workflow, or AI flow without prior discussion.
5. Do not submit generated code blindly. You are responsible for understanding every change you propose.
6. Do not mix unrelated fixes in a single contribution.
7. Do not downgrade readability for cleverness, compression, or unnecessary abstraction.
8. Do not change user-facing behavior silently. Any meaningful behavior change must be documented in the pull request.

## Required Before You Contribute

1. Review the current codebase and understand the feature you are touching.
2. Keep your change focused on one clear goal.
3. Update documentation when behavior, setup, or developer workflow changes.
4. Preserve the existing stack unless there is a strong technical reason not to.
5. Respect the existing product identity and maintain a polished end-user experience.

## Code Standards

- Use TypeScript and React patterns already present in the repository.
- Keep code simple, explicit, and maintainable.
- Prefer small, reversible changes over large speculative refactors.
- Reuse existing utilities and state flows before introducing new ones.
- Avoid dead code, placeholder code, and commented-out blocks.
- Name variables and functions clearly.
- Keep UI text professional, consistent, and intentional.

## AI and Shader Changes

- Any AI-related change must preserve safe, understandable user flows.
- Shader-related updates should avoid breaking the live editing workflow.
- If you modify prompts, generation logic, or response parsing, explain why in detail.
- If you alter session formats or uniform behavior, ensure backward compatibility whenever possible.

## Testing Expectations

Before submitting a contribution, at minimum:

1. Run `npm run build`.
2. Check that the app still loads locally.
3. Verify the area you changed manually.
4. Confirm there are no obvious regressions in core flows such as editing, controls, sessions, and rendering.

## Pull Request Rules

Every pull request should:

1. Have a clear title.
2. Explain what changed.
3. Explain why the change is needed.
4. List any risk, limitation, or follow-up work.
5. Stay small enough to review properly.

Pull requests may be closed without merge if they:

- conflict with project direction
- reduce code quality
- change branding or ownership without approval
- introduce unnecessary dependencies
- arrive without testing or explanation

## Final Authority

Hardik has final approval on roadmap, style, branding, architecture, and merge decisions. Opening a pull request does not guarantee acceptance.
