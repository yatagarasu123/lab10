# Лабораторна робота №10: OOP in Python
## Мета роботи:
Мета цієї лабораторної роботи полягає в ознайомленні з об'єктно-орієнтованим програмуванням (ООП) в Python.
### Очікуваний результат:
Оволодіння практичними навичками створення класів, роботи з атрибутами класів, та методами.
## Опис завдання:
У даній лабораторній роботі створюються класи у Python, кожен з яких має свої власні атрибути та методи, що демонструють основні концепції ООП.
## Виконання роботи:
### Структура проекту:
Кожне завдання представлене у вигляді окремого класу з відповідними атрибутами та методами.
### Опис файлів:
- **student_main.py**: містить код Python з класами для вирішення необхідних завдань.
- **README.md**: описує структуру проекту, призначення кожного файлу, основні класи та методи з поясненням їх роботи тощо.
### Опис основних класів та методів з поясненням їх роботи:
#### Task 1: Створення класу
Створіть клас Python під назвою "Student" з наступними атрибутами:
- name
- age
- grade

Приклад створення об'єкту класу:
```python
class Student:
    def __init__(self, name, age, grade):
        self.name = name
        self.age = age
        self.grade = grade
        
    def display_info(self):
        return f'name: {self.name}, age: {self.age}, grade: {self.grade}'
#Приклад використання
student = Student(name="Vlad", age=18, grade="A")
print(student.display_info())
```

### Результати:
Кожен з класів та методів виконує відповідну функціональність, яка була описана в завданні.
![image](https://github.com/yatagarasu123/lab10/assets/145234911/d7886726-f90f-4e35-bdf5-c0cfa86ce384)


### Висновки:
Лабораторна робота дозволила глибше ознайомитися з основними концепціями об'єктно-орієнтованого програмування в Python, а саме створення класів, методів, наслідування та інкапсуляції.
