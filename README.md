# 🛒 Grocery Store - End-to-End API Testing Project

This project demonstrates complete **API testing coverage** for a fictional Grocery Store backend using **Postman**. It covers essential workflows such as browsing products, managing cart items, placing orders, and handling authentication.

## 📌 Project Objective

To simulate a real-world e-commerce backend and apply practical API testing techniques with **Postman**, validating both functionality and data integrity across all endpoints.

---

## 🚀 Features Covered

### ✅ Products
- `GET /products` - Get all products  
- `GET /products/:id` - Get a single product by ID  

### ✅ Cart
- `GET /cart` - Retrieve cart  
- `GET /cart/items` - Get all items in cart  
- `POST /cart` - Create a new cart  
- `POST /cart/items` - Add item to cart  
- `PUT /cart/items/:id` - Modify existing item in cart  
- `PATCH /cart/items/:id` - Replace item in cart  
- `DELETE /cart/items/:id` - Remove item from cart  

### ✅ Orders
- `GET /orders` - Retrieve all orders  
- `GET /orders/:id` - Retrieve a specific order  
- `POST /orders` - Create a new order  
- `PUT /orders/:id` - Update an order  
- `DELETE /orders/:id` - Delete an order  

### ✅ Authentication
- `POST /register` - Register new API client  
- (Future Scope) Token-based request authorization  

---

## 🛠️ Tools & Technologies

- [Postman](https://www.postman.com/) – API request creation & testing  
- [Newman]([https://www.npmjs.com/package/newman](https://apistudy-9074.postman.co/workspace/Nezam-API~da5b5ab2-3b6e-4865-862f-0eac763833ab/collection/42160313-7a62890a-2954-4add-a0f6-6fceb8606e28?action=share&source=copy-link&creator=42160313)) – CLI test execution (optional)  
- [HTML Reporter for Newman](https://www.npmjs.com/package/newman-reporter-html) – Generate interactive HTML reports 

