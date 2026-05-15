# Módulos Customizados

Adicione seus módulos Python customizados aqui.

Exemplo de módulo simples:

```python
#!/usr/bin/python

from ansible.module_utils.basic import AnsibleModule

module = AnsibleModule(
    argument_spec=dict(
        name=dict(required=True, type='str'),
    )
)

result = dict(
    changed=False,
    message=f"Hello {module.params['name']}"
)

module.exit_json(**result)
```

Use no playbook:
```yaml
- name: Usar módulo customizado
  meu_modulo:
    name: "World"
```
