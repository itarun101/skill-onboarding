# Skill Onboarding

An agent-neutral skill for understanding and adopting skills across AI agents. It reads a skill's instructions and guides, explains what it does, checks compatibility with your chosen agent, and prepares tailored installation, verification, and first-use steps.

## Use

Give your agent a skill folder, repository, archive, or URL and ask it to explain or help install the skill. The onboarding skill can inspect a specific repository and guide you step by step.

## Install in Claude Code

Install with the Skills CLI: `npx skills add itarun101/skill-onboarding`. Choose Claude Code when prompted. The CLI can detect supported agents and install the skill into their configured locations. See the [Skills CLI guide](https://www.skills.sh/docs/cli).

Then ask Claude Code: `Use skill-onboarding to inspect and guide me through installing a skill from <repository URL>.`

## Other agent setup guides

- [OpenAI Codex — Skills](https://developers.openai.com/codex/skills/)
- [Anthropic Claude Code — Skills](https://docs.anthropic.com/en/docs/claude-code/skills)
- [Cursor — Rules for AI](https://docs.cursor.com/context/rules-for-ai)
- [Google Antigravity — Agent skills](https://antigravity.google/docs/skills)
- [GitHub Copilot — Add agent skills](https://docs.github.com/en/copilot/how-tos/copilot-cli/customize-copilot/add-skills)
- [Visual Studio Code — Agent skills](https://code.visualstudio.com/docs/agent-customization/agent-skills)

Installation locations and discovery differ by agent. Check each publisher's current documentation.

## Repository layout

- `skill-onboarding/SKILL.md` — skill instructions
- `skill-onboarding/references/onboarding-output.md` — response format guide

## License

No license is specified yet.
