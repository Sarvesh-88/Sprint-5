# Prodesk IT - Sprint 05: Task Management Board

A state-driven Kanban-style task management web application built for the Sprint 01 engineering requirements. This project demonstrates proficiency in Component Architecture, State Management (`useState`), Prop Drilling, and dynamic UI rendering without direct DOM manipulation.

## Important Links

* **Live Website:** [Insert your Vercel/Netlify link here]
* **Demo Video:** [Insert your Google Drive video link here]

## Screenshot

https://github.com/Sarvesh-88/Sprint-5/blob/main/Sprint-5-img.png

## Tech Stack

* **HTML5**
* **Vanilla CSS3** (Flexbox Layouts)
* **JavaScript (ES6+)**
* **React.js** (Functional Components & Hooks)

## Features Completed (Phase 1: Base MVP)

The following mandatory Phase 1 requirements have been successfully completed:

* **UI Architecture:** Built a structured 3-column layout dynamically categorizing tasks into To Do, In Progress, and Done sections.
* **State Management (Single Source of Truth):** Managed all tasks within a single master state array. Implemented an input capturing text to successfully inject a new object with a default "todo" status.
* **State Mutation (Move Task):** Implemented action buttons on each rendered card to mutate its column state dynamically. Tasks move fluidly between arrays without requiring `.push()` or `.splice()`.
* **Universal Delete Action:** Engineered a single, universal delete function triggered by the task ID, handling task removal seamlessly across all three rendered columns.
* **Architecture Constraint (Prop Drilling):** Extracted card rendering logic into a separate, reusable `<MyTaskCard />` child component. Passed data and mutator functions (delete and move) down from the parent state via props.
