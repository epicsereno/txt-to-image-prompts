# txt-to-image-prompts

A curated collection of text-to-image prompts for AI image generators.

## Structure

- `prompts/` — prompts by category (portraits, landscapes, fantasy, etc.)
- `templates/` — blank template for new prompts
- `schema/` — JSON schema for prompt metadata

## Format

Each prompt is a YAML file with frontmatter + prose body:

```yaml
---
title: My Prompt
tags: [tag1, tag2]
aspect_ratio: "16:9"
style: photorealistic
---

Your prompt as natural prose here.
```

## Contributing

Copy `templates/prompt-template.yaml`, fill it in, drop it in the right category folder, and open a PR.