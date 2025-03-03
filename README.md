# backpackpars
Парсит лидерборд бэкпака (первую 1000) быстро и через питончик

Краткий гайд по запуску скрипта

Установить Python
Убедитесь, что у вас установлен Python 3. Протестировано обычно на Python 3.7+.

Установить необходимые библиотеки

Selenium: pip install selenium
BeautifulSoup (библиотека bs4): pip install beautifulsoup4
Для WebDriver (например, ChromeDriver) нужно либо:
Установить драйвер вручную (скачать ChromeDriver, положить его в PATH или в папку со скриптом), либо
Установить через менеджер: pip install webdriver-manager и подкорректировать код, чтобы использовать from webdriver_manager.chrome import ChromeDriverManager.
Если не хотите возиться с менеджерами, просто держите актуальный ChromeDriver рядом со скриптом и назовите его chromedriver.exe (на Windows) или chromedriver (на Linux/Mac).

Скачать/создать файл со скриптом

Скопируйте весь Python-код в файл, например io_parser.py.
В нём уже есть все нужные импорты и функции.
Запуск скрипта

Откройте терминал/командную строку и перейдите в папку со скриптом (где лежит io_parser.py и chromedriver при необходимости).
Выполните:

python io_parser.py
