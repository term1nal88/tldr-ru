# unar

> Распаковать файлы из архива.  

- Распаковать файлы из архива в текущую директорию:

`unar {{archive}}`

- Распаковать файлы из архива в указанную директорию:

`unar -o {{path/to/directory}} {{archive}}`

- Перезаписать извлекаемый файл, если файл с таким именем уже существует:

`unar -f {{archive}}`

- Переименовать извлекаемый файл, если файл с таким именем уже существует:

`unar -r {{archive}}`

- Пропустить извлекаемый файл, если файл с таким именем уже существует:

`unar -s {{archive}}`
