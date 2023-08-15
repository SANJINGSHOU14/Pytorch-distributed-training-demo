# Pytorch-distributed-training-demo

> Pytorch distributed training demo using Single device with multiple GPUs

[![NPM Version][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Downloads Stats][npm-downloads]][npm-url]

Go through the whole process of distributed traning by training a simple CNN model.


## Installation

OS X & Linux:

```sh
git clone git@github.com:SANJINGSHOU14/Pytorch-distributed-training-demo.git
```

Windows:

just download the zip

## Usage example

Train the model on the single device with 4 GPUs
```sh
torchrun
    --standalone
    --nnodes=1
    --nproc-per-node=4
    YOUR_TRAINING_SCRIPT.py (--arg1 ... train script args...)
```
remember replace `YOUR_TRAINING_SCRIPT.py` with your script name.

## Development setup


```sh
pip install torch
```

## Release History


## Meta

Chao – chao299@outlook.com

Distributed under the GNU3 license. See ``LICENSE`` for more information.


## Contributing

1. Fork it (<https://github.com/yourname/yourproject/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

<!-- Markdown link & img dfn's -->


