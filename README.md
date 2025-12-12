# How To Use

On your repository root:

```sh
git submodule add https://github.com/noshiro-pf/common-agent-config.git agents/common
```

then

```sh
ln -s agents/common/agents/AGENTS.md AGENTS.md
```

Ignore `./agents` in `.prettierignore`, `.cspell.json`, `.markdownlint-cli2.mjs`, `eslint.config.mts` etc.
