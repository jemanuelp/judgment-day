# Judgment Day Skills

Portable OpenCode skills repository for the Judgment Day workflow.

## Use Locally

From this project, OpenCode loads skills through `opencode.json`:

```json
{
  "skills": {
    "paths": ["./skills"]
  }
}
```

Restart OpenCode after changing skills or config.

## Install On Another Device

Clone this project and either run OpenCode from the project directory, or add the cloned `skills` directory to your global OpenCode config:

```json
{
  "skills": {
    "paths": ["/absolute/path/to/judgment-day/skills"]
  }
}
```

The skill entrypoint is `skills/judgment-day/SKILL.md`.
