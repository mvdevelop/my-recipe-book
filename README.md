
# 📖 Meu Livro de Receitas – API .NET

API REST desenvolvida em **.NET** para gerenciar um livro de receitas, permitindo o cadastro, consulta, atualização e remoção de receitas culinárias.  
A documentação interativa da API é disponibilizada via **Swagger**.

---

## 🚀 Tecnologias Utilizadas

- **.NET (ASP.NET Core Web API)**
- **C#**
- **Swagger (Swashbuckle)**
- **Entity Framework Core**
- **Banco de Dados Relacional** (SQL Server / PostgreSQL / SQLite)
- **Docker** (opcional)

---

## 📂 Funcionalidades

- 📌 Cadastro de receitas
- 📌 Listagem de receitas
- 📌 Consulta de receita por ID
- 📌 Atualização de receitas
- 📌 Remoção de receitas
- 📌 Documentação automática com Swagger

---

## 📑 Documentação da API (Swagger)

Após iniciar a aplicação, a documentação estará disponível em:

https://localhost:5001/swagger

nginx
Copiar código

ou

http://localhost:5000/swagger

yaml
Copiar código

O Swagger permite:
- Testar todos os endpoints
- Visualizar modelos de requisição e resposta
- Ver códigos de status HTTP

---

## ⚙️ Pré-requisitos

Antes de iniciar, você precisará ter instalado:

- **.NET SDK** (versão 6 ou superior)
- **Git**
- Banco de dados configurado (opcional, dependendo do projeto)

Verifique a instalação:
```bash
dotnet --version
▶️ Como Executar o Projeto
1️⃣ Clonar o repositório
bash
Copiar código
git clone https://github.com/seu-usuario/meu-livro-de-receitas.git
cd meu-livro-de-receitas
2️⃣ Restaurar dependências
bash
Copiar código
dotnet restore
3️⃣ Executar a aplicação
bash
Copiar código
dotnet run
A API estará disponível em:

arduino
Copiar código
https://localhost:5001
🔗 Endpoints Principais (Exemplo)
Método	Rota	Descrição
GET	/api/receitas	Listar todas as receitas
GET	/api/receitas/{id}	Buscar receita por ID
POST	/api/receitas	Criar nova receita
PUT	/api/receitas/{id}	Atualizar receita
DELETE	/api/receitas/{id}	Remover receita

🧪 Exemplo de Requisição (POST)
json
Copiar código
{
  "titulo": "Bolo de Chocolate",
  "descricao": "Bolo simples e fofinho",
  "tempoPreparo": 60,
  "ingredientes": [
    "Farinha",
    "Ovos",
    "Chocolate em pó",
    "Açúcar"
  ]
}
🗂️ Estrutura do Projeto (Exemplo)
powershell
Copiar código
meu-livro-de-receitas/
├── Controllers/
├── Models/
├── Data/
├── Services/
├── Program.cs
└── appsettings.json
🔒 Boas Práticas
Uso de DTOs para entrada e saída de dados

Validações com Data Annotations

Separação de responsabilidades (Controllers, Services, Repositories)

Versionamento de API (opcional)

📌 Próximos Passos
Autenticação e autorização (JWT)

Paginação e filtros

Deploy em nuvem (Render, Azure, Railway)

Testes automatizados

👨‍💻 Autor
Desenvolvido por mvdevelop
📧 Email: seu-email-aqui
🔗 GitHub: seu-github-aqui

📄 Licença
Este projeto está sob a licença MIT.
Sinta-se à vontade para usar, modificar e contribuir 🚀

yaml
Copiar código
