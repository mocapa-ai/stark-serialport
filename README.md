# BrainCo RevoHand SDK Examples
## What's different from the original repo
### UV package wrapper
This repo wraps the original code as a Python package so it can be installed and run via `uv` without cloning the repo.
- Only the `revo2` module is packaged currently.

#### Installing:
```bash
uv build
```

#### Running:
```bash
uv build
uv run python stark_serialport/revo2/revo2_ctrl.py --port /dev/ttyUSB0
```

## Official Documentation

[Docs](https://www.brainco-hz.com/docs/revolimb-hand/revo2/parameters.html)

## Python Examples

Python development examples and usage instructions: [Python Development Guide](python/README.md)

## C++ Examples

C++ development examples and compilation instructions for Linux/Ubuntu environments: [Ubuntu C++ Development Guide](linux/README.md)

## ROS2 Examples

[brainco_hand_ros2](https://github.com/BrainCoTech/brainco_hand_ros2)
[URDF](https://github.com/BrainCoTech/revo2_description_ros1)
