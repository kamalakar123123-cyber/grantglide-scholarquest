# GrantGlide – ScholarQuest

A responsive scholarship discovery and application tracking mini-project built with HTML5, CSS3 and vanilla JavaScript.

## Project structure

```text
GrantGlide_ScholarQuest/
├── index.html
├── package.json
├── README.md
├── css/
│   └── style.css
├── js/
│   ├── app.js
│   └── data.js
└── data/
    └── scholarships.json
```

## Features included

- Student profile form (state, category, gender, income, degree, GPA and year)
- Multi-criteria scholarship matching
- Search and category filters
- Scholarship details, award amount, documents and official provider links
- Deadline countdown in days
- Saved scholarships
- Document readiness checklist
- Application pipeline (Bookmarked, Applied, Under Review, Awarded)
- Education funding gap calculator
- English/Telugu assistance preview
- Responsive desktop, tablet and mobile layouts
- Local browser storage using `localStorage`

## Run in Visual Studio Code (recommended)

1. Download and extract `GrantGlide_ScholarQuest.zip`.
2. Open Visual Studio Code.
3. Select **File → Open Folder**.
4. Choose the extracted `GrantGlide_ScholarQuest` folder.
5. In the Explorer, open `index.html`.
6. If Live Server is installed, right-click `index.html` and choose **Open with Live Server**.
7. The website opens in your browser. If you do not have Live Server, open `index.html` directly in Chrome.

No installation or backend server is required for this frontend demo.

## Data and persistence

- `js/data.js` contains the sample scholarship records and document list.
- `js/app.js` contains matching logic, navigation, filters, modals, tracker, checklist and calculator.
- Profile, saved items, application stages and checklist status are stored in this browser's `localStorage`. They remain after refresh on the same browser/device.
- `data/scholarships.json` is a readable copy of the sample data for project documentation.

## Important project note

This is an educational prototype, not an official scholarship portal. Some records are illustrative demo entries. Scholarship eligibility, award values and deadlines can change. Verify all information on the official provider website before applying. The project does not submit applications or upload sensitive certificates to a server.
