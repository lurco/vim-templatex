# A LaTeX template repository with Vim compatible snippets

## The best LaTeX templates (article, book, report, beamer, resume and more) coupled with simple snippets for the UltiSnip plugin

Required plugins: 

1. Vim plugin manager (Vundle Pathogen etc)
2. UltiSnip plugin (which in turn requires Python 3 in your Vim)
3. (optional) YouCompleteMe --- a stupendous autocomplete plugin for Vim, that
unfortunately requires a lot of dependencies and a seperate python installation.

---

### In order to load the full preamble template you can type 'preamble...' and use the YouCompleteMe suggestion bar in order:

1. preamble (for document class setttings and translation and encoding option for polish ISO-Latin-2 if this doesn't apply delete the first line)
2. polish-preamble (if the document is is polish)
3. xetex-preamble (if the document is to be rendered by XeTeX) or pdflatex-preamble (for pdfLaTeX)
4. preamble-graphics
5. preamble-math
6. preamble-pagestyles

I recommend putting this all in a seperate document 'preamble.tex'. Then you can put your entire content into the boilerplate.tex file
between the `\begin{document}` and `\end{document}`. You can create the environment with the snippet 'boilerplate'.
