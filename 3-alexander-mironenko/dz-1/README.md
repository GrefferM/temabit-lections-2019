Порядок виконання дз-1

1 - За допомогою команди:
	git clone https://github.com/Evan-Kork/temabit-lections-2019.git
	копіюємо репозитарій на свій ПК.
2 - $ cd temabit-lections-2019
	# за допомогою номанди 'cd' переходимо в папку репозитарію з яким 
	потрібно працювати
3- $ git checkout -b feature/3-alexander-mironenko/dz-1 
	# створюємо нову гілку 3-alexander-mironenko/dz-1, 
	та автоматично переключаємось на неї
4-$ git status - бачим незакомічену папку яку було попередньо створено
	3-alexander-mironenko/
5-$ git add . # добавляємо папку та все що в ній
6-$ git status - папка з файлом (new file:   3-alexander-mironenko/dz-1/README.md)
 	підсвічується зеленим, що говорить про готовність до команди commit

7-$ git commit -m "my first commit" - закомічуєм та прописуєм "коментар"
8-$ git push origin feature/3-alexander-mironenko/dz-1
	#завантаження змінених файлів з нової гілки на репозитарій




	Команди git
* git init         - создание подкаталога .git, инициализация репозитория.
* git clone remote - копирование репозитория.
* git status       - проверка состояния локального репозитория
* git add          - добавить индексацию файлов
    1. .           - папки и файлы на одном уровне и глубже
    2. '*'         - все папки и файлы на всех уровнях
* git commit
    1. -m 'message' - фиксируем файлы локально
    2. --amend -m   - изменить последний commit
* git push 
    1. -u origin master             - пуш в удаленный origin в ветку master
    2. --set-upstream origin master - устанавливает удаленную ветвь по умолчанию
* git pull                  - стягиваем последние изменения в репозиторий
* git fetch remote          - оновлевает информацию о последних изменениях
* git merge branch          - слитые ветки
### Информация о config и log
* git config       
    1. --global user.name  - глобально указываем имя юзера
    2. --global user.email - глобально указываем email.user
    3. --list              - вывод настроек config
* git log
    1. --pretty=oneline:                      - вывод в одну строку
    2. --pretty=format:"%h - %s | [%ad][%an]" - форматированный вывод
* git remote 
    1. show origin - информация про удаленный репозиторий
    2. -v          - сокращенная запись

### Работа с ветками
* git checkout 'name_branch' - переключиться на ветку name_branch
    1. -B 'name_branch'      - создание ветки и переключиться на ветку name_branch
* git branch                 - список доступных веток
    1. 'name-branch'         - создание ветки
    2. -D                    - удалить ветку (полное удаление)
* git reset                  - откат изменений
    1. @~                    - преведущий commit
    2. %h                    - хеш commit для перехода
* git reflog branch          - вывод последних действий
* git cherry-pick %h         - копирует commit