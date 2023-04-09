![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)

# Summary
This template shows how to build and push a docker image with GitHub Actions.

# How to use

* Customize the code of `Dockerfile`
* Prepare a docker repository on [DockerHub](https://hub.docker.com/) to host your project
* Customize the build-push action in `.github/workflows/docker-image.yaml`, in particular remember to use right DockerHub credentials and to add them to your repository 
secrets
* The workflow is (by default) run either when the code of the docker file or action script gets changed, or when triggered manually.