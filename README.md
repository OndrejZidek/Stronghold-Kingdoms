Only for educational purposes and personal using!
-----------
Not for online playing!
-----------

# Stronghold-Kingdoms
Fully work game client source + bot  
  
Game version: 2.0.26.1  
Path to game: C:/ProgramData/Firefly Studios/Stronghold Kingdoms/2.0.26.1/  

# Compile and Install  
Compile project in VisualStudio with all linked references. They should be placed in game folder (near StrongholdKingdoms.exe).  
Replace original StrongholdKingdoms.exe with compiled and launch it without launcher (updater).
  
Help
-----------
Site: http://shkbot.xyz/  
  
Features:
-----------

    Card autoloot
    Autotrading
        With target
        With parishes
        Many options
    Autoscouting
        Many options
    Autoreserching queue
    Not detectable


In future:

    Autorepair
        with troop placing
    More info about stashes at world map
    Building queue


=====

TODO:
-----------
     Автопочинка замка
        размещение войск
        достройка поломанного
    Автонайм
    Обновление глобальной карты раз в некоторое время
    Система автоматического управления монахами
    Проверка на lvlup карт
        вызывает ошибку двойного лута карт из-за нашей функции автолута
        можно добавить слип на минуту перед лутом и повторный чек (сомнительно – хак)
    Опция автопрогрузки деревни раз в некоторое время
        С проверкой по таймеру ожидания на мировой карте
    Файлы конфигурации бота
    Ограничение по продажам ресурсов в % (например, продавать только 20% от максимума)
        Приоритет (очередь) для торговли
    Улучшенный скаутинг
        каждой деревне по потоку
        близкие стеши в приоритете
        не разведанные стеши в приоритете
        выбор типов ресурсов для разведки
        реализация нормальной отправки единовременно не всех скаутов
        проверка количества ресурсов в тайнике перед отправкой (чтобы не разведывать волков и т.д.)
    Очередь строительства
    Информация о стешах на глобальной карте
        Количество ресурсов в остатке
        Быстрая отправка скаутов
    Исправить ошибку текстур мировой карты
