# 📌 TaPago

Uma plataforma para desenvolvedores e estudantes que querem tirar projetos do papel! Os usuários adicionam ideias de projetos e desafiam amigos a "patrociná-las". Inicialmente concebido para ser uma aplicação web.

## 💡Definições e conceitos:

- **Ludus:** sugestão de nome do app, remete ao nome das antigas escolas de treinamento de gladiadores
- **Arena:** grupo de amigos que verá os projetos e poderá apostar neles, remete a onde ocorriam combates de gladiadores
- **Leão:** projeto que será executado, alusão ao fato de ter que "matar" um leão para entregar o projeto
- **Patrono:** amigo que vai apostar no projeto, na antiguidade eram figuras ricas e influentes contra a procrastinação
- **Tributo:** preço que o Gladiador coloca em jogo ao aceitar um desafio, na Roma Antiga um tributo era um pagamento feito como forma de submissão ou para garantir proteção

## 💡Jogabilidade:

- Usuário cria uma Arena (grupo), onde será gerado um convite para outros amigos entrarem.
- O Gladiador (desenvolvedor) cria um Leão (projeto), com descrição, valor do Tributo (preço apostado) e prazo de entrega.
- Se ele matar o Leão a tempo (cumprir o desafio até o prazo de entrega), pode recuperar seu Tributo.
- Se falhar, o Patrono (quem cobra e avalia se o projeto foi entregue de acordo com as especificações) recebe o Tributo como compensação.

## 🚀 Tecnologias Utilizadas

- **Linguagem:** Python 3.10+
- **Frameworks:** Flask (para backend), SQLite (banco de dados)
- **Outras Ferramentas:** Docker (para ambiente de execução opcional), pytest (para testes)

## 📂 Estrutura do Projeto

```bash
📁 devchallenge
   ├── 📁 src  # Código-fonte
   │   ├── app.py  # Ponto de entrada principal
   │   ├── models.py  # Modelagem dos dados
   │   ├── routes.py  # Rotas da API
   │   ├── services.py  # Lógica de negócio
   ├── 📁 docs  # Documentação
   ├── 📁 tests  # Testes
   ├── 📄 README.md  # Este arquivo
   ├── 📄 .gitignore  # Arquivos ignorados pelo Git
   ├── 📄 requirements.txt  # Dependências do projeto
```

## 🛠️ Instalação e Execução

### Pré-requisitos

- Python 3.10+
- Pip (gerenciador de pacotes do Python)

### Passos para rodar o projeto

```bash
# Clone este repositório
git clone https://github.com/seu-usuario/devchallenge.git

# Acesse a pasta do projeto
cd devchallenge

# Instale as dependências
pip install -r requirements.txt

# Execute o projeto
python src/app.py
```

## ✅ Funcionalidades

- [ ] Criar e gerenciar perfil de usuário
- [ ] Criar e gerenciar projetos
- [ ] Criar e gerenciar custo por tempo
- [ ] Criar e gerenciar grupo de amigos
- [ ] Criar e usar convite para entrar no grupo
- [ ] Monitorar progresso do projeto
- [ ] Alerta de penalidade em caso de não entrega

## 📌 Próximos Passos

- Implementação de um painel para gestão dos projetos
- Integração com serviços de pagamento
- Notificações e lembretes automáticos
- Criação de login e captha
- Painel analitics para acompanhamento de entregas
- Criação de Ranking
- Criação de certificado para publicação no Linkedin

## 🧪 Testes

```bash
# Executar testes
pytest tests/
```

## 📄 Licença

Este projeto está sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.

