# Описание
---
Всё находится в 3х файлах. Чтобы скачать, надо найти кнопку Download 
и нажать "Скачать zip", потом распаковать и использовать, открыв папку 
в pycharm или еще где.

1. `index.py`
Основной файл, к нему подключены 2 других файла.

2. `modules/connect.py`
Файл, в котором собраны функции, в которых используется библиотека pandas

3. `modules/processing.py`
Файл, в котором собраны функции, которые делают основную работу - структурируют ячейки.

# Как запустить
---

- Установить библиотеки. 
Скорее всего, они уже все у вас будут, но лучше подстраховаться.
Команда в консоли:
```
pip install -r requirements.txt
```
У меня есть подозрения, что pycharm сделает снова в этом проекте локальное место для библиотек, поэтому, если эта команда не сработает, можно попробовать перейти в папку в консоли сначала (скиньте папку разархивированную на рабочий стол и переименуйте ее в "Anya" для удобства (но можно во что угодно))
``` 
cd Desktop
cd Anya
```
Теперь вы вошли в папку. 
Вообще, я работала с python3 (pip3), но, вроде, просто для pip тоже
должно работать.

- Открыть файл index.py и запустить его

> Основная работа была в файле processing.py, но запускать надо index.py, он как-бы объединяет все файлы, является главным. И если что-то изменили в каком-то файле, запускать все равно index.py.

По умолчанию результаты в файле excel/output4.xlsx
