# СОДЕРЖАНИЕ ПРОГРАММЫ:
## Урок 1. Вступление
## Урок 2. Введение в Python
    1. Настройка среды для разработки на Python.
        Некоторые вспомогательные команды:
            - комментирование строки                        -   #
            - комментирование нескольких строк              -   Ctrl+K + Ctrl+C
                                         или                -   '''  строки  '''
            - раскомментирование строк / строки             -   Ctrl+K + Ctrl+U
            - развернуть сокращение                         -   Tab
            - сдвинуть сторки вперед на расстояние Tab      -   Tab
            - сдвинуть сторки назад на расстояние Tab       -   Tab+Shift
            - отменить                                      -   Ctrl+Z
            - повторить                                     -   Ctrl+Y
            - вырезать                                      -   Ctrl+X
            - копировать                                    -   Ctrl+C
            - вставить                                       -   Ctrl+V
            - найти                                            Ctrl+F
            - заменить                                      -   Ctrl+H
            - сохранить файл                                -   Ctrl+S
            - открыть файл                                  -   Ctrl+O
    2. Переменные. Типы данных. Преобразование типов.
        Переменные используются для хранения данных. Переменные можно использовать несколько раз. Можно менять значение и тип переменной. Переменная должна называться так, чтобы по названию можно было понять её предназначение.
        Стиль имен переменных - маленькие буквы и знаки подчеркивания: person_age
        Самые простые типы:
            - целое число — int
            - число с плавающей точкой — float
            - логический тип (истина/ложь) — bool
            - ничего (пустой тип) — None
            - строка — str (более сложный тип, будет рассмотрен отдельно) 
        Приведение типов:
            - str(number) - число к строке
            - строка к числу int(word)
            - любые другие преобразования аналогично
    3. Ввод, вывод.
        Куда можно выводить информацию:
            - GUI - интерфейс
            - WEB. - сайты
            - Мобильное приложение
            - Хранилище, например файл или база данных
            - Консоль (Терминал)
        print - дополнительные возможности:
            вывод разных типов данных через:
            print(“hello”, “world”, sep = “ ”, end=" " )использование разных разделителей слов (sep=) и разных разделителей строк (end=)
        Ввод данных. input():
            result = input() - требует ввода пользователя и возвращает строку
            Что бы мы ни спрашивали у пользователя, для программы результатом ввода всегда будет строка (тип данных str).
        Проверка типа данных type():
            позволяет определить какой тип двнных содержит переменная. Например: x = 12  type(x) покажет <class int>
    4. Арифметические и логические операции. Соответствие нескольким условиям: and, or, not.
        Стандартные математические операции:
             +  сложение
             -  вычитание
             *  умножение
             /  деление (по умолчанию в вещественных числах)
             // целая часть от деления 
             %  остаток от деления
             ** возведение в степень
        Приоритет математических операции:
             ** возведение в степень
             *  умножение
             /  деление
             // целочисленное деление
             %  остаток от деления
             +  сложение
             -  вычитание
            круглые скобки () помогают управлять приоритетами - работает как в математике (умножение главнее сложения)
        В Python нет лимита по хранению данных (нет ограничения по битам для хранения числа из-за динамической типизации данных)
        Логические операции:
            ==  равно
            !=  не равно
            >   больше
            >=  больше или равно
            <   меньше
            <=  меньше или равно
            and и
            or  или
            not не
    5. Условные операторы.
            Блоки и отступы в коде:
                - Блок кода — логически сгруппированный набор команд.
                - В python нет {}, разделяющих блоки кода.
                - Поэтому обязательно делать отступы для каждого блока кода.
                - Отступ — 4 пробела (клавиша tab в pycharm и VSCode).

        Оператор if
            код
            if  условие
                действие при правдивом условии
            продолжение кода

        Оператор if - elif - else
            код
            if условие:
                код1
            elif другое условие:
                код2
            else:
                код3
            продолжение кода

        Вложенный if
            - Внутри if-elif-else может быть другой if.
            - Таких вложений может быть сколько угодно много.
    6. Понятие циклов. Цикл while.    
        Цикл - Много раз выполняем один и тот же набор действий
        Цикл while - Пока условие выполняется (True): делать определенный набор действий.
            while условие:
                действие1
                действие2
    7. Инструкции break и continue. Инструкция while — else.
        break - Выход из цикла (не важно, выполнилось условие или нет).
        continue - Переход на следующую итерацию цикла (команды в цикле после continue не выполняются).
        Цикл while-else - В блоке else (после while) мы выполняем действия после того, как вышли из цикла while, когда условие цикла стало неверным (False)
