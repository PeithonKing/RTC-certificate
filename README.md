We had two options:

1. build the PDF using PyLatex library
2. keep a jinja template and complete generate the files by command line

We went with option 2 because it looked neat

```bash
pdflatex main.tex -aux-directory=aux_files -job-name=honey_bunny -output-directory=certificates -quiet
```