# test-mortgage-calculator-
MORTGAGE CALCULATOR
# Personal Website with Mortgage Calculator

A Flask-based personal website featuring a mortgage calculator and calendar/reminder system.

## Features
- User authentication (login/register)
- Mortgage calculator
- Calendar with reminders
- Responsive design

## Local Development

1. Clone the repository
2. Create a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
4. Set environment variables:
   ```
   export FLASK_APP=app.py
   export FLASK_ENV=development
   export SECRET_KEY=your-secret-key-here
   ```
5. Run the application:
   ```
   flask run
   ```

## Deployment

This application is configured for deployment on Render.com:

1. Push your code to a GitHub repository
2. Create a new Web Service on Render
3. Connect your GitHub repository
4. Set the following environment variables:
   - `PYTHON_VERSION`: 3.9.13
   - `SECRET_KEY`: A secure random string
5. Deploy!

## Environment Variables

- `SECRET_KEY`: Secret key for session management

## License

MIT
