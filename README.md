# Gestão Casamento

Gestão Casamento é uma aplicação web desenvolvida para auxiliar na organização de listas de presentes e convidados para eventos de casamento. Utilizando Django como framework e Tailwind CSS para estilização, o projeto oferece uma interface elegante e intuitiva para que noivos e organizadores possam gerenciar as principais informações do evento de maneira prática.

Tecnologias Utilizadas
- Django: Framework backend em Python, responsável pela lógica e rotas da aplicação.
- HTML e Template Tags do Django: Estrutura básica de páginas e componentes dinâmicos.
- Tailwind CSS: Framework CSS para estilização de componentes com classes utilitárias, tornando o design responsivo e moderno.
- JavaScript (CDN do Tailwind): Inclusão para estilização dinâmica.
- Jinja: Usado para renderização dinâmica de conteúdo, especialmente útil nas templates.

# Funcionalidades
- Página Inicial: Uma navegação simples e organizada para acessar as listas de presentes e convidados.
- Lista de Presentes: Permite o gerenciamento de itens para presente, facilitando a escolha e aquisição de presentes por parte dos convidados.
- Lista de Convidados: Gerencia os convidados do evento, ajudando os organizadores a manterem controle sobre quem foi convidado e quem confirmou presença.

# Estrutura de Arquivo
- navbar.html: Arquivo de navegação compartilhada, carregado em todas as páginas.
- favicon.ico: Ícone de favorito personalizado para a aplicação.
- logo.webp: Logo da aplicação, exibido na barra de navegação.

# Pré-requisitos
- Python 3.x
- Django (instalável via pip)
- Configuração de ambiente virtual (opcional, mas recomendável)

# Como Rodar o Projeto

1. Clone o repositório:
git clone https://github.com/devkapassos/gestao_casamento.git
cd eu-noiva
2. Crie e ative o ambiente virtual:
python -m venv venv
source venv/bin/activate  # Para sistemas Unix
venv\Scripts\activate  # Para Windows
3. Instale as dependências:
pip install -r requirements.txt
4. Execute as migrações:
python manage.py migrate
5. Inicie o servidor local:
python manage.py runserver
6. Acesse http://127.0.0.1:8000/ no navegador para visualizar a aplicação.

# Estrutura de Código
eu-noiva/
├── noivos/
│   ├── templates/
│   │   ├── partials/
│   │   │   └── navbar.html
│   │   └── base.html
│   ├── static/
│   │   └── noivos/
│   │       └── img/
│   │           ├── favicon.ico
│   │           └── logo.webp
├── manage.py
└── README.md
