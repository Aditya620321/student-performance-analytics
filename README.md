# Student Performance & Attendance Analytics

A beginner **Excel data analytics mini-project** presented as a responsive **HTML + CSS-only dashboard**. Based on a classroom institute assignment using **10 anonymized student records**.

## Live website

After turning on **GitHub Pages**, open:

`https://YOUR_USERNAME.github.io/student-performance-analytics/`

Replace `YOUR_USERNAME` with your GitHub username. The link works after GitHub Pages finishes deployment.

## Project files

| File | Purpose |
| --- | --- |
| `index.html` | Semantic HTML containing the static dashboard, charts, and student records |
| `styles.css` | All dashboard layouts, colors, responsive styling, and CSS bar/donut charts |
| `Student_Performance_Analytics_Portfolio.xlsx` | Excel workbook with data, formulas, report, and original chart |
| `README.md` | Project documentation and publishing instructions |

## What the dashboard shows

- Total number of students
- Average class percentage and highest percentage
- Average attendance metric (as provided in the assignment)
- Student-wise percentage scores
- Subject average marks
- House-wise percentage averages
- Distribution of grades and the full anonymized student data table

## Tools and methods

- **Microsoft Excel:** VLOOKUP, SUM, AVERAGE, AVERAGEIF, IFS, data formatting, and charts.
- **HTML/CSS:** Responsive presentation, static horizontal bar charts, a conic-gradient donut chart, a table, and expandable native `<details>` sections.
- **No JavaScript:** All displayed metrics and charts are a *static snapshot*. They will not automatically update if the workbook changes; update `index.html` to change the numbers.

## Publish on GitHub Pages

1. Create a **public** GitHub repository named `student-performance-analytics`.
2. Upload **all four extracted files to the repository root** (don't upload just the ZIP).
3. In the repository, visit **Settings → Pages**.
4. In **Build and deployment**, select **Deploy from a branch**, select **main** and **/(root)**, then **Save**.
5. Once GitHub Pages shows your published site, open its URL.

## Data and limitations

All students are anonymized. Grades follow the grading rules from the Excel exercise. Attendance is the assignment's provided 0–100 attendance measure. The data set is small (10 students) and is intended for learning, not for making broad educational claims.

## Project contribution

The underlying Excel analysis was completed as an institute assignment. The web presentation was created with AI assistance and can be reviewed and customized as a learning exercise. The site does **not** claim to be an independently built JavaScript application.
