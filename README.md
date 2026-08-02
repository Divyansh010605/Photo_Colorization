# Photo Colorization

Automatic colorization of grayscale images using deep learning (ECCV 2016 and SIGGRAPH 2017 models).

## Overview
Uses two pre-trained CNN models to colorize black-and-white photos automatically.

## Setup
```bash
pip install -r requirements.txt
```

## Usage
```bash
python demo_release.py -i imgs/your_image.jpg
```

The output will be saved as `saved_eccv16.png` and `saved_siggraph17.png`.

## Options
- `-i / --img_path`: Path to the input image
- `-o / --save_prefix`: Output filename prefix
- `--use_gpu`: Enable GPU acceleration
