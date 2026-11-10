<!--
SPDX-FileCopyrightText: 2026 Priya Vijai Kalyan <priyavijai.kalyan2007@proton.me>
SPDX-FileCopyrightText: 2026 Outcrop Inc
SPDX-License-Identifier: MIT
File GUID: b9cb9b0a-f2d6-4f51-9512-0afcb0f12233
Created: 2026
-->

<!-- AGENT: Project-owned setup completion checklist. -->

# Project setup checklist

This setup selects instructions and creates placeholders. It does not build or deploy the product.
Complete these items before treating the project as ready.

## Files to complete

- [ ] `PROJECT_PROFILE.md`: Confirm source paths, languages, delivery choices, and tool roles.
- [ ] `PROJECT.md`: Complete business facts, architecture, commands, and environments.
- [ ] `ADDITIONAL.md`: Record local refinements and project-specific exceptions.
- [ ] `README.md`: Write verified prerequisites, installation steps, and first-use instructions.
- [ ] `CONTRIBUTING.md`: Set contribution and validation rules.
- [ ] `CODE_OF_CONDUCT.md`: Set conduct rules and private reporting contacts.
- [ ] `SECURITY.md`: Set private vulnerability contacts and supported-version policy.
- [ ] `LICENSE`: Review the selected terms and copyright ownership.
- [ ] `THIRD_PARTY_NOTICES.md`: Add project dependency notices and verify attribution.
- [ ] `build.sh`: Build selected components and prepare their configured outputs. Replace the TODO with verified commands.
- [ ] `test.sh`: Run configured component and cross-component tests. Replace the TODO with verified commands.
- [ ] `clean.sh`: Remove only verified generated output owned by this project. Replace the TODO with verified commands.
- [ ] `run.sh`: Start selected components for development. Replace the TODO with verified commands.
- [ ] `package.sh`: Package configured components for their delivery channels. Replace the TODO with verified commands.

## Operation scripts

Run ./build.sh --help for usage when build.sh is present.
Unimplemented operations log a TODO and exit with status 2. Help exits with status 0.
Use status 1 for a failed operation. Report success only after actual work completes.
Preserve owner implementations. Route root operations to the selected components.
Add the actual options, prerequisites, credentials source, and output paths before implementation.
