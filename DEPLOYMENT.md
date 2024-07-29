# Installation instructions

## For development

Configure keycloak's `LOGOUT_REDIRECT_URL` and `OAUTH_PROVIDERS` in `docker/pythonpath_dev/superset_config.py`.

An example realm and users export is provided in the `keycloak exports` folder.

You can launch the application with `docker compose up`.

## For production

There are no clear instruction on running this in production, but you can inspect [the official documentation](https://superset.apache.org/docs/configuration/configuring-superset/) for basic configuration options.

There is a `docker-compose-non-dev.yml` that was used for the production deployment.
