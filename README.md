# Skill Onboarding

An agent-neutral skill for understanding and adopting skills across AI agents. It reads a skill's instructions and related guides, explains what the skill does, checks fit with the target agent, and prepares clear installation, verification, and first-use steps.

## Supported agent coverage

The skill can prepare agent-specific guidance for Codex, Claude Code, Cursor, Google Antigravity, and other agents when their current documentation confirms support. A shared `SKILL.md` format does not guarantee identical discovery rules or installation paths, so the workflow checks the target agent's official documentation and marks unverified paths clearly.

## Use

Provide a skill folder, repository, archive, or URL and ask the agent to explain, compare installation options, or guide you through adoption. Specify your target agent and operating system when you want exact steps.

## Install

Place the `skill-onboarding` directory in a skill location supported by your chosen agent. Installation paths and discovery behavior vary; consult that agent's current official documentation. The skill can help determine the correct location and verification step.

## Contents

- `SKILL.md` — onboarding workflow and safety boundaries
- `references/onboarding-output.md` — suggested response structure

## License

No license is currently specified. Add a license file if you want to grant others explicit reuse rights.
