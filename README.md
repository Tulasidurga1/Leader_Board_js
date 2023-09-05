# Leader_Board_js
# Hosted Link:-https://tulasidurga1.github.io/Leader_Board_js/
### HTML Structure:

- The HTML structure defines the basic layout of the web page, including a form for adding players to a leaderboard and a section for displaying the leaderboard.
# CSS Styling:

- The CSS code provides styling to the HTML elements. Here's a summary of the CSS classes and their styles:
- *: Resets margin, padding, and box-sizing for all elements.
- body: Sets the overall styling for the body, including font, background color, and text color.
- main: Styles the main content container, making it a flex container with centered items.
- .main_title: Styles the main title.
- .main_form: Styles the form, making it a grid container.
- input: Styles input fields.
- .main_error-prompter: Styles the error prompt message (initially hidden).
- button:not(.main_form-submit-btn): Styles buttons in the form (circular shape).
- .main_form-submit-btn: Styles the form submission button.
- button:active: Adds a scaling effect to buttons when clicked.
- .main_scoreboard-wrapper: Styles the container for the leaderboard.
- .main_scoreboard: Styles individual leaderboard entries.
- .main_player-name: Styles player names.
- .main_time-stamp: Styles timestamp.
- .main_scoreboard-btn-container: Styles button container within leaderboard entries.
- @media (min-width:35.25em): Adds responsive styles for larger screens.
### JavaScript Functionality:

- JavaScript code at the end of the HTML document adds functionality to the webpage. It does the following:
- Listens for the form submission event.
- Prevents the default form submission behavior.
- Retrieves input values (first name, last name, country, and player score).
- Displays an error message if any of the input fields are empty.
- Creates a new leaderboard entry with the provided information.
- Appends the new entry to the leaderboard container.
- Sorts the leaderboard entries based on player scores.
- Adds event listeners to the buttons within each leaderboard entry to perform actions like deleting a player or modifying their score.
- There's also a generateDateAndTime function to create a timestamp for each entry.
- Explanation:

- The code defines the structure, style, and functionality of a leaderboard web application. Users can add players with their information and scores. The leaderboard displays the players in descending order based on their scores. Users can also interact with each player's entry through the buttons.
# Usage:

To use this code, you would need to have the HTML, CSS, and JavaScript files in the specified file paths ("style.css" and "src.js").
The HTML structure provides the layout for your webpage.
The CSS styles make your webpage visually appealing.
The JavaScript code handles user interactions, form submissions, and updates to the leaderboard.
