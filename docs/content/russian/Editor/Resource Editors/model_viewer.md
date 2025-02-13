+++
title = "Средство просмотра моделей"

[menu.main]
identifier = "model_viewer"
+++

------------------

Доступ к средству просмотра моделей можно получить из: Editor <strong>> </strong> Window <strong>> </strong> Show Model
![](/img/model_viewer/mv_empty.PNG)

На левой панели вы можете изменить Atmosphere, скрыть/показать землю или добавить столько объектов, сколько захотите. Сущности могут быть <strong>Human</strong> или простыми <strong>Mesh</strong>.
При нажатии <strong>Add Entity</strong> откроется модальное окно для выбора типа объекта.
![](/img/model_viewer/mv_add_entity.PNG)


#### Трансформация ####
На этой панели вы можете установить объекты Transform, Rotation и Scale.

#### Анимация ####
На этой панели вы можете выбрать тип скелета и анимацию. \\
Вы также можете фильтровать анимацию по имени. \\
Система фильтрации довольно сильна во всем движке, поэтому вы можете точно настроить фильтрацию. Некоторые примеры:\\
- idle = Будет фильтровать анимацию, содержащую "idle" \\
- .idle = Отфильтрует анимацию, начинающуюся с "idle" \\
- idle. = Отфильтрует анимацию, заканчивающуюся на "idle" \\
- -idle = Отфильтрует анимацию, не содержащую "idle" \\
 --- *Вы также можете использовать комбинации этих фильтров, помещая между ними пробел.* \\
- "idle -barmaid 2." = Будет фильтровать анимацию, содержащую "idle", и не содержащую "barmaid", и заканчивающеюся на "2". (например "guard_idle_2" который соответствует этому условию) \\
- "idle hangout 7" = Будет фильтровать анимацию, содержащую "idle", "hangout", и "7". (например "anim_hangout_idle_7" который соответствует этому условию)

--- Вы также можете наложить другую анимацию с помощью панели наложения.

#### Визуальные эффекты ####

На этой панели вы можете поместить любую сетку в любую часть человека и выбрать пол этого человека.

![](/img/model_viewer/mv_full.PNG)
![](/img/model_viewer/mv_fun.PNG)

## Сохранение / Загрузка сцены ##

Вы также можете сохранить / загрузить текущую рабочую сцену, щелкнув; File <strong>></strong> Save Scene <strong>></strong> *..Имя сохранения..* \\
Затем вы можете загрузить его с помощью; File <strong>></strong> Load Saved Scene <strong>></strong> *..Имя сохранения..* \\
Это восстановит все до состояния, в котором вы его сохранили. 
