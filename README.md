# Cursor Rules

A collection of reusable [Cursor](https://www.cursor.so/) rules for code quality, organization, and best practices. Designed to be included in multiple projects by cloning and ignoring in your main repo.

## Usage

### 1. Clone This Repo Into Your Project

From your project root:

```sh
git clone git@github.com:cuzelac/cursor-rules.git .cursor/rules
```

### 2. Add to `.gitignore`

Add the `.cursor/rules` to your project's `.gitignore` to avoid tracking the rules in your main repo:

```
echo .cursor/rules >> .gitignore
```

## Rule Example

See [`cursor-rules-location.mdc`](./cursor-rules-location.mdc) for a sample rule and documentation on correct rule placement.

## License

MIT License. See [LICENSE](./LICENSE) for details.

---

**Note:** This repo is intended for use with [Cursor](https://www.cursor.so/). Most users should not track this directory in their main project repo, but instead copy or symlink rules as needed. 