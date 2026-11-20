<img src="assets/logo.png" width="80" height="80" alt="">

# LinkedIn Skills

Two agent skills for turning a project, draft, or recent conversation into a LinkedIn post and an accompanying visual. Use them together or on their own.

I’ve made LinkedIn carousels about a Japanese reading extension and a watch strap I designed for 3D printing. One got a PS1-style fox. The other got a diagram of a spring bar, because it turns out a tiny metal pin can be the whole point of a slide.

After trying different openings, trimming drafts, and reworking the visuals, I wanted a way to reuse the parts that worked. That’s why I built these two skills. Start with a detail I can back up. Cut any line I’d never say out loud. Give the visual a reason to be there.

| Skill | What it does |
| --- | --- |
| [`linkedin-post`](skills/linkedin-post/SKILL.md) | Finds firsthand stories in the context you share, drafts in your voice, and revises copy while preserving lines you want to keep. |
| [`linkedin-visual`](skills/linkedin-visual/SKILL.md) | Creates or revises a static image, looping GIF, or multipage PDF carousel. It checks the exported file for readability and private details. |

## Install

Clone the repository.

```sh
git clone https://github.com/gonzalocibeira/linkedin-skills.git
cd linkedin-skills
```

For **Codex**, copy both skills into your personal skills directory.

```sh
mkdir -p "$HOME/.agents/skills"
cp -R skills/linkedin-post skills/linkedin-visual "$HOME/.agents/skills/"
```

For **Claude Code**, use its personal skills directory.

```sh
mkdir -p "$HOME/.claude/skills"
cp -R skills/linkedin-post skills/linkedin-visual "$HOME/.claude/skills/"
```

For a single project, use `.agents/skills/` or `.claude/skills/` in that project instead. Start a fresh session after copying the folders. [Codex skill docs](https://learn.chatgpt.com/docs/build-skills) · [Claude Code skill docs](https://code.claude.com/docs/en/skills)

## Try it

In Codex, mention the skill by name.

```text
Use $linkedin-post to find three post ideas from the project notes I shared.

Use $linkedin-post to shorten this draft. Keep the first and last lines exactly as written.

Use $linkedin-visual to turn this post into a five-page PDF carousel. Use the screenshots I attached.
```

In Claude Code, invoke the same skills with `/linkedin-post` or `/linkedin-visual` followed by your request.

For both in one workflow, ask `linkedin-post` to draft from your notes, then give `linkedin-visual` the final copy and any screenshots, brand assets, or format requirements. Publishing to LinkedIn is manual.

The skills contain instructions and optional interface metadata. Post discovery depends on the context your agent can access. Visual exports require an agent with suitable rendering tools and permission to write files.

## Contribute

Issues and pull requests are welcome. For a behavior change, include an example prompt and describe the output you expected. Use fictional or sanitized examples when sharing work context.

## License

Released under the [MIT License](LICENSE). You can use, modify, and redistribute the skills, including commercially, under the license terms.