### Урок 3. Разбор практического задания
    Домашнее задание к уроку 2:
        Выполните практическое задание для отработки пройденного материала. Проверьте себя, посмотрев разбор задания в следующем уроке.
        Проверка преподавателем в данном курсе не предусмотрена.
        Практическое задание
        1: Запросите от пользователя число, сохраните в переменную, прибавьте к числу 2 и выведите результат на экран. Если возникла ошибка, прочитайте ее, вспомните урок и постарайтесь устранить ошибку.
        2: Используя цикл, запрашивайте у пользователя число, пока оно не станет больше 0, но меньше 10.
        После того, как пользователь введет корректное число, возведите его в степень 2 и выведите на экран.
        Например, пользователь вводит число 123, вы сообщаете ему, что число неверное, и говорите о диапазоне допустимых. И просите ввести заново.
        Допустим, пользователь ввел 2, оно подходит. Возводим его в степень 2 и выводим 4.
        3: Создайте программу “Медицинская анкета”, где вы запросите у пользователя следующие данные: имя, фамилия, возраст и вес.
        Выведите результат согласно которому:
        Пациент в хорошем состоянии, если ему до 30 лет и вес от 50 и до 120 кг,
        Пациенту требуется заняться собой, если ему более 30 и вес меньше 50 или больше 120 кг
        Пациенту требуется врачебный осмотр, если ему более 40 и вес менее 50 или больше 120 кг.
        Все остальные варианты вы можете обработать на ваш вкус и полет фантазии.
        (Формула не соответствует реальной действительности и здесь используется только ради примера)
        Примечание: при написание программы обратите внимание на условия в задаче и в вашем коде.  Протестируйте программу несколько раз и убедитесь, что проверки срабатывают верно. В случае ошибок, уточните условия для той или иной ситуации.
        Пример: Вася Пупкин, 29 год, вес 90 - хорошее состояние
        Пример: Вася Пупкин, 31 год, вес 121 - следует заняться собой
        Пример: Вася Пупкин, 31 год, вес 49 - следует заняться собой
        Пример: Вася Пупкин, 41 год, вес 121 - следует обратится к врачу!
        Пример: Вася Пупкин, 41 год, вес 49 - следует обратится к врачу!
