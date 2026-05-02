# Frontend Development Mentorship — 12 Week Curriculum

> **From zero to junior frontend developer in 12 weeks.** A structured, project-based mentorship curriculum built around [freeCodeCamp](https://www.freecodecamp.org/), with weekly projects, mentor check-ins, and a portfolio-ready outcome.

## Repo Contents

- 📘 **[README.md](./README.md)** — The full 12-week curriculum (this file)
- ✅ **[progress-tracker.md](./progress-tracker.md)** — Weekly checklist the mentee ticks off as they go
- 🗒️ **[check-ins/](./check-ins/)** — One file per weekly mentor check-in
- 🛠️ **[projects/](./projects/)** — Index of all weekly projects with live links and repos
- 📚 **[resources/](./resources/)** — Curated supplementary resources

## How to Use This Repo

**If you're the mentee:** Fork this repo. Update `progress-tracker.md` weekly. Create a new file in `check-ins/` after each Saturday session. Add your project links to `projects/README.md` as you complete them. Commit often — your fork becomes a public artifact of your learning journey.

**If you're a mentor:** Use this as a starting point and adapt freely. The check-in templates and assessment rubric are designed to make weekly sessions productive without over-planning.

---

## Table of Contents

1. [Overview](#overview)
2. [Prerequisites & Setup](#prerequisites--setup)
3. [How This Curriculum Works](#how-this-curriculum-works)
4. [Weekly Time Commitment](#weekly-time-commitment)
5. [Phase 1 — Foundations (Weeks 1–4)](#phase-1--foundations-weeks-14)
6. [Phase 2 — JavaScript (Weeks 5–8)](#phase-2--javascript-weeks-58)
7. [Phase 3 — React & Modern Tooling (Weeks 9–11)](#phase-3--react--modern-tooling-weeks-911)
8. [Phase 4 — Capstone & Portfolio (Week 12)](#phase-4--capstone--portfolio-week-12)
9. [Mentor Check-in Template](#mentor-check-in-template)
10. [Assessment Rubric](#assessment-rubric)
11. [Beyond the Curriculum](#beyond-the-curriculum)

---

## Overview

By the end of this 12-week program, the mentee will be able to:

- Build responsive, accessible websites from a design or written spec using semantic HTML and modern CSS (Flexbox, Grid).
- Write clean, modern JavaScript (ES6+) and manipulate the DOM without a framework.
- Build single-page applications using React, including state management, hooks, and API consumption.
- Use Git, GitHub, and the command line confidently.
- Deploy projects to the web (Netlify / Vercel / GitHub Pages).
- Have a polished portfolio with at least 4 deployed projects and a personal site.

**Primary resource:** freeCodeCamp's *Responsive Web Design*, *JavaScript Algorithms and Data Structures*, and *Front End Development Libraries* certifications.

**Secondary resources:** MDN Web Docs, JavaScript.info, official React docs, YouTube channels (Kevin Powell, Web Dev Simplified, Fireship), and selected articles linked weekly.

---

## Prerequisites & Setup

The mentee should have these installed and ready **before Week 1**:

- [ ] A working laptop (Windows, macOS, or Linux) with at least 8GB RAM
- [ ] [Visual Studio Code](https://code.visualstudio.com/) with extensions: *Prettier*, *Live Server*, *ESLint*, *GitLens*
- [ ] [Google Chrome](https://www.google.com/chrome/) (we'll use DevTools heavily)
- [ ] [Git](https://git-scm.com/) installed and configured with their name and email
- [ ] A [GitHub](https://github.com/) account with profile photo and bio filled in
- [ ] A [freeCodeCamp](https://www.freecodecamp.org/) account
- [ ] A notebook (physical or digital — Notion / Obsidian) for daily notes
- [ ] [Node.js LTS version](https://nodejs.org/) installed (we'll use it from Week 9, but install early)

**Day 0 task:** Have the mentee push a `hello-world.html` file to a public GitHub repo. This validates the entire toolchain works before any real learning starts.

---

## How This Curriculum Works

Each week follows the same rhythm:

| Day        | Focus                                              |
|------------|----------------------------------------------------|
| Mon–Thu    | freeCodeCamp lessons + reading                     |
| Friday     | Mini-project applying the week's concepts          |
| Saturday   | 1-hour mentor check-in (live or async)             |
| Sunday     | Rest, review notes, prep questions for next week   |

Every project gets pushed to GitHub in its own repo. The mentee should write a real README for each one — this is non-negotiable, as it builds the portfolio in parallel with the learning.

---

## Weekly Time Commitment

- **Self-study:** 12–15 hours/week
- **Project work:** 3–5 hours/week
- **Mentor check-in:** 1 hour/week
- **Total:** ~18 hours/week

If the mentee can only commit 10 hours/week, stretch the curriculum to 16 weeks by spending two weeks on Weeks 6, 7, 9, and 10.

---

## Phase 1 — Foundations (Weeks 1–4)

### Week 1 — HTML Foundations & The Web

**Learning objectives:**
- Understand how the web works at a high level (client/server, HTTP, DNS, browsers).
- Write semantic HTML5 confidently.
- Use the command line for basic navigation (`cd`, `ls`, `mkdir`, `touch`).
- Use Git locally (`init`, `add`, `commit`, `status`, `log`).

**freeCodeCamp:**
- [ ] *Responsive Web Design* → "Learn HTML by Building a Cat Photo App"
- [ ] *Responsive Web Design* → "Learn Basic HTML by Building a Cat Photo App" (legacy version, optional review)

**Supplementary:**
- [ ] [MDN — HTML basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)
- [ ] Watch: *How the Internet Works in 5 Minutes* (YouTube)
- [ ] Read: [GitHub's "Hello World" guide](https://docs.github.com/en/get-started/quickstart/hello-world)

**Weekly project — "About Me" page:**
A single-page personal site with semantic HTML only (no CSS yet). Must include: header, nav, main with sections (about, skills, hobbies, contact), footer, at least one image with `alt` text, and one external link. Push to GitHub. Repo name: `about-me`.

**Mentor check-in questions:**
- Walk me through your HTML file. Why did you use `<section>` here vs `<div>`?
- What does "semantic" mean and why does it matter?
- Show me how you committed your changes in Git. What does `git status` tell you?

---

### Week 2 — CSS Fundamentals

**Learning objectives:**
- Understand the box model deeply (content, padding, border, margin).
- Use selectors (element, class, ID, descendant, pseudo-classes).
- Apply colors, fonts, spacing, and basic layout with `display`.
- Understand the cascade and specificity.

**freeCodeCamp:**
- [ ] *Responsive Web Design* → "Learn Basic CSS by Building a Cafe Menu"
- [ ] *Responsive Web Design* → "Learn CSS Colors by Building a Set of Colored Markers"

**Supplementary:**
- [ ] [MDN — CSS Box Model](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model)
- [ ] Watch: Kevin Powell — *CSS specificity made easy*
- [ ] Play: [CSS Diner](https://flukeout.github.io/) (entire game)

**Weekly project — Style the "About Me" page:**
Add CSS to last week's repo. Requirements: custom color palette (3–5 colors, document them in the README), at least one Google Font, hover states on links, consistent spacing system. Use a separate `styles.css` file.

**Mentor check-in questions:**
- Why does `.nav a` have higher specificity than `a`?
- What happens if two rules with the same specificity target the same element?
- Show me how you'd inspect an element in Chrome DevTools and override its styling live.

---

### Week 3 — Responsive Design, Flexbox & Grid

**Learning objectives:**
- Build mobile-first responsive layouts.
- Use Flexbox for 1-dimensional layouts.
- Use CSS Grid for 2-dimensional layouts.
- Use media queries.

**freeCodeCamp:**
- [ ] *Responsive Web Design* → "Learn CSS Flexbox by Building a Photo Gallery"
- [ ] *Responsive Web Design* → "Learn CSS Grid by Building a Magazine"
- [ ] *Responsive Web Design* → "Learn Responsive Web Design by Building a Piano"

**Supplementary:**
- [ ] Play: [Flexbox Froggy](https://flexboxfroggy.com/) (all levels)
- [ ] Play: [Grid Garden](https://cssgridgarden.com/) (all levels)
- [ ] Read: [CSS-Tricks — A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [ ] Read: [CSS-Tricks — A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

**Weekly project — Recipe page clone:**
Pick a recipe from any food blog and rebuild it. Must be fully responsive (test on 320px, 768px, and 1440px widths). Use Flexbox AND Grid in meaningful ways. Push to GitHub as `recipe-page` and deploy via GitHub Pages.

**Mentor check-in questions:**
- When would you reach for Flexbox vs Grid?
- What's "mobile-first" and why is it the default?
- Show me your media queries — explain your breakpoint choices.

---

### Week 4 — Accessibility, Forms & The First Cert

**Learning objectives:**
- Build accessible forms.
- Understand ARIA basics and screen-reader implications.
- Complete the first freeCodeCamp certification.

**freeCodeCamp:**
- [ ] *Responsive Web Design* → "Learn Accessibility by Building a Quiz"
- [ ] *Responsive Web Design* → "Learn HTML Forms by Building a Registration Form"
- [ ] **Build all 5 certification projects** (Survey Form, Tribute Page, Technical Documentation Page, Product Landing Page, Personal Portfolio Webpage)
- [ ] 🏆 **Earn the Responsive Web Design certification**

**Supplementary:**
- [ ] [The A11Y Project — Checklist](https://www.a11yproject.com/checklist/)
- [ ] Watch: *What is ARIA even for?* by Heydon Pickering

**Weekly project:**
The 5 freeCodeCamp certification projects ARE the project this week. Each one should be in its own GitHub repo with a real README and deployed live.

**Mentor check-in questions:**
- Show me one of your projects with screen reader simulation. What works? What doesn't?
- Why is `<label>` important for form accessibility?
- What did you find hardest about the cert projects?

> 🎯 **End of Phase 1 milestone:** 6+ deployed projects, freeCodeCamp Responsive Web Design certification, comfortable with HTML/CSS/Git/GitHub/CLI basics.

---

## Phase 2 — JavaScript (Weeks 5–8)

### Week 5 — JavaScript Basics

**Learning objectives:**
- Understand variables, data types, operators, and control flow.
- Write functions (declaration, expression, arrow).
- Use arrays and objects.

**freeCodeCamp:**
- [ ] *JavaScript Algorithms and Data Structures* → "Learn JavaScript by Building a Role Playing Game"
- [ ] *JavaScript Algorithms and Data Structures* → "Learn Form Validation by Building a Calorie Counter" (start)

**Supplementary:**
- [ ] [JavaScript.info](https://javascript.info/) — Chapters 2.1–2.10
- [ ] Watch: *JavaScript in 100 Seconds* (Fireship)

**Weekly project — Tip Calculator:**
A page with inputs for bill amount, tip %, and number of people. Outputs tip per person and total per person. No frameworks — vanilla JS only. Push to GitHub, deploy.

**Mentor check-in questions:**
- Explain `let`, `const`, and `var`. Which do you reach for and why?
- What's the difference between `==` and `===`?
- Walk me through your tip calculator's logic, line by line.

---

### Week 6 — DOM Manipulation & Events

**Learning objectives:**
- Select and modify DOM elements with JavaScript.
- Handle events (click, input, submit, keyboard).
- Understand the event loop at a beginner level.

**freeCodeCamp:**
- [ ] *JavaScript Algorithms and Data Structures* → "Learn Form Validation by Building a Calorie Counter" (finish)
- [ ] *JavaScript Algorithms and Data Structures* → "Learn Basic String and Array Methods by Building a Music Player"

**Supplementary:**
- [ ] [MDN — Introduction to the DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
- [ ] Watch: *What the heck is the event loop?* by Philip Roberts (JSConf)

**Weekly project — Interactive To-Do List:**
Add, delete, mark complete, filter (all/active/completed). Persist with `localStorage`. No frameworks. The mentee may not look at any tutorial that builds a to-do list — they must build it from their own logic.

**Mentor check-in questions:**
- Why use `addEventListener` instead of `onclick`?
- How does event delegation work, and where did you use it?
- What's `localStorage` and how does it differ from session storage and cookies?

---

### Week 7 — Modern JavaScript (ES6+)

**Learning objectives:**
- Use destructuring, spread/rest, template literals, arrow functions.
- Understand `this` and scope.
- Use array higher-order methods (`map`, `filter`, `reduce`, `find`).
- Understand asynchronous JavaScript (callbacks → promises → async/await).

**freeCodeCamp:**
- [ ] *JavaScript Algorithms and Data Structures* → "Learn the Date Object by Building a Date Formatter"
- [ ] *JavaScript Algorithms and Data Structures* → "Learn Modern JavaScript Methods by Building Football Team Cards"
- [ ] *JavaScript Algorithms and Data Structures* → "Learn Asynchronous Programming by Building an fCC Authors Page"

**Supplementary:**
- [ ] [JavaScript.info](https://javascript.info/) — Chapter 5 (Data types) and Chapter 11 (Promises, async/await)
- [ ] Watch: *JavaScript Promises in 10 Minutes* (Web Dev Simplified)

**Weekly project — Weather App:**
Use a free API (e.g., [OpenWeather](https://openweathermap.org/api) or [Open-Meteo](https://open-meteo.com/)). User enters a city, app shows current weather and a 5-day forecast. Use `fetch` and `async/await`. Handle errors (invalid city, network failure) gracefully.

**Mentor check-in questions:**
- Explain `async/await`. What does it actually return?
- What's the difference between `map` and `forEach`?
- How did you handle the API key? (This is a teaching moment about secrets.)

---

### Week 8 — JavaScript Algorithms & The Second Cert

**Learning objectives:**
- Solve common algorithmic problems.
- Get comfortable with debugging.
- Earn the second certification.

**freeCodeCamp:**
- [ ] *JavaScript Algorithms and Data Structures* → Complete remaining lessons through "Learn Functional Programming"
- [ ] **Build all 5 certification projects** (Palindrome Checker, Roman Numeral Converter, Telephone Number Validator, Cash Register, Pokémon Search App)
- [ ] 🏆 **Earn the JavaScript Algorithms and Data Structures certification**

**Supplementary:**
- [ ] [Codewars](https://www.codewars.com/) — Solve 5 problems at 8 kyu and 5 at 7 kyu
- [ ] Watch: *Debugging in Chrome DevTools* (any solid 20-min walkthrough)

**Weekly project:**
Same as Week 4 — the cert projects are the deliverables. Each in its own repo, each deployed.

**Mentor check-in questions:**
- Pick the cert project you struggled with most. Walk me through your solution and what you'd do differently.
- Show me how you used the Chrome debugger to solve a bug this week.

> 🎯 **End of Phase 2 milestone:** Comfortable with vanilla JS, can build interactive sites without a framework, has 10+ deployed projects, two freeCodeCamp certifications.

---

## Phase 3 — React & Modern Tooling (Weeks 9–11)

### Week 9 — Tooling, npm, and React Basics

**Learning objectives:**
- Use npm, `package.json`, and the terminal-based dev workflow.
- Understand what bundlers do (Vite at a high level).
- Write JSX, components, and pass props.
- Use `useState`.

**freeCodeCamp:**
- [ ] *Front End Development Libraries* → React lessons (entire React section)

**Supplementary:**
- [ ] [Official React Docs — Quick Start](https://react.dev/learn)
- [ ] [Official React Docs — Tutorial: Tic-Tac-Toe](https://react.dev/learn/tutorial-tic-tac-toe)
- [ ] Watch: *Vite in 100 Seconds* (Fireship)

**Setup task (Day 1):**
Scaffold a project with Vite: `npm create vite@latest my-first-react-app -- --template react`. Run it, modify it, commit it.

**Weekly project — To-Do List, ported to React:**
Take Week 6's to-do list and rebuild it in React with `useState` for state and `localStorage` for persistence. Compare the two implementations and write a section in the README about what's better/worse in React vs vanilla JS.

**Mentor check-in questions:**
- What is JSX, really? What does it compile to?
- Why must `useState`'s setter be called instead of mutating state directly?
- Walk me through the file structure Vite gave you.

---

### Week 10 — Hooks, Component Patterns & Routing

**Learning objectives:**
- Use `useEffect`, `useRef`, and `useContext`.
- Lift state up; pass callbacks down.
- Build multi-page apps with React Router.
- Fetch and display API data in React.

**freeCodeCamp:**
- [ ] Continue *Front End Development Libraries* if React content remains
- [ ] If finished, move to Redux lessons (optional but recommended)

**Supplementary:**
- [ ] [React Router Tutorial](https://reactrouter.com/en/main/start/tutorial)
- [ ] [Patterns.dev](https://www.patterns.dev/) — Read the React patterns section
- [ ] Watch: *10 React Hooks Explained* (Web Dev Simplified)

**Weekly project — Movie Search App:**
Use the [TMDB API](https://www.themoviedb.org/documentation/api) (free, registration required). Pages: Home (trending), Search (live results as user types — debounced), Movie Detail (`/movies/:id`). Use React Router. Loading states, error states, and empty states all handled.

**Mentor check-in questions:**
- When does `useEffect` run? What does the dependency array do?
- Why did we debounce the search? Show me your implementation.
- How did you organize your components and folders?

---

### Week 11 — Polishing, Forms, and the Third Cert

**Learning objectives:**
- Handle forms in React (controlled components).
- Style React apps (CSS modules, or a library like Tailwind).
- Earn the third certification.

**freeCodeCamp:**
- [ ] *Front End Development Libraries* → Complete remaining sections
- [ ] **Build all 5 certification projects** (Random Quote Machine, Markdown Previewer, Drum Machine, JavaScript Calculator, Pomodoro Clock)
- [ ] 🏆 **Earn the Front End Development Libraries certification**

**Supplementary:**
- [ ] [Tailwind CSS docs](https://tailwindcss.com/docs/installation) — set up in one project
- [ ] Read: [React forms — Controlled vs Uncontrolled](https://react.dev/learn/sharing-state-between-components)

**Weekly project:**
The 5 cert projects.

**Mentor check-in questions:**
- Explain controlled vs uncontrolled inputs. Which do you use and why?
- What's one thing you'd refactor in your Pomodoro Clock if you had more time?

> 🎯 **End of Phase 3 milestone:** Three freeCodeCamp certifications, comfortable building React apps with routing, hooks, and APIs, 15+ deployed projects.

---

## Phase 4 — Capstone & Portfolio (Week 12)

### Week 12 — Capstone Project & Portfolio Site

This entire week is dedicated to **one large capstone project** and the **portfolio site** that ties everything together.

**Capstone project requirements:**
- React + React Router
- Consumes a real API
- Has at least 4 distinct routes
- Implements a non-trivial feature (auth via a service like Firebase, a shopping cart, real-time updates, drag-and-drop, etc.)
- Fully responsive
- Deployed to Netlify or Vercel with a custom subdomain or netlify URL
- Real README with: screenshots, tech stack, features, how to run locally, what was hard, what's next

**Capstone ideas (pick one or pitch your own):**
- A movie/book/game tracker with user lists
- A recipe app with meal planning
- A budget tracker with charts
- A local events finder using a public events API
- A flashcard / spaced repetition app

**Portfolio site requirements:**
- Custom design (do not copy a template)
- About, Projects (link to 4+ best projects), Contact, Resume
- Working contact form (use [Formspree](https://formspree.io/) or similar — no backend needed)
- Deployed with a custom domain if possible

**Final check-in:**
A 30-minute "demo day" where the mentee walks the mentor through their portfolio and capstone as if they were interviewing.

> 🎯 **End of Program milestone:** Three certifications, 15+ deployed projects, polished portfolio, capstone project, ready to start applying for junior roles or freelance work.

---

## Mentor Check-in Template

Use this for the weekly Saturday check-in. Keep it to ~60 minutes.

```markdown
## Week [N] Check-in — [Date]

### Wins
- What went well this week?
- Concept that finally clicked?

### Stuck points
- What confused you?
- Where did you spend more than 30 minutes stuck?

### Code review (15 min)
- Live walkthrough of this week's project
- Mentor asks 2–3 of the week's check-in questions
- Mentor reviews one piece of code in detail

### Next week prep
- Any concerns about next week's topics?
- Adjust pace if needed

### Action items
- [ ] Mentee: ...
- [ ] Mentor: ...
```

---

## Assessment Rubric

At each phase milestone, assess against these criteria. Score 1 (struggling) — 5 (strong).

| Skill                                   | Phase 1 | Phase 2 | Phase 3 | Final |
|-----------------------------------------|:-------:|:-------:|:-------:|:-----:|
| Writes semantic, accessible HTML        |    ✓    |         |         |       |
| Builds responsive layouts confidently   |    ✓    |         |         |       |
| Uses Git/GitHub fluently                |    ✓    |    ✓    |    ✓    |   ✓   |
| Writes modern JavaScript                |         |    ✓    |         |       |
| Manipulates DOM without a framework     |         |    ✓    |         |       |
| Consumes APIs                           |         |    ✓    |    ✓    |   ✓   |
| Builds React apps with state and routing|         |         |    ✓    |   ✓   |
| Reads documentation independently       |         |    ✓    |    ✓    |   ✓   |
| Debugs systematically                   |    ✓    |    ✓    |    ✓    |   ✓   |
| Communicates work clearly (READMEs)     |    ✓    |    ✓    |    ✓    |   ✓   |

A 3+ on every relevant row at each phase = ready to advance.

---

## Beyond the Curriculum

Once the 12 weeks are done, here are next steps to discuss with the mentee:

**Skills to add (in order of impact):**
1. TypeScript — non-negotiable for most modern frontend jobs
2. Testing — Vitest + React Testing Library
3. A meta-framework — Next.js or Remix
4. State management at scale — Zustand or Redux Toolkit
5. Backend basics — Node.js + Express, or a BaaS like Supabase

**Career steps:**
- Polish LinkedIn with the new projects and skills
- Contribute to one open-source project (start with documentation fixes)
- Solve 2 LeetCode-style problems per week
- Apply for at least 5 junior roles per week
- Practice 1 mock interview per week (with the mentor or a peer)

**Community:**
- Join the freeCodeCamp Discord and forum
- Follow active frontend devs on Twitter/X and Bluesky
- Attend local meetups or virtual conferences (Frontend Masters has free conference recordings)

---

## License & Contributions

This curriculum is open for adaptation. If a future mentee finds a section unclear, the mentor and mentee should jointly update it via PR. Treat this document as living.

---

*Built around freeCodeCamp's curriculum because it is free, project-based, and constantly updated by an active community. All credit for the underlying lessons goes to the freeCodeCamp team and contributors.*
