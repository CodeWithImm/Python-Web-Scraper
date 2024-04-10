**Python Script for Web Automation with Selenium**

This repository contains a Python script named `tasks.py` that demonstrates basic web automation using the Selenium library. The script performs the following actions:

1. Opens a specified website in a web browser.
2. Enters a search term into a search field.
3. Captures a screenshot of the resulting webpage.
4. Closes all open browsers.

**Requirements**

To use this script, you'll need the following:

- Python 3.x ([https://www.python.org/downloads/](https://www.python.org/downloads/))
- Selenium library ([https://pypi.org/project/selenium/](https://pypi.org/project/selenium/))

**Installation**

1. Install Python if you haven't already.
2. Open a terminal or command prompt.
3. Navigate to your project directory using the `cd` command.
4. Install the Selenium library using pip:

   ```bash
   pip install selenium
   ```

**Usage**

1. Save the script as `tasks.py` in your project directory.
2. Modify the `open_the_website` function within `tasks.py` to specify the desired target website URL.
3. Update the `search_for` function to set the search term you want to enter.
4. Open a terminal or command prompt and navigate to your project directory.
5. Run the script using the following command:

   ```bash
   python tasks.py
   ```

**Explanation of the Script**

The `tasks.py` script consists of the following functions:

- `open_the_website(url)`: Takes a URL as input and opens it in a web browser using Selenium.
- `search_for(term)`: Locates a search field on the webpage (assuming it has the CSS selector "css:input") and enters the provided search term. Then, it simulates pressing the Enter key to submit the search.
- `store_screenshot(filename)`: Captures a screenshot of the current webpage and saves it to the specified filename (e.g., "output/screenshot.png").
- `main()`: The main execution block that calls the other functions in sequence. It opens the target website, performs the search, captures a screenshot, and finally closes all browsers.

**Additional Notes**

- This script assumes a basic HTML structure for the target website. You might need to adjust the CSS selector for the search field if it's different.
- For more complex web interactions, consider exploring advanced Selenium features and techniques.

I hope this README.md provides a clear and helpful guide for using your Python script!
