# Gitlab and Gitea comparision

## Gitlab

* You need to add `gitlab.local` to you host file. Docs say you can't use localhost
* Create a runner in gitlab-gui
```bash
cd gitlab-testing/gitlab-runner-mount
cp .config.toml.sample .config.toml
# Add your obtained token
```

## Gitea

* Copy you runner token and add it to you .env file
```bash
cd gitea-testing
cp .env.sample .env
# Add your obtained token
```
