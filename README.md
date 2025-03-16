📚 Gerenciamento de Biblioteca

📖 Descrição

Bem-vindo ao Gerenciamento de Biblioteca, um sistema desenvolvido em Python para organizar e gerenciar livros, autores, categorias e editoras. A arquitetura do projeto segue o padrão MVC (Model-View-Controller) simplificado, com camadas bem definidas.

📂 Estrutura do Projeto

/
├── dao/                 # Camada de Acesso a Dados (Data Access Object)
│   ├── autor_dao.py
│   ├── categoria_dao.py
│   ├── editora_dao.py
│   ├── livro_dao.py
│
├── model/               # Modelos das entidades do sistema
│   ├── autor.py
│   ├── categoria.py
│   ├── editora.py
│   ├── livro.py
│   ├── utils.py
│
├── service/             # Camada de Serviço (Regras de Negócio)
│   ├── autor_service.py
│   ├── categoria_service.py
│   ├── editora_service.py
│   ├── livro_service.py
│
├── main.py              # Ponto de entrada do sistema
├── README.md            # Documentação do projeto
├── .gitignore           # Arquivos ignorados pelo Git

⚙️ Requisitos

Python 3.8+

Bibliotecas adicionais (se houver)

🚀 Instalação

# Clone o repositório
git clone https://github.com/seu-usuario/seu-repositorio.git

# Acesse o diretório do projeto
cd nome-do-projeto

# Instale as dependências (caso necessário)
pip install -r requirements.txt

🏃 Uso

Para iniciar o sistema, utilize:

python main.py

🤝 Contribuição

Quer contribuir? Siga os passos:

Faça um fork do repositório

Crie uma branch para a sua funcionalidade (git checkout -b minha-feature)

Realize suas alterações e faça commit (git commit -m 'Adiciona minha feature')

Envie para o repositório remoto (git push origin minha-feature)

Abra um Pull Request