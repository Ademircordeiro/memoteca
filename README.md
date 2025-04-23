# Memoteca

\
Bem-vindo! Este repositório contém o projeto desenvolvido em estudo na Alura, com **Angular** para aprimorar minhas habilidades no framework Angular.

## 📖 Sobre o Projeto

A **Memoteca** é uma biblioteca de pensamentos. O projeto foi criado para consolidar conhecimentos em:

- **Diretivas**: Utilização de diretivas para manipular a exibição dos elementos na interface.
- **Services**: Criação de serviços para centralizar a lógica de negócio e compartilhamento de dados entre componentes.
- **Injeção de dependências**: Implementação do padrão de injeção de dependências do Angular para garantir modularidade e reutilização de código.
- **Requisições HTTP**: Consumo de uma API simulada com o uso do HttpClient para envio e recebimento de dados.

Este projeto é ideal para quem deseja estudar Angular ou explorar exemplos práticos de suas funcionalidades.

## 🚀 Funcionalidades

- 🔍 **Mural** de pensamentos:
  - Procurar
  - Favoritar
  - Editar
  - Excluir
- 🔍 **Novo pensamento**

## 🛠️ Tecnologias Utilizadas

- **Frontend**:
  - **Angular 14.0.0**: Framework principal.
  - **TypeScript**: Para tipagem estática e código robusto.
  - **CSS**: Estilização.
- **Ferramentas**:
  - **Git**: Controle de versão.
  - **npm**: Gerenciamento de dependências.
  - **Json Server**: Ferramenta para simular uma API REST fake, permitindo testar requisições HTTP com dados mockados durante o desenvolvimento.

## 📦 Instruções de Instalação

Siga os passos abaixo para rodar o projeto localmente:

1. **Clone o repositório**:

   ```bash
   git clone https://github.com/Ademircordeiro/memoteca.git
   cd memoteca
   ```

2. **Instale as dependências**:

   ```bash
   npm install
   ```

3. **Inicie o Json Server**:

   ```bash
   json-server --watch .\backend\db.json
   ```

4. **Inicie o servidor de desenvolvimento**:

   ```bash
   ng serve -o
   ```

## 🖥️ Como Usar

1. Abra a aplicação no navegador.
2. Use botão "Meu mural" para vizualizar os pensamentos cadastrados.
   - Use os ícones dentro de cada pensamento para Favoritar, Editar e Excluir pensamentos.
3. Use o botão "Meus favoritos para visualizar apenas os pensamentos favoritados".
4. Use o botão "Novo pensamento" para cadastrar um novo pensamento.
5. Explore o código-fonte para entender como **Diretivas**, **Services** e **Requisições HTTP** foram implementados.

## 🤝 Como Contribuir

1. Faça um **fork** do repositório.

2. Crie uma branch para sua feature:

   ```bash
   git checkout -b feature/nova-feature
   ```

3. Commit suas mudanças:

   ```bash
   git commit -m 'Adiciona nova feature'
   ```

4. Push para a branch:

   ```bash
   git push origin feature/nova-feature
   ```

5. Abra um **Pull Request** no GitHub.

## 📬 Contato

- **Autor**: Ademir Cordeiro
- **GitHub**: [Ademircordeiro](https://github.com/Ademircordeiro)
- **LinkedIn**: [linkedin.com/in/ademircordeiro](https://www.linkedin.com/in/ademircordeiro/)

📧 Dúvidas ou sugestões? Entre em contato via LinkedIn ou abra uma issue!

## ⭐ Apoie o Projeto

Gostou do projeto? Deixe uma **estrela** no repositório para apoiar! 🚀
