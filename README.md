# Docker Puppeteer

A Node + Puppeteer base image for running Puppeteer scripts. Add your own tools (such as Jest, Mocha, etc), link services you want to test via Docker Compose, and run your Puppeteer scripts with a headless Chromium.

Has Git installed as well to be possible to run NX tools (for example `affected:tests`) using only this container.

Container based on [Buildkite Puppeteer](https://github.com/buildkite/docker-puppeteer)

## Versions

See the list of [Docker Hub tags](https://hub.docker.com/r/dmk1111/puppeteer/tags/) for Puppeteer versions available.

## Example

See the [example directory](example) for a complete Docker Compose example, showing how to run Puppeteer against a linked Docker Compose web service.

## Releasing

1. Create a new release on GitHub. The image is tagged with the same version as Puppeteer.
2. Docker Hub automatically builds images for the tag.
3. There is no step 3.
