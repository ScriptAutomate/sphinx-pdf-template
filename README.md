# Sphinx PDF Output Template

- Uses GitHub Actions to generate a PDF from a Sphinx project, and upload the artifact
- Makes use of [docker-sphinx: sphinx-latexpdf](https://github.com/sphinx-doc/docker) for minimal Sphinx and LaTeX requirements
  - Pulls the following Docker container: [`sphinxdoc/sphinx-latexpdf:<sphinx-version>`](https://hub.docker.com/r/sphinxdoc/sphinx-latexpdf)
