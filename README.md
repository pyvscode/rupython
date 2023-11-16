# RuPython
Модуль для написания кода на русском языке, пытался сделать все как можно легко и понятно)

## Содержание

- [Установка](#установка)
- [Использование и примеры](#использование)
- [Лицензия](#лицензия)

## Установка

1. Клонируйте репозиторий: `git clone https://github.com/pyvscode/rupython.git`
2. Установите зависимости: `pip install -r requirements.txt`

#### ИЛИ

1. pip install rupython

## Использование

### Функция "напиши":

```py
import rupython
from rupython import *

напиши("Привет мир!")
```

### Функция "спросить":

```py
import rupython
from rupython import *

спросить("Бим")

ИЛИ

import rupython
from rupython import *

спросить()
```

### Логические действия "if":

```py
import rupython
from rupython import *

проверка(a == 11, напиши("Привет мир!"))
```

## Лицензия

Этот проект лицензирован по [лицензии MIT](LICENSE).
