# flask-web-server

This repository contains a simple Flask application designed to collect data from a web form and save it to a CSV file. Follow the steps below to set up and run the application locally.

## Setup & Installation

1. **Clone the repository**:
   ```
   git clone [URL_of_your_repository]
   cd [repository_name]
   ```

2. **Set up a virtual environment** (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install the required packages**:
   ```
   pip install Flask
   ```

4. **Run the application**:
   ```
   python [your_flask_app_filename].py
   ```

5. **Access the app**:
   Once the server is running, you can access the app by going to:
   ```
   http://localhost:5000/
   ```

## Usage

1. Visit the home page of the application.
2. Fill out the web form provided on the page.
3. Submit the form.
4. Upon successful submission, you will be redirected to `thankyou.html`.
5. The data from the form will be appended to a `database.csv` file in the root directory.

## Issues & Contributions

If you encounter any issues or would like to contribute improvements or features to this project, please open an issue or submit a pull request.
