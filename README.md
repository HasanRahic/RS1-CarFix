# CarFix eCommerce – ASP.NET Core & Angular

CarFix eCommerce is a full-stack web application built using **ASP.NET Core Web API** and **Angular**.  
The project includes product browsing, filtering, sorting, pagination, shopping cart, authentication, and admin CRUD with image upload.

This project is developed as part of the **RS1 project** (Faculty of Information Technologies, Mostar) and implements all required functionalities from the official assignment document.

---

## 🚀 Technologies

**Backend:**  
- ASP.NET Core Web API  
- Entity Framework Core  
- SQL Server  
- Repository Pattern + Specification Pattern  
- Identity + JWT Authentication  
- Middleware (global error handling)  
- Cloudinary image upload  

**Frontend:**  
- Angular 20  
- Angular Material  
- TailwindCSS  
- RxJS (debounced search)  
- Reactive Forms  
- HTTP Interceptor (JWT)  

---

## 🔥 Features

### 🛒 Shopping & Products  
- Product listing with images, price, brand, type  
- Filtering (brand, type)  
- Sorting (name, price asc/desc)  
- Pagination (client + server)  
- Live search with debouncing  
- Product details view  

### 🔐 Authentication  
- User login & registration  
- Strong password validation  
- JWT token + interceptor  
- Protected routes  

### 🧰 Admin Product Management  
- Create product  
- Edit product  
- Delete product  
- Upload images to Cloudinary  
- Reactive Forms with validation  

### 🛍️ Shopping Cart  
- Add/remove items  
- Update quantities  
- Subtotal, discount, shipping, total  
- Checkout page  
- *Checkout disabled when cart is empty*  

---

## 📁 Project Structure

backend/
├── API/ (controllers, program setup, middleware)
├── Core/ (entities, interfaces, specifications)
├── Infrastructure/ (database, repositories)

frontend/
├── client/
├── src/app/
├── features/ (account, products, shop)
├── shared/ (components, models)
├── core/ (interceptors, services)
├── public/


---


## 📥 Installation & Setup

### **Backend**
```bash
cd backend/api
dotnet restore
dotnet ef database update
dotnet run
```

### **Frontend**
```bash
cd frontend/client
npm install
ng serve
```

Frontend runs on: http://localhost:4200

Backend runs on: https://localhost:5001/api

#👤 Author

Hasan Rahić
Faculty of Information Technologies – Mostar
RS1 – Web Technologies
