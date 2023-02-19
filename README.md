# SimCity_RUS

#Русификатор для SimCity™

Файлы Русского языка взяты из оригинальной игры из Origin (EA App)

Если вы как и я купили игру на сторонем сайте и у вас только англ. версия то это вам поможет...

![img](/img/Instal1.png)
![img](/img/Instal2.png)

# Есть два способа поставить русский язык в игру: 

1. Закинуть папку с русским языком в папку игры
(У меня сработало но на второй запуск игры выдало ошибку)

![error](/img/error.png)

2. Заменить файл (Data.package) английского языка на русский


# Способ №1

Всю папку из архива закинуть в место, где у вас установлена SimCity 
У меня это C:\Program Files\EA Games

Там два файла для русского 

\SimCity\GDFBinary_ru_RU.dll

\SimCity\SimCityData\Locale\ru-ru\Data.package


![reg](/img/reg.jpeg)

Win+R, прописать regedit
Найдите игру в реестре и измените параметр "Locale" на ru_RU
Путь: \HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\Maxis\SimCity


# Способ №2

Взять из архива файл :

\SimCity\SimCityData\Locale\ru-ru\Data.package

Поместить его с заменой в папку с игрой по пути:

\SimCity\SimCityData\Locale\en-us\Data.package

# Теперь можно спокойно играть на русском языке

![ru_RU](/img/ru_RU.jpeg)
