# C++ and NASM Dev Container

This repo sets up a containerized development environment for learning C/C++ and NASM.

## 🚀 Getting Started

### Run Locally with Docker

```bash
docker build -t cpp-nasm-dev .
docker run -it -v $(pwd):/workspace cpp-nasm-dev
