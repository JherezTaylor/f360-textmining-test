# f360-textmining-test

Python code for text mining test

## Environment

- Ubuntu 17.04
- python3-dev
- libcurl4-openssl-dev [If not already installed in packages]

## Setup

Create your virtual environment of choice. I usually go with

```bash
virtualenv -p python3 venv
cd venv
. bin/activate
```

From the virtual environment, install the packages in requirements.txt with

```bash
pip install -r requirements.txt
```

After installing the packages execute the follow from your
shell:

```bash
pynlpir update
```

## Run

To run the code, open a terminal and start the notebook server with:

```bash
jupyter notebook
```

Enjoy :smiley: