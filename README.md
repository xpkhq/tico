# Tico

![Tico Logo](./docs/img/tico.png)

Tico is a tiny container runtime.

## About Tico & TCI

Tico aims to be tiny, robust and easy.

Tico doesn't follow OCI. Instead, we've created another standard, TCI (Tiny Container Interface).

Tico is lighter than Docker, as the containers aren't always full containers. They may be an application container containing just one process, without a filesystem. As a result, creating, booting and scheduling containers should be much quicker with Tico, as fast as running a new process.

Further information of TCI can be found in [docs/tci.md](docs/tci.md)
