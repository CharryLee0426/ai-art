# ComfyUI

## What is ComfyUI

[ComfyUI](https://github.com/comfyanonymous/ComfyUI) is an open-source, powerful, and modular backend stable diffusion GUI and backend. Compared with WebUI, it is more customable and more advanced. It has more community support and custom nodes. Here is the tutorial about setting up environment for both Windows PC and macOS.

## What do you need

For PC users, you had better to have:

* 16GB RAM;
* RTX Graphic Card with 8GB for reasoning, or 12-16GB for training;
* SSD;

For MacOS users, you had better to have:

* 16GB RAM;
* Apple Silicon Chip;
* Homebrew;

## How to install ComfyUI

For Windows users:

1. Install [Anaconda](https://www.anaconda.com/)
2. Install [Nvdia Cuda Toolkit](https://developer.nvidia.com/cuda-toolkit) if your PC has Nvidia GPU
3. Follow [Manual Install Windows/Linux](https://github.com/comfyanonymous/ComfyUI?tab=readme-ov-file#manual-install-windows-linux)'s guide to install the ComfyUI. Replace pytorch install command based on pytorch official website's command with correct CUDA version

For MacOS users:

1. Install [Homebrew](https://brew.sh/)
2. Install [Miniforge](https://github.com/conda-forge/miniforge) using
    ``` bash
    brew install miniforge
    ```
3. Follow [Apple Mac Silicon](https://github.com/comfyanonymous/ComfyUI?tab=readme-ov-file#apple-mac-silicon)'s guide to install the ComfyUI. Replace pytorch install command based on pytorch official website's command with apple silicon mps support version

For both, after doing this, follow [Running](https://github.com/comfyanonymous/ComfyUI?tab=readme-ov-file#running) part to test if installation is successful.

Last step, install ComfyUI Manager for further use, use [this](https://github.com/ltdrdata/ComfyUI-Manager#installation) guide.

## Basic Usage of ComfyUI

Follow [this](https://www.youtube.com/watch?v=LNOlk8oz1nY) youtube video. It is a series about ComfyUI. Following parts are also good resource for further learning.