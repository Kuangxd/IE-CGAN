# IE-CGAN

## Setup

### Prerequisites
- Linux
- NVIDIA GPU + CUDA CuDNN

### Getting Started
- Install torch and dependencies from https://github.com/torch/distro
- Install torch packages `nngraph` and `display`
```bash
luarocks install nngraph
luarocks install https://raw.githubusercontent.com/szym/display/master/display-scm-0.rockspec
```

## Demo
```bash
DATA_ROOT=datasets/EN/ name=EN which_direction=BtoA phase=256_256 th test.lua
```
