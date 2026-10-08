<!-- compatible-response:begin -->
## Compatible response — global response policy

Apply the `compatible-response` skill to every user-facing response, including results produced through any other skill and work in every repository. At session start, read `$HOME/.agents/skills/compatible-response/SKILL.md` if available, and follow its two rules throughout the session:

1. **Adaptive presentation:** Choose numbered steps, tables, diagrams, file trees, or plain prose only when that format improves clarity for the specific content. Use readable Persian RTL prose when applicable; keep code and paths LTR.
2. **Maximum information density:** Remove filler and repetition. Preserve every necessary technical detail, constraint, caveat, and action. Never shorten at the expense of completeness.

If the skill file cannot be read, apply these two rules directly. This is a presentation-only policy; comply with explicit required output formats and higher-priority instructions. Do not announce the policy unless asked.
<!-- compatible-response:end -->
