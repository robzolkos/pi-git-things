# pi-git-things

A small prompt package for [Pi](https://pi.dev), containing Git workflow helpers used by Rob Zolkos.

It adds prompt templates for common Git actions, focused on turning the current working tree changes into clear, review-ready Git text:

- **Propose a commit** — suggests a concise commit title, and only adds a body when the reason is not obvious from the title.
- **Propose a pull request** — suggests a PR title and description with a short summary that explains the why behind the change.

These prompts do not replace Git. They help prepare the human-facing parts of everyday Git work: commit messages and pull request descriptions.

## Install

```bash
pi install npm:pi-git-things
```

## Included prompts

- `proposed-commit` — draft a commit message for the current changes using Rob's preferred style.
- `proposed-pr` — draft a pull request title and description for the current changes.

## Style

The commit prompt favors Basecamp-style commit messages: imperative, concise, and usually title-only. The PR prompt favors a practical summary that explains what changed and why, without duplicating information Git already knows, such as file lists.
