# Web2py Internationalization (I18N) Dictionary

This is a dictionary file for internationalization (I18N) in web2py, a free open-source web framework for agile development of secure database-driven web applications.

## Installation

This file is already included in the web2py framework, so there is no need to install it separately.

## Usage

This file contains translations for various strings used in web2py. To use it, simply set the `T` function in your web2py application to use this dictionary:

```python
T.force('zh-cn')
```

This will set the language to Chinese (Simplified). You can replace `'zh-cn'` with any other language code supported by web2py.

## Contributing

If you find any errors or would like to contribute to this dictionary, please submit a pull request on the [web2py GitHub repository](https://github.com/web2py/web2py/tree/master/languages).

## References

- [web2py documentation](http://www.web2py.com/books/default/chapter/29/04/the-core#Internationalization)
- [List of language codes supported by web2py](http://www.web2py.com/books/default/chapter/29/04/the-core#Language-codes)