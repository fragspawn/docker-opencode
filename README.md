## Opencode setup for LAMP & Docker development

This is an extension the anomalyco/opencode container image to

* Add docker CLI to container-manage the parent environment
* contain the default BASH toolset needed for development in-container
* Incorporate a PHP environment with common extensions
* Node/NPM & composer 
* ports open for opencode UI & a spare to run http services in-container  

### Files

* docker-compose.yml to expose volumes with parent environment
* Dockerfile.oc that adds necessary packages for a dev environment

### Execute

```docker compose up```