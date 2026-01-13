# Nicolás Zapata Alzate - Resume

A professionally designed resume template built with LaTeX, showcasing the profile, work experience, and technical skills of Nicolás Zapata Alzate, a Software Developer specializing in AI, Machine Learning, and various programming frameworks.

## Overview

This resume is a LaTeX document that provides a comprehensive overview of professional experience, education, research work, projects, and technical skills. The document is formatted for A4 paper size with a clean, professional design.

## Features

- **Professional Layout**: Clean, modern design with accent color scheme (RGB: 40, 100, 200)
- **Multilingual Support**: Configured for English and Spanish using babel
- **Hyperlinked Content**: All URLs, emails, and social media links are clickable
- **Multi-column Layout**: Efficient use of space for contact information and education
- **Responsive Section Formatting**: Custom section titles with rule separators
- **Professional Photo Integration**: Includes profile picture in header

## File Structure

```
.
├── README.md                                  # Project documentation
├── picture.jpg                                # Profile photo (328 KB)
├── ResumeNicolasZapataAlzate.tex             # LaTeX source file
└── build/                                     # Output directory
    ├── ResumeNicolasZapataAlzate.aux         # LaTeX auxiliary file
    ├── ResumeNicolasZapataAlzate.log         # Compilation log
    ├── ResumeNicolasZapataAlzate.out         # Hyperref output file
    └── ResumeNicolasZapataAlzate.pdf         # Generated PDF (410 KB)
```

## Contents

The resume includes the following sections:

### 1. **Profile**
Professional summary highlighting expertise in Software Engineering, Linux/Windows environments, and AI/ML projects.

### 2. **Contact Information**
- Location: Manizales, Caldas, Colombia
- Phone: +57 3128856774
- Email: works_nicolasz@outlook.com
- Website: nicolas-zapata-portfolio.vercel.app
- GitHub: github.com/NicolasZapata
- LinkedIn: linkedin.com/in/nicolas-zapata-al
- Twitter: twitter.com/niczapata12

### 3. **Education**
- Bachelor in Informatics Engineering (2019-2023)
- La Rioja's International University Foundation (UNIR)
- Emphasis on Computer Engineering, Systems Engineering, and Software Engineering

### 4. **Languages**
- Spanish (Native)
- English (B2)

### 5. **Work Experience**
- **Software Developer** - Quanam Group, Colombia (Nov 2023 - May 2024)
  - Odoo16 development with Python, XML, and JavaScript
  - Technical support, module customization, and project management

- **IT Support** - Convivenita Colombia (Feb 2023 - Apr 2023)
  - Dashboard development for tracking entrants
  - Technical supervision and project management

- **Mobile Developer (Flutter)** - Vibbo (Apr 2021 - May 2021)
  - Flutter mobile app with RESTful APIs and PostgreSQL

- **Mobile Developer** - Digital Brainly Solutions (Jan 2021 - Apr 2021)
  - React Native chat UI and Ionic/Cordova sample pages

### 6. **Research Experience**
- **Academic AI Research** - UNIR (Mar 2020 - Dec 2022)
  - Python-based ML algorithms (supervised & deep learning)
  - Custom dataset design and model validation

### 7. **Projects**
- Coffee Image Classification Algorithm (Thesis)
- Todo React Vite
- Jetpack Compose Application
- Fast Web Node.js Practice
- Classification Tree UNIR
- OpenCV – UNIR
- Data Mining – UNIR
- Fashion Deep Learning

### 8. **Certifications**
- Introduction to Microsoft Azure Cloud Services (Coursera)
- Google AI Essentials (Credly)
- Java Career (Platzi)
- Android Course (Platzi)
- Firebase for Web (Platzi)
- Database Fundamentals (Platzi)
- Git & GitHub Fundamentals (Platzi)
- JavaScript Fundamentals (Platzi)
- Customer Service by IT Professionals (LinkedIn)

### 9. **Technical Skills**
- **Programming Languages:** Java, Kotlin, C, C++, C#, JavaScript, Python, Lua, SQL, Dart, HTML, CSS, R, LaTeX
- **Development Tools:** Cline, Android Studio, Arduino, Unity, Windsurf, Cursor, Visual Studio Code, IntelliJ IDEA, PyCharm, NeoVim, RStudio
- **Frameworks:** React, Odoo, Vite, Next.js, Node.js, Express
- **Databases:** MySQL, PostgreSQL, SQLite, MongoDB, Firebase
- **Mobile Development:** React Native, Flutter, Ionic, Android Studio
- **Collaboration Tools:** Notion, Trello, Jira, Figma, Git, GitHub, Docker, GitLab, BitBucket, Microservicios, Azure, ChatGPT, DeepSeek, Prompt Engineering, Antropic Claude
- **Operating Systems:** Arch Linux, Ubuntu, Linux Mint, Manjaro, Kali Linux
- **Artificial Intelligence:** Pandas, Numpy, Scikit-learn, Tensorflow, PyTorch, OpenCV, Keras, Matplotlib
- **Soft Skills:** Creativity, Critical Thinking, Teamwork, Communication, Self-Investigation

### 10. **Achievements**
- Android development (Java, Kotlin, React Native)
- Machine Learning implementation (Python and R)
- Enterprise solutions (Odoo, Azure, AWS)

## Dependencies

The resume uses the following LaTeX packages:

- `babel` - Multilingual support (English/Spanish)
- `geometry` - Page margins configuration
- `enumitem` - List formatting
- `hyperref` - Hyperlink support
- `xcolor` - Color definitions
- `fontawesome5` - Icon support
- `multicol` - Multi-column layout
- `titlesec` - Section title formatting
- `parskip` - Paragraph spacing
- `graphicx` - Image inclusion
- `setspace` - Line spacing

## Compilation

To compile the LaTeX source file into a PDF, use one of the following commands:

### Using pdflatex
```bash
pdflatex ResumeNicolasZapataAlzate.tex
pdflatex ResumeNicolasZapataAlzate.tex
```

### Using latexmk
```bash
latexmk -pdf ResumeNicolasZapataAlzate.tex
```

### Using xelatex
```bash
xelatex ResumeNicolasZapataAlzate.tex
xelatex ResumeNicolasZapataAlzate.tex
```

**Note**: Compile twice to ensure all references and hyperlinks are correctly resolved.

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

### Photo
Replace `picture.jpg` with your own photo. Ensure it's approximately 3cm wide for optimal fit.

## Output

The compiled PDF is generated in the `build/` directory with the following specifications:
- Paper size: A4
- Font size: 11pt
- Color scheme: Professional blue accents
- File size: ~410 KB

## License

This resume template is for personal use. Feel free to customize it for your own needs.

## Contact

For questions or collaboration opportunities, reach out via:
- Email: works_nicolasz@outlook.com
- LinkedIn: linkedin.com/in/nicolas-zapata-al
- GitHub: github.com/NicolasZapata
