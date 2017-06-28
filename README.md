# Documentation Framework for LaTeX
## Usage

1. Clone the repository
    + '''sh
git clone github.com/predictivemegadollars/documentation-template.git
'''
2. Open __master.tex__ and set the files you want to input
3. Compile with __pdflatex__ or __latexrun__:

'''sh
#pdflatex
pdflatex --shell-escape master.tex

#latexrun
./latexrun --latex-args "\-shell-escape" -O . -o report.pdf master.tex
'''



