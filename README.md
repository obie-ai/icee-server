# Icee.cc (Server)

Icee.cc exposes your localhost to the world for easy testing and sharing! No need to mess with DNS or deploy code just to have others test out your changes.

This repo is the server component. If you are just looking for the CLI Icee app, see [obie-ai/icee-client](https://github.com/obie-ai/icee-client).

## Overview ##

The default Icee client connects to the `icee.cc` server.

## REST API

### POST /api/tunnels

Create a new tunnel. An Icee client posts to this enpoint to request a new tunnel with a specific name or a randomly assigned name.

### GET /api/status

General server information.

## License ##
MIT