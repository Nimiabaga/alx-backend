0x02. i18n
Description
This project involves implementing internationalization (i18n) in a Flask web application. Internationalization allows the application to support multiple languages and locales, making it accessible to users worldwide. The project covers setting up a basic Flask app, configuring the Babel extension for translation, localizing templates, and handling locale-specific formatting such as dates and times.

Learning Objectives
By the end of this project, you should be able to:

Parametrize Flask templates to display different languages.
Infer the correct locale based on URL parameters, user settings, or request headers.
Localize timestamps using time zone information.
Implement user-specific settings for locale and time zone preferences.
Requirements
Environment: Ubuntu 18.04 LTS, Python 3.7
Style: PEP 8 (version 2.5)
Execution: All files must be executable, starting with #!/usr/bin/env python3
Documentation: Include a README.md file and proper code documentation for modules, classes, and methods.
Translations: Use Flask-Babel for managing translations.
Setup Instructions
Basic Flask App: Set up a basic Flask application with a single route and a simple HTML template.

Basic Babel Setup:

Install Flask-Babel: pip3 install flask_babel==2.0.0
Instantiate the Babel object and configure available languages (en, fr).
Locale Determination: Implement a function to determine the best match for the user's locale using request.accept_languages or URL parameters.

Template Localization: Use the _ or gettext function to parametrize your templates and manage translations with Babel.

User Login Simulation: Mock a user login system to demonstrate locale and timezone preference settings.

Timezone Handling: Use the pytz library to handle time zone validation and localization.

Tasks
0. Basic Flask App
Create a simple Flask app with a single route and template.

1. Basic Babel Setup
Set up Flask-Babel and configure available languages.

2. Get Locale from Request
Determine the user's locale using URL parameters or request.accept_languages.

3. Parametrize Templates
Localize templates using Flask-Babel and manage translation files.

4. Force Locale with URL Parameter
Allow users to force a specific locale using URL parameters.

5. Mock Logging In
Simulate a user login system to demonstrate locale and timezone preferences.

6. Use User Locale
Implement logic to use the user's preferred locale.

7. Infer Appropriate Time Zone
Handle time zone settings and validation using pytz.

Resources
Flask-Babel Documentation
Flask i18n Tutorial
pytz Library
AUTHOR 

JULIE PETERS
