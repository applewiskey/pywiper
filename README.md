# PyWiper
# Уничтожитель сообщений в telegram-группах
## Зачем
В последнее время в Интернете много всего пишут такого, что может быть интерпретировано согласно УК различных стран.
Данная утилита позволяет создавать безопасное пространство для диалога, так как все сообщения будут удалены после.
## Как работает
Администратор запускает утилиту, указывает ID чата и количество дней, за которые нужно удалить сообщения.
## Как лучше всего использовать
Запускать по расписанию в 00:00
# Установка
1. Сходить [сюда](https://my.telegram.org/apps) и получить ID и Secret для приложения
2. Установить [python3.6 и выше](https://www.python.org/downloads/)
3. Установить [pip для python 3.6](https://pip.pypa.io/en/stable/installing/)
4. Выполнить команду: pip3 install --user -r requrements.txt
5. Выполнить команду: python3 pywiper.py
6. Следовать инструкции из приложения
# Использование
Первый аргумент: всегда id:secret из пункта 1 инструкции.

Второй аргумент: может быть *list* или *wipe*.

## list
Показывает все ваши чаты ( группы и супергруппы ) в формате: ID   NAME
## wipe
Позволяет удалить сообщения по ID группы, полученном из команды *list*
Третий аргумент: ID группы
Четвертый аргумент ( опционально ): количество дней, которые нужно стереть. Считает от текущего момента.

# Авторы
- Идея и реализация для [tg-cli](https://github.com/vysheng/tg) - @annmuor
- Python-реализация - @stenopolz
