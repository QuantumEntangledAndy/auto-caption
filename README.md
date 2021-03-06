# Auto-caption.

[![PyPI](https://img.shields.io/pypi/v/auto-caption)](https://pypi.org/project/auto-caption/)
[![PyPI - Downloads](https://img.shields.io/pypi/dm/auto-caption)](https://pypi.org/project/auto-caption/)
[![PyPI - License](https://img.shields.io/pypi/l/auto-caption)](https://github.com/aguang-xyz/auto-caption)
[![Build/release](https://github.com/aguang-xyz/auto-caption/workflows/Build/release/badge.svg)](https://github.com/aguang-xyz/auto-caption/actions)

## Install.

### Install ffmpeg first.


```bash
sudo apt install ffmpeg
```

### Install through pypi.

```bash
pip3 install auto-caption
```

## Usage.

```bash
usage: auto-caption [-h] [--format FORMAT] [--output OUTPUT] video

Automatic captioning for movies.

positional arguments:
  video            The path of input video

optional arguments:
  -h, --help       show this help message and exit
  --format FORMAT  Output format (vtt/srt, default: vtt)
  --output OUTPUT  The path to write subtitle file
```

## Sample.

Click [here](https://aguang-xyz.github.io/auto-caption/samples/) to see sample captions generated by this program.
