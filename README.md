# Gitlab and Gitea comparision

## Gitlab

* You need to add `gitlab.local` to you host file. Docs say you can't use localhost
* Create a runner in gitlab-gui
```sh
cd gitlab-testing/gitlab-runner-mount
cp .config.toml.sample .config.toml
# Add your obtained token
```

## Gitea
