# Teste Prático QA - API
Repositório para os entregáveis do Teste Prático de QA (WEBe API)

Para realizar os testes no Postman é necessário importar o arquivo Testes API.postman_collection.json

A collection já está configurada com as variáveis e os cenários pré-definidos.

---------------------------------
## 2. API TESTING
A tarefa aqui é testar a API do Restful-Booker (https://restful-booker.herokuapp.com), um sistema de reservas de hotel. Suponha que a API precisa ser validada antes de ser integrada com o front-end e cabe a você testá-la. 

### 2.1 Instruções:
- 2.1.1 Analise a documentação da API fornecida 
-  2.1.2 Crie e execute testes para os endpoints principais 
-  2.1.3 Documente os resultados e comportamentos encontrados 

### 2.2 Cenários:

- 2.2.1 Autenticação:
- 2.2.1.1 Gerar token de autenticação 
- 2.2.1.2 Tentar gerar token com credenciais inválidas

#### 2.2.2 Gestão de reservas:
- 2.2.2.1 Criar uma nova reserva 
- 2.2.2.2 Buscar uma reserva específica 
- 2.2.2.3 Listar todas as reservas 
- 2.2.2.4 Atualizar uma reserva existente 
- 2.2.2.5 Deletar uma reserva

#### 2.2.3 Filtros e buscas:
- 2.2.3.1 Buscar reservas por nome 
-  2.2.3.2 Buscar reservas por data de check-in 
-  2.2.3.3 Buscar reservas por data de check-out 

### 2.3 Entregáveis:

#### 2.3.1 Collection contendo: 
- 2.3.1.1 Todos os requests organizados
- 2.3.1.2 Pelo menos um teste para cada request 
- 2.3.1.3 Variáveis de ambiente configuradas 

#### 2.3.2 Documento em Markdown (.md) contendo: 
- 2.3.2.1 Lista de cenários testados 
- 2.3.2.2 Resultados obtidos 
- 2.3.2.3 Bugs encontrados (se houver)

### 2.4 Pontos de atenção:
- 2.4.1 Tratamento de erros 
- 2.4.2 Validação de campos obrigatórios
- 2.4.3 Formato das datas 
- 2.4.4 Códigos de resposta HTTP 

### 2.5 Observações:
- 2.5.1 Use Postman ou qualquer outra ferramenta de sua preferência 
- 2.5.2 Documente quaisquer premissas assumidas, se possível.
