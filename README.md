# VBot
**Репозиторий не является официальным. Я не имею никакого отношения к данному проекту**. [Официальный репозиторий](https://github.com/ekonda/sketal) _(бот был переименован и переделан, вследствие чего лишился пары важных функций для меня, поэтому я решил склонировать последний коммит VBot перед его переименованием в Sketal)_.
# Настройка
<s>**Способ для Windows**

Для работы бота требуется [Python 3.6+](https://www.python.org/downloads/) _(для удобства не забудьте установить галочку **"Add to PATH"**)_, [XMPP](https://www.apachefriends.org/ru/download.html) или любое другое приложение для работы с **MySQL** (можно использовать также **PostgreSQL**).
1. Устанавливаем зависимости для Python из файла `requirements.txt`: `python -m pip install -r requirements.txt`
2. Заходим в XMPP, запускаем MySQL и через phpMyAdmin создаём **базу для бота** (пользователя можно не создавать, а пользоваться учёткой `root` без пароля)
3. Заполняем файл `settings.py` и запускаем бота через `vbot.py`. Имейте ввиду, что MySQL должен также всегда работать, без него бот не запустится.</s>

**По состоянию на июль 2020 года бот окончательно перестал работать из-за изменений в API ВКонтакте.** Ставить его бесполезно. 
