### Statystyka wyrazów ###

#### index.py ####

1. Naszym celem jest analiza statystyczna występowania wyrazów w Hamlecie 
2. Podziel tekst na poszczególne wyraz 
3. Oblicz ile razy wystepuje każdy w wyrazów

```python 
with open('hamlet.txt', 'r', encoding='utf-8') as file:
    text = file.read()
```

```python 
import re

text = "Hello, world. This is Python, easy to learn."

# podziel po spacji, kropce lub przecinku
words = re.split(r'[ ,.]+', text)


from collections import Counter # Klasa counter pomoże ci zliczyć wystąpienia
```

### Spłaszczanie listy ###

#### flatten.py ####

- podpowiedź: użyj rekurencji 

