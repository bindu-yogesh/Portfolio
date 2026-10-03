# Bindu Yogesh --- Personal Portfolio

A professional, responsive personal portfolio website showcasing my
projects, technical skills, open-source contributions, education, and
problem-solving journey.

## Overview

This portfolio is designed to present my work and technical profile in a
clean, recruiter-friendly format. It highlights my focus on software
development, Android development, data structures and algorithms, and
open-source contributions.

Live Demo : https://bindu-yogesh-portfolio.vercel.app/

## Features

-   Clean, minimal, professional design
-   Responsive layout for desktop and mobile
-   Sticky navigation bar with glass/blur effect
-   Smooth scrolling between sections
-   Animated hero section
-   Scroll-triggered reveal animations
-   Animated statistics/count-up effect
-   Interactive project cards with subtle 3D tilt
-   Cursor-following spotlight effect
-   Responsive mobile navigation
-   Reduced-motion accessibility support
-   Resume links throughout the portfolio
-   Project cards generated dynamically from JavaScript data

## Sections

The portfolio contains:

1.  **Hero** --- Introduction, internship availability, GitHub,
    LinkedIn, and key statistics
2.  **About** --- Interests and background
3.  **Skills** --- Languages, Android, Web, Backend & Databases, and
    Tools
4.  **Projects** --- Selected Android, web, AI, and practice projects
5.  **Open Source** --- NexusAI contribution and pull request
6.  **Education** --- Academic background and certifications
7.  **Contact** --- Email, LinkedIn, GitHub, LeetCode, and Resume

## Featured Projects

### Kisan Suvidha

A responsive agricultural web platform providing farmers with accessible
information and farming resources, including weather, market
information, and agricultural resources.

-   **Tech:** HTML5, CSS3, JavaScript
-   **Repository:** https://github.com/bindu-yogesh/kisan-suvidha
-   **Live:** https://kisan-suvidha.vercel.app

### Expense Tracker

An offline-first Android application for managing expenses, budgets,
categories, and recurring transactions. It uses Kotlin, Jetpack Compose,
MVVM, Room, and Kotlin Flow.

-   **Status:** Under development
-   **Tech:** Kotlin, Jetpack Compose, Room, MVVM, WorkManager
-   **Repository:** https://github.com/bindu-yogesh/Expense-Tracker-app

### LYNK (iTantra)

A multilingual Android communication system supporting speech-to-text
and text-to-speech across 10 languages. It supports communication over
Wi-Fi or Bluetooth using socket-based messaging, acknowledgements,
retries, reconnection, and priority handling for emergency messages.

-   **Tech:** Kotlin, Android, STT/TTS, Sockets
-   **Repository:** https://github.com/bindu-yogesh/LYNK

### AI Interview Simulator

A web application for practising mock interviews with AI-generated
questions and feedback.

-   **Tech:** JavaScript, AI
-   **Live:** https://ai-interview-stimulator-ebon.vercel.app

### LeetCode Pattern Tracker

A web application for structured algorithm practice. Problems are logged
and tagged by pattern, with views for pattern coverage, gaps, and
streaks.

-   **Tech:** JavaScript, Web
-   **Repository:**
    https://github.com/bindu-yogesh/leetcode-pattern-tracker-
-   **Live:** https://leetcode-pattern-tracker-sable.vercel.app

### Hand Connect

A project repository containing the source code on GitHub.

-   **Repository:** https://github.com/bindu-yogesh/hand-connect-

### Chess Game

A browser-based chess game with an interactive board and rule-based
gameplay.

-   **Tech:** HTML, CSS, JavaScript
-   **Repository:** https://github.com/bindu-yogesh/chessGame
-   **Live:** https://chess-game-ten-pi.vercel.app

### Web Drawing App

A browser-based drawing application with an interactive canvas for
sketches and illustrations.

-   **Tech:** HTML, CSS, JavaScript
-   **Repository:** https://github.com/bindu-yogesh/web-drawing
-   **Live:** https://web-drawing-murex.vercel.app

## Open Source

The portfolio highlights a contribution to **NexusAI**.

The contribution addressed error feedback in the chat interface by
adding toast notifications for backend streaming errors, along with
improvements to toast positioning and display duration.

-   Pull Request: https://github.com/P-r-e-m-i-u-m/NexusAI/pull/61
-   Repository: https://github.com/P-r-e-m-i-u-m/NexusAI

## Tech Stack

### Frontend

-   HTML5
-   CSS3
-   Vanilla JavaScript
-   CSS Grid
-   Flexbox
-   CSS Custom Properties

### Typography

-   Hanken Grotesk
-   Google Fonts

### Development

-   Git
-   GitHub
-   VS Code
-   Android Studio

## Animations & Interactions

The portfolio uses lightweight CSS and JavaScript interactions rather
than a large animation framework.

-   Hero entrance animation
-   Moving background glow
-   Scroll reveal animations using `IntersectionObserver`
-   Animated statistics
-   Project card 3D tilt on desktop
-   Interactive hero buttons
-   Cursor spotlight on devices with a fine pointer
-   Open-source contribution timeline animation
-   Sticky header state transition

Animations are disabled or reduced when the user's system preference is
set to `prefers-reduced-motion`.

## Project Structure

``` text
portfolio/
├── index.html
├── Bindu_Yogesh_Resume.pdf
└── README.md
```

The portfolio is intentionally lightweight and does not require a
frontend framework or build system.

## Run Locally

Clone the repository:

``` bash
git clone <your-repository-url>
cd <your-repository-folder>
```

Then open `index.html` in a browser.

For a better local development experience, use a local server such as VS
Code Live Server.

## Updating Projects

Projects are maintained in a JavaScript array inside `index.html`.

``` javascript
const projects = [
  {
    kind: "Android application",
    name: "Project Name",
    desc: "Project description.",
    tags: ["Kotlin", "Android"],
    code: "https://github.com/...",
    live: "https://..."
  }
];
```

Add or modify an object in the array to update the Projects section.

## Accessibility

The portfolio includes:

-   Semantic HTML structure
-   Visible keyboard focus states
-   Accessible mobile navigation attributes
-   `aria-label` and `aria-expanded` where appropriate
-   Reduced-motion support
-   Decorative animation elements marked as hidden from assistive
    technologies

## Responsive Design

The layout adapts to smaller screens using CSS media queries.

On mobile:

-   Navigation becomes a collapsible menu
-   Project and content grids become single-column layouts
-   Education details stack vertically
-   Open-source timeline changes to a vertical layout
-   Cursor spotlight is disabled on touch devices

## Customization

The main visual theme can be changed through CSS variables near the
beginning of `index.html`.

``` css
:root {
  --bg: #FAF9F6;
  --surface: #FFFFFF;
  --line: #E7E5E0;
  --text: #0F172A;
  --muted: #64748B;
  --accent: #4F46E5;
}
```

## License

This portfolio is a personal project by Bindu Yogesh.

The code can be used as inspiration, but personal information, links,
project descriptions, and branding belong to the portfolio owner.