### Урок 4. Встроенные типы и операции с ними
    1. Строки. Определение. Методы. Форматирование.
        Строка - str:
            Состоит из набора символов. При объявлении заключаем в одинарные ковычки (допускаются двойные ковычки)
            Можно получить символ по индексу - индексы начинаются  с 0
            В Python можно использовать отрицательные индексы - берет с конца символы [-1] - последний символ строки
        Срезы - Можно получить несколько символов (часть строки)
            - friend[start:end]
            - friend[1:4] где 1 - с какого символа, 4 - по какой символ
            - friend[:4] - срез с начала строки
            - friend[1:] - срез до конца строки
            - friend[::2] - срез с начала до конца с шагом 2
        Функция len и методы строки
            !!! Метод это функция, которая принадлежит к конкретному объекту и не может быть использована отдельно от него
                - friend.find(‘a’) - ищем символ ‘a’ в строке friend - возвращает индекс найденой строки или -1, если не найдет
                - len(friend) - длина строки (сколько в ней символов)
                - friend.split() - разбиение строки через пробел (возвращает список)
                - friend.isdigit() - строка состоит только из цифр (возвращает bool)
                - friend.isalpha() - строка состоит только из букв (возвращает bool)
                - friend.upper() - приведение строки к верхнему регистру
                - friend.lower() - приведение строки к нижнему регистру
        Другие методы строки:
            - функция help(str)
            - выпадающая подсказка в PyCharm
            - pythonworld.ru
            - официальная документация Python
            - google, ...
        Форматирование строк:
            - конкатенация (не рекомендуется) -                 'Hello, ' + name
            - % (не рекомендуется) -                            'Hello, %s'%(name)      // обознач. %s - строка, %d - число
            - format -                                          'Hello, {}!'.format(name)
            - Вставляем (интерполируем) переменную в строку -   f'Hello, {name}'                    - РЕКОМЕНДУЕТСЯ
    2. Списки. Определение. Методы. Оператор in. Кортежи.
        Списки (list):
            - Списки - упорядоченные изменяемые коллекции объектов произвольных типов -   some_list = [‘hello’, 123, True]
            - Чаще всего содержат элементы одного типа (например, имена друзей) -         friends = [‘Leo’, ‘Max’, ‘Kate’]
            В списке, как и в строке, доступны индексы но они будут не посимвольно а по элемнентам (то, что между запятыми)
            Так же, к списку, можно применять срезы.
        Функция len и методы списка:
            - len(friends) - длина списка (сколько в нем элементов)
            - friends.append(‘Ron’) - добавление нового элемента
            - friends.pop() - удаляем последний элемент и возвращаем его
            - friends.clear() - очищаем весь список
            - friends.reverse() - переворот списка
            - friends.remove(‘Ron’) - удаление объекта из списка
            - del friends[0] - удаление элемента по индексу
            - sorted(friends) - сортировка списка
        Другие методы list:
            - сортировка
            - сопирование
            - выпадающая подсказка в PyCharm
            - pythonworld.ru
            - официальная документация Python
            - google, ...
        Оператор in:
            - Позволяет проверить наличие элемента в списке - 'Max' in friends   (проверит есть ли элемент Max в списке friends)
            - результат True или False
            - работает со сторками -        'S' in 'Superman'
        Кортеж (tuple):
            - список, который нельзя изменять
            - записывается в круглых скобках -  roles = (‘user’, ‘manager’, ‘admin’)
            - служит для защиты от изменений
    3. Последовательности. Цикл for in.
        Последовательность:
            - контейнер, элементы которого представляют собой некую последовательность 
            - может быть как изменяемая (список), так и неизменяемая (кортеж, строка)
            - реализует определенные методы:
                    - доступна индексация
                    - взятие длины
                    - ...
                    - можно использовать цикл for
        Утиная типизация:
            - если это выглядит как утка, плавает как утка и крякает как утка, то это, возможно, и есть утка
            - в ООП-языках - определение факта реализации определенного интерфейса объектом без явного указания или наследования этого интерфейса, а просто по реализации полного набора его методов.
            - если объект содержит реализацию методов последовательности - он будет считаться последовательностью
        Цикл for
            - позволяет перебирать элементы последовательности по порядку без указания индекса -    for friend in frinds: (какое-то действие или условие, например print(friend)  (не забываем про 4 пробела))
            - заканчивает выполнение кода когда заканчивается последовательность элементов
            - позволяет совершать меньше ошибок при переборе элементов, чем цикл while
        for vs while - преимущество следует отдавать циклу for:
            - особенно при переборе последовательности
            - и когда нам не нужно манипулировать счетчиком индекса и условием цикла
    4. Range и когда его применять.
       Функция range
            - позволяет создать последовательность целых чисел
            - чаще всего используется с циклом for
        Параметры функции range:
            - range(start_or_stop, stop[, step]), где
                - start_or_stop -   начало и конец последовательности (1, 1000)
                - stop -            конец   (10)
                - step -            шаг     (1, 1000, 2), где 2 - шаг
        for vs for range vs while - какой выбрать:
            - for       - перебор последовательности. Индекс не нужен
            - for range - перебор последовательности. Нужен индекс
            - for range - необходимо пропустить некоторые элементы или идти с конца в начало
            - while     - цикл связан с условием, но не с последовательностью
    5. Словари. Определение. Методы. Перебор.
        Словарь dict:
            - к словарям относятся неупорядочные коллекции произвольных объектов с доступом по ключу.
            - объявление словаря -      my_dict = {key1: val1, key2: val2, ...} - указываем пары (ключ: значение)
            - все ключи - уникальны и с одним ключом может быть только одно значение
        Основные действия со словарем:
            - friend['name']            - получение элемента по ключу
            - friend['has_car'] = True  - добавление значения или изменение значения
            - remove friend['age']      - удаление элемента по ключу ???
            - del friend['age']         - удаление пары ключ: значение
            - оператор in 'age' in friend       например for in 'age' in friend: (какое либо действие, например - print("OK"))
        Варианты перебора словаря:
            - по ключам                 for key in friend.keys():       или  for key in friend:         // одно и то же
                                            print(key)          // получим все ключи (наименование ключей)
                                            print(friend[key])  // получим все значения (наименование значений)

            - по значениям              for val in friend.values():
                                            print(val)          // получим все значения (наименование значений)

            - по парам ключ, значение   for item in friend.items():
                                            print(item)         // получим значение пары в виде кортежа
                                        for key, val in friend.items():// такая запись разбивает пару на ключ и значение отдельно
                                            print(key)
                                            print(val)
    6. Множества. Методы. Применение.
        Множество set:
            - к множествам относятся неупорядочные коллекции, содержащие не повторяющиеся элементы - во множестве не может быть двух одинаковых элементов
            - объявление множества  sities = {'Las Vegas', 'Paris', 'Moscow'}
        Действия со множествами:
            - cities.add('Burma')       - добавление элемента. При добавлении дублирующего элемента - множество не изменится
            - cities.remove(Moscow')    - удаление элемента
            - len(cities)               - длина множества
            - оператор in, цикл for
            - работа с несколькими множествами (объединение, пересечение, ...)
        Операции со множествами:
            - объединение   |       // получим неповторяющиеся элементы
            - пересечение   &       // получим повторяющиеся элементы
            - разность      -       // получим отличия множеств друг от друга (поочередно вычитая один из другого)
            - существуют и другие методы и операции
### Урок 5. Разбор практического задания
    Практическое задание к уроку 4:
        1: Даны два произвольные списка. Удалите из первого списка элементы присутствующие во втором списке.
            Примечание. Списки создайте вручную, например так:
        my_list_1 = [2, 5, 8, 2, 12, 12, 4]
        my_list_2 = [2, 7, 12, 3]

        2: Дана дата в формате dd.mm.yyyy, например: 02.11.2013. Ваша задача — вывести дату в текстовом виде, например: второе ноября 2013 года. Склонением пренебречь (2000 года, 2010 года)
        3: Дан список заполненный произвольными целыми числами.
        Получите новый список, элементами которого будут только уникальные элементы исходного.
            Примечание. Списки создайте вручную, например так:
        my_list_1 = [2, 2, 5, 12, 8, 2, 12]

        В этом случае ответ будет:
        [5, 8]
### Урок 6. Практикум. Игра «Угадай число»
    1. Создание простой игры.
    2. Добавление уровня сложности.
    3. Игра для нескольких пользователей.
### Урок 7. Разбор практического задания
        Практическое задание к уроку 6:
        1. В этой игре человек загадывает число, а компьютер пытается его угадать.
        В начале игры человек загадывает число от 1 до 100 в уме или записывает его на листок бумаги. Компьютер начинает его отгадывать предлагая игроку варианты чисел. Если компьютер угадал число, игрок выбирает “победа”. Если компьютер назвал число меньше загаданного, игрок должен выбрать “загаданное число больше”. Если компьютер назвал число больше, игрок должен выбрать “загаданное число меньше”. Игра продолжается до тех пор пока компьютер не отгадает число.
        Пример игры:
        Допустим, пользователь загадал число 42
        `15
        35
        96
        <
        37
        74
        <
        52
        <
        42
        =`
             Примечание: Знаки “=”, “>” и “<” пользователь вводит с клавиатуры для общения с компьютером. Вы можете использовать этот способ или придумать свой.
### Урок 8. Функции
    1. Определение. Встроенные функции.
        Функция - это фрагмент программного кода (подпрограмма), к которому можно обратиться из другого места программы (Википедия).
            - Функции обычно имеют имя.
            - В Python можно создавать функции и без имени.
        Зачем нужны функции:
            - Для повторного использования кода.
            - Для создания более логичной структуры программы.
            - Для объединения нескольких небольших действий в одно.
        Полезные встроенные функции:
            - print() - вывод в консоль                     // передаем данные для вывода
            - input() - ввод с консоли                      // получаем данные в виде строки
            - type() - получение информации о типе данных   // передает переменную
            - range() - генератор последовательности        // передаем сколько, с какого элемента, можем передать шаг
            - len() - длина массива, списка, кортежа, ...   // передаем объект (строку, список и т.п.) для подсчета
            - abs() - модуль числа                          // передаем число или выражение
            - min() - минимальное значение                  // передаем список, последовательность, множества, ...
            - max() - максимальное значение                 // передаем список, последовательность, множества, ...
            - round() - округление числа                    // передаем число или выражение и количество знаков после запятой
            - sum() - сумма элементов последовательности    // передаем список, последовательность, множества, ...
            - enumerate() - нумерация последовательности    // передаем список и т.п. и число с которого стартуем (по умолчанию 0) 
    2. Создание собственных функций.
        Схема собстве й функции:
            def my_fu ):      // функция без входных параметров
                (тело нкции)
                retur es      // если надо вернуть результат
        Зачем писать свои функции:
            - Для повторного использования своего кода.
            - Для создания функционала, которого нет в стандартной библиотеке.
    3. Аргументы функции.
            - Аргументы функции — это переменные, которые функция может получить из внешнего кода.
            - Аргументы необходимы, так как функция «не видит» переменные, определённые за её границами. Поэтому нужные переменные надо передавать ей явно
            def my_func(параметр1, параметр2, ...)          // так записываются входные параметры функции
            Передача параметров может быть:
                - по порядку        my_func('Leo', 'Hello')
                - по имени          my_func(say='Hello', who='Leo')
                - по умолчанию      my_func(who, say='Hello') // если в функции не будет указан параметр say, будет по умолчанию
        args, kwargs:
            Иногда нужно реализовать передачу любого количества аргументов:
                - *args      - передача любого количества по порядку 
                    - передаем в функцию кортежем (в скобках через запятую)
                    - получаем при выводе - кортеж
                - **kwargs   - передача любого количества по имени  
                    - передаем в функцию как словарь (в скобках ключ=значение через запятую))
                    - выводит парами через пробел
    4. Области видимости.
        Область видимости:
            - В программировании обозначает область программы, в пределах которой идентификатор (имя) некоторой переменной продолжает быть связанным с этой переменной и возвращать её значение.
            - За пределами области видимости тот же самый идентификатор может быть связан с другой переменной, либо быть свободным (не связанным ни с какой из них).
            - область видимости объекта - это набор функций или модулей, внутри которых допустимо использование имени этого объекта.
        Локальные и глобальные переменные:
            - Глобальными называют объекты, объявление которых дано вне функции. Они доступны (видимы) во всем файле, в котором объявлены.
            - Локальными называют объекты, объявление которых дано внутри блока или функции. Эти объекты доступны только внутри того блока, в котором объявлены.
        global:
            - При желании можно изменить глобальную переменную
            - Для этого в функции нужно указать, что она глобальная
            - global my_var.
            - Этот механизм лучше не использовать. Мы рискуем, изменив значение переменной в одной функции, получить неверное значение в другой функции.
        Относительная область видимости:
            - в программе могут встречаться вложенные друг в друга функции
            - тогда мы рассматриваем область видимости относительно какой-либо функции
    5. Передача функции параметром в другую функцию. Лямбда-функции.
        Функция - тоже объект
            - можно записать в переменную.
            - её можно передавать параметром в другие функции.
            - Применение:
                - возможность не только входных данных, но и входных функций
                - внутри функции переменными являются:
                    - алгоритм
                    - последовательность действий
                    - сами действия
        lambda - функции:
            - применяются для создания анонимных функций по месту их использования, особенно если функция нужна - разово
            - пишется в одну строку
                lambda входные параметры: результат
        Примеры lambda - функции:
            def is_even(number):                // обычная запись функции
                return number % 2 == 0
            lambda number: number % 2 == 0      // запись lambda - функции
    6. Функции sorted, filter, map.
        sorted:
            - сортировка последовательности
            - sorted(iterable, *, key=None, reverse=False)             
                - sorted(iterable)                                      // iterable - список, кортеж, ..., отсортирует по порядку
                - sorted(iterable, reverse=True)                        // список, кортеж, ..., отсортирует в обратном порядке
                - sorted(iterable, key = my_func)                       // кортеж, ..., отсортирует по порядку по значениям ключа
                    Например:
                        cities = [('Москва', 1000), ('Лас-Вегас', 500), ('Екатеринбург', 2000)]
                        def my_func(city):
                            return city[1]
                        sorted(cities, key=my_func) или  sorted(cities, key=lambda city: city[1])
            - аргументы: последовательность, ключ для сортировки, порядок
        filter:
            - фильтрация последовательности
            - filter(function, iterable)        // function должна иметь либо True, либо False
            - аргументы: функция фильтрации, последовательность
                Например:
                    print(list(filter(lambda x: len(x)>3, names)))
        map:
            - применение функции к каждому элементу последовательности, т.е. она не фильтрует последовательность, а создает какую-то новую последовательность
            - map(func, iterable, ...)
            - аргументы: функция, последовательность
                Например:
                    print(list(map(lambda x: x**2), numbers)) 
        sorted, filter, map:
            - применяются к последовательности
            - имеют параметр - функцию
            - позволяют создавать код быстро и удобно
