### lesson 1: git commands

git init - инициализация локального репозитория
git add. - индексация всех файлов в папке (кроме тех, что записаны в файле .gitignore)
git commit -m 
git log - просмотр истории коммитов

Основная команда консоли
Ctrl + L — Очистить консоль от предыдущих вызовов.
Инициализация и Коммит
git init — Инициализация локального репозитория.
git add . — Индексация всех файлов в папке для следующего коммита (кроме тех, что указаны в .gitignore).
git commit -m "<описание изменений>" — Зафиксировать изменения с сообщением, описывающим их.
git log — Просмотр истории коммитов.
Управление Ветками
git branch -M main — Переименовать текущую ветку в main (полезно, если ветка названа master; main — новый стандарт).
Подключение к Удалённому Репозиторию
git remote add origin <ссылка на репозиторий> — Привязать локальный репозиторий к выбранному удалённому.
git push -u origin main — Отправить файлы в удалённый репозиторий и сделать текущую ветку основной для команды git push.
Клонирование и Подтягивание
git clone <SSH ключ репозитория> — Клонировать указанный репозиторий (не забудьте перейти в созданную папку в VSCode, чтобы работать в терминале).
git pull — Подтянуть изменения с указанной удалённой ветки.
Удаление Файлов из Индекса
git rm --cached <имя файла> — Снять индексацию с файла (удобно для файлов, которые нужно добавить в .gitignore, если они уже были проиндексированы).