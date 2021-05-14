
## **РОССИЙСКИЙ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ**
### **Факультет физико-математических и естественных наук**
### **Кафедра прикладной информатики и теории вероятностей**

### ОТЧЕТ
### ПО ЛАБОРАТОРНОЙ РАБОТЕ № 8
### Дисциплина: Операционные системы 


#### Студент: Боровикова Карина Владимировна
#### Преподаватель: Валиева Т. В.
#### Группа: НПИбд-01–20

### МОСКВА
### 2021 г.

**Цель работы:** 
Освоение основных возможностей командной оболочки Midnight Commander. Приобретение навыков практической работы по просмотру каталогов и файлов; манипуляций с ними.

**Объект исследования:** 
Операционная система Linux.

**Предмет исследования:**
Процесс работы с командной строкой и базовыми приложениями

**Техническое оснащение:**
Ноутбук с характеристиками и вводными данными:
- AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx, 2100 МГц, 8 Гб оперативной памяти, 12 Гб свободного места на жестком диске.
- ОС Майкрософт Windows 10 Домашняя для одного языка.
- VirtualBox версии 6.1.
- Дистрибутив Linux CentOS-7 для установки в виртуальную машину.

**Теоретические данные:**

*``Командная оболочка``* — интерфейс взаимодействия пользователя с операционной системой и программным обеспечением посредством команд.

*``Midnight Commander (или mc)``* — псевдографическая командная оболочка для UNIX/Linux систем.

Взаимодействия с`` mc``:

- ``F1`` - Вызов контекстно-зависимой подсказки

- ``F2`` - Вызов пользовательского меню с возможностью создания и/или дополнения дополнительных функций

- ``F3`` - Просмотр содержимого файла, на который указывает подсветка в активной панели (без возможности редактирования)

- ``F4`` - Вызов встроенного в mc редактора для изменения содержания файла, на который указывает подсветка в активной панели

- ``F5`` - Копирование одного или нескольких файлов, отмеченных в первой (активной) панели, в каталог, отображаемый на второй панели

- ``F6`` - Перенос одного или нескольких файлов, отмеченных в первой (активной) панели, в каталог, отображаемый на второй панели

- ``F7`` - Создание подкаталога в каталоге, отображаемом в активной панели

- ``F8`` - Удаление одного или нескольких файлов (каталогов), отмеченных в первой (активной) панели файлов

- ``F9`` - Вызов меню mc

- ``F10`` - Выход из mc

Более подробную информацию о горячих клавишах Midnight Commander можно получить из интернета.

**Условные обозначения:**
-   ``MC`` - Midmight Commander.


### **Ход выполнения работы:**

# **Задание по mc**

1. **Изучите информацию о mc, вызвав в командной строке man mc. (Рисунок 1)**

