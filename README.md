# B6.6.1

## Задание

Ссылка: [здесь](./TASK.md)

## Решение

Ansible-описание создавание роли - [roles/vsftpd/](./roles/vsftpd/)

```
# Заполняем перечень удаленных хостов для выполнения задания
vi hosts

# Устанавливаем, настраиваем сервис vsftpd
ansible-playbook site.yml -i hosts

# (На удаленных хостах) Проверяем наличие сервиса vsftpd
# systemctl status vsftpd
```
