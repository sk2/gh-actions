# gh-actions

Reusable GitHub Actions workflows for sk2 repositories.

## Versioning

Consumers should reference a tag, e.g. `@v1`.

After merging changes to `main`, update the `v1` tag to the latest commit:

```bash
git tag -f v1
git push -f origin v1
```

## Workflows

- `.github/workflows/rust-ci.yml`
- `.github/workflows/python-ci.yml`
- `.github/workflows/rust-python-maturin-ci.yml`
