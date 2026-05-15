# Ansible - Projeto Simples

Estrutura minimalista de projeto Ansible para começar rapidinho.

## 📁 Estrutura

```
.
├── ansible.cfg          # Configuração Ansible
├── inventory.ini        # Seus servidores
├── playbook.yml         # Playbook principal
├── requirements.yml     # Dependências (opcional)
├── roles/               # Suas roles
├── templates/           # Templates Jinja2
├── library/             # Módulos customizados
└── tests/               # Testes
```

## 🚀 Quick Start

```bash
# Edite inventory.ini com seus servidores
# Edite playbook.yml com suas tarefas
# Execute:
ansible-playbook playbook.yml
```

## 📝 Próximos Passos

1. Configure seus servidores em `inventory.ini`
2. Crie roles em `roles/`
3. Use templates em `templates/`
4. Adicione testes em `tests/`

Vá expandindo conforme necessário! 🚀
