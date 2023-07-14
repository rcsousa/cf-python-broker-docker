# Time and File Units in Czech Language

This is a Python dictionary that contains the singular and plural forms of time and file units in the Czech language. 

## Installation

There is no need to install anything to use this dictionary. Simply copy and paste the code into your Python script.

## Usage

To use this dictionary, simply access the key-value pairs as you would with any other Python dictionary. For example, to access the plural form of "minuta" (minute), you would use:

```python
units = {
    'vteřina': ['vteřiny', 'vteřin'],
    'vteřinou': ['vteřinami', 'vteřinami'],
    'minuta': ['minuty', 'minut'],
    'minutou': ['minutami', 'minutami'],
    'hodina': ['hodiny','hodin'],
    'hodinou': ['hodinami','hodinami'],
    'den': ['dny','dnů'],
    'dnem': ['dny','dny'],
    'týden': ['týdny','týdnů'],
    'týdnem': ['týdny','týdny'],
    'měsíc': ['měsíce','měsíců'],
    'měsícem': ['měsíci','měsíci'],
    'rok': ['roky','let'],
    'rokem': ['roky','lety'],
    'záznam': ['záznamy', 'záznamů'],
    'soubor': ['soubory', 'souborů']
}

print(units['minuta'][1]) # Output: minut
```

## Contributing

If you would like to contribute to this project, feel free to submit a pull request. 

## References

There are no external sources of information used in this code.