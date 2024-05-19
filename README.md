<h2>Телеграм бот, помогающий тестировщику сгенерировать файл</h2>

> **Статус проекта:**
>
> 🟢 Поддерживается (активный) 

## Цели и Задачи
* Бот принимает на входе тип и размер файла, а на выходе отдаёт сам файл.
* Это может пригодиться, когда на сайте есть ограничение на размер загрузки фото и нужно проверить граничные значения.

## 🖼 Скриншоты

Стартовое меню:

![image](https://raw.githubusercontent.com/German-D/generation_file/main/static/menu.png)

После выбора файла:

![image](https://raw.githubusercontent.com/German-D/generation_file/main/static/generate.png)

## 💻 Технологии

* Python
* Библиотека `telebot`

## ⏬ Установка на локальном компьютере

Клонируем удалённый репозиторий на локальную машину:

```markdown
git clone git@github.com:German-D/generation_file.git
```
Создать бота и через [@BotFather](https://t.me/BotFather) и вставить в проекте свой токен от бота

Создаём виртуальное окружение внутри папки проекта.
Далее команды для MacOS (для windows инуструкция [есть вот тут](https://realpython.com/python-virtual-environments-a-primer/#create-it))

``` markdown
python3 -m venv venv
```

``` markdown
source venv/bin/activate
```
Устанавливаем библиотеки

``` markdown
python3 -m pip install pyTelegramBotAPI
```

Запускаем
``` markdown
python3 main.py
```

## Автор

Герман Дольников (Телеграм @dolnikov)
