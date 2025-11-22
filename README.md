# STAT 184: A Moment of Mastery (Activity 14 Version Control)

This repository contains the required files and evidence for the STAT 184 assignment demonstrating mastery of version control workflows using Git and GitHub.

---

### 1. What This Repository Is About (Project Summary)

This project contains the complete, reproducible analysis for the Moment of Mastery (Activity #14). The analysis covers three main components:
1.  **Armed Forces Data Redux:** A contingent analysis showing the lack of independence between Rank and Sex among Army and Navy officers.
2.  **Baby Name Popularity:** A visualization tracking the popularity trends of the names 'Mary', 'Jennifer', and 'Liam' over time.
3.  **Box Problem:** A plot of the volume function for a box made from 36 x 48 inch paper, identifying the optimal cutout size 'x' and maximum volume.

### 2. Where the Data Comes From

* [cite_start]**Armed Forces Data:** Data is derived from the **DMDC Active-Duty Military Personnel Master File (June 2025)**[cite: 120]. [cite_start]The raw data is embedded directly into the QMD file using `dput()` for 100% self-containment[cite: 6]. [cite_start]The rank titles were scraped from a publicly accessible URL[cite: 99].
* [cite_start]**Baby Names Data:** This uses the standard **`babynames` R package dataset**[cite: 79].

### 3. Current Plan for the Project

The core project content is complete and finalized. The primary goal of this repository is to demonstrate proper Version Control System (VCS) practices.

* **Status:** All content has been finalized and merged into `main`.
* **Next Steps:** Finalize Issues documentation and submit the repository URL.

### 4. How the Repository is Organized

| File Name | Purpose |
| :--- | :--- |
| `MOM_Project.qmd` | **Source Code:** The Quarto document used to generate the report. Adheres to Tidyverse coding style and reproducibility standards. |
| `MOM_Project.pdf` | **Final Output:** The PDF report submitted for Activity #14. |
| `PROJECT_PLAN.md` | **Documentation:** The required file outlining the goals, needs, and steps for both the project and the VCS workflow. |
| `.gitignore` | Tells Git to ignore operating system files (like `.DS_Store`). |

### 5. Contact Information

* [cite_start]**Author:** Kyle Spaulding [cite: 2]
* **Course:** STAT 184
* **GitHub Username:** `spauldingk`

***

## 💻 Resuming Phase 3 Workflow

Once you have saved this content into your local `README.md` file in VS Code, proceed with the Git commands to complete the submission:

1.  **Commit and Push the updated $\text{README}$:**
    ```bash
    git add README.md
    git commit -m "DOCS: Final update to README with all required project details."
    ```
    ```bash
    git push origin main
    ```
2.  **Complete the Issues (Web Interface):** Create Issue 1 and Issue 2, apply the **`documentation`** label, and **Close** both, linking Issue 2 to the commit you just made.

This completes the entire assignment to the highest standard!