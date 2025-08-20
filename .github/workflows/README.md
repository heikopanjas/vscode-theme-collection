# GitHub Actions Workflow

This directory contains GitHub Actions workflows for the Ultralove Theme Collection.

## build-vsix.yml

Automatically builds VSIX packages for the VS Code theme extension.

### Triggers
- Push to `main` or `develop` branches
- Pull requests to `main`
- Git tags starting with `v` (e.g., `v0.1.0`, `v1.2.3`)
- Manual workflow dispatch

### What it does
1. **Validates** package.json and theme JSON files
2. **Builds** VSIX package using `@vscode/vsce`
3. **Uploads** VSIX as workflow artifact (30-day retention)
4. **Creates** GitHub releases for version tags
5. **Attaches** VSIX files to releases

### How to use

#### For development testing:
```bash
git push origin main
# Check Actions tab for build artifacts
```

#### For releases:
```bash
# Update version in package.json first
git tag v0.1.0
git push origin v0.1.0
# Check Releases section for downloadable VSIX
```

#### Manual trigger:
Go to Actions → Build VSIX Package → Run workflow

### Artifacts
- Build artifacts are available for 30 days in the Actions tab
- Release assets are permanent and attached to GitHub releases
- VSIX files can be installed with: `code --install-extension filename.vsix`
