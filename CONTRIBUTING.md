# Contributing

Thanks for looking. This account is maintained by one person, so the fastest way to get a change accepted is to make it easy to verify.

## Before opening a pull request

- **Open an issue first** for anything larger than a typo, a broken link, or a one-line fix. It avoids building something that does not fit.
- **One logical change per PR.** Mixed refactor + feature + formatting PRs are hard to review and usually get asked to split.
- **Say what you ran.** "Tests pass" is not enough — paste the command and the result. If you could not run something, say that too.

## What I look for

- A reproduction, not just a description. For a bug fix: the failing command before, and the passing command after.
- A test where one is possible. If a test is genuinely impractical, explain why.
- Honest scope. If a fix works on one platform but is untested on another, the PR description should say so.

## What gets closed quickly

- Changes that reformat unrelated code.
- Dependencies added for something the standard library already does.
- "Fixes" that suppress an error instead of addressing it.
- Claims in the description that the diff does not support.

## Review times

Expect a few days. If a PR goes quiet for more than two weeks, comment on it — that is a prompt, not a nuisance.

## Security

Do not open a public issue for a vulnerability. See [SECURITY.md](SECURITY.md).

## Licence

By contributing you agree that your contribution is licensed under the licence of the repository you are contributing to (MIT or Apache-2.0).
