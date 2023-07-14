# Web2py Internationalization (i18n) Dictionary

This is a dictionary file for internationalization (i18n) in the web2py framework. It contains translations for various strings used in the framework, such as error messages, button labels, and menu items.

## Installation

This file is already included in the web2py framework, so there is no need to install it separately.

## Usage

This file is used by the web2py framework to translate strings in the user interface. To use it, simply set the `T` function to the current language code, like this:

```python
T.force('ro') # set language to Romanian
```

Then, use the `T` function to translate strings in your code, like this:

```python
response.flash = T('Hello World')
```

## Contributing

If you would like to contribute to this dictionary file, you can do so by submitting a pull request on the web2py GitHub repository.

## References

- [Web2py documentation](http://www.web2py.com/books/default/chapter/29/04/the-core#Internationalization-i18n)