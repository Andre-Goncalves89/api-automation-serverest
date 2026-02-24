# 🚀 Automação de Testes de API - CRUD de Usuários (ServeRest)

Este projeto apresenta uma suíte de testes automatizados para o fluxo completo de gerenciamento de usuários em uma API RESTful. O foco principal foi aplicar conceitos de automação robusta, garantindo a integridade dos dados e a independência dos testes.

### 🛠️ O que foi implementado:

* **Fluxo CRUD Completo:** Testes encadeados de Cadastro (POST), Consulta (GET), Atualização (PUT) e Exclusão (DELETE).
* **Geração de Dados Dinâmicos:** Uso de variáveis dinâmicas do Postman para garantir que cada execução do teste seja única, evitando conflitos de dados.
* **Encadeamento de Requisições:** Captura automática de IDs gerados pela API para uso em requisições subsequentes (ID Chaining).
* **Asserções Avançadas:** Validação de Status Codes, JSON Schema e mensagens de retorno de negócio.

### 📋 Cenários Testados:

* **POST:** Criação de usuário com sucesso (Status 201).
* **GET:** Validação se o usuário criado persiste corretamente na base (Status 200).
* **PUT:** Atualização de dados cadastrais e validação da mensagem de sucesso (Status 200).
* **DELETE:** Remoção do usuário e verificação da limpeza da base (Status 200).
* **POST (Negative):** Validação de erro ao tentar cadastrar e-mail duplicado (Status 400).

### 🚀 Como utilizar:

1. Faça o download do arquivo `Product Management API - CRUD.postman_collection.json` neste repositório.
2. Importe para o seu **Postman**.
3. Execute a Collection utilizando o **Runner** do Postman.
