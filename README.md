# AddressByNameQGIS

Для работы плагина необходимы следующие зависимости
-
- overpy - https://pypi.org/project/overpy/
- geopy - https://pypi.org/project/geopy/
- pandas - https://pypi.org/project/pandas/

 Для установки библиотек необходимо в OSGeo4WShell следующую команду:
```python -m pip install overpy geopy pandas```

После установки библиотек открываем QGIS Desktop и переходим в Модули -> Управление модулями -> Параметры

Необходимо поставить галочку "Разрешить установку экспериментальных модулей"

Далее в разделе "Репозитории" нажать кнопку "Добавить", придумать название репозитория, и в поле "URL" вставить ссылку - ```https://lollipop4253.github.io/AddressByNameQGIS/zip/plugins.xml```