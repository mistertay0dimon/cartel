# cartel
cartel - это шуточная библиотека, которая выводит текст-мем из тиктока "Как ему не страшно говорить про кортель"

То есть она позволяет создать скрипт который будет этот текст выводить 
# Установка
Установить библиотеку можно командой:
```python
pip install cartel
```
# Использование
Чтобы сделать скрипт который будет выводить текст как ему не страшно блаблабла вам нужно в вашем новом .py файле ввести вот это:
```python
from cartel import cartel

text = cartel()
print(text)
```
После этого выведется текст как ему не страшно говорить блаблабла 

Новый формат текста:
```python
from cartel import new_cartel_text

text = new_cartel_text()
print(text)
```

Пользуйтесь! (Интересно для чего это будет использоваться...)

# Внимание 
С 1.1-a1 версии будет использоваться новый вариант старого формата тот который выше указан

Старый вариант старого формата (если у вас 1.0.01):
```python
from cartel import carteltext

text = carteltext()
print(text)
```
