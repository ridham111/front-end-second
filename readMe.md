# Meal App

Author: Ridham Pansuriya
Maintainer: Ridham Pansuriya

This repository contains code for a simple Meal App web application. The app allows users to search for meals, view meal details, and add favorite meals to a separate favorites page. The application is built using HTML, CSS, and JavaScript.

## Features

- Search for meals by entering a keyword in the search box.
- View a list of meals based on the search query.
- Click on a meal to view its details.
- Add meals to the favorites page by clicking the heart icon.
- Remove meals from the favorites page by clicking the heart icon again.

## Getting Started

To run this app, simply open the `index.html` file in your web browser. The application will load, and you can start searching for meals and adding them to your favorites.

## How to Use

1. Enter a keyword in the search box at the top of the page.
2. Click the "Search" button or press the "Enter" key to view meals that match the search query.
3. Click on a meal to view its details.
4. To add a meal to your favorites, click the heart icon next to the meal.
5. To remove a meal from your favorites, click the heart icon again.

## File Structure

- `index.html`: The main HTML file that defines the structure of the Meal App.
- `favorites.html`: The HTML file for the favorites page.
- `styles.css`: The CSS file that styles the appearance of the app.
- `app.js`: The JavaScript file that handles the functionality of the Meal App.
- `meal.js`: The JavaScript file that contains functions for fetching meal data.
- `favorites.js`: The JavaScript file that handles the favorites functionality.

## How the App Works

The app uses vanilla JavaScript to handle user interactions and make API calls to fetch meal data from TheMealDB API. It dynamically creates meal cards based on search results and displays meal details when a user clicks on a meal. Favorite meals are stored in an array and saved to local storage, so they persist across page reloads.

## External Libraries Used

The app utilizes the following external libraries:

- Font Awesome (version 6.4.0): Provides icons for the heart (favorite) button.

## Compatibility

The app has been tested and verified to work on modern web browsers, including Google Chrome, Mozilla Firefox, Microsoft Edge, and Safari.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Feedback and Contributions

If you have any feedback or suggestions for improvements, please feel free to create an issue or submit a pull request. Contributions to this project are welcome!

---

Thank you for using the Meal App! We hope you enjoy searching for meals and managing your favorite dishes. If you have any questions or encounter any issues, please don't hesitate to reach out. Bon appétit! 🍽️✨
