<div align="center">

# FocusFlow

### Modern Productivity Workspace Built with HTML, CSS & JavaScript

A clean, lightweight productivity platform that combines task management, time tracking, note-taking, goal planning, and productivity tools into a single unified interface.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://www.w3.org/TR/CSS/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)

</div>

---

## Overview

FocusFlow is a modern productivity workspace designed to help users organize daily activities from a single dashboard.

Instead of switching between multiple applications, FocusFlow combines task management, note-taking, Pomodoro sessions, goal tracking, and quick utilities into one seamless experience.

The project is built entirely with **HTML, CSS, and JavaScript**, requiring no backend or external frameworks.

---

## Features

| Module | Description |
|----------|-------------|
| Dashboard | Central workspace for all productivity tools |
| Pomodoro Timer | 25/5 productivity timer with session tracking |
| Task Manager | Create, organize, and manage daily tasks |
| Notes | Lightweight note-taking workspace |
| Goal Tracker | Track long-term goals and progress |
| Calculator | Quick calculations without leaving the workspace |
| User Profile | Personal dashboard and settings |
| Responsive UI | Works across desktop and mobile devices |
| Dark Theme | Modern glassmorphism interface with animations |

---

## Screenshots

> Add screenshots inside the `screenshots/` folder.

```
screenshots/
│
├── home.png
├── dashboard.png
├── tasks.png
├── pomodoro.png
├── notes.png
└── goals.png
```

Example:

```markdown
<p align="center">

<img src="screenshots/dashboard.png" width="900"/>

</p>
```

---

## Tech Stack

### Frontend

- HTML5
- CSS3
- JavaScript (ES6)

### UI

- Glassmorphism
- CSS Animations
- CSS Variables
- Flexbox
- CSS Grid

### Fonts

- Inter
- Playfair Display

---

## Project Structure

```text
FocusFlow/
│
├── index.html          # Login
├── 2.html              # Landing Page
├── 3.html              # Dashboard
├── 4.html              # Task Manager
├── 5.html              # Pomodoro Timer
├── 6.html              # Notes
├── 7.html              # Goal Tracker
├── 8.html              # Calculator
│
├── about1.html
├── contact1.html
├── profile1.html
│
├── css/
├── js/
├── assets/
├── screenshots/
└── README.md
```

---

## Architecture

```text
                User

                  │

                  ▼

          Landing Page

                  │

                  ▼

         Productivity Dashboard

        ┌────────┼────────┐
        │        │        │
        ▼        ▼        ▼

   Task App   Pomodoro   Notes

        │        │        │

        ├────────┼────────┤

                 ▼

          Goal Tracker

                 ▼

           Calculator
```

---

## Getting Started

Clone the repository

```bash
git clone https://github.com/your-username/FocusFlow.git
```

Navigate to the project

```bash
cd FocusFlow
```

Open the application

```bash
open index.html
```

or simply double-click **index.html**.

---

## Future Enhancements

- User Authentication
- Cloud Sync
- Calendar Integration
- Habit Tracker
- Expense Tracker
- Notifications
- Offline Support (PWA)
- AI Productivity Assistant
- Data Export & Backup

---

## Contributing

Contributions are welcome.

```bash
Fork the repository

Create a new branch

git checkout -b feature/new-feature

Commit changes

git commit -m "Add new feature"

Push

git push origin feature/new-feature
```

Finally, open a Pull Request.

---

## License

Distributed under the MIT License.

---

<div align="center">

Made with HTML, CSS & JavaScript.

If you found this project useful, consider giving it a ⭐.

</div>
