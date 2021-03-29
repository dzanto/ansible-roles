# Ansible roles
### Создание roles
Для создания roles необходимо в проекте создать папку с названием roles и перейти в нее
```
mkdir roles; cd roles
```
Выполнить команду инициализации role указав имя(например deploy-nginx):
```
ansible-galaxy init deploy-nginx
```
при инциализации создастся структура каталогов: defaults, files, handlers, meta, tasks, templates, tests, vars,
и пустых файлов main.yml
