# Compatible Response

A presentation-only skill for Codex. It chooses the clearest format for each response and keeps answers information-dense without removing essential evidence, constraints, or next actions.

## Contents

```text
compatible-response-skill/
├── compatible-response/
│   └── SKILL.md
└── AGENTS.fragment.md
```

## Install for one user

```sh
mkdir -p "$HOME/.agents/skills/compatible-response"
cp compatible-response/SKILL.md "$HOME/.agents/skills/compatible-response/SKILL.md"
```

Append the contents of `AGENTS.fragment.md` to the global Codex `AGENTS.md` used by your environment. This makes the policy load at session start instead of relying only on implicit skill discovery.

Restart Codex if the skill does not appear in a new session.

## Scope

The skill affects presentation only. It does not change task scope, authority, security rules, tool use, code behavior, or explicit output formats.
