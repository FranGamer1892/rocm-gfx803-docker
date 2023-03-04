# rocm-gfx803-docker

[![Publish](https://github.com/FranGamer1892/rocm-gfx803-docker/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/FranGamer1892/rocm-gfx803-docker/actions/workflows/docker-publish.yml)

[rocm-terminal](https://hub.docker.com/r/rocm/rocm-terminal) with gfx803 support made possible by [rocm-gfx803](https://github.com/xuhuisheng/rocm-gfx803).
Also check out the [5.4 branch](https://github.com/FranGamer1892/rocm-gfx803-docker/tree/5.4).

## Usage

```docker pull francisco1892/rocm-gfx803:latest``` to get the docker image.

See [rocm-docker](https://github.com/RadeonOpenCompute/ROCm-docker) for how to run the docker image.

## Installed packages

- torch-1.13.0a0+git49444c3-cp310-cp310-linux_x86_64.whl (v1.13.1)
- torchvision-0.14.1a0+5e8e2f1-cp310-cp310-linux_x86_64.whl (v0.14.1)
- torchaudio-0.13.1+b90d798-cp310-cp310-linux_x86_64.whl (v0.13.1)
- pytorch_lightning-2.0.0rc1-py3-none-any.whl ([commit](https://github.com/Lightning-AI/lightning/commit/bffbcc41b2b111a8ac09513d3ccd2f9f6fa216d7))
