# Malay Language Pack for web2py

This is a language pack for web2py in Malay language. It provides translations for various messages and labels used in web2py.

## Installation

To use this language pack, you need to have web2py installed on your system. If you don't have it installed, you can download it from the official website: https://www.web2py.com/init/default/download

Once you have web2py installed, follow these steps to install the Malay language pack:

1. Download the `malay.py` file from this repository.
2. Copy the `malay.py` file to the `languages` directory in your web2py application.
3. Open the `routes.py` file in your web2py application and add the following line at the top:

```python
from gluon.languages import read_possible_languages
```

4. Add the Malay language to the list of possible languages by adding the following line:

```python
read_possible_languages('/path/to/languages/folder', ['my'])
```

Replace `/path/to/languages/folder` with the path to the `languages` directory in your web2py application.

## Usage

To use the Malay language pack in your web2py application, set the `T` object's `lang` attribute to `'my'` in your controller or model:

```python
T.force('my')
```

This will set the language to Malay for the current request.

## Contributing

If you find any errors or want to suggest improvements to the Malay language pack, please feel free to open an issue or submit a pull request on GitHub.

## References

- [web2py official website](https://www.web2py.com/)
- [web2py documentation](https://www.web2py.com/books/default/chapter/29/00/introduction)