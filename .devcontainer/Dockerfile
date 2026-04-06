FROM mcr.microsoft.com/devcontainers/python:0-3.11-bullseye

RUN apt-get update && \
    apt-get install -y --no-install-recommends \
        gfortran \
        make \
        git \
        wget \
        build-essential \
    && rm -rf /var/lib/apt/lists/*

RUN pip install --upgrade pip && \
    pip install \
        "numpy<2.0" \
        scipy \
        matplotlib
