# Docker-node

A NodeJS Docker image with some additions :

- `ca-certificates` : Install `ca-certificates` package to fix issues during
[Circle CI's builds](https://support.circleci.com/hc/en-us/articles/360016505753-Resolve-Certificate-Signed-By-Unknown-Authority-error-in-Alpine-images)

This project keeps the same structure than the
[docker-node](https://github.com/nodejs/docker-node)
repository where the original NodeJS image are declared.
