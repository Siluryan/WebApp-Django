## Controle de estoque

### Como iniciar o projeto:

- Clone esse repositório
- Crie um ambiente virtual com Python 3 [instruções](https://cloud.google.com/python/docs/setup?hl=pt-br#linux)
- Instale as dependências (requirements.txt)
- Rode as migrações

Exemplo:
```sh
git clone git@github.com:Siluryan/Django-Estoque.git
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
```

Observação:
Caso o seu ambiente virtual não encontre os módulos (ex.:django.core.management) instale o django na sua estação de trabalho.