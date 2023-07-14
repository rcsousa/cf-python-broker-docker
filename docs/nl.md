# web2py Dutch Language File

This repository contains a Dutch language file for the web2py framework. The file contains translations for various messages and labels used in the framework.

## Installation

To use this language file, follow these steps:

1. Clone or download this repository.
2. Copy the `dutch.py` file to the `languages` directory of your web2py application.
3. In your web2py application, open the `routes.py` file and add the following line at the top:

```python
from gluon.languages import read_possible_languages
```

4. Still in the `routes.py` file, add the following line after the above line:

```python
read_possible_languages()
```

5. In the `routes.py` file, add the following line to the `routes_in` function:

```python
'(?P<language>[a-z]{2})/'+URL(args=request.args, vars=request.get_vars, host=True)
```

6. In the `routes.py` file, add the following line to the `routes_out` function:

```python
if T.accepted_language in ['nl']:
    url = '/%s%s' % (T.accepted_language, url)
```

7. Restart your web2py application.

## Usage

Once you have installed the language file, you can switch to Dutch by adding `/nl/` to the URL of your web2py application. For example, if your application is running at `http://localhost:8000/myapp/`, you can switch to Dutch by visiting `http://localhost:8000/nl/myapp/`.

## Contributing

If you find any errors or omissions in the translation, please feel free to submit a pull request or open an issue.

## References

- [web2py documentation](http://www.web2py.com/books/default/chapter/29/04/the-core#Languages)
- [web2py Dutch language file on GitHub](https://github.com/web2py/web2py/blob/master/languages/nl.py)