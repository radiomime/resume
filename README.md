# Resume

## Usage

### Requirements

`pdflatex` is required, on mac that will come in `mactex`. Also, `skim` is required for rendering the PDF on save.

### Generate a PDF

To generate a PDF from this LaTeX code, navigate to this folder in a terminal and run:

```sh
pdflatex resume.tex
```

### Editing live

```sh
# view new file via auto-refresh
open -a Skim resume.pdf

# compile new pdf on file save
latexmk -pdf -pvc resume.tex
```
