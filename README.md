# <span style="color:red"> __Git__<div style="width:300px">![Git logo](git.png) </div></p>

## <span style="color:red">__Git__</span> это - реалицаций распределённой системы управления версиями на локальном или удаленном репозитории.

### Основные команды git для настройки и окружения
|<span style="color:orange"><div style="width:160px"> __команда__ </div></span>      |<span style="color:orange">*описание*</span>
|                -                |                 -                                       |
|<span style="color:yellow"> __git__ <span style="color:green"> __config__<span style="color:red">  __--global user.email "[valid-email]”__</span>|<span style="color:orange">*Вносим в систему Git контактную информацию укажите ваш действующей e-mail* </span>|
|<span style="color:yellow"> __git__ <span style="color:green"> __config__<span style="color:red">  __--global user.name  “[firstname lastname]”__</span>|<span style="color:orange">*Вносим в систему Git контактную информацию укажите ваш имя* </span>|
|<span style="color:yellow"> __git__ <span style="color:green"> __config__<span style="color:red">  __--global color.ui auto__</span>|<span style="color:orange">*установливает автоматическую раскраску командной строки для Git для удобства просмотра* </span>|
|<span style="color:yellow"> __git__ <span style="color:green"> __config__<span style="color:red">  __--global alias.st status__</span>|<span style="color:orange">*Данной командой можно присвоить команде <span style="color:red">status</span> сокращение <span style="color:red">st* </span>|
|<span style="color:yellow"> __git__ <span style="color:green"> __config__<span style="color:red">  __--list__</span>|<span style="color:orange">*Просмотр настроек в виде списка* </span>|

### Основные команды git для работы с репозитарием (Добавление файлов и управление комитами )
|<span style="color:orange"><div style="width:160px"> __команда__ </div></span>      |<span style="color:orange">*описание*</span>
|                -                |                 -                                       |
|<span style="color:yellow"> __git__ <span style="color:green"> __init__</span>|<span style="color:orange">*Инициализирует локальный католог, как  репозиторий*</span>|
|<span style="color:yellow"> __git__   <span style="color:green">__add__ <span style="color:red"> *<имя_файла>* |<span style="color:orange">*Добавление файла в репозиторий для отслеживания* </span>|
|<span style="color:yellow"> __git__   <span style="color:green">__rm__ <span style="color:red"> *<имя файла>* |<span style="color:orange">*Отключает наблюдение за файлом в репозитории* </span>|
|<span style="color:yellow"> __git__   <span style="color:green">__ignore__ |<span style="color:orange">*созданый текстовый файл .gitignore, который используется для указания файлов и каталогов, которые GIT должен игнорировать, а не отслеживать. Это предотвращает включение конкретных файлов или шаблонов в контроль версий.* </span>|
|<span style="color:yellow"> __touch__   <span style="color:green">__.gitkeep__|<span style="color:orange">*создаёт текстовый файл .gitkeep, который используется для указания в нем имен папок.Сохранения пустых каталогов в репозитории GIT. Это не влияет на отслеживание файлов GIT; Его роль состоит в том, чтобы обеспечить сохранение пустых каталогов.* </span>|
|<span style="color:yellow"> __git__   <span style="color:green"> __status__</span>|<span style="color:orange">*Выводит состояние проекта, измененные и не добавленные файлы, индексированные файлы*</span>|
|<span style="color:yellow"> __git__   <span style="color:green"> __commit__</span>|<span style="color:orange">*Совершение коммита*</span>|
|<span style="color:yellow">__git__   <span style="color:green">__commit__<span style="color:red">  __-a__</span>|<span style="color:orange">*При указание ключа <span style="color:red"> -а </span> совершит коммит, автоматически индексируя изменения в файлах проекта. Новые файлы при этом индексироваться **не будут!** Удаление же файлов будет учтено.*</span>|
|<span style="color:yellow"> __git   <span style="color:green"> __commit__ <span style="color:red">-a -m "text"__</span>|<span style="color:orange">*Совершение коммита c ключами* <span style="color:red">*-a -m "text"*</span> позволяет задать заголовок для него|
|<span style="color:yellow"> __git__ <span style="color:green"> __reset__   <span style="color:red">\<name hesh> </span>|<span style="color:orange">*Возвращаемся на хеш с нужным именем и отменяем предыдущие коммиты* <span style="color:yellow"></span> |
|<span style="color:yellow"> __git__ <span style="color:green"> __revert__   <span style="color:red">\<name hesh> </span>|<span style="color:orange">*Отменение какого либо коммита по имени хеша* <span style="color:yellow"></span> |
|<span style="color:yellow"> __git__ <span style="color:green"> __restore__   <span style="color:red">\<name file> </span>|<span style="color:orange">*Отменяет последний коммит с разными параметрами(оставляет изменения и файлы, сохранение текущий изменений и удаление изменений последнего комита, удаление всех изменений и возврат к предыдущему коммиту )* <span style="color:yellow"></span> |

