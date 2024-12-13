
# Estudo sobre FastAPI

Neste repositório, estou realizando um estudo detalhado sobre o desenvolvimento de aplicações com **FastAPI**, uma das ferramentas mais modernas e poderosas para construção de APIs. O objetivo é explorar os principais conceitos e práticas envolvidas no uso do FastAPI, incluindo configuração do ambiente, testes, modelagem de dados, autenticação, deploy e muito mais.

![FastAPI logo](https://fastapi.tiangolo.com/img/logo-margin/logo-teal.png)

## Objetivos do Estudo

Este repositório aborda os seguintes tópicos:

### 1. **Configuração do Ambiente de Desenvolvimento para FastAPI**  
Vamos começar do **absoluto zero**, configurando o ambiente de desenvolvimento necessário para trabalhar com FastAPI. Isso inclui a instalação de dependências e a configuração básica para iniciar o desenvolvimento.

### 2. **Primeiros Passos com FastAPI e Testes**  
Após a configuração do ambiente, vamos explorar a estrutura básica de um projeto **FastAPI**. Também faremos uma introdução detalhada ao **Test Driven Development (TDD)**, onde aprenderemos a escrever testes e a garantir que nossa aplicação seja robusta desde o início.

### 3. **Modelagem de Dados com Pydantic e SQLAlchemy**  
Vamos aprender a modelar e manipular dados utilizando **Pydantic** e **SQLAlchemy**, duas ferramentas que tornam o FastAPI ainda mais eficiente. Pydantic é utilizado para validação de dados, enquanto SQLAlchemy facilita o trabalho com banco de dados relacional.

### 4. **Autenticação e Autorização em FastAPI**  
Neste módulo, construiremos um sistema de **autenticação completo** para proteger as rotas da nossa API. Apenas usuários autenticados poderão acessar certos dados, garantindo a segurança da aplicação.

### 5. **Testando sua Aplicação FastAPI**  
Aprenderemos a testar nossa aplicação FastAPI com **pytest** e **coverage**, além de integrar esses testes em um **pipeline de CI/CD com GitHub Actions** para garantir a qualidade do código em cada atualização.

### 6. **Dockerizando e Fazendo Deploy de sua Aplicação FastAPI**  
Por fim, vamos **dockerizar** nossa aplicação FastAPI e realizar o **deploy** usando a plataforma **Fly.io**, tornando nossa aplicação pronta para ser executada em produção.

---

## Tecnologias Utilizadas

- ![Python](https://img.shields.io/badge/python-3.8%2B-blue) **Python 3.8+**
- ![FastAPI](https://img.shields.io/badge/FastAPI-0.80%2B-blue) **FastAPI**
- ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-2.0%2B-orange) **SQLAlchemy**
- ![Pydantic](https://img.shields.io/badge/Pydantic-1.8%2B-green) **Pydantic**
- ![Docker](https://img.shields.io/badge/Docker-%20-blue) **Docker**
- ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions%20-%20-yellow) **GitHub Actions**

## Como Iniciar

1. **Clone este repositório:**

   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```

2. **Crie um ambiente virtual:**

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
   ```

3. **Instale as dependências:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Inicie o servidor FastAPI:**

   ```bash
   uvicorn app.main:app --reload
   ```

---

## Links Úteis

- [Documentação do FastAPI](https://fastapi.tiangolo.com/)
- [GitHub Actions](https://github.com/features/actions)
- [Docker Documentation](https://docs.docker.com/)
- [Fly.io Documentation](https://fly.io/docs/)

## Contribuindo

Se você gostaria de contribuir com este estudo, fique à vontade para abrir **issues** ou fazer **pull requests**. Sua contribuição será muito bem-vinda!

## Licença

Este repositório é licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Baseado no curso de FASTAPI de Eduardo Mendes (dunossauro)  
[https://fastapidozero.dunossauro.com/](https://fastapidozero.dunossauro.com/)

---




  
