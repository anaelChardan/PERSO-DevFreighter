# DevFreighter
Web Project Dockerization for development purposes.

# Goals

- To be able to Dockerize a project (with all the services in one Docker running Supervisord)

php devfreighter.phar create

> done!

Independing of the Platform it should

- install docker
- configure the docker-machine and the host of the docker machine if any (route, mount point etc.)
- build the image
- create the container and the volume for the persistent data.
- run the docker
- propose ultimately a system to allow the running of scripts from the project within docker

- create and kind of admin interface with useful services
  - phpmemcached admin
  - mongodb admin
  - supervisord web admin
- project must be install (as an option)
- with https, varnish or not etc..

# Discussion

- what about doing that with a .phar, we would use the exec or whatever is better to avoir long bash script
- the module configuration should be in YAML
- we need to create the Ansible Role to wrap the current version
- get the variable from somewhere


Let's do it
