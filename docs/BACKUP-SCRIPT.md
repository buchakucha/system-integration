# Cкрипт для резервного копирования данных backup.rb
Для работы скрипта необходимо передать три обязательных параметра с ключами:
1. `--pathdir="PATH_TO_DIRECTORY"` - путь до директории с проектом
2. `--pathbackup="PATH_TO_DIRECTORY_WITH_BACKUP"` - путь до директории, в которой будет содержаться backup-архив
3. `--action="ACTION"` - действие, которое необходимо выполнить:
	- `zip` - заархивировать данные приложений
	- `unzip` - разархивировать данные приложений
Скрипт хранится в папке `\backup`.
# Пример вызова
`./backup.rb --action="zip" --pathbackup="~/backups/" --pathdir="../"`
