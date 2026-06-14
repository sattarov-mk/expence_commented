# Expense Tracker 💰

A simple React application for tracking personal expenses.

## Features

* Add new expenses
* Filter expenses by year
* Display expense title, date, and price
* Automatic list updates using React State
* Form validation
* Reusable UI components
* Well-commented codebase for learning React fundamentals

## Technologies Used

* React 18
* JavaScript (ES6+)
* CSS3
* Create React App

## Project Structure

```text
src/
├── components/
│   ├── expenses/
│   │   ├── Expenses.jsx
│   │   ├── ExpenseItem.jsx
│   │   ├── ExpenseDate.jsx
│   │   └── ExpensesFilter.jsx
│   │
│   ├── newExpenses/
│   │   ├── NewExpenses.jsx
│   │   └── ExpenseForm.jsx
│   │
│   └── ui/
│       ├── Card.jsx
│       └── Button.jsx
│
├── App.jsx
└── index.js
```

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/expense-tracker.git
```

Navigate to the project directory:

```bash
cd expense-tracker
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm start
```

The application will be available at:

```text
http://localhost:3000
```

## How It Works

1. The application starts with several predefined expenses.
2. Users can add new expenses through a form.
3. Each expense contains:

   * Title
   * Price
   * Date
4. Expenses are stored in React state.
5. Users can filter expenses by year using a dropdown menu.
6. The interface updates automatically whenever data changes.

## Learning Objectives

This project demonstrates:

* React Components
* Props
* State Management with `useState`
* Derived Data
* Event Handling
* Controlled Forms
* Conditional Rendering
* List Rendering with `map`
* Basic Component Reusability

## Future Improvements

* Edit existing expenses
* Delete expenses
* Expense charts and analytics
* Local Storage support
* Backend integration
* User authentication
* Responsive mobile design

## Author

Created as a React learning project focused on understanding component architecture, state management, and form handling.
