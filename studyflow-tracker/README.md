# StudyFlow — Habit & Study Assignment Tracker

A clean, modular front-end web app built with **HTML5**, **Tailwind CSS**, and **Vanilla JavaScript** for tracking daily study habits, 7-day consistency streaks, Pomodoro focus sessions, and coursework deadlines.

## Project Folder Structure

```text
studyflow-tracker/
├── index.html       # Main application layout and UI sections
├── css/
│   └── styles.css   # Custom styles and Light/Dark mode theme rules
├── js/
│   └── app.js       # State management, Pomodoro timer, localStorage & CSV/JSON export
└── README.md        # Setup and customization guide
```

## How to Open & Edit in VS Code

1. **Unzip** `studyflow-tracker.zip` to a folder on your computer.
2. Open **VS Code** and select **File → Open Folder...**, then choose the `studyflow-tracker` folder.
3. To preview changes live while editing:
   - Install the **Live Server** extension in VS Code, right-click `index.html`, and select **Open with Live Server**, **or**
   - Double-click `index.html` to open it directly in any web browser.

## Easy Places to Customize

- **Course Subjects**: Edit the `<select id="subjectSelect">` and `<select id="subjectFilterSelect">` options in `index.html` to add your own semester subjects.
- **Starter Habits & Tasks**: Edit `getDefaultState()` inside `js/app.js`.
- **Theme Colors**: Adjust the `.light-mode` overrides in `css/styles.css` or the Tailwind utility classes in `index.html`.
