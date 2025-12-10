# PTIT Graduation Thesis Report

## AI-Integrated Accounting ERP System with RAG Technology

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![LaTeX](https://img.shields.io/badge/LaTeX-008080?logo=latex&logoColor=white)](https://www.latex-project.org/)
[![Vietnamese](https://img.shields.io/badge/Language-Vietnamese-red)](https://vi.wikipedia.org/wiki/Ti%E1%BA%BFng_Vi%E1%BB%87t)

This repository contains the graduation thesis report for the **Posts and Telecommunications Institute of Technology (PTIT)**, focusing on developing an AI-integrated accounting module within an ERP system using Retrieval-Augmented Generation (RAG) technology.

## 📋 Project Information

- **Title**: Building an AI Application to Support the Accounting Module in an ERP System (Xây dựng ứng dụng AI hỗ trợ phân hệ kế toán trong hệ thống ERP)
- **Student**: Duong Thanh Toan (N21DCCN085)
- **Class**: E21CQCNTT01-N
- **Major**: Information Technology
- **Program**: High-Quality Program
- **Academic Year**: 2021-2026

## 🎯 Project Objectives

This study aims to develop an intelligent ERP accounting system integrated with AI using RAG technology, providing a dual interface (traditional UI and natural language chatbot) to support efficient accounting management while complying with Vietnamese regulations.

### Short-term Goals
- Develop a core ERP platform with accounting modules (accounts receivable/payable management, financial reporting, electronic invoicing)
- Implement a basic RAG chatbot for data queries
- Reduce query time by up to 60%

### Long-term Goals
- Integrate advanced RAG for multi-module analysis and multi-turn conversations
- Automate accounting period closing
- Achieve ≥99% accuracy on test sets
- Ensure compliance with Circular 200/2014/TT-BTC (Vietnamese Accounting Standards)

## 📖 Report Structure

The report is organized into the following chapters:

1. **Introduction (Mở đầu)** - Project rationale, objectives, research subjects, and methodology
2. **Chapter 1: Overview (Tổng quan)** - Current state of ERP systems, AI integration trends, and challenges in Vietnam
3. **Chapter 2: Theoretical Foundation (Cơ sở lý thuyết)** - ERP systems, accounting principles (VAS/TT200), and technology stack
4. **Chapter 3: RAG Overview and Model Architecture (Tổng quan RAG và kiến trúc mô hình)** - RAG fundamentals, vector databases, and system architecture
5. **Chapter 4: System Analysis and Design (Phân tích và thiết kế hệ thống)** - Functional decomposition, use cases, and database design
6. **Chapter 5: Application Development (Phát triển ứng dụng)** - UI implementation and system features
7. **Chapter 6: Conclusion and Future Development (Kết luận và định hướng phát triển)** - Results, limitations, and roadmap

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
git clone https://github.com/thanhtoan105/Thesis-Defense-Report.git
cd Thesis-Defense-Report
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
├── cover.pdf                   # Cover page (imported as PDF)
├── ptit-report-template.sty    # Custom PTIT LaTeX template
├── references.bib              # Bibliography database
├── content/                    # Document content
│   ├── title.tex               # Title page
│   ├── title-block.tex         # Title block formatting
│   ├── acknowlegement.tex      # Acknowledgements
│   ├── introduction.tex        # Introduction (Mở đầu)
│   ├── abbreviation.tex        # Abbreviations definitions
│   ├── list_of_symbols_abberivation.tex  # List of symbols
│   ├── appendix.tex            # Appendices
│   └── chapters/               # Main chapters
│       ├── chapter_1.tex       # Overview (Tổng quan)
│       ├── chapter_2.tex       # Theoretical Foundation
│       ├── chapter_3.tex       # RAG Overview & Architecture
│       ├── chapter_4.tex       # System Analysis & Design
│       ├── chapter_5.tex       # Application Development
│       └── chapter_6.tex       # Conclusion & Future Work
├── images/                     # Images and figures
│   ├── PTIT_logo.png
│   ├── chapter_2/              # ERP, PostgreSQL, Spring Boot diagrams
│   ├── chapter_3/              # RAG architecture diagrams
│   ├── chapter_4/              # System design diagrams
│   └── chapter_5/              # Application screenshots
├── code/                       # Code examples
│   ├── example.py
│   ├── example.cpp
│   └── example-vietnamese.py
└── output/                     # Compiled output files
    └── main.pdf
```

## 🔧 Customization

### Modifying Student Information

Student and project information can be configured in the `main.tex` file or `content/title.tex`. The template uses commands like:

```latex
\newcommand{\supervisorname}{Your Supervisor Name}
\newcommand{\studentnameone}{Student Name - Student ID}
\newcommand{\classname}{Your Class}
\newcommand{\reporttitle}{Your Report Title}
```

### Adding New Chapters

1. Create a new `.tex` file in `content/chapters/`
2. Use the subfile document class:
   ```latex
   \documentclass[../../main.tex]{subfiles}
   \begin{document}
   \chapter{Your Chapter Title}
   % Chapter content
   \end{document}
   ```
3. Include it in `main.tex`:
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

## 🔑 Key Technologies Covered

- **ERP Systems** - Enterprise Resource Planning architecture and accounting modules
- **RAG (Retrieval-Augmented Generation)** - AI technique combining retrieval and generation
- **Large Language Models (LLMs)** - GPT/Claude integration for natural language processing
- **Vector Databases** - FAISS/Pinecone/Supabase Vector for semantic search
- **Vietnamese Accounting Standards** - VAS and Circular 200/2014/TT-BTC compliance
- **Spring Boot** - Backend framework for ERP system
- **ReactJS** - Frontend framework for user interface
- **PostgreSQL** - Relational database for accounting data

## 🙏 Acknowledgments

- **Posts and Telecommunications Institute of Technology (PTIT)** for providing the academic framework
- The **Information Technology Department** for technical support
- All contributors to the open-source LaTeX packages used in this project

## 📞 Contact

For questions or collaboration opportunities:

- **Duong Thanh Toan**: thanhtoan105
- **Project Repository**: [https://github.com/thanhtoan105/Thesis-Defense-Report](https://github.com/thanhtoan105/Thesis-Defense-Report)

---

**Note**: This thesis document is written primarily in Vietnamese as per academic requirements at PTIT. The README is provided in English for broader accessibility.
