# My Top Go-To Resources to set-up and organize a computational project with sample project folder layout

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16886694.svg)](https://doi.org/10.5281/zenodo.16886694)

## Here’s how to get started:

1. Set up your project workspace using the freely available **RStudio IDE** by Posit PBC:  
[posit.co/download/rstudio-desktop/](http://posit.co/download/rstudio-desktop/)

2. Follow best practices with the @Carpentries hands-on lesson:  
[https://datacarpentry.github.io/R-ecology-lesson-alternative/introduction-r-rstudio.html](https://datacarpentry.github.io/R-ecology-lesson-alternative/introduction-r-rstudio.html).

3. Explore top principles for project structure from this research article:  
["A quick guide to organizing computational biology projects"](https://pubmed.ncbi.nlm.nih.gov/19649301/).

4. Looking for more power? Try the new **Positron IDE** (integrates VS Code & AI):  
[positron.posit.co](https://positron.posit.co/)

5. Use Git version control from the start: [Get started with Git and GitHub](https://docs.github.com/en/get-started/start-your-journey)  
    - Initialize git in your project folder to track changes, collaborate, and tag milestones for reproducibility.
    - Add a `.gitignore` to exclude large or sensitive files (like `data/raw/`, `.Rhistory`, etc.).
    - Commit scripts, docs, and notes regularly, and host your repo on GitHub for backup, sharing, and citations in papers.

6. Sample project polder layout:
  ```
  project_NAME/
  ├── docs/                  # project documentation
  ├── metadata/              # experimental design, sample sheets, etc.
  ├── data/
  │   ├── raw/               # original data
  │   ├── processed/         # cleaned, analysis-ready data
  │   └── external/          # reference/external data
  ├── src/                   # analysis scripts
  │   ├── 1_ANALYSIS_NAME/
  │   └── 2_ANALYSIS_NAME/
  ├── results/               # results, figures, tables
  │   ├── 1_ANALYSIS_NAME/
  │   └── 2_ANALYSIS_NAME/
  ├── .gitignore             # tells Git which files/folders to ignore
  ├── Manuscript/            # paper drafts, publication figures, tables, supplementary
  ├── Project_analysis.ppt   # analysis slides 
  ├── Meeting_notes.md       # collaborative project meeting notes
  └── README.md              # project overview, objectives and analysis notes
  ```
