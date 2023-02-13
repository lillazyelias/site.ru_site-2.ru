Role Name
=========
site

Role Variables
--------------
| Name           | Default Value |
| -------------- | ------------- |
| `site1_domain:` | site.ru|
| `site2_domain:`| site-2.ru |

### Playbook

Пример плейбука для запуска роли:
```yaml
---
- hosts: all
  roles:
    - site

