# Skill Onboarding

An agent-neutral skill for understanding and adopting skills across AI agents. It reads a skill’s instructions and related guides, explains what the skill does, checks fit with the target agent, and prepares clear installation, verification, and first-use steps.

## Use

Provide a skill folder, repository, archive, or URL and ask your agent to explain the skill or guide you through installing it. For tailored steps, include your AI agent and operating system.

## Agent setup guides

These official guides explain how to add skills or configure agent instructions. Each agent has its own format and setup process, so check the guide for your platform.

- [OpenAI Codex — Skills](https://developers.openai.com/codex/skills/)
- [Anthropic Claude Code — Skills](https://docs.anthropic.com/en/docs/claude-code/skills)
- [Cursor — Rules for AI](https://docs.cursor.com/context/rules-for-ai)
- [Google Antigravity — Agent skills](https://antigravity.google/docs/skills)
- [GitHub Copilot — Add agent skills](https://docs.github.com/en/copilot/how-tos/copilot-cli/customize-copilot/add-skills)
- [Visual Studio Code — Agent skills](https://code.visualstudio.com/docs/agent-customization/agent-skills)

For another agent, check its publisher’s documentation for skill support, supported file formats, installation locations, and verification steps.

## Install

Place the `skill-onboarding` directory in a skill location supported by your chosen agent. Paths and discovery behavior vary; use that agent’s current official documentation.

## Contents

- `SKILL.md` — onboarding workflow and safety boundaries
- `references/onboarding-output.md` — suggested response structure

## License

No license is currently specified. Add a license file if you want to grant others explicit reuse rights.
