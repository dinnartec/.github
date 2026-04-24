## Summary

<!-- One or two sentences describing what this PR does.
     If there's no linked issue, briefly explain the motivation too. -->

## Linked issues

<!-- Use GitHub's closing keywords so the linked issue auto-closes when
     this PR merges.

     Supported keywords:
       close, closes, closed
       fix, fixes, fixed
       resolve, resolves, resolved

     Examples:
       Closes #42
       Fixes #100, resolves #101
       Closes dinnartec/brickend#5   (cross-repo)
-->

Closes #

## Changes

<!-- Bullet list of notable changes. Be specific — "refactor X to use Y"
     is better than "improved stuff". Skip this section for trivial PRs. -->

-
-

## How to verify

<!-- Steps a reviewer can follow to confirm the change works as described.
     Include edge cases you checked. Delete if the change is purely mechanical. -->

1.
2.

## Screenshots / Recordings

<!-- Required for any UI change. Show mobile + desktop when relevant.
     Use GIFs or short videos for interactions. Delete this whole section
     for non-UI PRs. -->

| Before | After |
|---|---|
|  |  |

## Deployment notes

<!-- Check anything that applies. Skip the section entirely if none apply. -->

- [ ] 🗄️ Database migration included (tested on a fresh local reset)
- [ ] 🔐 New environment variables (added to `.env.example` + deploy targets)
- [ ] 📦 New runtime dependency
- [ ] 🚢 Deploy order matters (explain below)
- [ ] ♻️ Cache or service-worker invalidation required
- [ ] 💥 Breaking change (document migration path below)

<!-- Details for any box above: -->

## Checklist

- [ ] PR title follows Conventional Commits: `type: short description`
- [ ] Branch name follows `type/short-description`
- [ ] Scoped to a single concern (split otherwise)
- [ ] Self-reviewed the diff before requesting review
- [ ] Tests added or updated where relevant
- [ ] Documentation updated if behavior changed
- [ ] No secrets committed (`.env`, keys, tokens)
- [ ] No debug logs or commented-out code left behind
- [ ] Accessibility verified for UI changes (keyboard + screen reader)
