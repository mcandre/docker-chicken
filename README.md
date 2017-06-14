# docker-chicken - a Docker container for Chicken Scheme

# DOCKER HUB

https://registry.hub.docker.com/u/mcandre/docker-chicken/

# EXAMPLE

```
$ make
docker run --rm mcandre/docker-chicken:latest csi -version

CHICKEN
(c) 2008-2013, The Chicken Team
(c) 2000-2007, Felix L. Winkelmann
Version 4.8.0.5 (stability/4.8.0) (rev 5bd53ac)
linux-unix-gnu-x86-64 [ 64bit manyargs dload ptables ]
compiled 2013-10-03 on aeryn.xorinia.dim (Darwin)
```

# REQUIREMENTS

* [Docker](https://www.docker.com/)

## Optional

* [make](http://www.gnu.org/software/make/)
* [Node.js](https://nodejs.org/en/) (for dockerlint)
* [editorconfig-cli](https://github.com/amyboyd/editorconfig-cli) (e.g. `go get github.com/amyboyd/editorconfig-cli`)
* [flcl](https://github.com/mcandre/flcl) (e.g. `go get github.com/mcandre/flcl/...`)
