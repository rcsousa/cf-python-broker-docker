# Russian Pluralization Dictionary

This code is a Python dictionary that contains singular and plural forms of Russian words. It is specifically designed to help with pluralizing words in the Russian language, which can be quite complex due to the various grammatical rules that apply.

## Installation

There is no need to install any dependencies to use this code. Simply copy and paste it into your Python script or import it as a module.

## Usage

To use this dictionary, simply access the key-value pairs as you would with any other Python dictionary. The keys are the singular forms of the words, and the values are lists containing the first and second plural forms of the words.

For example, to get the plural forms of the word "выбрана" (meaning "selected" in English), you would access the key "выбрана" like this:

```python
plural_forms = russian_pluralization_dict['выбрана']
```

This would return the list `['выбраны', 'выбрано']`, which contains the first and second plural forms of the word.

## Contributing

If you would like to contribute to this project, please feel free to submit a pull request. Any contributions are welcome!

## References

There are no external sources of information referenced in this code.