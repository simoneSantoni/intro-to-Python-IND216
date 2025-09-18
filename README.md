# Introduction to Python—IND216

## Overview

This repository contains comprehensive educational materials for an
introductory Python course (IND216) designed for analytics students. The
course emphasizes practical data wrangling skills using Python's technical and scientific
computing ecosystem, making it ideal for students with minimal or no
programming background.

## Course Philosophy

Rather than attempting an exhaustive coverage of Python's features, this
course focuses on building a solid foundation in:

- Core Python programming concepts
- Data manipulation fundamentals
- Scientific computing with NumPy
- Data analysis with Pandas

## Repository Contents

### 📚 Course Notes

- **Location**: `/notes/`
- **Format**: LaTeX source files and compiled PDF
- **Content**: Complete course notes covering six modules of Python
  programming for data analysis
- **Building**: Run `pdflatex -shell-escape notes.tex` from the notes
  directory

### 🌐 Interactive Website

The repository also hosts a Quarto-based website featuring a five-part
introduction to Python for MSc students in analytics, providing interactive examples and
exercises for hands-on learning.

## Learning Objectives

Upon completion of this course, students will be able to:

- Write Python scripts for data processing tasks
- Manipulate and analyze data using NumPy arrays
- Perform data wrangling operations with Pandas DataFrames
- Develop reproducible data analysis workflows

## Prerequisites

No prior programming experience is required. The course is designed to take
students from zero coding knowledge to practical data analysis skills.

## Getting Started

1. **Clone the repository**: `bash git clone
https://github.com/simoneSantoni/intro-to-Python-IND216.git `

2. **Set up Python environment** (recommended): `bash conda create -n ind216
python=3.9 conda activate ind216 conda install numpy pandas matplotlib
jupyter `

3. **Access course materials**:
   - PDF notes are available in `/notes/notes.pdf` after compilation
   - Interactive notebooks and examples are throughout the repository

## Course Modules

1. **Organization of the Notes and IND216** - Course overview and learning
   approach
2. **Getting Started with Python** - Installation, environments, and running
   programs
3. **Python Objects** - Data types, control flow, and basic programming
   constructs
4. **Technical & Scientific Computation with NumPy** - Array operations and
   numerical computing
5. **Data Management with Pandas** - DataFrames and data manipulation
6. **Applied Examples and Best Practices** - Real-world data analysis
   workflows

## Contributing

This is an educational repository. If you find errors or have suggestions for
improvements, please open an issue or submit a pull request.

## License

This educational material is provided under the MIT License. See the LICENSE
file for details.

## Contact

For questions about the course content or materials, please open an issue in
this repository.
