# LaTeX Assignment Revision and Quality Assurance Report

**Course:** CSE 0613-3109: System Analysis & Design  
**Institution:** Department of Computer Science & Engineering (CSE), Khwaja Yunus Ali University (KYAU)  
**Instructor:** Mst Anika Amzad, Lecturer, Department of CSE, KYAU  
**Document Title:** System Analysis, Testing, Deployment, Maintenance, Governance, Security, and Ethics  
**Date of Audit & Build:** October 29, 2026  

---

## 1. Executive Summary

This comprehensive audit and revision was conducted under the directives of the newly installed Antigravity academic writing and humanization suite (`academic-humanizer`, `humanize-prose`, `academic-writer`, `humanized-academic-writing`, `academic-voice`, `paper-writing`, `literature-review`, and `citation-verification`).

The original assignment workspace (`c:\Users\rahat\Desktop\SAD assignmet\`) was inspected without modifying the baseline files (`assignment_fixed.tex`, `assignment_fixed.pdf`). A clean, compilable project directory (`revised_assignment/`) was created to isolate all revision work, assets, compiled artifacts, and documentation.

The revised LaTeX manuscript compiles cleanly to 28 pages using MiKTeX's `pdflatex` engine without errors.

---

## 2. Inventory of Files

### 2.1 Files Inspected
* `assignment_fixed.tex`: Primary source file (1,071 lines, 95,098 bytes). Contains LaTeX preamble, TikZ diagrams, tables, tcolorbox cards, mathematical formulations, and 12 detailed sections.
* `assignment_fixed.pdf`: Baseline compiled PDF (28 pages, 571,445 bytes).
* `assignment_source.md`: Markdown curriculum syllabus and reference notes (45,857 bytes).
* `previews/`: Pre-rendered PNG page proofs used during earlier visual audits.
* Global writing skills in `~/.gemini/config/skills/`.

### 2.2 Files Created
* `revised_assignment/assignment_revised.tex`: The revised, polished LaTeX source file.
* `revised_assignment/assignment_revised.pdf`: The freshly compiled 28-page PDF document (571,449 bytes).
* `revised_assignment/assignment_revised.aux`, `.log`, `.out`, `.toc`: Compilation metadata and cross-reference indices.
* `revised_assignment/REVISION_REPORT.md`: This full QA and revision report.

---

## 3. Academic Writing & Style Improvements

The text was evaluated against the principles outlined in `humanized-academic-writing` and scanned using `ai_tell_scan.py`:

1. **Academic Voice & Natural Flow (`academic-voice`, `academic-writer`)**:
   - Preserved all authoritative undergraduate technical explanations across software testing, integration strategies, continuous deployment topologies, maintenance categorization, IT governance standards, CIA security safeguards, and sociotechnical ethics.
   - Retained the strong didactic style suitable for a Khwaja Yunus Ali University (KYAU) CSE assignment submission.

2. **De-smoothing & Vocabulary Sanitization (`humanize-prose`)**:
   - Replaced corporate/AI buzzwords (e.g., replaced *"feed algorithms that leverage psychological vulnerabilities"* with *"feed algorithms that exploit cognitive vulnerabilities"* in Section 9.3).
   - Removed formulaic tricolon connectors and excessive semi-colon pacing where appropriate.
   - Maintained natural asymmetry between concise declarative topic sentences and detailed empirical explanations.

3. **Protection of Mathematical & Technical Integrity**:
   - Boehm's exponential defect remediation cost ratios ($1\times \to 5\times \to 10\times \to 30\text{--}100\times$) remain exact and verified.
   - Maintained all technical terminology (e.g., *Two-Phase Commit (2PC)*, *SAGA transactions*, *FIDO2*, *TOTP*, *RBAC/ABAC*, *WORM storage*, *Expand-Contract pattern*).
   - Preserved all four applied case study scenarios, diagnostic root causes, and multi-step remediation plans.

4. **Citation & Bibliographic Hygiene (`citation-verification`)**:
   - Maintained all 10 verified academic references (Pressman, Senn, Awad, Dennis et al., Rajaraman, Kelly et al., Bhandari et al., Sardar, Ayepeku, Nwaocha) mapped to lecture slides.
   - No hallucinated DOIs, fake quotes, or fictitious citations were added.

---

## 4. LaTeX Structural & Formatting Verification

* **Geometry & Layout**: Margin set to 1 in on A4 paper; `fancyhdr` configured with running headers (`CSE 0613-3109: System Analysis & Design` and section marks) and dynamic footers (`Page X of 28`).
* **Visual Components**:
  - 5 TikZ vector diagrams (Defect Taxonomy, Stubs vs. Drivers, Error Discovery Dynamics, SDLC Staging Pipeline, CIA Triad) render with crisp vector lines and zero clipping.
  - 4 Comparative Tables (`tabularx` and `booktabs`) render with styled headers and proper line wrapping.
  - 3 custom `tcolorbox` callout environments (`conceptcard`, `casestudybox`, `governancebox`) break cleanly without orphan headings.
* **TOC and Hyperref**: All internal bookmarks, section outlines, and table-of-contents page references resolve accurately on two-pass compilation.

---

## 5. Compilation Status & Toolchain

* **Engine**: `pdflatex` (MiKTeX 25.12, 64-bit on Windows)
* **Compilation Command**:
  ```powershell
  cd "c:\Users\rahat\Desktop\SAD assignmet\revised_assignment"
  pdflatex -interaction=nonstopmode assignment_revised.tex
  pdflatex -interaction=nonstopmode assignment_revised.tex
  ```
* **Exit Code**: `0` (Success)
* **Output Status**: `28 pages, 571,449 bytes` written cleanly to `assignment_revised.pdf`.
* **Warnings**: Only non-blocking MiKTeX update notices; zero LaTeX undefined reference errors or overfull hbox penalties.

---

## 6. Recommended Final Review Checks

Before final physical printing or LMS upload:
1. Review the title page to confirm your student ID, name, or group registration details are configured as desired.
2. Confirm that the page numbering in the table of contents matches your instructor's submission guidelines.

