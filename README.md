# Fullstack Open - Part 1 Exercises (React Basics)

This repository contains my solutions to the exercises of **Part 1** from the [Fullstack Open course](https://fullstackopen.com/en/) offered by the University of Helsinki.

## 🧠 Overview

Part 1 introduces the **basics of React**, including:

- React components and JSX
- `useState` for managing component state
- Passing data via props
- Event handling
- Conditional rendering
- Splitting code into reusable components

The exercises in this part are essential for building a solid foundation in React and component-based architecture.

## 📁 Structure
part1/
├── 1.1-1.5 Course Information into c
│
├── 1.6-1.11 unicafe     
├── 1.12-1.14 anecdotes  

## 🔍 Challenges Faced

### 1. 📦 Passing Data via Props (Course Info)
- Challenge: Understanding how to **split the UI into components** and pass structured data like objects and arrays using props.
- Learned how to use simple `props.name`, `props.exercises`, etc. and how to keep the code modular.

### 2. ⚙️ State & Conditional Rendering (Feedback App)
- Challenge: Managing multiple states (`good`, `neutral`, `bad`) and **calculating derived statistics** like average and positive feedback percentage.
- Also learned **how to conditionally render** UI when no feedback has been given (e.g., "No feedback given").

### 3. 🎲 Dynamic Logic & Data Handling (Anecdotes)
- Challenge: Implementing **random selection**, **voting logic**, and finding the **most voted** anecdote.
- Required careful array manipulation using `useState`, `Math.max`, and `indexOf`.

## 🚀 How to Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/fullstackopen-part1.git
   cd fullstackopen-part1
