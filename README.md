[![CircleCI](https://dl.circleci.com/status-badge/img/gh/giantswarm/onepassword-scim-bridge-app/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/giantswarm/onepassword-scim-bridge-app/tree/main)
[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/giantswarm/onepassword-scim-bridge-app/badge)](https://securityscorecards.dev/viewer/?uri=github.com/giantswarm/onepassword-scim-bridge-app)

[Read me after cloning this template (GS staff only)](https://handbook.giantswarm.io/docs/dev-and-releng/app-developer-processes/adding_app_to_appcatalog/)

# onepassword-scim-bridge chart

This repository contains Giant Swarm App packaging for the 1Password SCIM Bridge Helm chart.

This app is intended for Giant Swarm internal use, but others are welcome to use it if it suits their needs.

## Installing

There are several ways to install this app onto a workload cluster.

- [Using GitOps to instantiate the App](https://docs.giantswarm.io/advanced/gitops/apps/)
- [Using our web interface](https://docs.giantswarm.io/platform-overview/web-interface/app-platform/#installing-an-app).
- By creating an [App resource](https://docs.giantswarm.io/use-the-api/management-api/crd/apps.application.giantswarm.io/) in the management cluster as explained in [Getting started with App Platform](https://docs.giantswarm.io/getting-started/app-platform/).

## Credit

- [1Password SCIM Bridge Helm Chart](https://github.com/1Password/op-scim-helm)
