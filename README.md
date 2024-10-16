# Projeto Final de Conclusão do Curso - EBAC

Este repositório contém o **Projeto Final** de conclusão do curso **Engenheiro de Qualidade de Software** da EBAC. Ele é composto por três projetos principais, relacionados às funcionalidades de um e-commerce, e um **Trabalho de Conclusão de Curso (TCC)** que aprofunda conceitos e práticas de Qualidade de Software.

## 01 Projeto Cypress

### 1. **Adicionar Item ao Carrinho - US001**

-   **Descrição**: Implementação e automação da funcionalidade que permite ao usuário adicionar um item ao carrinho de compras.
-   **Objetivo**: Garantir que os itens selecionados pelo usuário sejam corretamente adicionados ao carrinho e que o processo de compra seja iniciado.
-   **Cenários Testados**:
    -   Adicionar item ao carrinho com sucesso.
    -   Tentativa de adicionar item indisponível.
    -   Verificação da atualização correta da quantidade no carrinho.

### 2. **Login na Plataforma - US002**

-   **Descrição**: Automação do processo de login de usuários registrados na plataforma.
-   **Objetivo**: Validar que o sistema permite o login de usuários com credenciais válidas, e que mensagens de erro apropriadas são exibidas em caso de falha.
-   **Cenários Testados**:
    -   Login com credenciais válidas.
    -   Tentativa de login com senha incorreta.
    -   Recuperação de senha via e-mail.

### 3. **API de Cupons - US003**

-   **Descrição**: Criação e testes de uma API para gerenciamento de cupons de desconto no e-commerce.
-   **Objetivo**: Garantir que a API de cupons funcione corretamente, permitindo a criação, consulta e aplicação de cupons de desconto em compras.
-   **Cenários Testados**:
    -   Criação de cupons válidos.
    -   Validação de cupons expirados.
    -   Aplicação de cupons com restrições de uso (valor mínimo de compra, número de usos).

## 02 Projeto Mobile

-   **Automação Mobile**:
-   A funcionalidade de Catálogo de Produtos foi testada utilizando Appium para a plataforma Android, com os testes seguindo o padrão de Page Objects. Os testes estão localizados na pasta Mobile. Para essa automação, utilizei o padrão de projeto Page Objects para organizar e reutilizar código de forma eficiente.
-   **Integração Contínua**:
    Os testes automatizados foram configurados para serem executados em GitHub Actions, garantindo que todo código submetido seja verificado automaticamente. O pipeline de CI está configurado para executar testes de UI, API e Mobile, além de gerar relatórios detalhados.

## 03 Testes de Performance

-   **Utilizei o K6 para implementar os testes de performance para os seguintes cenários**:

-   Catálogo de Produtos: Testar o tempo de resposta ao acessar a página de catálogo.
    Login na plataforma: Avaliar o tempo de resposta do login para diferentes usuários.
    Configurações dos testes:
    -   Usuários virtuais: 20
    -   Duração: 2 minutos
    -   RampUp: 20 segundos

## Repositório no GitHub

-   Este repositório é público e contém todo o código-fonte das automações criadas para o TCC. O repositório pode ser acessado no link abaixo:
    -   https://github.com/qamichaelmaia/TCC-EBAC-QE.git

### Trabalho de Conclusão de Curso (TCC)

O **TCC** aborda os principais conceitos e práticas de **Engenharia de Qualidade de Software**, focando em automação de testes, boas práticas de desenvolvimento de software, e a importância da entrega contínua (CI/CD). Entre os tópicos abordados estão:

-   Introdução à Qualidade de Software.
-   Planejamento estratégico de testes e cobertura.
-   Automação de testes em sistemas frontend, backend, mobile e APIs.
-   Ferramentas: Cypress, PactumJS, Postman, WebDriver.
-   Integração de pipelines de CI/CD..

### Referências

-   **Este projeto foi desenvolvido com base nos módulos do curso de Engenharia de Qualidade de Software da EBAC, incluindo**:

    -   Módulos: 4, 5, 8, 10, 11, 12, 14, 16, 17, 22, 23, 24, 26, 28, 29, 30.
