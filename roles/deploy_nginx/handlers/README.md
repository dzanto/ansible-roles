В handlers/main.yml описываем обработчики(handlers) используемые в задачах

Например handler перезагружающий nginx, после изменения конфигурации web сервера
```
- name: Restart nginx
  service:
    name: nginx
    state: restarted
```
