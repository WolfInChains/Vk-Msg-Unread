# Vk-Msg-Unread
Скрипт для накрутки сообщений вк, который помечает все сообщения непрочитанными (в том числе и ваши). Так же добавлен скрипт для отправки сообщений рандомным пользователям вк, чтобы потом из них можно было сделать непрочитанные сообщения.
## Настройка
Устанавливаем недостающие библиотеки из requirements.txt

Токен получаем [здесь](https://oauth.vk.com/authorize?client_id=2685278&scope=1073737727&redirect_uri=https://oauth.vk.com/blank.html&display=page&response_type=token&revoke=1)

В адресной строке, все что между token= и & копируем, это и есть токен

Запускаем Msg.py и следуем указаниям.
## Компиляция
Чтобы собрать все в .exe файл используем команды:
```
pyinstaller -F Msg.py
pyinstaller -F SendMsg.py
```
