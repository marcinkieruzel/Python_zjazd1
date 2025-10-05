### Kalkulator ###

1. Zainstaluj moduł inquirer 
``` python

#pip install inquirer

import inquirer

question = [
    inquirer.List(
        'action',
        message="What do you want to do?",
        choices=['Start', 'Stop', 'Exit'],
    ),
]

answer = inquirer.prompt(question)
print(f"You selected: {answer['action']}")
```

2. Stwórz kalkulator który będzie pobierał od użytkownika `num_1` `num_2` oraz operację matematyczną z modułu inquirer `choices=['+','-', '*', '/']`

3. Wynik operacji przechowaj w zmiennej
4. Pozwól na wielokrotne kalkulacje (użyj pętli while)