### Урок 9. Разбор практического задания
    Практическое задание
        1: Создайте функцию, принимающую на вход имя, возраст и город проживания человека. Функция должна возвращать строку вида «Василий, 21 год(а), проживает в городе Москва»
        2: Создайте функцию, принимающую на вход 3 числа и возвращающую наибольшее из них.
        3: Давайте опишем пару сущностей player и enemy через словарь, который будет иметь ключи и значения:
        name - строка полученная от пользователя,
        health = 100,
        damage = 50. ### Поэкспериментируйте с значениями урона и жизней по желанию. ### Теперь надо создать функцию attack(person1, person2). Примечание: имена аргументов можете указать свои. ### Функция в качестве аргумента будет принимать атакующего и атакуемого. ### В теле функция должна получить параметр damage атакующего и отнять это количество от health атакуемого. Функция должна сама работать со словарями и изменять их значения.
        4: Давайте усложним предыдущее задание. Измените сущности, добавив новый параметр - armor = 1.2 (величина брони персонажа)
        Теперь надо добавить новую функцию, которая будет вычислять и возвращать полученный урон по формуле damage / armor
        Следовательно, у вас должно быть 2 функции:
        Наносит урон. Это улучшенная версия функции из задачи 3.
        Вычисляет урон по отношению к броне.
        Примечание. Функция номер 2 используется внутри функции номер 1 для вычисления урона и вычитания его из здоровья персонажа. 
