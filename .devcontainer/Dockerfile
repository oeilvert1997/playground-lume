# syntax=docker/dockerfile:1

FROM mcr.microsoft.com/devcontainers/base:ubuntu

# [Optional] Uncomment this section to install additional OS packages.
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends <your-package-list-here>

RUN curl -fsSL https://deno.land/install.sh | DENO_INSTALL=/usr/local sh

RUN deno completions zsh > ~/.zsh/completion/_deno