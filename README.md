# QALQAN

**CYBERSECURITY SIMULATOR**

QALQAN is an interactive cybersecurity career simulator and business-management game. Start as an intern, investigate security incidents, grow your professional skills, and build a cybersecurity company.

> **Status:** Beta  
> **Author:** Abduali

## Overview

QALQAN combines a SOC investigation simulator with a career progression system and a cybersecurity business tycoon. Players inspect incident evidence, identify security problems, choose defensive responses, and learn from post-mission explanations. Later, they recruit specialists, assign teams, deliver security contracts, manage operating costs, and grow a company.

The game is a self-contained static web application. It runs in a modern browser and does not require a server, account, external API, or build step. Game progress is stored locally in the browser using `localStorage`.

## Features

- **Interactive SOC Simulator** — inspect alerts, logs, endpoints, network indicators, and cloud configuration evidence.
- **Cybersecurity Missions** — scenario-based investigations with evidence collection, linked cases, decisions, outcomes, and learning notes.
- **AI Mentor Simulation** — an in-game mentor-style help chat with scripted cybersecurity explanations; it does not call an external AI service.
- **Career Progression** — advance from Intern through SOC and engineering roles into team leadership and entrepreneurship.
- **Cybersecurity Skill Tree** — develop network, system, security operations, and cloud security skills.
- **Company Management** — establish and expand QALQAN CYBER.
- **Employee Recruitment** — recruit specialists, train them, manage morale and fatigue, and assign staff to projects.
- **Security Contracts** — plan and deliver multi-stage projects for clients with different requirements and risk profiles.
- **Business Economics** — manage cash flow, salaries, operating costs, project expenses, taxes, and business investments.
- **Adaptive Device Detection** — automatic or manual Mobile, Tablet, Laptop, and Desktop display modes.
- **Monochrome Interface** — a high-contrast black-and-white interface.
- **Local Save System** — automatic browser saves, plus in-game save export and import.

## Gameplay

### 1. Career Mode

Begin as an Intern and work through SOC investigations. Explore evidence sources, connect related incidents, identify root causes, choose defensive actions, and review the educational explanation after each completed case. Earn experience, improve skills, and build professional reputation to unlock more demanding work.

### 2. Business Tycoon Mode

Use your experience to establish QALQAN CYBER. Recruit employees with different specializations, form project teams, invest in tools and office capacity, and take on client contracts. Project outcomes affect revenue, expenses, reputation, client satisfaction, and future opportunities.

## Technology Stack

- HTML5
- CSS3 (Grid, Flexbox, media queries, responsive viewport units)
- Vanilla JavaScript
- Browser `localStorage`
- GitHub Pages + GitHub Actions

There are no required third-party JavaScript libraries or runtime services.

## Installation

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Start a new game or continue from the save stored in that browser.

For local development, a simple static HTTP server can also be used, but it is not required. The game has no build step.

## Play Online

The GitHub Pages address for this repository is:

**https://abduali-kaz.github.io/qalqan-cybersecurity-simulator/**

The URL becomes available after the first successful GitHub Pages deployment. The deployment workflow runs automatically on every push to `main` and can also be started manually from the Actions tab.

## Screenshots

Screenshots of the Desktop, Laptop, Tablet, and Mobile layouts will be added here in a future update.

## Author

**Made by Abduali.**

## License

This project is released under the [MIT License](LICENSE). The license applies to the project materials owned by the author. Third-party names, marks, and any third-party materials remain subject to their respective rights and licenses.

## Disclaimer

QALQAN is an educational cybersecurity simulation. Its incident scenarios and decisions are fictional gameplay content intended to teach defensive security concepts, investigation habits, and risk-aware decision-making. It is **not** a tool for carrying out real-world cyberattacks, and it does not provide access to external systems or services.