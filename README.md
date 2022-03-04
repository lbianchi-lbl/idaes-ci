# IDAES CI

## Managing workflows

Workflows can be managed:

- Manually, from the "Actions" tab in this repository
- Programmatically, using the `gh` command-line tool

### Triggering a workflow

```sh
gh workflow run "All solvers" -f examples-pse-ref=main
```

### Downloading artifacts

```sh
gh run download --name examples-pse-html
```
