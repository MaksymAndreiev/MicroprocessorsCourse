# Laboratory work №3 "Basic circuits of digital electronics"

## Tasks

Create a table of the DPM8 processor's own mnemonic instruction symbols and test it. Write an assembly program, that
would compare two numbers x and y, which are in the four most significant and least significant bits when entered from
the keyboard, and ensure its error-free translation.

## Result

| No | Team       | Team description                                                                               |
|----|------------|------------------------------------------------------------------------------------------------|
| 1  | 00 0000 00 | Write from register A to register A (No operation)                                             |
| 2  | 00 0001 00 | Write from register B to register A                                                            |
| 3  | 00 0010 00 | Write from register C to register A                                                            |
| 4  | 00 0011 00 | Write from register D to register A                                                            |
| 5  | 00 0000 01 | Write from register A to register B                                                            |
| 6  | 00 0010 01 | Write from register C to register B                                                            |
| 7  | 00 0011 01 | Write from register D to register B                                                            |
| 8  | 00 0000 10 | Write from register A to register C                                                            |
| 9  | 00 0001 10 | Write from register B to register C                                                            |
| 10 | 00 0011 10 | Write from register D to register C                                                            |
| 11 | 00 0000 11 | Write from register A to register D                                                            |
| 12 | 00 0001 11 | Write from register B to register D                                                            |
| 13 | 00 0010 11 | Write from register C to register D                                                            |
| 14 | 00 1000 00 | Clear register A                                                                               |
| 15 | 00 1000 01 | Clear register B                                                                               |
| 16 | 00 1000 10 | Clear register C                                                                               |
| 17 | 00 1000 11 | Clear register D                                                                               |
| 18 | 00 1001 00 | Write the inverted value of the number from register A to register A                           |
| 19 | 00 1001 01 | Write the inverted value of the number from register A to register B                           |
| 20 | 00 1001 10 | Write the inverted value of the number from register A to register C                           |
| 21 | 00 1001 11 | Write the inverted value of the number from register A to register D                           |
| 22 | 00 1010 00 | Write the logical sum of the contents of registers A and B to register A                       |
| 23 | 00 1010 01 | Write the logical sum of the contents of registers A and B to register B                       |
| 24 | 00 1010 10 | Write the logical sum of the contents of registers A and B to register C                       |
| 25 | 00 1010 11 | Write the logical sum of the contents of registers A and B to register D                       |
| 26 | 00 1011 00 | Write to register A the result of logical multiplication of the contents of registers A and B  |
| 27 | 00 1011 01 | Write to register B the result of logical multiplication of the contents of registers A and B  |
| 28 | 00 1011 10 | Write the result of logical multiplication of the contents of registers A and B to register C  |
| 29 | 00 1011 11 | Write to register D the result of logical multiplication of the contents of registers A and B  |
| 30 | 00 1100 00 | Write the result of exclusive OR of the contents of registers A and B to register A            |
| 31 | 00 1100 01 | Write the result of the exclusive OR of the contents of registers A and B to register B        |
| 32 | 00 1100 10 | Write the result of the exclusive OR of the contents of registers A and B to register C        |
| 33 | 00 1100 11 | Write the result of the exclusive OR of the contents of registers A and B to register D        |
| 34 | 00 1101 00 | Write to register A the value of the number from register A shifted bitwise to the left        |
| 35 | 00 1101 01 | Write to register B the value of the number from register A shifted bitwise to the left        |
| 36 | 00 1101 10 | Write the value of the number from register A bitwise to the left to register C                |
| 37 | 00 1101 11 | Write the value of the number from register A bitwise to the left to register D                |
| 38 | 00 1110 00 | Write to register A the value of the number from register A shifted bitwise to the right       |
| 39 | 00 1110 01 | Write the value of the number from register A bitwise to the right to register B               |
| 40 | 00 1110 10 | Write the value of the number from register A bitwise to the right to register C               |
| 41 | 00 1110 11 | Write the value of the number from register A bitwise to the right to register D               |
| 42 | 00 1111 00 | Write to register A the result of arithmetic addition of the contents of registers A and B     |
| 43 | 00 1111 01 | Write the result of the arithmetic addition of the contents of registers A and B to register B |
| 44 | 00 1111 10 | Write the result of the arithmetic addition of the contents of registers A and B to register C |
| 45 | 00 1111 11 | Write the result of the arithmetic addition of the contents of registers A and B to register D |
| 46 | 01 0000 00 | Writing a number to register A                                                                 |
| 47 | 01 0000 01 | Writing a number to register B                                                                 |
| 48 | 01 0000 10 | Writing a number to register C                                                                 |
| 49 | 01 0000 11 | Writing a number to register D                                                                 |
| 50 | 10 0000 00 | A single unconditional jump command that transfers control to a specific address               |
| 51 | 11 0000 00 | Transfers control to a specific address if the contents of register A are 0                    |
| 52 | 11 0000 01 | Transfers control to a specific address if the contents of the A register are other than 0     |
| 53 | 11 0000 10 | Transfers control to a specific address if the carry bit is set                                |
| 54 | 11 0000 11 | Transfers control to a specific address if the carry bit is 0                                  |

# Лабораторна робота №3 «Базові схеми цифрової електроніки»

## Завдання

Створити таблицю власних мнемонічних позначень команд процесора DPM8 та протестувати її. Написати програму на асемблері,
яка б порівнювала два числа х та у, що знаходяться у чотирьох старших та молодших бітах при вводі з клавіатури, та
домогтися її безпомилкової трансляції.

