# Helm Chart Template

Use this template to build helm charts more quickly and easily. This includes Github actions for testing the chart installation into a kind cluster and automated releases to Github Pages.

See https://nthings.github.io/helm-chart/ for see the example deployed on this repo!.

## Helm Docs

README.md on the charts can be automatically generated with [helm-docs](https://github.com/norwoodj/helm-docs) check the pre-commit settings.

## Github Pages Helm Repository

You can take advantage of free Github Pages to host a free helm repository. Follow the instructions [here](https://docs.github.com/en/pages/quickstart) to set up Github Pages on your repository and check outh the release.yml workflow it will publish new charts versions automatically.