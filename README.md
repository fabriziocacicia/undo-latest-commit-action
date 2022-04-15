# Undo Latest Commit
A Github Action tu undo the latest commit.

## Usage
In order to use this action you first need to checkout the repository.
Add the following snippet to your workflow's yaml file:

```yaml
runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
        with:
           fetch-depth: 0
      - name: Undo Latest Commit
        uses: fabriziocacicia/undo-latest-commit-action@v0.1.0

```
