# Lightning Web Components and Salesforce Data

Este repositório contém exemplos e tutoriais sobre como usar Lightning Web Components (LWC) para interagir com dados do Salesforce.

## Índice

- [Introdução](#introdução)
- [Requisitos](#requisitos)
- [Instalação](#instalação)
- [Contribuição](#contribuição)
- [Contato](#contato)

## Introdução

Lightning Web Components (LWC) é um framework moderno para construir componentes de interface de usuário em Salesforce. Este repositório demonstra como criar e usar LWCs para acessar e manipular dados no Salesforce.

## Requisitos

- Salesforce DX
- Node.js
- VS Code (opcional, mas recomendado)
- Salesforce CLI

## Instalação

1. Clone este repositório:

    ```sh
    git clone https://github.com/seu-usuario/seu-repositorio.git
    cd seu-repositorio
    ```

2. Autentique-se no Salesforce:

    ```sh
    sfdx force:auth:web:login -d -a nome-da-organizacao
    ```

3. Instale o projeto na sua organização:

    ```sh
    sfdx force:source:push
    ```

4. Atribua a permissão de segurança necessária:

    ```sh
    sfdx force:user:permset:assign -n SeuPermSet
    ```

5. Abra a sua organização no Salesforce:

    ```sh
    sfdx force:org:open
    ```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e enviar pull requests.

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/sua-feature`)
3. Commit suas mudanças (`git commit -am 'Adiciona nova feature'`)
4. Envie para a branch (`git push origin feature/sua-feature`)
5. Crie um novo Pull Request

## Contato

Para mais informações, entre em contato através do email: [dev.alvarojordao@gmail.com](mailto:dev.alvarojordao@gmail.com).


