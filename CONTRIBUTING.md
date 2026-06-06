# Contributing

Thanks for helping grow this prompt library!

## Adding a Prompt

1. Copy `templates/prompt-template.yaml` into the right `prompts/<category>/` folder.
2. Rename it to a short kebab-case slug (e.g. `golden-hour-portrait.yaml`).
3. Fill in all frontmatter fields and write your prompt as prose below the `---` block.
4. Open a pull request with a clear title like `Add: golden hour portrait`.

## Prompt Guidelines

- **Original or attributed** — don't copy prompts verbatim from paid prompt packs without permission.
- **Self-contained** — the prompt body alone should be enough to generate a good image.
- **No harmful content** — no prompts designed to generate violence, hate, or non-consensual imagery.
- **No named real people** — use generic descriptions instead of celebrity names.
- **2–5 sentences** — concise but vivid.

## Required Metadata

| Field | Required | Notes |
|-------|----------|-------|
| `title` | Yes | Human-readable name |
| `tags` | Yes | 2–6 lowercase tags |
| `aspect_ratio` | Yes | e.g. `"1:1"`, `"16:9"`, `"9:16"`, `"4:3"`, `"3:4"` |
| `style` | Yes | e.g. photorealistic, illustration, anime, 3d-render |
| `models` | No | Which generators this was tested with |

## File Naming

- Use kebab-case: `neon-city-rain.yaml`
- One prompt per file
- Keep filenames under 50 characters

## Review Checklist

Before submitting, confirm:

- [ ] Prompt follows the YAML frontmatter format
- [ ] Placed in the correct category folder
- [ ] No typos in the prompt body
- [ ] Tags are relevant and lowercase
- [ ] Prompt describes one coherent scene