### Основные команды git для работы с репозитарием (логирование и статус )
|<span style="color:orange"><div style="width:160px"> __команда__ </div></span>      |<span style="color:orange">*описание*</span>
|                -                |                 -                                       |
|<span style="color:yellow"> __git__<span style="color:green"> __log__</span>|<span style="color:orange">*Выводит разнообразну информация о коммитах в целом, по отдельным файлам и различной глубины погружения в историю*</span>|
|<span style="color:yellow"> __git__<span style="color:green"> __log__<span style="color:red">  __-p__</span>|<span style="color:orange">*Получить подробную информацию о каждом в виде патчей по файлам из коммитов можно, добавив ключ <span style="color:red">-p (или -u)*</span>|
|<span style="color:yellow"> __git__<span style="color:green"> __log__<span style="color:red">  __--stat__</span>|<span style="color:orange">*Статистика изменения файлов, вроде числа измененных файлов, внесенных в них строк, удаленных файлов вызывается ключом <span style="color:red">--stat*</span>|
|<span style="color:yellow"> __git__ <span style="color:green"> __log__<span style="color:red">  __--summary__</span>|<span style="color:orange">*За информацию по созданиям, переименованиям и правам доступа файлов отвечает ключ <span style="color:red">__--summary__* </span>|
|<span style="color:yellow"> __git__ <span style="color:green"> __log__<span style="color:red"> __--oneline__</span>|<span style="color:orange">*Показывает лог  commit в одну строчку, после угазания ключа <span style="color:red">__--oneline__* </span>|
|<span style="color:yellow"> __git__ <span style="color:green">__log__<span style="color:red"> __--graph__</span>|<span style="color:orange">*Показывает лог c использованием графического вида* </span>|
|<span style="color:yellow"> __git__<span style="color:green"> __reflog__</span>|<span style="color:orange">*Выводит информация о всех действиях, в том числе об отмене коммитов*</span>|

### Основные команды git для работы с репозитарием (Ветвление и слияние)
|<span style="color:orange"><div style="width:160px"> __команда__ </div></span>      |<span style="color:orange">*описание*</span>
|                -                |                 -                                       |
|<span style="color:yellow"> __git__ <span style="color:green"> __branch__</span>|<span style="color:orange">*Показывает список веток и текущую отмеченной* (<span style="color:yellow">\*</span>) |
|<span style="color:yellow"> __git__ <span style="color:green"> __branch__<span style="color:red">  __\<name>__</span>|<span style="color:orange">*Создание новой ветки с именем <span style="color:red">name* </span>|
|<span style="color:yellow"> __git__ <span style="color:green"> __checkout__<span style="color:red">  __-b \<name>__</span>|<span style="color:orange">*Создание новой ветки с именем <span style="color:red">name* <span style="color:orange">*и переключением на нее*|
|<span style="color:yellow"> __git__ <span style="color:green"> __checkout__<span style="color:red">  __\<name>__</span>|<span style="color:orange">*Переключение на ветку <span style="color:red">name* |
|<span style="color:yellow"> __git__ <span style="color:green"> __merge__<span style="color:red">  __\<name>__</span>|<span style="color:orange">*Вливание в текущую ветку <- ветки с именем( <span style="color:red">name* <span style="color:orange">)|

### Основные команды git для работы с репозитарием (Работа с удаленным репозиторием)

|<span style="color:orange"><div style="width:240px"> __команда__ </div></span>      |<span style="color:orange">*описание*</span>
|                -                |                 -                                       |
|<span style="color:yellow"> __git__ <span style="color:green"> __remote add origin__<span style="color:red">  __\<URL project>__</span>|<span style="color:orange">*подключаем удаленный репозиторий( <span style="color:red">URL repo* <span style="color:orange">)|
|<span style="color:yellow"> __git__ <span style="color:green"> __remote__<span style="color:red">  __\-v__</span>|<span style="color:orange">*Просмотр адресов для чтения и записи, привязанные к репозиторию( <span style="color:red">URL repo* <span style="color:orange">)|
|<span style="color:yellow"> __git__<span style="color:green"> __push__</span>|<span style="color:orange">*Отправляет на удаленный репозитарий локальную версию*</span>|
|<span style="color:yellow"> __git__<span style="color:green"> __pull__</span>|<span style="color:orange">*Копирует удаленый репозиторий в локальный с функцией merge*</span>|
|<span style="color:yellow"> __git__ <span style="color:green"> __clone__<span style="color:red">  __\<URL project>__</span>|<span style="color:orange">*Копируем удаленный репозиторий в свою текущую локальную папку( <span style="color:red">URL repo* <span style="color:orange">)|
