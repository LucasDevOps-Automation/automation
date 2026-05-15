# Templates Jinja2

Adicione seus templates aqui e use nos playbooks:

```yaml
- name: Usar template
  template:
    src: arquivo.j2
    dest: /etc/arquivo.conf
```
