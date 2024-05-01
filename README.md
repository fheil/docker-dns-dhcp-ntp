# docker: dns-dhcp-ntp (for portainer stack editor)
Docker image with bind9, isc-dhcp and ntp

The docker-compose.yml is prepared to be used with [portainer.io](https://www.portainer.io) Stack-Editor.

You only have to define two environment variables:

* BASE_DIR
* BINDS

Example:
```
BASE_DIR=/foo/docker
BINDS=/binds
```
