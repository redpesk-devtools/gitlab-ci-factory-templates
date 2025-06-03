# gitlab-ci-factory-templates

Template .yml files for Gitlab CI (see [doc](https://docs.gitlab.com/ci/yaml/includes/)) to be used in your project to launch a build and redtests on a redpesk factory instance.

The main template uses `rp-cli` to connect to a redpesk factory instance.
Current variables used:
- RP_REMOTE_FACTORY_NAME: name to give to the redpesk factory instance to use (e.g. aquarium)
- RP_REMOTE_FACTORY_URL: URL of the redpesk factory to use (e.g. https://aquarium-app.redpesk.bzh)
- RP_REMOTE_FACTORY_TOKEN: Access token to the factory
- RP_REMOTE_FACTORY_PROJECT: Name of the factory's project
- RP_REMOTE_FACTORY_APP: Name of the factory's application to build / test
