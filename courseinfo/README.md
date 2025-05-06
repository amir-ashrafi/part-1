# Vite React Projects

This repository contains two sample projects built with React and Vite. Each project demonstrates different React concepts and is structured as a separate application. The projects included are:

- **Feedback Application:** A simple app to collect feedback and display real-time statistics.
- **Course Information App:** An app that displays course details, including the number of exercises in each part and the overall total.

---

## Projects Overview

### 1. Feedback Application

**Description:**  
The Feedback Application allows users to register their opinions by clicking on one of three buttons ("Good", "Neutral", or "Bad"). It calculates and displays statistics such as the total number of responses, the average score, and the percentage of positive feedback. This project is excellent for understanding state management and component communication in React.

**Key Components:**

- **Button:** Renders a clickable button that accepts a custom text and a click event handler.
- **StatisticLine:** Displays a single statistic (e.g., "Good 5").
- **Statistics:** Calculates and renders all statistics. It conditionally renders a message if no feedback has been given.
- **App:** The main component that manages state for the feedback values and renders the other components.

---

### 2. Course Information App

**Description:**  
The Course Information App demonstrates how to display course details using React components. It shows the course title, the names and number of exercises for each course part, and calculates the total number of exercises. This project is ideal for practicing passing props between components in React.

**Key Components:**

- **Header:** Displays the course name as the main title.
- **Part:** Renders details (name and exercises) for a single part of the course.
- **Content:** Aggregates several `Part` components to display all parts of the course.
- **Total:** Calculates and displays the sum of exercises from all parts.
- **App:** Maintains the course data and renders the Header, Content, and Total components.

---

## Repository Structure

Below is an example of the repository structure if you are using a monorepo approach with separate folders for each project:

You can verify your installations by running:
```bash
node -v
npm -v