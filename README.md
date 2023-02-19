# SimCity_RUS
Русификатор для SimCity™

# Если вы как и я Купили игру на сторонем сайте и у вас только Англ версия то это вам поможет

![img](/img/Instal1.png)
![img](/img/Instal2.png)

# Есть два способа поставить Русский язык в игру 

1 : закинуть папку с Русским языком в папку игры

(у меня сработало но на второй запуск игры выдало Ошибку)

![error](/img/error.png)

2 : заменить файл (Data.package) Английского языка на Русский


# Способ №1

Всю папку из Архива закинуть в место где у вас устоновленна SimCity 
У меня это C:\Program Files\EA Games

Там два Файла для Русского 

\SimCity\GDFBinary_ru_RU.dll

\SimCity\SimCityData\Locale\ru-ru\Data.package


![reg](/img/reg.jpeg)

Win+R прописать regedit
Найдите игру в реестре и измените параметр "Locale" на ru_RU
Путь \HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\Maxis\SimCity


# Способ №2

Взять из архива файл :

\SimCity\SimCityData\Locale\ru-ru\Data.package

Посестить его с заменой в папку с игрой по пути:

\SimCity\SimCityData\Locale\en-us\Data.package

# Теперь можно спокойно играть на Русском языке

![ru_RU](/img/ru_RU.jpeg)
