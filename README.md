# practice

### Учебная практика

Задание:  
Библиотека должна реализовать следующие операции очистки и преобразования данных:

- корректировка пропущенных значений с возможностью выбора одного из вариантов: игнорирование пропущенного значения, заполнение значением по умолчанию, заполнение средним;

- нормализация – приведение к единой шкале измерения. Например, в одном файле данные приведены в килограммах, а в выходном требуются в фунтах. Коэффициенты преобразования должны хранится в конфигурационных файлах или настраиваться через GUI;

- удаления дубликатов данных. Каждая строка данных характеризуется временной меткой. Библиотека должна удалять данные с одним временем.

- выявление выбросов (аномалий). На выбор - использованием статистических тестов (Z-оценка) , метрических или итерационных методов;

- выявление зашумленных данных* средствами кластерного анализа.

- редукция. Для уменьшения вычислительной сложности должен поддерживаться функционал удаления избыточных признаков (столбцов) на основе Хи-квадрат теста.

Входные данные:

Разнородный набор данных (категориальные и не категориальные, имеются пропуски) в формате CSV. Файл: NFA 2018.csv

Выходные данные:

Исходный набор данных в формате CSV, очищенный от пропусков и дубликатов.
