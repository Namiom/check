[К содержанию](./readme.md)

# Подготовка

**Цели**

***Полная готовность к работе с Git.***

## Установка имени и электронной почты

Если вы никогда ранее не использовали git, для начала вам необходимо осуществить установку.
Выполните следующие команды, чтобы git узнал ваше имя и электронную почту. 
Если git уже установлен, можете переходить к разделу окончания строк.

**Выполнить:**
```
git config --global user.name "Your Name"
git config --global user.email "your_email@whatever.com"
```
## Параметры установки окончаний строк
*Также, для пользователей Unix/Mac:*

**Выполнить:**
```
git config --global core.autocrlf input
git config --global core.safecrlf warn
```
**Для пользователей Windows:**

**Выполнить:**

```
git config --global core.autocrlf true
git config --global core.safecrlf warn
```

## Установка отображения unicode

По умолчанию, git будет печатать не-[ASCII](https://unicode-table.com/ru/#basic-latin) символов в именах файлов в виде восьмеричных последовательностей ```\nnn```. Что бы избежать нечитаемых строк, установите соответствующий флаг.

```
git config --global core.quotepath off
```