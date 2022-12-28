# docker-build-multi-architecture-workflow [![test](https://github.com/int128/docker-build-multi-architecture-workflow/actions/workflows/test.yaml/badge.svg)](https://github.com/int128/docker-build-multi-architecture-workflow/actions/workflows/test.yaml)

This is a reusable workflow for building a multi-architecture container image.

<img width="700" alt="image" src="https://user-images.githubusercontent.com/321266/209787155-1948c19e-6e78-4ec2-bfae-a288d8efed5e.png">

## Getting Started

```yaml
jobs:
  build:
    uses: int128/docker-build-multi-architecture-workflow/.github/workflows/build.yaml@v1
```

## Limitation

For now this action supports the following use-case.

- Always use the GitHub-hosted runner
- Push an image to GHCR (GitHub container registry)
