# Pluralize

This is a Python dictionary that contains singular and plural forms of some words in Ukrainian language. It is used to pluralize words in Ukrainian language based on the number of items.

## Installation

This code does not require any installation or dependencies.

## Usage

To use this code, simply import the dictionary and use it in your code to pluralize words in Ukrainian language based on the number of items.

```python
from pluralize import pluralize

items = 5
word = 'рядок'
plural_word = pluralize(items, word)
print(f"I have {items} {plural_word}.")
```

Output:
```
I have 5 рядків.
```

## Contributing

If you want to contribute to this project, feel free to fork the repository and submit a pull request.

## References

- [Ukrainian pluralization rules](https://uk.wikipedia.org/wiki/%D0%9C%D0%BD%D0%BE%D0%B6%D0%B8%D0%BD%D0%B0_%D1%83%D0%BA%D1%80%D0%B0%D1%97%D0%BD%D1%81%D1%8C%D0%BA%D0%BE%D1%97_%D0%BC%D0%BE%D0%B2%D0%B8) (in Ukrainian)