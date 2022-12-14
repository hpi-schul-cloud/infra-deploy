# infra-deploy
> This repository is used to enable development teams to roll out changes on clusters. It is based on the [dof-app-deploy](https://github.com/hpi-schul-cloud/dof_app_deploy) repository.

# Edusharing Crawler
Rollout Edusharing Crawlers.

Crawlers:
- hello_world
- mediothek_pixiothek_spider
- merlin_spider
- sodix_spider
- sodix_permissions
- h5p_upload

Clusters
- infra-dev-edusahring-1
- sc-dev-edusharing (no approval needed)
- sc-staging-edusharing
- sc-prod-edusharing

# Nextcloud Development space on dev cluster
A namespace, a bucket and a nextcloud installation can be created so that the dev team can develope on the dev nextcloud kubernetes cluster.

Cluster
- sc-dev-nextcloud