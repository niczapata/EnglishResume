# Nicolás Zapata Alzate - Resume

A professionally designed resume built with LaTeX, showcasing the profile, work experience, research, projects, and technical skills of **Nicolás Zapata Alzate**, a Software Engineer specializing in Data Automation, Backend Architecture, and Cloud-based Solutions.

## Overview

This resume is a LaTeX document that provides a comprehensive overview of professional experience, education, research work, projects, and technical skills. The document is formatted for A4 paper size with a clean, professional design.

## Features

- **Professional Layout**: Clean, minimal design with accent color scheme (RGB: 40, 100, 200)
- **ATS-Friendly**: Plain text contact information compatible with applicant tracking systems
- **Hyperlinked Content**: All URLs, emails, and social media links are clickable
- **Custom Section Formatting**: Section titles with rule separators and accent coloring

## File Structure

```
.
├── README.md                                  # Project documentation
├── ResumeNicolasZapataAlzate.tex              # LaTeX source file
└── build/                                     # Output directory
    ├── ResumeNicolasZapataAlzate.aux          # LaTeX auxiliary file
    ├── ResumeNicolasZapataAlzate.log          # Compilation log
    ├── ResumeNicolasZapataAlzate.out          # Hyperref output file
    └── ResumeNicolasZapataAlzate.pdf          # Generated PDF
```

## Contents

The resume includes the following sections:

### 1. **Contact**
- Location: Manizales, Colombia
- Phone: (+57) 312-885-6774
- Email: works_nicolasz@outlook.com
- Portfolio: nicolas-zapata-portfolio.vercel.app
- LinkedIn: linkedin.com/in/nicolas-zapata-al
- GitHub: github.com/NicolasZapata

### 2. **Summary**
Software Engineer with 3+ years of experience in data automation, backend architecture, and cloud-based solutions (Python, Node.js, AWS, Terraform).

### 3. **Work Experience**
- **Software Developer** — Quanam Group, Colombia (Nov 2023 – May 2024)
  - Odoo 16 module development (Inventory, CRM) with Python, XML, JavaScript
  - Barcode shipping system and petty cash management module
  - Automated reporting dashboards

- **Full-Stack Developer & IT Analyst** — Conviventia Colombia (Feb 2023 – Apr 2023)
  - Internal dashboard with Node.js, React, and SQL
  - Data migration and cross-departmental rollout

- **Mobile Developer (Flutter)** — Vibbo (Apr 2021 – May 2021)
  - Startup MVP features with Flutter (Dart), RESTful APIs, PostgreSQL, FastAPI JWT

### 4. **Research & Development**
- **AI Research Engineer** — UNIR (Mar 2020 – Dec 2022)
  - Python-based ML pipelines (scikit-learn, TensorFlow, Pandas)
  - Experimental frameworks for research reproducibility
  - Scalable, documented code for algorithmic research

### 5. **Technical Skills**
- **Programming & Automation:** Python, Node.js, JavaScript, SQL, Bash
- **Cloud & DevOps:** AWS (Lambda, API Gateway, S3, IAM, Cognito), Docker, CI/CD, Azure
- **APIs & Backend:** FastAPI, RESTful APIs, OAuth 2.0 / JWT, Unit Testing (Pytest), Microservices
- **Data & AI/ML:** Pandas, NumPy, scikit-learn, TensorFlow, PostgreSQL, MySQL, Data Pipelines (ETL), PyTorch, OpenCV, HuggingFace, OpenRouter
- **Frontend & Mobile:** React, React Native, Flutter, HTML/CSS
- **Tools:** Git, Linux, Odoo

### 6. **Soft Skills**
Analytical Problem-Solving, Proactive Mindset, Effective Communication, Collaborative Teamwork, Adaptability

### 7. **Projects**
- End-to-End Coffee Bean Classification Model (Python, TensorFlow, Computer Vision)
- Data Processing & Classification Pipeline (Python, scikit-learn, pandas, NumPy)

### 8. **Education**
- **Bachelor in Informatics Engineering** — UNIR (Feb 2019 – Jul 2023)
- **English Diploma Program** — Universidad Autónoma de Manizales (Feb 2025 – Present)

### 9. **Certifications**
- Introduction to Microsoft Azure Cloud Services — Coursera (Feb 2025)
- Google AI Essentials — Coursera (Aug 2024)
- Java Career (Java SE, Java EE) — Platzi
- JavaScript, Git, Database Fundamentals — Platzi

## Dependencies

The resume uses the following LaTeX packages:

- `inputenc` — UTF-8 encoding
- `babel` — English language support
- `geometry` — Page margins configuration
- `enumitem` — List formatting
- `hyperref` — Hyperlink support
- `xcolor` — Color definitions
- `titlesec` — Section title formatting
- `parskip` — Paragraph spacing
- `setspace` — Line spacing

## Compilation

To compile the LaTeX source file into a PDF:

### Using pdflatex
```bash
pdflatex ResumeNicolasZapataAlzate.tex
pdflatex ResumeNicolasZapataAlzate.tex
```

### Using latexmk
```bash
latexmk -pdf ResumeNicolasZapataAlzate.tex
```

**Note**: Compile twice to ensure all hyperlinks are correctly resolved.

## Customization

### Colors
Modify the accent color by changing the RGB values:
```latex
\definecolor{accent}{RGB}{40, 100, 200}
```

### Margins
Adjust page margins in the geometry package:
```latex
\usepackage[margin=1in]{geometry}
```

## Output

The compiled PDF has the following specifications:
- Paper size: A4
- Font size: 11pt
- Color scheme: Professional blue accents

## License

This resume template is for personal use. Feel free to customize it for your own needs.

## Contact

For questions or collaboration opportunities, reach out via:
- Email: works_nicolasz@outlook.com
- LinkedIn: linkedin.com/in/nicolas-zapata-al
- GitHub: github.com/NicolasZapata
