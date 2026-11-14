# Contributing to Porthole

Thanks for taking the time to contribute! 🎉

## Ways to help

- 🐛 **Report a bug** — open an issue using the *Bug report* template.
- 💡 **Suggest a feature** — open an issue using the *Feature request* template.
- 🔧 **Send a pull request** — fixes, new routes, new views, accessibility improvements.

## Development setup

Porthole is a single, dependency-free HTML file — there is no build step.

```bash
git clone https://github.com/TheAlta/Porthole.git
cd Porthole
# open directly…
start porthole-seat-view.html        # Windows
open porthole-seat-view.html         # macOS
xdg-open porthole-seat-view.html     # Linux
# …or serve it locally
npx serve .
```

## Pull request workflow

1. Fork the repo and create a branch from `main`:
   `git checkout -b feat/short-description`
2. Make your change and test it in at least one Chromium browser and Firefox or Safari,
   at both desktop and phone widths, in light and dark mode.
3. Use [Conventional Commits](https://www.conventionalcommits.org/) for messages,
   e.g. `feat: add Tehran → Kish route`, `fix: shade slider keyboard focus`.
4. Update `CHANGELOG.md` under **Unreleased**.
5. Open a PR and fill in the template.

## Style

- Keep the project a single self-contained HTML file.
- Use the existing CSS custom properties (`--bg`, `--ink`, `--accent`, …) instead of hard-coded colors.
- Keep interactive controls keyboard-reachable and labelled.

By participating you agree to follow the [Code of Conduct](CODE_OF_CONDUCT.md).