![](https://sun9-24.userapi.com/impg/7fGZh8npPg1ezyzwm6oXVVArDYJOpreLM_HYdg/iwKBRAlKC5o.jpg?size=755x498&quality=96&sign=c416fe874c17dadd38bb33b93bfc6a4a&type=album)

*Рисунок 1. Изучаю ``man mc``*

2. **Запустите из командной строки mc, изучите его структуру и меню. (Рисунок 2)**

Midnight commander имеет 2 пенели, на них отображаются все файлы и каталоги домашнего каталога, меню,с помощью которого управляем файлами, каталогами, настройками и прочим (рисунок 2).

![](https://sun9-11.userapi.com/impg/CCZeCBoYaWCWU2lz5E17LHqnxZSNmGL7I8LXng/4WrqD2r4j1w.jpg?size=768x724&quality=96&sign=e4fd5f8cdb515643bdfffde514eff2a3&type=album)

*Рисунок 2. Запускаю ``mc`` из командной строки, изучаю его структуру и меню.*

3. **Выполните несколько операций в mc, используя управляющие клавиши**

### **Операции с панелями**

- Меняю панели местами нажатием клавиш ``Ctrl + u`` или нажатием кнопки в mc "поменять панели местами"(Рисунок 3);

    ![](https://sun9-3.userapi.com/impg/Ct-VH3OibqeGbvnEHGBdv7cvOhCUAvu7Lm8rtw/nSqH3SfzQ5c.jpg?size=759x711&quality=96&sign=707159025f25db26333af17890a3b945&type=album)

    *Рисунок 3. Нажимаю ``Ctrl + u``. Панели поменялись местами.*

- Временно отключаю панели, используя клавиши ``Ctrl + o``(Рисунок 4);

    ![](https://sun9-72.userapi.com/impg/rQJ7voG4Usb2ICPVwyIoNf2FqrvCCMEgcPqNFA/TBY6Ox_QYzA.jpg?size=757x762&quality=96&sign=d9936d56ff654ce7d85875360badc3dc&type=album)

    *Рисунок 4. Нажимаю ``Ctrl + o``. Панели отклчились.*

- Gроизводим сравнение каталогов нажатием ``Ctrl + x + d``(Рисунок 5);

    ![](https://sun9-39.userapi.com/impg/C581S7qPq_J6RUT76Y6cqnXLVlu9QBhPEXyivg/YruiS5TyH5k.jpg?size=596x132&quality=96&sign=49d4ea010b954dffd6b5c64463d29271&type=album)

    *Рисунок 5. Нажимаю ``Ctrl + x + d``. Открылась панель сравнения каталогов.*



- Переводим панели в режим "Быстрый просмотр"(Рисунок 6), "Информация" (Рисунок 7) или "Дерево" (Рисунок 8) используя панель управления mc.

    ![](https://sun9-41.userapi.com/impg/hJGxIHNhBu3nvDuSzQ2tuBaoZRQpnx0oqOK-2g/BAk2CtZ6j64.jpg?size=768x763&quality=96&sign=8e4ea0de523b2e439c15fe833c8afa74&type=album)

    *Рисунок 6. Перевожу правую панель в режим "Быстрый просмотр".


    ![](https://sun9-74.userapi.com/impg/6s0sdlGZ99B4zhI899YXLcntTtzBSWRh0zGOig/BKs0Pf5nsuY.jpg?size=752x615&quality=96&sign=edaf8397ee82b1b65f307953329ce8b2&type=album)

    **Рисунок 7. Перевожу панель в режим "Информация".*


    ![](https://sun9-16.userapi.com/impg/j9WLNu-EiPgHj05z01TrfX8p0kFq008HuZyuQQ/8wCtgsR4HIA.jpg?size=744x648&quality=96&sign=3a622b6ad09d1fef92f474b3660cc787&type=album)

    **Рисунок 8. Перевожу панель в режим "Дерево".*

 ### **Выделение/отмена выделения файлов**

- Выделение файлов и отмена выделения файлов происходят с помощью выделения курсором определенного нужного нам файла и нажатием клавиши ``insert`` (Рисунок 9).

    ![](https://sun9-25.userapi.com/impg/WS-Psw84a0sHo7gP2m7AZf-slWRQFFRannIdLw/eQIVtkBxptc.jpg?size=451x386&quality=96&sign=418940e8c8268178ad5eae00ff4869db&type=album)

    **Рисунок 9. Выделяю файл .bash_logout.*

### **Копирование файлов**
- Копировние файлов выполняется с помощью выделения файла (см. предыдущий пункт) и нажатия клавиши ``F5``(Рисунок 10.).

    ![](https://sun9-9.userapi.com/impg/8tHtEMxkLy_9UbpbjOttDZSyu4Vo6HQg1pknbA/qGBrzh_l2LU.jpg?size=680x275&quality=96&sign=3dbae1c6f86984946a17dbb80d0a7bc9&type=album)

    *Рисунок 10. Окно копирования файла.*

- Группу файлов можно выделить, дополнительно нажав ``+``. Снять выделение можно, нажав ``/`` (Рисунок 11).

    ![](https://sun9-28.userapi.com/impg/IbqL8u7WpTM6qlgMjt5JP8xge5ukPiwPOWu5Lw/3r-pbUPUQtE.jpg?size=476x143&quality=96&sign=c060000ea022517a66a943240e906ab5&type=album)

    *Рисунок 11. Отмечаем группу файлов*

### **Перемещение файлов**

Перемещение файлов выполняется с помощью выделения файла (см. предыдущий пункт) и нажатия клавиши ``F6`` (Рисунок 12)

![](https://sun9-10.userapi.com/impg/Ajw222b8G-_Ekx9MyZvFcjHKHpx9HaPOaX3ciQ/rWnIUKmaYXg.jpg?size=686x276&quality=96&sign=5355a245fb8952bbc3310f6e6493b184&type=album)

*Рисунок 12. Окно перемещения файлов*

### **Получение информации о размере и правах доступа на файлы и/или каталоги**.

Получение информации о размере и правах доступа на файлы и/или каталоги происходит с помощью открытия вкладок ``Файл`` -> ``Права доступа``.

![](https://sun9-45.userapi.com/impg/fcZ3iPlQFeuv027TgkdOR18kvDobnuu9FvO_7Q/PNG6XosNVWg.jpg?size=641x451&quality=96&sign=7b7e63497720fe12597ad88012b0ee75&type=album)

*Рисунок 13. Получаем информацию*

4. **Выполните основные команды меню левой (или правой) панели. Оцените степень подробности вывода информации о файлах.**


    Для этого будем менять команды в правой панели, а в левой будем выбирать файл.

    - Быстрый просмотр. Данная опция позволяет нам просмотреть содержимое файла прямо в панели, не открывая его (рисунок 14).
    ![](https://sun9-41.userapi.com/impg/hJGxIHNhBu3nvDuSzQ2tuBaoZRQpnx0oqOK-2g/BAk2CtZ6j64.jpg?size=768x763&quality=96&sign=8e4ea0de523b2e439c15fe833c8afa74&type=album)

    *Рисунок 14. Перевожу правую панель в режим "Быстрый просмотр".

    - Информация. здесь мы можем увидеть некоторые сведения о файле - его имя, расположение, права доступа, владельца, размер и т.д. (рисунок 15) Информация достаточно подробная.

    ![](https://sun9-74.userapi.com/impg/6s0sdlGZ99B4zhI899YXLcntTtzBSWRh0zGOig/BKs0Pf5nsuY.jpg?size=752x615&quality=96&sign=edaf8397ee82b1b65f307953329ce8b2&type=album)

    **Рисунок 15. Перевожу панель в режим "Информация".*

    - Дерево. Позволяет нам увидеть развернутое дерево каталогой устройства (рисунок 16).

    ![](https://sun9-16.userapi.com/impg/j9WLNu-EiPgHj05z01TrfX8p0kFq008HuZyuQQ/8wCtgsR4HIA.jpg?size=744x648&quality=96&sign=3a622b6ad09d1fef92f474b3660cc787&type=album)

    **Рисунок 16. Перевожу панель в режим "Дерево".*

5. **Используя возможности подменю ``Файл`` , выполните:**

- просмотр содержимого текстового файла

Просмотрим содержимое текстового файла text.txt прошлой лабораторной работы следующим образом ``Файл`` -> ``Просмотр``.(Рисунок 17)

![](https://sun9-24.userapi.com/impg/AB-JGfSiLJtuKFpX338Cz8PniW8tWZVnrwlLzg/G9WfDSUeKD4.jpg?size=762x234&quality=96&sign=db7d5a358ec939dcca009d00eae28895&type=album)

*Рисунок 17. Просмотр содержимого файл .txt

- редактирование содержимого текстового файла (без сохранения результатов редактирования);

    Открываю файл text.txt

    ![](https://sun9-16.userapi.com/impg/XeYhMrkg2XJJJ43-RKjPyvItgvZIV226OWbLvA/hRlGwdsfecs.jpg?size=750x264&quality=96&sign=dde06a13e811c53c1d17c7692023a731&type=album)

    *Рисунок 18. Изначальный файл.*

    Редактирую файл, вставляя текст ``"f[f[ff[f["``.

    ![](https://sun9-16.userapi.com/impg/kcmiLK2LUDCsYgNY0PogcLplbhO_3GeksJA7-A/gqPsdioeqGk.jpg?size=756x254&quality=96&sign=fb29a505f0fee3e30f3241c6bd1562bf&type=album)

    *Рисунок 19. Редактируем файл.*

    Далее закрываем файл, нажав в окне сохранения кнопку ``нет``.

    ![](https://sun9-58.userapi.com/impg/RARVxvOZ-xmH2A0SGHKtAcjpt7jifYxbX9W5MQ/w72xdGLGQls.jpg?size=512x181&quality=96&sign=6c4f5ebe68e5819147bfd5d6f3b9035b&type=album)

    *Рисунок 20. При закрытии файла, его не сохраняем.*

-  создание каталога;

    Для этого воспользуемся клавишей ``F7`` и введем имя нового каталога ``conference``(Рисунок 21), после чего проверим список файлов и каталогов домашнего каталога на его наличие;

    ![](https://sun9-20.userapi.com/impg/8z50-I5uJH36IpH4pS0lc2iOc8V078wfX_DfHg/AEt_I4cH_wU.jpg?size=409x168&quality=96&sign=cc0b9062266f55201620f6fa11e9f061&type=album)

    *рисунок 21. Создаем файл ``conference``.*

    ![](https://sun9-27.userapi.com/impg/YY7AR9iwSU2kf-hVUsUECJoUcLy7nrmFmieHBQ/YDCguOq9P18.jpg?size=744x138&quality=96&sign=8748a6b779e2dda9e5d041181bab6f6a&type=album)

    *Рисунок 22. Проверяем налиичие файла в корневой директории*


- копирование в файлов в созданный каталог.

    Выделяем файл ``conf.txt`` и копируем так, как описано выше, выбираем путь, то есть каталог ``conference``, в который нужно скопировать файл.(Рисунок 23) Проверяем правильность копирования файлов.(Рисунок 24)

    ![](https://sun9-33.userapi.com/impg/0ZrUSbeMKOu5RFz4OS_FKpqZ7dvA0jxj0Xc3Xg/ZkyjmbYcyWc.jpg?size=678x276&quality=96&sign=219551ebc9081da41f6f5843b2f2e26b&type=album)

    *Рисунок 23. Копируем файл.*

    ![](https://sun9-46.userapi.com/impg/fbbaAqkxYHmYyLTCmRIDxhtupqIDRB1EI1giUw/j5aAhn7bZ5Q.jpg?size=407x131&quality=96&sign=9ed6c310b2b06bd0cd1b57d1bbd03f02&type=album)

    *Рисунок 24. Проверяем наличие файла в каталоге ``conference``.

6. **С помощью соответствующих средств подменю ``Команда`` осуществите:**

- поиск в файловой системе файла с заданными условиями (например, файла с расширением .c или .cpp, содержащего строку main);

    Делаем это с помощью вкладки ``Поиск файла``
    Вводим параметры(Рисунок 25) и просматриваем результаты поиска (Рисунок 26).

    ![](https://sun9-56.userapi.com/impg/7P8PeLegFg-3l4x_Pzf4ab6T80XMbeQQ6HZsmw/is_vS8vfIBc.jpg?size=627x360&quality=96&sign=dfaebe4e865c51d6201edafbedbecaed&type=album)

    *Рисунок 25. Вводим парамкетры поиска.* 

    ![](https://sun9-28.userapi.com/impg/lTumef19x1a-dKwT7F-nRXL6l-J5acdlk9rsRQ/2LVJ4MTK_Pc.jpg?size=582x446&quality=96&sign=e60b4f80e5faa70898c96f283c673820&type=album)

    *Рисунок 26. Просматриваем результаты поиска*

- выбор в истории (Рисунок 27) и повторение одной из предыдущих команд(Рисунок 28).

    Просматриваю историю команд с помощью вкладки ``История командной строки``.

    ![](https://sun9-50.userapi.com/impg/dbcIqUanxNpFV_vQJ3UDDX782Fcpmc0TtRMH7A/0nMUp9w5JdY.jpg?size=266x128&quality=96&sign=f8e37ca50854d0fca2bd20dc1bf69876&type=album)

    *Рисунок 27. Просматриваем историю команд*
    
    Выполняем последнюю команду из истории команд. Последней командой была команда ``cd ski.plases``
    Мы видим, что на предыдущем этапе мы находились в корневой директории. На данном этапе видим, что место нашего расположения изменилось на каталог ``ski.plases``, находящийся в корневой директроии, а это значит, что команда выполнилась успешно.

    ![](https://sun9-59.userapi.com/impg/0enF-esCAGqUfSWQx-Odh6d7AaKKjURQs7OxEw/hNldskAt9iY.jpg?size=479x138&quality=96&sign=3a3910eb471af4f8af4390cb09a24697&type=album)

    *Рисунок 28. Выполняем последнюю команду из истории команд.*

- переход в домашний каталог;

    Ввожу в командной строке ``cd``и нажимаю ``Ввод``.(Рисунок 29)

    ![](https://sun9-37.userapi.com/impg/NFxgsIAVOHN4rCg2IviMkKG8GvbliaMNDgqOOw/6QVeXE8qwHs.jpg?size=574x126&quality=96&sign=086d757dcfa3ffe951fb8a13f14f1b7a&type=album)

    *Рисунок 29. Ввод ``cd``*

-  анализ файла меню и файла расширений.

    Для анализа файла расширений, нажимаем вкладки ``Команда ``(Рисунок 30) -> ``Редактировать файл расширений``(Рисунок 31)

    ![](https://sun9-27.userapi.com/impg/vJgCcHzREiGJHxxf2RUiKvlJ0X_mWYuZntrATw/3e1LFwh7ojA.jpg?size=416x130&quality=96&sign=c18ccacdfafc7f2e902d57e97698cca6&type=album)

    *Рисунок 30. Меню ``Команда``.*

    ![](https://sun9-16.userapi.com/impg/C9kJkp4s7GRvL7JbXzr7JsGIusmBmQkmZnx-VQ/ftaJ-NHiPBE.jpg?size=732x546&quality=96&sign=7a84dd34d2f07c82616c9d096cc6e7f1&type=album)

    *Рисунок 31. Файл расширений.*

    Для анализа файла меню, нажимаем вкладки ``Команда `` (Рисунок 30) -> ``Редактировать файл меню``(Рисунок 32)

    ![](https://sun9-9.userapi.com/impg/lVtYrxJ4EZ0oP79wuuqbQK4roBZss_MIbDg_uA/FZvlotVmx1I.jpg?size=745x550&quality=96&sign=e1bb33f4074f4e2fbca7f71032f219ac&type=album)

    *Рисунок 32. Файл меню.*

7. **Вызовите подменю Настройки . Освойте операции, определяющие структуру экрана mc (Full screen, Double Width, Show Hidden Files и т.д.)**

    Осваиваем операции, определяющие структуру экрана mc.(Рисунки 33-34)

    ![](https://sun9-39.userapi.com/impg/k-J36KWBbFA649-A0U9My2Sy7LRpuztSsYTcbw/4tahQoNjpQI.jpg?size=427x220&quality=96&sign=f5541708acfd0215ef8c33e24fd01d57&type=album)

    *Рисунок 33. Меню ``Настройки``*

    ![](https://sun9-52.userapi.com/impg/Xc3aURI3ogoMRs8ntGFscFWdXJCpLfXCteVzvA/d4_WUSaz-YU.jpg?size=745x348&quality=96&sign=52a23adbea6d53f2f33a5971da60dbbc&type=album)

    *Рисунок 34. Вкладка ``Настройка панелей``*

## **Задание по встроенному редактору mc.**

1. **Создайте текстовой файл text.txt.**

    Создаю текстовый файл с помощью команды ``touch text.txt``.(Рисунок 35)

    ![](https://sun3-16.userapi.com/impg/sNJvzwX2Vfl6v1NMKN1PNk_d3aF-U5UBEfnZEw/0xzMHm3EmFQ.jpg?size=631x130&quality=96&sign=fdb2d033229a0698ce5d865aab611cfd&type=album)

    *Рисунок 35. Создаю файл с помощью команды ``touch``*


2. **Откройте этот файл с помощью встроенного в mc редактора.**

    Открываю созданный файл в меню ``Файл`` -> ``Правка``(Рисунок 36)

    ![](https://sun9-45.userapi.com/impg/gFDYHKAkfcYs6BC6_MqJOCCSCb5vu0yOLpxrLg/THgajH-ZchY.jpg?size=736x290&quality=96&sign=c0de2bda08a4ec84140e286ffabf58ca&type=album)

    *Рисунок 36. Открываю файл*

3. **Вставьте в открытый файл небольшой фрагмент текста, скопированный из любого другого файла или Интернета.**

    Копирую из интернета определение слова "ДОБРО" с помощбю комбинации клавиш ``Ctrl + Shift + c``, вставляю во встроенный в mc редакторс помощью комбинации клавиш ``Ctrl + Shift + v``.(Рисунок 37)

    ![](https://sun9-45.userapi.com/impg/LOaZUq5hS1B_lLVLYobsDLUkbf9RL_WLGqi2aA/53WflHuAaP8.jpg?size=751x235&quality=96&sign=e0c43d005a1b86a62d73fc89f8511c7b&type=album)

    *Рисунок 37. Вставляю в файл фрвгмент текста.*

4. **Проделайте с текстом следующие манипуляции, используя горячие клавиши:**

    1. Удалите строку текста.

    Делаю это с помощью команды ``Ctrl + y``. До(Рисунок 38)/ После(Рисунок 39)

    ![](https://sun9-26.userapi.com/impg/Ca8wyDs7-KJIjgiSjAUMuF_W-jMfTNJe62AXzg/wJIAqSDTwmQ.jpg?size=730x158&quality=96&sign=673bfc25666a242bd9fb4ae64f68d955&type=album)
    
    *Рисунок 38. Файл до удаления третьей строки*

    ![](https://sun9-43.userapi.com/impg/wKpRojq-x-4RoSZYyrgX75HBVWIRNMcxCt-sYw/5hu1nOOizjo.jpg?size=724x150&quality=96&sign=78aacdb2d06d9f2259ec9e61f5c4e08c&type=album)

    *Рисунок 39. Файл после удаления третьей строки*

    2. Выделите фрагмент текста и скопируйте его на новую строку.

    Выделим фрагмент текста и скопируем его на новую строку (Рисунки 40-41). Для этого сначала выберем фрагмент (последнюю строку, нажмем ``Enter``, чтобы перенести копирование на след. строку, теперь нажмем клавишу ``F5``, чтобы скопировать.

    ![](https://sun9-55.userapi.com/impg/m48Vmzuh7frZr7R5uypclVjFIcQmUUZgQ5qlEg/NuNB6RCBndQ.jpg?size=712x167&quality=96&sign=6a2bf1ed3b986297e7ee16d52a9bd0af&type=album)

    *Рисунок 40. До копирования.*

    ![](https://sun9-41.userapi.com/impg/iDvdPUr0G0N1jLH6Qem7UaEL5zGDreQJ0E_k-g/eeOjPcVMOm0.jpg?size=725x178&quality=96&sign=6b8d3773e47b7f0b567b6e0bf26f4e33&type=album)
    
    *Рисунок 41. После копирования.*

    3. Выделите фрагмент текста и перенесите его на новую строку.

    Выделим фрагмент текста и перенесем его на новую строку (Рисунок 42-43). Для этого сначала выделим фрагмент (пятая строка), нажмем клавишу ``F6``, которая позволяем перемещать фрагменты, далее жмем ``Enter``, чтобы переместить строку на новую.

    ![](https://sun9-51.userapi.com/impg/CcIvtlk6YBXwxRH4veRnLPFiH6lawr1WK8oWpA/ZjRCwUgHM2Q.jpg?size=730x171&quality=96&sign=b06f9e5f573a1b4163db816f09a341fc&type=album)

    *Рисунок 42. До копирования.*

    ![](https://sun9-1.userapi.com/impg/8bTU6IZowmJ4vQYWDkXWixh7mAYBnS4EddECVw/tXQLAjHkBrc.jpg?size=730x172&quality=96&sign=c7c68c9336e142eefaa03ba78a631efc&type=album)

    *Рисунок 43. До копирования.*

    4. Сохраните файл.

    Для этого на нижней панели редактора нажмем "Сохранить".(Рисунок 44)

    ![](https://sun9-54.userapi.com/impg/qIe_5RepK11LOYrLvXFHZyMmRPT9FPTMk5jXCQ/HBqrn5MbDHU.jpg?size=598x136&quality=96&sign=b83702d1f6bf1471588bf1c02b22e5ee&type=album)

    *Рисунок 44. Нажимаем "Сохранить".*

    5. Отмените последнее действие.

    Мы уже сохранили файл, допишем в конце какой-нибудь текст. (Рисунок 45)

    ![](https://sun9-16.userapi.com/impg/Em1Adfg9EibmGXOUp9vJzJLXvKTlQMaKZ6tQJw/wJit18nr3HY.jpg?size=601x199&quality=96&sign=a4c5b06768b3802f87cbc9b59835241b&type=album)

    *Рисунок 45. Дописываем текст.*

    Отмена действий производится нажатием ``Ctrl + u``. Выполняем данную комбинацию клавиш и видим, что наши предыдущие действия отменяются.(Рисунок 46)

    ![](https://sun9-40.userapi.com/impg/-EANzFYDrBZaB5ReuC0ikUq_dl6cZBNF66r-7g/HG5Lg2F3z6A.jpg?size=645x136&quality=96&sign=27d322ea0302bc2c89180e3c9a9be1b2&type=album)

    *Рисунок 46. Нажимаем ``Ctrl + u ``. Действия отменяются.*

    6. Перейдите в конец файла (нажав комбинацию клавиш) и напишите некоторый текст.
    Делаю это с помощью команды ``Ctrl + End ``.(Рисунок 47)

    ![](https://sun9-19.userapi.com/impg/OX9Vpy6_XwKWZ2Wh5Vv58WM6JYV-AOZ-72OYaw/peO12XYMy5k.jpg?size=701x127&quality=96&sign=a61297d610fb700dd119cc49ea2c07b8&type=album)

    *Рисунок 47. Перешла в конец и написала текст "текст текст текст"*

    7. Перейдите в начало файла (нажав комбинацию клавиш) и напишите некоторый текст.

    Делаю это с помощью команды ```Ctrl + Home``.(Рисунок 48)

    ![](https://sun9-70.userapi.com/impg/tMdEnGYvRpQ8HjPNIHv3yoEs67RKIVXwn-7PqA/vmHTTCdhiAg.jpg?size=681x222&quality=96&sign=68e63fa87ab88abb9c3ee74f73263ea6&type=album)

    *Рисунок 48. Перехожу в начало файла и дописываю текст "ДОБРО ДОБРО".

    8. Сохраните и закройте файл.(Рисунок 49)

    ![](https://sun9-54.userapi.com/impg/qIe_5RepK11LOYrLvXFHZyMmRPT9FPTMk5jXCQ/HBqrn5MbDHU.jpg?size=598x136&quality=96&sign=b83702d1f6bf1471588bf1c02b22e5ee&type=album)

    *Рисунок 49. Сохраняю файл и закрываю его*


5. **Откройте файл с исходным текстом на некотором языке программирования (например C или Java)**(Рисунок 50)

    ![](https://sun9-65.userapi.com/impg/4xMSmCU-AZD9yquES5n8HHvYFqGm4RhEdKqWgA/i9CD3DXiGX8.jpg?size=769x447&quality=96&sign=af4467a707b79769eea06e09961301a0&type=album)

    *Рисунок 50. Открыли файл. Подсветка включена"

6. **Используя меню редактора, включите подсветку синтаксиса, если она не включена, или выключите, если она включена.**     (Рисунки 51-52)

    ![](https://sun9-73.userapi.com/impg/txkFHlQlwe2BV6VGnnSdKEba797xrvO5osoYGQ/fNvGXUFlf5g.jpg?size=742x496&quality=96&sign=5d9fb9d5bdefdf3a159a63462a9f5f3a&type=album)

    *Рисунок 51. Нажимаем кнопку ``Включить/выключить подсветку синтаксиса``*

    ![](https://sun9-51.userapi.com/impg/XoUSXIiDk0D40KCeI6JGTBj787Cd2fq31tcFlA/GgFIJzMYM7M.jpg?size=747x512&quality=96&sign=754e10e071dd9ce11ff0f8afea5312db&type=album)

    *Рисунок 52. Подсветка синтаксиса отключена.*



## **Вывод:**
 Я освоила основные возможности командной оболочки Midnight Commander (MC). Приобрела навыки практической работы по просмотру каталогов и файлов и манипуляций с ними.

## **Библиографический список:**

[1]: Инструкции к лабораторной работе (файл 005-lab_mc.pdf, предоставленный на сайте).
