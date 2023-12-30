**Виконали:** 
*студенти 2-го курсу, групи ІМ-21:* 

<span padding-right:5em></span> **Галай Андрій** [Пошта: tytianiuk@gmail.com]
<span padding-right:5em></span> **Дворецька Анастасія** [Пошта: nastyadvoretskaya2005@gmail.com]

**Керівник**

*доцент кафедри ОТ ФІОТ, к.т.н., доцент*<span padding-right:5em></span> **Андрій БОЛДАК** 

[НТУУ "КИЇВСЬКИЙ ПОЛІТЕХНІЧНИЙ ІНСТИТУТ імені ІГОРЯ СІКОРСЬКОГО](https://kpi.ua/)

[Факультет інформатики та обчислювальної техніки](https://fiot.kpi.ua/)

[Кафедра обчислювальної техніки](https://comsys.kpi.ua/)

Київ

# Переваги використання хмарних баз даних

ВСТУП

## Створення хмарної бази даних використовуючи платформу Google Cloud

Для початку потрібно пройти рєстрацію. Далі обираємо бажану СУБД і налаштовуємо рушія:
![СУБД](./src/images/photo_2023-12-30_15-52-20.png)

Виконавши всі налаштування, можемо побачити, що наше хмарне сховище було створено:
![Cloud storage](./src/images/photo_2023-12-30_15-52-20.png)

Тепер створимо базу даних та протестуємо її роботу. Для простоти підключимося до хмарного сховища використовуючи термінал:

![Connecting to storage](./src/images/photo_2023-12-30_15-45-08.png)

Створимо нову базу даних із назвою “store”:
![Creating a db](./src/images/photo_2023-12-30_15-45-09.png)

Тепер створимо нову таблицю та внесемо до неї дані:
![Creating a table](./src/images/photo_2023-12-30_15-45-10.png)
![Filling table](./src/images/photo_2023-12-30_15-45-11.png)
![Select query](./src/images/photo_2023-12-30_15-45-12.png)

Дані було збережено у хмарній базі даних.
Тепер спробуємо підключитися та дістати дані використовуючи інший пристрій:
![Testing](./src/images/photo_2023-12-30_16-04-21.png)

Дані були успішно дістані з бази даних. Зробимо новий запис у таблиці:
![Creating a new query](./src/images/photo_2023-12-30_16-25-08.jpg)

Тепер перевіримо чи видно зміни з пристрою, який ми використовували до цього:
![Testing changes](./src/images/photo_2023-12-30_16-25-12.jpg)

Дані є, а отже все працює правильно.

## Висновок


