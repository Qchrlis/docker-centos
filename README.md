# docker-centos - Docker base images for CentOS

# ABOUT

docker-centos is a collection of [chroot](http://man.cx/chroot) + [rpm](http://man.cx/rpm)-generated CentOS base images.

# DOCKER HUB

https://registry.hub.docker.com/u/mcandre/docker-centos/

# EXAMPLE

```
$ make
docker run --rm mcandre/docker-centos:latest sh -c 'cat /etc/*release*'
CentOS Linux release 7.1.1503 (Core)
Derived from Red Hat Enterprise Linux 7.1 (Source)
NAME="CentOS Linux"
VERSION="7 (Core)"
ID="centos"
ID_LIKE="rhel fedora"
VERSION_ID="7"
PRETTY_NAME="CentOS Linux 7 (Core)"
ANSI_COLOR="0;31"
CPE_NAME="cpe:/o:centos:centos:7"
HOME_URL="https://www.centos.org/"
BUG_REPORT_URL="https://bugs.centos.org/"

CENTOS_MANTISBT_PROJECT="CentOS-7"
CENTOS_MANTISBT_PROJECT_VERSION="7"
REDHAT_SUPPORT_PRODUCT="centos"
REDHAT_SUPPORT_PRODUCT_VERSION="7"

CentOS Linux release 7.1.1503 (Core)
CentOS Linux release 7.1.1503 (Core)
cpe:/o:centos:centos:7
```

# REQUIREMENTS

* [Docker](https://www.docker.com/)

## Optional

* [make](http://www.gnu.org/software/make/)
* [Node.js](https://nodejs.org/en/) (for dockerlint)
* [editorconfig-cli](https://github.com/amyboyd/editorconfig-cli) (e.g. `go get github.com/amyboyd/editorconfig-cli`)
* [flcl](https://github.com/mcandre/flcl) (e.g. `go get github.com/mcandre/flcl/...`)
