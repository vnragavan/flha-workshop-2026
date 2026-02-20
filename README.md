# FLHA Workshop 2026

If you use Cursor and want to avoid `Co-authored-by: Cursor` in commits:

- **In Cursor:** Open **Cursor Settings → Agents → Attribution** and turn it off.
- This repo also has a Git `prepare-commit-msg` hook that strips any `Co-authored-by` line from commit messages, so even if Cursor adds it, the hook removes it before the commit is created.
