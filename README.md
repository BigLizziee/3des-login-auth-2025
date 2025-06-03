# Projeto de Autenticação: Login Auth

Este repositório contém a estrutura de autenticação desenvolvida para o projeto **Login**.

## Tarefas da Atividade em Grupo (Máximo 3 Pessoas)

Para esta atividade, o grupo deverá seguir os seguintes passos:

1.  **Clonar o Repositório:** Obtenha uma cópia local deste projeto.
2.  **Testar a API:** Utilize o **Insomnia** para realizar testes funcionais na API de autenticação.
3.  **Estudar e Documentar:** Analise a estrutura do projeto e crie uma documentação detalhada sobre seu funcionamento.
4.  **Detalhar Bibliotecas:** Documente todas as bibliotecas utilizadas no projeto, explicando suas funções específicas.
5.  **Criar Diagrama de Atividades (UML):** Elabore um Diagrama de Atividades (DA) em UML para ilustrar visualmente o fluxo de funcionamento da autenticação.

## Entendendo o Fluxo de Autenticação

O processo de autenticação nesta API funciona da seguinte maneira:

1.  **Instalação:** Comece instalando todas as dependências necessárias do projeto.
2.  **Configuração do Teste:** Configure o Insomnia para interagir com a API em execução no seu ambiente de desenvolvimento (VS Code).
3.  **Login:** Realize uma requisição de login para a API, fornecendo o e-mail e a senha definidos no código-fonte.
4.  **Geração do Token:** Se as credenciais estiverem corretas, a API gerará um Token JWT (JSON Web Token). Este token possui um tempo de validade de 2 minutos.
5.  **Acesso a Rotas Protegidas:** Com o token válido em mãos, você poderá acessar rotas protegidas da API (como a seção de "Posts"). Para isso, será necessário incluir o token na sua requisição, seguindo o processo de autenticação definido.

## Recursos Visuais e Testes

Abaixo estão os wireframes e exemplos de testes realizados:

*   **Wireframe de Login:**
    ![Wireframe de Login]("C:\Users\Instrutor\Pictures\Screenshots\Captura de tela 2025-06-03 143119.png")
*   **Wireframe de Posts e Autenticação:**
    ![Wireframe de Posts e Autenticação]("C:\Users\Instrutor\Pictures\Screenshots\Captura de tela 2025-06-03 143031.png")

## Equipe de Testes

Os testes foram conduzidos pelos seguintes colaboradores:

*   [Beatriz](https://github.com/beatriz1094 )
*   [Lizzie](https://github.com/BigLizzieee )

## Tecnologias Empregadas

As seguintes tecnologias foram essenciais para o desenvolvimento e teste deste projeto:

| Tecnologia | Propósito                                      |
| :--------- | :--------------------------------------------- |
| VsCode     | Ambiente de Desenvolvimento Integrado (IDE)    |
| Insomnia   | Ferramenta para testes de APIs (Back-End)      |
| Node.js    | Ambiente de execução para JavaScript (Vanilla) |
| Git        | Sistema de controle de versão e colaboração    |

## Diagramas do Projeto

Consulte o Diagrama de Atividades e o Diagrama Entidade-Relacionamento (DER) para uma compreensão mais aprofundada da estrutura:

![Diagrama UML]("C:\Users\Instrutor\Downloads\diagrama_atividades_jwt.png")
