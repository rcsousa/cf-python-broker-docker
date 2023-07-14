# App-Specific Example Router

This is a simple router that is used for setting languages from the app/languages directory as a part of the application path: app/<lang>/controller/function. The language from default.py or 'en' (if the file is not found) is used as the default language.

## Installation

To use this router, you must follow these steps:

1. Rename <web2py-root-dir>/router.example.py to routes.py
2. Rename this APP/routes.example.py to APP/routes.py (where APP is your application directory)
3. Restart web2py (or reload routes in web2py admin interface)

You can copy this file to any application's root directory without changes!

## Dependencies

This code requires the following dependencies:

- fileutils
- languages

## Execution

To execute this code, you must follow the installation instructions above and then run your web2py application. The router will automatically set the language based on the URL path.

## Contribution

If you want to contribute to this project, please follow these steps:

1. Fork this repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add some feature'`)
5. Push to the branch (`git push origin feature/your-feature`)
6. Create a new Pull Request

## References

For more information on web2py, please refer to the official documentation: https://www.web2py.com/