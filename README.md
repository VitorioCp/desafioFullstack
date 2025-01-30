# Desafio Fullstack
## 🚀 Tecnologias Utilizadas
### Backend
- .NET 9
- Entity Framework Core
- SQLite
- OpenAPI (Swagger)

 ### Backend
 - React
 - Vite
 - Material-UI
 - Axios
 - React Router DOM
 - Styled Components

## 🔧 Como Configurar e Executar o Projeto
### 🖥 Backend
- .NET 9 instalado
- SQLite instalado
#### 1 Navegue até a pasta do backend
#### 2 Restaure as dependências:
    - dotnet restore
#### 3 Execute as migrações do banco de dados:
    - dotnet ef database update
#### 4 Inicie o backend:
    - dotnet run
    
### 🌐 Frontend
- Node.js instalado
  #### 1 Navegue até a pasta do frontend
  #### 2 Instale as dependências
      - npm install
  #### 3 inicie o frontend
      - npm run dev
  #### 4 acesse ao navegador
      - http://localhost:{porta hospedada}


### Observação: a porta configurada no frontend para conexão com o backend é 5050. Caso o servidor do backend esteja sendo executado em outra porta, será necessário atualizar a rota correspondente no código do frontend.
    -cd src/services/api.ts
