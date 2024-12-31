# Примеры форматирования кода

## Простой блок кода с подсветкой синтаксиса
```python
def hello_world():
    print("Hello, World!")
```

## Блок кода с номерами строк
```python linenums="1" hl_lines="2 3"
def calculate_sum(a, b):
    """Calculate sum of two numbers."""
    result = a + b
    return result
```

## Блок кода с заголовком
```python title="example.py"
class Example:
    def __init__(self):
        self.value = "Hello"
```

### Блок кода с аннотациями
```python
def process_data(data): # (1)
    if not data: # (2)
        return None
    return data.process()
```

1. Основная функция обработки
2. Проверка на пустые данные

## Вставка эмодзи
:smile: :heart: :thumbsup:

## Admonitions (блоки примечаний)
!!! note "Примечание"
    Это примечание будет отображаться в отдельном блоке

!!! warning "Внимание"
    Это предупреждение будет выделено

??? example "Раскрывающийся блок"
    Этот текст будет скрыт по умолчанию