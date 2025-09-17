# GitHub App

Projeto para gestão e automação de tokens e autenticação no GitHub.

## Descrição

Este projeto contém ferramentas e scripts para:
- Gerenciamento de tokens GitHub
- Autenticação e autorização
- Segurança de credenciais
- Automações relacionadas à API do GitHub

## Instalação

```bash
# Instalar dependências
poetry install --no-root

# Ativar ambiente virtual
source .venv/bin/activate
```

## Uso

```bash
# Executar scripts
python scripts/security.py
```

## Estrutura

```
github-app/
├── scripts/
│   └── security.py
├── pyproject.toml
└── README.md
```

## Dependências

- `pwdlib[argon2]` - Para hash de senhas com Argon2

## Desenvolvimento

Este projeto faz parte da organização [splor-mg](https://github.com/orgs/splor-mg/repositories) e está relacionado ao artigo sobre [Autenticação, Autorização e Tokens JWT no GitHub](https://handbook.splor-mg.org/blog/posts/20250917_autenticacao-autorizacao-tokens-jwt/).
