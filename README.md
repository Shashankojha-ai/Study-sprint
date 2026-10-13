# 📚 StudySprint

### Your syllabus. Your strategy. Your progress.

StudySprint is a lightweight study-planning web application that helps students organize their syllabus, create daily study schedules, and track their academic progress.

Instead of feeling overwhelmed by a large syllabus, students can break chapters into manageable study sessions and work toward completing them one day at a time.

**Plan smarter. Study consistently. Track your progress.**

---

## ✨ Features

- 📖 **Syllabus Management** — Add and organize chapters across different subjects.
- ⏱️ **Time Estimation** — Assign estimated study hours to each chapter.
- 📅 **Automatic Scheduling** — Generate a daily study plan based on available study hours.
- ✂️ **Session Splitting** — Divide longer chapters into smaller sessions.
- ✅ **Progress Tracking** — Mark sessions as complete and monitor overall progress.
- 🔄 **Rescheduling** — Rearrange unfinished sessions across available study days.
- 📊 **Progress Dashboard** — View chapters, sessions, completed tasks, and completion percentage.
- 💾 **Automatic Saving** — Preserve your syllabus and progress using browser local storage.
- 📱 **Responsive Design** — Use the application on desktop and mobile devices.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Styling and responsive layout |
| JavaScript | Scheduling and application functionality |
| Local Storage | Saving user data in the browser |

StudySprint requires no external libraries, paid APIs, database, or backend server.

## 🚀 Getting Started

### Prerequisites

You need:
- A modern web browser.
- Git, if you want to clone the repository.
- A code editor such as Visual Studio Code (optional).

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/Shashankojha-ai/StudySprint.git
```

**2. Open the project directory**

```bash
cd StudySprint
```

**3. Launch the application**

Open `index.html` in your browser.

Alternatively, open the folder in Visual Studio Code and use the Live Server extension.

No additional installation or configuration is required.

> Note: The repository URL above assumes that your repository is named `StudySprint`. Update it if your actual repository uses a different name.

## 📖 How to Use

### 1. Add Chapters
Enter a subject, chapter name, difficulty level, and estimated study time.

### 2. Set Daily Availability
Choose how many hours you can dedicate to studying each day.

### 3. Generate Your Plan
Generate a schedule that distributes your chapters across available study days.

### 4. Complete Study Sessions
Mark each session as completed when you finish studying.

### 5. Track Progress
Monitor your completed sessions and overall syllabus completion percentage.

### 6. Reschedule Unfinished Sessions
Move unfinished sessions to available study days when your schedule changes.

### 7. Manage Your Syllabus
Delete chapters you no longer need or reset your planner when starting over.

## 🧠 How the Scheduling Works

StudySprint uses a straightforward scheduling algorithm:

1. Collect the estimated study time for each chapter.
2. Read the user's available study hours per day.
3. Divide longer chapters into smaller sessions when necessary.
4. Assign sessions to consecutive study dates.
5. Track completion independently for each session.

The schedule is an estimate, not a guarantee of how long studying will take.

The current version does not automatically optimize schedules around examination dates, chapter prerequisites, or learning performance.

## 📁 Project Structure

```text
StudySprint/
├── index.html    # HTML, CSS, and JavaScript
└── README.md     # Project documentation
```

The application uses a single HTML file to keep the project lightweight and easy to understand.

## 💾 Data Storage and Privacy

StudySprint stores its data locally in the browser using `localStorage`.

- No account or registration is required.
- No backend server is needed.
- Study data is not automatically synchronized between devices.
- Clearing browser storage may permanently remove saved progress.

**Important:** Generating a new study plan replaces the existing sessions. Export or otherwise preserve important information before regenerating a plan if you need to keep your progress.

## 🔮 Future Improvements

Potential features for future versions include:

- [ ] Dedicated daily study view
- [ ] Study streaks and achievements
- [ ] Subject-specific filters and colours
- [ ] Examination deadlines and countdowns
- [ ] Difficulty-based scheduling
- [ ] Calendar and timetable views
- [ ] Export and import of study plans
- [ ] Built-in study timer
- [ ] Study reminders and notifications
- [ ] Improved revision scheduling
- [ ] Optional cloud synchronization

These are planned improvements, not features currently implemented.

## 🤝 Contributing

Contributions, bug reports, and feature suggestions are welcome.

To contribute:

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Test your changes.
5. Submit a pull request describing your improvements.

Please keep contributions focused, readable, and consistent with the project's lightweight architecture.

## 👨‍💻 Author

**Shashank Ojha**

- GitHub: [@Shashankojha-ai](https://github.com/Shashankojha-ai)

## 📄 License

The project's license has not yet been specified.

Add a `LICENSE` file and update this section when you choose a license.

---

**StudySprint — Make every study session count. 🚀**
