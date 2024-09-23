*Detailed instructions on how to contribute to the project, if applicable. Must include section about Oracle Contributor Agreement with link and instructions*

# Contributing to this repository

We welcome your contributions! There are multiple ways to contribute.

## Opening issues

For bugs or enhancement requests, please file a GitHub issue unless it's
security related. When filing a bug remember that the better written the bug is,
the more likely it is to be fixed. If you think you've found a security
vulnerability, do not raise a GitHub issue and follow the instructions in our
[security policy](./SECURITY.md).

## Contributing code

We welcome your code contributions. For this project you must request **authorization** through a GitHub Discussion.

Before submitting code via a pull request, you will need to have signed the [Oracle Contributor Agreement][OCA] (OCA) and your commits need to include the following line using the name and e-mail address you used to sign the OCA:

```text
Signed-off-by: Your Name <you@example.org>
```

This can be automatically added to pull requests by committing with `--sign-off`
or `-s`, e.g.

```text
git commit --signoff
```

Only pull requests from committers that can be verified as having signed the OCA
can be accepted.

## Semantic Commit Messages

See how a minor change to your commit message style can make you a better programmer.

Format: `<type>(<scope>): <subject>`

`<scope>` is optional

### Example

```
feat: add hat wobble
^--^  ^------------^
|     |
|     +-> Summary in present tense.
|
+-------> Type: chore, docs, feat, fix, refactor, style, or test.
```

More Examples:

- `feat`: (new feature for the user, not a new feature for build script)
- `fix`: (bug fix for the user, not a fix to a build script)
- `docs`: (changes to the documentation)
- `style`: (formatting, missing semi colons, etc; no production code change)
- `refactor`: (refactoring production code, eg. renaming a variable)
- `test`: (adding missing tests, refactoring tests; no production code change)
- `chore`: (updating grunt tasks etc; no production code change)
- `merge`: (merging branch tasks)

References:

- [Github \[joshbuchea\] - Semantic Commit Messages](https://gist.githubusercontent.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716/raw/e75b1b9536ee5ee82e2ec0ba8948d8f8238488c3/semantic-commit-messages.md)

----

## Pull request process

1. Ensure there is an issue created to track and discuss the fix or enhancement
   you intend to submit.
2. Fork this repository.
3. Create a branch in your fork to implement the changes. We recommend using
   the issue number as part of your branch name, e.g. `1234-fixes`.
4. Ensure that any documentation is updated with the changes that are required
   by your change.
5. Ensure that any samples are updated if the base image has been changed.
6. Submit the pull request. *Do not leave the pull request blank*. Explain exactly
   what your changes are meant to do and provide simple steps on how to validate.
   your changes. Ensure that you reference the issue you created as well.
7. We will assign the pull request to 2-3 people for review before it is merged.

## Code of conduct

Follow the [Golden Rule](https://en.wikipedia.org/wiki/Golden_Rule). If you'd
like more specific guidelines, see the [Contributor Covenant Code of Conduct][COC].

[OCA]: https://oca.opensource.oracle.com
[COC]: https://www.contributor-covenant.org/version/1/4/code-of-conduct/
