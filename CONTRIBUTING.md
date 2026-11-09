# Contributing to NobleFactor

Thank you for your interest. These terms apply to every NobleFactor repository that doesn't carry a `CONTRIBUTING.md`
of its own.

## License and sign-off

A contribution is licensed under the license of the repository it is made to, in that repository's `LICENSE` file,
without additional terms or conditions.

Every pull request carries a [Developer Certificate of Origin](https://developercertificate.org/) sign-off as the last
lines of its description:

```text
Signed-off-by: Your Name <you@example.com>
```

The line certifies that you wrote the contribution or have the right to submit it under the repository's license. A
pull request is squash-merged, and its description becomes the message of the commit that lands, so the sign-off
travels with the change. The commits on your branch need none.

## AI disclosure (required)

Contributions made with AI assistance are welcome, but the assistance must be disclosed. AI is acknowledged, never
credited: no AI tool appears as an author or co-author. A pull request made with AI assistance says so in its
description and ends with a line naming the tool, after the sign-off:

```text
Assisted-by: <tool name>
```

You remain responsible for having the right to submit everything in the pull request, disclosed or not.

**Undisclosed AI use is a bannable offense.** If a contribution is found to contain AI-generated material that was not
disclosed, the contributor is permanently banned from NobleFactor's repositories. Disclosure costs one line;
concealment costs the maintainers the ability to trust every past and future submission from that contributor.

## Workflow

1. Open or find an issue that describes the change, with the issue form that fits it.
2. Branch from the repository's default branch. A branch is named `<type>/<issue>-<name>`, its type one of `chore`,
   `doc`, `feature`, `fix`, `hotfix`, `refactor` and `release`; GitHub refuses any other name.
3. Open a pull request back to the default branch. Its template asks for a summary, the issues it closes, the test
   plan, the AI disclosure and the two lines above.
4. The repository's checks must pass before a pull request merges.

To report a security vulnerability, don't open an issue: see [SECURITY.md](https://github.com/NobleFactor/.github/blob/main/SECURITY.md).
