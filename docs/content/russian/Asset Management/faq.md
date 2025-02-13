+++
title = "Часто задаваемые вопросы"
weight = 3
+++

##### Как установить инструменты?

Вы можете скачать «Mount & Blade Bannerlord Modding Tools» в разделе «Инструменты» Steam. Обратите внимание, что инструменты используют некоторые файлы, загруженные в самой игре. Таким образом, инструменты и игра должны быть одной версии и установлены на одном жестком диске.

##### Как запустить инструменты?
Вы можете использовать опцию ```SinglePlayer``` из ```Launcher```, и как только вы окажетесь в начальном меню, вы можете либо нажать кнопку ```Editor```, либо комбинацию клавиш ```Ctrl + E```, чтобы запустить редактор.

##### Как создать ваш собственный модуль?
У нас есть встроенная функция в редакторе, которая создает новый модуль и заполняет его примерами XML-файлов, зарегистрированных в модуле, для упрощения добавления нового контента. После открытия редактора вы можете использовать опцию «Create New Module» в меню «File» на верхней панели инструментов. Обратите внимание, что вам необходимо перезапустить игру, чтобы зарегистрировать модуль из Launcher.

##### Как редактировать оригинальные ресурсы?
Вы не можете редактировать оригинальные ресурсы, вы можете переопределить их в своем собственном модуле. Подробности смотрите на http://docs.modding.bannerlord.com/asset-management/asset-types/overriding_assets/

##### Я не могу добавить новые меши, текстуры и т.д.
Вы не можете добавлять ресурсы в оригинальные модули, вы должны добавить их в свой собственный модуль. В начале вам необходимо создать новый модуль: http://docs.modding.bannerlord.com/asset-management/quickguide_create_a_mod/
Подробнее о добавлении новых ассетов: http://docs.modding.bannerlord.com/asset-management/asset-types/overriding_assets/

##### Примеры сцен на которые стоит обратить внимание

- empire_village_003
- khuzait_castle_002
- sturgia_town_b
- battle_terrain_v
- empire_castle_keep_a_l3_interior
- empire_house_c_tavern_a
- empire_dungeon_a
- arena_empire_a
- Main_map

##### Где найти примеры ассетов?
Вы можете просмотреть исходные ресурсы из браузера ресурсов, но для них нет исходных файлов, и вы не можете их экспортировать. Вскоре мы предоставим несколько примеров исходных файлов. 

##### У меня есть моды с DLL, и мои инструменты для создания модов не запускаются.
Если у вас есть какие-либо моды с включенными DLL, обязательно скопируйте их также в папку ```Modules\MOD_NAME\bin\Win64_Shipping_wEditor```.

##### Мои инструменты моддинга не запускаются
Убедитесь, что на вашем компьютере установлен Visual Studio 2013 Redist x64. Также проверьте, совпадают ли номера версий базовой игры и инструментов моддинга. Если все вышеперечисленные проверки не работают, вы можете создать новую тему в разделе «Bug & Crashes» на форумах по моддингу (https://forums.taleworlds.com/index.php?forums/bug-crash-reports.784/). 