# Contributing to supaDev

## Branches

- `main` is always in a working state. Don't commit to it directly.
- Create a branch per change: `feature/<short-name>`, `fix/<short-name>` or `docs/<short-name>`.

## Commits

- Write the subject in the imperative mood, under 72 characters: "Add login form", not "Added login form".
- Leave a blank line, then explain *why* in the body if it isn't obvious.
- When you pair with someone, credit them with a trailer at the end of the message:

  ```
  Co-authored-by: Name <ID+username@users.noreply.github.com>
  ```

  The noreply address is under GitHub → Settings → Emails.

## Pull requests

1. Push your branch and open a pull request into `main`.
2. Describe what changed and how you checked it.
3. Merge with a **merge commit** (not squash) so co-author trailers are kept.
4. Delete the branch after merging.
