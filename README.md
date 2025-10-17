# 🛒 Bajar Lagbe - Java Shopping Application

![Java](https://img.shields.io/badge/Java-8%2B-blue)
![Swing](https://img.shields.io/badge/GUI-Swing-orange)
![MySQL](https://img.shields.io/badge/Database-MySQL-lightblue)
![License](https://img.shields.io/badge/License-MIT-green)

A comprehensive desktop-based e-commerce application built with Java Swing, providing a complete shopping experience with user authentication, product management, and order processing capabilities.

## ✨ Features

### 🔐 User Management
- **User Registration & Login** - Secure authentication system
- **Profile Management** - Update user information and preferences
- **Session Management** - Maintain user sessions across application

### 🏪 Product Catalog
- **Product Browsing** - View available products with details
- **Category Management** - Organized product categorization
- **Search Functionality** - Find products quickly
- **Inventory Tracking** - Real-time stock management

### 🛒 Shopping Cart
- **Add/Remove Items** - Dynamic cart management
- **Quantity Updates** - Modify product quantities
- **Price Calculation** - Automatic total calculation
- **Cart Persistence** - Save cart between sessions

### 💳 Order System
- **Order Processing** - Complete purchase workflow
- **Order History** - Track past purchases
- **Order Details** - View comprehensive order information
- **Status Tracking** - Monitor order progress

### ⚙️ Administration
- **Admin Dashboard** - Comprehensive management interface
- **User Management** - Admin control over user accounts
- **Product CRUD** - Add, edit, delete products
- **Sales Analytics** - View business insights

## 🛠️ Technology Stack

### Frontend
- **Java Swing** - Desktop GUI framework
- **WindowBuilder** - GUI design tool (Eclipse Plugin)

### Backend
- **Java 8+** - Core programming language
- **JDBC** - Database connectivity
- **Java Collections Framework** - Data structure management

### Database
- **MySQL** - Primary relational database
- **SQLite** - Lightweight alternative option

### Development Tools
- **Eclipse IDE** - Primary development environment
- **MySQL Workbench** - Database management
- **Git** - Version control system

## 🚀 Installation Guide

### Prerequisites
- Java JDK 8 or higher
- MySQL Server 5.7+
- Eclipse IDE (recommended)
- WindowBuilder Plugin for Eclipse

### Step-by-Step Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/mehedipolash/Java_project_Bajar_lagbe.git
   cd Java_project_Bajar_lagbe
   ```

2. **Import into Eclipse**
   - Open Eclipse IDE
   - File → Import → Existing Projects into Workspace
   - Select the cloned repository folder
   - Click Finish

3. **Configure Build Path**
   - Right-click project → Build Path → Configure Build Path
   - Ensure Java SDK is properly set
   - Add MySQL connector JAR to classpath

## 🗄️ Database Setup

### MySQL Configuration

1. **Create Database**
   ```sql
   CREATE DATABASE bajar_lagbe;
   USE bajar_lagbe;
   ```

2. **Execute Schema Script**
   - Locate the SQL script file in the project
   - Execute it in MySQL Workbench or command line
   - Or use the automatic database setup in the application

3. **Database Connection**
   Update database credentials in `DBConnection.java`:
   ```java
   private static final String URL = "jdbc:mysql://localhost:3306/bajar_lagbe";
   private static final String USERNAME = "your_username";
   private static final String PASSWORD = "your_password";
   ```

### Alternative: SQLite Setup
The application also supports SQLite for simpler deployment:
- No server setup required
- Automatic database file creation
- Perfect for development and testing

## 📁 Project Structure

```
Java_project_Bajar_lagbe/
├── src/
│   ├── model/
│   │   ├── User.java          # User entity class
│   │   ├── Product.java       # Product entity class
│   │   ├── Cart.java          # Shopping cart management
│   │   └── Order.java         # Order processing
│   ├── view/
│   │   ├── LoginFrame.java    # User authentication UI
│   │   ├── ProductView.java   # Product catalog UI
│   │   ├── CartView.java      # Shopping cart UI
│   │   └── AdminPanel.java    # Administration UI
│   ├── controller/
│   │   ├── UserController.java # User management logic
│   │   ├── ProductController.java # Product operations
│   │   └── OrderController.java # Order processing logic
│   ├── database/
│   │   └── DBConnection.java  # Database connection management
│   └── util/
│       └── Validation.java    # Input validation utilities
├── lib/                       # External libraries
├── database/                  # SQL scripts and schemas
└── documentation/             # Project documentation
```

## 💡 Usage

### For Customers
1. **Registration & Login**
   - Launch the application
   - Register a new account or login with existing credentials
   
2. **Shopping Experience**
   - Browse products in the catalog
   - Use search and filter options
   - Add desired items to cart
   - Review cart and proceed to checkout

3. **Order Management**
   - Complete purchase process
   - View order history
   - Track order status

### For Administrators
1. **Admin Access**
   - Login with administrator credentials
   - Access admin dashboard

2. **Management Functions**
   - Add new products to catalog
   - Update product information
   - Manage user accounts
   - View sales reports

## 🤝 Contributing

We welcome contributions to enhance Bajar Lagbe! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Developer

**Mehedi Hasan Polash**
- GitHub: [@mehedipolash](https://github.com/mehedipolash)
- Project Repository: [Java_project_Bajar_lagbe](https://github.com/mehedipolash/Java_project_Bajar_lagbe)

## 🔮 Future Enhancements

- [ ] Payment gateway integration
- [ ] Email notification system
- [ ] Advanced reporting and analytics
- [ ] Multi-language support
- [ ] Mobile companion application
- [ ] Cloud deployment capability
- [ ] REST API development
- [ ] Enhanced security features

---

<div align="center">

**Built with ❤️ using Java Swing & MySQL**

⭐ Star this repository if you find it helpful!

</div>
