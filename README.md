# gha-go-pulumi-task-cicd
GitHub Action for CI/CD with go, Pulumi and Task

## Usage
```yaml
- name: Deploy Pulumi changes
  uses: tunein/gha-go-pulumi-task-cicd@v1
  with:
    role-to-assume: 'arn:aws:iam::761851213649:role/platform_github_actions'
    gh_pat: ${{ secrets.GH_PAT }}
    task: 'deploy'
```

Parameters are described in the `action.yaml`.
