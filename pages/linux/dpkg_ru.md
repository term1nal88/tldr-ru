# dpkg

> Менеджер *.deb пакетов в Debian.

- Установить новый пакет:

`dpkg -i {{/path/to/file}}`

- Удалить пакет:

`dpkg -r {{package_name}}`

- Вывести список установленных пакетов:

`dpkg -l {{pattern}}`

- Отобразить содержимое пакета:

`dpkg -L {{package_name}}`

- Отобразить, какой пакет содержится в файле:

`dpkg -S {{file_name}}`
