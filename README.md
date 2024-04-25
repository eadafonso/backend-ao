# Desafio Back-end - LAB-APP

Obrigado pelo seu interesse em trabalhar conosco! Abaixo, você encontrará todas as informações necessárias para iniciar o seu desafio.

## Sobre o projecto (LAB-APP)

O objetivo deste desafio é criar uma aplicação backend (API) que forneça operações CRUD (Create, Read, Update, Delete) para gerenciar informações sobre escolas. 

## Avisos antes de começar

- Leia com atenção este documento todo e tente seguir ao **máximo** as instruções;
- Crie um repositório no seu GitHub **sem citar nada relacionado a LBC**;
- Faça seus commits no seu repositório;
- Envie o link do seu repositório para o seguinte email: **edvaldo.afonso@lbc-global.com**;
- Fique à vontade para perguntar qualquer dúvida;
- Fique calmo, respire, assim como você, também já passamos por essa etapa. Boa sorte! :)

_Corpo do Email com o link do repositório do desafio_

> Seu Nome
>
> Nome do recrutador (Edvaldo Afonso)
>
> Link do repositório
>
> Link do Linkedin

### Requisitos

Abaixo estão descritas as funcionalidades que você deve adicionar à sua aplicação.

- Você pode escolher qualquer linguagem de backend de sua preferência, como Node.js, Python (com Flask ou Django), Java (com Spring Boot), etc.
- Implemente as operações básicas de CRUD para manipular os dados das escolas. Isso inclui:
    - Create (Criar): Permitir a criação de uma nova escola com os seguintes campos obrigatórios: nome, email, número de salas e província.
    - Read (Ler): Recuperar informações sobre uma escola específica e listar todas as escolas existentes.
    - Update (Atualizar): Permitir a atualização dos dados de uma escola existente.
    - Delete (Excluir): Permitir a exclusão de uma escola existente.
- A província deve ser preenchida através de um JSON enviado no formato da requisição. Seu aplicativo deve ser capaz de filtrar as províncias disponíveis com base nos dados fornecidos no JSON.
- Utilize o Swagger para documentar sua API. Isso inclui descrever os endpoints disponíveis, os parâmetros necessários, os tipos de resposta esperados, etc.
- Upload de Excel e Carregamento de Dados na Base de Dados: Seu aplicativo deve permitir que os usuários façam upload de um arquivo Excel contendo informações sobre as escolas e, em seguida, carregue esses dados na base de dados. Para isso, siga as especificações abaixo:
    - Estrutura do Excel: O arquivo Excel deve seguir uma estrutura específica, com colunas para cada campo de dados da escola (nome, email, número de salas, província).
    - Preenchimento do Excel: Antes do upload, o usuário deve preencher o Excel com os dados das escolas.
    - Upload do Excel: O aplicativo deve permitir que o usuário faça o upload do arquivo Excel.
    - Carregamento dos Dados: Após o upload, o aplicativo deve ler os dados do Excel e inseri-los na base de dados, criando uma nova entrada para cada escola no arquivo Excel.

---


## 📅 Entrega

Esse desafio **precisa ser entregue através de algum repositório** em até **2 dias** e será avaliado por nós de acordo com os pontos citados acima.

## Contacto

Email para tirar dúvidas: edvaldo.afonso@lbc-global.com 

### Boa sorte!
