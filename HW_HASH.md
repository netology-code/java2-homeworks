# Домашнее задание к занятию "Коллекция HashMap и HashSet"

## Цель задания

1. Научиться использовать мапы
2. Правильно настраивать классы для корректной работы в качестве ключей в `HashMap`

------

## Инструкция к заданию

1. Для каждой задачи создайте отдельный реплит, если об обратном не сказано в условии
1. Саму программу вы пишете в IDEA, реплит используется только для сдачи кода
3. В окне редактора IDEA наберите программный код, решающий поставленную задачу
5. Загружаете файлы из папки src проекта в реплит
6. Отправьте выполненную работу на проверку в личном кабинете Нетологии

------

## Материалы, которые пригодятся для выполнения задания

1. [Как поделиться реплитом для проверки?](https://github.com/netology-code/java2-homeworks/blob/main/QA_ReplitShare.md)
2. [Как автоотформатировать код?](https://github.com/netology-code/java2-homeworks/blob/main/QA_Format.md)
3. [Как залить проект из идеи в реплит?](https://github.com/netology-code/java2-homeworks/blob/main/QA_ReplitUpload.md)

------

## Задание 1 (обязательное)

Вашей задачей будет написание сервиса услуг доставки товаров по миру.

Адрес доставки будет задаваться двумя данными: страна (`country`) и город (`city`).
Создайте для этих целей класс `Address`.

В `main` создайте несколько адресов и мапу `costPerAddress`, в которой ключом будет адрес, а значением - цена доставки 1 кг. груза.
Заполните мапу созданными адресами и произвольными значениями цен доставки по этим адресам.

Далее в цикле пользователь вводит заказы (или end). Каждый заказ состоит из трёх частей: страны, города и веса (в кг.) доставляемого товара.
В ответ нужно либо написать, что такой адрес не обслуживается, либо написать стоимость доставки и общую сумму всех сделанных доставок.

### Пример работы программы
```text
...

Заполнение нового заказа.
Введите страну: Росссия
Введите город: Казань
Введите вес (кг): 13
Стоимость доставки составит: 2600 руб.
Общая стоимость всех доставок: 12600 руб.

Заполнение нового заказа.
Введите страну: Росссия
Введите город: Лысые Пеньки
Введите вес (кг): 3
Доставки по этому адресу нет
```

------

## Задание 2 (обязательное)

:warning: _Эта задача - усложнение первой задачи, поэтому делается в том же реплите. Как итог вы сдаёте один реплит, в которой либо первая, либо вторая задача._

Добавьте помимо общей суммы вывод информации о том, в какое количество уникальных стран были оформлены доставки.
Уникальность означает, что если по России было отправлено, например, три заказа, то учитываться это должно как одна страна.

------

## Правила приема работы

Прикреплена ссылка на реплит с решением задачи.

------

## Критерии оценки

1. Программа запускается и отрабатывает без ошибок
2. Программа соответствует всем требованиям из условия задачи
3. Программа работает правильно на всех примерах из условия
4. Программный код отформатирован и соответствует пройденным требованиям к качеству кода
5. Программа спроектирована достаточно логично и правильно, не противоречит общепринятым в производстве практикам и традициям
6. При наличии недочётов, в зависимости от их серьёзности и количества, работа может быть отправлена на доработку или принята; решение принимается на основе экспертной оценки работы.