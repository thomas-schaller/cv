# CV — Thomas Schaller

Projet LaTeX généré à partir du CV PDF fourni.

## Compilation

Avec une distribution LaTeX standard :

```bash
pdflatex -interaction=nonstopmode cv.tex
```

Le PDF sera généré sous :

```text
cv.pdf
```

## Structure

- `cv.tex` : point d'entrée
- `preamble.tex` : packages et configuration
- `config/` : couleurs, typographie et commandes
- `sections/` : contenu du CV
- `assets/` : ressources graphiques

## Principe

Le cv est basé sur mes expériences.
