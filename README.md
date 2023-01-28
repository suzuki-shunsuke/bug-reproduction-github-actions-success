# bug-reproduction-github-actions-success

Reproduction code of https://github.com/community/community/discussions/45058

## How to reproduce

1. [Fork this repository](https://github.com/suzuki-shunsuke/bug-reproduction-github-actions-success/fork)
1. [Run GitHub Actions Workflow](https://github.com/suzuki-shunsuke/bug-reproduction-github-actions-success/actions/workflows/test.yaml)

You can run the workflow from Web UI or by [GitHub CLI](https://cli.github.com/manual/gh_workflow_run).

```console
$ gh workflow run test.yaml
```

## Expected behaviour

The job `zoo` is run.

## Actual behavior

The job `zoo` is skipped.

https://github.com/suzuki-shunsuke/bug-reproduction-github-actions-success/actions/runs/4032247270

<img width="1085" alt="image" src="https://user-images.githubusercontent.com/13323303/215272328-d2067ef0-415f-4a02-9baa-8b654413f039.png">

## LICENSE

[MIT](LICENSE)
