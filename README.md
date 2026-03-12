# Завдання 5
## Кравченко Ярослав
### Загальне завдання
Використовуючи створені раніше класи та шаблон проектування
Command, розробити клас Menu як контейнер команд, що розширюється,
реалізувати обробку даних колекції та окремих елементів (масштабування,
інтерполяція, нормалізація, сортування, пошук і т.д.).
Реалізувати можливість скасування (undo) операцій (команд).
Продемонструвати поняття "макрокоманда".
Під час розробки програми використовувати шаблон Singletone.
Забезпечити діалоговий інтерфейс із користувачем.
Розробити клас для тестування функціональності програми.
Використати коментарі для автоматичного створення документації
засобами javadoc.

#### Скріншоти завдання

AppMain - Головний клас, діалоговий інтерфейс

![Код](https://github.com/Yarickkk/zav5/blob/main/AppM1.png)
![Код](https://github.com/Yarickkk/zav5/blob/main/AppM2.png)
![Код](https://github.com/Yarickkk/zav5/blob/main/AppM3.png)
![Код](https://github.com/Yarickkk/zav5/blob/main/AppM4.png)
![Код](https://github.com/Yarickkk/zav5/blob/main/AppM5.png)

Command - Базовий інтерфейс

![Код](https://github.com/Yarickkk/zav5/blob/main/Command1.png)

UndoManager - Зберігає стек виконаних команд для можливості їх скасування

![Код](https://github.com/Yarickkk/zav5/blob/main/UndoM1.png)

ScaleCommand - Масштабування результатів

![Код](https://github.com/Yarickkk/zav5/blob/main/Scale.png)

MacroCommand - Макрокоманди

![Код](https://github.com/Yarickkk/zav5/blob/main/Macro.png)

Menu - Контейнер команд

![Код](https://github.com/Yarickkk/zav5/blob/main/Menu.png)

CommandPatternTest - Тестування

![Код](https://github.com/Yarickkk/zav5/blob/main/Test.png)

Приклад роботи програми

![Приклад](https://github.com/Yarickkk/zav5/blob/main/Priklad.png)
![Приклад](https://github.com/Yarickkk/zav5/blob/main/priklad2.png)
