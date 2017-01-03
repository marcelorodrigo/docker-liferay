marcelorodrigo/docker-liferay
================================

Liferay Community Edition 7.0-GA3 Docker Image
This image is based on Java 8 Alpine image

[![Docker Stars](https://img.shields.io/docker/stars/marcelorodrigo/docker-liferay?maxAge=2592000)]()
[![Docker Pulls](https://img.shields.io/docker/pulls/marcelorodrigo/docker-liferay.svg?maxAge=2592000)]()
[![](https://images.microbadger.com/badges/image/marcelorodrigo/docker-liferay.svg)](http://microbadger.com/images/marcelorodrigo/docker-liferay)
[![We love bikes](https://img.shields.io/badge/we%20love-bikes-orange.svg)]()

Running your Liferay Server
--------------------------------------

Start your image binding the external ports 80 in all interfaces to your container:

    docker run -p 80:8080 marcelorodrigo/liferay

