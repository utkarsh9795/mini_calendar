
 Mini Calendar

A simple, interactive calendar built using HTML, CSS, and JavaScript. This project enables users to view the calendar for any month of any year, navigate between months, and displays today's date by default.

 Features

- Display Current Date: By default, the calendar opens to the current month and highlights today's date.
- Month Navigation: Users can navigate between months using "Next" and "Previous" buttons.
- Responsive Design: The calendar adjusts for various screen sizes.
- Year Selection: Users can select a specific year to view the calendar for any month in that year.
- Days Highlighted: The current day is highlighted to easily identify today's date.
  
 Tech Stack

- HTML: For structuring the layout of the calendar.
- CSS: For styling and making the calendar visually appealing.
- JavaScript: For dynamic functionality, such as navigating months and setting the current date.

 How It Works

The project relies on JavaScript's `Date` object to calculate the days in each month and automatically adjusts for leap years. When a user selects a different month or year, the JavaScript function recalculates and displays the correct number of days.

 JavaScript Functions

- Initialize Calendar: Loads the current month and highlights today's date.
- Navigation: Functions to move between months and years.
- Date Calculations: Uses JavaScript's `Date` object to calculate the correct start day of the month and total days in each month.

 Project Structure

```
├── index.html       # Main HTML file
├── style.css        # CSS styling for the calendar
└── script.js        # JavaScript file containing all the logic
```

 `index.html`

This file provides the basic structure for the calendar interface, including buttons for month navigation and displays for the current month and year.

 `style.css`

The CSS file styles the calendar, ensuring a clean and user-friendly interface. It includes classes to highlight the current day, style the navigation buttons, and align calendar elements.

 `script.js`

The JavaScript file handles the core functionality:
  - Calculates the days in each month.
  - Allows navigation between months.
  - Highlights today's date by default.
  - Updates the display based on user interactions.

 Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mini-calendar.git
   ```
2. Open `index.html` in your preferred browser.

 Usage

- By default, the calendar opens to the current month.
- Use the "Next" and "Previous" buttons to navigate between months.
- Select a specific year to view a month in that year.

 Contributing

Contributions are welcome! If you have suggestions, feel free to open an issue or submit a pull request.


Feel free to customize this further based on your project structure or additional features.
