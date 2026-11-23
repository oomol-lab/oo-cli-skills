# oo-cli-skills

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

Ready-to-use bundled [Agent Skills](https://agentskills.io) from [`oomol-lab/oo-cli`](https://github.com/oomol-lab/oo-cli), pre-rendered in the **universal** agent format.

> [!NOTE]
> The `skills/` directory is automatically synced from [`oomol-lab/oo-cli`](https://github.com/oomol-lab/oo-cli) on every release. Please submit skill template changes to `oomol-lab/oo-cli` instead of editing `skills/` here directly.

## Included Skills

| Skill | Path | Description |
| --- | --- | --- |
| `oo` | [`skills/oo`](./skills/oo) | Core hosted capability router for OOMOL connectors, hosted AI, Open Flow, billing, and team operations via the `oo` CLI. |
| `oo-find-skills` | [`skills/oo-find-skills`](./skills/oo-find-skills) | Discover, compare, install, and troubleshoot published OOMOL / `oo` skills. |
| `oo-create-skill` | [`skills/oo-create-skill`](./skills/oo-create-skill) | Author and structure new Agent Skills, including `oo`-powered and workflow-backed skills. |
| `oo-publish-skill` | [`skills/oo-publish-skill`](./skills/oo-publish-skill) | Validate and publish skills to OOMOL Skills Hub. |

## Usage

Install directly with the Skills CLI:

```bash
npx skills add oomol-lab/oo-cli-skills
```

Or let `oo` manage bundled skills natively for all your local agents:

```bash
oo skills install
```

## License

[MIT](./LICENSE) © OOMOL Lab
