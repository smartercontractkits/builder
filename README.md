# Builder Docker Image

This project contains the docker image used as part of [NuLink](https://github.com/smartercontractkits/nulink)'s Continuous Integration (CI).

It is based on the baidu SGX builder image and adds Go 1.13, Node 10.16.3 and Yarn 1.17.3.

On merges to master it publishes a [docker image](https://hub.docker.com/r/smartercontractkits/builder).
