# B661
---

Ansible роль для установки, запуска службы и добавления конфигурционного файла vsftpd на localhost. 

---

Скопировать по пути /etc/ansible/roles. При необходимости изменить адрес в vsftpd/tests/inventory

Запуск playbook: ansible-playbook  .vsftpd/tests/test.yml -K

```-K, --ask-become-pass  ask for privilege escalation password (пароль рута, для повышения привилегий при подключении)```
```-k, --ask-pass         ask for connection password (пароль для входа)```

