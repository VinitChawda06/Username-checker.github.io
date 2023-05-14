
# Username Checker App

This is a simple Flask web application that checks if a given username meets certain requirements. The application checks if the username:

1. Contains at least one lowercase letter.
2. Contains at least one uppercase letter.
3. Ends with a number.

If the username meets all three requirements, the application displays a success message. Otherwise, the application displays an error message listing the missing requirements.

## Technologies Used

- Python
- Flask
- HTML
- Bootstrap
- Git

## Files

The following files make up the application:

- `Username-checker.py`: This file contains the Flask application code, including the `index` and `report` routes that handle the application logic.

- `basicflask.html`: This file contains the basic structure for all web pages in the application. It includes Bootstrap CSS and JavaScript for styling.

- `indexflask.html`: This file extends the `basicflask.html` template and contains the HTML for the main page of the application. It includes a form where the user can input their desired username.

- `reportflask.html`: This file extends the `basicflask.html` template and contains the HTML for the page that displays the results of the username check. It includes conditional statements to display the success or error messages based on the results of the check.

## Usage

To use the application, simply run the `Username-checker.py` file and navigate to `http://localhost:5000` in a web browser. Enter a username that meets the requirements in the input field and click the submit button. The application will display a success or error message based on the username entered.

## Contributing

Contributions to this project are welcome! To contribute, please create a pull request with any improvements or suggestions.
