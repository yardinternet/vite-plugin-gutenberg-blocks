# 📦 Fork Notice

This is a maintained fork of [evo-mark/vite-plugin-gutenberg-blocks](https://github.com/evo-mark/vite-plugin-gutenberg-blocks).

## Added features

- `entryDir` prop — allows us to specify a custom entry directory for Gutenberg blocks, making the package compatible with theme-based block development.

## Install

```bash
npm install @yardinternet/vite-plugin-gutenberg-blocks
```

Used in the Yard Toolkit

## 🔄 Keeping Up With Upstream

The upstream remote is still configured:

```
git remote add upstream https://github.com/evo-mark/vite-plugin-gutenberg-blocks.git
```

To pull updates:

```
git fetch upstream
git checkout main
git merge upstream/main
```

Be aware: since this is a heavy fork, merge conflicts may need manual resolution.

## 🚀 How to publish

1. Change the version of `package.json` to the desired version and commit this change.
2. Go to [releases of the package](https://github.com/yardinternet/vite-plugin-gutenberg-blocks/releases) and click on "Draft a new release"
3. Click "Choose a tag", type the corresponding version and press Enter. Add a title and description for the release.
4. Click "Publish release"

The Github Workflow `release-package.yml` will run whenever a release is created in this repository. If the tests pass, then the package will be published to Github packages.
