# goals

A useful goal connects a broad objective to a measurable result, an accountable owner, and a review date. This skill rewrites one intention, designs a short goal set, or audits existing goals without inventing the numbers that make them testable.

It produces:

- **Goal Rewrite** (A. Rewrite): built from one intention, objective, and any supplied measure fields.
- **Goal Set** (B. Goal set): built from several intentions, a common objective, horizon, and constraints.
- **Goal Audit** (C. Audit): built from existing goals and any supplied objective or review process.

It executes the [Goals playbook](https://www.andrewluxem.com/playbooks/goals). The playbook teaches the framework. This skill runs it and returns a working artifact.

**Static by construction: no dependencies, executable code, telemetry, network calls, remote instructions, auto-update, scheduled work, or background behavior.** It reads only the files in its own skill folder. Nothing happens until a user or agent invokes it.

## Install

Clone and copy the skill into Claude Code:

```bash
git clone https://github.com/andrewluxem/goals.git
cp -r goals/skills/goals ~/.claude/skills/
```

Or install it as a Claude Code plugin:

```text
/plugin marketplace add andrewluxem/goals
/plugin install goals@goals
```

For clients that install from an archive, keep using the versioned [goals v1.0.0 ZIP](https://www.andrewluxem.com/downloads/goals-v1.0.0.zip).

## Invoke it

```text
Rewrite these goals so they are measurable
Rewrite improve onboarding as a measurable goal. The objective is to help new
Make these goals better: improve communication, grow engagement, ship faster,
```

Naming the skill is always valid: `use the goals skill`.

## Files

```text
.claude-plugin/
  plugin.json
  marketplace.json
skills/goals/
  SKILL.md
  meta.yaml
  LICENSE.md
  assets/
  references/
README.md
LICENSE
```

The complete canonical package is copied under `skills/goals/`, including every asset, reference, example, and license file present in the source.

## Versioning

Plugin installation is version-pinned. When behavior changes, update the version consistently in `SKILL.md`, `meta.yaml`, and `.claude-plugin/plugin.json`, then add a changelog entry. Reinstalling is an explicit update; this repository never auto-updates itself.

## License

MIT. See [LICENSE](LICENSE). The canonical skill folder carries the same authorization in [skills/goals/LICENSE.md](skills/goals/LICENSE.md).

---

## More playbooks

This skill packages one playbook from the free library at [github.com/andrewluxem/playbooks](https://github.com/andrewluxem/playbooks). Every playbook is free to read, with no email required.
