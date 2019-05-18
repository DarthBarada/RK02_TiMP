Отчет 
======
###### | Митрофанов Дмитрий | Группа ИУ8-23 | 
---
### Выбранные типы:
- [ ] Список
  - [X] list
- [ ] Очередь
  - [ ] queue
- [ ] Дерево
  - [X] tree
- [ ] Множество
  - [ ] set
---
Основная часть
--------------
---
---
### 1. Список
1. [Реализация списка для работы с АТД (arias-spu/adt-list)](https://github.com/janLin9453/Tree)
2. Variable size array (рус. массив переменной длины) - "является структурой данных массива, длина которого определяется во время выполнения (а не во время компиляции).".
3. Файл [vsarray.cpp](https://github.com/arias-spu/adt-list/blob/master/vsarray.cpp)
    >
    > [55](https://github.com/arias-spu/adt-list/blob/b6e649b2667b44b9fb5e8ffb3f1c0a5bf0d500c1/vsarray.cpp#L55) - добавление элемента;
    >
    > [74](https://github.com/arias-spu/adt-list/blob/b6e649b2667b44b9fb5e8ffb3f1c0a5bf0d500c1/vsarray.cpp#L74) - изменение размера;
    >
    > [95](https://github.com/arias-spu/adt-list/blob/b6e649b2667b44b9fb5e8ffb3f1c0a5bf0d500c1/vsarray.cpp#L95) - удаление элемента по позиции;
    >
    > [107](https://github.com/arias-spu/adt-list/blob/b6e649b2667b44b9fb5e8ffb3f1c0a5bf0d500c1/vsarray.cpp#L107) - обращение к элементу по позиции;
4. Данный тип может применяться для хранения совокупностей параметров, объединённых по общему признаку. К примеру степени свободы персонажа в игре и т.п.
### 2. Очередь
`main body`

---
### 3. Дерево

1. [Реализация дерева для работы с АТД (janLin9453/Tree)](https://github.com/janLin9453/Tree)
2. Red Black Tree (рус. Красно-чёрное дерево) - "это одно из самобалансирующихся двоичных деревьев поиска, гарантирующих логарифмический рост высоты дерева от числа узлов и быстро выполняющее основные операции дерева поиска: добавление, удаление и поиск узла".
3. Файл [RedBlackTree.h](https://github.com/janLin9453/Tree/blob/master/RedBlackTree.h)
   > [83](https://github.com/janLin9453/Tree/blob/b50f3da1d5d0614028580f594ddfa1a2853eb017/RedBlackTree.h#L83) - вставка нового элемента в определённую позицию;
   >
   > [123](https://github.com/janLin9453/Tree/blob/b50f3da1d5d0614028580f594ddfa1a2853eb017/RedBlackTree.h#L123) - вставка поддерева;
   >
   > [182](https://github.com/janLin9453/Tree/blob/b50f3da1d5d0614028580f594ddfa1a2853eb017/RedBlackTree.h#L182) - поиск элемента;
   >
   > [200](https://github.com/janLin9453/Tree/blob/b50f3da1d5d0614028580f594ddfa1a2853eb017/RedBlackTree.h#L200) - удаление элемента;
   >
   >[340](https://github.com/janLin9453/Tree/blob/b50f3da1d5d0614028580f594ddfa1a2853eb017/RedBlackTree.h#L340) - печать дерева;
   >
   > [370](https://github.com/janLin9453/Tree/blob/b50f3da1d5d0614028580f594ddfa1a2853eb017/RedBlackTree.h#L370) - перебор элементов ветви дерева;
   >
   > [449](https://github.com/janLin9453/Tree/blob/b50f3da1d5d0614028580f594ddfa1a2853eb017/RedBlackTree.h#L449) - создание уровня;
4. В различных задачах применяются различные виды деревьев:
    * при разработке парсеров или трансляторов полезным может оказаться дерево синтаксического разбора;
    * при работе со строками удобными могут оказаться суффиксные деревья;
    * при разработке оптимальных алгоритмов на графах полезным может оказаться структура данных в виде кучи;
    * двоичные деревья поиска используются при реализациях словаря, они являются достаточно простым и распространенным видом деревьев, поэтому их мы рассмотрим более подробно;
---
### 4. Множество
`main body`

---
