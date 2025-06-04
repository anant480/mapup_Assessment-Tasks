# mapup_Assessment-Tasks
# Calgary HTTP Log Analysis Assessment

## Overview
This repository contains the solution to the Calgary HTTP Dataset analysis assessment. The goal was to analyze one year of HTTP request logs from the University of Calgary's Computer Science web server, extracting insights and answering specific questions.

---

## Folder Structure
- `analysis.ipynb` : Jupyter Notebook with all code, analysis, and output results.
- `analysis.html` : Exported HTML version of the notebook for easy viewing.
- `transcript.txt` : Full transcript of the explanation video submitted.
- `README.md` : This file, containing notes and overview.

---

## Approach and Tools
- Data loaded and parsed from compressed `.gz` Apache log file.
- Used Python with `pandas`, `re`, and `datetime` libraries for data cleaning and analysis.
- Applied regex to parse log lines, converted timestamps to datetime objects, and extracted relevant fields.
- Analysis includes counts, groupings, and filtering based on the assessment tasks.
- Results are printed and visualized within the Jupyter notebook.
  
---

## Assumptions and Notes
- Malformed or incomplete log lines were skipped during parsing.
- Bytes field missing or non-numeric values were treated as zero.
- Date formatting follows the specified `dd-MMM-yyyy` style.
- Only logs from July 1995 were included in bandwidth per day calculation as requested.
- The transcript corresponds to the video walkthrough explaining methodology and code.

---

## Challenges
- Parsing large text files efficiently.
- Handling inconsistent or missing data in log entries.
- Ensuring correct datetime parsing with timezones.
- Managing memory during group-by operations on large datasets.

---

## How to Run
1. Open `analysis.ipynb` in Jupyter Notebook.
2. Run all cells sequentially to reproduce the results.
3. Alternatively, view `analysis.html` for a static report.

---

## Contact
For questions or clarifications, please reach out at:  
**Email:** anantnarayan480@gmail.com  
**Phone:** +91 9198466233

---

*Thank you for the opportunity to complete this assessment!*

