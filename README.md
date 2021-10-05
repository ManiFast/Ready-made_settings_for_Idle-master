### Инстукция по созданию **ИСПОЛНЯЕМОГО ФАЙЛА** для idle master

+ Перекидываем папку `idle master` на рабочий стол или любую другую папку (*Важно не изменять название папок*).

+ Создаём на рабочем столе фаил с расширением ".bat", и пишем туда команды как в cmd (Подтема. Работа с атрибутом dir).

```
cd idle master/
cd idle_master_extended_v1.7/
```
+ Далее заходим в стим и в магазине ищем игру которую хотим запустить, копируем адресс страницы (ПКМ, copy URL)

+ Вставляем в браузер и копируем цифры

<!--фото 1-->
![](https://github.com/Stas-inside/Ready-made_settings_for_Idle-master/blob/main/Pictures/Capture.PNG)

+ потом вставляем в фаил "start steam-idle.exe " и ваше скопированное число.

Вот как должно быть у вас

```
dir
cd DarkC/
cd idle master/
cd idle_master_extended_v1.7/

start steam-idle.exe 730
```

+ Когда вы добавите много игр, чтобы не запутаться можно добавлять коментарий rem и двльше любое слово (**из тогоже семейства cmd**).
Например:
```
dir
cd DarkC/
cd idle master/
cd idle_master_extended_v1.7/

start steam-idle.exe 730 rem CSGO
start steam-idle.exe 1172470 rem Apex
start steam-idle.exe 220200 rem KSP
```

+ После чего запустить фаил, *и не открывать игру*.
<!--фото 2-->
![](https://github.com/Stas-inside/Ready-made_settings_for_Idle-master/blob/main/Pictures/Captu323re.PNG)

**\s/**
