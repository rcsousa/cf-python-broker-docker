# Web2py Internationalization (I18N) Dictionary

This is a dictionary file for internationalization (I18N) in web2py. It contains translations for various strings used in the web2py framework. 

## Installation

This file is already included in the web2py framework, so there is no need to install it separately.

## Usage

This file is used by web2py to translate strings in the framework to different languages. To use it, simply set the language code in the `routes.py` file of your web2py application:

```python
routers = dict(
    BASE = dict(
        default_application='myapp',
        default_controller='default',
        default_function='index',
        language='zh-cn' # set the language code here
    )
)
```

## Contributing

If you would like to contribute to this dictionary file, you can do so by submitting a pull request to the web2py GitHub repository.

## References

- [Web2py documentation](http://www.web2py.com/books/default/chapter/29/04/the-core#Internationalization)