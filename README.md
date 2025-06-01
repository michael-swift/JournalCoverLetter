# Manuscript Submission Cover Letter

A LaTeX template for cover letters when submitting scientific manuscripts to journals.

## Quick Start

1. Clone or download this repository
2. Open `template.tex` in your LaTeX editor
3. Customize the key sections (see below)
4. Compile to PDF

## Customization Guide

### Essential Changes
- **Line 19**: Change journal name (`\journalname{Your Journal Name}`)
- **Line 38**: Replace logo (`logos/your_logo.png`)
- **Line 44**: Update your department and address
- **Line 55**: Change recipient (`Dear Editor` or specific name)
- **Line 57**: Update your manuscript title
- **Lines 60-76**: Replace lorem ipsum with your research summary
- **Lines 83-97**: Update suggested and conflicted reviewers
- **Line 106**: Add your name/signature

### Optional Customizations
- **Line 10**: Adjust text color (`\definecolor{mygray}{gray}{0.2}`)
- **Lines 68-72**: Modify numbered points format
- **Line 52**: Adjust horizontal rule thickness (`1.2pt`)

## File Structure
- `template.tex` - Main LaTeX template
- `bib.bib` - Sample bibliography (update with your references)
- `logos/` - Directory for institutional logos
