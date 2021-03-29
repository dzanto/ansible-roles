tasks/main.yml содержит список основных задач, задачи могут быть разделены на разные yml файлы и подключены в main.yml с помощью - include, например:
```
---
- include: nginx-setup.yml
- include: create-log.yml
- include: reboot.yml
- include: error-handling.yml
```
