# cv

My resume repo.

## Contains

* Markdown

## FAQ

* How to generate pdf from markdown?

```bash
pandoc README.md --to=pdf -t latex -o cv.pdf --pdf-engine=/Library/Tex/texbin/pdflatex -V geometry:"top=1cm, bottom=0cm, left=1cm, right=1cm"
```

