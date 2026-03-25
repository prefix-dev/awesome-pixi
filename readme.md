# Awesome Pixi [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Pixi is a cross-platform, cross-language software development manager for reproducible environments and packages.

This is a curated list of awesome things related to Pixi.

## Contents

- [Learning](#learning)
- [Extensions](#extensions)
- [Build Backends](#build-backends)
- [IDE Support](#ide-support)
- [Projects using Pixi](#projects-using-pixi)
- [Contribute](#contribute)

## Learning

Where can you learn about Pixi?

- [Main Docs](http://pixi.sh)
- [GitHub Repo](http://github.com/prefix-dev/pixi)
- Videos
  - [Jean Golding Institute](https://www.youtube.com/watch?v=ws92c5NFPaU) - Can others reproduce your `conda` results? Using `pixi` in a Python data analysis project.
  - [Inspiring Computing](https://www.youtube.com/watch?v=jkkMZqdbEeY) - Pixi: Getting Started.
  - [Anaconda](https://www.youtube.com/watch?v=sItH-WKxdBo) - Environment Management with Pixi.
  - [ROS with Pixi playlist](https://www.youtube.com/watch?v=-ywpmxbb8_A&list=PLJ18jaEFbsWiCfrbczEoDTXqhpdsZJfjc) - Playlist containing short videos to manage ROS environments with Pixi.
- Conference talks:
  - [EuroPython 2025](https://www.youtube.com/watch?v=HOqv3kh4z_c) - Unlocking Hidden Power of Conda with Pixi — Ruben Arts, Julian Hofer.
  - [SciPy 2025](https://www.youtube.com/watch?v=UeyMkK5MzcA) - Reproducible Science Made Easy: Package Management with Pixi - Ruben Arts & Wolf Vollprecht.
  - [PyCon DE 2025](https://www.youtube.com/watch?v=ScxPMrIMahY) - Streamlining Python deployment with Pixi: A Perspective from production - Dennis Weyland.
  - [PyData Paris 2024](https://www.youtube.com/watch?v=O-up045PgXE) - Bridging the worlds: pixi reimplements pip and conda in Rust - Nichita Morcotilo.
- Conference Workshops:
  - [SciPy 2025](https://www.youtube.com/watch?v=8AYp3MlRSNA) - Reproducible Machine Learning Workflows for Scientists with pixi - Arts, Feickert, & Kirkham.

### Example projects

- [pixi-docker-chtc](https://github.com/UW-Madison-DSI/pixi-docker-chtc) - Example configurations for using containerized Pixi environments with HTCondor and GPUs.

## Extensions

Community made tools and extensions, [documentation](https://pixi.sh/latest/integration/extensions/introduction/).

- [pixi-diff-to-markdown](https://github.com/pavelzw/pixi-diff-to-markdown) - Generate markdown summaries from `pixi update`.
- [pixi-pack](https://github.com/quantco/pixi-pack) && `pixi-unpack` - Pack Pixi environments to/from a tarball.
- [pixi-diff](https://github.com/pavelzw/pixi-diff) - Generate JSON diffs between lockfiles.
- [pixi-inspect](https://github.com/toprinse/pixi-inspect) - Analyze a conda package and extracts metadata from its `index.json`.
- [pixi-inject](https://github.com/pavelzw/pixi-inject) - Inject conda packages into an already existing conda prefix.
- [pixi-outdated](https://github.com/benmoss/pixi-outdated) - Find outdated packages in an environment.
- [pixi-to-conda-lock](https://github.com/basnijholt/pixi-to-conda-lock) - Convert Pixi lockfiles to conda-lock format.
- [pixi-ros](https://github.com/ruben-arts/pixi-ros) - Initialize a Pixi workspace from a ROS workspace.
- [pixi-browse](https://github.com/pavelzw/pixi-browse) - Browse conda packages interactively.
- [pixi-skills](https://github.com/pavelzw/pixi-skills) - Manage coding agent skills with Pixi.
- [pixi-install-to-prefix](https://github.com/pavelzw/pixi-install-to-prefix) - Install Pixi environments to an arbitrary prefix.

## Build Backends

Pixi build backends for building conda packages with `pixi build`, [documentation](https://pixi.prefix.dev/latest/build/getting_started/).

- [pixi-build-python](https://pixi.prefix.dev/latest/build/backends/pixi-build-python/) - Build backend for Python projects.
- [pixi-build-cmake](https://pixi.prefix.dev/latest/build/backends/pixi-build-cmake/) - Build backend for CMake projects.
- [pixi-build-rust](https://pixi.prefix.dev/latest/build/backends/pixi-build-rust/) - Build backend for Rust projects.
- [pixi-build-r](https://pixi.prefix.dev/latest/build/backends/pixi-build-r/) - Build backend for R packages.
- [pixi-build-mojo](https://pixi.prefix.dev/latest/build/backends/pixi-build-mojo/) - Build backend for Mojo projects.
- [pixi-build-rattler-build](https://pixi.prefix.dev/latest/build/backends/pixi-build-rattler-build/) - Build backend using rattler-build.
- [pixi-build-ros](https://pixi.prefix.dev/latest/build/backends/pixi-build-ros/) - Build backend for ROS packages.

## IDE Support

Tools to help you use Pixi in your favorite IDE.

- [pixi-pycharm](https://github.com/pavelzw/pixi-pycharm) - Conda shim for PyCharm that proxies Pixi.
- [pixi-kernel](https://github.com/renan-r-santos/pixi-kernel) - Jupyter kernels using Pixi for reproducible notebooks.
- [pixi-vscode](https://marketplace.visualstudio.com/items?itemName=jjjermiah.pixi-vscode) - Visual Studio Code extension to manage Pixi environments.

## Projects using Pixi

- [lfortran](https://github.com/lfortran/lfortran) - A modern interactive compiler and runtime for Fortran.
- [FreeCAD](https://github.com/FreeCAD/FreeCAD) - A general-purpose parametric 3D CAD modeler and a BIM software.

### GPU Computing

- [NVIDIA/numba-cuda](https://github.com/NVIDIA/numba-cuda) - The CUDA target for Numba.
- [modular/mojo-gpu-puzzles](https://github.com/modular/mojo-gpu-puzzles) - A collection of GPU-accelerated puzzles implemented in Mojo.

### Robotics

- [ros2](https://github.com/ros2/ros2) - The Robot Operating System, is a meta operating system for robots.
- [VSLAM-LAB](https://github.com/VSLAM-LAB/VSLAM-LAB) - A Comprehensive Framework for Visual SLAM Systems and Datasets.
- [rerun](https://github.com/rerun-io/rerun) - An open source SDK for logging, storing, querying, and visualizing multimodal and multi-rate data.

### Deep Learning / Machine Learning

- [VistaDream](https://github.com/pablovela5620/VistaDream) - Sampling multiview consistent images for single-view scene reconstruction.
- [pfizer-opensource/bigwig-loader](https://github.com/pfizer-opensource/bigwig-loader) - A fast dataloader for bigwig files made for machine learning.
- [facebookresearch/momentum](https://github.com/facebookresearch/momentum) - A library for human kinematic motion and numerical optimization solvers to apply human motion.

### Data Science / Data Analysis

- [SciPy](https://github.com/scipy/scipy) - Scientific computing library for Python.
- [MODFLOW6](https://github.com/MODFLOW-ORG/modflow6) - USGS Modular Hydrologic Model.
- [Bodo](https://github.com/bodo-ai/Bodo) - High-Performance Python Compute Engine for Data and AI.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
