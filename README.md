# Bitnami Confluent Schema Registry Stack

## What is Confluent Schema Registry?

> Confluent Schema Registry provides a RESTful interface by adding a serving layer for your metadata on top of Kafka. It expands Kafka enabling support for Apache Avro, JSON, and Protobuf schemas.

[Overview of Confluent Schema Registry](https://www.confluent.io)



## TL;DR

```console
$ docker run --name schema-registry bitnami/schema-registry:latest
```

## Why use Bitnami Images?

* Bitnami closely tracks upstream source changes and promptly publishes new versions of this image using our automated systems.
* With Bitnami images the latest bug fixes and features are available as soon as possible.
* Bitnami containers, virtual machines and cloud images use the same components and configuration approach - making it easy to switch between formats based on your project needs.
* All our images are based on [minideb](https://github.com/bitnami/minideb) a minimalist Debian based container image which gives you a small base container image and the familiarity of a leading Linux distribution.
* All Bitnami images available in Docker Hub are signed with [Docker Content Trust (DCT)](https://docs.docker.com/engine/security/trust/content_trust/). You can use `DOCKER_CONTENT_TRUST=1` to verify the integrity of the images.
* Bitnami container images are released on a regular basis with the latest distribution packages available.

## Supported tags and respective `Dockerfile` links

Learn more about the Bitnami tagging policy and the difference between rolling tags and immutable tags [in our documentation page](https://docs.bitnami.com/tutorials/understand-rolling-tags-containers/).


* [`7.1`, `7.1-debian-11`, `7.1.3`, `7.1.3-debian-11-r1`, `latest` (7.1/debian-11/Dockerfile)](https://github.com/bitnami/bitnami-docker-schema-registry/blob/7.1.3-debian-11-r1/7.1/debian-11/Dockerfile)
* [`7.0`, `7.0-debian-11`, `7.0.5`, `7.0.5-debian-11-r0` (7.0/debian-11/Dockerfile)](https://github.com/bitnami/bitnami-docker-schema-registry/blob/7.0.5-debian-11-r0/7.0/debian-11/Dockerfile)
* [`6.2`, `6.2-debian-11`, `6.2.6`, `6.2.6-debian-11-r0` (6.2/debian-11/Dockerfile)](https://github.com/bitnami/bitnami-docker-schema-registry/blob/6.2.6-debian-11-r0/6.2/debian-11/Dockerfile)
* [`6.1`, `6.1-debian-11`, `6.1.1`, `6.1.1-debian-11-r0` (6.1/debian-11/Dockerfile)](https://github.com/bitnami/bitnami-docker-schema-registry/blob/6.1.1-debian-11-r0/6.1/debian-11/Dockerfile)
* [`6.0`, `6.0-debian-11`, `6.0.8`, `6.0.8-debian-11-r0` (6.0/debian-11/Dockerfile)](https://github.com/bitnami/bitnami-docker-schema-registry/blob/6.0.8-debian-11-r0/6.0/debian-11/Dockerfile)

Subscribe to project updates by watching the [bitnami/schema-registry GitHub repo](https://github.com/bitnami/bitnami-docker-schema-registry).

## Get this image

The recommended way to get the Bitnami schema-registry Docker Image is to pull the prebuilt image from the [Docker Hub Registry](https://hub.docker.com/r/bitnami/schema-registry).

```console
$ docker pull bitnami/schema-registry:latest
```

To use a specific version, you can pull a versioned tag. You can view the [list of available versions](https://hub.docker.com/r/bitnami/schema-registry/tags/) in the Docker Hub Registry.

```console
$ docker pull bitnami/schema-registry:[TAG]
```

If you wish, you can also build the image yourself.

```console
$ docker build -t bitnami/schema-registry:latest 'https://github.com/bitnami/bitnami-docker-schema-registry.git#master:7.1/debian-11'
```

## Contributing

We'd love for you to contribute to this container. You can request new features by creating an [issue](https://github.com/bitnami/bitnami-docker-schema-registry/issues), or submit a [pull request](https://github.com/bitnami/bitnami-docker-schema-registry/pulls) with your contribution.

## Issues

If you encountered a problem running this container, you can file an [issue](https://github.com/bitnami/bitnami-docker-schema-registry/issues/new). For us to provide better support, be sure to include the following information in your issue:

- Host OS and version
- Docker version (`docker version`)
- Output of `docker info`
- Version of this container
- The command you used to run the container, and any relevant output you saw (masking any sensitive information)

## License

Copyright &copy; 2022 Bitnami

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
