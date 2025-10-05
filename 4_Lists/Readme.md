### Statystyka wyrazów ### 

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

# Split by space, comma, or dot
words = re.split(r'[ ,.]+', text)
```