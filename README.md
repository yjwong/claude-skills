# claude-skills

Personal collection of [Claude Code](https://claude.com/claude-code) skills.

## Skills

### `critic`

Delivers a harsh, discerning product critique designed to drive improvements,
in one of two modes:

- **`jobs`** — taste-driven, reductive, reframes the problem.
- **`michelin`** — standards-driven, forensic execution audit.

Triggers on `/critic`, "critique this", "tear this apart", "be brutal about
this", "what would Steve Jobs / a Michelin inspector say about this", or any
request for an unsparing review of a product, feature, design, copy, or UX.

## Installation

Clone this repo somewhere, then symlink the skills you want into your Claude
Code skills directory:

```bash
git clone git@github.com:yjwong/claude-skills.git ~/Documents/claude-skills
ln -s ~/Documents/claude-skills/critic ~/.claude/skills/critic
```

Symlinks are recommended over copies so `git pull` updates flow through with
no re-install.
