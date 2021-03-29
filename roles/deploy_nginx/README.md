### Создание roles
Для создания roles необходимо в проекте создать папку с названием roles и перейти в нее
```
mkdir roles; cd roles
```
Выполнить команду инициализации role указав имя(например deploy-nginx):
```
ansible-galaxy init deploy-nginx
```
при инциализации создастся структура пустых файлов main.yml и каталогов:
- tasks - главный список задач выполняемых ролью
- handlers - обработчики указанные в задачах
- defaults - дефолтные переменные для роли
- vars - остальные переменные для роли
- files - файлы предназначенные для деплоя ролью
- templates - j2 шаблоны предназначенные для деплоя ролью
- meta - метаданные
- tests

https://docs.ansible.com/ansible/latest/user_guide/playbooks_reuse_roles.html
