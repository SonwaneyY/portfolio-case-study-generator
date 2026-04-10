# Claude Skill: Case Study

> A Claude Code skill that helps designers craft portfolio-ready case studies — structured, compelling, and recruiter-friendly.

Turn raw project notes into polished design case studies that tell the story of your process, decisions, and impact. Built as a [Claude Code skill](https://docs.anthropic.com/en/docs/claude-code) you can drop into your `~/.claude/skills/` folder and invoke on demand.

## Why this skill?

Most designers know their work is strong but freeze up when it's time to write about it. Case studies end up either too thin (just screenshots) or too long (every Figma iteration documented). This skill gives Claude the structure, tone, and storytelling conventions that top portfolios use — so you can go from messy project notes to a scannable, hire-worthy case study in one pass.

**Good for:**
- Product designers assembling a portfolio
- UX designers preparing interview case study walkthroughs
- Design leads documenting work for internal showcases
- Freelancers writing client-ready project recaps

## What's inside

| File | Purpose |
|---|---|
| `SKILL.md` | The skill definition Claude loads — structure, writing tips, best practices |
| `PROJECT-TEMPLATE.md` | A fill-in-the-blank template for a single case study |
| `design-portfolio-guide.md` | Broader guidance for assembling a portfolio of case studies |
| `slide-template.md` | Presentation-deck layout for walking through a case study live |
| `tone-guide.md` | Voice and tone conventions — first-person, specific, quantified |
| `references.md` | Reference links and exemplars |

## The case study structure

Every case study produced by this skill follows a six-part arc:

1. **Overview** — role, timeline, hook metric
2. **Challenge** — business context, user pain, constraints
3. **Process** — research, ideation, key decisions, iteration
4. **Solution** — final design walkthrough and rationale
5. **Impact** — quantitative and qualitative results
6. **Reflection** — learnings and what you'd do differently

## Installation

### Option 1: Drop it into your Claude skills folder

```bash
git clone https://github.com/<your-username>/claude-skill-case-study.git ~/.claude/skills/case-study
```

On Windows:

```powershell
git clone https://github.com/<your-username>/claude-skill-case-study.git "$env:USERPROFILE\.claude\skills\case-study"
```

Claude Code will auto-discover the skill on next launch.

### Option 2: Use it as a standalone template

Clone the repo anywhere and copy `PROJECT-TEMPLATE.md` into your portfolio project. Fill it in manually or feed it to any LLM with `SKILL.md` as the system prompt.

## Usage

Once installed as a Claude Code skill, just ask:

```
Use the case-study skill to write a case study for [your project]
```

Or invoke it directly:

```
/case-study
```

Claude will walk you through the six sections, ask targeted questions about your role and impact, and produce a draft you can paste into Notion, Framer, Webflow, or a PDF portfolio.

## Writing principles this skill enforces

- **First person for your contributions** — be specific about your role vs. the team
- **Lead with the most impressive outcome** — the hook wins attention
- **Show process, don't document every step** — highlight insight moments and pivots
- **Quantify impact** wherever possible
- **Edit ruthlessly** — shorter is better

## Contributing

Issues and PRs welcome. If you've shipped a portfolio using this skill and have improvements — tone tweaks, new sections, better templates — open a PR.

## License

MIT

## Related

- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) — the CLI this skill plugs into
- [Anthropic Skills](https://docs.anthropic.com/en/docs/claude-code/skills) — official skill documentation

---

**Keywords:** claude code skill, design case study, portfolio template, ux case study, product design portfolio, design storytelling, case study generator, claude ai skill
