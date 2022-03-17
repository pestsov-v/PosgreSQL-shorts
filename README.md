# Выжимка по работе с PosgreSQL

## Простые запросы SELECT



| Ключевое слово | Описание | Место в запросе | Детали | Пример использования |
| :------: | :----- | :-----------: | :---: | :---------------: |
| SELECT | Выбирает необходимые столбцы запроса| Вначале запроса | - | SELECT country |
| FROM | Определяет таблицу из которой выбирать данные | После параметров ключевого слова SELECT | - | SELECT country FROM countries | 
| DISTINCT | Убирает строки с повторяющимися значениями | После SELECT | - | SELECT DISTINCT country FROM countries |
| COUNT | Подсчитывает количество строк столбца запроса | После SELECT | - | SELECT COUNT (country) FROM countries | 
| COUNT + DISTINCT | Подсчитывает уникальное количество строк столбца запроса | После SELECT | - | SELECT COUNT (DISTINCT person_name) 
