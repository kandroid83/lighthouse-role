# lighthouse-role

Роль Ansible для установки Lighthouse — веб-интерфейса для ClickHouse, раздаётся через Nginx.

## Переменные

| Переменная | Значение по умолчанию | Описание |
|---|---|---|
| lighthouse_dest | /var/www/lighthouse | Куда клонировать репозиторий |
| lighthouse_port | 80 | Порт Nginx |
| nginx_user | www-data | Пользователь Nginx |

## Пример использования

    - hosts: lighthouse
      roles:
        - lighthouse-role
