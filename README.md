# webuni-cloudnative-block4-deploy-postgres
WebUni Cloud-Native Application Development training's 4th block - Postgres deployment configuration

# How to start the Chart
helm upgrade postgresql bitnami/postgresql --version 12.1.9 -n webuni --set auth.password=<ENTER-PASSWORD> -f values.yaml --install
