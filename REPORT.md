Отчет 
======
###### | Митрофанов Дмитрий | Группа ИУ8-23 | 
***
### Задача:
Выбрать на github по одному проекту, иллюстрирующему работу с абстрактными типами данных (список, очередь, дерево, множество).

Для приведенных типов данных необходимо отметить (номерами строк в файлах) функции работы с абстрактными типами данных (далее АТД), которые были пройдены на лекциях.

Также необходимо отметить, для чего применяется данный АТД в проекте (2-3 предложения).

Про каждый АТД в отчете необходимо написать:
   * Имя проекта
   * Тип данных
   * Номера строк с функциями АТД
   * Описание назначения АТД
---
### Выбранные типы:
- [ ] Список
  - [X] list
- [ ] Очередь
  - [ ] queue
- [ ] Дерево
  - [ ] tree
- [ ] Множество
  - [ ] map
  
## Основная часть
### 1. Список
1. Проект: [Lockstar/lockstar-gta-sa-mod](https://github.com/Lockstar/lockstar-gta-sa-mod)
2. list
3. [CTaskManagementSystemSA.cpp](https://github.com/Lockstar/lockstar-gta-sa-mod/blob/eb73e1b2dcb3366d5008f21275e98ca921b258e3/src/game_sa/CTaskManagementSystemSA.cpp) - файл системнго менеджмента задач, в котором описываются методы одноимённой библиотеки [CTaskManagementSystemSA.h](https://github.com/Lockstar/lockstar-gta-sa-mod/blob/eb73e1b2dcb3366d5008f21275e98ca921b258e3/src/game_sa/CTaskManagementSystemSA.h).
###### Объявление:  [std::list < STaskListItem* >     m_TaskList](https://github.com/Lockstar/lockstar-gta-sa-mod/blob/eb73e1b2dcb3366d5008f21275e98ca921b258e3/src/game_sa/CTaskManagementSystemSA.h#L47) ;
   >
   > [33](https://github.com/Lockstar/lockstar-gta-sa-mod/blob/eb73e1b2dcb3366d5008f21275e98ca921b258e3/src/game_sa/CTaskManagementSystemSA.cpp#L33), [34](https://github.com/Lockstar/lockstar-gta-sa-mod/blob/eb73e1b2dcb3366d5008f21275e98ca921b258e3/src/game_sa/CTaskManagementSystemSA.cpp#L34) - получение итераторов на начало и конец вектора;
   >
   > [40](https://github.com/Lockstar/lockstar-gta-sa-mod/blob/eb73e1b2dcb3366d5008f21275e98ca921b258e3/src/game_sa/CTaskManagementSystemSA.cpp#L40) - очистка вектора ;
   >
   > [49](https://github.com/Lockstar/lockstar-gta-sa-mod/blob/eb73e1b2dcb3366d5008f21275e98ca921b258e3/src/game_sa/CTaskManagementSystemSA.cpp#L49) - добавление в конец ;
   >
   > [71](https://github.com/Lockstar/lockstar-gta-sa-mod/blob/eb73e1b2dcb3366d5008f21275e98ca921b258e3/src/game_sa/CTaskManagementSystemSA.cpp#L71) - удаление элемента методом erase ;
   > 
4. Используемая переменная m_TaskList типа std::list<...> нужна для хранения задач, которые будут выполнены в ходе работы программы. Выбранный тип обосновывается набором операций над ним (очистка, удаление элементов, добавление элементов, последовательный обход), а также отсутствием необходимости доступа к i-му элементу.
---
### 2. Очередь
1.Проект: [ ]()
2. 
3. 
   > 
   > []() - ;
   >
   > []() - ;
   >
   > []() - ;
   >
   > []() - ;
   > 
4.
---
### 3. Дерево
1.Проект: [ ]()
2. 
3. 
   > 
   > []() - ;
   >
   > []() - ;
   >
   > []() - ;
   >
   > []() - ;
   > 
4.
---
### 4. Множество
1. Проект: [Lockstar/lockstar-gta-sa-mod](https://github.com/Lockstar/lockstar-gta-sa-mod)
2. map
3. [CGameSA.cpp](https://github.com/Lockstar/lockstar-gta-sa-mod/blob/eb73e1b2dcb3366d5008f21275e98ca921b258e3/src/game_sa/CGameSA.cpp) - файл внутриигровых интерфейсных возможностей, в котором описываются методы одноимённой бибилиотеки [CGameSA.h](https://github.com/Lockstar/lockstar-gta-sa-mod/blob/eb73e1b2dcb3366d5008f21275e98ca921b258e3/src/game_sa/CGameSA.h).
###### Объявление:  [std::map < std::string, BYTE* > m_Cheats](https://github.com/Lockstar/lockstar-gta-sa-mod/blob/eb73e1b2dcb3366d5008f21275e98ca921b258e3/src/game_sa/CGameSA.h#L231) ;
   > 
   > [513](https://github.com/Lockstar/lockstar-gta-sa-mod/blob/eb73e1b2dcb3366d5008f21275e98ca921b258e3/src/game_sa/CGameSA.cpp#L513) - нахождение содержимого контейнера по ключу ;
   >
   > [531](https://github.com/Lockstar/lockstar-gta-sa-mod/blob/eb73e1b2dcb3366d5008f21275e98ca921b258e3/src/game_sa/CGameSA.cpp#L531) - получение итераторов на начало и конец вектора; ;
   >
4. Используемая переменная m_Cheats типа std::map<...> нужна для хранения читов и информации о их состоянии (вкл или выкл), которые будут использованы в ходе работы программы.
---
