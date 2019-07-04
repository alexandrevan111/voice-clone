# Real-Time Voice Cloning

## Quick start
### Requirements
You will need the following whether you plan to use the toolbox only or to retrain the models.

**Python 3.7**. Python 3.6 might work too, but I wouldn't go lower because I make extensive use of pathlib.

Run `pip install -r requirements.txt` to install the necessary packages. Additionally you will need [PyTorch](https://pytorch.org/get-started/locally/).

A GPU is mandatory, but you don't necessarily need a high tier GPU if you only want to use the toolbox.

### Preliminary
Before you download any dataset, you can begin by testing your configuration with:

`python demo_cli.py`

If all tests pass, you're good to go.

### Toolbox
You can then try the toolbox:

`python demo_toolbox.py -d <datasets_root>`  
or  
`python demo_toolbox.py`  