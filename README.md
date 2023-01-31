## Running this project

1. Create a virtual environment by executing the following command in the terminal:
    - Unix/macOS: `python3 -m venv env-name`
    - Windows: `python -m venv env-name`
    - Replace `env-name` with a desired name for the virtual environment.
2. Activate the virtual environment using the following command in the terminal:
    - Unix/macOS: `source env-name/bin/activate`
    - Windows: `.\env-name\Scripts\activate`
3. Install project dependencies by executing the following command in the terminal: `pip install -r requirements.txt`
4. Run the test cases by navigating to the project's root directory in the terminal and executing the following command: `pytest`

## Accessing the documentation page

1. Start the development server by executing the following command in the terminal: `uvicorn app.main:app --reload`
2. To view the documentation, navigate to `localhost:8000/docs` in your web browser.
