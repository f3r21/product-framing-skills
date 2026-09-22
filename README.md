# product-framing-skills

Two Claude Code skills for framing a product problem before anyone designs a solution.

| Skill | What it does | Sources |
|---|---|---|
| `reviewing-problem-statements` | Reviews a problem statement criterion by criterion, flags a solution in disguise, and rewrites one on request. | ProductPlan, ProdPad |
| `building-personas` | Builds a persona from a problem statement, keeping what is known apart from what is assumed, or reviews one you bring. | Product School, Mind the Product |

Each skill cites only its sources, listed with links at the end of its `SKILL.md`, and says
"not covered" where they are silent.

## Install

Copy a skill's folder into `.claude/skills/` in your project, or into `~/.claude/skills/` to use
it in every project:

```sh
git clone https://github.com/f3r21/product-framing-skills.git
mkdir -p ~/.claude/skills
cp -R product-framing-skills/skills/* ~/.claude/skills/
```

Then paste a problem statement and ask for a review or a persona, or type
`/reviewing-problem-statements` or `/building-personas`.

## License

[MIT](LICENSE)
