# UhttBarcodeReference
Universe-HTT barcode reference

[Universe-HTT](https://uhtt.ru)

[Компания Петроглиф](http://www.petroglif.ru)

Самый большой и аккуратный открытый справочник штрихкодов в интернете! Если не верите - поисковики помогут развеять сомнения.
Чуть менее 3 миллионов штрихкодов стандартов ean13,ean8,upc-e,upc-a с соответствующими наименованиями, брэндами и категориями.

Оригинал справочника находится на сервере Universe-HTT - здесь мы размещаем его копию, содержащую следующие поля:

* (ID) Идентификатор товара в базе данных Universe-HTT
* (UPCEAN) Штрихкод
* (Name) Наименование товара
* (CategoryID) Идентификатор категории в базе данных Universe-HTT
* (CategoryName) Наименование категории
* (BrandID) Идентификатор брэнда в базе данных Universe-HTT
* (BrandName) Наименование брэнда

Данные представлены в текстовом формате в кодировке UTF-8 с символом табуляции (0x09) в качестве разделителя полей.

При формировании этого справочника из оригинала извлекаются только валидные UPC/EAN штрихкоды. Таким образом, все
штрихкоды в этом репозитории гарантированно соответствуют указанным стандартам (что не исключает некоторых иных проблем).
Кроме того, штрихкоды EAN13 с ведущей цифрой 2 (приватные коды) практически отсутствуют (без гарантии).

Репозиторий в каталоге DATA содержит данные, разбитые на фрагменты (примерно по 8Мб каждый). Полный файл, упакованный в формате 7z, находится в [релизах](https://github.com/papyrussolution/UhttBarcodeReference/releases).

В качестве благодарности, вы можете отметить звездочкой этот репозиторий, а так же репозиторий [OpenPapyrus](https://github.com/papyrussolution/OpenPapyrus) поскольку именно эту великолепную ERP-систему мы используем для администрирования, обработки и обеспечения доступа к данным справочника через портал [Universe-HTT](https://uhtt.ru).

---------------------------

The largest and most accurate open reference book of bar codes on the Internet! If you do not believe it, the search engines will help dispel doubts.
Slightly less than 3 million bar codes of ean13, ean8, upc-e, upc-a standards with corresponding names, brands and categories.

The original directory is located on the Universe-HTT server - here we place its copy containing the following fields:

* (ID) The identifier of the goods in the Universe-HTT database
* (UPCEAN) Barcode
* (Name) Product name
* (CategoryID) Category ID in the Universe-HTT database
* (CategoryName) Category name
* (BrandID) Brand identifier in the Universe-HTT database
* (BrandName) Brand name

Data is presented in text format in UTF-8 encoding with a tab (0x09) as a field separator.

When creating this directory, only valid UPC / EAN barcodes are extracted from the original. Thus, all
barcodes in this repository are guaranteed to meet the specified standards (which does not exclude some other problems).
In addition, bar codes EAN13 with leading digit 2 (private codes) are practically absent (without warranty).

The repository in the DATA directory contains data broken into fragments (approximately 8MB each). The complete file, packed in 7z format, is in [releases](https://github.com/papyrussolution/UhttBarcodeReference/releases).

As gratitude, you can mark this repository with an asterisk, as well as the [OpenPapyrus](https://github.com/papyrussolution/OpenPapyrus) repository, since we use this excellent ERP-system for administration, processing and access to the directory data through the portal [Universe-HTT](https://uhtt.ru).
