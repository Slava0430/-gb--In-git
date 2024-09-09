!Основные команды Git
Введение в контроль версий. Работа с Git. Составление инструкции по работе с Git.
✦ git init – инициализация локального репозитория
✦ git status – получить информацию от git о его текущем состоянии
✦ git add – добавить файл или файлы к следующему коммиту
✦ git commit -m “message” – создание коммита.
✦ git log – вывод на экран истории всех коммитов с их хеш-кодами
✦ git checkout – переход от одного коммита к другому
✦ git checkout master – вернуться к актуальному состоянию и продолжить работу
✦ git diff – увидеть разницу между текущим файлом и закоммиченным файлом
Синтаксис языка Markdown
Введение в контроль версий. Работа с Git. Составление инструкции по работе с Git.
Справочник по Markdown от Microsoft:
https://docs.microsoft.com/ru-ru/contribute/markdown-reference
✦ # Заголовок – выделение заголовков. Количество символов “#” задаёт уровень заголовка
(поддерживается 6 уровней).
✦ = или - – подчёркиванием этими символами (не менее 3 подряд) выделяют заголовки первого
(“=”) и второго (“-”) уровней.
✦ ** Полужирное начертание** или __ Полужирное начертание__
✦ *Курсивное начертание* или _Курсивное начертание_
✦ ***Полужирное курсивное начертание***
✦ ~~Зачёркнутый текст~~
✦ * Строка – ненумерованные списки, символ “*” в начале строки
✦ 1, 2, 3 … – нумерованные списки
## Added Number
![Hello](car.jpg)
## Added Diff
f
!Основные команды Git
Введение в контроль версий. Работа с Git. Составление инструкции по работе с Git.
✦ git init – инициализация локального репозитория
✦ git status – получить информацию от git о его текущем состоянии
✦ git add – добавить файл или файлы к следующему коммиту
✦ git commit -m “message” – создание коммита.
✦ git log – вывод на экран истории всех коммитов с их хеш-кодами
✦ git checkout – переход от одного коммита к другому
✦ git checkout master – вернуться к актуальному состоянию и продолжить работу
✦ git diff – увидеть разницу между текущим файлом и закоммиченным файлом
Синтаксис языка Markdown
Введение в контроль версий. Работа с Git. Составление инструкции по работе с Git.
Справочник по Markdown от Microsoft:
https://docs.microsoft.com/ru-ru/contribute/markdown-reference
✦ # Заголовок – выделение заголовков. Количество символов “#” задаёт уровень заголовка
(поддерживается 6 уровней).
✦ = или - – подчёркиванием этими символами (не менее 3 подряд) выделяют заголовки первого
(“=”) и второго (“-”) уровней.
✦ ** Полужирное начертание** или __ Полужирное начертание__
✦ *Курсивное начертание* или _Курсивное начертание_
✦ ***Полужирное курсивное начертание***
✦ ~~Зачёркнутый текст~~
✦ * Строка – ненумерованные списки, символ “*” в начале строки
✦ 1, 2, 3 … – нумерованные списки
*Added List*

$ git log --graph
* commit 223337d8d5a5322970d8b536130f75409b5d5653 (HEAD -> Main)
| Author: Alex <alexpetrutik91@gmail.com>
| Date:   Tue Sep 3 21:30:39 2024 +0300
|
|     Delete List
|
* commit 3b03be31fdb5b49d95a84cca67cd552858ce4b07
| Author: Alex <alexpetrutik91@gmail.com>
| Date:   Tue Sep 3 21:28:04 2024 +0300
|
|     Added
|
* commit d856e84f55a10b498277a07cc5051c58ade8d642
| Author: Alex <alexpetrutik91@gmail.com>
| Date:   Tue Sep 3 21:19:57 2024 +0300
|
|     Added Diff and Images
|
*   commit 6347b8bab6b5ae9b3a64b3a1b60aee5977259360
|\  Merge: 8c04ddd 47e3c63
| | Author: Alex <alexpetrutik91@gmail.com>
| | Date:   Tue Sep 3 21:16:27 2024 +0300
| |
| |     Merge branch 'Diff' into Main
| |
| * commit 47e3c63c2b15ca8472487d690a72d4644706ee11 (Diff)
| | Author: Alex <alexpetrutik91@gmail.com>
| | Date:   Tue Sep 3 20:37:41 2024 +0300
| |
| |     Added Diff
| |
* |   commit 8c04ddd188a13f9c92a2dd64b081612f42e2b707
|\ \  Merge: 21027b6 93f7215
| | | Author: Alex <alexpetrutik91@gmail.com>
| | | Date:   Tue Sep 3 21:08:49 2024 +0300
| | |
| | |     Merge branch 'Number' into Main
| | |
| * | commit 93f7215ee8b730a238b943ee1864ac2e301234e1 (Number)
| |/  Author: Alex <alexpetrutik91@gmail.com>
| |   Date:   Tue Sep 3 20:32:54 2024 +0300
| |
| |       Added Number
| |
* | commit 21027b65ea29e2fc040e530ffcdede0aa74bef7c
| | Author: Alex <alexpetrutik91@gmail.com>
| | Date:   Tue Sep 3 21:04:26 2024 +0300
| |
| |     Added Images
| |
* | commit 16faefd03e4a81eaf56f17321922727e1f2ee4ed
|/  Author: Alex <alexpetrutik91@gmail.com>
|   Date:   Tue Sep 3 20:58:00 2024 +0300
|
|       Added gitignore
|
* commit 1958c65c72bb172ac9a0ecafd8ee23f5e92cc7b6
| Author: Alex <alexpetrutik91@gmail.com>
| Date:   Tue Sep 3 20:31:05 2024 +0300
|
|     Added Main
|
* commit 3c6bd2df066f02a207802c657c6f72377e2150ca (origin/main, origin/HEAD)
  Author: AlexanderFanipol <160220406+AlexanderFanipol@users.noreply.github.com>
  Date:   Mon Aug 19 21:33:36 2024 +0300

      Initial commit
(END)

Как сделать pull request
Делаем   (ответвление) репозитория fork
Делаем git clone   версии репозитория СВОЕЙ
Создаем новую ветку и в НЕЕ вносим свои изменения
Фиксируем изменения (делаем коммиты)
Отправляем свою версию в свой GitHub
На сайте GitHub нажимаем кнопку pull request
