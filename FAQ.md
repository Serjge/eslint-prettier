## FAQ

### Если после клона с репозитория во всех файлах ругаеться eslint на пробел в конце строк?
Выполнить команды в терминале: 

git config core.autocrlf false 

git rm --cached -r. 

git reset --hard
