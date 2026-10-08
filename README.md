# Christian Orrala's plugins

A plugin marketplace for coding agents. Each plugin lives in its own
repository; this one lists them so you can install them by name.

| Plugin | What it does | Repository |
|---|---|---|
| `upspec` | Fifteen skills for specification-first development with use cases, for any stack | [ChristianOrrala/upspec](https://github.com/ChristianOrrala/upspec) |
| `a-files` | Five files every coding agent reads first, with the skill that keeps them, their check and a git hook | [ChristianOrrala/a-files](https://github.com/ChristianOrrala/a-files) |

## Install

Add the marketplace once, then install the plugins you want.

Claude Code:

```text
/plugin marketplace add ChristianOrrala/plugins
/plugin install upspec@christian-orrala
/plugin install a-files@christian-orrala
```

Codex:

```text
codex plugin marketplace add ChristianOrrala/plugins
codex plugin add upspec@christian-orrala
codex plugin add a-files@christian-orrala
```

## Using them together

Each plugin works alone. In one project they work together: the A-files
track the work, and each ability in `ABILITIES.md` links to the upspec use
cases that specify it.
Each plugin's README explains how to start.

## License

MIT. Copyright (c) 2026 Christian Orrala.
