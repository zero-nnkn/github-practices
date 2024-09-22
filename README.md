## Commit messages Emoji
An combination of [Gitm😂ji](https://gitmoji.dev/) and [Angular convention](https://github.com/angular/angular/blob/22b96b9/CONTRIBUTING.md?fbclid=IwZXh0bgNhZW0CMTAAAR2LQVjo1dQwMh9G3W8yRjOn_TwKJvYQXKXgJ5JukKESElZ3cgyvda1TPn4_aem_AYayFnZXHwUm6ikGpkabBduLzKvmpgRVffJKt88fkheQPDJXHSY76RbHGa1fzhHIwzAmNn8uLg6Lilh43pB8-4CZ#-commit-message-guidelines) with some tweaks on my part.

## Commit messages format
We use angular's commit messages format and with gitmoji added at the beginning.
```
<gitmoji> <type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

Examples:
```
📝 docs(api): update api doc
```

## Gitmoji for commit types
Add `chore` and `wip` to basic angular commit types.

| Types      | Gitmoji | Description                                               |
|:-----------|:------- |:----------------------------------------------------------|
| `feat`     | ✨ (normal) vs. 💥 (breaking change) | New features                |
| `fix`      | 🐛 (normal) vs 🚑️ (hotfix)           | Bug fix                     |
| `build`    | 👷 | Changes that affect the build system or external dependencies |
| `ci`       | 💚 | Changes to our CI configuration files and scripts             |
| `docs`     | 📝 | Documentation only changes                                    |
| `perf`     | ⚡️ | Improve performance                                           |
| `refactor` | ♻️ | Refactor code                                                 |
| `style`    | 🎨 | Improve structure/format of the code                          |
| `test`     | ✅ | Add, update or pass tests                                     |
| `chore`    | 🔵 | Something that doesn’t fit the other types                    |
| `wip`      | 🚧 | Working in progress                                           |

## Pre-commit
### Hooks
#### Basic hooks
- [pre-commit-hooks](https://github.com/pre-commit/pre-commit-hooks): Some out-of-the-box hooks for pre-commit.

#### Python code linter and formatter
> We are using ruff in this repo because it can be used to replace most of the other tools.

- [ruff](https://github.com/astral-sh/ruff): Extremely fast Python linter and code formatter that support lint rules from many popular tools like Flake8, isort, etc.
- [mypy](https://github.com/python/mypy): Static Typing for Python.
- [flake8](https://github.com/PyCQA/flake8): Plugin for flake8 (wrap PyFlakes, pycodestyle, McCabe)
- [black](https://github.com/psf/black): Uncompromising Python code formatter.
- [isort](https://github.com/PyCQA/isort): Python code formatter for sorting and categorizing imports.
- [autoflake](https://github.com/PyCQA/autoflake): Tool to removes unused imports/variables as reported by pyflakes.
- [pyupgrade](https://github.com/asottile/pyupgrade): Tool to automatically upgrade syntax for newer versions of the language.

#### Text/Doc
- [doctoc](https://github.com/thlorenz/doctoc): Tool to generates table of contents for markdown files.
- [markdownlint](https://github.com/markdownlint/markdownlint): Markdown lint tool.
- [codespell](https://github.com/codespell-project/codespell): Tool for code misspellings checking.

### CI
[pre-commit.ci](https://pre-commit.ci/): GitHub app for pre-commit.
