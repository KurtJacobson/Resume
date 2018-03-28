# Résumé

This repo contains the XeLaTeX source code for my résumé.  
You can view the compiled PDF document here: [resume.pdf](https://kurtjacobson.github.io/Resume/resume.pdf)

## Compiling

The main XeLaTeX source file is `resume.tex`, which compiles to `resume.pdf`.

Instructions for compiling the document (TeX &rarr;(XeLaTeX)&rarr; PDF):

- **Method 1:** Use `latexmk` for fully automated document generation:
    - `latexmk -xelatex resume.tex`
    (add the `-pvc` switch to automatically recompile on changes)

- **Method 2:** Use `XeLaTeX` directly:
    - `xelatex "resume.tex"`
    (run multiple times to resolve cross-references if needed)

## Dependencies

The Debian `latexmk` and `texlive-xetex` packages are required.

## License

This is free and unencumbered software released into the public domain.
For more information, please see the file `LICENSE` or refer to <http://unlicense.org>.
