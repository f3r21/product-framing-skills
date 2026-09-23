# product-framing-skills

Three Claude Code skills for framing a product problem before anyone designs a solution.

| Skill | What it does | Sources |
|---|---|---|
| `reviewing-problem-statements` | Reviews a problem statement criterion by criterion, flags a solution in disguise, and rewrites one on request. | ProductPlan, ProdPad |
| `building-personas` | Builds a persona from a problem statement, keeping what is known apart from what is assumed, or reviews one you bring. | Product School, Mind the Product |
| `scoping-an-mvp` | Scopes an MVP hypothesis from a candidate feature list, with what is out and why, and a Now / Next / Later roadmap, or reviews one you bring. | Atlassian, ProdPad |

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

Then paste a problem statement and ask for a review or a persona, or paste a candidate feature
list and ask which to build first; or type `/reviewing-problem-statements`,
`/building-personas` or `/scoping-an-mvp`.

## License

[MIT](LICENSE)
