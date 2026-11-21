# Carousel Playbook Kit

A skills plugin for Claude Code and Codex. Plan Instagram and LinkedIn carousels, write educational posts that lead into an offer, and turn finished copy into consistent slide prompts.

| Skill | When to use it |
| --- | --- |
| `carousel-copy` | Plan a carousel slide by slide, or audit a draft for its hook, word count, visual direction, and call to action. |
| `carousel-copywriter` | Write an educational Instagram carousel with a narrative that connects each slide and leads naturally into an offer. |
| `design-taste` | Turn approved copy into image prompts, explore three hook and CTA designs, and carry the chosen layout across the value slides. |

## Install in Claude Code

Run these commands in Claude Code, one at a time.

```text
/plugin marketplace add rusticmarketer/carousel-design-playbook
/plugin install carousel-playbook-kit@carousel-design-playbook
/reload-plugins
```

Try `/carousel-playbook-kit:carousel-copy Plan a seven-slide Instagram carousel about following up with a new lead.` Use `/carousel-playbook-kit:carousel-copywriter` for narrative copy or `/carousel-playbook-kit:design-taste` for visual prompts.

## Install in Codex

Run these commands in a terminal.

```sh
codex plugin marketplace add rusticmarketer/carousel-design-playbook
codex plugin add carousel-playbook-kit@carousel-design-playbook
```

Start a new Codex session and ask, “Use Carousel Playbook Kit to plan a seven-slide carousel about what happens in the first five minutes after a lead fills out a form.”

## Playbook and source

Both marketplaces load the same [plugin directory](./plugins/carousel-playbook-kit). The original kit includes a walkthrough of the copy, hook, anchor-slide, and CTA workflow. Read the [system guide](./plugins/carousel-playbook-kit/skills/carousel-copy/references/carousel-system-guide.md) and the [original kit notes and credits](./plugins/carousel-playbook-kit/README.txt).
