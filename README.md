<div align="center">
  <img src="https://gist.githubusercontent.com/0-vortex/3ba0d05bcd4afdbd0f2bf20542caf682/raw/02c432297a6822cd2944a41b9cc9986357d49748/His_Worshipful_Grace-1.svg" width="400">

# @tmcb/conventional-commit

> Never miss a conventional commit with [**commitizen**](https://github.com/commitizen/cz-cli) running on [**npx**](https://www.npmjs.com/package/npx).

[![Commits](https://img.shields.io/github/commit-activity/w/open-sauced/conventional-commit?style=flat)](https://github.com/open-sauced/conventional-commit/pulse)
[![Issues](https://img.shields.io/github/issues/open-sauced/conventional-commit.svg?style=flat)](https://github.com/open-sauced/conventional-commit/issues)
[![Releases](https://img.shields.io/github/v/release/open-sauced/conventional-commit.svg?style=flat)](https://github.com/open-sauced/conventional-commit/releases)

</div>

## 📦 Install

This package is binary and doesn't require installation however you can add it to your repository as a `devDependency`:

```shell
npm install --save-dev @tmcb/conventional-commit
```

## 🚀 Usage

All you have to do is run the script next to your `package.json`:

```shell
npx @tmcb/conventional-commit
# or
npx conventional-commit
```

## 🔧 Configuration

The most common use case for this package is to run it instead of the `git commit` command inside your `npm` scripts:

```json
{
  "scripts": {
    "push": "npx @tmcb/conventional-commit"
  }
}
```

or

```json
{
  "scripts": {
    "push": "npx conventional-commit"
  }
}
```

If you want to ensure local-only usage:

```json
{
  "scripts": {
    "push": "conventional-commit"
  }
}
```

## 🤝 Contributing

If you decide to fix a bug, make sure to use the conventional commit available at:

```shell
npm run push
```

## ⚖️ LICENSE

MIT © [TED (Teodor-Eugen Dutulescu) Vortex](./LICENSE)
