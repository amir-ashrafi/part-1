# Feedback Application

This project is a simple feedback application built using React and Vite. In this app, users can provide feedback by clicking one of three buttons ("Good", "Neutral", or "Bad"). The app then calculates and displays key statistics such as the total feedback count, the average score, and the percentage of positive feedback.

## Features

- **Feedback Submission:** Users can register their feedback using three distinct buttons.
- **Real-time Statistics:** The app calculates the total number of responses, an average score (where "Good" is considered positive and "Bad" negative), and the percentage of positive feedback.
- **Conditional Rendering:** If no feedback is given, the app displays a "No feedback given" message.
- **Component-based Structure:** The app is organized using several reusable components:
  - **Button:** A simple component for rendering a clickable button.
  - **StatisticLine:** Displays a single row of statistic data in a table.
  - **Statistics:** Aggregates and presents the calculated statistics in a table format.
  - **App:** The main component that manages the state for feedback values and renders the buttons and statistics.

