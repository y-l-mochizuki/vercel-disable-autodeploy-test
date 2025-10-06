FYI: https://vercel.com/docs/project-configuration/git-configuration#turning-off-all-automatic-deployments

mainブランチマージ時に自動でvercelのデプロイが行われないかの確認をするだけのrepository
```
{
  "$schema": "https://openapi.vercel.sh/vercel.json",
  "git": {
    "deploymentEnabled": false
  }
}
```
