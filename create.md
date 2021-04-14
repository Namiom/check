[К содержанию](./readme.md)

# Создание проекта

**Цели**

Научиться создавать git репозиторий с нуля.

## Создайте страницу «Hello, World»

Начните работу в пустом рабочем каталоге (например Work, если вы скачали архив с предыдущего шага) с создания пустого каталога с именем ***«hello»***, затем войдите в него и создайте там файл с именем ***hello.html*** с таким содержанием.

**Выполните:**
```
mkdir hello
cd hello
touch hello.html
```

**Фаил**: *hello.html*

```
Hello, World
```
## Создайте репозиторий

Теперь у вас есть каталог с одним файлом. Чтобы создать git репозиторий из этого каталога, выполните команду git init.

**Dыполните:**
```
git init
```

**Результат:**

```
$ git init
Initialized empty Git repository in /Users/alex/Documents/Presentations/githowto/auto/hello/.git/
```

## Добавьте страницу в репозиторий

Теперь давайте добавим в репозиторий страницу ***«Hello, World».***

**Выполните:**

```
git add hello.html
git commit -m "First Commit"
```
Вы увидите …

**Результат:**

```
$ git add hello.html
$ git commit -m "First Commit"
[master (root-commit) 911e8c9] First Commit
 1 files changed, 1 insertions(+), 0 deletions(-)
 create mode 100644 hello.html
 ```