# Exemplo de role simples

Crie suas roles aqui com a estrutura:

```
minha_role/
├── tasks/
│   └── main.yml
├── defaults/
│   └── main.yml
├── templates/
└── handlers/
    └── main.yml
```

Depois use no playbook.yml:
```yaml
roles:
  - minha_role
```
