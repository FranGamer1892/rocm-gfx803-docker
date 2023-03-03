# rocm-gfx803-docker

[![Publish](https://github.com/FranGamer1892/rocm-gfx803-docker/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/FranGamer1892/rocm-gfx803-docker/actions/workflows/docker-publish.yml)

[rocm-terminal](https://hub.docker.com/r/rocm/rocm-terminal) with gfx803 support made possible by [rocm-gfx803](https://github.com/xuhuisheng/rocm-gfx803).
Also check out the [latest branch](https://github.com/FranGamer1892/rocm-gfx803-docker/tree/latest).

## Usage

```docker pull francisco1892/rocm-gfx803:5.4``` to get the docker image.

See [rocm-docker](https://github.com/RadeonOpenCompute/ROCm-docker) for how to run the docker image.

## Installed packages

- torch-1.11.0a0+git503a092-cp38-cp38-linux_x86_64.whl
- torchvision-0.12.0a0+2662797-cp38-cp38-linux_x86_64.whl
- torchaudio-0.11.0+820b383-cp38-cp38-linux_x86_64.whl
- tensorflow_rocm-2.8.0-cp38-cp38-linux_x86_64.whl
