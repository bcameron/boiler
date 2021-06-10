# Boiler
A monorepo collection of mutually compatable starter projects for web apps and websites.

## Organization and Expectations
The folders are organized like this `[domain]/[technology_detail1_deatil2]`. We prefer duplication for variations witb descriptive names in the secondary level folder, for example `api/goland_postgres_basic`. 

Runnnig the `scripts/dev.sh` runs the project providing system dependencies have been installed. System dependencies should be clearly described as the first item after the brief project description. `scripts/build.sh` and `scripts/deploy.sh` scripts are available where appropriate and possible. `dev` scripts should handle live reloading and facilitate rapid iteration where possible, they can therefore be blocking. `run` scripts can serve as a more primitive non live reloading version of the `dev` script where appropriate. `scripts/test.sh` tests a project where appropriate, which is most of the time when resources are available.

TODO: We endevour to supply `docker-compose.yaml` files for quick starting a collection of projects that work together.
TODO: We endevour to supply Kubernetes deployments as examples (details to be clarified).

## List of projects

### `db/postgres`
PostgreSQL starter kit.

### `api/golang_postgres_pgx`
Template for serving and api using Golang backed by a PostgreSQL database.

### `frontend/sveltekit`
Templste for creating a server side rendered web app using SvelteKit.

