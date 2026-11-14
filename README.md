# MyCV

LaTeX source of my academic CV. The compiled PDF is [`sample.pdf`](sample.pdf).

It lists education, publications (conference papers, journal manuscripts and preprints), research and teaching experience, projects, skills and achievements. The same information, with links to papers and certificates, is on [ratulhasan.dev](https://ratulhasan.dev).

## Build

The source works with pdfLaTeX, XeLaTeX or LuaLaTeX. With a TeX Live or MacTeX installation:

```bash
latexmk -pdf sample.tex      # pdfLaTeX
# or
latexmk -xelatex sample.tex  # XeLaTeX
```

`latexmk -c` removes the auxiliary files afterwards.

## Files

| File | Purpose |
| ---- | ------- |
| `sample.tex` | CV source (single-file, `article` class with `fontawesome5`, `paracol` and `tikz`) |
| `sample.pdf` | Compiled CV |
| `latexmkrc` | latexmk settings |

---

Ratul Hasan · [ratulhasan.dev](https://ratulhasan.dev) · [Google Scholar](https://scholar.google.com/citations?user=EfwUJ2cAAAAJ&hl=en) · [ORCID](https://orcid.org/0009-0009-5429-7501)
