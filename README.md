## Описание проекта 
<b>Парсер для поиска товаров с максимальными бонусами на сайте СберМегаМаркет.</b><br><br>
<em>Просматривает все товары и возвращает датафрейм с данными по каждому товару, включая размер бонуса и его процент от стоимости.
С помощью переменных можно задать: город доставки, интересующий каталог с товарами и количество просматриваемых страниц в каталоге.</em>

## Использование
1. клонировать репозиторий
```
git clone https://github.com/MawneIl/parser_SberMegaMarket.git
``` 
2. перейти в корневую папку проекта используя GitBash
```
cd parser_SberMegaMarket
```
3. установить необходимые библиотеки из файла requirements.txt
```
pip install requirements.txt
```
5. открыть в редакторе файл main
6. в ячейке variables изменить переменные, используя подсказки
7. запустить все ячейки на выполнение.

<em>В результате, ниже ячейки variables будет доступен датафрейм df с таблицей по всем товарам из указанного каталога.
В конце файла реализован поиск лучшего предложения с выводом ссылки на товар.</em>

## Технологии
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Selenium](https://img.shields.io/badge/-selenium-%43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![BeautifulSoup4](https://img.shields.io/badge/BeautifulSoup4-%23ffffff.svg?style=for-the-badge&logo=BeautifulSoup4&logoColor=black)
