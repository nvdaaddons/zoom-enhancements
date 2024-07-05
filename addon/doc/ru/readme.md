# Улучшения доступности Zoom #

* Авторы: Мохамад Сулиман (Mohamad Suliman), Эйлана Бениш (Eilana Benish)
* Загрузить [стабильную версию][1]
* Совместимость с NVDA: от 2018.4 до 2022.1

Это дополнение упрощает использование Zoom для пользователей NVDA,
предоставляя сочетания клавиш для обработки оповещений о различных событиях
во время совещания, делает процесс удаленного управления намного более
доступным и плавным и многое другое.

## сочетания клавиш для управления оповещениями на встречах 

* NVDA + Shift + A: переключение между различными режимами выдачи
  оповещений. Доступны следующие режимы:

    * Режим сообщения всех оповещений, в котором все оповещения объявляются
      как обычно
    * Сигнал для оповещений, при котором NVDA будет воспроизводить короткий
      звуковой сигнал для каждого оповещения, отображаемого в Zoom
    * Отключить все оповещения, при этом NVDA будет игнорировать все
      оповещения
    * Пользовательский режим, в котором пользователь может настроить, какие
      оповещения он хочет получать, а какие нет. Это можно сделать с помощью
      диалога настроек дополнения или с помощью специальных сочетаний клавиш

Следующие сочетания клавиш можно использовать для включения / выключения
оповещений каждого типа (обратите внимание, что это будет действовать при
выборе пользовательского режима):

* NVDA + Ctrl + 1: Участник Присоединился/покинул Собрание (Только ведущий)
* NVDA + Ctrl + 2: Участник присоединился/покинул комнату ожидания (только
  ведущий)
* NVDA + Ctrl + 3: Звук отключён ведущим
* NVDA + Ctrl + 4: Видео остановлено ведущим
* NVDA + Ctrl + 5: Общий доступ к экрану запущен/остановлен участником
* NVDA + Ctrl + 6: Разрешение на запись получено/отменено
* NVDA + Ctrl + 7: Получен публичный чат во время собрания
* NVDA + Ctrl + 8: Получен приватный чат во время собрания
* NVDA + Ctrl + 9: Загрузка файла во время собрания завершена
* NVDA + Ctrl + 0: Привилегия участника предоставлена/отозвана
* NVDA + Shift + Ctrl + 1: Участник Поднял/Опустил Руку (Только ведущий)
* NVDA + Shift + Ctrl + 2: Получено/отозвано разрешение на удалённое
  управление
* NVDA + Shift + Ctrl + 3: Получено сообщение IM-чата


Обратите внимание, что для нормальной работы дополнения необходимо оставить
выбранными все типы оповещений (в настройках доступности Zoom).

## Сочетание клавиш для открытия диалога дополнения 

NVDA + Z Открывает диалог дополнения !

Используя этот диалог, вы сможете :

* Просмотреть, какие оповещения объявляются, а какие нет
* Выбрать типы оповещений, которые вам нужно объявлять
* Изменить режим объявления оповещений
* Сохранить пользовательские изменения

## Дистанционное управление 

после получения разрешения на дистанционное управление NVDA + O переместит
фокус на экран с дистанционным управлением или из него

Обратите внимание, что основное внимание должно быть сосредоточено на одном
из элементов управления собранием, чтобы иметь возможность удаленно
управлять другим экраном

## Важное замечание

В настоящее время функция пользовательского режима оповещений (когда
пользователь может выбрать, какие оповещения ему нужны, а какие нет)
работает в Zoom только в том случае, если язык пользовательского интерфейса
установлен на английский.

[[!tag dev stable]]

[1]: https://www.nvaccess.org/addonStore/legacy?file=zoomEnhancements