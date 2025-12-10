# PTIT Internship Graduation Report

## AI-Based Mobile System for Plant Disease Detection and Monitoring

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![LaTeX](https://img.shields.io/badge/LaTeX-008080?logo=latex&logoColor=white)](https://www.latex-project.org/)
[![Vietnamese](https://img.shields.io/badge/Language-Vietnamese-red)](https://vi.wikipedia.org/wiki/Ti%E1%BA%BFng_Vi%E1%BB%87t)

This repository contains the graduation report for the internship project at **Posts and Telecommunications Institute of Technology (PTIT)**, focusing on developing an AI-based mobile system for plant disease detection and monitoring.

## 📋 Project Information

- **Title**: AI-Based Mobile System for Plant Disease Detection and Monitoring
- **Students**: 
  - Tran Nguyen Phi Hung (N21DCCN036)
  - Duong Thanh Toan (N21DCCN085)
- **Class**: E21CQCNTT01-N
- **Major**: Artificial Intelligence
- **Program**: High-Quality Program
- **Supervisor**: PhD. Nguyen Minh Tuan
- **Academic Year**: 2021

## 🎯 Project Objectives

This study aims to develop an intelligent mobile application system that can:

- **Automatically detect and classify plant diseases** through image analysis
- **Provide real-time monitoring capabilities** for crop health assessment
- **Offer accessible diagnostic tools** for farmers and agricultural professionals
- **Deliver actionable recommendations** for disease management and treatment

## 📖 Report Structure

The report is organized into the following chapters:

1. **Introduction** - Project rationale, objectives, and methodology
2. **Chapter 1** - Literature review and theoretical background
3. **Chapter 2** - System design and architecture
4. **Chapter 3** - Implementation and development
5. **Chapter 4** - Testing and evaluation
6. **Chapter 5** - Results and conclusions

## 🛠️ Technical Requirements

### Prerequisites

To compile this LaTeX document, you need:

- **LaTeX Distribution**: TeX Live (recommended) or MiKTeX
- **XeLaTeX Engine**: Required for Vietnamese language support
- **Bibliography Tool**: Biber or BibTeX
- **Fonts**: Times New Roman (included in most systems)

### Required Packages

The document uses the custom `ptit-report-template.sty` style file which includes:

- `fontspec` - For font management
- `babel` - For Vietnamese language support
- `geometry` - For page layout
- `graphicx` - For image handling
- `hyperref` - For hyperlinks and references
- `biblatex` - For bibliography management

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/thanhtoan105/PTIT-Intership-Graduation-Report.git
cd PTIT-Intership-Graduation-Report
```

### 2. Compile the Document

#### Option A: Using XeLaTeX (Recommended)

```bash
xelatex main.tex
biber main
xelatex main.tex
xelatex main.tex
```

#### Option B: Using LaTeX Workshop (VS Code)

1. Install the LaTeX Workshop extension
2. Open `main.tex`
3. Use the "🎯 Complete Build (bibliography + glossaries)" recipe
4. The compiled PDF will be generated in the `output/` directory

### 3. View the Output

The compiled PDF will be available as:
- `output/main.pdf` - Full document with bibliography
- `output/main_flat.pdf` - Flattened version (if generated)

## 📁 Project Structure

```
├── main.tex                    # Main document file
├── main_flat.tex              # Flattened version
├── ptit-report-template.sty   # Custom PTIT template
├── ref.bib                    # Bibliography database
├── content/                   # Document content
│   ├── title.tex             # Title page
│   ├── inner_title.tex       # Inner title page
│   ├── acknowlegement.tex    # Acknowledgements
│   ├── introduction.tex      # Introduction
│   ├── acronyms.tex          # Acronyms and abbreviations
│   └── chapters/             # Main chapters
│       ├── chapter_1.tex
│       ├── chapter_2.tex
│       ├── chapter_3.tex
│       ├── chapter_4.tex
│       └── chapter_5.tex
├── images/                   # Images and figures
│   ├── PTIT_logo.png
│   ├── chapter_1/
│   ├── chapter_2/
│   ├── chapter_3/
│   ├── chapter_4/
│   └── chapter_5/
├── code/                     # Code examples
│   ├── example.py
│   ├── example.cpp
│   └── example-vietnamese.py
├── appendix/                 # Appendices
│   └── appendix.tex
└── output/                   # Compiled output files
    └── main.pdf
```

## 🔧 Customization

### Modifying Student Information

Edit the following commands in `main.tex`:

```latex
\newcommand{\supervisorname}{PhD. Nguyen Minh Tuan}
\newcommand{\studentnameone}{Your Name - Student ID}
\newcommand{\studentnametwo}{Partner Name - Student ID}
\newcommand{\classname}{Your Class}
\newcommand{\majorname}{Your Major}
\newcommand{\reporttitle}{Your Report Title}
```

### Adding New Chapters

1. Create a new `.tex` file in `content/chapters/`
2. Add the chapter to `main.tex`:
   ```latex
   \subfile{content/chapters/your_new_chapter}
   ```

### Adding Images

1. Place images in the appropriate `images/chapter_x/` directory
2. Reference in your document:
   ```latex
   \includegraphics[width=0.8\textwidth]{chapter_1/your_image.png}
   ```

## 🤝 Contributing

This is an academic project, but suggestions and improvements are welcome:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add some improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Create a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Posts and Telecommunications Institute of Technology (PTIT)** for providing the academic framework
- **PhD. Nguyen Minh Tuan** for supervision and guidance
- The **Artificial Intelligence Department** for technical support
- All contributors to the open-source LaTeX packages used in this project

## 📞 Contact

For questions or collaboration opportunities:

- **Tran Nguyen Phi Hung**: [Contact information]
- **Duong Thanh Toan**: [Contact information]
- **Project Repository**: [https://github.com/thanhtoan105/PTIT-Intership-Graduation-Report](https://github.com/thanhtoan105/PTIT-Intership-Graduation-Report)

---

**Note**: This document is written primarily in Vietnamese as per academic requirements. The README is provided in English for broader accessibility.
