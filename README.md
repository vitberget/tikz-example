# Fun with LaTeX & TikZ

## Make PDF

1. Run:
   ```sh
   xelatex example.tex
   ```
2. View *example.pdf*

## Make just SVG

1. Run:
   ```sh
   xelatex -shell-escape example-svg.tex
   pdf2svg example-svg.pdf example-svg.svg
   ```
2. View *example-svg.svg*
