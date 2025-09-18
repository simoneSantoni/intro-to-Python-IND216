# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is an educational repository for "Introduction to Python - IND216/SMM692" course. The repository contains LaTeX-based course notes and supporting materials for teaching Python programming.

## Project Structure

- `notes/` - Main directory containing course materials
  - `notes.tex` - LaTeX source for course notes
  - `notes.pdf` - Compiled PDF output
  - `data/` - Sample data files used in examples
  - Various `.png` images - Screenshots and diagrams for the course
  - `.pgf` files - Plot graphics for the notes
  - `.npy`/`.npz` files - NumPy data files for examples

## Build Commands

### LaTeX Document Compilation
To compile the course notes PDF:
```bash
cd notes
pdflatex -shell-escape notes.tex
```
Note: The `-shell-escape` flag is required for the `minted` package used for code syntax highlighting.

For complete compilation with references and table of contents:
```bash
cd notes
pdflatex -shell-escape notes.tex
pdflatex -shell-escape notes.tex  # Run twice for references
```

## Key Dependencies

The LaTeX document uses:
- `minted` package for Python code syntax highlighting (requires Python Pygments)
- `tcolorbox` for code listing environments
- Standard LaTeX packages for mathematics and formatting

## Development Notes

- The repository is primarily for educational content, not a software project
- Python code snippets are embedded within the LaTeX document
- No Python package management files (requirements.txt, setup.py, etc.) as this is documentation-focused
- Git is tracking changes to the PDF and auxiliary LaTeX files