## Результат

| No | Команда    | Опис команди                                                                  |
|----|------------|-------------------------------------------------------------------------------|
| 1  | 00 0000 00 | Перезапис з регістра A в регістр A (No operation)                             |
| 2  | 00 0001 00 | Перезапис з регістра B в регістр A                                            |
| 3  | 00 0010 00 | Перезапис з регістра C в регістр A                                            |
| 4  | 00 0011 00 | Перезапис з регістра D в регістр A                                            |
| 5  | 00 0000 01 | Перезапис з регістра A в регістр B                                            |
| 6  | 00 0010 01 | Перезапис з регістра C в регістр B                                            |
| 7  | 00 0011 01 | Перезапис з регістра D в регістр B                                            |
| 8  | 00 0000 10 | Перезапис з регістра A в регістр C                                            |
| 9  | 00 0001 10 | Перезапис з регістра B в регістр C                                            |
| 10 | 00 0011 10 | Перезапис з регістра D в регістр C                                            |
| 11 | 00 0000 11 | Перезапис з регістра A в регістр D                                            |
| 12 | 00 0001 11 | Перезапис з регістра B в регістр D                                            |
| 13 | 00 0010 11 | Перезапис з регістра C в регістр D                                            |
| 14 | 00 1000 00 | Очистити регістр A                                                            |
| 15 | 00 1000 01 | Очистити регістр B                                                            |
| 16 | 00 1000 10 | Очистити регістр C                                                            |
| 17 | 00 1000 11 | Очистити регістр D                                                            |
| 18 | 00 1001 00 | Записати в регістр А інвертоване значення числа із регістра А                 |
| 19 | 00 1001 01 | Записати в регістр В інвертоване значення числа із регістра А                 |
| 20 | 00 1001 10 | Записати в регістр С інвертоване значення числа із регістра А                 |
| 21 | 00 1001 11 | Записати в регістр D інвертоване значення числа із регістра А                 |
| 22 | 00 1010 00 | Записати в регістр А логічну суму вмісту регістрів А і В                      |
| 23 | 00 1010 01 | Записати в регістр В логічну суму вмісту регістрів А і В                      |
| 24 | 00 1010 10 | Записати в регістр С логічну суму вмісту регістрів А і В                      |
| 25 | 00 1010 11 | Записати в регістр D логічну суму вмісту регістрів А і В                      |
| 26 | 00 1011 00 | Записати в регістр А результат логічного перемноження вмісту регістрів А і В  |
| 27 | 00 1011 01 | Записати в регістр В результат логічного перемноження вмісту регістрів А і В  |
| 28 | 00 1011 10 | Записати в регістр С результат логічного перемноження вмісту регістрів А і В  |
| 29 | 00 1011 11 | Записати в регістр D результат логічного перемноження вмісту регістрів А і В  |
| 30 | 00 1100 00 | Записати в регістр А результат виключного АБО вмісту регістрів А і В          |
| 31 | 00 1100 01 | Записати в регістр B результат виключного АБО вмісту регістрів А і В          |
| 32 | 00 1100 10 | Записати в регістр C результат виключного АБО вмісту регістрів А і В          |
| 33 | 00 1100 11 | Записати в регістр D результат виключного АБО вмісту регістрів А і В          |
| 34 | 00 1101 00 | Записати в регістр А значення числа з регістра А зміщене побітово вліво       |
| 35 | 00 1101 01 | Записати в регістр B значення числа з регістра А зміщене побітово вліво       |
| 36 | 00 1101 10 | Записати в регістр C значення числа з регістра А зміщене побітово вліво       |
| 37 | 00 1101 11 | Записати в регістр D значення числа з регістра А зміщене побітово вліво       |
| 38 | 00 1110 00 | Записати в регістр А значення числа з регістра А зміщене побітово вправо      |
| 39 | 00 1110 01 | Записати в регістр B значення числа з регістра А зміщене побітово вправо      |
| 40 | 00 1110 10 | Записати в регістр C значення числа з регістра А зміщене побітово вправо      |
| 41 | 00 1110 11 | Записати в регістр D значення числа з регістра А зміщене побітово вправо      |
| 42 | 00 1111 00 | Записати в регістр А результат арифметичного додавання вмісту регістрів А і В |
| 43 | 00 1111 01 | Записати в регістр B результат арифметичного додавання вмісту регістрів А і В |
| 44 | 00 1111 10 | Записати в регістр C результат арифметичного додавання вмісту регістрів А і В |
| 45 | 00 1111 11 | Записати в регістр D результат арифметичного додавання вмісту регістрів А і В |
| 46 | 01 0000 00 | Запис числа в регістр А                                                       |
| 47 | 01 0000 01 | Запис числа в регістр B                                                       |
| 48 | 01 0000 10 | Запис числа в регістр С                                                       |
| 49 | 01 0000 11 | Запис числа в регістр D                                                       |
| 50 | 10 0000 00 | Єдина команда безумовного переходу, передає управління на певну адресу        |
| 51 | 11 0000 00 | Передає управління на певну адресу, якщо вміст регістра А дорівнює 0          |
| 52 | 11 0000 01 | Передає управління на певну адресу, якщо вміст регістра А відмінний від 0     |
| 53 | 11 0000 10 | Передає управління на певну адресу, якщо встановлено біт переносу             |
| 54 | 11 0000 11 | Передає управління на певну адресу, якщо біт переносу дорівнює 0              |
