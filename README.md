# EWTLabs
Ergonomic web technologies 6th semester laboratory works BSUIR



[Открыть лабораторные работы](https://mangust777.github.io/EWTLabs/)

# Долголев Иван

## Python разработчик

- **E-mail:** ivantakoiivan85@gmail.com
- **Phone:** +375 (29) 676-22-89
- **Telegram:** @ivancontact24
- **GitHub:** [github.com/mangust777](https://github.com/mangust777)

## Обо мне

_Привет_

![Начинающий Python разработчик](image.png)

Начинающий разработчик на Python, стремлюсь получить практический опыт и развиваться в сфере программирования. Открыт к общению, не боюсь сложностей и с энтузиазмом подхожу к решению задач. Быстро обучаюсь и готов интенсивно работать, чтобы восполнить пробелы в знаниях и приносить реальную пользу команде.

## Навыки

- _Python (Core / Standard Library)_
- _Django_
- _SQLAlchemy_
- _pip + setuptools_
- _attrs_
- _SQL_
- _Git_
- Знание принципов и паттернов разработки
- Английский – B1-B2

## Опыт

### Курсовой проект на тему “Сайт магазина косметики” – декабрь 2024, БГУИР

- Разработал и реализовал:
  - Серверную часть с использованием Django Framework
  - Клиент – статический веб-сайт.

## Образование

| Год              | Учебное заведение | Специальность         |
| ---------------- | ----------------- | --------------------- |
| 2022 – настоящее | БГУИР             | Инженер-системотехник |

## Пример кода: Пузырьковая сортировка на Python

```python
class BubbleSorter:
    @staticmethod
    def sort(arr):
        n = len(arr)
        for i in range(n):
            swapped = False
            for j in range(0, n - i - 1):
                if arr[j] > arr[j + 1]:
                    arr[j], arr[j + 1] = arr[j + 1], arr[j]
                    swapped = True
            if not swapped:
                break  # Массив уже отсортирован

if __name__ == "__main__":
    numbers = [5, 3, 8, 4, 2]
    print("До сортировки:", numbers)
    BubbleSorter.sort(numbers)
    print("После сортировки:", numbers)
```
