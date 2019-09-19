# Read PDF Content

A simple script which allows pdf text to be read.

## Installation

### Virtual environment:

Create virtual environment with name venv within project folder.

```
python -m virtualenv venv
```

This allows activation of virtual environment with 

```
.\venv\Scripts\activate
```

### Requirements

```
pip install -r requirements.txt
```

## Usage

The read_pdf.py file contains the function extract_text_from_pdf,
which takes as argument the path to the pdf and returns all the text retrieved from the pdf.

```
pdf_text = extract_text_from_pdf(/path/to/pdf)
```

This can be run from the terminal with:
```
python read_pdf.py > output_file.txt
```