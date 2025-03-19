# Day 1

Порешал таск Selectel CTF
Послушал лекцию Солар по введению в профессию
Смотрю пятый день курса по питону (не досмотрел день грустные скобочки) вот что изучил пока что:

```python
## Сегодня изучаем лупы

fruits = ["apple", "banana", "cherry"]

for fruit in fruits:
    print(fruit)
    print(fruit + " pie")
    print(fruits)

student_scores = [150, 231, 325, 43]

print(max(student_scores))

best = student_scores[0]  # задаем переменной 'best' значение первого студента

for student in student_scores:
    if student > best:
        best = student

print(best)

```
