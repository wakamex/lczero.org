---
title: "Download Lc0"
weight: 200
---

The latest stable version of Lc0 is **{{< param lc0version >}}**.

There are several versions of the engine which use different hardware to evaluate neural network.

## Windows

Every package contains both **lc0.exe** (the engine), and **client.exe** (only needed if you would like to contribute training games).

CUDA version is recommended for fairly recent NVidia GPU (year 2014 or later).  
Supported GPUs are GTX&nbsp;7xx, GTX&nbsp;8xx, GTX&nbsp;9xx, GTX&nbsp;1xxx, RTX&nbsp;2xxx and so on.  
**[Download Lc0 {{< param lc0version >}} for Windows, with CUDA backend](https://github.com/LeelaChessZero/lc0/releases/download/{{<param lc0version>}}/lc0-{{<param lc0version>}}-windows-gpu-nvidia-cuda.zip)**

OpenCL version is for non-NVidia GPUs, and for older NVidia GPUs.  
**[Download Lc0 {{< param lc0version >}} for Windows, with OpenCL backend](https://github.com/LeelaChessZero/lc0/releases/download/{{<param lc0version>}}/lc0-{{<param lc0version>}}-windows-gpu-opencl.zip)**

DNNL BLAS version is for computers without GPUs, but with modern CPUs.  
**[Download Lc0 {{< param lc0version >}} for Windows, with DNNL BLAS backend](https://github.com/LeelaChessZero/lc0/releases/download/{{<param lc0version>}}/lc0-{{<param lc0version>}}-windows-cpu-dnnl.zip)**

OpenBLAS version is for older CPUs.  
**[Download Lc0 {{< param lc0version >}} for Windows, with OpenBLAS backend](https://github.com/LeelaChessZero/lc0/releases/download/{{<param lc0version>}}/lc0-{{<param lc0version>}}-windows-cpu-openblas.zip)**

Older versions and beta releases are available at our [GitHub releases page](https://github.com/LeelaChessZero/lc0/releases).

## Other versions

TODO(write about other OSes, including Linux, MacOS and Android. Possibly in a separate article)
