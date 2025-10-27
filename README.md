<<<<<<< HEAD
<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

## Author: Daisy Grace Carreon & Clarisahaina Gonting(Partner)

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

You may also try the [Laravel Bootcamp](https://bootcamp.laravel.com), where you will be guided through building a modern Laravel application from scratch.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 2000 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://patreon.com/taylorotwell).

### Premium Partners

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Cubet Techno Labs](https://cubettech.com)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[Many](https://www.many.co.uk)**
- **[Webdock, Fast VPS Hosting](https://www.webdock.io/en)**
- **[DevSquad](https://devsquad.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
- **[OP.GG](https://op.gg)**
- **[WebReinvent](https://webreinvent.com/?utm_source=laravel&utm_medium=github&utm_campaign=patreon-sponsors)**
- **[Lendio](https://lendio.com)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
=======
# midterm-exam
>>>>>>> 2f3dae5468183f47ef1e36506ebd77f4a510baf0
# **Project Title: Sales-System**

## **Description / Overview**
The **Sales-System** is designed to manage and record product sales efficiently. It allows users to add, edit, and delete products, monitor stock levels, and process sales transactions. When a sale is recorded, the system automatically deducts the sold quantity from the product’s stock, ensuring accurate and real-time inventory management. This system helps automate manual sales recording and provides an organized view of sales and inventory data.

---

## **Objectives**
- To design a simple and user-friendly sales management system.  
- To automate the recording and computation of sales transactions.  
- To maintain accurate and up-to-date product inventory.  
- To automatically update stock quantities after each sale.  
- To enhance efficiency and accuracy in managing business transactions.  

---

## **Features / Functionality**
- **Add Product** – Allows the user to input new product details such as name, price, and stock quantity.  
- **Edit Product** – Enables modification of product information.  
- **Delete Product** – Removes a product from the list.  
- **View Products** – Displays a table of all available products with their price and stock.  
- **Add Sale** – Records new sales transactions, including date, product, price, and quantity.  
- **Automatic Calculation** – Computes subtotal and total amounts for each sale.  
- **Inventory Update** – Automatically deducts sold quantities from product stock after each sale.  
- **View, Edit, and Delete Sales** – Provides control over recorded sales transactions.  

---

## **Installation Instructions**
To install the **Sales-System**, follow these steps:

1. **Download or Clone** this project from your repository.  
2. **Install Required Software:**  
   - Install **Composer**.  
   - Install a web server such as **XAMPP** or **WAMP**.  
3. **Set Up the Laravel Project:**  
   - Run `composer install` in your project directory.  
   - Copy `.env.example` and rename it to `.env`.  
   - Update your database credentials in the `.env` file.  
4. **Set Up the Database:**  
   - Open **phpMyAdmin**.  
   - Create a database (e.g., `sales_db`).  
   - Run `php artisan migrate` to create tables.  
   - Optionally, run `php artisan db:seed` to insert sample data.  
5. **Run the Project:**  
   - Run `php artisan key:generate`.  
   - Start the Laravel server with `php artisan serve`.  
   - Open your browser and go to [http://127.0.0.1:8000](http://127.0.0.1:8000).  

---

## **Usage**
- Go to the **Products** page.  
- Click **+ Add Product** to add new items with price and stock quantity.  
- View, Edit, or Delete products as needed.  
- Go to the **Sales** page.  
- Click **+ New Sale** to record a transaction.  
- The system will automatically calculate the subtotal and total amount and update (deduct) the product stock based on the quantity sold.  

---

## **Screenshots**

### **Products Page**
![Products Page](Screenshot%202025-10-27%20143122.png)  
*Displays the list of products with their name, price, and stock quantity.*

### **Sales Page**
![Sales Page](Screenshot%202025-10-27%20143130.png)  
*Allows users to record new sales transactions. The system automatically calculates totals and updates stock.*

---

## **Contributors**
- **Daisy Grace Carreon** *(Developer)*  
- **Clarisahaina Gonting** *(Partner)*  

---

## **License**
This project is licensed for **educational purposes only**.  
You may modify, distribute, and use it for learning and development purposes, but it is **not intended for commercial use**.
