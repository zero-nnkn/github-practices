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
| `chore`    | 🧹 | Something that doesn’t fit the other types                    |
| `wip`      | 🚧 | Working in progress                                           |
