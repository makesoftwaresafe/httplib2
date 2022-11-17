# Welcome

You have come to the right place if you want to support httplib2 by doing. Thank you!

- [Reporting security / sensitive issues](SECURITY.md)
- [Regular issues](https://github.com/httplib2/httplib2/issues?q=) please try to find existing solution first, search without issue/open filters.
- If you intend to propose code change, there is no need to open an issue first. Pull request is more than enough. `git diff` in message is fine too.
- Tests use TLS certificates/keys generated by `script/generate-tls`


## Submitting changes (pull request policy)

- Run `pre-commit install` once to setup hooks that detect/fix common style issues and run unit tests. [pre-commit website](https://pre-commit.com/)
- If you don't want pre-commit hooks, please run `script/test` before commit
- Test is required, or at least coverage must not decrease
- One commit is strongly preferred, except for very big changes
- Feel free to append yourself into __contributors__
- Commit message should follow the following formula:

>subsystem: description of why the change is useful
>
>optional details
>
>links to related issues or websites

The why part is very important. Diff already says what is changed. Explain why.