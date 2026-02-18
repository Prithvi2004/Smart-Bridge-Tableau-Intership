# Smart Bridge Tableau Internship Project

A data visualization project focused on **Indian Union Budget analysis** using **Tableau** with a lightweight **Flask** web integration.

## Repository Link

- GitHub: https://github.com/Prithvi2004/Smart-Bridge-Tableau-Intership

## Project Overview

This project presents insights from Indian Union Budget data (FY 2021–22 to FY 2023–24) through an interactive Tableau dashboard.  
The dashboard is integrated into a Flask web application so it can be viewed from a browser-based interface.

## Live Dashboard & Demo

- Tableau Public Dashboard: https://public.tableau.com/views/UnionBudget_17711331782220/Dashboard1?:embed=yes&:showVizHome=no
- Project Demo Video: https://drive.google.com/file/d/1p-WN-HVotYTnmvzjE4CRtU4gdcPbVVAQ/view?usp=sharing

## Tech Stack

- Tableau (dashboard/story creation)
- Flask (web app integration)
- HTML/CSS (frontend page)

## Current Web App Routes

Defined in `Flask/app.py`:

- `/` → Home page with embedded Tableau dashboard
- `/about`
- `/dashboard`
- `/story`
- `/insights`

> Note: In the current repository state, `index.html` is present in templates and fully functional for the dashboard embed.

## Project Structure

```text
Smart-Bridge-Tableau-Intership/
├── 1. Assignment/
├── 2. Ideation Phase/
├── 3. Requirement Analysis/
├── 4. Project Design Phase/
├── 5. Project Planning Phase/
├── 6. Project Executable Files/
│   ├── Dataset/
│   │   └── Indian Union Budget FY 21-22 till 23-24.xls
│   ├── Flask/
│   ├── Tableau File/
│   └── Tableau dashboard Public URL.txt
├── 7. Functional and Performance Testing/
├── 8. Doc and Demo/
│   └── video_link.txt
└── Flask/
    ├── app.py
    ├── requirements.txt
    ├── static/
    └── templates/
```

## Run Locally (Flask)

1. Clone the repository:

   ```bash
   git clone https://github.com/Prithvi2004/Smart-Bridge-Tableau-Intership.git
   cd Smart-Bridge-Tableau-Intership/Flask
   ```

2. (Optional) Create and activate a virtual environment:

   ```bash
   python -m venv .venv
   .venv\Scripts\activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the app:

   ```bash
   python app.py
   ```

5. Open in browser:
   - http://127.0.0.1:5000/

## Requirements

From `Flask/requirements.txt`:

- Flask==3.0.0
- gunicorn==21.2.0

## Author

- **Madivada Prithvi**

---
