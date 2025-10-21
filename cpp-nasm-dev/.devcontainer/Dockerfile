FROM debian:bullseye

RUN apt update && apt install -y \
  build-essential \
  clang \
  nasm \
  cmake \
  gdb \
  vim \
  git

WORKDIR /workspace
CMD [ "bash" ]
