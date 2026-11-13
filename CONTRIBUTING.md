# Contributing to Kola

These rules apply to every kolapp-tech repository unless the repository has its own CONTRIBUTING file.

## Working on a change
- Branch from `main`. Production deploys from `main`, so `main` must always work.
- Open a pull request. Every pull request gets a preview deploy; check it before asking for review.
- Keep pull requests small and say in plain words what changed and how you checked it.
- Merge only when the checks are green.

## Never
- Commit secrets: API keys, tokens, passwords, SIP or payment credentials. They live in Vercel, Render, Modal and
  GitHub secrets, never in code, chat or screenshots. If one leaks, rotate it at once and tell the team.
- Let Kola guess. Order status, delivery times and balances are only ever what staff or the partner's API set.
- Present Kola as built for one payment provider only.

## Writing
- Plain, clear English in code comments, docs and product copy.
- User-facing text in Pidgin, Yoruba, Igbo or Hausa is checked by a native speaker before it ships.