### Урок 10. Модули и библиотеки
        1. Модули. Определение. Применение. Подключение модулей.
            Определение модуля:
                - Python позволяет поместить классы, функции, данные а также скрипты в отдельный файл и использовать их в других программах.
                - Модулем в Python называется любой файл с программой.
            Зачем нужны модули:
                - Повторное использование кода.
                - Управление пространством имен.
                - Деление большого проекта на мелкие части.
            Разновидности модулей:
                - встроенные (math, random, ...)
                - сторонние (django, PyQt5, ...)
                - свои (любой .py файл)
                - между своими и сторонними модулями нет принципиальной разницы, отличие только в авторе
            Варианты подключения:
                - модуль целиком import repository1 as rp
                - модуль целиком import repository2
                - rp.insert_phone - функции могут работаь по разному repository2.insert_phone
                - псевдоним для модуля import math as mt
                - импорт всего содержания from math import * (не рекомендуется)
                - импорт конкретных функций, классов, … from math import sin, cos
        2. Стандартные модули math, random.
            Библиотека math
                Использование math
                    - Математические функции.
                    - Работа с числами.
                Основные функции math
                    - factorial - факториал числа
                    - exp - экспонента
                    - log, log2, log10 - логарифмы
                    - sqrt - квадратный корень
                    - sin, cos, asin, asoc, ...
                    - и многие другие
            Библиотека random
                Использование random
                    - Генерация случайных чисел
                    - Букв
                    - Элементов последовательности
                Основные функции random
                    - randint - целое случайное число от A до B
                    - choice - случайный элемент последовательности
                    - shuffle - перемешивает последовательность
                    - random - случайное число от 0 до 1
                    - sample - список длиной k из последовательности
                    - и многие другие
        3. Создание собственных модулей.
            Создание своего модуля

            Импорт данных из своего модуля:
                - Совершается так же, как и из стандартных модулей
                - При импорте нужно учитывать путь до модуля
                    Примеры:
                        import firstmodule
                        import folder.secondmodule
            Модули со скриптами:
                - При любом варианте импорта скрипты будут выполняться
                - Если не указано никаких условий (if __name__ == ‘__main__’)
                - Это обязательно нужно учитывать при импорте
            if __name__ == ‘__main__’
                - Ограничивает выполнение скриптов
                - При импорте код не будет выполняться
                - Он будет выполняться при запуске модуля
        4. Пакеты.
            Определение пакета:
                - Пакет - каталог, включающий в себя другие пакеты и модули
                - Пакет содержит файл __init__.py
            Назначение пакета:
                - Формирование пространства имен
                - Работа с модулями с указанием уровня вложенности
                - пакет1.пакет2.модуль
                - Уровни отделяются точкой
            Варианты импортов:
                - import .модуль - внутри пакета из одного модуля в другой
                - import пакет.модуль - стандартно
                - import, from, as ...
                - вложенность пакетов может быть любой (пакет в пакете ...)
        5. Модули os, sys.
            Модуль os:
                - Функции для работы с операционной системой
                - Не зависит от конкретной ОС
                Функции и переменные os:
                    - name - имя операционной системы
                    - chdir - смена текущей директории 
                    - getcwd() - текущая рабочая директория
                    - mkdir() - создание директории (папки)
                    - os.path - модуль для работы с путями 
                    - и многие другие
            Модуль sys:
                - Взаимодействие с интерпретатором Python
                Функции и переменные sys:
                    - executable - путь к интерпретатору Python
                    - exit() - выход из Python
                    - platform - информация об ОС
                    - path - список путей поиска модулей
                        sys.path:
                            - очень важная переменная
                            - она хранит пути? по которым Python ищет модули
                            - она имеет изменяемый тип данных list
                            - таким образом мы можем изменять эту переменную
                    - argv - список аргументов командной строки
                    - и многие другие
        6. Запуск скрипта с параметрами.
            sys.argv:
                - список аргументов командной строки при запуске скрипта Python
                - sys.argv[0] - путь до скрипта
                - остальные параметры передаются при вызове скрипта через пробел
                - python my_script.py par1 par2 par3 ...    