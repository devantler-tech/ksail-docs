# Instructions for ksail-go PR

This document contains instructions for creating a PR on the [ksail-go repository](https://github.com/devantler-tech/ksail-go) to remove the documentation that has been migrated to this repository.

## Summary

The documentation has been successfully migrated from `devantler-tech/ksail-go` to `devantler-tech/ksail-docs`. A corresponding PR needs to be created on the ksail-go repository to:

1. Remove the `docs/` directory
2. Update the README.md to point to the new documentation location

## Changes Required in ksail-go

### 1. Remove the docs directory

Delete the entire `docs/` directory and all its contents:

```bash
git rm -r docs/
```

This includes:
- `docs/README.md`
- `docs/configuration/` (3 markdown files)
- `docs/images/` (7 image files)
- `docs/overview/` (12 markdown files including core-concepts subdirectory)
- `docs/use-cases/` (4 markdown files)

Total: 31 files to be removed

### 2. Update README.md

In the ksail-go repository's README.md, update the documentation section (around lines 71-76) from:

```markdown
## Documentation 📚

### For Users 📖

- Browse the Markdown documentation under [`docs/`](./docs/). Start with [`docs/README.md`](./docs/README.md) for the directory layout and validation commands.
- Run `ksail --help` or `ksail <command> --help` for the latest CLI flags.
```

To:

```markdown
## Documentation 📚

### For Users 📖

- Browse the complete documentation at [devantler-tech/ksail-docs](https://github.com/devantler-tech/ksail-docs)
- Run `ksail --help` or `ksail <command> --help` for the latest CLI flags.
```

## PR Details

**Title:** `docs: migrate documentation to ksail-docs repository`

**Description:**
```
This PR removes the documentation from the ksail-go repository as it has been migrated to the dedicated documentation repository at https://github.com/devantler-tech/ksail-docs.

## Changes
- Remove `docs/` directory and all contents (31 files)
- Update README.md to reference the new documentation location

## Related PRs
- ksail-docs PR: [link to this PR]

## Rationale
Separating documentation into its own repository allows for:
- Better documentation maintenance and updates independent of code releases
- Dedicated documentation workflows and validation
- Easier contribution process for documentation-only changes
- Potential for GitHub Pages publishing
```

## Verification

After creating the PR, verify:
1. All 31 files from the `docs/` directory are removed
2. README.md correctly links to the ksail-docs repository
3. No broken internal links remain in the ksail-go repository
4. The build/CI passes without the docs directory

## Notes

- This is part of the documentation reorganization effort
- All documentation content has been preserved in the ksail-docs repository
- Users can still access documentation through the ksail-docs repository
