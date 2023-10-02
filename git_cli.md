# <span style="color:red"> __Git__</p>

## Git это - одна из реалицаций распределённой системы управления версиями на локальном или удаленном репозитории.

### Основные команды git для настройки и окружения

### Основные команды git для работы с репозитарием (Добавление и отслеживание)
|<span style="color:orange"><div style="width:160px"> __команда__ </div></span>      |<span style="color:orange">*описание*</span>
|                -                |                 -                                       |
|<span style="color:yellow"> __git__ <span style="color:green"> __init__</span>|<span style="color:orange">*Инициализирует локальный католог, как  репозиторий*</span>|
|<span style="color:yellow"> __git__   <span style="color:green">__add__ <span style="color:red"> *<имя_файла>* |<span style="color:orange">*Добавление файла в репозиторий для отслеживания* </span>|
|<span style="color:yellow"> __git__   <span style="color:green">__rm__ <span style="color:red"> *<имя файла>* |<span style="color:orange">*Отключает наблюдение за файлом в репозитории* </span>|
|<span style="color:yellow"> __git__   <span style="color:green"> __status__</span>|<span style="color:orange">*Выводит состояние проекта, измененные и не добавленные файлы, индексированные файлы*</span>|
|<span style="color:yellow"> __git__   <span style="color:green"> __commit__</span>|<span style="color:orange">*Совершение коммита*</span>|
|<span style="color:yellow">__git__   <span style="color:green">__commit__<span style="color:red">  __-a__</span>|<span style="color:orange">*При указание ключа <span style="color:red"> -а </span> совершит коммит, автоматически индексируя изменения в файлах проекта. Новые файлы при этом индексироваться **не будут!** Удаление же файлов будет учтено.*</span>|
|<span style="color:yellow"> __git   <span style="color:green"> __commit__ <span style="color:red">-a -m "text"__</span>|<span style="color:orange">*Совершение коммита c ключами* <span style="color:red">*-a -m "text"*</span> позволяет задать заголовок для него|
|<span style="color:yellow"> __git__<span style="color:green"> __log__</span>|<span style="color:orange">*Выводит разнообразну информация о коммитах в целом, по отдельным файлам и различной глубины погружения в историю*</span>|
|<span style="color:yellow"> __git__<span style="color:green"> __log__<span style="color:red">  __-p__</span>|<span style="color:orange">*Получить подробную информацию о каждом в виде патчей по файлам из коммитов можно, добавив ключ <span style="color:red">-p (или -u)*</span>|
|<span style="color:yellow"> __git__<span style="color:green"> __log__<span style="color:red">  __--stat__</span>|<span style="color:orange">*Статистика изменения файлов, вроде числа измененных файлов, внесенных в них строк, удаленных файлов вызывается ключом <span style="color:red">--stat*</span>|
|<span style="color:yellow"> __git__ <span style="color:green"> __log__<span style="color:red">  __--summary__</span>|<span style="color:orange">*За информацию по созданиям, переименованиям и правам доступа файлов отвечает ключ <span style="color:red">__--summary__* </span>|
|<span style="color:yellow"> __git__ <span style="color:green"> __log__<span style="color:red"> __--oneline__</span>|<span style="color:orange">*Показывает лог  commit в одну строчку, после угазания ключа <span style="color:red">__--oneline__* </span>|
|<span style="color:yellow"> __git__ <span style="color:green">__log__<span style="color:red"> __--graph__</span>|<span style="color:orange">*Показывает лог c использованием графического вида* </span>|

### Основные команды git для работы с репозитарием (Ветвление и слияние)
