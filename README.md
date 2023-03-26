# Containers

Our images come in two flavors to support different architectures: `arm64` and `amd64`.
Uses by [helm](https://github.com/sergelogvinov/helm-charts) deployments.

* [Fluentd](fluentd) - with common plugins
    * `docker pull ghcr.io/sergelogvinov/fluentd:latest`
    * `docker pull sergelog/fluentd:1.15.3`
* [Keydb](keydb) - keydb with wal-g
    * `docker pull ghcr.io/sergelogvinov/keydb:latest`
* [Mongodb](mongodb) - mongodb with wal-g
    * `docker pull ghcr.io/sergelogvinov/mongodb:latest`
* [Mongosqld](mongosqld) - mongosqld
    * `docker pull ghcr.io/sergelogvinov/mongosqld:latest`
* [Nginx-openrestry](nginx-openrestry) - nginx with lua
    * `docker pull ghcr.io/sergelogvinov/nginx-openrestry:latest`
* [Openvpn](openvpn) - openvpn with opt
    * `docker pull ghcr.io/sergelogvinov/openvpn:latest`
    * `docker pull sergelog/openvpn:2.5.8-2`
* [PGBouncer](pgbouncer) - postgresql pooler
    * `docker pull ghcr.io/sergelogvinov/pgbouncer:latest`
* [Postgresql](postgresql) - postgresql with wal-g
    * `docker pull ghcr.io/sergelogvinov/postgresql:latest`
* [Tabix](tabix) - postgresql with wal-g
    * `docker pull ghcr.io/sergelogvinov/tabix:latest`
