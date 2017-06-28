# Documentation Framework for LaTeX
## Usage

1. Clone the repository
```sh
git clone https://github.com/predictivemegadollars/documentation-template.git
```
2. Open __master.tex__ and set the files you want to input
3. Set your project name using the custom __\setProject{}__ command provided from the .sty file.
4. Compile with __pdflatex__ or __latexrun__:

```sh
#pdflatex
pdflatex --shell-escape master.tex

#latexrun
./latexrun --latex-args "\-shell-escape" -O . -o report.pdf master.tex
```



