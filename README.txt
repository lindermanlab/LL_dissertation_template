Linderman Lab Stanford PhD Dissertation Template
================================================

A LaTeX template for Stanford PhD dissertations, pre-configured with
Stanford formatting requirements. Based on classicthesis v4.2 by
André Miede (http://www.miede.de), licensed under the GNU GPL v2+.

Quick Start
-----------
1. Edit thesis-config.tex to fill in your name, title, department, etc.
2. Update FrontBackmatter/Titlepage.tex with your title and name.
3. Write your chapters in Chapters/ and include them in thesis.tex.
4. Add bibliography entries to Bibliography.bib.
5. Build with: pdflatex thesis.tex && biber thesis && pdflatex thesis.tex && pdflatex thesis.tex

Stanford Formatting
-------------------
- US letter paper, 12pt font
- 1.5 inch left margin, 1 inch on all other sides
- 1.5 line spacing (onehalfspacing)
- Times New Roman font (mathptmx)
- Roman numeral front matter starting at page iv
- See: https://studentservices.stanford.edu/my-academics/earn-my-degree/graduate-degree-progress/dissertations-and-theses/prepare-your-work-0

File Structure
--------------
thesis.tex           - Main document
thesis-config.tex    - Personal data, packages, theorem environments
thesis.sty           - Style file (classicthesis-based)
Chapters/            - Chapter files
FrontBackmatter/     - Title page, abstract, acknowledgments, TOC, bibliography
Figures/             - Figures (organize by chapter)
Bibliography.bib     - Bibliography database (processed by biber)
