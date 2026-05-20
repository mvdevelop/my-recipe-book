
# 📖 My Recipe Book – .NET API

A REST API developed in **.NET** to manage a cookbook, allowing the creation, retrieval, update, and deletion (CRUD) of culinary recipes.  
The interactive API documentation is provided via **Swagger**.

---

## 🚀 Technologies Used

- **.NET (ASP.NET Core Web API)**
- **C#**
- **Swagger (Swashbuckle)**
- **Entity Framework Core**
- **Relational Database** (SQL Server / PostgreSQL / SQLite)
- **Docker** (optional)

---

## 📂 Features

- 📌 Recipe registration
- 📌 List all recipes
- 📌 Find recipe by ID
- 📌 Update recipes
- 📌 Delete recipes
- 📌 Automatic documentation with Swagger

---

## 📑 API Documentation (Swagger)

Once the application is running, the documentation will be available at:

- `https://localhost:5001/swagger`
- `http://localhost:5000/swagger`

Swagger allows you to:
- Test all endpoints interactively
- View request and response models
- Check HTTP status codes

---

## ⚙️ Prerequisites

Before you begin, make sure you have installed:

- **.NET SDK** (version 6 or higher)
- **Git**
- Configured Database (optional, depending on your setup)

Verify your installation:
```bash
dotnet --version
```

---

## ▶️ How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com
cd my-recipe-book
```

### 2. Restore dependencies
```bash
dotnet restore
```

### 3. Run the application
```bash
dotnet run
```

The API will be up and running at: `https://localhost:5001`

---

## 🔗 Main Endpoints


| Method | Route | Description |
| :--- | :--- | :--- |
| **GET** | `/api/recipes` | List all recipes |
| **GET** | `/api/recipes/{id}` | Get a recipe by ID |
| **POST** | `/api/recipes` | Create a new recipe |
| **PUT** | `/api/recipes/{id}` | Update an existing recipe |
| **DELETE**| `/api/recipes/{id}` | Delete a recipe |

---

## 🧪 Request Example (POST /api/recipes)

```json
{
  "title": "Chocolate Cake",
  "description": "Simple and fluffy cake recipe",
  "prepTime": 60,
  "ingredients": [
    "Flour",
    "Eggs",
    "Cocoa powder",
    "Sugar"
  ]
}
```

---

## 🗂️ Project Structure

```text
my-recipe-book/
├── Controllers/
├── Models/
├── Data/
├── Services/
├── Program.cs
└── appsettings.json
```

---

## 🔒 Best Practices Implemented

*   Use of Data Transfer Objects (DTOs) for requests and responses.
*   Data validation using Data Annotations.
*   Separation of Concerns (Controllers, Services, Repositories).
*   API Versioning (optional).

---

## 📌 Next Steps / Roadmap

*   Authentication and Authorization (JWT)
*   Pagination and Filtering
*   Cloud Deployment (Render, Azure, Railway)
*   Automated Testing

---

## 👨‍💻 Author

*   Developed by **mvdevelop**
*   **LinkedIn:** [://linkedin.com](https://www.://linkedin.com/)
*   **GitHub:** [://github.com](https://://github.com)

---

## 📄 License

This project is licensed under the MIT License.  
Feel free to use, modify, and contribute! 🚀
