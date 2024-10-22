# FROM mcr.microsoft.com/devcontainers/base:debian-12
FROM mcr.microsoft.com/devcontainers/cpp:debian-12

COPY ./reinstall-cmake.sh /tmp/

# RUN apt-get update \
#     && apt-get install -y build-essential git python3 cmake

RUN chmod +x /tmp/reinstall-cmake.sh && /tmp/reinstall-cmake.sh \
    && rm -f /tmp/reinstall-cmake.sh