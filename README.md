# Docker GDAL2

GDAL2 Docker images.

## Versions
The philosophy behind Git / Docker tags correlation we ended up using is simple: the master branch of this repo contains as many folders containing different Docker image builds as Docker tags we like to have. We don't use Git tags nor branches to try to correlate with Docker tags. We try this in the past and was a mess. Each version packages makes a folder, each folder builds a __geographica/gdal2__ Docker tag bundling different library versions.

These are the available versions:
- GDAL 2.0.1
- GDAL 2.0.2
- GDAL 2.1.0
- GDAL 2.1.1
- GDAL 2.1.2
- GDAL 2.1.3
- GDAL 2.2.0
- GDAL 2.2.1
- GDAL 2.2.2
- GDAL 2.2.3
- GDAL 2.2.4
- GDAL 2.3.0
- GDAL 2.3.1
- GDAL 2.3.2
- GDAL 2.4.0
- Daily - Nightly Snapshots; to test new features (use at your own risk!!).

## DockerHub
Pulling image from DockerHub (use "latest" or version*):

```bash
$ docker pull geographica/gdal2:latest
```
*Daily is for testing purposes only, and is only available for building image directly from Dockerfile (not available for pulling from Dokerhub).

[DockerHub repo link](https://hub.docker.com/r/geographica/gdal2/)

## GDAL 2 info
- http://download.osgeo.org/gdal/presentations/GDAL%202.1%20(FOSS4G%20Bonn%202016).pdf
- https://2015.foss4g-na.org/session/gdal-20-overview
- http://trac.osgeo.org/gdal/wiki/GDAL20Changes

## Credits
- https://github.com/OSGeo/gdal
- https://registry.hub.docker.com/u/geodata/gdal/
