# DevOps_production_project

`python` app with `nginx` server with `keycloak` OIDC , in `docker`, orchestrated with `docker-compose`.

## Development

Start the environment: `docker-compose up -d`




### Endpoints

1. http://localhost/: "Hello world!" index page
1. http://localhost/login: redirects to `keycloak` auth
1. http://localhost/auth/callback: `keycloak` callback after login

