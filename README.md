# E-commerce

## Descrição do Projeto
Este projeto é uma plataforma de e-commerce desenvolvida com Django, HTML e CSS. Ela permite que usuários naveguem por produtos, adicionem itens ao carrinho de compras e realizem pedidos. Este sistema também inclui gerenciamento de usuários, um painel administrativo para gerenciar produtos e pedidos, e funcionalidades de pagamento.

## Tecnologias Utilizadas
- **Django**: Framework de desenvolvimento web de alto nível que promove desenvolvimento rápido e design limpo.
- **HTML**: Estrutura o conteúdo das páginas.
- **CSS**: Estiliza as páginas, melhorando a experiência do usuário.

## Funcionalidades
- **Navegação de Produtos**: Usuários podem visualizar produtos categorizados.
- **Carrinho de Compras**: Adicionar e remover produtos do carrinho de compras.
- **Gestão de Usuários**: Cadastro, login e gestão de perfis de usuários.
- **Checkout e Pagamento**: Processo de checkout e integração com gateways de pagamento.
- **Painel Administrativo**: Interface para administração de produtos, pedidos e clientes.

## Instalação e Configuração
Para configurar e rodar o projeto localmente, siga os passos abaixo:

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/ecommerce-django.git

2. Navegue até o diretório do projeto:
   ```bash
   cd ecommerce-django

3. Crie um ambiente virtual:
   ```bash
   python -m venv venv

4. Ative o ambiente virtual:
   ```bash
   source venv/bin/activate  # No Windows use `venv\Scripts\activate`

5. Instale as dependências:
   ```bash
   pip install -r requirements.txt

6. Realize as migrações do banco de dados:
   ```bash
   python manage.py migrate

7. Inicie o servidor de desenvolvimento:
   ```bash
   python manage.py runserver



