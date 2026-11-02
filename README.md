# Skills by Tobias Oberrauch

Reusable agent skills for coding workflows.

## UltraCode for OpenCode

Install the skill:

```bash
npx skills add tobiasoberrauch/skills --skill ultracode -a opencode
```

This installs the UltraCode **skill instructions**. To install the optional OpenCode primary/subagents and slash commands, copy files from `opencode/agents/` and `opencode/commands/` into the matching `.opencode/` project folders (or global `~/.config/opencode/` folders). Review existing files before copying; restart OpenCode afterwards.

Commands: `/ultracode`, `/uc-plan`, `/uc-fix`, `/uc-review`. These require installing the corresponding agent and command files, not just the skill.

UltraCode includes planning, scoped code edits, testing, security and independent review. Agent use is model- and provider-independent. No automatic background execution or test success is implied.
