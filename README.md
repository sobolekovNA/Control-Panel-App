# Тестовые задания
Боковая панель для создания миссий. 

Процесс разработки:
14.04.22
Все работает на SingleActivity через 2 NavigationControler:

1 - main_page_navigation для создания и добавления новых фрагментов на главный экран

2 - control_panel_navigation для работы с выезжающей панели управления
  
Создание миссии занимет много места, поэтому выезжающее меню справа реализовано через ViewPager, он занимает все пространство на экране, что удобно при заполнении полей.

Все экраны отрисованы как в техническом задании, кнопки работают.

Можно создавать миссии, которые созраняются в базу данных ROOM.

22.04.22
Внесены правки в соответсвии с комментарием от разработчика. А конкретно:

1. Реализовал отображение созданных миссий
2. Поправил верстку в соответсвии с файлом figma
3. Добился стабильной работы приложения

а также

4. Переписал базу данных
5. Добавил возможность редактировать миссии
6. Реализовал выпадающее подменю у миссий
7. Реализовал выпадающее меню поиска
8. Сделал рипл эффект на кнопки


03.05.22
Внесены новые правки:

1. Поправил верстку, теперь она идеальная
2. Реализовал локальные и серверные миссии
3. Добавил тестовые данные в бд
4. Добавил единицы измерения в настройке миссии

Сделано за 16 дней.

![ЦИТ Тестовое задание](https://user-images.githubusercontent.com/83010842/166404663-7158cad8-447d-41e0-b760-75a22b05cb8f.png)
