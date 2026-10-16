# roblox-forge (Claude Code skill)

Own-art pipeline for anime-style Roblox games, learned building Anime Clone Eggs (Oct 2026):
code-drawn flipbook VFX (Conqueror's Haki, Super Saiyan auras), code-built R6 KeyframeSequence
animations, UI art/juice rules, the Studio MCP preview/upload/capture loop, and R6 mesh hair from a
control-point lock blueprint built headless in Blender.

## Install
Unzip `roblox-forge.zip` into `~/.claude/skills/` so you get `~/.claude/skills/roblox-forge/SKILL.md`.

## Contents
- `SKILL.md` - core loop, routing, gotchas, what is and is not proven
- `references/` - vfx, animation, ui, pipeline, characters
- `scripts/` - texture generators, validator, aura modules, keyframe builder, Studio preview, `hair/` pipeline

No Toolbox assets or benchmark geometry are included.

---

# roblox-dev-playbook (Claude Code skill)

The whole-project playbook from the same build: lean multi-agent workflow, Studio MCP habits, VFX,
modeling/characters, animation/cutscenes, UI, map building, audio, economy/launch/LiveOps, testing and
security. `SKILL.md` routes to one reference file per domain so a session loads only what it needs.

## Install
Unzip `roblox-dev-playbook.zip` into `~/.claude/skills/` so you get
`~/.claude/skills/roblox-dev-playbook/SKILL.md`. For auto-loading on every Roblox prompt, register
`hooks/roblox-router.sh` as a UserPromptSubmit hook (steps in the skill's README.md).
