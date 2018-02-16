# docker-testcafe-node

NOTE: Use for testing only! Root user is being used.

https://github.com/theogravity/docker-testcafe-node

https://hub.docker.com/r/personalife/docker-testcafe-node

- Docker-in-docker
- Alpine linux
- curl
- python + pip
- awscli
- bash
- jq
- ecs-deploy
- boto3
- yarn

## Publishing

This repo is integrated directly into docker cloud for auto-publishing.

- When a PR goes into master, a new docker image tagged with `latest` is automatically created
- When A new version is tagged under github releases, a
new docker image will be created with that tag. The tag version format must be `vX.Y.Z`
