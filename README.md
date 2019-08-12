# `pre-commit` demo repo

Demo repo to illustrate [creating custom Git Hooks](https://ajkueterman.dev/posts/intro-to-custom-client-git-hooks-pre-commit/).

## Repo Setup

To configure this repo in order to test the included `pre-commit` hooks, run this command from the root directory:

```bash
git config core.hooksPath .githooks
```

Any commits after that should run the custom script and block commits accordingly.
