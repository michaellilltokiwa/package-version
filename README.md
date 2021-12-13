# package-version

GitHub Action that reads the npm version from package.json file.

## Usage

```yaml
- uses: gagle/package-version@v1.0.0
  id: package-version

- run: ${{ steps.package-version.outputs.version }}
```
