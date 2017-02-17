[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/hipsteripsum.svg)](https://hub.docker.com/r/rubygem/hipsteripsum/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/hipsteripsum.svg)](https://hub.docker.com/r/rubygem/hipsteripsum/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/hipsteripsum.svg)](https://hub.docker.com/r/rubygem/hipsteripsum/)
[![Gem Downloads](https://img.shields.io/gem/dt/hipsteripsum.svg)](https://rubygems.org/gems/hipsteripsum/)
# hipsteripsum

Auto-Generated Docker image for hipsteripsum to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/hipsteripsum`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/hipsteripsum`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/hipsteripsum`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/hipsteripsum/)
