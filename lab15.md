# РОССИЙСКИЙ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ
### Факультет физико-математических и естественных наук

***ОТЧЕТ*** 

***ЛАБОРАТОРНОЙ РАБОТЕ №15***

1. дисциплина:	Операционные системы	
   
Студент: Хайдари Ахмад Насир                                 

Группа: НБИбд 01-20

### Цель работы

Приобретение практических навыков работы с именованными каналами.

### Ход работы:

1. Изучил приведённые в тексте программы server.c и client.c и взяла данные примеры за образец.
   
   <a href="https://wampi.ru/image/RAwcs2g"><img src="https://ia.wampi.ru/2021/09/12/1.png" alt="1.png" border="0"></a>

   * common.h
<a href="https://wampi.ru/image/RAwcCp0"><img src="https://ic.wampi.ru/2021/09/12/2.png" alt="2.png" border="0"></a>

* server.c
 <a href="https://wampi.ru/image/RAvo8On"><img src="https://ic.wampi.ru/2021/09/12/3.png" alt="3.png" border="0"></a>

 * client.c
   <a href="https://wampi.ru/image/RAvotv7"><img src="https://ic.wampi.ru/2021/09/12/4.png" alt="4.png" border="0"></a>


   2. Написал аналогичные программы, внеся следующие изменения:
- работает не 1 клиент, а несколько (например, два).
- клиенты передают текущее время с некоторой периодичностью (например, раз в пять секунд). Использовал функцию sleep() для приостановки работы клиента.
- сервер работает не бесконечно, а прекращает работу через некоторое время (например, 30 сек). Использовал функцию clock() для определения времени работы
сервера.


* makefile, написал *make* для активации кода.

* Результаты:
я не мог дать результат из этой лаборатории, меня пытались. но, к сожалению, я не получил.

<a href="https://wampi.ru/image/RAwdckc"><img src="https://ia.wampi.ru/2021/09/12/last.png" alt="last.png" border="0"></a>


----

### Вывод

Практических навыков работы с так называемыми трубами не получил. 

----