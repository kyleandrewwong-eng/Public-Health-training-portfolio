# Public Health Training Portfolio

This repository contains a personal training portfolio for public health advanced training. It includes:

- A **Weekly Reflections Dashboard** (`index.html`)
- A **Training Requirements Dashboard** (`training_dashboard.html`)

Both are designed to run entirely in the browser and store data locally on your device.

---

## 1. Weekly Reflections Dashboard (`index.html`)

The reflections dashboard is the home page of the site.

### Features

- **Weekly reflections from 9/2/2026 onward**
  - Weeks are grouped into collapsible folders:
    - Feb – May 2026  
    - Jun – Sep 2026  
    - Oct 2026 – Jan 2027
  - Each week opens a structured reflection template:
    - Communicable diseases  
    - Immunisation  
    - Environmental health  
    - Aboriginal team  
    - Project work (with sub‑projects such as “Healthy skins, healthy kids”, “Evaluation of pre‑call programme…”, “Cold chain review”)  
    - Education completed (papers, seminars, meetings, conferences)

- **Auto‑save**
  - Text is saved automatically to your browser’s local storage per week.
  - You can close the browser and return later; content reloads automatically.

- **Template reset**
  - “Reset Template” button restores that week’s reflection to the original section headings if needed.

- **Important dates calendar**
  - Add dates and short descriptions for key events (seminars, exams, project milestones).
  - Events are stored locally and shown in a sorted list.

- **Navigation to training requirements**
  - Top‑right link opens `training_dashboard.html` in a new tab.

---

## 2. Training Requirements Dashboard (`training_dashboard.html`)

This page tracks formal college requirements and deadlines.

### Key Sections

- **Learning contracts & reports**
  - Learning contract (Years 1–3)
  - Learning contract report (Years 1–3)
  - Checkboxes to mark each as complete.

- **Workplace reports**
  - 2 workplace reports in total.
  - Workplace Report 1: submission window 1–29 March 2026.
  - Workplace Report 2: date TBD.

- **Summative assessments**
  - Direct observations (Practical & Professional Skills): 3 total.
  - Professional qualities assessments: 3 total.
  - Oral presentations (summative): 2 total.
  - Each item has individual checkboxes and an auto‑updating “0/3” or “0/2” counter.

- **Key dates & deadlines**
  - Workplace report submission window (1–29 March 2026)
  - Weekly seminars (24 April – 28 August 2026)
  - Advanced training research project dates (15 June, 15 September)
  - Exam application period (June) and exam date (October)
  - Monthly webinars placeholder

- **Additional requirements**
  - Application to commence
  - Research project
  - Aboriginal, Torres Strait Islander & Māori cultural competence course/certificate

### Deadline highlighting

- Rows and timeline items change colour based on how close the deadline is:
  - Amber: due within 4 weeks.
  - Red: due within 2 weeks or currently in an active submission window.
- Completed items (when their checkbox is ticked) are no longer highlighted.

- All checkbox states are stored in the browser’s local storage.

---

## 3. How to run locally

1. Download or clone this repository.
2. Open `index.html` in a web browser (e.g. Chrome, Edge, Firefox).
3. Ensure `training_dashboard.html` is in the **same folder** so the “College Requirements” link works.

No server or backend is required; everything runs client‑side.

---

## 4. GitHub Pages deployment

This repository is suitable for static hosting (e.g. GitHub Pages):

1. In the repository settings, enable GitHub Pages.
2. Choose:
   - Source: deploy from the `main` branch
   - Folder: `/ (root)`
3. After deployment, visit the provided URL.  
   - The reflections dashboard will load at `/` (from `index.html`).
   - The training requirements dashboard will be accessible via the “College Requirements” link.

---

## 5. Future ideas

Possible future enhancements:

- Add authentication and cloud storage (e.g. Firebase) so reflections and checklists sync across devices.
- Export reflections or requirements to PDF/CSV for submission or backup.
- Wrap the site as a desktop app using a framework like Electron or Tauri.

