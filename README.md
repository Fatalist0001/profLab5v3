# GitCheatSheet
Student assignment to learn git commands

### Задание для студентов

Вам нужно пыполнять задяния и вносить изменения в файл README.md, записывая команду, которую вы выполнили.

**Задание 1**. Виберите (локальную) папку для нового проекта и клонируйте в нее данный репозиторий.
```sh
git clone https://github.com/teacher-fiit/GitCheatSheet
```
**Задание 2**. Перейдите в созданную (клон6ированную) папку.
```sh
cd GitCheatSheet
```
**Задание 3**. Заполните второй столбец таблицы html-файла: после записи каждой ячейки индексируйте измененные файлы и выполняйте коммит.
```sh
git add .
git commit -m "update README.md"
```
**Задание 4**. Дополните файл style.css. Индексируйте измененные файлы и выполните коммит.
```sh
git add .
git commit -m "update style.css"
```
**Задание 5**. Создайте пустой (без файлов) публичный удаленный репозиторий в своем аккаунте на GitHub. 
**Задание 6**. Отправьте изменения на удаленный репозиторий. Если будет необходимость, настройте подключения к удаленному репозиторию.
```sh
git remote add profLab5v3 https://github.com/Fatalist0001/profLab5v3
git push profLab5v3 main
```
