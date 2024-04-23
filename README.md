# Transceiver 📡

Transceiver is a python library that swiftly exchanges fundamental data structures, specifically numpy arrays, between processes, optimizing AI inference tasks that utilize ComfyUI.

## Why?

When processing a large number of requests, the SaveImage and LoadImage nodes may be IO-limited, and using shared memory improves performance by passing images only through memory access, not through IO.

## Install as ComfyUI custom nodes

```bash
cd /path/to/ComfyUI
source venv/bin/activate
cd custom_nodes
git clone https://github.com/nat-chan/transceiver
cd transceiver
pip install -e .
cd ../.. # cd /path/to/ComfyUI
python main.py # launch
```

## Install as Python library

```bash
pip install transceiver
```

## Features

### SaveImageMem

todo

### LoadImageMem

todo
