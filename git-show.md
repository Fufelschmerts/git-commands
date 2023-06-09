[⬅ к содержанию](./readme.md)

# git show 

**git show [хэш]** показывает информацию по определённому коммиту.

При выполнении команды **git show** вы можете указать идентификатор коммита, ветку, тег или любой другой указатель на коммит. Git отобразит информацию о выбранном коммите, включая следующие сведения:

**Коммит**: Уникальный идентификатор коммита (SHA-1 хэш).

**Автор**: Имя и адрес электронной почты автора коммита.

**Дата**: Дата и время создания коммита.

**Сообщение** **коммита**: Описание изменений, внесенных в коммите.

**Изменения файлов**: Перечисление файлов, измененных в коммите, и их статусы (добавление, изменение, удаление).

**Пример**

```bash=
$ git show <commit>  # Показать информацию о конкретном коммите
$ git show HEAD      # Показать информацию о последнем коммите
$ git show           # Показать информацию о текущем коммите (HEAD)
```