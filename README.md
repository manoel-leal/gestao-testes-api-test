# gestao-testes-api-test
Projeto de automação de testes de API REST utilizando as tecnologias Supertest + Jest (Javascript).\

# Projeto de Automação de Testes de API REST

## 📌 Introdução
Este repositório contém a automação de testes para a API REST do sistema, utilizando as bibliotecas **Supertest** e **Jest**.  
O objetivo é garantir a qualidade e confiabilidade das funcionalidades expostas pelo back-end, validando cenários de sucesso e falha de forma automatizada.  

### Tecnologias utilizadas
- [Node.js](https://nodejs.org/)  
- [Jest](https://jestjs.io/) — framework de testes  
- [Supertest](https://github.com/ladjs/supertest) — cliente HTTP para testes de APIs  
- [Faker](https://www.npmjs.com/package/faker) — geração de dados dinâmicos para os testes  

---

## ✅ Pré-requisitos
Antes de iniciar, certifique-se de ter instalado:
- **Node.js** (versão 16 ou superior)  
- **npm** (gerenciador de pacotes do Node)  
- A aplicação **back-end** em execução localmente  

---

## 🔗 Repositório da aplicação back-end
A aplicação que será testada está disponível em:  
[https://github.com/manoel-leal/gestao-testes-api-sandbox](https://github.com/manoel-leal/gestao-testes-api-sandbox)

---

## ⚙️ Configuração e instalação
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio-testes.git
    ```
2. Acesse a pasta do projeto:
   ```bash
   cd seu-repositorio-testes
    ```
3. Instale as dependências:
   ```bash
   npm install
    ```
4. - Configure as variáveis de ambiente (se necessário), como a URL base da API:
- Arquivo: config/urls.js
- Exemplo:
   ```bash
   module.exports = {
  BASE_URL: "http://localhost:3000/api",
  PATHS: {
    LOGIN: "/login",
    USUARIOS: "/usuarios",
    PLANOS: "/planos"
  }
};
    ```
