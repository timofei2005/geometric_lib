# Math formulas
## Area
- Circle: S = πR²
- Rectangle: S = ab
- Square: S = a²

## Perimeter
- Circle: P = 2πR
- Rectangle: P = 2a + 2b
- Square: P = 4a

# Общее описание решения
### В проекте собраны различные математические формулы
Формулы для вычисления площади круга, прямоугольника, квадрата, треугольника
Формулы для вычисления периметра круга, прямоугольника, квадрата, треугольника
## Описания работы программы circle.py
### 1)Описание работы функции Area(г)
### Параметры функции:
 r - радиус круга
### Результат выполнения функции:
Функция возвращает значение площади круга
### Пример работы функции:
- input -> 10
- area10)
- return math.pi * r * r
- output > 314.159265358979


### 2) Описание работы функции perimeter (r)
### Параметры функиии:
- r - радиус круга
### Результат выполнения функции
- Функция возвращает значение длины окружности 
- ### Пример работы финкции:
- input - > 10 
- perimetr (10)
- return 2 * math.pi * r 
- output -> 62.83185307179586
- 
### Описания работы программы rectangle.py

### 1) Описание работы функии area(a, b)
### Параметры функции：
- а - первая сторона прямоугольника
- b - вторая сторона прямоугольника 
### Результат вылолнения функции:
- Функция возвращает значение площади прямоугольника
### Пример работы функции：
- input -> 10 20
- area (10, 20)
- return a * b output -> 200

### 2) Описание работы функции perimetr(a, b)

### Параметры функции:
- a - первая сторона прямоугольника
- b - вторая сторона прямоугольника
### Результат работы функции:
- Функция возвращает значение периметра прямоугольника
### Пример работы функции:
- input -> 10 20
- perimetr (10, 20)
- return 2 * (a + b)
- output -> 60

## Описание работы программы square.py
### 1) Описание работы функции  area(a)

### Параметры функции:
- а - сторона квадрата
### Резильтат выполнения функиии:
- Функция возвращает значение площади квадрата
### Пример работы функции：
- input -> 10
- area (10)
- return a * a output -> 100

### 2) Описание работы функции  perimetr(a)

### Параметры функции:
- а - сторона квадрата
### Резильтат выполнения функиии:
- Функция возвращает значение периметра квадрата
### Пример работы функции：
- input -> 10
- perimetr (10)
- return 4 * a 
- output -> 40


## Описание работы программы triangle.py
### 1) Описание работы функции  area(a, h)

### Параметры функции:
- а - сторона триугольника
- h - высота, опущенная на сторону а
### Резильтат выполнения функиии:
- Функция возвращает значение площади триугольника
### Пример работы функции：
- input -> 10 4
- area (10, 4)
- return a * h / 2 
- output -> 20.0

### 2) Описание работы функции  perimetr(a,b,c)

### Параметры функции:
- а - сторона триугольника
- b - сторона триугольника
- c - сторона триугольника

### Резильтат выполнения функиии:
- Функция возвращает значение периметра триугольника

### Пример работы функции：
- input -> 10,10,10
- perimetr (10,10,10)
- return a + b + c
- output -> 30

### История изменения проекта с хешами коммитов

commit 15c140eb024547d8ebe88099d4ae5e3d095f6c2b

    Добавлена документация на файл triangle.py

commit 87dc1d03f06a9b246a3bb85c216c0a74e3af9984

    Добавлена документация на файл square.py

commit add78d8c01baf7ddb23185ab16f3b70f05b9db41

    Добавленна документация на файл rectangle.py

commit 25e098c3b0c8879ed834730485e4691f298d0b54


    Добавлена документация на файл cyrcle.py

commit cc3c3ec24564fbf1bf688e1f99c3a344024f671b 

    ddsfsdfdsf

commit 8e43e15aa39675d3067ddec8452bcbef6a89d0a7 

    added triangle.py and change perimetr funtion

commit 9ad435e0fde1be9c44c9ab4706f53034eb75a4fa


    added a new file rectangle.py

commit d078c8d9ee6155f3cb0e577d28d337b791de28e2 

    L-03: Docs added

commit 8ba9aeb3cea847b63a91ac378a2a6db758682460


    L-03: Circle and square added
