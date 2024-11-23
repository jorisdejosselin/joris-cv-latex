# Joris de Josselin de Jong - Professional CV

## Overview
LaTeX-based professional Curriculum Vitae for Joris de Josselin de Jong.

## Requirements
- LaTeX distribution (TeX Live or MiKTeX)
- moderncv package
- XeLaTeX or pdfLaTeX compiler

## Compilation

### On macOS

1. Install MacTeX, which includes the TeX Live distribution and necessary tools:
  ```bash
  brew install --cask mactex-no-gui
  ```
2. OPTIONAL: Ensure that the TeX Live binaries are in your PATH. You can add the following line to your shell profile (e.g., .bash_profile, .zshrc):
  ```
  export PATH="/Library/TeX/texbin:$PATH"
  ```
3. Compile the CV using:
  ```
  xelatex cv_joris_de_josselin_de_jong.tex
  ```