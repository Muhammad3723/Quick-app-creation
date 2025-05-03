## 🚀 QuickApp — ASP.NET Core 9 / Angular 19 Project Template

A clean, modular, and production-ready **Angular 19 + ASP.NET Core 9** project template built for rapid development of modern web applications.

This template includes user authentication, role-based authorization, CRUD functionality, responsive design, and API integration out-of-the-box.

---

### ✨ Key Features

* ✅ Angular 19 Frontend with Bootstrap 5
* ✅ ASP.NET Core 9 REST API Backend
* ✅ Full Login System with Roles & Permissions
* ✅ Code-First EF Core Integration
* ✅ Swagger UI for API Documentation
* ✅ JWT-based Authentication with Refresh Tokens
* ✅ Email Support with Configuration
* ✅ Responsive Design with Theming (SASS)
* ✅ Internationalization (i18n) Support

---

### 📦 Technology Stack

* **Frontend:** Angular 19, TypeScript, Bootstrap 5, RxJS
* **Backend:** ASP.NET Core 9 Web API, Entity Framework Core
* **Auth:** ASP.NET Core Identity, JWT Tokens
* **Tools:** Swagger, Angular CLI, .NET CLI

---

### 🛠 Installation Instructions

**Option 1:** Clone this repo and open in Visual Studio / VS Code
**Option 2:** Create a new project using this as a starter template

**Initial Setup:**

1. Restore backend dependencies:

   ```bash
   dotnet restore
   ```

2. Restore frontend dependencies:

   ```bash
   npm install
   ```

3. Run the backend server:

   ```bash
   dotnet run
   ```

4. Run the Angular app:

   ```bash
   ng serve
   ```

> Make sure to match `baseUrl` in `environment.ts` with the backend server URL.

---

### 🔐 Default Login Credentials

| Role          | Username | Email                                         | Password     |
| ------------- | -------- | --------------------------------------------- | ------------ |
| Admin         | admin    | [admin@example.com](mailto:admin@example.com) | tempP\@ss123 |
| Standard User | user     | [user@example.com](mailto:user@example.com)   | tempP\@ss123 |

---

### 📚 Documentation Links

* [ASP.NET Core Docs](https://learn.microsoft.com/aspnet/core)
* [Entity Framework Core](https://learn.microsoft.com/ef/core)
* [Angular 19 Overview](https://angular.dev/overview)
* [Angular CLI Guide](https://angular.dev/cli)
* [Bootstrap 5](https://getbootstrap.com/docs/5.2/getting-started/introduction)

---

### ✅ Built-in Features

* Authentication & Authorization
* Role Management with Permission Flags
* Email Confirmation and Password Reset Support
* CRUD-ready Components
* Configuration & Notification Services
* Responsive Layout
* Localization/i18n Ready
* Theming with SASS
* Optimized Folder Structure

---

### 💻 Folder Structure (Simplified)

```
/ClientApp         → Angular Frontend  
/Controllers       → ASP.NET Core API Controllers  
/Models            → EF Core Models  
/Services          → Backend Business Logic  
/Data              → DbContext and Migrations  
```

---

### 🧪 Development Tips

* Make sure `dotnet restore` and `npm install` complete before first run.
* To host backend and frontend separately, configure the client `baseUrl`.
* For production, use `ng build --prod` and configure ASP.NET to serve static files.

---

### 📄 License

This project is licensed under the [MIT License](LICENSE).
