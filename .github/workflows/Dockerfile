ARG IMAGE
FROM ${IMAGE}
ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get update && apt-get install -y --no-install-recommends \
        build-essential \
        debhelper \
        devscripts \
        dh-exec \
        pkg-config && \
    rm -rf /var/lib/apt/lists/*
COPY . /src/
WORKDIR /src/
